# BookingsBlock
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `bookingsBlock`
> Block header and grid details including actual and potential room and revenue statistics catering events and the associated profile and reservations data.
  
**Return:** [`[BookingsBlockType]`](#bookingsblocktype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`BookingsBlockQueryArgumentsType!`](#bookingsblockqueryargumentstype) |  |

## Object Types

### BookingsBlockType

| Field | Type | Description |
| --- | --- | --- |
| blockDetails | [`BookingsBlockBlockDetailsType`](#bookingsblockblockdetailstype) | Block |
| blockAliasesDetails | [`BookingsBlockBlockAliasesDetailsType`](#bookingsblockblockaliasesdetailstype) | Block Aliases Details |
| marketDetails | [`BookingsBlockMarketDetailsType`](#bookingsblockmarketdetailstype) | Market Details |
| blockRatesDetails | [`BookingsBlockBlockRatesDetailsType`](#bookingsblockblockratesdetailstype) | Block Rates |
| blockOwnerDetails | [`BookingsBlockBlockOwnerDetailsType`](#bookingsblockblockownerdetailstype) | Block Owner |
| blockCompanyProfileDetails | [`BookingsBlockBlockCompanyProfileDetailsType`](#bookingsblockblockcompanyprofiledetailstype) | Block Profile Company |
| blockCompanyContactProfileDetails | [`BookingsBlockBlockCompanyContactProfileDetailsType`](#bookingsblockblockcompanycontactprofiledetailstype) | Block Profile Company Contact |
| blockSourceProfileDetails | [`BookingsBlockBlockSourceProfileDetailsType`](#bookingsblockblocksourceprofiledetailstype) | Block Profile Source |
| blockSourceContactProfileDetails | [`BookingsBlockBlockSourceContactProfileDetailsType`](#bookingsblockblocksourcecontactprofiledetailstype) | Block ProfileSource Contact |
| blockTravelAgentProfileDetails | [`BookingsBlockBlockTravelAgentProfileDetailsType`](#bookingsblockblocktravelagentprofiledetailstype) | Block Profile Travel Agent |
| blockTravelAgentContactProfileDetails | [`BookingsBlockBlockTravelAgentContactProfileDetailsType`](#bookingsblockblocktravelagentcontactprofiledetailstype) | Block Profile Travel Agent Contact |
| blockDetailDetails | [`BookingsBlockBlockDetailDetailsType`](#bookingsblockblockdetaildetailstype) | Block Detail |
| eventRevenueDetails | [`BookingsBlockEventRevenueDetailsType`](#bookingsblockeventrevenuedetailstype) | Event Revenue Details |
| reservationDetails | [`BookingsBlockReservationDetailsType`](#bookingsblockreservationdetailstype) | Reservation Details |
| reservationDepositScheduleDetails | [`BookingsBlockReservationDepositScheduleDetailsType`](#bookingsblockreservationdepositscheduledetailstype) | Reservation Deposit Schedule |
| financialTransactionDetails | [`BookingsBlockFinancialTransactionDetailsType`](#bookingsblockfinancialtransactiondetailstype) | Financial Transaction |
| reservationCancelPolicyDetails | [`BookingsBlockReservationCancelPolicyDetailsType`](#bookingsblockreservationcancelpolicydetailstype) | Reservation Cancel Policy Details |
| blockAccessExclusionsDetails | [`BookingsBlockBlockAccessExclusionsDetailsType`](#bookingsblockblockaccessexclusionsdetailstype) | Block Access Exclusions Details |
| blockNoteDetails | [`BookingsBlockBlockNoteDetailsType`](#bookingsblockblocknotedetailstype) | Block Note |
| blockProductDetails | [`BookingsBlockBlockProductDetailsType`](#bookingsblockblockproductdetailstype) | Block Product |
| blockItemDetails | [`BookingsBlockBlockItemDetailsType`](#bookingsblockblockitemdetailstype) | Block Item |
| blockTraceDetails | [`BookingsBlockBlockTraceDetailsType`](#bookingsblockblocktracedetailstype) | Block Trace |
| blockAlternateDatesDetails | [`BookingsBlockBlockAlternateDatesDetailsType`](#bookingsblockblockalternatedatesdetailstype) | Block Alternate Dates |
| sellMessagesDetails | [`BookingsBlockSellMessagesDetailsType`](#bookingsblocksellmessagesdetailstype) | Sell Messages Details |
| propertyPropertyDetails | [`BookingsBlockPropertyPropertyDetailsType`](#bookingsblockpropertypropertydetailstype) | Resort Details |
| allotmentSubscriptionDetails | [`BookingsBlockAllotmentSubscriptionDetailsType`](#bookingsblockallotmentsubscriptiondetailstype) | Allotment Subscription |
| bookingsBlockRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockDetailsType

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

### BookingsBlockBlockAliasesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| alias | `String` | Alias |
| allotmentHeaderId | `Float` | Allotment Header ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ualias | `String` | Not in use. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockMarketDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market group attached to the market code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketgroupid | `String` | Marketgroupid |
| marketid | `String` | Marketid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printGroup | `String` | Print Group for Nationality Report |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repMarketSellSequence | `Float` | Reporting Market Sell Sequence |
| repParentSellSequence | `Float` | Reporting Parent Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| scOrderby | `Float` | Sc Orderby |
| trxCode | `String` | Transaction Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockRatesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| beginDate | `Date` | Begin Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| endDate | `Date` | End Date |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| negotiatedYN | `String` | Negotiated rate Y/N |
| offsetType | `String` | Offset Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeLocked | `String` | Not used |
| rateType | `String` | Rate Type |
| recordType | `String` | Record Type |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockOwnerDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookId | `Float` | Book ID |
| cateringOwnerTitle | `String` | Catering Owner Title |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| fullName | `String` | Full Name |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameID | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerEmail | `String` | Owner Email |
| ownerPhone | `String` | Phone no. |
| ownerType | `String` | Owner Type |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primarySfaYn | `String` | Primary SFA owner before the property owner was assigned |
| primaryYN | `String` | Primary YN |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| roomsOwnerCode | `String` | Rooms Owner Code |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userResort | `String` | Property User belongs to |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockCompanyProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| companyID | `Float` | Company ID |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| state | `String` | State |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockCompanyContactProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| companyContactID | `Float` | Company Contact ID |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| state | `String` | State |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockSourceProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| sourceID | `Float` | Source ID |
| state | `String` | State |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockSourceContactProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| sourceContactID | `Float` | Source Contact ID |
| state | `String` | State |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockTravelAgentProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| state | `String` | State |
| toType | `String` | To Type |
| travelAgentID | `Float` | Travel Agent ID |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockTravelAgentContactProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| bookingID | `Float` | Booking ID |
| city | `String` | City |
| countryCode | `String` | Country Code |
| countryDescription | `String` | Country Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayName | `String` | Display Name |
| eMail | `String` | E Mail |
| externalYN | `String` | External YN |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneNo | `String` | Phone no. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printAccountYN | `String` | Defines if this linked profile is the Default to be used when creating activities and printing BEOs S&C ProForma and S&C Contracts. |
| property | `String` | Code to uniquely identify the Property |
| province | `String` | Province |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| state | `String` | State |
| toType | `String` | To Type |
| travelAgentContactID | `Float` | Travel Agent Contact ID |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockDetailDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionId | `Float` | Action ID |
| aggregateContractOccupancy | `Float` | Number of rooms that are in "contracted" status in this business block  for the particular room type & date that this record corresponds to. |
| aggregatePickupOccupancy | `Float` | Aggregate Pickup Occupancy |
| aggregateProspectiveOccupancy | `Float` | Aggregate Prospective Occupancy |
| allotmentDetailId | `Float` | Allotment_detail_id -- Sequence generated column. |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentbusinessdate | `Date` | Allotmentbusinessdate |
| allotmentid | `Float` | Block ID |
| available | `Float` | Indicates if Employee is available for task assignment. |
| blockEndDate | `Date` | Block End Date |
| blockedOcc1 | `Float` | Blocked Occ 1 |
| blockedOcc2 | `Float` | Blocked Occ 2 |
| blockedOcc3 | `Float` | Blocked Occ 3 |
| blockedOcc4 | `Float` | Blocked Occ 4 |
| blockedOccupancy4 | `Float` | Projected number of rooms with Quadruple occupancy  when the business block is in the Initial status ( not open for pickup yet ) for the particular room type & date that this record corresponds to. |
| blockedRooms | `Float` | Blocked Rooms |
| bookingPosition | `Float` | Stores the Booking Position room pickup. |
| cDiscountAmount | `Float` | Central Discount Amt |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMaterializationAmnt | `Float` | Central Materialization Amnt |
| cPickupRate2 | `Float` | Central Pickup Rate2 |
| cPickupRate1 | `Float` | Central Pickup Rate1 |
| cPickupRate3 | `Float` | Central Pickup Rate3 |
| cPickupRate4 | `Float` | Central Pickup Rate4 |
| cPickupRateap | `Float` | Central Pickup Rateap |
| centralContractRevenue | `Float` | Central Contract Revenue |
| centralOrderBy | `Float` | Central Order By |
| centralPickupRevenue | `Float` | Central Pickup Revenue |
| centralProspectiveRevenue | `Float` | Central Prospective Revenue |
| centralRateAmountFor1PAX | `Float` | Central Rate Amount for 1 PAX |
| centralRateAmountFor2PAX | `Float` | Central Rate Amount for 2 PAX |
| centralRateAmountFor3PAX | `Float` | Central Rate Amount for 3 PAX |
| centralRateAmountFor4PAX | `Float` | Central Rate Amount for 4 PAX |
| centralRateAmountPerAdditionalPerson | `Float` | Central Rate Amount per Additional Person |
| centralRateAmountPerChild | `Float` | Central Rate Amount per Child |
| centralRoomPoolDescription | `String` | Central Room Pool Description |
| changeDate | `Date` | Change Date |
| contractOccupancy3 | `Float` | Number of rooms with Triple occupancy that are in "contracted" status in this business block  for the particular room type & date that this record corresponds to. |
| contractOccupancyBy1PAX | `Float` | Number of rooms with Single occupancy that are in "contracted" status in this business block  for the particular room type & date that this record corresponds to. |
| contractOccupancyBy2PAX | `Float` | Number of rooms with Double occupancy that are in "contracted" status in this business block  for the particular room type & date that this record corresponds to. |
| contractOccupancyBy4PAX | `Float` | Number of rooms with Quadruple occupancy that are in "contracted" status in this business block  for the particular room type & date that this record corresponds to. |
| contractRevenue | `Float` | Contract Revenue |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `DateTime` | Created Date |
| currentRooms | `Float` | Current Rooms |
| cutoffDate | `Date` | Cutoff Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| discountAmt | `Float` | Discount Amount |
| discountPct | `Float` | Discount Percentage. |
| discountReasonCode | `String` | Discount Reason Code |
| dmlSeqNumber | `Float` | Dml Sequence No |
| elastic | `Float` | Elastic |
| elasticSold | `Float` | Not Used. |
| fixedRateYn | `String` | Fixed Rate Y/N |
| insertUser | `Float` | Insert User |
| internalAllotmentdetailid | `Float` | Allotmentdetailid |
| inventoryControlMode | `String` | Indicates how the inventory for this allotment date is controlled. Possible values: [K]eep in the block Release to [M]aster Release to [H]ouse. |
| inventoryDate | `DateTime` | Last date when column inventory_deduct was changed. |
| inventoryDeduct | `Float` | Stores either forecast_to_sell/to_sell/sold column depending on Record Type. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationID | `String` | Internal ID to uniquely identify the Property |
| materializationAmnt | `Float` | Materialization Amnt |
| oTBOcc1 | `Float` | OTB Occ 1 |
| oTBOcc2 | `Float` | OTB Occ 2 |
| oTBOcc3 | `Float` | OTB Occ 3 |
| oTBOcc4 | `Float` | OTB Occ 4 |
| oTBRooms | `Float` | OTB Rooms |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalRooms | `Float` | FORCASTED_TO_SELL inventory |
| physicalConversionFactor | `Float` | Not Used. |
| pickupOccupancyBy1PAX | `Float` | Number of rooms with Single occupancy that are in "Picked Up" status in this business block  for the particular room type & date that this record corresponds to. |
| pickupOccupancyBy2PAX | `Float` | Number of rooms with Double occupancy that are in "Picked Up" status in this business block  for the particular room type & date that this record corresponds to. |
| pickupOccupancyBy3PAX | `Float` | Number of rooms with Triple occupancy that are in "Picked Up" status in this business block  for the particular room type & date that this record corresponds to. |
| pickupOccupancyBy4PAX | `Float` | Number of rooms with Quadruple occupancy that are in "Picked Up" status in this business block  for the particular room type & date that this record corresponds to. |
| pickupRate1 | `Float` | Rate ( Amount ) to be used for rooms with Single occupancy in this business block  for the particular room type & date that this record corresponds to. |
| pickupRate2 | `Float` | Rate ( Amount ) to be used for rooms with Double occupancy in this business block  for the particular room type & date that this record corresponds to. |
| pickupRate3 | `Float` | Rate ( Amount ) to be used for rooms with Triple occupancy in this business block  for the particular room type & date that this record corresponds to. |
| pickupRate4 | `Float` | Rate ( Amount ) to be used for rooms with Quadruple occupancy in this business block  for the particular room type & date that this record corresponds to. |
| pickupRateap | `Float` | Rate ( Amount ) to be used for rooms with occupancy more than 4 in this business block  for the particular room type & date that this record corresponds to. |
| pickupRevenue | `Float` | Pickup Revenue |
| poolOrderBy | `Float` | Pool Order By |
| poolResort | `String` | Pool Property |
| poolRoomCategory | `String` | Pool Room Category |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| prospectiveOccupancyBy1PAX | `Float` | Projected number of rooms with Single occupancy  when the business block is in the Initial status ( not open for pickup yet ) for the particular room type & date that this record corresponds to. |
| prospectiveOccupancyBy2PAX | `Float` | Projected number of rooms with Double occupancy  when the business block is in the Initial status ( not open for pickup yet ) for the particular room type & date that this record corresponds to. |
| prospectiveOccupancyBy3PAX | `Float` | Projected number of rooms with Triple occupancy  when the business block is in the Initial status ( not open for pickup yet ) for the particular room type & date that this record corresponds to. |
| prospectiveRevenue | `Float` | Prospective Revenue |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rate2 | `Float` | 2 person rate |
| rate4 | `Float` | 4  person rate |
| rateAmountFor1PAX | `Float` | 1 person rate |
| rateAmountFor3PAX | `Float` | 3  person rate |
| rateAmountPerAdditionalPerson | `Float` | Additional person rate. |
| rateAmountPerChild | `Float` | Rate amount to be applied for children in this business block for the room type and date that this record corresponds to .. |
| recordType | `String` | Record Type |
| released | `Float` | Number of rooms released by block cutoff |
| resort | `String` | Property |
| roomCatOrderBy | `Float` | Room Cat Order By |
| roomCatResort | `String` | Room Cat Property |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| roomPoolCode | `String` | Room Pool Code |
| roomPoolDescription | `String` | Room Pool Description |
| roomRoomClass | `String` | Room Room Class |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| scRoomCategory | `String` | Sc Room Category |
| scroomcategoryid | `String` | Scroomcategoryid |
| shoulderDateYN | `String` | Shoulder Date YN |
| stayDay | `Date` | Stay Day |
| subBlockPickup | `Float` | Number of rooms allotted by Sub-Allocations for the Master-Allocation. |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `DateTime` | Updated Date |

[⬆ Back to Query](#query)

---

### BookingsBlockEventRevenueDetailsType

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

### BookingsBlockReservationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| accompaniedYN | `String` | Accompanied YN |
| accompanyingName | `String` | Accompanying guest names. |
| actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| actualCheckInDate | `Date` | Actual Check-In Date |
| actualCheckInTime | `String` | Actual Check-In Time |
| actualCheckOutDate | `Date` | Actual Check-Out Date |
| actualCheckOutTime | `String` | Actual Check-Out Time |
| addressId | `Float` | Address ID |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| agencyprofileid | `Float` | Agencyprofileid |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| allotmentid | `Float` | Block ID |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| approvalAmount | `Float` | Approval Amount |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| approvalCode | `String` | Approval Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `Date` | Arrival Date |
| arrivalDateTime | `DateTime` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| arrivalTime | `String` | Activity begin time |
| arrivaltransportid | `String` | Arrivaltransportid |
| attachedDate | `Date` | Attached Date |
| authorizedBillingYN | `String` | Not used. |
| authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| autoSettleDays | `Float` | Auto Settle Days |
| autoSettleType | `String` | Auto Settle Type |
| autoSettleYN | `String` | Auto Settle YN |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardMembershipID | `Float` | Award Membership ID |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| backToBackYN | `String` | Back To Back YN |
| balance | `Float` | Balance on the account. |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| basedOnRule | `String` | Based On Rule |
| baseratecurrencyid | `String` | Baseratecurrencyid |
| beginCity | `String` | Begin City |
| beginDatetime | `DateTime` | Begin Datetime |
| beginDistrict | `String` | Begin District |
| beginState | `String` | Begin State |
| beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| billNumber | `String` | Bill Number |
| billingContact | `String` | Billing Contact |
| billingContactDisplayName | `String` | Billing Contact Display Name |
| billingContactId | `Float` | Billing Contact ID |
| billingContactName | `String` | Billing Contact Name |
| billingcontactprofileid | `Float` | Billing Contact Profile ID |
| blockCode | `String` | Block Code |
| blockCreateDate | `DateTime` | Block Create Date |
| blockID | `Float` | Block ID |
| blockName | `String` | Block Name |
| blockResort | `String` | Property this block belongs to. |
| blockStatus | `String` | Block Status |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDateCreated | `Date` | Business Date Created |
| businessDatetimeCreated | `DateTime` | Business Datetime Created |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cAutoPostAmount | `Float` | Central Auto Post Amount |
| cBaseRateAmount | `Float` | Central Base Rate Amount |
| cDiscountAmount | `Float` | C Discount Amount |
| cDiscountAmt | `Float` | C Discount Amt |
| cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFixedCharge | `Float` | Central Fixed Charge |
| cGrossRateAmount | `Float` | Central Gross Rate Amt |
| cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| cNetRoomAmount | `Float` | Central Net Room Amt |
| cOriginalBaseRate | `Float` | Central Original Base Rate |
| cPackageAmount | `Float` | Central Pkg Amt |
| cPackageTax | `Float` | Central Pkg Tax |
| cRateAmount | `Float` | C Rate Amount |
| cRoomCost | `Float` | Central Room Cost |
| cRoomTax | `Float` | Central Room Tax |
| cShareAmountOriginal | `Float` | Central Share Amount Original |
| cUpsellCharge | `Float` | Central Upsell Charge |
| cancelDate | `Date` | Cancel Date |
| cancelReason | `String` | Cancel Reason |
| cancelTime | `String` | Cancel Time |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationDatetime | `DateTime` | Cancellation Datetime |
| cancellationNumber | `String` | Cancellation Number |
| cancellationReasonDescription | `String` | Cancellation Reason Description |
| cancellationreasonid | `String` | Cancellationreasonid |
| cancelledBy | `String` | The user who canceled this Reservation. |
| cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| cardNumberByMembershipType | `String` | Card Number by Membership Type |
| centralApprovalAmount | `Float` | Central Approval Amount |
| centralCancelReason | `String` | Central Cancel Reason |
| centralCommissionCode | `String` | Central Commission Code |
| centralCommissionDescription | `String` | Central Commission Description |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralDiscountReason | `String` | Central Discount Reason |
| centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralGuestType | `String` | Central Guest Type |
| centralHurdle | `Float` | Central Hurdle |
| centralPackageCode | `String` | Central Package Code |
| centralPackageCodeDescription | `String` | Central Package Code Description |
| centralPackageForecastGroup | `String` | Central Package Forecast Group |
| centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| centralPaymentAmount | `Float` | Central Payment Amount |
| centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| centralPromotionDescription | `String` | Central Promotion Description |
| centralRateableValue | `Float` | Central Rateable Value |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomTypeCode | `String` | Central Room Type Code |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| centralSharedRoomRate | `Float` | Central Shared Room Rate |
| centralSpecialRequestDescription | `String` | Central Special Request Description |
| centralTaxType | `String` | Central Tax Type |
| centralTaxTypeDescription | `String` | Central Tax Type Description |
| centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRoomRate | `Float` | Central Total Room Rate |
| centralWaitlistPriority | `String` | Central Waitlist Priority |
| centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| centralWaitlistReason | `String` | Central Waitlist Reason |
| centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| chainCode | `String` | Chain Code |
| channelDescription | `String` | Channel Description |
| channelOrderBy | `Float` | Channel Order By |
| channelid | `String` | Channelid |
| checkInInitiatedBy | `String` | Check In Initiated By |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| childBucket1 | `Float` | Child Bucket 1 |
| childBucket4 | `Float` | Child Bucket 4 |
| childBucket5 | `Float` | Child Bucket 5 |
| children | `Float` | Children |
| childrenAgeGroup2 | `Float` | Children Age Group 2) |
| childrenAgeGroup3 | `Float` | Children Age Group 3) |
| childrenAges | `String` | Children Ages |
| commissionCode | `String` | Commission Code |
| commissionDescription | `String` | Commission Description |
| commissionHoldCode | `String` | Commission Hold Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYN | `String` | Commissionable YN |
| commissionid | `String` | Commissionid |
| compHouse | `String` | Comp House |
| compTypeCode | `String` | Comp Type Code |
| companyCity | `String` | Company City |
| companyCountry | `String` | Company Country |
| companyID | `Float` | Company ID |
| companyName | `String` | Company Name |
| companyProfileCorporateID | `String` | Company Profile Corporate ID |
| companyProfileID | `Float` | Company Profile ID |
| complimentaryYN | `String` | Complimentary YN |
| compreasonid | `String` | Compreasonid |
| computedResvStatus | `String` | Calculated reservation status. |
| confirmationLegNumber | `Float` | Confirmation Leg Number. |
| confirmationNo | `String` | Shared Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactName | `String` | Contact Name; UDFC02 on reservation. |
| contactProfileID | `Float` | Contact Profile ID |
| contactProfileName | `String` | Contact Profile Name |
| createdBy | `String` | The name of the user who created the record. |
| createdByDefaultResort | `String` | Created By Default Property |
| createdDate | `Date` | Created Date |
| createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| creditCardAuthDate | `Date` | Credit Card Auth Date |
| creditCardId | `Float` | Credit Card ID |
| creditLimit | `Float` | Credit Limit |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReferenceNumber | `String` | Custom Reference Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| deletedFlag | `String` | Deleted Flag |
| departtransportid | `String` | Departtransportid |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Departure Date |
| departureDateTime | `Date` | Departure Date Time |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportationYN | `String` | Departure Transportation YN |
| depositMaturityType | `String` | Stores the Deposit maturity preference. |
| detatchedDate | `Date` | Detatched Date |
| detatchedYN | `String` | Detatched YN |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| directbillauthby | `Float` | Directbillauthby |
| discountAmount | `Float` | Discount Amount |
| discountAmt | `Float` | Discount Amount |
| discountPercent | `Float` | Discount Percentage. |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReason | `String` | Discount Reason |
| discountReasonDescription | `String` | Discount Reason Description |
| discountreasonid | `String` | Discountreasonid |
| displayColor | `String` | Display Color |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYN | `String` | Do not move room flag. |
| dropOffCarrierCode | `String` | Drop Off Carrier Code |
| dropOffDate | `Date` | Drop Off Date |
| dropOffStation | `String` | Drop Off Station |
| dropOffTime | `String` | Drop Off Time |
| dropOffType | `String` | Drop Off Type |
| dropOffTypeDescription | `String` | Drop Off Type Description |
| eTRComments | `String` | Comments related to Estimated Time of Return. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| emailId | `Float` | Email ID |
| emailYn | `String` | Email Y/N |
| endCity | `String` | End City |
| endDatetime | `DateTime` | End Datetime |
| endDistrict | `String` | End District |
| endState | `String` | End State |
| endbusinessdate | `Date` | Endbusinessdate |
| entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| estimatedDepartureTime | `Date` | Estimated Departure Time |
| eventId | `Float` | Event ID |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalReference | `String` | External Reference |
| externalReferencesList | `String` | External References List |
| extraBeds | `Float` | Extra Beds |
| fBRevenue | `Float` | FB Revenue |
| fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| faxId | `Float` | Fax ID |
| faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| feature | `String` | This stores the codes for the rooms features. Currently not used |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| fixedCharge | `Float` | Not used. |
| fixedRateYN | `String` | Fixed Rate YN |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioNumber | `String` | Folio Number |
| folioText1 | `String` | Folio Text1 |
| folioText2 | `String` | Folio Text2 |
| foreignCurrencyID | `String` | Foreign Currency ID |
| freeChild | `Float` | Free Child |
| frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| grossRateFuture | `Float` | Gross Rate Future |
| grossRatePast | `Float` | Gross Rate Past |
| groupName | `String` | Group Name |
| groupProfileARNumber | `Float` | Group Profile AR Number |
| groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| groupProfileClientID | `String` | Group Profile Client ID |
| groupProfileID | `Float` | Group Profile ID |
| groupProfileName | `String` | Group Profile Name |
| guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| guaranteecodeid | `String` | Guaranteecodeid |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| guestSignature | `String` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestType | `String` | Guest Type |
| guestprofileid | `Float` | Guestprofileid |
| gueststatusid | `String` | Gueststatusid |
| guesttypeid | `String` | Guesttypeid |
| housekeepingServiceTime | `String` | Housekeeping Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | Hurdle Override |
| iDByMembershipClass | `String` | ID by Membership Class |
| iDByMembershipType | `String` | ID by Membership Type |
| individualCity | `String` | Guest Address. |
| individualCountry | `String` | Country of the guest |
| individualFirstName | `String` | Individual First Name |
| individualLastName | `String` | Individual Last Name |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertDateTime | `DateTime` | Insert DateTime |
| insertUser | `Float` | Insert User |
| intermediaryYn | `String` | Intermediary Y/N |
| internalAwardMembershipId | `Float` | Award Membership ID |
| internalBaseratecode | `String` | Baseratecode |
| internalBlockId | `Float` | Block ID. |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalSourceprofileid | `Float` | Sourceprofileid |
| itemsQuantities | `String` | Items and Quantities |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyValidUntil | `Date` | Key Valid Until |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastRoomNumber | `String` | Not used. |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| leadTimeDays | `Float` | Lead Time for ordering |
| lengthOfStay | `Float` | Length of Stay |
| linkedArrivalDate | `DateTime` | Linked Arrival Date |
| linkedDepartureDate | `DateTime` | Linked Departure Date |
| linkedRoomType | `String` | Linked Room Type |
| listOfMembershipID | `String` | Membership ID |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| mailYn | `String` | Mail Y/N |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| mcGenBeginDistrict | `String` | Mc Gen Begin District |
| mcGenBeginState | `String` | Mc Gen Begin State |
| mcGenEndDistrict | `String` | Mc Gen End District |
| mcGenEndState | `String` | Mc Gen End State |
| mcGenNextCountry | `String` | Mc Gen Next Country |
| mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| memberDescription | `String` | Member Description |
| memberLevel | `String` | Member Level |
| memberNumber | `String` | Member Number |
| membershipClass | `String` | Membership Class |
| membershipClassDescription | `String` | Membership Class Description |
| membershipCode | `String` | Membership Code |
| membershipId | `Float` | Membership ID |
| membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| name | `String` | Name |
| nameUsageType | `String` | Name Usage Type |
| nextCountry | `String` | Next Country |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| numberOfRooms | `Float` | No of Rooms |
| operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originOfBooking | `String` | Origin Of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| packageCode | `String` | Package Code |
| packageCodeDescription | `String` | Package Code Description |
| packageForecastGroup | `String` | Package Forecast Group |
| packageForecastGroupDescription | `String` | Package Forecast Group Description |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| parentreservationid | `Float` | Parentreservationid |
| partAllotment | `String` | Part Allotment |
| partyCode | `String` | Party Code |
| paxNo | `Float` | Pax Number |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentMethod | `String` | Payment Method |
| paymentmethodid | `String` | Paymentmethodid |
| periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pickUpCarrierCode | `String` | Pick Up Carrier Code |
| pickUpDate | `Date` | Pick Up Date |
| pickUpStation | `String` | Pick Up Station |
| pickUpTransportNumber | `String` | Pick Up Transport Number |
| pickUpType | `String` | Pick Up Type |
| pickUpTypeDescription | `String` | Pick Up Type Description |
| pickUpTime | `String` | Pick-Up Time |
| pickupRequiredYN | `String` | Pickup Required YN |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| postingAllowedYN | `String` | Posting Allowed YN |
| preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| preArrReviewedUser | `Float` | User id who reviewed the record. |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| preferredRoomType | `String` | Preferred Room Type |
| previousCountry | `String` | Previous Country |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryShare | `String` | Primary Share |
| printRateYN | `String` | Print Rate YN |
| projectedFBRevenue | `Float` | Projected FB Revenue |
| projectedRoomRevenue | `Float` | Projected Room Revenue |
| projectedTotalRevenue | `Float` | Projected Total Revenue |
| promotionCode | `String` | Promotion Code |
| promotionDescription | `String` | Promotion Description |
| property | `String` | Indicates if the value set for the specific property. |
| pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| purgeDate | `DateTime` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quantity | `Float` | Number of Rooms |
| queuePriority | `Float` | Queue priority of the reservation. |
| queueWaitTime | `Float` | Queue Wait Time |
| quoteId | `String` | Quote ID provided by external system. |
| rateAmount | `Float` | Rate Amount |
| rateCode | `String` | Rate Code |
| rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| rateableValue | `Float` | Stay rateable value. |
| ratecodeid | `String` | Ratecodeid |
| rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| rdResvStatus | `String` | Rd Reservation Status |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| rdenResort | `String` | Rden Property |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| registrationNumber | `Float` | Registration Number |
| reinstateDate | `DateTime` | Reinstate Date |
| repChannel | `String` | Reporting Channel |
| repChannelDescription | `String` | Reporting Channel Description |
| reportId | `String` | Report ID |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `DateTime` | Reservation Date |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | Reservation Type Description |
| reservationid | `Float` | Reservationid |
| resort | `String` | Property |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | Restriction Override |
| resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| resvNameid | `Float` | Reservation Nameid |
| resvNumber | `Float` | Not used in PMS currently. |
| resvcontactprofileid | `Float` | Resvcontactprofileid |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rhBillingContactId | `Float` | Rh Billing Contact ID |
| rhReservationContactId | `Float` | Rh Resv Contact ID |
| rhRoomFeatures | `String` | Rh Room Features |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomInstructions | `String` | Room Instructions |
| roomResort | `String` | Meeting Room Property |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueRemaining | `Float` | Room Revenue Remaining |
| roomServiceTime | `String` | This is the Turndown room service time. |
| roomTypeDescription | `String` | Room Type Description |
| roomTypeToChargeCode | `String` | Room Type To Charge Code |
| roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomid | `String` | Roomid |
| routingYN | `String` | Routing YN |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| sguestName | `String` | Sguest Name |
| shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| shareId | `Float` | Share ID. |
| shareName | `String` | Share Name |
| sharePrcnt | `Float` | Not used. |
| shareSeqNumber | `Float` | Type of revenue |
| shareOfRateAmount | `Float` | Share of Rate Amount |
| sharedGuestName | `String` | Shared Guest Name |
| sharedProfileID | `Float` | Shared Profile ID |
| sharedReservationStatus | `String` | Shared Reservation Status |
| sharingYN | `String` | Sharing YN |
| sourceCity | `String` | Source City |
| sourceCode | `String` | Source Code |
| sourceCountry | `String` | Source Country |
| sourceName | `String` | Source Name |
| sourceProfileARNumber | `Float` | Source Profile AR Number |
| sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| sourceProfileIATANumber | `String` | Source Profile IATA Number |
| sourceProfileID | `Float` | Source Profile ID |
| sourceProfileName | `String` | Source Profile Name |
| sourceid | `String` | Sourceid |
| specialRequest | `String` | Special Request |
| specialRequestDescription | `String` | Special Request Description |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| splitfromreservationid | `Float` | Splitfromreservationid |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| stayRecordId | `Float` | Stay Record ID |
| suiteNumber | `String` | Suite Number |
| superSearchIndexText | `String` | Super Search Index Text |
| taRecordLocator | `String` | Ta Record Locator |
| taxExemptNumber | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Float` | Tax No of Stays |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| taxtypeid | `String` | Taxtypeid |
| tiad | `String` | Tiad |
| ticketNos | `String` | Ticket Nos |
| totalCostOfStay | `Float` | Total Cost of Stay |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueRemaining | `Float` | Total Revenue Remaining |
| totalRoomRate | `Float` | Total Room Rate |
| trackItGroups | `String` | Track It Groups |
| trackItTypes | `String` | Track It Types |
| transactionid | `Float` | Transactionid |
| travelAgentCity | `String` | Travel Agent Address. |
| travelAgentCountry | `String` | Travel Agent Country |
| travelAgentID | `Float` | Travel Agent ID |
| travelAgentName | `String` | Travel Agent Name |
| travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| travelAgentProfileID | `Float` | Travel Agent Profile ID |
| travelAgentProfileName | `String` | Travel Agent Profile Name |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
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
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateDate | `DateTime` | Update Date |
| updateDatetime | `DateTime` | Update Datetime |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedByDefaultResort | `String` | Updated By Default Property |
| updatedDate | `Date` | Updated Date |
| updatedTime | `String` | Updated Time |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| visaExpiryDate | `Date` | Visa Expiry Date |
| visaIssueDate | `Date` | Visa Issue Date |
| visaNumber | `String` | Visa Number |
| waitlistComment | `String` | Waitlist Comment |
| waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| waitlistPriority | `String` | Waitlist Priority |
| waitlistPriorityDescription | `String` | Waitlist Priority Description |
| waitlistReason | `String` | Waitlist Reason |
| waitlistReasonDescription | `String` | Waitlist Reason Description |
| waitlistpriorityid | `String` | Waitlistpriorityid |
| waitlistreasonid | `String` | Waitlistreasonid |
| walkInYN | `String` | Walk-In YN |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingsBlockReservationDepositScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activityDeposit | `Float` | Deposit Amount for the Activity. Populated by Concept system currently. |
| cActivityDeposit | `Float` | Central Activity Deposit |
| cCancelPnltyAmount | `Float` | Central Cancel Pnlty Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForeignDepositAmount | `Float` | Central Foreign Deposit Amount |
| cancelDeadline | `Date` | Date the reservation can be cancelled |
| cancelPnltyAmount | `Float` | Amount to be charged for a cancellation |
| centralDepositAmountOutstanding | `Float` | Central Deposit Amount Outstanding |
| centralDepositAmountRequested | `Float` | Central Deposit Amount Requested |
| centralTotalDepositPayments | `Float` | Central Total Deposit Payments |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| depositAmountOutstanding | `Float` | Deposit Amount Outstanding |
| depositAmountRequested | `Float` | Deposit Amount Requested |
| depositDueDate | `Date` | Deposit Due Date |
| depositPercentage | `Float` | Deposit Percentage |
| depositReqLinkId | `Float` | ID will be populated for reversal records to link the main deposit request. |
| depositReqReceiptNo | `Float` | Deposit Req Receipt Number |
| depositReqReversalYn | `String` | Identifies if this record is a deposit request reversal. |
| depositRule | `String` | Deposit Rule |
| depositRuleDescription | `String` | Deposit Rule Description |
| depositRuleType | `String` | Deposit Rule Type |
| depositScheduleReservationNameId | `Float` | Deposit Schedule Resv Name ID |
| depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| dmlSeqNumber | `Float` | Dml Sequence No |
| exchangeRateInfo | `String` | Exchange Rate info used for cancelation penalty if Rate code is in a difference currency. |
| externalId | `String` | External ID |
| foreignDepositAmount | `Float` | Deposit Amount in Foreign currency if Rate code is in a different currency. |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualYn | `String` | Manual Y/N |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentFlag | `String` | Not used |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processedYn | `String` | Processed Y/N |
| productId | `String` | Product ID |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateDcSeq | `Float` | Rate Dc Sequence |
| reservationDepositScheduleId | `Float` | Resv Deposit Schedule ID |
| roomDeposit | `Float` | Deposit Amount due to pure room charges. |
| totalDepositPayments | `Float` | Amount of the transaction that resulted in the form being required |
| trxDate | `Date` | Transaction Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockFinancialTransactionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aRLedgerCredit | `Float` | AR Ledger Credit |
| aRLedgerDebit | `Float` | AR Ledger Debit |
| aRState | `String` | AR State |
| aRTransferDate | `Date` | AR Transfer Date |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountCode | `Float` | Account Code |
| accountName | `String` | Account Name |
| accountNumber | `String` | Account Number |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| adjustmentYN | `String` | Adjustment YN |
| advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| advgentranscodeid | `String` | Advgentranscodeid |
| allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| approvalCode | `String` | Approval Code |
| approvalDate | `Date` | Approval Date |
| approvalStatus | `String` | Approval Status |
| arrangementCode | `String` | Arrangement Code |
| arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| arrangementId | `Float` | Arrangement ID |
| articleId | `Float` | Article ID |
| associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| authemployeeid | `Float` | Authemployeeid |
| authorizer | `String` | Authorizer |
| autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| autoSettleYn | `String` | Auto Settle Y/N |
| billingEventID | `Float` | Billing Event ID |
| bonusCheckId | `Float` | Bonus Check ID |
| bucketCode | `String` | Bucket code related to this redemption. |
| bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| businessDate | `Date` | Business Date |
| cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| cChangeDue | `Float` | Central Change Due |
| cContractGrossAmount | `Float` | Central Contract Gross Amount |
| cContractGuestCredit | `Float` | Central Contract Guest Credit |
| cContractGuestDebit | `Float` | Central Contract Guest Debit |
| cContractNetAmount | `Float` | Central Contract Net Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| cPackageAllowance | `Float` | Central Package Allowance |
| cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| cParallelNetAmount | `Float` | Central Parallel Net Amount |
| cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| cTaxRate | `Float` | Central Tax Rate |
| cVatAmount | `Float` | Central Vat Amount |
| cCApproval | `String` | CC Approval Code |
| calculatePointsYN | `String` | Calculate Points YN |
| cashBagNumber | `String` | Cash Bag Number |
| cashier | `String` | Cashier |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierID | `Float` | Cashier ID |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| centralCashierCredit | `Float` | Central Cashier Credit |
| centralCashierDebit | `Float` | Central Cashier Debit |
| centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| centralDepositAmountPaid | `Float` | Central Deposit Amount Paid |
| centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| centralGrossAmount | `Float` | Central Gross Amount |
| centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| centralInHouseCredit | `Float` | Central In-House Credit |
| centralInHouseDebit | `Float` | Central In-House Debit |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralNetAmount | `Float` | Central Net Amount |
| centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| centralPackage | `String` | Central Package |
| centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| centralPricePerUnit | `Float` | Central Price Per Unit |
| centralRevenueIncluded | `Float` | Central Revenue Included |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| chainCode | `String` | Chain Code |
| changeDue | `Float` | Change Due |
| checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| checkNumber | `String` | Check Number |
| closureNumber | `Float` | Closure Number |
| collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| comments | `String` | Comments |
| compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| compTypeCode | `String` | Comp Type Code |
| complinktranscodeid | `String` | Complinktranscodeid |
| compressedYn | `String` | Compressed Y/N |
| contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| couponNo | `String` | Coupon Number |
| covers | `String` | Covers |
| creditCardId | `Float` | Credit Card ID |
| creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| creditYN | `String` | Credit YN |
| currencyCode | `String` | Currency Code |
| customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debitYN | `String` | Debit YN |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| depositLedgerCredit | `Float` | Deposit Ledger Credit |
| depositLedgerDebit | `Float` | Deposit Ledger Debit |
| depositTransactionId | `String` | Deposit Transaction ID |
| depositlinkfintransid | `Float` | Depositlinkfintransid |
| displayflag | `String` | Displayflag |
| dualCurrency | `String` | Cuurency code for parrallel currency. |
| dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| exchangeDate | `Date` | Exchange Date |
| exchangeDifferenceYN | `String` | Exchange Difference YN |
| exchangeRate | `Float` | Exchange Rate |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| extTransactionId | `String` | Transaction ID from external system. |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| financialTransactionCodeType | `String` | Financial Transaction Code Type |
| fintransactionid | `Float` | Fintransactionid |
| fintransid | `Float` | Fintransid |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fixedChargesYN | `String` | Fixed Charges YN |
| folioNo | `Float` | Folio Number |
| folioType | `String` | Folio Type |
| folioTypeJoin | `String` | Folio Type Join |
| folioView | `Float` | Folio View |
| folioid | `Float` | Folioid |
| foreignCurrencyID | `String` | Foreign Currency ID |
| forexCommAmount | `Float` | Foreign Exchange commission amount. |
| forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| fromReservationId | `Float` | From Resv ID |
| ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| genCashierId | `Float` | General Cashier Id. |
| gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| grossAmount | `Float` | Gross Amount |
| groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| guestCountry | `String` | Guest Country |
| guestCountryCode | `String` | Guest Country Code |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| inHouseCredit | `Float` | In-House Credit |
| inHouseDebit | `Float` | In-House Debit |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| installments | `Float` | Installments |
| internalArticleid | `Float` | Articleid |
| internalBusinessdate | `Date` | Businessdate |
| internalCashierid | `Float` | Cashierid |
| internalWindowId | `Float` | Internal Window ID |
| internalYN | `String` | Internal YN |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNumber | `Float` | Invoice Number |
| invoiceType | `String` | Invoice Type |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkTrxNumber | `Float` | Link Transaction No |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketid | `String` | Marketid |
| membershipID | `Float` | Membership ID |
| mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| netAmount | `Float` | Net Amount |
| nonRevenueAmount | `Float` | Non Revenue Amount |
| numberDialed | `String` | Number Dialed. |
| oTransactionDesc | `String` | Transaction Description. |
| oVOSCurrency | `String` | Currency code for contract currency. |
| oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| onHoldYN | `String` | On Hold YN |
| orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalBillNumber | `Float` | Stores original bill number after void. |
| originalFolioNumber | `String` | Stores original folio type after void. |
| originalReservationNameId | `Float` | Original Resv Name ID |
| originalRoom | `String` | Original Room |
| originalresvid | `Float` | Originalresvid |
| othersBagNumber | `String` | Others Bag Number |
| package | `String` | Package |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| packageLedgerDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| packagelinkfintransid | `Float` | Packagelinkfintransid |
| parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| parentfintransid | `Float` | Parentfintransid |
| passerByName | `String` | Passerby Name. |
| paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| paymentType | `String` | Payment Type |
| paymentsReference | `String` | Payments-Reference |
| postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| postedAmountInTransactionCurrency | `Float` | Posted Amount in Transaction Currency |
| postingDate | `DateTime` | Posting Date |
| postingRhythm | `String` | Posting Rhythm |
| postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| postitNo | `Float` | Postit Number |
| postitYn | `String` | Postit Y/N |
| pricePerUnit | `Float` | Price Per Unit |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processed8300YN | `String` | Processed 8300 YN |
| productid | `String` | Productid |
| profileid | `Float` | Profileid |
| profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| proformaYn | `String` | Proforma Y/N |
| property | `String` | Code to uniquely identify the Property |
| propertyBillPrefix | `String` | Property Bill Prefix |
| quantity | `Float` | Quantity |
| queueName | `String` | Queue Name |
| rateCode | `String` | Rate Code |
| ratecodeid | `String` | Ratecodeid |
| receiptNumber | `Float` | Receipt Number |
| receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| repTransactionCode | `String` | Reporting Trx Code |
| repTransactionCodeGroup | `String` | Reporting Tc Group |
| repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationid | `Float` | Reservationid |
| resvenddate | `Date` | Resvenddate |
| revenueAmount | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| revisionNo | `Float` | Revision Number |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomClass | `String` | Room Class |
| roomNts | `Float` | Room Nts |
| roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| roomNumber | `String` | Room Number |
| roomid | `String` | Roomid |
| roundFactorYn | `String` | Round Factor Y/N |
| roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| routedYn | `String` | Indicates if the transaction has been routed. |
| routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| serviceChargeIncludedRevenueTaxPercent | `Float` | Service Charge Included Revenue Tax Percent |
| serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| settlementFlag | `String` | Settlement Flag |
| sourceCode | `String` | Source Code |
| sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceid | `String` | Sourceid |
| splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| supplement | `String` | Supplement |
| taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| targetResort | `String` | Target Property |
| targetlocationid | `String` | Targetlocationid |
| taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| taxElements | `String` | Tax Elements |
| taxGeneratedYN | `String` | Tax Generated YN |
| taxInclusiveYN | `String` | Tax Inclusive YN |
| taxInvNumber | `String` | Tax Invoice No |
| taxRate | `Float` | Tax Rate |
| taxRateType | `String` | Tax Rate Type |
| tcGroup | `String` | Transaction Code Group |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tclCode1 | `String` | Class1 Code. |
| tclCode2 | `String` | Class1 Code. |
| thresholdDiversionId | `Float` | Threshold Diversion ID |
| thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| thresholdEntityType | `String` | Threshold Entity Type |
| thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| toReservationNameId | `Float` | To Resv Name ID |
| tranActionId | `Float` | Tran Action ID |
| transactionActivityDate | `Date` | Transaction Activity Date |
| transactionCode | `String` | Transaction Code |
| transactionCodeDescription | `String` | Transaction Code Description |
| transactionCodeGroupDesc | `String` | Tc Group Description |
| transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| transactionDate | `Date` | Transaction Date |
| transactionNumberAddedBy | `Float` | Transaction Number Added By |
| transactionPostingDate | `Date` | Transaction Posting Date |
| transactionPostingTime | `String` | Time transaction was posted. |
| transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| transactionStatus | `String` | Transaction Status |
| transactionType | `String` | Transaction Type |
| transactionFromAccount | `Float` | Transaction from Account |
| transactionToAccount | `Float` | Transaction to Account |
| transactionsReasonCode | `String` | Transactions-Reason Code |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transferfromaccountid | `Float` | Transferfromaccountid |
| transferfromresvid | `Float` | Transferfromresvid |
| transfertoaccountid | `Float` | Transfertoaccountid |
| transfertoresvid | `Float` | Transfertoresvid |
| travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| trxCode | `String` | Transaction Code |
| trxNo | `Float` | Trx Number |
| trxNoAgainstPackage | `Float` | Trx Number Against Package |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberHeader | `Float` | Transaction No Header |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| trxType | `String` | Transaction type: possible values: [CACH]. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| userID | `Float` | User ID |
| vatAmount | `Float` | Tax Amount for Commission. |
| vatOffsetYn | `String` | Vat Offset Y/N |
| vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### BookingsBlockReservationCancelPolicyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| percentCancellation | `Float` | Percentage to be charged for the cancellation |
| percentDue | `Float` | Percentage due for the cancellation |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForeignCancelAmount | `Float` | Central Foreign Cancel Amount |
| cancellationDate | `DateTime` | Cancel Date. |
| cancellationPenalty | `String` | Cancellation Penalty |
| cancellationPenaltyAmount | `Float` | Amount to be charged for the cancellation |
| cancellationPenaltyType | `String` | Cancellation Penalty Type |
| cancellationRuleDescription | `String` | Cancellation Rule Description |
| centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| dmlSeqNumber | `Float` | Dml Sequence No |
| exchangeRateInfo | `String` | Exchange Rate info used for cancelation penalty if Rate code is in a difference currency. |
| externalId | `String` | External ID |
| foreignCancelAmount | `Float` | Cancel Amount in Foreign currency if Rate code is in a different currency. |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualYn | `String` | Manual Y/N |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processedYn | `String` | Processed Y/N |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateDcSeq | `Float` | Rate Dc Sequence |
| reservationCancelPolicyId | `Float` | Internal |
| reservationNameId | `Float` | Resv Name ID |
| roomNights | `Float` | Room Nights |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockAccessExclusionsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessExclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| accessSourceType | `String` | Always CRO. |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allowCancelReservation | `String` | Has permission to cancel reservations for the block. |
| allowCreateReservation | `String` | Has permission to create reservations for the block. |
| allowModifyReservation | `String` | Has permission to modify reservations for the block. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| hideFromAvailabilityScreen | `String` | Hide(Y) / Display (N): Access excluded business blocks in availability screen. |
| hub | `String` | CRO code. |
| inactive | `String` | Inactive |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockNoteDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentid | `Float` | Block ID |
| allotmentnoteid | `Float` | Allotmentnoteid |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| bookId | `Float` | Book ID |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `DateTime` | Created Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| externalId | `Float` | External ID |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertUser | `Float` | Insert User |
| internalYN | `String` | Internal YN |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| leadnoteflag | `String` | Leadnoteflag |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterNoteId | `Float` | Foreign Key on book$notes.note_id. |
| noteCode | `String` | Note Code |
| noteDetails | `String` | Note Details |
| noteId | `Float` | Note ID |
| noteTitle | `String` | Note Title |
| noteTypeCode | `String` | Note Type Code |
| notetypeid | `String` | Notetypeid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentnoteid | `Float` | Parentnoteid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `DateTime` | Updated Date |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockProductDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionId | `Float` | Action ID |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentProductId | `Float` | System Generated number that uniquely identifies a record in this table. |
| allotmentid | `Float` | Block ID |
| beginDate | `Date` | Begin Date |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| calculationRule | `String` | Calculation Rule |
| centralPackageAllowance | `Float` | Central Package Allowance |
| centralPackageCode | `String` | Central Package Code |
| centralPackageDecsription | `String` | Central Package Decsription |
| centralPrice | `Float` | Central Price |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| dmlSeqNumber | `Float` | Dml Sequence No |
| endDate | `Date` | End Date |
| formula | `String` | Formula |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalAllotmentproductid | `Float` | Allotmentproductid |
| internalProductid | `String` | Productid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationID | `String` | Internal ID to uniquely identify the Property |
| offsetType | `String` | Offset Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageAllowance | `Float` | Allowance for the product. |
| packageCode | `String` | Package Code |
| packageDescription | `String` | Package Description |
| postingRhythm | `String` | Posting Rhythm |
| postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| price | `Float` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| productGroup | `String` | Product Group |
| productId | `String` | Product ID |
| productSource | `String` | Product Source |
| property | `String` | Code to uniquely identify the Property |
| qtyExcluded | `Float` | Quantity Excluded |
| quantity | `Float` | Quantity |
| rateCode | `String` | Rate Code |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockItemDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentid | `Float` | Block ID |
| allotmentitemid | `Float` | Allotmentitemid |
| availableFrom | `Date` | Item available from this time. |
| availableFromTime | `String` | Available From Time |
| availableTo | `Date` | Item available until this time. |
| availableToTime | `String` | Available To Time |
| beginDate | `Date` | Begin Date |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| cPrice | `Float` | Central Price |
| cateringitemid | `Float` | Cateringitemid |
| centralItemDescription | `String` | Central Item Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| hourlyYn | `String` | Hourly Y/N |
| id | `Float` | ID |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| itemClass | `String` | Item Class |
| itemCode | `String` | Item Code |
| itemDescription | `String` | Item Description |
| itemId | `Float` | Item ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| price | `Float` | Price |
| priceCode | `String` | Price Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| quantity | `Float` | Quantity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateName | `String` | Rate Name |
| repItemClass | `String` | Reporting Item Class |
| revenueType | `String` | Revenue Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockTraceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionId | `Float` | Action ID |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentid | `Float` | Block ID |
| allotmenttraceid | `Float` | Allotmenttraceid |
| blockEndDate | `Date` | Block End Date |
| centralDepartmentDescription | `String` | Central Department Description |
| createdBy | `String` | The name of the user who created the record. |
| createdOn | `DateTime` | Created On |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| departmentCode | `String` | Department Code |
| departmentDescription | `String` | Department Description |
| dmlSeqNumber | `Float` | Dml Sequence No |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resolvedBy | `String` | Resolved By |
| resolvedOn | `DateTime` | Resolved On |
| traceDate | `Date` | Trace Date |
| traceId | `Float` | Trace ID |
| traceStatus | `String` | Trace Status |
| traceText | `String` | Trace Text |
| traceTime | `String` | Trace Time |
| tracebusinessdate | `DateTime` | Tracebusinessdate |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedOn | `DateTime` | Updated On |

[⬆ Back to Query](#query)

---

### BookingsBlockBlockAlternateDatesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentAltDateSeqno | `Float` | Primary Key ID. |
| allotmentHeaderId | `Float` | Allotment Header ID |
| alternateEndDate | `Date` | Alternate Departure Date. |
| alternateStartDate | `Date` | Alternate Arrival Date. |
| arrivalDate | `Date` | Arrival Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| departureDate | `Date` | Departure Date |
| doubleOccupancyRate | `Float` | 2 Person Rate. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| mainBookDatesYn | `String` | Indicates if this record corresponds with the main booking dates. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| preferredYn | `String` | Indicates the preferred alternate date. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priority | `Float` | Priority |
| property | `String` | Code to uniquely identify the Property |
| quadrupleOccupancyRate | `Float` | 3 Person Rate. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| roomType | `String` | Room Type |
| scRoomCategory | `String` | Sc Room Category |
| singleOccupancyRate | `Float` | 1 Person Rate. |
| tripleOccupancyRate | `Float` | 3 Person Rate. |

[⬆ Back to Query](#query)

---

### BookingsBlockSellMessagesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| beginDate | `Date` | Begin Date |
| blockCode | `String` | Block Code |
| centralRoomType | `String` | Central Room Type |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| endDate | `Date` | End Date |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| roomCategory | `String` | Room Category |
| roomType | `String` | Room Type |
| sellId | `Float` | The primary key for this table. |
| sellMessage | `String` | The actual message to be displayed. |
| sequence | `Float` | Sequence |
| stickyFlag | `String` | Stick the message on top of the screen without scrolling it. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsBlockPropertyPropertyDetailsType

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

### BookingsBlockAllotmentSubscriptionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookingId | `Float` | Block ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| exchangeYN | `String` | Allow exchange of the block |
| extBookingID | `String` | Ext Allotment ID |
| externalReference | `String` | This is External systems reference no or Block Code |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| interfaceID | `String` | This is the Interface_id of the System which sent/Received Allotment |
| jRNUpdateDate | `Date` | JRN Update Date and Time |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revisionToken | `String` | This field stores the revision token from Marsha interface for Marriott. |
| uDFC01 | `String` | UDFC01 |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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

### BookingsBlockQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| allotmentDetailsAgentContactNameId | `FloatInput` | Agent Contact Name ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsAgentNameId | `FloatInput` | Agent Name ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsAllotmentCode | `StringInput` | Block Code |  |
| allotmentDetailsAllotmentHeaderId | `FloatInput` | Block ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsOwnerCode | `StringInput` | Block Owner Code |  |
| allotmentDetailsBookingId | `StringInput` | External S&C vendor booking ID and used in HYATT-mode. | `conditionalInputPair(pair: 2)` |
| allotmentDetailsBookingStatusOrder | `FloatInput` | Booking Status Order | `conditionalInputPair(pair: 2)` |
| allotmentDetailsBlockType | `StringInput` | Determines block being [G] - Group or [W] - Wholesale. |  |
| allotmentDetailsCXchangeDate | `DateInput` | Central Xchange Date | `conditionalInputPair(pair: 2)` |
| allotmentDetailsChainCode | `StringInput` | Chain Code | `conditionalInputPair(pair: 1)` |
| allotmentDetailsCompanyNameId | `FloatInput` | Company Name ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsContactNameId | `FloatInput` | Contact Name ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsInsertDate | `DateTimeInput` | Created Date | `conditionalInputPair(pair: 2)` |
| allotmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentDetailsDueDateOrd | `DateInput` | Due Date Sorting Column. | `conditionalInputPair(pair: 2)` |
| allotmentDetailsEndDate | `DateInput` | End Date | `conditionalInputPair(pair: 2)` |
| allotmentDetailsInsertUser | `FloatInput` | Insert User | `conditionalInputPair(pair: 2)` |
| allotmentDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. | `conditionalInputPair(pair: 2)` |
| allotmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time | `conditionalInputPair(pair: 2)` |
| allotmentDetailsMarketCode | `StringInput` | Market  Code |  |
| allotmentDetailsSuperBlockId | `FloatInput` | Parent Block ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsSuperBlockResort | `StringInput` | Parent Resort |  |
| allotmentDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. | `conditionalInputPair(pair: 2)` |
| allotmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentDetailsOrmsBlockClass | `StringInput` | ORMS Block Class |  |
| allotmentDetailsOwner | `FloatInput` | Owner | `conditionalInputPair(pair: 2)` |
| allotmentDetailsResort | `StringInput` | Code to uniquely identify the Property | `conditionalInputPair(pair: 1)` |
| allotmentDetailsRateCode | `StringInput` | Rate Code |  |
| allotmentDetailsGuaranteeCode | `StringInput` | Reservation Type |  |
| allotmentDetailsBookingStatus | `StringInput` | Room Status |  |
| allotmentDetailsShoulderEndDate | `DateInput` | Shoulder End | `conditionalInputPair(pair: 2)` |
| allotmentDetailsShoulderBeginDate | `DateInput` | Shoulder Start | `conditionalInputPair(pair: 2)` |
| allotmentDetailsSourceNameId | `FloatInput` | Source Name ID | `conditionalInputPair(pair: 2)` |
| allotmentDetailsBeginDate | `DateInput` | Start Date | `conditionalInputPair(pair: 2)` |
| allotmentDetailsTourcode | `StringInput` | Tour Code. | `conditionalInputPair(pair: 2)` |
| allotmentDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |  |
| allotmentDetailsUpdateDate | `DateTimeInput` | Updated Date | `conditionalInputPair(pair: 2)` |
| allotmentDetailsXudescription | `StringInput` | Multi Byte Description in uppercase |  |
| blockaliasesDetailsAlias | `StringInput` | Alias |  |
| blockaliasesDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| blockaliasesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| blockaliasesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| blockaliasesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| blockaliasesDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| blockaliasesDetailsUalias | `StringInput` | Not in use. |  |
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| marketDetailsMarketCode | `StringInput` | Market Code |  |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |  |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |  |
| marketDetailsMarketid | `StringInput` | Marketid |  |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| marketDetailsResort | `StringInput` | Property |  |
| allotmentratesDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmentratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentratesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentratesDetailsOffsetType | `StringInput` | Offset Type |  |
| allotmentratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentratesDetailsResort | `StringInput` | Property |  |
| allotmentratesDetailsRateCode | `StringInput` | Rate Code |  |
| allotmentratesDetailsRecordType | `StringInput` | Record Type |  |
| allotmentownerDetailsBookId | `FloatInput` | Book ID |  |
| allotmentownerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentownerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentownerDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentownerDetailsUserId | `FloatInput` | Name ID |  |
| allotmentownerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentownerDetailsOwnerType | `StringInput` | Owner Type |  |
| allotmentownerDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentownerDetailsUserResort | `StringInput` | Property User belongs to |  |
| allotmentprofilecompanyDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofilecompanyDetailsLinkId | `FloatInput` | Company ID |  |
| allotmentprofilecompanyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofilecompanyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofilecompanyDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofilecompanyDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofilecompanyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofilecompanyDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofilecompanycontactDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofilecompanycontactDetailsLinkId | `FloatInput` | Company Contact ID |  |
| allotmentprofilecompanycontactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofilecompanycontactDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofilecompanycontactDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofilecompanycontactDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofilecompanycontactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofilecompanycontactDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofilesourceDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofilesourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofilesourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofilesourceDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofilesourceDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofilesourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofilesourceDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofilesourceDetailsLinkId | `FloatInput` | Source ID |  |
| allotmentprofilesourcecontactDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofilesourcecontactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofilesourcecontactDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofilesourcecontactDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofilesourcecontactDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofilesourcecontactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofilesourcecontactDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofilesourcecontactDetailsLinkId | `FloatInput` | Source Contact ID |  |
| allotmentprofiletaDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofiletaDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofiletaDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofiletaDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofiletaDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofiletaDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofiletaDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofiletaDetailsLinkId | `FloatInput` | Travel Agent ID |  |
| allotmentprofiletacontactDetailsBookingId | `FloatInput` | Booking ID |  |
| allotmentprofiletacontactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentprofiletacontactDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentprofiletacontactDetailsLinkType | `StringInput` | Link Type |  |
| allotmentprofiletacontactDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentprofiletacontactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentprofiletacontactDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentprofiletacontactDetailsLinkId | `FloatInput` | Travel Agent Contact ID |  |
| allotmentdetailDetailsAllotmentDetailId | `FloatInput` | Allotment_detail_id -- Sequence generated column. |  |
| allotmentdetailDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmentdetailDetailsAllotmentid | `FloatInput` | Block ID |  |
| allotmentdetailDetailsChangeDate | `DateInput` | Change Date |  |
| allotmentdetailDetailsCutoffDate | `DateInput` | Cutoff Date |  |
| allotmentdetailDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentdetailDetailsAllotmentdetailid | `FloatInput` | Allotmentdetailid |  |
| allotmentdetailDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentdetailDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentdetailDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentdetailDetailsRecordType | `StringInput` | Record Type |  |
| allotmentdetailDetailsResort | `StringInput` | Property |  |
| allotmentdetailDetailsRoomcategoryid | `StringInput` | Roomcategoryid |  |
| allotmentdetailDetailsAllotmentDate | `DateInput` | Stay Day |  |
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
| reservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |  |
| reservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |  |
| reservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |  |
| reservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |  |
| reservationDetailsAllotmentid | `FloatInput` | Block ID |  |
| reservationDetailsTruncBeginDate | `DateInput` | Arrival Date |  |
| reservationDetailsBillingContactId | `FloatInput` | Billing Contact ID |  |
| reservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |  |
| reservationDetailsAllotmentHeaderId | `FloatInput` | Block ID |  |
| reservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID |  |
| reservationDetailsBusinessDateCreated | `DateInput` | Business Date Created |  |
| reservationDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| reservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date |  |
| reservationDetailsCancellationNo | `StringInput` | Cancellation Number |  |
| reservationDetailsChainCode | `StringInput` | Chain Code |  |
| reservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |  |
| reservationDetailsCreditCardId | `FloatInput` | Credit Card ID |  |
| reservationDetailsCustomReference | `StringInput` | Custom Reference Number |  |
| reservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| reservationDetailsTruncEndDate | `DateInput` | Departure Date |  |
| reservationDetailsEnddatetime | `DateTimeInput` | End Datetime |  |
| reservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate |  |
| reservationDetailsEventId | `FloatInput` | Event ID |  |
| reservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |  |
| reservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |  |
| reservationDetailsGuestprofileid | `FloatInput` | Guestprofileid |  |
| reservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |  |
| reservationDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| reservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |  |
| reservationDetailsInsertUser | `FloatInput` | Insert User |  |
| reservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID |  |
| reservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| reservationDetailsEndDate | `DateTimeInput` | Linked Departure Date |  |
| reservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| reservationDetailsNameUsageType | `StringInput` | Name Usage Type |  |
| reservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| reservationDetailsOriginalEndDate | `DateInput` | Original End Date |  |
| reservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |  |
| reservationDetailsParentreservationid | `FloatInput` | Parentreservationid |  |
| reservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |  |
| reservationDetailsQuoteId | `StringInput` | Quote ID provided by external system. |  |
| reservationDetailsResvContactId | `FloatInput` | Resv Contact ID |  |
| reservationDetailsResvNameId | `FloatInput` | Reservation Name ID |  |
| reservationDetailsResvStatus | `StringInput` | Reservation Status |  |
| reservationDetailsGuaranteeCode | `StringInput` | Reservation Type |  |
| reservationDetailsReservationid | `FloatInput` | Reservationid |  |
| reservationDetailsResort | `StringInput` | Property |  |
| reservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |  |
| reservationDetailsResvNameid | `FloatInput` | Reservation Nameid |  |
| reservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |  |
| reservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |  |
| reservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |  |
| reservationDetailsRoomCategory | `StringInput` | Room Category |  |
| reservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |  |
| reservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |  |
| reservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |  |
| reservationDetailsSguestName | `StringInput` | Sguest Name |  |
| reservationDetailsNameId | `FloatInput` | Shared Profile ID |  |
| reservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |  |
| reservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |  |
| reservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |  |
| reservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |  |
| reservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |  |
| reservationDetailsUpdateDate | `DateTimeInput` | Update Date |  |
| reservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |  |
| resvdepositscheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| resvdepositscheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| resvdepositscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| resvdepositscheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| resvdepositscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| resvdepositscheduleDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| resvdepositscheduleDetailsResvDepositScheduleId | `FloatInput` | Resv Deposit Schedule ID |  |
| financialtransDetailsArLedCredit | `FloatInput` | AR Ledger Credit |  |
| financialtransDetailsArLedDebit | `FloatInput` | AR Ledger Debit |  |
| financialtransDetailsArState | `StringInput` | AR State |  |
| financialtransDetailsArNumber | `FloatInput` | Account Code |  |
| financialtransDetailsAccountid | `FloatInput` | Accountid |  |
| financialtransDetailsArticleId | `FloatInput` | Article ID |  |
| financialtransDetailsAuthemployeeid | `FloatInput` | Authemployeeid |  |
| financialtransDetailsBonusCheckId | `FloatInput` | Bonus Check ID |  |
| financialtransDetailsBusinessDate | `DateInput` | Business Date |  |
| financialtransDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| financialtransDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |  |
| financialtransDetailsCashierId | `FloatInput` | Cashier ID |  |
| financialtransDetailsChainCode | `StringInput` | Chain Code |  |
| financialtransDetailsChequeNumber | `StringInput` | Check Number |  |
| financialtransDetailsClosureNo | `FloatInput` | Closure Number |  |
| financialtransDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |  |
| financialtransDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |  |
| financialtransDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| financialtransDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |  |
| financialtransDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |  |
| financialtransDetailsFintransactionid | `FloatInput` | Fintransactionid |  |
| financialtransDetailsFintransid | `FloatInput` | Fintransid |  |
| financialtransDetailsBillNo | `FloatInput` | Folio Number |  |
| financialtransDetailsFolioView | `FloatInput` | Folio View |  |
| financialtransDetailsFolioid | `FloatInput` | Folioid |  |
| financialtransDetailsFromResvId | `FloatInput` | From Resv ID |  |
| financialtransDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |  |
| financialtransDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |  |
| financialtransDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |  |
| financialtransDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |  |
| financialtransDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| financialtransDetailsArticleid | `FloatInput` | Articleid |  |
| financialtransDetailsBusinessdate | `DateInput` | Businessdate |  |
| financialtransDetailsCashierid | `FloatInput` | Cashierid |  |
| financialtransDetailsFolioNo | `FloatInput` | Internal Window ID |  |
| financialtransDetailsInvoiceNo | `FloatInput` | Invoice Number |  |
| financialtransDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| financialtransDetailsLinkTrxNo | `FloatInput` | Link Transaction No |  |
| financialtransDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| financialtransDetailsNameId | `FloatInput` | Name ID |  |
| financialtransDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| financialtransDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |  |
| financialtransDetailsOriginalRoom | `StringInput` | Original Room |  |
| financialtransDetailsOriginalresvid | `FloatInput` | Originalresvid |  |
| financialtransDetailsProduct | `StringInput` | Package |  |
| financialtransDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |  |
| financialtransDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |  |
| financialtransDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |  |
| financialtransDetailsParentfintransid | `FloatInput` | Parentfintransid |  |
| financialtransDetailsPostitNo | `FloatInput` | Postit Number |  |
| financialtransDetailsProductid | `StringInput` | Productid |  |
| financialtransDetailsProfileid | `FloatInput` | Profileid |  |
| financialtransDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| financialtransDetailsRateCode | `StringInput` | Rate Code |  |
| financialtransDetailsRatecodeid | `StringInput` | Ratecodeid |  |
| financialtransDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |  |
| financialtransDetailsReservationid | `FloatInput` | Reservationid |  |
| financialtransDetailsRoom | `StringInput` | Room Number |  |
| financialtransDetailsRoomid | `StringInput` | Roomid |  |
| financialtransDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |  |
| financialtransDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |  |
| financialtransDetailsTaxElements | `StringInput` | Tax Elements |  |
| financialtransDetailsTcGroup | `StringInput` | Transaction Code Group |  |
| financialtransDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |  |
| financialtransDetailsTranActionId | `FloatInput` | Tran Action ID |  |
| financialtransDetailsTranscodeid | `StringInput` | Transaction Code |  |
| financialtransDetailsTrxDate | `DateInput` | Transaction Date |  |
| financialtransDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |  |
| financialtransDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |  |
| financialtransDetailsTrxCode | `StringInput` | Transaction Code |  |
| financialtransDetailsTrxNo | `FloatInput` | Trx Number |  |
| financialtransDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |  |
| financialtransDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |  |
| financialtransDetailsTrxNoHeader | `FloatInput` | Transaction No Header |  |
| financialtransDetailsAuthorizerId | `FloatInput` | User ID |  |
| reservationcancelpolicyDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| reservationcancelpolicyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| reservationcancelpolicyDetailsExternalId | `StringInput` | External ID |  |
| reservationcancelpolicyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| reservationcancelpolicyDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| reservationcancelpolicyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| reservationcancelpolicyDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| reservationcancelpolicyDetailsResvCancelPolicyId | `FloatInput` | Internal |  |
| reservationcancelpolicyDetailsResvNameId | `FloatInput` | Resv Name ID |  |
| blockaccessexclusionsDetailsAccessSourceType | `StringInput` | Always CRO. |  |
| blockaccessexclusionsDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| blockaccessexclusionsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| blockaccessexclusionsDetailsAccessSourceValue | `StringInput` | CRO code. |  |
| blockaccessexclusionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| blockaccessexclusionsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| blockaccessexclusionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| blockaccessexclusionsDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentnoteDetailsAllotmentid | `FloatInput` | Block ID |  |
| allotmentnoteDetailsAllotmentnoteid | `FloatInput` | Allotmentnoteid |  |
| allotmentnoteDetailsBookId | `FloatInput` | Book ID |  |
| allotmentnoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentnoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentnoteDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentnoteDetailsNoteId | `FloatInput` | Note ID |  |
| allotmentnoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentnoteDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentproductDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmentproductDetailsAllotmentProductId | `FloatInput` | System Generated number that uniquely identifies a record in this table. |  |
| allotmentproductDetailsAllotmentid | `FloatInput` | Block ID |  |
| allotmentproductDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentproductDetailsAllotmentproductid | `FloatInput` | Allotmentproductid |  |
| allotmentproductDetailsProductid | `StringInput` | Productid |  |
| allotmentproductDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentproductDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentproductDetailsOffsetType | `StringInput` | Offset Type |  |
| allotmentproductDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentproductDetailsProductId | `StringInput` | Product ID |  |
| allotmentproductDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmentitemDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmentitemDetailsAllotmentid | `FloatInput` | Block ID |  |
| allotmentitemDetailsAllotmentitemid | `FloatInput` | Allotmentitemid |  |
| allotmentitemDetailsCateringitemid | `FloatInput` | Cateringitemid |  |
| allotmentitemDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentitemDetailsId | `FloatInput` | ID |  |
| allotmentitemDetailsItemId | `FloatInput` | Item ID |  |
| allotmentitemDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentitemDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentitemDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentitemDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmenttraceDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmenttraceDetailsAllotmentid | `FloatInput` | Block ID |  |
| allotmenttraceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmenttraceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmenttraceDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmenttraceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmenttraceDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| allotmenttraceDetailsTraceId | `FloatInput` | Trace ID |  |
| allotmentalternatedatesDetailsAllotmentAltDateSeqno | `FloatInput` | Primary Key ID. |  |
| allotmentalternatedatesDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| allotmentalternatedatesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentalternatedatesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| allotmentalternatedatesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentalternatedatesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentalternatedatesDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| sellmessagesDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| sellmessagesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| sellmessagesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| sellmessagesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| sellmessagesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| sellmessagesDetailsResort | `StringInput` | Property |  |
| sellmessagesDetailsRateCode | `StringInput` | Rate Code |  |
| sellmessagesDetailsRoomCategory | `StringInput` | Room Category |  |
| sellmessagesDetailsSellId | `FloatInput` | The primary key for this table. |  |
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
| allotmentsubscriptionDetailsBookingId | `FloatInput` | Block ID |  |
| allotmentsubscriptionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| allotmentsubscriptionDetailsExtAllotmentId | `StringInput` | Ext Allotment ID |  |
| allotmentsubscriptionDetailsInterfaceId | `StringInput` | This is the Interface_id of the System which sent/Received Allotment |  |
| allotmentsubscriptionDetailsJrnUpdateDttm | `DateTimeInput` | JRN Update Date |  |
| allotmentsubscriptionDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| allotmentsubscriptionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| allotmentsubscriptionDetailsResort | `StringInput` | Code to uniquely identify the Property |  |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query bookingsBlock($input: BookingsBlockQueryArgumentsType!) {
  bookingsBlock(input: $input) @stream {
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
    blockAliasesDetails {
      alias
      allotmentHeaderId
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ualias
      updateDate
      updateUser
    }
    marketDetails {
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      dSI
      deletedFlag
      displayColor
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketgroupid
      marketid
      organizationID
      primaryKeyID
      printGroup
      property
      repItem
      repItemName
      repItemOrderby
      repMarketSellSequence
      repParentSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      scOrderby
      trxCode
      updateDate
      updateUser
    }
    blockRatesDetails {
      allotmentHeaderId
      beginDate
      dSI
      deletedFlag
      description
      endDate
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      negotiatedYN
      offsetType
      organizationID
      primaryKeyID
      primaryYN
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeLocked
      rateType
      recordType
    }
    blockOwnerDetails {
      bookId
      cateringOwnerTitle
      dSI
      deletedFlag
      description
      fullName
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      nameID
      organizationID
      ownerEmail
      ownerPhone
      ownerType
      primaryKeyID
      primarySfaYn
      primaryYN
      property
      rNAInsertDate
      rNAUpdateDate
      relationship
      roomsOwnerCode
      toType
      updateDate
      updateUser
      userResort
    }
    blockCompanyProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      companyID
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      state
      toType
      updateDate
      updateUser
    }
    blockCompanyContactProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      companyContactID
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      state
      toType
      updateDate
      updateUser
    }
    blockSourceProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      sourceID
      state
      toType
      updateDate
      updateUser
    }
    blockSourceContactProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      sourceContactID
      state
      toType
      updateDate
      updateUser
    }
    blockTravelAgentProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      state
      toType
      travelAgentID
      updateDate
      updateUser
    }
    blockTravelAgentContactProfileDetails {
      address1
      address2
      address3
      address4
      bookingID
      city
      countryCode
      countryDescription
      dSI
      deletedFlag
      description
      displayName
      eMail
      externalYN
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkType
      locationID
      nameType
      organizationID
      phoneNo
      postalCode
      primaryKeyID
      primaryYN
      printAccountYN
      property
      province
      rNAInsertDate
      rNAUpdateDate
      relationship
      state
      toType
      travelAgentContactID
      updateDate
      updateUser
    }
    blockDetailDetails {
      actionId
      aggregateContractOccupancy
      aggregatePickupOccupancy
      aggregateProspectiveOccupancy
      allotmentDetailId
      allotmentHeaderId
      allotmentbusinessdate
      allotmentid
      available
      blockEndDate
      blockedOcc1
      blockedOcc2
      blockedOcc3
      blockedOcc4
      blockedOccupancy4
      blockedRooms
      bookingPosition
      cDiscountAmount
      cExchangeDate
      cExchangeRate
      cMaterializationAmnt
      cPickupRate2
      cPickupRate1
      cPickupRate3
      cPickupRate4
      cPickupRateap
      centralContractRevenue
      centralOrderBy
      centralPickupRevenue
      centralProspectiveRevenue
      centralRateAmountFor1PAX
      centralRateAmountFor2PAX
      centralRateAmountFor3PAX
      centralRateAmountFor4PAX
      centralRateAmountPerAdditionalPerson
      centralRateAmountPerChild
      centralRoomPoolDescription
      changeDate
      contractOccupancy3
      contractOccupancyBy1PAX
      contractOccupancyBy2PAX
      contractOccupancyBy4PAX
      contractRevenue
      createdBy
      createdDate
      currentRooms
      cutoffDate
      dSI
      discountAmt
      discountPct
      discountReasonCode
      dmlSeqNumber
      elastic
      elasticSold
      fixedRateYn
      insertUser
      internalAllotmentdetailid
      inventoryControlMode
      inventoryDate
      inventoryDeduct
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      materializationAmnt
      oTBOcc1
      oTBOcc2
      oTBOcc3
      oTBOcc4
      oTBRooms
      organizationID
      originalRooms
      physicalConversionFactor
      pickupOccupancyBy1PAX
      pickupOccupancyBy2PAX
      pickupOccupancyBy3PAX
      pickupOccupancyBy4PAX
      pickupRate1
      pickupRate2
      pickupRate3
      pickupRate4
      pickupRateap
      pickupRevenue
      poolOrderBy
      poolResort
      poolRoomCategory
      primaryKeyID
      prospectiveOccupancyBy1PAX
      prospectiveOccupancyBy2PAX
      prospectiveOccupancyBy3PAX
      prospectiveRevenue
      rNAInsertDate
      rNAUpdateDate
      rate2
      rate4
      rateAmountFor1PAX
      rateAmountFor3PAX
      rateAmountPerAdditionalPerson
      rateAmountPerChild
      recordType
      released
      resort
      roomCatOrderBy
      roomCatResort
      roomCategory
      roomClass
      roomPool
      roomPoolCode
      roomPoolDescription
      roomRoomClass
      roomType
      roomTypeDescription
      roomcategoryid
      roomclassid
      scRoomCategory
      scroomcategoryid
      shoulderDateYN
      stayDay
      subBlockPickup
      updateUser
      updatedBy
      updatedDate
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
    reservationDetails {
      aSBProratedYn
      accompaniedYN
      accompanyingName
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      allotmentRecordType
      allotmentid
      amenityEligibleYn
      amenityLevelCode
      amountPercent
      approvalAmount
      approvalAmountCalcMethod
      approvalCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalTime
      arrivaltransportid
      attachedDate
      authorizedBillingYN
      authorizedBy
      authorizerId
      autoCheckinYn
      autoPopulateRoutingYn
      autoSettleDays
      autoSettleType
      autoSettleYN
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipID
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      backToBackYN
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
      beginDatetime
      beginDistrict
      beginState
      beginSystemDateTime
      billNumber
      billingContact
      billingContactDisplayName
      billingContactId
      billingContactName
      billingcontactprofileid
      blockCode
      blockCreateDate
      blockID
      blockName
      blockResort
      blockStatus
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      businessDatetimeCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cDiscountAmount
      cDiscountAmt
      cEffectiveRateAmount
      cExchangeDate
      cExchangeRate
      cFixedCharge
      cGrossRateAmount
      cLocalBaseRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmountOriginal
      cUpsellCharge
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationDatetime
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      cancelledBy
      cardNumberByMembershipClass
      cardNumberByMembershipType
      centralApprovalAmount
      centralCancelReason
      centralCommissionCode
      centralCommissionDescription
      centralCreditLimit
      centralDiscountReason
      centralDiscountReasonDescription
      centralFBRevenue
      centralGuestType
      centralHurdle
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPaymentAmount
      centralProjectedFBRevenue
      centralProjectedRoomRevenue
      centralProjectedTotalRevenue
      centralPromotionDescription
      centralRateableValue
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralRoomTypeCode
      centralRoomTypeDescription
      centralRoomTypeToChargeCode
      centralRoomTypeToChargeDescription
      centralSharedRoomRate
      centralSpecialRequestDescription
      centralTaxType
      centralTaxTypeDescription
      centralTotalCostOfStay
      centralTotalRevenue
      centralTotalRoomRate
      centralWaitlistPriority
      centralWaitlistPriorityDescription
      centralWaitlistReason
      centralWaitlistReasonDescription
      chainCode
      channelDescription
      channelOrderBy
      channelid
      checkInInitiatedBy
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAges
      commissionCode
      commissionDescription
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compHouse
      compTypeCode
      companyCity
      companyCountry
      companyID
      companyName
      companyProfileCorporateID
      companyProfileID
      complimentaryYN
      compreasonid
      computedResvStatus
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactName
      contactProfileID
      contactProfileName
      createdBy
      createdByDefaultResort
      createdDate
      createdTime
      creditCardAuthDate
      creditCardId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      deletedFlag
      departtransportid
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      depositMaturityType
      detatchedDate
      detatchedYN
      directBillVerifyResponse
      directbillauthby
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountReasonDescription
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      dropOffType
      dropOffTypeDescription
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endCity
      endDatetime
      endDistrict
      endState
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      excludeFromAutoAuthorizationYN
      expectedTimeOfReturnETR
      exportCheckinresId
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externalReferencesList
      extraBeds
      fBRevenue
      fBRevenueRemaining
      faxId
      faxYn
      feature
      financiallyResponsibleYn
      fixedCharge
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioNumber
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      frequentFlyerMembershipYN
      grossRateFuture
      grossRatePast
      groupName
      groupProfileARNumber
      groupProfileARNumberCentral
      groupProfileClientID
      groupProfileID
      groupProfileName
      guaranteeCodePreCi
      guaranteecodeid
      guestFirstName
      guestFirstNameSdx
      guestLastNameSdx
      guestSignature
      guestStatus
      guestType
      guestprofileid
      gueststatusid
      guesttypeid
      housekeepingServiceTime
      hurdle
      hurdleOverride
      iDByMembershipClass
      iDByMembershipType
      individualCity
      individualCountry
      individualFirstName
      individualLastName
      insertActionInstanceId
      insertDate
      insertDateTime
      insertUser
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      itemsQuantities
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyValidUntil
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoomNumber
      lastSettleDate
      leadTimeDays
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      linkedRoomType
      listOfMembershipID
      localBaseRateAmount
      locationID
      loyaltySchemeMembershipYN
      mailYn
      manualCheckoutStatus
      marketCode
      marketid
      mcGenBeginDistrict
      mcGenBeginState
      mcGenEndDistrict
      mcGenEndState
      mcGenNextCountry
      mcGenPreviousCountry
      memberDescription
      memberLevel
      memberNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipId
      membershipLevelByMembershipClass
      membershipTypeByMembershipClass
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextCountry
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCode
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      ownerFfFlag
      ownerOrFriendsFamily
      packageCode
      packageCodeDescription
      packageForecastGroup
      packageForecastGroupDescription
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      paxNo
      paymentAmount
      paymentMethod
      paymentmethodid
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pickUpCarrierCode
      pickUpDate
      pickUpStation
      pickUpTransportNumber
      pickUpType
      pickUpTypeDescription
      pickUpTime
      pickupRequiredYN
      points
      pointsEligibilityCode
      postCoFlag
      postStayChargingYN
      postingAllowedYN
      preArrReviewedDt
      preArrReviewedUser
      preChargingYn
      preRegisteredYn
      preference
      preferenceType
      preferredRoomType
      previousCountry
      primaryKeyID
      primaryShare
      printRateYN
      projectedFBRevenue
      projectedRoomRevenue
      projectedTotalRevenue
      promotionCode
      promotionDescription
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      queuePriority
      queueWaitTime
      quoteId
      rateAmount
      rateCode
      rateCodeDescriptions
      rateTier
      rateableValue
      ratecodeid
      rdHousekeepingExpectedServiceTime
      rdResvStatus
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      repChannel
      repChannelDescription
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationDate
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reservationid
      resort
      resortChargeNumber
      restrictionOverride
      resvGuid
      resvNameid
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rhRoomFeatures
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomResort
      roomRevenue
      roomRevenueRemaining
      roomServiceTime
      roomTypeDescription
      roomTypeToChargeCode
      roomTypeToChargeDescription
      roomcategoryid
      roomid
      routingYN
      scheduleCheckoutYn
      sguestFirstname
      sguestName
      shareConfirmationNumbers
      shareId
      shareName
      sharePrcnt
      shareSeqNumber
      shareOfRateAmount
      sharedGuestName
      sharedProfileID
      sharedReservationStatus
      sharingYN
      sourceCity
      sourceCode
      sourceCountry
      sourceName
      sourceProfileARNumber
      sourceProfileARNumberCentral
      sourceProfileIATANumber
      sourceProfileID
      sourceProfileName
      sourceid
      specialRequest
      specialRequestDescription
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      suiteNumber
      superSearchIndexText
      taRecordLocator
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxTypeDescription
      taxtypeid
      tiad
      ticketNos
      totalCostOfStay
      totalRevenue
      totalRevenueRemaining
      totalRoomRate
      trackItGroups
      trackItTypes
      transactionid
      travelAgentCity
      travelAgentCountry
      travelAgentID
      travelAgentName
      travelAgentProfileARNumber
      travelAgentProfileARNumberCentral
      travelAgentProfileIATANumber
      travelAgentProfileID
      travelAgentProfileName
      truncActualCheckOutDate
      turndownStatus
      turndownYN
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
      uniCardId
      updateDate
      updateDatetime
      updateUser
      updatedBy
      updatedByDefaultResort
      updatedDate
      updatedTime
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      waitlistPriority
      waitlistPriorityDescription
      waitlistReason
      waitlistReasonDescription
      waitlistpriorityid
      waitlistreasonid
      walkInYN
      yieldableYn
      ymCode
    }
    reservationDepositScheduleDetails {
      activityDeposit
      cActivityDeposit
      cCancelPnltyAmount
      cExchangeDate
      cExchangeRate
      cForeignDepositAmount
      cancelDeadline
      cancelPnltyAmount
      centralDepositAmountOutstanding
      centralDepositAmountRequested
      centralTotalDepositPayments
      comments
      dSI
      deletedFlag
      depositAmountOutstanding
      depositAmountRequested
      depositDueDate
      depositPercentage
      depositReqLinkId
      depositReqReceiptNo
      depositReqReversalYn
      depositRule
      depositRuleDescription
      depositRuleType
      depositScheduleReservationNameId
      depositType
      dmlSeqNumber
      exchangeRateInfo
      externalId
      foreignDepositAmount
      insertActionInstanceId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualYn
      organizationID
      paymentFlag
      primaryKeyID
      processedYn
      productId
      property
      rNAInsertDate
      rNAUpdateDate
      rateDcSeq
      reservationDepositScheduleId
      roomDeposit
      totalDepositPayments
      trxDate
      updateDate
      updateUser
    }
    financialTransactionDetails {
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
      centralDepositAmountPaid
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
      postedAmountInTransactionCurrency
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
    reservationCancelPolicyDetails {
      percentCancellation
      percentDue
      cExchangeDate
      cExchangeRate
      cForeignCancelAmount
      cancellationDate
      cancellationPenalty
      cancellationPenaltyAmount
      cancellationPenaltyType
      cancellationRuleDescription
      centralCancellationPenaltyAmount
      dSI
      deletedFlag
      description
      dmlSeqNumber
      exchangeRateInfo
      externalId
      foreignCancelAmount
      insertActionInstanceId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualYn
      organizationID
      primaryKeyID
      processedYn
      property
      rNAInsertDate
      rNAUpdateDate
      rateDcSeq
      reservationCancelPolicyId
      reservationNameId
      roomNights
      updateDate
      updateUser
    }
    blockAccessExclusionsDetails {
      accessExclusionMessage
      accessSourceType
      allotmentHeaderId
      allowCancelReservation
      allowCreateReservation
      allowModifyReservation
      dSI
      deletedFlag
      hideFromAvailabilityScreen
      hub
      inactive
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    blockNoteDetails {
      allotmentid
      allotmentnoteid
      blockBeginDate
      blockEndDate
      bookId
      createdBy
      createdDate
      dSI
      deletedflag
      externalId
      inactiveDate
      inactiveflag
      insertUser
      internalYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      leadnoteflag
      locationID
      masterNoteId
      noteCode
      noteDetails
      noteId
      noteTitle
      noteTypeCode
      notetypeid
      organizationID
      parentnoteid
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      updateUser
      updatedBy
      updatedDate
    }
    blockProductDetails {
      actionId
      allotmentHeaderId
      allotmentProductId
      allotmentid
      beginDate
      blockBeginDate
      blockEndDate
      calculationRule
      centralPackageAllowance
      centralPackageCode
      centralPackageDecsription
      centralPrice
      currency
      dSI
      deletedflag
      dmlSeqNumber
      endDate
      formula
      inactiveflag
      insertDate
      insertUser
      internalAllotmentproductid
      internalProductid
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      offsetType
      organizationID
      packageAllowance
      packageCode
      packageDescription
      postingRhythm
      postingType
      price
      primaryKeyID
      productGroup
      productId
      productSource
      property
      qtyExcluded
      quantity
      rateCode
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    blockItemDetails {
      allotmentHeaderId
      allotmentid
      allotmentitemid
      availableFrom
      availableFromTime
      availableTo
      availableToTime
      beginDate
      blockBeginDate
      blockEndDate
      cPrice
      cateringitemid
      centralItemDescription
      dSI
      deletedflag
      endDate
      hourlyYn
      id
      inactiveflag
      insertDate
      insertUser
      itemClass
      itemCode
      itemDescription
      itemId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      price
      priceCode
      primaryKeyID
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateName
      repItemClass
      revenueType
      updateDate
      updateUser
    }
    blockTraceDetails {
      actionId
      allotmentHeaderId
      allotmentid
      allotmenttraceid
      blockEndDate
      centralDepartmentDescription
      createdBy
      createdOn
      dSI
      departmentCode
      departmentDescription
      dmlSeqNumber
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resolvedBy
      resolvedOn
      traceDate
      traceId
      traceStatus
      traceText
      traceTime
      tracebusinessdate
      updateUser
      updatedBy
      updatedOn
    }
    blockAlternateDatesDetails {
      allotmentAltDateSeqno
      allotmentHeaderId
      alternateEndDate
      alternateStartDate
      arrivalDate
      dSI
      departureDate
      doubleOccupancyRate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      mainBookDatesYn
      organizationID
      preferredYn
      primaryKeyID
      priority
      property
      quadrupleOccupancyRate
      rNAInsertDate
      rNAUpdateDate
      roomType
      scRoomCategory
      singleOccupancyRate
      tripleOccupancyRate
    }
    sellMessagesDetails {
      allotmentHeaderId
      beginDate
      blockCode
      centralRoomType
      chainCode
      dSI
      endDate
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      roomCategory
      roomType
      sellId
      sellMessage
      sequence
      stickyFlag
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
    allotmentSubscriptionDetails {
      bookingId
      dSI
      deletedFlag
      exchangeYN
      extBookingID
      externalReference
      insertDate
      insertUser
      interfaceID
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revisionToken
      uDFC01
      updateDate
      updateUser
    }
  }
}
```