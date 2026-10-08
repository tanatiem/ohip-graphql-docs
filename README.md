# Oracle Opera OHIP GraphQL API Documentation

**Source:** Derived from the official Oracle Hospitality `hospitality-api-docs` schema definitions.  
[GraphQL Data APIs Schema definitions](https://github.com/oracle/hospitality-api-docs/tree/main/graphql/data-apis)

---

## 📌 API Reference Index

| Subject Area | Description |
| :--- | :--- |
| [Activities](docs/Activities.md) | Provides information of Sales activities related to Accounts Contacts and Blocks for the selected Property. |
| [ARAccountsReceivable](docs/ARAccountsReceivable.md) | Detailed Accounts Receivable data including  Adjustments Payments Invoices and Posting for AR Accounts with linked reservation data. |
| [ARAgingReport](docs/ARAgingReport.md) | Detailed information on accounts receivable transactions including aging bucket of invoices open transaction amounts folio information and the account details. |
| [ARLedger](docs/ARLedger.md) | Ledger details showing activity in accounts receivables including reservation and transaction details. |
| [BookingReservationExtended](docs/BookingReservationExtended.md) | Provide booking reservation information with extended or additional details such as blocks routing etc. |
| [BookingsBlock](docs/BookingsBlock.md) | Block header and grid details including actual and potential room and revenue statistics catering events and the associated profile and reservations data. |
| [BookingsBlockProductionChanges](docs/BookingsBlockProductionChanges.md) | Detailed information on blocks and any changes to the number of rooms or revenue by stay date property and Block Owner. |
| [BookingsBlockStatusChanges](docs/BookingsBlockStatusChanges.md) | Detailed information on the status changes throughout the production period of a block including the new and old status codes rooms and associated revenues by property and Block Owner. |
| [BookingsReservation](docs/BookingsReservation.md) | Detailed information on reservations booked in the past and future including market code rate code reservation status guest information and associated room and revenue details. |
| [CateringEventForecast](docs/CateringEventForecast.md) | Event revenue forecast details for defined periods broken down by Event Type Revenue Group and Revenue Type. |
| [CateringEventPostings](docs/CateringEventPostings.md) | Catering Event and resource revenue postings details. |
| [CateringEventsAndResources](docs/CateringEventsAndResources.md) | Catering Event and Event Resource details. |
| [CateringEventStatusChanges](docs/CateringEventStatusChanges.md) | Detailed information on the status changes throughout the production period of an event including the new and old status codes guest counts and associated revenues by property. |
| [CateringEventTypes](docs/CateringEventTypes.md) | Event Type configuration details. |
| [ChangesLog](docs/ChangesLog.md) | Detailed change log of activities performed on a specific reservation block profile etc. |
| [ConfigurationChain](docs/ConfigurationChain.md) | Chain code details. |
| [ConfigurationResort](docs/ConfigurationResort.md) | Basic property configuration information. |
| [EFolio](docs/EFolio.md) | Fiscal e-invoicing data for properties with electronic invoicing integration. |
| [ExportMappings](docs/ExportMappings.md) | Mapping configuration for exports. |
| [FinancialCommissions](docs/FinancialCommissions.md) | Detailed travel agent commission records and payment status. |
| [FinancialDepositLedger](docs/FinancialDepositLedger.md) | Deposit ledger information including advanced deposit payments and associated reservation details. |
| [FinancialGuestLedger](docs/FinancialGuestLedger.md) | Guest ledger details including daily revenue and non-revenue charges and payments for in-house guests. |
| [FinancialTransactionCodes](docs/FinancialTransactionCodes.md) | Configuration of financial transaction codes subgroups and transaction groups. |
| [FinancialTransactionDetails](docs/FinancialTransactionDetails.md) | Detailed transaction postings including debits credits folio windows and cashier details. |
| [FinancialTransactionDetailsExtended](docs/FinancialTransactionDetailsExtended.md) | Extended transaction records including detailed financial breakdown and audit trail information. |
| [FinancialTransactionsSummary](docs/FinancialTransactionsSummary.md) | Summary of financial transactions aggregated by transaction code date and property. |
| [IntegrationConfigurations](docs/IntegrationConfigurations.md) | Details of interface and integration settings configured for the property. |
| [InventoryFunctionSpaces](docs/InventoryFunctionSpaces.md) | Function space configuration setup and availability details. |
| [InventoryHousekeepingManagementRoom](docs/InventoryHousekeepingManagementRoom.md) | Room housekeeping status including dirty clean inspected and out of order states. |
| [InventoryHousekeepingManagementTaskSheet](docs/InventoryHousekeepingManagementTaskSheet.md) | Housekeeping task sheets section assignments and attendant workload details. |
| [InventoryRooms](docs/InventoryRooms.md) | Room definitions features room types and physical inventory attributes. |
| [InventoryRoomsManagement](docs/InventoryRoomsManagement.md) | Room status management out of service and out of order room tracking. |
| [LeisureExperiences](docs/LeisureExperiences.md) | Activity bookings spa golf and leisure experience reservations and itineraries. |
| [ProfilesAccounts](docs/ProfilesAccounts.md) | Company and travel agent profile details including addresses contacts and billing preferences. |
| [ProfilesAddresses](docs/ProfilesAddresses.md) | Postal address details linked to individual company and travel agent profiles. |
| [ProfilesCommunications](docs/ProfilesCommunications.md) | Contact methods such as phone numbers email addresses and URLs for profiles. |
| [ProfilesContacts](docs/ProfilesContacts.md) | Contact persons linked to company or group profiles. |
| [ProfilesIndividuals](docs/ProfilesIndividuals.md) | Guest profile demographics preferences VIP status and language settings. |
| [ProfilesLoyalty](docs/ProfilesLoyalty.md) | Membership and loyalty program account configurations and member details. |
| [ProfilesLoyaltyClaims](docs/ProfilesLoyaltyClaims.md) | Retroactive stay claims and point credit adjustments. |
| [ProfilesLoyaltyTransactions](docs/ProfilesLoyaltyTransactions.md) | Points accrual redemption and tier points transaction history. |
| [ProfilesMembershipTransactions](docs/ProfilesMembershipTransactions.md) | Detailed transactions and point movements on guest membership accounts. |
| [ProfilesNotes](docs/ProfilesNotes.md) | Internal notes and special instructions attached to profiles. |
| [ProfilesRelationships](docs/ProfilesRelationships.md) | Relationships established between different profiles (e.g. employee-company contact-account). |
| [ProfilesRelationshipTypes](docs/ProfilesRelationshipTypes.md) | Relationship types and hierarchy definitions. |
| [ProfilesStayRecords](docs/ProfilesStayRecords.md) | Historical stay statistics revenue contributions and stay dates for profiles. |
| [PromotionCouponCodes](docs/PromotionCouponCodes.md) | Promotional coupon codes usage tracking and validation rules. |
| [Property](docs/Property.md) | Property-level configuration details currency and operational settings. |
| [RatesBuckets](docs/RatesBuckets.md) | Rate bucket configurations and classifications. |
| [RatesCategories](docs/RatesCategories.md) | Rate category grouping and management structures. |
| [RatesClasses](docs/RatesClasses.md) | Rate classes definitions used for grouping rate codes. |
| [RatesCodeDetails](docs/RatesCodeDetails.md) | Detailed pricing component inclusions and rules per rate code. |
| [RatesCodes](docs/RatesCodes.md) | Master definitions of rate codes market restrictions and currency. |
| [RatesDepositAndCancellationRules](docs/RatesDepositAndCancellationRules.md) | Deposit schedules cancellation policies and penalty rules associated with rates. |
| [RatesHurdles](docs/RatesHurdles.md) | Hurdle rate thresholds and yield management restrictions by date. |
| [RatesRateSeasons](docs/RatesRateSeasons.md) | Seasonality definitions date ranges and seasonal rate associations. |
| [RatesRestrictions](docs/RatesRestrictions.md) | Stay restrictions such as minimum length of stay closed to arrival and stay-through rules. |
| [RatesTiers](docs/RatesTiers.md) | Length of stay rate tier definitions and pricing tiers. |
| [ResortBudgetForecast](docs/ResortBudgetForecast.md) | Budget and target financial forecast figures by property and accounting period. |
| [RevenueFixedCharges](docs/RevenueFixedCharges.md) | Recurring scheduled charges and package add-ons attached to reservations. |
| [RevenueGroupsAndTypes](docs/RevenueGroupsAndTypes.md) | Revenue groupings transaction classifications and reporting bucket definitions. |
| [RevenuePackages](docs/RevenuePackages.md) | Package definitions inclusive items allowances and package pricing rules. |
| [SalesManagerGoals](docs/SalesManagerGoals.md) | Sales manager production targets room night goals and revenue quotas. |
| [SimpleReportsActivities](docs/SimpleReportsActivities.md) | Simplified reporting view of sales activities and completed tasks. |
| [SimpleReportsBookingBlocks](docs/SimpleReportsBookingBlocks.md) | Simplified reporting view of room block allocations and pickup. |
| [SimpleReportsBookingsReservation](docs/SimpleReportsBookingsReservation.md) | Simplified reporting view of guest reservations and stay details. |
| [SimpleReportsEvents](docs/SimpleReportsEvents.md) | Simplified reporting view of catering and function space events. |
| [SimpleReportsFinancialTransactions](docs/SimpleReportsFinancialTransactions.md) | Simplified reporting view of daily financial transactions and ledger postings. |
| [SimpleReportsProfileIndividuals](docs/SimpleReportsProfileIndividuals.md) | Simplified reporting view of individual guest profiles. |
| [StatisticsForecastSummary](docs/StatisticsForecastSummary.md) | Summary forward-looking occupancy and room revenue projections. |
| [StatisticsHistoryAndForecast](docs/StatisticsHistoryAndForecast.md) | Combined historical actuals and future forecast statistics. |
| [StatisticsManagersReport](docs/StatisticsManagersReport.md) | Daily manager report metrics including RevPAR ADR and occupancy figures. |
| [StatisticsReservationPace](docs/StatisticsReservationPace.md) | Booking pace comparison showing pickup trends over time against past periods. |
| [StatisticsReservationsDaily](docs/StatisticsReservationsDaily.md) | Daily breakdown of reservation counts arrivals departures and stayovers. |
| [StatisticsReservationsDailySummary](docs/StatisticsReservationsDailySummary.md) | Aggregated daily room nights and revenue statistics. |
| [StatisticsReservationsSummary](docs/StatisticsReservationsSummary.md) | High-level summary of reservation statistics by market segment and rate code. |


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

```python
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
| --- | --- | --- | --- |
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

