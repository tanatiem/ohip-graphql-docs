# CateringEventsAndResources
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `cateringEventsAndResources`
> Event and Block details including group profile information menu packages and revenues broken down by event type.
  
**Return:** [`[CateringEventsAndResourcesType]`](#cateringeventsandresourcestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`CateringEventsAndResourcesQueryArgumentsType!`](#cateringeventsandresourcesqueryargumentstype) |  |

## Object Types

### CateringEventsAndResourcesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | eventDetails | [`CateringEventsAndResourcesEventDetailsType`](#cateringeventsandresourceseventdetailstype) | Event Details |
| 2 | eventPackageRevenueDetails | [`CateringEventsAndResourcesEventPackageRevenueDetailsType`](#cateringeventsandresourceseventpackagerevenuedetailstype) | Event Package Revenue |
| 3 | eventRevenueDetails | [`CateringEventsAndResourcesEventRevenueDetailsType`](#cateringeventsandresourceseventrevenuedetailstype) | Event Revenue Details |
| 4 | eventResourceNoteDetails | [`CateringEventsAndResourcesEventResourceNoteDetailsType`](#cateringeventsandresourceseventresourcenotedetailstype) | Event Resource Note Details |
| 5 | eventRoomWaitDetails | [`CateringEventsAndResourcesEventRoomWaitDetailsType`](#cateringeventsandresourceseventroomwaitdetailstype) | Event Room Wait Details |
| 6 | eventMenuDetails | [`CateringEventsAndResourcesEventMenuDetailsType`](#cateringeventsandresourceseventmenudetailstype) | Event Menu Details |
| 7 | eventMenuRevenueDetails | [`CateringEventsAndResourcesEventMenuRevenueDetailsType`](#cateringeventsandresourceseventmenurevenuedetailstype) | Event Menu Revenue Details |
| 8 | eventItemDetails | [`CateringEventsAndResourcesEventItemDetailsType`](#cateringeventsandresourceseventitemdetailstype) | Event Item Details |
| 9 | eventNotesDetails | [`CateringEventsAndResourcesEventNotesDetailsType`](#cateringeventsandresourceseventnotesdetailstype) | Event Notes Details |
| 10 | blockDetails | [`CateringEventsAndResourcesBlockDetailsType`](#cateringeventsandresourcesblockdetailstype) | Block |
| 11 | propertyPropertyDetails | [`CateringEventsAndResourcesPropertyPropertyDetailsType`](#cateringeventsandresourcespropertypropertydetailstype) | Resort Details |
| 12 | cateringEventsAndResourcesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualAttendees | `Float` | Actual Attendees |
| 2 | allotmentid | `Float` | Block ID |
| 3 | allowRegistryYn | `String` | Specifies if attendees can register for this event. |
| 4 | attendees | `Float` | Attendees |
| 5 | averageRate | `Float` | Average Rate |
| 6 | blockEndDate | `DateTime` | Block End Date |
| 7 | blockID | `Float` | Block ID |
| 8 | blockStartDate | `Date` | Block Start Date |
| 9 | bookingBlockEndDate | `Date` | Block End Date |
| 10 | cTotalRevenue | `Float` | Central Total Revenue |
| 11 | centralDiscountAmount | `Float` | Central Discount Amount |
| 12 | centralMealType | `String` | Central Meal Type |
| 13 | centralPackagePrice | `Float` | Central Package Price |
| 14 | centralRentalAmount | `Float` | Central Rental Amount |
| 15 | centralRoomClass | `String` | Central Room Class |
| 16 | centralRoomClassDescription | `String` | Central Room Class Description |
| 17 | chainCode | `String` | Chain Code |
| 18 | combinationRoomYN | `String` | Combination Room YN |
| 19 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 20 | deletedFlag | `String` | Deleted Flag |
| 21 | detailedPostingYn | `String` | Detailed Posting = 'Y' indicated that non included menu items will be posted individually and the unit price is stored when posting any revenue. |
| 22 | discountAmount | `Float` | Discount Amount |
| 23 | discountPercentage | `Float` | Discount Percentage |
| 24 | doNotMove | `String` | Do Not Move |
| 25 | doorCard | `String` | Door Card |
| 26 | doorcardYn | `String` | Display Doorcard Y/N. |
| 27 | doorcardflag | `String` | Doorcardflag |
| 28 | duration | `Float` | Duration |
| 29 | endDate | `DateTime` | End Date |
| 30 | endDateTime | `Date` | End Date Time |
| 31 | endTime | `String` | End Time |
| 32 | endTimeWithTeardown | `String` | End Time with Teardown |
| 33 | evResort | `String` | Event Property. |
| 34 | evStatusOrderBy | `Float` | Ev Status Order By |
| 35 | evType | `String` | Ev Type |
| 36 | eventID | `Float` | Event ID |
| 37 | eventIDSTR | `String` | Event ID STR |
| 38 | eventLinkType | `String` | Event Link Type |
| 39 | eventName | `String` | Event Name |
| 40 | eventProperty | `String` | Event Property |
| 41 | eventStatus | `String` | Event Status |
| 42 | eventlocationid | `String` | Eventlocationid |
| 43 | eventtypeid | `String` | Eventtypeid |
| 44 | excludeFromForecastYn | `String` | Exclude From Forecast Y/N |
| 45 | excludefromforecastflag | `String` | Excludefromforecastflag |
| 46 | expectedAttendees | `Float` | Expected Attendees |
| 47 | fbaId | `Float` | Fba ID |
| 48 | flatPackagePriceYN | `String` | Flat Package Price YN |
| 49 | forecastRevenueOnlyYn | `String` | Even though resources may be booked only the forecasted values will drive reporting revenue and production revenues. |
| 50 | forecastrevenueonlyflag | `String` | Forecastrevenueonlyflag |
| 51 | groupId | `Float` | Group ID |
| 52 | guaranteedAttendees | `Float` | Guaranteed Attendees |
| 53 | hourlyRentalRateYN | `String` | Hourly Rental Rate YN |
| 54 | inactiveDate | `Date` | Inactive Date |
| 55 | includeSetupInHourlyRateYN | `String` | Stores the INCLUDE_SETUP_IN_HOURLY_RATE parameter value at the time this rate was calculated hourly for the first time. |
| 56 | insertDate | `DateTime` | Insert Date |
| 57 | insertUser | `Float` | Insert User |
| 58 | inspectedDate | `Date` | Inspection Date |
| 59 | inspectedUser | `Float` | Inspection User |
| 60 | inspectedYn | `String` | Function Space has been inspected |
| 61 | internalEventid | `Float` | Eventid |
| 62 | isPartOfAPackageYN | `String` | Is Part of a Package YN |
| 63 | jRNUpdateDate | `Date` | JRN Update Date |
| 64 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 65 | linkedEvent | `Float` | Linked Event |
| 66 | locationID | `String` | Internal ID to uniquely identify the Property |
| 67 | loudEvent | `String` | Loud Event |
| 68 | masterEventID | `Float` | Master Event ID |
| 69 | masterEventYN | `String` | Master Event YN |
| 70 | maxGroup | `Float` | Maximum number of groups for a Shared function space allowed. |
| 71 | mealType | `String` | Meal Type Code |
| 72 | meetingRoomType | `String` | Type of meeting room |
| 73 | meetingRoomYN | `String` | Meeting Room YN |
| 74 | minimumRevenueYn | `String` | Minimum Revenue Y/N |
| 75 | onTheBooksAttendees | `Float` | On the Books Attendees |
| 76 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 77 | origEventId | `Float` | Stores the original EVENT_ID prior to a migration. |
| 78 | packageActualAttendees | `Float` | Package Actual Attendees |
| 79 | packageCode | `String` | Package Code |
| 80 | packageDiscountPercentage | `Float` | Package Discount Percentage |
| 81 | packageEvId | `Float` | Pkg Ev ID |
| 82 | packageExpAttendees | `Float` | Expected Attendees |
| 83 | packageGuaranteedAttendees | `Float` | Guranteed Attendees |
| 84 | packageID | `Float` | Package ID |
| 85 | packageName | `String` | Package Name |
| 86 | packagePrice | `Float` | Package Price |
| 87 | packageProperty | `String` | Package Property |
| 88 | packageeventid | `Float` | Packageeventid |
| 89 | parenteventid | `Float` | Parenteventid |
| 90 | pkgActAttendees | `Float` | Package Act Attendees |
| 91 | pkgExportAttendees | `Float` | Package Exp Attendees |
| 92 | pkgGuaAttendees | `Float` | Package Gua Attendees |
| 93 | pkgLink | `Float` | Package Link |
| 94 | pkgName | `String` | Package Name |
| 95 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 96 | rentalAmount | `Float` | Rental Amount |
| 97 | rentalCode | `String` | Room Ratecode |
| 98 | rentalRateType | `String` | Rental Rate Type |
| 99 | revenueActualization | `String` | Allow manual Edit of Actual figures |
| 100 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 101 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 102 | roomClass | `String` | Room Class |
| 103 | roomClassDescription | `String` | Room Class Description |
| 104 | roomType | `String` | Room Type |
| 105 | roomid | `String` | Roomid |
| 106 | roomsetuptypeid | `String` | Roomsetuptypeid |
| 107 | selectRatecodeInCentralYn | `String` | Identifies if the user can select a rate code in central system for this event otherwise "CUSTOM" is used. |
| 108 | setAttendees | `Float` | Set Attendees |
| 109 | setupStyle | `String` | Setup Style |
| 110 | setupTime | `Float` | Setup Time |
| 111 | shareableSpace | `String` | Shareable Space |
| 112 | sharedYN | `String` | Shared YN |
| 113 | space | `String` | Space |
| 114 | spaceDescription | `String` | Space Description |
| 115 | startDate | `DateTime` | Start Date |
| 116 | startDateTime | `Date` | Start Date Time |
| 117 | startTime | `String` | Start Time |
| 118 | startTimeWithSetup | `String` | Start Time with Setup |
| 119 | statusDate | `Date` | Date when the status was changed |
| 120 | tearDownTime | `Float` | Tear-Down Time |
| 121 | totalAvailableRooms | `Float` | Total Available Rooms |
| 122 | totalBlockedRooms | `Float` | Total Blocked Rooms |
| 123 | totalContractedRooms | `Float` | Total Contracted Rooms |
| 124 | totalOriginalRooms | `Float` | Total Original Rooms |
| 125 | totalPickupRooms | `Float` | Total Pickup Rooms |
| 126 | totalRevenue | `Float` | Total Revenue |
| 127 | tracecode | `String` | Tracecode |
| 128 | turnToStatus | `String` | Turn to Status |
| 129 | updateDate | `DateTime` | Update Date |
| 130 | updateUser | `Float` | Update User |
| 131 | v6EventId | `Float` | Stores the migrated V6 Event ID. |
| 132 | waitlistYn | `String` | Event is waitlisted? |
| 133 | waitlistflag | `String` | Waitlistflag |
| 134 | wlIgnoreYn | `String` | Ignore Waitlist Flag? |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventPackageRevenueDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualAttendees | `Float` | Actual Attendees |
| 2 | allotmentid | `Float` | Block ID |
| 3 | blockBeginDate | `Date` | Block Begin Date |
| 4 | blockEndDate | `Date` | Block End Date |
| 5 | blockID | `Float` | Block ID |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | centralDiscountedExpectedRevenue | `Float` | Central Discounted Expected Revenue |
| 9 | centralExpectedCost | `Float` | Central Expected Cost |
| 10 | centralForecastRevenue | `Float` | Central Forecast Revenue |
| 11 | centralPackageExpectedRevenue | `Float` | Central Package Expected Revenue |
| 12 | centralTotalDiscountedExpectedRevenue | `Float` | Central Total Discounted Expected Revenue |
| 13 | centralTotalExpectedRevenue | `Float` | Central Total Expected Revenue |
| 14 | centralTotalForecastRevenue | `Float` | Central Total Forecast Revenue |
| 15 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | discountPercentage | `Float` | Discount Percentage |
| 18 | discountedExpectedRevenue | `Float` | Discounted Expected Revenue |
| 19 | eventId | `Float` | Event ID |
| 20 | eventpkgrevenueid | `Float` | Eventpkgrevenueid |
| 21 | eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| 22 | expectedAttendees | `Float` | Expected Attendees |
| 23 | expectedAttendees1 | `Float` | Expected Attendees |
| 24 | expectedRevenue | `Float` | Expected Revenue |
| 25 | flatYN | `String` | Flat YN |
| 26 | forecastRevenue | `Float` | Forecast Revenue |
| 27 | guaranteedAttendees | `Float` | Guaranteed Attendees |
| 28 | insertDate | `DateTime` | Insert Date |
| 29 | insertUser | `Float` | Insert User |
| 30 | internalEventid | `Float` | Eventid |
| 31 | jRNUpdateDate | `Date` | JRN Update Date |
| 32 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 33 | locationID | `String` | Internal ID to uniquely identify the Property |
| 34 | orderBy | `Float` | Order By |
| 35 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 36 | packageExpectedCost | `Float` | Package Expected Cost |
| 37 | packageID | `Float` | Package ID |
| 38 | packageProperty | `String` | Package Property |
| 39 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 40 | revenueGroup | `String` | Revenue Group |
| 41 | revenueType | `String` | Revenue Type |
| 42 | revenuetypeid | `String` | Revenuetypeid |
| 43 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 44 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 45 | totalDiscountedExpectedRevenue | `Float` | Total Discounted Expected Revenue |
| 46 | totalExpectedRevenue | `Float` | Total Expected Revenue |
| 47 | totalForecastRevenue | `Float` | Total Forecast Revenue |
| 48 | updateDate | `DateTime` | Update Date |
| 49 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventRevenueDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualCost | `Float` | Actual Cost |
| 2 | actualRevenue | `Float` | Actual Revenue |
| 3 | allotmentid | `Float` | Block ID |
| 4 | billedCost | `Float` | Billed Cost |
| 5 | billedRevenue | `Float` | Billed Revenue |
| 6 | blockBeginDate | `Date` | Block Begin Date |
| 7 | blockEndDate | `Date` | Block End Date |
| 8 | blockID | `Float` | Block ID |
| 9 | cExchangeDate | `Date` | Central Xchange Date |
| 10 | cExchangeRate | `Float` | Central Xchange Rate |
| 11 | centralActualCost | `Float` | Central Actual Cost |
| 12 | centralActualRevenue | `Float` | Central Actual Revenue |
| 13 | centralBilledCost | `Float` | Central Billed Cost |
| 14 | centralBilledRevenue | `Float` | Central Billed Revenue |
| 15 | centralExpectedCost | `Float` | Central Expected Cost |
| 16 | centralExpectedRevenue | `Float` | Central Expected Revenue |
| 17 | centralForecastRevenue | `Float` | Central Forecast Revenue |
| 18 | centralGuaranteedCost | `Float` | Central Guaranteed Cost |
| 19 | centralGuaranteedRevenue | `Float` | Central Guaranteed Revenue |
| 20 | centralOnTheBooksRevenue | `Float` | Central On the Books Revenue |
| 21 | centralTotalForecastedRevenue | `Float` | Central Total Forecasted Revenue |
| 22 | customYn | `String` | Custom Y/N |
| 23 | customrevtypeflag | `String` | Customrevtypeflag |
| 24 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 25 | deletedFlag | `String` | Deleted Flag |
| 26 | eventID | `Float` | Event ID |
| 27 | eventStatus | `String` | Event Status |
| 28 | eventrevenueid | `Float` | Eventrevenueid |
| 29 | expectedCost | `Float` | Expected Cost |
| 30 | expectedRevenue | `Float` | Expected Revenue |
| 31 | flatRateYN | `String` | Flat Rate YN |
| 32 | flatYN | `String` | Flat YN |
| 33 | forecastCateringRevenue | `Float` | Forecast Catering Revenue |
| 34 | forecastRevenue | `Float` | Forecast Revenue |
| 35 | forecastRevenueEditedYN | `String` | Indicates if the event forecast revenue has been modified by the user. |
| 36 | forecastRevenueOnlyYn | `String` | Even though resources may be booked only the forecasted values will drive reporting revenue and production revenues. |
| 37 | guaranteedCost | `Float` | Guaranteed Cost |
| 38 | guaranteedRevenue | `Float` | Guaranteed Revenue |
| 39 | ignoreForecastYN | `String` | Ignore Forecast YN |
| 40 | inactiveDate | `DateTime` | Inactive Date |
| 41 | insertDate | `DateTime` | Insert Date |
| 42 | insertUser | `Float` | Insert User |
| 43 | internalEventid | `Float` | Eventid |
| 44 | jRNUpdateDate | `Date` | JRN Update Date |
| 45 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 46 | locationID | `String` | Internal ID to uniquely identify the Property |
| 47 | minimumRevenueYn | `String` | Minimum Revenue Y/N |
| 48 | onTheBooksAttendees | `Float` | On the Books Attendees |
| 49 | onTheBooksRevenue | `Float` | On the Books Revenue |
| 50 | orderBy | `Float` | Order By |
| 51 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 52 | packageRevenueYN | `String` | Package Revenue YN |
| 53 | packagerevenueflag | `String` | Packagerevenueflag |
| 54 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 55 | property | `String` | Property |
| 56 | revenueGroup | `String` | Revenue Group |
| 57 | revenueType | `String` | Revenue Type |
| 58 | revenuetypeid | `String` | Revenuetypeid |
| 59 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 60 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 61 | updateDate | `DateTime` | Update Date |
| 62 | updateUser | `Float` | Update User |
| 63 | useForecastValueOnlyYN | `String` | Use Forecast Value Only YN |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventResourceNoteDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentid | `Float` | Block ID |
| 2 | blockBeginDate | `Date` | Block Begin Date |
| 3 | blockEndDate | `Date` | Block End Date |
| 4 | blockID | `Float` | Block ID |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | eventID | `Float` | Event ID |
| 8 | eventitempmsref | `Float` | Eventitempmsref |
| 9 | eventmenupmsref | `Float` | Eventmenupmsref |
| 10 | eventresourceid | `Float` | Eventresourceid |
| 11 | eventresourcenoteid | `Float` | Eventresourcenoteid |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | internalDeletedflag | `String` | Deleted Flag |
| 15 | internalEventid | `Float` | Eventid |
| 16 | internalNotetitle | `String` | Notetitle |
| 17 | internalYn | `String` | Internal Y/N |
| 18 | internalnoteflag | `String` | Internalnoteflag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | manuallyAddedYN | `String` | Indicates if the note was manually added by the user. |
| 23 | noteDetails | `String` | Note Details |
| 24 | noteID | `Float` | Note ID |
| 25 | noteTitle | `String` | Note Title |
| 26 | order | `Float` | Order |
| 27 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 28 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 29 | property | `String` | Property |
| 30 | resourceId | `Float` | Resource ID |
| 31 | resourceType | `String` | Resource Type |
| 32 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 33 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventRoomWaitDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountName | `String` | Account Name |
| 2 | allotmentid | `Float` | Block ID |
| 3 | attendees | `Float` | Attendees |
| 4 | beginDate | `DateTime` | Begin Date |
| 5 | blockEndDate | `Date` | Block End Date |
| 6 | blockName | `String` | Block Name |
| 7 | bookId | `Float` | Book ID |
| 8 | catStatus | `String` | Catering Status |
| 9 | cateringOwner | `String` | Catering Owner |
| 10 | cateringYn | `String` | Catering Y/N |
| 11 | cateringbookingstatusid | `String` | Catering Booking Status ID |
| 12 | cateringflag | `String` | Cateringflag |
| 13 | centralTotalRevenue | `Float` | Central Total Revenue |
| 14 | currentEvent | `Float` | Current Event |
| 15 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | doNotMoveYN | `String` | Do Not Move YN |
| 18 | endDate | `DateTime` | End Date |
| 19 | endDateD | `Date` | End Date D |
| 20 | endTime | `String` | End Time |
| 21 | eventName | `String` | Event Name |
| 22 | eventType | `String` | Event Type |
| 23 | eventid | `Float` | Eventid |
| 24 | eventlocationid | `String` | Eventlocationid |
| 25 | eventroomwaitlistid | `Float` | Eventroomwaitlistid |
| 26 | exclusiveYN | `String` | Exclusive YN |
| 27 | insertDate | `DateTime` | Insert Date |
| 28 | insertUser | `Float` | Insert User |
| 29 | internalWaitlistdate | `Date` | Waitlistdate |
| 30 | jRNUpdateDate | `Date` | JRN Update Date |
| 31 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 32 | locationID | `String` | Internal ID to uniquely identify the Property |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 35 | priority | `Float` | Priority |
| 36 | property | `String` | Code to uniquely identify the Property |
| 37 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 38 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 39 | roomResort | `String` | Meeting Room Property |
| 40 | roomid | `String` | Roomid |
| 41 | shareableYN | `String` | Shareable YN |
| 42 | space | `String` | Space |
| 43 | startDate | `Date` | Start Date |
| 44 | startTime | `String` | Activity begin time |
| 45 | status | `String` | Status |
| 46 | totalRevenue | `Float` | Total Revenue |
| 47 | turnToStatus | `String` | Turn To Status |
| 48 | turntobookingstatusid | `String` | Turntobookingstatusid |
| 49 | updateDate | `DateTime` | Update Date |
| 50 | updateUser | `Float` | Update User |
| 51 | waitlistDate | `Date` | Date when Room got waitlisted |
| 52 | waitlistedEvent | `Float` | Waitlist ID |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventMenuDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualCovers | `Float` | Actual Number of Covers |
| 2 | actualNumbers | `Float` | Actual Numbers |
| 3 | allotmentid | `Float` | Block ID |
| 4 | billedNumbers | `Float` | Billed Numbers |
| 5 | blockBeginDate | `Date` | Block Begin Date |
| 6 | blockEndDate | `Date` | Block End Date |
| 7 | blockID | `Float` | Block ID |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cateringmenuid | `Float` | Cateringmenuid |
| 11 | centralDiscountedPrice | `Float` | Central Discounted Price |
| 12 | centralPrice | `Float` | Central Price |
| 13 | complimentaryMenus | `Float` | Complimentary Number of Menus |
| 14 | consumptionYn | `String` | Consumption Y/N |
| 15 | consumptionflag | `String` | Consumptionflag |
| 16 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 17 | deletedFlag | `String` | Deleted Flag |
| 18 | description | `String` | Description |
| 19 | discount | `Float` | Discount |
| 20 | discountedPrice | `Float` | Discounted Price |
| 21 | eventID | `Float` | Event ID |
| 22 | eventMenuID | `Float` | Menu ID |
| 23 | eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| 24 | expectedNumbers | `Float` | Expected Numbers |
| 25 | foodOrBeverage | `String` | Food or Beverage |
| 26 | gratuityYn | `String` | Gratuity is included |
| 27 | gratuityincludedflag | `String` | Gratuityincludedflag |
| 28 | guaranteedNumber | `Float` | Guaranteed Number |
| 29 | insertDate | `DateTime` | Insert Date |
| 30 | insertUser | `Float` | Insert User |
| 31 | internalEventMenuID | `Float` | Eventmenuid |
| 32 | internalEventid | `Float` | Eventid |
| 33 | jRNUpdateDate | `Date` | JRN Update Date |
| 34 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 35 | locationID | `String` | Internal ID to uniquely identify the Property |
| 36 | menuId | `Float` | Menu ID |
| 37 | menuResort | `String` | Menu Property |
| 38 | menulocationid | `String` | Menulocationid |
| 39 | multiChoiceYn | `String` | Indicates a Multichoice Menu |
| 40 | multichoiceflag | `String` | Multichoiceflag |
| 41 | name | `String` | Name |
| 42 | numberOfSetMenus | `Float` | Number of Set Menus |
| 43 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 44 | packageActual | `Float` | Actual number of menus booked via package. |
| 45 | packageBilled | `Float` | Billed number of menus booked via package. |
| 46 | packageExpected | `Float` | Expected number of menus booked via package. |
| 47 | packageGuaranteed | `Float` | Guaranteed number of menus booked via package. |
| 48 | packageID | `Float` | Package ID |
| 49 | personsPerTable | `Float` | Number of person per table used to calculate the serving |
| 50 | price | `Float` | Price |
| 51 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 52 | property | `String` | Property |
| 53 | restrictions | `String` | Menu Restrictions |
| 54 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 55 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 56 | sequenceOrder | `Float` | Sequence Order |
| 57 | servingEnd | `DateTime` | Serving End Time |
| 58 | servingEndDate | `Date` | Serving End Date |
| 59 | servingEndTime | `String` | Serving End Time |
| 60 | servingEndTrunc | `Date` | Serving End Trunc |
| 61 | servingPerPersonOrPerTable | `String` | Serving Per Person or Per Table |
| 62 | servingStart | `DateTime` | Serving Start Time |
| 63 | servingStartDate | `Date` | Serving Start Date |
| 64 | servingStartTime | `String` | Serving Start Time |
| 65 | servingStartTrunc | `Date` | Date Component of Serving Start Date/Time. |
| 66 | updateDate | `DateTime` | Update Date |
| 67 | updateUser | `Float` | Update User |
| 68 | voucherInstructions | `String` | Ticket/Voucher Instructions |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventMenuRevenueDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualCost | `Float` | Actual Cost |
| 2 | actualExtraCost | `Float` | Actual Extra Cost |
| 3 | actualExtraRevenue | `Float` | Actual Extra Revenue |
| 4 | actualNumber | `Float` | Actual Number |
| 5 | actualPrice | `Float` | Actual Price |
| 6 | allotmentid | `Float` | Block ID |
| 7 | billedCost | `Float` | Billed Cost |
| 8 | billedExtraCost | `Float` | Billed Extra Cost |
| 9 | billedExtraRevenue | `Float` | Billed Extra Revenue |
| 10 | billedNumber | `Float` | Billed Number |
| 11 | billedPrice | `Float` | Billed Price |
| 12 | blockBeginDate | `Date` | Block Begin Date |
| 13 | blockEndDate | `Date` | Block End Date |
| 14 | bookId | `Float` | Book ID |
| 15 | cExchangeDate | `Date` | Central Xchange Date |
| 16 | cExchangeRate | `Float` | Central Xchange Rate |
| 17 | cExpectedCost | `Float` | Central Expected Cost |
| 18 | cItemCost | `Float` | Central Item Cost |
| 19 | cItemPrice | `Float` | Central Item Price |
| 20 | centralActualCost | `Float` | Central Actual Cost |
| 21 | centralActualExtraCost | `Float` | Central Actual Extra Cost |
| 22 | centralActualExtraRevenue | `Float` | Central Actual Extra Revenue |
| 23 | centralActualPrice | `Float` | Central Actual Price |
| 24 | centralBilledCost | `Float` | Central Billed Cost |
| 25 | centralBilledExtraCost | `Float` | Central Billed Extra Cost |
| 26 | centralBilledExtraRevenue | `Float` | Central Billed Extra Revenue |
| 27 | centralBilledPrice | `Float` | Central Billed Price |
| 28 | centralDiscountedMenuPrice | `Float` | Central Menu Price |
| 29 | centralDiscountedPrice | `Float` | Central Discounted Price |
| 30 | centralExpectedExtraCost | `Float` | Central Expected Extra Cost |
| 31 | centralExpectedExtraRevenue | `Float` | Central Expected Extra Revenue |
| 32 | centralGuaranteedCost | `Float` | Central Guaranteed Cost |
| 33 | centralGuaranteedExtraCost | `Float` | Central Guaranteed Extra Cost |
| 34 | centralGuaranteedExtraRevenue | `Float` | Central Guaranteed Extra Revenue |
| 35 | centralGuaranteedPrice | `Float` | Central Guaranteed Price |
| 36 | centralInternalQuote | `Float` | Central Internal Quote |
| 37 | centralMenuPrice | `Float` | Central Menu Price |
| 38 | complimentaryNumber | `Float` | Complimentary Number of Menus |
| 39 | customYN | `String` | Custom YN |
| 40 | customrevtypeflag | `String` | Customrevtypeflag |
| 41 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 42 | deletedFlag | `String` | Deleted Flag |
| 43 | discountedMenuPrice | `Float` | Menu Price |
| 44 | discountedPrice | `Float` | Discounted Price |
| 45 | eventId | `Float` | Event ID |
| 46 | eventMenuId | `Float` | Event Menu ID |
| 47 | eventpkgrevenueid | `Float` | Eventpkgrevenueid |
| 48 | expectedCost | `Float` | Expected Cost |
| 49 | expectedExtraCost | `Float` | Expected Extra Cost |
| 50 | expectedExtraRevenue | `Float` | Expected Extra Revenue |
| 51 | expectedNumber | `Float` | Expected Number |
| 52 | guaranteedCost | `Float` | Guaranteed Cost |
| 53 | guaranteedExtraCost | `Float` | Guaranteed Extra Cost |
| 54 | guaranteedExtraRevenue | `Float` | Guaranteed Extra Revenue |
| 55 | guaranteedNumber | `Float` | Guaranteed Number |
| 56 | guaranteedPrice | `Float` | Guaranteed Price |
| 57 | insertDate | `DateTime` | Insert Date |
| 58 | insertUser | `Float` | Insert User |
| 59 | internalEventid | `Float` | Eventid |
| 60 | internalEventmenuid | `Float` | Eventmenuid |
| 61 | internalQuote | `Float` | Expected Price |
| 62 | itemCost | `Float` | Item Cost |
| 63 | itemPrice | `Float` | Item Price |
| 64 | jRNUpdateDate | `Date` | JRN Update Date |
| 65 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 66 | locationID | `String` | Internal ID to uniquely identify the Property |
| 67 | menuDiscountPercentage | `Float` | Menu Discount Percentage |
| 68 | menuPrice | `Float` | Menu Price |
| 69 | orderBy | `Float` | Order By |
| 70 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 71 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 72 | property | `String` | Code to uniquely identify the Property |
| 73 | revGroup | `String` | Revenue Group |
| 74 | revenueType | `String` | Revenue Type |
| 75 | revenuetypeid | `String` | Revenuetypeid |
| 76 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 77 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 78 | updateDate | `DateTime` | Update Date |
| 79 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventItemDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualExternalCost | `Float` | Actual external Cost |
| 2 | actualExternalQuantity | `Float` | Actual External Quantity |
| 3 | actualInternalCost | `Float` | Actual Internal cost |
| 4 | actualInternalQuantity | `Float` | Actual Internal Quantity |
| 5 | actualQuantity | `Float` | Actual Quantity |
| 6 | actualRevenue | `Float` | Actual Revenue |
| 7 | additionalDetails | `String` | Item Attribute Name |
| 8 | allotmentid | `Float` | Block ID |
| 9 | billedQuantity | `Float` | Billed Quantity |
| 10 | blockBeginDate | `Date` | Block Begin Date |
| 11 | blockEndDate | `Date` | Block End Date |
| 12 | blockID | `Float` | Block ID |
| 13 | cExchangeDate | `Date` | Central Xchange Date |
| 14 | cExchangeRate | `Float` | Central Xchange Rate |
| 15 | cGuaranteedRevenue | `Float` | C Guaranteed Revenue |
| 16 | cateringitemid | `Float` | Cateringitemid |
| 17 | centralActualExternalCost | `Float` | Central Actual External Cost |
| 18 | centralActualInternalCost | `Float` | Central Actual Internal Cost |
| 19 | centralActualRevenue | `Float` | Central Actual Revenue |
| 20 | centralDiscountedPrice | `Float` | Central Discounted Price |
| 21 | centralExpectedInternalCost | `Float` | Central Expected Internal Cost |
| 22 | centralExpectedRevenue | `Float` | Central Expected Revenue |
| 23 | centralExternalCost | `Float` | Central External Cost |
| 24 | centralItemClassName | `String` | Central Item Class Name |
| 25 | centralPrice | `Float` | Central Price |
| 26 | customYn | `String` | Custom Y/N |
| 27 | customitemflag | `String` | Customitemflag |
| 28 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 29 | deletedFlag | `String` | Deleted Flag |
| 30 | departmentID | `String` | Department ID |
| 31 | description | `String` | Description |
| 32 | discount | `Float` | Discount |
| 33 | discountableYN | `String` | Discountable YN |
| 34 | discountedPrice | `Float` | Discounted Price |
| 35 | endDateTrunc | `Date` | End Date Trunc |
| 36 | endTime | `DateTime` | End Time |
| 37 | eventID | `Float` | Event ID |
| 38 | eventItemID | `Float` | Event Item ID |
| 39 | eventItemgId | `Float` | EVENT_ITEMGROUP_SEQNO |
| 40 | eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| 41 | expectedExternalCost | `Float` | External cost |
| 42 | expectedInternalCost | `Float` | Internal Cost |
| 43 | expectedRevenue | `Float` | Expected Revenue |
| 44 | externalOrder | `String` | Item is external |
| 45 | externalQuantity | `Float` | External Quantity booked |
| 46 | guaranteedQuantity | `Float` | Guaranteed Quantity by client |
| 47 | guaranteedRevenue | `Float` | Guaranteed Revenue |
| 48 | hourlyYn | `String` | Hourly Y/N |
| 49 | hourlycostflag | `String` | Hourlycostflag |
| 50 | insertDate | `DateTime` | Insert Date |
| 51 | insertUser | `Float` | Insert User |
| 52 | internalEventid | `Float` | Eventid |
| 53 | internalEventitemid | `Float` | Eventitemid |
| 54 | internalQuantity | `Float` | Internal Quantity booked |
| 55 | itemClassID | `Float` | Item Group ID |
| 56 | itemClassName | `String` | Item Class Name |
| 57 | itemID | `Float` | Item ID |
| 58 | itemName | `String` | Item Name |
| 59 | itemResort | `String` | Item Property |
| 60 | itemlocationid | `String` | Itemlocationid |
| 61 | itemrateId | `Float` | Itemrate ID |
| 62 | itmaId | `Float` | Itma ID |
| 63 | itmcId | `Float` | Item Class ID |
| 64 | jRNUpdateDate | `Date` | JRN Update Date |
| 65 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 66 | locationID | `String` | Internal ID to uniquely identify the Property |
| 67 | order | `Float` | Order |
| 68 | orderExternalYN | `String` | Order External YN |
| 69 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 70 | packageID | `Float` | Package ID |
| 71 | price | `Float` | Price |
| 72 | priceCode | `String` | Price Code |
| 73 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 74 | property | `String` | Property |
| 75 | quantity | `Float` | Quantity |
| 76 | quickInsertCode | `String` | Quick Insert Code |
| 77 | revenueType | `String` | Revenue Type |
| 78 | revenuetypeid | `String` | Revenuetypeid |
| 79 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 80 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 81 | setUpTime | `Float` | Set-Up Time |
| 82 | showItemOnEventOrderYN | `String` | Show Item on Event Order YN |
| 83 | showOnBEOYN | `String` | Show on BEO YN |
| 84 | startDateTrunc | `Date` | Start Date Trunc |
| 85 | startTime | `DateTime` | Start Time |
| 86 | tearDownTime | `Float` | Tear-Down Time |
| 87 | updateDate | `DateTime` | Update Date |
| 88 | updateUser | `Float` | Update User |
| 89 | vendorID | `Float` | Vendor ID |
| 90 | vendorName | `String` | Vendor Identification Code. ( uppercase ) |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventNotesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | eventID | `Float` | Event ID |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | internalYN | `String` | Internal YN |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | locationID | `String` | Internal ID to uniquely identify the Property |
| 11 | note | `String` | Note |
| 12 | noteCode | `String` | Note Code |
| 13 | noteId | `Float` | Note ID |
| 14 | noteTitle | `String` | Note Title |
| 15 | order | `Float` | Order |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | property | `String` | Code to uniquely identify the Property |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesBlockDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionId | `Float` | Action ID |
| 2 | actualAverageRoomRate | `Float` | Actual Average Room Rate |
| 3 | actualFBRevenue | `Float` | Actual F&B Revenue |
| 4 | actualOtherRevenue | `Float` | Other revenue |
| 5 | actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| 6 | actualRoomRevenue | `Float` | Actual revenue of the room |
| 7 | addInfo | `String` | Add Info |
| 8 | agentContactNameId | `Float` | Agent Contact Name ID |
| 9 | agentNameId | `Float` | Agent Name ID |
| 10 | agentprofileid | `Float` | Agentprofileid |
| 11 | allAliases | `String` | All Aliases |
| 12 | allBlockOwners | `String` | All Block Owners |
| 13 | allCateringOwners | `String` | All Catering Owners |
| 14 | allCompanyContacts | `String` | All Company Contacts |
| 15 | allRateCodes | `String` | All Rate Codes |
| 16 | allRoomOwners | `String` | All Room Owners |
| 17 | allRoomPools | `String` | All Room Pools |
| 18 | allRoomTypes | `String` | All Room Types |
| 19 | allSourceContacts | `String` | All Source Contacts |
| 20 | allTravelAgentContacts | `String` | All Travel Agent Contacts |
| 21 | allotmentOrigin | `String` | Allotment Origin |
| 22 | allotmentType | `String` | Type of Block alloted for the group. |
| 23 | allotmentcurrencyid | `String` | Allotmentcurrencyid |
| 24 | allotmentid | `Float` | Block ID |
| 25 | allowPickup | `String` | Allow a pickup for a group with this booking status |
| 26 | alternateBlockName | `String` | Multi Byte Description Field |
| 27 | alternateDates | `String` | Alternate Dates |
| 28 | arrivalTime | `DateTime` | Arrival Time |
| 29 | attachmentURL | `String` | URL pointing to Lead Attachments. |
| 30 | attendeesGuaranteed | `Float` | Attendees Guaranteed |
| 31 | autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| 32 | averageRate | `Float` | Average Rate |
| 33 | bEOLastPrint | `DateTime` | Date when the BEO report was last printed for this business block. |
| 34 | beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| 35 | blockAlias | `String` | Block Alias |
| 36 | blockCode | `String` | Block Code |
| 37 | blockDateActual | `Date` | Block Date Actual |
| 38 | blockDateDefinite | `DateTime` | Block Date Definite |
| 39 | blockDateProspect | `DateTime` | Block Date Prospect |
| 40 | blockDateTentative | `DateTime` | Block Date Tentative |
| 41 | blockDescription | `String` | Block Description |
| 42 | blockID | `Float` | Block ID |
| 43 | blockMode | `String` | Classifies this allotment record: MASTER_ALLOCATION SUB_ALLOCATION SUB_BOOKING SUB_TOUR SUB_ITINERARY |
| 44 | blockOwnerCode | `String` | Block Owner Code |
| 45 | blockOwnerFullName | `String` | Block Owner Full Name |
| 46 | blockPackage | `String` | Block Package |
| 47 | blockPackageDescription | `String` | Block Package Description |
| 48 | blockStatus | `String` | Block Status |
| 49 | blockStatusDescription | `String` | Block Status Description |
| 50 | blockTypeCode | `String` | Block Type Code |
| 51 | blockTypeCodeDescription | `String` | Block Type Code Description |
| 52 | blockpackageid | `String` | Blockpackageid |
| 53 | bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| 54 | bookingMethodOrderBy | `Float` | Booking Method Order By |
| 55 | bookingStatusOrder | `Float` | Booking Status Order |
| 56 | bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| 57 | bookingTypeDescription | `String` | Booking Type Description |
| 58 | bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| 59 | bookingsourceid | `String` | Bookingsourceid |
| 60 | bookingstatusid | `String` | Bookingstatusid |
| 61 | bookingtypeid | `String` | Bookingtypeid |
| 62 | breakfastDescription | `String` | Breakfast Description |
| 63 | breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| 64 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 65 | breakfastIncluded | `String` | Breakfast Included |
| 66 | breakfastPrice | `Float` | Breakfast Price |
| 67 | bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| 68 | bwiUrl | `String` | URL populated bu CRS. |
| 69 | cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| 70 | cBreakfastPrice | `Float` | Central Bfst Price |
| 71 | cCompRoomValue | `Float` | Central Comp Room Value |
| 72 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 73 | cExchangeDate | `Date` | Central Xchange Date |
| 74 | cExchangeRate | `Float` | Central Xchange Rate |
| 75 | cFBCommission1 | `Float` | Central Fb Commission 1 |
| 76 | cFBCommission2 | `Float` | Central Fb Commission 2 |
| 77 | cPorteragePrice | `Float` | Central Porterage Price |
| 78 | cRoomCommission1 | `Float` | Central Rm Commission 1 |
| 79 | cRoomCommission2 | `Float` | Central Rm Commission 2 |
| 80 | cServiceCharge | `Float` | Central Service Charge |
| 81 | cServiceFee | `Float` | Central Service Fee |
| 82 | cRSGtdYn | `String` | CRS Guaranteed Y/N |
| 83 | cancelRule | `String` | Not Used |
| 84 | canceldestinationid | `String` | Canceldestinationid |
| 85 | cancellationDestination | `String` | Cancellation Destination |
| 86 | cancellationDestinationDescription | `String` | Cancellation Destination Description |
| 87 | cancellationNumber | `Float` | Cancellation Number |
| 88 | cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| 89 | cancellationreasonid | `String` | Cancellationreasonid |
| 90 | catCutoff | `Date` | Catering Cutoff |
| 91 | catDateProspect | `DateTime` | Cat Date Prospect |
| 92 | catOwner | `Float` | Catering Owner |
| 93 | catOwnerProperty | `String` | Property of Catering Owner |
| 94 | catReturnToInventory | `String` | Cat Return To Inventory |
| 95 | catStartingStatus | `String` | Cat Starting Status |
| 96 | catcurrencyid | `String` | Catcurrencyid |
| 97 | cateringCancellationDate | `Date` | Catering Cancellation Date |
| 98 | cateringCancellationDescription | `String` | Catering Cancellation Description |
| 99 | cateringCancellationNumber | `Float` | Catering Cancellation Number |
| 100 | cateringCancellationReason | `String` | Catering Cancellation Reason |
| 101 | cateringCurrency | `String` | Catering Currency |
| 102 | cateringDateActual | `Date` | Catering Date Actual |
| 103 | cateringDecisionDate | `Date` | Catering Decision Date |
| 104 | cateringDeductInventory | `String` | Catering Deduct Inventory |
| 105 | cateringExchangeRate | `Float` | Catering Exchange Rate |
| 106 | cateringFollowupDate | `Date` | Catering Followup Date |
| 107 | cateringOnlyYN | `String` | Catering only Revenue. |
| 108 | cateringOrderBy | `Float` | Catering Order By |
| 109 | cateringOwnerCode | `String` | Catering Owner Code |
| 110 | cateringOwnerFullName | `String` | Catering Owner Full Name |
| 111 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 112 | cateringQuoteCurrency | `String` | Catering Quote Currency |
| 113 | cateringStatus | `String` | Catering Status |
| 114 | cateringStatusColor | `String` | Catering Status Color |
| 115 | cateringStatusDescription | `String` | Catering Status Description |
| 116 | cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 117 | cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| 118 | cateringcurrencyid | `String` | Cateringcurrencyid |
| 119 | cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| 120 | cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| 121 | cateringstatusid | `String` | Cateringstatusid |
| 122 | cenralFBRevenue | `Float` | Cenral FB Revenue |
| 123 | centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| 124 | centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| 125 | centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| 126 | centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| 127 | centralAverageRoomRate | `Float` | Central Average Room Rate |
| 128 | centralBlockPackage | `String` | Central Block Package |
| 129 | centralBlockPackageDescription | `String` | Central Block Package Description |
| 130 | centralBlockStatus | `String` | Central Block Status |
| 131 | centralBlockStatusDescription | `String` | Central Block Status Description |
| 132 | centralBlockTypeCode | `String` | Central Block Type Code |
| 133 | centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| 134 | centralBookingType | `String` | Central Booking Type |
| 135 | centralBookingTypeDescription | `String` | Central Booking Type Description |
| 136 | centralCancellationDestination | `String` | Central Cancellation Destination |
| 137 | centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| 138 | centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| 139 | centralCateringStatus | `String` | Central Catering Status |
| 140 | centralCateringStatusDescription | `String` | Central Catering Status Description |
| 141 | centralConversionCode | `String` | Central Conversion Code |
| 142 | centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| 143 | centralIndustryCode | `String` | Central Industry Code |
| 144 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 145 | centralItemsForThisBlock | `String` | Central Items for this Block |
| 146 | centralMarketDescription | `String` | Central Market Description |
| 147 | centralMarketCode | `String` | Central Market code |
| 148 | centralMeetingBudget | `Float` | Central Meeting Budget |
| 149 | centralMeetingRevenue | `Float` | Central Meeting Revenue |
| 150 | centralOriginCode | `String` | Central Origin Code |
| 151 | centralOriginCodeDescription | `String` | Central Origin Code Description |
| 152 | centralOtherRevenue | `Float` | Central Other Revenue |
| 153 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 154 | centralPayment | `String` | Central Payment |
| 155 | centralPaymentDescription | `String` | Central Payment Description |
| 156 | centralRankingCode | `String` | Central Ranking Code |
| 157 | centralRankingCodeDescription | `String` | Central Ranking Code Description |
| 158 | centralReservationMethodCode | `String` | Central Reservation Method Code |
| 159 | centralReservationMethodDescription | `String` | Central Reservation Method Description |
| 160 | centralReservationType | `String` | Central Reservation Type |
| 161 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 162 | centralRoomRevenue | `Float` | Central Room Revenue |
| 163 | centralSourceCode | `String` | Central Source Code |
| 164 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 165 | centralTaxAmount | `Float` | Central Tax Amount |
| 166 | chainCode | `String` | Chain Code |
| 167 | channelid | `String` | Channelid |
| 168 | code | `String` | Code |
| 169 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 170 | comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| 171 | comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| 172 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 173 | comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 174 | comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 175 | commissionAmount | `String` | Commission Amount |
| 176 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 177 | commissionableYn | `String` | Commissionable Y/N |
| 178 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 179 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 180 | compRooms | `Float` | Number of complimentary Rooms |
| 181 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 182 | companyAll | `String` | Company All |
| 183 | companyNameId | `Float` | Company Name ID |
| 184 | companyprofileid | `Float` | Companyprofileid |
| 185 | competition | `String` | Competition |
| 186 | contactNameId | `Float` | Contact Name ID |
| 187 | contactprofileid | `Float` | Contactprofileid |
| 188 | contractNumber | `String` | Contract Number |
| 189 | controlBlockLocally | `String` | Control Block Y/N |
| 190 | conversionCode | `String` | Conversion Code |
| 191 | coversionCodeDescription | `String` | Coversion Code Description |
| 192 | createdBy | `String` | The name of the user who created the record. |
| 193 | createdDate | `DateTime` | Created Date |
| 194 | createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| 195 | creditCardId | `Float` | Credit Card ID |
| 196 | currency | `String` | Currency |
| 197 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 198 | dateAcl | `Date` | Date Acl |
| 199 | dateCfl | `Date` | Date Cfl |
| 200 | dateDefinite | `DateTime` | Date Definite |
| 201 | dateLsl | `Date` | Date Lsl |
| 202 | dateOpenedForPickup | `Date` | Date Opened for Pickup |
| 203 | datePel | `DateTime` | Date Pel |
| 204 | dateTdl | `DateTime` | Date Tdl |
| 205 | dateTentative | `DateTime` | Date Tentative |
| 206 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 207 | deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| 208 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 209 | deletedflag | `String` | Deleted Flag |
| 210 | departureTime | `DateTime` | Departure Time |
| 211 | description | `String` | Description |
| 212 | distributed | `String` | Distributed |
| 213 | distributedDate | `DateTime` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| 214 | dmlSeqNumber | `Float` | Dml Sequence No |
| 215 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 216 | downloadDate | `Date` | Download Date |
| 217 | downloadResort | `String` | Download Property |
| 218 | downloadSrep | `Float` | Download Srep |
| 219 | dueDate | `Date` | Due Date |
| 220 | dueDateOrd | `Date` | Due Date Sorting Column. |
| 221 | endDate | `Date` | End Date |
| 222 | endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| 223 | endbusinessdate | `Date` | Endbusinessdate |
| 224 | eventAttendees | `Float` | Event Attendees |
| 225 | exchangePostingType | `String` | Exchange Posting Type |
| 226 | exchangeRate | `Float` | Exchange Rate |
| 227 | exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| 228 | externalReference | `String` | External Reference |
| 229 | externalRfpId | `String` | External RFP ID. |
| 230 | externalRfpSystem | `String` | External RFP System Identification Code. |
| 231 | externallyLocked | `String` | Externally Locked |
| 232 | fBRevenue | `Float` | Projected F&B Revenue. |
| 233 | fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| 234 | fbCommission1 | `Float` | stores FB commission for Agent 1 |
| 235 | fbCommission2 | `Float` | stores FB commission for Agent 2 |
| 236 | fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| 237 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 238 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 239 | fitdiscounttype | `String` | Fitdiscounttype |
| 240 | flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| 241 | followupDate | `Date` | Followup Date |
| 242 | fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| 243 | functionType | `String` | Function Type |
| 244 | giid | `String` | Group IATA Number. |
| 245 | greekContractNr | `String` | Greek Contract Number. |
| 246 | groupAccountID | `Float` | Group Account ID |
| 247 | guaranteecodeid | `String` | Guaranteecodeid |
| 248 | guaranteedRate | `String` | Rate Guaranteed Y/N. |
| 249 | guaranteedYN | `String` | Guaranteed YN |
| 250 | hideacctinfoflag | `String` | Hideacctinfoflag |
| 251 | hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| 252 | hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| 253 | hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| 254 | hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| 255 | hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| 256 | hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| 257 | hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| 258 | hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| 259 | hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| 260 | inactiveDate | `Date` | Inactive Date |
| 261 | inactiveflag | `String` | Inactive Flag |
| 262 | industryCode | `String` | Indicates the Non-Compete code of a block. |
| 263 | industryCodeDescription | `String` | Industry Code Description |
| 264 | info | `String` | Not Used |
| 265 | informationBoard | `String` | Information Board |
| 266 | insertUser | `Float` | Insert User |
| 267 | inventoryControl | `String` | Inventory Control |
| 268 | inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| 269 | inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| 270 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 271 | items | `String` | Items |
| 272 | itemsForThisBlock | `String` | Items for this Block |
| 273 | jRNUpdateDate | `Date` | JRN Update Date |
| 274 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 275 | keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| 276 | laptopChange | `Float` | Laptop Change |
| 277 | leadOrigin | `String` | Lead Origin |
| 278 | leadSentYN | `String` | Lead Sent YN |
| 279 | leadSource | `String` | Lead Source |
| 280 | leadType | `String` | Lead Type |
| 281 | leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| 282 | leaderrorflag | `String` | Leaderrorflag |
| 283 | leadisnewflag | `String` | Leadisnewflag |
| 284 | leadoriginid | `String` | Leadoriginid |
| 285 | leadreceivedflag | `String` | Leadreceivedflag |
| 286 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 287 | leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| 288 | leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| 289 | leadserverpendingflag | `String` | Leadserverpendingflag |
| 290 | leadsourceid | `String` | Leadsourceid |
| 291 | leadstatus | `String` | Leadstatus |
| 292 | linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 293 | locationID | `String` | Internal ID to uniquely identify the Property |
| 294 | lostTo | `String` | Competitor to whom the booking was lost. |
| 295 | mainmarket | `String` | Mainmarket |
| 296 | mainmarketid | `String` | Mainmarketid |
| 297 | manuallyCutoffYN | `String` | Block was cutoff manullay |
| 298 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 299 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 300 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 301 | marketCode | `String` | Market  Code |
| 302 | marketDescription | `String` | Market Description |
| 303 | marketid | `String` | Marketid |
| 304 | masterBlockID | `Float` | Parent Block ID |
| 305 | masterBlockProperty | `String` | Parent Resort |
| 306 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 307 | meetingBudget | `Float` | Meeting Budget |
| 308 | meetingRevenue | `Float` | Meeting Revenue for SFA |
| 309 | offsetType | `String` | Offset Type |
| 310 | orderBy | `Float` | Order By |
| 311 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 312 | origAllotmentHeaderId | `Float` | Stores the original ALLOTMENT_HEADER_ID prior to a migration. |
| 313 | originCode | `String` | Origin Code |
| 314 | originCodeDescription | `String` | Origin Code Description |
| 315 | originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| 316 | originalEndDate | `Date` | Original End Date |
| 317 | originalRateCode | `String` | Not used |
| 318 | originalStartDate | `Date` | Original Start Date |
| 319 | originalratecodeid | `String` | Originalratecodeid |
| 320 | ormsBlockClass | `String` | ORMS Block Class |
| 321 | ormsFinalBlock | `String` | ORMS Final Block |
| 322 | ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| 323 | ormsTransientBlock | `String` | ORMS Transient Block |
| 324 | otherRevenue | `Float` | Projected Other Revenue. |
| 325 | owner | `Float` | Owner |
| 326 | ownerResort | `String` | Owner Property |
| 327 | owneremployeeid | `Float` | Owneremployeeid |
| 328 | ownerlocationd | `String` | Ownerlocationd |
| 329 | parentallotmentid | `Float` | Parentallotmentid |
| 330 | payment | `String` | Payment |
| 331 | paymentDescription | `String` | Payment Description |
| 332 | paymentmethodid | `String` | Paymentmethodid |
| 333 | personsPerRoom | `Float` | Persons Per Room |
| 334 | porterageIncluded | `String` | Porterage Included |
| 335 | porteragePrice | `Float` | Porterage Price |
| 336 | potAverageRoomRate | `Float` | Pot Average Room Rate |
| 337 | potFbRevenue1 | `Float` | Pot FB Revenue1 |
| 338 | potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| 339 | potRoomNights | `Float` | Projected Room Nights. |
| 340 | potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| 341 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 342 | printRate | `String` | Print Rate |
| 343 | profileId | `Float` | Profile ID |
| 344 | program | `String` | Program |
| 345 | property | `String` | Code to uniquely identify the Property |
| 346 | proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| 347 | proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| 348 | proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| 349 | proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| 350 | proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| 351 | proposalSentDate | `DateTime` | Proposal Sent Date |
| 352 | proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| 353 | proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| 354 | proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| 355 | proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| 356 | proposalViewToken | `String` | Proposal View Token |
| 357 | publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| 358 | rankingCode | `String` | Indicates the ranking of a block. |
| 359 | rankingCodeDescription | `String` | Ranking Code Description |
| 360 | rateCode | `String` | Rate Code |
| 361 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 362 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 363 | rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 364 | rateTier | `Float` | Rate Tier |
| 365 | ratecodeid | `String` | Ratecodeid |
| 366 | readyForDistribution | `String` | Ready for Distribution |
| 367 | regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| 368 | repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| 369 | repBsOrderBy | `Float` | Rep Bs Order By |
| 370 | repCatOrderBy | `Float` | Rep Cat Order By |
| 371 | replDate | `DateTime` | Reply Date |
| 372 | replVia | `String` | Reply Communication Method |
| 373 | replstatus | `String` | Lead Replystatus [ACL|TDL] |
| 374 | replyBy | `Float` | Reply By |
| 375 | representative | `String` | Representative |
| 376 | reservationMethod | `String` | Reservation Method |
| 377 | reservationType | `String` | Reservation Type |
| 378 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 379 | reservationid | `Float` | Reservationid |
| 380 | reserveInventoryYN | `String` | Reserve Inventory YN |
| 381 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 382 | resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| 383 | respTime | `Float` | Response Time. |
| 384 | respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| 385 | returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| 386 | rivMarketSegment | `String` | Not used |
| 387 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 388 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 389 | roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| 390 | roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| 391 | roomNightsSold | `Float` | Room Nights Sold |
| 392 | roomOwnerCode | `String` | Room Owner Code |
| 393 | roomOwnerFullName | `String` | Room Owner Full Name |
| 394 | roomRevenue | `Float` | Projected Room Revenue. |
| 395 | roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| 396 | roomStatus | `String` | Room Status |
| 397 | roomingListDue | `Date` | Rooming List Due |
| 398 | roomingListRules | `String` | Stores Rooming List Rules. |
| 399 | roomsCancellationDate | `Date` | Rooms Cancellation Date |
| 400 | roomsCancellationReason | `String` | Rooms Cancellation Reason |
| 401 | roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| 402 | roomsCurrency | `String` | Rooms Currency |
| 403 | roomsDecisionDate | `Date` | Rooms Decision Date |
| 404 | roomsExchangeRate | `Float` | Rooms Exchange Rate |
| 405 | roomsOwner | `Float` | Rooms Owner |
| 406 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 407 | roomsPerDay | `Float` | Rooms Per Day |
| 408 | roomsQuoteCurrency | `String` | Rooms Quote Currency |
| 409 | roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| 410 | salesId | `String` | Not used |
| 411 | sbegindate | `Date` | Sbegindate |
| 412 | scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| 413 | sellThruYn | `String` | Sell Thru Indicator. |
| 414 | sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| 415 | senddate | `Date` | Senddate |
| 416 | sentBy | `Float` | Sent By |
| 417 | sentDate | `DateTime` | Sent Date |
| 418 | sentVia | `String` | Sent Via |
| 419 | serviceCharge | `Float` | Service Charge |
| 420 | serviceFee | `Float` | Service Fee Amount per room/night |
| 421 | serviceFeeYn | `String` | Service Fee applies? |
| 422 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 423 | servicePerc | `Float` | Service Percentage included. |
| 424 | shoulderEnd | `Date` | Shoulder End |
| 425 | shoulderStart | `Date` | Shoulder Start |
| 426 | showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 427 | snapshotSetup | `String` | Snapshot has been created |
| 428 | sourceCode | `String` | Source Code |
| 429 | sourceCodeDescription | `String` | Source Code Description |
| 430 | sourceContactAll | `String` | Source Contact All |
| 431 | sourceNameId | `Float` | Source Name ID |
| 432 | sourceid | `Float` | Sourceid |
| 433 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 434 | startDate | `Date` | Start Date |
| 435 | startingStatus | `String` | Booking starting status (intial pickup) |
| 436 | status | `String` | Status |
| 437 | statusColor | `String` | Status Color |
| 438 | statusType | `String` | Type of booking status (initial) |
| 439 | subAllocationYN | `String` | Sub Allocation YN |
| 440 | superSearchIndexText | `String` | Super Search Index Text |
| 441 | suppressRate | `String` | Suppress Rate |
| 442 | syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the allotment_detail trigger. |
| 443 | synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| 444 | taxAmount | `Float` | Tax Amount |
| 445 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 446 | taxIncludedYn | `String` | Tax is included in this rate. |
| 447 | taxType | `String` | Tax Type |
| 448 | taxtypeid | `String` | Taxtypeid |
| 449 | tbdRates | `String` | To be Determined Rates |
| 450 | tdlReason | `String` | Tdl Reason |
| 451 | tentativeLevel | `Float` | Not used |
| 452 | tlpResponseid | `String` | Stores the TLPe - Response ID |
| 453 | tlpUrl | `String` | Stores the TLPe - Result URL. |
| 454 | tourCode | `String` | Tour Code. |
| 455 | traceCode | `String` | Trace Code |
| 456 | traceDescription | `String` | Trace Description |
| 457 | trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 458 | travelAgentAll | `String` | Travel Agent All |
| 459 | travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| 460 | turndownreasonid | `Float` | Turndownreasonid |
| 461 | uDFC01 | `String` | UDFC01 |
| 462 | uDFC02 | `String` | UDFC02 |
| 463 | uDFC03 | `String` | UDFC03 |
| 464 | uDFC04 | `String` | UDFC04 |
| 465 | uDFC05 | `String` | UDFC05 |
| 466 | uDFC06 | `String` | UDFC06 |
| 467 | uDFC07 | `String` | UDFC07 |
| 468 | uDFC08 | `String` | UDFC08 |
| 469 | uDFC09 | `String` | UDFC09 |
| 470 | uDFC10 | `String` | UDFC10 |
| 471 | uDFC11 | `String` | UDFC11 |
| 472 | uDFC12 | `String` | UDFC12 |
| 473 | uDFC13 | `String` | UDFC13 |
| 474 | uDFC14 | `String` | UDFC14 |
| 475 | uDFC15 | `String` | UDFC15 |
| 476 | uDFC16 | `String` | UDFC16 |
| 477 | uDFC17 | `String` | UDFC17 |
| 478 | uDFC18 | `String` | UDFC18 |
| 479 | uDFC19 | `String` | UDFC19 |
| 480 | uDFC20 | `String` | UDFC20 |
| 481 | uDFC21 | `String` | UDFC21 |
| 482 | uDFC22 | `String` | UDFC22 |
| 483 | uDFC23 | `String` | UDFC23 |
| 484 | uDFC24 | `String` | UDFC24 |
| 485 | uDFC25 | `String` | UDFC25 |
| 486 | uDFC26 | `String` | UDFC26 |
| 487 | uDFC27 | `String` | UDFC27 |
| 488 | uDFC28 | `String` | UDFC28 |
| 489 | uDFC29 | `String` | UDFC29 |
| 490 | uDFC30 | `String` | UDFC30 |
| 491 | uDFC31 | `String` | UDFC31 |
| 492 | uDFC32 | `String` | UDFC32 |
| 493 | uDFC33 | `String` | UDFC33 |
| 494 | uDFC34 | `String` | UDFC34 |
| 495 | uDFC35 | `String` | UDFC35 |
| 496 | uDFC36 | `String` | UDFC36 |
| 497 | uDFC37 | `String` | UDFC37 |
| 498 | uDFC38 | `String` | UDFC38 |
| 499 | uDFC39 | `String` | UDFC39 |
| 500 | uDFC40 | `String` | UDFC40 |
| 501 | uDFD01 | `Date` | UDFD01 |
| 502 | uDFD02 | `Date` | UDFD02 |
| 503 | uDFD03 | `Date` | UDFD03 |
| 504 | uDFD04 | `Date` | UDFD04 |
| 505 | uDFD05 | `Date` | UDFD05 |
| 506 | uDFD06 | `Date` | UDFD06 |
| 507 | uDFD07 | `Date` | UDFD07 |
| 508 | uDFD08 | `Date` | UDFD08 |
| 509 | uDFD09 | `Date` | UDFD09 |
| 510 | uDFD10 | `Date` | UDFD10 |
| 511 | uDFD11 | `Date` | UDFD11 |
| 512 | uDFD12 | `Date` | UDFD12 |
| 513 | uDFD13 | `Date` | UDFD13 |
| 514 | uDFD14 | `Date` | UDFD14 |
| 515 | uDFD15 | `Date` | UDFD15 |
| 516 | uDFD16 | `Date` | UDFD16 |
| 517 | uDFD17 | `Date` | UDFD17 |
| 518 | uDFD18 | `Date` | UDFD18 |
| 519 | uDFD19 | `Date` | UDFD19 |
| 520 | uDFD20 | `Date` | UDFD20 |
| 521 | uDFN01 | `Float` | UDFN01 |
| 522 | uDFN02 | `Float` | UDFN02 |
| 523 | uDFN03 | `Float` | UDFN03 |
| 524 | uDFN04 | `Float` | UDFN04 |
| 525 | uDFN05 | `Float` | UDFN05 |
| 526 | uDFN06 | `Float` | UDFN06 |
| 527 | uDFN07 | `Float` | UDFN07 |
| 528 | uDFN08 | `Float` | UDFN08 |
| 529 | uDFN09 | `Float` | UDFN09 |
| 530 | uDFN10 | `Float` | UDFN10 |
| 531 | uDFN11 | `Float` | UDFN11 |
| 532 | uDFN12 | `Float` | UDFN12 |
| 533 | uDFN13 | `Float` | UDFN13 |
| 534 | uDFN14 | `Float` | UDFN14 |
| 535 | uDFN15 | `Float` | UDFN15 |
| 536 | uDFN16 | `Float` | UDFN16 |
| 537 | uDFN17 | `Float` | UDFN17 |
| 538 | uDFN18 | `Float` | UDFN18 |
| 539 | uDFN19 | `Float` | UDFN19 |
| 540 | uDFN20 | `Float` | UDFN20 |
| 541 | uDFN21 | `Float` | UDFN21 |
| 542 | uDFN22 | `Float` | UDFN22 |
| 543 | uDFN23 | `Float` | UDFN23 |
| 544 | uDFN24 | `Float` | UDFN24 |
| 545 | uDFN25 | `Float` | UDFN25 |
| 546 | uDFN26 | `Float` | UDFN26 |
| 547 | uDFN27 | `Float` | UDFN27 |
| 548 | uDFN28 | `Float` | UDFN28 |
| 549 | uDFN29 | `Float` | UDFN29 |
| 550 | uDFN30 | `Float` | UDFN30 |
| 551 | uDFN31 | `Float` | UDFN31 |
| 552 | uDFN32 | `Float` | UDFN32 |
| 553 | uDFN33 | `Float` | UDFN33 |
| 554 | uDFN34 | `Float` | UDFN34 |
| 555 | uDFN35 | `Float` | UDFN35 |
| 556 | uDFN36 | `Float` | UDFN36 |
| 557 | uDFN37 | `Float` | UDFN37 |
| 558 | uDFN38 | `Float` | UDFN38 |
| 559 | uDFN39 | `Float` | UDFN39 |
| 560 | uDFN40 | `Float` | UDFN40 |
| 561 | ualias | `String` | Not in use. |
| 562 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 563 | updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| 564 | updateUser | `Float` | Update User |
| 565 | updatedBy | `String` | Updated By |
| 566 | updatedDate | `DateTime` | Updated Date |
| 567 | uploadDate | `Date` | Upload Date |
| 568 | webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| 569 | webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| 570 | xudescription | `String` | Multi Byte Description in uppercase |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesPropertyPropertyDetailsType

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

### CateringEventsAndResourcesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| eventDetailsAllotmentid | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsBookId | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsAllotmentenddate | `DateInput` | Block End Date<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| eventDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventDetailsEndDate | `DateTimeInput` | End Date<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsEndDateTime | `DateInput` | End Date Time<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsEvResort | `StringInput` | Event Property.<br>`@conditionalInputPair(pair: 1)` |
| eventDetailsEvType | `StringInput` | Ev Type |
| eventDetailsEventId | `FloatInput` | Event ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsEventLinkType | `StringInput` | Event Link Type |
| eventDetailsResort | `StringInput` | Event Property<br>`@conditionalInputPair(pair: 1)` |
| eventDetailsEvStatus | `StringInput` | Event Status |
| eventDetailsEventlocationid | `StringInput` | Eventlocationid |
| eventDetailsEventtypeid | `StringInput` | Eventtypeid |
| eventDetailsGroupId | `FloatInput` | Group ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsInsertDate | `DateTimeInput` | Insert Date<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsEventid | `FloatInput` | Eventid<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsEventLinkId | `FloatInput` | Linked Event<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsMasterEventId | `FloatInput` | Master Event ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventDetailsPkgEvId | `FloatInput` | Pkg Ev ID<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsPackageeventid | `FloatInput` | Packageeventid<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsParenteventid | `FloatInput` | Parenteventid<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsPkgLink | `FloatInput` | Package Link<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsRoomid | `StringInput` | Roomid |
| eventDetailsRoom | `StringInput` | Space |
| eventDetailsStartDate | `DateTimeInput` | Start Date<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsStartDateTime | `DateInput` | Start Date Time<br>`@conditionalInputPair(pair: 2)` |
| eventDetailsTracecode | `StringInput` | Tracecode |
| eventDetailsUpdateDate | `DateTimeInput` | Update Date<br>`@conditionalInputPair(pair: 2)` |
| eventpkgrevenueDetailsAllotmentid | `FloatInput` | Block ID |
| eventpkgrevenueDetailsBookId | `FloatInput` | Block ID |
| eventpkgrevenueDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventpkgrevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventpkgrevenueDetailsEventId | `FloatInput` | Event ID |
| eventpkgrevenueDetailsEventpkgrevenueid | `FloatInput` | Eventpkgrevenueid |
| eventpkgrevenueDetailsEventpkgsummaryid | `FloatInput` | Eventpkgsummaryid |
| eventpkgrevenueDetailsEventid | `FloatInput` | Eventid |
| eventpkgrevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventpkgrevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventpkgrevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventpkgrevenueDetailsPkgId | `FloatInput` | Package ID |
| eventpkgrevenueDetailsResort | `StringInput` | Package Property |
| eventpkgrevenueDetailsRevType | `StringInput` | Revenue Type |
| eventrevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventrevenueDetailsEventId | `FloatInput` | Event ID |
| eventrevenueDetailsEventrevenueid | `FloatInput` | Eventrevenueid |
| eventrevenueDetailsEventid | `FloatInput` | Eventid |
| eventrevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventrevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventrevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventrevenueDetailsPkgRevenueYn | `StringInput` | Package Revenue YN |
| eventrevenueDetailsPackagerevenueflag | `StringInput` | Packagerevenueflag |
| eventrevenueDetailsResort | `StringInput` | Property |
| eventrevenueDetailsRevType | `StringInput` | Revenue Type |
| eventrevenueDetailsRevenuetypeid | `StringInput` | Revenuetypeid |
| eventresourcenoteDetailsAllotmentid | `FloatInput` | Block ID |
| eventresourcenoteDetailsBookId | `FloatInput` | Block ID |
| eventresourcenoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventresourcenoteDetailsEventId | `FloatInput` | Event ID |
| eventresourcenoteDetailsEventresourcenoteid | `FloatInput` | Eventresourcenoteid |
| eventresourcenoteDetailsEventid | `FloatInput` | Eventid |
| eventresourcenoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventresourcenoteDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventresourcenoteDetailsNoteId | `FloatInput` | Note ID |
| eventresourcenoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventresourcenoteDetailsResort | `StringInput` | Property |
| eventresourcenoteDetailsResourceType | `StringInput` | Resource Type |
| eventroomwaitDetailsAllotmentid | `FloatInput` | Block ID |
| eventroomwaitDetailsBookId | `FloatInput` | Book ID |
| eventroomwaitDetailsCatStatus | `StringInput` | Catering Status |
| eventroomwaitDetailsEventId | `FloatInput` | Current Event |
| eventroomwaitDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventroomwaitDetailsEventid | `FloatInput` | Eventid |
| eventroomwaitDetailsEventlocationid | `StringInput` | Eventlocationid |
| eventroomwaitDetailsEventroomwaitlistid | `FloatInput` | Eventroomwaitlistid |
| eventroomwaitDetailsWaitlistdate | `DateInput` | Waitlistdate |
| eventroomwaitDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventroomwaitDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventroomwaitDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventroomwaitDetailsPriority | `FloatInput` | Priority |
| eventroomwaitDetailsResort | `StringInput` | Code to uniquely identify the Property |
| eventroomwaitDetailsRoomResort | `StringInput` | Meeting Room Property |
| eventroomwaitDetailsTurntoStatus | `StringInput` | Turn To Status |
| eventroomwaitDetailsWaitlistDate | `DateInput` | Date when Room got waitlisted |
| eventroomwaitDetailsWaitlistId | `FloatInput` | Waitlist ID |
| eventmenuDetailsBookId | `FloatInput` | Block ID |
| eventmenuDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventmenuDetailsCateringmenuid | `FloatInput` | Cateringmenuid |
| eventmenuDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventmenuDetailsEventId | `FloatInput` | Event ID |
| eventmenuDetailsEventMenuId | `FloatInput` | Menu ID |
| eventmenuDetailsEventmenuid | `FloatInput` | Eventmenuid |
| eventmenuDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventmenuDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventmenuDetailsMenuId | `FloatInput` | Menu ID |
| eventmenuDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventmenuDetailsResort | `StringInput` | Property |
| eventmenuDetailsServingStartTrunc | `DateInput` | Date Component of Serving Start Date/Time. |
| eventmenurevenueDetailsBookId | `FloatInput` | Book ID |
| eventmenurevenueDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventmenurevenueDetailsCustomYn | `StringInput` | Custom YN |
| eventmenurevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventmenurevenueDetailsEventId | `FloatInput` | Event ID |
| eventmenurevenueDetailsEventMenuId | `FloatInput` | Event Menu ID |
| eventmenurevenueDetailsEventpkgrevenueid | `FloatInput` | Eventpkgrevenueid |
| eventmenurevenueDetailsEventid | `FloatInput` | Eventid |
| eventmenurevenueDetailsEventmenuid | `FloatInput` | Eventmenuid |
| eventmenurevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventmenurevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventmenurevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventmenurevenueDetailsResort | `StringInput` | Code to uniquely identify the Property |
| eventmenurevenueDetailsRevType | `StringInput` | Revenue Type |
| eventmenurevenueDetailsRevenuetypeid | `StringInput` | Revenuetypeid |
| eventitemDetailsAllotmentid | `FloatInput` | Block ID |
| eventitemDetailsBookId | `FloatInput` | Block ID |
| eventitemDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventitemDetailsCateringitemid | `FloatInput` | Cateringitemid |
| eventitemDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventitemDetailsEventId | `FloatInput` | Event ID |
| eventitemDetailsEventItemId | `FloatInput` | Event Item ID |
| eventitemDetailsEventItemgId | `FloatInput` | EVENT_ITEMGROUP_SEQNO |
| eventitemDetailsEventitemid | `FloatInput` | Eventitemid |
| eventitemDetailsItemId | `FloatInput` | Item ID |
| eventitemDetailsItemResort | `StringInput` | Item Property |
| eventitemDetailsItemlocationid | `StringInput` | Itemlocationid |
| eventitemDetailsItemrateId | `FloatInput` | Itemrate ID |
| eventitemDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventitemDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventitemDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventitemDetailsResort | `StringInput` | Property |
| eventitemDetailsRevenueType | `StringInput` | Revenue Type |
| eventitemDetailsRevenuetypeid | `StringInput` | Revenuetypeid |
| eventnotesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventnotesDetailsEventId | `FloatInput` | Event ID |
| eventnotesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventnotesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventnotesDetailsNoteCode | `StringInput` | Note Code |
| eventnotesDetailsNoteId | `FloatInput` | Note ID |
| eventnotesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventnotesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| eventnotesDetailsUpdateUser | `FloatInput` | Update User |
| allotmentDetailsAgentContactNameId | `FloatInput` | Agent Contact Name ID |
| allotmentDetailsAgentNameId | `FloatInput` | Agent Name ID |
| allotmentDetailsAllotmentCode | `StringInput` | Block Code |
| allotmentDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| allotmentDetailsOwnerCode | `StringInput` | Block Owner Code |
| allotmentDetailsBookingId | `StringInput` | External S&C vendor booking ID and used in HYATT-mode. |
| allotmentDetailsBookingStatusOrder | `FloatInput` | Booking Status Order |
| allotmentDetailsBlockType | `StringInput` | Determines block being [G] - Group or [W] - Wholesale. |
| allotmentDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| allotmentDetailsChainCode | `StringInput` | Chain Code |
| allotmentDetailsCompanyNameId | `FloatInput` | Company Name ID |
| allotmentDetailsContactNameId | `FloatInput` | Contact Name ID |
| allotmentDetailsInsertDate | `DateTimeInput` | Created Date |
| allotmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| allotmentDetailsDueDateOrd | `DateInput` | Due Date Sorting Column. |
| allotmentDetailsEndDate | `DateInput` | End Date |
| allotmentDetailsInsertUser | `FloatInput` | Insert User |
| allotmentDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |
| allotmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| allotmentDetailsMarketCode | `StringInput` | Market  Code |
| allotmentDetailsSuperBlockId | `FloatInput` | Parent Block ID |
| allotmentDetailsSuperBlockResort | `StringInput` | Parent Resort |
| allotmentDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| allotmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| allotmentDetailsOrmsBlockClass | `StringInput` | ORMS Block Class |
| allotmentDetailsOwner | `FloatInput` | Owner |
| allotmentDetailsResort | `StringInput` | Code to uniquely identify the Property |
| allotmentDetailsRateCode | `StringInput` | Rate Code |
| allotmentDetailsGuaranteeCode | `StringInput` | Reservation Type |
| allotmentDetailsBookingStatus | `StringInput` | Room Status |
| allotmentDetailsShoulderEndDate | `DateInput` | Shoulder End |
| allotmentDetailsShoulderBeginDate | `DateInput` | Shoulder Start |
| allotmentDetailsSourceNameId | `FloatInput` | Source Name ID |
| allotmentDetailsBeginDate | `DateInput` | Start Date |
| allotmentDetailsTourcode | `StringInput` | Tour Code. |
| allotmentDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |
| allotmentDetailsUpdateDate | `DateTimeInput` | Updated Date |
| allotmentDetailsXudescription | `StringInput` | Multi Byte Description in uppercase |
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

**`conditionalInputPair(pair: 1)`**
- eventDetailsChainCode
- eventDetailsEvResort
- eventDetailsResort

**`conditionalInputPair(pair: 2)`**
- eventDetailsAllotmentid
- eventDetailsBookId
- eventDetailsAllotmentenddate
- eventDetailsEndDate
- eventDetailsEndDateTime
- eventDetailsEventId
- eventDetailsGroupId
- eventDetailsInsertDate
- eventDetailsEventid
- eventDetailsJrnupdatedttm
- eventDetailsEventLinkId
- eventDetailsLocationid
- eventDetailsMasterEventId
- eventDetailsPkgEvId
- eventDetailsPackageeventid
- eventDetailsParenteventid
- eventDetailsPkgLink
- eventDetailsStartDate
- eventDetailsStartDateTime
- eventDetailsUpdateDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query cateringEventsAndResources($input: CateringEventsAndResourcesQueryArgumentsType!) {
  cateringEventsAndResources(input: $input) @stream {
    eventDetails {
      actualAttendees
      allotmentid
      allowRegistryYn
      attendees
      averageRate
      blockEndDate
      blockID
      blockStartDate
      bookingBlockEndDate
      cTotalRevenue
      centralDiscountAmount
      centralMealType
      centralPackagePrice
      centralRentalAmount
      centralRoomClass
      centralRoomClassDescription
      chainCode
      combinationRoomYN
      dSI
      deletedFlag
      detailedPostingYn
      discountAmount
      discountPercentage
      doNotMove
      doorCard
      doorcardYn
      doorcardflag
      duration
      endDate
      endDateTime
      endTime
      endTimeWithTeardown
      evResort
      evStatusOrderBy
      evType
      eventID
      eventIDSTR
      eventLinkType
      eventName
      eventProperty
      eventStatus
      eventlocationid
      eventtypeid
      excludeFromForecastYn
      excludefromforecastflag
      expectedAttendees
      fbaId
      flatPackagePriceYN
      forecastRevenueOnlyYn
      forecastrevenueonlyflag
      groupId
      guaranteedAttendees
      hourlyRentalRateYN
      inactiveDate
      includeSetupInHourlyRateYN
      insertDate
      insertUser
      inspectedDate
      inspectedUser
      inspectedYn
      internalEventid
      isPartOfAPackageYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkedEvent
      locationID
      loudEvent
      masterEventID
      masterEventYN
      maxGroup
      mealType
      meetingRoomType
      meetingRoomYN
      minimumRevenueYn
      onTheBooksAttendees
      organizationID
      origEventId
      packageActualAttendees
      packageCode
      packageDiscountPercentage
      packageEvId
      packageExpAttendees
      packageGuaranteedAttendees
      packageID
      packageName
      packagePrice
      packageProperty
      packageeventid
      parenteventid
      pkgActAttendees
      pkgExportAttendees
      pkgGuaAttendees
      pkgLink
      pkgName
      primaryKeyID
      rentalAmount
      rentalCode
      rentalRateType
      revenueActualization
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomClassDescription
      roomType
      roomid
      roomsetuptypeid
      selectRatecodeInCentralYn
      setAttendees
      setupStyle
      setupTime
      shareableSpace
      sharedYN
      space
      spaceDescription
      startDate
      startDateTime
      startTime
      startTimeWithSetup
      statusDate
      tearDownTime
      totalAvailableRooms
      totalBlockedRooms
      totalContractedRooms
      totalOriginalRooms
      totalPickupRooms
      totalRevenue
      tracecode
      turnToStatus
      updateDate
      updateUser
      v6EventId
      waitlistYn
      waitlistflag
      wlIgnoreYn
    }
    eventPackageRevenueDetails {
      actualAttendees
      allotmentid
      blockBeginDate
      blockEndDate
      blockID
      cExchangeDate
      cExchangeRate
      centralDiscountedExpectedRevenue
      centralExpectedCost
      centralForecastRevenue
      centralPackageExpectedRevenue
      centralTotalDiscountedExpectedRevenue
      centralTotalExpectedRevenue
      centralTotalForecastRevenue
      dSI
      deletedFlag
      discountPercentage
      discountedExpectedRevenue
      eventId
      eventpkgrevenueid
      eventpkgsummaryid
      expectedAttendees
      expectedAttendees1
      expectedRevenue
      flatYN
      forecastRevenue
      guaranteedAttendees
      insertDate
      insertUser
      internalEventid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      orderBy
      organizationID
      packageExpectedCost
      packageID
      packageProperty
      primaryKeyID
      revenueGroup
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      totalDiscountedExpectedRevenue
      totalExpectedRevenue
      totalForecastRevenue
      updateDate
      updateUser
    }
    eventRevenueDetails {
      actualCost
      actualRevenue
      allotmentid
      billedCost
      billedRevenue
      blockBeginDate
      blockEndDate
      blockID
      cExchangeDate
      cExchangeRate
      centralActualCost
      centralActualRevenue
      centralBilledCost
      centralBilledRevenue
      centralExpectedCost
      centralExpectedRevenue
      centralForecastRevenue
      centralGuaranteedCost
      centralGuaranteedRevenue
      centralOnTheBooksRevenue
      centralTotalForecastedRevenue
      customYn
      customrevtypeflag
      dSI
      deletedFlag
      eventID
      eventStatus
      eventrevenueid
      expectedCost
      expectedRevenue
      flatRateYN
      flatYN
      forecastCateringRevenue
      forecastRevenue
      forecastRevenueEditedYN
      forecastRevenueOnlyYn
      guaranteedCost
      guaranteedRevenue
      ignoreForecastYN
      inactiveDate
      insertDate
      insertUser
      internalEventid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      minimumRevenueYn
      onTheBooksAttendees
      onTheBooksRevenue
      orderBy
      organizationID
      packageRevenueYN
      packagerevenueflag
      primaryKeyID
      property
      revenueGroup
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
      useForecastValueOnlyYN
    }
    eventResourceNoteDetails {
      allotmentid
      blockBeginDate
      blockEndDate
      blockID
      dSI
      deletedFlag
      eventID
      eventitempmsref
      eventmenupmsref
      eventresourceid
      eventresourcenoteid
      insertDate
      insertUser
      internalDeletedflag
      internalEventid
      internalNotetitle
      internalYn
      internalnoteflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manuallyAddedYN
      noteDetails
      noteID
      noteTitle
      order
      organizationID
      primaryKeyID
      property
      resourceId
      resourceType
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    eventRoomWaitDetails {
      accountName
      allotmentid
      attendees
      beginDate
      blockEndDate
      blockName
      bookId
      catStatus
      cateringOwner
      cateringYn
      cateringbookingstatusid
      cateringflag
      centralTotalRevenue
      currentEvent
      dSI
      deletedFlag
      doNotMoveYN
      endDate
      endDateD
      endTime
      eventName
      eventType
      eventid
      eventlocationid
      eventroomwaitlistid
      exclusiveYN
      insertDate
      insertUser
      internalWaitlistdate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      priority
      property
      rnaInsertDate
      rnaUpdateDate
      roomResort
      roomid
      shareableYN
      space
      startDate
      startTime
      status
      totalRevenue
      turnToStatus
      turntobookingstatusid
      updateDate
      updateUser
      waitlistDate
      waitlistedEvent
    }
    eventMenuDetails {
      actualCovers
      actualNumbers
      allotmentid
      billedNumbers
      blockBeginDate
      blockEndDate
      blockID
      cExchangeDate
      cExchangeRate
      cateringmenuid
      centralDiscountedPrice
      centralPrice
      complimentaryMenus
      consumptionYn
      consumptionflag
      dSI
      deletedFlag
      description
      discount
      discountedPrice
      eventID
      eventMenuID
      eventpkgsummaryid
      expectedNumbers
      foodOrBeverage
      gratuityYn
      gratuityincludedflag
      guaranteedNumber
      insertDate
      insertUser
      internalEventMenuID
      internalEventid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      menuId
      menuResort
      menulocationid
      multiChoiceYn
      multichoiceflag
      name
      numberOfSetMenus
      organizationID
      packageActual
      packageBilled
      packageExpected
      packageGuaranteed
      packageID
      personsPerTable
      price
      primaryKeyID
      property
      restrictions
      rnaInsertDate
      rnaUpdateDate
      sequenceOrder
      servingEnd
      servingEndDate
      servingEndTime
      servingEndTrunc
      servingPerPersonOrPerTable
      servingStart
      servingStartDate
      servingStartTime
      servingStartTrunc
      updateDate
      updateUser
      voucherInstructions
    }
    eventMenuRevenueDetails {
      actualCost
      actualExtraCost
      actualExtraRevenue
      actualNumber
      actualPrice
      allotmentid
      billedCost
      billedExtraCost
      billedExtraRevenue
      billedNumber
      billedPrice
      blockBeginDate
      blockEndDate
      bookId
      cExchangeDate
      cExchangeRate
      cExpectedCost
      cItemCost
      cItemPrice
      centralActualCost
      centralActualExtraCost
      centralActualExtraRevenue
      centralActualPrice
      centralBilledCost
      centralBilledExtraCost
      centralBilledExtraRevenue
      centralBilledPrice
      centralDiscountedMenuPrice
      centralDiscountedPrice
      centralExpectedExtraCost
      centralExpectedExtraRevenue
      centralGuaranteedCost
      centralGuaranteedExtraCost
      centralGuaranteedExtraRevenue
      centralGuaranteedPrice
      centralInternalQuote
      centralMenuPrice
      complimentaryNumber
      customYN
      customrevtypeflag
      dSI
      deletedFlag
      discountedMenuPrice
      discountedPrice
      eventId
      eventMenuId
      eventpkgrevenueid
      expectedCost
      expectedExtraCost
      expectedExtraRevenue
      expectedNumber
      guaranteedCost
      guaranteedExtraCost
      guaranteedExtraRevenue
      guaranteedNumber
      guaranteedPrice
      insertDate
      insertUser
      internalEventid
      internalEventmenuid
      internalQuote
      itemCost
      itemPrice
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      menuDiscountPercentage
      menuPrice
      orderBy
      organizationID
      primaryKeyID
      property
      revGroup
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    eventItemDetails {
      actualExternalCost
      actualExternalQuantity
      actualInternalCost
      actualInternalQuantity
      actualQuantity
      actualRevenue
      additionalDetails
      allotmentid
      billedQuantity
      blockBeginDate
      blockEndDate
      blockID
      cExchangeDate
      cExchangeRate
      cGuaranteedRevenue
      cateringitemid
      centralActualExternalCost
      centralActualInternalCost
      centralActualRevenue
      centralDiscountedPrice
      centralExpectedInternalCost
      centralExpectedRevenue
      centralExternalCost
      centralItemClassName
      centralPrice
      customYn
      customitemflag
      dSI
      deletedFlag
      departmentID
      description
      discount
      discountableYN
      discountedPrice
      endDateTrunc
      endTime
      eventID
      eventItemID
      eventItemgId
      eventpkgsummaryid
      expectedExternalCost
      expectedInternalCost
      expectedRevenue
      externalOrder
      externalQuantity
      guaranteedQuantity
      guaranteedRevenue
      hourlyYn
      hourlycostflag
      insertDate
      insertUser
      internalEventid
      internalEventitemid
      internalQuantity
      itemClassID
      itemClassName
      itemID
      itemName
      itemResort
      itemlocationid
      itemrateId
      itmaId
      itmcId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      order
      orderExternalYN
      organizationID
      packageID
      price
      priceCode
      primaryKeyID
      property
      quantity
      quickInsertCode
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      setUpTime
      showItemOnEventOrderYN
      showOnBEOYN
      startDateTrunc
      startTime
      tearDownTime
      updateDate
      updateUser
      vendorID
      vendorName
    }
    eventNotesDetails {
      chainCode
      dSI
      deletedFlag
      eventID
      insertDate
      insertUser
      internalYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      note
      noteCode
      noteId
      noteTitle
      order
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    blockDetails {
      actionId
      actualAverageRoomRate
      actualFBRevenue
      actualOtherRevenue
      actualRoomNightsSold
      actualRoomRevenue
      addInfo
      agentContactNameId
      agentNameId
      agentprofileid
      allAliases
      allBlockOwners
      allCateringOwners
      allCompanyContacts
      allRateCodes
      allRoomOwners
      allRoomPools
      allRoomTypes
      allSourceContacts
      allTravelAgentContacts
      allotmentOrigin
      allotmentType
      allotmentcurrencyid
      allotmentid
      allowPickup
      alternateBlockName
      alternateDates
      arrivalTime
      attachmentURL
      attendeesGuaranteed
      autoLoadForecastYn
      averageRate
      bEOLastPrint
      beginDateOriginal
      blockAlias
      blockCode
      blockDateActual
      blockDateDefinite
      blockDateProspect
      blockDateTentative
      blockDescription
      blockID
      blockMode
      blockOwnerCode
      blockOwnerFullName
      blockPackage
      blockPackageDescription
      blockStatus
      blockStatusDescription
      blockTypeCode
      blockTypeCodeDescription
      blockpackageid
      bookingId
      bookingMethodOrderBy
      bookingStatusOrder
      bookingType
      bookingTypeDescription
      bookingmethodInactiveDate
      bookingsourceid
      bookingstatusid
      bookingtypeid
      breakfastDescription
      breakfastInclPrice
      breakfastInclYn
      breakfastIncluded
      breakfastPrice
      bwiLeadId
      bwiUrl
      cBreakfastInclPrice
      cBreakfastPrice
      cCompRoomValue
      cDoubleRoomSupplementPrice
      cExchangeDate
      cExchangeRate
      cFBCommission1
      cFBCommission2
      cPorteragePrice
      cRoomCommission1
      cRoomCommission2
      cServiceCharge
      cServiceFee
      cRSGtdYn
      cancelRule
      canceldestinationid
      cancellationDestination
      cancellationDestinationDescription
      cancellationNumber
      cancellationPenaltyAmount
      cancellationreasonid
      catCutoff
      catDateProspect
      catOwner
      catOwnerProperty
      catReturnToInventory
      catStartingStatus
      catcurrencyid
      cateringCancellationDate
      cateringCancellationDescription
      cateringCancellationNumber
      cateringCancellationReason
      cateringCurrency
      cateringDateActual
      cateringDecisionDate
      cateringDeductInventory
      cateringExchangeRate
      cateringFollowupDate
      cateringOnlyYN
      cateringOrderBy
      cateringOwnerCode
      cateringOwnerFullName
      cateringPkgsYn
      cateringQuoteCurrency
      cateringStatus
      cateringStatusColor
      cateringStatusDescription
      cateringStatusType
      cateringcancelreasonid
      cateringcurrencyid
      cateringowneremployeeid
      cateringquotecurrencyid
      cateringstatusid
      cenralFBRevenue
      centralActualAverageRoomRate
      centralActualFBRevenue
      centralActualOtherRevenue
      centralActualRoomRevenue
      centralAverageRoomRate
      centralBlockPackage
      centralBlockPackageDescription
      centralBlockStatus
      centralBlockStatusDescription
      centralBlockTypeCode
      centralBlockTypeCodeDescription
      centralBookingType
      centralBookingTypeDescription
      centralCancellationDestination
      centralCancellationDestinationDescription
      centralCancellationPenaltyAmount
      centralCateringStatus
      centralCateringStatusDescription
      centralConversionCode
      centralCoversionCodeDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralItemsForThisBlock
      centralMarketDescription
      centralMarketCode
      centralMeetingBudget
      centralMeetingRevenue
      centralOriginCode
      centralOriginCodeDescription
      centralOtherRevenue
      centralOwner
      centralPayment
      centralPaymentDescription
      centralRankingCode
      centralRankingCodeDescription
      centralReservationMethodCode
      centralReservationMethodDescription
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralSourceCode
      centralSourceCodeDescription
      centralTaxAmount
      chainCode
      channelid
      code
      comAddress
      comAddress2
      comAddress3
      comMethod
      comMethod2
      comMethod3
      commissionAmount
      commissionablePerc
      commissionableYn
      compPerStayYn
      compRoomValue
      compRooms
      compRoomsFixedYn
      companyAll
      companyNameId
      companyprofileid
      competition
      contactNameId
      contactprofileid
      contractNumber
      controlBlockLocally
      conversionCode
      coversionCodeDescription
      createdBy
      createdDate
      createdAsOpportunityYN
      creditCardId
      currency
      dSI
      dateAcl
      dateCfl
      dateDefinite
      dateLsl
      dateOpenedForPickup
      datePel
      dateTdl
      dateTentative
      dblRoomSupplementPrice
      deductInventory
      defaultPmReservationNameId
      deletedflag
      departureTime
      description
      distributed
      distributedDate
      dmlSeqNumber
      doubleRoomSupplementYN
      downloadDate
      downloadResort
      downloadSrep
      dueDate
      dueDateOrd
      endDate
      endDateOriginal
      endbusinessdate
      eventAttendees
      exchangePostingType
      exchangeRate
      exclusionMessage
      externalReference
      externalRfpId
      externalRfpSystem
      externallyLocked
      fBRevenue
      fbAgendaCurrency
      fbCommission1
      fbCommission2
      fitContractMode
      fitDiscountLevel
      fitDiscountPerc
      fitdiscounttype
      flatRateYn
      followupDate
      fsOverbookingYn
      functionType
      giid
      greekContractNr
      groupAccountID
      guaranteecodeid
      guaranteedRate
      guaranteedYN
      hideacctinfoflag
      hlxCanxNoticeDays
      hlxCommissionableYn
      hlxDdSecuredYn
      hlxDepositDays
      hlxDiSecuredYn
      hlxHousinginfoSecuredYn
      hlxRateAllSecuredYn
      hlxRatesGnrSecuredYn
      hlxReturnEachDayYn
      inactiveDate
      inactiveflag
      industryCode
      industryCodeDescription
      info
      informationBoard
      insertUser
      inventoryControl
      inventoryCutOffDate
      inventoryCutOffDays
      isacOpptyId
      items
      itemsForThisBlock
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepLeadControlYN
      laptopChange
      leadOrigin
      leadSentYN
      leadSource
      leadType
      leadchangeBypropertyYn
      leaderrorflag
      leadisnewflag
      leadoriginid
      leadreceivedflag
      leadsend
      leadsend2
      leadsend3
      leadserverpendingflag
      leadsourceid
      leadstatus
      linkDate
      locationID
      lostTo
      mainmarket
      mainmarketid
      manuallyCutoffYN
      marEventType
      marHouseProtectYn
      marRollEndDateYn
      marketCode
      marketDescription
      marketid
      masterBlockID
      masterBlockProperty
      masterNameId
      meetingBudget
      meetingRevenue
      offsetType
      orderBy
      organizationID
      origAllotmentHeaderId
      originCode
      originCodeDescription
      originalBeginDateHolidex
      originalEndDate
      originalRateCode
      originalStartDate
      originalratecodeid
      ormsBlockClass
      ormsFinalBlock
      ormsForecastReviewReason
      ormsTransientBlock
      otherRevenue
      owner
      ownerResort
      owneremployeeid
      ownerlocationd
      parentallotmentid
      payment
      paymentDescription
      paymentmethodid
      personsPerRoom
      porterageIncluded
      porteragePrice
      potAverageRoomRate
      potFbRevenue1
      potOtherRevenue1
      potRoomNights
      potRoomRevenue1
      primaryKeyID
      printRate
      profileId
      program
      property
      proposalCombineEventsYn
      proposalDecisionSelection
      proposalFollowupSelection
      proposalInclAltNamesYn
      proposalOwnerSelection
      proposalSentDate
      proposalShowEventpriceYn
      proposalShowPmsRoomTypeYn
      proposalShowSpacenameYn
      proposalSpaceMeasurement
      proposalViewToken
      publishRatesYn
      rankingCode
      rankingCodeDescription
      rateCode
      rateOverride
      rateOverrideReason
      rateProtect
      rateTier
      ratecodeid
      readyForDistribution
      regeneratedLeadYn
      repBookingmethodOrderby
      repBsOrderBy
      repCatOrderBy
      replDate
      replVia
      replstatus
      replyBy
      representative
      reservationMethod
      reservationType
      reservationTypeDescription
      reservationid
      reserveInventoryYN
      resortBooked
      resourceDiscountPercent
      respTime
      respTimeCode
      returnToInventory
      rivMarketSegment
      rnaInsertDate
      rnaUpdateDate
      roomCommission1
      roomCommission2
      roomNightsSold
      roomOwnerCode
      roomOwnerFullName
      roomRevenue
      roomRevenueTransactionCode
      roomStatus
      roomingListDue
      roomingListRules
      roomsCancellationDate
      roomsCancellationReason
      roomsCancellationReasonDescription
      roomsCurrency
      roomsDecisionDate
      roomsExchangeRate
      roomsOwner
      roomsOwnerResort
      roomsPerDay
      roomsQuoteCurrency
      roomsowneremployeeid
      salesId
      sbegindate
      scQuoteId
      sellThruYn
      sendToCentralYn
      senddate
      sentBy
      sentDate
      sentVia
      serviceCharge
      serviceFee
      serviceFeeYn
      serviceInclYn
      servicePerc
      shoulderEnd
      shoulderStart
      showRateAmountYN
      snapshotSetup
      sourceCode
      sourceCodeDescription
      sourceContactAll
      sourceNameId
      sourceid
      sourceprofprofileid
      startDate
      startingStatus
      status
      statusColor
      statusType
      subAllocationYN
      superSearchIndexText
      suppressRate
      syncContractYn
      synchronize
      taxAmount
      taxIncludedPerc
      taxIncludedYn
      taxType
      taxtypeid
      tbdRates
      tdlReason
      tentativeLevel
      tlpResponseid
      tlpUrl
      tourCode
      traceCode
      traceDescription
      trackChangesYN
      travelAgentAll
      travelAgentRecordLocator
      turndownreasonid
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
      ualias
      udescription
      updateDateExternal
      updateUser
      updatedBy
      updatedDate
      uploadDate
      webBookable
      webOverbookYN
      xudescription
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
event_details_schema = {
    'actualAttendees': pl.Float64,
    'allotmentid': pl.Float64,
    'allowRegistryYn': pl.Utf8,
    'attendees': pl.Float64,
    'averageRate': pl.Float64,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockStartDate': pl.Utf8,
    'bookingBlockEndDate': pl.Utf8,
    'cTotalRevenue': pl.Float64,
    'centralDiscountAmount': pl.Float64,
    'centralMealType': pl.Utf8,
    'centralPackagePrice': pl.Float64,
    'centralRentalAmount': pl.Float64,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'combinationRoomYN': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'detailedPostingYn': pl.Utf8,
    'discountAmount': pl.Float64,
    'discountPercentage': pl.Float64,
    'doNotMove': pl.Utf8,
    'doorCard': pl.Utf8,
    'doorcardYn': pl.Utf8,
    'doorcardflag': pl.Utf8,
    'duration': pl.Float64,
    'endDate': pl.Utf8,
    'endDateTime': pl.Utf8,
    'endTime': pl.Utf8,
    'endTimeWithTeardown': pl.Utf8,
    'evResort': pl.Utf8,
    'evStatusOrderBy': pl.Float64,
    'evType': pl.Utf8,
    'eventID': pl.Float64,
    'eventIDSTR': pl.Utf8,
    'eventLinkType': pl.Utf8,
    'eventName': pl.Utf8,
    'eventProperty': pl.Utf8,
    'eventStatus': pl.Utf8,
    'eventlocationid': pl.Utf8,
    'eventtypeid': pl.Utf8,
    'excludeFromForecastYn': pl.Utf8,
    'excludefromforecastflag': pl.Utf8,
    'expectedAttendees': pl.Float64,
    'fbaId': pl.Float64,
    'flatPackagePriceYN': pl.Utf8,
    'forecastRevenueOnlyYn': pl.Utf8,
    'forecastrevenueonlyflag': pl.Utf8,
    'groupId': pl.Float64,
    'guaranteedAttendees': pl.Float64,
    'hourlyRentalRateYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'includeSetupInHourlyRateYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'inspectedDate': pl.Utf8,
    'inspectedUser': pl.Float64,
    'inspectedYn': pl.Utf8,
    'internalEventid': pl.Float64,
    'isPartOfAPackageYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkedEvent': pl.Float64,
    'locationID': pl.Utf8,
    'loudEvent': pl.Utf8,
    'masterEventID': pl.Float64,
    'masterEventYN': pl.Utf8,
    'maxGroup': pl.Float64,
    'mealType': pl.Utf8,
    'meetingRoomType': pl.Utf8,
    'meetingRoomYN': pl.Utf8,
    'minimumRevenueYn': pl.Utf8,
    'onTheBooksAttendees': pl.Float64,
    'organizationID': pl.Int64,
    'origEventId': pl.Float64,
    'packageActualAttendees': pl.Float64,
    'packageCode': pl.Utf8,
    'packageDiscountPercentage': pl.Float64,
    'packageEvId': pl.Float64,
    'packageExpAttendees': pl.Float64,
    'packageGuaranteedAttendees': pl.Float64,
    'packageID': pl.Float64,
    'packageName': pl.Utf8,
    'packagePrice': pl.Float64,
    'packageProperty': pl.Utf8,
    'packageeventid': pl.Float64,
    'parenteventid': pl.Float64,
    'pkgActAttendees': pl.Float64,
    'pkgExportAttendees': pl.Float64,
    'pkgGuaAttendees': pl.Float64,
    'pkgLink': pl.Float64,
    'pkgName': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rentalAmount': pl.Float64,
    'rentalCode': pl.Utf8,
    'rentalRateType': pl.Utf8,
    'revenueActualization': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomType': pl.Utf8,
    'roomid': pl.Utf8,
    'roomsetuptypeid': pl.Utf8,
    'selectRatecodeInCentralYn': pl.Utf8,
    'setAttendees': pl.Float64,
    'setupStyle': pl.Utf8,
    'setupTime': pl.Float64,
    'shareableSpace': pl.Utf8,
    'sharedYN': pl.Utf8,
    'space': pl.Utf8,
    'spaceDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'startDateTime': pl.Utf8,
    'startTime': pl.Utf8,
    'startTimeWithSetup': pl.Utf8,
    'statusDate': pl.Utf8,
    'tearDownTime': pl.Float64,
    'totalAvailableRooms': pl.Float64,
    'totalBlockedRooms': pl.Float64,
    'totalContractedRooms': pl.Float64,
    'totalOriginalRooms': pl.Float64,
    'totalPickupRooms': pl.Float64,
    'totalRevenue': pl.Float64,
    'tracecode': pl.Utf8,
    'turnToStatus': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'v6EventId': pl.Float64,
    'waitlistYn': pl.Utf8,
    'waitlistflag': pl.Utf8,
    'wlIgnoreYn': pl.Utf8,
}
```
```python
event_package_revenue_details_schema = {
    'actualAttendees': pl.Float64,
    'allotmentid': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralDiscountedExpectedRevenue': pl.Float64,
    'centralExpectedCost': pl.Float64,
    'centralForecastRevenue': pl.Float64,
    'centralPackageExpectedRevenue': pl.Float64,
    'centralTotalDiscountedExpectedRevenue': pl.Float64,
    'centralTotalExpectedRevenue': pl.Float64,
    'centralTotalForecastRevenue': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'discountPercentage': pl.Float64,
    'discountedExpectedRevenue': pl.Float64,
    'eventId': pl.Float64,
    'eventpkgrevenueid': pl.Float64,
    'eventpkgsummaryid': pl.Float64,
    'expectedAttendees': pl.Float64,
    'expectedAttendees1': pl.Float64,
    'expectedRevenue': pl.Float64,
    'flatYN': pl.Utf8,
    'forecastRevenue': pl.Float64,
    'guaranteedAttendees': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'packageExpectedCost': pl.Float64,
    'packageID': pl.Float64,
    'packageProperty': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'revenueGroup': pl.Utf8,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'totalDiscountedExpectedRevenue': pl.Float64,
    'totalExpectedRevenue': pl.Float64,
    'totalForecastRevenue': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
event_revenue_details_schema = {
    'actualCost': pl.Float64,
    'actualRevenue': pl.Float64,
    'allotmentid': pl.Float64,
    'billedCost': pl.Float64,
    'billedRevenue': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralActualCost': pl.Float64,
    'centralActualRevenue': pl.Float64,
    'centralBilledCost': pl.Float64,
    'centralBilledRevenue': pl.Float64,
    'centralExpectedCost': pl.Float64,
    'centralExpectedRevenue': pl.Float64,
    'centralForecastRevenue': pl.Float64,
    'centralGuaranteedCost': pl.Float64,
    'centralGuaranteedRevenue': pl.Float64,
    'centralOnTheBooksRevenue': pl.Float64,
    'centralTotalForecastedRevenue': pl.Float64,
    'customYn': pl.Utf8,
    'customrevtypeflag': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'eventID': pl.Float64,
    'eventStatus': pl.Utf8,
    'eventrevenueid': pl.Float64,
    'expectedCost': pl.Float64,
    'expectedRevenue': pl.Float64,
    'flatRateYN': pl.Utf8,
    'flatYN': pl.Utf8,
    'forecastCateringRevenue': pl.Float64,
    'forecastRevenue': pl.Float64,
    'forecastRevenueEditedYN': pl.Utf8,
    'forecastRevenueOnlyYn': pl.Utf8,
    'guaranteedCost': pl.Float64,
    'guaranteedRevenue': pl.Float64,
    'ignoreForecastYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'minimumRevenueYn': pl.Utf8,
    'onTheBooksAttendees': pl.Float64,
    'onTheBooksRevenue': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'packageRevenueYN': pl.Utf8,
    'packagerevenueflag': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'revenueGroup': pl.Utf8,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'useForecastValueOnlyYN': pl.Utf8,
}
```
```python
event_resource_note_details_schema = {
    'allotmentid': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'eventID': pl.Float64,
    'eventitempmsref': pl.Float64,
    'eventmenupmsref': pl.Float64,
    'eventresourceid': pl.Float64,
    'eventresourcenoteid': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalEventid': pl.Float64,
    'internalNotetitle': pl.Utf8,
    'internalYn': pl.Utf8,
    'internalnoteflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manuallyAddedYN': pl.Utf8,
    'noteDetails': pl.Utf8,
    'noteID': pl.Float64,
    'noteTitle': pl.Utf8,
    'order': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'resourceId': pl.Float64,
    'resourceType': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
event_room_wait_details_schema = {
    'accountName': pl.Utf8,
    'allotmentid': pl.Float64,
    'attendees': pl.Float64,
    'beginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockName': pl.Utf8,
    'bookId': pl.Float64,
    'catStatus': pl.Utf8,
    'cateringOwner': pl.Utf8,
    'cateringYn': pl.Utf8,
    'cateringbookingstatusid': pl.Utf8,
    'cateringflag': pl.Utf8,
    'centralTotalRevenue': pl.Float64,
    'currentEvent': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateD': pl.Utf8,
    'endTime': pl.Utf8,
    'eventName': pl.Utf8,
    'eventType': pl.Utf8,
    'eventid': pl.Float64,
    'eventlocationid': pl.Utf8,
    'eventroomwaitlistid': pl.Float64,
    'exclusiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalWaitlistdate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'priority': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomid': pl.Utf8,
    'shareableYN': pl.Utf8,
    'space': pl.Utf8,
    'startDate': pl.Utf8,
    'startTime': pl.Utf8,
    'status': pl.Utf8,
    'totalRevenue': pl.Float64,
    'turnToStatus': pl.Utf8,
    'turntobookingstatusid': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'waitlistDate': pl.Utf8,
    'waitlistedEvent': pl.Float64,
}
```
```python
event_menu_details_schema = {
    'actualCovers': pl.Float64,
    'actualNumbers': pl.Float64,
    'allotmentid': pl.Float64,
    'billedNumbers': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cateringmenuid': pl.Float64,
    'centralDiscountedPrice': pl.Float64,
    'centralPrice': pl.Float64,
    'complimentaryMenus': pl.Float64,
    'consumptionYn': pl.Utf8,
    'consumptionflag': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'discount': pl.Float64,
    'discountedPrice': pl.Float64,
    'eventID': pl.Float64,
    'eventMenuID': pl.Float64,
    'eventpkgsummaryid': pl.Float64,
    'expectedNumbers': pl.Float64,
    'foodOrBeverage': pl.Utf8,
    'gratuityYn': pl.Utf8,
    'gratuityincludedflag': pl.Utf8,
    'guaranteedNumber': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventMenuID': pl.Float64,
    'internalEventid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'menuId': pl.Float64,
    'menuResort': pl.Utf8,
    'menulocationid': pl.Utf8,
    'multiChoiceYn': pl.Utf8,
    'multichoiceflag': pl.Utf8,
    'name': pl.Utf8,
    'numberOfSetMenus': pl.Float64,
    'organizationID': pl.Int64,
    'packageActual': pl.Float64,
    'packageBilled': pl.Float64,
    'packageExpected': pl.Float64,
    'packageGuaranteed': pl.Float64,
    'packageID': pl.Float64,
    'personsPerTable': pl.Float64,
    'price': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'restrictions': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequenceOrder': pl.Float64,
    'servingEnd': pl.Utf8,
    'servingEndDate': pl.Utf8,
    'servingEndTime': pl.Utf8,
    'servingEndTrunc': pl.Utf8,
    'servingPerPersonOrPerTable': pl.Utf8,
    'servingStart': pl.Utf8,
    'servingStartDate': pl.Utf8,
    'servingStartTime': pl.Utf8,
    'servingStartTrunc': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'voucherInstructions': pl.Utf8,
}
```
```python
event_menu_revenue_details_schema = {
    'actualCost': pl.Float64,
    'actualExtraCost': pl.Float64,
    'actualExtraRevenue': pl.Float64,
    'actualNumber': pl.Float64,
    'actualPrice': pl.Float64,
    'allotmentid': pl.Float64,
    'billedCost': pl.Float64,
    'billedExtraCost': pl.Float64,
    'billedExtraRevenue': pl.Float64,
    'billedNumber': pl.Float64,
    'billedPrice': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'bookId': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cExpectedCost': pl.Float64,
    'cItemCost': pl.Float64,
    'cItemPrice': pl.Float64,
    'centralActualCost': pl.Float64,
    'centralActualExtraCost': pl.Float64,
    'centralActualExtraRevenue': pl.Float64,
    'centralActualPrice': pl.Float64,
    'centralBilledCost': pl.Float64,
    'centralBilledExtraCost': pl.Float64,
    'centralBilledExtraRevenue': pl.Float64,
    'centralBilledPrice': pl.Float64,
    'centralDiscountedMenuPrice': pl.Float64,
    'centralDiscountedPrice': pl.Float64,
    'centralExpectedExtraCost': pl.Float64,
    'centralExpectedExtraRevenue': pl.Float64,
    'centralGuaranteedCost': pl.Float64,
    'centralGuaranteedExtraCost': pl.Float64,
    'centralGuaranteedExtraRevenue': pl.Float64,
    'centralGuaranteedPrice': pl.Float64,
    'centralInternalQuote': pl.Float64,
    'centralMenuPrice': pl.Float64,
    'complimentaryNumber': pl.Float64,
    'customYN': pl.Utf8,
    'customrevtypeflag': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'discountedMenuPrice': pl.Float64,
    'discountedPrice': pl.Float64,
    'eventId': pl.Float64,
    'eventMenuId': pl.Float64,
    'eventpkgrevenueid': pl.Float64,
    'expectedCost': pl.Float64,
    'expectedExtraCost': pl.Float64,
    'expectedExtraRevenue': pl.Float64,
    'expectedNumber': pl.Float64,
    'guaranteedCost': pl.Float64,
    'guaranteedExtraCost': pl.Float64,
    'guaranteedExtraRevenue': pl.Float64,
    'guaranteedNumber': pl.Float64,
    'guaranteedPrice': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'internalEventmenuid': pl.Float64,
    'internalQuote': pl.Float64,
    'itemCost': pl.Float64,
    'itemPrice': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'menuDiscountPercentage': pl.Float64,
    'menuPrice': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'revGroup': pl.Utf8,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
event_item_details_schema = {
    'actualExternalCost': pl.Float64,
    'actualExternalQuantity': pl.Float64,
    'actualInternalCost': pl.Float64,
    'actualInternalQuantity': pl.Float64,
    'actualQuantity': pl.Float64,
    'actualRevenue': pl.Float64,
    'additionalDetails': pl.Utf8,
    'allotmentid': pl.Float64,
    'billedQuantity': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'blockID': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGuaranteedRevenue': pl.Float64,
    'cateringitemid': pl.Float64,
    'centralActualExternalCost': pl.Float64,
    'centralActualInternalCost': pl.Float64,
    'centralActualRevenue': pl.Float64,
    'centralDiscountedPrice': pl.Float64,
    'centralExpectedInternalCost': pl.Float64,
    'centralExpectedRevenue': pl.Float64,
    'centralExternalCost': pl.Float64,
    'centralItemClassName': pl.Utf8,
    'centralPrice': pl.Float64,
    'customYn': pl.Utf8,
    'customitemflag': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'departmentID': pl.Utf8,
    'description': pl.Utf8,
    'discount': pl.Float64,
    'discountableYN': pl.Utf8,
    'discountedPrice': pl.Float64,
    'endDateTrunc': pl.Utf8,
    'endTime': pl.Utf8,
    'eventID': pl.Float64,
    'eventItemID': pl.Float64,
    'eventItemgId': pl.Float64,
    'eventpkgsummaryid': pl.Float64,
    'expectedExternalCost': pl.Float64,
    'expectedInternalCost': pl.Float64,
    'expectedRevenue': pl.Float64,
    'externalOrder': pl.Utf8,
    'externalQuantity': pl.Float64,
    'guaranteedQuantity': pl.Float64,
    'guaranteedRevenue': pl.Float64,
    'hourlyYn': pl.Utf8,
    'hourlycostflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'internalEventitemid': pl.Float64,
    'internalQuantity': pl.Float64,
    'itemClassID': pl.Float64,
    'itemClassName': pl.Utf8,
    'itemID': pl.Float64,
    'itemName': pl.Utf8,
    'itemResort': pl.Utf8,
    'itemlocationid': pl.Utf8,
    'itemrateId': pl.Float64,
    'itmaId': pl.Float64,
    'itmcId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'order': pl.Float64,
    'orderExternalYN': pl.Utf8,
    'organizationID': pl.Int64,
    'packageID': pl.Float64,
    'price': pl.Float64,
    'priceCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'quickInsertCode': pl.Utf8,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'setUpTime': pl.Float64,
    'showItemOnEventOrderYN': pl.Utf8,
    'showOnBEOYN': pl.Utf8,
    'startDateTrunc': pl.Utf8,
    'startTime': pl.Utf8,
    'tearDownTime': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vendorID': pl.Float64,
    'vendorName': pl.Utf8,
}
```
```python
event_notes_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'eventID': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'note': pl.Utf8,
    'noteCode': pl.Utf8,
    'noteId': pl.Float64,
    'noteTitle': pl.Utf8,
    'order': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
block_details_schema = {
    'actionId': pl.Float64,
    'actualAverageRoomRate': pl.Float64,
    'actualFBRevenue': pl.Float64,
    'actualOtherRevenue': pl.Float64,
    'actualRoomNightsSold': pl.Float64,
    'actualRoomRevenue': pl.Float64,
    'addInfo': pl.Utf8,
    'agentContactNameId': pl.Float64,
    'agentNameId': pl.Float64,
    'agentprofileid': pl.Float64,
    'allAliases': pl.Utf8,
    'allBlockOwners': pl.Utf8,
    'allCateringOwners': pl.Utf8,
    'allCompanyContacts': pl.Utf8,
    'allRateCodes': pl.Utf8,
    'allRoomOwners': pl.Utf8,
    'allRoomPools': pl.Utf8,
    'allRoomTypes': pl.Utf8,
    'allSourceContacts': pl.Utf8,
    'allTravelAgentContacts': pl.Utf8,
    'allotmentOrigin': pl.Utf8,
    'allotmentType': pl.Utf8,
    'allotmentcurrencyid': pl.Utf8,
    'allotmentid': pl.Float64,
    'allowPickup': pl.Utf8,
    'alternateBlockName': pl.Utf8,
    'alternateDates': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'attachmentURL': pl.Utf8,
    'attendeesGuaranteed': pl.Float64,
    'autoLoadForecastYn': pl.Utf8,
    'averageRate': pl.Float64,
    'bEOLastPrint': pl.Utf8,
    'beginDateOriginal': pl.Utf8,
    'blockAlias': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockDateActual': pl.Utf8,
    'blockDateDefinite': pl.Utf8,
    'blockDateProspect': pl.Utf8,
    'blockDateTentative': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockID': pl.Float64,
    'blockMode': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockOwnerFullName': pl.Utf8,
    'blockPackage': pl.Utf8,
    'blockPackageDescription': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockStatusDescription': pl.Utf8,
    'blockTypeCode': pl.Utf8,
    'blockTypeCodeDescription': pl.Utf8,
    'blockpackageid': pl.Utf8,
    'bookingId': pl.Utf8,
    'bookingMethodOrderBy': pl.Float64,
    'bookingStatusOrder': pl.Float64,
    'bookingType': pl.Utf8,
    'bookingTypeDescription': pl.Utf8,
    'bookingmethodInactiveDate': pl.Utf8,
    'bookingsourceid': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'bookingtypeid': pl.Utf8,
    'breakfastDescription': pl.Utf8,
    'breakfastInclPrice': pl.Float64,
    'breakfastInclYn': pl.Utf8,
    'breakfastIncluded': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'bwiLeadId': pl.Utf8,
    'bwiUrl': pl.Utf8,
    'cBreakfastInclPrice': pl.Float64,
    'cBreakfastPrice': pl.Float64,
    'cCompRoomValue': pl.Float64,
    'cDoubleRoomSupplementPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFBCommission1': pl.Float64,
    'cFBCommission2': pl.Float64,
    'cPorteragePrice': pl.Float64,
    'cRoomCommission1': pl.Float64,
    'cRoomCommission2': pl.Float64,
    'cServiceCharge': pl.Float64,
    'cServiceFee': pl.Float64,
    'cRSGtdYn': pl.Utf8,
    'cancelRule': pl.Utf8,
    'canceldestinationid': pl.Utf8,
    'cancellationDestination': pl.Utf8,
    'cancellationDestinationDescription': pl.Utf8,
    'cancellationNumber': pl.Float64,
    'cancellationPenaltyAmount': pl.Float64,
    'cancellationreasonid': pl.Utf8,
    'catCutoff': pl.Utf8,
    'catDateProspect': pl.Utf8,
    'catOwner': pl.Float64,
    'catOwnerProperty': pl.Utf8,
    'catReturnToInventory': pl.Utf8,
    'catStartingStatus': pl.Utf8,
    'catcurrencyid': pl.Utf8,
    'cateringCancellationDate': pl.Utf8,
    'cateringCancellationDescription': pl.Utf8,
    'cateringCancellationNumber': pl.Float64,
    'cateringCancellationReason': pl.Utf8,
    'cateringCurrency': pl.Utf8,
    'cateringDateActual': pl.Utf8,
    'cateringDecisionDate': pl.Utf8,
    'cateringDeductInventory': pl.Utf8,
    'cateringExchangeRate': pl.Float64,
    'cateringFollowupDate': pl.Utf8,
    'cateringOnlyYN': pl.Utf8,
    'cateringOrderBy': pl.Float64,
    'cateringOwnerCode': pl.Utf8,
    'cateringOwnerFullName': pl.Utf8,
    'cateringPkgsYn': pl.Utf8,
    'cateringQuoteCurrency': pl.Utf8,
    'cateringStatus': pl.Utf8,
    'cateringStatusColor': pl.Utf8,
    'cateringStatusDescription': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringcancelreasonid': pl.Float64,
    'cateringcurrencyid': pl.Utf8,
    'cateringowneremployeeid': pl.Float64,
    'cateringquotecurrencyid': pl.Utf8,
    'cateringstatusid': pl.Utf8,
    'cenralFBRevenue': pl.Float64,
    'centralActualAverageRoomRate': pl.Float64,
    'centralActualFBRevenue': pl.Float64,
    'centralActualOtherRevenue': pl.Float64,
    'centralActualRoomRevenue': pl.Float64,
    'centralAverageRoomRate': pl.Float64,
    'centralBlockPackage': pl.Utf8,
    'centralBlockPackageDescription': pl.Utf8,
    'centralBlockStatus': pl.Utf8,
    'centralBlockStatusDescription': pl.Utf8,
    'centralBlockTypeCode': pl.Utf8,
    'centralBlockTypeCodeDescription': pl.Utf8,
    'centralBookingType': pl.Utf8,
    'centralBookingTypeDescription': pl.Utf8,
    'centralCancellationDestination': pl.Utf8,
    'centralCancellationDestinationDescription': pl.Utf8,
    'centralCancellationPenaltyAmount': pl.Float64,
    'centralCateringStatus': pl.Utf8,
    'centralCateringStatusDescription': pl.Utf8,
    'centralConversionCode': pl.Utf8,
    'centralCoversionCodeDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralItemsForThisBlock': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMeetingBudget': pl.Float64,
    'centralMeetingRevenue': pl.Float64,
    'centralOriginCode': pl.Utf8,
    'centralOriginCodeDescription': pl.Utf8,
    'centralOtherRevenue': pl.Float64,
    'centralOwner': pl.Utf8,
    'centralPayment': pl.Utf8,
    'centralPaymentDescription': pl.Utf8,
    'centralRankingCode': pl.Utf8,
    'centralRankingCodeDescription': pl.Utf8,
    'centralReservationMethodCode': pl.Utf8,
    'centralReservationMethodDescription': pl.Utf8,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceCodeDescription': pl.Utf8,
    'centralTaxAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'channelid': pl.Utf8,
    'code': pl.Utf8,
    'comAddress': pl.Utf8,
    'comAddress2': pl.Utf8,
    'comAddress3': pl.Utf8,
    'comMethod': pl.Utf8,
    'comMethod2': pl.Utf8,
    'comMethod3': pl.Utf8,
    'commissionAmount': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'compPerStayYn': pl.Utf8,
    'compRoomValue': pl.Float64,
    'compRooms': pl.Float64,
    'compRoomsFixedYn': pl.Utf8,
    'companyAll': pl.Utf8,
    'companyNameId': pl.Float64,
    'companyprofileid': pl.Float64,
    'competition': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactprofileid': pl.Float64,
    'contractNumber': pl.Utf8,
    'controlBlockLocally': pl.Utf8,
    'conversionCode': pl.Utf8,
    'coversionCodeDescription': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdAsOpportunityYN': pl.Utf8,
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'dateAcl': pl.Utf8,
    'dateCfl': pl.Utf8,
    'dateDefinite': pl.Utf8,
    'dateLsl': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'datePel': pl.Utf8,
    'dateTdl': pl.Utf8,
    'dateTentative': pl.Utf8,
    'dblRoomSupplementPrice': pl.Float64,
    'deductInventory': pl.Utf8,
    'defaultPmReservationNameId': pl.Float64,
    'deletedflag': pl.Utf8,
    'departureTime': pl.Utf8,
    'description': pl.Utf8,
    'distributed': pl.Utf8,
    'distributedDate': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doubleRoomSupplementYN': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'dueDateOrd': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateOriginal': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'eventAttendees': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exclusionMessage': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalRfpId': pl.Utf8,
    'externalRfpSystem': pl.Utf8,
    'externallyLocked': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fbAgendaCurrency': pl.Utf8,
    'fbCommission1': pl.Float64,
    'fbCommission2': pl.Float64,
    'fitContractMode': pl.Utf8,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'fitdiscounttype': pl.Utf8,
    'flatRateYn': pl.Utf8,
    'followupDate': pl.Utf8,
    'fsOverbookingYn': pl.Utf8,
    'functionType': pl.Utf8,
    'giid': pl.Utf8,
    'greekContractNr': pl.Utf8,
    'groupAccountID': pl.Float64,
    'guaranteecodeid': pl.Utf8,
    'guaranteedRate': pl.Utf8,
    'guaranteedYN': pl.Utf8,
    'hideacctinfoflag': pl.Utf8,
    'hlxCanxNoticeDays': pl.Float64,
    'hlxCommissionableYn': pl.Utf8,
    'hlxDdSecuredYn': pl.Utf8,
    'hlxDepositDays': pl.Float64,
    'hlxDiSecuredYn': pl.Utf8,
    'hlxHousinginfoSecuredYn': pl.Utf8,
    'hlxRateAllSecuredYn': pl.Utf8,
    'hlxRatesGnrSecuredYn': pl.Utf8,
    'hlxReturnEachDayYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'info': pl.Utf8,
    'informationBoard': pl.Utf8,
    'insertUser': pl.Int64,
    'inventoryControl': pl.Utf8,
    'inventoryCutOffDate': pl.Utf8,
    'inventoryCutOffDays': pl.Float64,
    'isacOpptyId': pl.Utf8,
    'items': pl.Utf8,
    'itemsForThisBlock': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepLeadControlYN': pl.Utf8,
    'laptopChange': pl.Float64,
    'leadOrigin': pl.Utf8,
    'leadSentYN': pl.Utf8,
    'leadSource': pl.Utf8,
    'leadType': pl.Utf8,
    'leadchangeBypropertyYn': pl.Utf8,
    'leaderrorflag': pl.Utf8,
    'leadisnewflag': pl.Utf8,
    'leadoriginid': pl.Utf8,
    'leadreceivedflag': pl.Utf8,
    'leadsend': pl.Utf8,
    'leadsend2': pl.Utf8,
    'leadsend3': pl.Utf8,
    'leadserverpendingflag': pl.Utf8,
    'leadsourceid': pl.Utf8,
    'leadstatus': pl.Utf8,
    'linkDate': pl.Utf8,
    'locationID': pl.Utf8,
    'lostTo': pl.Utf8,
    'mainmarket': pl.Utf8,
    'mainmarketid': pl.Utf8,
    'manuallyCutoffYN': pl.Utf8,
    'marEventType': pl.Utf8,
    'marHouseProtectYn': pl.Utf8,
    'marRollEndDateYn': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketid': pl.Utf8,
    'masterBlockID': pl.Float64,
    'masterBlockProperty': pl.Utf8,
    'masterNameId': pl.Float64,
    'meetingBudget': pl.Float64,
    'meetingRevenue': pl.Float64,
    'offsetType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'origAllotmentHeaderId': pl.Float64,
    'originCode': pl.Utf8,
    'originCodeDescription': pl.Utf8,
    'originalBeginDateHolidex': pl.Utf8,
    'originalEndDate': pl.Utf8,
    'originalRateCode': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'originalratecodeid': pl.Utf8,
    'ormsBlockClass': pl.Utf8,
    'ormsFinalBlock': pl.Utf8,
    'ormsForecastReviewReason': pl.Utf8,
    'ormsTransientBlock': pl.Utf8,
    'otherRevenue': pl.Float64,
    'owner': pl.Float64,
    'ownerResort': pl.Utf8,
    'owneremployeeid': pl.Float64,
    'ownerlocationd': pl.Utf8,
    'parentallotmentid': pl.Float64,
    'payment': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'personsPerRoom': pl.Float64,
    'porterageIncluded': pl.Utf8,
    'porteragePrice': pl.Float64,
    'potAverageRoomRate': pl.Float64,
    'potFbRevenue1': pl.Float64,
    'potOtherRevenue1': pl.Float64,
    'potRoomNights': pl.Float64,
    'potRoomRevenue1': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRate': pl.Utf8,
    'profileId': pl.Float64,
    'program': pl.Utf8,
    'property': pl.Utf8,
    'proposalCombineEventsYn': pl.Utf8,
    'proposalDecisionSelection': pl.Utf8,
    'proposalFollowupSelection': pl.Utf8,
    'proposalInclAltNamesYn': pl.Utf8,
    'proposalOwnerSelection': pl.Utf8,
    'proposalSentDate': pl.Utf8,
    'proposalShowEventpriceYn': pl.Utf8,
    'proposalShowPmsRoomTypeYn': pl.Utf8,
    'proposalShowSpacenameYn': pl.Utf8,
    'proposalSpaceMeasurement': pl.Utf8,
    'proposalViewToken': pl.Utf8,
    'publishRatesYn': pl.Utf8,
    'rankingCode': pl.Utf8,
    'rankingCodeDescription': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateOverride': pl.Utf8,
    'rateOverrideReason': pl.Utf8,
    'rateProtect': pl.Utf8,
    'rateTier': pl.Float64,
    'ratecodeid': pl.Utf8,
    'readyForDistribution': pl.Utf8,
    'regeneratedLeadYn': pl.Utf8,
    'repBookingmethodOrderby': pl.Float64,
    'repBsOrderBy': pl.Float64,
    'repCatOrderBy': pl.Float64,
    'replDate': pl.Utf8,
    'replVia': pl.Utf8,
    'replstatus': pl.Utf8,
    'replyBy': pl.Float64,
    'representative': pl.Utf8,
    'reservationMethod': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'reserveInventoryYN': pl.Utf8,
    'resortBooked': pl.Utf8,
    'resourceDiscountPercent': pl.Float64,
    'respTime': pl.Float64,
    'respTimeCode': pl.Utf8,
    'returnToInventory': pl.Utf8,
    'rivMarketSegment': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCommission1': pl.Float64,
    'roomCommission2': pl.Float64,
    'roomNightsSold': pl.Float64,
    'roomOwnerCode': pl.Utf8,
    'roomOwnerFullName': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTransactionCode': pl.Utf8,
    'roomStatus': pl.Utf8,
    'roomingListDue': pl.Utf8,
    'roomingListRules': pl.Utf8,
    'roomsCancellationDate': pl.Utf8,
    'roomsCancellationReason': pl.Utf8,
    'roomsCancellationReasonDescription': pl.Utf8,
    'roomsCurrency': pl.Utf8,
    'roomsDecisionDate': pl.Utf8,
    'roomsExchangeRate': pl.Float64,
    'roomsOwner': pl.Float64,
    'roomsOwnerResort': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'roomsQuoteCurrency': pl.Utf8,
    'roomsowneremployeeid': pl.Float64,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'scQuoteId': pl.Utf8,
    'sellThruYn': pl.Utf8,
    'sendToCentralYn': pl.Utf8,
    'senddate': pl.Utf8,
    'sentBy': pl.Float64,
    'sentDate': pl.Utf8,
    'sentVia': pl.Utf8,
    'serviceCharge': pl.Float64,
    'serviceFee': pl.Float64,
    'serviceFeeYn': pl.Utf8,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'showRateAmountYN': pl.Utf8,
    'snapshotSetup': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceContactAll': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceid': pl.Float64,
    'sourceprofprofileid': pl.Float64,
    'startDate': pl.Utf8,
    'startingStatus': pl.Utf8,
    'status': pl.Utf8,
    'statusColor': pl.Utf8,
    'statusType': pl.Utf8,
    'subAllocationYN': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'suppressRate': pl.Utf8,
    'syncContractYn': pl.Utf8,
    'synchronize': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'taxType': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tbdRates': pl.Utf8,
    'tdlReason': pl.Utf8,
    'tentativeLevel': pl.Float64,
    'tlpResponseid': pl.Utf8,
    'tlpUrl': pl.Utf8,
    'tourCode': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceDescription': pl.Utf8,
    'trackChangesYN': pl.Utf8,
    'travelAgentAll': pl.Utf8,
    'travelAgentRecordLocator': pl.Utf8,
    'turndownreasonid': pl.Float64,
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
    'ualias': pl.Utf8,
    'udescription': pl.Utf8,
    'updateDateExternal': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'webBookable': pl.Utf8,
    'webOverbookYN': pl.Utf8,
    'xudescription': pl.Utf8,
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