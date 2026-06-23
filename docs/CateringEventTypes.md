# CateringEventTypes
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `cateringEventTypes`
> Event type definitions.
  
**Return:** [`[CateringEventTypesType]`](#cateringeventtypestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`CateringEventTypesQueryArgumentsType!`](#cateringeventtypesqueryargumentstype) |  |

## Object Types

### CateringEventTypesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | eventTypeDetails | [`CateringEventTypesEventTypeDetailsType`](#cateringeventtypeseventtypedetailstype) | Event Type Details |
| 2 | cateringEventTypesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### CateringEventTypesEventTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | centralBlockName | `String` | Central Block Name |
| 3 | centralEventType | `String` | Central Event Type |
| 4 | chainCode | `String` | Chain Code |
| 5 | coverable | `String` | Coverable |
| 6 | coverableYn | `String` | Coverable Y/N |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | defaultEndDate | `Date` | Default End Date |
| 9 | defaultStartDate | `Date` | Default Start Date |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | eventType | `String` | Event Type |
| 12 | eventTypeDescription | `String` | Event Type Description |
| 13 | eventtypeid | `String` | Eventtypeid |
| 14 | inactiveDate | `Date` | Inactive Date |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | internalDeletedflag | `String` | Deleted Flag |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | locationID | `String` | Internal ID to uniquely identify the Property |
| 21 | mealType | `String` | Meal Type Code |
| 22 | mealtypeid | `String` | Mealtypeid |
| 23 | orderBy | `Float` | Order By |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | repItem | `String` | Reporting Item |
| 27 | repItemName | `String` | Reporting Item Name |
| 28 | repItemOrderby | `Float` | Reporting Item Orderby |
| 29 | repOrderBy | `Float` | Reporting Order By |
| 30 | repUpdateDate | `Date` | Reporting Updatedate |
| 31 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 32 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 33 | updateDate | `DateTime` | Update Date |
| 34 | updateUser | `Float` | Update User |
| 35 | webBookingYn | `String` | Web Booking Y/N |

[⬆ Back to Query](#query)

---

## Input Types

### DateInput

| Field | Type | Description |
| --- | --- | --- |
| _eq | `Date` |  |
| _ne | `Date` |  |
| _in | `[Date]` |  |
| _nin | `[Date]` |  |
| _gt | `Date` |  |
| _lt | `Date` |  |
| _gte | `Date` |  |
| _lte | `Date` |  |
| _btn | [`DateRangeInput`](#daterangeinput) |  |
| _isNull | `Boolean` |  |

[⬆ Back to Query](#query)

---

### DateRangeInput

| Field | Type | Description |
| --- | --- | --- |
| start | `Date!` |  |
| end | `Date!` |  |

[⬆ Back to Query](#query)

---

### DateTimeInput

| Field | Type | Description |
| --- | --- | --- |
| _eq | `DateTime` |  |
| _ne | `DateTime` |  |
| _in | `[DateTime]` |  |
| _nin | `[DateTime]` |  |
| _gt | `DateTime` |  |
| _lt | `DateTime` |  |
| _gte | `DateTime` |  |
| _lte | `DateTime` |  |
| _btn | [`DateTimeRangeInput`](#datetimerangeinput) |  |
| _isNull | `Boolean` |  |

[⬆ Back to Query](#query)

---

### DateTimeRangeInput

| Field | Type | Description |
| --- | --- | --- |
| start | `DateTime!` |  |
| end | `DateTime!` |  |

[⬆ Back to Query](#query)

---

### StringInput

| Field | Type | Description |
| --- | --- | --- |
| _eq | `String` |  |
| _ne | `String` |  |
| _in | `[String]` |  |
| _nin | `[String]` |  |
| _gt | `String` |  |
| _lt | `String` |  |
| _gte | `String` |  |
| _lte | `String` |  |
| _isNull | `Boolean` |  |

[⬆ Back to Query](#query)

---

### FloatInput

| Field | Type | Description |
| --- | --- | --- |
| _eq | `Float` |  |
| _ne | `Float` |  |
| _in | `[Float]` |  |
| _nin | `[Float]` |  |
| _gt | `Float` |  |
| _lt | `Float` |  |
| _gte | `Float` |  |
| _lte | `Float` |  |
| _btn | [`FloatRangeInput`](#floatrangeinput) |  |
| _isNull | `Boolean` |  |

[⬆ Back to Query](#query)

---

### FloatRangeInput

| Field | Type | Description |
| --- | --- | --- |
| start | `Float!` |  |
| end | `Float!` |  |

[⬆ Back to Query](#query)

---

### CateringEventTypesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| eventtypeDetailsChainCode | `StringInput!` | Chain Code<br>`@mandatoryInput` |
| eventtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventtypeDetailsEventType | `StringInput` | Event Type |
| eventtypeDetailsEventtypeid | `StringInput` | Eventtypeid |
| eventtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
#### Validation Rules

**`mandatoryInput`**
- eventtypeDetailsChainCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query cateringEventTypes($input: CateringEventTypesQueryArgumentsType!) {
  cateringEventTypes(input: $input) @stream {
    eventTypeDetails {
      activeYN
      centralBlockName
      centralEventType
      chainCode
      coverable
      coverableYn
      dSI
      defaultEndDate
      defaultStartDate
      deletedFlag
      eventType
      eventTypeDescription
      eventtypeid
      inactiveDate
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      mealType
      mealtypeid
      orderBy
      organizationID
      primaryKeyID
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
      webBookingYn
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
event_type_details_schema = {
    'activeYN': pl.Utf8,
    'centralBlockName': pl.Utf8,
    'centralEventType': pl.Utf8,
    'chainCode': pl.Utf8,
    'coverable': pl.Utf8,
    'coverableYn': pl.Utf8,
    'dSI': pl.Int64,
    'defaultEndDate': pl.Utf8,
    'defaultStartDate': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'eventType': pl.Utf8,
    'eventTypeDescription': pl.Utf8,
    'eventtypeid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'mealType': pl.Utf8,
    'mealtypeid': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'webBookingYn': pl.Utf8,
}
```