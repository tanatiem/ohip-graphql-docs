# SalesManagerGoals
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| salesManagerDetails | [`SalesManagerGoalsSalesManagerDetailsType`](#salesmanagergoalssalesmanagerdetailstype) | Sales Manager Details |
| employeeGoalDetails | [`SalesManagerGoalsEmployeeGoalDetailsType`](#salesmanagergoalsemployeegoaldetailstype) | Employee Goal Details |
| workOrdersDetails | [`SalesManagerGoalsWorkOrdersDetailsType`](#salesmanagergoalsworkordersdetailstype) | Work Orders Details |
| ownerAccountDailyStatisticsDetails | [`SalesManagerGoalsOwnerAccountDailyStatisticsDetailsType`](#salesmanagergoalsowneraccountdailystatisticsdetailstype) | Owner Account Daily Statistics |
| salesManagerGoalsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsSalesManagerDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| firstName | `String` | First Name |
| fullName | `String` | Full Name |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastName | `String` | Last Name |
| middleName | `String` | Middle Name |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerCode | `String` | Owner Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsEmployeeGoalDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activityNumber | `Float` | Number of Activities |
| activityType | `String` | Activity Type |
| activitytypeid | `String` | Activitytypeid |
| appInsertUser | `String` | App Insert User |
| appUpdateUser | `String` | App Update User |
| arrivalEndDate | `Date` | Arrival Period End Date |
| arrivalGoalYN | `String` | Arrival Goal if Y |
| arrivalStartDate | `Date` | Arrival Period Start |
| arrivalgoalflag | `String` | Arrivalgoalflag |
| auSrepCode | `String` | Au Srep Code |
| budgetType | `String` | Budget Type |
| cCateringAvgCheck | `Float` | Central Catering Avg Check |
| cCateringFBRevenue | `Float` | Central Catering Fb Revenue |
| cCateringOtherRevenue | `Float` | Central Catering Other Revenue |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoomAvgRate | `Float` | Central Room Avg Rate |
| cRoomRevenue | `Float` | Central Room Revenue |
| cateringAverageCheck | `Float` | Average Guestcheck per period |
| cateringCovers | `Float` | Catering Covers per period |
| cateringFBRevenue | `Float` | Food/Beverage Revenue per period |
| cateringOtherRevenue | `Float` | Other Revenue per period |
| centralActivityType | `String` | Central Activity Type |
| centralMarketCode | `String` | Central Market Code |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| employeegoalid | `Float` | Employeegoalid |
| employeeid | `Float` | Employeeid |
| firstName | `String` | First Name |
| fullName | `String` | Full Name |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| lastName | `String` | Last Name |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| middleName | `String` | Middle Name |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| periodCode | `String` | Period Code |
| periodType | `String` | Period Type |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| productionEndDate | `Date` | Production Period End Date |
| productionStartDate | `Date` | Production Period Start |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomAvgRate | `Float` | Room Avg Rate |
| roomNights | `Float` | Room Nights |
| roomRevenue | `Float` | Room Revenue |
| salesGoalID | `Float` | Primary Key |
| srepCode | `String` | Srep Code |
| type | `String` | Goal Types |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userID | `Float` | User ID |
| yearId | `Float` | Year ID |

[⬆ Back to Query](#query)

---

### SalesManagerGoalsWorkOrdersDetailsType

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

### SalesManagerGoalsOwnerAccountDailyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountOwner | `String` | Account Owner |
| accountOwnerCode | `String` | Account Owner Code |
| accountOwnerEmail | `String` | Account Owner Email |
| accountOwnerPhone | `String` | Phone no. |
| accountOwnerTitle | `String` | Account Owner Title |
| accountSrepCode | `String` | Account Srep Code |
| adr | `Float` | Average Daily Rate |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| cTotalFBRevenue | `Float` | Central Total Fb Revenue |
| cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| cTotalOtherRevenue | `Float` | Central Total Other Revenue |
| cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| cTotalRoomRevenue | `Float` | Central Total Room Revenue |
| cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| cTotalTotalRevenue | `Float` | Central Total Total Revenue |
| cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| grpAverageDailyRate | `Float` | Group Adr |
| grpFBRevenue | `Float` | Group F&B Revenue. |
| grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| grpNumberCancels | `Float` | Group Number of Cancellations. |
| grpNumberNights | `Float` | Group Number of Nights. |
| grpNumberNumberShows | `Float` | Group Number of No Shows. |
| grpNumberStays | `Float` | Group Number of Stays. |
| grpOtherRevenue | `Float` | Group Other Revenue. |
| grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| grpRoomRevenue | `Float` | Group Room Revenue. |
| grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| grpTotalRevenue | `Float` | Group Total Revenue. |
| grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| individualCancels | `Float` | Individual Cancels |
| individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| individualNoShows | `Float` | Individual Number Shows |
| individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| individualRoomNights | `Float` | Individual Room Nights |
| individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| individualStays | `Float` | Individual Stays |
| individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| localCurrency | `String` | Local Currency Code. |
| locationId | `String` | Location ID |
| nameId | `Float` | Name ID |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerProfileId | `Float` | Owner Profile ID |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| profileOwnerId | `Float` | Profile Owner ID |
| property | `String` | Indicates if the value set for the specific property. |
| relationship | `String` | Relationship |
| relationshipid | `String` | Relationshipid |
| resort | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomRevenueTax | `Float` | Room Revenue Tax |
| stayDate | `Date` | Stay Date |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| toType | `String` | To Type |
| totalAdr | `Float` | Total Average Daily Rate |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| totalNumberCancels | `Float` | Total Number Cancels |
| totalNumberNights | `Float` | Total Number Nights |
| totalNumberNoShows | `Float` | Total Number Number Shows |
| totalNumberStays | `Float` | Total Number Stays |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| totalTotalRevenue | `Float` | Total Total Revenue |
| totalTotalRevenueTax | `Float` | Total Total Revenue Tax |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userId | `Float` | User ID |

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