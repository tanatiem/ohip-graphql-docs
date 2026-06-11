# Oracle Opera OHIP GraphQL API Documentation

**Source:** Derived from the official Oracle Hospitality `hospitality-api-docs` schema definitions.  
[GraphQL Data APIs Schema definitions](https://github.com/oracle/hospitality-api-docs/tree/main/graphql/data-apis)

---

## 📌 API Reference Index

### 🛌 Bookings & Reservations
* [Activities](docs/Activities.md)
* [Bookings Reservation](docs/BookingsReservation.md)
* [Booking Reservation (Extended)](docs/BookingReservationExtended.md)
* [Bookings Block](docs/BookingsBlock.md)
* [Bookings Block Production Changes](docs/BookingsBlockProductionChanges.md)
* [Bookings Block Status Changes](docs/BookingsBlockStatusChanges.md)

### 👤 Guest Profiles & Loyalty
* [Profiles Accounts](docs/ProfilesAccounts.md)
* [Profiles Addresses](docs/ProfilesAddresses.md)
* [Profiles Communications](docs/ProfilesCommunications.md)
* [Profiles Contacts](docs/ProfilesContacts.md)
* [Profiles Individuals](docs/ProfilesIndividuals.md)
* [Profiles Notes](docs/ProfilesNotes.md)
* [Profiles Relationships](docs/ProfilesRelationships.md)
* [Profiles Relationship Types](docs/ProfilesRelationshipTypes.md)
* [Profiles Loyalty](docs/ProfilesLoyalty.md)
* [Profiles Loyalty Claims](docs/ProfilesLoyaltyClaims.md)
* [Profiles Loyalty Transactions](docs/ProfilesLoyaltyTransactions.md)

### ⚙️ Property & System Configuration
* [Property](docs/Property.md)
* [Configuration Chain](docs/ConfigurationChain.md)
* [Configuration Resort](docs/ConfigurationResort.md)
* [Integration Configurations](docs/IntegrationConfigurations.md)
* [Export Mappings](docs/ExportMappings.md)
* [Changes Log](docs/ChangesLog.md)
* [Promotion Coupon Codes](docs/PromotionCouponCodes.md)

### 📊 Statistics & Reports
* [Resort Budget Forecast](docs/ResortBudgetForecast.md)
* [Sales Manager Goals](docs/SalesManagerGoals.md)
* [Statistics Forecast Summary](docs/StatisticsForecastSummary.md)
* [Statistics History & Forecast](docs/StatisticsHistoryAndForecast.md)
* [Statistics Managers Report](docs/StatisticsManagersReport.md)
* [Statistics Reservation Pace](docs/StatisticsReservationPace.md)
* [Statistics Reservations Daily](docs/StatisticsReservationsDaily.md)
* [Statistics Reservations Daily Summary](docs/StatisticsReservationsDailySummary.md)
* [Statistics Reservations Summary](docs/StatisticsReservationsSummary.md)

### 📉 Simple Reports
* [Simple Reports: Activities](docs/SimpleReportsActivities.md)
* [Simple Reports: Booking Blocks](docs/SimpleReportsBookingBlocks.md)
* [Simple Reports: Bookings Reservation](docs/SimpleReportsBookingsReservation.md)
* [Simple Reports: Events](docs/SimpleReportsEvents.md)
* [Simple Reports: Financial Transactions](docs/SimpleReportsFinancialTransactions.md)
* [Simple Reports: Profile Individuals](docs/SimpleReportsProfileIndividuals.md)

### 💳 Accounts Receivable (AR) & Financials
* [AR Accounts Receivable](docs/ARAccountsReceivable.md)
* [AR Aging Report](docs/ARAgingReport.md)
* [AR Ledger](docs/ARLedger.md)
* [E-Folio](docs/EFolio.md)
* [Financial Commissions](docs/FinancialCommissions.md)
* [Financial Deposit Ledger](docs/FinancialDepositLedger.md)
* [Financial Guest Ledger](docs/FinancialGuestLedger.md)
* [Financial Transaction Codes](docs/FinancialTransactionCodes.md)
* [Financial Transaction Details](docs/FinancialTransactionDetails.md)
* [Financial Transaction Details (Extended)](docs/FinancialTransactionDetailsExtended.md)
* [Financial Transactions Summary](docs/FinancialTransactionsSummary.md)

### 🏷️ Rates & Revenue Management
* [Rates Codes](docs/RatesCodes.md)
* [Rates Code Details](docs/RatesCodeDetails.md)
* [Rates Categories](docs/RatesCategories.md)
* [Rates Classes](docs/RatesClasses.md)
* [Rates Buckets](docs/RatesBuckets.md)
* [Rates Tiers](docs/RatesTiers.md)
* [Rates Rate Seasons](docs/RatesRateSeasons.md)
* [Rates Hurdles](docs/RatesHurdles.md)
* [Rates Restrictions](docs/RatesRestrictions.md)
* [Rates Deposit & Cancellation Rules](docs/RatesDepositAndCancellationRules.md)
* [Revenue Fixed Charges](docs/RevenueFixedCharges.md)
* [Revenue Groups & Types](docs/RevenueGroupsAndTypes.md)
* [Revenue Packages](docs/RevenuePackages.md)

### 🍽️ Catering & Events
* [Catering Event Forecast](docs/CateringEventForecast.md)
* [Catering Event Postings](docs/CateringEventPostings.md)
* [Catering Event Status Changes](docs/CateringEventStatusChanges.md)
* [Catering Event Types](docs/CateringEventTypes.md)
* [Catering Events & Resources](docs/CateringEventsAndResources.md)

### 🔑 Inventory & Housekeeping
* [Inventory Rooms](docs/InventoryRooms.md)
* [Inventory Rooms Management](docs/InventoryRoomsManagement.md)
* [Inventory Function Spaces](docs/InventoryFunctionSpaces.md)
* [Inventory Housekeeping Management Room](docs/InventoryHousekeepingManagementRoom.md)
* [Inventory Housekeeping Management Task Sheet](docs/InventoryHousekeepingManagementTaskSheet.md)

---

# Notes

## API Response Modes

The GraphQL API returns data in two distinct formats depending on the presence of the `@stream` directive.
- **Standard Mode:** Returns a single, well-formed JSON object.
- **Stream Mode:** The expected extraction method for large datasets. Yields chunked, incremental responses requiring specialized parsing to stitch the payloads together.


### 1. Stream Mode (`@stream`)

**Request Example:**

```graphql
query Property($input: PropertyQueryArgumentsType!) {
  property(input: $input) @stream {
    propertyPropertyDetails {
      property
      propertyName
      chainCode
      countryCode
      primaryKeyID
      dSI
      organizationID
      deletedFlag
      insertDate
      updateDate
    }
  }
}
```

**Response Payload:**

The response arrives as multiple `content-type` chunks. The data is nested within an `incremental` array.

```
---
content-type: application/json; charset=utf-8

{"hasNext":true,"data":{"property":[]},"extensions":{}}
---
content-type: application/json; charset=utf-8

{"hasNext":true,"incremental":[{"items":[{"propertyPropertyDetails":{"property":"ARIV","propertyName":"Anantara Riverside Bangkok Resort","chainCode":"MHG","countryCode":"TBA","primaryKeyID":22,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2024-03-15 03:57:32","updateDate":"2024-04-30 01:12:57"},"propertyRecordCount":1}]}]}
---
content-type: application/json; charset=utf-8

{"hasNext":true,"incremental":[{"items":[{"propertyPropertyDetails":{"property":"ASIA","propertyName":"Anantara Siam Bangkok Hotels","chainCode":"MHG","countryCode":"TBA","primaryKeyID":49,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2026-04-20 10:05:52","updateDate":"2026-03-06 02:39:44"},"propertyRecordCount":2}]},{"items":[{"propertyPropertyDetails":{"property":"VRIV","propertyName":"Avani+ Riverside Bangkok Hotel","chainCode":"MHG","countryCode":"TBA","primaryKeyID":12,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2024-05-15 01:21:10","updateDate":"2024-05-01 04:40:36"},"propertyRecordCount":3}]}]}
---
content-type: application/json; charset=utf-8

{"hasNext":false,"extensions":{"totalRecordCount":3}}
-----
```
### 2. Standard Mode (JSON)

**Request Example:**

```graphql
query Property($input: PropertyQueryArgumentsType!) {
  property(input: $input) {
    propertyPropertyDetails {
      property
      propertyName
      chainCode
      countryCode
      primaryKeyID
      dSI
      organizationID
      deletedFlag
      insertDate
      updateDate
    }
  }
}
```

**Response Payload:**

```json
{
    "data": {
        "property": [
            {
                "propertyPropertyDetails": {
                    "property": "ARIV",
                    "propertyName": "Anantara Riverside Bangkok Resort",
                    "chainCode": "MHG",
                    "countryCode": "TBA",
                    "primaryKeyID": 22,
                    "dSI": 672,
                    "organizationID": 4671,
                    "deletedFlag": "N",
                    "insertDate": "2024-03-15 03:57:32",
                    "updateDate": "2024-04-30 01:12:57"
                },
                "propertyRecordCount": 1
            },
            {
                "propertyPropertyDetails": {
                    "property": "ASIA",
                    "propertyName": "Anantara Siam Bangkok Hotels",
                    "chainCode": "MHG",
                    "countryCode": "TBA",
                    "primaryKeyID": 49,
                    "dSI": 672,
                    "organizationID": 4671,
                    "deletedFlag": "N",
                    "insertDate": "2026-04-20 10:05:52",
                    "updateDate": "2026-03-06 02:39:44"
                },
                "propertyRecordCount": 2
            },
            {
                "propertyPropertyDetails": {
                    "property": "VRIV",
                    "propertyName": "Avani+ Riverside Bangkok Hotel",
                    "chainCode": "MHG",
                    "countryCode": "TBA",
                    "primaryKeyID": 12,
                    "dSI": 672,
                    "organizationID": 4671,
                    "deletedFlag": "N",
                    "insertDate": "2024-05-15 01:21:10",
                    "updateDate": "2024-05-01 04:40:36"
                },
                "propertyRecordCount": 3
            }
        ]
    },
    "extensions": {
        "count": {
            "Property_property": 3
        }
    }
}
```

# Known Request Errors

## Fields not available
Not all fields stated in the graphql specification are actually available.

```json
{
    "errors": [
        {
            "message": "Cannot query field \"internalDeletedFlag\" on type \"ConfigurationResortMarketDetailsType\".",
            "o:errorCode": "GRAPHQL_VALIDATION_FAILED"
        },
        {
            "message": "Cannot query field \"marketGroupCodeDescription\" on type \"ConfigurationResortMarketDetailsType\".",
            "o:errorCode": "GRAPHQL_VALIDATION_FAILED"
        }
    ],
    "extensions": {}
}
```

## Exceeding Maximum # of columns: 150
```json
{
    "errors": [
        {
            "message": "Number of fields in query exceeds the maximum allowed number",
            "o:errorCode": "INP-003",
            "detail": "Maximum of 150 fields are allowed, 262 fields are requested",
            "subjectArea": "Property"
        }
    ],
    "data": {
        "property": null
    },
    "extensions": {}
}
```

