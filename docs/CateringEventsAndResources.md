# CateringEventsAndResources
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Date` |  |  |
| _ne | `Date` |  |  |
| _in | `[Date]` |  |  |
| _nin | `[Date]` |  |  |
| _gt | `Date` |  |  |
| _lt | `Date` |  |  |
| _gte | `Date` |  |  |
| _lte | `Date` |  |  |
| _btn | [`DateRangeInput`](#daterangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Date!` |  |  |
| end | `Date!` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `DateTime` |  |  |
| _ne | `DateTime` |  |  |
| _in | `[DateTime]` |  |  |
| _nin | `[DateTime]` |  |  |
| _gt | `DateTime` |  |  |
| _lt | `DateTime` |  |  |
| _gte | `DateTime` |  |  |
| _lte | `DateTime` |  |  |
| _btn | [`DateTimeRangeInput`](#datetimerangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `DateTime!` |  |  |
| end | `DateTime!` |  |  |

[⬆ Back to Query](#query)

---

### StringInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `String` |  |  |
| _ne | `String` |  |  |
| _in | `[String]` |  |  |
| _nin | `[String]` |  |  |
| _gt | `String` |  |  |
| _lt | `String` |  |  |
| _gte | `String` |  |  |
| _lte | `String` |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Float` |  |  |
| _ne | `Float` |  |  |
| _in | `[Float]` |  |  |
| _nin | `[Float]` |  |  |
| _gt | `Float` |  |  |
| _lt | `Float` |  |  |
| _gte | `Float` |  |  |
| _lte | `Float` |  |  |
| _btn | [`FloatRangeInput`](#floatrangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Float!` |  |  |
| end | `Float!` |  |  |

[⬆ Back to Query](#query)

---

### CateringEventsAndResourcesQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| eventDetailsAllotmentid | `FloatInput` | Block ID | `conditionalInputPair(pair: 2)` |
| eventDetailsBookId | `FloatInput` | Block ID | `conditionalInputPair(pair: 2)` |
| eventDetailsAllotmentenddate | `DateInput` | Block End Date | `conditionalInputPair(pair: 2)` |
| eventDetailsChainCode | `StringInput` | Chain Code | `conditionalInputPair(pair: 1)` |
| eventDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventDetailsEndDate | `DateTimeInput` | End Date | `conditionalInputPair(pair: 2)` |
| eventDetailsEndDateTime | `DateInput` | End Date Time | `conditionalInputPair(pair: 2)` |
| eventDetailsEvResort | `StringInput` | Event Property. | `conditionalInputPair(pair: 1)` |
| eventDetailsEvType | `StringInput` | Ev Type |  |
| eventDetailsEventId | `FloatInput` | Event ID | `conditionalInputPair(pair: 2)` |
| eventDetailsEventLinkType | `StringInput` | Event Link Type |  |
| eventDetailsResort | `StringInput` | Event Property | `conditionalInputPair(pair: 1)` |
| eventDetailsEvStatus | `StringInput` | Event Status |  |
| eventDetailsEventlocationid | `StringInput` | Eventlocationid |  |
| eventDetailsEventtypeid | `StringInput` | Eventtypeid |  |
| eventDetailsGroupId | `FloatInput` | Group ID | `conditionalInputPair(pair: 2)` |
| eventDetailsInsertDate | `DateTimeInput` | Insert Date | `conditionalInputPair(pair: 2)` |
| eventDetailsEventid | `FloatInput` | Eventid | `conditionalInputPair(pair: 2)` |
| eventDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time | `conditionalInputPair(pair: 2)` |
| eventDetailsEventLinkId | `FloatInput` | Linked Event | `conditionalInputPair(pair: 2)` |
| eventDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property | `conditionalInputPair(pair: 2)` |
| eventDetailsMasterEventId | `FloatInput` | Master Event ID | `conditionalInputPair(pair: 2)` |
| eventDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventDetailsPkgEvId | `FloatInput` | Pkg Ev ID | `conditionalInputPair(pair: 2)` |
| eventDetailsPackageeventid | `FloatInput` | Packageeventid | `conditionalInputPair(pair: 2)` |
| eventDetailsParenteventid | `FloatInput` | Parenteventid | `conditionalInputPair(pair: 2)` |
| eventDetailsPkgLink | `FloatInput` | Package Link | `conditionalInputPair(pair: 2)` |
| eventDetailsRoomid | `StringInput` | Roomid |  |
| eventDetailsRoom | `StringInput` | Space |  |
| eventDetailsStartDate | `DateTimeInput` | Start Date | `conditionalInputPair(pair: 2)` |
| eventDetailsStartDateTime | `DateInput` | Start Date Time | `conditionalInputPair(pair: 2)` |
| eventDetailsTracecode | `StringInput` | Tracecode |  |
| eventDetailsUpdateDate | `DateTimeInput` | Update Date | `conditionalInputPair(pair: 2)` |
| eventpkgrevenueDetailsAllotmentid | `FloatInput` | Block ID |  |
| eventpkgrevenueDetailsBookId | `FloatInput` | Block ID |  |
| eventpkgrevenueDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| eventpkgrevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventpkgrevenueDetailsEventId | `FloatInput` | Event ID |  |
| eventpkgrevenueDetailsEventpkgrevenueid | `FloatInput` | Eventpkgrevenueid |  |
| eventpkgrevenueDetailsEventpkgsummaryid | `FloatInput` | Eventpkgsummaryid |  |
| eventpkgrevenueDetailsEventid | `FloatInput` | Eventid |  |
| eventpkgrevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventpkgrevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventpkgrevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventpkgrevenueDetailsPkgId | `FloatInput` | Package ID |  |
| eventpkgrevenueDetailsResort | `StringInput` | Package Property |  |
| eventpkgrevenueDetailsRevType | `StringInput` | Revenue Type |  |
| eventrevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventrevenueDetailsEventId | `FloatInput` | Event ID |  |
| eventrevenueDetailsEventrevenueid | `FloatInput` | Eventrevenueid |  |
| eventrevenueDetailsEventid | `FloatInput` | Eventid |  |
| eventrevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventrevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventrevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventrevenueDetailsPkgRevenueYn | `StringInput` | Package Revenue YN |  |
| eventrevenueDetailsPackagerevenueflag | `StringInput` | Packagerevenueflag |  |
| eventrevenueDetailsResort | `StringInput` | Property |  |
| eventrevenueDetailsRevType | `StringInput` | Revenue Type |  |
| eventrevenueDetailsRevenuetypeid | `StringInput` | Revenuetypeid |  |
| eventresourcenoteDetailsAllotmentid | `FloatInput` | Block ID |  |
| eventresourcenoteDetailsBookId | `FloatInput` | Block ID |  |
| eventresourcenoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventresourcenoteDetailsEventId | `FloatInput` | Event ID |  |
| eventresourcenoteDetailsEventresourcenoteid | `FloatInput` | Eventresourcenoteid |  |
| eventresourcenoteDetailsEventid | `FloatInput` | Eventid |  |
| eventresourcenoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventresourcenoteDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventresourcenoteDetailsNoteId | `FloatInput` | Note ID |  |
| eventresourcenoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventresourcenoteDetailsResort | `StringInput` | Property |  |
| eventresourcenoteDetailsResourceType | `StringInput` | Resource Type |  |
| eventroomwaitDetailsAllotmentid | `FloatInput` | Block ID |  |
| eventroomwaitDetailsBookId | `FloatInput` | Book ID |  |
| eventroomwaitDetailsCatStatus | `StringInput` | Catering Status |  |
| eventroomwaitDetailsEventId | `FloatInput` | Current Event |  |
| eventroomwaitDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventroomwaitDetailsEventid | `FloatInput` | Eventid |  |
| eventroomwaitDetailsEventlocationid | `StringInput` | Eventlocationid |  |
| eventroomwaitDetailsEventroomwaitlistid | `FloatInput` | Eventroomwaitlistid |  |
| eventroomwaitDetailsWaitlistdate | `DateInput` | Waitlistdate |  |
| eventroomwaitDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventroomwaitDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventroomwaitDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventroomwaitDetailsPriority | `FloatInput` | Priority |  |
| eventroomwaitDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| eventroomwaitDetailsRoomResort | `StringInput` | Meeting Room Property |  |
| eventroomwaitDetailsTurntoStatus | `StringInput` | Turn To Status |  |
| eventroomwaitDetailsWaitlistDate | `DateInput` | Date when Room got waitlisted |  |
| eventroomwaitDetailsWaitlistId | `FloatInput` | Waitlist ID |  |
| eventmenuDetailsBookId | `FloatInput` | Block ID |  |
| eventmenuDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| eventmenuDetailsCateringmenuid | `FloatInput` | Cateringmenuid |  |
| eventmenuDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventmenuDetailsEventId | `FloatInput` | Event ID |  |
| eventmenuDetailsEventMenuId | `FloatInput` | Menu ID |  |
| eventmenuDetailsEventmenuid | `FloatInput` | Eventmenuid |  |
| eventmenuDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventmenuDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventmenuDetailsMenuId | `FloatInput` | Menu ID |  |
| eventmenuDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventmenuDetailsResort | `StringInput` | Property |  |
| eventmenuDetailsServingStartTrunc | `DateInput` | Date Component of Serving Start Date/Time. |  |
| eventmenurevenueDetailsBookId | `FloatInput` | Book ID |  |
| eventmenurevenueDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| eventmenurevenueDetailsCustomYn | `StringInput` | Custom YN |  |
| eventmenurevenueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventmenurevenueDetailsEventId | `FloatInput` | Event ID |  |
| eventmenurevenueDetailsEventMenuId | `FloatInput` | Event Menu ID |  |
| eventmenurevenueDetailsEventpkgrevenueid | `FloatInput` | Eventpkgrevenueid |  |
| eventmenurevenueDetailsEventid | `FloatInput` | Eventid |  |
| eventmenurevenueDetailsEventmenuid | `FloatInput` | Eventmenuid |  |
| eventmenurevenueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventmenurevenueDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventmenurevenueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventmenurevenueDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| eventmenurevenueDetailsRevType | `StringInput` | Revenue Type |  |
| eventmenurevenueDetailsRevenuetypeid | `StringInput` | Revenuetypeid |  |
| eventitemDetailsAllotmentid | `FloatInput` | Block ID |  |
| eventitemDetailsBookId | `FloatInput` | Block ID |  |
| eventitemDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| eventitemDetailsCateringitemid | `FloatInput` | Cateringitemid |  |
| eventitemDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventitemDetailsEventId | `FloatInput` | Event ID |  |
| eventitemDetailsEventItemId | `FloatInput` | Event Item ID |  |
| eventitemDetailsEventItemgId | `FloatInput` | EVENT_ITEMGROUP_SEQNO |  |
| eventitemDetailsEventitemid | `FloatInput` | Eventitemid |  |
| eventitemDetailsItemId | `FloatInput` | Item ID |  |
| eventitemDetailsItemResort | `StringInput` | Item Property |  |
| eventitemDetailsItemlocationid | `StringInput` | Itemlocationid |  |
| eventitemDetailsItemrateId | `FloatInput` | Itemrate ID |  |
| eventitemDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventitemDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventitemDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventitemDetailsResort | `StringInput` | Property |  |
| eventitemDetailsRevenueType | `StringInput` | Revenue Type |  |
| eventitemDetailsRevenuetypeid | `StringInput` | Revenuetypeid |  |
| eventnotesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| eventnotesDetailsEventId | `FloatInput` | Event ID |  |
| eventnotesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| eventnotesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| eventnotesDetailsNoteCode | `StringInput` | Note Code |  |
| eventnotesDetailsNoteId | `FloatInput` | Note ID |  |
| eventnotesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| eventnotesDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| eventnotesDetailsUpdateUser | `FloatInput` | Update User |  |
| allotmentDetailsAgentContactNameId | `FloatInput` | Agent Contact Name ID |  |
| allotmentDetailsAgentNameId | `FloatInput` | Agent Name ID |  |
| allotmentDetailsAllotmentCode | `StringInput` | Block Code |  |
| allotmentDetailsAllotmentHeaderId | `FloatInput` | Block ID |  |
| allotmentDetailsOwnerCode | `StringInput` | Block Owner Code |  |
| allotmentDetailsBookingId | `StringInput` | External S&C vendor booking ID and used in HYATT-mode. |  |
| allotmentDetailsBookingStatusOrder | `FloatInput` | Booking Status Order |  |
| allotmentDetailsBlockType | `StringInput` | Determines block being [G] - Group or [W] - Wholesale. |  |
| allotmentDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| allotmentDetailsChainCode | `StringInput` | Chain Code |  |
| allotmentDetailsCompanyNameId | `FloatInput` | Company Name ID |  |
| allotmentDetailsContactNameId | `FloatInput` | Contact Name ID |  |
| allotmentDetailsInsertDate | `DateTimeInput` | Created Date |  |
| allotmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentDetailsDueDateOrd | `DateInput` | Due Date Sorting Column. |  |
| allotmentDetailsEndDate | `DateInput` | End Date |  |
| allotmentDetailsInsertUser | `FloatInput` | Insert User |  |
| allotmentDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |  |
| allotmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentDetailsMarketCode | `StringInput` | Market  Code |  |
| allotmentDetailsSuperBlockId | `FloatInput` | Parent Block ID |  |
| allotmentDetailsSuperBlockResort | `StringInput` | Parent Resort |  |
| allotmentDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |  |
| allotmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentDetailsOrmsBlockClass | `StringInput` | ORMS Block Class |  |
| allotmentDetailsOwner | `FloatInput` | Owner |  |
| allotmentDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentDetailsRateCode | `StringInput` | Rate Code |  |
| allotmentDetailsGuaranteeCode | `StringInput` | Reservation Type |  |
| allotmentDetailsBookingStatus | `StringInput` | Room Status |  |
| allotmentDetailsShoulderEndDate | `DateInput` | Shoulder End |  |
| allotmentDetailsShoulderBeginDate | `DateInput` | Shoulder Start |  |
| allotmentDetailsSourceNameId | `FloatInput` | Source Name ID |  |
| allotmentDetailsBeginDate | `DateInput` | Start Date |  |
| allotmentDetailsTourcode | `StringInput` | Tour Code. |  |
| allotmentDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |  |
| allotmentDetailsUpdateDate | `DateTimeInput` | Updated Date |  |
| allotmentDetailsXudescription | `StringInput` | Multi Byte Description in uppercase |  |
| resortDetailsResort | `StringInput` | The property that the record belongs to |  |
| resortDetailsArAcctNoFormat | `StringInput` | Number format of AR account no. |  |
| resortDetailsArAcctNoMandYn | `StringInput` | Specifies if the AR acct No is mandatory(Y/N) |  |
| resortDetailsArAgent | `StringInput` | Default Account Type for an Agent for the Property |  |
| resortDetailsArBalTrxCode | `StringInput` | Internal |  |
| resortDetailsArCompany | `StringInput` | Default Account Type for a Company for the Property |  |
| resortDetailsArCreditTrxCode | `StringInput` | Internal |  |
| resortDetailsArGroups | `StringInput` | Default Account Type for a Group for the Property |  |
| resortDetailsArIndividuals | `StringInput` | Default Account Type for Individual for the Property |  |
| resortDetailsArSettleCode | `StringInput` | Internal |  |
| resortDetailsArTypewriter | `StringInput` | Internal |  |
| resortDetailsAccessCode | `StringInput` | Access Code |  |
| resortDetailsQtyHandicappedRooms | `FloatInput` | Number of handicapped rooms. |  |
| resortDetailsAgingLevel1 | `FloatInput` | Aging bucket 1 |  |
| resortDetailsAgingLevel2 | `FloatInput` | Aging bucket 2 |  |
| resortDetailsAgingLevel3 | `FloatInput` | Aging bucket 3 |  |
| resortDetailsAgingLevel4 | `FloatInput` | Aging bucket 4 |  |
| resortDetailsAgingLevel5 | `FloatInput` | Aging bucket 3 |  |
| resortDetailsAirport | `StringInput` | The Airport Code for the airport near the property |  |
| resortDetailsAirportDistance | `StringInput` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |  |
| resortDetailsAirportTime | `StringInput` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |  |
| resortDetailsAllowLoginYn | `StringInput` | Allow loggin in to this resort(Y/N) |  |
| resortDetailsAllowancePeriodAdj | `StringInput` | Period for the allowance |  |
| resortDetailsAwardsTimeout | `FloatInput` | Internal |  |
| resortDetailsBrArea | `StringInput` | Ball Room Area |  |
| resortDetailsBrSeats | `FloatInput` | No of Ballroom Seats |  |
| resortDetailsBaseLanguage | `StringInput` | The base language of the Hotel |  |
| resortDetailsBlock | `StringInput` | It contains the reservation type to be used when making group block |  |
| resortDetailsBrandCode | `StringInput` | Brand Code of the property. |  |
| resortDetailsBudgetMonth | `FloatInput` | Financial Year of the Property |  |
| resortDetailsBeginDate | `DateInput` | The date this resort becomes valid for use by the system |  |
| resortDetailsBusinessId | `StringInput` | Value for the parameter. |  |
| resortDetailsBusinessRegCode | `StringInput` | Value for the parameter. |  |
| resortDetailsCroCode | `StringInput` | Code for the CRO |  |
| resortDetailsCashShiftDrop | `StringInput` | Internal |  |
| resortDetailsCateringCurrencyCode | `StringInput` | Catering Currency Code used when Catering Currency differs from base currency. |  |
| resortDetailsCateringCurrencyFormat | `StringInput` | Catering currency format. |  |
| resortDetailsCXchangeDate | `DateInput` | Central  Exchange Date |  |
| resortDetailsCXchangeRate | `FloatInput` | Central  Exchange Rate |  |
| resortDetailsCCreditLimit | `FloatInput` | Central Credit Limit |  |
| resortDetailsCentralCurrencyCode | `StringInput` | Central Currency Code |  |
| resortDetailsCentralCurrencyDesc | `StringInput` | Central Currency Description |  |
| resortDetailsCDblRate2 | `FloatInput` | Central Double Rate2 |  |
| resortDetailsCDblRate1 | `FloatInput` | Central Double Rate1 |  |
| resortDetailsRepPasserbyMarket | `StringInput` | Central Passerby Market |  |
| resortDetailsRepPasserbySource | `StringInput` | Central Passerby Source |  |
| resortDetailsRepResortType | `StringInput` | Central Property Type |  |
| resortDetailsCSglRate1 | `FloatInput` | Central Sgl Rate1 |  |
| resortDetailsCSglRate2 | `FloatInput` | Central Sgl Rate 2 |  |
| resortDetailsRepState | `StringInput` | Central State |  |
| resortDetailsRepStateDesc | `StringInput` | Central State Description |  |
| resortDetailsCSuiRate1 | `FloatInput` | Central Sui Rate1 |  |
| resortDetailsCSuiRate2 | `FloatInput` | Central Sui Rate 2 |  |
| resortDetailsCTplRate1 | `FloatInput` | Central Tpl Rate1 |  |
| resortDetailsCTplRate2 | `FloatInput` | Central Tpl Rate 2 |  |
| resortDetailsCWarningAmount | `FloatInput` | Central Warning Amount |  |
| resortDetailsChainCode | `StringInput` | Chain Code for the chain to which the property belongs |  |
| resortDetailsChainDescription | `StringInput` | The description of this chain. |  |
| resortDetailsChainMode | `StringInput` | Chain Mode |  |
| resortDetailsCheckExgPaidout | `StringInput` | Internal |  |
| resortDetailsCheckOutTime | `DateTimeInput` | The Hotel official check out time |  |
| resortDetailsCheckShiftDrop | `StringInput` | Internal |  |
| resortDetailsCheckTrxcode | `StringInput` | Internal |  |
| resortDetailsCheckInTime | `DateTimeInput` | The Hotel official check intime |  |
| resortDetailsCity | `StringInput` | The physical city in which this property resides. |  |
| resortDetailsCityDescription | `StringInput` | City Description |  |
| resortDetailsComAddress | `StringInput` | Internal |  |
| resortDetailsComMethod | `StringInput` | Internal |  |
| resortDetailsComNameXrefId | `FloatInput` | Internal |  |
| resortDetailsCompanyAddressType | `StringInput` | Internal |  |
| resortDetailsCompanyPhoneType | `StringInput` | Internal |  |
| resortDetailsConfigurationMode | `StringInput` | Internal |  |
| resortDetailsConfirmRegcardPrinter | `StringInput` | Internal |  |
| resortDetailsQtyConnectingRooms | `FloatInput` | Number of connecting rooms. |  |
| resortDetailsAllContacts | `StringInput` | The unique name of application user |  |
| resortDetailsCopies | `FloatInput` | Number of copies to be printed |  |
| resortDetailsCountryName | `StringInput` | Country name. |  |
| resortDetailsCountryCode | `StringInput` | The name of the country in which this property resides. |  |
| resortDetailsCountryMode | `StringInput` | Value for the parameter. |  |
| resortDetailsCreditLimit | `FloatInput` | The default credit limit for guests. |  |
| resortDetailsCurrencyCode | `StringInput` | Currency Code. |  |
| resortDetailsCurrencySymbol | `StringInput` | Currency Symbol like $ or EURO symbol |  |
| resortDetailsCurrencyName | `StringInput` | A description of this currency. |  |
| resortDetailsLocalCurrencyFormat | `StringInput` | Format for the local currency. |  |
| resortDetailsCurtainColor | `StringInput` | Color that of the background |  |
| resortDetailsDsi | `FloatInput` | DSI |  |
| resortDetailsDateForAging | `StringInput` | Date the aging should begin |  |
| resortDetailsDateSeparator | `StringInput` | Type of separator to distinguish between DD MM and YYYY |  |
| resortDetailsDecimalPlaces | `FloatInput` | Number of places for the default currency |  |
| resortDetailsDecimalSeparator | `StringInput` | Type of decimal separator |  |
| resortDetailsCurrencyDecimals | `FloatInput` | Number of decimals to designate currency |  |
| resortDetailsDefaultFolioStyle | `FloatInput` | Folio style to be used for all guests |  |
| resortDetailsDefaultGuestAddress | `StringInput` | Default guest address format. |  |
| resortDetailsDefaultMembershipType | `StringInput` | Future use |  |
| resortDetailsDefaultPostingRoom | `StringInput` | Future use |  |
| resortDetailsDefaultPropertyAddress | `StringInput` | Default property address format. |  |
| resortDetailsDefaultRateCode | `StringInput` | Future use |  |
| resortDetailsDefaultRatecodePcr | `StringInput` | Rate code used to default a PCR rate code used in FIT Contracts. |  |
| resortDetailsDefaultRatecodeRack | `StringInput` | Rate code used to default a RACK rate code used for FIT Contracts. |  |
| resortDetailsDefaultRegistrationCard | `StringInput` | Default registration card for the property. |  |
| resortDetailsDefaultReservationType | `StringInput` | The Default reservation type for this property |  |
| resortDetailsDeletedFlag | `StringInput` | Deleted Flag |  |
| resortDetailsDepositLedTrxCode | `StringInput` | Future use |  |
| resortDetailsDestinationId | `StringInput` | Destination ID |  |
| resortDetailsDfltPkgTranCode | `StringInput` | Future use |  |
| resortDetailsDfltTranCodeRateCode | `StringInput` | Future use |  |
| resortDetailsDirections | `StringInput` | Internal |  |
| resortDetailsDirsales | `StringInput` | Future use |  |
| resortDetailsDisableLoginYn | `StringInput` | LOGIN into the application is disabled. |  |
| resortDetailsQtyDoubleRooms | `FloatInput` | Number of double rooms. |  |
| resortDetailsDownloadRestYn | `StringInput` | Download Rest YN |  |
| resortDetailsDutyManagerPager | `StringInput` | Pager number for the Manager on duty for the property. |  |
| resortDetailsEmail | `StringInput` | Email id for the property. |  |
| resortDetailsEndDate | `DateInput` | Future use. |  |
| resortDetailsExchangePostingType | `StringInput` | Default Exchange posting status for the property |  |
| resortDetailsFloorNumExecutiveFloor | `StringInput` | Floor number of executive floor. |  |
| resortDetailsExpHotelCode | `StringInput` | Hotel code used for third party exports |  |
| resortDetailsExtExpFileLocation | `StringInput` | Future use |  |
| resortDetailsExtPropertyCode | `StringInput` | Future use |  |
| resortDetailsExternalScYn | `StringInput` | Indicates that the property uses an external SC system. |  |
| resortDetailsQtyFamilyRooms | `FloatInput` | Number of family rooms. |  |
| resortDetailsFaxNoFormat | `StringInput` | Fax number formats. |  |
| resortDetailsFax | `StringInput` | The fax phone number |  |
| resortDetailsFiscalEndDate | `DateInput` | Future use |  |
| resortDetailsFiscalPeriodType | `StringInput` | Future use |  |
| resortDetailsFiscalStartDate | `DateInput` | Future use |  |
| resortDetailsFiscalStartMonth | `FloatInput` | Fiscal Year Begin Month |  |
| resortDetailsFiscalStartYear | `FloatInput` | Fiscal Year Begin Year |  |
| resortDetailsFlags | `StringInput` | Screen Painter flags to indicate whether an item is changable/ movable etc. |  |
| resortDetailsFlowCode | `StringInput` | Future use |  |
| resortDetailsFnsTier | `StringInput` | Property Free Nights Stay Tier. |  |
| resortDetailsFolioLanguage1 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage2 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage3 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage4 | `StringInput` | Other languages |  |
| resortDetailsGenmgr | `StringInput` | Future use |  |
| resortDetailsGroupRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for Group |  |
| resortDetailsGuestLookupTimeout | `FloatInput` | Future use |  |
| resortDetailsQtyGuestElevators | `FloatInput` | Number of guest elevators. |  |
| resortDetailsQtyGuestRoomFloors | `FloatInput` | Total of guest rooms floors. |  |
| resortDetailsHotelCode | `StringInput` | Future use |  |
| resortDetailsHotelFc | `StringInput` | Future use |  |
| resortDetailsHotelId | `StringInput` | Hotel id |  |
| resortDetailsHotelType | `StringInput` | Future use |  |
| resortDetailsImgDirectionId | `FloatInput` | Future use |  |
| resortDetailsImgHotelId | `FloatInput` | Future use |  |
| resortDetailsImgMapId | `FloatInput` | Future use |  |
| resortDetailsInactiveDaysForGuestProfil | `FloatInput` | Future use |  |
| resortDetailsInactiveFlag | `StringInput` | Inactive Flag |  |
| resortDetailsIndividualAddressType | `StringInput` | Future use |  |
| resortDetailsIndividualPhoneType | `StringInput` | Future use |  |
| resortDetailsIndividualRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for group |  |
| resortDetailsInsertDate | `DateTimeInput` | The date the record was created |  |
| resortDetailsInsertUser | `FloatInput` | The user that created the record |  |
| resortDetailsIntTaxIncludedYn | `StringInput` | Int Tax Included YN |  |
| resortDetailsInventoryYn | `StringInput` | Future use |  |
| resortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| resortDetailsKeepAvailability | `FloatInput` | To calculate the entire availability of the Hotel for future reservations |  |
| resortDetailsLatitude | `FloatInput` | Latitude of the property in decimal |  |
| resortDetailsLeadsend | `StringInput` | Future use |  |
| resortDetailsLegalOwner | `StringInput` | The owner who owns this property |  |
| resortDetailsLocationId | `StringInput` | The property that the record belongs to |  |
| resortDetailsLongDateFormat | `StringInput` | Long date format for the property. |  |
| resortDetailsLongStayControl | `FloatInput` | The default length of stay |  |
| resortDetailsLongitude | `FloatInput` | Longitude of the property in decimal |  |
| resortDetailsMaxAdultsFamilyRoom | `FloatInput` | Maximum adults in family rooms. |  |
| resortDetailsMaxChildrenFamilyRoom | `FloatInput` | Maximum children in family rooms. |  |
| resortDetailsMaxOccupancy | `FloatInput` | Future use |  |
| resortDetailsMaxcreditdays | `FloatInput` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |  |
| resortDetailsMbsSupportedYn | `StringInput` | Indicates whether the property supports MBS. Used in some file exports. |  |
| resortDetailsMeetRooms | `FloatInput` | Future use |  |
| resortDetailsMeetSeats | `FloatInput` | Future use |  |
| resortDetailsMeetSpace | `FloatInput` | Future use |  |
| resortDetailsMeetingFc | `StringInput` | Future use |  |
| resortDetailsMinDaysBet2ReminderLetter | `FloatInput` | Minimum days for reminder letter. |  |
| resortDetailsNameIdLink | `FloatInput` | Internal |  |
| resortDetailsNightAuditCashierId | `StringInput` | Future use |  |
| resortDetailsQtyNonSmokingRooms | `FloatInput` | Number of non smoking rooms. |  |
| resortDetailsNotes | `StringInput` | Notes for the property |  |
| resortDetailsNumberBeds | `FloatInput` | Total number of beds in this property |  |
| resortDetailsNumberFloors | `FloatInput` | Total number of floors in this property |  |
| resortDetailsNumberRooms | `FloatInput` | Number of Rooms |  |
| resortDetailsOpusCurrencyCode | `StringInput` | Future use |  |
| resortDetailsOrganizationId | `FloatInput` | Organization ID |  |
| resortDetailsOrganizationid | `FloatInput` | Organization Internal ID |  |
| resortDetailsOwnership | `StringInput` | Future use |  |
| resortDetailsPackageLoss | `StringInput` | Package Loss code for a particular package |  |
| resortDetailsPackageProfit | `StringInput` | Package Profit code for a particular Package |  |
| resortDetailsParentOrgCode | `StringInput` | Parent Org Code |  |
| resortDetailsPasserbyMarket | `StringInput` | Market code |  |
| resortDetailsPasserbySource | `StringInput` | Source code |  |
| resortDetailsPath | `StringInput` | Path |  |
| resortDetailsPaymentDate | `DateTimeInput` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |  |
| resortDetailsPerReservationRoomLimit | `FloatInput` | Future use |  |
| resortDetailsTelephone | `StringInput` | The direct dial phone number of this property |  |
| resortDetailsPostCode | `StringInput` | The postal code of this property. |  |
| resortDetailsPkid | `FloatInput` | Primary Key ID |  |
| resortDetailsProinfoUrl | `StringInput` | URL where property information is located. |  |
| resortDetailsPropMapUrl | `StringInput` | Property MAP URL. |  |
| resortDetailsPropPicUrl | `StringInput` | Property picture URL. |  |
| resortDetailsLocationid | `StringInput` | The property that the record belongs to |  |
| resortDetailsName | `StringInput` | The name of this property. |  |
| resortDetailsResortType | `StringInput` | Type of resort. |  |
| resortDetailsQuotedCurrency | `StringInput` | Future use |  |
| resortDetailsRnaInsertdate | `DateTimeInput` | RNA Insert Date |  |
| resortDetailsRnaUpdatedate | `DateTimeInput` | RNA Update Date |  |
| resortDetailsReconcileDate | `DateTimeInput` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |  |
| resortDetailsRegionCode | `StringInput` | Future use |  |
| resortDetailsRegionDescription | `StringInput` | Description of the Region. |  |
| resortDetailsRestaurant | `FloatInput` | Future use |  |
| resortDetailsRhythmSheets | `FloatInput` | Total number of Sheets |  |
| resortDetailsRhythmTowels | `FloatInput` | Total number of Towels |  |
| resortDetailsRoomAmenity | `StringInput` | Room amenity. |  |
| resortDetailsSglNum | `StringInput` | Future use |  |
| resortDetailsSglRate1 | `FloatInput` | Future use |  |
| resortDetailsSglRate2 | `FloatInput` | Future use |  |
| resortDetailsSuiNum | `StringInput` | Future use |  |
| resortDetailsSuiRate1 | `FloatInput` | Future use |  |
| resortDetailsSuiRate2 | `FloatInput` | Future use |  |
| resortDetailsSaveProfiles | `FloatInput` | To store number of days before deleting the gest profile |  |
| resortDetailsScriptId | `FloatInput` | Future use |  |
| resortDetailsSeason1 | `StringInput` | Future use |  |
| resortDetailsSeason2 | `StringInput` | Future use |  |
| resortDetailsSeason3 | `StringInput` | Future use |  |
| resortDetailsSeason4 | `StringInput` | Future use |  |
| resortDetailsSeason5 | `StringInput` | Future use |  |
| resortDetailsSendLeadAsBooking | `StringInput` | Indicates that the property accepts leads as bookings. |  |
| resortDetailsShopDescription | `StringInput` | Shop description. |  |
| resortDetailsShortDateFormat | `StringInput` | Short date format for the property. |  |
| resortDetailsQtySingleRooms | `FloatInput` | Number of single rooms. |  |
| resortDetailsSourceCommission | `StringInput` | For default commission percentage |  |
| resortDetailsState | `StringInput` | The state in which this property is located. |  |
| resortDetailsStateDesc | `StringInput` | Description of the state. |  |
| resortDetailsStreet | `StringInput` | The street of the property. |  |
| resortDetailsQtySuites | `FloatInput` | Number of suites. |  |
| resortDetailsSummCurrencyCode | `StringInput` | Internal |  |
| resortDetailsTaCommission | `StringInput` | For default commission percentage |  |
| resortDetailsTplNum | `StringInput` | Future use |  |
| resortDetailsTplRate1 | `FloatInput` | Future use |  |
| resortDetailsTplRate2 | `FloatInput` | Future use |  |
| resortDetailsTelephoneNoFormat | `StringInput` | Formats for telephone number |  |
| resortDetailsThousandSeparator | `StringInput` | Separator for monetory values |  |
| resortDetailsTimeFormat | `StringInput` | Default time format for the property. |  |
| resortDetailsTimezoneRegion | `StringInput` | Time zone region selected by the employee. |  |
| resortDetailsTollfree | `StringInput` | Toll free telephone number. |  |
| resortDetailsTotRooms | `FloatInput` | Future use |  |
| resortDetailsTouristNumber | `StringInput` | Tourist Number |  |
| resortDetailsTranslateMulticharYn | `StringInput` | Indicates whether the property handles multi byte characters and whether they are translateable or not |  |
| resortDetailsTurnawayCode | `StringInput` | Turnaway code for the property. |  |
| resortDetailsQtyTwinRooms | `FloatInput` | Number of twin rooms. |  |
| resortDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |
| resortDetailsUpdateUser | `FloatInput` | The user that modified the record |  |
| resortDetailsVatId | `StringInput` | VAT ID of this property. |  |
| resortDetailsVideocheckoutPrinter | `StringInput` | Future use |  |
| resortDetailsVideoCoStart | `DateTimeInput` | Video check out start time. |  |
| resortDetailsVideoCoStop | `DateTimeInput` | Video check out end time. |  |
| resortDetailsWakeUpDelay | `FloatInput` | Future use |  |
| resortDetailsWarningAmount | `FloatInput` | Amount at which warning is raised. |  |
| resortDetailsWebaddress | `StringInput` | Webaddress of the property |  |
| resortDetailsWeekendDays | `StringInput` | Weekend days for the property. |  |
| resortDetailsZeroInvPurDays | `FloatInput` | Internal |  |

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