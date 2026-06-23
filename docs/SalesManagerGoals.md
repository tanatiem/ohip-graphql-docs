# SalesManagerGoals
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `salesManagerGoals`
> The Sales Manager Goals subject Area enable the end users to retrieve information / create reports to compare the goals set for the Sales Managers against completed activities and against statistical revenue data associated to profiles.
  
**Return:** [`[SalesManagerGoalsType]`](#salesmanagergoalstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`SalesManagerGoalsQueryArgumentsType!`](#salesmanagergoalsqueryargumentstype) |  |

## Object Types

### SalesManagerGoalsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | salesManagerDetails | [`SalesManagerGoalsSalesManagerDetailsType`](#salesmanagergoalssalesmanagerdetailstype) | Sales Manager Details |
| 2 | employeeGoalDetails | [`SalesManagerGoalsEmployeeGoalDetailsType`](#salesmanagergoalsemployeegoaldetailstype) | Employee Goal Details |
| 3 | workOrdersDetails | [`SalesManagerGoalsWorkOrdersDetailsType`](#salesmanagergoalsworkordersdetailstype) | Work Orders Details |
| 4 | ownerAccountDailyStatisticsDetails | [`SalesManagerGoalsOwnerAccountDailyStatisticsDetailsType`](#salesmanagergoalsowneraccountdailystatisticsdetailstype) | Owner Account Daily Statistics |
| 5 | salesManagerGoalsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsSalesManagerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | firstName | `String` | First Name |
| 4 | fullName | `String` | Full Name |
| 5 | jRNUpdateDate | `Date` | JRN Update Date |
| 6 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 7 | lastName | `String` | Last Name |
| 8 | middleName | `String` | Middle Name |
| 9 | nameId | `Float` | Name ID |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | ownerCode | `String` | Owner Code |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsEmployeeGoalDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activityNumber | `Float` | Number of Activities |
| 2 | activityType | `String` | Activity Type |
| 3 | activitytypeid | `String` | Activitytypeid |
| 4 | appInsertUser | `String` | App Insert User |
| 5 | appUpdateUser | `String` | App Update User |
| 6 | arrivalEndDate | `Date` | Arrival Period End Date |
| 7 | arrivalGoalYN | `String` | Arrival Goal if Y |
| 8 | arrivalStartDate | `Date` | Arrival Period Start |
| 9 | arrivalgoalflag | `String` | Arrivalgoalflag |
| 10 | auSrepCode | `String` | Au Srep Code |
| 11 | budgetType | `String` | Budget Type |
| 12 | cCateringAvgCheck | `Float` | Central Catering Avg Check |
| 13 | cCateringFBRevenue | `Float` | Central Catering Fb Revenue |
| 14 | cCateringOtherRevenue | `Float` | Central Catering Other Revenue |
| 15 | cExchangeDate | `Date` | Central Xchange Date |
| 16 | cExchangeRate | `Float` | Central Xchange Rate |
| 17 | cRoomAvgRate | `Float` | Central Room Avg Rate |
| 18 | cRoomRevenue | `Float` | Central Room Revenue |
| 19 | cateringAverageCheck | `Float` | Average Guestcheck per period |
| 20 | cateringCovers | `Float` | Catering Covers per period |
| 21 | cateringFBRevenue | `Float` | Food/Beverage Revenue per period |
| 22 | cateringOtherRevenue | `Float` | Other Revenue per period |
| 23 | centralActivityType | `String` | Central Activity Type |
| 24 | centralMarketCode | `String` | Central Market Code |
| 25 | chainCode | `String` | Chain Code |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | deletedFlag | `String` | Deleted Flag |
| 28 | employeegoalid | `Float` | Employeegoalid |
| 29 | employeeid | `Float` | Employeeid |
| 30 | firstName | `String` | First Name |
| 31 | fullName | `String` | Full Name |
| 32 | inactiveDate | `Date` | Inactive Date |
| 33 | inactiveflag | `String` | Inactive Flag |
| 34 | insertDate | `DateTime` | Insert Date |
| 35 | insertUser | `Float` | Insert User |
| 36 | internalDeletedflag | `String` | Deleted Flag |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | laptopChange | `Float` | Laptop Change |
| 40 | lastName | `String` | Last Name |
| 41 | locationID | `String` | Internal ID to uniquely identify the Property |
| 42 | marketCode | `String` | Market Code |
| 43 | marketid | `String` | Marketid |
| 44 | middleName | `String` | Middle Name |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | periodCode | `String` | Period Code |
| 47 | periodType | `String` | Period Type |
| 48 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 49 | productionEndDate | `Date` | Production Period End Date |
| 50 | productionStartDate | `Date` | Production Period Start |
| 51 | property | `String` | Code to uniquely identify the Property |
| 52 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 53 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 54 | roomAvgRate | `Float` | Room Avg Rate |
| 55 | roomNights | `Float` | Room Nights |
| 56 | roomRevenue | `Float` | Room Revenue |
| 57 | salesGoalID | `Float` | Primary Key |
| 58 | srepCode | `String` | Srep Code |
| 59 | type | `String` | Goal Types |
| 60 | updateDate | `DateTime` | Update Date |
| 61 | updateUser | `Float` | Update User |
| 62 | userID | `Float` | User ID |
| 63 | yearId | `Float` | Year ID |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsWorkOrdersDetailsType

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

### SalesManagerGoalsOwnerAccountDailyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountOwner | `String` | Account Owner |
| 2 | accountOwnerCode | `String` | Account Owner Code |
| 3 | accountOwnerEmail | `String` | Account Owner Email |
| 4 | accountOwnerPhone | `String` | Phone no. |
| 5 | accountOwnerTitle | `String` | Account Owner Title |
| 6 | accountSrepCode | `String` | Account Srep Code |
| 7 | adr | `Float` | Average Daily Rate |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| 11 | cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| 12 | cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| 13 | cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| 14 | cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| 15 | cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| 16 | cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| 17 | cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| 18 | cTotalFBRevenue | `Float` | Central Total Fb Revenue |
| 19 | cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| 20 | cTotalOtherRevenue | `Float` | Central Total Other Revenue |
| 21 | cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| 22 | cTotalRoomRevenue | `Float` | Central Total Room Revenue |
| 23 | cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| 24 | cTotalTotalRevenue | `Float` | Central Total Total Revenue |
| 25 | cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| 26 | centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| 27 | centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| 28 | centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| 29 | centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| 30 | centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| 31 | centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| 32 | centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| 33 | centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| 34 | chainCode | `String` | Chain Code |
| 35 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 36 | deletedFlag | `String` | Deleted Flag |
| 37 | description | `String` | Description |
| 38 | grpAverageDailyRate | `Float` | Group Adr |
| 39 | grpFBRevenue | `Float` | Group F&B Revenue. |
| 40 | grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| 41 | grpNumberCancels | `Float` | Group Number of Cancellations. |
| 42 | grpNumberNights | `Float` | Group Number of Nights. |
| 43 | grpNumberNumberShows | `Float` | Group Number of No Shows. |
| 44 | grpNumberStays | `Float` | Group Number of Stays. |
| 45 | grpOtherRevenue | `Float` | Group Other Revenue. |
| 46 | grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| 47 | grpRoomRevenue | `Float` | Group Room Revenue. |
| 48 | grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| 49 | grpTotalRevenue | `Float` | Group Total Revenue. |
| 50 | grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| 51 | inactiveDate | `DateTime` | Inactive Date |
| 52 | inactiveFlag | `String` | Inactive Flag |
| 53 | individualCancels | `Float` | Individual Cancels |
| 54 | individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| 55 | individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| 56 | individualNoShows | `Float` | Individual Number Shows |
| 57 | individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| 58 | individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| 59 | individualRoomNights | `Float` | Individual Room Nights |
| 60 | individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| 61 | individualStays | `Float` | Individual Stays |
| 62 | individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| 63 | individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
| 64 | insertDate | `DateTime` | Insert Date |
| 65 | insertUser | `Float` | Insert User |
| 66 | internalOrganizationId | `Float` | Organization ID |
| 67 | jRNUpdateDate | `Date` | JRN Update Date |
| 68 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 69 | laptopChange | `Float` | Laptop Change |
| 70 | localCurrency | `String` | Local Currency Code. |
| 71 | locationId | `String` | Location ID |
| 72 | nameId | `Float` | Name ID |
| 73 | nameType | `String` | Name Type |
| 74 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 75 | ownerProfileId | `Float` | Owner Profile ID |
| 76 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 77 | primaryYN | `String` | Primary YN |
| 78 | profileOwnerId | `Float` | Profile Owner ID |
| 79 | property | `String` | Indicates if the value set for the specific property. |
| 80 | relationship | `String` | Relationship |
| 81 | relationshipid | `String` | Relationshipid |
| 82 | resort | `String` | Property |
| 83 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 84 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 85 | roomRevenueTax | `Float` | Room Revenue Tax |
| 86 | stayDate | `Date` | Stay Date |
| 87 | stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| 88 | stayYear | `Float` | Year of Summary. |
| 89 | toType | `String` | To Type |
| 90 | totalAdr | `Float` | Total Average Daily Rate |
| 91 | totalFbRevenue | `Float` | Total FB Revenue |
| 92 | totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| 93 | totalNumberCancels | `Float` | Total Number Cancels |
| 94 | totalNumberNights | `Float` | Total Number Nights |
| 95 | totalNumberNoShows | `Float` | Total Number Number Shows |
| 96 | totalNumberStays | `Float` | Total Number Stays |
| 97 | totalOtherRevenue | `Float` | Total Other Revenue |
| 98 | totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| 99 | totalRoomRevenue | `Float` | Total Room Revenue |
| 100 | totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| 101 | totalTotalRevenue | `Float` | Total Total Revenue |
| 102 | totalTotalRevenueTax | `Float` | Total Total Revenue Tax |
| 103 | updateDate | `DateTime` | Update Date |
| 104 | updateUser | `Float` | Update User |
| 105 | userId | `Float` | User ID |

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

### SalesManagerGoalsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| salesmanagerDetailsChainCode | `StringInput` | Chain Code |
| salesmanagerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| salesmanagerDetailsFirst | `StringInput` | First Name |
| salesmanagerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| salesmanagerDetailsLast | `StringInput` | Last Name |
| salesmanagerDetailsNameId | `FloatInput` | Name ID |
| salesmanagerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| salesmanagerDetailsSrepCode | `StringInput!` | Owner Code<br>`@mandatoryInput` |
| employeegoalDetailsActType | `StringInput` | Activity Type |
| employeegoalDetailsActivitytypeid | `StringInput` | Activitytypeid |
| employeegoalDetailsBudgetType | `StringInput` | Budget Type |
| employeegoalDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| employeegoalDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| employeegoalDetailsEmployeegoalid | `FloatInput` | Employeegoalid |
| employeegoalDetailsEmployeeid | `FloatInput` | Employeeid |
| employeegoalDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| employeegoalDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| employeegoalDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| employeegoalDetailsPeriodCode | `StringInput` | Period Code |
| employeegoalDetailsPeriodType | `StringInput` | Period Type |
| employeegoalDetailsResort | `StringInput` | Code to uniquely identify the Property |
| employeegoalDetailsGoalId | `FloatInput` | Primary Key |
| employeegoalDetailsGoalType | `StringInput` | Goal Types |
| employeegoalDetailsNameId | `FloatInput` | User ID |
| employeegoalDetailsYearId | `FloatInput` | Year ID |
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
| workordersDetailsResort | `StringInput` | Code to uniquely identify the Property |
| workordersDetailsReasonCode | `StringInput` | Reason Code |
| workordersDetailsRequestTypeId | `StringInput` | Request type that need to be generated. |
| workordersDetailsRequestTypeTemplatesId | `FloatInput` | Stores the Campaign Type Template ID used for a campaign. |
| workordersDetailsStatusCode | `StringInput` | Status Code |
| workordersDetailsSurveyId | `FloatInput` | Linked Survey ID |
| workordersDetailsTaskCode | `FloatInput` | Task Code |
| workordersDetailsTaskitemNumber | `FloatInput` | Taskitem Number |
| workordersDetailsTypeCode | `StringInput` | Type Code |
| owneraccountdailystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| owneraccountdailystatDetailsOrganizationId | `FloatInput` | Organization ID |
| owneraccountdailystatDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| owneraccountdailystatDetailsLocationId | `StringInput` | Location ID |
| owneraccountdailystatDetailsNameId | `FloatInput` | Name ID |
| owneraccountdailystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| owneraccountdailystatDetailsOwnerProfileId | `FloatInput` | Owner Profile ID |
| owneraccountdailystatDetailsProfileOwnerId | `FloatInput` | Profile Owner ID |
| owneraccountdailystatDetailsResort | `StringInput` | Property |
| owneraccountdailystatDetailsUserId | `FloatInput` | User ID |
#### Validation Rules

**`mandatoryInput`**
- salesmanagerDetailsSrepCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query salesManagerGoals($input: SalesManagerGoalsQueryArgumentsType!) {
  salesManagerGoals(input: $input) @stream {
    salesManagerDetails {
      chainCode
      dSI
      firstName
      fullName
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastName
      middleName
      nameId
      organizationID
      ownerCode
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
    }
    employeeGoalDetails {
      activityNumber
      activityType
      activitytypeid
      appInsertUser
      appUpdateUser
      arrivalEndDate
      arrivalGoalYN
      arrivalStartDate
      arrivalgoalflag
      auSrepCode
      budgetType
      cCateringAvgCheck
      cCateringFBRevenue
      cCateringOtherRevenue
      cExchangeDate
      cExchangeRate
      cRoomAvgRate
      cRoomRevenue
      cateringAverageCheck
      cateringCovers
      cateringFBRevenue
      cateringOtherRevenue
      centralActivityType
      centralMarketCode
      chainCode
      dSI
      deletedFlag
      employeegoalid
      employeeid
      firstName
      fullName
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      lastName
      locationID
      marketCode
      marketid
      middleName
      organizationID
      periodCode
      periodType
      primaryKeyID
      productionEndDate
      productionStartDate
      property
      rnaInsertDate
      rnaUpdateDate
      roomAvgRate
      roomNights
      roomRevenue
      salesGoalID
      srepCode
      type
      updateDate
      updateUser
      userID
      yearId
    }
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
    ownerAccountDailyStatisticsDetails {
      accountOwner
      accountOwnerCode
      accountOwnerEmail
      accountOwnerPhone
      accountOwnerTitle
      accountSrepCode
      adr
      cExchangeDate
      cExchangeRate
      cGroupFBRevenue
      cGroupFBRevenueTax
      cGroupOtherRevenue
      cGroupOtherRevenueTax
      cGroupRoomRevenue
      cGroupRoomRevenueTax
      cGroupTotalRevenue
      cGroupTotalRevenueTax
      cTotalFBRevenue
      cTotalFBRevenueTax
      cTotalOtherRevenue
      cTotalOtherRevenueTax
      cTotalRoomRevenue
      cTotalRoomRevenueTax
      cTotalTotalRevenue
      cTotalTotalRevenueTax
      centralIndividualFBRevenueNet
      centralIndividualFBRevenueTax
      centralIndividualOtherRevenueNet
      centralIndividualOtherRevenueTax
      centralIndividualRoomRevenueNet
      centralIndividualRoomRevenueTax
      centralIndividualTotalRevenueNet
      centralIndividualTotalRevenueTax
      chainCode
      dSI
      deletedFlag
      description
      grpAverageDailyRate
      grpFBRevenue
      grpFBRevenueTax
      grpNumberCancels
      grpNumberNights
      grpNumberNumberShows
      grpNumberStays
      grpOtherRevenue
      grpOtherRevenueTax
      grpRoomRevenue
      grpRoomRevenueTax
      grpTotalRevenue
      grpTotalRevenueTax
      inactiveDate
      inactiveFlag
      individualCancels
      individualFBRevenueNet
      individualFBRevenueTax
      individualNoShows
      individualOtherRevenueNet
      individualOtherRevenueTax
      individualRoomNights
      individualRoomRevenueNet
      individualStays
      individualTotalRevenueNet
      individualTotalRevenueTax
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      localCurrency
      locationId
      nameId
      nameType
      organizationID
      ownerProfileId
      primaryKeyID
      primaryYN
      profileOwnerId
      property
      relationship
      relationshipid
      resort
      rnaInsertDate
      rnaUpdateDate
      roomRevenueTax
      stayDate
      stayMonth
      stayYear
      toType
      totalAdr
      totalFbRevenue
      totalFbRevenueTax
      totalNumberCancels
      totalNumberNights
      totalNumberNoShows
      totalNumberStays
      totalOtherRevenue
      totalOtherRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
      updateDate
      updateUser
      userId
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
sales_manager_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'firstName': pl.Utf8,
    'fullName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastName': pl.Utf8,
    'middleName': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'ownerCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
employee_goal_details_schema = {
    'activityNumber': pl.Float64,
    'activityType': pl.Utf8,
    'activitytypeid': pl.Utf8,
    'appInsertUser': pl.Utf8,
    'appUpdateUser': pl.Utf8,
    'arrivalEndDate': pl.Utf8,
    'arrivalGoalYN': pl.Utf8,
    'arrivalStartDate': pl.Utf8,
    'arrivalgoalflag': pl.Utf8,
    'auSrepCode': pl.Utf8,
    'budgetType': pl.Utf8,
    'cCateringAvgCheck': pl.Float64,
    'cCateringFBRevenue': pl.Float64,
    'cCateringOtherRevenue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoomAvgRate': pl.Float64,
    'cRoomRevenue': pl.Float64,
    'cateringAverageCheck': pl.Float64,
    'cateringCovers': pl.Float64,
    'cateringFBRevenue': pl.Float64,
    'cateringOtherRevenue': pl.Float64,
    'centralActivityType': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'employeegoalid': pl.Float64,
    'employeeid': pl.Float64,
    'firstName': pl.Utf8,
    'fullName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastName': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'middleName': pl.Utf8,
    'organizationID': pl.Int64,
    'periodCode': pl.Utf8,
    'periodType': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'productionEndDate': pl.Utf8,
    'productionStartDate': pl.Utf8,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomAvgRate': pl.Float64,
    'roomNights': pl.Float64,
    'roomRevenue': pl.Float64,
    'salesGoalID': pl.Float64,
    'srepCode': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userID': pl.Float64,
    'yearId': pl.Float64,
}
```
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
owner_account_daily_statistics_details_schema = {
    'accountOwner': pl.Utf8,
    'accountOwnerCode': pl.Utf8,
    'accountOwnerEmail': pl.Utf8,
    'accountOwnerPhone': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountSrepCode': pl.Utf8,
    'adr': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGroupFBRevenue': pl.Float64,
    'cGroupFBRevenueTax': pl.Float64,
    'cGroupOtherRevenue': pl.Float64,
    'cGroupOtherRevenueTax': pl.Float64,
    'cGroupRoomRevenue': pl.Float64,
    'cGroupRoomRevenueTax': pl.Float64,
    'cGroupTotalRevenue': pl.Float64,
    'cGroupTotalRevenueTax': pl.Float64,
    'cTotalFBRevenue': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenue': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRoomRevenue': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cTotalTotalRevenue': pl.Float64,
    'cTotalTotalRevenueTax': pl.Float64,
    'centralIndividualFBRevenueNet': pl.Float64,
    'centralIndividualFBRevenueTax': pl.Float64,
    'centralIndividualOtherRevenueNet': pl.Float64,
    'centralIndividualOtherRevenueTax': pl.Float64,
    'centralIndividualRoomRevenueNet': pl.Float64,
    'centralIndividualRoomRevenueTax': pl.Float64,
    'centralIndividualTotalRevenueNet': pl.Float64,
    'centralIndividualTotalRevenueTax': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'grpAverageDailyRate': pl.Float64,
    'grpFBRevenue': pl.Float64,
    'grpFBRevenueTax': pl.Float64,
    'grpNumberCancels': pl.Float64,
    'grpNumberNights': pl.Float64,
    'grpNumberNumberShows': pl.Float64,
    'grpNumberStays': pl.Float64,
    'grpOtherRevenue': pl.Float64,
    'grpOtherRevenueTax': pl.Float64,
    'grpRoomRevenue': pl.Float64,
    'grpRoomRevenueTax': pl.Float64,
    'grpTotalRevenue': pl.Float64,
    'grpTotalRevenueTax': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'individualCancels': pl.Float64,
    'individualFBRevenueNet': pl.Float64,
    'individualFBRevenueTax': pl.Float64,
    'individualNoShows': pl.Float64,
    'individualOtherRevenueNet': pl.Float64,
    'individualOtherRevenueTax': pl.Float64,
    'individualRoomNights': pl.Float64,
    'individualRoomRevenueNet': pl.Float64,
    'individualStays': pl.Float64,
    'individualTotalRevenueNet': pl.Float64,
    'individualTotalRevenueTax': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'localCurrency': pl.Utf8,
    'locationId': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'organizationID': pl.Int64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryYN': pl.Utf8,
    'profileOwnerId': pl.Float64,
    'property': pl.Utf8,
    'relationship': pl.Utf8,
    'relationshipid': pl.Utf8,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomRevenueTax': pl.Float64,
    'stayDate': pl.Utf8,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'toType': pl.Utf8,
    'totalAdr': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
    'totalNumberCancels': pl.Float64,
    'totalNumberNights': pl.Float64,
    'totalNumberNoShows': pl.Float64,
    'totalNumberStays': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueTax': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueTax': pl.Float64,
    'totalTotalRevenue': pl.Float64,
    'totalTotalRevenueTax': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userId': pl.Float64,
}
```