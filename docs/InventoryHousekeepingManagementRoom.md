# InventoryHousekeepingManagementRoom
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | houseKeepingDailyTaskRoomDetails | [`InventoryHousekeepingManagementRoomHouseKeepingDailyTaskRoomDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingdailytaskroomdetailstype) | House Keeping Daily Task Room |
| 2 | roomDetails | [`InventoryHousekeepingManagementRoomRoomDetailsType`](#inventoryhousekeepingmanagementroomroomdetailstype) | Room Details |
| 3 | houseKeepingReservationGuestDetails | [`InventoryHousekeepingManagementRoomHouseKeepingReservationGuestDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingreservationguestdetailstype) | HK Reservation and Guest |
| 4 | houseKeepingReservationDetails | [`InventoryHousekeepingManagementRoomHouseKeepingReservationDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingreservationdetailstype) | HK Reservation and Guest |
| 5 | houseKeepingTasksDetails | [`InventoryHousekeepingManagementRoomHouseKeepingTasksDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingtasksdetailstype) | HK Task and Facility Codes |
| 6 | houseKeepingTasksRoomCategoryFacilityCodesDetails | [`InventoryHousekeepingManagementRoomHouseKeepingTasksRoomCategoryFacilityCodesDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingtasksroomcategoryfacilitycodesdetailstype) | HK Task and Facility Codes |
| 7 | houseKeepingEmployeePointsDetails | [`InventoryHousekeepingManagementRoomHouseKeepingEmployeePointsDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingemployeepointsdetailstype) | HK Task and Employee Points |
| 8 | houseKeepingDailyTaskDetails | [`InventoryHousekeepingManagementRoomHouseKeepingDailyTaskDetailsType`](#inventoryhousekeepingmanagementroomhousekeepingdailytaskdetailstype) | HK Task and Employee Points |
| 9 | propertyPropertyDetails | [`InventoryHousekeepingManagementRoomPropertyPropertyDetailsType`](#inventoryhousekeepingmanagementroompropertypropertydetailstype) | Resort Details |
| 10 | dateCalendarDetails | [`InventoryHousekeepingManagementRoomDateCalendarDetailsType`](#inventoryhousekeepingmanagementroomdatecalendardetailstype) | Date Calendar |
| 11 | inventoryHousekeepingManagementRoomRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingDailyTaskRoomDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrivalRoom | `Float` | Arrival Room |
| 2 | assignmentCode | `String` | Code indicating why this room was assigned to this task sheet. |
| 3 | assignmentComments | `String` | Additional comments why this room was assigned to this task sheet. |
| 4 | attendantRoomStatus | `String` | Attendant Room Status |
| 5 | attendantRoomStatusDesc | `String` | Attendant Room Status Desc |
| 6 | autoGenerateFilters | `String` | Auto generated filters. |
| 7 | autoGenerateInd | `String` | Indicates if task has been automatically generated. |
| 8 | businessDate | `Date` | Business date. |
| 9 | cCreditFromSpecials | `Float` | Central Credit From Specials |
| 10 | cExchangeDate | `Date` | Central Xchange Date |
| 11 | cExchangeRate | `Float` | Central Xchange Rate |
| 12 | cleanInd | `Float` | Clean Individual |
| 13 | creditFromSpecials | `Float` | Credits based on Specials attached to the reservation. |
| 14 | credits | `Float` | Credits |
| 15 | creditsRem | `String` | Remarks for the credits |
| 16 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 17 | deletedFlag | `String` | Deleted Flag |
| 18 | depRoomInd | `Float` | Dep Room Individual |
| 19 | dirtyInd | `Float` | Dirty Individual |
| 20 | facilityTaskCodes | `String` | Facility Task Codes |
| 21 | finalEndRoomStatus | `String` | Final End Room Status |
| 22 | houseUseRooms | `Float` | House Use Rooms |
| 23 | housekeepingBreakoutJobId | `Float` | Hk Breakout Job ID |
| 24 | housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| 25 | inspectedInd | `Float` | Inspected Individual |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | locationID | `String` | Internal ID to uniquely identify the Property |
| 29 | lockedByUser | `Float` | User ID who locked this tasksheet. |
| 30 | lockedDate | `Date` | Date and Time that this task sheet was locked. |
| 31 | maxCredits | `Float` | Credits assigned for a particular task. |
| 32 | oOORooms | `Float` | OOO Rooms |
| 33 | oOSRooms | `Float` | OOS Rooms |
| 34 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 35 | pickupInd | `Float` | Pickup Individual |
| 36 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 37 | priorityTask | `String` | Priority Task |
| 38 | priorityTaskDescription | `String` | Priority Task Description |
| 39 | property | `String` | Code to uniquely identify the Property |
| 40 | resvnRoom | `String` | Component Suite / Room number that is booked for the reservation that currently occupies the physical room. |
| 41 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 42 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 43 | roomInstrDetails | `String` | Room Instr Details |
| 44 | roomInstructions | `String` | Room Instructions |
| 45 | roomMoved | `String` | Flag to indicate if this task was assigned during automatic breakout. |
| 46 | rooms | `String` | Rooms |
| 47 | serviceTime | `String` | Turndown service time |
| 48 | simpleTaskYn | `String` | This indicates whether the task is simple or not |
| 49 | squareUnits | `Float` | Square Units |
| 50 | targetCredits | `Float` | Target Credits |
| 51 | taskCompletedDate | `Date` | Date on which task is completed. |
| 52 | taskDate | `Date` | Breakout Date. |
| 53 | taskInstructions | `String` | Any specific instructions for the task. |
| 54 | taskSeqNumber | `Float` | Task Sequence No |
| 55 | taskSheet | `Float` | task sheet associated with this room on business_date |
| 56 | taskSheetLocked | `String` | Task Sheet Locked |
| 57 | taskSheetType | `String` | Indicates the task sheet type possible values: [A]utomatic [F]loating Sheet [N]o Services required [M]anually created |
| 58 | travelingCredits | `Float` | Total traveling credits for this task sheet based on change of floors |
| 59 | turndown | `String` | Turndown service Y/N |
| 60 | turndownExtrasYn | `String` | Indicates if extra turndown services are applicable. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomRoomDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessible | `String` | Accessible |
| 2 | areaF | `Float` | Area in sqft |
| 3 | areaM | `Float` | Area in sqm |
| 4 | assignAssignStatus | `String` | Assign Assign Status |
| 5 | assignDate | `DateTime` | Room assignment date |
| 6 | assignReasonDesc | `String` | Assign Reason Desc |
| 7 | assignType | `String` | Assign Type |
| 8 | assignemployeeid | `Float` | Assignemployeeid |
| 9 | assignreasonid | `String` | Assignreasonid |
| 10 | bedType | `String` | Bed Type |
| 11 | building | `String` | Building |
| 12 | buildingGroup | `String` | Building Group |
| 13 | businessDate | `Date` | Business Date |
| 14 | cExchangeDate | `Date` | Central Xchange Date |
| 15 | cExchangeRate | `Float` | Central Xchange Rate |
| 16 | cMinimumRevenue | `Float` | Central Minimum Revenue |
| 17 | cRackRate | `Float` | Central Rack Rate |
| 18 | centralMeetingRoomType | `String` | Central Meeting Room Type |
| 19 | centralRoomClass | `String` | Central Room Class |
| 20 | centralRoomType | `String` | Central Room Type |
| 21 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 22 | combinationRoomYN | `String` | Combination Room YN |
| 23 | comments | `String` | Comments |
| 24 | componentRoom | `String` | Suite component room numbers |
| 25 | connectingRoomNumber | `String` | Connecting Room Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | daySection | `String` | Indicates the section to which employee belongs. |
| 28 | deductYN | `String` | Deduct YN |
| 29 | defatulratecodeid | `String` | Defatulratecodeid |
| 30 | defaultRateDesc | `String` | Default Rate Description |
| 31 | deletedflag | `String` | Deleted Flag |
| 32 | departureCredits | `Float` | Credits associated with the task after departure. |
| 33 | description | `String` | Description |
| 34 | diaryName | `String` | Diary name to show room in |
| 35 | diarydisplayflag | `String` | Diarydisplayflag |
| 36 | discrepancy | `String` | Discrepancy |
| 37 | doors | `String` | Number of doors |
| 38 | eveningSection | `String` | Section the room belongs to for evening housekeeping |
| 39 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 40 | excludedEventTypes | `String` | Stores event types which do not require alternate spaces. |
| 41 | facing | `String` | Direction room faces |
| 42 | floor | `String` | Floor |
| 43 | foPers | `Float` | The persons staying in room according to Front office. |
| 44 | forceAlternateYn | `String` | Defines if the function space needs an alternate space when booked. |
| 45 | frontDeskLocation | `String` | The front desk location this room should check in to. |
| 46 | frontOfficeStatus | `String` | Front Office Status of the room i.e.: Vacant or Occupied. |
| 47 | fullUtilizationTime | `Float` | Minutes occupied that define the room as 100% utilized. Maximum is 1440 minutes. |
| 48 | genericYN | `String` | Generic YN |
| 49 | handicapflag | `String` | Handicapflag |
| 50 | heightmaxF | `Float` | Max Height in ft |
| 51 | heightmaxM | `Float` | Max Height in m |
| 52 | heightminF | `Float` | Minumum heigth of room (feet) |
| 53 | heightminM | `Float` | Minumum heigth of room (meters) |
| 54 | holdDateTime | `DateTime` | Date and time when room will be released from hold. |
| 55 | holdType | `String` | Hold type from resort_assignment_reasons table. |
| 56 | holdUser | `Float` | User that is holding the room. |
| 57 | housekeepingAssignmentOrderBy | `Float` | Sequence for automatically generated task assignment. |
| 58 | housekeepingInspDate | `Date` | Housekeeping Inspected date |
| 59 | housekeepingInspEmpId | `String` | Houskeeping inspected employee id |
| 60 | housekeepingPers | `Float` | The number of persons staying in the room according to housekeeping |
| 61 | housekeepingStatus | `String` | The status of this room according to housekeeping |
| 62 | imageId | `Float` | Image ID |
| 63 | inactiveflag | `String` | Inactive Flag |
| 64 | includeInStatisticsYN | `String` | Include in Statistics YN |
| 65 | insertDate | `DateTime` | Insert Date |
| 66 | insertUser | `Float` | Insert User |
| 67 | internalTempflag | `String` | Tempflag |
| 68 | jRNUpdateDate | `Date` | JRN Update Date |
| 69 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 70 | keyCode | `String` | The current key code for this room.  Used to create keys for a room. |
| 71 | keyOptions | `String` | Privileges available for this key |
| 72 | lastCheckOutDate | `Date` | The last check out date for this room. |
| 73 | lastMeterReading | `Float` | The last meter reading for condos that track electrical usage of rented rooms. |
| 74 | lengthF | `Float` | Length (feet) |
| 75 | lengthM | `Float` | Length (meters) |
| 76 | light | `String` | Number of lights in the room |
| 77 | locationID | `String` | Internal ID to uniquely identify the Property |
| 78 | loudspeakersflag | `String` | Loudspeakersflag |
| 79 | maxAdvance | `Float` | Maximum number of days before the catering event date  that the space can be booked on the web. |
| 80 | maxCapacity | `Float` | Function Space Maximum Capacity. |
| 81 | maxSharedGroups | `Float` | Maximum number of groups for a Shared function space allowed. |
| 82 | maximumOccupancy | `Float` | Maximum Occupancy |
| 83 | measurement | `String` | The unit of measurement for this square units (IE: Feet Meters etc) |
| 84 | meetingRoomType | `String` | Type of meeting room |
| 85 | meetingRoomYN | `String` | Meeting Room YN |
| 86 | meetingroomTypeDesc | `String` | Meetingroom Type Description |
| 87 | meetingroomTypeSeq | `Float` | Meetingroom Type Sequence |
| 88 | microphoneSocketTypes | `String` | Type of microphone sockets |
| 89 | microphoneSockets | `Float` | Number of microphone sockets |
| 90 | minAdvance | `Float` | Minimum number of days before the catering event date that the space can be booked on the web. |
| 91 | minCapacity | `Float` | Minimum Capacity |
| 92 | minimumRevenue | `Float` | Minimum Revenue |
| 93 | numberOfBeds | `Float` | Specifies the number of beds in this room. |
| 94 | occupancyCondition | `String` | Current room condition updated daily.(ie StayOverDueOutExpected etc) |
| 95 | occupantDiscrepancy | `Float` | Discrepancy between front desk and housekeeping |
| 96 | onlinePrintingYn | `String` | Used for pseudo rooms. If Y then this pseudo room will be included in Online Printing for reservation changes. |
| 97 | orderBy2 | `Float` | Display sequence 2 |
| 98 | orderBy3 | `Float` | Display sequence 3 |
| 99 | orderBy4 | `Float` | Display sequence 4 |
| 100 | orderBy5 | `Float` | Display sequence 5 |
| 101 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 102 | ovosGradeCode | `String` | Stores a Grade associated with a unit to determine the room display order in Room Assignment and Room Plan screens. |
| 103 | ovosUnitYn | `String` | Room can be OVOS unit. |
| 104 | pcode | `String` | Not used |
| 105 | personDiscrepancy | `Float` | Person discrepancy between front desk and houskeeping |
| 106 | phoneNumber | `String` | Phone Number |
| 107 | physicalNumberOfRooms | `Float` | Physical Number of Rooms |
| 108 | pickupCredits | `Float` | Houskeeping credits for cleaning room in pickup status |
| 109 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 110 | property | `String` | Code to uniquely identify the Property |
| 111 | pseudoRoomYN | `String` | Pseudo Room YN |
| 112 | publishedRateAmount | `Float` | Default rate for the room |
| 113 | publishedRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 114 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 115 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 116 | rateCode | `String` | Rate Code |
| 117 | rating | `String` | Rating |
| 118 | repAssignReasonDescription | `String` | Reporting Assign Reason Desc |
| 119 | repBedTypeDescription | `String` | Reporting Bed Type Desc |
| 120 | repMeetingroomTypeDescription | `String` | Reporting Meetingroom Type Desc |
| 121 | repMeetingroomTypeSequence | `Float` | Reporting Meetingroom Type Seq |
| 122 | repRoomClassSellSequence | `Float` | Reporting Room Class Sell Seq |
| 123 | repRoomFeaturesDescs | `String` | Reporting Room Features Descs |
| 124 | repRoomStatusReason | `String` | Reporting Room Status Reason |
| 125 | repRoomStatusReasonDescription | `String` | Reporting Room Status Reason Desc |
| 126 | returnStatus | `String` | Room return status |
| 127 | room | `String` | Room |
| 128 | roomAssignmentRating | `Float` | Room Assignment Rating. |
| 129 | roomCategoryBedtype | `String` | Room Category Bedtype |
| 130 | roomCategoryDesc | `String` | Room Category Desc |
| 131 | roomClass | `String` | Room Class |
| 132 | roomClassCentralDescription | `String` | Room Class Central Description |
| 133 | roomClassDescription | `String` | Room Class Description |
| 134 | roomClassSequence | `Float` | Room Class Sequence |
| 135 | roomCondition | `String` | Room Condition |
| 136 | roomFeatureDescription | `String` | Room Feature Description |
| 137 | roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| 138 | roomNumber | `String` | Room Number |
| 139 | roomParity | `String` | Room Parity |
| 140 | roomStatus | `String` | Room Status |
| 141 | roomStatusDescription | `String` | Room Status Description |
| 142 | roomStatusFromDate | `Date` | The date as of which the room_status is valid. |
| 143 | roomStatusReason | `String` | Room Status Reason |
| 144 | roomStatusReasonDesc | `String` | Room Status Reason Description |
| 145 | roomStatusRemarks | `String` | Room status remarks |
| 146 | roomStatusToDate | `Date` | The date till which the room_status is valid.(Used during OO and OS status of rooms ) |
| 147 | roomType | `String` | Room Type |
| 148 | roomUseCount | `Float` | Total Count of the number of days the room was used. |
| 149 | roomcategoryid | `String` | Roomcategoryid |
| 150 | roomclassid | `String` | Roomclassid |
| 151 | roomid | `String` | Roomid |
| 152 | roomstatusreasonid | `String` | Roomstatusreasonid |
| 153 | sequence | `Float` | Sequence |
| 154 | serviceStatus | `String` | Current guest service status code for this room. Example: Service status can be DND (Do Not Disturb) or MUP (Make Up Room) |
| 155 | setupNotes | `String` | Notes for the setup of the room |
| 156 | shareableflag | `String` | Shareableflag |
| 157 | smoking | `String` | Smoking |
| 158 | smokingPreferences | `String` | Smoking Preferences |
| 159 | squareUnits | `Float` | The square units for this room (IE: if a condo in the US likely the square feet of this room) |
| 160 | stayoverCredits | `Float` | Stayover Credits |
| 161 | suiteType | `String` | Standard or Suite |
| 162 | suiteYN | `String` | Suite YN |
| 163 | supplement | `String` | Supplement |
| 164 | tempFlag | `String` | Temp Flag |
| 165 | translationboothNum | `Float` | Number for the booth |
| 166 | turnDown | `String` | Turn Down |
| 167 | turndownCredits | `Float` | Houskeeping credits for Turndown. |
| 168 | tvRadioSockets | `Float` | Number of TV or radio sockets |
| 169 | unit | `String` | Unit |
| 170 | updateDate | `DateTime` | Update Date |
| 171 | updateUser | `Float` | Update User |
| 172 | visibleOnWebYn | `String` | Flag makes a Function Space visible on the web. |
| 173 | webBookingYn | `String` | Web Booking Y/N |
| 174 | weightF | `Float` | Room weigth (feet) |
| 175 | weightM | `Float` | Room weigth (meters) |
| 176 | widthF | `Float` | Width (feet) |
| 177 | widthM | `Float` | Width (meters) |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingReservationGuestDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | guestProfileID | `Float` | The primary key for this table. |
| 2 | aRNumber | `String` | Account number. |
| 3 | aRNumberCentral | `String` | Account Receivable No. of this profile. |
| 4 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 5 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 6 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 7 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 8 | accountBillingContact | `String` | Billing contact person in company. |
| 9 | accountSource | `String` | Used in S&.C Module. |
| 10 | accountType | `String` | Account Type of this Profile |
| 11 | accountTypeDescription | `String` | The description of this value. |
| 12 | accountsourceDesc | `String` | The description of this value. |
| 13 | actionCode | `String` | Mailing action codes. |
| 14 | activeYN | `String` | Profile is active or not. |
| 15 | address1 | `String` | The first line of street address. |
| 16 | address2 | `String` | The second line of street address. |
| 17 | address3 | `String` | The third line of street address. |
| 18 | address4 | `String` | The fourth line of street address. |
| 19 | addressId | `Float` | The primary key for this table. |
| 20 | addressLangCodeDesc | `String` | Description for each language code. |
| 21 | addressLanguageCode | `String` | Address Language Code |
| 22 | addressType | `String` | The type of address. |
| 23 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 24 | allResorts | `String` | All Resorts |
| 25 | alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&.C |
| 26 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 27 | alternateLanguageDescription | `String` | Description for each language code. |
| 28 | alternateSalutation | `String` | Alternate Salutation |
| 29 | autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| 30 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 31 | billingCode | `String` | The billing code for this name record. |
| 32 | billingInstruction | `String` | Billing Instruction |
| 33 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 34 | birthCountry | `String` | Country of Birth |
| 35 | birthDate | `Date` | Date of Birth of the Individual Profiles. |
| 36 | birthDateStr | `String` | Stores the encrypted birth date. |
| 37 | birthPlace | `String` | Place of Birth |
| 38 | blMsg | `String` | Any Message for the Restricted profile. |
| 39 | businessSegment | `String` | Used in S&.C Module. |
| 40 | businessSegmentDescription | `String` | The description of this value. |
| 41 | businessTitle | `String` | The business title for this individual. |
| 42 | cExchangeDate | `Date` | Central Xchange Date |
| 43 | cExchangeRate | `Float` | Central Xchange Rate |
| 44 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 45 | cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| 46 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 47 | centralAccountType | `String` | Central Account Type |
| 48 | centralBusinessSegment | `String` | Central Business Segment |
| 49 | centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| 50 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 51 | centralDefaultKeyword | `String` | The keyword to search on. |
| 52 | centralGuestTitleCode | `String` | Central Guest Title Code |
| 53 | centralInactiveReason | `String` | Central Inactive Reason |
| 54 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 55 | centralMailActionDescription | `String` | Central Mail Action Description |
| 56 | centralMailingActionCode | `String` | Central Mailing Action Code |
| 57 | centralPriority | `String` | Central Priority |
| 58 | centralStateCode | `String` | Central State Code |
| 59 | centralTerritory | `String` | Central Territory |
| 60 | centralVIPCode | `String` | Central VIP Code |
| 61 | centralVIPDescription | `String` | Central VIP Description |
| 62 | chainCode | `String` | Chain Code |
| 63 | city | `String` | The city for this address. |
| 64 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 65 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 66 | combinedName | `String` | Combined Name |
| 67 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 68 | comments | `String` | Not Used. |
| 69 | commissionCode | `String` | Commission Code for the Commission Percentage. |
| 70 | commissionCodes | `String` | Code for the commission for Travel Agent |
| 71 | commissionCurrencyId | `String` | Comm Curr ID |
| 72 | commissionid | `String` | Commission Code for the Commission Percentage. |
| 73 | communicationRole1 | `String` | Role in which this phone type belongs to. |
| 74 | communicationRole2 | `String` | Role in which this phone type belongs to. |
| 75 | communicationRole3 | `String` | Role in which this phone type belongs to. |
| 76 | communicationType1 | `String` | The type of this phone number. |
| 77 | communicationType2 | `String` | The type of this phone number. |
| 78 | communicationType3 | `String` | The type of this phone number. |
| 79 | communicationValue1 | `String` | The phone number for this record |
| 80 | communicationValue2 | `String` | The phone number for this record |
| 81 | communicationValue3 | `String` | The phone number for this record |
| 82 | companyAlternate | `String` | Extended Byte Company Name |
| 83 | companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| 84 | companyNameId | `Float` | Not used. |
| 85 | competition | `String` | Competaion code . |
| 86 | competitionDesc | `String` | The description of this value. |
| 87 | contactYN | `String` | Used in S&.C Module. |
| 88 | contractNo | `String` | Group Contract number. |
| 89 | contractRecvDate | `Date` | The date the group contract was received. |
| 90 | corpTypeDesc | `String` | Corp Type Description |
| 91 | corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 92 | country | `String` | Country name. |
| 93 | countryCode | `String` | Country . |
| 94 | createdByUser | `String` | The user that created the record |
| 95 | createdOnDate | `DateTime` | The date the record was created |
| 96 | creditRating | `String` | Credit rating. |
| 97 | currencyCode | `String` | Currency Code |
| 98 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 99 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 100 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 101 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 102 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 103 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 104 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 105 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 106 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 107 | debtorName | `String` | Debtor Name |
| 108 | decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| 109 | defaultKeyword | `String` | The keyword to search on. |
| 110 | deletedFlag | `String` | Deleted Flag |
| 111 | department | `String` | Used in S&.C Module. |
| 112 | deptId | `String` | Used in S&.C Module. |
| 113 | description | `String` | Used in QMS Module |
| 114 | directBillBatchType | `String` | Direct Bill Batch Type |
| 115 | displayName | `String` | Display Name |
| 116 | downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| 117 | downloadResort | `String` | REsort name which has downloaded on the laptop. |
| 118 | downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| 119 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 120 | eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| 121 | email | `String` | The phone number for this record |
| 122 | emailYN | `String` | Email YN |
| 123 | envelopeGreeting | `String` | Field which stores the envelop greeting used in S&.C |
| 124 | externalDisplayName | `String` | External Display Name |
| 125 | externalFirstName | `String` | The first name of an individual. |
| 126 | externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| 127 | externalName | `String` | The last name of the individual profile. |
| 128 | externalReferenceRequ | `String` | Not Used. |
| 129 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 130 | fMembershipCardNumbers | `String` | Membership Card Number. |
| 131 | fMembershipClassDesc | `String` | Descripion of membership class |
| 132 | fMembershipClasses | `String` | F Membership Classes |
| 133 | fMembershipCodes | `String` | F Membership Codes |
| 134 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 135 | fMembershipIds | `String` | Primary Key for this table. |
| 136 | fMembershipType | `String` | Type of the Membership. |
| 137 | fSubscriptionDb | `String` | The ID of the external Database. |
| 138 | fSubscriptionYn | `String` | The ID of the external Database. |
| 139 | faxNumber | `String` | The phone number for this record |
| 140 | firstName | `String` | The first name of an individual name. |
| 141 | firstNameAlternate | `String` | First Name Alternate |
| 142 | firstNameIncognito | `String` | The keyword to search on. |
| 143 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 144 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 145 | gDSTransactionNo | `String` | Not used. |
| 146 | gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| 147 | geographicRegion | `String` | Not used. |
| 148 | guestClassification | `String` | Not used. |
| 149 | guestCountry | `String` | Country name. |
| 150 | guestCurrencyCode | `String` | Currency code for the Commission payment. |
| 151 | guestLanguageCode | `String` | Description for each language code. |
| 152 | guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent &. Source) are stored in this column. |
| 153 | guestMiddleName | `String` | The middle name of this individual. |
| 154 | guestNameSuffix | `String` | Guest Name Suffix |
| 155 | guestPrivilegeYN | `String` | Guest Privilege YN |
| 156 | guestTitleCode | `String` | The title of the individual. |
| 157 | hasRequestedMailYN | `String` | Has Requested Mail YN |
| 158 | historyYN | `String` | Keep guest in history Y/N |
| 159 | holdCode | `String` | Hold code for the Commission handling purposes. |
| 160 | iataConsortia | `String` | Consortia for the IATA number. |
| 161 | idCountry | `String` | The country where ID was issued |
| 162 | idDate | `Date` | Issued date of Identification |
| 163 | idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| 164 | idPlace | `String` | The place where ID was issued |
| 165 | idType | `String` | Identification Type. Eg Passport Driving License etc |
| 166 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 167 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 168 | inactiveFlag | `String` | Inactive Flag |
| 169 | inactiveReason | `String` | Reason why record was inactivated. |
| 170 | inactiveReasonDescription | `String` | The description of this value. |
| 171 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 172 | indexName | `String` | Index Name |
| 173 | industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| 174 | industryDesc | `String` | The description of this value. |
| 175 | influence | `String` | Used in S&.C Module. |
| 176 | influenceDesc | `String` | The description of this value. |
| 177 | interest | `String` | Interest Code. |
| 178 | internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| 179 | internalDeletedflag | `String` | Deleted Flag |
| 180 | internalInactiveflag | `String` | Inactive Flag |
| 181 | languageCode | `String` | Primary language used for the profile. |
| 182 | laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| 183 | lastGroup | `String` | Last Group |
| 184 | lastNameAlternate | `String` | Last Name Alternate |
| 185 | lastNameIncognito | `String` | The keyword to search on. |
| 186 | lastRate | `Float` | Last Rate |
| 187 | lastRateCode | `String` | Last Rate Code |
| 188 | lastRoom | `String` | The room that is booked for this reservation leg. |
| 189 | lastRoomProperty | `String` | Last Room Property |
| 190 | lastSource | `String` | Last Source |
| 191 | lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| 192 | lastUpdatedResort | `String` | Last property that updated this record. |
| 193 | legalCompany | `String` | The legal company name for this company. |
| 194 | letterGreeting | `String` | Used in S&.C Module. |
| 195 | mailActionDescription | `String` | The description of this value. |
| 196 | mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| 197 | mailType | `String` | The type of mail this user should be sent. |
| 198 | mailingActionCode | `String` | Mailing action codes. |
| 199 | marketResearchYN | `String` | Market Research YN |
| 200 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 201 | nameTaxType | `String` | Not used. |
| 202 | nameType | `String` | The type of Profile. |
| 203 | nameTypeDescription | `String` | The description of this value. |
| 204 | name2 | `String` | Not Used. |
| 205 | name3 | `String` | Not used. |
| 206 | nationality | `String` | Nationality |
| 207 | nationalityCode | `String` | Nationality of the individual. |
| 208 | negotiatedRateCodes | `String` | The rate code for which this record applies. |
| 209 | nextStay | `Date` | This is a begin_date  with no  time component. |
| 210 | nickname | `String` | The nickname of this individual. |
| 211 | organizationID | `Float` | Organization ID |
| 212 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 213 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 214 | phone | `String` | The phone number for this record |
| 215 | phoneWeb | `String` | The phone number for this record |
| 216 | phoneYN | `String` | Phone YN |
| 217 | postalCode | `String` | The postal code of this address. |
| 218 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 219 | preferredRoomNo | `String` | Preferred Room Number |
| 220 | primaryAddressId | `Float` | Not used. |
| 221 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 222 | primaryNameId | `Float` | Not Used. |
| 223 | primaryOwner | `String` | Primary Owner |
| 224 | primaryOwnerCode | `String` | Primary Owner Code |
| 225 | primaryPhoneId | `Float` | Not used. |
| 226 | priority | `String` | Priority of the account |
| 227 | priorityDesc | `String` | The description of this value. |
| 228 | privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 229 | productInterest | `String` | Preference Code. Part of the Primary Key. |
| 230 | profession | `String` | The profession of the Individual |
| 231 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 232 | profileId | `Float` | The primary key for this table. |
| 233 | profileType | `String` | The type of Profile. |
| 234 | propertyRegistered | `String` | Resort for which Job is registered. |
| 235 | protected | `String` | Protected |
| 236 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 237 | rateStructure | `String` | The default rate structure for this name. |
| 238 | region | `String` | The region for this name. |
| 239 | regionid | `String` | The region for this name. |
| 240 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 241 | repAccountsource | `String` | Reporting Accountsource |
| 242 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 243 | repCompetitionCode | `String` | Reporting Competition Code |
| 244 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 245 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 246 | repIndustryCode | `String` | Reporting Industry Code |
| 247 | repIndustryDescription | `String` | Reporting Industry Desc |
| 248 | repInfluence | `String` | Reporting Influence |
| 249 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 250 | repNameType | `String` | Reporting Name Type |
| 251 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 252 | repNationalityCode | `String` | Rep Nationality Code |
| 253 | repNationalityDescription | `String` | Rep Nationality Description |
| 254 | repPriorityDescription | `String` | Reporting Priority Desc |
| 255 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 256 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 257 | repScope | `String` | Reporting Scope |
| 258 | repScopeCity | `String` | Reporting Scope City |
| 259 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 260 | repScopeDescription | `String` | Reporting Scope Desc |
| 261 | repStateDescription | `String` | Reporting State Desc |
| 262 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 263 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 264 | repTitleName | `String` | Reporting Title Name |
| 265 | repeatGuestId | `String` | The primary membership # for this guest. |
| 266 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 267 | requestType | `String` | This column store the Name of the Company Profiles. |
| 268 | restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| 269 | restrictedRule | `String` | The description of this value. |
| 270 | resvContact | `String` | Reservation Contact person. |
| 271 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 272 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 273 | roomsPotential | `String` | Potential no of rooms per year for a account |
| 274 | roomsPotentialDesc | `String` | The description of this value. |
| 275 | sMSYN | `String` | Use this alert to text a notification. |
| 276 | salutation | `String` | Salutation Greeting |
| 277 | scope | `String` | Scope of the account |
| 278 | scopeCity | `String` | Scope City |
| 279 | scopeCityDesc | `String` | The description of this value. |
| 280 | scopeDesc | `String` | The description of this value. |
| 281 | searchName | `String` | The Uppercase value of Last or Company. |
| 282 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 283 | sfirst | `String` | Uppercase value of First Name. |
| 284 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 285 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 286 | srepCode | `String` | Used in QMS Module |
| 287 | state | `String` | The state of this address. |
| 288 | stateCode | `String` | State Code |
| 289 | stateDescription | `String` | Description of the state. |
| 290 | summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| 291 | summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| 292 | superSearchIndexText | `String` | Used in Oracle Text Index. |
| 293 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 294 | taxCategory | `String` | Tax Category |
| 295 | taxExemptStatus | `String` | Not used. |
| 296 | taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| 297 | taxID2 | `String` | Tax No |
| 298 | taxOffice | `String` | Tax Office Name |
| 299 | taxType | `String` | Tax Type |
| 300 | territory | `String` | TERRITORY of  a account |
| 301 | territoryDesc | `String` | The description of this value. |
| 302 | thirdPartyYN | `String` | Third Party YN |
| 303 | titleAlternate | `String` | Title Alternate |
| 304 | titleName | `String` | The description of this value. |
| 305 | titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| 306 | totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| 307 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 308 | traceCode | `String` | Code to Trace a record for all Triggered actions. |
| 309 | tracecodeDesc | `String` | Description |
| 310 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 311 | uDFC01 | `String` | User defined character field. |
| 312 | uDFC02 | `String` | User defined character field. |
| 313 | uDFC03 | `String` | User defined character field. |
| 314 | uDFC04 | `String` | User defined character field. |
| 315 | uDFC05 | `String` | User defined character field. |
| 316 | uDFC06 | `String` | User defined character field. |
| 317 | uDFC07 | `String` | User defined character field. |
| 318 | uDFC08 | `String` | User defined character field. |
| 319 | uDFC09 | `String` | User defined character field. |
| 320 | uDFC10 | `String` | User defined character field. |
| 321 | uDFC11 | `String` | User defined character field. |
| 322 | uDFC12 | `String` | User defined character field. |
| 323 | uDFC13 | `String` | User defined character field. |
| 324 | uDFC14 | `String` | User defined character field. |
| 325 | uDFC15 | `String` | User defined character field. |
| 326 | uDFC16 | `String` | User defined character field. |
| 327 | uDFC17 | `String` | User defined character field. |
| 328 | uDFC18 | `String` | User defined character field. |
| 329 | uDFC19 | `String` | User defined character field. |
| 330 | uDFC20 | `String` | User defined character field. |
| 331 | uDFC21 | `String` | User defined character field. |
| 332 | uDFC22 | `String` | User defined character field. |
| 333 | uDFC23 | `String` | User defined character field. |
| 334 | uDFC24 | `String` | User defined character field. |
| 335 | uDFC25 | `String` | User defined character field. |
| 336 | uDFC26 | `String` | User defined character field. |
| 337 | uDFC27 | `String` | User defined character field. |
| 338 | uDFC28 | `String` | User defined character field. |
| 339 | uDFC29 | `String` | User defined character field. |
| 340 | uDFC30 | `String` | User defined character field. |
| 341 | uDFC31 | `String` | User defined character field. |
| 342 | uDFC32 | `String` | User defined character field. |
| 343 | uDFC33 | `String` | User defined character field. |
| 344 | uDFC34 | `String` | User defined character field. |
| 345 | uDFC35 | `String` | User defined character field. |
| 346 | uDFC36 | `String` | User defined character field. |
| 347 | uDFC37 | `String` | User defined character field. |
| 348 | uDFC38 | `String` | User defined character field. |
| 349 | uDFC39 | `String` | User defined character field. |
| 350 | uDFC40 | `String` | User defined character field. |
| 351 | uDFD01 | `Date` | User defined date field. |
| 352 | uDFD02 | `Date` | User defined date field. |
| 353 | uDFD03 | `Date` | User defined date field. |
| 354 | uDFD04 | `Date` | User defined date field. |
| 355 | uDFD05 | `Date` | User defined date field. |
| 356 | uDFD06 | `Date` | User defined date field. |
| 357 | uDFD07 | `Date` | User defined date field. |
| 358 | uDFD08 | `Date` | User defined date field. |
| 359 | uDFD09 | `Date` | User defined date field. |
| 360 | uDFD10 | `Date` | User defined date field. |
| 361 | uDFD11 | `Date` | User defined date field. |
| 362 | uDFD12 | `Date` | User defined date field. |
| 363 | uDFD13 | `Date` | User defined date field. |
| 364 | uDFD14 | `Date` | User defined date field. |
| 365 | uDFD15 | `Date` | User defined date field. |
| 366 | uDFD16 | `Date` | User defined date field. |
| 367 | uDFD17 | `Date` | User defined date field. |
| 368 | uDFD18 | `Date` | User defined date field. |
| 369 | uDFD19 | `Date` | User defined date field. |
| 370 | uDFD20 | `Date` | User defined date field. |
| 371 | uDFN01 | `Float` | User defined number field. |
| 372 | uDFN02 | `Float` | User defined number field. |
| 373 | uDFN03 | `Float` | User defined number field. |
| 374 | uDFN04 | `Float` | User defined number field. |
| 375 | uDFN05 | `Float` | User defined number field. |
| 376 | uDFN06 | `Float` | User defined number field. |
| 377 | uDFN07 | `Float` | User defined number field. |
| 378 | uDFN08 | `Float` | User defined number field. |
| 379 | uDFN09 | `Float` | User defined number field. |
| 380 | uDFN10 | `Float` | User defined number field. |
| 381 | uDFN11 | `Float` | User defined number field. |
| 382 | uDFN12 | `Float` | User defined number field. |
| 383 | uDFN13 | `Float` | User defined number field. |
| 384 | uDFN14 | `Float` | User defined number field. |
| 385 | uDFN15 | `Float` | User defined number field. |
| 386 | uDFN16 | `Float` | User defined number field. |
| 387 | uDFN17 | `Float` | User defined number field. |
| 388 | uDFN18 | `Float` | User defined number field. |
| 389 | uDFN19 | `Float` | User defined number field. |
| 390 | uDFN20 | `Float` | User defined number field. |
| 391 | uDFN21 | `Float` | User defined number field. |
| 392 | uDFN22 | `Float` | User defined number field. |
| 393 | uDFN23 | `Float` | User defined number field. |
| 394 | uDFN24 | `Float` | User defined number field. |
| 395 | uDFN25 | `Float` | User defined number field. |
| 396 | uDFN26 | `Float` | User defined number field. |
| 397 | uDFN27 | `Float` | User defined number field. |
| 398 | uDFN28 | `Float` | User defined number field. |
| 399 | uDFN29 | `Float` | User defined number field. |
| 400 | uDFN30 | `Float` | User defined number field. |
| 401 | uDFN31 | `Float` | User defined number field. |
| 402 | uDFN32 | `Float` | User defined number field. |
| 403 | uDFN33 | `Float` | User defined number field. |
| 404 | uDFN34 | `Float` | User defined number field. |
| 405 | uDFN35 | `Float` | User defined number field. |
| 406 | uDFN36 | `Float` | User defined number field. |
| 407 | uDFN37 | `Float` | User defined number field. |
| 408 | uDFN38 | `Float` | User defined number field. |
| 409 | uDFN39 | `Float` | User defined number field. |
| 410 | uDFN40 | `Float` | User defined number field. |
| 411 | updateDate | `DateTime` | The date the record was modified |
| 412 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 413 | updateUser | `String` | The user that modified the record |
| 414 | uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| 415 | vIPCode | `String` | VIP Status of the Individual. |
| 416 | vIPDescription | `String` | The description of this value. |
| 417 | vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| 418 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 419 | vipAuthorization | `String` | Not Used. |
| 420 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 421 | xdisplayName | `String` | Xdisplay Name |
| 422 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualCheckInDate | `DateTime` | Actual Check-In Date |
| 2 | actualCheckInTime | `String` | Actual Check-In Time |
| 3 | actualCheckOutDate | `DateTime` | Actual Check-Out Date |
| 4 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 5 | adultSTR | `String` | Adult STR |
| 6 | adults | `Float` | Adults |
| 7 | adultsTaxFree | `Float` | Adults Tax Free |
| 8 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 9 | arrivalDate | `Date` | Arrival Date |
| 10 | arrivalDateSTR | `String` | Arrival Date STR |
| 11 | arrivalTime | `String` | Activity begin time |
| 12 | arrivalTimeSTR | `String` | Arrival Time STR |
| 13 | autoPostAmount | `Float` | Not used. |
| 14 | awardCode | `String` | Award Code |
| 15 | awardCode1 | `String` | Award code 1 |
| 16 | awardCode2 | `String` | Award code 2 |
| 17 | awardCode3 | `String` | Award code 3 |
| 18 | awardCode4 | `String` | Award Code 4 |
| 19 | awardCode5 | `String` | Award code 5 |
| 20 | awardVoucher1 | `String` | Award Voucher number 1 |
| 21 | awardVoucher2 | `String` | Award Voucher number 2 |
| 22 | awardVoucher3 | `String` | Award Voucher number 3 |
| 23 | awardVoucher4 | `String` | Award Voucher number 4 |
| 24 | awardVoucher5 | `String` | Award Voucher number 5 |
| 25 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 26 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 27 | baseRateAmount | `Float` | Base Rate Amount |
| 28 | basedOnRule | `String` | Based On Rule |
| 29 | beginDate | `DateTime` | Begin Date |
| 30 | billingContactId | `Float` | Billing Contact ID |
| 31 | blockCode | `String` | Block Code |
| 32 | blockDescription | `String` | Block Description |
| 33 | blockID | `Float` | Block ID |
| 34 | blockResort | `String` | Property this block belongs to. |
| 35 | bookedRoomCategory | `String` | Booked Room Category |
| 36 | businessDate | `Date` | Business Date |
| 37 | businessDateCreated | `Date` | Business Date Created |
| 38 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 39 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 40 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 41 | cDiscountAmount | `Float` | Central Discount Amt |
| 42 | cExchangeDate | `Date` | Central Xchange Date |
| 43 | cExchangeRate | `Float` | Central Xchange Rate |
| 44 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 45 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 46 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 47 | cPackageAmount | `Float` | Central Pkg Amt |
| 48 | cPackageTax | `Float` | Central Pkg Tax |
| 49 | cRateAmount | `Float` | Central Rate Amount |
| 50 | cRoomCost | `Float` | Central Room Cost |
| 51 | cRoomTax | `Float` | Central Room Tax |
| 52 | cShareAmount | `Float` | Central Share Amount |
| 53 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 54 | cUpsellCharge | `Float` | Central Upsell Charge |
| 55 | cancellationCode | `String` | Cancellation Code |
| 56 | cancellationDate | `DateTime` | Cancellation Date |
| 57 | cancellationNo | `Float` | Cancellation Number |
| 58 | cancellationReasonDesc | `String` | Cancellation Reason Description |
| 59 | childSTR | `String` | Child STR |
| 60 | children | `Float` | Children |
| 61 | childrenTaxFree | `Float` | Children Tax Free |
| 62 | children1 | `Float` | Children1 |
| 63 | children2 | `Float` | Children2 |
| 64 | children3 | `Float` | Children3 |
| 65 | children4 | `Float` | Children4 |
| 66 | children5 | `Float` | Children5 |
| 67 | commissionCode | `String` | Commission Code |
| 68 | commissionPaid | `Float` | Commission Paid |
| 69 | commissionableYn | `String` | Commissionable Y/N |
| 70 | companyId | `Float` | Company ID |
| 71 | confirmationNumber | `String` | Confirmation Number |
| 72 | cribs | `Float` | Cribs |
| 73 | currencyCode | `String` | Currency Code |
| 74 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 75 | dayUseYn | `String` | Day Use Y/N |
| 76 | deletedFlag | `String` | Deleted Flag |
| 77 | depDateSTR | `String` | Dep Date STR |
| 78 | depTimeSTR | `String` | Dep Time STR |
| 79 | departureDate | `Date` | Departure Date |
| 80 | departureTime | `String` | Departure Time |
| 81 | discountAmt | `Float` | Discount Amount |
| 82 | discountPrcnt | `Float` | Discount Prcnt |
| 83 | discountReasonCode | `String` | Discount Reason Code |
| 84 | dmlSeqNumber | `Float` | Dml Sequence No |
| 85 | doNotMoveYn | `String` | Do not move room flag. |
| 86 | dueOutYn | `String` | Due Out Y/N |
| 87 | endDate | `DateTime` | End Date |
| 88 | exchangePostingType | `String` | Exchange Posting Type |
| 89 | exchangeRate | `Float` | Exchange Rate |
| 90 | extSegNo | `Float` | Not used |
| 91 | extSeqNumber | `Float` | Not used |
| 92 | externalReference | `String` | External Reference |
| 93 | extraBeds | `Float` | Extra Beds |
| 94 | fixedRateYn | `String` | Fixed Rate Y/N |
| 95 | grossRateAmt | `Float` | Not used. |
| 96 | groupId | `Float` | Group ID |
| 97 | guaranteeCode | `String` | Guarantee Code |
| 98 | guestName | `String` | Guest Name |
| 99 | guestNameFirstLastInitial | `String` | Guest Name First Last Initial |
| 100 | housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| 101 | houseuseYN | `String` | Houseuse YN |
| 102 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 103 | insertDate | `DateTime` | Insert Date |
| 104 | insertUser | `Float` | Insert User |
| 105 | internalBlockId | `Float` | Block ID. |
| 106 | jRNUpdateDate | `Date` | JRN Update Date |
| 107 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 108 | lastShareCalculation | `String` | Calculation method used to distribute the total room rate between shares: [S]plit [Z]ero [F]ull and [P]ercentage. |
| 109 | lengthOfStay | `Float` | Length of Stay |
| 110 | marketCode | `String` | Market Code |
| 111 | membershipLevel | `String` | Membership Level |
| 112 | membershipPoints | `Float` | Indicates if the Revenue Type is valid for calculating Membership Points. |
| 113 | membershipType | `String` | Membership Type |
| 114 | nameId | `Float` | Name ID |
| 115 | netRoomAmt | `Float` | Not used. |
| 116 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 117 | originOfBooking | `String` | Origin of Booking |
| 118 | originalBaseRate | `Float` | Not used. |
| 119 | originalEndDate | `Date` | Original End Date |
| 120 | originalStartDate | `Date` | Original Start Date |
| 121 | packageAmt | `Float` | Not used. |
| 122 | physicalQuantity | `Float` | Physical Quantity |
| 123 | physicalRooms | `Float` | Physical Rooms |
| 124 | pkgTax | `Float` | Not used. |
| 125 | points | `Float` | Points |
| 126 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 127 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 128 | property | `String` | Code to uniquely identify the Property |
| 129 | quantity | `Float` | Quantity |
| 130 | rESVJRNUpdateDTTM | `DateTime` | RESV JRN Update DTTM |
| 131 | rESVJRNUpdateDate | `Date` | RESV JRN Update Date |
| 132 | rateAmount | `Float` | Rate Amount |
| 133 | rateCode | `String` | Rate Code |
| 134 | rdAdults | `Float` | Rd Adults |
| 135 | rdBaseRateAmount | `Float` | Rd Base Rate Amount |
| 136 | rdCBaseRateAmount | `Float` | Rd Central Base Rate Amount |
| 137 | rdCExchangeDate | `Date` | Rd Central Xchange Date |
| 138 | rdCExchangeRate | `Float` | Rd Central Xchange Rate |
| 139 | rdChildren | `Float` | Rd Children |
| 140 | rdDmlSeqNumber | `Float` | Rd Dml Sequence No |
| 141 | rdInsertActionInstanceId | `Float` | Rd Insert Action Instance ID |
| 142 | rdInsertDate | `DateTime` | Rd Insert Date |
| 143 | rdInsertUser | `Float` | Rd Insert User |
| 144 | rdUpdateDate | `DateTime` | Rd Update Date |
| 145 | rdUpdateUser | `Float` | Rd Update User |
| 146 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 147 | reservationContactId | `Float` | Resv Contact ID |
| 148 | reservationDate | `Date` | Reservation Date |
| 149 | reservationNameId | `Float` | Resv Name ID |
| 150 | reservationStatus | `String` | Reservation Status |
| 151 | resvCleaningTime | `String` | Reservation Cleaning Time |
| 152 | resvDailyElSequence | `Float` | Reservation Daily El Seq |
| 153 | resvItems | `String` | Reservation Items |
| 154 | resvRoomFeatures | `String` | Reservation Room Features |
| 155 | resvRoomStatus | `String` | Reservation Room Status |
| 156 | resvSpecials | `String` | Reservation Specials |
| 157 | resvStatus | `String` | Reservation Status |
| 158 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 159 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 160 | room | `String` | Room |
| 161 | roomAssignment | `String` | Room Assignment |
| 162 | roomCategory | `String` | Room Category |
| 163 | roomClass | `String` | Room Class |
| 164 | roomCost | `Float` | Room Cost |
| 165 | roomInstructions | `String` | Room Instructions |
| 166 | roomTax | `Float` | Room Tax |
| 167 | scheduledMoveDatetime | `DateTime` | Scheduled Move Datetime |
| 168 | scheduledMoveOutRoom | `String` | Scheduled Move Out Room |
| 169 | scheduledMoveStatus | `String` | Scheduled Move Status |
| 170 | scheduledMoveTime | `String` | Scheduled Move Time |
| 171 | shareAmount | `Float` | Share Amount |
| 172 | shareAmountOriginal | `Float` | The original rate amount for the reservation date. |
| 173 | sharePaymentType | `String` | Not used. |
| 174 | sharePrcnt | `Float` | Not used. |
| 175 | sharePriority | `Float` | Not used. |
| 176 | sourceId | `Float` | Source ID |
| 177 | traces | `String` | Traces |
| 178 | travelAgentId | `Float` | Travel Agent ID |
| 179 | truncActualCheckInDate | `Date` | Usually will be begin date and will have no time component. |
| 180 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 181 | turnDownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 182 | updateDate | `DateTime` | Update Date |
| 183 | updateUser | `Float` | Update User |
| 184 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingTasksDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | autoAssignedYn | `String` | Flag to indicate if this task was assigned during automatic breakout. |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | colors | `String` | Colors |
| 4 | creditWeighting | `Float` | Credit Weighting. NULL will be treated as 100. |
| 5 | creditsDeparture | `Float` | Credits associated with the task after departure. |
| 6 | customizableYn | `String` | Is Task customizable ? |
| 7 | departureRoomDefaultTask | `String` | Indicates if the task is set as departure room default task. |
| 8 | guestRequestedTask | `String` | Flag indicates if the guest has to explicitly request this task. |
| 9 | housekeepingTaskCredits | `Float` | Housekeeping Task Credits |
| 10 | inactive | `String` | Inactive |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | linenChange | `String` | Indicates if this facility task requires a Linen Change. |
| 13 | room | `String` | Room |
| 14 | sequence | `Float` | Sequence |
| 15 | taskAssignDate | `Date` | When this task was last assigned. |
| 16 | taskCode | `String` | Task Code |
| 17 | taskCredits | `Float` | Task Credits |
| 18 | taskDSI | `Float` | Task DSI |
| 19 | taskDeletedFlag | `String` | Task Deleted Flag |
| 20 | taskDescription | `String` | Task Description |
| 21 | taskFrequency | `Float` | Task Frequency |
| 22 | taskInsertDate | `DateTime` | Task Insert Date |
| 23 | taskInsertUser | `Float` | Task Insert User |
| 24 | taskInstructions | `String` | Task Instructions |
| 25 | taskJRNUpdateDate | `Date` | Task JRN Update Date |
| 26 | taskJRNUpdateDateAndTime | `DateTime` | Task JRN Update Date and Time |
| 27 | taskLocationID | `String` | Task Location ID |
| 28 | taskOrganizationID | `Float` | Task Organization ID |
| 29 | taskPrimaryKeyID | `Float` | Task Primary Key ID |
| 30 | taskPriority | `Float` | Task Priority |
| 31 | taskProperty | `String` | Task Property |
| 32 | taskRNAInsertDate | `DateTime` | Task RNA Insert Date |
| 33 | taskRNAUpdateDate | `DateTime` | Task RNA Update Date |
| 34 | taskSeqNumber | `Float` | Task Sequence No |
| 35 | taskUpdateDate | `DateTime` | Task Update Date |
| 36 | taskUpdateUser | `Float` | Task Update User |
| 37 | unitOfFrequency | `String` | Indicates the unit of frequency for the task to be executed. |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingTasksRoomCategoryFacilityCodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | credits | `Float` | Credits |
| 2 | customizePromptYn | `String` | Flag indicates if the user should be prompted when a user customizes the schedule for a particular reservation. |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | dayOfTheWeekSchedule | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 5 | day1 | `String` | Day1 |
| 6 | day2 | `String` | Day2 |
| 7 | day3 | `String` | Day3 |
| 8 | day4 | `String` | Day4 |
| 9 | day5 | `String` | Day5 |
| 10 | day6 | `String` | Day6 |
| 11 | day7 | `String` | Day7 |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | facilityTask | `String` | Facility Task |
| 14 | facilityTaskSeq | `Float` | Facility Task Sequence |
| 15 | facilityTask1 | `String` | Facility Task1 |
| 16 | frequency | `String` | Frequency |
| 17 | includeOnArrivalDay | `String` | Include on Arrival Day |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertDate1 | `Date` | Insert Date1 |
| 20 | insertUser | `Float` | Insert User |
| 21 | insertUser1 | `Float` | Insert User1 |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | marketCodes | `String` | Comma delimited list of Market Codes. |
| 26 | marketDescription | `String` | Market Description |
| 27 | messageText | `String` | Free format text that will be displayed when a user customizes the schedule for a particular reservation. |
| 28 | moveupPenultimateYn | `String` | Indicate if the task should be rescheduled to 1 day earlier when it is due 1 day before the day of departure. |
| 29 | numberOfDays | `Float` | Number of Days |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 32 | priority | `Float` | Priority |
| 33 | property | `String` | Code to uniquely identify the Property |
| 34 | quantity | `Float` | Quantity |
| 35 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 36 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 37 | rateCode | `String` | Rate Code |
| 38 | rateCodeDescriptions | `String` | Rate Code Descriptions |
| 39 | repMarketCodesDescription | `String` | Reporting Market Codes Desc |
| 40 | repSpecialRequestsDescription | `String` | Reporting Special Requests Desc |
| 41 | repVIPStatusesDescription | `String` | Reporting Vip Statuses Desc |
| 42 | roomCategory | `String` | Room Category |
| 43 | roomCategory1 | `String` | Room Category1 |
| 44 | schedule | `String` | Schedule |
| 45 | specialRequestsCodes | `String` | Special Requests Codes |
| 46 | specialRequestsDescriptions | `String` | Special Requests Descriptions |
| 47 | startingOnDay | `Float` | Stay day that the first task in this cycle will be applied. 0 will indicate that the task is due on the day of arrival. Cycle will repeat for every FREQUENCY_DAYS days after arrival. |
| 48 | supplyCode | `String` | Supply Code |
| 49 | supplyDescription | `String` | Supply Description |
| 50 | supplySequence | `Float` | Supply Sequence |
| 51 | updateDate | `DateTime` | Update Date |
| 52 | updateDate1 | `Date` | Update Date1 |
| 53 | updateUser | `Float` | Update User |
| 54 | updateUser1 | `Float` | Update User1 |
| 55 | vIPLevelsCode | `String` | Comma delimited list of VIP status codes. |
| 56 | vIPLevelsDescription | `String` | VIP Levels Description |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingEmployeePointsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | appUserId | `Float` | App User ID |
| 2 | available | `String` | Indicates if Employee is available for task assignment. |
| 3 | building | `String` | Building |
| 4 | day1 | `String` | Day1 |
| 5 | day2 | `String` | Day2 |
| 6 | day3 | `String` | Day3 |
| 7 | day4 | `String` | Day4 |
| 8 | day5 | `String` | Day5 |
| 9 | day6 | `String` | Day6 |
| 10 | day7 | `String` | Day7 |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | empName | `String` | Name of the employee |
| 13 | floor | `String` | Floor |
| 14 | floorDesc | `String` | Floor Description |
| 15 | housekeepingSectionCode | `String` | Indicates the section to which employee belongs. |
| 16 | inactiveDate | `Date` | Inactive Date |
| 17 | jobCode | `String` | Job Code |
| 18 | phoneNo | `String` | Phone no. |
| 19 | points | `Float` | Points |
| 20 | pointsDate | `Date` | Date the points were allocated |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | repFloorDescription | `String` | Reporting Floor Desc |
| 23 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 24 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 25 | sectionDesc | `String` | Description of the section |
| 26 | status | `String` | Status |
| 27 | userName | `String` | User Name |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomHouseKeepingDailyTaskDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | applicationUser | `String` | Application User |
| 2 | attendantCode | `String` | Attendant Code |
| 3 | attendantCodeName | `String` | Attendant Code Name |
| 4 | attendantDescription | `String` | Attendant Description |
| 5 | attendantInstructions | `String` | Attendant Instructions |
| 6 | attendantStatus | `String` | Attendant Status |
| 7 | autoGenerateFilters | `String` | Auto generated filters. |
| 8 | autoGenerateInd | `String` | Indicates if task has been automatically generated. |
| 9 | businessDate | `Date` | Business Date |
| 10 | completedDateSTR | `String` | Completed date STR |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | dailyTaskAttendantCode | `String` | Daily Task Attendant Code |
| 13 | dailyTaskDSI | `Float` | Daily Task DSI |
| 14 | dailyTaskJRNUpdateDate | `Date` | Daily Task JRN Update Date |
| 15 | dailyTaskJRNUpdateDateAndTime | `Date` | Daily Task JRN Update Date and Time |
| 16 | dailyTaskLocationID | `String` | Daily Task Location ID |
| 17 | dailyTaskOrganizationID | `Float` | Daily Task Organization ID |
| 18 | dailyTaskResort | `String` | Daily Task Resort |
| 19 | deletedFlag | `String` | Deleted Flag |
| 20 | facilityCredits | `Float` | Facility Credits |
| 21 | floor | `String` | Floor |
| 22 | housekeepingBreakoutJobId | `Float` | Hk Breakout Job ID |
| 23 | housekeepingTaskCodesList | `String` | Housekeeping Task Codes List |
| 24 | jRNUpdateDate | `Date` | JRN Update Date |
| 25 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | lockedByUser | `Float` | User ID who locked this tasksheet. |
| 28 | lockedDate | `Date` | Date and Time that this task sheet was locked. |
| 29 | lockedYn | `String` | Locked Y/N |
| 30 | miscellaneousCredits | `Float` | Miscellaneous Credits |
| 31 | numRooms | `Float` | Num Rooms |
| 32 | numberOfBuildings | `Float` | Number of Buildings |
| 33 | numberOfFloors | `Float` | Number of Floors |
| 34 | numberOfGroups | `Float` | Number of Groups |
| 35 | numberOfSections | `Float` | Number of Sections |
| 36 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 37 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 38 | property | `String` | Code to uniquely identify the Property |
| 39 | repFloorDescription | `String` | Reporting Floor Desc |
| 40 | rnaInsertDate | `Date` | RnA Insertdate |
| 41 | rnaUpdateDate | `Date` | RnA Updatedate |
| 42 | roomInstructions | `String` | Room Instructions |
| 43 | roomWithNoFloor | `Float` | Room with no Floor |
| 44 | roomWithNoGroup | `Float` | Room with no Group |
| 45 | roomWithNoSection | `Float` | Room with no Section |
| 46 | section | `String` | Description of the section |
| 47 | simpleTaskYn | `String` | This indicates whether the task is simple or not |
| 48 | systemDateSTR | `String` | System Date STR |
| 49 | systemTimeSTR | `String` | System Time STR |
| 50 | targetCredits | `Float` | Target Credits |
| 51 | taskCode | `String` | Task Code |
| 52 | taskCompletedDate | `Date` | Date on which task is completed. |
| 53 | taskCredits | `Float` | Credits assigned for a particular task. |
| 54 | taskDate | `Date` | Breakout Date. |
| 55 | taskDateResortFormat | `String` | Task Date Resort Format |
| 56 | taskInstructions | `String` | Any specific instructions for the task. |
| 57 | taskSeqNumber | `Float` | Task Sequence No |
| 58 | taskSheet | `String` | Task Sheet |
| 59 | taskSheetDateSTR | `String` | Task Sheet Date STR |
| 60 | taskSheetNo | `Float` | task sheet associated with this room on business_date |
| 61 | taskSheetType | `String` | Indicates the task sheet type possible values: [A]utomatic [F]loating Sheet [N]o Services required [M]anually created |
| 62 | totalFacilityCredits | `Float` | Total Facility Credits |
| 63 | totalItemCredits | `Float` | Total Item Credits |
| 64 | totalMiscellaneousCredits | `Float` | Total Miscellaneous Credits |
| 65 | totalSpecialCredits | `Float` | Total Special Credits |
| 66 | totalTasks | `String` | Total Tasks |
| 67 | totalTravellingBuildingCredits | `Float` | Total Travelling Building Credits |
| 68 | totalTravellingCredits | `Float` | Total Travelling Credits |
| 69 | totalTravellingFloorCredits | `Float` | Total Travelling Floor Credits |
| 70 | totalTravellingGroupCredits | `Float` | Total Travelling Group Credits |
| 71 | totalTravellingSectionCredits | `Float` | Total Travelling Section Credits |
| 72 | travelingCredits | `Float` | Total traveling credits for this task sheet based on change of floors |

[⬆ Back to Query](#query)

---

### InventoryHousekeepingManagementRoomPropertyPropertyDetailsType

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

### InventoryHousekeepingManagementRoomDateCalendarDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dayDesc | `String` | Day Description. |
| 2 | dayEndDate | `Date` | Day End Date. |
| 3 | dayNoOfMonth | `Float` | Day number of the month. |
| 4 | dayNoOfQuarter | `Float` | Day number of the quarter. |
| 5 | dayNoOfWeek | `String` | Day number of the week. |
| 6 | dayOfWeek | `String` | Day Of Week |
| 7 | dayOfYear | `Float` | Day of the Year. |
| 8 | dayTimespan | `Float` | Day Timespan. |
| 9 | daykey | `Date` | Daykey |
| 10 | internalMonthkey | `Float` | Monthkey |
| 11 | internalYearkey | `Float` | Yearkey |
| 12 | isoWeekOfYear | `String` | Iso Week Of Year |
| 13 | julianDaykey | `String` | Julian Daykey |
| 14 | lastYearDaykey | `Date` | Last Year Daykey |
| 15 | monthDsc | `String` | Month Description. |
| 16 | monthEndDate | `Date` | Month End Date. |
| 17 | monthKey | `String` | Month Key |
| 18 | monthName | `String` | Month Name. |
| 19 | monthOfQuarter | `Float` | Month of the quarter. |
| 20 | monthOfYear | `Float` | Month of the year. |
| 21 | monthTimespan | `Float` | Month Timespan. |
| 22 | monthYrKey | `String` | Month Year Key |
| 23 | priorJulianDaykey | `String` | Prior Julian Daykey |
| 24 | priorMonthKey | `String` | Prior Month Key |
| 25 | priorWeekKey | `String` | Prior Week Key |
| 26 | priorYearDaykey | `Date` | Prior Year Daykey |
| 27 | priorYearKey | `String` | Prior Year Key |
| 28 | priorYearMonthKey | `String` | Prior Year Month Key |
| 29 | priorYearQuarterKey | `String` | Prior Year Quarter Key |
| 30 | priorYearWeekKey | `String` | Prior Year Week Key |
| 31 | quarterDsc | `String` | Quarter Description. |
| 32 | quarterEndDate | `Date` | Quarter End Date. |
| 33 | quarterKey | `String` | Quarter Key |
| 34 | quarterOfYear | `String` | Quarter of the year. |
| 35 | quarterTimespan | `Float` | Quarter Timespan. |
| 36 | weekDsc | `String` | Week Dsc |
| 37 | weekEndDate | `Date` | End date of the week. |
| 38 | weekEndDsc | `String` | Week End Dsc |
| 39 | weekEndKey | `String` | Week End Key |
| 40 | weekEndMonthDsc | `String` | Week End Month Dsc |
| 41 | weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| 42 | weekKey | `String` | Week Key |
| 43 | weekOfMonth | `String` | Week of the month. |
| 44 | weekOfYear | `String` | Week of the year. |
| 45 | weekTimespan | `Float` | Week Timespan. |
| 46 | yearDsc | `String` | Year description. |
| 47 | yearEndDate | `Date` | Year End Date. |
| 48 | yearKey | `String` | Year Key |
| 49 | yearTimespan | `Float` | Year Timespan. |

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
#### Validation Rules

**`mandatoryInput`**
- hkdailytaskroomDetailsResort
- hkdailytaskroomDetailsTaskDate


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'pickupInd': pl.Float64,
    'primaryKeyID': pl.Int64,
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
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'ovosGradeCode': pl.Utf8,
    'ovosUnitYn': pl.Utf8,
    'pcode': pl.Utf8,
    'personDiscrepancy': pl.Float64,
    'phoneNumber': pl.Utf8,
    'physicalNumberOfRooms': pl.Float64,
    'pickupCredits': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'visibleOnWebYn': pl.Utf8,
    'webBookingYn': pl.Utf8,
    'weightF': pl.Float64,
    'weightM': pl.Float64,
    'widthF': pl.Float64,
    'widthM': pl.Float64,
}
```
```python
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
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
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
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'upsellCharge': pl.Float64,
}
```
```python
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
```
```python
house_keeping_tasks_room_category_facility_codes_details_schema = {
    'credits': pl.Float64,
    'customizePromptYn': pl.Utf8,
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
    'insertUser1': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCodes': pl.Utf8,
    'marketDescription': pl.Utf8,
    'messageText': pl.Utf8,
    'moveupPenultimateYn': pl.Utf8,
    'numberOfDays': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'updateUser1': pl.Float64,
    'vIPLevelsCode': pl.Utf8,
    'vIPLevelsDescription': pl.Utf8,
}
```
```python
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
    'primaryKeyID': pl.Int64,
    'repFloorDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sectionDesc': pl.Utf8,
    'status': pl.Utf8,
    'userName': pl.Utf8,
}
```
```python
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
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
```python
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