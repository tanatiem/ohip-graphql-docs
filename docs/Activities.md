# Activities
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| Field | Type | Description |
| --- | --- | --- |
| workOrdersDetails | [`ActivitiesWorkOrdersDetailsType`](#activitiesworkordersdetailstype) | Work Orders Details |
| activityProfileDetails | [`ActivitiesActivityProfileDetailsType`](#activitiesactivityprofiledetailstype) | Activity Profile Details |
| activityBlockDetails | [`ActivitiesActivityBlockDetailsType`](#activitiesactivityblockdetailstype) | Activity Block |
| activityContactProfileDetails | [`ActivitiesActivityContactProfileDetailsType`](#activitiesactivitycontactprofiledetailstype) | Activity Contact Profile Details |
| propertyPropertyDetails | [`ActivitiesPropertyPropertyDetailsType`](#activitiespropertypropertydetailstype) | Resort Details |
| activitiesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ActivitiesWorkOrdersDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountAll | `String` | Account All |
| activityAmount | `Float` | Total amount for the specific Activity. |
| activityClass | `String` | Activity Class |
| activityCompleted | `String` | Activity Completed |
| activityCompletedBy | `String` | Activity Completed By |
| activityCompletionDate | `Float` | Activity Completion Date |
| activityCreatedBy | `String` | Activity Created By |
| activityCreatedOn | `DateTime` | Activity Created On |
| activityEndDate | `DateTime` | Activity End Date |
| activityID | `Float` | Activity ID |
| activityName | `String` | Description of the Problem reported |
| activityNotes | `String` | Activity Notes |
| activityOwnerCode | `DateTime` | Activity Owner Code |
| activityPriority | `String` | Activity Priority |
| activityResult | `String` | Activity Result |
| activityStartDate | `DateTime` | Activity Start Date |
| activityTraceCode | `String` | Activity Trace Code |
| activityType | `String` | Activity Type |
| activityTypeDescription | `String` | Activity Type Description |
| activityUpdatedBy | `String` | Activity Updated By |
| activityUpdatedOn | `DateTime` | Activity Updated On |
| activityUserNameID | `String` | Activity User Name ID |
| assignedBy | `Float` | User who assigned the task. |
| assignedOnDate | `DateTime` | Date on which this work order was assigned to someone else |
| attachmentLocation | `String` | Attachment Location |
| attachmentOwner | `String` | Owner who created this attachment. [ACCOUNT CONTACT ACTIVITY or BOOKING] |
| attendees | `Float` | Attendees |
| author | `Float` | Author |
| blockAll | `String` | Block All |
| cActivityAmount | `Float` | Central Activity Amount |
| cDepositAmount | `Float` | Central Deposit Amount |
| cEstCateringRevenue | `Float` | Central Est Cat Revenue |
| cEstOtherRevenue | `Float` | Central Est Other Revenue |
| cEstRoomRevenue | `Float` | Central Est Rm Revenue |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cTotalLaborCost | `Float` | Central Total Labor Cost |
| cTotalPartsCost | `Float` | Central Total Parts Cost |
| campaignStatusCode | `String` | Stores the status codes for Campaign Management |
| categoryCode | `String` | Category Code |
| centralActivityType | `String` | Central Activity Type |
| centralActivityTypeDescription | `String` | Central Activity Type Description |
| chainCode | `String` | Chain Code |
| completedBy | `Float` | Completed By |
| contactAll | `String` | Contact All |
| createdBy | `Float` | Created By |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| databaseId | `String` | Database ID |
| deletedFlag | `String` | Deleted Flag |
| dependingOnWoNumber | `Float` | This defines the oprder of execution between two sub work orders as one of them may be dependent on the other. |
| depositAmount | `Float` | Deposit Amount |
| depositOwner | `String` | Owner of the Deposit. It can be Opera (O) or Cencept (C). |
| deptOfAction | `String` | Dept to which the employee who created the work order belongs |
| downloadDate | `DateTime` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| dueDate | `DateTime` | Due Date |
| endTime | `String` | End Time |
| estCatRevenue | `Float` | Estimated revenue. |
| estOtherRevenue | `Float` | Estimated others revenue. |
| estRoomNights | `Float` | Estimated room nights. |
| estRoomRevenue | `Float` | Estimated room revenue. |
| estTimeToComplete | `Float` | Time estimated to complete the work order |
| estUotCode | `String` | Est Uot Code |
| externalSystem | `String` | External System |
| externalSystemId | `String` | External System ID. |
| foRoomStatus | `String` | Room status at the tome of creation of work order if it happens to be in a room |
| fullName | `String` | Full Name |
| generatedByCampaign | `String` | Indicates if a Campain generated this activity. |
| generatedByFreqId | `Float` | The frequency ID which generated this activity. |
| globalYn | `String` | Global Y/N |
| guestOriginatedYn | `String` | Whether the work order is guest originated or not |
| guestRoomYn | `String` | Whether this location is a a guest room or not |
| guestType | `String` | Guest Type |
| highPriorityYn | `String` | Whether the work order is having high priority or not. |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalYn | `String` | Internal Y/N |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationCode | `String` | Location Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSub | `String` | Decides whether a particular workorder is a master or sub or none. |
| minutesBeforeAlert | `Float` | Number of minutes before the activity start time when the alert will be raised. (Default value) |
| nameID | `Float` | Name ID |
| notifiedYn | `String` | Has the user been notified about this activity ? |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origWoNumber | `Float` | Stores the original WORK_NUMBER prior to a migration. |
| ownerEmail | `String` | Owner Email |
| ownerPhone | `String` | Phone no. |
| ownerTitle | `String` | Owner Title |
| parentWoNumber | `Float` | Wo_number to which current work order is a sub work ordergenerated work_order number |
| plantItemCode | `String` | Plant Item Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priorityChangedYn | `String` | Whether the priority was manually changed or not |
| privateYn | `String` | Private Y/N |
| property | `String` | Code to uniquely identify the Property |
| proposalSentDate | `DateTime` | Proposal Sent Date |
| proposalViewToken | `String` | Proposal View Token |
| reasonCode | `String` | Reason Code |
| releasedBy | `Float` | Emp number of the person who has released this workorder |
| releasedDate | `DateTime` | Date on which a work orderwas released |
| requestTemplateId | `Float` | Stores the request template ID for Campaign Management. |
| requestTypeId | `String` | Request type that need to be generated. |
| requestTypeTemplatesId | `Float` | Stores the Campaign Type Template ID used for a campaign. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| sendMethod | `String` | Default method for sending a Request Type. |
| showOn | `DateTime` | Scheduled workorder .reminder to display on date |
| startTime | `String` | Start Time |
| statusCode | `String` | Status Code |
| surveyId | `Float` | Linked Survey ID |
| takenBy | `Float` | Empnumber of the person who has accepted this workorder |
| takenDate | `DateTime` | Date on which an employee has accepted this workorder |
| taskCode | `Float` | Task Code |
| taskitemNumber | `Float` | Taskitem Number |
| timezoneConvertedYn | `String` | Indicated if the activity times are converted to database time zone. |
| totalLaborCost | `Float` | Calculated Labor cost spent for this workorder |
| totalPartsCost | `Float` | Calculate total parts cost spent for this workorder |
| typeCode | `String` | Type Code |
| updateUser | `Float` | Update User |
| uploadDate | `DateTime` | Upload Date |
| userExt | `String` | Extension of the user |

[⬆ Back to Query](#query)

---

### ActivitiesActivityProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountAddress4 | `String` | Account Address 4 |
| accountCountryCode | `String` | Account Country Code |
| accountCountryName | `String` | Account Country Name |
| accountPhone | `String` | Phone no. |
| accountPostalCode | `String` | Account Postal Code |
| accountState | `String` | Account State |
| accountType | `String` | Account Type |
| actId | `Float` | Activity ID |
| actResort | `String` | Act Property |
| addressId | `Float` | Address ID |
| attachmentYn | `String` | Identifies a linked attachment. |
| chainCode | `String` | Chain Code |
| contactAddress1 | `String` | Contact Address 1 |
| contactAddress2 | `String` | Contact Address 2 |
| contactAddress3 | `String` | Contact Address 3 |
| contactCity | `String` | Contact City |
| contactEmail | `String` | Contact Email |
| contactID | `Float` | Contact ID |
| contactName | `String` | Contact Name |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailId | `Float` | Email ID |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkId | `Float` | Link ID |
| linkResort | `String` | Stores the property of the linked entity. |
| linkType | `String` | Link Type |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryContactYN | `String` | Primary Contact YN |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| relationship | `String` | Relationship |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ActivitiesActivityBlockDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actId | `Float` | Activity ID |
| actResort | `String` | Act Property |
| addressId | `Float` | Address ID |
| ahUpdateUser | `Float` | Ah Update User |
| allotmentOrigin | `String` | Allotment Origin |
| alternateBlockName | `String` | Multi Byte Description Field |
| attachmentYn | `String` | Identifies a linked attachment. |
| blockCode | `String` | Block Code |
| blockDeletedDate | `Date` | Block Deleted Date |
| blockID | `Float` | Block ID |
| blockName | `String` | Block Name |
| blockOwnerCode | `String` | Block Owner Code |
| blockOwnerFullName | `String` | Block Owner Full Name |
| blockStatus | `String` | Block Status |
| blockTypeCode | `String` | Block Type Code |
| blockTypeCodeDescription | `String` | Block Type Code Description |
| cateringOnlyYN | `String` | Catering only Revenue. |
| cateringStatus | `String` | Catering Status |
| centralBlockTypeCode | `String` | Central Block Type Code |
| centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| centralCateringStatus | `String` | Central Catering Status |
| centralMarketCode | `String` | Central Market  Code |
| centralMarketDescription | `String` | Central Market Description |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginCodeDescription | `String` | Central Origin Code Description |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomStatus | `String` | Central Room Status |
| centralSourceCode | `String` | Central Source Code |
| centralSourceCodeDescription | `String` | Central Source Code Description |
| chainCode | `String` | Chain Code |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `DateTime` | Created Date |
| cutoffDate | `Date` | Cutoff Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| decisionDate | `Date` | Decision Date |
| deletedFlag | `String` | Deleted Flag |
| emailId | `Float` | Email ID |
| endDate | `Date` | End Date |
| externalReference | `String` | External Reference |
| followupDate | `Date` | Followup Date |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| inventoryControl | `String` | Inventory Control |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkId | `Float` | Link ID |
| linkResort | `String` | Stores the property of the linked entity. |
| linkType | `String` | Link Type |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originCodeDescription | `String` | Origin Code Description |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYn | `String` | Primary Y/N |
| relationship | `String` | Relationship |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | The Description of the Guarantee code. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| shoulderEnd | `Date` | Shoulder End |
| shoulderStart | `Date` | Shoulder Start |
| sourceCode | `String` | Source Code |
| sourceCodeDescription | `String` | Source Code Description |
| startDate | `Date` | Start Date |
| status | `String` | Status |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `DateTime` | Updated Date |

[⬆ Back to Query](#query)

---

### ActivitiesActivityContactProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountAddress4 | `String` | Account Address 4 |
| accountCountryCode | `String` | Account Country Code |
| accountCountryName | `String` | Account Country Name |
| accountPhone | `String` | Phone no. |
| accountPostalCode | `String` | Account Postal Code |
| accountState | `String` | Account State |
| accountType | `String` | Account Type |
| actId | `Float` | Activity ID |
| actResort | `String` | Act Property |
| addressId | `Float` | Address ID |
| attachmentYn | `String` | Identifies a linked attachment. |
| chainCode | `String` | Chain Code |
| contactAddress1 | `String` | Contact Address 1 |
| contactAddress2 | `String` | Contact Address 2 |
| contactAddress3 | `String` | Contact Address 3 |
| contactCity | `String` | Contact City |
| contactEmail | `String` | Contact Email |
| contactID | `Float` | Contact ID |
| contactName | `String` | Contact Name |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailId | `Float` | Email ID |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkId | `Float` | Link ID |
| linkResort | `String` | Stores the property of the linked entity. |
| linkType | `String` | Link Type |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryContactYN | `String` | Primary Contact YN |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| relationship | `String` | Relationship |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ActivitiesPropertyPropertyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| property | `String` | The property that the record belongs to |
| aRAccountNoFormat | `String` | Number format of AR account no. |
| aRAccountNumberMandatoryYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| aRAgent | `String` | Default Account Type for an Agent for the Property |
| aRBalanceTrxCode | `String` | Internal |
| aRCompany | `String` | Default Account Type for a Company for the Property |
| aRCreditTrxCode | `String` | Internal |
| aRGroups | `String` | Default Account Type for a Group for the Property |
| aRIndividuals | `String` | Default Account Type for Individual for the Property |
| aRSettleCode | `String` | Internal |
| aRTypewriter | `String` | Internal |
| accessCode | `String` | Access Code |
| accessibleRooms | `Float` | Number of handicapped rooms. |
| agingLevel1 | `Float` | Aging bucket 1 |
| agingLevel2 | `Float` | Aging bucket 2 |
| agingLevel3 | `Float` | Aging bucket 3 |
| agingLevel4 | `Float` | Aging bucket 4 |
| agingLevel5 | `Float` | Aging bucket 3 |
| airport | `String` | The Airport Code for the airport near the property |
| airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| allowLoginYN | `String` | Allow loggin in to this resort(Y/N) |
| allowancePeriodAdj | `String` | Period for the allowance |
| awardsTimeout | `Float` | Internal |
| ballroomArea | `String` | Ball Room Area |
| ballroomSeats | `Float` | No of Ballroom Seats |
| baseLanguage | `String` | The base language of the Hotel |
| block | `String` | It contains the reservation type to be used when making group block |
| brandCode | `String` | Brand Code of the property. |
| budgetMonth | `Float` | Financial Year of the Property |
| businessDate | `Date` | The date this resort becomes valid for use by the system |
| businessID | `String` | Value for the parameter. |
| businessRegistrationCode | `String` | Value for the parameter. |
| cROCODE | `String` | Code for the CRO |
| cashShiftDrop | `String` | Internal |
| cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| cateringCurrencyFormat | `String` | Catering currency format. |
| centralXchangeDate | `Date` | Central  Exchange Date |
| centralXchangeRate | `Float` | Central  Exchange Rate |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralCurrencyCode | `String` | Central Currency Code |
| centralCurrencyDescription | `String` | Central Currency Description |
| centralDblRate2 | `Float` | Central Double Rate2 |
| centralDblRate1 | `Float` | Central Double Rate1 |
| centralPasserbyMarket | `String` | Central Passerby Market |
| centralPasserbySource | `String` | Central Passerby Source |
| centralPropertyType | `String` | Central Property Type |
| centralSglRate1 | `Float` | Central Sgl Rate1 |
| centralSglRate2 | `Float` | Central Sgl Rate 2 |
| centralState | `String` | Central State |
| centralStateDescription | `String` | Central State Description |
| centralSuiRate1 | `Float` | Central Sui Rate1 |
| centralSuiRate2 | `Float` | Central Sui Rate 2 |
| centralTplRate1 | `Float` | Central Tpl Rate1 |
| centralTplRate2 | `Float` | Central Tpl Rate 2 |
| centralWarningAmount | `Float` | Central Warning Amount |
| chainCode | `String` | Chain Code for the chain to which the property belongs |
| chainDescription | `String` | The description of this chain. |
| chainMode | `String` | Chain Mode |
| checkExgPaidout | `String` | Internal |
| checkOutTime | `DateTime` | The Hotel official check out time |
| checkShiftDrop | `String` | Internal |
| checkTrxcode | `String` | Internal |
| checkInTime | `DateTime` | The Hotel official check intime |
| city | `String` | The physical city in which this property resides. |
| cityDescription | `String` | City Description |
| comAddress | `String` | Internal |
| comMethod | `String` | Internal |
| comNameXrefId | `Float` | Internal |
| companyAddressType | `String` | Internal |
| companyPhoneType | `String` | Internal |
| configurationMode | `String` | Internal |
| confirmRegcardPrinter | `String` | Internal |
| connectingRooms | `Float` | Number of connecting rooms. |
| contacts | `String` | The unique name of application user |
| copies | `Float` | Number of copies to be printed |
| country | `String` | Country name. |
| countryCode | `String` | The name of the country in which this property resides. |
| countryMode | `String` | Value for the parameter. |
| creditLimit | `Float` | The default credit limit for guests. |
| currencyCode | `String` | Currency Code. |
| currencyCodeSymbol | `String` | Currency Symbol like $ or EURO symbol |
| currencyDescription | `String` | A description of this currency. |
| currencyFormat | `String` | Format for the local currency. |
| curtainColor | `String` | Color that of the background |
| dSI | `Float` | DSI |
| dateForAging | `String` | Date the aging should begin |
| dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| decimalPlaces | `Float` | Number of places for the default currency |
| decimalSeparator | `String` | Type of decimal separator |
| decimals | `Float` | Number of decimals to designate currency |
| defaultFolioStyle | `Float` | Folio style to be used for all guests |
| defaultGuestAddress | `String` | Default guest address format. |
| defaultMembershipType | `String` | Future use |
| defaultPostingRoom | `String` | Future use |
| defaultPropertyAddress | `String` | Default property address format. |
| defaultRateCode | `String` | Future use |
| defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| defaultRegistrationCard | `String` | Default registration card for the property. |
| defaultReservationType | `String` | The Default reservation type for this property |
| deletedFlag | `String` | Deleted Flag |
| depositLedgerTrxCode | `String` | Future use |
| destinationId | `String` | Destination ID |
| dfltPkgTranCode | `String` | Future use |
| dfltTranCodeRateCode | `String` | Future use |
| directions | `String` | Internal |
| dirsales | `String` | Future use |
| disableLoginYN | `String` | LOGIN into the application is disabled. |
| doubleRooms | `Float` | Number of double rooms. |
| downloadRestYN | `String` | Download Rest YN |
| dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| email | `String` | Email id for the property. |
| endDate | `Date` | Future use. |
| exchangePostingType | `String` | Default Exchange posting status for the property |
| executiveFloorNumber | `String` | Floor number of executive floor. |
| expHotelCode | `String` | Hotel code used for third party exports |
| extExpFileLocation | `String` | Future use |
| extPropertyCode | `String` | Future use |
| externalSCYN | `String` | Indicates that the property uses an external SC system. |
| familyRooms | `Float` | Number of family rooms. |
| faxNoFormat | `String` | Fax number formats. |
| faxNumber | `String` | The fax phone number |
| fiscalEndDate | `Date` | Future use |
| fiscalPeriodType | `String` | Future use |
| fiscalStartDate | `Date` | Future use |
| fiscalYearBeginMonth | `Float` | Fiscal Year Begin Month |
| fiscalYearBeginYear | `Float` | Fiscal Year Begin Year |
| flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| flowCode | `String` | Future use |
| fnsTier | `String` | Property Free Nights Stay Tier. |
| folioLanguage1 | `String` | Other languages |
| folioLanguage2 | `String` | Other languages |
| folioLanguage3 | `String` | Other languages |
| folioLanguage4 | `String` | Other languages |
| genmgr | `String` | Future use |
| groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| guestLookupTimeout | `Float` | Future use |
| guestRoomElevators | `Float` | Number of guest elevators. |
| guestRoomFloors | `Float` | Total of guest rooms floors. |
| hotelCode | `String` | Future use |
| hotelFC | `String` | Future use |
| hotelID | `String` | Hotel id |
| hotelType | `String` | Future use |
| iMGDirectionID | `Float` | Future use |
| iMGHotelID | `Float` | Future use |
| iMGMapID | `Float` | Future use |
| inactiveDaysForGuestProfile | `Float` | Future use |
| inactiveFlag | `String` | Inactive Flag |
| individualAddressType | `String` | Future use |
| individualPhoneType | `String` | Future use |
| individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `Float` | The user that created the record |
| intTaxIncludedYN | `String` | Int Tax Included YN |
| inventoryYN | `String` | Future use |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| latitude | `Float` | Latitude of the property in decimal |
| leadsend | `String` | Future use |
| legalOwner | `String` | The owner who owns this property |
| locationID | `String` | The property that the record belongs to |
| longDateFormat | `String` | Long date format for the property. |
| longStayControl | `Float` | The default length of stay |
| longitude | `Float` | Longitude of the property in decimal |
| maxAdultsInFamilyRoom | `Float` | Maximum adults in family rooms. |
| maxChildrenInFamilyRoom | `Float` | Maximum children in family rooms. |
| maxOccupancy | `Float` | Future use |
| maximumCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| mbsSupportedYN | `String` | Indicates whether the property supports MBS. Used in some file exports. |
| meetRooms | `Float` | Future use |
| meetSeats | `Float` | Future use |
| meetSpace | `Float` | Future use |
| meetingFC | `String` | Future use |
| minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| nameIdLink | `Float` | Internal |
| nightAuditCashierID | `String` | Future use |
| nonSmokingRooms | `Float` | Number of non smoking rooms. |
| noteDetails | `String` | Notes for the property |
| numberOfBeds | `Float` | Total number of beds in this property |
| numberOfFloors | `Float` | Total number of floors in this property |
| numberOfRooms | `Float` | Number of Rooms |
| opusCurrencyCode | `String` | Future use |
| organizationID | `Float` | Organization ID |
| organizationInternalID | `Float` | Organization Internal ID |
| ownership | `String` | Future use |
| packageLoss | `String` | Package Loss code for a particular package |
| packageProfit | `String` | Package Profit code for a particular Package |
| parentOrgCode | `String` | Parent Org Code |
| passerbyMarket | `String` | Market code |
| passerbySource | `String` | Source code |
| path | `String` | Path |
| paymentDate | `DateTime` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| perReservationRoomLimit | `Float` | Future use |
| phoneNumber | `String` | The direct dial phone number of this property |
| postalCode | `String` | The postal code of this property. |
| primaryKeyID | `Float` | Primary Key ID |
| proinfoUrl | `String` | URL where property information is located. |
| propMapUrl | `String` | Property MAP URL. |
| propPicUrl | `String` | Property picture URL. |
| propertyCode | `String` | The property that the record belongs to |
| propertyName | `String` | The name of this property. |
| propertyType | `String` | Type of resort. |
| quotedCurrency | `String` | Future use |
| rNAInsertdate | `DateTime` | RNA Insert Date |
| rNAUpdatedate | `DateTime` | RNA Update Date |
| reconcileDate | `DateTime` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| regionCode | `String` | Future use |
| regionDescription | `String` | Description of the Region. |
| restaurant | `Float` | Future use |
| rhythmSheets | `Float` | Total number of Sheets |
| rhythmTowels | `Float` | Total number of Towels |
| roomAmenities | `String` | Room amenity. |
| sGLNum | `String` | Future use |
| sGLRate1 | `Float` | Future use |
| sGLRate2 | `Float` | Future use |
| sUINum | `String` | Future use |
| sUIRate1 | `Float` | Future use |
| sUIRate2 | `Float` | Future use |
| saveProfiles | `Float` | To store number of days before deleting the gest profile |
| scriptID | `Float` | Future use |
| season1 | `String` | Future use |
| season2 | `String` | Future use |
| season3 | `String` | Future use |
| season4 | `String` | Future use |
| season5 | `String` | Future use |
| sendLeadAsBooking | `String` | Indicates that the property accepts leads as bookings. |
| shopDescription | `String` | Shop description. |
| shortDateFormat | `String` | Short date format for the property. |
| singleRooms | `Float` | Number of single rooms. |
| sourceCommission | `String` | For default commission percentage |
| state | `String` | The state in which this property is located. |
| stateDescription | `String` | Description of the state. |
| street | `String` | The street of the property. |
| suites | `Float` | Number of suites. |
| summCurrencyCode | `String` | Internal |
| tACommission | `String` | For default commission percentage |
| tPLNum | `String` | Future use |
| tPLRate1 | `Float` | Future use |
| tPLRate2 | `Float` | Future use |
| telephoneNoFormat | `String` | Formats for telephone number |
| thousandSeparator | `String` | Separator for monetory values |
| timeFormat | `String` | Default time format for the property. |
| timeZone | `String` | Time zone region selected by the employee. |
| tollFree | `String` | Toll free telephone number. |
| totalRooms | `Float` | Future use |
| touristNumber | `String` | Tourist Number |
| translateMulticharYN | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| turnawayCode | `String` | Turnaway code for the property. |
| twinRooms | `Float` | Number of twin rooms. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |
| vatID | `String` | VAT ID of this property. |
| videoCheckoutPrinter | `String` | Future use |
| videoCheckoutStart | `DateTime` | Video check out start time. |
| videoCheckoutStop | `DateTime` | Video check out end time. |
| wakeUpDelay | `Float` | Future use |
| warningAmount | `Float` | Amount at which warning is raised. |
| web | `String` | Webaddress of the property |
| weekendDays | `String` | Weekend days for the property. |
| zeroInvPurDays | `Float` | Internal |

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
    'origWoNumber': pl.Float64,
    'ownerEmail': pl.Utf8,
    'ownerPhone': pl.Utf8,
    'ownerTitle': pl.Utf8,
    'parentWoNumber': pl.Float64,
    'plantItemCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'nameType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryContactYN': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'relationship': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
    'decisionDate': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'endDate': pl.Utf8,
    'externalReference': pl.Utf8,
    'followupDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'inventoryControl': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'organizationID': pl.Float64,
    'originCode': pl.Utf8,
    'originCodeDescription': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'emailId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkId': pl.Float64,
    'linkResort': pl.Utf8,
    'linkType': pl.Utf8,
    'nameType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryContactYN': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'relationship': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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