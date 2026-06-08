# ProfilesRelationshipTypes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesRelationshipTypes`
> Relationship type definition.
  
**Return:** [`[ProfilesRelationshipTypesType]`](#profilesrelationshiptypestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesRelationshipTypesQueryArgumentsType!`](#profilesrelationshiptypesqueryargumentstype) |  |

## Object Types

### ProfilesRelationshipTypesType

| Field | Type | Description |
| --- | --- | --- |
| relationshipDetails | [`ProfilesRelationshipTypesRelationshipDetailsType`](#profilesrelationshiptypesrelationshipdetailstype) | Relationship Details |
| profilesRelationshipTypesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesRelationshipTypesRelationshipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromType | `String` | From Relationship Type. |
| globalYn | `String` | Global Y/N |
| hierarchyYN | `String` | Hierarchy YN |
| ignoreProtectionYn | `String` | Indicates if custom profile protection is not applicable for this relationship type. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| individualYN | `String` | Individual YN |
| inheritRatesYN | `String` | Inherit Rates YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| relationCategory | `String` | Module related to this Name Type whether it is used in PMS S&C etc. |
| relationship | `String` | Relationship |
| relationshipId | `String` | Relationship ID |
| relationshipRole | `String` | Used in S&C Module |
| relationshipType | `String` | Relationship Type |
| relationshippms | `String` | Relationshippms |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| tempFlag | `String` | Temp Flag |
| toDescription | `String` | Description of the To Relationship. |
| toIndividualYN | `String` | To Individual YN |
| toInheritRatesYN | `String` | To Inherit Rates YN |
| toRelationship | `String` | To Relationship type. |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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

### ProfilesRelationshipTypesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| relationshipDetailsChainCode | `StringInput!` | Chain Code<br>`@mandatoryInput` |
| relationshipDetailsFromType | `StringInput` | From Relationship Type. |
| relationshipDetailsOrganizationId | `FloatInput` | Organization ID |
| relationshipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| relationshipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| relationshipDetailsRelationCategory | `StringInput` | Module related to this Name Type whether it is used in PMS S&C etc. |
| relationshipDetailsRelationshipId | `StringInput` | Relationship ID |
| relationshipDetailsRelationship | `StringInput` | Relationship Type |
| relationshipDetailsToType | `StringInput` | To Type |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesRelationshipTypes($input: ProfilesRelationshipTypesQueryArgumentsType!) {
  profilesRelationshipTypes(input: $input) @stream {
    relationshipDetails {
      canDeleteYn
      chainCode
      dSI
      deletedFlag
      fromType
      globalYn
      hierarchyYN
      ignoreProtectionYn
      inactiveDate
      inactiveFlag
      individualYN
      inheritRatesYN
      insertDate
      insertUser
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      primaryYN
      relationCategory
      relationship
      relationshipId
      relationshipRole
      relationshipType
      relationshippms
      rnaInsertDate
      rnaUpdateDate
      tempFlag
      toDescription
      toIndividualYN
      toInheritRatesYN
      toRelationship
      toType
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
relationship_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fromType': pl.Utf8,
    'globalYn': pl.Utf8,
    'hierarchyYN': pl.Utf8,
    'ignoreProtectionYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'individualYN': pl.Utf8,
    'inheritRatesYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'relationCategory': pl.Utf8,
    'relationship': pl.Utf8,
    'relationshipId': pl.Utf8,
    'relationshipRole': pl.Utf8,
    'relationshipType': pl.Utf8,
    'relationshippms': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'tempFlag': pl.Utf8,
    'toDescription': pl.Utf8,
    'toIndividualYN': pl.Utf8,
    'toInheritRatesYN': pl.Utf8,
    'toRelationship': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```