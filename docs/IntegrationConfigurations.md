# IntegrationConfigurations
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `integrationConfigurations`
> Exchange Configurations data including External Systems External Databases Business Events Interface Setup Interface Controls and Interface Mappings.
  
**Return:** [`[IntegrationConfigurationsType]`](#integrationconfigurationstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`IntegrationConfigurationsQueryArgumentsType!`](#integrationconfigurationsqueryargumentstype) |  |

## Object Types

### IntegrationConfigurationsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | externalSystems | [`IntegrationConfigurationsExternalSystemsType`](#integrationconfigurationsexternalsystemstype) | External System Resort |
| 2 | externalSystemProperties | [`IntegrationConfigurationsExternalSystemPropertiesType`](#integrationconfigurationsexternalsystempropertiestype) | External System Resort |
| 3 | interfaceMappings | [`IntegrationConfigurationsInterfaceMappingsType`](#integrationconfigurationsinterfacemappingstype) | Interface Setup Mapping and Parameters |
| 4 | interfaceParameters | [`IntegrationConfigurationsInterfaceParametersType`](#integrationconfigurationsinterfaceparameterstype) | Interface Setup Mapping and Parameters |
| 5 | interfaceSetup | [`IntegrationConfigurationsInterfaceSetupType`](#integrationconfigurationsinterfacesetuptype) | Interface Setup Mapping and Parameters |
| 6 | businessEventConfiguration | [`IntegrationConfigurationsBusinessEventConfigurationType`](#integrationconfigurationsbusinesseventconfigurationtype) | External System Database Business Events |
| 7 | externalDatabases | [`IntegrationConfigurationsExternalDatabasesType`](#integrationconfigurationsexternaldatabasestype) | External System Database Business Events |
| 8 | integrationConfigurationsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalSystemsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | batchBE | `String` | Batch BE |
| 2 | dSI | `Float` | DSI |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | externalSystem | `String` | External System |
| 6 | externalURI | `String` | External URI |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | lookupYN | `String` | Lookup YN |
| 10 | organizationID | `Float` | Organization ID |
| 11 | primaryKeyID | `Float` | Primary Key ID |
| 12 | rNUpdateDate | `Date` | JRN Update Date |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 15 | systemType | `String` | System Type |
| 16 | updateDate | `DateTime` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalSystemPropertiesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | consumerName | `String` | Consumer Name |
| 2 | dSI | `Float` | DSI |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | displayYN | `String` | Display YN |
| 5 | externalSystem | `String` | External System |
| 6 | inactiveDate | `Date` | Inactive Date |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | machineName | `String` | Machine Name |
| 10 | organizationID | `Float` | Organization ID |
| 11 | primaryKeyID | `Float` | Primary Key ID |
| 12 | property | `String` | Property |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 15 | status | `String` | Status |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceMappingsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | conversionCode | `String` | Conversion Code |
| 3 | dSI | `Float` | DSI |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | externalToOPERA | `String` | External To OPERA |
| 6 | externalValue | `String` | External Value |
| 7 | insertDate | `Date` | Insert Date |
| 8 | interfaceId | `String` | Interface Id |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| 11 | oPERAToExternal | `String` | OPERA To External |
| 12 | oPERAValue | `String` | OPERA Value |
| 13 | organizationID | `Float` | Organization ID |
| 14 | primaryKeyID | `Float` | Primary Key ID |
| 15 | property | `String` | Property |
| 16 | rNAInsertDate | `Date` | RNA Insert Date |
| 17 | rNAUpdateDate | `Date` | RNA Update Date |
| 18 | updateDate | `Date` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceParametersType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | insertDate | `Date` | Insert Date |
| 6 | interfaceId | `String` | Interface Id |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Organization ID |
| 10 | parameterGroup | `String` | Parameter Group |
| 11 | parameterName | `String` | Parameter Name |
| 12 | parameterValue | `String` | Parameter Value |
| 13 | primaryKeyID | `Float` | Primary Key ID |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `Date` | RNA Insert Date |
| 16 | rNAUpdateDate | `Date` | RNA Update Date |
| 17 | updateDate | `Date` | Update Date |
| 18 | newView | `String` | new view |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceSetupType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI |
| 3 | dataFlow | `String` | Data Flow |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | deltaChangesYN | `String` | Delta Changes YN |
| 6 | description | `String` | Description |
| 7 | externalProperty | `String` | External Property |
| 8 | insertDate | `Date` | Insert Date |
| 9 | interfaceId | `String` | Interface Id |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| 12 | oPERAProperty | `String` | OPERA Property |
| 13 | organizationID | `Float` | Organization ID |
| 14 | primaryKeyID | `Float` | Primary Key ID |
| 15 | rNAInsertDate | `Date` | RNA Insert Date |
| 16 | rNAUpdateDate | `Date` | RNA Update Date |
| 17 | updateDate | `Date` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsBusinessEventConfigurationType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionType | `String` | Action Type |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI |
| 4 | dataElement | `String` | Data Element |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | externalDatabase | `String` | External Database |
| 7 | externalSystem | `String` | External System |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | module | `String` | Module |
| 12 | organizationID | `Float` | Organization ID |
| 13 | primaryKeyID | `Float` | Primary Key ID |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `Date` | RNA Update Date |
| 16 | updateDate | `Date` | Update Date |
| 17 | whereClause | `String` | Where Clause |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalDatabasesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | externalDatabase | `String` | External Database |
| 6 | externalSystem | `String` | External System |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Organization ID |
| 10 | primaryKeyID | `Float` | Primary Key ID |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | updateDate | `Date` | Update Date |

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

### IntegrationConfigurationsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| extsysresortdetailsConsumerName | `StringInput` | Consumer Name |
| extsysresortdetailsDsi | `FloatInput` | DSI |
| extsysresortdetailsEsDsi | `FloatInput` | DSI |
| extsysresortdetailsCode | `StringInput` | External System |
| extsysresortdetailsEsCode | `StringInput!` | External System<br>`@mandatoryInput` |
| extsysresortdetailsExternalUri | `StringInput` | External URI |
| extsysresortdetailsInactiveDate | `DateInput` | Inactive Date |
| extsysresortdetailsJrnUpdateDttm | `DateTimeInput` | JRN Update Date and Time |
| extsysresortdetailsEsJrnUpdateDttm | `DateTimeInput` | JRN Update Date and Time |
| extsysresortdetailsOrganizationid | `FloatInput` | Organization ID |
| extsysresortdetailsEsOrganizationid | `FloatInput` | Organization ID |
| extsysresortdetailsResort | `StringInput` | Property |
| interfacealldetailsDetailsMapChainCode | `StringInput` | Chain Code |
| interfacealldetailsDetailsConversionCode | `StringInput` | Conversion Code |
| interfacealldetailsDetailsMapDsi | `FloatInput` | DSI |
| interfacealldetailsDetailsDsi | `FloatInput` | DSI |
| interfacealldetailsDetailsSuDsi | `FloatInput` | DSI |
| interfacealldetailsDetailsExternalResort | `StringInput` | External Property |
| interfacealldetailsDetailsExtValue | `StringInput` | External Value |
| interfacealldetailsDetailsMapInterfaceId | `StringInput` | Interface Id |
| interfacealldetailsDetailsInterfaceId | `StringInput` | Interface Id |
| interfacealldetailsDetailsSuInterfaceId | `StringInput` | Interface Id |
| interfacealldetailsDetailsMapJrnUpdateDttm | `DateInput` | JRN Update Date and Time |
| interfacealldetailsDetailsJrnUpdateDttm | `DateInput` | JRN Update Date and Time |
| interfacealldetailsDetailsSuJrnUpdateDttm | `DateInput` | JRN Update Date and Time |
| interfacealldetailsDetailsPmsResort | `StringInput` | OPERA Property |
| interfacealldetailsDetailsPmsValue | `StringInput` | OPERA Value |
| interfacealldetailsDetailsMapOrganizationid | `FloatInput` | Organization ID |
| interfacealldetailsDetailsOrganizationid | `FloatInput` | Organization ID |
| interfacealldetailsDetailsSuOrganizationid | `FloatInput` | Organization ID |
| interfacealldetailsDetailsParameterName | `StringInput` | Parameter Name |
| interfacealldetailsDetailsResort | `StringInput` | Property |
| interfacealldetailsDetailsMapResort | `StringInput` | Property |
| extdbbuseventDetailsActionType | `StringInput` | Action Type |
| extdbbuseventDetailsEdDsi | `FloatInput` | DSI |
| extdbbuseventDetailsDsi | `FloatInput` | DSI |
| extdbbuseventDetailsDataElement | `StringInput` | Data Element |
| extdbbuseventDetailsEdDatabaseId | `StringInput` | External Database |
| extdbbuseventDetailsDatabaseId | `StringInput` | External Database |
| extdbbuseventDetailsExtSystemCode | `StringInput` | External System |
| extdbbuseventDetailsJrnUpdateDttm | `DateTimeInput` | JRN Update Date and Time |
| extdbbuseventDetailsEdJrnUpdateDttm | `DateTimeInput` | JRN Update Date and Time |
| extdbbuseventDetailsModule | `StringInput` | Module |
| extdbbuseventDetailsEdOrganizationid | `FloatInput` | Organization ID |
#### Validation Rules

**`mandatoryInput`**
- extsysresortdetailsEsCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query integrationConfigurations($input: IntegrationConfigurationsQueryArgumentsType!) {
  integrationConfigurations(input: $input) @stream {
    externalSystems {
      batchBE
      dSI
      deletedFlag
      description
      externalSystem
      externalURI
      insertDate
      jRNUpdateDateAndTime
      lookupYN
      organizationID
      primaryKeyID
      rNUpdateDate
      rNAInsertDate
      rNAUpdateDate
      systemType
      updateDate
    }
    externalSystemProperties {
      consumerName
      dSI
      deletedFlag
      displayYN
      externalSystem
      inactiveDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      machineName
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      status
    }
    interfaceMappings {
      chainCode
      conversionCode
      dSI
      deletedFlag
      externalToOPERA
      externalValue
      insertDate
      interfaceId
      jRNUpdateDate
      jRNUpdateDateAndTime
      oPERAToExternal
      oPERAValue
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateDate
    }
    interfaceParameters {
      chainCode
      dSI
      deletedFlag
      description
      insertDate
      interfaceId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      parameterGroup
      parameterName
      parameterValue
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateDate
      newView
    }
    interfaceSetup {
      chainCode
      dSI
      dataFlow
      deletedFlag
      deltaChangesYN
      description
      externalProperty
      insertDate
      interfaceId
      jRNUpdateDate
      jRNUpdateDateAndTime
      oPERAProperty
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
    }
    businessEventConfiguration {
      actionType
      chainCode
      dSI
      dataElement
      deletedFlag
      externalDatabase
      externalSystem
      insertDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      module
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
      whereClause
    }
    externalDatabases {
      chainCode
      dSI
      deletedFlag
      description
      externalDatabase
      externalSystem
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateDate
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
external_systems_schema = {
    'batchBE': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'externalSystem': pl.Utf8,
    'externalURI': pl.Utf8,
    'insertDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lookupYN': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNUpdateDate': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'systemType': pl.Utf8,
    'updateDate': pl.Utf8,
}
```
```python
external_system_properties_schema = {
    'consumerName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayYN': pl.Utf8,
    'externalSystem': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'machineName': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'status': pl.Utf8,
}
```
```python
interface_mappings_schema = {
    'chainCode': pl.Utf8,
    'conversionCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'externalToOPERA': pl.Utf8,
    'externalValue': pl.Utf8,
    'insertDate': pl.Utf8,
    'interfaceId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'oPERAToExternal': pl.Utf8,
    'oPERAValue': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
}
```
```python
interface_parameters_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'interfaceId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'parameterGroup': pl.Utf8,
    'parameterName': pl.Utf8,
    'parameterValue': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'newView': pl.Utf8,
}
```
```python
interface_setup_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'dataFlow': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'deltaChangesYN': pl.Utf8,
    'description': pl.Utf8,
    'externalProperty': pl.Utf8,
    'insertDate': pl.Utf8,
    'interfaceId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'oPERAProperty': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
}
```
```python
business_event_configuration_schema = {
    'actionType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'dataElement': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'externalDatabase': pl.Utf8,
    'externalSystem': pl.Utf8,
    'insertDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'module': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'whereClause': pl.Utf8,
}
```
```python
external_databases_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'externalDatabase': pl.Utf8,
    'externalSystem': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
}
```