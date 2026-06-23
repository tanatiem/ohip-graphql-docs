# PromotionCouponCodes
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `promotionCouponCodes`
> Promotion Coupon Codes details
  
**Return:** [`[PromotionCouponCodesType]`](#promotioncouponcodestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`PromotionCouponCodesQueryArgumentsType!`](#promotioncouponcodesqueryargumentstype) |  |

## Object Types

### PromotionCouponCodesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | promotionCouponCodesDetail | [`PromotionCouponCodesPromotionCouponCodesDetailType`](#promotioncouponcodespromotioncouponcodesdetailtype) | One Time Promo Coupons |
| 2 | promotionCouponCodesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### PromotionCouponCodesPromotionCouponCodesDetailType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | batchCode | `String` | Batch Code |
| 2 | chainCode | `String` | Chain Code |
| 3 | couponCode | `String` | Coupon Code |
| 4 | couponID | `Float` | Coupon ID |
| 5 | createDate | `Date` | Create Date |
| 6 | dSI | `Float` | DSI |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | exportDate | `Date` | Export Date |
| 9 | inactiveDate | `Date` | Inactive Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| 13 | organizationID | `Float` | Organization ID |
| 14 | primaryKeyID | `Float` | Primary Key ID |
| 15 | promotionCode | `String` | Promotion Code |
| 16 | property | `String` | Property |
| 17 | rNAInsertDate | `Date` | RNA Insert Date |
| 18 | rNAUpdateDate | `Date` | RNA Update Date |
| 19 | status | `String` | Status |
| 20 | updateDate | `Date` | Update Date |
| 21 | updateUser | `Float` | Update User |
| 22 | usedInReservationNameID | `Float` | Used In Reservation Name ID |
| 23 | usedInReservationProperty | `String` | Used In Reservation Property |

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

### PromotionCouponCodesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| onetimepromocouponsDetailsBatchCode | `StringInput` | Batch Code |
| onetimepromocouponsDetailsCouponCode | `StringInput` | Coupon Code |
| onetimepromocouponsDetailsCouponId | `FloatInput` | Coupon ID |
| onetimepromocouponsDetailsPromotionCode | `StringInput` | Promotion Code |
| onetimepromocouponsDetailsResort | `StringInput!` | Property<br>`@mandatoryInput` |
| onetimepromocouponsDetailsUsedInResvNameId | `FloatInput` | Used In Reservation Name ID |
| onetimepromocouponsDetailsUsedInResvResort | `StringInput` | Used In Reservation Property |
#### Validation Rules

**`mandatoryInput`**
- onetimepromocouponsDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query promotionCouponCodes($input: PromotionCouponCodesQueryArgumentsType!) {
  promotionCouponCodes(input: $input) @stream {
    promotionCouponCodesDetail {
      batchCode
      chainCode
      couponCode
      couponID
      createDate
      dSI
      deletedFlag
      exportDate
      inactiveDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      promotionCode
      property
      rNAInsertDate
      rNAUpdateDate
      status
      updateDate
      updateUser
      usedInReservationNameID
      usedInReservationProperty
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
promotion_coupon_codes_detail_schema = {
    'batchCode': pl.Utf8,
    'chainCode': pl.Utf8,
    'couponCode': pl.Utf8,
    'couponID': pl.Float64,
    'createDate': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'exportDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'promotionCode': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'status': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'usedInReservationNameID': pl.Float64,
    'usedInReservationProperty': pl.Utf8,
}
```