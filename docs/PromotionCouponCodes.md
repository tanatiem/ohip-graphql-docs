# PromotionCouponCodes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| promotionCouponCodesDetail | [`PromotionCouponCodesPromotionCouponCodesDetailType`](#promotioncouponcodespromotioncouponcodesdetailtype) | One Time Promo Coupons |
| promotionCouponCodesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### PromotionCouponCodesPromotionCouponCodesDetailType

| Field | Type | Description |
| --- | --- | --- |
| batchCode | `String` | Batch Code |
| chainCode | `String` | Chain Code |
| couponCode | `String` | Coupon Code |
| couponID | `Float` | Coupon ID |
| createDate | `Date` | Create Date |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| exportDate | `Date` | Export Date |
| inactiveDate | `Date` | Inactive Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| promotionCode | `String` | Promotion Code |
| property | `String` | Property |
| rNAInsertDate | `Date` | RNA Insert Date |
| rNAUpdateDate | `Date` | RNA Update Date |
| status | `String` | Status |
| updateDate | `Date` | Update Date |
| updateUser | `Float` | Update User |
| usedInReservationNameID | `Float` | Used In Reservation Name ID |
| usedInReservationProperty | `String` | Used In Reservation Property |

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