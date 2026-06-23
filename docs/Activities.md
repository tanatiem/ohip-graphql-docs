# Activities
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `activities`
> Provides information of Sales activities related to Accounts Contacts and Blocks for the selected Property.
  
**Return:** [`[ActivitiesType]`](#activitiestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ActivitiesQueryArgumentsType!`](#activitiesqueryargumentstype) |  |

## Object Types

### ActivitiesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | workOrdersDetails | [`ActivitiesWorkOrdersDetailsType`](#activitiesworkordersdetailstype) | Work Orders Details |
| 2 | activityProfileDetails | [`ActivitiesActivityProfileDetailsType`](#activitiesactivityprofiledetailstype) | Activity Profile Details |
| 3 | activityBlockDetails | [`ActivitiesActivityBlockDetailsType`](#activitiesactivityblockdetailstype) | Activity Block |
| 4 | activityContactProfileDetails | [`ActivitiesActivityContactProfileDetailsType`](#activitiesactivitycontactprofiledetailstype) | Activity Contact Profile Details |
| 5 | propertyPropertyDetails | [`ActivitiesPropertyPropertyDetailsType`](#activitiespropertypropertydetailstype) | Resort Details |
| 6 | activitiesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ActivitiesWorkOrdersDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountAll | `String` | Account All |
| 2 | activityAmount | `Float` | Total amount for the specific Activity. |
| 3 | activityClass | `String` | Activity Class |
| 4 | activityCompleted | `String` | Activity Completed |
| 5 | activityCompletedBy | `String` | Activity Completed By |
| 6 | activityCompletionDate | `Float` | Activity Completion Date |
| 7 | activityCreatedBy | `String` | Activity Created By |
| 8 | activityCreatedOn | `DateTime` | Activity Created On |
| 9 | activityEndDate | `DateTime` | Activity End Date |
| 10 | activityID | `Float` | Activity ID |
| 11 | activityName | `String` | Description of the Problem reported |
| 12 | activityNotes | `String` | Activity Notes |
| 13 | activityOwnerCode | `DateTime` | Activity Owner Code |
| 14 | activityPriority | `String` | Activity Priority |
| 15 | activityResult | `String` | Activity Result |
| 16 | activityStartDate | `DateTime` | Activity Start Date |
| 17 | activityTraceCode | `String` | Activity Trace Code |
| 18 | activityType | `String` | Activity Type |
| 19 | activityTypeDescription | `String` | Activity Type Description |
| 20 | activityUpdatedBy | `String` | Activity Updated By |
| 21 | activityUpdatedOn | `DateTime` | Activity Updated On |
| 22 | activityUserNameID | `String` | Activity User Name ID |
| 23 | assignedBy | `Float` | User who assigned the task. |
| 24 | assignedOnDate | `DateTime` | Date on which this work order was assigned to someone else |
| 25 | attachmentLocation | `String` | Attachment Location |
| 26 | attachmentOwner | `String` | Owner who created this attachment. [ACCOUNT CONTACT ACTIVITY or BOOKING] |
| 27 | attendees | `Float` | Attendees |
| 28 | author | `Float` | Author |
| 29 | blockAll | `String` | Block All |
| 30 | cActivityAmount | `Float` | Central Activity Amount |
| 31 | cDepositAmount | `Float` | Central Deposit Amount |
| 32 | cEstCateringRevenue | `Float` | Central Est Cat Revenue |
| 33 | cEstOtherRevenue | `Float` | Central Est Other Revenue |
| 34 | cEstRoomRevenue | `Float` | Central Est Rm Revenue |
| 35 | cExchangeDate | `Date` | Central Xchange Date |
| 36 | cExchangeRate | `Float` | Central Xchange Rate |
| 37 | cTotalLaborCost | `Float` | Central Total Labor Cost |
| 38 | cTotalPartsCost | `Float` | Central Total Parts Cost |
| 39 | campaignStatusCode | `String` | Stores the status codes for Campaign Management |
| 40 | categoryCode | `String` | Category Code |
| 41 | centralActivityType | `String` | Central Activity Type |
| 42 | centralActivityTypeDescription | `String` | Central Activity Type Description |
| 43 | chainCode | `String` | Chain Code |
| 44 | completedBy | `Float` | Completed By |
| 45 | contactAll | `String` | Contact All |
| 46 | createdBy | `Float` | Created By |
| 47 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 48 | databaseId | `String` | Database ID |
| 49 | deletedFlag | `String` | Deleted Flag |
| 50 | dependingOnWoNumber | `Float` | This defines the oprder of execution between two sub work orders as one of them may be dependent on the other. |
| 51 | depositAmount | `Float` | Deposit Amount |
| 52 | depositOwner | `String` | Owner of the Deposit. It can be Opera (O) or Cencept (C). |
| 53 | deptOfAction | `String` | Dept to which the employee who created the work order belongs |
| 54 | downloadDate | `DateTime` | Download Date |
| 55 | downloadResort | `String` | Download Property |
| 56 | downloadSrep | `Float` | Download Srep |
| 57 | dueDate | `DateTime` | Due Date |
| 58 | endTime | `String` | End Time |
| 59 | estCatRevenue | `Float` | Estimated revenue. |
| 60 | estOtherRevenue | `Float` | Estimated others revenue. |
| 61 | estRoomNights | `Float` | Estimated room nights. |
| 62 | estRoomRevenue | `Float` | Estimated room revenue. |
| 63 | estTimeToComplete | `Float` | Time estimated to complete the work order |
| 64 | estUotCode | `String` | Est Uot Code |
| 65 | externalSystem | `String` | External System |
| 66 | externalSystemId | `String` | External System ID. |
| 67 | foRoomStatus | `String` | Room status at the tome of creation of work order if it happens to be in a room |
| 68 | fullName | `String` | Full Name |
| 69 | generatedByCampaign | `String` | Indicates if a Campain generated this activity. |
| 70 | generatedByFreqId | `Float` | The frequency ID which generated this activity. |
| 71 | globalYn | `String` | Global Y/N |
| 72 | guestOriginatedYn | `String` | Whether the work order is guest originated or not |
| 73 | guestRoomYn | `String` | Whether this location is a a guest room or not |
| 74 | guestType | `String` | Guest Type |
| 75 | highPriorityYn | `String` | Whether the work order is having high priority or not. |
| 76 | inactiveDate | `DateTime` | Inactive Date |
| 77 | insertDate | `DateTime` | Insert Date |
| 78 | insertUser | `Float` | Insert User |
| 79 | internalYn | `String` | Internal Y/N |
| 80 | jRNUpdateDate | `Date` | JRN Update Date |
| 81 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 82 | laptopChange | `Float` | Laptop Change |
| 83 | locationCode | `String` | Location Code |
| 84 | locationID | `String` | Internal ID to uniquely identify the Property |
| 85 | masterSub | `String` | Decides whether a particular workorder is a master or sub or none. |
| 86 | minutesBeforeAlert | `Float` | Number of minutes before the activity start time when the alert will be raised. (Default value) |
| 87 | nameID | `Float` | Name ID |
| 88 | notifiedYn | `String` | Has the user been notified about this activity ? |
| 89 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 90 | origWoNumber | `Float` | Stores the original WORK_NUMBER prior to a migration. |
| 91 | ownerEmail | `String` | Owner Email |
| 92 | ownerPhone | `String` | Phone no. |
| 93 | ownerTitle | `String` | Owner Title |
| 94 | parentWoNumber | `Float` | Wo_number to which current work order is a sub work ordergenerated work_order number |
| 95 | plantItemCode | `String` | Plant Item Code |
| 96 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 97 | priorityChangedYn | `String` | Whether the priority was manually changed or not |
| 98 | privateYn | `String` | Private Y/N |
| 99 | property | `String` | Code to uniquely identify the Property |
| 100 | proposalSentDate | `DateTime` | Proposal Sent Date |
| 101 | proposalViewToken | `String` | Proposal View Token |
| 102 | reasonCode | `String` | Reason Code |
| 103 | releasedBy | `Float` | Emp number of the person who has released this workorder |
| 104 | releasedDate | `DateTime` | Date on which a work orderwas released |
| 105 | requestTemplateId | `Float` | Stores the request template ID for Campaign Management. |
| 106 | requestTypeId | `String` | Request type that need to be generated. |
| 107 | requestTypeTemplatesId | `Float` | Stores the Campaign Type Template ID used for a campaign. |
| 108 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 109 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 110 | room | `String` | Room |
| 111 | sendMethod | `String` | Default method for sending a Request Type. |
| 112 | showOn | `DateTime` | Scheduled workorder .reminder to display on date |
| 113 | startTime | `String` | Start Time |
| 114 | statusCode | `String` | Status Code |
| 115 | surveyId | `Float` | Linked Survey ID |
| 116 | takenBy | `Float` | Empnumber of the person who has accepted this workorder |
| 117 | takenDate | `DateTime` | Date on which an employee has accepted this workorder |
| 118 | taskCode | `Float` | Task Code |
| 119 | taskitemNumber | `Float` | Taskitem Number |
| 120 | timezoneConvertedYn | `String` | Indicated if the activity times are converted to database time zone. |
| 121 | totalLaborCost | `Float` | Calculated Labor cost spent for this workorder |
| 122 | totalPartsCost | `Float` | Calculate total parts cost spent for this workorder |
| 123 | typeCode | `String` | Type Code |
| 124 | updateUser | `Float` | Update User |
| 125 | uploadDate | `DateTime` | Upload Date |
| 126 | userExt | `String` | Extension of the user |

[⬆ Back to Query](#query)

---

### ActivitiesActivityProfileDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountAddress4 | `String` | Account Address 4 |
| 2 | accountCountryCode | `String` | Account Country Code |
| 3 | accountCountryName | `String` | Account Country Name |
| 4 | accountPhone | `String` | Phone no. |
| 5 | accountPostalCode | `String` | Account Postal Code |
| 6 | accountState | `String` | Account State |
| 7 | accountType | `String` | Account Type |
| 8 | actId | `Float` | Activity ID |
| 9 | actResort | `String` | Act Property |
| 10 | addressId | `Float` | Address ID |
| 11 | attachmentYn | `String` | Identifies a linked attachment. |
| 12 | chainCode | `String` | Chain Code |
| 13 | contactAddress1 | `String` | Contact Address 1 |
| 14 | contactAddress2 | `String` | Contact Address 2 |
| 15 | contactAddress3 | `String` | Contact Address 3 |
| 16 | contactCity | `String` | Contact City |
| 17 | contactEmail | `String` | Contact Email |
| 18 | contactID | `Float` | Contact ID |
| 19 | contactName | `String` | Contact Name |
| 20 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 21 | deletedFlag | `String` | Deleted Flag |
| 22 | emailId | `Float` | Email ID |
| 23 | inactiveDate | `DateTime` | Inactive Date |
| 24 | insertDate | `DateTime` | Insert Date |
| 25 | insertUser | `Float` | Insert User |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | laptopChange | `Float` | Laptop Change |
| 29 | linkId | `Float` | Link ID |
| 30 | linkResort | `String` | Stores the property of the linked entity. |
| 31 | linkType | `String` | Link Type |
| 32 | nameType | `String` | Name Type |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryContactYN | `String` | Primary Contact YN |
| 35 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 36 | relationship | `String` | Relationship |
| 37 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 38 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 39 | toType | `String` | To Type |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ActivitiesActivityBlockDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actId | `Float` | Activity ID |
| 2 | actResort | `String` | Act Property |
| 3 | addressId | `Float` | Address ID |
| 4 | ahUpdateUser | `Float` | Ah Update User |
| 5 | allotmentOrigin | `String` | Allotment Origin |
| 6 | alternateBlockName | `String` | Multi Byte Description Field |
| 7 | attachmentYn | `String` | Identifies a linked attachment. |
| 8 | blockCode | `String` | Block Code |
| 9 | blockDeletedDate | `Date` | Block Deleted Date |
| 10 | blockID | `Float` | Block ID |
| 11 | blockName | `String` | Block Name |
| 12 | blockOwnerCode | `String` | Block Owner Code |
| 13 | blockOwnerFullName | `String` | Block Owner Full Name |
| 14 | blockStatus | `String` | Block Status |
| 15 | blockTypeCode | `String` | Block Type Code |
| 16 | blockTypeCodeDescription | `String` | Block Type Code Description |
| 17 | cateringOnlyYN | `String` | Catering only Revenue. |
| 18 | cateringStatus | `String` | Catering Status |
| 19 | centralBlockTypeCode | `String` | Central Block Type Code |
| 20 | centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| 21 | centralCateringStatus | `String` | Central Catering Status |
| 22 | centralMarketCode | `String` | Central Market  Code |
| 23 | centralMarketDescription | `String` | Central Market Description |
| 24 | centralOriginCode | `String` | Central Origin Code |
| 25 | centralOriginCodeDescription | `String` | Central Origin Code Description |
| 26 | centralReservationType | `String` | Central Reservation Type |
| 27 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 28 | centralRoomStatus | `String` | Central Room Status |
| 29 | centralSourceCode | `String` | Central Source Code |
| 30 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 31 | chainCode | `String` | Chain Code |
| 32 | createdBy | `String` | The name of the user who created the record. |
| 33 | createdDate | `DateTime` | Created Date |
| 34 | cutoffDate | `Date` | Cutoff Date |
| 35 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 36 | decisionDate | `Date` | Decision Date |
| 37 | deletedFlag | `String` | Deleted Flag |
| 38 | emailId | `Float` | Email ID |
| 39 | endDate | `Date` | End Date |
| 40 | externalReference | `String` | External Reference |
| 41 | followupDate | `Date` | Followup Date |
| 42 | inactiveDate | `DateTime` | Inactive Date |
| 43 | insertDate | `DateTime` | Insert Date |
| 44 | insertUser | `Float` | Insert User |
| 45 | inventoryControl | `String` | Inventory Control |
| 46 | jRNUpdateDate | `Date` | JRN Update Date |
| 47 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 48 | laptopChange | `Float` | Laptop Change |
| 49 | linkId | `Float` | Link ID |
| 50 | linkResort | `String` | Stores the property of the linked entity. |
| 51 | linkType | `String` | Link Type |
| 52 | marketCode | `String` | Market Code |
| 53 | marketDescription | `String` | Market Description |
| 54 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 55 | originCode | `String` | Origin Code |
| 56 | originCodeDescription | `String` | Origin Code Description |
| 57 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 58 | primaryYn | `String` | Primary Y/N |
| 59 | relationship | `String` | Relationship |
| 60 | reservationType | `String` | Reservation Type |
| 61 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 62 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 63 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 64 | shoulderEnd | `Date` | Shoulder End |
| 65 | shoulderStart | `Date` | Shoulder Start |
| 66 | sourceCode | `String` | Source Code |
| 67 | sourceCodeDescription | `String` | Source Code Description |
| 68 | startDate | `Date` | Start Date |
| 69 | status | `String` | Status |
| 70 | toType | `String` | To Type |
| 71 | updateDate | `DateTime` | Update Date |
| 72 | updateUser | `Float` | Update User |
| 73 | updatedBy | `String` | Updated By |
| 74 | updatedDate | `DateTime` | Updated Date |

[⬆ Back to Query](#query)

---

### ActivitiesActivityContactProfileDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountAddress4 | `String` | Account Address 4 |
| 2 | accountCountryCode | `String` | Account Country Code |
| 3 | accountCountryName | `String` | Account Country Name |
| 4 | accountPhone | `String` | Phone no. |
| 5 | accountPostalCode | `String` | Account Postal Code |
| 6 | accountState | `String` | Account State |
| 7 | accountType | `String` | Account Type |
| 8 | actId | `Float` | Activity ID |
| 9 | actResort | `String` | Act Property |
| 10 | addressId | `Float` | Address ID |
| 11 | attachmentYn | `String` | Identifies a linked attachment. |
| 12 | chainCode | `String` | Chain Code |
| 13 | contactAddress1 | `String` | Contact Address 1 |
| 14 | contactAddress2 | `String` | Contact Address 2 |
| 15 | contactAddress3 | `String` | Contact Address 3 |
| 16 | contactCity | `String` | Contact City |
| 17 | contactEmail | `String` | Contact Email |
| 18 | contactID | `Float` | Contact ID |
| 19 | contactName | `String` | Contact Name |
| 20 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 21 | deletedFlag | `String` | Deleted Flag |
| 22 | emailId | `Float` | Email ID |
| 23 | inactiveDate | `Date` | Inactive Date |
| 24 | insertDate | `DateTime` | Insert Date |
| 25 | insertUser | `Float` | Insert User |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | laptopChange | `Float` | Laptop Change |
| 29 | linkId | `Float` | Link ID |
| 30 | linkResort | `String` | Stores the property of the linked entity. |
| 31 | linkType | `String` | Link Type |
| 32 | nameType | `String` | Name Type |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryContactYN | `String` | Primary Contact YN |
| 35 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 36 | relationship | `String` | Relationship |
| 37 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 38 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 39 | toType | `String` | To Type |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ActivitiesPropertyPropertyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | property | `String` | The property that the record belongs to |
| 2 | aRAccountNoFormat | `String` | Number format of AR account no. |
| 3 | aRAccountNumberMandatoryYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| 4 | aRAgent | `String` | Default Account Type for an Agent for the Property |
| 5 | aRBalanceTrxCode | `String` | Internal |
| 6 | aRCompany | `String` | Default Account Type for a Company for the Property |
| 7 | aRCreditTrxCode | `String` | Internal |
| 8 | aRGroups | `String` | Default Account Type for a Group for the Property |
| 9 | aRIndividuals | `String` | Default Account Type for Individual for the Property |
| 10 | aRSettleCode | `String` | Internal |
| 11 | aRTypewriter | `String` | Internal |
| 12 | accessCode | `String` | Access Code |
| 13 | accessibleRooms | `Float` | Number of handicapped rooms. |
| 14 | agingLevel1 | `Float` | Aging bucket 1 |
| 15 | agingLevel2 | `Float` | Aging bucket 2 |
| 16 | agingLevel3 | `Float` | Aging bucket 3 |
| 17 | agingLevel4 | `Float` | Aging bucket 4 |
| 18 | agingLevel5 | `Float` | Aging bucket 3 |
| 19 | airport | `String` | The Airport Code for the airport near the property |
| 20 | airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| 21 | airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| 22 | allowLoginYN | `String` | Allow loggin in to this resort(Y/N) |
| 23 | allowancePeriodAdj | `String` | Period for the allowance |
| 24 | awardsTimeout | `Float` | Internal |
| 25 | ballroomArea | `String` | Ball Room Area |
| 26 | ballroomSeats | `Float` | No of Ballroom Seats |
| 27 | baseLanguage | `String` | The base language of the Hotel |
| 28 | block | `String` | It contains the reservation type to be used when making group block |
| 29 | brandCode | `String` | Brand Code of the property. |
| 30 | budgetMonth | `Float` | Financial Year of the Property |
| 31 | businessDate | `Date` | The date this resort becomes valid for use by the system |
| 32 | businessID | `String` | Value for the parameter. |
| 33 | businessRegistrationCode | `String` | Value for the parameter. |
| 34 | cROCODE | `String` | Code for the CRO |
| 35 | cashShiftDrop | `String` | Internal |
| 36 | cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| 37 | cateringCurrencyFormat | `String` | Catering currency format. |
| 38 | centralXchangeDate | `Date` | Central  Exchange Date |
| 39 | centralXchangeRate | `Float` | Central  Exchange Rate |
| 40 | centralCreditLimit | `Float` | Central Credit Limit |
| 41 | centralCurrencyCode | `String` | Central Currency Code |
| 42 | centralCurrencyDescription | `String` | Central Currency Description |
| 43 | centralDblRate2 | `Float` | Central Double Rate2 |
| 44 | centralDblRate1 | `Float` | Central Double Rate1 |
| 45 | centralPasserbyMarket | `String` | Central Passerby Market |
| 46 | centralPasserbySource | `String` | Central Passerby Source |
| 47 | centralPropertyType | `String` | Central Property Type |
| 48 | centralSglRate1 | `Float` | Central Sgl Rate1 |
| 49 | centralSglRate2 | `Float` | Central Sgl Rate 2 |
| 50 | centralState | `String` | Central State |
| 51 | centralStateDescription | `String` | Central State Description |
| 52 | centralSuiRate1 | `Float` | Central Sui Rate1 |
| 53 | centralSuiRate2 | `Float` | Central Sui Rate 2 |
| 54 | centralTplRate1 | `Float` | Central Tpl Rate1 |
| 55 | centralTplRate2 | `Float` | Central Tpl Rate 2 |
| 56 | centralWarningAmount | `Float` | Central Warning Amount |
| 57 | chainCode | `String` | Chain Code for the chain to which the property belongs |
| 58 | chainDescription | `String` | The description of this chain. |
| 59 | chainMode | `String` | Chain Mode |
| 60 | checkExgPaidout | `String` | Internal |
| 61 | checkOutTime | `DateTime` | The Hotel official check out time |
| 62 | checkShiftDrop | `String` | Internal |
| 63 | checkTrxcode | `String` | Internal |
| 64 | checkInTime | `DateTime` | The Hotel official check intime |
| 65 | city | `String` | The physical city in which this property resides. |
| 66 | cityDescription | `String` | City Description |
| 67 | comAddress | `String` | Internal |
| 68 | comMethod | `String` | Internal |
| 69 | comNameXrefId | `Float` | Internal |
| 70 | companyAddressType | `String` | Internal |
| 71 | companyPhoneType | `String` | Internal |
| 72 | configurationMode | `String` | Internal |
| 73 | confirmRegcardPrinter | `String` | Internal |
| 74 | connectingRooms | `Float` | Number of connecting rooms. |
| 75 | contacts | `String` | The unique name of application user |
| 76 | copies | `Float` | Number of copies to be printed |
| 77 | country | `String` | Country name. |
| 78 | countryCode | `String` | The name of the country in which this property resides. |
| 79 | countryMode | `String` | Value for the parameter. |
| 80 | creditLimit | `Float` | The default credit limit for guests. |
| 81 | currencyCode | `String` | Currency Code. |
| 82 | currencyCodeSymbol | `String` | Currency Symbol like $ or EURO symbol |
| 83 | currencyDescription | `String` | A description of this currency. |
| 84 | currencyFormat | `String` | Format for the local currency. |
| 85 | curtainColor | `String` | Color that of the background |
| 86 | dSI | `Float` | DSI |
| 87 | dateForAging | `String` | Date the aging should begin |
| 88 | dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| 89 | decimalPlaces | `Float` | Number of places for the default currency |
| 90 | decimalSeparator | `String` | Type of decimal separator |
| 91 | decimals | `Float` | Number of decimals to designate currency |
| 92 | defaultFolioStyle | `Float` | Folio style to be used for all guests |
| 93 | defaultGuestAddress | `String` | Default guest address format. |
| 94 | defaultMembershipType | `String` | Future use |
| 95 | defaultPostingRoom | `String` | Future use |
| 96 | defaultPropertyAddress | `String` | Default property address format. |
| 97 | defaultRateCode | `String` | Future use |
| 98 | defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| 99 | defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| 100 | defaultRegistrationCard | `String` | Default registration card for the property. |
| 101 | defaultReservationType | `String` | The Default reservation type for this property |
| 102 | deletedFlag | `String` | Deleted Flag |
| 103 | depositLedgerTrxCode | `String` | Future use |
| 104 | destinationId | `String` | Destination ID |
| 105 | dfltPkgTranCode | `String` | Future use |
| 106 | dfltTranCodeRateCode | `String` | Future use |
| 107 | directions | `String` | Internal |
| 108 | dirsales | `String` | Future use |
| 109 | disableLoginYN | `String` | LOGIN into the application is disabled. |
| 110 | doubleRooms | `Float` | Number of double rooms. |
| 111 | downloadRestYN | `String` | Download Rest YN |
| 112 | dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| 113 | email | `String` | Email id for the property. |
| 114 | endDate | `Date` | Future use. |
| 115 | exchangePostingType | `String` | Default Exchange posting status for the property |
| 116 | executiveFloorNumber | `String` | Floor number of executive floor. |
| 117 | expHotelCode | `String` | Hotel code used for third party exports |
| 118 | extExpFileLocation | `String` | Future use |
| 119 | extPropertyCode | `String` | Future use |
| 120 | externalSCYN | `String` | Indicates that the property uses an external SC system. |
| 121 | familyRooms | `Float` | Number of family rooms. |
| 122 | faxNoFormat | `String` | Fax number formats. |
| 123 | faxNumber | `String` | The fax phone number |
| 124 | fiscalEndDate | `Date` | Future use |
| 125 | fiscalPeriodType | `String` | Future use |
| 126 | fiscalStartDate | `Date` | Future use |
| 127 | fiscalYearBeginMonth | `Float` | Fiscal Year Begin Month |
| 128 | fiscalYearBeginYear | `Float` | Fiscal Year Begin Year |
| 129 | flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| 130 | flowCode | `String` | Future use |
| 131 | fnsTier | `String` | Property Free Nights Stay Tier. |
| 132 | folioLanguage1 | `String` | Other languages |
| 133 | folioLanguage2 | `String` | Other languages |
| 134 | folioLanguage3 | `String` | Other languages |
| 135 | folioLanguage4 | `String` | Other languages |
| 136 | genmgr | `String` | Future use |
| 137 | groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| 138 | guestLookupTimeout | `Float` | Future use |
| 139 | guestRoomElevators | `Float` | Number of guest elevators. |
| 140 | guestRoomFloors | `Float` | Total of guest rooms floors. |
| 141 | hotelCode | `String` | Future use |
| 142 | hotelFC | `String` | Future use |
| 143 | hotelID | `String` | Hotel id |
| 144 | hotelType | `String` | Future use |
| 145 | iMGDirectionID | `Float` | Future use |
| 146 | iMGHotelID | `Float` | Future use |
| 147 | iMGMapID | `Float` | Future use |
| 148 | inactiveDaysForGuestProfile | `Float` | Future use |
| 149 | inactiveFlag | `String` | Inactive Flag |
| 150 | individualAddressType | `String` | Future use |
| 151 | individualPhoneType | `String` | Future use |
| 152 | individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| 153 | insertDate | `DateTime` | The date the record was created |
| 154 | insertUser | `Float` | The user that created the record |
| 155 | intTaxIncludedYN | `String` | Int Tax Included YN |
| 156 | inventoryYN | `String` | Future use |
| 157 | jRNUpdateDate | `Date` | JRN Update Date |
| 158 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 159 | keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| 160 | latitude | `Float` | Latitude of the property in decimal |
| 161 | leadsend | `String` | Future use |
| 162 | legalOwner | `String` | The owner who owns this property |
| 163 | locationID | `String` | The property that the record belongs to |
| 164 | longDateFormat | `String` | Long date format for the property. |
| 165 | longStayControl | `Float` | The default length of stay |
| 166 | longitude | `Float` | Longitude of the property in decimal |
| 167 | maxAdultsInFamilyRoom | `Float` | Maximum adults in family rooms. |
| 168 | maxChildrenInFamilyRoom | `Float` | Maximum children in family rooms. |
| 169 | maxOccupancy | `Float` | Future use |
| 170 | maximumCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| 171 | mbsSupportedYN | `String` | Indicates whether the property supports MBS. Used in some file exports. |
| 172 | meetRooms | `Float` | Future use |
| 173 | meetSeats | `Float` | Future use |
| 174 | meetSpace | `Float` | Future use |
| 175 | meetingFC | `String` | Future use |
| 176 | minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| 177 | nameIdLink | `Float` | Internal |
| 178 | nightAuditCashierID | `String` | Future use |
| 179 | nonSmokingRooms | `Float` | Number of non smoking rooms. |
| 180 | noteDetails | `String` | Notes for the property |
| 181 | numberOfBeds | `Float` | Total number of beds in this property |
| 182 | numberOfFloors | `Float` | Total number of floors in this property |
| 183 | numberOfRooms | `Float` | Number of Rooms |
| 184 | opusCurrencyCode | `String` | Future use |
| 185 | organizationID | `Float` | Organization ID |
| 186 | organizationInternalID | `Float` | Organization Internal ID |
| 187 | ownership | `String` | Future use |
| 188 | packageLoss | `String` | Package Loss code for a particular package |
| 189 | packageProfit | `String` | Package Profit code for a particular Package |
| 190 | parentOrgCode | `String` | Parent Org Code |
| 191 | passerbyMarket | `String` | Market code |
| 192 | passerbySource | `String` | Source code |
| 193 | path | `String` | Path |
| 194 | paymentDate | `DateTime` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| 195 | perReservationRoomLimit | `Float` | Future use |
| 196 | phoneNumber | `String` | The direct dial phone number of this property |
| 197 | postalCode | `String` | The postal code of this property. |
| 198 | primaryKeyID | `Float` | Primary Key ID |
| 199 | proinfoUrl | `String` | URL where property information is located. |
| 200 | propMapUrl | `String` | Property MAP URL. |
| 201 | propPicUrl | `String` | Property picture URL. |
| 202 | propertyCode | `String` | The property that the record belongs to |
| 203 | propertyName | `String` | The name of this property. |
| 204 | propertyType | `String` | Type of resort. |
| 205 | quotedCurrency | `String` | Future use |
| 206 | rNAInsertdate | `DateTime` | RNA Insert Date |
| 207 | rNAUpdatedate | `DateTime` | RNA Update Date |
| 208 | reconcileDate | `DateTime` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| 209 | regionCode | `String` | Future use |
| 210 | regionDescription | `String` | Description of the Region. |
| 211 | restaurant | `Float` | Future use |
| 212 | rhythmSheets | `Float` | Total number of Sheets |
| 213 | rhythmTowels | `Float` | Total number of Towels |
| 214 | roomAmenities | `String` | Room amenity. |
| 215 | sGLNum | `String` | Future use |
| 216 | sGLRate1 | `Float` | Future use |
| 217 | sGLRate2 | `Float` | Future use |
| 218 | sUINum | `String` | Future use |
| 219 | sUIRate1 | `Float` | Future use |
| 220 | sUIRate2 | `Float` | Future use |
| 221 | saveProfiles | `Float` | To store number of days before deleting the gest profile |
| 222 | scriptID | `Float` | Future use |
| 223 | season1 | `String` | Future use |
| 224 | season2 | `String` | Future use |
| 225 | season3 | `String` | Future use |
| 226 | season4 | `String` | Future use |
| 227 | season5 | `String` | Future use |
| 228 | sendLeadAsBooking | `String` | Indicates that the property accepts leads as bookings. |
| 229 | shopDescription | `String` | Shop description. |
| 230 | shortDateFormat | `String` | Short date format for the property. |
| 231 | singleRooms | `Float` | Number of single rooms. |
| 232 | sourceCommission | `String` | For default commission percentage |
| 233 | state | `String` | The state in which this property is located. |
| 234 | stateDescription | `String` | Description of the state. |
| 235 | street | `String` | The street of the property. |
| 236 | suites | `Float` | Number of suites. |
| 237 | summCurrencyCode | `String` | Internal |
| 238 | tACommission | `String` | For default commission percentage |
| 239 | tPLNum | `String` | Future use |
| 240 | tPLRate1 | `Float` | Future use |
| 241 | tPLRate2 | `Float` | Future use |
| 242 | telephoneNoFormat | `String` | Formats for telephone number |
| 243 | thousandSeparator | `String` | Separator for monetory values |
| 244 | timeFormat | `String` | Default time format for the property. |
| 245 | timeZone | `String` | Time zone region selected by the employee. |
| 246 | tollFree | `String` | Toll free telephone number. |
| 247 | totalRooms | `Float` | Future use |
| 248 | touristNumber | `String` | Tourist Number |
| 249 | translateMulticharYN | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| 250 | turnawayCode | `String` | Turnaway code for the property. |
| 251 | twinRooms | `Float` | Number of twin rooms. |
| 252 | updateDate | `DateTime` | The date the record was modified |
| 253 | updateUser | `Float` | The user that modified the record |
| 254 | vatID | `String` | VAT ID of this property. |
| 255 | videoCheckoutPrinter | `String` | Future use |
| 256 | videoCheckoutStart | `DateTime` | Video check out start time. |
| 257 | videoCheckoutStop | `DateTime` | Video check out end time. |
| 258 | wakeUpDelay | `Float` | Future use |
| 259 | warningAmount | `Float` | Amount at which warning is raised. |
| 260 | web | `String` | Webaddress of the property |
| 261 | weekendDays | `String` | Weekend days for the property. |
| 262 | zeroInvPurDays | `Float` | Internal |

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

### ActivitiesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| workordersDetailsCompletedYn | `StringInput` | Activity Completed |
| workordersDetailsCreatedDate | `DateTimeInput` | Activity Created On |
| workordersDetailsEndDate | `DateTimeInput` | Activity End Date |
| workordersDetailsWoNumber | `FloatInput` | Activity ID |
| workordersDetailsProblemDesc | `StringInput` | Description of the Problem reported |
| workordersDetailsPriorityCode | `StringInput` | Activity Priority |
| workordersDetailsStartDate | `DateTimeInput` | Activity Start Date |
| workordersDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| workordersDetailsEstUotCode | `StringInput` | Est Uot Code |
| workordersDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| workordersDetailsLocationCode | `StringInput` | Location Code |
| workordersDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| workordersDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| workordersDetailsParentWoNumber | `FloatInput` | Wo_number to which current work order is a sub work ordergenerated work_order number |
| workordersDetailsPlantItemCode | `StringInput` | Plant Item Code |
| workordersDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| workordersDetailsReasonCode | `StringInput` | Reason Code |
| workordersDetailsRequestTypeId | `StringInput` | Request type that need to be generated. |
| workordersDetailsRequestTypeTemplatesId | `FloatInput` | Stores the Campaign Type Template ID used for a campaign. |
| workordersDetailsStatusCode | `StringInput` | Status Code |
| workordersDetailsSurveyId | `FloatInput` | Linked Survey ID |
| workordersDetailsTaskCode | `FloatInput` | Task Code |
| workordersDetailsTaskitemNumber | `FloatInput` | Taskitem Number |
| workordersDetailsTypeCode | `StringInput` | Type Code |
| activityprofileDetailsActId | `FloatInput` | Activity ID |
| activityprofileDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| activityprofileDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| activityprofileDetailsLinkId | `FloatInput` | Link ID |
| activityprofileDetailsLinkType | `StringInput` | Link Type |
| activityprofileDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| activityallotmentDetailsActId | `FloatInput` | Activity ID |
| activityallotmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| activityallotmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| activityallotmentDetailsLinkId | `FloatInput` | Link ID |
| activityallotmentDetailsLinkType | `StringInput` | Link Type |
| activityallotmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| activityprofilecontactDetailsActId | `FloatInput` | Activity ID |
| activityprofilecontactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| activityprofilecontactDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| activityprofilecontactDetailsLinkId | `FloatInput` | Link ID |
| activityprofilecontactDetailsLinkType | `StringInput` | Link Type |
| activityprofilecontactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortDetailsResort | `StringInput` | The property that the record belongs to |
| resortDetailsArAcctNoFormat | `StringInput` | Number format of AR account no. |
| resortDetailsArAcctNoMandYn | `StringInput` | Specifies if the AR acct No is mandatory(Y/N) |
| resortDetailsArAgent | `StringInput` | Default Account Type for an Agent for the Property |
| resortDetailsArBalTrxCode | `StringInput` | Internal |
| resortDetailsArCompany | `StringInput` | Default Account Type for a Company for the Property |
| resortDetailsArCreditTrxCode | `StringInput` | Internal |
| resortDetailsArGroups | `StringInput` | Default Account Type for a Group for the Property |
| resortDetailsArIndividuals | `StringInput` | Default Account Type for Individual for the Property |
| resortDetailsArSettleCode | `StringInput` | Internal |
| resortDetailsArTypewriter | `StringInput` | Internal |
| resortDetailsAccessCode | `StringInput` | Access Code |
| resortDetailsQtyHandicappedRooms | `FloatInput` | Number of handicapped rooms. |
| resortDetailsAgingLevel1 | `FloatInput` | Aging bucket 1 |
| resortDetailsAgingLevel2 | `FloatInput` | Aging bucket 2 |
| resortDetailsAgingLevel3 | `FloatInput` | Aging bucket 3 |
| resortDetailsAgingLevel4 | `FloatInput` | Aging bucket 4 |
| resortDetailsAgingLevel5 | `FloatInput` | Aging bucket 3 |
| resortDetailsAirport | `StringInput` | The Airport Code for the airport near the property |
| resortDetailsAirportDistance | `StringInput` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| resortDetailsAirportTime | `StringInput` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| resortDetailsAllowLoginYn | `StringInput` | Allow loggin in to this resort(Y/N) |
| resortDetailsAllowancePeriodAdj | `StringInput` | Period for the allowance |
| resortDetailsAwardsTimeout | `FloatInput` | Internal |
| resortDetailsBrArea | `StringInput` | Ball Room Area |
| resortDetailsBrSeats | `FloatInput` | No of Ballroom Seats |
| resortDetailsBaseLanguage | `StringInput` | The base language of the Hotel |
| resortDetailsBlock | `StringInput` | It contains the reservation type to be used when making group block |
| resortDetailsBrandCode | `StringInput` | Brand Code of the property. |
| resortDetailsBudgetMonth | `FloatInput` | Financial Year of the Property |
| resortDetailsBeginDate | `DateInput` | The date this resort becomes valid for use by the system |
| resortDetailsBusinessId | `StringInput` | Value for the parameter. |
| resortDetailsBusinessRegCode | `StringInput` | Value for the parameter. |
| resortDetailsCroCode | `StringInput` | Code for the CRO |
| resortDetailsCashShiftDrop | `StringInput` | Internal |
| resortDetailsCateringCurrencyCode | `StringInput` | Catering Currency Code used when Catering Currency differs from base currency. |
| resortDetailsCateringCurrencyFormat | `StringInput` | Catering currency format. |
| resortDetailsCXchangeDate | `DateInput` | Central  Exchange Date |
| resortDetailsCXchangeRate | `FloatInput` | Central  Exchange Rate |
| resortDetailsCCreditLimit | `FloatInput` | Central Credit Limit |
| resortDetailsCentralCurrencyCode | `StringInput` | Central Currency Code |
| resortDetailsCentralCurrencyDesc | `StringInput` | Central Currency Description |
| resortDetailsCDblRate2 | `FloatInput` | Central Double Rate2 |
| resortDetailsCDblRate1 | `FloatInput` | Central Double Rate1 |
| resortDetailsRepPasserbyMarket | `StringInput` | Central Passerby Market |
| resortDetailsRepPasserbySource | `StringInput` | Central Passerby Source |
| resortDetailsRepResortType | `StringInput` | Central Property Type |
| resortDetailsCSglRate1 | `FloatInput` | Central Sgl Rate1 |
| resortDetailsCSglRate2 | `FloatInput` | Central Sgl Rate 2 |
| resortDetailsRepState | `StringInput` | Central State |
| resortDetailsRepStateDesc | `StringInput` | Central State Description |
| resortDetailsCSuiRate1 | `FloatInput` | Central Sui Rate1 |
| resortDetailsCSuiRate2 | `FloatInput` | Central Sui Rate 2 |
| resortDetailsCTplRate1 | `FloatInput` | Central Tpl Rate1 |
| resortDetailsCTplRate2 | `FloatInput` | Central Tpl Rate 2 |
| resortDetailsCWarningAmount | `FloatInput` | Central Warning Amount |
| resortDetailsChainCode | `StringInput` | Chain Code for the chain to which the property belongs |
| resortDetailsChainDescription | `StringInput` | The description of this chain. |
| resortDetailsChainMode | `StringInput` | Chain Mode |
| resortDetailsCheckExgPaidout | `StringInput` | Internal |
| resortDetailsCheckOutTime | `DateTimeInput` | The Hotel official check out time |
| resortDetailsCheckShiftDrop | `StringInput` | Internal |
| resortDetailsCheckTrxcode | `StringInput` | Internal |
| resortDetailsCheckInTime | `DateTimeInput` | The Hotel official check intime |
| resortDetailsCity | `StringInput` | The physical city in which this property resides. |
| resortDetailsCityDescription | `StringInput` | City Description |
| resortDetailsComAddress | `StringInput` | Internal |
| resortDetailsComMethod | `StringInput` | Internal |
| resortDetailsComNameXrefId | `FloatInput` | Internal |
| resortDetailsCompanyAddressType | `StringInput` | Internal |
| resortDetailsCompanyPhoneType | `StringInput` | Internal |
| resortDetailsConfigurationMode | `StringInput` | Internal |
| resortDetailsConfirmRegcardPrinter | `StringInput` | Internal |
| resortDetailsQtyConnectingRooms | `FloatInput` | Number of connecting rooms. |
| resortDetailsAllContacts | `StringInput` | The unique name of application user |
| resortDetailsCopies | `FloatInput` | Number of copies to be printed |
| resortDetailsCountryName | `StringInput` | Country name. |
| resortDetailsCountryCode | `StringInput` | The name of the country in which this property resides. |
| resortDetailsCountryMode | `StringInput` | Value for the parameter. |
| resortDetailsCreditLimit | `FloatInput` | The default credit limit for guests. |
| resortDetailsCurrencyCode | `StringInput` | Currency Code. |
| resortDetailsCurrencySymbol | `StringInput` | Currency Symbol like $ or EURO symbol |
| resortDetailsCurrencyName | `StringInput` | A description of this currency. |
| resortDetailsLocalCurrencyFormat | `StringInput` | Format for the local currency. |
| resortDetailsCurtainColor | `StringInput` | Color that of the background |
| resortDetailsDsi | `FloatInput` | DSI |
| resortDetailsDateForAging | `StringInput` | Date the aging should begin |
| resortDetailsDateSeparator | `StringInput` | Type of separator to distinguish between DD MM and YYYY |
| resortDetailsDecimalPlaces | `FloatInput` | Number of places for the default currency |
| resortDetailsDecimalSeparator | `StringInput` | Type of decimal separator |
| resortDetailsCurrencyDecimals | `FloatInput` | Number of decimals to designate currency |
| resortDetailsDefaultFolioStyle | `FloatInput` | Folio style to be used for all guests |
| resortDetailsDefaultGuestAddress | `StringInput` | Default guest address format. |
| resortDetailsDefaultMembershipType | `StringInput` | Future use |
| resortDetailsDefaultPostingRoom | `StringInput` | Future use |
| resortDetailsDefaultPropertyAddress | `StringInput` | Default property address format. |
| resortDetailsDefaultRateCode | `StringInput` | Future use |
| resortDetailsDefaultRatecodePcr | `StringInput` | Rate code used to default a PCR rate code used in FIT Contracts. |
| resortDetailsDefaultRatecodeRack | `StringInput` | Rate code used to default a RACK rate code used for FIT Contracts. |
| resortDetailsDefaultRegistrationCard | `StringInput` | Default registration card for the property. |
| resortDetailsDefaultReservationType | `StringInput` | The Default reservation type for this property |
| resortDetailsDeletedFlag | `StringInput` | Deleted Flag |
| resortDetailsDepositLedTrxCode | `StringInput` | Future use |
| resortDetailsDestinationId | `StringInput` | Destination ID |
| resortDetailsDfltPkgTranCode | `StringInput` | Future use |
| resortDetailsDfltTranCodeRateCode | `StringInput` | Future use |
| resortDetailsDirections | `StringInput` | Internal |
| resortDetailsDirsales | `StringInput` | Future use |
| resortDetailsDisableLoginYn | `StringInput` | LOGIN into the application is disabled. |
| resortDetailsQtyDoubleRooms | `FloatInput` | Number of double rooms. |
| resortDetailsDownloadRestYn | `StringInput` | Download Rest YN |
| resortDetailsDutyManagerPager | `StringInput` | Pager number for the Manager on duty for the property. |
| resortDetailsEmail | `StringInput` | Email id for the property. |
| resortDetailsEndDate | `DateInput` | Future use. |
| resortDetailsExchangePostingType | `StringInput` | Default Exchange posting status for the property |
| resortDetailsFloorNumExecutiveFloor | `StringInput` | Floor number of executive floor. |
| resortDetailsExpHotelCode | `StringInput` | Hotel code used for third party exports |
| resortDetailsExtExpFileLocation | `StringInput` | Future use |
| resortDetailsExtPropertyCode | `StringInput` | Future use |
| resortDetailsExternalScYn | `StringInput` | Indicates that the property uses an external SC system. |
| resortDetailsQtyFamilyRooms | `FloatInput` | Number of family rooms. |
| resortDetailsFaxNoFormat | `StringInput` | Fax number formats. |
| resortDetailsFax | `StringInput` | The fax phone number |
| resortDetailsFiscalEndDate | `DateInput` | Future use |
| resortDetailsFiscalPeriodType | `StringInput` | Future use |
| resortDetailsFiscalStartDate | `DateInput` | Future use |
| resortDetailsFiscalStartMonth | `FloatInput` | Fiscal Year Begin Month |
| resortDetailsFiscalStartYear | `FloatInput` | Fiscal Year Begin Year |
| resortDetailsFlags | `StringInput` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| resortDetailsFlowCode | `StringInput` | Future use |
| resortDetailsFnsTier | `StringInput` | Property Free Nights Stay Tier. |
| resortDetailsFolioLanguage1 | `StringInput` | Other languages |
| resortDetailsFolioLanguage2 | `StringInput` | Other languages |
| resortDetailsFolioLanguage3 | `StringInput` | Other languages |
| resortDetailsFolioLanguage4 | `StringInput` | Other languages |
| resortDetailsGenmgr | `StringInput` | Future use |
| resortDetailsGroupRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for Group |
| resortDetailsGuestLookupTimeout | `FloatInput` | Future use |
| resortDetailsQtyGuestElevators | `FloatInput` | Number of guest elevators. |
| resortDetailsQtyGuestRoomFloors | `FloatInput` | Total of guest rooms floors. |
| resortDetailsHotelCode | `StringInput` | Future use |
| resortDetailsHotelFc | `StringInput` | Future use |
| resortDetailsHotelId | `StringInput` | Hotel id |
| resortDetailsHotelType | `StringInput` | Future use |
| resortDetailsImgDirectionId | `FloatInput` | Future use |
| resortDetailsImgHotelId | `FloatInput` | Future use |
| resortDetailsImgMapId | `FloatInput` | Future use |
| resortDetailsInactiveDaysForGuestProfil | `FloatInput` | Future use |
| resortDetailsInactiveFlag | `StringInput` | Inactive Flag |
| resortDetailsIndividualAddressType | `StringInput` | Future use |
| resortDetailsIndividualPhoneType | `StringInput` | Future use |
| resortDetailsIndividualRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for group |
| resortDetailsInsertDate | `DateTimeInput` | The date the record was created |
| resortDetailsInsertUser | `FloatInput` | The user that created the record |
| resortDetailsIntTaxIncludedYn | `StringInput` | Int Tax Included YN |
| resortDetailsInventoryYn | `StringInput` | Future use |
| resortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortDetailsKeepAvailability | `FloatInput` | To calculate the entire availability of the Hotel for future reservations |
| resortDetailsLatitude | `FloatInput` | Latitude of the property in decimal |
| resortDetailsLeadsend | `StringInput` | Future use |
| resortDetailsLegalOwner | `StringInput` | The owner who owns this property |
| resortDetailsLocationId | `StringInput` | The property that the record belongs to |
| resortDetailsLongDateFormat | `StringInput` | Long date format for the property. |
| resortDetailsLongStayControl | `FloatInput` | The default length of stay |
| resortDetailsLongitude | `FloatInput` | Longitude of the property in decimal |
| resortDetailsMaxAdultsFamilyRoom | `FloatInput` | Maximum adults in family rooms. |
| resortDetailsMaxChildrenFamilyRoom | `FloatInput` | Maximum children in family rooms. |
| resortDetailsMaxOccupancy | `FloatInput` | Future use |
| resortDetailsMaxcreditdays | `FloatInput` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| resortDetailsMbsSupportedYn | `StringInput` | Indicates whether the property supports MBS. Used in some file exports. |
| resortDetailsMeetRooms | `FloatInput` | Future use |
| resortDetailsMeetSeats | `FloatInput` | Future use |
| resortDetailsMeetSpace | `FloatInput` | Future use |
| resortDetailsMeetingFc | `StringInput` | Future use |
| resortDetailsMinDaysBet2ReminderLetter | `FloatInput` | Minimum days for reminder letter. |
| resortDetailsNameIdLink | `FloatInput` | Internal |
| resortDetailsNightAuditCashierId | `StringInput` | Future use |
| resortDetailsQtyNonSmokingRooms | `FloatInput` | Number of non smoking rooms. |
| resortDetailsNotes | `StringInput` | Notes for the property |
| resortDetailsNumberBeds | `FloatInput` | Total number of beds in this property |
| resortDetailsNumberFloors | `FloatInput` | Total number of floors in this property |
| resortDetailsNumberRooms | `FloatInput` | Number of Rooms |
| resortDetailsOpusCurrencyCode | `StringInput` | Future use |
| resortDetailsOrganizationId | `FloatInput` | Organization ID |
| resortDetailsOrganizationid | `FloatInput` | Organization Internal ID |
| resortDetailsOwnership | `StringInput` | Future use |
| resortDetailsPackageLoss | `StringInput` | Package Loss code for a particular package |
| resortDetailsPackageProfit | `StringInput` | Package Profit code for a particular Package |
| resortDetailsParentOrgCode | `StringInput` | Parent Org Code |
| resortDetailsPasserbyMarket | `StringInput` | Market code |
| resortDetailsPasserbySource | `StringInput` | Source code |
| resortDetailsPath | `StringInput` | Path |
| resortDetailsPaymentDate | `DateTimeInput` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| resortDetailsPerReservationRoomLimit | `FloatInput` | Future use |
| resortDetailsTelephone | `StringInput` | The direct dial phone number of this property |
| resortDetailsPostCode | `StringInput` | The postal code of this property. |
| resortDetailsPkid | `FloatInput` | Primary Key ID |
| resortDetailsProinfoUrl | `StringInput` | URL where property information is located. |
| resortDetailsPropMapUrl | `StringInput` | Property MAP URL. |
| resortDetailsPropPicUrl | `StringInput` | Property picture URL. |
| resortDetailsLocationid | `StringInput` | The property that the record belongs to |
| resortDetailsName | `StringInput` | The name of this property. |
| resortDetailsResortType | `StringInput` | Type of resort. |
| resortDetailsQuotedCurrency | `StringInput` | Future use |
| resortDetailsRnaInsertdate | `DateTimeInput` | RNA Insert Date |
| resortDetailsRnaUpdatedate | `DateTimeInput` | RNA Update Date |
| resortDetailsReconcileDate | `DateTimeInput` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| resortDetailsRegionCode | `StringInput` | Future use |
| resortDetailsRegionDescription | `StringInput` | Description of the Region. |
| resortDetailsRestaurant | `FloatInput` | Future use |
| resortDetailsRhythmSheets | `FloatInput` | Total number of Sheets |
| resortDetailsRhythmTowels | `FloatInput` | Total number of Towels |
| resortDetailsRoomAmenity | `StringInput` | Room amenity. |
| resortDetailsSglNum | `StringInput` | Future use |
| resortDetailsSglRate1 | `FloatInput` | Future use |
| resortDetailsSglRate2 | `FloatInput` | Future use |
| resortDetailsSuiNum | `StringInput` | Future use |
| resortDetailsSuiRate1 | `FloatInput` | Future use |
| resortDetailsSuiRate2 | `FloatInput` | Future use |
| resortDetailsSaveProfiles | `FloatInput` | To store number of days before deleting the gest profile |
| resortDetailsScriptId | `FloatInput` | Future use |
| resortDetailsSeason1 | `StringInput` | Future use |
| resortDetailsSeason2 | `StringInput` | Future use |
| resortDetailsSeason3 | `StringInput` | Future use |
| resortDetailsSeason4 | `StringInput` | Future use |
| resortDetailsSeason5 | `StringInput` | Future use |
| resortDetailsSendLeadAsBooking | `StringInput` | Indicates that the property accepts leads as bookings. |
| resortDetailsShopDescription | `StringInput` | Shop description. |
| resortDetailsShortDateFormat | `StringInput` | Short date format for the property. |
| resortDetailsQtySingleRooms | `FloatInput` | Number of single rooms. |
| resortDetailsSourceCommission | `StringInput` | For default commission percentage |
| resortDetailsState | `StringInput` | The state in which this property is located. |
| resortDetailsStateDesc | `StringInput` | Description of the state. |
| resortDetailsStreet | `StringInput` | The street of the property. |
| resortDetailsQtySuites | `FloatInput` | Number of suites. |
| resortDetailsSummCurrencyCode | `StringInput` | Internal |
| resortDetailsTaCommission | `StringInput` | For default commission percentage |
| resortDetailsTplNum | `StringInput` | Future use |
| resortDetailsTplRate1 | `FloatInput` | Future use |
| resortDetailsTplRate2 | `FloatInput` | Future use |
| resortDetailsTelephoneNoFormat | `StringInput` | Formats for telephone number |
| resortDetailsThousandSeparator | `StringInput` | Separator for monetory values |
| resortDetailsTimeFormat | `StringInput` | Default time format for the property. |
| resortDetailsTimezoneRegion | `StringInput` | Time zone region selected by the employee. |
| resortDetailsTollfree | `StringInput` | Toll free telephone number. |
| resortDetailsTotRooms | `FloatInput` | Future use |
| resortDetailsTouristNumber | `StringInput` | Tourist Number |
| resortDetailsTranslateMulticharYn | `StringInput` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| resortDetailsTurnawayCode | `StringInput` | Turnaway code for the property. |
| resortDetailsQtyTwinRooms | `FloatInput` | Number of twin rooms. |
| resortDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| resortDetailsUpdateUser | `FloatInput` | The user that modified the record |
| resortDetailsVatId | `StringInput` | VAT ID of this property. |
| resortDetailsVideocheckoutPrinter | `StringInput` | Future use |
| resortDetailsVideoCoStart | `DateTimeInput` | Video check out start time. |
| resortDetailsVideoCoStop | `DateTimeInput` | Video check out end time. |
| resortDetailsWakeUpDelay | `FloatInput` | Future use |
| resortDetailsWarningAmount | `FloatInput` | Amount at which warning is raised. |
| resortDetailsWebaddress | `StringInput` | Webaddress of the property |
| resortDetailsWeekendDays | `StringInput` | Weekend days for the property. |
| resortDetailsZeroInvPurDays | `FloatInput` | Internal |
#### Validation Rules

**`mandatoryInput`**
- workordersDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query activities($input: ActivitiesQueryArgumentsType!) {
  activities(input: $input) @stream {
    workOrdersDetails {
      accountAll
      activityAmount
      activityClass
      activityCompleted
      activityCompletedBy
      activityCompletionDate
      activityCreatedBy
      activityCreatedOn
      activityEndDate
      activityID
      activityName
      activityNotes
      activityOwnerCode
      activityPriority
      activityResult
      activityStartDate
      activityTraceCode
      activityType
      activityTypeDescription
      activityUpdatedBy
      activityUpdatedOn
      activityUserNameID
      assignedBy
      assignedOnDate
      attachmentLocation
      attachmentOwner
      attendees
      author
      blockAll
      cActivityAmount
      cDepositAmount
      cEstCateringRevenue
      cEstOtherRevenue
      cEstRoomRevenue
      cExchangeDate
      cExchangeRate
      cTotalLaborCost
      cTotalPartsCost
      campaignStatusCode
      categoryCode
      centralActivityType
      centralActivityTypeDescription
      chainCode
      completedBy
      contactAll
      createdBy
      dSI
      databaseId
      deletedFlag
      dependingOnWoNumber
      depositAmount
      depositOwner
      deptOfAction
      downloadDate
      downloadResort
      downloadSrep
      dueDate
      endTime
      estCatRevenue
      estOtherRevenue
      estRoomNights
      estRoomRevenue
      estTimeToComplete
      estUotCode
      externalSystem
      externalSystemId
      foRoomStatus
      fullName
      generatedByCampaign
      generatedByFreqId
      globalYn
      guestOriginatedYn
      guestRoomYn
      guestType
      highPriorityYn
      inactiveDate
      insertDate
      insertUser
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationCode
      locationID
      masterSub
      minutesBeforeAlert
      nameID
      notifiedYn
      organizationID
      origWoNumber
      ownerEmail
      ownerPhone
      ownerTitle
      parentWoNumber
      plantItemCode
      primaryKeyID
      priorityChangedYn
      privateYn
      property
      proposalSentDate
      proposalViewToken
      reasonCode
      releasedBy
      releasedDate
      requestTemplateId
      requestTypeId
      requestTypeTemplatesId
      rnaInsertDate
      rnaUpdateDate
      room
      sendMethod
      showOn
      startTime
      statusCode
      surveyId
      takenBy
      takenDate
      taskCode
      taskitemNumber
      timezoneConvertedYn
      totalLaborCost
      totalPartsCost
      typeCode
      updateUser
      uploadDate
      userExt
    }
    activityProfileDetails {
      accountAddress4
      accountCountryCode
      accountCountryName
      accountPhone
      accountPostalCode
      accountState
      accountType
      actId
      actResort
      addressId
      attachmentYn
      chainCode
      contactAddress1
      contactAddress2
      contactAddress3
      contactCity
      contactEmail
      contactID
      contactName
      dSI
      deletedFlag
      emailId
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkId
      linkResort
      linkType
      nameType
      organizationID
      primaryContactYN
      primaryKeyID
      relationship
      rnaInsertDate
      rnaUpdateDate
      toType
      updateDate
      updateUser
    }
    activityBlockDetails {
      actId
      actResort
      addressId
      ahUpdateUser
      allotmentOrigin
      alternateBlockName
      attachmentYn
      blockCode
      blockDeletedDate
      blockID
      blockName
      blockOwnerCode
      blockOwnerFullName
      blockStatus
      blockTypeCode
      blockTypeCodeDescription
      cateringOnlyYN
      cateringStatus
      centralBlockTypeCode
      centralBlockTypeCodeDescription
      centralCateringStatus
      centralMarketCode
      centralMarketDescription
      centralOriginCode
      centralOriginCodeDescription
      centralReservationType
      centralReservationTypeDescription
      centralRoomStatus
      centralSourceCode
      centralSourceCodeDescription
      chainCode
      createdBy
      createdDate
      cutoffDate
      dSI
      decisionDate
      deletedFlag
      emailId
      endDate
      externalReference
      followupDate
      inactiveDate
      insertDate
      insertUser
      inventoryControl
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkId
      linkResort
      linkType
      marketCode
      marketDescription
      organizationID
      originCode
      originCodeDescription
      primaryKeyID
      primaryYn
      relationship
      reservationType
      reservationTypeDescription
      rnaInsertDate
      rnaUpdateDate
      shoulderEnd
      shoulderStart
      sourceCode
      sourceCodeDescription
      startDate
      status
      toType
      updateDate
      updateUser
      updatedBy
      updatedDate
    }
    activityContactProfileDetails {
      accountAddress4
      accountCountryCode
      accountCountryName
      accountPhone
      accountPostalCode
      accountState
      accountType
      actId
      actResort
      addressId
      attachmentYn
      chainCode
      contactAddress1
      contactAddress2
      contactAddress3
      contactCity
      contactEmail
      contactID
      contactName
      dSI
      deletedFlag
      emailId
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkId
      linkResort
      linkType
      nameType
      organizationID
      primaryContactYN
      primaryKeyID
      relationship
      rnaInsertDate
      rnaUpdateDate
      toType
      updateDate
      updateUser
    }
    propertyPropertyDetails {
      property
      aRAccountNoFormat
      aRAccountNumberMandatoryYN
      aRAgent
      aRBalanceTrxCode
      aRCompany
      aRCreditTrxCode
      aRGroups
      aRIndividuals
      aRSettleCode
      aRTypewriter
      accessCode
      accessibleRooms
      agingLevel1
      agingLevel2
      agingLevel3
      agingLevel4
      agingLevel5
      airport
      airportDistance
      airportTime
      allowLoginYN
      allowancePeriodAdj
      awardsTimeout
      ballroomArea
      ballroomSeats
      baseLanguage
      block
      brandCode
      budgetMonth
      businessDate
      businessID
      businessRegistrationCode
      cROCODE
      cashShiftDrop
      cateringCurrencyCode
      cateringCurrencyFormat
      centralXchangeDate
      centralXchangeRate
      centralCreditLimit
      centralCurrencyCode
      centralCurrencyDescription
      centralDblRate2
      centralDblRate1
      centralPasserbyMarket
      centralPasserbySource
      centralPropertyType
      centralSglRate1
      centralSglRate2
      centralState
      centralStateDescription
      centralSuiRate1
      centralSuiRate2
      centralTplRate1
      centralTplRate2
      centralWarningAmount
      chainCode
      chainDescription
      chainMode
      checkExgPaidout
      checkOutTime
      checkShiftDrop
      checkTrxcode
      checkInTime
      city
      cityDescription
      comAddress
      comMethod
      comNameXrefId
      companyAddressType
      companyPhoneType
      configurationMode
      confirmRegcardPrinter
      connectingRooms
      contacts
      copies
      country
      countryCode
      countryMode
      creditLimit
      currencyCode
      currencyCodeSymbol
      currencyDescription
      currencyFormat
      curtainColor
      dSI
      dateForAging
      dateSeparator
      decimalPlaces
      decimalSeparator
      decimals
      defaultFolioStyle
      defaultGuestAddress
      defaultMembershipType
      defaultPostingRoom
      defaultPropertyAddress
      defaultRateCode
      defaultRatecodePcr
      defaultRatecodeRack
      defaultRegistrationCard
      defaultReservationType
      deletedFlag
      depositLedgerTrxCode
      destinationId
      dfltPkgTranCode
      dfltTranCodeRateCode
      directions
      dirsales
      disableLoginYN
      doubleRooms
      downloadRestYN
      dutyManagerPager
      email
      endDate
      exchangePostingType
      executiveFloorNumber
      expHotelCode
      extExpFileLocation
      extPropertyCode
      externalSCYN
      familyRooms
      faxNoFormat
      faxNumber
      fiscalEndDate
      fiscalPeriodType
      fiscalStartDate
      fiscalYearBeginMonth
      fiscalYearBeginYear
      flags
      flowCode
      fnsTier
      folioLanguage1
      folioLanguage2
      folioLanguage3
      folioLanguage4
      genmgr
      groupRoomWarning
      guestLookupTimeout
      guestRoomElevators
      guestRoomFloors
      hotelCode
      hotelFC
      hotelID
      hotelType
      iMGDirectionID
      iMGHotelID
      iMGMapID
      inactiveDaysForGuestProfile
      inactiveFlag
      individualAddressType
      individualPhoneType
      individualRoomWarning
      insertDate
      insertUser
      intTaxIncludedYN
      inventoryYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepAvailability
      latitude
      leadsend
      legalOwner
      locationID
      longDateFormat
      longStayControl
      longitude
      maxAdultsInFamilyRoom
      maxChildrenInFamilyRoom
      maxOccupancy
      maximumCreditDays
      mbsSupportedYN
      meetRooms
      meetSeats
      meetSpace
      meetingFC
      minDaysBet2ReminderLetter
      nameIdLink
      nightAuditCashierID
      nonSmokingRooms
      noteDetails
      numberOfBeds
      numberOfFloors
      numberOfRooms
      opusCurrencyCode
      organizationID
      organizationInternalID
      ownership
      packageLoss
      packageProfit
      parentOrgCode
      passerbyMarket
      passerbySource
      path
      paymentDate
      perReservationRoomLimit
      phoneNumber
      postalCode
      primaryKeyID
      proinfoUrl
      propMapUrl
      propPicUrl
      propertyCode
      propertyName
      propertyType
      quotedCurrency
      rNAInsertdate
      rNAUpdatedate
      reconcileDate
      regionCode
      regionDescription
      restaurant
      rhythmSheets
      rhythmTowels
      roomAmenities
      sGLNum
      sGLRate1
      sGLRate2
      sUINum
      sUIRate1
      sUIRate2
      saveProfiles
      scriptID
      season1
      season2
      season3
      season4
      season5
      sendLeadAsBooking
      shopDescription
      shortDateFormat
      singleRooms
      sourceCommission
      state
      stateDescription
      street
      suites
      summCurrencyCode
      tACommission
      tPLNum
      tPLRate1
      tPLRate2
      telephoneNoFormat
      thousandSeparator
      timeFormat
      timeZone
      tollFree
      totalRooms
      touristNumber
      translateMulticharYN
      turnawayCode
      twinRooms
      updateDate
      updateUser
      vatID
      videoCheckoutPrinter
      videoCheckoutStart
      videoCheckoutStop
      wakeUpDelay
      warningAmount
      web
      weekendDays
      zeroInvPurDays
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
work_orders_details_schema = {
    'accountAll': pl.Utf8,
    'activityAmount': pl.Float64,
    'activityClass': pl.Utf8,
    'activityCompleted': pl.Utf8,
    'activityCompletedBy': pl.Utf8,
    'activityCompletionDate': pl.Float64,
    'activityCreatedBy': pl.Utf8,
    'activityCreatedOn': pl.Utf8,
    'activityEndDate': pl.Utf8,
    'activityID': pl.Float64,
    'activityName': pl.Utf8,
    'activityNotes': pl.Utf8,
    'activityOwnerCode': pl.Utf8,
    'activityPriority': pl.Utf8,
    'activityResult': pl.Utf8,
    'activityStartDate': pl.Utf8,
    'activityTraceCode': pl.Utf8,
    'activityType': pl.Utf8,
    'activityTypeDescription': pl.Utf8,
    'activityUpdatedBy': pl.Utf8,
    'activityUpdatedOn': pl.Utf8,
    'activityUserNameID': pl.Utf8,
    'assignedBy': pl.Float64,
    'assignedOnDate': pl.Utf8,
    'attachmentLocation': pl.Utf8,
    'attachmentOwner': pl.Utf8,
    'attendees': pl.Float64,
    'author': pl.Float64,
    'blockAll': pl.Utf8,
    'cActivityAmount': pl.Float64,
    'cDepositAmount': pl.Float64,
    'cEstCateringRevenue': pl.Float64,
    'cEstOtherRevenue': pl.Float64,
    'cEstRoomRevenue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cTotalLaborCost': pl.Float64,
    'cTotalPartsCost': pl.Float64,
    'campaignStatusCode': pl.Utf8,
    'categoryCode': pl.Utf8,
    'centralActivityType': pl.Utf8,
    'centralActivityTypeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'completedBy': pl.Float64,
    'contactAll': pl.Utf8,
    'createdBy': pl.Float64,
    'dSI': pl.Int64,
    'databaseId': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'dependingOnWoNumber': pl.Float64,
    'depositAmount': pl.Float64,
    'depositOwner': pl.Utf8,
    'deptOfAction': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'endTime': pl.Utf8,
    'estCatRevenue': pl.Float64,
    'estOtherRevenue': pl.Float64,
    'estRoomNights': pl.Float64,
    'estRoomRevenue': pl.Float64,
    'estTimeToComplete': pl.Float64,
    'estUotCode': pl.Utf8,
    'externalSystem': pl.Utf8,
    'externalSystemId': pl.Utf8,
    'foRoomStatus': pl.Utf8,
    'fullName': pl.Utf8,
    'generatedByCampaign': pl.Utf8,
    'generatedByFreqId': pl.Float64,
    'globalYn': pl.Utf8,
    'guestOriginatedYn': pl.Utf8,
    'guestRoomYn': pl.Utf8,
    'guestType': pl.Utf8,
    'highPriorityYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSub': pl.Utf8,
    'minutesBeforeAlert': pl.Float64,
    'nameID': pl.Float64,
    'notifiedYn': pl.Utf8,
    'organizationID': pl.Int64,
    'origWoNumber': pl.Float64,
    'ownerEmail': pl.Utf8,
    'ownerPhone': pl.Utf8,
    'ownerTitle': pl.Utf8,
    'parentWoNumber': pl.Float64,
    'plantItemCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'priorityChangedYn': pl.Utf8,
    'privateYn': pl.Utf8,
    'property': pl.Utf8,
    'proposalSentDate': pl.Utf8,
    'proposalViewToken': pl.Utf8,
    'reasonCode': pl.Utf8,
    'releasedBy': pl.Float64,
    'releasedDate': pl.Utf8,
    'requestTemplateId': pl.Float64,
    'requestTypeId': pl.Utf8,
    'requestTypeTemplatesId': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'sendMethod': pl.Utf8,
    'showOn': pl.Utf8,
    'startTime': pl.Utf8,
    'statusCode': pl.Utf8,
    'surveyId': pl.Float64,
    'takenBy': pl.Float64,
    'takenDate': pl.Utf8,
    'taskCode': pl.Float64,
    'taskitemNumber': pl.Float64,
    'timezoneConvertedYn': pl.Utf8,
    'totalLaborCost': pl.Float64,
    'totalPartsCost': pl.Float64,
    'typeCode': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'userExt': pl.Utf8,
}
```
```python
activity_profile_details_schema = {
    'accountAddress4': pl.Utf8,
    'accountCountryCode': pl.Utf8,
    'accountCountryName': pl.Utf8,
    'accountPhone': pl.Utf8,
    'accountPostalCode': pl.Utf8,
    'accountState': pl.Utf8,
    'accountType': pl.Utf8,
    'actId': pl.Float64,
    'actResort': pl.Utf8,
    'addressId': pl.Float64,
    'attachmentYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'contactAddress1': pl.Utf8,
    'contactAddress2': pl.Utf8,
    'contactAddress3': pl.Utf8,
    'contactCity': pl.Utf8,
    'contactEmail': pl.Utf8,
    'contactID': pl.Float64,
    'contactName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'nameType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryContactYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'relationship': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
activity_block_details_schema = {
    'actId': pl.Float64,
    'actResort': pl.Utf8,
    'addressId': pl.Float64,
    'ahUpdateUser': pl.Float64,
    'allotmentOrigin': pl.Utf8,
    'alternateBlockName': pl.Utf8,
    'attachmentYn': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockDeletedDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockOwnerFullName': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockTypeCode': pl.Utf8,
    'blockTypeCodeDescription': pl.Utf8,
    'cateringOnlyYN': pl.Utf8,
    'cateringStatus': pl.Utf8,
    'centralBlockTypeCode': pl.Utf8,
    'centralBlockTypeCodeDescription': pl.Utf8,
    'centralCateringStatus': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralOriginCode': pl.Utf8,
    'centralOriginCodeDescription': pl.Utf8,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomStatus': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceCodeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'cutoffDate': pl.Utf8,
    'dSI': pl.Int64,
    'decisionDate': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'endDate': pl.Utf8,
    'externalReference': pl.Utf8,
    'followupDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'inventoryControl': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originCodeDescription': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYn': pl.Utf8,
    'relationship': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'status': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
}
```
```python
activity_contact_profile_details_schema = {
    'accountAddress4': pl.Utf8,
    'accountCountryCode': pl.Utf8,
    'accountCountryName': pl.Utf8,
    'accountPhone': pl.Utf8,
    'accountPostalCode': pl.Utf8,
    'accountState': pl.Utf8,
    'accountType': pl.Utf8,
    'actId': pl.Float64,
    'actResort': pl.Utf8,
    'addressId': pl.Float64,
    'attachmentYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'contactAddress1': pl.Utf8,
    'contactAddress2': pl.Utf8,
    'contactAddress3': pl.Utf8,
    'contactCity': pl.Utf8,
    'contactEmail': pl.Utf8,
    'contactID': pl.Float64,
    'contactName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'nameType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryContactYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'relationship': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_property_details_schema = {
    'property': pl.Utf8,
    'aRAccountNoFormat': pl.Utf8,
    'aRAccountNumberMandatoryYN': pl.Utf8,
    'aRAgent': pl.Utf8,
    'aRBalanceTrxCode': pl.Utf8,
    'aRCompany': pl.Utf8,
    'aRCreditTrxCode': pl.Utf8,
    'aRGroups': pl.Utf8,
    'aRIndividuals': pl.Utf8,
    'aRSettleCode': pl.Utf8,
    'aRTypewriter': pl.Utf8,
    'accessCode': pl.Utf8,
    'accessibleRooms': pl.Float64,
    'agingLevel1': pl.Float64,
    'agingLevel2': pl.Float64,
    'agingLevel3': pl.Float64,
    'agingLevel4': pl.Float64,
    'agingLevel5': pl.Float64,
    'airport': pl.Utf8,
    'airportDistance': pl.Utf8,
    'airportTime': pl.Utf8,
    'allowLoginYN': pl.Utf8,
    'allowancePeriodAdj': pl.Utf8,
    'awardsTimeout': pl.Float64,
    'ballroomArea': pl.Utf8,
    'ballroomSeats': pl.Float64,
    'baseLanguage': pl.Utf8,
    'block': pl.Utf8,
    'brandCode': pl.Utf8,
    'budgetMonth': pl.Float64,
    'businessDate': pl.Utf8,
    'businessID': pl.Utf8,
    'businessRegistrationCode': pl.Utf8,
    'cROCODE': pl.Utf8,
    'cashShiftDrop': pl.Utf8,
    'cateringCurrencyCode': pl.Utf8,
    'cateringCurrencyFormat': pl.Utf8,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'centralCreditLimit': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralCurrencyDescription': pl.Utf8,
    'centralDblRate2': pl.Float64,
    'centralDblRate1': pl.Float64,
    'centralPasserbyMarket': pl.Utf8,
    'centralPasserbySource': pl.Utf8,
    'centralPropertyType': pl.Utf8,
    'centralSglRate1': pl.Float64,
    'centralSglRate2': pl.Float64,
    'centralState': pl.Utf8,
    'centralStateDescription': pl.Utf8,
    'centralSuiRate1': pl.Float64,
    'centralSuiRate2': pl.Float64,
    'centralTplRate1': pl.Float64,
    'centralTplRate2': pl.Float64,
    'centralWarningAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'chainDescription': pl.Utf8,
    'chainMode': pl.Utf8,
    'checkExgPaidout': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'checkShiftDrop': pl.Utf8,
    'checkTrxcode': pl.Utf8,
    'checkInTime': pl.Utf8,
    'city': pl.Utf8,
    'cityDescription': pl.Utf8,
    'comAddress': pl.Utf8,
    'comMethod': pl.Utf8,
    'comNameXrefId': pl.Float64,
    'companyAddressType': pl.Utf8,
    'companyPhoneType': pl.Utf8,
    'configurationMode': pl.Utf8,
    'confirmRegcardPrinter': pl.Utf8,
    'connectingRooms': pl.Float64,
    'contacts': pl.Utf8,
    'copies': pl.Float64,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryMode': pl.Utf8,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyCodeSymbol': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencyFormat': pl.Utf8,
    'curtainColor': pl.Utf8,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'dateSeparator': pl.Utf8,
    'decimalPlaces': pl.Float64,
    'decimalSeparator': pl.Utf8,
    'decimals': pl.Float64,
    'defaultFolioStyle': pl.Float64,
    'defaultGuestAddress': pl.Utf8,
    'defaultMembershipType': pl.Utf8,
    'defaultPostingRoom': pl.Utf8,
    'defaultPropertyAddress': pl.Utf8,
    'defaultRateCode': pl.Utf8,
    'defaultRatecodePcr': pl.Utf8,
    'defaultRatecodeRack': pl.Utf8,
    'defaultRegistrationCard': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositLedgerTrxCode': pl.Utf8,
    'destinationId': pl.Utf8,
    'dfltPkgTranCode': pl.Utf8,
    'dfltTranCodeRateCode': pl.Utf8,
    'directions': pl.Utf8,
    'dirsales': pl.Utf8,
    'disableLoginYN': pl.Utf8,
    'doubleRooms': pl.Float64,
    'downloadRestYN': pl.Utf8,
    'dutyManagerPager': pl.Utf8,
    'email': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'executiveFloorNumber': pl.Utf8,
    'expHotelCode': pl.Utf8,
    'extExpFileLocation': pl.Utf8,
    'extPropertyCode': pl.Utf8,
    'externalSCYN': pl.Utf8,
    'familyRooms': pl.Float64,
    'faxNoFormat': pl.Utf8,
    'faxNumber': pl.Utf8,
    'fiscalEndDate': pl.Utf8,
    'fiscalPeriodType': pl.Utf8,
    'fiscalStartDate': pl.Utf8,
    'fiscalYearBeginMonth': pl.Float64,
    'fiscalYearBeginYear': pl.Float64,
    'flags': pl.Utf8,
    'flowCode': pl.Utf8,
    'fnsTier': pl.Utf8,
    'folioLanguage1': pl.Utf8,
    'folioLanguage2': pl.Utf8,
    'folioLanguage3': pl.Utf8,
    'folioLanguage4': pl.Utf8,
    'genmgr': pl.Utf8,
    'groupRoomWarning': pl.Float64,
    'guestLookupTimeout': pl.Float64,
    'guestRoomElevators': pl.Float64,
    'guestRoomFloors': pl.Float64,
    'hotelCode': pl.Utf8,
    'hotelFC': pl.Utf8,
    'hotelID': pl.Utf8,
    'hotelType': pl.Utf8,
    'iMGDirectionID': pl.Float64,
    'iMGHotelID': pl.Float64,
    'iMGMapID': pl.Float64,
    'inactiveDaysForGuestProfile': pl.Float64,
    'inactiveFlag': pl.Utf8,
    'individualAddressType': pl.Utf8,
    'individualPhoneType': pl.Utf8,
    'individualRoomWarning': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'intTaxIncludedYN': pl.Utf8,
    'inventoryYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepAvailability': pl.Float64,
    'latitude': pl.Float64,
    'leadsend': pl.Utf8,
    'legalOwner': pl.Utf8,
    'locationID': pl.Utf8,
    'longDateFormat': pl.Utf8,
    'longStayControl': pl.Float64,
    'longitude': pl.Float64,
    'maxAdultsInFamilyRoom': pl.Float64,
    'maxChildrenInFamilyRoom': pl.Float64,
    'maxOccupancy': pl.Float64,
    'maximumCreditDays': pl.Float64,
    'mbsSupportedYN': pl.Utf8,
    'meetRooms': pl.Float64,
    'meetSeats': pl.Float64,
    'meetSpace': pl.Float64,
    'meetingFC': pl.Utf8,
    'minDaysBet2ReminderLetter': pl.Float64,
    'nameIdLink': pl.Float64,
    'nightAuditCashierID': pl.Utf8,
    'nonSmokingRooms': pl.Float64,
    'noteDetails': pl.Utf8,
    'numberOfBeds': pl.Float64,
    'numberOfFloors': pl.Float64,
    'numberOfRooms': pl.Float64,
    'opusCurrencyCode': pl.Utf8,
    'organizationID': pl.Int64,
    'organizationInternalID': pl.Float64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'parentOrgCode': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'path': pl.Utf8,
    'paymentDate': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'phoneNumber': pl.Utf8,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'proinfoUrl': pl.Utf8,
    'propMapUrl': pl.Utf8,
    'propPicUrl': pl.Utf8,
    'propertyCode': pl.Utf8,
    'propertyName': pl.Utf8,
    'propertyType': pl.Utf8,
    'quotedCurrency': pl.Utf8,
    'rNAInsertdate': pl.Utf8,
    'rNAUpdatedate': pl.Utf8,
    'reconcileDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionDescription': pl.Utf8,
    'restaurant': pl.Float64,
    'rhythmSheets': pl.Float64,
    'rhythmTowels': pl.Float64,
    'roomAmenities': pl.Utf8,
    'sGLNum': pl.Utf8,
    'sGLRate1': pl.Float64,
    'sGLRate2': pl.Float64,
    'sUINum': pl.Utf8,
    'sUIRate1': pl.Float64,
    'sUIRate2': pl.Float64,
    'saveProfiles': pl.Float64,
    'scriptID': pl.Float64,
    'season1': pl.Utf8,
    'season2': pl.Utf8,
    'season3': pl.Utf8,
    'season4': pl.Utf8,
    'season5': pl.Utf8,
    'sendLeadAsBooking': pl.Utf8,
    'shopDescription': pl.Utf8,
    'shortDateFormat': pl.Utf8,
    'singleRooms': pl.Float64,
    'sourceCommission': pl.Utf8,
    'state': pl.Utf8,
    'stateDescription': pl.Utf8,
    'street': pl.Utf8,
    'suites': pl.Float64,
    'summCurrencyCode': pl.Utf8,
    'tACommission': pl.Utf8,
    'tPLNum': pl.Utf8,
    'tPLRate1': pl.Float64,
    'tPLRate2': pl.Float64,
    'telephoneNoFormat': pl.Utf8,
    'thousandSeparator': pl.Utf8,
    'timeFormat': pl.Utf8,
    'timeZone': pl.Utf8,
    'tollFree': pl.Utf8,
    'totalRooms': pl.Float64,
    'touristNumber': pl.Utf8,
    'translateMulticharYN': pl.Utf8,
    'turnawayCode': pl.Utf8,
    'twinRooms': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatID': pl.Utf8,
    'videoCheckoutPrinter': pl.Utf8,
    'videoCheckoutStart': pl.Utf8,
    'videoCheckoutStop': pl.Utf8,
    'wakeUpDelay': pl.Float64,
    'warningAmount': pl.Float64,
    'web': pl.Utf8,
    'weekendDays': pl.Utf8,
    'zeroInvPurDays': pl.Float64,
}
```