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

{"hasNext":true,"incremental":[{"items":[{"propertyPropertyDetails":{"property":"AAA","primaryKeyID":22,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2024-03-15 03:57:32","updateDate":"2024-04-30 01:12:57"},"propertyRecordCount":1}]}]}
---
content-type: application/json; charset=utf-8

{"hasNext":true,"incremental":[{"items":[{"propertyPropertyDetails":{"property":"BBB","primaryKeyID":49,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2026-04-20 10:05:52","updateDate":"2026-03-06 02:39:44"},"propertyRecordCount":2}]},{"items":[{"propertyPropertyDetails":{"property":"CCC","primaryKeyID":12,"dSI":672,"organizationID":4671,"deletedFlag":"N","insertDate":"2024-05-15 01:21:10","updateDate":"2024-05-01 04:40:36"},"propertyRecordCount":3}]}]}
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
                    "property": "AAA",
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
                    "property": "BBB",
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
                    "property": "CCC",
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

## Understanding Row Explosion

**GraphQL Query:**

```graphql
query configurationResort($input: ConfigurationResortQueryArgumentsType!) {
  configurationResort(input: $input) {
    propertyPropertyDetails {
      property
      propertyName
      updateDate
    }
  }
}
```
**GraphQL Variables:**

```graphql
{
  "input": {
    "resortDetailsResort": {
        "_in": ["AAA","BBB"]
    }
  }
}
```

<details open>
<summary>Response JSON</summary>

```json
{
    "data": {
        "configurationResort": [
            {
                "propertyPropertyDetails": {
                    "property": "AAA",
                    "propertyName": "AAA Resort",
                    "updateDate": "2024-04-30 01:12:57"
                },
                "configurationResortRecordCount": 1
            },
            {
                "propertyPropertyDetails": {
                    "property": "BBB",
                    "propertyName": "BBB Resort",
                    "updateDate": "2026-03-06 02:39:44"
                },
                "configurationResortRecordCount": 2
            }
        ]
    },
    "extensions": {
        "count": {
            "ConfigurationResort_configurationResort": 2
        }
    }
}
```
</details>

**Parsed JSON**
| property | propertyName | updateDate | RecordCount |
| --- | --- | --- |
| AAA | AAA Resort | 2024-04-30 01:12:57 | 1 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | 2 |


As per request variables, this query returns 2 rows, one for each hotel with the `property`,`propertyName`,`updateDate` in  `propertyPropertyDetails` object.

However, a single hotel have multiple market groups configured, adding `marketGroupDetails` to the exact same query introduces a `1:Many relationship`.

**GraphQL Query:**

```graphql
query configurationResort($input: ConfigurationResortQueryArgumentsType!) {
  configurationResort(input: $input) {
    propertyPropertyDetails {
      property
      propertyName
      updateDate
    }
    marketGroupDetails {
      marketGroup
      marketgroupid
      updateDate
    }
  }
}

```
<details open>
<summary>Response JSON</summary>

```json
{
  "data": {
    "configurationResort": [
        {
            "propertyPropertyDetails": {
                "property": "AAA",
                "propertyName": "AAA Resort",
                "updateDate": "2024-04-30 01:12:57"
            },
            "marketGroupDetails": {
                "marketGroup": "BEN",
                "marketgroupid": "BEN",
                "updateDate": "2024-04-05 08:15:40"
            },
            "configurationResortRecordCount": 1
        },
        {
            "propertyPropertyDetails": {
                "property": "AAA",
                "propertyName": "AAA Resort",
                "updateDate": "2024-04-30 01:12:57"
            },
            "marketGroupDetails": {
                "marketGroup": "CMP",
                "marketgroupid": "CMP",
                "updateDate": "2024-04-05 08:15:40"
            },
            "configurationResortRecordCount": 2
        },
        ...
    ]
  }
  ...
}

```

</details>

**Parsed Response**
| Property | Property Name | Property `updateDate` | Market Group | Market Group ID | Market Group `updateDate` | Record Count |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| AAA | AAA Resort | 2024-04-30 01:12:57 | BEN | BEN | 2024-04-05 08:15:40 | 1 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | CMP | CMP | 2024-04-05 08:15:40 | 2 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | CAT | CAT | 2024-04-05 08:15:40 | 3 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | COR | COR | 2024-04-05 08:15:40 | 4 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | CON | CON | 2024-04-05 08:15:40 | 5 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | COO | COO | 2024-04-05 08:15:40 | 6 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | DIS | DIS | 2024-04-05 08:15:40 | 7 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | GRP | GRP | 2024-04-05 08:15:40 | 8 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | CORP | CORP | 2024-04-05 08:15:40 | 9 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | PER | PER | 2024-04-05 08:15:40 | 10 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | HOU | HOU | 2024-04-05 08:15:40 | 11 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | HAC | HAC | 2024-04-05 08:15:40 | 12 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | PKG | PKG | 2024-04-05 08:15:40 | 13 |
| AAA | AAA Resort | 2024-04-30 01:12:57 | WHO | WHO | 2024-04-05 08:15:40 | 14 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | BEN | BEN | 2026-04-20 09:49:44 | 15 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | CAT | CAT | 2026-04-20 09:49:44 | 16 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | CMP | CMP | 2026-04-20 09:49:44 | 17 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | CON | CON | 2026-04-20 09:49:44 | 18 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | COO | COO | 2026-04-20 09:49:44 | 19 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | COR | COR | 2026-04-20 09:49:44 | 20 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | DIS | DIS | 2026-04-20 09:49:44 | 21 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | GRP | GRP | 2026-04-20 09:49:44 | 22 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | HAC | HAC | 2026-04-20 09:49:44 | 23 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | HOU | HOU | 2026-04-20 09:49:44 | 24 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | PER | PER | 2026-04-20 09:49:44 | 25 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | PKG | PKG | 2026-04-20 09:49:44 | 26 |
| BBB | BBB Resort | 2026-03-06 02:39:44 | WHO | WHO | 2026-04-20 09:49:44 | 27 |

The result is exploded from one row per one hotel with the duplcated data from the `parent`, working like `SQL join`.

### ℹ️ Decoupled Extractions
When extracting data to build normalized tables to build a data warehouse, 1:Many relationships should be extracted via independent API requests:
1. **The Parent Query**: Extracts the core entity as its native grain.
2. **The Child Query**: Calling the same subject area with different query. We may also need some IDs field from the parent for joining in Data Warehouse layer. (if it's not available in its own object).

>I'm not sure at the moment what keys that we need to extract for joining tables. We will have to wait for the GraphQL workshop to identify the exact composite keys necessary to guarantee **`cross-datacenter uniqueness`**.

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

