# CateringEventPostings
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `cateringEventPostings`
> Event posting details including revenues by property Block Event and Revenue groups
  
**Return:** [`[CateringEventPostingsType]`](#cateringeventpostingstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`CateringEventPostingsQueryArgumentsType!`](#cateringeventpostingsqueryargumentstype) |  |

## Object Types

### CateringEventPostingsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | eventPostingDetails | [`CateringEventPostingsEventPostingDetailsType`](#cateringeventpostingseventpostingdetailstype) | Event Posting Details |
| 2 | eventDetails | [`CateringEventPostingsEventDetailsType`](#cateringeventpostingseventdetailstype) | Event Details |
| 3 | blockDetails | [`CateringEventPostingsBlockDetailsType`](#cateringeventpostingsblockdetailstype) | Block |
| 4 | financialTransactionIncRevenueTaxDetails | [`CateringEventPostingsFinancialTransactionIncRevenueTaxDetailsType`](#cateringeventpostingsfinancialtransactionincrevenuetaxdetailstype) | Financial Transaction Inc Revenue Tax Details |
| 5 | financialTransactionExtraRevenueTaxDetails | [`CateringEventPostingsFinancialTransactionExtraRevenueTaxDetailsType`](#cateringeventpostingsfinancialtransactionextrarevenuetaxdetailstype) | Financial Transaction Extra Revenue Tax Details |
| 6 | financialTransactionSvcChargeIncRevDetails | [`CateringEventPostingsFinancialTransactionSvcChargeIncRevDetailsType`](#cateringeventpostingsfinancialtransactionsvcchargeincrevdetailstype) | Financial Transaction Svc Charge Inc Revenue Details |
| 7 | financialTransactionSvcChargeExtraRevDetails | [`CateringEventPostingsFinancialTransactionSvcChargeExtraRevDetailsType`](#cateringeventpostingsfinancialtransactionsvcchargeextrarevdetailstype) | Financial Transaction Svc Charge Extra Revenue Details |
| 8 | cateringEventPostingsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### CateringEventPostingsEventPostingDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentid | `Float` | Block ID |
| 2 | blockBeginDate | `Date` | Block Begin Date |
| 3 | blockEndDate | `Date` | Block End Date |
| 4 | bookId | `Float` | Book ID |
| 5 | businessDate | `DateTime` | Business Date |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | cPostedToExtra | `Float` | Central Posted To Extra |
| 9 | cPostedToIncl | `Float` | Central Posted To Incl |
| 10 | cSvcTaxExtra | `Float` | Central Svc Tax Extra |
| 11 | cSvcTaxInclude | `Float` | Central Svc Tax Include |
| 12 | cTaxExtra | `Float` | Central Tax Extra |
| 13 | cTaxIncl | `Float` | Central Tax Incl |
| 14 | cTransactionExtra | `Float` | Central Trx Extra |
| 15 | cTransactionIncl | `Float` | Central Trx Incl |
| 16 | calculationRuleExtra | `String` | Service Charge is calculated [NET] or [GROSS] for Extra Revenue ? |
| 17 | calculationRuleIncluded | `String` | Service Charge is calculated [NET] or [GROSS] for Included Revenue ? |
| 18 | centralPostingRevenueExtra | `Float` | Central Posting - Revenue Extra |
| 19 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 20 | centralServiceChargeIncluded | `Float` | Central Service Charge - Included |
| 21 | centralServiceChargeExtra | `Float` | Central Service Charge- Extra |
| 22 | centralTaxType | `String` | Central Tax Type |
| 23 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 24 | centralUnitPrice | `Float` | Central Unit Price |
| 25 | checkNumber | `String` | Check Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | deletedFlag | `String` | Deleted Flag |
| 28 | evPostId | `Float` | Event Post ID Primary Key |
| 29 | eventId | `Float` | Event ID |
| 30 | eventpostingid | `Float` | Eventpostingid |
| 31 | extraallotmentid | `Float` | Extraallotmentid |
| 32 | extraforresvid | `Float` | Extraforresvid |
| 33 | extratranscodeid | `String` | Extratranscodeid |
| 34 | includedallotmentid | `Float` | Includedallotmentid |
| 35 | includedforresvid | `Float` | Includedforresvid |
| 36 | includedtranscodeid | `String` | Includedtranscodeid |
| 37 | insertUser | `Float` | Insert User |
| 38 | internalEventid | `Float` | Eventid |
| 39 | jRNUpdateDate | `Date` | JRN Update Date |
| 40 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 41 | locationID | `String` | Internal ID to uniquely identify the Property |
| 42 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 43 | postedById | `Float` | Posted By ID |
| 44 | postedByUserName | `String` | The User ID who posted the message. |
| 45 | postedDateExtra | `Date` | Posted Date Extra |
| 46 | postedDateIncluded | `Date` | Posted Date Included |
| 47 | postedToExtra | `Float` | Posted To Extra |
| 48 | postedToIncl | `Float` | Posted To Incl |
| 49 | postedYN | `String` | Posted YN |
| 50 | postedByProperty | `String` | Posted by Property |
| 51 | postedToRoomExtra | `String` | Posted to Room - Extra |
| 52 | postedToRoomIncluded | `String` | Posted to Room - Included |
| 53 | postingRevenueExtra | `Float` | Extra Revenue Amount |
| 54 | postinglocationid | `String` | Postinglocationid |
| 55 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 56 | property | `String` | Code to uniquely identify the Property |
| 57 | resourceName | `String` | Resource Name |
| 58 | resourceType | `String` | Resource Type |
| 59 | revenueIncluded | `Float` | Included Revenue Amount |
| 60 | revenueType | `String` | Revenue Type |
| 61 | revenuetypeid | `String` | Revenuetypeid |
| 62 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 63 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 64 | serviceChargeIncluded | `Float` | Service Charge - Included |
| 65 | serviceChargePercentExtra | `Float` | Service Charge Percentage for Extra Revenue. |
| 66 | serviceChargePercentIncluded | `Float` | Service Charge Percentage for Included Revenue. |
| 67 | serviceChargeTransactionCode | `String` | Service Charge Transaction Code for Included Revenue. |
| 68 | serviceChargeExtra | `Float` | Service Charge- Extra |
| 69 | svcTaxExtra | `Float` | Svc Tax Extra |
| 70 | svcTaxInclude | `Float` | Svc Tax Include |
| 71 | svcTrxCodeExtra | `String` | Service Charge Transaction Code for Extra Revenue. |
| 72 | svcTrxNumberExtra | `Float` | Transaction ID for Service Charge included Revenue. |
| 73 | svcTrxNumberIncl | `Float` | Transaction ID for Service Charge extra Revenue. |
| 74 | taxExtra | `Float` | Tax Extra |
| 75 | taxIncl | `Float` | Tax Incl |
| 76 | taxType | `String` | Tax Type |
| 77 | taxTypeDescription | `String` | Tax Type Description |
| 78 | transactionCodeExtraRevenue | `String` | Transactioncode for Extra Revenue |
| 79 | transactionCodeIncludedRevenue | `String` | Transactioncode for Included Revenue |
| 80 | trxExtra | `Float` | Transaction Extra |
| 81 | trxIncl | `Float` | Transaction Incl |
| 82 | trxNumberExtra | `Float` | Transaction No Extra |
| 83 | trxNumberIncl | `Float` | Transaction No Incl |
| 84 | unitPrice | `Float` | Unit Price |
| 85 | units | `Float` | Number of units which will be used to calculate the total revenue to be posted. |
| 86 | updateDate | `DateTime` | Update Date |
| 87 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### CateringEventPostingsEventDetailsType

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

### CateringEventPostingsBlockDetailsType

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

### CateringEventPostingsFinancialTransactionIncRevenueTaxDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 4 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 5 | aRState | `String` | AR State |
| 6 | aRTransferDate | `Date` | AR Transfer Date |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountCode | `Float` | Account Code |
| 10 | accountName | `String` | Account Name |
| 11 | accountNumber | `String` | Account Number |
| 12 | accountTypeFlag | `String` | Account Type Flag |
| 13 | accountid | `Float` | Accountid |
| 14 | adjustmentYN | `String` | Adjustment YN |
| 15 | advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 17 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 18 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 19 | advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 20 | advgentranscodeid | `String` | Advgentranscodeid |
| 21 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 22 | apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 23 | approvalCode | `String` | Approval Code |
| 24 | approvalDate | `Date` | Approval Date |
| 25 | approvalStatus | `String` | Approval Status |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 31 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 32 | authemployeeid | `Float` | Authemployeeid |
| 33 | authorizer | `String` | Authorizer |
| 34 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 35 | autoSettleYn | `String` | Auto Settle Y/N |
| 36 | billingEventID | `Float` | Billing Event ID |
| 37 | bonusCheckId | `Float` | Bonus Check ID |
| 38 | bucketCode | `String` | Bucket code related to this redemption. |
| 39 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 40 | businessDate | `Date` | Business Date |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cChangeDue | `Float` | Central Change Due |
| 43 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 44 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 45 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 46 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 51 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 52 | cPackageAllowance | `Float` | Central Package Allowance |
| 53 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 54 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 55 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 56 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 57 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 58 | cTaxRate | `Float` | Central Tax Rate |
| 59 | cVatAmount | `Float` | Central Vat Amount |
| 60 | cCApproval | `String` | CC Approval Code |
| 61 | calculatePointsYN | `String` | Calculate Points YN |
| 62 | cashBagNumber | `String` | Cash Bag Number |
| 63 | cashier | `String` | Cashier |
| 64 | cashierCredit | `Float` | Cashier Credit |
| 65 | cashierDebit | `Float` | Cashier Debit |
| 66 | cashierID | `Float` | Cashier ID |
| 67 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 68 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 69 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 70 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 71 | centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| 72 | centralCashierCredit | `Float` | Central Cashier Credit |
| 73 | centralCashierDebit | `Float` | Central Cashier Debit |
| 74 | centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| 75 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 76 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 77 | centralGrossAmount | `Float` | Central Gross Amount |
| 78 | centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| 79 | centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| 80 | centralInHouseCredit | `Float` | Central In-House Credit |
| 81 | centralInHouseDebit | `Float` | Central In-House Debit |
| 82 | centralIncludedRevenueTax | `Float` | Central Included Revenue Tax |
| 83 | centralMarketCode | `String` | Central Market Code |
| 84 | centralMarketDescription | `String` | Central Market Description |
| 85 | centralMarketGroupCode | `String` | Central Market Group Code |
| 86 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 87 | centralNetAmount | `Float` | Central Net Amount |
| 88 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 89 | centralPackage | `String` | Central Package |
| 90 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 91 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 92 | centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| 93 | centralPricePerUnit | `Float` | Central Price Per Unit |
| 94 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 95 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 96 | centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 97 | centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 98 | chainCode | `String` | Chain Code |
| 99 | changeDue | `Float` | Change Due |
| 100 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 101 | checkNumber | `String` | Check Number |
| 102 | closureNumber | `Float` | Closure Number |
| 103 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 104 | comments | `String` | Comments |
| 105 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 106 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 107 | compTypeCode | `String` | Comp Type Code |
| 108 | complinktranscodeid | `String` | Complinktranscodeid |
| 109 | compressedYn | `String` | Compressed Y/N |
| 110 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 111 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 112 | couponNo | `String` | Coupon Number |
| 113 | covers | `String` | Covers |
| 114 | creditCardId | `Float` | Credit Card ID |
| 115 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 116 | creditYN | `String` | Credit YN |
| 117 | currencyCode | `String` | Currency Code |
| 118 | customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| 119 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 120 | debitYN | `String` | Debit YN |
| 121 | deferredYn | `String` | Deferred Y/N |
| 122 | deletedFlag | `String` | Deleted Flag |
| 123 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 124 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 125 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 126 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 127 | depositTransactionId | `String` | Deposit Transaction ID |
| 128 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 129 | displayflag | `String` | Displayflag |
| 130 | dualCurrency | `String` | Cuurency code for parrallel currency. |
| 131 | dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| 132 | dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 133 | dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 134 | dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| 135 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 136 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 137 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 138 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 139 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 140 | exchangeDate | `Date` | Exchange Date |
| 141 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 142 | exchangeRate | `Float` | Exchange Rate |
| 143 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 144 | expInvoiceType | `String` | Export Invoice Type |
| 145 | expOriginalInvoice | `String` | Export Original Invoice |
| 146 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 147 | extTransactionId | `String` | Transaction ID from external system. |
| 148 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 149 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 150 | financialTransactionCodeType | `String` | Financial Transaction Code Type |
| 151 | fintransactionid | `Float` | Fintransactionid |
| 152 | fintransid | `Float` | Fintransid |
| 153 | fiscalBillNo | `String` | Fiscal Bill Number |
| 154 | fixedChargesYN | `String` | Fixed Charges YN |
| 155 | folioNo | `Float` | Folio Number |
| 156 | folioType | `String` | Folio Type |
| 157 | folioTypeJoin | `String` | Folio Type Join |
| 158 | folioView | `Float` | Folio View |
| 159 | folioid | `Float` | Folioid |
| 160 | foreignCurrencyID | `String` | Foreign Currency ID |
| 161 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 162 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 163 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 164 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 165 | fromReservationId | `Float` | From Resv ID |
| 166 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 167 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 168 | genCashierId | `Float` | General Cashier Id. |
| 169 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 170 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 171 | grossAmount | `Float` | Gross Amount |
| 172 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 173 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 174 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 175 | guestCountry | `String` | Guest Country |
| 176 | guestCountryCode | `String` | Guest Country Code |
| 177 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 178 | inHouseCredit | `Float` | In-House Credit |
| 179 | inHouseDebit | `Float` | In-House Debit |
| 180 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 181 | includedRevenueTax | `Float` | Included Revenue Tax |
| 182 | includedRevenueTaxPercent | `Float` | Included Revenue Tax Percent |
| 183 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 184 | insertDate | `DateTime` | Insert Date |
| 185 | insertUser | `Float` | Insert User |
| 186 | insertUserName | `String` | The name of the user who created the record. |
| 187 | installments | `Float` | Installments |
| 188 | internalArticleid | `Float` | Articleid |
| 189 | internalBusinessdate | `Date` | Businessdate |
| 190 | internalCashierid | `Float` | Cashierid |
| 191 | internalWindowId | `Float` | Internal Window ID |
| 192 | internalYN | `String` | Internal YN |
| 193 | invoiceCloseDate | `Date` | Invoice Close Date |
| 194 | invoiceNumber | `Float` | Invoice Number |
| 195 | invoiceType | `String` | Invoice Type |
| 196 | jRNUpdateDate | `Date` | JRN Update Date |
| 197 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 198 | linkTrxNumber | `Float` | Link Transaction No |
| 199 | locationID | `String` | Internal ID to uniquely identify the Property |
| 200 | marketCode | `String` | Market Code |
| 201 | marketDescription | `String` | Market Description |
| 202 | marketDisplaySequence | `Float` | Market Display Sequence |
| 203 | marketGroupCode | `String` | Market Group Code |
| 204 | marketGroupDescription | `String` | Market Group Description |
| 205 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 206 | marketid | `String` | Marketid |
| 207 | membershipID | `Float` | Membership ID |
| 208 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 209 | nameId | `Float` | Name ID |
| 210 | nameTaxType | `String` | Name Tax Type |
| 211 | netAmount | `Float` | Net Amount |
| 212 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 213 | numberDialed | `String` | Number Dialed. |
| 214 | oTransactionDesc | `String` | Transaction Description. |
| 215 | oVOSCurrency | `String` | Currency code for contract currency. |
| 216 | oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 217 | oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 218 | oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 219 | oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 220 | onHoldYN | `String` | On Hold YN |
| 221 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 222 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 223 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 224 | originalBillNumber | `Float` | Stores original bill number after void. |
| 225 | originalFolioNumber | `String` | Stores original folio type after void. |
| 226 | originalReservationNameId | `Float` | Original Resv Name ID |
| 227 | originalRoom | `String` | Original Room |
| 228 | originalresvid | `Float` | Originalresvid |
| 229 | othersBagNumber | `String` | Others Bag Number |
| 230 | package | `String` | Package |
| 231 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 232 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 233 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 234 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 235 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 236 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 237 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 238 | parentfintransid | `Float` | Parentfintransid |
| 239 | passerByName | `String` | Passerby Name. |
| 240 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 241 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 242 | paymentType | `String` | Payment Type |
| 243 | paymentsReference | `String` | Payments-Reference |
| 244 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 245 | postingDate | `DateTime` | Posting Date |
| 246 | postingRhythm | `String` | Posting Rhythm |
| 247 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 248 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 249 | postitNo | `Float` | Postit Number |
| 250 | postitYn | `String` | Postit Y/N |
| 251 | pricePerUnit | `Float` | Price Per Unit |
| 252 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 253 | processed8300YN | `String` | Processed 8300 YN |
| 254 | productid | `String` | Productid |
| 255 | profileid | `Float` | Profileid |
| 256 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 257 | proformaYn | `String` | Proforma Y/N |
| 258 | property | `String` | Code to uniquely identify the Property |
| 259 | propertyBillPrefix | `String` | Property Bill Prefix |
| 260 | quantity | `Float` | Quantity |
| 261 | queueName | `String` | Queue Name |
| 262 | rateCode | `String` | Rate Code |
| 263 | ratecodeid | `String` | Ratecodeid |
| 264 | receiptNumber | `Float` | Receipt Number |
| 265 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 266 | repTransactionCode | `String` | Reporting Trx Code |
| 267 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 268 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 269 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 270 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 271 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 272 | reservationid | `Float` | Reservationid |
| 273 | resvenddate | `Date` | Resvenddate |
| 274 | revenueAmount | `Float` | Revenue Amount. |
| 275 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 276 | revisionNo | `Float` | Revision Number |
| 277 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 278 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 279 | roomClass | `String` | Room Class |
| 280 | roomNts | `Float` | Room Nts |
| 281 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 282 | roomNumber | `String` | Room Number |
| 283 | roomid | `String` | Roomid |
| 284 | roundFactorYn | `String` | Round Factor Y/N |
| 285 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 286 | routedYn | `String` | Indicates if the transaction has been routed. |
| 287 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 288 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 289 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 290 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 291 | settlementFlag | `String` | Settlement Flag |
| 292 | sourceCode | `String` | Source Code |
| 293 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 294 | sourceDescription | `String` | Source Description |
| 295 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 296 | sourceGroupCode | `String` | Source Group Code |
| 297 | sourceGroupDescription | `String` | Source Group Description |
| 298 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 299 | sourceid | `String` | Sourceid |
| 300 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 301 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 302 | supplement | `String` | Supplement |
| 303 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 304 | targetResort | `String` | Target Property |
| 305 | targetlocationid | `String` | Targetlocationid |
| 306 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 307 | taxElements | `String` | Tax Elements |
| 308 | taxGeneratedYN | `String` | Tax Generated YN |
| 309 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 310 | taxInvNumber | `String` | Tax Invoice No |
| 311 | taxRate | `Float` | Tax Rate |
| 312 | taxRateType | `String` | Tax Rate Type |
| 313 | tcGroup | `String` | Transaction Code Group |
| 314 | tcSubgroup | `String` | Transaction Code Subgroup |
| 315 | tclCode1 | `String` | Class1 Code. |
| 316 | tclCode2 | `String` | Class1 Code. |
| 317 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 318 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 319 | thresholdEntityType | `String` | Threshold Entity Type |
| 320 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 321 | toReservationNameId | `Float` | To Resv Name ID |
| 322 | tranActionId | `Float` | Tran Action ID |
| 323 | transactionActivityDate | `Date` | Transaction Activity Date |
| 324 | transactionCode | `String` | Transaction Code |
| 325 | transactionCodeDescription | `String` | Transaction Code Description |
| 326 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 327 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 328 | transactionDate | `Date` | Transaction Date |
| 329 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 330 | transactionPostingDate | `Date` | Transaction Posting Date |
| 331 | transactionPostingTime | `String` | Time transaction was posted. |
| 332 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 333 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 334 | transactionStatus | `String` | Transaction Status |
| 335 | transactionType | `String` | Transaction Type |
| 336 | transactionFromAccount | `Float` | Transaction from Account |
| 337 | transactionToAccount | `Float` | Transaction to Account |
| 338 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 339 | transcodearrangementid | `Float` | Transcodearrangementid |
| 340 | transferfromaccountid | `Float` | Transferfromaccountid |
| 341 | transferfromresvid | `Float` | Transferfromresvid |
| 342 | transfertoaccountid | `Float` | Transfertoaccountid |
| 343 | transfertoresvid | `Float` | Transfertoresvid |
| 344 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 345 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 346 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 347 | trxCode | `String` | Transaction Code |
| 348 | trxNo | `Float` | Trx Number |
| 349 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 350 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 351 | trxNumberHeader | `Float` | Transaction No Header |
| 352 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 353 | trxServiceType | `String` | Transaction Service Type |
| 354 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 355 | updateDate | `DateTime` | Update Date |
| 356 | updateUser | `Float` | Update User |
| 357 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 358 | userID | `Float` | User ID |
| 359 | vatAmount | `Float` | Tax Amount for Commission. |
| 360 | vatOffsetYn | `String` | Vat Offset Y/N |
| 361 | vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### CateringEventPostingsFinancialTransactionExtraRevenueTaxDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 4 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 5 | aRState | `String` | AR State |
| 6 | aRTransferDate | `Date` | AR Transfer Date |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountCode | `Float` | Account Code |
| 10 | accountName | `String` | Account Name |
| 11 | accountNumber | `String` | Account Number |
| 12 | accountTypeFlag | `String` | Account Type Flag |
| 13 | accountid | `Float` | Accountid |
| 14 | adjustmentYN | `String` | Adjustment YN |
| 15 | advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 17 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 18 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 19 | advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 20 | advgentranscodeid | `String` | Advgentranscodeid |
| 21 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 22 | apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 23 | approvalCode | `String` | Approval Code |
| 24 | approvalDate | `Date` | Approval Date |
| 25 | approvalStatus | `String` | Approval Status |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 31 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 32 | authemployeeid | `Float` | Authemployeeid |
| 33 | authorizer | `String` | Authorizer |
| 34 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 35 | autoSettleYn | `String` | Auto Settle Y/N |
| 36 | billingEventID | `Float` | Billing Event ID |
| 37 | bonusCheckId | `Float` | Bonus Check ID |
| 38 | bucketCode | `String` | Bucket code related to this redemption. |
| 39 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 40 | businessDate | `Date` | Business Date |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cChangeDue | `Float` | Central Change Due |
| 43 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 44 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 45 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 46 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 51 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 52 | cPackageAllowance | `Float` | Central Package Allowance |
| 53 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 54 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 55 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 56 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 57 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 58 | cTaxRate | `Float` | Central Tax Rate |
| 59 | cVatAmount | `Float` | Central Vat Amount |
| 60 | cCApproval | `String` | CC Approval Code |
| 61 | calculatePointsYN | `String` | Calculate Points YN |
| 62 | cashBagNumber | `String` | Cash Bag Number |
| 63 | cashier | `String` | Cashier |
| 64 | cashierCredit | `Float` | Cashier Credit |
| 65 | cashierDebit | `Float` | Cashier Debit |
| 66 | cashierID | `Float` | Cashier ID |
| 67 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 68 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 69 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 70 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 71 | centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| 72 | centralCashierCredit | `Float` | Central Cashier Credit |
| 73 | centralCashierDebit | `Float` | Central Cashier Debit |
| 74 | centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| 75 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 76 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 77 | centralExtraRevenueTax | `Float` | Central Extra Revenue Tax |
| 78 | centralGrossAmount | `Float` | Central Gross Amount |
| 79 | centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| 80 | centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| 81 | centralInHouseCredit | `Float` | Central In-House Credit |
| 82 | centralInHouseDebit | `Float` | Central In-House Debit |
| 83 | centralMarketCode | `String` | Central Market Code |
| 84 | centralMarketDescription | `String` | Central Market Description |
| 85 | centralMarketGroupCode | `String` | Central Market Group Code |
| 86 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 87 | centralNetAmount | `Float` | Central Net Amount |
| 88 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 89 | centralPackage | `String` | Central Package |
| 90 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 91 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 92 | centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| 93 | centralPricePerUnit | `Float` | Central Price Per Unit |
| 94 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 95 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 96 | centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 97 | centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 98 | chainCode | `String` | Chain Code |
| 99 | changeDue | `Float` | Change Due |
| 100 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 101 | checkNumber | `String` | Check Number |
| 102 | closureNumber | `Float` | Closure Number |
| 103 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 104 | comments | `String` | Comments |
| 105 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 106 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 107 | compTypeCode | `String` | Comp Type Code |
| 108 | complinktranscodeid | `String` | Complinktranscodeid |
| 109 | compressedYn | `String` | Compressed Y/N |
| 110 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 111 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 112 | couponNo | `String` | Coupon Number |
| 113 | covers | `String` | Covers |
| 114 | creditCardId | `Float` | Credit Card ID |
| 115 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 116 | creditYN | `String` | Credit YN |
| 117 | currencyCode | `String` | Currency Code |
| 118 | customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| 119 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 120 | debitYN | `String` | Debit YN |
| 121 | deferredYn | `String` | Deferred Y/N |
| 122 | deletedFlag | `String` | Deleted Flag |
| 123 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 124 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 125 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 126 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 127 | depositTransactionId | `String` | Deposit Transaction ID |
| 128 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 129 | displayflag | `String` | Displayflag |
| 130 | dualCurrency | `String` | Cuurency code for parrallel currency. |
| 131 | dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| 132 | dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 133 | dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 134 | dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| 135 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 136 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 137 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 138 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 139 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 140 | exchangeDate | `Date` | Exchange Date |
| 141 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 142 | exchangeRate | `Float` | Exchange Rate |
| 143 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 144 | expInvoiceType | `String` | Export Invoice Type |
| 145 | expOriginalInvoice | `String` | Export Original Invoice |
| 146 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 147 | extTransactionId | `String` | Transaction ID from external system. |
| 148 | extraRevenueTax | `Float` | Extra Revenue Tax |
| 149 | extraRevenueTaxPercent | `Float` | Extra Revenue Tax Percent |
| 150 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 151 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 152 | financialTransactionCodeType | `String` | Financial Transaction Code Type |
| 153 | fintransactionid | `Float` | Fintransactionid |
| 154 | fintransid | `Float` | Fintransid |
| 155 | fiscalBillNo | `String` | Fiscal Bill Number |
| 156 | fixedChargesYN | `String` | Fixed Charges YN |
| 157 | folioNo | `Float` | Folio Number |
| 158 | folioType | `String` | Folio Type |
| 159 | folioTypeJoin | `String` | Folio Type Join |
| 160 | folioView | `Float` | Folio View |
| 161 | folioid | `Float` | Folioid |
| 162 | foreignCurrencyID | `String` | Foreign Currency ID |
| 163 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 164 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 165 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 166 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 167 | fromReservationId | `Float` | From Resv ID |
| 168 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 169 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 170 | genCashierId | `Float` | General Cashier Id. |
| 171 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 172 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 173 | grossAmount | `Float` | Gross Amount |
| 174 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 175 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 176 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 177 | guestCountry | `String` | Guest Country |
| 178 | guestCountryCode | `String` | Guest Country Code |
| 179 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 180 | inHouseCredit | `Float` | In-House Credit |
| 181 | inHouseDebit | `Float` | In-House Debit |
| 182 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 183 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 184 | insertDate | `DateTime` | Insert Date |
| 185 | insertUser | `Float` | Insert User |
| 186 | insertUserName | `String` | The name of the user who created the record. |
| 187 | installments | `Float` | Installments |
| 188 | internalArticleid | `Float` | Articleid |
| 189 | internalBusinessdate | `Date` | Businessdate |
| 190 | internalCashierid | `Float` | Cashierid |
| 191 | internalWindowId | `Float` | Internal Window ID |
| 192 | internalYN | `String` | Internal YN |
| 193 | invoiceCloseDate | `Date` | Invoice Close Date |
| 194 | invoiceNumber | `Float` | Invoice Number |
| 195 | invoiceType | `String` | Invoice Type |
| 196 | jRNUpdateDate | `Date` | JRN Update Date |
| 197 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 198 | linkTrxNumber | `Float` | Link Transaction No |
| 199 | locationID | `String` | Internal ID to uniquely identify the Property |
| 200 | marketCode | `String` | Market Code |
| 201 | marketDescription | `String` | Market Description |
| 202 | marketDisplaySequence | `Float` | Market Display Sequence |
| 203 | marketGroupCode | `String` | Market Group Code |
| 204 | marketGroupDescription | `String` | Market Group Description |
| 205 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 206 | marketid | `String` | Marketid |
| 207 | membershipID | `Float` | Membership ID |
| 208 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 209 | nameId | `Float` | Name ID |
| 210 | nameTaxType | `String` | Name Tax Type |
| 211 | netAmount | `Float` | Net Amount |
| 212 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 213 | numberDialed | `String` | Number Dialed. |
| 214 | oTransactionDesc | `String` | Transaction Description. |
| 215 | oVOSCurrency | `String` | Currency code for contract currency. |
| 216 | oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 217 | oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 218 | oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 219 | oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 220 | onHoldYN | `String` | On Hold YN |
| 221 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 222 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 223 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 224 | originalBillNumber | `Float` | Stores original bill number after void. |
| 225 | originalFolioNumber | `String` | Stores original folio type after void. |
| 226 | originalReservationNameId | `Float` | Original Resv Name ID |
| 227 | originalRoom | `String` | Original Room |
| 228 | originalresvid | `Float` | Originalresvid |
| 229 | othersBagNumber | `String` | Others Bag Number |
| 230 | package | `String` | Package |
| 231 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 232 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 233 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 234 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 235 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 236 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 237 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 238 | parentfintransid | `Float` | Parentfintransid |
| 239 | passerByName | `String` | Passerby Name. |
| 240 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 241 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 242 | paymentType | `String` | Payment Type |
| 243 | paymentsReference | `String` | Payments-Reference |
| 244 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 245 | postingDate | `DateTime` | Posting Date |
| 246 | postingRhythm | `String` | Posting Rhythm |
| 247 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 248 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 249 | postitNo | `Float` | Postit Number |
| 250 | postitYn | `String` | Postit Y/N |
| 251 | pricePerUnit | `Float` | Price Per Unit |
| 252 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 253 | processed8300YN | `String` | Processed 8300 YN |
| 254 | productid | `String` | Productid |
| 255 | profileid | `Float` | Profileid |
| 256 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 257 | proformaYn | `String` | Proforma Y/N |
| 258 | property | `String` | Code to uniquely identify the Property |
| 259 | propertyBillPrefix | `String` | Property Bill Prefix |
| 260 | quantity | `Float` | Quantity |
| 261 | queueName | `String` | Queue Name |
| 262 | rateCode | `String` | Rate Code |
| 263 | ratecodeid | `String` | Ratecodeid |
| 264 | receiptNumber | `Float` | Receipt Number |
| 265 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 266 | repTransactionCode | `String` | Reporting Trx Code |
| 267 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 268 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 269 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 270 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 271 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 272 | reservationid | `Float` | Reservationid |
| 273 | resvenddate | `Date` | Resvenddate |
| 274 | revenueAmount | `Float` | Revenue Amount. |
| 275 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 276 | revisionNo | `Float` | Revision Number |
| 277 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 278 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 279 | roomClass | `String` | Room Class |
| 280 | roomNts | `Float` | Room Nts |
| 281 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 282 | roomNumber | `String` | Room Number |
| 283 | roomid | `String` | Roomid |
| 284 | roundFactorYn | `String` | Round Factor Y/N |
| 285 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 286 | routedYn | `String` | Indicates if the transaction has been routed. |
| 287 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 288 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 289 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 290 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 291 | settlementFlag | `String` | Settlement Flag |
| 292 | sourceCode | `String` | Source Code |
| 293 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 294 | sourceDescription | `String` | Source Description |
| 295 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 296 | sourceGroupCode | `String` | Source Group Code |
| 297 | sourceGroupDescription | `String` | Source Group Description |
| 298 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 299 | sourceid | `String` | Sourceid |
| 300 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 301 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 302 | supplement | `String` | Supplement |
| 303 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 304 | targetResort | `String` | Target Property |
| 305 | targetlocationid | `String` | Targetlocationid |
| 306 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 307 | taxElements | `String` | Tax Elements |
| 308 | taxGeneratedYN | `String` | Tax Generated YN |
| 309 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 310 | taxInvNumber | `String` | Tax Invoice No |
| 311 | taxRate | `Float` | Tax Rate |
| 312 | taxRateType | `String` | Tax Rate Type |
| 313 | tcGroup | `String` | Transaction Code Group |
| 314 | tcSubgroup | `String` | Transaction Code Subgroup |
| 315 | tclCode1 | `String` | Class1 Code. |
| 316 | tclCode2 | `String` | Class1 Code. |
| 317 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 318 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 319 | thresholdEntityType | `String` | Threshold Entity Type |
| 320 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 321 | toReservationNameId | `Float` | To Resv Name ID |
| 322 | tranActionId | `Float` | Tran Action ID |
| 323 | transactionActivityDate | `Date` | Transaction Activity Date |
| 324 | transactionCode | `String` | Transaction Code |
| 325 | transactionCodeDescription | `String` | Transaction Code Description |
| 326 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 327 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 328 | transactionDate | `Date` | Transaction Date |
| 329 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 330 | transactionPostingDate | `Date` | Transaction Posting Date |
| 331 | transactionPostingTime | `String` | Time transaction was posted. |
| 332 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 333 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 334 | transactionStatus | `String` | Transaction Status |
| 335 | transactionType | `String` | Transaction Type |
| 336 | transactionFromAccount | `Float` | Transaction from Account |
| 337 | transactionToAccount | `Float` | Transaction to Account |
| 338 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 339 | transcodearrangementid | `Float` | Transcodearrangementid |
| 340 | transferfromaccountid | `Float` | Transferfromaccountid |
| 341 | transferfromresvid | `Float` | Transferfromresvid |
| 342 | transfertoaccountid | `Float` | Transfertoaccountid |
| 343 | transfertoresvid | `Float` | Transfertoresvid |
| 344 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 345 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 346 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 347 | trxCode | `String` | Transaction Code |
| 348 | trxNo | `Float` | Trx Number |
| 349 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 350 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 351 | trxNumberHeader | `Float` | Transaction No Header |
| 352 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 353 | trxServiceType | `String` | Transaction Service Type |
| 354 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 355 | updateDate | `DateTime` | Update Date |
| 356 | updateUser | `Float` | Update User |
| 357 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 358 | userID | `Float` | User ID |
| 359 | vatAmount | `Float` | Tax Amount for Commission. |
| 360 | vatOffsetYn | `String` | Vat Offset Y/N |
| 361 | vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### CateringEventPostingsFinancialTransactionSvcChargeIncRevDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 4 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 5 | aRState | `String` | AR State |
| 6 | aRTransferDate | `Date` | AR Transfer Date |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountCode | `Float` | Account Code |
| 10 | accountName | `String` | Account Name |
| 11 | accountNumber | `String` | Account Number |
| 12 | accountTypeFlag | `String` | Account Type Flag |
| 13 | accountid | `Float` | Accountid |
| 14 | adjustmentYN | `String` | Adjustment YN |
| 15 | advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 17 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 18 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 19 | advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 20 | advgentranscodeid | `String` | Advgentranscodeid |
| 21 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 22 | apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 23 | approvalCode | `String` | Approval Code |
| 24 | approvalDate | `Date` | Approval Date |
| 25 | approvalStatus | `String` | Approval Status |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 31 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 32 | authemployeeid | `Float` | Authemployeeid |
| 33 | authorizer | `String` | Authorizer |
| 34 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 35 | autoSettleYn | `String` | Auto Settle Y/N |
| 36 | billingEventID | `Float` | Billing Event ID |
| 37 | bonusCheckId | `Float` | Bonus Check ID |
| 38 | bucketCode | `String` | Bucket code related to this redemption. |
| 39 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 40 | businessDate | `Date` | Business Date |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cChangeDue | `Float` | Central Change Due |
| 43 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 44 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 45 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 46 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 51 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 52 | cPackageAllowance | `Float` | Central Package Allowance |
| 53 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 54 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 55 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 56 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 57 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 58 | cTaxRate | `Float` | Central Tax Rate |
| 59 | cVatAmount | `Float` | Central Vat Amount |
| 60 | cCApproval | `String` | CC Approval Code |
| 61 | calculatePointsYN | `String` | Calculate Points YN |
| 62 | cashBagNumber | `String` | Cash Bag Number |
| 63 | cashier | `String` | Cashier |
| 64 | cashierCredit | `Float` | Cashier Credit |
| 65 | cashierDebit | `Float` | Cashier Debit |
| 66 | cashierID | `Float` | Cashier ID |
| 67 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 68 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 69 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 70 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 71 | centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| 72 | centralCashierCredit | `Float` | Central Cashier Credit |
| 73 | centralCashierDebit | `Float` | Central Cashier Debit |
| 74 | centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| 75 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 76 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 77 | centralGrossAmount | `Float` | Central Gross Amount |
| 78 | centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| 79 | centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| 80 | centralInHouseCredit | `Float` | Central In-House Credit |
| 81 | centralInHouseDebit | `Float` | Central In-House Debit |
| 82 | centralMarketCode | `String` | Central Market Code |
| 83 | centralMarketDescription | `String` | Central Market Description |
| 84 | centralMarketGroupCode | `String` | Central Market Group Code |
| 85 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 86 | centralNetAmount | `Float` | Central Net Amount |
| 87 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 88 | centralPackage | `String` | Central Package |
| 89 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 90 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 91 | centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| 92 | centralPricePerUnit | `Float` | Central Price Per Unit |
| 93 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 94 | centralServiceChargeIncludedRevenueTax | `Float` | Central Service Charge Included Revenue Tax |
| 95 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 96 | centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 97 | centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 98 | chainCode | `String` | Chain Code |
| 99 | changeDue | `Float` | Change Due |
| 100 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 101 | checkNumber | `String` | Check Number |
| 102 | closureNumber | `Float` | Closure Number |
| 103 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 104 | comments | `String` | Comments |
| 105 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 106 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 107 | compTypeCode | `String` | Comp Type Code |
| 108 | complinktranscodeid | `String` | Complinktranscodeid |
| 109 | compressedYn | `String` | Compressed Y/N |
| 110 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 111 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 112 | couponNo | `String` | Coupon Number |
| 113 | covers | `String` | Covers |
| 114 | creditCardId | `Float` | Credit Card ID |
| 115 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 116 | creditYN | `String` | Credit YN |
| 117 | currencyCode | `String` | Currency Code |
| 118 | customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| 119 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 120 | debitYN | `String` | Debit YN |
| 121 | deferredYn | `String` | Deferred Y/N |
| 122 | deletedFlag | `String` | Deleted Flag |
| 123 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 124 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 125 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 126 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 127 | depositTransactionId | `String` | Deposit Transaction ID |
| 128 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 129 | displayflag | `String` | Displayflag |
| 130 | dualCurrency | `String` | Cuurency code for parrallel currency. |
| 131 | dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| 132 | dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 133 | dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 134 | dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| 135 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 136 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 137 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 138 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 139 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 140 | exchangeDate | `Date` | Exchange Date |
| 141 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 142 | exchangeRate | `Float` | Exchange Rate |
| 143 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 144 | expInvoiceType | `String` | Export Invoice Type |
| 145 | expOriginalInvoice | `String` | Export Original Invoice |
| 146 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 147 | extTransactionId | `String` | Transaction ID from external system. |
| 148 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 149 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 150 | financialTransactionCodeType | `String` | Financial Transaction Code Type |
| 151 | fintransactionid | `Float` | Fintransactionid |
| 152 | fintransid | `Float` | Fintransid |
| 153 | fiscalBillNo | `String` | Fiscal Bill Number |
| 154 | fixedChargesYN | `String` | Fixed Charges YN |
| 155 | folioNo | `Float` | Folio Number |
| 156 | folioType | `String` | Folio Type |
| 157 | folioTypeJoin | `String` | Folio Type Join |
| 158 | folioView | `Float` | Folio View |
| 159 | folioid | `Float` | Folioid |
| 160 | foreignCurrencyID | `String` | Foreign Currency ID |
| 161 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 162 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 163 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 164 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 165 | fromReservationId | `Float` | From Resv ID |
| 166 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 167 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 168 | genCashierId | `Float` | General Cashier Id. |
| 169 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 170 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 171 | grossAmount | `Float` | Gross Amount |
| 172 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 173 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 174 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 175 | guestCountry | `String` | Guest Country |
| 176 | guestCountryCode | `String` | Guest Country Code |
| 177 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 178 | inHouseCredit | `Float` | In-House Credit |
| 179 | inHouseDebit | `Float` | In-House Debit |
| 180 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 181 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 182 | insertDate | `DateTime` | Insert Date |
| 183 | insertUser | `Float` | Insert User |
| 184 | insertUserName | `String` | The name of the user who created the record. |
| 185 | installments | `Float` | Installments |
| 186 | internalArticleid | `Float` | Articleid |
| 187 | internalBusinessdate | `Date` | Businessdate |
| 188 | internalCashierid | `Float` | Cashierid |
| 189 | internalWindowId | `Float` | Internal Window ID |
| 190 | internalYN | `String` | Internal YN |
| 191 | invoiceCloseDate | `Date` | Invoice Close Date |
| 192 | invoiceNumber | `Float` | Invoice Number |
| 193 | invoiceType | `String` | Invoice Type |
| 194 | jRNUpdateDate | `Date` | JRN Update Date |
| 195 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 196 | linkTrxNumber | `Float` | Link Transaction No |
| 197 | locationID | `String` | Internal ID to uniquely identify the Property |
| 198 | marketCode | `String` | Market Code |
| 199 | marketDescription | `String` | Market Description |
| 200 | marketDisplaySequence | `Float` | Market Display Sequence |
| 201 | marketGroupCode | `String` | Market Group Code |
| 202 | marketGroupDescription | `String` | Market Group Description |
| 203 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 204 | marketid | `String` | Marketid |
| 205 | membershipID | `Float` | Membership ID |
| 206 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 207 | nameId | `Float` | Name ID |
| 208 | nameTaxType | `String` | Name Tax Type |
| 209 | netAmount | `Float` | Net Amount |
| 210 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 211 | numberDialed | `String` | Number Dialed. |
| 212 | oTransactionDesc | `String` | Transaction Description. |
| 213 | oVOSCurrency | `String` | Currency code for contract currency. |
| 214 | oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 215 | oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 216 | oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 217 | oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 218 | onHoldYN | `String` | On Hold YN |
| 219 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 220 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 221 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 222 | originalBillNumber | `Float` | Stores original bill number after void. |
| 223 | originalFolioNumber | `String` | Stores original folio type after void. |
| 224 | originalReservationNameId | `Float` | Original Resv Name ID |
| 225 | originalRoom | `String` | Original Room |
| 226 | originalresvid | `Float` | Originalresvid |
| 227 | othersBagNumber | `String` | Others Bag Number |
| 228 | package | `String` | Package |
| 229 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 230 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 231 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 232 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 233 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 234 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 235 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 236 | parentfintransid | `Float` | Parentfintransid |
| 237 | passerByName | `String` | Passerby Name. |
| 238 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 239 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 240 | paymentType | `String` | Payment Type |
| 241 | paymentsReference | `String` | Payments-Reference |
| 242 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 243 | postingDate | `DateTime` | Posting Date |
| 244 | postingRhythm | `String` | Posting Rhythm |
| 245 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 246 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 247 | postitNo | `Float` | Postit Number |
| 248 | postitYn | `String` | Postit Y/N |
| 249 | pricePerUnit | `Float` | Price Per Unit |
| 250 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 251 | processed8300YN | `String` | Processed 8300 YN |
| 252 | productid | `String` | Productid |
| 253 | profileid | `Float` | Profileid |
| 254 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 255 | proformaYn | `String` | Proforma Y/N |
| 256 | property | `String` | Code to uniquely identify the Property |
| 257 | propertyBillPrefix | `String` | Property Bill Prefix |
| 258 | quantity | `Float` | Quantity |
| 259 | queueName | `String` | Queue Name |
| 260 | rateCode | `String` | Rate Code |
| 261 | ratecodeid | `String` | Ratecodeid |
| 262 | receiptNumber | `Float` | Receipt Number |
| 263 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 264 | repTransactionCode | `String` | Reporting Trx Code |
| 265 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 266 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 267 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 268 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 269 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 270 | reservationid | `Float` | Reservationid |
| 271 | resvenddate | `Date` | Resvenddate |
| 272 | revenueAmount | `Float` | Revenue Amount. |
| 273 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 274 | revisionNo | `Float` | Revision Number |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomClass | `String` | Room Class |
| 278 | roomNts | `Float` | Room Nts |
| 279 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 280 | roomNumber | `String` | Room Number |
| 281 | roomid | `String` | Roomid |
| 282 | roundFactorYn | `String` | Round Factor Y/N |
| 283 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 284 | routedYn | `String` | Indicates if the transaction has been routed. |
| 285 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 286 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 287 | serviceChargeIncludedRevenueTax | `Float` | Service Charge Included Revenue Tax |
| 288 | serviceChargeIncludedRevenueTaxPercent | `Float` | Service Charge Included Revenue Tax Percent |
| 289 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 290 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 291 | settlementFlag | `String` | Settlement Flag |
| 292 | sourceCode | `String` | Source Code |
| 293 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 294 | sourceDescription | `String` | Source Description |
| 295 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 296 | sourceGroupCode | `String` | Source Group Code |
| 297 | sourceGroupDescription | `String` | Source Group Description |
| 298 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 299 | sourceid | `String` | Sourceid |
| 300 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 301 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 302 | supplement | `String` | Supplement |
| 303 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 304 | targetResort | `String` | Target Property |
| 305 | targetlocationid | `String` | Targetlocationid |
| 306 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 307 | taxElements | `String` | Tax Elements |
| 308 | taxGeneratedYN | `String` | Tax Generated YN |
| 309 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 310 | taxInvNumber | `String` | Tax Invoice No |
| 311 | taxRate | `Float` | Tax Rate |
| 312 | taxRateType | `String` | Tax Rate Type |
| 313 | tcGroup | `String` | Transaction Code Group |
| 314 | tcSubgroup | `String` | Transaction Code Subgroup |
| 315 | tclCode1 | `String` | Class1 Code. |
| 316 | tclCode2 | `String` | Class1 Code. |
| 317 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 318 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 319 | thresholdEntityType | `String` | Threshold Entity Type |
| 320 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 321 | toReservationNameId | `Float` | To Resv Name ID |
| 322 | tranActionId | `Float` | Tran Action ID |
| 323 | transactionActivityDate | `Date` | Transaction Activity Date |
| 324 | transactionCode | `String` | Transaction Code |
| 325 | transactionCodeDescription | `String` | Transaction Code Description |
| 326 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 327 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 328 | transactionDate | `Date` | Transaction Date |
| 329 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 330 | transactionPostingDate | `Date` | Transaction Posting Date |
| 331 | transactionPostingTime | `String` | Time transaction was posted. |
| 332 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 333 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 334 | transactionStatus | `String` | Transaction Status |
| 335 | transactionType | `String` | Transaction Type |
| 336 | transactionFromAccount | `Float` | Transaction from Account |
| 337 | transactionToAccount | `Float` | Transaction to Account |
| 338 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 339 | transcodearrangementid | `Float` | Transcodearrangementid |
| 340 | transferfromaccountid | `Float` | Transferfromaccountid |
| 341 | transferfromresvid | `Float` | Transferfromresvid |
| 342 | transfertoaccountid | `Float` | Transfertoaccountid |
| 343 | transfertoresvid | `Float` | Transfertoresvid |
| 344 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 345 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 346 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 347 | trxCode | `String` | Transaction Code |
| 348 | trxNo | `Float` | Trx Number |
| 349 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 350 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 351 | trxNumberHeader | `Float` | Transaction No Header |
| 352 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 353 | trxServiceType | `String` | Transaction Service Type |
| 354 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 355 | updateDate | `DateTime` | Update Date |
| 356 | updateUser | `Float` | Update User |
| 357 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 358 | userID | `Float` | User ID |
| 359 | vatAmount | `Float` | Tax Amount for Commission. |
| 360 | vatOffsetYn | `String` | Vat Offset Y/N |
| 361 | vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### CateringEventPostingsFinancialTransactionSvcChargeExtraRevDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 4 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 5 | aRState | `String` | AR State |
| 6 | aRTransferDate | `Date` | AR Transfer Date |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountCode | `Float` | Account Code |
| 10 | accountName | `String` | Account Name |
| 11 | accountNumber | `String` | Account Number |
| 12 | accountTypeFlag | `String` | Account Type Flag |
| 13 | accountid | `Float` | Accountid |
| 14 | adjustmentYN | `String` | Adjustment YN |
| 15 | advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 17 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 18 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 19 | advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 20 | advgentranscodeid | `String` | Advgentranscodeid |
| 21 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 22 | apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 23 | approvalCode | `String` | Approval Code |
| 24 | approvalDate | `Date` | Approval Date |
| 25 | approvalStatus | `String` | Approval Status |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 31 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 32 | authemployeeid | `Float` | Authemployeeid |
| 33 | authorizer | `String` | Authorizer |
| 34 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 35 | autoSettleYn | `String` | Auto Settle Y/N |
| 36 | billingEventID | `Float` | Billing Event ID |
| 37 | bonusCheckId | `Float` | Bonus Check ID |
| 38 | bucketCode | `String` | Bucket code related to this redemption. |
| 39 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 40 | businessDate | `Date` | Business Date |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cChangeDue | `Float` | Central Change Due |
| 43 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 44 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 45 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 46 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 51 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 52 | cPackageAllowance | `Float` | Central Package Allowance |
| 53 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 54 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 55 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 56 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 57 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 58 | cTaxRate | `Float` | Central Tax Rate |
| 59 | cVatAmount | `Float` | Central Vat Amount |
| 60 | cCApproval | `String` | CC Approval Code |
| 61 | calculatePointsYN | `String` | Calculate Points YN |
| 62 | cashBagNumber | `String` | Cash Bag Number |
| 63 | cashier | `String` | Cashier |
| 64 | cashierCredit | `Float` | Cashier Credit |
| 65 | cashierDebit | `Float` | Cashier Debit |
| 66 | cashierID | `Float` | Cashier ID |
| 67 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 68 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 69 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 70 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 71 | centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| 72 | centralCashierCredit | `Float` | Central Cashier Credit |
| 73 | centralCashierDebit | `Float` | Central Cashier Debit |
| 74 | centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| 75 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 76 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 77 | centralGrossAmount | `Float` | Central Gross Amount |
| 78 | centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| 79 | centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| 80 | centralInHouseCredit | `Float` | Central In-House Credit |
| 81 | centralInHouseDebit | `Float` | Central In-House Debit |
| 82 | centralMarketCode | `String` | Central Market Code |
| 83 | centralMarketDescription | `String` | Central Market Description |
| 84 | centralMarketGroupCode | `String` | Central Market Group Code |
| 85 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 86 | centralNetAmount | `Float` | Central Net Amount |
| 87 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 88 | centralPackage | `String` | Central Package |
| 89 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 90 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 91 | centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| 92 | centralPricePerUnit | `Float` | Central Price Per Unit |
| 93 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 94 | centralServiceChargeExtraRevenueTax | `Float` | Central Service Charge Extra Revenue Tax |
| 95 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 96 | centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 97 | centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 98 | chainCode | `String` | Chain Code |
| 99 | changeDue | `Float` | Change Due |
| 100 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 101 | checkNumber | `String` | Check Number |
| 102 | closureNumber | `Float` | Closure Number |
| 103 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 104 | comments | `String` | Comments |
| 105 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 106 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 107 | compTypeCode | `String` | Comp Type Code |
| 108 | complinktranscodeid | `String` | Complinktranscodeid |
| 109 | compressedYn | `String` | Compressed Y/N |
| 110 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 111 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 112 | couponNo | `String` | Coupon Number |
| 113 | covers | `String` | Covers |
| 114 | creditCardId | `Float` | Credit Card ID |
| 115 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 116 | creditYN | `String` | Credit YN |
| 117 | currencyCode | `String` | Currency Code |
| 118 | customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| 119 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 120 | debitYN | `String` | Debit YN |
| 121 | deferredYn | `String` | Deferred Y/N |
| 122 | deletedFlag | `String` | Deleted Flag |
| 123 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 124 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 125 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 126 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 127 | depositTransactionId | `String` | Deposit Transaction ID |
| 128 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 129 | displayflag | `String` | Displayflag |
| 130 | dualCurrency | `String` | Cuurency code for parrallel currency. |
| 131 | dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| 132 | dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 133 | dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 134 | dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| 135 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 136 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 137 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 138 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 139 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 140 | exchangeDate | `Date` | Exchange Date |
| 141 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 142 | exchangeRate | `Float` | Exchange Rate |
| 143 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 144 | expInvoiceType | `String` | Export Invoice Type |
| 145 | expOriginalInvoice | `String` | Export Original Invoice |
| 146 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 147 | extTransactionId | `String` | Transaction ID from external system. |
| 148 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 149 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 150 | financialTransactionCodeType | `String` | Financial Transaction Code Type |
| 151 | fintransactionid | `Float` | Fintransactionid |
| 152 | fintransid | `Float` | Fintransid |
| 153 | fiscalBillNo | `String` | Fiscal Bill Number |
| 154 | fixedChargesYN | `String` | Fixed Charges YN |
| 155 | folioNo | `Float` | Folio Number |
| 156 | folioType | `String` | Folio Type |
| 157 | folioTypeJoin | `String` | Folio Type Join |
| 158 | folioView | `Float` | Folio View |
| 159 | folioid | `Float` | Folioid |
| 160 | foreignCurrencyID | `String` | Foreign Currency ID |
| 161 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 162 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 163 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 164 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 165 | fromReservationId | `Float` | From Resv ID |
| 166 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 167 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 168 | genCashierId | `Float` | General Cashier Id. |
| 169 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 170 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 171 | grossAmount | `Float` | Gross Amount |
| 172 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 173 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 174 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 175 | guestCountry | `String` | Guest Country |
| 176 | guestCountryCode | `String` | Guest Country Code |
| 177 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 178 | inHouseCredit | `Float` | In-House Credit |
| 179 | inHouseDebit | `Float` | In-House Debit |
| 180 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 181 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 182 | insertDate | `DateTime` | Insert Date |
| 183 | insertUser | `Float` | Insert User |
| 184 | insertUserName | `String` | The name of the user who created the record. |
| 185 | installments | `Float` | Installments |
| 186 | internalArticleid | `Float` | Articleid |
| 187 | internalBusinessdate | `Date` | Businessdate |
| 188 | internalCashierid | `Float` | Cashierid |
| 189 | internalWindowId | `Float` | Internal Window ID |
| 190 | internalYN | `String` | Internal YN |
| 191 | invoiceCloseDate | `Date` | Invoice Close Date |
| 192 | invoiceNumber | `Float` | Invoice Number |
| 193 | invoiceType | `String` | Invoice Type |
| 194 | jRNUpdateDate | `Date` | JRN Update Date |
| 195 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 196 | linkTrxNumber | `Float` | Link Transaction No |
| 197 | locationID | `String` | Internal ID to uniquely identify the Property |
| 198 | marketCode | `String` | Market Code |
| 199 | marketDescription | `String` | Market Description |
| 200 | marketDisplaySequence | `Float` | Market Display Sequence |
| 201 | marketGroupCode | `String` | Market Group Code |
| 202 | marketGroupDescription | `String` | Market Group Description |
| 203 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 204 | marketid | `String` | Marketid |
| 205 | membershipID | `Float` | Membership ID |
| 206 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 207 | nameId | `Float` | Name ID |
| 208 | nameTaxType | `String` | Name Tax Type |
| 209 | netAmount | `Float` | Net Amount |
| 210 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 211 | numberDialed | `String` | Number Dialed. |
| 212 | oTransactionDesc | `String` | Transaction Description. |
| 213 | oVOSCurrency | `String` | Currency code for contract currency. |
| 214 | oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 215 | oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 216 | oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 217 | oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 218 | onHoldYN | `String` | On Hold YN |
| 219 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 220 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 221 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 222 | originalBillNumber | `Float` | Stores original bill number after void. |
| 223 | originalFolioNumber | `String` | Stores original folio type after void. |
| 224 | originalReservationNameId | `Float` | Original Resv Name ID |
| 225 | originalRoom | `String` | Original Room |
| 226 | originalresvid | `Float` | Originalresvid |
| 227 | othersBagNumber | `String` | Others Bag Number |
| 228 | package | `String` | Package |
| 229 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 230 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 231 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 232 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 233 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 234 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 235 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 236 | parentfintransid | `Float` | Parentfintransid |
| 237 | passerByName | `String` | Passerby Name. |
| 238 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 239 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 240 | paymentType | `String` | Payment Type |
| 241 | paymentsReference | `String` | Payments-Reference |
| 242 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 243 | postingDate | `DateTime` | Posting Date |
| 244 | postingRhythm | `String` | Posting Rhythm |
| 245 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 246 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 247 | postitNo | `Float` | Postit Number |
| 248 | postitYn | `String` | Postit Y/N |
| 249 | pricePerUnit | `Float` | Price Per Unit |
| 250 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 251 | processed8300YN | `String` | Processed 8300 YN |
| 252 | productid | `String` | Productid |
| 253 | profileid | `Float` | Profileid |
| 254 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 255 | proformaYn | `String` | Proforma Y/N |
| 256 | property | `String` | Code to uniquely identify the Property |
| 257 | propertyBillPrefix | `String` | Property Bill Prefix |
| 258 | quantity | `Float` | Quantity |
| 259 | queueName | `String` | Queue Name |
| 260 | rateCode | `String` | Rate Code |
| 261 | ratecodeid | `String` | Ratecodeid |
| 262 | receiptNumber | `Float` | Receipt Number |
| 263 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 264 | repTransactionCode | `String` | Reporting Trx Code |
| 265 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 266 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 267 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 268 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 269 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 270 | reservationid | `Float` | Reservationid |
| 271 | resvenddate | `Date` | Resvenddate |
| 272 | revenueAmount | `Float` | Revenue Amount. |
| 273 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 274 | revisionNo | `Float` | Revision Number |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomClass | `String` | Room Class |
| 278 | roomNts | `Float` | Room Nts |
| 279 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 280 | roomNumber | `String` | Room Number |
| 281 | roomid | `String` | Roomid |
| 282 | roundFactorYn | `String` | Round Factor Y/N |
| 283 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 284 | routedYn | `String` | Indicates if the transaction has been routed. |
| 285 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 286 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 287 | serviceChargeExtraRevenueTax | `Float` | Service Charge Extra Revenue Tax |
| 288 | serviceChargeExtraRevenueTaxPercent | `Float` | Service Charge Extra Revenue Tax Percent |
| 289 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 290 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 291 | settlementFlag | `String` | Settlement Flag |
| 292 | sourceCode | `String` | Source Code |
| 293 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 294 | sourceDescription | `String` | Source Description |
| 295 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 296 | sourceGroupCode | `String` | Source Group Code |
| 297 | sourceGroupDescription | `String` | Source Group Description |
| 298 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 299 | sourceid | `String` | Sourceid |
| 300 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 301 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 302 | supplement | `String` | Supplement |
| 303 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 304 | targetResort | `String` | Target Property |
| 305 | targetlocationid | `String` | Targetlocationid |
| 306 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 307 | taxElements | `String` | Tax Elements |
| 308 | taxGeneratedYN | `String` | Tax Generated YN |
| 309 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 310 | taxInvNumber | `String` | Tax Invoice No |
| 311 | taxRate | `Float` | Tax Rate |
| 312 | taxRateType | `String` | Tax Rate Type |
| 313 | tcGroup | `String` | Transaction Code Group |
| 314 | tcSubgroup | `String` | Transaction Code Subgroup |
| 315 | tclCode1 | `String` | Class1 Code. |
| 316 | tclCode2 | `String` | Class1 Code. |
| 317 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 318 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 319 | thresholdEntityType | `String` | Threshold Entity Type |
| 320 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 321 | toReservationNameId | `Float` | To Resv Name ID |
| 322 | tranActionId | `Float` | Tran Action ID |
| 323 | transactionActivityDate | `Date` | Transaction Activity Date |
| 324 | transactionCode | `String` | Transaction Code |
| 325 | transactionCodeDescription | `String` | Transaction Code Description |
| 326 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 327 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 328 | transactionDate | `Date` | Transaction Date |
| 329 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 330 | transactionPostingDate | `Date` | Transaction Posting Date |
| 331 | transactionPostingTime | `String` | Time transaction was posted. |
| 332 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 333 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 334 | transactionStatus | `String` | Transaction Status |
| 335 | transactionType | `String` | Transaction Type |
| 336 | transactionFromAccount | `Float` | Transaction from Account |
| 337 | transactionToAccount | `Float` | Transaction to Account |
| 338 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 339 | transcodearrangementid | `Float` | Transcodearrangementid |
| 340 | transferfromaccountid | `Float` | Transferfromaccountid |
| 341 | transferfromresvid | `Float` | Transferfromresvid |
| 342 | transfertoaccountid | `Float` | Transfertoaccountid |
| 343 | transfertoresvid | `Float` | Transfertoresvid |
| 344 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 345 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 346 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 347 | trxCode | `String` | Transaction Code |
| 348 | trxNo | `Float` | Trx Number |
| 349 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 350 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 351 | trxNumberHeader | `Float` | Transaction No Header |
| 352 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 353 | trxServiceType | `String` | Transaction Service Type |
| 354 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 355 | updateDate | `DateTime` | Update Date |
| 356 | updateUser | `Float` | Update User |
| 357 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 358 | userID | `Float` | User ID |
| 359 | vatAmount | `Float` | Tax Amount for Commission. |
| 360 | vatOffsetYn | `String` | Vat Offset Y/N |
| 361 | vendorTranID | `String` | Vendor Tran ID |

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

### CateringEventPostingsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| eventpostingDetailsBookId | `FloatInput` | Book ID |
| eventpostingDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventpostingDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventpostingDetailsEvPostId | `FloatInput` | Event Post ID Primary Key |
| eventpostingDetailsEventId | `FloatInput` | Event ID |
| eventpostingDetailsEventpostingid | `FloatInput` | Eventpostingid |
| eventpostingDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventpostingDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventpostingDetailsPostedById | `FloatInput` | Posted By ID |
| eventpostingDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| eventpostingDetailsPostedBy | `StringInput` | Resource Type |
| eventpostingDetailsRevenueType | `StringInput` | Revenue Type |
| eventDetailsAllotmentid | `FloatInput` | Block ID |
| eventDetailsBookId | `FloatInput` | Block ID |
| eventDetailsAllotmentenddate | `DateInput` | Block End Date |
| eventDetailsChainCode | `StringInput` | Chain Code |
| eventDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventDetailsEndDate | `DateTimeInput` | End Date |
| eventDetailsEndDateTime | `DateInput` | End Date Time |
| eventDetailsEvResort | `StringInput` | Event Property. |
| eventDetailsEvType | `StringInput` | Ev Type |
| eventDetailsEventId | `FloatInput` | Event ID |
| eventDetailsEventLinkType | `StringInput` | Event Link Type |
| eventDetailsResort | `StringInput` | Event Property |
| eventDetailsEvStatus | `StringInput` | Event Status |
| eventDetailsEventlocationid | `StringInput` | Eventlocationid |
| eventDetailsEventtypeid | `StringInput` | Eventtypeid |
| eventDetailsGroupId | `FloatInput` | Group ID |
| eventDetailsInsertDate | `DateTimeInput` | Insert Date |
| eventDetailsEventid | `FloatInput` | Eventid |
| eventDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventDetailsEventLinkId | `FloatInput` | Linked Event |
| eventDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| eventDetailsMasterEventId | `FloatInput` | Master Event ID |
| eventDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventDetailsPkgEvId | `FloatInput` | Pkg Ev ID |
| eventDetailsPackageeventid | `FloatInput` | Packageeventid |
| eventDetailsParenteventid | `FloatInput` | Parenteventid |
| eventDetailsPkgLink | `FloatInput` | Package Link |
| eventDetailsRoomid | `StringInput` | Roomid |
| eventDetailsRoom | `StringInput` | Space |
| eventDetailsStartDate | `DateTimeInput` | Start Date |
| eventDetailsStartDateTime | `DateInput` | Start Date Time |
| eventDetailsTracecode | `StringInput` | Tracecode |
| eventDetailsUpdateDate | `DateTimeInput` | Update Date |
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
| financialtransincrevenuetaxDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtransincrevenuetaxDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtransincrevenuetaxDetailsArState | `StringInput` | AR State |
| financialtransincrevenuetaxDetailsArNumber | `FloatInput` | Account Code |
| financialtransincrevenuetaxDetailsAccountid | `FloatInput` | Accountid |
| financialtransincrevenuetaxDetailsArticleId | `FloatInput` | Article ID |
| financialtransincrevenuetaxDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtransincrevenuetaxDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtransincrevenuetaxDetailsBusinessDate | `DateInput` | Business Date |
| financialtransincrevenuetaxDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtransincrevenuetaxDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtransincrevenuetaxDetailsCashierId | `FloatInput` | Cashier ID |
| financialtransincrevenuetaxDetailsChainCode | `StringInput` | Chain Code |
| financialtransincrevenuetaxDetailsChequeNumber | `StringInput` | Check Number |
| financialtransincrevenuetaxDetailsClosureNo | `FloatInput` | Closure Number |
| financialtransincrevenuetaxDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtransincrevenuetaxDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtransincrevenuetaxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtransincrevenuetaxDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtransincrevenuetaxDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtransincrevenuetaxDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtransincrevenuetaxDetailsFintransid | `FloatInput` | Fintransid |
| financialtransincrevenuetaxDetailsBillNo | `FloatInput` | Folio Number |
| financialtransincrevenuetaxDetailsFolioView | `FloatInput` | Folio View |
| financialtransincrevenuetaxDetailsFolioid | `FloatInput` | Folioid |
| financialtransincrevenuetaxDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtransincrevenuetaxDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtransincrevenuetaxDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtransincrevenuetaxDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtransincrevenuetaxDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtransincrevenuetaxDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtransincrevenuetaxDetailsArticleid | `FloatInput` | Articleid |
| financialtransincrevenuetaxDetailsBusinessdate | `DateInput` | Businessdate |
| financialtransincrevenuetaxDetailsCashierid | `FloatInput` | Cashierid |
| financialtransincrevenuetaxDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtransincrevenuetaxDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtransincrevenuetaxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtransincrevenuetaxDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtransincrevenuetaxDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtransincrevenuetaxDetailsNameId | `FloatInput` | Name ID |
| financialtransincrevenuetaxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtransincrevenuetaxDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtransincrevenuetaxDetailsOriginalRoom | `StringInput` | Original Room |
| financialtransincrevenuetaxDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtransincrevenuetaxDetailsProduct | `StringInput` | Package |
| financialtransincrevenuetaxDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtransincrevenuetaxDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtransincrevenuetaxDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtransincrevenuetaxDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtransincrevenuetaxDetailsPostitNo | `FloatInput` | Postit Number |
| financialtransincrevenuetaxDetailsProductid | `StringInput` | Productid |
| financialtransincrevenuetaxDetailsProfileid | `FloatInput` | Profileid |
| financialtransincrevenuetaxDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtransincrevenuetaxDetailsRateCode | `StringInput` | Rate Code |
| financialtransincrevenuetaxDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtransincrevenuetaxDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtransincrevenuetaxDetailsReservationid | `FloatInput` | Reservationid |
| financialtransincrevenuetaxDetailsRoom | `StringInput` | Room Number |
| financialtransincrevenuetaxDetailsRoomid | `StringInput` | Roomid |
| financialtransincrevenuetaxDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtransincrevenuetaxDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtransincrevenuetaxDetailsTaxElements | `StringInput` | Tax Elements |
| financialtransincrevenuetaxDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtransincrevenuetaxDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtransincrevenuetaxDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtransincrevenuetaxDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtransincrevenuetaxDetailsTrxDate | `DateInput` | Transaction Date |
| financialtransincrevenuetaxDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtransincrevenuetaxDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtransincrevenuetaxDetailsTrxCode | `StringInput` | Transaction Code |
| financialtransincrevenuetaxDetailsTrxNo | `FloatInput` | Trx Number |
| financialtransincrevenuetaxDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtransincrevenuetaxDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtransincrevenuetaxDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtransincrevenuetaxDetailsAuthorizerId | `FloatInput` | User ID |
| financialtransextrarevenuetaxDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtransextrarevenuetaxDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtransextrarevenuetaxDetailsArState | `StringInput` | AR State |
| financialtransextrarevenuetaxDetailsArNumber | `FloatInput` | Account Code |
| financialtransextrarevenuetaxDetailsAccountid | `FloatInput` | Accountid |
| financialtransextrarevenuetaxDetailsArticleId | `FloatInput` | Article ID |
| financialtransextrarevenuetaxDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtransextrarevenuetaxDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtransextrarevenuetaxDetailsBusinessDate | `DateInput` | Business Date |
| financialtransextrarevenuetaxDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtransextrarevenuetaxDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtransextrarevenuetaxDetailsCashierId | `FloatInput` | Cashier ID |
| financialtransextrarevenuetaxDetailsChainCode | `StringInput` | Chain Code |
| financialtransextrarevenuetaxDetailsChequeNumber | `StringInput` | Check Number |
| financialtransextrarevenuetaxDetailsClosureNo | `FloatInput` | Closure Number |
| financialtransextrarevenuetaxDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtransextrarevenuetaxDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtransextrarevenuetaxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtransextrarevenuetaxDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtransextrarevenuetaxDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtransextrarevenuetaxDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtransextrarevenuetaxDetailsFintransid | `FloatInput` | Fintransid |
| financialtransextrarevenuetaxDetailsBillNo | `FloatInput` | Folio Number |
| financialtransextrarevenuetaxDetailsFolioView | `FloatInput` | Folio View |
| financialtransextrarevenuetaxDetailsFolioid | `FloatInput` | Folioid |
| financialtransextrarevenuetaxDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtransextrarevenuetaxDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtransextrarevenuetaxDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtransextrarevenuetaxDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtransextrarevenuetaxDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtransextrarevenuetaxDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtransextrarevenuetaxDetailsArticleid | `FloatInput` | Articleid |
| financialtransextrarevenuetaxDetailsBusinessdate | `DateInput` | Businessdate |
| financialtransextrarevenuetaxDetailsCashierid | `FloatInput` | Cashierid |
| financialtransextrarevenuetaxDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtransextrarevenuetaxDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtransextrarevenuetaxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtransextrarevenuetaxDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtransextrarevenuetaxDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtransextrarevenuetaxDetailsNameId | `FloatInput` | Name ID |
| financialtransextrarevenuetaxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtransextrarevenuetaxDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtransextrarevenuetaxDetailsOriginalRoom | `StringInput` | Original Room |
| financialtransextrarevenuetaxDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtransextrarevenuetaxDetailsProduct | `StringInput` | Package |
| financialtransextrarevenuetaxDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtransextrarevenuetaxDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtransextrarevenuetaxDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtransextrarevenuetaxDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtransextrarevenuetaxDetailsPostitNo | `FloatInput` | Postit Number |
| financialtransextrarevenuetaxDetailsProductid | `StringInput` | Productid |
| financialtransextrarevenuetaxDetailsProfileid | `FloatInput` | Profileid |
| financialtransextrarevenuetaxDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtransextrarevenuetaxDetailsRateCode | `StringInput` | Rate Code |
| financialtransextrarevenuetaxDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtransextrarevenuetaxDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtransextrarevenuetaxDetailsReservationid | `FloatInput` | Reservationid |
| financialtransextrarevenuetaxDetailsRoom | `StringInput` | Room Number |
| financialtransextrarevenuetaxDetailsRoomid | `StringInput` | Roomid |
| financialtransextrarevenuetaxDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtransextrarevenuetaxDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtransextrarevenuetaxDetailsTaxElements | `StringInput` | Tax Elements |
| financialtransextrarevenuetaxDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtransextrarevenuetaxDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtransextrarevenuetaxDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtransextrarevenuetaxDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtransextrarevenuetaxDetailsTrxDate | `DateInput` | Transaction Date |
| financialtransextrarevenuetaxDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtransextrarevenuetaxDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtransextrarevenuetaxDetailsTrxCode | `StringInput` | Transaction Code |
| financialtransextrarevenuetaxDetailsTrxNo | `FloatInput` | Trx Number |
| financialtransextrarevenuetaxDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtransextrarevenuetaxDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtransextrarevenuetaxDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtransextrarevenuetaxDetailsAuthorizerId | `FloatInput` | User ID |
| financialtranssvcchargeincrevDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtranssvcchargeincrevDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtranssvcchargeincrevDetailsArState | `StringInput` | AR State |
| financialtranssvcchargeincrevDetailsArNumber | `FloatInput` | Account Code |
| financialtranssvcchargeincrevDetailsAccountid | `FloatInput` | Accountid |
| financialtranssvcchargeincrevDetailsArticleId | `FloatInput` | Article ID |
| financialtranssvcchargeincrevDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtranssvcchargeincrevDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtranssvcchargeincrevDetailsBusinessDate | `DateInput` | Business Date |
| financialtranssvcchargeincrevDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtranssvcchargeincrevDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtranssvcchargeincrevDetailsCashierId | `FloatInput` | Cashier ID |
| financialtranssvcchargeincrevDetailsChainCode | `StringInput` | Chain Code |
| financialtranssvcchargeincrevDetailsChequeNumber | `StringInput` | Check Number |
| financialtranssvcchargeincrevDetailsClosureNo | `FloatInput` | Closure Number |
| financialtranssvcchargeincrevDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtranssvcchargeincrevDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtranssvcchargeincrevDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtranssvcchargeincrevDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtranssvcchargeincrevDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtranssvcchargeincrevDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtranssvcchargeincrevDetailsFintransid | `FloatInput` | Fintransid |
| financialtranssvcchargeincrevDetailsBillNo | `FloatInput` | Folio Number |
| financialtranssvcchargeincrevDetailsFolioView | `FloatInput` | Folio View |
| financialtranssvcchargeincrevDetailsFolioid | `FloatInput` | Folioid |
| financialtranssvcchargeincrevDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtranssvcchargeincrevDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtranssvcchargeincrevDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtranssvcchargeincrevDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtranssvcchargeincrevDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtranssvcchargeincrevDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtranssvcchargeincrevDetailsArticleid | `FloatInput` | Articleid |
| financialtranssvcchargeincrevDetailsBusinessdate | `DateInput` | Businessdate |
| financialtranssvcchargeincrevDetailsCashierid | `FloatInput` | Cashierid |
| financialtranssvcchargeincrevDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtranssvcchargeincrevDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtranssvcchargeincrevDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtranssvcchargeincrevDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtranssvcchargeincrevDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtranssvcchargeincrevDetailsNameId | `FloatInput` | Name ID |
| financialtranssvcchargeincrevDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtranssvcchargeincrevDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtranssvcchargeincrevDetailsOriginalRoom | `StringInput` | Original Room |
| financialtranssvcchargeincrevDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtranssvcchargeincrevDetailsProduct | `StringInput` | Package |
| financialtranssvcchargeincrevDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtranssvcchargeincrevDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtranssvcchargeincrevDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtranssvcchargeincrevDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtranssvcchargeincrevDetailsPostitNo | `FloatInput` | Postit Number |
| financialtranssvcchargeincrevDetailsProductid | `StringInput` | Productid |
| financialtranssvcchargeincrevDetailsProfileid | `FloatInput` | Profileid |
| financialtranssvcchargeincrevDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtranssvcchargeincrevDetailsRateCode | `StringInput` | Rate Code |
| financialtranssvcchargeincrevDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtranssvcchargeincrevDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtranssvcchargeincrevDetailsReservationid | `FloatInput` | Reservationid |
| financialtranssvcchargeincrevDetailsRoom | `StringInput` | Room Number |
| financialtranssvcchargeincrevDetailsRoomid | `StringInput` | Roomid |
| financialtranssvcchargeincrevDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtranssvcchargeincrevDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtranssvcchargeincrevDetailsTaxElements | `StringInput` | Tax Elements |
| financialtranssvcchargeincrevDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtranssvcchargeincrevDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtranssvcchargeincrevDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtranssvcchargeincrevDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtranssvcchargeincrevDetailsTrxDate | `DateInput` | Transaction Date |
| financialtranssvcchargeincrevDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtranssvcchargeincrevDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtranssvcchargeincrevDetailsTrxCode | `StringInput` | Transaction Code |
| financialtranssvcchargeincrevDetailsTrxNo | `FloatInput` | Trx Number |
| financialtranssvcchargeincrevDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtranssvcchargeincrevDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtranssvcchargeincrevDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtranssvcchargeincrevDetailsAuthorizerId | `FloatInput` | User ID |
| financialtranssvcchargeextrarevDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtranssvcchargeextrarevDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtranssvcchargeextrarevDetailsArState | `StringInput` | AR State |
| financialtranssvcchargeextrarevDetailsArNumber | `FloatInput` | Account Code |
| financialtranssvcchargeextrarevDetailsAccountid | `FloatInput` | Accountid |
| financialtranssvcchargeextrarevDetailsArticleId | `FloatInput` | Article ID |
| financialtranssvcchargeextrarevDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtranssvcchargeextrarevDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtranssvcchargeextrarevDetailsBusinessDate | `DateInput` | Business Date |
| financialtranssvcchargeextrarevDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtranssvcchargeextrarevDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtranssvcchargeextrarevDetailsCashierId | `FloatInput` | Cashier ID |
| financialtranssvcchargeextrarevDetailsChainCode | `StringInput` | Chain Code |
| financialtranssvcchargeextrarevDetailsChequeNumber | `StringInput` | Check Number |
| financialtranssvcchargeextrarevDetailsClosureNo | `FloatInput` | Closure Number |
| financialtranssvcchargeextrarevDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtranssvcchargeextrarevDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtranssvcchargeextrarevDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtranssvcchargeextrarevDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtranssvcchargeextrarevDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtranssvcchargeextrarevDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtranssvcchargeextrarevDetailsFintransid | `FloatInput` | Fintransid |
| financialtranssvcchargeextrarevDetailsBillNo | `FloatInput` | Folio Number |
| financialtranssvcchargeextrarevDetailsFolioView | `FloatInput` | Folio View |
| financialtranssvcchargeextrarevDetailsFolioid | `FloatInput` | Folioid |
| financialtranssvcchargeextrarevDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtranssvcchargeextrarevDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtranssvcchargeextrarevDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtranssvcchargeextrarevDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtranssvcchargeextrarevDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtranssvcchargeextrarevDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtranssvcchargeextrarevDetailsArticleid | `FloatInput` | Articleid |
| financialtranssvcchargeextrarevDetailsBusinessdate | `DateInput` | Businessdate |
| financialtranssvcchargeextrarevDetailsCashierid | `FloatInput` | Cashierid |
| financialtranssvcchargeextrarevDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtranssvcchargeextrarevDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtranssvcchargeextrarevDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtranssvcchargeextrarevDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtranssvcchargeextrarevDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtranssvcchargeextrarevDetailsNameId | `FloatInput` | Name ID |
| financialtranssvcchargeextrarevDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtranssvcchargeextrarevDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtranssvcchargeextrarevDetailsOriginalRoom | `StringInput` | Original Room |
| financialtranssvcchargeextrarevDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtranssvcchargeextrarevDetailsProduct | `StringInput` | Package |
| financialtranssvcchargeextrarevDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtranssvcchargeextrarevDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtranssvcchargeextrarevDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtranssvcchargeextrarevDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtranssvcchargeextrarevDetailsPostitNo | `FloatInput` | Postit Number |
| financialtranssvcchargeextrarevDetailsProductid | `StringInput` | Productid |
| financialtranssvcchargeextrarevDetailsProfileid | `FloatInput` | Profileid |
| financialtranssvcchargeextrarevDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtranssvcchargeextrarevDetailsRateCode | `StringInput` | Rate Code |
| financialtranssvcchargeextrarevDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtranssvcchargeextrarevDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtranssvcchargeextrarevDetailsReservationid | `FloatInput` | Reservationid |
| financialtranssvcchargeextrarevDetailsRoom | `StringInput` | Room Number |
| financialtranssvcchargeextrarevDetailsRoomid | `StringInput` | Roomid |
| financialtranssvcchargeextrarevDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtranssvcchargeextrarevDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtranssvcchargeextrarevDetailsTaxElements | `StringInput` | Tax Elements |
| financialtranssvcchargeextrarevDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtranssvcchargeextrarevDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtranssvcchargeextrarevDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtranssvcchargeextrarevDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtranssvcchargeextrarevDetailsTrxDate | `DateInput` | Transaction Date |
| financialtranssvcchargeextrarevDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtranssvcchargeextrarevDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtranssvcchargeextrarevDetailsTrxCode | `StringInput` | Transaction Code |
| financialtranssvcchargeextrarevDetailsTrxNo | `FloatInput` | Trx Number |
| financialtranssvcchargeextrarevDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtranssvcchargeextrarevDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtranssvcchargeextrarevDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtranssvcchargeextrarevDetailsAuthorizerId | `FloatInput` | User ID |
#### Validation Rules

**`mandatoryInput`**
- eventpostingDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query cateringEventPostings($input: CateringEventPostingsQueryArgumentsType!) {
  cateringEventPostings(input: $input) @stream {
    eventPostingDetails {
      allotmentid
      blockBeginDate
      blockEndDate
      bookId
      businessDate
      cExchangeDate
      cExchangeRate
      cPostedToExtra
      cPostedToIncl
      cSvcTaxExtra
      cSvcTaxInclude
      cTaxExtra
      cTaxIncl
      cTransactionExtra
      cTransactionIncl
      calculationRuleExtra
      calculationRuleIncluded
      centralPostingRevenueExtra
      centralRevenueIncluded
      centralServiceChargeIncluded
      centralServiceChargeExtra
      centralTaxType
      centralTaxTypeDescription
      centralUnitPrice
      checkNumber
      dSI
      deletedFlag
      evPostId
      eventId
      eventpostingid
      extraallotmentid
      extraforresvid
      extratranscodeid
      includedallotmentid
      includedforresvid
      includedtranscodeid
      insertUser
      internalEventid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      postedById
      postedByUserName
      postedDateExtra
      postedDateIncluded
      postedToExtra
      postedToIncl
      postedYN
      postedByProperty
      postedToRoomExtra
      postedToRoomIncluded
      postingRevenueExtra
      postinglocationid
      primaryKeyID
      property
      resourceName
      resourceType
      revenueIncluded
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      serviceChargeIncluded
      serviceChargePercentExtra
      serviceChargePercentIncluded
      serviceChargeTransactionCode
      serviceChargeExtra
      svcTaxExtra
      svcTaxInclude
      svcTrxCodeExtra
      svcTrxNumberExtra
      svcTrxNumberIncl
      taxExtra
      taxIncl
      taxType
      taxTypeDescription
      transactionCodeExtraRevenue
      transactionCodeIncludedRevenue
      trxExtra
      trxIncl
      trxNumberExtra
      trxNumberIncl
      unitPrice
      units
      updateDate
      updateUser
    }
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
    financialTransactionIncRevenueTaxDetails {
      aRChargeTransferFlagYN
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      adjustmentYN
      advGenerateTrxCode
      advanceBillReversedYn
      advanceBillYn
      advancedGenerateYn
      advancedGeneratedAdjustment
      advgentranscodeid
      allowanceType
      apartmentStyleBillingType
      approvalCode
      approvalDate
      approvalStatus
      arrangementCode
      arrangementDesc
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authemployeeid
      authorizer
      autoCreditbillYn
      autoSettleYn
      billingEventID
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cCashierOpeningBalance
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cTaxRate
      cVatAmount
      cCApproval
      calculatePointsYN
      cashBagNumber
      cashier
      cashierCredit
      cashierDebit
      cashierID
      cashierOpeningBalance
      ccRefundPosting
      centralARLedgerCredit
      centralARLedgerDebit
      centralAdvancedGeneratedTransactionCode
      centralCashierCredit
      centralCashierDebit
      centralCreditCardSurcharge
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralGrossAmount
      centralGuestAccountLedgerCredit
      centralGuestAccountLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralIncludedRevenueTax
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetAmount
      centralNonRevenueAmount
      centralPackage
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralPostedAmountInBaseCurrency
      centralPricePerUnit
      centralRevenueIncluded
      centralTransactionCodeDescription
      centralTrialBalanceAmountGross
      centralTrialBalanceAmountNet
      chainCode
      changeDue
      checkFileId
      checkNumber
      closureNumber
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      complinktranscodeid
      compressedYn
      contractforeigncurrencyid
      correctionYn
      couponNo
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      customChargeDate
      dSI
      debitYN
      deferredYn
      deletedFlag
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      depositlinkfintransid
      displayflag
      dualCurrency
      dualCurrencyGrossAmount
      dualCurrencyGuestCredit
      dualCurrencyGuestDebit
      dualCurrencyNetAmount
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionCodeType
      fintransactionid
      fintransid
      fiscalBillNo
      fixedChargesYN
      folioNo
      folioType
      folioTypeJoin
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      guestCountry
      guestCountryCode
      hotelAcct
      inHouseCredit
      inHouseDebit
      incTaxDeductedYn
      includedRevenueTax
      includedRevenueTaxPercent
      individualAdjustmentYN
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketid
      membershipID
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      oTransactionDesc
      oVOSCurrency
      oVOSGrossAmount
      oVOSGuestCredit
      oVOSGuestDebit
      oVOSNetAmount
      onHoldYN
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      originalresvid
      othersBagNumber
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      packagelinkfintransid
      parallelforeigncurrencyid
      parentfintransid
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      paymentsReference
      postedAmountInBaseCurrency
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300YN
      productid
      profileid
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rateCode
      ratecodeid
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationid
      resvenddate
      revenueAmount
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roomid
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      splitType
      stampDutyYN
      supplement
      taCommissionNetYn
      targetResort
      targetlocationid
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionActivityDate
      transactionCode
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionReservationNameID
      transactionStatus
      transactionType
      transactionFromAccount
      transactionToAccount
      transactionsReasonCode
      transcodearrangementid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      travelAgentCommissionableYN
      trialBalanceAmountGross
      trialBalanceAmountNet
      trxCode
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxType
      updateDate
      updateUser
      upsellChargeYn
      userID
      vatAmount
      vatOffsetYn
      vendorTranID
    }
    financialTransactionExtraRevenueTaxDetails {
      aRChargeTransferFlagYN
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      adjustmentYN
      advGenerateTrxCode
      advanceBillReversedYn
      advanceBillYn
      advancedGenerateYn
      advancedGeneratedAdjustment
      advgentranscodeid
      allowanceType
      apartmentStyleBillingType
      approvalCode
      approvalDate
      approvalStatus
      arrangementCode
      arrangementDesc
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authemployeeid
      authorizer
      autoCreditbillYn
      autoSettleYn
      billingEventID
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cCashierOpeningBalance
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cTaxRate
      cVatAmount
      cCApproval
      calculatePointsYN
      cashBagNumber
      cashier
      cashierCredit
      cashierDebit
      cashierID
      cashierOpeningBalance
      ccRefundPosting
      centralARLedgerCredit
      centralARLedgerDebit
      centralAdvancedGeneratedTransactionCode
      centralCashierCredit
      centralCashierDebit
      centralCreditCardSurcharge
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralExtraRevenueTax
      centralGrossAmount
      centralGuestAccountLedgerCredit
      centralGuestAccountLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetAmount
      centralNonRevenueAmount
      centralPackage
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralPostedAmountInBaseCurrency
      centralPricePerUnit
      centralRevenueIncluded
      centralTransactionCodeDescription
      centralTrialBalanceAmountGross
      centralTrialBalanceAmountNet
      chainCode
      changeDue
      checkFileId
      checkNumber
      closureNumber
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      complinktranscodeid
      compressedYn
      contractforeigncurrencyid
      correctionYn
      couponNo
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      customChargeDate
      dSI
      debitYN
      deferredYn
      deletedFlag
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      depositlinkfintransid
      displayflag
      dualCurrency
      dualCurrencyGrossAmount
      dualCurrencyGuestCredit
      dualCurrencyGuestDebit
      dualCurrencyNetAmount
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      extraRevenueTax
      extraRevenueTaxPercent
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionCodeType
      fintransactionid
      fintransid
      fiscalBillNo
      fixedChargesYN
      folioNo
      folioType
      folioTypeJoin
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      guestCountry
      guestCountryCode
      hotelAcct
      inHouseCredit
      inHouseDebit
      incTaxDeductedYn
      individualAdjustmentYN
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketid
      membershipID
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      oTransactionDesc
      oVOSCurrency
      oVOSGrossAmount
      oVOSGuestCredit
      oVOSGuestDebit
      oVOSNetAmount
      onHoldYN
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      originalresvid
      othersBagNumber
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      packagelinkfintransid
      parallelforeigncurrencyid
      parentfintransid
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      paymentsReference
      postedAmountInBaseCurrency
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300YN
      productid
      profileid
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rateCode
      ratecodeid
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationid
      resvenddate
      revenueAmount
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roomid
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      splitType
      stampDutyYN
      supplement
      taCommissionNetYn
      targetResort
      targetlocationid
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionActivityDate
      transactionCode
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionReservationNameID
      transactionStatus
      transactionType
      transactionFromAccount
      transactionToAccount
      transactionsReasonCode
      transcodearrangementid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      travelAgentCommissionableYN
      trialBalanceAmountGross
      trialBalanceAmountNet
      trxCode
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxType
      updateDate
      updateUser
      upsellChargeYn
      userID
      vatAmount
      vatOffsetYn
      vendorTranID
    }
    financialTransactionSvcChargeIncRevDetails {
      aRChargeTransferFlagYN
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      adjustmentYN
      advGenerateTrxCode
      advanceBillReversedYn
      advanceBillYn
      advancedGenerateYn
      advancedGeneratedAdjustment
      advgentranscodeid
      allowanceType
      apartmentStyleBillingType
      approvalCode
      approvalDate
      approvalStatus
      arrangementCode
      arrangementDesc
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authemployeeid
      authorizer
      autoCreditbillYn
      autoSettleYn
      billingEventID
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cCashierOpeningBalance
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cTaxRate
      cVatAmount
      cCApproval
      calculatePointsYN
      cashBagNumber
      cashier
      cashierCredit
      cashierDebit
      cashierID
      cashierOpeningBalance
      ccRefundPosting
      centralARLedgerCredit
      centralARLedgerDebit
      centralAdvancedGeneratedTransactionCode
      centralCashierCredit
      centralCashierDebit
      centralCreditCardSurcharge
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralGrossAmount
      centralGuestAccountLedgerCredit
      centralGuestAccountLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetAmount
      centralNonRevenueAmount
      centralPackage
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralPostedAmountInBaseCurrency
      centralPricePerUnit
      centralRevenueIncluded
      centralServiceChargeIncludedRevenueTax
      centralTransactionCodeDescription
      centralTrialBalanceAmountGross
      centralTrialBalanceAmountNet
      chainCode
      changeDue
      checkFileId
      checkNumber
      closureNumber
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      complinktranscodeid
      compressedYn
      contractforeigncurrencyid
      correctionYn
      couponNo
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      customChargeDate
      dSI
      debitYN
      deferredYn
      deletedFlag
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      depositlinkfintransid
      displayflag
      dualCurrency
      dualCurrencyGrossAmount
      dualCurrencyGuestCredit
      dualCurrencyGuestDebit
      dualCurrencyNetAmount
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionCodeType
      fintransactionid
      fintransid
      fiscalBillNo
      fixedChargesYN
      folioNo
      folioType
      folioTypeJoin
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      guestCountry
      guestCountryCode
      hotelAcct
      inHouseCredit
      inHouseDebit
      incTaxDeductedYn
      individualAdjustmentYN
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketid
      membershipID
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      oTransactionDesc
      oVOSCurrency
      oVOSGrossAmount
      oVOSGuestCredit
      oVOSGuestDebit
      oVOSNetAmount
      onHoldYN
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      originalresvid
      othersBagNumber
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      packagelinkfintransid
      parallelforeigncurrencyid
      parentfintransid
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      paymentsReference
      postedAmountInBaseCurrency
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300YN
      productid
      profileid
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rateCode
      ratecodeid
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationid
      resvenddate
      revenueAmount
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roomid
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceChargeIncludedRevenueTax
      serviceChargeIncludedRevenueTaxPercent
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      splitType
      stampDutyYN
      supplement
      taCommissionNetYn
      targetResort
      targetlocationid
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionActivityDate
      transactionCode
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionReservationNameID
      transactionStatus
      transactionType
      transactionFromAccount
      transactionToAccount
      transactionsReasonCode
      transcodearrangementid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      travelAgentCommissionableYN
      trialBalanceAmountGross
      trialBalanceAmountNet
      trxCode
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxType
      updateDate
      updateUser
      upsellChargeYn
      userID
      vatAmount
      vatOffsetYn
      vendorTranID
    }
    financialTransactionSvcChargeExtraRevDetails {
      aRChargeTransferFlagYN
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      adjustmentYN
      advGenerateTrxCode
      advanceBillReversedYn
      advanceBillYn
      advancedGenerateYn
      advancedGeneratedAdjustment
      advgentranscodeid
      allowanceType
      apartmentStyleBillingType
      approvalCode
      approvalDate
      approvalStatus
      arrangementCode
      arrangementDesc
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authemployeeid
      authorizer
      autoCreditbillYn
      autoSettleYn
      billingEventID
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cCashierOpeningBalance
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cTaxRate
      cVatAmount
      cCApproval
      calculatePointsYN
      cashBagNumber
      cashier
      cashierCredit
      cashierDebit
      cashierID
      cashierOpeningBalance
      ccRefundPosting
      centralARLedgerCredit
      centralARLedgerDebit
      centralAdvancedGeneratedTransactionCode
      centralCashierCredit
      centralCashierDebit
      centralCreditCardSurcharge
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralGrossAmount
      centralGuestAccountLedgerCredit
      centralGuestAccountLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetAmount
      centralNonRevenueAmount
      centralPackage
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralPostedAmountInBaseCurrency
      centralPricePerUnit
      centralRevenueIncluded
      centralServiceChargeExtraRevenueTax
      centralTransactionCodeDescription
      centralTrialBalanceAmountGross
      centralTrialBalanceAmountNet
      chainCode
      changeDue
      checkFileId
      checkNumber
      closureNumber
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      complinktranscodeid
      compressedYn
      contractforeigncurrencyid
      correctionYn
      couponNo
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      customChargeDate
      dSI
      debitYN
      deferredYn
      deletedFlag
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      depositlinkfintransid
      displayflag
      dualCurrency
      dualCurrencyGrossAmount
      dualCurrencyGuestCredit
      dualCurrencyGuestDebit
      dualCurrencyNetAmount
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionCodeType
      fintransactionid
      fintransid
      fiscalBillNo
      fixedChargesYN
      folioNo
      folioType
      folioTypeJoin
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      guestCountry
      guestCountryCode
      hotelAcct
      inHouseCredit
      inHouseDebit
      incTaxDeductedYn
      individualAdjustmentYN
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketid
      membershipID
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      oTransactionDesc
      oVOSCurrency
      oVOSGrossAmount
      oVOSGuestCredit
      oVOSGuestDebit
      oVOSNetAmount
      onHoldYN
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      originalresvid
      othersBagNumber
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      packagelinkfintransid
      parallelforeigncurrencyid
      parentfintransid
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      paymentsReference
      postedAmountInBaseCurrency
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300YN
      productid
      profileid
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rateCode
      ratecodeid
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationid
      resvenddate
      revenueAmount
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roomid
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceChargeExtraRevenueTax
      serviceChargeExtraRevenueTaxPercent
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      splitType
      stampDutyYN
      supplement
      taCommissionNetYn
      targetResort
      targetlocationid
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionActivityDate
      transactionCode
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionReservationNameID
      transactionStatus
      transactionType
      transactionFromAccount
      transactionToAccount
      transactionsReasonCode
      transcodearrangementid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      travelAgentCommissionableYN
      trialBalanceAmountGross
      trialBalanceAmountNet
      trxCode
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxType
      updateDate
      updateUser
      upsellChargeYn
      userID
      vatAmount
      vatOffsetYn
      vendorTranID
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
event_posting_details_schema = {
    'allotmentid': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'bookId': pl.Float64,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cPostedToExtra': pl.Float64,
    'cPostedToIncl': pl.Float64,
    'cSvcTaxExtra': pl.Float64,
    'cSvcTaxInclude': pl.Float64,
    'cTaxExtra': pl.Float64,
    'cTaxIncl': pl.Float64,
    'cTransactionExtra': pl.Float64,
    'cTransactionIncl': pl.Float64,
    'calculationRuleExtra': pl.Utf8,
    'calculationRuleIncluded': pl.Utf8,
    'centralPostingRevenueExtra': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralServiceChargeIncluded': pl.Float64,
    'centralServiceChargeExtra': pl.Float64,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralUnitPrice': pl.Float64,
    'checkNumber': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'evPostId': pl.Float64,
    'eventId': pl.Float64,
    'eventpostingid': pl.Float64,
    'extraallotmentid': pl.Float64,
    'extraforresvid': pl.Float64,
    'extratranscodeid': pl.Utf8,
    'includedallotmentid': pl.Float64,
    'includedforresvid': pl.Float64,
    'includedtranscodeid': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'postedById': pl.Float64,
    'postedByUserName': pl.Utf8,
    'postedDateExtra': pl.Utf8,
    'postedDateIncluded': pl.Utf8,
    'postedToExtra': pl.Float64,
    'postedToIncl': pl.Float64,
    'postedYN': pl.Utf8,
    'postedByProperty': pl.Utf8,
    'postedToRoomExtra': pl.Utf8,
    'postedToRoomIncluded': pl.Utf8,
    'postingRevenueExtra': pl.Float64,
    'postinglocationid': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'resourceName': pl.Utf8,
    'resourceType': pl.Utf8,
    'revenueIncluded': pl.Float64,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'serviceChargeIncluded': pl.Float64,
    'serviceChargePercentExtra': pl.Float64,
    'serviceChargePercentIncluded': pl.Float64,
    'serviceChargeTransactionCode': pl.Utf8,
    'serviceChargeExtra': pl.Float64,
    'svcTaxExtra': pl.Float64,
    'svcTaxInclude': pl.Float64,
    'svcTrxCodeExtra': pl.Utf8,
    'svcTrxNumberExtra': pl.Float64,
    'svcTrxNumberIncl': pl.Float64,
    'taxExtra': pl.Float64,
    'taxIncl': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'transactionCodeExtraRevenue': pl.Utf8,
    'transactionCodeIncludedRevenue': pl.Utf8,
    'trxExtra': pl.Float64,
    'trxIncl': pl.Float64,
    'trxNumberExtra': pl.Float64,
    'trxNumberIncl': pl.Float64,
    'unitPrice': pl.Float64,
    'units': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
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
financial_transaction_inc_revenue_tax_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
    'advGenerateTrxCode': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advancedGeneratedAdjustment': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'allowanceType': pl.Utf8,
    'apartmentStyleBillingType': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billingEventID': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCashierOpeningBalance': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'cCApproval': pl.Utf8,
    'calculatePointsYN': pl.Utf8,
    'cashBagNumber': pl.Utf8,
    'cashier': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAdvancedGeneratedTransactionCode': pl.Utf8,
    'centralCashierCredit': pl.Float64,
    'centralCashierDebit': pl.Float64,
    'centralCreditCardSurcharge': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestAccountLedgerCredit': pl.Float64,
    'centralGuestAccountLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralIncludedRevenueTax': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackage': pl.Utf8,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralPostedAmountInBaseCurrency': pl.Float64,
    'centralPricePerUnit': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralTransactionCodeDescription': pl.Utf8,
    'centralTrialBalanceAmountGross': pl.Float64,
    'centralTrialBalanceAmountNet': pl.Float64,
    'chainCode': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'customChargeDate': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'dualCurrency': pl.Utf8,
    'dualCurrencyGrossAmount': pl.Float64,
    'dualCurrencyGuestCredit': pl.Float64,
    'dualCurrencyGuestDebit': pl.Float64,
    'dualCurrencyNetAmount': pl.Float64,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionCodeType': pl.Utf8,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'guestCountry': pl.Utf8,
    'guestCountryCode': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'incTaxDeductedYn': pl.Utf8,
    'includedRevenueTax': pl.Float64,
    'includedRevenueTaxPercent': pl.Float64,
    'individualAdjustmentYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketid': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'oVOSCurrency': pl.Utf8,
    'oVOSGrossAmount': pl.Float64,
    'oVOSGuestCredit': pl.Float64,
    'oVOSGuestDebit': pl.Float64,
    'oVOSNetAmount': pl.Float64,
    'onHoldYN': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'othersBagNumber': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300YN': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roomid': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'stampDutyYN': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionReservationNameID': pl.Float64,
    'transactionStatus': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transactionsReasonCode': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'travelAgentCommissionableYN': pl.Utf8,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'userID': pl.Float64,
    'vatAmount': pl.Float64,
    'vatOffsetYn': pl.Utf8,
    'vendorTranID': pl.Utf8,
}
```
```python
financial_transaction_extra_revenue_tax_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
    'advGenerateTrxCode': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advancedGeneratedAdjustment': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'allowanceType': pl.Utf8,
    'apartmentStyleBillingType': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billingEventID': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCashierOpeningBalance': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'cCApproval': pl.Utf8,
    'calculatePointsYN': pl.Utf8,
    'cashBagNumber': pl.Utf8,
    'cashier': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAdvancedGeneratedTransactionCode': pl.Utf8,
    'centralCashierCredit': pl.Float64,
    'centralCashierDebit': pl.Float64,
    'centralCreditCardSurcharge': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralExtraRevenueTax': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestAccountLedgerCredit': pl.Float64,
    'centralGuestAccountLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackage': pl.Utf8,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralPostedAmountInBaseCurrency': pl.Float64,
    'centralPricePerUnit': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralTransactionCodeDescription': pl.Utf8,
    'centralTrialBalanceAmountGross': pl.Float64,
    'centralTrialBalanceAmountNet': pl.Float64,
    'chainCode': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'customChargeDate': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'dualCurrency': pl.Utf8,
    'dualCurrencyGrossAmount': pl.Float64,
    'dualCurrencyGuestCredit': pl.Float64,
    'dualCurrencyGuestDebit': pl.Float64,
    'dualCurrencyNetAmount': pl.Float64,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'extraRevenueTax': pl.Float64,
    'extraRevenueTaxPercent': pl.Float64,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionCodeType': pl.Utf8,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'guestCountry': pl.Utf8,
    'guestCountryCode': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'incTaxDeductedYn': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketid': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'oVOSCurrency': pl.Utf8,
    'oVOSGrossAmount': pl.Float64,
    'oVOSGuestCredit': pl.Float64,
    'oVOSGuestDebit': pl.Float64,
    'oVOSNetAmount': pl.Float64,
    'onHoldYN': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'othersBagNumber': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300YN': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roomid': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'stampDutyYN': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionReservationNameID': pl.Float64,
    'transactionStatus': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transactionsReasonCode': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'travelAgentCommissionableYN': pl.Utf8,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'userID': pl.Float64,
    'vatAmount': pl.Float64,
    'vatOffsetYn': pl.Utf8,
    'vendorTranID': pl.Utf8,
}
```
```python
financial_transaction_svc_charge_inc_rev_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
    'advGenerateTrxCode': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advancedGeneratedAdjustment': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'allowanceType': pl.Utf8,
    'apartmentStyleBillingType': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billingEventID': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCashierOpeningBalance': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'cCApproval': pl.Utf8,
    'calculatePointsYN': pl.Utf8,
    'cashBagNumber': pl.Utf8,
    'cashier': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAdvancedGeneratedTransactionCode': pl.Utf8,
    'centralCashierCredit': pl.Float64,
    'centralCashierDebit': pl.Float64,
    'centralCreditCardSurcharge': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestAccountLedgerCredit': pl.Float64,
    'centralGuestAccountLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackage': pl.Utf8,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralPostedAmountInBaseCurrency': pl.Float64,
    'centralPricePerUnit': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralServiceChargeIncludedRevenueTax': pl.Float64,
    'centralTransactionCodeDescription': pl.Utf8,
    'centralTrialBalanceAmountGross': pl.Float64,
    'centralTrialBalanceAmountNet': pl.Float64,
    'chainCode': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'customChargeDate': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'dualCurrency': pl.Utf8,
    'dualCurrencyGrossAmount': pl.Float64,
    'dualCurrencyGuestCredit': pl.Float64,
    'dualCurrencyGuestDebit': pl.Float64,
    'dualCurrencyNetAmount': pl.Float64,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionCodeType': pl.Utf8,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'guestCountry': pl.Utf8,
    'guestCountryCode': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'incTaxDeductedYn': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketid': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'oVOSCurrency': pl.Utf8,
    'oVOSGrossAmount': pl.Float64,
    'oVOSGuestCredit': pl.Float64,
    'oVOSGuestDebit': pl.Float64,
    'oVOSNetAmount': pl.Float64,
    'onHoldYN': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'othersBagNumber': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300YN': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roomid': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceChargeIncludedRevenueTax': pl.Float64,
    'serviceChargeIncludedRevenueTaxPercent': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'stampDutyYN': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionReservationNameID': pl.Float64,
    'transactionStatus': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transactionsReasonCode': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'travelAgentCommissionableYN': pl.Utf8,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'userID': pl.Float64,
    'vatAmount': pl.Float64,
    'vatOffsetYn': pl.Utf8,
    'vendorTranID': pl.Utf8,
}
```
```python
financial_transaction_svc_charge_extra_rev_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
    'advGenerateTrxCode': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advancedGeneratedAdjustment': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'allowanceType': pl.Utf8,
    'apartmentStyleBillingType': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billingEventID': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCashierOpeningBalance': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'cCApproval': pl.Utf8,
    'calculatePointsYN': pl.Utf8,
    'cashBagNumber': pl.Utf8,
    'cashier': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAdvancedGeneratedTransactionCode': pl.Utf8,
    'centralCashierCredit': pl.Float64,
    'centralCashierDebit': pl.Float64,
    'centralCreditCardSurcharge': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestAccountLedgerCredit': pl.Float64,
    'centralGuestAccountLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackage': pl.Utf8,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralPostedAmountInBaseCurrency': pl.Float64,
    'centralPricePerUnit': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralServiceChargeExtraRevenueTax': pl.Float64,
    'centralTransactionCodeDescription': pl.Utf8,
    'centralTrialBalanceAmountGross': pl.Float64,
    'centralTrialBalanceAmountNet': pl.Float64,
    'chainCode': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'customChargeDate': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'dualCurrency': pl.Utf8,
    'dualCurrencyGrossAmount': pl.Float64,
    'dualCurrencyGuestCredit': pl.Float64,
    'dualCurrencyGuestDebit': pl.Float64,
    'dualCurrencyNetAmount': pl.Float64,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionCodeType': pl.Utf8,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'guestCountry': pl.Utf8,
    'guestCountryCode': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'incTaxDeductedYn': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketid': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'oVOSCurrency': pl.Utf8,
    'oVOSGrossAmount': pl.Float64,
    'oVOSGuestCredit': pl.Float64,
    'oVOSGuestDebit': pl.Float64,
    'oVOSNetAmount': pl.Float64,
    'onHoldYN': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'othersBagNumber': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300YN': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roomid': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceChargeExtraRevenueTax': pl.Float64,
    'serviceChargeExtraRevenueTaxPercent': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'stampDutyYN': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionReservationNameID': pl.Float64,
    'transactionStatus': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transactionsReasonCode': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'travelAgentCommissionableYN': pl.Utf8,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'userID': pl.Float64,
    'vatAmount': pl.Float64,
    'vatOffsetYn': pl.Utf8,
    'vendorTranID': pl.Utf8,
}
```