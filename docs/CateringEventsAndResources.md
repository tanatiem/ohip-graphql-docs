# CateringEventsAndResources
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| Field | Type | Description |
| --- | --- | --- |
| eventDetails | [`CateringEventsAndResourcesEventDetailsType`](#cateringeventsandresourceseventdetailstype) | Event Details |
| eventPackageRevenueDetails | [`CateringEventsAndResourcesEventPackageRevenueDetailsType`](#cateringeventsandresourceseventpackagerevenuedetailstype) | Event Package Revenue |
| eventRevenueDetails | [`CateringEventsAndResourcesEventRevenueDetailsType`](#cateringeventsandresourceseventrevenuedetailstype) | Event Revenue Details |
| eventResourceNoteDetails | [`CateringEventsAndResourcesEventResourceNoteDetailsType`](#cateringeventsandresourceseventresourcenotedetailstype) | Event Resource Note Details |
| eventRoomWaitDetails | [`CateringEventsAndResourcesEventRoomWaitDetailsType`](#cateringeventsandresourceseventroomwaitdetailstype) | Event Room Wait Details |
| eventMenuDetails | [`CateringEventsAndResourcesEventMenuDetailsType`](#cateringeventsandresourceseventmenudetailstype) | Event Menu Details |
| eventMenuRevenueDetails | [`CateringEventsAndResourcesEventMenuRevenueDetailsType`](#cateringeventsandresourceseventmenurevenuedetailstype) | Event Menu Revenue Details |
| eventItemDetails | [`CateringEventsAndResourcesEventItemDetailsType`](#cateringeventsandresourceseventitemdetailstype) | Event Item Details |
| eventNotesDetails | [`CateringEventsAndResourcesEventNotesDetailsType`](#cateringeventsandresourceseventnotesdetailstype) | Event Notes Details |
| blockDetails | [`CateringEventsAndResourcesBlockDetailsType`](#cateringeventsandresourcesblockdetailstype) | Block |
| propertyPropertyDetails | [`CateringEventsAndResourcesPropertyPropertyDetailsType`](#cateringeventsandresourcespropertypropertydetailstype) | Resort Details |
| cateringEventsAndResourcesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualAttendees | `Float` | Actual Attendees |
| allotmentid | `Float` | Block ID |
| allowRegistryYn | `String` | Specifies if attendees can register for this event. |
| attendees | `Float` | Attendees |
| averageRate | `Float` | Average Rate |
| blockEndDate | `DateTime` | Block End Date |
| blockID | `Float` | Block ID |
| blockStartDate | `Date` | Block Start Date |
| bookingBlockEndDate | `Date` | Block End Date |
| cTotalRevenue | `Float` | Central Total Revenue |
| centralDiscountAmount | `Float` | Central Discount Amount |
| centralMealType | `String` | Central Meal Type |
| centralPackagePrice | `Float` | Central Package Price |
| centralRentalAmount | `Float` | Central Rental Amount |
| centralRoomClass | `String` | Central Room Class |
| centralRoomClassDescription | `String` | Central Room Class Description |
| chainCode | `String` | Chain Code |
| combinationRoomYN | `String` | Combination Room YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| detailedPostingYn | `String` | Detailed Posting = 'Y' indicated that non included menu items will be posted individually and the unit price is stored when posting any revenue. |
| discountAmount | `Float` | Discount Amount |
| discountPercentage | `Float` | Discount Percentage |
| doNotMove | `String` | Do Not Move |
| doorCard | `String` | Door Card |
| doorcardYn | `String` | Display Doorcard Y/N. |
| doorcardflag | `String` | Doorcardflag |
| duration | `Float` | Duration |
| endDate | `DateTime` | End Date |
| endDateTime | `Date` | End Date Time |
| endTime | `String` | End Time |
| endTimeWithTeardown | `String` | End Time with Teardown |
| evResort | `String` | Event Property. |
| evStatusOrderBy | `Float` | Ev Status Order By |
| evType | `String` | Ev Type |
| eventID | `Float` | Event ID |
| eventIDSTR | `String` | Event ID STR |
| eventLinkType | `String` | Event Link Type |
| eventName | `String` | Event Name |
| eventProperty | `String` | Event Property |
| eventStatus | `String` | Event Status |
| eventlocationid | `String` | Eventlocationid |
| eventtypeid | `String` | Eventtypeid |
| excludeFromForecastYn | `String` | Exclude From Forecast Y/N |
| excludefromforecastflag | `String` | Excludefromforecastflag |
| expectedAttendees | `Float` | Expected Attendees |
| fbaId | `Float` | Fba ID |
| flatPackagePriceYN | `String` | Flat Package Price YN |
| forecastRevenueOnlyYn | `String` | Even though resources may be booked only the forecasted values will drive reporting revenue and production revenues. |
| forecastrevenueonlyflag | `String` | Forecastrevenueonlyflag |
| groupId | `Float` | Group ID |
| guaranteedAttendees | `Float` | Guaranteed Attendees |
| hourlyRentalRateYN | `String` | Hourly Rental Rate YN |
| inactiveDate | `Date` | Inactive Date |
| includeSetupInHourlyRateYN | `String` | Stores the INCLUDE_SETUP_IN_HOURLY_RATE parameter value at the time this rate was calculated hourly for the first time. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| inspectedDate | `Date` | Inspection Date |
| inspectedUser | `Float` | Inspection User |
| inspectedYn | `String` | Function Space has been inspected |
| internalEventid | `Float` | Eventid |
| isPartOfAPackageYN | `String` | Is Part of a Package YN |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkedEvent | `Float` | Linked Event |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loudEvent | `String` | Loud Event |
| masterEventID | `Float` | Master Event ID |
| masterEventYN | `String` | Master Event YN |
| maxGroup | `Float` | Maximum number of groups for a Shared function space allowed. |
| mealType | `String` | Meal Type Code |
| meetingRoomType | `String` | Type of meeting room |
| meetingRoomYN | `String` | Meeting Room YN |
| minimumRevenueYn | `String` | Minimum Revenue Y/N |
| onTheBooksAttendees | `Float` | On the Books Attendees |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origEventId | `Float` | Stores the original EVENT_ID prior to a migration. |
| packageActualAttendees | `Float` | Package Actual Attendees |
| packageCode | `String` | Package Code |
| packageDiscountPercentage | `Float` | Package Discount Percentage |
| packageEvId | `Float` | Pkg Ev ID |
| packageExpAttendees | `Float` | Expected Attendees |
| packageGuaranteedAttendees | `Float` | Guranteed Attendees |
| packageID | `Float` | Package ID |
| packageName | `String` | Package Name |
| packagePrice | `Float` | Package Price |
| packageProperty | `String` | Package Property |
| packageeventid | `Float` | Packageeventid |
| parenteventid | `Float` | Parenteventid |
| pkgActAttendees | `Float` | Package Act Attendees |
| pkgExportAttendees | `Float` | Package Exp Attendees |
| pkgGuaAttendees | `Float` | Package Gua Attendees |
| pkgLink | `Float` | Package Link |
| pkgName | `String` | Package Name |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rentalAmount | `Float` | Rental Amount |
| rentalCode | `String` | Room Ratecode |
| rentalRateType | `String` | Rental Rate Type |
| revenueActualization | `String` | Allow manual Edit of Actual figures |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomType | `String` | Room Type |
| roomid | `String` | Roomid |
| roomsetuptypeid | `String` | Roomsetuptypeid |
| selectRatecodeInCentralYn | `String` | Identifies if the user can select a rate code in central system for this event otherwise "CUSTOM" is used. |
| setAttendees | `Float` | Set Attendees |
| setupStyle | `String` | Setup Style |
| setupTime | `Float` | Setup Time |
| shareableSpace | `String` | Shareable Space |
| sharedYN | `String` | Shared YN |
| space | `String` | Space |
| spaceDescription | `String` | Space Description |
| startDate | `DateTime` | Start Date |
| startDateTime | `Date` | Start Date Time |
| startTime | `String` | Start Time |
| startTimeWithSetup | `String` | Start Time with Setup |
| statusDate | `Date` | Date when the status was changed |
| tearDownTime | `Float` | Tear-Down Time |
| totalAvailableRooms | `Float` | Total Available Rooms |
| totalBlockedRooms | `Float` | Total Blocked Rooms |
| totalContractedRooms | `Float` | Total Contracted Rooms |
| totalOriginalRooms | `Float` | Total Original Rooms |
| totalPickupRooms | `Float` | Total Pickup Rooms |
| totalRevenue | `Float` | Total Revenue |
| tracecode | `String` | Tracecode |
| turnToStatus | `String` | Turn to Status |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| v6EventId | `Float` | Stores the migrated V6 Event ID. |
| waitlistYn | `String` | Event is waitlisted? |
| waitlistflag | `String` | Waitlistflag |
| wlIgnoreYn | `String` | Ignore Waitlist Flag? |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventPackageRevenueDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualAttendees | `Float` | Actual Attendees |
| allotmentid | `Float` | Block ID |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockID | `Float` | Block ID |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralDiscountedExpectedRevenue | `Float` | Central Discounted Expected Revenue |
| centralExpectedCost | `Float` | Central Expected Cost |
| centralForecastRevenue | `Float` | Central Forecast Revenue |
| centralPackageExpectedRevenue | `Float` | Central Package Expected Revenue |
| centralTotalDiscountedExpectedRevenue | `Float` | Central Total Discounted Expected Revenue |
| centralTotalExpectedRevenue | `Float` | Central Total Expected Revenue |
| centralTotalForecastRevenue | `Float` | Central Total Forecast Revenue |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| discountPercentage | `Float` | Discount Percentage |
| discountedExpectedRevenue | `Float` | Discounted Expected Revenue |
| eventId | `Float` | Event ID |
| eventpkgrevenueid | `Float` | Eventpkgrevenueid |
| eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| expectedAttendees | `Float` | Expected Attendees |
| expectedAttendees1 | `Float` | Expected Attendees |
| expectedRevenue | `Float` | Expected Revenue |
| flatYN | `String` | Flat YN |
| forecastRevenue | `Float` | Forecast Revenue |
| guaranteedAttendees | `Float` | Guaranteed Attendees |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalEventid | `Float` | Eventid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageExpectedCost | `Float` | Package Expected Cost |
| packageID | `Float` | Package ID |
| packageProperty | `String` | Package Property |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| revenueGroup | `String` | Revenue Group |
| revenueType | `String` | Revenue Type |
| revenuetypeid | `String` | Revenuetypeid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| totalDiscountedExpectedRevenue | `Float` | Total Discounted Expected Revenue |
| totalExpectedRevenue | `Float` | Total Expected Revenue |
| totalForecastRevenue | `Float` | Total Forecast Revenue |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventRevenueDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualCost | `Float` | Actual Cost |
| actualRevenue | `Float` | Actual Revenue |
| allotmentid | `Float` | Block ID |
| billedCost | `Float` | Billed Cost |
| billedRevenue | `Float` | Billed Revenue |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockID | `Float` | Block ID |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralActualCost | `Float` | Central Actual Cost |
| centralActualRevenue | `Float` | Central Actual Revenue |
| centralBilledCost | `Float` | Central Billed Cost |
| centralBilledRevenue | `Float` | Central Billed Revenue |
| centralExpectedCost | `Float` | Central Expected Cost |
| centralExpectedRevenue | `Float` | Central Expected Revenue |
| centralForecastRevenue | `Float` | Central Forecast Revenue |
| centralGuaranteedCost | `Float` | Central Guaranteed Cost |
| centralGuaranteedRevenue | `Float` | Central Guaranteed Revenue |
| centralOnTheBooksRevenue | `Float` | Central On the Books Revenue |
| centralTotalForecastedRevenue | `Float` | Central Total Forecasted Revenue |
| customYn | `String` | Custom Y/N |
| customrevtypeflag | `String` | Customrevtypeflag |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| eventID | `Float` | Event ID |
| eventStatus | `String` | Event Status |
| eventrevenueid | `Float` | Eventrevenueid |
| expectedCost | `Float` | Expected Cost |
| expectedRevenue | `Float` | Expected Revenue |
| flatRateYN | `String` | Flat Rate YN |
| flatYN | `String` | Flat YN |
| forecastCateringRevenue | `Float` | Forecast Catering Revenue |
| forecastRevenue | `Float` | Forecast Revenue |
| forecastRevenueEditedYN | `String` | Indicates if the event forecast revenue has been modified by the user. |
| forecastRevenueOnlyYn | `String` | Even though resources may be booked only the forecasted values will drive reporting revenue and production revenues. |
| guaranteedCost | `Float` | Guaranteed Cost |
| guaranteedRevenue | `Float` | Guaranteed Revenue |
| ignoreForecastYN | `String` | Ignore Forecast YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalEventid | `Float` | Eventid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| minimumRevenueYn | `String` | Minimum Revenue Y/N |
| onTheBooksAttendees | `Float` | On the Books Attendees |
| onTheBooksRevenue | `Float` | On the Books Revenue |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageRevenueYN | `String` | Package Revenue YN |
| packagerevenueflag | `String` | Packagerevenueflag |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| revenueGroup | `String` | Revenue Group |
| revenueType | `String` | Revenue Type |
| revenuetypeid | `String` | Revenuetypeid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| useForecastValueOnlyYN | `String` | Use Forecast Value Only YN |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventResourceNoteDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentid | `Float` | Block ID |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockID | `Float` | Block ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| eventID | `Float` | Event ID |
| eventitempmsref | `Float` | Eventitempmsref |
| eventmenupmsref | `Float` | Eventmenupmsref |
| eventresourceid | `Float` | Eventresourceid |
| eventresourcenoteid | `Float` | Eventresourcenoteid |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalEventid | `Float` | Eventid |
| internalNotetitle | `String` | Notetitle |
| internalYn | `String` | Internal Y/N |
| internalnoteflag | `String` | Internalnoteflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manuallyAddedYN | `String` | Indicates if the note was manually added by the user. |
| noteDetails | `String` | Note Details |
| noteID | `Float` | Note ID |
| noteTitle | `String` | Note Title |
| order | `Float` | Order |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| resourceId | `Float` | Resource ID |
| resourceType | `String` | Resource Type |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventRoomWaitDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountName | `String` | Account Name |
| allotmentid | `Float` | Block ID |
| attendees | `Float` | Attendees |
| beginDate | `DateTime` | Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockName | `String` | Block Name |
| bookId | `Float` | Book ID |
| catStatus | `String` | Catering Status |
| cateringOwner | `String` | Catering Owner |
| cateringYn | `String` | Catering Y/N |
| cateringbookingstatusid | `String` | Catering Booking Status ID |
| cateringflag | `String` | Cateringflag |
| centralTotalRevenue | `Float` | Central Total Revenue |
| currentEvent | `Float` | Current Event |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| doNotMoveYN | `String` | Do Not Move YN |
| endDate | `DateTime` | End Date |
| endDateD | `Date` | End Date D |
| endTime | `String` | End Time |
| eventName | `String` | Event Name |
| eventType | `String` | Event Type |
| eventid | `Float` | Eventid |
| eventlocationid | `String` | Eventlocationid |
| eventroomwaitlistid | `Float` | Eventroomwaitlistid |
| exclusiveYN | `String` | Exclusive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalWaitlistdate | `Date` | Waitlistdate |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priority | `Float` | Priority |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomResort | `String` | Meeting Room Property |
| roomid | `String` | Roomid |
| shareableYN | `String` | Shareable YN |
| space | `String` | Space |
| startDate | `Date` | Start Date |
| startTime | `String` | Activity begin time |
| status | `String` | Status |
| totalRevenue | `Float` | Total Revenue |
| turnToStatus | `String` | Turn To Status |
| turntobookingstatusid | `String` | Turntobookingstatusid |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| waitlistDate | `Date` | Date when Room got waitlisted |
| waitlistedEvent | `Float` | Waitlist ID |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventMenuDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualCovers | `Float` | Actual Number of Covers |
| actualNumbers | `Float` | Actual Numbers |
| allotmentid | `Float` | Block ID |
| billedNumbers | `Float` | Billed Numbers |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockID | `Float` | Block ID |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cateringmenuid | `Float` | Cateringmenuid |
| centralDiscountedPrice | `Float` | Central Discounted Price |
| centralPrice | `Float` | Central Price |
| complimentaryMenus | `Float` | Complimentary Number of Menus |
| consumptionYn | `String` | Consumption Y/N |
| consumptionflag | `String` | Consumptionflag |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| discount | `Float` | Discount |
| discountedPrice | `Float` | Discounted Price |
| eventID | `Float` | Event ID |
| eventMenuID | `Float` | Menu ID |
| eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| expectedNumbers | `Float` | Expected Numbers |
| foodOrBeverage | `String` | Food or Beverage |
| gratuityYn | `String` | Gratuity is included |
| gratuityincludedflag | `String` | Gratuityincludedflag |
| guaranteedNumber | `Float` | Guaranteed Number |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalEventMenuID | `Float` | Eventmenuid |
| internalEventid | `Float` | Eventid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| menuId | `Float` | Menu ID |
| menuResort | `String` | Menu Property |
| menulocationid | `String` | Menulocationid |
| multiChoiceYn | `String` | Indicates a Multichoice Menu |
| multichoiceflag | `String` | Multichoiceflag |
| name | `String` | Name |
| numberOfSetMenus | `Float` | Number of Set Menus |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageActual | `Float` | Actual number of menus booked via package. |
| packageBilled | `Float` | Billed number of menus booked via package. |
| packageExpected | `Float` | Expected number of menus booked via package. |
| packageGuaranteed | `Float` | Guaranteed number of menus booked via package. |
| packageID | `Float` | Package ID |
| personsPerTable | `Float` | Number of person per table used to calculate the serving |
| price | `Float` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| restrictions | `String` | Menu Restrictions |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequenceOrder | `Float` | Sequence Order |
| servingEnd | `DateTime` | Serving End Time |
| servingEndDate | `Date` | Serving End Date |
| servingEndTime | `String` | Serving End Time |
| servingEndTrunc | `Date` | Serving End Trunc |
| servingPerPersonOrPerTable | `String` | Serving Per Person or Per Table |
| servingStart | `DateTime` | Serving Start Time |
| servingStartDate | `Date` | Serving Start Date |
| servingStartTime | `String` | Serving Start Time |
| servingStartTrunc | `Date` | Date Component of Serving Start Date/Time. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| voucherInstructions | `String` | Ticket/Voucher Instructions |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventMenuRevenueDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualCost | `Float` | Actual Cost |
| actualExtraCost | `Float` | Actual Extra Cost |
| actualExtraRevenue | `Float` | Actual Extra Revenue |
| actualNumber | `Float` | Actual Number |
| actualPrice | `Float` | Actual Price |
| allotmentid | `Float` | Block ID |
| billedCost | `Float` | Billed Cost |
| billedExtraCost | `Float` | Billed Extra Cost |
| billedExtraRevenue | `Float` | Billed Extra Revenue |
| billedNumber | `Float` | Billed Number |
| billedPrice | `Float` | Billed Price |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| bookId | `Float` | Book ID |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cExpectedCost | `Float` | Central Expected Cost |
| cItemCost | `Float` | Central Item Cost |
| cItemPrice | `Float` | Central Item Price |
| centralActualCost | `Float` | Central Actual Cost |
| centralActualExtraCost | `Float` | Central Actual Extra Cost |
| centralActualExtraRevenue | `Float` | Central Actual Extra Revenue |
| centralActualPrice | `Float` | Central Actual Price |
| centralBilledCost | `Float` | Central Billed Cost |
| centralBilledExtraCost | `Float` | Central Billed Extra Cost |
| centralBilledExtraRevenue | `Float` | Central Billed Extra Revenue |
| centralBilledPrice | `Float` | Central Billed Price |
| centralDiscountedMenuPrice | `Float` | Central Menu Price |
| centralDiscountedPrice | `Float` | Central Discounted Price |
| centralExpectedExtraCost | `Float` | Central Expected Extra Cost |
| centralExpectedExtraRevenue | `Float` | Central Expected Extra Revenue |
| centralGuaranteedCost | `Float` | Central Guaranteed Cost |
| centralGuaranteedExtraCost | `Float` | Central Guaranteed Extra Cost |
| centralGuaranteedExtraRevenue | `Float` | Central Guaranteed Extra Revenue |
| centralGuaranteedPrice | `Float` | Central Guaranteed Price |
| centralInternalQuote | `Float` | Central Internal Quote |
| centralMenuPrice | `Float` | Central Menu Price |
| complimentaryNumber | `Float` | Complimentary Number of Menus |
| customYN | `String` | Custom YN |
| customrevtypeflag | `String` | Customrevtypeflag |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| discountedMenuPrice | `Float` | Menu Price |
| discountedPrice | `Float` | Discounted Price |
| eventId | `Float` | Event ID |
| eventMenuId | `Float` | Event Menu ID |
| eventpkgrevenueid | `Float` | Eventpkgrevenueid |
| expectedCost | `Float` | Expected Cost |
| expectedExtraCost | `Float` | Expected Extra Cost |
| expectedExtraRevenue | `Float` | Expected Extra Revenue |
| expectedNumber | `Float` | Expected Number |
| guaranteedCost | `Float` | Guaranteed Cost |
| guaranteedExtraCost | `Float` | Guaranteed Extra Cost |
| guaranteedExtraRevenue | `Float` | Guaranteed Extra Revenue |
| guaranteedNumber | `Float` | Guaranteed Number |
| guaranteedPrice | `Float` | Guaranteed Price |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalEventid | `Float` | Eventid |
| internalEventmenuid | `Float` | Eventmenuid |
| internalQuote | `Float` | Expected Price |
| itemCost | `Float` | Item Cost |
| itemPrice | `Float` | Item Price |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| menuDiscountPercentage | `Float` | Menu Discount Percentage |
| menuPrice | `Float` | Menu Price |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| revGroup | `String` | Revenue Group |
| revenueType | `String` | Revenue Type |
| revenuetypeid | `String` | Revenuetypeid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventItemDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualExternalCost | `Float` | Actual external Cost |
| actualExternalQuantity | `Float` | Actual External Quantity |
| actualInternalCost | `Float` | Actual Internal cost |
| actualInternalQuantity | `Float` | Actual Internal Quantity |
| actualQuantity | `Float` | Actual Quantity |
| actualRevenue | `Float` | Actual Revenue |
| additionalDetails | `String` | Item Attribute Name |
| allotmentid | `Float` | Block ID |
| billedQuantity | `Float` | Billed Quantity |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| blockID | `Float` | Block ID |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cGuaranteedRevenue | `Float` | C Guaranteed Revenue |
| cateringitemid | `Float` | Cateringitemid |
| centralActualExternalCost | `Float` | Central Actual External Cost |
| centralActualInternalCost | `Float` | Central Actual Internal Cost |
| centralActualRevenue | `Float` | Central Actual Revenue |
| centralDiscountedPrice | `Float` | Central Discounted Price |
| centralExpectedInternalCost | `Float` | Central Expected Internal Cost |
| centralExpectedRevenue | `Float` | Central Expected Revenue |
| centralExternalCost | `Float` | Central External Cost |
| centralItemClassName | `String` | Central Item Class Name |
| centralPrice | `Float` | Central Price |
| customYn | `String` | Custom Y/N |
| customitemflag | `String` | Customitemflag |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| departmentID | `String` | Department ID |
| description | `String` | Description |
| discount | `Float` | Discount |
| discountableYN | `String` | Discountable YN |
| discountedPrice | `Float` | Discounted Price |
| endDateTrunc | `Date` | End Date Trunc |
| endTime | `DateTime` | End Time |
| eventID | `Float` | Event ID |
| eventItemID | `Float` | Event Item ID |
| eventItemgId | `Float` | EVENT_ITEMGROUP_SEQNO |
| eventpkgsummaryid | `Float` | Eventpkgsummaryid |
| expectedExternalCost | `Float` | External cost |
| expectedInternalCost | `Float` | Internal Cost |
| expectedRevenue | `Float` | Expected Revenue |
| externalOrder | `String` | Item is external |
| externalQuantity | `Float` | External Quantity booked |
| guaranteedQuantity | `Float` | Guaranteed Quantity by client |
| guaranteedRevenue | `Float` | Guaranteed Revenue |
| hourlyYn | `String` | Hourly Y/N |
| hourlycostflag | `String` | Hourlycostflag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalEventid | `Float` | Eventid |
| internalEventitemid | `Float` | Eventitemid |
| internalQuantity | `Float` | Internal Quantity booked |
| itemClassID | `Float` | Item Group ID |
| itemClassName | `String` | Item Class Name |
| itemID | `Float` | Item ID |
| itemName | `String` | Item Name |
| itemResort | `String` | Item Property |
| itemlocationid | `String` | Itemlocationid |
| itemrateId | `Float` | Itemrate ID |
| itmaId | `Float` | Itma ID |
| itmcId | `Float` | Item Class ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| order | `Float` | Order |
| orderExternalYN | `String` | Order External YN |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageID | `Float` | Package ID |
| price | `Float` | Price |
| priceCode | `String` | Price Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| quantity | `Float` | Quantity |
| quickInsertCode | `String` | Quick Insert Code |
| revenueType | `String` | Revenue Type |
| revenuetypeid | `String` | Revenuetypeid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| setUpTime | `Float` | Set-Up Time |
| showItemOnEventOrderYN | `String` | Show Item on Event Order YN |
| showOnBEOYN | `String` | Show on BEO YN |
| startDateTrunc | `Date` | Start Date Trunc |
| startTime | `DateTime` | Start Time |
| tearDownTime | `Float` | Tear-Down Time |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vendorID | `Float` | Vendor ID |
| vendorName | `String` | Vendor Identification Code. ( uppercase ) |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesEventNotesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| eventID | `Float` | Event ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalYN | `String` | Internal YN |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| note | `String` | Note |
| noteCode | `String` | Note Code |
| noteId | `Float` | Note ID |
| noteTitle | `String` | Note Title |
| order | `Float` | Order |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesBlockDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionId | `Float` | Action ID |
| actualAverageRoomRate | `Float` | Actual Average Room Rate |
| actualFBRevenue | `Float` | Actual F&B Revenue |
| actualOtherRevenue | `Float` | Other revenue |
| actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| actualRoomRevenue | `Float` | Actual revenue of the room |
| addInfo | `String` | Add Info |
| agentContactNameId | `Float` | Agent Contact Name ID |
| agentNameId | `Float` | Agent Name ID |
| agentprofileid | `Float` | Agentprofileid |
| allAliases | `String` | All Aliases |
| allBlockOwners | `String` | All Block Owners |
| allCateringOwners | `String` | All Catering Owners |
| allCompanyContacts | `String` | All Company Contacts |
| allRateCodes | `String` | All Rate Codes |
| allRoomOwners | `String` | All Room Owners |
| allRoomPools | `String` | All Room Pools |
| allRoomTypes | `String` | All Room Types |
| allSourceContacts | `String` | All Source Contacts |
| allTravelAgentContacts | `String` | All Travel Agent Contacts |
| allotmentOrigin | `String` | Allotment Origin |
| allotmentType | `String` | Type of Block alloted for the group. |
| allotmentcurrencyid | `String` | Allotmentcurrencyid |
| allotmentid | `Float` | Block ID |
| allowPickup | `String` | Allow a pickup for a group with this booking status |
| alternateBlockName | `String` | Multi Byte Description Field |
| alternateDates | `String` | Alternate Dates |
| arrivalTime | `DateTime` | Arrival Time |
| attachmentURL | `String` | URL pointing to Lead Attachments. |
| attendeesGuaranteed | `Float` | Attendees Guaranteed |
| autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| averageRate | `Float` | Average Rate |
| bEOLastPrint | `DateTime` | Date when the BEO report was last printed for this business block. |
| beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| blockAlias | `String` | Block Alias |
| blockCode | `String` | Block Code |
| blockDateActual | `Date` | Block Date Actual |
| blockDateDefinite | `DateTime` | Block Date Definite |
| blockDateProspect | `DateTime` | Block Date Prospect |
| blockDateTentative | `DateTime` | Block Date Tentative |
| blockDescription | `String` | Block Description |
| blockID | `Float` | Block ID |
| blockMode | `String` | Classifies this allotment record: MASTER_ALLOCATION SUB_ALLOCATION SUB_BOOKING SUB_TOUR SUB_ITINERARY |
| blockOwnerCode | `String` | Block Owner Code |
| blockOwnerFullName | `String` | Block Owner Full Name |
| blockPackage | `String` | Block Package |
| blockPackageDescription | `String` | Block Package Description |
| blockStatus | `String` | Block Status |
| blockStatusDescription | `String` | Block Status Description |
| blockTypeCode | `String` | Block Type Code |
| blockTypeCodeDescription | `String` | Block Type Code Description |
| blockpackageid | `String` | Blockpackageid |
| bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| bookingMethodOrderBy | `Float` | Booking Method Order By |
| bookingStatusOrder | `Float` | Booking Status Order |
| bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| bookingTypeDescription | `String` | Booking Type Description |
| bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| bookingsourceid | `String` | Bookingsourceid |
| bookingstatusid | `String` | Bookingstatusid |
| bookingtypeid | `String` | Bookingtypeid |
| breakfastDescription | `String` | Breakfast Description |
| breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastIncluded | `String` | Breakfast Included |
| breakfastPrice | `Float` | Breakfast Price |
| bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| bwiUrl | `String` | URL populated bu CRS. |
| cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| cBreakfastPrice | `Float` | Central Bfst Price |
| cCompRoomValue | `Float` | Central Comp Room Value |
| cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFBCommission1 | `Float` | Central Fb Commission 1 |
| cFBCommission2 | `Float` | Central Fb Commission 2 |
| cPorteragePrice | `Float` | Central Porterage Price |
| cRoomCommission1 | `Float` | Central Rm Commission 1 |
| cRoomCommission2 | `Float` | Central Rm Commission 2 |
| cServiceCharge | `Float` | Central Service Charge |
| cServiceFee | `Float` | Central Service Fee |
| cRSGtdYn | `String` | CRS Guaranteed Y/N |
| cancelRule | `String` | Not Used |
| canceldestinationid | `String` | Canceldestinationid |
| cancellationDestination | `String` | Cancellation Destination |
| cancellationDestinationDescription | `String` | Cancellation Destination Description |
| cancellationNumber | `Float` | Cancellation Number |
| cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| cancellationreasonid | `String` | Cancellationreasonid |
| catCutoff | `Date` | Catering Cutoff |
| catDateProspect | `DateTime` | Cat Date Prospect |
| catOwner | `Float` | Catering Owner |
| catOwnerProperty | `String` | Property of Catering Owner |
| catReturnToInventory | `String` | Cat Return To Inventory |
| catStartingStatus | `String` | Cat Starting Status |
| catcurrencyid | `String` | Catcurrencyid |
| cateringCancellationDate | `Date` | Catering Cancellation Date |
| cateringCancellationDescription | `String` | Catering Cancellation Description |
| cateringCancellationNumber | `Float` | Catering Cancellation Number |
| cateringCancellationReason | `String` | Catering Cancellation Reason |
| cateringCurrency | `String` | Catering Currency |
| cateringDateActual | `Date` | Catering Date Actual |
| cateringDecisionDate | `Date` | Catering Decision Date |
| cateringDeductInventory | `String` | Catering Deduct Inventory |
| cateringExchangeRate | `Float` | Catering Exchange Rate |
| cateringFollowupDate | `Date` | Catering Followup Date |
| cateringOnlyYN | `String` | Catering only Revenue. |
| cateringOrderBy | `Float` | Catering Order By |
| cateringOwnerCode | `String` | Catering Owner Code |
| cateringOwnerFullName | `String` | Catering Owner Full Name |
| cateringPkgsYn | `String` | Catering Pkgs Y/N |
| cateringQuoteCurrency | `String` | Catering Quote Currency |
| cateringStatus | `String` | Catering Status |
| cateringStatusColor | `String` | Catering Status Color |
| cateringStatusDescription | `String` | Catering Status Description |
| cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| cateringcurrencyid | `String` | Cateringcurrencyid |
| cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| cateringstatusid | `String` | Cateringstatusid |
| cenralFBRevenue | `Float` | Cenral FB Revenue |
| centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| centralAverageRoomRate | `Float` | Central Average Room Rate |
| centralBlockPackage | `String` | Central Block Package |
| centralBlockPackageDescription | `String` | Central Block Package Description |
| centralBlockStatus | `String` | Central Block Status |
| centralBlockStatusDescription | `String` | Central Block Status Description |
| centralBlockTypeCode | `String` | Central Block Type Code |
| centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| centralBookingType | `String` | Central Booking Type |
| centralBookingTypeDescription | `String` | Central Booking Type Description |
| centralCancellationDestination | `String` | Central Cancellation Destination |
| centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| centralCateringStatus | `String` | Central Catering Status |
| centralCateringStatusDescription | `String` | Central Catering Status Description |
| centralConversionCode | `String` | Central Conversion Code |
| centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralItemsForThisBlock | `String` | Central Items for this Block |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketCode | `String` | Central Market code |
| centralMeetingBudget | `Float` | Central Meeting Budget |
| centralMeetingRevenue | `Float` | Central Meeting Revenue |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginCodeDescription | `String` | Central Origin Code Description |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| centralPayment | `String` | Central Payment |
| centralPaymentDescription | `String` | Central Payment Description |
| centralRankingCode | `String` | Central Ranking Code |
| centralRankingCodeDescription | `String` | Central Ranking Code Description |
| centralReservationMethodCode | `String` | Central Reservation Method Code |
| centralReservationMethodDescription | `String` | Central Reservation Method Description |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralSourceCode | `String` | Central Source Code |
| centralSourceCodeDescription | `String` | Central Source Code Description |
| centralTaxAmount | `Float` | Central Tax Amount |
| chainCode | `String` | Chain Code |
| channelid | `String` | Channelid |
| code | `String` | Code |
| comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| commissionAmount | `String` | Commission Amount |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| compRooms | `Float` | Number of complimentary Rooms |
| compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| companyAll | `String` | Company All |
| companyNameId | `Float` | Company Name ID |
| companyprofileid | `Float` | Companyprofileid |
| competition | `String` | Competition |
| contactNameId | `Float` | Contact Name ID |
| contactprofileid | `Float` | Contactprofileid |
| contractNumber | `String` | Contract Number |
| controlBlockLocally | `String` | Control Block Y/N |
| conversionCode | `String` | Conversion Code |
| coversionCodeDescription | `String` | Coversion Code Description |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `DateTime` | Created Date |
| createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| creditCardId | `Float` | Credit Card ID |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateAcl | `Date` | Date Acl |
| dateCfl | `Date` | Date Cfl |
| dateDefinite | `DateTime` | Date Definite |
| dateLsl | `Date` | Date Lsl |
| dateOpenedForPickup | `Date` | Date Opened for Pickup |
| datePel | `DateTime` | Date Pel |
| dateTdl | `DateTime` | Date Tdl |
| dateTentative | `DateTime` | Date Tentative |
| dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| deletedflag | `String` | Deleted Flag |
| departureTime | `DateTime` | Departure Time |
| description | `String` | Description |
| distributed | `String` | Distributed |
| distributedDate | `DateTime` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| dueDate | `Date` | Due Date |
| dueDateOrd | `Date` | Due Date Sorting Column. |
| endDate | `Date` | End Date |
| endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| endbusinessdate | `Date` | Endbusinessdate |
| eventAttendees | `Float` | Event Attendees |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| externalReference | `String` | External Reference |
| externalRfpId | `String` | External RFP ID. |
| externalRfpSystem | `String` | External RFP System Identification Code. |
| externallyLocked | `String` | Externally Locked |
| fBRevenue | `Float` | Projected F&B Revenue. |
| fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| fbCommission1 | `Float` | stores FB commission for Agent 1 |
| fbCommission2 | `Float` | stores FB commission for Agent 2 |
| fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| fitdiscounttype | `String` | Fitdiscounttype |
| flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| followupDate | `Date` | Followup Date |
| fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| functionType | `String` | Function Type |
| giid | `String` | Group IATA Number. |
| greekContractNr | `String` | Greek Contract Number. |
| groupAccountID | `Float` | Group Account ID |
| guaranteecodeid | `String` | Guaranteecodeid |
| guaranteedRate | `String` | Rate Guaranteed Y/N. |
| guaranteedYN | `String` | Guaranteed YN |
| hideacctinfoflag | `String` | Hideacctinfoflag |
| hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| industryCode | `String` | Indicates the Non-Compete code of a block. |
| industryCodeDescription | `String` | Industry Code Description |
| info | `String` | Not Used |
| informationBoard | `String` | Information Board |
| insertUser | `Float` | Insert User |
| inventoryControl | `String` | Inventory Control |
| inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| items | `String` | Items |
| itemsForThisBlock | `String` | Items for this Block |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| laptopChange | `Float` | Laptop Change |
| leadOrigin | `String` | Lead Origin |
| leadSentYN | `String` | Lead Sent YN |
| leadSource | `String` | Lead Source |
| leadType | `String` | Lead Type |
| leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| leaderrorflag | `String` | Leaderrorflag |
| leadisnewflag | `String` | Leadisnewflag |
| leadoriginid | `String` | Leadoriginid |
| leadreceivedflag | `String` | Leadreceivedflag |
| leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| leadserverpendingflag | `String` | Leadserverpendingflag |
| leadsourceid | `String` | Leadsourceid |
| leadstatus | `String` | Leadstatus |
| linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lostTo | `String` | Competitor to whom the booking was lost. |
| mainmarket | `String` | Mainmarket |
| mainmarketid | `String` | Mainmarketid |
| manuallyCutoffYN | `String` | Block was cutoff manullay |
| marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| marketCode | `String` | Market  Code |
| marketDescription | `String` | Market Description |
| marketid | `String` | Marketid |
| masterBlockID | `Float` | Parent Block ID |
| masterBlockProperty | `String` | Parent Resort |
| masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| meetingBudget | `Float` | Meeting Budget |
| meetingRevenue | `Float` | Meeting Revenue for SFA |
| offsetType | `String` | Offset Type |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origAllotmentHeaderId | `Float` | Stores the original ALLOTMENT_HEADER_ID prior to a migration. |
| originCode | `String` | Origin Code |
| originCodeDescription | `String` | Origin Code Description |
| originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| originalEndDate | `Date` | Original End Date |
| originalRateCode | `String` | Not used |
| originalStartDate | `Date` | Original Start Date |
| originalratecodeid | `String` | Originalratecodeid |
| ormsBlockClass | `String` | ORMS Block Class |
| ormsFinalBlock | `String` | ORMS Final Block |
| ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| ormsTransientBlock | `String` | ORMS Transient Block |
| otherRevenue | `Float` | Projected Other Revenue. |
| owner | `Float` | Owner |
| ownerResort | `String` | Owner Property |
| owneremployeeid | `Float` | Owneremployeeid |
| ownerlocationd | `String` | Ownerlocationd |
| parentallotmentid | `Float` | Parentallotmentid |
| payment | `String` | Payment |
| paymentDescription | `String` | Payment Description |
| paymentmethodid | `String` | Paymentmethodid |
| personsPerRoom | `Float` | Persons Per Room |
| porterageIncluded | `String` | Porterage Included |
| porteragePrice | `Float` | Porterage Price |
| potAverageRoomRate | `Float` | Pot Average Room Rate |
| potFbRevenue1 | `Float` | Pot FB Revenue1 |
| potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| potRoomNights | `Float` | Projected Room Nights. |
| potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRate | `String` | Print Rate |
| profileId | `Float` | Profile ID |
| program | `String` | Program |
| property | `String` | Code to uniquely identify the Property |
| proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| proposalSentDate | `DateTime` | Proposal Sent Date |
| proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| proposalViewToken | `String` | Proposal View Token |
| publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| rankingCode | `String` | Indicates the ranking of a block. |
| rankingCodeDescription | `String` | Ranking Code Description |
| rateCode | `String` | Rate Code |
| rateOverride | `String` | Indicates if the rate code can be overridden. |
| rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| rateTier | `Float` | Rate Tier |
| ratecodeid | `String` | Ratecodeid |
| readyForDistribution | `String` | Ready for Distribution |
| regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| repBsOrderBy | `Float` | Rep Bs Order By |
| repCatOrderBy | `Float` | Rep Cat Order By |
| replDate | `DateTime` | Reply Date |
| replVia | `String` | Reply Communication Method |
| replstatus | `String` | Lead Replystatus [ACL|TDL] |
| replyBy | `Float` | Reply By |
| representative | `String` | Representative |
| reservationMethod | `String` | Reservation Method |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | The Description of the Guarantee code. |
| reservationid | `Float` | Reservationid |
| reserveInventoryYN | `String` | Reserve Inventory YN |
| resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| respTime | `Float` | Response Time. |
| respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| rivMarketSegment | `String` | Not used |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| roomNightsSold | `Float` | Room Nights Sold |
| roomOwnerCode | `String` | Room Owner Code |
| roomOwnerFullName | `String` | Room Owner Full Name |
| roomRevenue | `Float` | Projected Room Revenue. |
| roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| roomStatus | `String` | Room Status |
| roomingListDue | `Date` | Rooming List Due |
| roomingListRules | `String` | Stores Rooming List Rules. |
| roomsCancellationDate | `Date` | Rooms Cancellation Date |
| roomsCancellationReason | `String` | Rooms Cancellation Reason |
| roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| roomsCurrency | `String` | Rooms Currency |
| roomsDecisionDate | `Date` | Rooms Decision Date |
| roomsExchangeRate | `Float` | Rooms Exchange Rate |
| roomsOwner | `Float` | Rooms Owner |
| roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| roomsPerDay | `Float` | Rooms Per Day |
| roomsQuoteCurrency | `String` | Rooms Quote Currency |
| roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| salesId | `String` | Not used |
| sbegindate | `Date` | Sbegindate |
| scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| sellThruYn | `String` | Sell Thru Indicator. |
| sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| senddate | `Date` | Senddate |
| sentBy | `Float` | Sent By |
| sentDate | `DateTime` | Sent Date |
| sentVia | `String` | Sent Via |
| serviceCharge | `Float` | Service Charge |
| serviceFee | `Float` | Service Fee Amount per room/night |
| serviceFeeYn | `String` | Service Fee applies? |
| serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| servicePerc | `Float` | Service Percentage included. |
| shoulderEnd | `Date` | Shoulder End |
| shoulderStart | `Date` | Shoulder Start |
| showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| snapshotSetup | `String` | Snapshot has been created |
| sourceCode | `String` | Source Code |
| sourceCodeDescription | `String` | Source Code Description |
| sourceContactAll | `String` | Source Contact All |
| sourceNameId | `Float` | Source Name ID |
| sourceid | `Float` | Sourceid |
| sourceprofprofileid | `Float` | Sourceprofprofileid |
| startDate | `Date` | Start Date |
| startingStatus | `String` | Booking starting status (intial pickup) |
| status | `String` | Status |
| statusColor | `String` | Status Color |
| statusType | `String` | Type of booking status (initial) |
| subAllocationYN | `String` | Sub Allocation YN |
| superSearchIndexText | `String` | Super Search Index Text |
| suppressRate | `String` | Suppress Rate |
| syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the allotment_detail trigger. |
| synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| taxAmount | `Float` | Tax Amount |
| taxIncludedPerc | `Float` | Percentage of included Tax. |
| taxIncludedYn | `String` | Tax is included in this rate. |
| taxType | `String` | Tax Type |
| taxtypeid | `String` | Taxtypeid |
| tbdRates | `String` | To be Determined Rates |
| tdlReason | `String` | Tdl Reason |
| tentativeLevel | `Float` | Not used |
| tlpResponseid | `String` | Stores the TLPe - Response ID |
| tlpUrl | `String` | Stores the TLPe - Result URL. |
| tourCode | `String` | Tour Code. |
| traceCode | `String` | Trace Code |
| traceDescription | `String` | Trace Description |
| trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| travelAgentAll | `String` | Travel Agent All |
| travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| turndownreasonid | `Float` | Turndownreasonid |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| ualias | `String` | Not in use. |
| udescription | `String` | This is upper-case description of regular description column for fast search |
| updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `DateTime` | Updated Date |
| uploadDate | `Date` | Upload Date |
| webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| xudescription | `String` | Multi Byte Description in uppercase |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesPropertyPropertyDetailsType

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