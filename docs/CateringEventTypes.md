# CateringEventTypes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| eventTypeDetails | [`CateringEventTypesEventTypeDetailsType`](#cateringeventtypeseventtypedetailstype) | Event Type Details |
| cateringEventTypesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### CateringEventTypesEventTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| centralBlockName | `String` | Central Block Name |
| centralEventType | `String` | Central Event Type |
| chainCode | `String` | Chain Code |
| coverable | `String` | Coverable |
| coverableYn | `String` | Coverable Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultEndDate | `Date` | Default End Date |
| defaultStartDate | `Date` | Default Start Date |
| deletedFlag | `String` | Deleted Flag |
| eventType | `String` | Event Type |
| eventTypeDescription | `String` | Event Type Description |
| eventtypeid | `String` | Eventtypeid |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| mealType | `String` | Meal Type Code |
| mealtypeid | `String` | Mealtypeid |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| webBookingYn | `String` | Web Booking Y/N |

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

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

event_type_details_schema = {
    'activeYN': pl.Utf8,
    'centralBlockName': pl.Utf8,
    'centralEventType': pl.Utf8,
    'chainCode': pl.Utf8,
    'coverable': pl.Utf8,
    'coverableYn': pl.Utf8,
    'dSI': pl.Float64,
    'defaultEndDate': pl.Utf8,
    'defaultStartDate': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'eventType': pl.Utf8,
    'eventTypeDescription': pl.Utf8,
    'eventtypeid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'mealType': pl.Utf8,
    'mealtypeid': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'webBookingYn': pl.Utf8,
}

```