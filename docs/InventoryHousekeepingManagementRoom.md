# InventoryHousekeepingManagementRoom
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `inventoryHousekeepingManagementRoom`
> Details on Tasks Task Sheets and Credits and providing Information on Rooms Room Attributes and Statuses for the current date
  
**Return:** [`[InventoryHousekeepingManagementRoomType]`](#inventoryhousekeepingmanagementroomtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`InventoryHousekeepingManagementRoomQueryArgumentsType!`](#inventoryhousekeepingmanagementroomqueryargumentstype) |  |

## Object Types

### InventoryHousekeepingManagementRoomType

| Field | Type | Description |
| --- | --- | --- |
| houseKeepingDailyTaskRoomDetails | [`InventoryHousekeepingManagementRoomHouseKeepingDailyTaskRoomDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingdailytaskroomdetailstype) | House Keeping Daily Task Room |
| roomDetails | [`InventoryHousekeepingManagementRoomRoomDetailsType`](#inventoryhousekeepingmanagementroomroomdetailstype) | Room Details |
| houseKeepingReservationGuestDetails | [`InventoryHousekeepingManagementRoomHouseKeepingReservationGuestDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingreservationguestdetailstype) | HK Reservation and Guest |
| houseKeepingReservationDetails | [`InventoryHousekeepingManagementRoomHouseKeepingReservationDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingreservationdetailstype) | HK Reservation and Guest |
| houseKeepingTasksDetails | [`InventoryHousekeepingManagementRoomHouseKeepingTasksDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingtasksdetailstype) | HK Task and Facility Codes |
| houseKeepingTasksRoomCategoryFacilityCodesDetails | [`InventoryHousekeepingManagementRoomHouseKeepingTasksRoomCategoryFacilityCodesDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingtasksroomcategoryfacilitycodesdetailstype) | HK Task and Facility Codes |
| houseKeepingEmployeePointsDetails | [`InventoryHousekeepingManagementRoomHouseKeepingEmployeePointsDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingemployeepointsdetailstype) | HK Task and Employee Points |
| houseKeepingDailyTaskDetails | [`InventoryHousekeepingManagementRoomHouseKeepingDailyTaskDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingdailytaskdetailstype) | HK Task and Employee Points |
| propertyPropertyDetails | [`InventoryHousekeepingManagementRoomPropertyPropertyDetailsType`](#inventoryhousekeepingmanagementroompropertypropertydetailstype) | Resort Details |
| dateCalendarDetails | [`InventoryHousekeepingManagementRoomDateCalendarDetailsType`](#inventoryhousekeepingmanagementroomdatecalendardetailstype) | Date Calendar |
| inventoryHousekeepingManagementRoomRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingDailyTaskRoomDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrivalRoom | `Float` | Arrival Room |
| assignmentCode | `String` | Code indicating why this room was assigned to this task sheet. |
| assignmentComments | `String` | Additional comments why this room was assigned to this task sheet. |
| attendantRoomStatus | `String` | Attendant Room Status |
| attendantRoomStatusDesc | `String` | Attendant Room Status Desc |
| autoGenerateFilters | `String` | Auto generated filters. |
| autoGenerateInd | `String` | Indicates if task has been automatically generated. |
| businessDate | `Date` | Business date. |
| cCreditFromSpecials | `Float` | Central Credit From Specials |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cleanInd | `Float` | Clean Individual |
| creditFromSpecials | `Float` | Credits based on Specials attached to the reservation. |
| credits | `Float` | Credits |
| creditsRem | `String` | Remarks for the credits |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| depRoomInd | `Float` | Dep Room Individual |
| dirtyInd | `Float` | Dirty Individual |
| facilityTaskCodes | `String` | Facility Task Codes |
| finalEndRoomStatus | `String` | Final End Room Status |
| houseUseRooms | `Float` | House Use Rooms |
| housekeepingBreakoutJobId | `Float` | Hk Breakout Job ID |
| housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| inspectedInd | `Float` | Inspected Individual |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lockedByUser | `Float` | User ID who locked this tasksheet. |
| lockedDate | `Date` | Date and Time that this task sheet was locked. |
| maxCredits | `Float` | Credits assigned for a particular task. |
| oOORooms | `Float` | OOO Rooms |
| oOSRooms | `Float` | OOS Rooms |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pickupInd | `Float` | Pickup Individual |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priorityTask | `String` | Priority Task |
| priorityTaskDescription | `String` | Priority Task Description |
| property | `String` | Code to uniquely identify the Property |
| resvnRoom | `String` | Component Suite / Room number that is booked for the reservation that currently occupies the physical room. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomInstrDetails | `String` | Room Instr Details |
| roomInstructions | `String` | Room Instructions |
| roomMoved | `String` | Flag to indicate if this task was assigned during automatic breakout. |
| rooms | `String` | Rooms |
| serviceTime | `String` | Turndown service time |
| simpleTaskYn | `String` | This indicates whether the task is simple or not |
| squareUnits | `Float` | Square Units |
| targetCredits | `Float` | Target Credits |
| taskCompletedDate | `Date` | Date on which task is completed. |
| taskDate | `Date` | Breakout Date. |
| taskInstructions | `String` | Any specific instructions for the task. |
| taskSeqNumber | `Float` | Task Sequence No |
| taskSheet | `Float` | task sheet associated with this room on business_date |
| taskSheetLocked | `String` | Task Sheet Locked |
| taskSheetType | `String` | Indicates the task sheet type possible values: [A]utomatic [F]loating Sheet [N]o Services required [M]anually created |
| travelingCredits | `Float` | Total traveling credits for this task sheet based on change of floors |
| turndown | `String` | Turndown service Y/N |
| turndownExtrasYn | `String` | Indicates if extra turndown services are applicable. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomRoomDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessible | `String` | Accessible |
| areaF | `Float` | Area in sqft |
| areaM | `Float` | Area in sqm |
| assignAssignStatus | `String` | Assign Assign Status |
| assignDate | `DateTime` | Room assignment date |
| assignReasonDesc | `String` | Assign Reason Desc |
| assignType | `String` | Assign Type |
| assignemployeeid | `Float` | Assignemployeeid |
| assignreasonid | `String` | Assignreasonid |
| bedType | `String` | Bed Type |
| building | `String` | Building |
| buildingGroup | `String` | Building Group |
| businessDate | `Date` | Business Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMinimumRevenue | `Float` | Central Minimum Revenue |
| cRackRate | `Float` | Central Rack Rate |
| centralMeetingRoomType | `String` | Central Meeting Room Type |
| centralRoomClass | `String` | Central Room Class |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| combinationRoomYN | `String` | Combination Room YN |
| comments | `String` | Comments |
| componentRoom | `String` | Suite component room numbers |
| connectingRoomNumber | `String` | Connecting Room Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daySection | `String` | Indicates the section to which employee belongs. |
| deductYN | `String` | Deduct YN |
| defatulratecodeid | `String` | Defatulratecodeid |
| defaultRateDesc | `String` | Default Rate Description |
| deletedflag | `String` | Deleted Flag |
| departureCredits | `Float` | Credits associated with the task after departure. |
| description | `String` | Description |
| diaryName | `String` | Diary name to show room in |
| diarydisplayflag | `String` | Diarydisplayflag |
| discrepancy | `String` | Discrepancy |
| doors | `String` | Number of doors |
| eveningSection | `String` | Section the room belongs to for evening housekeeping |
| evisitorFacilityId | `String` | Facility ID for eVisitor. |
| excludedEventTypes | `String` | Stores event types which do not require alternate spaces. |
| facing | `String` | Direction room faces |
| floor | `String` | Floor |
| foPers | `Float` | The persons staying in room according to Front office. |
| forceAlternateYn | `String` | Defines if the function space needs an alternate space when booked. |
| frontDeskLocation | `String` | The front desk location this room should check in to. |
| frontOfficeStatus | `String` | Front Office Status of the room i.e.: Vacant or Occupied. |
| fullUtilizationTime | `Float` | Minutes occupied that define the room as 100% utilized. Maximum is 1440 minutes. |
| genericYN | `String` | Generic YN |
| handicapflag | `String` | Handicapflag |
| heightmaxF | `Float` | Max Height in ft |
| heightmaxM | `Float` | Max Height in m |
| heightminF | `Float` | Minumum heigth of room (feet) |
| heightminM | `Float` | Minumum heigth of room (meters) |
| holdDateTime | `DateTime` | Date and time when room will be released from hold. |
| holdType | `String` | Hold type from resort_assignment_reasons table. |
| holdUser | `Float` | User that is holding the room. |
| housekeepingAssignmentOrderBy | `Float` | Sequence for automatically generated task assignment. |
| housekeepingInspDate | `Date` | Housekeeping Inspected date |
| housekeepingInspEmpId | `String` | Houskeeping inspected employee id |
| housekeepingPers | `Float` | The number of persons staying in the room according to housekeeping |
| housekeepingStatus | `String` | The status of this room according to housekeeping |
| imageId | `Float` | Image ID |
| inactiveflag | `String` | Inactive Flag |
| includeInStatisticsYN | `String` | Include in Statistics YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalTempflag | `String` | Tempflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyCode | `String` | The current key code for this room.  Used to create keys for a room. |
| keyOptions | `String` | Privileges available for this key |
| lastCheckOutDate | `Date` | The last check out date for this room. |
| lastMeterReading | `Float` | The last meter reading for condos that track electrical usage of rented rooms. |
| lengthF | `Float` | Length (feet) |
| lengthM | `Float` | Length (meters) |
| light | `String` | Number of lights in the room |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loudspeakersflag | `String` | Loudspeakersflag |
| maxAdvance | `Float` | Maximum number of days before the catering event date  that the space can be booked on the web. |
| maxCapacity | `Float` | Function Space Maximum Capacity. |
| maxSharedGroups | `Float` | Maximum number of groups for a Shared function space allowed. |
| maximumOccupancy | `Float` | Maximum Occupancy |
| measurement | `String` | The unit of measurement for this square units (IE: Feet Meters etc) |
| meetingRoomType | `String` | Type of meeting room |
| meetingRoomYN | `String` | Meeting Room YN |
| meetingroomTypeDesc | `String` | Meetingroom Type Description |
| meetingroomTypeSeq | `Float` | Meetingroom Type Sequence |
| microphoneSocketTypes | `String` | Type of microphone sockets |
| microphoneSockets | `Float` | Number of microphone sockets |
| minAdvance | `Float` | Minimum number of days before the catering event date that the space can be booked on the web. |
| minCapacity | `Float` | Minimum Capacity |
| minimumRevenue | `Float` | Minimum Revenue |
| numberOfBeds | `Float` | Specifies the number of beds in this room. |
| occupancyCondition | `String` | Current room condition updated daily.(ie StayOverDueOutExpected etc) |
| occupantDiscrepancy | `Float` | Discrepancy between front desk and housekeeping |
| onlinePrintingYn | `String` | Used for pseudo rooms. If Y then this pseudo room will be included in Online Printing for reservation changes. |
| orderBy2 | `Float` | Display sequence 2 |
| orderBy3 | `Float` | Display sequence 3 |
| orderBy4 | `Float` | Display sequence 4 |
| orderBy5 | `Float` | Display sequence 5 |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ovosGradeCode | `String` | Stores a Grade associated with a unit to determine the room display order in Room Assignment and Room Plan screens. |
| ovosUnitYn | `String` | Room can be OVOS unit. |
| pcode | `String` | Not used |
| personDiscrepancy | `Float` | Person discrepancy between front desk and houskeeping |
| phoneNumber | `String` | Phone Number |
| physicalNumberOfRooms | `Float` | Physical Number of Rooms |
| pickupCredits | `Float` | Houskeeping credits for cleaning room in pickup status |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| publishedRateAmount | `Float` | Default rate for the room |
| publishedRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rating | `String` | Rating |
| repAssignReasonDescription | `String` | Reporting Assign Reason Desc |
| repBedTypeDescription | `String` | Reporting Bed Type Desc |
| repMeetingroomTypeDescription | `String` | Reporting Meetingroom Type Desc |
| repMeetingroomTypeSequence | `Float` | Reporting Meetingroom Type Seq |
| repRoomClassSellSequence | `Float` | Reporting Room Class Sell Seq |
| repRoomFeaturesDescs | `String` | Reporting Room Features Descs |
| repRoomStatusReason | `String` | Reporting Room Status Reason |
| repRoomStatusReasonDescription | `String` | Reporting Room Status Reason Desc |
| returnStatus | `String` | Room return status |
| room | `String` | Room |
| roomAssignmentRating | `Float` | Room Assignment Rating. |
| roomCategoryBedtype | `String` | Room Category Bedtype |
| roomCategoryDesc | `String` | Room Category Desc |
| roomClass | `String` | Room Class |
| roomClassCentralDescription | `String` | Room Class Central Description |
| roomClassDescription | `String` | Room Class Description |
| roomClassSequence | `Float` | Room Class Sequence |
| roomCondition | `String` | Room Condition |
| roomFeatureDescription | `String` | Room Feature Description |
| roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| roomNumber | `String` | Room Number |
| roomParity | `String` | Room Parity |
| roomStatus | `String` | Room Status |
| roomStatusDescription | `String` | Room Status Description |
| roomStatusFromDate | `Date` | The date as of which the room_status is valid. |
| roomStatusReason | `String` | Room Status Reason |
| roomStatusReasonDesc | `String` | Room Status Reason Description |
| roomStatusRemarks | `String` | Room status remarks |
| roomStatusToDate | `Date` | The date till which the room_status is valid.(Used during OO and OS status of rooms ) |
| roomType | `String` | Room Type |
| roomUseCount | `Float` | Total Count of the number of days the room was used. |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| roomid | `String` | Roomid |
| roomstatusreasonid | `String` | Roomstatusreasonid |
| sequence | `Float` | Sequence |
| serviceStatus | `String` | Current guest service status code for this room. Example: Service status can be DND (Do Not Disturb) or MUP (Make Up Room) |
| setupNotes | `String` | Notes for the setup of the room |
| shareableflag | `String` | Shareableflag |
| smoking | `String` | Smoking |
| smokingPreferences | `String` | Smoking Preferences |
| squareUnits | `Float` | The square units for this room (IE: if a condo in the US likely the square feet of this room) |
| stayoverCredits | `Float` | Stayover Credits |
| suiteType | `String` | Standard or Suite |
| suiteYN | `String` | Suite YN |
| supplement | `String` | Supplement |
| tempFlag | `String` | Temp Flag |
| translationboothNum | `Float` | Number for the booth |
| turnDown | `String` | Turn Down |
| turndownCredits | `Float` | Houskeeping credits for Turndown. |
| tvRadioSockets | `Float` | Number of TV or radio sockets |
| unit | `String` | Unit |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| visibleOnWebYn | `String` | Flag makes a Function Space visible on the web. |
| webBookingYn | `String` | Web Booking Y/N |
| weightF | `Float` | Room weigth (feet) |
| weightM | `Float` | Room weigth (meters) |
| widthF | `Float` | Width (feet) |
| widthM | `Float` | Width (meters) |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingReservationGuestDetailsType

| Field | Type | Description |
| --- | --- | --- |
| guestProfileID | `Float` | The primary key for this table. |
| aRNumber | `String` | Account number. |
| aRNumberCentral | `String` | Account Receivable No. of this profile. |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountBillingContact | `String` | Billing contact person in company. |
| accountSource | `String` | Used in S&.C Module. |
| accountType | `String` | Account Type of this Profile |
| accountTypeDescription | `String` | The description of this value. |
| accountsourceDesc | `String` | The description of this value. |
| actionCode | `String` | Mailing action codes. |
| activeYN | `String` | Profile is active or not. |
| address1 | `String` | The first line of street address. |
| address2 | `String` | The second line of street address. |
| address3 | `String` | The third line of street address. |
| address4 | `String` | The fourth line of street address. |
| addressId | `Float` | The primary key for this table. |
| addressLangCodeDesc | `String` | Description for each language code. |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | The type of address. |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allResorts | `String` | All Resorts |
| alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&.C |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Description for each language code. |
| alternateSalutation | `String` | Alternate Salutation |
| autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| availabilityOverride | `String` | Does profile have Availability Override Y/N |
| billingCode | `String` | The billing code for this name record. |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthCountry | `String` | Country of Birth |
| birthDate | `Date` | Date of Birth of the Individual Profiles. |
| birthDateStr | `String` | Stores the encrypted birth date. |
| birthPlace | `String` | Place of Birth |
| blMsg | `String` | Any Message for the Restricted profile. |
| businessSegment | `String` | Used in S&.C Module. |
| businessSegmentDescription | `String` | The description of this value. |
| businessTitle | `String` | The business title for this individual. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountType | `String` | Central Account Type |
| centralBusinessSegment | `String` | Central Business Segment |
| centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| centralCorporateIDType | `String` | Central Corporate ID Type |
| centralDefaultKeyword | `String` | The keyword to search on. |
| centralGuestTitleCode | `String` | Central Guest Title Code |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralMailingActionCode | `String` | Central Mailing Action Code |
| centralPriority | `String` | Central Priority |
| centralStateCode | `String` | Central State Code |
| centralTerritory | `String` | Central Territory |
| centralVIPCode | `String` | Central VIP Code |
| centralVIPDescription | `String` | Central VIP Description |
| chainCode | `String` | Chain Code |
| city | `String` | The city for this address. |
| clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| comments | `String` | Not Used. |
| commissionCode | `String` | Commission Code for the Commission Percentage. |
| commissionCodes | `String` | Code for the commission for Travel Agent |
| commissionCurrencyId | `String` | Comm Curr ID |
| commissionid | `String` | Commission Code for the Commission Percentage. |
| communicationRole1 | `String` | Role in which this phone type belongs to. |
| communicationRole2 | `String` | Role in which this phone type belongs to. |
| communicationRole3 | `String` | Role in which this phone type belongs to. |
| communicationType1 | `String` | The type of this phone number. |
| communicationType2 | `String` | The type of this phone number. |
| communicationType3 | `String` | The type of this phone number. |
| communicationValue1 | `String` | The phone number for this record |
| communicationValue2 | `String` | The phone number for this record |
| communicationValue3 | `String` | The phone number for this record |
| companyAlternate | `String` | Extended Byte Company Name |
| companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| companyNameId | `Float` | Not used. |
| competition | `String` | Competaion code . |
| competitionDesc | `String` | The description of this value. |
| contactYN | `String` | Used in S&.C Module. |
| contractNo | `String` | Group Contract number. |
| contractRecvDate | `Date` | The date the group contract was received. |
| corpTypeDesc | `String` | Corp Type Description |
| corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country name. |
| countryCode | `String` | Country . |
| createdByUser | `String` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| creditRating | `String` | Credit rating. |
| currencyCode | `String` | Currency Code |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| debtorName | `String` | Debtor Name |
| decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| defaultKeyword | `String` | The keyword to search on. |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Used in S&.C Module. |
| deptId | `String` | Used in S&.C Module. |
| description | `String` | Used in QMS Module |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| downloadResort | `String` | REsort name which has downloaded on the laptop. |
| downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| email | `String` | The phone number for this record |
| emailYN | `String` | Email YN |
| envelopeGreeting | `String` | Field which stores the envelop greeting used in S&.C |
| externalDisplayName | `String` | External Display Name |
| externalFirstName | `String` | The first name of an individual. |
| externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| externalName | `String` | The last name of the individual profile. |
| externalReferenceRequ | `String` | Not Used. |
| externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| fMembershipCardNumbers | `String` | Membership Card Number. |
| fMembershipClassDesc | `String` | Descripion of membership class |
| fMembershipClasses | `String` | F Membership Classes |
| fMembershipCodes | `String` | F Membership Codes |
| fMembershipDescriptions | `String` | F Membership Descriptions |
| fMembershipIds | `String` | Primary Key for this table. |
| fMembershipType | `String` | Type of the Membership. |
| fSubscriptionDb | `String` | The ID of the external Database. |
| fSubscriptionYn | `String` | The ID of the external Database. |
| faxNumber | `String` | The phone number for this record |
| firstName | `String` | The first name of an individual name. |
| firstNameAlternate | `String` | First Name Alternate |
| firstNameIncognito | `String` | The keyword to search on. |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestCountry | `String` | Country name. |
| guestCurrencyCode | `String` | Currency code for the Commission payment. |
| guestLanguageCode | `String` | Description for each language code. |
| guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent &. Source) are stored in this column. |
| guestMiddleName | `String` | The middle name of this individual. |
| guestNameSuffix | `String` | Guest Name Suffix |
| guestPrivilegeYN | `String` | Guest Privilege YN |
| guestTitleCode | `String` | The title of the individual. |
| hasRequestedMailYN | `String` | Has Requested Mail YN |
| historyYN | `String` | Keep guest in history Y/N |
| holdCode | `String` | Hold code for the Commission handling purposes. |
| iataConsortia | `String` | Consortia for the IATA number. |
| idCountry | `String` | The country where ID was issued |
| idDate | `Date` | Issued date of Identification |
| idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| idPlace | `String` | The place where ID was issued |
| idType | `String` | Identification Type. Eg Passport Driving License etc |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason why record was inactivated. |
| inactiveReasonDescription | `String` | The description of this value. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| indexName | `String` | Index Name |
| industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| industryDesc | `String` | The description of this value. |
| influence | `String` | Used in S&.C Module. |
| influenceDesc | `String` | The description of this value. |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| languageCode | `String` | Primary language used for the profile. |
| laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| lastGroup | `String` | Last Group |
| lastNameAlternate | `String` | Last Name Alternate |
| lastNameIncognito | `String` | The keyword to search on. |
| lastRate | `Float` | Last Rate |
| lastRateCode | `String` | Last Rate Code |
| lastRoom | `String` | The room that is booked for this reservation leg. |
| lastRoomProperty | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | The legal company name for this company. |
| letterGreeting | `String` | Used in S&.C Module. |
| mailActionDescription | `String` | The description of this value. |
| mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| mailType | `String` | The type of mail this user should be sent. |
| mailingActionCode | `String` | Mailing action codes. |
| marketResearchYN | `String` | Market Research YN |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| nameTaxType | `String` | Not used. |
| nameType | `String` | The type of Profile. |
| nameTypeDescription | `String` | The description of this value. |
| name2 | `String` | Not Used. |
| name3 | `String` | Not used. |
| nationality | `String` | Nationality |
| nationalityCode | `String` | Nationality of the individual. |
| negotiatedRateCodes | `String` | The rate code for which this record applies. |
| nextStay | `Date` | This is a begin_date  with no  time component. |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Organization ID |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| phone | `String` | The phone number for this record |
| phoneWeb | `String` | The phone number for this record |
| phoneYN | `String` | Phone YN |
| postalCode | `String` | The postal code of this address. |
| postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| preferredRoomNo | `String` | Preferred Room Number |
| primaryAddressId | `Float` | Not used. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryNameId | `Float` | Not Used. |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| primaryPhoneId | `Float` | Not used. |
| priority | `String` | Priority of the account |
| priorityDesc | `String` | The description of this value. |
| privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| productInterest | `String` | Preference Code. Part of the Primary Key. |
| profession | `String` | The profession of the Individual |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileId | `Float` | The primary key for this table. |
| profileType | `String` | The type of Profile. |
| propertyRegistered | `String` | Resort for which Job is registered. |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | The region for this name. |
| regionid | `String` | The region for this name. |
| repAccountTypeDescription | `String` | Reporting Account Type Description |
| repAccountsource | `String` | Reporting Accountsource |
| repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| repCompetitionCode | `String` | Reporting Competition Code |
| repCompetitionDescription | `String` | Reporting Competition Desc |
| repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| repIndustryCode | `String` | Reporting Industry Code |
| repIndustryDescription | `String` | Reporting Industry Desc |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repNameType | `String` | Reporting Name Type |
| repNameTypeDescription | `String` | Reporting Name Type Description |
| repNationalityCode | `String` | Rep Nationality Code |
| repNationalityDescription | `String` | Rep Nationality Description |
| repPriorityDescription | `String` | Reporting Priority Desc |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repScopeCityDescription | `String` | Reporting Scope City Desc |
| repScopeDescription | `String` | Reporting Scope Desc |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTerritoryDescription | `String` | Reporting Territory Desc |
| repTitleName | `String` | Reporting Title Name |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| requestType | `String` | This column store the Name of the Company Profiles. |
| restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| restrictedRule | `String` | The description of this value. |
| resvContact | `String` | Reservation Contact person. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotential | `String` | Potential no of rooms per year for a account |
| roomsPotentialDesc | `String` | The description of this value. |
| sMSYN | `String` | Use this alert to text a notification. |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope of the account |
| scopeCity | `String` | Scope City |
| scopeCityDesc | `String` | The description of this value. |
| scopeDesc | `String` | The description of this value. |
| searchName | `String` | The Uppercase value of Last or Company. |
| searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sfirst | `String` | Uppercase value of First Name. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| srepCode | `String` | Used in QMS Module |
| state | `String` | The state of this address. |
| stateCode | `String` | State Code |
| stateDescription | `String` | Description of the state. |
| summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| superSearchIndexText | `String` | Used in Oracle Text Index. |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| taxID2 | `String` | Tax No |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| territory | `String` | TERRITORY of  a account |
| territoryDesc | `String` | The description of this value. |
| thirdPartyYN | `String` | Third Party YN |
| titleAlternate | `String` | Title Alternate |
| titleName | `String` | The description of this value. |
| titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| traceCode | `String` | Code to Trace a record for all Triggered actions. |
| tracecodeDesc | `String` | Description |
| typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| uDFC01 | `String` | User defined character field. |
| uDFC02 | `String` | User defined character field. |
| uDFC03 | `String` | User defined character field. |
| uDFC04 | `String` | User defined character field. |
| uDFC05 | `String` | User defined character field. |
| uDFC06 | `String` | User defined character field. |
| uDFC07 | `String` | User defined character field. |
| uDFC08 | `String` | User defined character field. |
| uDFC09 | `String` | User defined character field. |
| uDFC10 | `String` | User defined character field. |
| uDFC11 | `String` | User defined character field. |
| uDFC12 | `String` | User defined character field. |
| uDFC13 | `String` | User defined character field. |
| uDFC14 | `String` | User defined character field. |
| uDFC15 | `String` | User defined character field. |
| uDFC16 | `String` | User defined character field. |
| uDFC17 | `String` | User defined character field. |
| uDFC18 | `String` | User defined character field. |
| uDFC19 | `String` | User defined character field. |
| uDFC20 | `String` | User defined character field. |
| uDFC21 | `String` | User defined character field. |
| uDFC22 | `String` | User defined character field. |
| uDFC23 | `String` | User defined character field. |
| uDFC24 | `String` | User defined character field. |
| uDFC25 | `String` | User defined character field. |
| uDFC26 | `String` | User defined character field. |
| uDFC27 | `String` | User defined character field. |
| uDFC28 | `String` | User defined character field. |
| uDFC29 | `String` | User defined character field. |
| uDFC30 | `String` | User defined character field. |
| uDFC31 | `String` | User defined character field. |
| uDFC32 | `String` | User defined character field. |
| uDFC33 | `String` | User defined character field. |
| uDFC34 | `String` | User defined character field. |
| uDFC35 | `String` | User defined character field. |
| uDFC36 | `String` | User defined character field. |
| uDFC37 | `String` | User defined character field. |
| uDFC38 | `String` | User defined character field. |
| uDFC39 | `String` | User defined character field. |
| uDFC40 | `String` | User defined character field. |
| uDFD01 | `Date` | User defined date field. |
| uDFD02 | `Date` | User defined date field. |
| uDFD03 | `Date` | User defined date field. |
| uDFD04 | `Date` | User defined date field. |
| uDFD05 | `Date` | User defined date field. |
| uDFD06 | `Date` | User defined date field. |
| uDFD07 | `Date` | User defined date field. |
| uDFD08 | `Date` | User defined date field. |
| uDFD09 | `Date` | User defined date field. |
| uDFD10 | `Date` | User defined date field. |
| uDFD11 | `Date` | User defined date field. |
| uDFD12 | `Date` | User defined date field. |
| uDFD13 | `Date` | User defined date field. |
| uDFD14 | `Date` | User defined date field. |
| uDFD15 | `Date` | User defined date field. |
| uDFD16 | `Date` | User defined date field. |
| uDFD17 | `Date` | User defined date field. |
| uDFD18 | `Date` | User defined date field. |
| uDFD19 | `Date` | User defined date field. |
| uDFD20 | `Date` | User defined date field. |
| uDFN01 | `Float` | User defined number field. |
| uDFN02 | `Float` | User defined number field. |
| uDFN03 | `Float` | User defined number field. |
| uDFN04 | `Float` | User defined number field. |
| uDFN05 | `Float` | User defined number field. |
| uDFN06 | `Float` | User defined number field. |
| uDFN07 | `Float` | User defined number field. |
| uDFN08 | `Float` | User defined number field. |
| uDFN09 | `Float` | User defined number field. |
| uDFN10 | `Float` | User defined number field. |
| uDFN11 | `Float` | User defined number field. |
| uDFN12 | `Float` | User defined number field. |
| uDFN13 | `Float` | User defined number field. |
| uDFN14 | `Float` | User defined number field. |
| uDFN15 | `Float` | User defined number field. |
| uDFN16 | `Float` | User defined number field. |
| uDFN17 | `Float` | User defined number field. |
| uDFN18 | `Float` | User defined number field. |
| uDFN19 | `Float` | User defined number field. |
| uDFN20 | `Float` | User defined number field. |
| uDFN21 | `Float` | User defined number field. |
| uDFN22 | `Float` | User defined number field. |
| uDFN23 | `Float` | User defined number field. |
| uDFN24 | `Float` | User defined number field. |
| uDFN25 | `Float` | User defined number field. |
| uDFN26 | `Float` | User defined number field. |
| uDFN27 | `Float` | User defined number field. |
| uDFN28 | `Float` | User defined number field. |
| uDFN29 | `Float` | User defined number field. |
| uDFN30 | `Float` | User defined number field. |
| uDFN31 | `Float` | User defined number field. |
| uDFN32 | `Float` | User defined number field. |
| uDFN33 | `Float` | User defined number field. |
| uDFN34 | `Float` | User defined number field. |
| uDFN35 | `Float` | User defined number field. |
| uDFN36 | `Float` | User defined number field. |
| uDFN37 | `Float` | User defined number field. |
| uDFN38 | `Float` | User defined number field. |
| uDFN39 | `Float` | User defined number field. |
| uDFN40 | `Float` | User defined number field. |
| updateDate | `DateTime` | The date the record was modified |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | The user that modified the record |
| uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| vIPCode | `String` | VIP Status of the Individual. |
| vIPDescription | `String` | The description of this value. |
| vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xdisplayName | `String` | Xdisplay Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingReservationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualCheckInDate | `DateTime` | Actual Check-In Date |
| actualCheckInTime | `String` | Actual Check-In Time |
| actualCheckOutDate | `DateTime` | Actual Check-Out Date |
| actualCheckOutTime | `String` | Actual Check-Out Time |
| adultSTR | `String` | Adult STR |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| arrivalDate | `Date` | Arrival Date |
| arrivalDateSTR | `String` | Arrival Date STR |
| arrivalTime | `String` | Activity begin time |
| arrivalTimeSTR | `String` | Arrival Time STR |
| autoPostAmount | `Float` | Not used. |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| baseRateAmount | `Float` | Base Rate Amount |
| basedOnRule | `String` | Based On Rule |
| beginDate | `DateTime` | Begin Date |
| billingContactId | `Float` | Billing Contact ID |
| blockCode | `String` | Block Code |
| blockDescription | `String` | Block Description |
| blockID | `Float` | Block ID |
| blockResort | `String` | Property this block belongs to. |
| bookedRoomCategory | `String` | Booked Room Category |
| businessDate | `Date` | Business Date |
| businessDateCreated | `Date` | Business Date Created |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cAutoPostAmount | `Float` | Central Auto Post Amount |
| cBaseRateAmount | `Float` | Central Base Rate Amount |
| cDiscountAmount | `Float` | Central Discount Amt |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cGrossRateAmount | `Float` | Central Gross Rate Amt |
| cNetRoomAmount | `Float` | Central Net Room Amt |
| cOriginalBaseRate | `Float` | Central Original Base Rate |
| cPackageAmount | `Float` | Central Pkg Amt |
| cPackageTax | `Float` | Central Pkg Tax |
| cRateAmount | `Float` | Central Rate Amount |
| cRoomCost | `Float` | Central Room Cost |
| cRoomTax | `Float` | Central Room Tax |
| cShareAmount | `Float` | Central Share Amount |
| cShareAmountOriginal | `Float` | Central Share Amount Original |
| cUpsellCharge | `Float` | Central Upsell Charge |
| cancellationCode | `String` | Cancellation Code |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationNo | `Float` | Cancellation Number |
| cancellationReasonDesc | `String` | Cancellation Reason Description |
| childSTR | `String` | Child STR |
| children | `Float` | Children |
| childrenTaxFree | `Float` | Children Tax Free |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| commissionCode | `String` | Commission Code |
| commissionPaid | `Float` | Commission Paid |
| commissionableYn | `String` | Commissionable Y/N |
| companyId | `Float` | Company ID |
| confirmationNumber | `String` | Confirmation Number |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUseYn | `String` | Day Use Y/N |
| deletedFlag | `String` | Deleted Flag |
| depDateSTR | `String` | Dep Date STR |
| depTimeSTR | `String` | Dep Time STR |
| departureDate | `Date` | Departure Date |
| departureTime | `String` | Departure Time |
| discountAmt | `Float` | Discount Amount |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReasonCode | `String` | Discount Reason Code |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveYn | `String` | Do not move room flag. |
| dueOutYn | `String` | Due Out Y/N |
| endDate | `DateTime` | End Date |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| externalReference | `String` | External Reference |
| extraBeds | `Float` | Extra Beds |
| fixedRateYn | `String` | Fixed Rate Y/N |
| grossRateAmt | `Float` | Not used. |
| groupId | `Float` | Group ID |
| guaranteeCode | `String` | Guarantee Code |
| guestName | `String` | Guest Name |
| guestNameFirstLastInitial | `String` | Guest Name First Last Initial |
| housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| houseuseYN | `String` | Houseuse YN |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalBlockId | `Float` | Block ID. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastShareCalculation | `String` | Calculation method used to distribute the total room rate between shares: [S]plit [Z]ero [F]ull and [P]ercentage. |
| lengthOfStay | `Float` | Length of Stay |
| marketCode | `String` | Market Code |
| membershipLevel | `String` | Membership Level |
| membershipPoints | `Float` | Indicates if the Revenue Type is valid for calculating Membership Points. |
| membershipType | `String` | Membership Type |
| nameId | `Float` | Name ID |
| netRoomAmt | `Float` | Not used. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originOfBooking | `String` | Origin of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| packageAmt | `Float` | Not used. |
| physicalQuantity | `Float` | Physical Quantity |
| physicalRooms | `Float` | Physical Rooms |
| pkgTax | `Float` | Not used. |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| quantity | `Float` | Quantity |
| rESVJRNUpdateDTTM | `DateTime` | RESV JRN Update DTTM |
| rESVJRNUpdateDate | `Date` | RESV JRN Update Date |
| rateAmount | `Float` | Rate Amount |
| rateCode | `String` | Rate Code |
| rdAdults | `Float` | Rd Adults |
| rdBaseRateAmount | `Float` | Rd Base Rate Amount |
| rdCBaseRateAmount | `Float` | Rd Central Base Rate Amount |
| rdCExchangeDate | `Date` | Rd Central Xchange Date |
| rdCExchangeRate | `Float` | Rd Central Xchange Rate |
| rdChildren | `Float` | Rd Children |
| rdDmlSeqNumber | `Float` | Rd Dml Sequence No |
| rdInsertActionInstanceId | `Float` | Rd Insert Action Instance ID |
| rdInsertDate | `DateTime` | Rd Insert Date |
| rdInsertUser | `Float` | Rd Insert User |
| rdUpdateDate | `DateTime` | Rd Update Date |
| rdUpdateUser | `Float` | Rd Update User |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `Date` | Reservation Date |
| reservationNameId | `Float` | Resv Name ID |
| reservationStatus | `String` | Reservation Status |
| resvCleaningTime | `String` | Reservation Cleaning Time |
| resvDailyElSequence | `Float` | Reservation Daily El Seq |
| resvItems | `String` | Reservation Items |
| resvRoomFeatures | `String` | Reservation Room Features |
| resvRoomStatus | `String` | Reservation Room Status |
| resvSpecials | `String` | Reservation Specials |
| resvStatus | `String` | Reservation Status |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomAssignment | `String` | Room Assignment |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomInstructions | `String` | Room Instructions |
| roomTax | `Float` | Room Tax |
| scheduledMoveDatetime | `DateTime` | Scheduled Move Datetime |
| scheduledMoveOutRoom | `String` | Scheduled Move Out Room |
| scheduledMoveStatus | `String` | Scheduled Move Status |
| scheduledMoveTime | `String` | Scheduled Move Time |
| shareAmount | `Float` | Share Amount |
| shareAmountOriginal | `Float` | The original rate amount for the reservation date. |
| sharePaymentType | `String` | Not used. |
| sharePrcnt | `Float` | Not used. |
| sharePriority | `Float` | Not used. |
| sourceId | `Float` | Source ID |
| traces | `String` | Traces |
| travelAgentId | `Float` | Travel Agent ID |
| truncActualCheckInDate | `Date` | Usually will be begin date and will have no time component. |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turnDownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingTasksDetailsType

| Field | Type | Description |
| --- | --- | --- |
| autoAssignedYn | `String` | Flag to indicate if this task was assigned during automatic breakout. |
| canDeleteYn | `String` | Can Delete Y/N |
| colors | `String` | Colors |
| creditWeighting | `Float` | Credit Weighting. NULL will be treated as 100. |
| creditsDeparture | `Float` | Credits associated with the task after departure. |
| customizableYn | `String` | Is Task customizable ? |
| departureRoomDefaultTask | `String` | Indicates if the task is set as departure room default task. |
| guestRequestedTask | `String` | Flag indicates if the guest has to explicitly request this task. |
| housekeepingTaskCredits | `Float` | Housekeeping Task Credits |
| inactive | `String` | Inactive |
| inactiveDate | `DateTime` | Inactive Date |
| linenChange | `String` | Indicates if this facility task requires a Linen Change. |
| room | `String` | Room |
| sequence | `Float` | Sequence |
| taskAssignDate | `Date` | When this task was last assigned. |
| taskCode | `String` | Task Code |
| taskCredits | `Float` | Task Credits |
| taskDSI | `Float` | Task DSI |
| taskDeletedFlag | `String` | Task Deleted Flag |
| taskDescription | `String` | Task Description |
| taskFrequency | `Float` | Task Frequency |
| taskInsertDate | `DateTime` | Task Insert Date |
| taskInsertUser | `Float` | Task Insert User |
| taskInstructions | `String` | Task Instructions |
| taskJRNUpdateDate | `Date` | Task JRN Update Date |
| taskJRNUpdateDateAndTime | `DateTime` | Task JRN Update Date and Time |
| taskLocationID | `String` | Task Location ID |
| taskOrganizationID | `Float` | Task Organization ID |
| taskPrimaryKeyID | `Float` | Task Primary Key ID |
| taskPriority | `Float` | Task Priority |
| taskProperty | `String` | Task Property |
| taskRNAInsertDate | `DateTime` | Task RNA Insert Date |
| taskRNAUpdateDate | `DateTime` | Task RNA Update Date |
| taskSeqNumber | `Float` | Task Sequence No |
| taskUpdateDate | `DateTime` | Task Update Date |
| taskUpdateUser | `Float` | Task Update User |
| unitOfFrequency | `String` | Indicates the unit of frequency for the task to be executed. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingTasksRoomCategoryFacilityCodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| credits | `Float` | Credits |
| customizePromptYn | `String` | Flag indicates if the user should be prompted when a user customizes the schedule for a particular reservation. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayOfTheWeekSchedule | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| day1 | `String` | Day1 |
| day2 | `String` | Day2 |
| day3 | `String` | Day3 |
| day4 | `String` | Day4 |
| day5 | `String` | Day5 |
| day6 | `String` | Day6 |
| day7 | `String` | Day7 |
| deletedFlag | `String` | Deleted Flag |
| facilityTask | `String` | Facility Task |
| facilityTaskSeq | `Float` | Facility Task Sequence |
| facilityTask1 | `String` | Facility Task1 |
| frequency | `String` | Frequency |
| includeOnArrivalDay | `String` | Include on Arrival Day |
| insertDate | `DateTime` | Insert Date |
| insertDate1 | `Date` | Insert Date1 |
| insertUser | `Float` | Insert User |
| insertUser1 | `Float` | Insert User1 |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCodes | `String` | Comma delimited list of Market Codes. |
| marketDescription | `String` | Market Description |
| messageText | `String` | Free format text that will be displayed when a user customizes the schedule for a particular reservation. |
| moveupPenultimateYn | `String` | Indicate if the task should be rescheduled to 1 day earlier when it is due 1 day before the day of departure. |
| numberOfDays | `Float` | Number of Days |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priority | `Float` | Priority |
| property | `String` | Code to uniquely identify the Property |
| quantity | `Float` | Quantity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescriptions | `String` | Rate Code Descriptions |
| repMarketCodesDescription | `String` | Reporting Market Codes Desc |
| repSpecialRequestsDescription | `String` | Reporting Special Requests Desc |
| repVIPStatusesDescription | `String` | Reporting Vip Statuses Desc |
| roomCategory | `String` | Room Category |
| roomCategory1 | `String` | Room Category1 |
| schedule | `String` | Schedule |
| specialRequestsCodes | `String` | Special Requests Codes |
| specialRequestsDescriptions | `String` | Special Requests Descriptions |
| startingOnDay | `Float` | Stay day that the first task in this cycle will be applied. 0 will indicate that the task is due on the day of arrival. Cycle will repeat for every FREQUENCY_DAYS days after arrival. |
| supplyCode | `String` | Supply Code |
| supplyDescription | `String` | Supply Description |
| supplySequence | `Float` | Supply Sequence |
| updateDate | `DateTime` | Update Date |
| updateDate1 | `Date` | Update Date1 |
| updateUser | `Float` | Update User |
| updateUser1 | `Float` | Update User1 |
| vIPLevelsCode | `String` | Comma delimited list of VIP status codes. |
| vIPLevelsDescription | `String` | VIP Levels Description |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingEmployeePointsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| appUserId | `Float` | App User ID |
| available | `String` | Indicates if Employee is available for task assignment. |
| building | `String` | Building |
| day1 | `String` | Day1 |
| day2 | `String` | Day2 |
| day3 | `String` | Day3 |
| day4 | `String` | Day4 |
| day5 | `String` | Day5 |
| day6 | `String` | Day6 |
| day7 | `String` | Day7 |
| deletedFlag | `String` | Deleted Flag |
| empName | `String` | Name of the employee |
| floor | `String` | Floor |
| floorDesc | `String` | Floor Description |
| housekeepingSectionCode | `String` | Indicates the section to which employee belongs. |
| inactiveDate | `Date` | Inactive Date |
| jobCode | `String` | Job Code |
| phoneNo | `String` | Phone no. |
| points | `Float` | Points |
| pointsDate | `Date` | Date the points were allocated |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| repFloorDescription | `String` | Reporting Floor Desc |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sectionDesc | `String` | Description of the section |
| status | `String` | Status |
| userName | `String` | User Name |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingDailyTaskDetailsType

| Field | Type | Description |
| --- | --- | --- |
| applicationUser | `String` | Application User |
| attendantCode | `String` | Attendant Code |
| attendantCodeName | `String` | Attendant Code Name |
| attendantDescription | `String` | Attendant Description |
| attendantInstructions | `String` | Attendant Instructions |
| attendantStatus | `String` | Attendant Status |
| autoGenerateFilters | `String` | Auto generated filters. |
| autoGenerateInd | `String` | Indicates if task has been automatically generated. |
| businessDate | `Date` | Business Date |
| completedDateSTR | `String` | Completed date STR |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyTaskAttendantCode | `String` | Daily Task Attendant Code |
| dailyTaskDSI | `Float` | Daily Task DSI |
| dailyTaskJRNUpdateDate | `Date` | Daily Task JRN Update Date |
| dailyTaskJRNUpdateDateAndTime | `Date` | Daily Task JRN Update Date and Time |
| dailyTaskLocationID | `String` | Daily Task Location ID |
| dailyTaskOrganizationID | `Float` | Daily Task Organization ID |
| dailyTaskResort | `String` | Daily Task Resort |
| deletedFlag | `String` | Deleted Flag |
| facilityCredits | `Float` | Facility Credits |
| floor | `String` | Floor |
| housekeepingBreakoutJobId | `Float` | Hk Breakout Job ID |
| housekeepingTaskCodesList | `String` | Housekeeping Task Codes List |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lockedByUser | `Float` | User ID who locked this tasksheet. |
| lockedDate | `Date` | Date and Time that this task sheet was locked. |
| lockedYn | `String` | Locked Y/N |
| miscellaneousCredits | `Float` | Miscellaneous Credits |
| numRooms | `Float` | Num Rooms |
| numberOfBuildings | `Float` | Number of Buildings |
| numberOfFloors | `Float` | Number of Floors |
| numberOfGroups | `Float` | Number of Groups |
| numberOfSections | `Float` | Number of Sections |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| repFloorDescription | `String` | Reporting Floor Desc |
| rnaInsertDate | `Date` | RnA Insertdate |
| rnaUpdateDate | `Date` | RnA Updatedate |
| roomInstructions | `String` | Room Instructions |
| roomWithNoFloor | `Float` | Room with no Floor |
| roomWithNoGroup | `Float` | Room with no Group |
| roomWithNoSection | `Float` | Room with no Section |
| section | `String` | Description of the section |
| simpleTaskYn | `String` | This indicates whether the task is simple or not |
| systemDateSTR | `String` | System Date STR |
| systemTimeSTR | `String` | System Time STR |
| targetCredits | `Float` | Target Credits |
| taskCode | `String` | Task Code |
| taskCompletedDate | `Date` | Date on which task is completed. |
| taskCredits | `Float` | Credits assigned for a particular task. |
| taskDate | `Date` | Breakout Date. |
| taskDateResortFormat | `String` | Task Date Resort Format |
| taskInstructions | `String` | Any specific instructions for the task. |
| taskSeqNumber | `Float` | Task Sequence No |
| taskSheet | `String` | Task Sheet |
| taskSheetDateSTR | `String` | Task Sheet Date STR |
| taskSheetNo | `Float` | task sheet associated with this room on business_date |
| taskSheetType | `String` | Indicates the task sheet type possible values: [A]utomatic [F]loating Sheet [N]o Services required [M]anually created |
| totalFacilityCredits | `Float` | Total Facility Credits |
| totalItemCredits | `Float` | Total Item Credits |
| totalMiscellaneousCredits | `Float` | Total Miscellaneous Credits |
| totalSpecialCredits | `Float` | Total Special Credits |
| totalTasks | `String` | Total Tasks |
| totalTravellingBuildingCredits | `Float` | Total Travelling Building Credits |
| totalTravellingCredits | `Float` | Total Travelling Credits |
| totalTravellingFloorCredits | `Float` | Total Travelling Floor Credits |
| totalTravellingGroupCredits | `Float` | Total Travelling Group Credits |
| totalTravellingSectionCredits | `Float` | Total Travelling Section Credits |
| travelingCredits | `Float` | Total traveling credits for this task sheet based on change of floors |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomPropertyPropertyDetailsType

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

### InventoryHousekeepingManagementRoomDateCalendarDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dayDesc | `String` | Day Description. |
| dayEndDate | `Date` | Day End Date. |
| dayNoOfMonth | `Float` | Day number of the month. |
| dayNoOfQuarter | `Float` | Day number of the quarter. |
| dayNoOfWeek | `String` | Day number of the week. |
| dayOfWeek | `String` | Day Of Week |
| dayOfYear | `Float` | Day of the Year. |
| dayTimespan | `Float` | Day Timespan. |
| daykey | `Date` | Daykey |
| internalMonthkey | `Float` | Monthkey |
| internalYearkey | `Float` | Yearkey |
| isoWeekOfYear | `String` | Iso Week Of Year |
| julianDaykey | `String` | Julian Daykey |
| lastYearDaykey | `Date` | Last Year Daykey |
| monthDsc | `String` | Month Description. |
| monthEndDate | `Date` | Month End Date. |
| monthKey | `String` | Month Key |
| monthName | `String` | Month Name. |
| monthOfQuarter | `Float` | Month of the quarter. |
| monthOfYear | `Float` | Month of the year. |
| monthTimespan | `Float` | Month Timespan. |
| monthYrKey | `String` | Month Year Key |
| priorJulianDaykey | `String` | Prior Julian Daykey |
| priorMonthKey | `String` | Prior Month Key |
| priorWeekKey | `String` | Prior Week Key |
| priorYearDaykey | `Date` | Prior Year Daykey |
| priorYearKey | `String` | Prior Year Key |
| priorYearMonthKey | `String` | Prior Year Month Key |
| priorYearQuarterKey | `String` | Prior Year Quarter Key |
| priorYearWeekKey | `String` | Prior Year Week Key |
| quarterDsc | `String` | Quarter Description. |
| quarterEndDate | `Date` | Quarter End Date. |
| quarterKey | `String` | Quarter Key |
| quarterOfYear | `String` | Quarter of the year. |
| quarterTimespan | `Float` | Quarter Timespan. |
| weekDsc | `String` | Week Dsc |
| weekEndDate | `Date` | End date of the week. |
| weekEndDsc | `String` | Week End Dsc |
| weekEndKey | `String` | Week End Key |
| weekEndMonthDsc | `String` | Week End Month Dsc |
| weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| weekKey | `String` | Week Key |
| weekOfMonth | `String` | Week of the month. |
| weekOfYear | `String` | Week of the year. |
| weekTimespan | `Float` | Week Timespan. |
| yearDsc | `String` | Year description. |
| yearEndDate | `Date` | Year End Date. |
| yearKey | `String` | Year Key |
| yearTimespan | `Float` | Year Timespan. |

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

### InventoryHousekeepingManagementRoomQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| hkdailytaskroomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hkdailytaskroomDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| hkdailytaskroomDetailsTaskDate | `DateInput!` | Breakout Date.<br>`@mandatoryInput` |
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
| hkreservationguestDetailsNameId | `FloatInput` | The primary key for this table. |
| hkreservationguestDetailsActiveYn | `StringInput` | Profile is active or not. |
| hkreservationguestDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| hkreservationguestDetailsChainCode | `StringInput` | Chain Code |
| hkreservationguestDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| hkreservationguestDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |
| hkreservationguestDetailsContactFlag | `StringInput` | Used in S&.C Module. |
| hkreservationguestDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| hkreservationguestDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent &. Source) are stored in this column. |
| hkreservationguestDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| hkreservationguestDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| hkreservationguestDetailsIndexName | `StringInput` | Index Name |
| hkreservationguestDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hkreservationguestDetailsNameType | `StringInput` | The type of Profile. |
| hkreservationguestDetailsProfileId | `FloatInput` | The primary key for this table. |
| hkreservationguestDetailsProfileType | `StringInput` | The type of Profile. |
| hkreservationguestDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| hkreservationguestDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| hkreservationguestDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| hkreservationguestDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| hkreservationguestDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| hkreservationguestDetailsSrepCode | `StringInput` | Used in QMS Module |
| hkreservationguestDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| hkreservationguestDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| hktaskfacilitycodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hktaskfacilitycodesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| hktaskemployeepointsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hktaskemployeepointsDetailsResort | `StringInput` | Code to uniquely identify the Property |
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
| datedetailDetailsDaykey | `DateInput` | Daykey |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query inventoryHousekeepingManagementRoom($input: InventoryHousekeepingManagementRoomQueryArgumentsType!) {
  inventoryHousekeepingManagementRoom(input: $input) @stream {
    houseKeepingDailyTaskRoomDetails {
      arrivalRoom
      assignmentCode
      assignmentComments
      attendantRoomStatus
      attendantRoomStatusDesc
      autoGenerateFilters
      autoGenerateInd
      businessDate
      cCreditFromSpecials
      cExchangeDate
      cExchangeRate
      cleanInd
      creditFromSpecials
      credits
      creditsRem
      dSI
      deletedFlag
      depRoomInd
      dirtyInd
      facilityTaskCodes
      finalEndRoomStatus
      houseUseRooms
      housekeepingBreakoutJobId
      housekeepingExpectedServiceTime
      inspectedInd
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      lockedByUser
      lockedDate
      maxCredits
      oOORooms
      oOSRooms
      organizationID
      pickupInd
      primaryKeyID
      priorityTask
      priorityTaskDescription
      property
      resvnRoom
      rnaInsertDate
      rnaUpdateDate
      roomInstrDetails
      roomInstructions
      roomMoved
      rooms
      serviceTime
      simpleTaskYn
      squareUnits
      targetCredits
      taskCompletedDate
      taskDate
      taskInstructions
      taskSeqNumber
      taskSheet
      taskSheetLocked
      taskSheetType
      travelingCredits
      turndown
      turndownExtrasYn
    }
    roomDetails {
      accessible
      areaF
      areaM
      assignAssignStatus
      assignDate
      assignReasonDesc
      assignType
      assignemployeeid
      assignreasonid
      bedType
      building
      buildingGroup
      businessDate
      cExchangeDate
      cExchangeRate
      cMinimumRevenue
      cRackRate
      centralMeetingRoomType
      centralRoomClass
      centralRoomType
      centralRoomTypeDescription
      combinationRoomYN
      comments
      componentRoom
      connectingRoomNumber
      dSI
      daySection
      deductYN
      defatulratecodeid
      defaultRateDesc
      deletedflag
      departureCredits
      description
      diaryName
      diarydisplayflag
      discrepancy
      doors
      eveningSection
      evisitorFacilityId
      excludedEventTypes
      facing
      floor
      foPers
      forceAlternateYn
      frontDeskLocation
      frontOfficeStatus
      fullUtilizationTime
      genericYN
      handicapflag
      heightmaxF
      heightmaxM
      heightminF
      heightminM
      holdDateTime
      holdType
      holdUser
      housekeepingAssignmentOrderBy
      housekeepingInspDate
      housekeepingInspEmpId
      housekeepingPers
      housekeepingStatus
      imageId
      inactiveflag
      includeInStatisticsYN
      insertDate
      insertUser
      internalTempflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyCode
      keyOptions
      lastCheckOutDate
      lastMeterReading
      lengthF
      lengthM
      light
      locationID
      loudspeakersflag
      maxAdvance
      maxCapacity
      maxSharedGroups
      maximumOccupancy
      measurement
      meetingRoomType
      meetingRoomYN
      meetingroomTypeDesc
      meetingroomTypeSeq
      microphoneSocketTypes
      microphoneSockets
      minAdvance
      minCapacity
      minimumRevenue
      numberOfBeds
      occupancyCondition
      occupantDiscrepancy
      onlinePrintingYn
      orderBy2
      orderBy3
      orderBy4
      orderBy5
      organizationID
      ovosGradeCode
      ovosUnitYn
      pcode
      personDiscrepancy
      phoneNumber
      physicalNumberOfRooms
      pickupCredits
      primaryKeyID
      property
      pseudoRoomYN
      publishedRateAmount
      publishedRateCode
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rating
      repAssignReasonDescription
      repBedTypeDescription
      repMeetingroomTypeDescription
      repMeetingroomTypeSequence
      repRoomClassSellSequence
      repRoomFeaturesDescs
      repRoomStatusReason
      repRoomStatusReasonDescription
      returnStatus
      room
      roomAssignmentRating
      roomCategoryBedtype
      roomCategoryDesc
      roomClass
      roomClassCentralDescription
      roomClassDescription
      roomClassSequence
      roomCondition
      roomFeatureDescription
      roomFeatures
      roomNumber
      roomParity
      roomStatus
      roomStatusDescription
      roomStatusFromDate
      roomStatusReason
      roomStatusReasonDesc
      roomStatusRemarks
      roomStatusToDate
      roomType
      roomUseCount
      roomcategoryid
      roomclassid
      roomid
      roomstatusreasonid
      sequence
      serviceStatus
      setupNotes
      shareableflag
      smoking
      smokingPreferences
      squareUnits
      stayoverCredits
      suiteType
      suiteYN
      supplement
      tempFlag
      translationboothNum
      turnDown
      turndownCredits
      tvRadioSockets
      unit
      updateDate
      updateUser
      visibleOnWebYn
      webBookingYn
      weightF
      weightM
      widthF
      widthM
    }
    houseKeepingReservationGuestDetails {
      guestProfileID
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      accountTypeDescription
      accountsourceDesc
      actionCode
      activeYN
      address1
      address2
      address3
      address4
      addressId
      addressLangCodeDesc
      addressLanguageCode
      addressType
      alienRegistrationNo
      allResorts
      alternateEnvelopeGreeting
      alternateLanguage
      alternateLanguageDescription
      alternateSalutation
      autoEnrollMemberYN
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessSegment
      businessSegmentDescription
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      ccProfileYn
      centralAccountType
      centralBusinessSegment
      centralBusinessSegmentDescription
      centralCorporateIDType
      centralDefaultKeyword
      centralGuestTitleCode
      centralInactiveReason
      centralInactiveReasonDescription
      centralMailActionDescription
      centralMailingActionCode
      centralPriority
      centralStateCode
      centralTerritory
      centralVIPCode
      centralVIPDescription
      chainCode
      city
      clientID
      collectionUserId
      combinedName
      commPayCentral
      comments
      commissionCode
      commissionCodes
      commissionCurrencyId
      commissionid
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      companyAlternate
      companyGroupId
      companyNameId
      competition
      competitionDesc
      contactYN
      contractNo
      contractRecvDate
      corpTypeDesc
      corporateIDType
      country
      countryCode
      createdByUser
      createdOnDate
      creditRating
      currencyCode
      currencySymbol
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      debtorName
      decimalPositions
      defaultKeyword
      deletedFlag
      department
      deptId
      description
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYN
      envelopeGreeting
      externalDisplayName
      externalFirstName
      externalId
      externalName
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fMembershipType
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      firstName
      firstNameAlternate
      firstNameIncognito
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestCountry
      guestCurrencyCode
      guestLanguageCode
      guestLastName
      guestMiddleName
      guestNameSuffix
      guestPrivilegeYN
      guestTitleCode
      hasRequestedMailYN
      historyYN
      holdCode
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      includeInTax1099Yn
      indexName
      industryCode
      industryDesc
      influence
      influenceDesc
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      languageCode
      laptopChange
      lastGroup
      lastNameAlternate
      lastNameIncognito
      lastRate
      lastRateCode
      lastRoom
      lastRoomProperty
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailActionDescription
      mailList
      mailType
      mailingActionCode
      marketResearchYN
      masterAccountYn
      nameTaxType
      nameType
      nameTypeDescription
      name2
      name3
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      paymentDueDays
      phone
      phoneWeb
      phoneYN
      postalCode
      postalCodeExtension
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      priorityDesc
      privacyFlagYN
      productInterest
      profession
      profileCreditLimit
      profileId
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rateStructure
      region
      regionid
      repAccountTypeDescription
      repAccountsource
      repAccountsourceDescription
      repCompetitionCode
      repCompetitionDescription
      repCorpTypeDescription
      repIndustryCode
      repIndustryDescription
      repInfluence
      repInfluenceDescription
      repNameType
      repNameTypeDescription
      repNationalityCode
      repNationalityDescription
      repPriorityDescription
      repRoomsPotential
      repRoomsPotentialDescription
      repScope
      repScopeCity
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTaxTypeDescription
      repTerritoryDescription
      repTitleName
      repeatGuestId
      replaceAddress
      requestType
      restricted
      restrictedRule
      resvContact
      rnaInsertDate
      rnaUpdateDate
      roomsPotential
      roomsPotentialDesc
      sMSYN
      salutation
      scope
      scopeCity
      scopeCityDesc
      scopeDesc
      searchName
      searchNameAlternate
      sfirst
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      stateDescription
      summRefCc
      summRefCurrencyId
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      territoryDesc
      thirdPartyYN
      titleAlternate
      titleName
      titleSuffix
      totalStay
      tourOperatorType
      traceCode
      tracecodeDesc
      typeOfTax1099
      uDFC01
      uDFC02
      uDFC03
      uDFC04
      uDFC05
      uDFC06
      uDFC07
      uDFC08
      uDFC09
      uDFC10
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vIPCode
      vIPDescription
      vendorId
      vendorSiteId
      vipAuthorization
      visaValidityType
      xdisplayName
      xmiddleName
    }
    houseKeepingReservationDetails {
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      adultSTR
      adults
      adultsTaxFree
      allotmentRecordType
      arrivalDate
      arrivalDateSTR
      arrivalTime
      arrivalTimeSTR
      autoPostAmount
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      baseRateAmount
      basedOnRule
      beginDate
      billingContactId
      blockCode
      blockDescription
      blockID
      blockResort
      bookedRoomCategory
      businessDate
      businessDateCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cDiscountAmount
      cExchangeDate
      cExchangeRate
      cGrossRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmount
      cShareAmountOriginal
      cUpsellCharge
      cancellationCode
      cancellationDate
      cancellationNo
      cancellationReasonDesc
      childSTR
      children
      childrenTaxFree
      children1
      children2
      children3
      children4
      children5
      commissionCode
      commissionPaid
      commissionableYn
      companyId
      confirmationNumber
      cribs
      currencyCode
      dSI
      dayUseYn
      deletedFlag
      depDateSTR
      depTimeSTR
      departureDate
      departureTime
      discountAmt
      discountPrcnt
      discountReasonCode
      dmlSeqNumber
      doNotMoveYn
      dueOutYn
      endDate
      exchangePostingType
      exchangeRate
      extSegNo
      extSeqNumber
      externalReference
      extraBeds
      fixedRateYn
      grossRateAmt
      groupId
      guaranteeCode
      guestName
      guestNameFirstLastInitial
      housekeepingExpectedServiceTime
      houseuseYN
      insertActionInstanceId
      insertDate
      insertUser
      internalBlockId
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastShareCalculation
      lengthOfStay
      marketCode
      membershipLevel
      membershipPoints
      membershipType
      nameId
      netRoomAmt
      organizationID
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      packageAmt
      physicalQuantity
      physicalRooms
      pkgTax
      points
      pointsEligibilityCode
      primaryKeyID
      property
      quantity
      rESVJRNUpdateDTTM
      rESVJRNUpdateDate
      rateAmount
      rateCode
      rdAdults
      rdBaseRateAmount
      rdCBaseRateAmount
      rdCExchangeDate
      rdCExchangeRate
      rdChildren
      rdDmlSeqNumber
      rdInsertActionInstanceId
      rdInsertDate
      rdInsertUser
      rdUpdateDate
      rdUpdateUser
      referralYn
      reservationContactId
      reservationDate
      reservationNameId
      reservationStatus
      resvCleaningTime
      resvDailyElSequence
      resvItems
      resvRoomFeatures
      resvRoomStatus
      resvSpecials
      resvStatus
      rnaInsertDate
      rnaUpdateDate
      room
      roomAssignment
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomTax
      scheduledMoveDatetime
      scheduledMoveOutRoom
      scheduledMoveStatus
      scheduledMoveTime
      shareAmount
      shareAmountOriginal
      sharePaymentType
      sharePrcnt
      sharePriority
      sourceId
      traces
      travelAgentId
      truncActualCheckInDate
      truncActualCheckOutDate
      turnDownStatus
      updateDate
      updateUser
      upsellCharge
    }
    houseKeepingTasksDetails {
      autoAssignedYn
      canDeleteYn
      colors
      creditWeighting
      creditsDeparture
      customizableYn
      departureRoomDefaultTask
      guestRequestedTask
      housekeepingTaskCredits
      inactive
      inactiveDate
      linenChange
      room
      sequence
      taskAssignDate
      taskCode
      taskCredits
      taskDSI
      taskDeletedFlag
      taskDescription
      taskFrequency
      taskInsertDate
      taskInsertUser
      taskInstructions
      taskJRNUpdateDate
      taskJRNUpdateDateAndTime
      taskLocationID
      taskOrganizationID
      taskPrimaryKeyID
      taskPriority
      taskProperty
      taskRNAInsertDate
      taskRNAUpdateDate
      taskSeqNumber
      taskUpdateDate
      taskUpdateUser
      unitOfFrequency
    }
    houseKeepingTasksRoomCategoryFacilityCodesDetails {
      credits
      customizePromptYn
      dSI
      dayOfTheWeekSchedule
      day1
      day2
      day3
      day4
      day5
      day6
      day7
      deletedFlag
      facilityTask
      facilityTaskSeq
      facilityTask1
      frequency
      includeOnArrivalDay
      insertDate
      insertDate1
      insertUser
      insertUser1
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCodes
      marketDescription
      messageText
      moveupPenultimateYn
      numberOfDays
      organizationID
      primaryKeyID
      priority
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescriptions
      repMarketCodesDescription
      repSpecialRequestsDescription
      repVIPStatusesDescription
      roomCategory
      roomCategory1
      schedule
      specialRequestsCodes
      specialRequestsDescriptions
      startingOnDay
      supplyCode
      supplyDescription
      supplySequence
      updateDate
      updateDate1
      updateUser
      updateUser1
      vIPLevelsCode
      vIPLevelsDescription
    }
    houseKeepingEmployeePointsDetails {
      appUserId
      available
      building
      day1
      day2
      day3
      day4
      day5
      day6
      day7
      deletedFlag
      empName
      floor
      floorDesc
      housekeepingSectionCode
      inactiveDate
      jobCode
      phoneNo
      points
      pointsDate
      primaryKeyID
      repFloorDescription
      rnaInsertDate
      rnaUpdateDate
      sectionDesc
      status
      userName
    }
    houseKeepingDailyTaskDetails {
      applicationUser
      attendantCode
      attendantCodeName
      attendantDescription
      attendantInstructions
      attendantStatus
      autoGenerateFilters
      autoGenerateInd
      businessDate
      completedDateSTR
      dSI
      dailyTaskAttendantCode
      dailyTaskDSI
      dailyTaskJRNUpdateDate
      dailyTaskJRNUpdateDateAndTime
      dailyTaskLocationID
      dailyTaskOrganizationID
      dailyTaskResort
      deletedFlag
      facilityCredits
      floor
      housekeepingBreakoutJobId
      housekeepingTaskCodesList
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      lockedByUser
      lockedDate
      lockedYn
      miscellaneousCredits
      numRooms
      numberOfBuildings
      numberOfFloors
      numberOfGroups
      numberOfSections
      organizationID
      primaryKeyID
      property
      repFloorDescription
      rnaInsertDate
      rnaUpdateDate
      roomInstructions
      roomWithNoFloor
      roomWithNoGroup
      roomWithNoSection
      section
      simpleTaskYn
      systemDateSTR
      systemTimeSTR
      targetCredits
      taskCode
      taskCompletedDate
      taskCredits
      taskDate
      taskDateResortFormat
      taskInstructions
      taskSeqNumber
      taskSheet
      taskSheetDateSTR
      taskSheetNo
      taskSheetType
      totalFacilityCredits
      totalItemCredits
      totalMiscellaneousCredits
      totalSpecialCredits
      totalTasks
      totalTravellingBuildingCredits
      totalTravellingCredits
      totalTravellingFloorCredits
      totalTravellingGroupCredits
      totalTravellingSectionCredits
      travelingCredits
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
    dateCalendarDetails {
      dayDesc
      dayEndDate
      dayNoOfMonth
      dayNoOfQuarter
      dayNoOfWeek
      dayOfWeek
      dayOfYear
      dayTimespan
      daykey
      internalMonthkey
      internalYearkey
      isoWeekOfYear
      julianDaykey
      lastYearDaykey
      monthDsc
      monthEndDate
      monthKey
      monthName
      monthOfQuarter
      monthOfYear
      monthTimespan
      monthYrKey
      priorJulianDaykey
      priorMonthKey
      priorWeekKey
      priorYearDaykey
      priorYearKey
      priorYearMonthKey
      priorYearQuarterKey
      priorYearWeekKey
      quarterDsc
      quarterEndDate
      quarterKey
      quarterOfYear
      quarterTimespan
      weekDsc
      weekEndDate
      weekEndDsc
      weekEndKey
      weekEndMonthDsc
      weekEndMonthEndDate
      weekKey
      weekOfMonth
      weekOfYear
      weekTimespan
      yearDsc
      yearEndDate
      yearKey
      yearTimespan
    }
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

house_keeping_daily_task_room_details_schema = {
    'arrivalRoom': pl.Float64,
    'assignmentCode': pl.Utf8,
    'assignmentComments': pl.Utf8,
    'attendantRoomStatus': pl.Utf8,
    'attendantRoomStatusDesc': pl.Utf8,
    'autoGenerateFilters': pl.Utf8,
    'autoGenerateInd': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCreditFromSpecials': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cleanInd': pl.Float64,
    'creditFromSpecials': pl.Float64,
    'credits': pl.Float64,
    'creditsRem': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'depRoomInd': pl.Float64,
    'dirtyInd': pl.Float64,
    'facilityTaskCodes': pl.Utf8,
    'finalEndRoomStatus': pl.Utf8,
    'houseUseRooms': pl.Float64,
    'housekeepingBreakoutJobId': pl.Float64,
    'housekeepingExpectedServiceTime': pl.Utf8,
    'inspectedInd': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'lockedByUser': pl.Float64,
    'lockedDate': pl.Utf8,
    'maxCredits': pl.Float64,
    'oOORooms': pl.Float64,
    'oOSRooms': pl.Float64,
    'organizationID': pl.Float64,
    'pickupInd': pl.Float64,
    'primaryKeyID': pl.Float64,
    'priorityTask': pl.Utf8,
    'priorityTaskDescription': pl.Utf8,
    'property': pl.Utf8,
    'resvnRoom': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomInstrDetails': pl.Utf8,
    'roomInstructions': pl.Utf8,
    'roomMoved': pl.Utf8,
    'rooms': pl.Utf8,
    'serviceTime': pl.Utf8,
    'simpleTaskYn': pl.Utf8,
    'squareUnits': pl.Float64,
    'targetCredits': pl.Float64,
    'taskCompletedDate': pl.Utf8,
    'taskDate': pl.Utf8,
    'taskInstructions': pl.Utf8,
    'taskSeqNumber': pl.Float64,
    'taskSheet': pl.Float64,
    'taskSheetLocked': pl.Utf8,
    'taskSheetType': pl.Utf8,
    'travelingCredits': pl.Float64,
    'turndown': pl.Utf8,
    'turndownExtrasYn': pl.Utf8,
}

room_details_schema = {
    'accessible': pl.Utf8,
    'areaF': pl.Float64,
    'areaM': pl.Float64,
    'assignAssignStatus': pl.Utf8,
    'assignDate': pl.Utf8,
    'assignReasonDesc': pl.Utf8,
    'assignType': pl.Utf8,
    'assignemployeeid': pl.Float64,
    'assignreasonid': pl.Utf8,
    'bedType': pl.Utf8,
    'building': pl.Utf8,
    'buildingGroup': pl.Utf8,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMinimumRevenue': pl.Float64,
    'cRackRate': pl.Float64,
    'centralMeetingRoomType': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'combinationRoomYN': pl.Utf8,
    'comments': pl.Utf8,
    'componentRoom': pl.Utf8,
    'connectingRoomNumber': pl.Utf8,
    'dSI': pl.Float64,
    'daySection': pl.Utf8,
    'deductYN': pl.Utf8,
    'defatulratecodeid': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'deletedflag': pl.Utf8,
    'departureCredits': pl.Float64,
    'description': pl.Utf8,
    'diaryName': pl.Utf8,
    'diarydisplayflag': pl.Utf8,
    'discrepancy': pl.Utf8,
    'doors': pl.Utf8,
    'eveningSection': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'excludedEventTypes': pl.Utf8,
    'facing': pl.Utf8,
    'floor': pl.Utf8,
    'foPers': pl.Float64,
    'forceAlternateYn': pl.Utf8,
    'frontDeskLocation': pl.Utf8,
    'frontOfficeStatus': pl.Utf8,
    'fullUtilizationTime': pl.Float64,
    'genericYN': pl.Utf8,
    'handicapflag': pl.Utf8,
    'heightmaxF': pl.Float64,
    'heightmaxM': pl.Float64,
    'heightminF': pl.Float64,
    'heightminM': pl.Float64,
    'holdDateTime': pl.Utf8,
    'holdType': pl.Utf8,
    'holdUser': pl.Float64,
    'housekeepingAssignmentOrderBy': pl.Float64,
    'housekeepingInspDate': pl.Utf8,
    'housekeepingInspEmpId': pl.Utf8,
    'housekeepingPers': pl.Float64,
    'housekeepingStatus': pl.Utf8,
    'imageId': pl.Float64,
    'inactiveflag': pl.Utf8,
    'includeInStatisticsYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalTempflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyCode': pl.Utf8,
    'keyOptions': pl.Utf8,
    'lastCheckOutDate': pl.Utf8,
    'lastMeterReading': pl.Float64,
    'lengthF': pl.Float64,
    'lengthM': pl.Float64,
    'light': pl.Utf8,
    'locationID': pl.Utf8,
    'loudspeakersflag': pl.Utf8,
    'maxAdvance': pl.Float64,
    'maxCapacity': pl.Float64,
    'maxSharedGroups': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'measurement': pl.Utf8,
    'meetingRoomType': pl.Utf8,
    'meetingRoomYN': pl.Utf8,
    'meetingroomTypeDesc': pl.Utf8,
    'meetingroomTypeSeq': pl.Float64,
    'microphoneSocketTypes': pl.Utf8,
    'microphoneSockets': pl.Float64,
    'minAdvance': pl.Float64,
    'minCapacity': pl.Float64,
    'minimumRevenue': pl.Float64,
    'numberOfBeds': pl.Float64,
    'occupancyCondition': pl.Utf8,
    'occupantDiscrepancy': pl.Float64,
    'onlinePrintingYn': pl.Utf8,
    'orderBy2': pl.Float64,
    'orderBy3': pl.Float64,
    'orderBy4': pl.Float64,
    'orderBy5': pl.Float64,
    'organizationID': pl.Float64,
    'ovosGradeCode': pl.Utf8,
    'ovosUnitYn': pl.Utf8,
    'pcode': pl.Utf8,
    'personDiscrepancy': pl.Float64,
    'phoneNumber': pl.Utf8,
    'physicalNumberOfRooms': pl.Float64,
    'pickupCredits': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'publishedRateAmount': pl.Float64,
    'publishedRateCode': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rating': pl.Utf8,
    'repAssignReasonDescription': pl.Utf8,
    'repBedTypeDescription': pl.Utf8,
    'repMeetingroomTypeDescription': pl.Utf8,
    'repMeetingroomTypeSequence': pl.Float64,
    'repRoomClassSellSequence': pl.Float64,
    'repRoomFeaturesDescs': pl.Utf8,
    'repRoomStatusReason': pl.Utf8,
    'repRoomStatusReasonDescription': pl.Utf8,
    'returnStatus': pl.Utf8,
    'room': pl.Utf8,
    'roomAssignmentRating': pl.Float64,
    'roomCategoryBedtype': pl.Utf8,
    'roomCategoryDesc': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassCentralDescription': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomClassSequence': pl.Float64,
    'roomCondition': pl.Utf8,
    'roomFeatureDescription': pl.Utf8,
    'roomFeatures': pl.Utf8,
    'roomNumber': pl.Utf8,
    'roomParity': pl.Utf8,
    'roomStatus': pl.Utf8,
    'roomStatusDescription': pl.Utf8,
    'roomStatusFromDate': pl.Utf8,
    'roomStatusReason': pl.Utf8,
    'roomStatusReasonDesc': pl.Utf8,
    'roomStatusRemarks': pl.Utf8,
    'roomStatusToDate': pl.Utf8,
    'roomType': pl.Utf8,
    'roomUseCount': pl.Float64,
    'roomcategoryid': pl.Utf8,
    'roomclassid': pl.Utf8,
    'roomid': pl.Utf8,
    'roomstatusreasonid': pl.Utf8,
    'sequence': pl.Float64,
    'serviceStatus': pl.Utf8,
    'setupNotes': pl.Utf8,
    'shareableflag': pl.Utf8,
    'smoking': pl.Utf8,
    'smokingPreferences': pl.Utf8,
    'squareUnits': pl.Float64,
    'stayoverCredits': pl.Float64,
    'suiteType': pl.Utf8,
    'suiteYN': pl.Utf8,
    'supplement': pl.Utf8,
    'tempFlag': pl.Utf8,
    'translationboothNum': pl.Float64,
    'turnDown': pl.Utf8,
    'turndownCredits': pl.Float64,
    'tvRadioSockets': pl.Float64,
    'unit': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'visibleOnWebYn': pl.Utf8,
    'webBookingYn': pl.Utf8,
    'weightF': pl.Float64,
    'weightM': pl.Float64,
    'widthF': pl.Float64,
    'widthM': pl.Float64,
}

house_keeping_reservation_guest_details_schema = {
    'guestProfileID': pl.Float64,
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountsourceDesc': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressId': pl.Float64,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allResorts': pl.Utf8,
    'alternateEnvelopeGreeting': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'autoEnrollMemberYN': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessSegmentDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralBusinessSegmentDescription': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralGuestTitleCode': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralMailingActionCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'comments': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodes': pl.Utf8,
    'commissionCurrencyId': pl.Utf8,
    'commissionid': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'competitionDesc': pl.Utf8,
    'contactYN': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corpTypeDesc': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'debtorName': pl.Utf8,
    'decimalPositions': pl.Float64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYN': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalDisplayName': pl.Utf8,
    'externalFirstName': pl.Utf8,
    'externalId': pl.Utf8,
    'externalName': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fMembershipType': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'firstName': pl.Utf8,
    'firstNameAlternate': pl.Utf8,
    'firstNameIncognito': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestCountry': pl.Utf8,
    'guestCurrencyCode': pl.Utf8,
    'guestLanguageCode': pl.Utf8,
    'guestLastName': pl.Utf8,
    'guestMiddleName': pl.Utf8,
    'guestNameSuffix': pl.Utf8,
    'guestPrivilegeYN': pl.Utf8,
    'guestTitleCode': pl.Utf8,
    'hasRequestedMailYN': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryDesc': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDesc': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastGroup': pl.Utf8,
    'lastNameAlternate': pl.Utf8,
    'lastNameIncognito': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRateCode': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastRoomProperty': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYN': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Float64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Float64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'priorityDesc': pl.Utf8,
    'privacyFlagYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'requestType': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'roomsPotentialDesc': pl.Utf8,
    'sMSYN': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDesc': pl.Utf8,
    'scopeDesc': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDescription': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDesc': pl.Utf8,
    'thirdPartyYN': pl.Utf8,
    'titleAlternate': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalStay': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'tracecodeDesc': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
    'uDFC01': pl.Utf8,
    'uDFC02': pl.Utf8,
    'uDFC03': pl.Utf8,
    'uDFC04': pl.Utf8,
    'uDFC05': pl.Utf8,
    'uDFC06': pl.Utf8,
    'uDFC07': pl.Utf8,
    'uDFC08': pl.Utf8,
    'uDFC09': pl.Utf8,
    'uDFC10': pl.Utf8,
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Utf8,
    'uploadDate': pl.Utf8,
    'vIPCode': pl.Utf8,
    'vIPDescription': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xdisplayName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}

house_keeping_reservation_details_schema = {
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'adultSTR': pl.Utf8,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateSTR': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivalTimeSTR': pl.Utf8,
    'autoPostAmount': pl.Float64,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'baseRateAmount': pl.Float64,
    'basedOnRule': pl.Utf8,
    'beginDate': pl.Utf8,
    'billingContactId': pl.Float64,
    'blockCode': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockID': pl.Float64,
    'blockResort': pl.Utf8,
    'bookedRoomCategory': pl.Utf8,
    'businessDate': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmount': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancellationCode': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationNo': pl.Float64,
    'cancellationReasonDesc': pl.Utf8,
    'childSTR': pl.Utf8,
    'children': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionableYn': pl.Utf8,
    'companyId': pl.Float64,
    'confirmationNumber': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Float64,
    'dayUseYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depDateSTR': pl.Utf8,
    'depTimeSTR': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureTime': pl.Utf8,
    'discountAmt': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReasonCode': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveYn': pl.Utf8,
    'dueOutYn': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'externalReference': pl.Utf8,
    'extraBeds': pl.Float64,
    'fixedRateYn': pl.Utf8,
    'grossRateAmt': pl.Float64,
    'groupId': pl.Float64,
    'guaranteeCode': pl.Utf8,
    'guestName': pl.Utf8,
    'guestNameFirstLastInitial': pl.Utf8,
    'housekeepingExpectedServiceTime': pl.Utf8,
    'houseuseYN': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalBlockId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastShareCalculation': pl.Utf8,
    'lengthOfStay': pl.Float64,
    'marketCode': pl.Utf8,
    'membershipLevel': pl.Utf8,
    'membershipPoints': pl.Float64,
    'membershipType': pl.Utf8,
    'nameId': pl.Float64,
    'netRoomAmt': pl.Float64,
    'organizationID': pl.Float64,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'packageAmt': pl.Float64,
    'physicalQuantity': pl.Float64,
    'physicalRooms': pl.Float64,
    'pkgTax': pl.Float64,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rESVJRNUpdateDTTM': pl.Utf8,
    'rESVJRNUpdateDate': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rdAdults': pl.Float64,
    'rdBaseRateAmount': pl.Float64,
    'rdCBaseRateAmount': pl.Float64,
    'rdCExchangeDate': pl.Utf8,
    'rdCExchangeRate': pl.Float64,
    'rdChildren': pl.Float64,
    'rdDmlSeqNumber': pl.Float64,
    'rdInsertActionInstanceId': pl.Float64,
    'rdInsertDate': pl.Utf8,
    'rdInsertUser': pl.Float64,
    'rdUpdateDate': pl.Utf8,
    'rdUpdateUser': pl.Float64,
    'referralYn': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationStatus': pl.Utf8,
    'resvCleaningTime': pl.Utf8,
    'resvDailyElSequence': pl.Float64,
    'resvItems': pl.Utf8,
    'resvRoomFeatures': pl.Utf8,
    'resvRoomStatus': pl.Utf8,
    'resvSpecials': pl.Utf8,
    'resvStatus': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomAssignment': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomTax': pl.Float64,
    'scheduledMoveDatetime': pl.Utf8,
    'scheduledMoveOutRoom': pl.Utf8,
    'scheduledMoveStatus': pl.Utf8,
    'scheduledMoveTime': pl.Utf8,
    'shareAmount': pl.Float64,
    'shareAmountOriginal': pl.Float64,
    'sharePaymentType': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'sharePriority': pl.Float64,
    'sourceId': pl.Float64,
    'traces': pl.Utf8,
    'travelAgentId': pl.Float64,
    'truncActualCheckInDate': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turnDownStatus': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'upsellCharge': pl.Float64,
}

house_keeping_tasks_details_schema = {
    'autoAssignedYn': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'colors': pl.Utf8,
    'creditWeighting': pl.Float64,
    'creditsDeparture': pl.Float64,
    'customizableYn': pl.Utf8,
    'departureRoomDefaultTask': pl.Utf8,
    'guestRequestedTask': pl.Utf8,
    'housekeepingTaskCredits': pl.Float64,
    'inactive': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'linenChange': pl.Utf8,
    'room': pl.Utf8,
    'sequence': pl.Float64,
    'taskAssignDate': pl.Utf8,
    'taskCode': pl.Utf8,
    'taskCredits': pl.Float64,
    'taskDSI': pl.Float64,
    'taskDeletedFlag': pl.Utf8,
    'taskDescription': pl.Utf8,
    'taskFrequency': pl.Float64,
    'taskInsertDate': pl.Utf8,
    'taskInsertUser': pl.Float64,
    'taskInstructions': pl.Utf8,
    'taskJRNUpdateDate': pl.Utf8,
    'taskJRNUpdateDateAndTime': pl.Utf8,
    'taskLocationID': pl.Utf8,
    'taskOrganizationID': pl.Float64,
    'taskPrimaryKeyID': pl.Float64,
    'taskPriority': pl.Float64,
    'taskProperty': pl.Utf8,
    'taskRNAInsertDate': pl.Utf8,
    'taskRNAUpdateDate': pl.Utf8,
    'taskSeqNumber': pl.Float64,
    'taskUpdateDate': pl.Utf8,
    'taskUpdateUser': pl.Float64,
    'unitOfFrequency': pl.Utf8,
}

house_keeping_tasks_room_category_facility_codes_details_schema = {
    'credits': pl.Float64,
    'customizePromptYn': pl.Utf8,
    'dSI': pl.Float64,
    'dayOfTheWeekSchedule': pl.Utf8,
    'day1': pl.Utf8,
    'day2': pl.Utf8,
    'day3': pl.Utf8,
    'day4': pl.Utf8,
    'day5': pl.Utf8,
    'day6': pl.Utf8,
    'day7': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'facilityTask': pl.Utf8,
    'facilityTaskSeq': pl.Float64,
    'facilityTask1': pl.Utf8,
    'frequency': pl.Utf8,
    'includeOnArrivalDay': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertDate1': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUser1': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCodes': pl.Utf8,
    'marketDescription': pl.Utf8,
    'messageText': pl.Utf8,
    'moveupPenultimateYn': pl.Utf8,
    'numberOfDays': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'priority': pl.Float64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'repMarketCodesDescription': pl.Utf8,
    'repSpecialRequestsDescription': pl.Utf8,
    'repVIPStatusesDescription': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomCategory1': pl.Utf8,
    'schedule': pl.Utf8,
    'specialRequestsCodes': pl.Utf8,
    'specialRequestsDescriptions': pl.Utf8,
    'startingOnDay': pl.Float64,
    'supplyCode': pl.Utf8,
    'supplyDescription': pl.Utf8,
    'supplySequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateDate1': pl.Utf8,
    'updateUser': pl.Float64,
    'updateUser1': pl.Float64,
    'vIPLevelsCode': pl.Utf8,
    'vIPLevelsDescription': pl.Utf8,
}

house_keeping_employee_points_details_schema = {
    'appUserId': pl.Float64,
    'available': pl.Utf8,
    'building': pl.Utf8,
    'day1': pl.Utf8,
    'day2': pl.Utf8,
    'day3': pl.Utf8,
    'day4': pl.Utf8,
    'day5': pl.Utf8,
    'day6': pl.Utf8,
    'day7': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'empName': pl.Utf8,
    'floor': pl.Utf8,
    'floorDesc': pl.Utf8,
    'housekeepingSectionCode': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'jobCode': pl.Utf8,
    'phoneNo': pl.Utf8,
    'points': pl.Float64,
    'pointsDate': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'repFloorDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sectionDesc': pl.Utf8,
    'status': pl.Utf8,
    'userName': pl.Utf8,
}

house_keeping_daily_task_details_schema = {
    'applicationUser': pl.Utf8,
    'attendantCode': pl.Utf8,
    'attendantCodeName': pl.Utf8,
    'attendantDescription': pl.Utf8,
    'attendantInstructions': pl.Utf8,
    'attendantStatus': pl.Utf8,
    'autoGenerateFilters': pl.Utf8,
    'autoGenerateInd': pl.Utf8,
    'businessDate': pl.Utf8,
    'completedDateSTR': pl.Utf8,
    'dSI': pl.Float64,
    'dailyTaskAttendantCode': pl.Utf8,
    'dailyTaskDSI': pl.Float64,
    'dailyTaskJRNUpdateDate': pl.Utf8,
    'dailyTaskJRNUpdateDateAndTime': pl.Utf8,
    'dailyTaskLocationID': pl.Utf8,
    'dailyTaskOrganizationID': pl.Float64,
    'dailyTaskResort': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'facilityCredits': pl.Float64,
    'floor': pl.Utf8,
    'housekeepingBreakoutJobId': pl.Float64,
    'housekeepingTaskCodesList': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'lockedByUser': pl.Float64,
    'lockedDate': pl.Utf8,
    'lockedYn': pl.Utf8,
    'miscellaneousCredits': pl.Float64,
    'numRooms': pl.Float64,
    'numberOfBuildings': pl.Float64,
    'numberOfFloors': pl.Float64,
    'numberOfGroups': pl.Float64,
    'numberOfSections': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'repFloorDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomInstructions': pl.Utf8,
    'roomWithNoFloor': pl.Float64,
    'roomWithNoGroup': pl.Float64,
    'roomWithNoSection': pl.Float64,
    'section': pl.Utf8,
    'simpleTaskYn': pl.Utf8,
    'systemDateSTR': pl.Utf8,
    'systemTimeSTR': pl.Utf8,
    'targetCredits': pl.Float64,
    'taskCode': pl.Utf8,
    'taskCompletedDate': pl.Utf8,
    'taskCredits': pl.Float64,
    'taskDate': pl.Utf8,
    'taskDateResortFormat': pl.Utf8,
    'taskInstructions': pl.Utf8,
    'taskSeqNumber': pl.Float64,
    'taskSheet': pl.Utf8,
    'taskSheetDateSTR': pl.Utf8,
    'taskSheetNo': pl.Float64,
    'taskSheetType': pl.Utf8,
    'totalFacilityCredits': pl.Float64,
    'totalItemCredits': pl.Float64,
    'totalMiscellaneousCredits': pl.Float64,
    'totalSpecialCredits': pl.Float64,
    'totalTasks': pl.Utf8,
    'totalTravellingBuildingCredits': pl.Float64,
    'totalTravellingCredits': pl.Float64,
    'totalTravellingFloorCredits': pl.Float64,
    'totalTravellingGroupCredits': pl.Float64,
    'totalTravellingSectionCredits': pl.Float64,
    'travelingCredits': pl.Float64,
}

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

date_calendar_details_schema = {
    'dayDesc': pl.Utf8,
    'dayEndDate': pl.Utf8,
    'dayNoOfMonth': pl.Float64,
    'dayNoOfQuarter': pl.Float64,
    'dayNoOfWeek': pl.Utf8,
    'dayOfWeek': pl.Utf8,
    'dayOfYear': pl.Float64,
    'dayTimespan': pl.Float64,
    'daykey': pl.Utf8,
    'internalMonthkey': pl.Float64,
    'internalYearkey': pl.Float64,
    'isoWeekOfYear': pl.Utf8,
    'julianDaykey': pl.Utf8,
    'lastYearDaykey': pl.Utf8,
    'monthDsc': pl.Utf8,
    'monthEndDate': pl.Utf8,
    'monthKey': pl.Utf8,
    'monthName': pl.Utf8,
    'monthOfQuarter': pl.Float64,
    'monthOfYear': pl.Float64,
    'monthTimespan': pl.Float64,
    'monthYrKey': pl.Utf8,
    'priorJulianDaykey': pl.Utf8,
    'priorMonthKey': pl.Utf8,
    'priorWeekKey': pl.Utf8,
    'priorYearDaykey': pl.Utf8,
    'priorYearKey': pl.Utf8,
    'priorYearMonthKey': pl.Utf8,
    'priorYearQuarterKey': pl.Utf8,
    'priorYearWeekKey': pl.Utf8,
    'quarterDsc': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterKey': pl.Utf8,
    'quarterOfYear': pl.Utf8,
    'quarterTimespan': pl.Float64,
    'weekDsc': pl.Utf8,
    'weekEndDate': pl.Utf8,
    'weekEndDsc': pl.Utf8,
    'weekEndKey': pl.Utf8,
    'weekEndMonthDsc': pl.Utf8,
    'weekEndMonthEndDate': pl.Utf8,
    'weekKey': pl.Utf8,
    'weekOfMonth': pl.Utf8,
    'weekOfYear': pl.Utf8,
    'weekTimespan': pl.Float64,
    'yearDsc': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearKey': pl.Utf8,
    'yearTimespan': pl.Float64,
}

```