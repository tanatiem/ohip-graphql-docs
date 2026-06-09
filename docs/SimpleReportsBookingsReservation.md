# SimpleReportsBookingsReservation
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `simpleReportsBookingsReservation`
> The Simple Reports Bookings Reservation Subject Area simplifies creating and building adhoc reports including the ability to create new reports.
  
**Return:** [`[SimpleReportsBookingsReservationType]`](#simplereportsbookingsreservationtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`SimpleReportsBookingsReservationQueryArgumentsType!`](#simplereportsbookingsreservationqueryargumentstype) |  |

## Object Types

### SimpleReportsBookingsReservationType

| Field | Type | Description |
| --- | --- | --- |
| reservationGeneralDetails | [`SimpleReportsBookingsReservationReservationGeneralDetailsType`](#simplereportsbookingsreservationreservationgeneraldetailstype) | Reservation General Details |
| propertyPropertyDetails | [`SimpleReportsBookingsReservationPropertyPropertyDetailsType`](#simplereportsbookingsreservationpropertypropertydetailstype) | Resort Details |
| simpleReportsBookingsReservationRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingsReservationReservationGeneralDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| accompanyingNames | `String` | Accompanying guest names. |
| accompanyingYn | `String` | Identifies if this reservation has accompanying guests Y/N |
| actualCheckInDate | `DateTime` | Actual Check In Date |
| actualCheckOutDate | `DateTime` | Actual Check Out Date |
| addressId | `Float` | Address ID |
| addresseeName | `String` | Addressee Name |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| arrival | `DateTime` | Arrival |
| arrivalCarrierCode | `String` | Arrival Carrier Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `Date` | Trunc Arrival |
| arrivalDateTime | `DateTime` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| arrivalStationCode | `String` | Arrival Station Code |
| arrivalSystemDateTime | `DateTime` | Arrival System Date Time |
| arrivalTime | `String` | Arrival Time |
| arrivalTranportationYn | `String` | Arrival Tranportation Y/N |
| arrivalTransportCode | `String` | Arrival Transport Code |
| arrivalTransportType | `String` | Arrival Transport Type |
| authorisedBillingYn | `String` | Not used. |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoSettleDays | `Float` | Auto Settle Days |
| autoSettleYn | `String` | Auto Settle Y/N |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardMembershipId | `Float` | Award Membership ID |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| balance | `Float` | Balance on the account. |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| basedOnRule | `String` | Based On Rule |
| billingContactId | `Float` | Billing Contact ID |
| billingContactName | `String` | Billing Contact Name |
| blockCode | `String` | Block Code |
| blockId | `Float` | Block ID. |
| blockResort | `String` | Property this block belongs to. |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedRoomCategoryLabel | `String` | This column holds the label (description) of room category originally booked not necessarily the one in which the guest stayed. |
| businessDateCreated | `Date` | Business Date Created |
| businessTitle | `String` | Business Title |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cCreditLimit | `Float` | Central Credit Limit |
| cDiscountAmount | `Float` | Central Discount Amt |
| cHurdle | `Float` | Central Hurdle |
| cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| cRateableValue | `Float` | Central Rateable Value |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationNo | `String` | Cancellation Number |
| cancellationReasonCode | `String` | Cancellation Reason Code |
| cancellationReasonDesc | `String` | Cancellation Reason Description |
| channel | `String` | Channel |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| children | `Float` | Children |
| childrenTaxFree | `Float` | Children Tax Free |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| comments | `String` | Comments |
| commissionCode | `String` | Commission Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYn | `String` | Commissionable Y/N |
| compTypeCode | `String` | Comp Type Code |
| companyId | `Float` | Company ID |
| companyName | `String` | Company Name |
| complimentaryYn | `String` | Complimentary Y/N |
| computedResvStatus | `String` | Calculated reservation status. |
| confirmationLegNo | `Float` | Confirmation Leg Number. |
| confirmationLetter | `String` | Confirmation letter name is stored. |
| confirmationLetterId | `Float` | Confirmation Letter ID |
| confirmationNo | `String` | Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactNameId | `Float` | Contact Name ID |
| creditLimit | `Float` | Credit Limit |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReference | `String` | Custom Reference |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| dateOpenedForPickup | `Date` | Business Date when the business block was opened for pickup. |
| deletedFlag | `String` | Deleted Flag |
| departure | `DateTime` | Departure |
| departureCarrierCode | `String` | Departure Carrier Code |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Trunc Departure |
| departureDateTime | `Date` | Departure Date Time |
| departureEstimateTime | `Date` | Departure Estimate Time |
| departureStationCode | `String` | Departure Station Code |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportType | `String` | Departure Transport Type |
| departureTransportationYn | `String` | Departure Transportation Y/N |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| discountAmt | `Float` | Discount Amount |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReasonCode | `String` | Discount Reason Code |
| displayColor | `String` | Display Color |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYn | `String` | Do not move room flag. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| etrComments | `String` | Comments related to Estimated Time of Return. |
| eventId | `Float` | Event ID |
| exchangeDate | `Date` | Exchange Date |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| expectedTimeOfReturn | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalLegNo | `Float` | Reservation leg number for itinerary reservations. |
| externalReference | `String` | External Reference |
| externalReferenceType | `String` | Type of external reference depending from what external system the number was passed. |
| extnNumber | `Float` | Extn Number |
| extnType | `String` | Extn Type |
| extraBeds | `Float` | Extra Beds |
| fbRevenue | `Float` | FB Revenue |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| firstNightUpsell | `Float` | Incremental Upsell Charge for the first night. |
| fixedCharge | `Float` | Not used. |
| fixedRateYn | `String` | Fixed Rate Y/N |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioText1 | `String` | Folio Text1 |
| folioYn | `String` | Folio Y/N |
| gDSRecordLocator | `String` | GDS Record Locator |
| groupId | `Float` | Group ID |
| groupName | `String` | Group Name |
| guaranteeCode | `String` | Guarantee Code |
| guaranteeCodeDesc | `String` | The Description of the Guarantee code. |
| guestCountry | `String` | Country of the guest |
| guestCountryDesc | `String` | Guest Country Description |
| guestEmail | `String` | Guest Email |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLanguage | `String` | The code of the Guest Language  for reporting purposes. |
| guestLanguageDesc | `String` | The Description of the Language Code. Used only during the Conversion process. |
| guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| guestMiddleName | `String` | Middle name of the Guest who stayed in this hotel for this reservation. |
| guestName | `String` | Guest Name |
| guestNameId | `Float` | Guest Name ID |
| guestPhone | `String` | Not used. |
| guestPrivYn | `String` | Guest Priv Y/N |
| guestSignature | `String` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestTitle | `String` | Guest Title |
| guestTitleDesc | `String` | Guest Title Description |
| guestType | `String` | Guest Type |
| guestVIPDesc | `String` | Guest Vip Description |
| hasAnyShareFixedRateYn | `String` | Not used. |
| houseUseYn | `String` | House Use Y/N |
| housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | This will be taken from the field OVERRIDE in the HURDLE_RATES table.  This entry does not indicate that the rateable value of the reservation was less than the hurdle rate at the time of booking.  In fact if any date of the reservation touches an overri |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | Insert User |
| intermediaryYn | `String` | Intermediary Y/N |
| internalPrimaryKeyIDToUniquelyIdentifyTheRow | `Float` | Primary Key ID |
| invItemCodes | `String` | Invoice Item Codes |
| invItemIds | `String` | Invoice Item Ids |
| isUpsoldYn | `String` | Indicates if the reservation has already been upsold. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyOptions | `String` | Privileges available for this key |
| keyValidUntil | `Date` | Key Valid Until |
| lastDirectBillBatchDate | `Date` | Last Direct Bill Batch Date |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastRoom | `String` | Not used. |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| locatorYn | `String` | Not used. |
| maintainRoomFeatures | `String` | Maintain Room Features |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketDesc | `String` | Description of the Market Code. |
| masterShare | `String` | Indicates if this a master or slave reservation for perfect share |
| mealplanYn | `String` | Not used. |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipNumber | `String` | Membership Number |
| membershipRank | `Float` | Membership Rank |
| membershipType | `String` | Membership Type |
| messageYn | `String` | Identifies if there were any messages for the Guest on this reservation. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| multipleAdultsYn | `String` | Not used. |
| multipleBillingContactIdYN | `String` | Multiple Billing Contact ID Yn |
| multipleBlocksYn | `String` | Multiple Blocks Y/N |
| multipleBookedRoomCateringYN | `String` | Not used. |
| multipleChildrenYn | `String` | Not used. |
| multipleCommentsYn | `String` | Not used. |
| multipleCommissionCodeYN | `String` | Multiple Comm Code Y/N |
| multipleCompanyIdYN | `String` | Multiple Company ID Yn |
| multipleCribsYn | `String` | Multiple Cribs Y/N |
| multipleCurrencyCodeYn | `String` | Multiple Currency Code Y/N |
| multipleDiscountAmountYN | `String` | Multiple Discount Amt Y/N |
| multipleDiscountPrcntYn | `String` | Multiple Discount Prcnt Y/N |
| multipleExtensionsYn | `String` | Multiple Extensions Y/N |
| multipleFixedRate | `String` | Multiple Fixed Rate |
| multipleGroupIdYN | `String` | Multiple Group ID Yn |
| multipleMarketCodeYn | `String` | Not used. |
| multipleMembershipsYn | `String` | Multiple Memberships Y/N |
| multipleOriginOfBookingYN | `String` | Not used. |
| multiplePtsEligibilityYn | `String` | Multiple Pts Eligibility Y/N |
| multipleRateCodeYn | `String` | Not used. |
| multipleReservationContactIdYN | `String` | Multiple Resv Contact ID Yn |
| multipleRoomCategoryYn | `String` | Not used. |
| multipleRoomYn | `String` | Not used. |
| multipleSegmentsYn | `String` | Multiple Segments Y/N |
| multipleShareAmountYn | `String` | Not used. |
| multipleSourceIdYN | `String` | Multiple Source ID Yn |
| multipleTravelAgentIdYN | `String` | Multiple Travel Agent ID Yn |
| multipleXbedsYn | `String` | Multiple Xbeds Y/N |
| multipleYn | `String` | Not used. |
| nameTaxDescription | `String` | Name Tax Description |
| nameTaxType | `String` | Name Tax Type |
| nameType | `String` | Name Type |
| nameUsageType | `String` | Name Usage Type |
| nationality | `String` | Nationality |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| nights | `Float` | Nights |
| numberOfRooms | `Float` | No of Rooms |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| orgRoomCategory | `String` | Room Category prior to upsale. |
| orgRoomCategoryLabel | `String` | Room Category Label prior to upsale. |
| orgStayCost | `Float` | Total Cost of Stay prior to upsale. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originOfBooking | `String` | Origin of Booking |
| originOfBookingDesc | `String` | Description of the Origin of Booking code. |
| originalArrival | `Date` | Original Arrival |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| overrideTurndownFlagYn | `String` | Override Turndown Flag Y/N |
| ownerFfFlag | `String` | Owner Ff Flag |
| paramMobility | `String` | Param Mobility |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| partyCode | `String` | Party Code |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentMethod | `String` | Payment Method |
| paymentMethodDesc | `String` | Payment Method Description |
| periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pmsBusinessDate | `Date` | Pms Business Date |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| pointsEligibilityDesc | `String` | Points Eligibility Description |
| postChargingYn | `String` | Indicates if the reservation has charging privileges after checkout. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postingAllowedYn | `String` | Posting Allowed Y/N |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| preferredRoomType | `String` | Not used. |
| printRateYn | `String` | Print Rate Y/N |
| products | `String` | Products Codes |
| profLoyaltySegmentCodes | `String` | Prof Loyalty Segment Codes |
| promotions | `String` | Promotions. |
| property | `String` | Code to uniquely identify the Property |
| psuedoRoomType | `String` | Psuedo Room Type |
| purgeDate | `DateTime` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quoteId | `String` | Quote ID provided by external system. |
| rateCode | `String` | Rate Code |
| rateMobileChkoutAllowed | `String` | Rate Mobile Chkout Allowed |
| rateableValue | `Float` | Stay rateable value. |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| rdenResort | `String` | Rden Property |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| reinstateDate | `DateTime` | Reinstate Date |
| repCancellationReasonCode | `String` | Reporting Cancellation Reason Code |
| repChannel | `String` | Reporting Channel |
| repCommissionCode | `String` | Reporting Commission Code |
| repDiscountReason | `String` | Reporting Discount Reason |
| repGuaranteeCode | `String` | Reporting Guarantee Code |
| repGuaranteeCodeDescription | `String` | Reporting Guarantee Code Desc |
| repGuestType | `String` | Reporting Guest Type |
| repNameTaxType | `String` | Reporting Name Tax Type |
| repNameTaxTypeDescription | `String` | Reporting Name Tax Type Desc |
| repProductCodes | `String` | Reporting Product Codes |
| repRoomCategoryLabel | `String` | Reporting Room Category Label |
| repWlPriority | `String` | Reporting Wl Priority |
| repWlReasonCode | `String` | Reporting Wl Reason Code |
| repWlReasonDescription | `String` | Reporting Wl Reason Desc |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationClDestinationId | `String` | Resv Cl Destination ID |
| reservationConfLetterId | `Float` | Internal |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `DateTime` | Reservation Date |
| reservationNameId | `Float` | Resv Name ID |
| reservationPreferences | `String` | Reservation Preferences |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | This field will be populated with a "Y" if the user has overridden any restriction with the exception of a hurdle override to accept the reservation. |
| resvClDestination | `String` | Reservation Cl Destination |
| resvConfLetterLta | `DateTime` | Reservation Conf Letter Lta |
| resvConfLetterStatus | `String` | Reservation Conf Letter Status |
| resvContactName | `String` | Reservation Contact Name |
| resvLoyaltySegmentCodes | `String` | Reservation Loyalty Segment Codes |
| resvNumber | `Float` | Not used in PMS currently. |
| resvStatus | `String` | Reservation Status |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rnBillingContactId | `Float` | Rn Billing Contact ID |
| rnReservationContactId | `Float` | Rn Resv Contact ID |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomCategoryLabel | `String` | Room Category Label |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| roomInstructions | `String` | Room Instructions |
| roomResort | `String` | Meeting Room Property |
| roomRevenue | `Float` | Room Revenue |
| roomServiceTime | `String` | This is the Turndown room service time. |
| routingYn | `String` | Routing Y/N |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| sfirstGuestName | `String` | Upper case of First name of the Guest who stayed in this hotel for this reservation. This is used  forthe Search purposes. |
| sguestName | `String` | Sguest Name |
| shareAmount | `Float` | Share Amount |
| shareId | `Float` | Share ID. |
| sharePrcnt | `Float` | Not used. |
| shareSeqNumber | `Float` | Type of revenue |
| sharedYn | `String` | Shared Y/N |
| sname | `String` | The Uppercase value of Last or Company. |
| sourceId | `Float` | Source ID |
| sourceName | `String` | Source Name |
| specialRequests | `String` | Special Requests |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomLabel | `String` | Statistical Room Label |
| statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| suiteWith | `String` | Suite With |
| superSearchIndexText | `String` | Super Search Index Text |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sysStatus | `String` | Record status. |
| taRecordLocator | `String` | Ta Record Locator |
| taxExemptNo | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Float` | Tax No of Stays |
| taxRegistrationNo | `Float` | Tax Registration Number |
| tiad | `String` | Tiad |
| totalRevenue | `Float` | Total Revenue |
| totalStayCostAfterUpsell | `Float` | Total Cost of Stay after upsale. |
| totalUpsellCharge | `Float` | Total Upsell Charge |
| traceYn | `String` | Identifies if there were any traces for the Guest on this reservation. |
| travelAgentId | `Float` | Travel Agent ID |
| travelAgentName | `String` | Travel Agent Name |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| udfc01 | `String` | Udfc01 |
| udfc02 | `String` | Udfc02 |
| udfc03 | `String` | Udfc03 |
| udfc04 | `String` | Udfc04 |
| udfc05 | `String` | Udfc05 |
| udfc06 | `String` | Udfc06 |
| udfc07 | `String` | Udfc07 |
| udfc08 | `String` | Udfc08 |
| udfc09 | `String` | Udfc09 |
| udfc10 | `String` | Udfc10 |
| udfc11 | `String` | Udfc11 |
| udfc12 | `String` | Udfc12 |
| udfc13 | `String` | Udfc13 |
| udfc14 | `String` | Udfc14 |
| udfc15 | `String` | Udfc15 |
| udfc16 | `String` | Udfc16 |
| udfc17 | `String` | Udfc17 |
| udfc18 | `String` | Udfc18 |
| udfc19 | `String` | Udfc19 |
| udfc20 | `String` | Udfc20 |
| udfc21 | `String` | Udfc21 |
| udfc22 | `String` | Udfc22 |
| udfc23 | `String` | Udfc23 |
| udfc24 | `String` | Udfc24 |
| udfc25 | `String` | Udfc25 |
| udfc26 | `String` | Udfc26 |
| udfc27 | `String` | Udfc27 |
| udfc28 | `String` | Udfc28 |
| udfc29 | `String` | Udfc29 |
| udfc30 | `String` | Udfc30 |
| udfc31 | `String` | Udfc31 |
| udfc32 | `String` | Udfc32 |
| udfc33 | `String` | Udfc33 |
| udfc34 | `String` | Udfc34 |
| udfc35 | `String` | Udfc35 |
| udfc36 | `String` | Udfc36 |
| udfc37 | `String` | Udfc37 |
| udfc38 | `String` | Udfc38 |
| udfc39 | `String` | Udfc39 |
| udfc40 | `String` | Udfc40 |
| udfd01 | `Date` | Udfd01 |
| udfd02 | `Date` | Udfd02 |
| udfd03 | `Date` | Udfd03 |
| udfd04 | `Date` | Udfd04 |
| udfd05 | `Date` | Udfd05 |
| udfd06 | `Date` | Udfd06 |
| udfd07 | `Date` | Udfd07 |
| udfd08 | `Date` | Udfd08 |
| udfd09 | `Date` | Udfd09 |
| udfd10 | `Date` | Udfd10 |
| udfd11 | `Date` | Udfd11 |
| udfd12 | `Date` | Udfd12 |
| udfd13 | `Date` | Udfd13 |
| udfd14 | `Date` | Udfd14 |
| udfd15 | `Date` | Udfd15 |
| udfd16 | `Date` | Udfd16 |
| udfd17 | `Date` | Udfd17 |
| udfd18 | `Date` | Udfd18 |
| udfd19 | `Date` | Udfd19 |
| udfd20 | `Date` | Udfd20 |
| udfn01 | `Float` | Udfn01 |
| udfn02 | `Float` | Udfn02 |
| udfn03 | `Float` | Udfn03 |
| udfn04 | `Float` | Udfn04 |
| udfn05 | `Float` | Udfn05 |
| udfn06 | `Float` | Udfn06 |
| udfn07 | `Float` | Udfn07 |
| udfn08 | `Float` | Udfn08 |
| udfn09 | `Float` | Udfn09 |
| udfn10 | `Float` | Udfn10 |
| udfn11 | `Float` | Udfn11 |
| udfn12 | `Float` | Udfn12 |
| udfn13 | `Float` | Udfn13 |
| udfn14 | `Float` | Udfn14 |
| udfn15 | `Float` | Udfn15 |
| udfn16 | `Float` | Udfn16 |
| udfn17 | `Float` | Udfn17 |
| udfn18 | `Float` | Udfn18 |
| udfn19 | `Float` | Udfn19 |
| udfn20 | `Float` | Udfn20 |
| udfn21 | `Float` | Udfn21 |
| udfn22 | `Float` | Udfn22 |
| udfn23 | `Float` | Udfn23 |
| udfn24 | `Float` | Udfn24 |
| udfn25 | `Float` | Udfn25 |
| udfn26 | `Float` | Udfn26 |
| udfn27 | `Float` | Udfn27 |
| udfn28 | `Float` | Udfn28 |
| udfn29 | `Float` | Udfn29 |
| udfn30 | `Float` | Udfn30 |
| udfn31 | `Float` | Udfn31 |
| udfn32 | `Float` | Udfn32 |
| udfn33 | `Float` | Udfn33 |
| udfn34 | `Float` | Udfn34 |
| udfn35 | `Float` | Udfn35 |
| udfn36 | `Float` | Udfn36 |
| udfn37 | `Float` | Udfn37 |
| udfn38 | `Float` | Udfn38 |
| udfn39 | `Float` | Udfn39 |
| udfn40 | `Float` | Udfn40 |
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| updateUserName | `String` | Update User |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| upsellRuleId | `Float` | Upsell Rule ID |
| upsoldByUserId | `Float` | User ID who upsold the reservation. |
| videoCheckoutYn | `String` | Flag if the guest can do video checkout |
| vip | `String` | VIP Status |
| visaExpirationDate | `Date` | Visa Expiration Date |
| visaIssueDate | `Date` | Visa Issue Date |
| visaNumber | `String` | Visa Number |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| walkinYn | `String` | Walkin Y/N |
| wlPriority | `String` | Wl Priority |
| wlReasonCode | `String` | Wl Reason Code |
| wlReasonDescription | `String` | Wl Reason Description |
| wlTelephoneNo | `String` | This is the waitlist telephone number. |
| xcompanyName | `String` | Extended Byte Company Name |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingsReservationPropertyPropertyDetailsType

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

### SimpleReportsBookingsReservationQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| reservationgeneralDetailsActualCheckInDate | `DateTimeInput` | Actual Check In Date |
| reservationgeneralDetailsActualCheckOutDate | `DateTimeInput` | Actual Check Out Date |
| reservationgeneralDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationgeneralDetailsTruncArrival | `DateInput!` | Trunc Arrival<br>`@mandatoryInput` |
| reservationgeneralDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationgeneralDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationgeneralDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationgeneralDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationgeneralDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| reservationgeneralDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationgeneralDetailsConfirmationNo | `StringInput` | Confirmation Number |
| reservationgeneralDetailsCustomReference | `StringInput` | Custom Reference |
| reservationgeneralDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationgeneralDetailsDeparture | `DateTimeInput` | Departure |
| reservationgeneralDetailsTruncDeparture | `DateInput!` | Trunc Departure<br>`@mandatoryInput` |
| reservationgeneralDetailsEventId | `FloatInput` | Event ID |
| reservationgeneralDetailsExternalReference | `StringInput` | External Reference |
| reservationgeneralDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationgeneralDetailsGuaranteeCode | `StringInput` | Guarantee Code |
| reservationgeneralDetailsGuestNameId | `FloatInput` | Guest Name ID |
| reservationgeneralDetailsInsertUser | `FloatInput` | Insert User |
| reservationgeneralDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationgeneralDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationgeneralDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationgeneralDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationgeneralDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationgeneralDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationgeneralDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| reservationgeneralDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationgeneralDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationgeneralDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationgeneralDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationgeneralDetailsResvStatus | `StringInput` | Reservation Status |
| reservationgeneralDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationgeneralDetailsSfirstGuestName | `StringInput` | Upper case of First name of the Guest who stayed in this hotel for this reservation. This is used  forthe Search purposes. |
| reservationgeneralDetailsSguestName | `StringInput` | Sguest Name |
| reservationgeneralDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationgeneralDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationgeneralDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationgeneralDetailsUpdateDate | `DateTimeInput` | Update Date |
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
query simpleReportsBookingsReservation($input: SimpleReportsBookingsReservationQueryArgumentsType!) {
  simpleReportsBookingsReservation(input: $input) @stream {
    reservationGeneralDetails {
      aSBProratedYn
      accompanyingNames
      accompanyingYn
      actualCheckInDate
      actualCheckOutDate
      addressId
      addresseeName
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      alienRegistrationNo
      allotmentHeaderId
      allotmentRecordType
      alternateLanguage
      alternateSalutation
      alternateTitle
      amenityEligibleYn
      amenityLevelCode
      amountPercent
      anonymizationStatus
      approvalAmountCalcMethod
      arrival
      arrivalCarrierCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalStationCode
      arrivalSystemDateTime
      arrivalTime
      arrivalTranportationYn
      arrivalTransportCode
      arrivalTransportType
      authorisedBillingYn
      authorizerId
      autoCheckinYn
      autoSettleDays
      autoSettleYn
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipId
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      billingContactId
      billingContactName
      blockCode
      blockId
      blockResort
      bonusCheckId
      bookedRoomCategory
      bookedRoomCategoryLabel
      businessDateCreated
      businessTitle
      bxgyDiscountYn
      cCreditLimit
      cDiscountAmount
      cHurdle
      cLocalBaseRateAmount
      cRateableValue
      cancellationDate
      cancellationNo
      cancellationReasonCode
      cancellationReasonDesc
      channel
      checkinDuration
      children
      childrenTaxFree
      children1
      children2
      children3
      children4
      children5
      comments
      commissionCode
      commissionPaid
      commissionPayoutTo
      commissionableYn
      compTypeCode
      companyId
      companyName
      complimentaryYn
      computedResvStatus
      confirmationLegNo
      confirmationLetter
      confirmationLetterId
      confirmationNo
      consumerYn
      contactNameId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReference
      dSI
      dateOfArrivalInCountry
      dateOpenedForPickup
      deletedFlag
      departure
      departureCarrierCode
      departureComments
      departureDate
      departureDateTime
      departureEstimateTime
      departureStationCode
      departureTime
      departureTransportCode
      departureTransportType
      departureTransportationYn
      directBillVerifyResponse
      discountAmt
      discountPrcnt
      discountReasonCode
      displayColor
      doNotMoveRoom
      doNotMoveYn
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      entryDate
      entryPoint
      etrComments
      eventId
      exchangeDate
      exchangePostingType
      exchangeRate
      expectedTimeOfReturn
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalLegNo
      externalReference
      externalReferenceType
      extnNumber
      extnType
      extraBeds
      fbRevenue
      financiallyResponsibleYn
      firstNightUpsell
      fixedCharge
      fixedRateYn
      folioAddrElementId
      folioCloseDate
      folioText1
      folioYn
      gDSRecordLocator
      groupId
      groupName
      guaranteeCode
      guaranteeCodeDesc
      guestCountry
      guestCountryDesc
      guestEmail
      guestFirstName
      guestFirstNameSdx
      guestLanguage
      guestLanguageDesc
      guestLastNameSdx
      guestMiddleName
      guestName
      guestNameId
      guestPhone
      guestPrivYn
      guestSignature
      guestStatus
      guestTitle
      guestTitleDesc
      guestType
      guestVIPDesc
      hasAnyShareFixedRateYn
      houseUseYn
      housekeepingExpectedServiceTime
      hurdle
      hurdleOverride
      immigrationStatus
      insertDate
      insertUser
      insertUserName
      intermediaryYn
      internalPrimaryKeyIDToUniquelyIdentifyTheRow
      invItemCodes
      invItemIds
      isUpsoldYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyOptions
      keyValidUntil
      lastDirectBillBatchDate
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoom
      lastSettleDate
      localBaseRateAmount
      locatorYn
      maintainRoomFeatures
      manualCheckoutStatus
      marketCode
      marketDesc
      masterShare
      mealplanYn
      membershipId
      membershipLevel
      membershipNumber
      membershipRank
      membershipType
      messageYn
      mobileAudioKeyYn
      multipleAdultsYn
      multipleBillingContactIdYN
      multipleBlocksYn
      multipleBookedRoomCateringYN
      multipleChildrenYn
      multipleCommentsYn
      multipleCommissionCodeYN
      multipleCompanyIdYN
      multipleCribsYn
      multipleCurrencyCodeYn
      multipleDiscountAmountYN
      multipleDiscountPrcntYn
      multipleExtensionsYn
      multipleFixedRate
      multipleGroupIdYN
      multipleMarketCodeYn
      multipleMembershipsYn
      multipleOriginOfBookingYN
      multiplePtsEligibilityYn
      multipleRateCodeYn
      multipleReservationContactIdYN
      multipleRoomCategoryYn
      multipleRoomYn
      multipleSegmentsYn
      multipleShareAmountYn
      multipleSourceIdYN
      multipleTravelAgentIdYN
      multipleXbedsYn
      multipleYn
      nameTaxDescription
      nameTaxType
      nameType
      nameUsageType
      nationality
      nextDestination
      nights
      numberOfRooms
      optInBatchFolYn
      optedForCommissionYN
      orgRoomCategory
      orgRoomCategoryLabel
      orgStayCost
      organizationID
      originOfBooking
      originOfBookingDesc
      originalArrival
      originalBaseRate
      originalEndDate
      overrideTurndownFlagYn
      ownerFfFlag
      paramMobility
      parentReservationNameId
      partyCode
      paymentAmount
      paymentMethod
      paymentMethodDesc
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pmsBusinessDate
      points
      pointsEligibilityCode
      pointsEligibilityDesc
      postChargingYn
      postCoFlag
      postingAllowedYn
      preChargingYn
      preRegisteredYn
      preferredRoomType
      printRateYn
      products
      profLoyaltySegmentCodes
      promotions
      property
      psuedoRoomType
      purgeDate
      purposeOfStay
      quoteId
      rateCode
      rateMobileChkoutAllowed
      rateableValue
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      reinstateDate
      repCancellationReasonCode
      repChannel
      repCommissionCode
      repDiscountReason
      repGuaranteeCode
      repGuaranteeCodeDescription
      repGuestType
      repNameTaxType
      repNameTaxTypeDescription
      repProductCodes
      repRoomCategoryLabel
      repWlPriority
      repWlReasonCode
      repWlReasonDescription
      resInsertSource
      resInsertSourceType
      reservationClDestinationId
      reservationConfLetterId
      reservationContactId
      reservationDate
      reservationNameId
      reservationPreferences
      resortChargeNumber
      restrictionOverride
      resvClDestination
      resvConfLetterLta
      resvConfLetterStatus
      resvContactName
      resvLoyaltySegmentCodes
      resvNumber
      resvStatus
      revenueTypeCode
      rnBillingContactId
      rnReservationContactId
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomCategoryLabel
      roomClass
      roomCost
      roomFeatures
      roomInstructions
      roomResort
      roomRevenue
      roomServiceTime
      routingYn
      scheduleCheckoutYn
      sfirstGuestName
      sguestName
      shareAmount
      shareId
      sharePrcnt
      shareSeqNumber
      sharedYn
      sname
      sourceId
      sourceName
      specialRequests
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      statisticalRateTier
      statisticalRoomLabel
      statisticalRoomType
      suiteWith
      superSearchIndexText
      sxfirstName
      sxname
      sysStatus
      taRecordLocator
      taxExemptNo
      taxNumberOfStays
      taxRegistrationNo
      tiad
      totalRevenue
      totalStayCostAfterUpsell
      totalUpsellCharge
      traceYn
      travelAgentId
      travelAgentName
      truncActualCheckOutDate
      turndownStatus
      udfc01
      udfc02
      udfc03
      udfc04
      udfc05
      udfc06
      udfc07
      udfc08
      udfc09
      udfc10
      udfc11
      udfc12
      udfc13
      udfc14
      udfc15
      udfc16
      udfc17
      udfc18
      udfc19
      udfc20
      udfc21
      udfc22
      udfc23
      udfc24
      udfc25
      udfc26
      udfc27
      udfc28
      udfc29
      udfc30
      udfc31
      udfc32
      udfc33
      udfc34
      udfc35
      udfc36
      udfc37
      udfc38
      udfc39
      udfc40
      udfd01
      udfd02
      udfd03
      udfd04
      udfd05
      udfd06
      udfd07
      udfd08
      udfd09
      udfd10
      udfd11
      udfd12
      udfd13
      udfd14
      udfd15
      udfd16
      udfd17
      udfd18
      udfd19
      udfd20
      udfn01
      udfn02
      udfn03
      udfn04
      udfn05
      udfn06
      udfn07
      udfn08
      udfn09
      udfn10
      udfn11
      udfn12
      udfn13
      udfn14
      udfn15
      udfn16
      udfn17
      udfn18
      udfn19
      udfn20
      udfn21
      udfn22
      udfn23
      udfn24
      udfn25
      udfn26
      udfn27
      udfn28
      udfn29
      udfn30
      udfn31
      udfn32
      udfn33
      udfn34
      udfn35
      udfn36
      udfn37
      udfn38
      udfn39
      udfn40
      uniCardId
      updateDate
      updateUser
      updateUserName
      upsellCharge
      upsellRuleId
      upsoldByUserId
      videoCheckoutYn
      vip
      visaExpirationDate
      visaIssueDate
      visaNumber
      visaValidityType
      walkinYn
      wlPriority
      wlReasonCode
      wlReasonDescription
      wlTelephoneNo
      xcompanyName
      xfirstName
      xlastName
      yieldableYn
      ymCode
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
reservation_general_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompanyingNames': pl.Utf8,
    'accompanyingYn': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeName': pl.Utf8,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allotmentHeaderId': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'anonymizationStatus': pl.Utf8,
    'approvalAmountCalcMethod': pl.Float64,
    'arrival': pl.Utf8,
    'arrivalCarrierCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalStationCode': pl.Utf8,
    'arrivalSystemDateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivalTranportationYn': pl.Utf8,
    'arrivalTransportCode': pl.Utf8,
    'arrivalTransportType': pl.Utf8,
    'authorisedBillingYn': pl.Utf8,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleYn': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipId': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockId': pl.Float64,
    'blockResort': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedRoomCategoryLabel': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessTitle': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cCreditLimit': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cHurdle': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cRateableValue': pl.Float64,
    'cancellationDate': pl.Utf8,
    'cancellationNo': pl.Utf8,
    'cancellationReasonCode': pl.Utf8,
    'cancellationReasonDesc': pl.Utf8,
    'channel': pl.Utf8,
    'checkinDuration': pl.Float64,
    'children': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'comments': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYn': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyId': pl.Float64,
    'companyName': pl.Utf8,
    'complimentaryYn': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNo': pl.Float64,
    'confirmationLetter': pl.Utf8,
    'confirmationLetterId': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactNameId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReference': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departure': pl.Utf8,
    'departureCarrierCode': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureEstimateTime': pl.Utf8,
    'departureStationCode': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportType': pl.Utf8,
    'departureTransportationYn': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'discountAmt': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReasonCode': pl.Utf8,
    'displayColor': pl.Utf8,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYn': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'etrComments': pl.Utf8,
    'eventId': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'expectedTimeOfReturn': pl.Utf8,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalLegNo': pl.Float64,
    'externalReference': pl.Utf8,
    'externalReferenceType': pl.Utf8,
    'extnNumber': pl.Float64,
    'extnType': pl.Utf8,
    'extraBeds': pl.Float64,
    'fbRevenue': pl.Float64,
    'financiallyResponsibleYn': pl.Utf8,
    'firstNightUpsell': pl.Float64,
    'fixedCharge': pl.Float64,
    'fixedRateYn': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioYn': pl.Utf8,
    'gDSRecordLocator': pl.Utf8,
    'groupId': pl.Float64,
    'groupName': pl.Utf8,
    'guaranteeCode': pl.Utf8,
    'guaranteeCodeDesc': pl.Utf8,
    'guestCountry': pl.Utf8,
    'guestCountryDesc': pl.Utf8,
    'guestEmail': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLanguage': pl.Utf8,
    'guestLanguageDesc': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestMiddleName': pl.Utf8,
    'guestName': pl.Utf8,
    'guestNameId': pl.Float64,
    'guestPhone': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestTitle': pl.Utf8,
    'guestTitleDesc': pl.Utf8,
    'guestType': pl.Utf8,
    'guestVIPDesc': pl.Utf8,
    'hasAnyShareFixedRateYn': pl.Utf8,
    'houseUseYn': pl.Utf8,
    'housekeepingExpectedServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'intermediaryYn': pl.Utf8,
    'internalPrimaryKeyIDToUniquelyIdentifyTheRow': pl.Float64,
    'invItemCodes': pl.Utf8,
    'invItemIds': pl.Utf8,
    'isUpsoldYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyOptions': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastDirectBillBatchDate': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locatorYn': pl.Utf8,
    'maintainRoomFeatures': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDesc': pl.Utf8,
    'masterShare': pl.Utf8,
    'mealplanYn': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipRank': pl.Float64,
    'membershipType': pl.Utf8,
    'messageYn': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'multipleAdultsYn': pl.Utf8,
    'multipleBillingContactIdYN': pl.Utf8,
    'multipleBlocksYn': pl.Utf8,
    'multipleBookedRoomCateringYN': pl.Utf8,
    'multipleChildrenYn': pl.Utf8,
    'multipleCommentsYn': pl.Utf8,
    'multipleCommissionCodeYN': pl.Utf8,
    'multipleCompanyIdYN': pl.Utf8,
    'multipleCribsYn': pl.Utf8,
    'multipleCurrencyCodeYn': pl.Utf8,
    'multipleDiscountAmountYN': pl.Utf8,
    'multipleDiscountPrcntYn': pl.Utf8,
    'multipleExtensionsYn': pl.Utf8,
    'multipleFixedRate': pl.Utf8,
    'multipleGroupIdYN': pl.Utf8,
    'multipleMarketCodeYn': pl.Utf8,
    'multipleMembershipsYn': pl.Utf8,
    'multipleOriginOfBookingYN': pl.Utf8,
    'multiplePtsEligibilityYn': pl.Utf8,
    'multipleRateCodeYn': pl.Utf8,
    'multipleReservationContactIdYN': pl.Utf8,
    'multipleRoomCategoryYn': pl.Utf8,
    'multipleRoomYn': pl.Utf8,
    'multipleSegmentsYn': pl.Utf8,
    'multipleShareAmountYn': pl.Utf8,
    'multipleSourceIdYN': pl.Utf8,
    'multipleTravelAgentIdYN': pl.Utf8,
    'multipleXbedsYn': pl.Utf8,
    'multipleYn': pl.Utf8,
    'nameTaxDescription': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameType': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nationality': pl.Utf8,
    'nextDestination': pl.Utf8,
    'nights': pl.Float64,
    'numberOfRooms': pl.Float64,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'orgRoomCategory': pl.Utf8,
    'orgRoomCategoryLabel': pl.Utf8,
    'orgStayCost': pl.Float64,
    'organizationID': pl.Int64,
    'originOfBooking': pl.Utf8,
    'originOfBookingDesc': pl.Utf8,
    'originalArrival': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'overrideTurndownFlagYn': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'paramMobility': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'partyCode': pl.Utf8,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentMethodDesc': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pmsBusinessDate': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'pointsEligibilityDesc': pl.Utf8,
    'postChargingYn': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postingAllowedYn': pl.Utf8,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'printRateYn': pl.Utf8,
    'products': pl.Utf8,
    'profLoyaltySegmentCodes': pl.Utf8,
    'promotions': pl.Utf8,
    'property': pl.Utf8,
    'psuedoRoomType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quoteId': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateMobileChkoutAllowed': pl.Utf8,
    'rateableValue': pl.Float64,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'reinstateDate': pl.Utf8,
    'repCancellationReasonCode': pl.Utf8,
    'repChannel': pl.Utf8,
    'repCommissionCode': pl.Utf8,
    'repDiscountReason': pl.Utf8,
    'repGuaranteeCode': pl.Utf8,
    'repGuaranteeCodeDescription': pl.Utf8,
    'repGuestType': pl.Utf8,
    'repNameTaxType': pl.Utf8,
    'repNameTaxTypeDescription': pl.Utf8,
    'repProductCodes': pl.Utf8,
    'repRoomCategoryLabel': pl.Utf8,
    'repWlPriority': pl.Utf8,
    'repWlReasonCode': pl.Utf8,
    'repWlReasonDescription': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationClDestinationId': pl.Utf8,
    'reservationConfLetterId': pl.Float64,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationPreferences': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvClDestination': pl.Utf8,
    'resvConfLetterLta': pl.Utf8,
    'resvConfLetterStatus': pl.Utf8,
    'resvContactName': pl.Utf8,
    'resvLoyaltySegmentCodes': pl.Utf8,
    'resvNumber': pl.Float64,
    'resvStatus': pl.Utf8,
    'revenueTypeCode': pl.Utf8,
    'rnBillingContactId': pl.Float64,
    'rnReservationContactId': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomCategoryLabel': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomFeatures': pl.Utf8,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'routingYn': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sfirstGuestName': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareAmount': pl.Float64,
    'shareId': pl.Float64,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'sharedYn': pl.Utf8,
    'sname': pl.Utf8,
    'sourceId': pl.Float64,
    'sourceName': pl.Utf8,
    'specialRequests': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomLabel': pl.Utf8,
    'statisticalRoomType': pl.Float64,
    'suiteWith': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'sysStatus': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNo': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxRegistrationNo': pl.Float64,
    'tiad': pl.Utf8,
    'totalRevenue': pl.Float64,
    'totalStayCostAfterUpsell': pl.Float64,
    'totalUpsellCharge': pl.Float64,
    'traceYn': pl.Utf8,
    'travelAgentId': pl.Float64,
    'travelAgentName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'udfc01': pl.Utf8,
    'udfc02': pl.Utf8,
    'udfc03': pl.Utf8,
    'udfc04': pl.Utf8,
    'udfc05': pl.Utf8,
    'udfc06': pl.Utf8,
    'udfc07': pl.Utf8,
    'udfc08': pl.Utf8,
    'udfc09': pl.Utf8,
    'udfc10': pl.Utf8,
    'udfc11': pl.Utf8,
    'udfc12': pl.Utf8,
    'udfc13': pl.Utf8,
    'udfc14': pl.Utf8,
    'udfc15': pl.Utf8,
    'udfc16': pl.Utf8,
    'udfc17': pl.Utf8,
    'udfc18': pl.Utf8,
    'udfc19': pl.Utf8,
    'udfc20': pl.Utf8,
    'udfc21': pl.Utf8,
    'udfc22': pl.Utf8,
    'udfc23': pl.Utf8,
    'udfc24': pl.Utf8,
    'udfc25': pl.Utf8,
    'udfc26': pl.Utf8,
    'udfc27': pl.Utf8,
    'udfc28': pl.Utf8,
    'udfc29': pl.Utf8,
    'udfc30': pl.Utf8,
    'udfc31': pl.Utf8,
    'udfc32': pl.Utf8,
    'udfc33': pl.Utf8,
    'udfc34': pl.Utf8,
    'udfc35': pl.Utf8,
    'udfc36': pl.Utf8,
    'udfc37': pl.Utf8,
    'udfc38': pl.Utf8,
    'udfc39': pl.Utf8,
    'udfc40': pl.Utf8,
    'udfd01': pl.Utf8,
    'udfd02': pl.Utf8,
    'udfd03': pl.Utf8,
    'udfd04': pl.Utf8,
    'udfd05': pl.Utf8,
    'udfd06': pl.Utf8,
    'udfd07': pl.Utf8,
    'udfd08': pl.Utf8,
    'udfd09': pl.Utf8,
    'udfd10': pl.Utf8,
    'udfd11': pl.Utf8,
    'udfd12': pl.Utf8,
    'udfd13': pl.Utf8,
    'udfd14': pl.Utf8,
    'udfd15': pl.Utf8,
    'udfd16': pl.Utf8,
    'udfd17': pl.Utf8,
    'udfd18': pl.Utf8,
    'udfd19': pl.Utf8,
    'udfd20': pl.Utf8,
    'udfn01': pl.Float64,
    'udfn02': pl.Float64,
    'udfn03': pl.Float64,
    'udfn04': pl.Float64,
    'udfn05': pl.Float64,
    'udfn06': pl.Float64,
    'udfn07': pl.Float64,
    'udfn08': pl.Float64,
    'udfn09': pl.Float64,
    'udfn10': pl.Float64,
    'udfn11': pl.Float64,
    'udfn12': pl.Float64,
    'udfn13': pl.Float64,
    'udfn14': pl.Float64,
    'udfn15': pl.Float64,
    'udfn16': pl.Float64,
    'udfn17': pl.Float64,
    'udfn18': pl.Float64,
    'udfn19': pl.Float64,
    'udfn20': pl.Float64,
    'udfn21': pl.Float64,
    'udfn22': pl.Float64,
    'udfn23': pl.Float64,
    'udfn24': pl.Float64,
    'udfn25': pl.Float64,
    'udfn26': pl.Float64,
    'udfn27': pl.Float64,
    'udfn28': pl.Float64,
    'udfn29': pl.Float64,
    'udfn30': pl.Float64,
    'udfn31': pl.Float64,
    'udfn32': pl.Float64,
    'udfn33': pl.Float64,
    'udfn34': pl.Float64,
    'udfn35': pl.Float64,
    'udfn36': pl.Float64,
    'udfn37': pl.Float64,
    'udfn38': pl.Float64,
    'udfn39': pl.Float64,
    'udfn40': pl.Float64,
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'updateUserName': pl.Utf8,
    'upsellCharge': pl.Float64,
    'upsellRuleId': pl.Float64,
    'upsoldByUserId': pl.Float64,
    'videoCheckoutYn': pl.Utf8,
    'vip': pl.Utf8,
    'visaExpirationDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'walkinYn': pl.Utf8,
    'wlPriority': pl.Utf8,
    'wlReasonCode': pl.Utf8,
    'wlReasonDescription': pl.Utf8,
    'wlTelephoneNo': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
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