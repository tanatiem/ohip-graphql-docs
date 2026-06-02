# IntegrationConfigurations
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| externalSystems | [`IntegrationConfigurationsExternalSystemsType`](#integrationconfigurationsexternalsystemstype) | External System Resort |
| externalSystemProperties | [`IntegrationConfigurationsExternalSystemPropertiesType`](#integrationconfigurationsexternalsystempropertiestype) | External System Resort |
| interfaceMappings | [`IntegrationConfigurationsInterfaceMappingsType`](#integrationconfigurationsinterfacemappingstype) | Interface Setup Mapping and Parameters |
| interfaceParameters | [`IntegrationConfigurationsInterfaceParametersType`](#integrationconfigurationsinterfaceparameterstype) | Interface Setup Mapping and Parameters |
| interfaceSetup | [`IntegrationConfigurationsInterfaceSetupType`](#integrationconfigurationsinterfacesetuptype) | Interface Setup Mapping and Parameters |
| businessEventConfiguration | [`IntegrationConfigurationsBusinessEventConfigurationType`](#integrationconfigurationsbusinesseventconfigurationtype) | External System Database Business Events |
| externalDatabases | [`IntegrationConfigurationsExternalDatabasesType`](#integrationconfigurationsexternaldatabasestype) | External System Database Business Events |
| integrationConfigurationsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalSystemsType

| Field | Type | Description |
| --- | --- | --- |
| batchBE | `String` | Batch BE |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| externalSystem | `String` | External System |
| externalURI | `String` | External URI |
| insertDate | `DateTime` | Insert Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lookupYN | `String` | Lookup YN |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| rNUpdateDate | `Date` | JRN Update Date |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| systemType | `String` | System Type |
| updateDate | `DateTime` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalSystemPropertiesType

| Field | Type | Description |
| --- | --- | --- |
| consumerName | `String` | Consumer Name |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| displayYN | `String` | Display YN |
| externalSystem | `String` | External System |
| inactiveDate | `Date` | Inactive Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| machineName | `String` | Machine Name |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| status | `String` | Status |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceMappingsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| conversionCode | `String` | Conversion Code |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| externalToOPERA | `String` | External To OPERA |
| externalValue | `String` | External Value |
| insertDate | `Date` | Insert Date |
| interfaceId | `String` | Interface Id |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| oPERAToExternal | `String` | OPERA To External |
| oPERAValue | `String` | OPERA Value |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| property | `String` | Property |
| rNAInsertDate | `Date` | RNA Insert Date |
| rNAUpdateDate | `Date` | RNA Update Date |
| updateDate | `Date` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceParametersType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `Date` | Insert Date |
| interfaceId | `String` | Interface Id |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| organizationID | `Float` | Organization ID |
| parameterGroup | `String` | Parameter Group |
| parameterName | `String` | Parameter Name |
| parameterValue | `String` | Parameter Value |
| primaryKeyID | `Float` | Primary Key ID |
| property | `String` | Property |
| rNAInsertDate | `Date` | RNA Insert Date |
| rNAUpdateDate | `Date` | RNA Update Date |
| updateDate | `Date` | Update Date |
| newView | `String` | new view |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsInterfaceSetupType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI |
| dataFlow | `String` | Data Flow |
| deletedFlag | `String` | Deleted Flag |
| deltaChangesYN | `String` | Delta Changes YN |
| description | `String` | Description |
| externalProperty | `String` | External Property |
| insertDate | `Date` | Insert Date |
| interfaceId | `String` | Interface Id |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `Date` | JRN Update Date and Time |
| oPERAProperty | `String` | OPERA Property |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| rNAInsertDate | `Date` | RNA Insert Date |
| rNAUpdateDate | `Date` | RNA Update Date |
| updateDate | `Date` | Update Date |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsBusinessEventConfigurationType

| Field | Type | Description |
| --- | --- | --- |
| actionType | `String` | Action Type |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI |
| dataElement | `String` | Data Element |
| deletedFlag | `String` | Deleted Flag |
| externalDatabase | `String` | External Database |
| externalSystem | `String` | External System |
| insertDate | `DateTime` | Insert Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| module | `String` | Module |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `Date` | RNA Update Date |
| updateDate | `Date` | Update Date |
| whereClause | `String` | Where Clause |

[⬆ Back to Query](#query)

---

### IntegrationConfigurationsExternalDatabasesType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| externalDatabase | `String` | External Database |
| externalSystem | `String` | External System |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Organization ID |
| primaryKeyID | `Float` | Primary Key ID |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `Date` | Update Date |

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