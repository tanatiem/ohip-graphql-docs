# BookingsReservation
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `bookingsReservation`
> Detailed information on reservations booked in the past and future including market code rate code reservation status guest information and associated room and revenue details.
  
**Return:** [`[BookingsReservationType]`](#bookingsreservationtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`BookingsReservationQueryArgumentsType!`](#bookingsreservationqueryargumentstype) |  |

## Object Types

### BookingsReservationType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationDetails | [`BookingsReservationReservationDetailsType`](#bookingsreservationreservationdetailstype) | Reservation Details |
| 2 | accompanyingGuestDetails | [`BookingsReservationAccompanyingGuestDetailsType`](#bookingsreservationaccompanyingguestdetailstype) | Accompanying Guest Details |
| 3 | channelDetails | [`BookingsReservationChannelDetailsType`](#bookingsreservationchanneldetailstype) | Channel Details |
| 4 | externalReferencesDetails | [`BookingsReservationExternalReferencesDetailsType`](#bookingsreservationexternalreferencesdetailstype) | External References Details |
| 5 | fixedChargesDetails | [`BookingsReservationFixedChargesDetailsType`](#bookingsreservationfixedchargesdetailstype) | Fixed Charges Details |
| 6 | guestReservationMessagesDetails | [`BookingsReservationGuestReservationMessagesDetailsType`](#bookingsreservationguestreservationmessagesdetailstype) | Guest Reservation Messages |
| 7 | locatorsDetails | [`BookingsReservationLocatorsDetailsType`](#bookingsreservationlocatorsdetailstype) | Locators Details |
| 8 | marketDetails | [`BookingsReservationMarketDetailsType`](#bookingsreservationmarketdetailstype) | Market Details |
| 9 | profileAllInformationDetails | [`BookingsReservationProfileAllInformationDetailsType`](#bookingsreservationprofileallinformationdetailstype) | Profile All Details |
| 10 | reservationProfileAccountsCompanyDetails | [`BookingsReservationReservationProfileAccountsCompanyDetailsType`](#bookingsreservationreservationprofileaccountscompanydetailstype) | Reservation Profile Accounts Company Details |
| 11 | profileAccountsTravelAgentDetails | [`BookingsReservationProfileAccountsTravelAgentDetailsType`](#bookingsreservationprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| 12 | reservationProfileAccountsSourceDetails | [`BookingsReservationReservationProfileAccountsSourceDetailsType`](#bookingsreservationreservationprofileaccountssourcedetailstype) | Reservation Profile Accounts Source Details |
| 13 | rateCodeDetails | [`BookingsReservationRateCodeDetailsType`](#bookingsreservationratecodedetailstype) | Rate Code Details |
| 14 | reservationAlertsDetails | [`BookingsReservationReservationAlertsDetailsType`](#bookingsreservationreservationalertsdetailstype) | Reservation Alerts Details |
| 15 | reservationCancelPolicyDetails | [`BookingsReservationReservationCancelPolicyDetailsType`](#bookingsreservationreservationcancelpolicydetailstype) | Reservation Cancel Policy Details |
| 16 | reservationDetailDetails | [`BookingsReservationReservationDetailDetailsType`](#bookingsreservationreservationdetaildetailstype) | Reservation Detail Details |
| 17 | reservationEcouponsDetails | [`BookingsReservationReservationEcouponsDetailsType`](#bookingsreservationreservationecouponsdetailstype) | Reservation Ecoupons Details |
| 18 | reservationItemsDetails | [`BookingsReservationReservationItemsDetailsType`](#bookingsreservationreservationitemsdetailstype) | Reservation Items Details |
| 19 | reservationPreferenceDetails | [`BookingsReservationReservationPreferenceDetailsType`](#bookingsreservationreservationpreferencedetailstype) | Reservation Preference |
| 20 | reservationProductsDetails | [`BookingsReservationReservationProductsDetailsType`](#bookingsreservationreservationproductsdetailstype) | Reservation Products Details |
| 21 | reservationPromotionsDetails | [`BookingsReservationReservationPromotionsDetailsType`](#bookingsreservationreservationpromotionsdetailstype) | Reservation Promotions Details |
| 22 | reservationStatusDetails | [`BookingsReservationReservationStatusDetailsType`](#bookingsreservationreservationstatusdetailstype) | Reservation Status Details |
| 23 | reservationThresholdsDetails | [`BookingsReservationReservationThresholdsDetailsType`](#bookingsreservationreservationthresholdsdetailstype) | Reservation Thresholds Details |
| 24 | propertyPropertyDetails | [`BookingsReservationPropertyPropertyDetailsType`](#bookingsreservationpropertypropertydetailstype) | Resort Details |
| 25 | propertyServiceRequestsDetails | [`BookingsReservationPropertyServiceRequestsDetailsType`](#bookingsreservationpropertyservicerequestsdetailstype) | Property Service Requests |
| 26 | reservationCommentDetails | [`BookingsReservationReservationCommentDetailsType`](#bookingsreservationreservationcommentdetailstype) | Reservation Comment |
| 27 | reservationConfirmationLetterDetails | [`BookingsReservationReservationConfirmationLetterDetailsType`](#bookingsreservationreservationconfirmationletterdetailstype) | Reservation Confirmation Letter |
| 28 | reservationDepositScheduleDetails | [`BookingsReservationReservationDepositScheduleDetailsType`](#bookingsreservationreservationdepositscheduledetailstype) | Reservation Deposit Schedule |
| 29 | reservationPaymentMethodsDetails | [`BookingsReservationReservationPaymentMethodsDetailsType`](#bookingsreservationreservationpaymentmethodsdetailstype) | Reservation Payment Methods |
| 30 | reservationProductsTicketsDetails | [`BookingsReservationReservationProductsTicketsDetailsType`](#bookingsreservationreservationproductsticketsdetailstype) | Reservation Products Tickets |
| 31 | roomCategoryDetails | [`BookingsReservationRoomCategoryDetailsType`](#bookingsreservationroomcategorydetailstype) | Room Category Details |
| 32 | bookedRoomCategoryDetails | [`BookingsReservationBookedRoomCategoryDetailsType`](#bookingsreservationbookedroomcategorydetailstype) | Booked Room Category Details |
| 33 | routingInstructionDetails | [`BookingsReservationRoutingInstructionDetailsType`](#bookingsreservationroutinginstructiondetailstype) | Routing Instruction Details |
| 34 | sourceTableDetails | [`BookingsReservationSourceTableDetailsType`](#bookingsreservationsourcetabledetailstype) | Source Table Details |
| 35 | trackitItemsDetails | [`BookingsReservationTrackitItemsDetailsType`](#bookingsreservationtrackititemsdetailstype) | Trackit Items Details |
| 36 | guestReservationTracesDetails | [`BookingsReservationGuestReservationTracesDetailsType`](#bookingsreservationguestreservationtracesdetailstype) | Guest Reservation Traces |
| 37 | rotationPointAdjustments | [`BookingsReservationRotationPointAdjustmentsType`](#bookingsreservationrotationpointadjustmentstype) | OVOS Rotation Points Adjustment |
| 38 | rotationOverrides | [`BookingsReservationRotationOverridesType`](#bookingsreservationrotationoverridestype) | OVOS Rotation Overrides |
| 39 | linkedReservationDetails | [`BookingsReservationLinkedReservationDetailsType`](#bookingsreservationlinkedreservationdetailstype) | Linked Reservation Details |
| 40 | sharedReservationDetails | [`BookingsReservationSharedReservationDetailsType`](#bookingsreservationsharedreservationdetailstype) | Shared Reservation Details |
| 41 | reservationMembershipDetails | [`BookingsReservationReservationMembershipDetailsType`](#bookingsreservationreservationmembershipdetailstype) | Reservation Membership |
| 42 | bookingsReservationRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `DateTime` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `DateTime` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `DateTime` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `DateTime` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | chainCode | `String` | Chain Code |
| 152 | channelDescription | `String` | Channel Description |
| 153 | channelOrderBy | `Float` | Channel Order By |
| 154 | channelid | `String` | Channelid |
| 155 | checkInInitiatedBy | `String` | Check In Initiated By |
| 156 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 157 | childBucket1 | `Float` | Child Bucket 1 |
| 158 | childBucket4 | `Float` | Child Bucket 4 |
| 159 | childBucket5 | `Float` | Child Bucket 5 |
| 160 | children | `Float` | Children |
| 161 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 162 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 163 | childrenAges | `String` | Children Ages |
| 164 | commissionCode | `String` | Commission Code |
| 165 | commissionDescription | `String` | Commission Description |
| 166 | commissionHoldCode | `String` | Commission Hold Code |
| 167 | commissionPaid | `Float` | Commission Paid |
| 168 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 169 | commissionableYN | `String` | Commissionable YN |
| 170 | commissionid | `String` | Commissionid |
| 171 | compHouse | `String` | Comp House |
| 172 | compTypeCode | `String` | Comp Type Code |
| 173 | companyCity | `String` | Company City |
| 174 | companyCountry | `String` | Company Country |
| 175 | companyID | `Float` | Company ID |
| 176 | companyName | `String` | Company Name |
| 177 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 178 | companyProfileID | `Float` | Company Profile ID |
| 179 | complimentaryYN | `String` | Complimentary YN |
| 180 | compreasonid | `String` | Compreasonid |
| 181 | computedResvStatus | `String` | Calculated reservation status. |
| 182 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 183 | confirmationNo | `String` | Shared Confirmation Number |
| 184 | consumerYn | `String` | Consumer Y/N |
| 185 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 186 | contactProfileID | `Float` | Contact Profile ID |
| 187 | contactProfileName | `String` | Contact Profile Name |
| 188 | createdBy | `String` | The name of the user who created the record. |
| 189 | createdByDefaultResort | `String` | Created By Default Property |
| 190 | createdDate | `Date` | Created Date |
| 191 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 192 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 193 | creditCardId | `Float` | Credit Card ID |
| 194 | creditLimit | `Float` | Credit Limit |
| 195 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 196 | cribs | `Float` | Cribs |
| 197 | currencyCode | `String` | Currency Code |
| 198 | customReferenceNumber | `String` | Custom Reference Number |
| 199 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 200 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 201 | deletedFlag | `String` | Deleted Flag |
| 202 | departtransportid | `String` | Departtransportid |
| 203 | departureComments | `String` | Departure Comments |
| 204 | departureDate | `Date` | Departure Date |
| 205 | departureDateTime | `Date` | Departure Date Time |
| 206 | departureTime | `String` | Departure Time |
| 207 | departureTransportCode | `String` | Departure Transport Code |
| 208 | departureTransportationYN | `String` | Departure Transportation YN |
| 209 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 210 | detatchedDate | `Date` | Detatched Date |
| 211 | detatchedYN | `String` | Detatched YN |
| 212 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 213 | directbillauthby | `Float` | Directbillauthby |
| 214 | discountAmount | `Float` | Discount Amount |
| 215 | discountAmt | `Float` | Discount Amount |
| 216 | discountPercent | `Float` | Discount Percentage. |
| 217 | discountPrcnt | `Float` | Discount Prcnt |
| 218 | discountReason | `String` | Discount Reason |
| 219 | discountReasonDescription | `String` | Discount Reason Description |
| 220 | discountreasonid | `String` | Discountreasonid |
| 221 | displayColor | `String` | Display Color |
| 222 | dmlSeqNumber | `Float` | Dml Sequence No |
| 223 | doNotMoveRoom | `String` | Do Not Move Room |
| 224 | doNotMoveYN | `String` | Do not move room flag. |
| 225 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 226 | dropOffDate | `Date` | Drop Off Date |
| 227 | dropOffStation | `String` | Drop Off Station |
| 228 | dropOffTime | `String` | Drop Off Time |
| 229 | dropOffType | `String` | Drop Off Type |
| 230 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 231 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 232 | effectiveRateAmount | `Float` | Not used. |
| 233 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 234 | emailAddress | `String` | Email Address |
| 235 | emailFolioYn | `String` | Email Folio Y/N |
| 236 | emailId | `Float` | Email ID |
| 237 | emailYn | `String` | Email Y/N |
| 238 | endCity | `String` | End City |
| 239 | endDatetime | `DateTime` | End Datetime |
| 240 | endDistrict | `String` | End District |
| 241 | endState | `String` | End State |
| 242 | endbusinessdate | `Date` | Endbusinessdate |
| 243 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 244 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 245 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 246 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 247 | eventId | `Float` | Event ID |
| 248 | exchangePostingType | `String` | Exchange Posting Type |
| 249 | exchangeRate | `Float` | Exchange Rate |
| 250 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 251 | expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 252 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 253 | extSegNo | `Float` | Not used |
| 254 | extSeqNumber | `Float` | Not used |
| 255 | extensionId | `Float` | Internal extension number for the main reservation |
| 256 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 257 | externalReference | `String` | External Reference |
| 258 | externalReferencesList | `String` | External References List |
| 259 | extraBeds | `Float` | Extra Beds |
| 260 | fBRevenue | `Float` | FB Revenue |
| 261 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 262 | faxId | `Float` | Fax ID |
| 263 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 264 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 265 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 266 | fixedCharge | `Float` | Not used. |
| 267 | fixedRateYN | `String` | Fixed Rate YN |
| 268 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 269 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 270 | folioNumber | `String` | Folio Number |
| 271 | folioText1 | `String` | Folio Text1 |
| 272 | folioText2 | `String` | Folio Text2 |
| 273 | foreignCurrencyID | `String` | Foreign Currency ID |
| 274 | freeChild | `Float` | Free Child |
| 275 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 276 | grossRateFuture | `Float` | Gross Rate Future |
| 277 | grossRatePast | `Float` | Gross Rate Past |
| 278 | groupName | `String` | Group Name |
| 279 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 280 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 281 | groupProfileClientID | `String` | Group Profile Client ID |
| 282 | groupProfileID | `Float` | Group Profile ID |
| 283 | groupProfileName | `String` | Group Profile Name |
| 284 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 285 | guaranteecodeid | `String` | Guaranteecodeid |
| 286 | guestFirstName | `String` | Guest First Name |
| 287 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 288 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 289 | guestSignature | `String` | Signature of the guest |
| 290 | guestStatus | `String` | Used for Police/Tourist Export |
| 291 | guestType | `String` | Guest Type |
| 292 | guestprofileid | `Float` | Guestprofileid |
| 293 | gueststatusid | `String` | Gueststatusid |
| 294 | guesttypeid | `String` | Guesttypeid |
| 295 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 296 | hurdle | `Float` | Hurdle |
| 297 | hurdleOverride | `String` | Hurdle Override |
| 298 | iDByMembershipClass | `String` | ID by Membership Class |
| 299 | iDByMembershipType | `String` | ID by Membership Type |
| 300 | individualCity | `String` | Guest Address. |
| 301 | individualCountry | `String` | Country of the guest |
| 302 | individualFirstName | `String` | Individual First Name |
| 303 | individualLastName | `String` | Individual Last Name |
| 304 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 305 | insertDate | `DateTime` | Insert Date |
| 306 | insertDateTime | `DateTime` | Insert DateTime |
| 307 | insertUser | `Float` | Insert User |
| 308 | intermediaryYn | `String` | Intermediary Y/N |
| 309 | internalAwardMembershipId | `Float` | Award Membership ID |
| 310 | internalBaseratecode | `String` | Baseratecode |
| 311 | internalBlockId | `Float` | Block ID. |
| 312 | internalCompanyprofileid | `Float` | Companyprofileid |
| 313 | internalGroupprofileid | `Float` | Groupprofileid |
| 314 | internalSourceprofileid | `Float` | Sourceprofileid |
| 315 | itemsQuantities | `String` | Items and Quantities |
| 316 | jRNUpdateDate | `Date` | JRN Update Date |
| 317 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 318 | keyValidUntil | `Date` | Key Valid Until |
| 319 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 320 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 321 | lastRoomNumber | `String` | Not used. |
| 322 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 323 | leadTimeDays | `Float` | Lead Time for ordering |
| 324 | lengthOfStay | `Float` | Length of Stay |
| 325 | linkedArrivalDate | `DateTime` | Linked Arrival Date |
| 326 | linkedDepartureDate | `DateTime` | Linked Departure Date |
| 327 | linkedRoomType | `String` | Linked Room Type |
| 328 | listOfMembershipID | `String` | Membership ID |
| 329 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 330 | locationID | `String` | Internal ID to uniquely identify the Property |
| 331 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 332 | mailYn | `String` | Mail Y/N |
| 333 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 334 | marketCode | `String` | Market Code |
| 335 | marketid | `String` | Marketid |
| 336 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 337 | mcGenBeginState | `String` | Mc Gen Begin State |
| 338 | mcGenEndDistrict | `String` | Mc Gen End District |
| 339 | mcGenEndState | `String` | Mc Gen End State |
| 340 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 341 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 342 | memberDescription | `String` | Member Description |
| 343 | memberLevel | `String` | Member Level |
| 344 | memberNumber | `String` | Member Number |
| 345 | membershipClass | `String` | Membership Class |
| 346 | membershipClassDescription | `String` | Membership Class Description |
| 347 | membershipCode | `String` | Membership Code |
| 348 | membershipId | `Float` | Membership ID |
| 349 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 350 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 351 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 352 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 353 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 354 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 355 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 356 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 357 | name | `String` | Name |
| 358 | nameUsageType | `String` | Name Usage Type |
| 359 | nextCountry | `String` | Next Country |
| 360 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 361 | numberOfRooms | `Float` | No of Rooms |
| 362 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 363 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 364 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 365 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 366 | originCode | `String` | Origin Code |
| 367 | originOfBooking | `String` | Origin Of Booking |
| 368 | originalBaseRate | `Float` | Not used. |
| 369 | originalEndDate | `Date` | Original End Date |
| 370 | originalStartDate | `Date` | Original Start Date |
| 371 | ownerFfFlag | `String` | Owner Ff Flag |
| 372 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 373 | packageCode | `String` | Package Code |
| 374 | packageCodeDescription | `String` | Package Code Description |
| 375 | packageForecastGroup | `String` | Package Forecast Group |
| 376 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 377 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 378 | parentreservationid | `Float` | Parentreservationid |
| 379 | partAllotment | `String` | Part Allotment |
| 380 | partyCode | `String` | Party Code |
| 381 | paxNo | `Float` | Pax Number |
| 382 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 383 | paymentMethod | `String` | Payment Method |
| 384 | paymentmethodid | `String` | Paymentmethodid |
| 385 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 386 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 387 | phoneId | `Float` | Phone ID |
| 388 | physicalQuantity | `Float` | Physical Quantity |
| 389 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 390 | pickUpDate | `Date` | Pick Up Date |
| 391 | pickUpStation | `String` | Pick Up Station |
| 392 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 393 | pickUpType | `String` | Pick Up Type |
| 394 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 395 | pickUpTime | `String` | Pick-Up Time |
| 396 | pickupRequiredYN | `String` | Pickup Required YN |
| 397 | points | `Float` | Points |
| 398 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 399 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 400 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 401 | postingAllowedYN | `String` | Posting Allowed YN |
| 402 | preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 403 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 404 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 405 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 406 | preference | `String` | Preference |
| 407 | preferenceType | `String` | Preference Type |
| 408 | preferredRoomType | `String` | Preferred Room Type |
| 409 | previousCountry | `String` | Previous Country |
| 410 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 411 | primaryShare | `String` | Primary Share |
| 412 | printRateYN | `String` | Print Rate YN |
| 413 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 414 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 415 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 416 | promotionCode | `String` | Promotion Code |
| 417 | promotionDescription | `String` | Promotion Description |
| 418 | property | `String` | Indicates if the value set for the specific property. |
| 419 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 420 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 421 | purgeDate | `DateTime` | Purge Date |
| 422 | purposeOfStay | `String` | Purpose of stay. |
| 423 | quantity | `Float` | Number of Rooms |
| 424 | queuePriority | `Float` | Queue priority of the reservation. |
| 425 | queueWaitTime | `Float` | Queue Wait Time |
| 426 | quoteId | `String` | Quote ID provided by external system. |
| 427 | rateAmount | `Float` | Rate Amount |
| 428 | rateCode | `String` | Rate Code |
| 429 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 430 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 431 | rateableValue | `Float` | Stay rateable value. |
| 432 | ratecodeid | `String` | Ratecodeid |
| 433 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 434 | rdResvStatus | `String` | Rd Reservation Status |
| 435 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 436 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 437 | rdenReservationDate | `Date` | Rden Reservation Date |
| 438 | rdenResort | `String` | Rden Property |
| 439 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 440 | registrationCardNo | `String` | Registration Card Number |
| 441 | registrationNumber | `Float` | Registration Number |
| 442 | reinstateDate | `DateTime` | Reinstate Date |
| 443 | repChannel | `String` | Reporting Channel |
| 444 | repChannelDescription | `String` | Reporting Channel Description |
| 445 | reportId | `String` | Report ID |
| 446 | resInsertSource | `String` | Reservation Insert Source |
| 447 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 448 | reservationContactId | `Float` | Resv Contact ID |
| 449 | reservationDate | `DateTime` | Reservation Date |
| 450 | reservationNameID | `Float` | Reservation Name ID |
| 451 | reservationStatus | `String` | Reservation Status |
| 452 | reservationType | `String` | Reservation Type |
| 453 | reservationTypeDescription | `String` | Reservation Type Description |
| 454 | reservationid | `Float` | Reservationid |
| 455 | resort | `String` | Property |
| 456 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 457 | restrictionOverride | `String` | Restriction Override |
| 458 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 459 | resvNameid | `Float` | Reservation Nameid |
| 460 | resvNumber | `Float` | Not used in PMS currently. |
| 461 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 462 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 463 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 464 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 465 | rhRoomFeatures | `String` | Rh Room Features |
| 466 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 467 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 468 | room | `String` | Room |
| 469 | roomCategory | `String` | Room Category |
| 470 | roomClass | `String` | Room Class |
| 471 | roomCost | `Float` | Room Cost |
| 472 | roomInstructions | `String` | Room Instructions |
| 473 | roomResort | `String` | Meeting Room Property |
| 474 | roomRevenue | `Float` | Room Revenue |
| 475 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 476 | roomServiceTime | `String` | This is the Turndown room service time. |
| 477 | roomTypeDescription | `String` | Room Type Description |
| 478 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 479 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 480 | roomcategoryid | `String` | Roomcategoryid |
| 481 | roomid | `String` | Roomid |
| 482 | routingYN | `String` | Routing YN |
| 483 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 484 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 485 | sguestName | `String` | Sguest Name |
| 486 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 487 | shareId | `Float` | Share ID. |
| 488 | shareName | `String` | Share Name |
| 489 | sharePrcnt | `Float` | Not used. |
| 490 | shareSeqNumber | `Float` | Type of revenue |
| 491 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 492 | sharedGuestName | `String` | Shared Guest Name |
| 493 | sharedProfileID | `Float` | Shared Profile ID |
| 494 | sharedReservationStatus | `String` | Shared Reservation Status |
| 495 | sharingYN | `String` | Sharing YN |
| 496 | sourceCity | `String` | Source City |
| 497 | sourceCode | `String` | Source Code |
| 498 | sourceCountry | `String` | Source Country |
| 499 | sourceName | `String` | Source Name |
| 500 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 501 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 502 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 503 | sourceProfileID | `Float` | Source Profile ID |
| 504 | sourceProfileName | `String` | Source Profile Name |
| 505 | sourceid | `String` | Sourceid |
| 506 | specialRequest | `String` | Special Request |
| 507 | specialRequestDescription | `String` | Special Request Description |
| 508 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 509 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 510 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 511 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 512 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 513 | splitfromreservationid | `Float` | Splitfromreservationid |
| 514 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 515 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 516 | stayRecordId | `Float` | Stay Record ID |
| 517 | suiteNumber | `String` | Suite Number |
| 518 | superSearchIndexText | `String` | Super Search Index Text |
| 519 | taRecordLocator | `String` | Ta Record Locator |
| 520 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 521 | taxNumberOfStays | `Float` | Tax No of Stays |
| 522 | taxType | `String` | Tax Type |
| 523 | taxTypeDescription | `String` | Tax Type Description |
| 524 | taxtypeid | `String` | Taxtypeid |
| 525 | tiad | `String` | Tiad |
| 526 | ticketNos | `String` | Ticket Nos |
| 527 | totalCostOfStay | `Float` | Total Cost of Stay |
| 528 | totalRevenue | `Float` | Total Revenue |
| 529 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 530 | totalRoomRate | `Float` | Total Room Rate |
| 531 | trackItGroups | `String` | Track It Groups |
| 532 | trackItTypes | `String` | Track It Types |
| 533 | transactionid | `Float` | Transactionid |
| 534 | travelAgentCity | `String` | Travel Agent Address. |
| 535 | travelAgentCountry | `String` | Travel Agent Country |
| 536 | travelAgentID | `Float` | Travel Agent ID |
| 537 | travelAgentName | `String` | Travel Agent Name |
| 538 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 539 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 540 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 541 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 542 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 543 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 544 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 545 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 546 | uDFC01 | `String` | UDFC01 |
| 547 | uDFC02 | `String` | UDFC02 |
| 548 | uDFC03 | `String` | UDFC03 |
| 549 | uDFC04 | `String` | UDFC04 |
| 550 | uDFC05 | `String` | UDFC05 |
| 551 | uDFC06 | `String` | UDFC06 |
| 552 | uDFC07 | `String` | UDFC07 |
| 553 | uDFC08 | `String` | UDFC08 |
| 554 | uDFC09 | `String` | UDFC09 |
| 555 | uDFC10 | `String` | UDFC10 |
| 556 | uDFC11 | `String` | UDFC11 |
| 557 | uDFC12 | `String` | UDFC12 |
| 558 | uDFC13 | `String` | UDFC13 |
| 559 | uDFC14 | `String` | UDFC14 |
| 560 | uDFC15 | `String` | UDFC15 |
| 561 | uDFC16 | `String` | UDFC16 |
| 562 | uDFC17 | `String` | UDFC17 |
| 563 | uDFC18 | `String` | UDFC18 |
| 564 | uDFC19 | `String` | UDFC19 |
| 565 | uDFC20 | `String` | UDFC20 |
| 566 | uDFC21 | `String` | UDFC21 |
| 567 | uDFC22 | `String` | UDFC22 |
| 568 | uDFC23 | `String` | UDFC23 |
| 569 | uDFC24 | `String` | UDFC24 |
| 570 | uDFC25 | `String` | UDFC25 |
| 571 | uDFC26 | `String` | UDFC26 |
| 572 | uDFC27 | `String` | UDFC27 |
| 573 | uDFC28 | `String` | UDFC28 |
| 574 | uDFC29 | `String` | UDFC29 |
| 575 | uDFC30 | `String` | UDFC30 |
| 576 | uDFC31 | `String` | UDFC31 |
| 577 | uDFC32 | `String` | UDFC32 |
| 578 | uDFC33 | `String` | UDFC33 |
| 579 | uDFC34 | `String` | UDFC34 |
| 580 | uDFC35 | `String` | UDFC35 |
| 581 | uDFC36 | `String` | UDFC36 |
| 582 | uDFC37 | `String` | UDFC37 |
| 583 | uDFC38 | `String` | UDFC38 |
| 584 | uDFC39 | `String` | UDFC39 |
| 585 | uDFC40 | `String` | UDFC40 |
| 586 | uDFD01 | `Date` | UDFD01 |
| 587 | uDFD02 | `Date` | UDFD02 |
| 588 | uDFD03 | `Date` | UDFD03 |
| 589 | uDFD04 | `Date` | UDFD04 |
| 590 | uDFD05 | `Date` | UDFD05 |
| 591 | uDFD06 | `Date` | UDFD06 |
| 592 | uDFD07 | `Date` | UDFD07 |
| 593 | uDFD08 | `Date` | UDFD08 |
| 594 | uDFD09 | `Date` | UDFD09 |
| 595 | uDFD10 | `Date` | UDFD10 |
| 596 | uDFD11 | `Date` | UDFD11 |
| 597 | uDFD12 | `Date` | UDFD12 |
| 598 | uDFD13 | `Date` | UDFD13 |
| 599 | uDFD14 | `Date` | UDFD14 |
| 600 | uDFD15 | `Date` | UDFD15 |
| 601 | uDFD16 | `Date` | UDFD16 |
| 602 | uDFD17 | `Date` | UDFD17 |
| 603 | uDFD18 | `Date` | UDFD18 |
| 604 | uDFD19 | `Date` | UDFD19 |
| 605 | uDFD20 | `Date` | UDFD20 |
| 606 | uDFN01 | `Float` | UDFN01 |
| 607 | uDFN02 | `Float` | UDFN02 |
| 608 | uDFN03 | `Float` | UDFN03 |
| 609 | uDFN04 | `Float` | UDFN04 |
| 610 | uDFN05 | `Float` | UDFN05 |
| 611 | uDFN06 | `Float` | UDFN06 |
| 612 | uDFN07 | `Float` | UDFN07 |
| 613 | uDFN08 | `Float` | UDFN08 |
| 614 | uDFN09 | `Float` | UDFN09 |
| 615 | uDFN10 | `Float` | UDFN10 |
| 616 | uDFN11 | `Float` | UDFN11 |
| 617 | uDFN12 | `Float` | UDFN12 |
| 618 | uDFN13 | `Float` | UDFN13 |
| 619 | uDFN14 | `Float` | UDFN14 |
| 620 | uDFN15 | `Float` | UDFN15 |
| 621 | uDFN16 | `Float` | UDFN16 |
| 622 | uDFN17 | `Float` | UDFN17 |
| 623 | uDFN18 | `Float` | UDFN18 |
| 624 | uDFN19 | `Float` | UDFN19 |
| 625 | uDFN20 | `Float` | UDFN20 |
| 626 | uDFN21 | `Float` | UDFN21 |
| 627 | uDFN22 | `Float` | UDFN22 |
| 628 | uDFN23 | `Float` | UDFN23 |
| 629 | uDFN24 | `Float` | UDFN24 |
| 630 | uDFN25 | `Float` | UDFN25 |
| 631 | uDFN26 | `Float` | UDFN26 |
| 632 | uDFN27 | `Float` | UDFN27 |
| 633 | uDFN28 | `Float` | UDFN28 |
| 634 | uDFN29 | `Float` | UDFN29 |
| 635 | uDFN30 | `Float` | UDFN30 |
| 636 | uDFN31 | `Float` | UDFN31 |
| 637 | uDFN32 | `Float` | UDFN32 |
| 638 | uDFN33 | `Float` | UDFN33 |
| 639 | uDFN34 | `Float` | UDFN34 |
| 640 | uDFN35 | `Float` | UDFN35 |
| 641 | uDFN36 | `Float` | UDFN36 |
| 642 | uDFN37 | `Float` | UDFN37 |
| 643 | uDFN38 | `Float` | UDFN38 |
| 644 | uDFN39 | `Float` | UDFN39 |
| 645 | uDFN40 | `Float` | UDFN40 |
| 646 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 647 | updateDate | `DateTime` | Update Date |
| 648 | updateDatetime | `DateTime` | Update Datetime |
| 649 | updateUser | `Float` | Update User |
| 650 | updatedBy | `String` | Updated By |
| 651 | updatedByDefaultResort | `String` | Updated By Default Property |
| 652 | updatedDate | `Date` | Updated Date |
| 653 | updatedTime | `String` | Updated Time |
| 654 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 655 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 656 | visaExpiryDate | `Date` | Visa Expiry Date |
| 657 | visaIssueDate | `Date` | Visa Issue Date |
| 658 | visaNumber | `String` | Visa Number |
| 659 | waitlistComment | `String` | Waitlist Comment |
| 660 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 661 | waitlistPriority | `String` | Waitlist Priority |
| 662 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 663 | waitlistReason | `String` | Waitlist Reason |
| 664 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 665 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 666 | waitlistreasonid | `String` | Waitlistreasonid |
| 667 | walkInYN | `String` | Walk-In YN |
| 668 | yieldableYn | `String` | Yieldable Y/N |
| 669 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingsReservationAccompanyingGuestDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | alternateEnvelopeGreeting | `String` | Alternate Envelope Greeting |
| 3 | alternateFirstName | `String` | Alternate First Name |
| 4 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 5 | alternateLastName | `String` | Alternate Last Name |
| 6 | alternateSalutation | `String` | Alternate Salutation |
| 7 | attachDateTime | `Date` | Attach Date Time |
| 8 | autoenrollMemberYN | `String` | Autoenroll Member YN |
| 9 | birthCountry | `String` | Country of birth. |
| 10 | birthDate | `Date` | Birth Date |
| 11 | birthDateStr | `String` | Birth Date Str |
| 12 | birthPlace | `String` | Place of birth. |
| 13 | cashBlInd | `String` | Cash Bl Ind |
| 14 | centralNationality | `String` | Central Nationality |
| 15 | centralNationalityDescription | `String` | Central Nationality Description |
| 16 | centralTitle | `String` | Central Title |
| 17 | clientID | `String` | Client ID |
| 18 | contactFlag | `String` | Contact Flag |
| 19 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 20 | detachDateTime | `Date` | Detach Date Time |
| 21 | detachedYN | `String` | Detached YN |
| 22 | email | `String` | Email |
| 23 | emailYN | `String` | Email YN |
| 24 | envelopeGreeting | `String` | Envelope Greeting |
| 25 | firstName | `String` | First Name |
| 26 | gender | `String` | Gender |
| 27 | guestPrivYN | `String` | Guest Priv YN |
| 28 | inactiveReason | `String` | Inactive Reason |
| 29 | inactiveReasonCode | `String` | Inactive Reason Code |
| 30 | jRNUpdateDate | `Date` | JRN Update Date |
| 31 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 32 | language | `String` | Language |
| 33 | languageDescription | `String` | Language Description |
| 34 | lastName | `String` | Last Name |
| 35 | mailActionCodes | `String` | Mail Action Codes |
| 36 | mailActionDesc | `String` | Mail Action Desc |
| 37 | mailList | `String` | Mail List |
| 38 | marketResearchYN | `String` | Market Research YN |
| 39 | markets | `String` | Markets |
| 40 | marketsDesc | `String` | Markets Desc |
| 41 | middleName | `String` | Middle Name |
| 42 | nameID | `Float` | Name ID |
| 43 | nationality | `String` | Nationality |
| 44 | nationalityDescription | `String` | Nationality Description |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 47 | phone | `String` | Phone no. |
| 48 | phoneYN | `String` | Phone YN |
| 49 | primaryKeyID | `Float` | Primary Key ID |
| 50 | profilePrivacyFlag | `String` | Profile Privacy Flag |
| 51 | property | `String` | Code to uniquely identify the Property |
| 52 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 53 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 54 | repInactiveReason | `String` | Rep Inactive Reason |
| 55 | repInactiveReasonCode | `String` | Rep Inactive Reason Code |
| 56 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 57 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 58 | repMarkets | `String` | Rep Markets |
| 59 | repMarketsDesc | `String` | Rep Markets Desc |
| 60 | repVIPName | `String` | Rep VIP Name |
| 61 | repVIPStatus | `String` | Rep VIP Status |
| 62 | reservationNameId | `Float` | Resv Name ID |
| 63 | restrictedRule | `String` | Restricted Rule |
| 64 | sMSYN | `String` | SMS YN |
| 65 | salutation | `String` | Salutation Greeting |
| 66 | tax1No | `String` | Tax1 No |
| 67 | tax2No | `String` | Tax2 No |
| 68 | thirdPartyYN | `String` | Third Party YN |
| 69 | title | `String` | Title |
| 70 | uDFC01 | `String` | UDFC01 |
| 71 | uDFC02 | `String` | UDFC02 |
| 72 | uDFC03 | `String` | UDFC03 |
| 73 | uDFC04 | `String` | UDFC04 |
| 74 | uDFC05 | `String` | UDFC05 |
| 75 | uDFC06 | `String` | UDFC06 |
| 76 | uDFC07 | `String` | UDFC07 |
| 77 | uDFC08 | `String` | UDFC08 |
| 78 | uDFC09 | `String` | UDFC09 |
| 79 | uDFC10 | `String` | UDFC10 |
| 80 | uDFC11 | `String` | UDFC11 |
| 81 | uDFC12 | `String` | UDFC12 |
| 82 | uDFC13 | `String` | UDFC13 |
| 83 | uDFC14 | `String` | UDFC14 |
| 84 | uDFC15 | `String` | UDFC15 |
| 85 | uDFC16 | `String` | UDFC16 |
| 86 | uDFC17 | `String` | UDFC17 |
| 87 | uDFC18 | `String` | UDFC18 |
| 88 | uDFC19 | `String` | UDFC19 |
| 89 | uDFC20 | `String` | UDFC20 |
| 90 | uDFC21 | `String` | UDFC21 |
| 91 | uDFC22 | `String` | UDFC22 |
| 92 | uDFC23 | `String` | UDFC23 |
| 93 | uDFC24 | `String` | UDFC24 |
| 94 | uDFC25 | `String` | UDFC25 |
| 95 | uDFC26 | `String` | UDFC26 |
| 96 | uDFC27 | `String` | UDFC27 |
| 97 | uDFC28 | `String` | UDFC28 |
| 98 | uDFC29 | `String` | UDFC29 |
| 99 | uDFC30 | `String` | UDFC30 |
| 100 | uDFC31 | `String` | UDFC31 |
| 101 | uDFC32 | `String` | UDFC32 |
| 102 | uDFC33 | `String` | UDFC33 |
| 103 | uDFC34 | `String` | UDFC34 |
| 104 | uDFC35 | `String` | UDFC35 |
| 105 | uDFC36 | `String` | UDFC36 |
| 106 | uDFC37 | `String` | UDFC37 |
| 107 | uDFC38 | `String` | UDFC38 |
| 108 | uDFC39 | `String` | UDFC39 |
| 109 | uDFC40 | `String` | UDFC40 |
| 110 | uDFD01 | `Date` | UDFD01 |
| 111 | uDFD02 | `Date` | UDFD02 |
| 112 | uDFD03 | `Date` | UDFD03 |
| 113 | uDFD04 | `Date` | UDFD04 |
| 114 | uDFD05 | `Date` | UDFD05 |
| 115 | uDFD06 | `Date` | UDFD06 |
| 116 | uDFD07 | `Date` | UDFD07 |
| 117 | uDFD08 | `Date` | UDFD08 |
| 118 | uDFD09 | `Date` | UDFD09 |
| 119 | uDFD10 | `Date` | UDFD10 |
| 120 | uDFD11 | `Date` | UDFD11 |
| 121 | uDFD12 | `Date` | UDFD12 |
| 122 | uDFD13 | `Date` | UDFD13 |
| 123 | uDFD14 | `Date` | UDFD14 |
| 124 | uDFD15 | `Date` | UDFD15 |
| 125 | uDFD16 | `Date` | UDFD16 |
| 126 | uDFD17 | `Date` | UDFD17 |
| 127 | uDFD18 | `Date` | UDFD18 |
| 128 | uDFD19 | `Date` | UDFD19 |
| 129 | uDFD20 | `Date` | UDFD20 |
| 130 | uDFN01 | `Float` | UDFN01 |
| 131 | uDFN02 | `Float` | UDFN02 |
| 132 | uDFN03 | `Float` | UDFN03 |
| 133 | uDFN04 | `Float` | UDFN04 |
| 134 | uDFN05 | `Float` | UDFN05 |
| 135 | uDFN06 | `Float` | UDFN06 |
| 136 | uDFN07 | `Float` | UDFN07 |
| 137 | uDFN08 | `Float` | UDFN08 |
| 138 | uDFN09 | `Float` | UDFN09 |
| 139 | uDFN10 | `Float` | UDFN10 |
| 140 | uDFN11 | `Float` | UDFN11 |
| 141 | uDFN12 | `Float` | UDFN12 |
| 142 | uDFN13 | `Float` | UDFN13 |
| 143 | uDFN14 | `Float` | UDFN14 |
| 144 | uDFN15 | `Float` | UDFN15 |
| 145 | uDFN16 | `Float` | UDFN16 |
| 146 | uDFN17 | `Float` | UDFN17 |
| 147 | uDFN18 | `Float` | UDFN18 |
| 148 | uDFN19 | `Float` | UDFN19 |
| 149 | uDFN20 | `Float` | UDFN20 |
| 150 | uDFN21 | `Float` | UDFN21 |
| 151 | uDFN22 | `Float` | UDFN22 |
| 152 | uDFN23 | `Float` | UDFN23 |
| 153 | uDFN24 | `Float` | UDFN24 |
| 154 | uDFN25 | `Float` | UDFN25 |
| 155 | uDFN26 | `Float` | UDFN26 |
| 156 | uDFN27 | `Float` | UDFN27 |
| 157 | uDFN28 | `Float` | UDFN28 |
| 158 | uDFN29 | `Float` | UDFN29 |
| 159 | uDFN30 | `Float` | UDFN30 |
| 160 | uDFN31 | `Float` | UDFN31 |
| 161 | uDFN32 | `Float` | UDFN32 |
| 162 | uDFN33 | `Float` | UDFN33 |
| 163 | uDFN34 | `Float` | UDFN34 |
| 164 | uDFN35 | `Float` | UDFN35 |
| 165 | uDFN36 | `Float` | UDFN36 |
| 166 | uDFN37 | `Float` | UDFN37 |
| 167 | uDFN38 | `Float` | UDFN38 |
| 168 | uDFN39 | `Float` | UDFN39 |
| 169 | uDFN40 | `Float` | UDFN40 |
| 170 | vIPName | `String` | VIP Name |
| 171 | vIPStatus | `String` | VIP Status |

[⬆ Back to Query](#query)

---

### BookingsReservationChannelDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralOriginCode | `String` | Central Origin Code |
| 4 | centralOriginDescription | `String` | Central Origin Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | channelid | `String` | Channelid |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | displayColor | `String` | Display Color |
| 12 | entityName | `String` | Entity Name |
| 13 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | internalDeletedflag | `String` | Deleted Flag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | originCode | `String` | Origin Code |
| 25 | originDescription | `String` | Origin Description |
| 26 | originDisplaySequence | `Float` | Origin Display Sequence |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationExternalReferencesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | deletedFlag | `String` | Deleted Flag |
| 3 | extCancellationNo | `String` | Cancellation number received from the external system. |
| 4 | externalReferenceLegNumber | `Float` | Reservation leg number for itinerary reservations. |
| 5 | externalReferenceNumber | `String` | External Reference Number |
| 6 | externalReferenceType | `String` | Type of external reference depending from what external system the number was passed. |
| 7 | externalStatus | `String` | Status of the reservation in the external system 'C' -> Cancelled value NULL or 'A' -> 'Active'. |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | manualYn | `String` | Manual Y/N |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Code to uniquely identify the Property |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | reservationNameId | `Float` | Resv Name ID |
| 20 | revisionToken | `String` | Indicates the revision of information provided by an external system that this record corresponds to. This will be used to keep information consistent between OPERA and the external system. |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |
| 23 | upperExternalReference | `String` | External reference stored in upper case. |

[⬆ Back to Query](#query)

---

### BookingsReservationFixedChargesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `Float` | Account Code |
| 2 | accountid | `Float` | Accountid |
| 3 | amountOrPercentage | `Float` | Amount or Percentage |
| 4 | amountOrPercentageFlag | `String` | Percentage / Amount flag. Allowed values: AMOUNT PERCENT. |
| 5 | articleId | `Float` | Article ID |
| 6 | beginDateNullable | `Date` | The date from which the charge is effective (null allowed). |
| 7 | businessDate | `Date` | Business Date |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cPrice | `Float` | Central Price |
| 11 | centralTransactionCode | `String` | Central Transaction Code |
| 12 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | daytoexecute | `String` | Daytoexecute |
| 15 | deletedFlag | `String` | Deleted Flag |
| 16 | endDate | `Date` | End Date |
| 17 | endDateNullable | `Date` | The date from which the charge is not effective (null allowed). |
| 18 | fixedChargesId | `Float` | Unique number to identify the entry. |
| 19 | fixedchargespmsref | `Float` | Fixedchargespmsref |
| 20 | frequency | `String` | Frequency |
| 21 | insertDate | `DateTime` | Insert Date |
| 22 | insertUser | `Float` | Insert User |
| 23 | insertUserName | `String` | The name of the user who created the record. |
| 24 | internalArticleid | `Float` | Articleid |
| 25 | internalFixedchargesid | `Float` | Fixedchargesid |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | locationID | `String` | Internal ID to uniquely identify the Property |
| 29 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 30 | percentage | `Float` | Percentage |
| 31 | price | `Float` | Price |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | property | `String` | Code to uniquely identify the Property |
| 34 | quantity | `Float` | Quantity |
| 35 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 36 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 37 | reservationNameId | `Float` | Resv Name ID |
| 38 | reservationid | `Float` | Reservationid |
| 39 | resvenddate | `Date` | Resvenddate |
| 40 | roomnights | `Float` | Roomnights |
| 41 | supplement | `String` | Supplement |
| 42 | transactionCode | `String` | Rate transaction code |
| 43 | transactionCodeDescription | `String` | Transaction Code Description |
| 44 | transactionCodeGroup | `Float` | Transaction Code Group |
| 45 | transactionCodeSubGroup | `Float` | Transaction Code Sub-Group |
| 46 | transactionCodeType | `String` | Transaction Code Type |
| 47 | transcodeid | `String` | Transcodeid |
| 48 | updateUser | `Float` | Update User |
| 49 | updatedate | `Date` | Update Date |
| 50 | yearlyfixedchargedate | `Date` | Yearlyfixedchargedate |

[⬆ Back to Query](#query)

---

### BookingsReservationGuestReservationMessagesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | deletedFlag | `String` | Deleted Flag |
| 3 | description | `String` | Description |
| 4 | guestMessage | `String` | Guest Message |
| 5 | jRNUpdateDate | `Date` | JRN Update Date |
| 6 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 7 | locationID | `String` | Internal ID to uniquely identify the Property |
| 8 | messagePrintedDate | `Date` | Message Printed Date |
| 9 | msgid | `Float` | Msgid |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | printMessageYN | `String` | Print Message YN |
| 13 | printedStatus | `String` | Message print status |
| 14 | property | `String` | Code to uniquely identify the Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | receivedBy | `String` | User who received message |
| 18 | recipientName | `String` | Recipient Name |
| 19 | reservationNameId | `Float` | Resv Name ID |
| 20 | sentToRoomYN | `String` | Indicates whether message has been sent to the guest?s room. |
| 21 | smsSentBy | `String` | Last user that sent a QRUSH SMS Text message. |
| 22 | statusDate | `Date` | Date when the status was changed |
| 23 | statusFlag | `String` | Status Flag |
| 24 | textSentDate | `Date` | Last Date when a QRUSH SMS Text message was sent. |
| 25 | textYN | `String` | Text YN |

[⬆ Back to Query](#query)

---

### BookingsReservationLocatorsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | beginDate | `Date` | Begin Date |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | endDate | `Date` | End Date |
| 5 | enteredBy | `String` | User who entered the trace |
| 6 | enteredOn | `Date` | User who entered the locator |
| 7 | fromDatetime | `Date` | From Datetime |
| 8 | fromTime | `String` | Start time of the update process for the table. |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | locationID | `String` | Internal ID to uniquely identify the Property |
| 12 | locationText | `String` | Location Text |
| 13 | locatorId | `Float` | Internal locator id |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Code to uniquely identify the Property |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | reservationNameId | `Float` | Resv Name ID |
| 20 | toDatetime | `Date` | To Datetime |
| 21 | toTime | `String` | End time of the update process for the table. |

[⬆ Back to Query](#query)

---

### BookingsReservationMarketDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralMarketCode | `String` | Central Market Code |
| 2 | centralMarketDescription | `String` | Central Market Description |
| 3 | centralMarketGroupCode | `String` | Central Market Group Code |
| 4 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | displayColor | `String` | Display Color |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveYN | `String` | Inactive YN |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | internalDeletedflag | `String` | Deleted Flag |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | locationID | `String` | Internal ID to uniquely identify the Property |
| 16 | marketCode | `String` | Market Code |
| 17 | marketDescription | `String` | Market Description |
| 18 | marketDisplaySequence | `Float` | Market Display Sequence |
| 19 | marketGroupCode | `String` | Market group attached to the market code |
| 20 | marketGroupDescription | `String` | Market Group Description |
| 21 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 22 | marketgroupid | `String` | Marketgroupid |
| 23 | marketid | `String` | Marketid |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | printGroup | `String` | Print Group for Nationality Report |
| 27 | property | `String` | Property |
| 28 | repItem | `String` | Reporting Item |
| 29 | repItemName | `String` | Reporting Item Name |
| 30 | repItemOrderby | `Float` | Reporting Item Orderby |
| 31 | repMarketSellSequence | `Float` | Reporting Market Sell Sequence |
| 32 | repParentSellSequence | `Float` | Reporting Parent Sell Sequence |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | scOrderby | `Float` | Sc Orderby |
| 37 | trxCode | `String` | Transaction Code |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationProfileAllInformationDetailsType

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
| 9 | accountSource | `String` | Used in S&C Module. |
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
| 25 | alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
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
| 39 | businessSegment | `String` | Used in S&C Module. |
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
| 87 | contactYN | `String` | Used in S&C Module. |
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
| 107 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 108 | debtorName | `String` | Debtor Name |
| 109 | decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| 110 | defaultKeyword | `String` | The keyword to search on. |
| 111 | deletedFlag | `String` | Deleted Flag |
| 112 | department | `String` | Used in S&C Module. |
| 113 | deptId | `String` | Used in S&C Module. |
| 114 | description | `String` | Used in QMS Module |
| 115 | directBillBatchType | `String` | Direct Bill Batch Type |
| 116 | displayName | `String` | Display Name |
| 117 | downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| 118 | downloadResort | `String` | REsort name which has downloaded on the laptop. |
| 119 | downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| 120 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 121 | eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| 122 | email | `String` | The phone number for this record |
| 123 | emailYN | `String` | Email YN |
| 124 | envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| 125 | externalDisplayName | `String` | External Display Name |
| 126 | externalFirstName | `String` | The first name of an individual. |
| 127 | externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| 128 | externalName | `String` | The last name of the individual profile. |
| 129 | externalReferenceRequ | `String` | Not Used. |
| 130 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 131 | fMembershipCardNumbers | `String` | Membership Card Number. |
| 132 | fMembershipClassDesc | `String` | Descripion of membership class |
| 133 | fMembershipClasses | `String` | F Membership Classes |
| 134 | fMembershipCodes | `String` | F Membership Codes |
| 135 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 136 | fMembershipIds | `String` | Primary Key for this table. |
| 137 | fMembershipType | `String` | Type of the Membership. |
| 138 | fSubscriptionDb | `String` | The ID of the external Database. |
| 139 | fSubscriptionYn | `String` | The ID of the external Database. |
| 140 | faxNumber | `String` | The phone number for this record |
| 141 | firstName | `String` | The first name of an individual name. |
| 142 | firstNameAlternate | `String` | First Name Alternate |
| 143 | firstNameIncognito | `String` | The keyword to search on. |
| 144 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 145 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 146 | gDSTransactionNo | `String` | Not used. |
| 147 | gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| 148 | geographicRegion | `String` | Not used. |
| 149 | guestClassification | `String` | Not used. |
| 150 | guestCountry | `String` | Country name. |
| 151 | guestCurrencyCode | `String` | Currency code for the Commission payment. |
| 152 | guestLanguageCode | `String` | Description for each language code. |
| 153 | guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 154 | guestMiddleName | `String` | The middle name of this individual. |
| 155 | guestNameSuffix | `String` | Guest Name Suffix |
| 156 | guestPrivilegeYN | `String` | Guest Privilege YN |
| 157 | guestTitleCode | `String` | The title of the individual. |
| 158 | hasRequestedMailYN | `String` | Has Requested Mail YN |
| 159 | historyYN | `String` | Keep guest in history Y/N |
| 160 | holdCode | `String` | Hold code for the Commission handling purposes. |
| 161 | iataConsortia | `String` | Consortia for the IATA number. |
| 162 | idCountry | `String` | The country where ID was issued |
| 163 | idDate | `Date` | Issued date of Identification |
| 164 | idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| 165 | idPlace | `String` | The place where ID was issued |
| 166 | idType | `String` | Identification Type. Eg Passport Driving License etc |
| 167 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 168 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 169 | inactiveFlag | `String` | Inactive Flag |
| 170 | inactiveReason | `String` | Reason why record was inactivated. |
| 171 | inactiveReasonDescription | `String` | The description of this value. |
| 172 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 173 | indexName | `String` | Index Name |
| 174 | industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| 175 | industryDesc | `String` | The description of this value. |
| 176 | influence | `String` | Used in S&C Module. |
| 177 | influenceDesc | `String` | The description of this value. |
| 178 | interest | `String` | Interest Code. |
| 179 | internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| 180 | internalDeletedflag | `String` | Deleted Flag |
| 181 | internalInactiveflag | `String` | Inactive Flag |
| 182 | internalOrganizationId | `Float` | Organization ID |
| 183 | jRNUpdateDate | `Date` | JRN Update Date |
| 184 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 185 | languageCode | `String` | Primary language used for the profile. |
| 186 | laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| 187 | lastGroup | `String` | Last Group |
| 188 | lastNameAlternate | `String` | Last Name Alternate |
| 189 | lastNameIncognito | `String` | The keyword to search on. |
| 190 | lastRate | `Float` | Last Rate |
| 191 | lastRateCode | `String` | Last Rate Code |
| 192 | lastRoom | `String` | The room that is booked for this reservation leg. |
| 193 | lastRoomProperty | `String` | Last Room Property |
| 194 | lastSource | `String` | Last Source |
| 195 | lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| 196 | lastUpdatedResort | `String` | Last property that updated this record. |
| 197 | legalCompany | `String` | The legal company name for this company. |
| 198 | letterGreeting | `String` | Used in S&C Module. |
| 199 | mailActionDescription | `String` | The description of this value. |
| 200 | mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| 201 | mailType | `String` | The type of mail this user should be sent. |
| 202 | mailingActionCode | `String` | Mailing action codes. |
| 203 | marketResearchYN | `String` | Market Research YN |
| 204 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 205 | nameTaxType | `String` | Not used. |
| 206 | nameType | `String` | The type of Profile. |
| 207 | nameTypeDescription | `String` | The description of this value. |
| 208 | name2 | `String` | Not Used. |
| 209 | name3 | `String` | Not used. |
| 210 | nationality | `String` | Nationality |
| 211 | nationalityCode | `String` | Nationality of the individual. |
| 212 | negotiatedRateCodes | `String` | The rate code for which this record applies. |
| 213 | nextStay | `Date` | This is a begin_date  with no  time component. |
| 214 | nickname | `String` | The nickname of this individual. |
| 215 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 216 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 217 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 218 | phone | `String` | The phone number for this record |
| 219 | phoneWeb | `String` | The phone number for this record |
| 220 | phoneYN | `String` | Phone YN |
| 221 | postalCode | `String` | The postal code of this address. |
| 222 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 223 | preferredRoomNo | `String` | Preferred Room Number |
| 224 | primaryAddressId | `Float` | Not used. |
| 225 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 226 | primaryNameId | `Float` | Not Used. |
| 227 | primaryOwner | `String` | Primary Owner |
| 228 | primaryOwnerCode | `String` | Primary Owner Code |
| 229 | primaryPhoneId | `Float` | Not used. |
| 230 | priority | `String` | Priority of the account |
| 231 | priorityDesc | `String` | The description of this value. |
| 232 | privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 233 | productInterest | `String` | Preference Code. Part of the Primary Key. |
| 234 | profession | `String` | The profession of the Individual |
| 235 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 236 | profileId | `Float` | The primary key for this table. |
| 237 | profileType | `String` | The type of Profile. |
| 238 | propertyRegistered | `String` | Resort for which Job is registered. |
| 239 | protected | `String` | Protected |
| 240 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 241 | rateStructure | `String` | The default rate structure for this name. |
| 242 | region | `String` | The region for this name. |
| 243 | regionid | `String` | The region for this name. |
| 244 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 245 | repAccountsource | `String` | Reporting Accountsource |
| 246 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 247 | repCompetitionCode | `String` | Reporting Competition Code |
| 248 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 249 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 250 | repIndustryCode | `String` | Reporting Industry Code |
| 251 | repIndustryDescription | `String` | Reporting Industry Desc |
| 252 | repInfluence | `String` | Reporting Influence |
| 253 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 254 | repNameType | `String` | Reporting Name Type |
| 255 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 256 | repNationalityCode | `String` | Rep Nationality Code |
| 257 | repNationalityDescription | `String` | Rep Nationality Description |
| 258 | repPriorityDescription | `String` | Reporting Priority Desc |
| 259 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 260 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 261 | repScope | `String` | Reporting Scope |
| 262 | repScopeCity | `String` | Reporting Scope City |
| 263 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 264 | repScopeDescription | `String` | Reporting Scope Desc |
| 265 | repStateDescription | `String` | Reporting State Desc |
| 266 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 267 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 268 | repTitleName | `String` | Reporting Title Name |
| 269 | repeatGuestId | `String` | The primary membership # for this guest. |
| 270 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 271 | requestType | `String` | This column store the Name of the Company Profiles. |
| 272 | restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| 273 | restrictedRule | `String` | The description of this value. |
| 274 | resvContact | `String` | Reservation Contact person. |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomsPotential | `String` | Potential no of rooms per year for a account |
| 278 | roomsPotentialDesc | `String` | The description of this value. |
| 279 | sMSYN | `String` | Use this alert to text a notification. |
| 280 | salutation | `String` | Salutation Greeting |
| 281 | scope | `String` | Scope of the account |
| 282 | scopeCity | `String` | Scope City |
| 283 | scopeCityDesc | `String` | The description of this value. |
| 284 | scopeDesc | `String` | The description of this value. |
| 285 | searchName | `String` | The Uppercase value of Last or Company. |
| 286 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 287 | sfirst | `String` | Uppercase value of First Name. |
| 288 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 289 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 290 | srepCode | `String` | Used in QMS Module |
| 291 | state | `String` | The state of this address. |
| 292 | stateCode | `String` | State Code |
| 293 | stateDescription | `String` | Description of the state. |
| 294 | summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| 295 | summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| 296 | superSearchIndexText | `String` | Used in Oracle Text Index. |
| 297 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 298 | taxCategory | `String` | Tax Category |
| 299 | taxExemptStatus | `String` | Not used. |
| 300 | taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| 301 | taxID2 | `String` | Tax No |
| 302 | taxOffice | `String` | Tax Office Name |
| 303 | taxType | `String` | Tax Type |
| 304 | territory | `String` | TERRITORY of  a account |
| 305 | territoryDesc | `String` | The description of this value. |
| 306 | thirdPartyYN | `String` | Third Party YN |
| 307 | titleAlternate | `String` | Title Alternate |
| 308 | titleName | `String` | The description of this value. |
| 309 | titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| 310 | totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| 311 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 312 | traceCode | `String` | Code to Trace a record for all Triggered actions. |
| 313 | tracecodeDesc | `String` | Description |
| 314 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 315 | uDFC01 | `String` | User defined character field. |
| 316 | uDFC02 | `String` | User defined character field. |
| 317 | uDFC03 | `String` | User defined character field. |
| 318 | uDFC04 | `String` | User defined character field. |
| 319 | uDFC05 | `String` | User defined character field. |
| 320 | uDFC06 | `String` | User defined character field. |
| 321 | uDFC07 | `String` | User defined character field. |
| 322 | uDFC08 | `String` | User defined character field. |
| 323 | uDFC09 | `String` | User defined character field. |
| 324 | uDFC10 | `String` | User defined character field. |
| 325 | uDFC11 | `String` | User defined character field. |
| 326 | uDFC12 | `String` | User defined character field. |
| 327 | uDFC13 | `String` | User defined character field. |
| 328 | uDFC14 | `String` | User defined character field. |
| 329 | uDFC15 | `String` | User defined character field. |
| 330 | uDFC16 | `String` | User defined character field. |
| 331 | uDFC17 | `String` | User defined character field. |
| 332 | uDFC18 | `String` | User defined character field. |
| 333 | uDFC19 | `String` | User defined character field. |
| 334 | uDFC20 | `String` | User defined character field. |
| 335 | uDFC21 | `String` | User defined character field. |
| 336 | uDFC22 | `String` | User defined character field. |
| 337 | uDFC23 | `String` | User defined character field. |
| 338 | uDFC24 | `String` | User defined character field. |
| 339 | uDFC25 | `String` | User defined character field. |
| 340 | uDFC26 | `String` | User defined character field. |
| 341 | uDFC27 | `String` | User defined character field. |
| 342 | uDFC28 | `String` | User defined character field. |
| 343 | uDFC29 | `String` | User defined character field. |
| 344 | uDFC30 | `String` | User defined character field. |
| 345 | uDFC31 | `String` | User defined character field. |
| 346 | uDFC32 | `String` | User defined character field. |
| 347 | uDFC33 | `String` | User defined character field. |
| 348 | uDFC34 | `String` | User defined character field. |
| 349 | uDFC35 | `String` | User defined character field. |
| 350 | uDFC36 | `String` | User defined character field. |
| 351 | uDFC37 | `String` | User defined character field. |
| 352 | uDFC38 | `String` | User defined character field. |
| 353 | uDFC39 | `String` | User defined character field. |
| 354 | uDFC40 | `String` | User defined character field. |
| 355 | uDFD01 | `Date` | User defined date field. |
| 356 | uDFD02 | `Date` | User defined date field. |
| 357 | uDFD03 | `Date` | User defined date field. |
| 358 | uDFD04 | `Date` | User defined date field. |
| 359 | uDFD05 | `Date` | User defined date field. |
| 360 | uDFD06 | `Date` | User defined date field. |
| 361 | uDFD07 | `Date` | User defined date field. |
| 362 | uDFD08 | `Date` | User defined date field. |
| 363 | uDFD09 | `Date` | User defined date field. |
| 364 | uDFD10 | `Date` | User defined date field. |
| 365 | uDFD11 | `Date` | User defined date field. |
| 366 | uDFD12 | `Date` | User defined date field. |
| 367 | uDFD13 | `Date` | User defined date field. |
| 368 | uDFD14 | `Date` | User defined date field. |
| 369 | uDFD15 | `Date` | User defined date field. |
| 370 | uDFD16 | `Date` | User defined date field. |
| 371 | uDFD17 | `Date` | User defined date field. |
| 372 | uDFD18 | `Date` | User defined date field. |
| 373 | uDFD19 | `Date` | User defined date field. |
| 374 | uDFD20 | `Date` | User defined date field. |
| 375 | uDFN01 | `Float` | User defined number field. |
| 376 | uDFN02 | `Float` | User defined number field. |
| 377 | uDFN03 | `Float` | User defined number field. |
| 378 | uDFN04 | `Float` | User defined number field. |
| 379 | uDFN05 | `Float` | User defined number field. |
| 380 | uDFN06 | `Float` | User defined number field. |
| 381 | uDFN07 | `Float` | User defined number field. |
| 382 | uDFN08 | `Float` | User defined number field. |
| 383 | uDFN09 | `Float` | User defined number field. |
| 384 | uDFN10 | `Float` | User defined number field. |
| 385 | uDFN11 | `Float` | User defined number field. |
| 386 | uDFN12 | `Float` | User defined number field. |
| 387 | uDFN13 | `Float` | User defined number field. |
| 388 | uDFN14 | `Float` | User defined number field. |
| 389 | uDFN15 | `Float` | User defined number field. |
| 390 | uDFN16 | `Float` | User defined number field. |
| 391 | uDFN17 | `Float` | User defined number field. |
| 392 | uDFN18 | `Float` | User defined number field. |
| 393 | uDFN19 | `Float` | User defined number field. |
| 394 | uDFN20 | `Float` | User defined number field. |
| 395 | uDFN21 | `Float` | User defined number field. |
| 396 | uDFN22 | `Float` | User defined number field. |
| 397 | uDFN23 | `Float` | User defined number field. |
| 398 | uDFN24 | `Float` | User defined number field. |
| 399 | uDFN25 | `Float` | User defined number field. |
| 400 | uDFN26 | `Float` | User defined number field. |
| 401 | uDFN27 | `Float` | User defined number field. |
| 402 | uDFN28 | `Float` | User defined number field. |
| 403 | uDFN29 | `Float` | User defined number field. |
| 404 | uDFN30 | `Float` | User defined number field. |
| 405 | uDFN31 | `Float` | User defined number field. |
| 406 | uDFN32 | `Float` | User defined number field. |
| 407 | uDFN33 | `Float` | User defined number field. |
| 408 | uDFN34 | `Float` | User defined number field. |
| 409 | uDFN35 | `Float` | User defined number field. |
| 410 | uDFN36 | `Float` | User defined number field. |
| 411 | uDFN37 | `Float` | User defined number field. |
| 412 | uDFN38 | `Float` | User defined number field. |
| 413 | uDFN39 | `Float` | User defined number field. |
| 414 | uDFN40 | `Float` | User defined number field. |
| 415 | updateDate | `DateTime` | The date the record was modified |
| 416 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 417 | updateUser | `String` | The user that modified the record |
| 418 | uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| 419 | vIPCode | `String` | VIP Status of the Individual. |
| 420 | vIPDescription | `String` | The description of this value. |
| 421 | vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| 422 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 423 | vipAuthorization | `String` | Not Used. |
| 424 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 425 | xdisplayName | `String` | Xdisplay Name |
| 426 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationProfileAccountsCompanyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `Date` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | referenceCurrency | `String` | Reference Currency |
| 170 | repInfluence | `String` | Reporting Influence |
| 171 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 172 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 173 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 174 | repNationalityCode | `String` | Reporting Nationality Code |
| 175 | repNationalityDescription | `String` | Reporting Nationality Description |
| 176 | repStateDescription | `String` | Reporting State Desc |
| 177 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 178 | repTitleName | `String` | Reporting Title Name |
| 179 | repVIPName | `String` | Reporting Vip Name |
| 180 | repVIPStatus | `String` | Reporting Vip Status |
| 181 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 182 | resortRegistered | `String` | Resort for which Job is registered. |
| 183 | restricted | `String` | Restricted |
| 184 | restrictedRule | `String` | Restricted Rule |
| 185 | salutation | `String` | Salutation Greeting |
| 186 | scope | `String` | Scope |
| 187 | scopeCity | `String` | Scope City |
| 188 | scopeCityDecription | `String` | Scope City Decription |
| 189 | scopeDescription | `String` | Scope Description |
| 190 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 191 | sfirst | `String` | Uppercase value of First Name. |
| 192 | state | `String` | State |
| 193 | stateCode | `String` | State Code |
| 194 | stateDesc | `String` | State Description of the Guest of Payee |
| 195 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 196 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 197 | tax1No | `String` | Tax1 Number |
| 198 | tax2No | `String` | Tax2 Number |
| 199 | taxCategory | `String` | Tax Category |
| 200 | taxType | `String` | Tax Type |
| 201 | taxTypeDescription | `String` | Tax Type Description |
| 202 | territory | `String` | Territory |
| 203 | territoryDescription | `String` | Territory Description |
| 204 | thirdPartyYn | `String` | Third Party Y/N |
| 205 | traceCode | `String` | Trace Code |
| 206 | traceCodeDescription | `String` | Trace Code Description |
| 207 | uDFC01 | `String` | UDFC01 |
| 208 | uDFC02 | `String` | UDFC02 |
| 209 | uDFC03 | `String` | UDFC03 |
| 210 | uDFC04 | `String` | UDFC04 |
| 211 | uDFC05 | `String` | UDFC05 |
| 212 | uDFC06 | `String` | UDFC06 |
| 213 | uDFC07 | `String` | UDFC07 |
| 214 | uDFC08 | `String` | UDFC08 |
| 215 | uDFC09 | `String` | UDFC09 |
| 216 | uDFC10 | `String` | UDFC10 |
| 217 | uDFC11 | `String` | UDFC11 |
| 218 | uDFC12 | `String` | UDFC12 |
| 219 | uDFC13 | `String` | UDFC13 |
| 220 | uDFC14 | `String` | UDFC14 |
| 221 | uDFC15 | `String` | UDFC15 |
| 222 | uDFC16 | `String` | UDFC16 |
| 223 | uDFC17 | `String` | UDFC17 |
| 224 | uDFC18 | `String` | UDFC18 |
| 225 | uDFC19 | `String` | UDFC19 |
| 226 | uDFC20 | `String` | UDFC20 |
| 227 | uDFC21 | `String` | UDFC21 |
| 228 | uDFC22 | `String` | UDFC22 |
| 229 | uDFC23 | `String` | UDFC23 |
| 230 | uDFC24 | `String` | UDFC24 |
| 231 | uDFC25 | `String` | UDFC25 |
| 232 | uDFC26 | `String` | UDFC26 |
| 233 | uDFC27 | `String` | UDFC27 |
| 234 | uDFC28 | `String` | UDFC28 |
| 235 | uDFC29 | `String` | UDFC29 |
| 236 | uDFC30 | `String` | UDFC30 |
| 237 | uDFC31 | `String` | UDFC31 |
| 238 | uDFC32 | `String` | UDFC32 |
| 239 | uDFC33 | `String` | UDFC33 |
| 240 | uDFC34 | `String` | UDFC34 |
| 241 | uDFC35 | `String` | UDFC35 |
| 242 | uDFC36 | `String` | UDFC36 |
| 243 | uDFC37 | `String` | UDFC37 |
| 244 | uDFC38 | `String` | UDFC38 |
| 245 | uDFC39 | `String` | UDFC39 |
| 246 | uDFC40 | `String` | UDFC40 |
| 247 | uDFD01 | `Date` | UDFD01 |
| 248 | uDFD02 | `Date` | UDFD02 |
| 249 | uDFD03 | `Date` | UDFD03 |
| 250 | uDFD04 | `Date` | UDFD04 |
| 251 | uDFD05 | `Date` | UDFD05 |
| 252 | uDFD06 | `Date` | UDFD06 |
| 253 | uDFD07 | `Date` | UDFD07 |
| 254 | uDFD08 | `Date` | UDFD08 |
| 255 | uDFD09 | `Date` | UDFD09 |
| 256 | uDFD10 | `Date` | UDFD10 |
| 257 | uDFD11 | `Date` | UDFD11 |
| 258 | uDFD12 | `Date` | UDFD12 |
| 259 | uDFD13 | `Date` | UDFD13 |
| 260 | uDFD14 | `Date` | UDFD14 |
| 261 | uDFD15 | `Date` | UDFD15 |
| 262 | uDFD16 | `Date` | UDFD16 |
| 263 | uDFD17 | `Date` | UDFD17 |
| 264 | uDFD18 | `Date` | UDFD18 |
| 265 | uDFD19 | `Date` | UDFD19 |
| 266 | uDFD20 | `Date` | UDFD20 |
| 267 | uDFN01 | `Float` | UDFN01 |
| 268 | uDFN02 | `Float` | UDFN02 |
| 269 | uDFN03 | `Float` | UDFN03 |
| 270 | uDFN04 | `Float` | UDFN04 |
| 271 | uDFN05 | `Float` | UDFN05 |
| 272 | uDFN06 | `Float` | UDFN06 |
| 273 | uDFN07 | `Float` | UDFN07 |
| 274 | uDFN08 | `Float` | UDFN08 |
| 275 | uDFN09 | `Float` | UDFN09 |
| 276 | uDFN10 | `Float` | UDFN10 |
| 277 | uDFN11 | `Float` | UDFN11 |
| 278 | uDFN12 | `Float` | UDFN12 |
| 279 | uDFN13 | `Float` | UDFN13 |
| 280 | uDFN14 | `Float` | UDFN14 |
| 281 | uDFN15 | `Float` | UDFN15 |
| 282 | uDFN16 | `Float` | UDFN16 |
| 283 | uDFN17 | `Float` | UDFN17 |
| 284 | uDFN18 | `Float` | UDFN18 |
| 285 | uDFN19 | `Float` | UDFN19 |
| 286 | uDFN20 | `Float` | UDFN20 |
| 287 | uDFN21 | `Float` | UDFN21 |
| 288 | uDFN22 | `Float` | UDFN22 |
| 289 | uDFN23 | `Float` | UDFN23 |
| 290 | uDFN24 | `Float` | UDFN24 |
| 291 | uDFN25 | `Float` | UDFN25 |
| 292 | uDFN26 | `Float` | UDFN26 |
| 293 | uDFN27 | `Float` | UDFN27 |
| 294 | uDFN28 | `Float` | UDFN28 |
| 295 | uDFN29 | `Float` | UDFN29 |
| 296 | uDFN30 | `Float` | UDFN30 |
| 297 | uDFN31 | `Float` | UDFN31 |
| 298 | uDFN32 | `Float` | UDFN32 |
| 299 | uDFN33 | `Float` | UDFN33 |
| 300 | uDFN34 | `Float` | UDFN34 |
| 301 | uDFN35 | `Float` | UDFN35 |
| 302 | uDFN36 | `Float` | UDFN36 |
| 303 | uDFN37 | `Float` | UDFN37 |
| 304 | uDFN38 | `Float` | UDFN38 |
| 305 | uDFN39 | `Float` | UDFN39 |
| 306 | uDFN40 | `Float` | UDFN40 |
| 307 | updateDate | `DateTime` | Update Date |
| 308 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 309 | updateUser | `String` | Update User |
| 310 | vipName | `String` | VIP Name |
| 311 | vipStatus | `String` | VIP Status |
| 312 | xcompanyName | `String` | Extended Byte Company Name |
| 313 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 314 | xfirstName | `String` | Xfirst Name |
| 315 | xlastName | `String` | Xlast Name |
| 316 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingsReservationProfileAccountsTravelAgentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `Date` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | referenceCurrency | `String` | Reference Currency |
| 170 | repInfluence | `String` | Reporting Influence |
| 171 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 172 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 173 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 174 | repNationalityCode | `String` | Reporting Nationality Code |
| 175 | repNationalityDescription | `String` | Reporting Nationality Description |
| 176 | repStateDescription | `String` | Reporting State Desc |
| 177 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 178 | repTitleName | `String` | Reporting Title Name |
| 179 | repVIPName | `String` | Reporting Vip Name |
| 180 | repVIPStatus | `String` | Reporting Vip Status |
| 181 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 182 | resortRegistered | `String` | Resort for which Job is registered. |
| 183 | restricted | `String` | Restricted |
| 184 | restrictedRule | `String` | Restricted Rule |
| 185 | salutation | `String` | Salutation Greeting |
| 186 | scope | `String` | Scope |
| 187 | scopeCity | `String` | Scope City |
| 188 | scopeCityDecription | `String` | Scope City Decription |
| 189 | scopeDescription | `String` | Scope Description |
| 190 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 191 | sfirst | `String` | Uppercase value of First Name. |
| 192 | state | `String` | State |
| 193 | stateCode | `String` | State Code |
| 194 | stateDesc | `String` | State Description of the Guest of Payee |
| 195 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 196 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 197 | tax1No | `String` | Tax1 Number |
| 198 | tax2No | `String` | Tax2 Number |
| 199 | taxCategory | `String` | Tax Category |
| 200 | taxType | `String` | Tax Type |
| 201 | taxTypeDescription | `String` | Tax Type Description |
| 202 | territory | `String` | Territory |
| 203 | territoryDescription | `String` | Territory Description |
| 204 | thirdPartyYn | `String` | Third Party Y/N |
| 205 | traceCode | `String` | Trace Code |
| 206 | traceCodeDescription | `String` | Trace Code Description |
| 207 | uDFC01 | `String` | UDFC01 |
| 208 | uDFC02 | `String` | UDFC02 |
| 209 | uDFC03 | `String` | UDFC03 |
| 210 | uDFC04 | `String` | UDFC04 |
| 211 | uDFC05 | `String` | UDFC05 |
| 212 | uDFC06 | `String` | UDFC06 |
| 213 | uDFC07 | `String` | UDFC07 |
| 214 | uDFC08 | `String` | UDFC08 |
| 215 | uDFC09 | `String` | UDFC09 |
| 216 | uDFC10 | `String` | UDFC10 |
| 217 | uDFC11 | `String` | UDFC11 |
| 218 | uDFC12 | `String` | UDFC12 |
| 219 | uDFC13 | `String` | UDFC13 |
| 220 | uDFC14 | `String` | UDFC14 |
| 221 | uDFC15 | `String` | UDFC15 |
| 222 | uDFC16 | `String` | UDFC16 |
| 223 | uDFC17 | `String` | UDFC17 |
| 224 | uDFC18 | `String` | UDFC18 |
| 225 | uDFC19 | `String` | UDFC19 |
| 226 | uDFC20 | `String` | UDFC20 |
| 227 | uDFC21 | `String` | UDFC21 |
| 228 | uDFC22 | `String` | UDFC22 |
| 229 | uDFC23 | `String` | UDFC23 |
| 230 | uDFC24 | `String` | UDFC24 |
| 231 | uDFC25 | `String` | UDFC25 |
| 232 | uDFC26 | `String` | UDFC26 |
| 233 | uDFC27 | `String` | UDFC27 |
| 234 | uDFC28 | `String` | UDFC28 |
| 235 | uDFC29 | `String` | UDFC29 |
| 236 | uDFC30 | `String` | UDFC30 |
| 237 | uDFC31 | `String` | UDFC31 |
| 238 | uDFC32 | `String` | UDFC32 |
| 239 | uDFC33 | `String` | UDFC33 |
| 240 | uDFC34 | `String` | UDFC34 |
| 241 | uDFC35 | `String` | UDFC35 |
| 242 | uDFC36 | `String` | UDFC36 |
| 243 | uDFC37 | `String` | UDFC37 |
| 244 | uDFC38 | `String` | UDFC38 |
| 245 | uDFC39 | `String` | UDFC39 |
| 246 | uDFC40 | `String` | UDFC40 |
| 247 | uDFD01 | `Date` | UDFD01 |
| 248 | uDFD02 | `Date` | UDFD02 |
| 249 | uDFD03 | `Date` | UDFD03 |
| 250 | uDFD04 | `Date` | UDFD04 |
| 251 | uDFD05 | `Date` | UDFD05 |
| 252 | uDFD06 | `Date` | UDFD06 |
| 253 | uDFD07 | `Date` | UDFD07 |
| 254 | uDFD08 | `Date` | UDFD08 |
| 255 | uDFD09 | `Date` | UDFD09 |
| 256 | uDFD10 | `Date` | UDFD10 |
| 257 | uDFD11 | `Date` | UDFD11 |
| 258 | uDFD12 | `Date` | UDFD12 |
| 259 | uDFD13 | `Date` | UDFD13 |
| 260 | uDFD14 | `Date` | UDFD14 |
| 261 | uDFD15 | `Date` | UDFD15 |
| 262 | uDFD16 | `Date` | UDFD16 |
| 263 | uDFD17 | `Date` | UDFD17 |
| 264 | uDFD18 | `Date` | UDFD18 |
| 265 | uDFD19 | `Date` | UDFD19 |
| 266 | uDFD20 | `Date` | UDFD20 |
| 267 | uDFN01 | `Float` | UDFN01 |
| 268 | uDFN02 | `Float` | UDFN02 |
| 269 | uDFN03 | `Float` | UDFN03 |
| 270 | uDFN04 | `Float` | UDFN04 |
| 271 | uDFN05 | `Float` | UDFN05 |
| 272 | uDFN06 | `Float` | UDFN06 |
| 273 | uDFN07 | `Float` | UDFN07 |
| 274 | uDFN08 | `Float` | UDFN08 |
| 275 | uDFN09 | `Float` | UDFN09 |
| 276 | uDFN10 | `Float` | UDFN10 |
| 277 | uDFN11 | `Float` | UDFN11 |
| 278 | uDFN12 | `Float` | UDFN12 |
| 279 | uDFN13 | `Float` | UDFN13 |
| 280 | uDFN14 | `Float` | UDFN14 |
| 281 | uDFN15 | `Float` | UDFN15 |
| 282 | uDFN16 | `Float` | UDFN16 |
| 283 | uDFN17 | `Float` | UDFN17 |
| 284 | uDFN18 | `Float` | UDFN18 |
| 285 | uDFN19 | `Float` | UDFN19 |
| 286 | uDFN20 | `Float` | UDFN20 |
| 287 | uDFN21 | `Float` | UDFN21 |
| 288 | uDFN22 | `Float` | UDFN22 |
| 289 | uDFN23 | `Float` | UDFN23 |
| 290 | uDFN24 | `Float` | UDFN24 |
| 291 | uDFN25 | `Float` | UDFN25 |
| 292 | uDFN26 | `Float` | UDFN26 |
| 293 | uDFN27 | `Float` | UDFN27 |
| 294 | uDFN28 | `Float` | UDFN28 |
| 295 | uDFN29 | `Float` | UDFN29 |
| 296 | uDFN30 | `Float` | UDFN30 |
| 297 | uDFN31 | `Float` | UDFN31 |
| 298 | uDFN32 | `Float` | UDFN32 |
| 299 | uDFN33 | `Float` | UDFN33 |
| 300 | uDFN34 | `Float` | UDFN34 |
| 301 | uDFN35 | `Float` | UDFN35 |
| 302 | uDFN36 | `Float` | UDFN36 |
| 303 | uDFN37 | `Float` | UDFN37 |
| 304 | uDFN38 | `Float` | UDFN38 |
| 305 | uDFN39 | `Float` | UDFN39 |
| 306 | uDFN40 | `Float` | UDFN40 |
| 307 | updateDate | `DateTime` | Update Date |
| 308 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 309 | updateUser | `String` | Update User |
| 310 | vipName | `String` | VIP Name |
| 311 | vipStatus | `String` | VIP Status |
| 312 | xcompanyName | `String` | Extended Byte Company Name |
| 313 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 314 | xfirstName | `String` | Xfirst Name |
| 315 | xlastName | `String` | Xlast Name |
| 316 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationProfileAccountsSourceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `Date` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | referenceCurrency | `String` | Reference Currency |
| 170 | repInfluence | `String` | Reporting Influence |
| 171 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 172 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 173 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 174 | repNationalityCode | `String` | Reporting Nationality Code |
| 175 | repNationalityDescription | `String` | Reporting Nationality Description |
| 176 | repStateDescription | `String` | Reporting State Desc |
| 177 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 178 | repTitleName | `String` | Reporting Title Name |
| 179 | repVIPName | `String` | Reporting Vip Name |
| 180 | repVIPStatus | `String` | Reporting Vip Status |
| 181 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 182 | resortRegistered | `String` | Resort for which Job is registered. |
| 183 | restricted | `String` | Restricted |
| 184 | restrictedRule | `String` | Restricted Rule |
| 185 | salutation | `String` | Salutation Greeting |
| 186 | scope | `String` | Scope |
| 187 | scopeCity | `String` | Scope City |
| 188 | scopeCityDecription | `String` | Scope City Decription |
| 189 | scopeDescription | `String` | Scope Description |
| 190 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 191 | sfirst | `String` | Uppercase value of First Name. |
| 192 | state | `String` | State |
| 193 | stateCode | `String` | State Code |
| 194 | stateDesc | `String` | State Description of the Guest of Payee |
| 195 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 196 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 197 | tax1No | `String` | Tax1 Number |
| 198 | tax2No | `String` | Tax2 Number |
| 199 | taxCategory | `String` | Tax Category |
| 200 | taxType | `String` | Tax Type |
| 201 | taxTypeDescription | `String` | Tax Type Description |
| 202 | territory | `String` | Territory |
| 203 | territoryDescription | `String` | Territory Description |
| 204 | thirdPartyYn | `String` | Third Party Y/N |
| 205 | traceCode | `String` | Trace Code |
| 206 | traceCodeDescription | `String` | Trace Code Description |
| 207 | uDFC01 | `String` | UDFC01 |
| 208 | uDFC02 | `String` | UDFC02 |
| 209 | uDFC03 | `String` | UDFC03 |
| 210 | uDFC04 | `String` | UDFC04 |
| 211 | uDFC05 | `String` | UDFC05 |
| 212 | uDFC06 | `String` | UDFC06 |
| 213 | uDFC07 | `String` | UDFC07 |
| 214 | uDFC08 | `String` | UDFC08 |
| 215 | uDFC09 | `String` | UDFC09 |
| 216 | uDFC10 | `String` | UDFC10 |
| 217 | uDFC11 | `String` | UDFC11 |
| 218 | uDFC12 | `String` | UDFC12 |
| 219 | uDFC13 | `String` | UDFC13 |
| 220 | uDFC14 | `String` | UDFC14 |
| 221 | uDFC15 | `String` | UDFC15 |
| 222 | uDFC16 | `String` | UDFC16 |
| 223 | uDFC17 | `String` | UDFC17 |
| 224 | uDFC18 | `String` | UDFC18 |
| 225 | uDFC19 | `String` | UDFC19 |
| 226 | uDFC20 | `String` | UDFC20 |
| 227 | uDFC21 | `String` | UDFC21 |
| 228 | uDFC22 | `String` | UDFC22 |
| 229 | uDFC23 | `String` | UDFC23 |
| 230 | uDFC24 | `String` | UDFC24 |
| 231 | uDFC25 | `String` | UDFC25 |
| 232 | uDFC26 | `String` | UDFC26 |
| 233 | uDFC27 | `String` | UDFC27 |
| 234 | uDFC28 | `String` | UDFC28 |
| 235 | uDFC29 | `String` | UDFC29 |
| 236 | uDFC30 | `String` | UDFC30 |
| 237 | uDFC31 | `String` | UDFC31 |
| 238 | uDFC32 | `String` | UDFC32 |
| 239 | uDFC33 | `String` | UDFC33 |
| 240 | uDFC34 | `String` | UDFC34 |
| 241 | uDFC35 | `String` | UDFC35 |
| 242 | uDFC36 | `String` | UDFC36 |
| 243 | uDFC37 | `String` | UDFC37 |
| 244 | uDFC38 | `String` | UDFC38 |
| 245 | uDFC39 | `String` | UDFC39 |
| 246 | uDFC40 | `String` | UDFC40 |
| 247 | uDFD01 | `Date` | UDFD01 |
| 248 | uDFD02 | `Date` | UDFD02 |
| 249 | uDFD03 | `Date` | UDFD03 |
| 250 | uDFD04 | `Date` | UDFD04 |
| 251 | uDFD05 | `Date` | UDFD05 |
| 252 | uDFD06 | `Date` | UDFD06 |
| 253 | uDFD07 | `Date` | UDFD07 |
| 254 | uDFD08 | `Date` | UDFD08 |
| 255 | uDFD09 | `Date` | UDFD09 |
| 256 | uDFD10 | `Date` | UDFD10 |
| 257 | uDFD11 | `Date` | UDFD11 |
| 258 | uDFD12 | `Date` | UDFD12 |
| 259 | uDFD13 | `Date` | UDFD13 |
| 260 | uDFD14 | `Date` | UDFD14 |
| 261 | uDFD15 | `Date` | UDFD15 |
| 262 | uDFD16 | `Date` | UDFD16 |
| 263 | uDFD17 | `Date` | UDFD17 |
| 264 | uDFD18 | `Date` | UDFD18 |
| 265 | uDFD19 | `Date` | UDFD19 |
| 266 | uDFD20 | `Date` | UDFD20 |
| 267 | uDFN01 | `Float` | UDFN01 |
| 268 | uDFN02 | `Float` | UDFN02 |
| 269 | uDFN03 | `Float` | UDFN03 |
| 270 | uDFN04 | `Float` | UDFN04 |
| 271 | uDFN05 | `Float` | UDFN05 |
| 272 | uDFN06 | `Float` | UDFN06 |
| 273 | uDFN07 | `Float` | UDFN07 |
| 274 | uDFN08 | `Float` | UDFN08 |
| 275 | uDFN09 | `Float` | UDFN09 |
| 276 | uDFN10 | `Float` | UDFN10 |
| 277 | uDFN11 | `Float` | UDFN11 |
| 278 | uDFN12 | `Float` | UDFN12 |
| 279 | uDFN13 | `Float` | UDFN13 |
| 280 | uDFN14 | `Float` | UDFN14 |
| 281 | uDFN15 | `Float` | UDFN15 |
| 282 | uDFN16 | `Float` | UDFN16 |
| 283 | uDFN17 | `Float` | UDFN17 |
| 284 | uDFN18 | `Float` | UDFN18 |
| 285 | uDFN19 | `Float` | UDFN19 |
| 286 | uDFN20 | `Float` | UDFN20 |
| 287 | uDFN21 | `Float` | UDFN21 |
| 288 | uDFN22 | `Float` | UDFN22 |
| 289 | uDFN23 | `Float` | UDFN23 |
| 290 | uDFN24 | `Float` | UDFN24 |
| 291 | uDFN25 | `Float` | UDFN25 |
| 292 | uDFN26 | `Float` | UDFN26 |
| 293 | uDFN27 | `Float` | UDFN27 |
| 294 | uDFN28 | `Float` | UDFN28 |
| 295 | uDFN29 | `Float` | UDFN29 |
| 296 | uDFN30 | `Float` | UDFN30 |
| 297 | uDFN31 | `Float` | UDFN31 |
| 298 | uDFN32 | `Float` | UDFN32 |
| 299 | uDFN33 | `Float` | UDFN33 |
| 300 | uDFN34 | `Float` | UDFN34 |
| 301 | uDFN35 | `Float` | UDFN35 |
| 302 | uDFN36 | `Float` | UDFN36 |
| 303 | uDFN37 | `Float` | UDFN37 |
| 304 | uDFN38 | `Float` | UDFN38 |
| 305 | uDFN39 | `Float` | UDFN39 |
| 306 | uDFN40 | `Float` | UDFN40 |
| 307 | updateDate | `DateTime` | Update Date |
| 308 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 309 | updateUser | `String` | Update User |
| 310 | vipName | `String` | VIP Name |
| 311 | vipStatus | `String` | VIP Status |
| 312 | xcompanyName | `String` | Extended Byte Company Name |
| 313 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 314 | xfirstName | `String` | Xfirst Name |
| 315 | xlastName | `String` | Xlast Name |
| 316 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingsReservationRateCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| 2 | addition | `String` | Amount to be added to the base rate when shown on rate query |
| 3 | advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| 4 | advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| 5 | advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| 6 | advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| 7 | advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| 8 | alternateRateCode | `String` | Alternative rate code if current rate is not available |
| 9 | availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| 10 | backToBackYN | `String` | Back To Back YN |
| 11 | baseAmount | `Float` | Base Amount |
| 12 | baseFltPct | `String` | Flat or Percentage of the Base Rate |
| 13 | baseRateCode | `String` | Base Rate Code |
| 14 | baseRounding | `String` | Indicates if rounding of rate is required |
| 15 | baseType | `String` | Indicating a rate type such as flat rate or percentage rate. Possible values are: FLAT DIFFERENTIAL and NULL. |
| 16 | bbarBaseAmount | `Float` | This column use to store Percentage or Amount difference between BAR Rate code and this Rate Code. |
| 17 | bbarBaseFltPct | `String` | This flag column identify that amount column represent Flat or Percentage value. |
| 18 | bbarBaseRounding | `String` | This column identify the rounding formula for the BBAR Rate calculation. |
| 19 | bbarBasedYn | `String` | This column will identify that Rate Code is Best BAR based rate code or not. Possible values are Y/N. |
| 20 | bbarCompareYn | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BBAR rate code. |
| 21 | bbarYn | `String` | Bbar Y/N |
| 22 | blockName | `String` | Block Name |
| 23 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 24 | breakfastPrice | `Float` | Breakfast Price |
| 25 | businessDate | `Date` | Business Date |
| 26 | bypassHurdleYn | `String` | In case of ORMS when this flag is Y system ignore this rate code from Hurdle Check. |
| 27 | bypassRankCheckYn | `String` | Indicates that this rate code will not go through rank validations if value is 'Y'. |
| 28 | cBaseAmount | `Float` | Central Base Amount |
| 29 | cBbarBaseAmount | `Float` | Central Bbar Base Amount |
| 30 | cBreakfastPrice | `Float` | Central Bfst Price |
| 31 | cDbaseAmount | `Float` | Central Dbase Amount |
| 32 | cDiscountRateAmount | `Float` | Central Discount Rate Amount |
| 33 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 34 | cExchangeDate | `Date` | Central Xchange Date |
| 35 | cExchangeRate | `Float` | Central Xchange Rate |
| 36 | cRateFloor | `Float` | Central Rate Floor |
| 37 | cRateLevel | `Float` | Central Rate Level |
| 38 | cRodBaseAmount | `Float` | Central Rod Base Amount |
| 39 | cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| 40 | catPackageCode | `String` | Stores the catering package code linked to this rate code. |
| 41 | cateringPackageYN | `String` | Specifies if a catering package is linked to this rate code. |
| 42 | centralMarketCode | `String` | Central Market Code |
| 43 | centralMarketDescription | `String` | Central Market Description |
| 44 | centralMarketGroupCode | `String` | Central Market Group Code |
| 45 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 46 | centralRateBucket | `String` | Central Rate Bucket |
| 47 | centralRateBucketDescription | `String` | Central Rate Bucket Description |
| 48 | centralRateCategory | `String` | Central Rate Category |
| 49 | centralRateCategoryDescription | `String` | Central Rate Category Description |
| 50 | centralRateClass | `String` | Central Rate Class |
| 51 | centralRateClassDescription | `String` | Central Rate Class Description |
| 52 | centralRoomType | `String` | Central Room Type |
| 53 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 54 | centralSourceCode | `String` | Central Source Code |
| 55 | centralSourceDescription | `String` | Central Source Description |
| 56 | centralSourceGroupCode | `String` | Central Source Group Code |
| 57 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 58 | changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| 59 | commissionPercent | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| 60 | commissionCode | `String` | Commission Code |
| 61 | commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| 62 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 63 | commissionableYn | `String` | Commissionable Y/N |
| 64 | complimentaryYN | `String` | Complimentary YN |
| 65 | currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| 66 | currencyCode | `String` | Currency Code |
| 67 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 68 | dailyRatesYn | `String` | Daily Rates Y/N |
| 69 | dayUseYN | `String` | Day use reservation Y/N. |
| 70 | daysWhenClosedToArrival | `String` | Days the rate restriction is not available for arrival |
| 71 | dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| 72 | dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| 73 | dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| 74 | dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| 75 | dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| 76 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 77 | defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| 78 | deletedFlag | `String` | Deleted Flag |
| 79 | depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| 80 | deptCode | `String` | Department code for the transaction. |
| 81 | discountRateAmount | `Float` | Discount rate amount value. |
| 82 | discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| 83 | discountYN | `String` | Discount Flag. |
| 84 | displaySequence | `Float` | Display Sequence |
| 85 | displaySet | `String` | Display Set |
| 86 | distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| 87 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 88 | endDate | `Date` | End Date |
| 89 | eventProperty | `String` | Indicates if the value set for the specific property. |
| 90 | exchangeType | `String` | Exchange Type |
| 91 | externallyControlledYN | `String` | Externally Controlled YN |
| 92 | extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| 93 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 94 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 95 | flatYN | `String` | Flat YN |
| 96 | folioText | `String` | Text displayed on the Folio |
| 97 | frequentFlyerYN | `String` | Frequent Flyer YN |
| 98 | gDSAllowedYN | `String` | Is this rate code available for GDS |
| 99 | groupCode | `String` | Group Code |
| 100 | highlightRateAmountYn | `String` | To highlight on the rate query |
| 101 | houseUseYN | `String` | House-Use YN |
| 102 | inactiveDate | `Date` | Inactive Date |
| 103 | insertDate | `DateTime` | Insert Date |
| 104 | insertUser | `Float` | Insert User |
| 105 | internalLocationId | `String` | Location ID |
| 106 | internalOrganizationId | `Float` | Organization ID |
| 107 | jRNUpdateDate | `Date` | JRN Update Date |
| 108 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 109 | locationID | `String` | Internal ID to uniquely identify the Property |
| 110 | longInfo | `String` | Long Info |
| 111 | loyaltyProgramYN | `String` | Flag to indicate if this is a loyalty program |
| 112 | mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| 113 | marketCode | `String` | Market Code |
| 114 | marketDescription | `String` | Market Description |
| 115 | marketGroupCode | `String` | Market Group Code |
| 116 | marketGroupDescription | `String` | Market Group Description |
| 117 | marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| 118 | maximumDaysAdvanceBooking | `Float` | Maximum Days Advance Booking |
| 119 | maximumLengthOfStay | `Float` | Maximum Length of Stay |
| 120 | maximumOccupancy | `Float` | Maximum Occupancy |
| 121 | mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| 122 | minimumDaysAdvanceBooking | `Float` | Minimum Days Advance Booking |
| 123 | minimumOccupancy | `Float` | Minimum Occupancy |
| 124 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 125 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 126 | multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| 127 | myFidelioUploadYN | `String` | MyFidelio Upload YN |
| 128 | negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| 129 | occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| 130 | occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| 131 | operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| 132 | orderBy | `Float` | Order By |
| 133 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 134 | originalRateCode | `String` | Original Rate Code |
| 135 | orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| 136 | overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| 137 | ownerRateYN | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| 138 | packageTransactionCode | `String` | Package Transaction Code |
| 139 | packageTransactionCodeWeekend | `String` | Package Transaction Code Weekend |
| 140 | packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| 141 | packageTransactionTaxIncludedYN | `String` | Transaction code is inclusive of tax Y/N |
| 142 | packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| 143 | packageYN | `String` | Package YN |
| 144 | packages | `String` | Packages |
| 145 | pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| 146 | postingRhythm | `String` | Posting Rhythm |
| 147 | postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| 148 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 149 | printRateYn | `String` | Print Rate Y/N |
| 150 | privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| 151 | privilegedYn | `String` | Indicates if rate is privileged or not. |
| 152 | profitTransactionCode | `String` | Profit Transaction Code |
| 153 | property | `String` | Code to uniquely identify the Property |
| 154 | propertyName | `String` | Property Name |
| 155 | rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| 156 | rankValue | `Float` | Rank Value |
| 157 | rateBucket | `String` | Yield rate bucket |
| 158 | rateBucketDescription | `String` | Rate Bucket Description |
| 159 | rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| 160 | rateCategory | `String` | Rate Category |
| 161 | rateCategoryDescription | `String` | Rate Category Description |
| 162 | rateClass | `String` | Rate Class |
| 163 | rateClassDescription | `String` | Rate Class Description |
| 164 | rateCodeId | `String` | Rate Code ID |
| 165 | rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| 166 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 167 | rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| 168 | rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| 169 | rateLabel | `String` | Rate Label |
| 170 | rateLevel | `Float` | Rate Level this rate code belongs to. |
| 171 | rateUpdateYN | `String` | Needs to send this rate to GDS or not. |
| 172 | rateinfoUrl | `String` | Rateinfo Url |
| 173 | redemptionRateYN | `String` | Redemption Rate YN |
| 174 | regionalAvailabilityYN | `String` | Regional Availability YN |
| 175 | repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| 176 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 177 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 178 | rodBaseAmount | `Float` | Rod Base Amount |
| 179 | rodBaseFltPct | `String` | Rod Base Flt Pct |
| 180 | rodBaseRounding | `String` | Rod Base Rounding |
| 181 | rodBasedYn | `String` | Is the group code rate of day based |
| 182 | rodYn | `String` | Rod Y/N |
| 183 | roomAssignmentValue | `Float` | Room Assignment Value |
| 184 | roomType | `String` | Room Type |
| 185 | roomTypeDescription | `String` | Room Type Description |
| 186 | sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| 187 | sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| 188 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 189 | servicePerc | `Float` | Service Percentage included. |
| 190 | shortInfo | `String` | Information to be used in the rate query |
| 191 | showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 192 | sourceCode | `String` | Source Code |
| 193 | sourceDescription | `String` | Source Description |
| 194 | sourceGroupCode | `String` | Source Group Code |
| 195 | sourceGroupDescription | `String` | Source Group Description |
| 196 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 197 | taxIncludedYn | `String` | Tax is included in this rate. |
| 198 | tieredYN | `String` | Indicates if the rate is a tiered rate. |
| 199 | transactionCode | `String` | Rate transaction code |
| 200 | transactionCodeWeekend | `String` | Transaction Code Weekend |
| 201 | transactionTaxWeekendIncludedYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| 202 | unitOfLengthOfStay | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| 203 | updateDate | `DateTime` | Update Date |
| 204 | updateUser | `Float` | Update User |
| 205 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 206 | voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| 207 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 208 | wkDeptCode | `String` | Wk Dept Code |
| 209 | yieldAs | `String` | Yield As |
| 210 | yieldableYN | `String` | Yieldable YN |
| 211 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationAlertsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | alertCode | `String` | Alert Code |
| 2 | alertDescription | `String` | Alert Description |
| 3 | alertText | `String` | Alert Text |
| 4 | area | `String` | Area |
| 5 | brandStayCnt | `Float` | Brand Stay Count |
| 6 | comments | `String` | Comments |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | department | `String` | Department |
| 10 | displayAlertYN | `String` | Display Alert YN |
| 11 | emailAddress | `String` | Email Address |
| 12 | emailYn | `String` | Email Y/N |
| 13 | externalAlertId | `String` | Unique ID in External System. |
| 14 | hasTagsYn | `String` | Indicates if the current alert can contain tags. |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | language | `String` | Language |
| 20 | lastStayDate | `Date` | Last Stay Date |
| 21 | lastStayLocation | `String` | Last Stay Location |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | membershipAlertYn | `String` | Indicate if the current alert belongs to a membership module. |
| 24 | membershipCardNo | `String` | Membership Card Number |
| 25 | orderBy | `Float` | Order By |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | pref1 | `String` | Preference 1 |
| 28 | pref2 | `String` | Preference 2 |
| 29 | pref3 | `String` | Preference 3 |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | printAlertYN | `String` | Use this alert to print notification. |
| 32 | printerName | `String` | Name of the printer where alert will be printed. |
| 33 | property | `String` | Code to uniquely identify the Property |
| 34 | propertyStayCnt | `Float` | Property Stay Count |
| 35 | propertyStayDate | `Date` | Previous Stay Date at this property for repeat guests. |
| 36 | queryId | `Float` | Query ID |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 39 | reportName | `String` | Report Name |
| 40 | reservationAlertId | `Float` | Resv Alert ID |
| 41 | reservationNameId | `Float` | Resv Name ID |
| 42 | skipGuestOverviewYn | `String` | Indicates if the guest overview screen should be suppressed. |
| 43 | smsNumber | `String` | The phone number to where the notification will be send. |
| 44 | smsYn | `String` | Use this alert to text a notification. |
| 45 | udfc01 | `String` | Udfc01 |
| 46 | udfc02 | `String` | Udfc02 |
| 47 | udfc03 | `String` | Udfc03 |
| 48 | udfc04 | `String` | Udfc04 |
| 49 | udfc05 | `String` | Udfc05 |
| 50 | udfc06 | `String` | Udfc06 |
| 51 | udfc07 | `String` | Udfc07 |
| 52 | udfc08 | `String` | Udfc08 |
| 53 | udfc09 | `String` | Udfc09 |
| 54 | udfc10 | `String` | Udfc10 |
| 55 | udfc11 | `String` | Udfc11 |
| 56 | udfc12 | `String` | Udfc12 |
| 57 | udfc13 | `String` | Udfc13 |
| 58 | udfc14 | `String` | Udfc14 |
| 59 | udfc15 | `String` | Udfc15 |
| 60 | udfc16 | `String` | Udfc16 |
| 61 | udfc17 | `String` | Udfc17 |
| 62 | udfc18 | `String` | Udfc18 |
| 63 | udfc19 | `String` | Udfc19 |
| 64 | udfc20 | `String` | Udfc20 |
| 65 | udfc21 | `String` | Udfc21 |
| 66 | udfc22 | `String` | Udfc22 |
| 67 | udfc23 | `String` | Udfc23 |
| 68 | udfc24 | `String` | Udfc24 |
| 69 | udfc25 | `String` | Udfc25 |
| 70 | udfc26 | `String` | Udfc26 |
| 71 | udfc27 | `String` | Udfc27 |
| 72 | udfc28 | `String` | Udfc28 |
| 73 | udfc29 | `String` | Udfc29 |
| 74 | udfc30 | `String` | Udfc30 |
| 75 | udfc31 | `String` | Udfc31 |
| 76 | udfc32 | `String` | Udfc32 |
| 77 | udfc33 | `String` | Udfc33 |
| 78 | udfc34 | `String` | Udfc34 |
| 79 | udfc35 | `String` | Udfc35 |
| 80 | udfc36 | `String` | Udfc36 |
| 81 | udfc37 | `String` | Udfc37 |
| 82 | udfc38 | `String` | Udfc38 |
| 83 | udfc39 | `String` | Udfc39 |
| 84 | udfc40 | `String` | Udfc40 |
| 85 | udfd01 | `Date` | Udfd01 |
| 86 | udfd02 | `Date` | Udfd02 |
| 87 | udfd03 | `Date` | Udfd03 |
| 88 | udfd04 | `Date` | Udfd04 |
| 89 | udfd05 | `Date` | Udfd05 |
| 90 | udfd06 | `Date` | Udfd06 |
| 91 | udfd07 | `Date` | Udfd07 |
| 92 | udfd08 | `Date` | Udfd08 |
| 93 | udfd09 | `Date` | Udfd09 |
| 94 | udfd10 | `Date` | Udfd10 |
| 95 | udfd11 | `Date` | Udfd11 |
| 96 | udfd12 | `Date` | Udfd12 |
| 97 | udfd13 | `Date` | Udfd13 |
| 98 | udfd14 | `Date` | Udfd14 |
| 99 | udfd15 | `Date` | Udfd15 |
| 100 | udfd16 | `Date` | Udfd16 |
| 101 | udfd17 | `Date` | Udfd17 |
| 102 | udfd18 | `Date` | Udfd18 |
| 103 | udfd19 | `Date` | Udfd19 |
| 104 | udfd20 | `Date` | Udfd20 |
| 105 | udfn01 | `Float` | Udfn01 |
| 106 | udfn02 | `Float` | Udfn02 |
| 107 | udfn03 | `Float` | Udfn03 |
| 108 | udfn04 | `Float` | Udfn04 |
| 109 | udfn05 | `Float` | Udfn05 |
| 110 | udfn06 | `Float` | Udfn06 |
| 111 | udfn07 | `Float` | Udfn07 |
| 112 | udfn08 | `Float` | Udfn08 |
| 113 | udfn09 | `Float` | Udfn09 |
| 114 | udfn10 | `Float` | Udfn10 |
| 115 | udfn11 | `Float` | Udfn11 |
| 116 | udfn12 | `Float` | Udfn12 |
| 117 | udfn13 | `Float` | Udfn13 |
| 118 | udfn14 | `Float` | Udfn14 |
| 119 | udfn15 | `Float` | Udfn15 |
| 120 | udfn16 | `Float` | Udfn16 |
| 121 | udfn17 | `Float` | Udfn17 |
| 122 | udfn18 | `Float` | Udfn18 |
| 123 | udfn19 | `Float` | Udfn19 |
| 124 | udfn20 | `Float` | Udfn20 |
| 125 | udfn21 | `Float` | Udfn21 |
| 126 | udfn22 | `Float` | Udfn22 |
| 127 | udfn23 | `Float` | Udfn23 |
| 128 | udfn24 | `Float` | Udfn24 |
| 129 | udfn25 | `Float` | Udfn25 |
| 130 | udfn26 | `Float` | Udfn26 |
| 131 | udfn27 | `Float` | Udfn27 |
| 132 | udfn28 | `Float` | Udfn28 |
| 133 | udfn29 | `Float` | Udfn29 |
| 134 | udfn30 | `Float` | Udfn30 |
| 135 | udfn31 | `Float` | Udfn31 |
| 136 | udfn32 | `Float` | Udfn32 |
| 137 | udfn33 | `Float` | Udfn33 |
| 138 | udfn34 | `Float` | Udfn34 |
| 139 | udfn35 | `Float` | Udfn35 |
| 140 | udfn36 | `Float` | Udfn36 |
| 141 | udfn37 | `Float` | Udfn37 |
| 142 | udfn38 | `Float` | Udfn38 |
| 143 | udfn39 | `Float` | Udfn39 |
| 144 | udfn40 | `Float` | Udfn40 |
| 145 | updateDate | `DateTime` | Update Date |
| 146 | updateUser | `Float` | Update User |
| 147 | validationAlertYn | `String` | Indicates if this alert will be used to perform a validation. |
| 148 | validationOverridePermission | `String` | The user permission required in order to override a validation alert. |
| 149 | valueRating | `String` | Value Rating |
| 150 | vipStatus | `String` | VIP Status |
| 151 | welcomeOfferCode | `String` | Offer code if this alert is linked to a guest welcome offer. |
| 152 | welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationCancelPolicyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | percentCancellation | `Float` | Percentage to be charged for the cancellation |
| 2 | percentDue | `Float` | Percentage due for the cancellation |
| 3 | cExchangeDate | `Date` | Central Xchange Date |
| 4 | cExchangeRate | `Float` | Central Xchange Rate |
| 5 | cForeignCancelAmount | `Float` | Central Foreign Cancel Amount |
| 6 | cancellationDate | `DateTime` | Cancel Date. |
| 7 | cancellationPenalty | `String` | Cancellation Penalty |
| 8 | cancellationPenaltyAmount | `Float` | Amount to be charged for the cancellation |
| 9 | cancellationPenaltyType | `String` | Cancellation Penalty Type |
| 10 | cancellationRuleDescription | `String` | Cancellation Rule Description |
| 11 | centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | description | `String` | Description |
| 15 | dmlSeqNumber | `Float` | Dml Sequence No |
| 16 | exchangeRateInfo | `String` | Exchange Rate info used for cancelation penalty if Rate code is in a difference currency. |
| 17 | externalId | `String` | External ID |
| 18 | foreignCancelAmount | `Float` | Cancel Amount in Foreign currency if Rate code is in a different currency. |
| 19 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 20 | insertDate | `DateTime` | Insert Date |
| 21 | insertUser | `Float` | Insert User |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | manualYn | `String` | Manual Y/N |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | processedYn | `String` | Processed Y/N |
| 29 | property | `String` | Code to uniquely identify the Property |
| 30 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 31 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 32 | rateDcSeq | `Float` | Rate Dc Sequence |
| 33 | reservationCancelPolicyId | `Float` | Internal |
| 34 | reservationNameId | `Float` | Resv Name ID |
| 35 | roomNights | `Float` | Room Nights |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationDetailDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | allotmentHeaderId | `Float` | Allotment Header ID |
| 4 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 5 | autoPostAmount | `Float` | Not used. |
| 6 | awardCode | `String` | Award Code |
| 7 | awardCode1 | `String` | Award code 1 |
| 8 | awardCode2 | `String` | Award code 2 |
| 9 | awardCode3 | `String` | Award code 3 |
| 10 | awardCode4 | `String` | Award Code 4 |
| 11 | awardCode5 | `String` | Award code 5 |
| 12 | awardNumber | `String` | Award Voucher number 1 |
| 13 | awardVoucher2 | `String` | Award Voucher number 2 |
| 14 | awardVoucher3 | `String` | Award Voucher number 3 |
| 15 | awardVoucher4 | `String` | Award Voucher number 4 |
| 16 | awardVoucher5 | `String` | Award Voucher number 5 |
| 17 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 18 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 19 | baseRateAmount | `Float` | Base Rate Amount |
| 20 | basedOnRule | `String` | Based On Rule |
| 21 | billing | `String` | Billing |
| 22 | billingContactId | `Float` | Billing Contact ID |
| 23 | blockCode | `String` | Block Code |
| 24 | blockId | `Float` | Block ID. |
| 25 | blockResort | `String` | Property this block belongs to. |
| 26 | bookedRoomCategory | `String` | Booked Room Category |
| 27 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 28 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 29 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 30 | cExchangeDate | `Date` | Central Xchange Date |
| 31 | cExchangeRate | `Float` | Central Xchange Rate |
| 32 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 33 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 34 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 35 | cPackageAmount | `Float` | Central Pkg Amt |
| 36 | cPackageTax | `Float` | Central Pkg Tax |
| 37 | cRoomCost | `Float` | Central Room Cost |
| 38 | cRoomTax | `Float` | Central Room Tax |
| 39 | cShareAmount | `Float` | Central Share Amount |
| 40 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 41 | cUpsellCharge | `Float` | Central Upsell Charge |
| 42 | cancellationCode | `String` | Cancellation Code |
| 43 | cancellationDate | `Date` | Cancellation Date |
| 44 | cancellationNo | `Float` | Cancellation Number |
| 45 | cancellationReasonDesc | `String` | Cancellation Reason Description |
| 46 | centralDiscountAmount | `Float` | Central Discount Amount |
| 47 | centralDiscountCode | `String` | Central Discount Code |
| 48 | centralDiscountCodeDescription | `String` | Central Discount Code Description |
| 49 | centralEffectiveRate | `Float` | Central Effective Rate |
| 50 | centralMarketCode | `String` | Central Market Code |
| 51 | centralMarketCodeDescription | `String` | Central Market Code Description |
| 52 | centralRoomType | `String` | Central Room Type |
| 53 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 54 | centralRoomTypeToCharge | `String` | Central Room Type to Charge |
| 55 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 56 | centralSourceCode | `String` | Central Source Code |
| 57 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 58 | child | `Float` | Child |
| 59 | childrenTaxFree | `Float` | Children Tax Free |
| 60 | children1 | `Float` | Children1 |
| 61 | children2 | `Float` | Children2 |
| 62 | children3 | `Float` | Children3 |
| 63 | children4 | `Float` | Children4 |
| 64 | children5 | `Float` | Children5 |
| 65 | commissionCode | `String` | Commission Code |
| 66 | commissionPaid | `Float` | Commission Paid |
| 67 | commissionableYn | `String` | Commissionable Y/N |
| 68 | company | `String` | Company |
| 69 | companyId | `Float` | Company ID |
| 70 | contact | `String` | Contact Name; UDFC02 on reservation. |
| 71 | corpID | `String` | Corp ID |
| 72 | cribs | `Float` | Cribs |
| 73 | currencyCode | `String` | Currency Code |
| 74 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 75 | dayUseYn | `String` | Day Use Y/N |
| 76 | deAdults | `Float` | De Adults |
| 77 | deBaseRateAmount | `Float` | De Base Rate Amount |
| 78 | deCBaseRateAmount | `Float` | De Central Base Rate Amount |
| 79 | deCExchangeDate | `Date` | De Central Xchange Date |
| 80 | deCExchangeRate | `Float` | De Central Xchange Rate |
| 81 | deChildren | `Float` | De Children |
| 82 | deDmlSeqNumber | `Float` | De Dml Sequence No |
| 83 | deInsertActionInstanceId | `Float` | De Insert Action Instance ID |
| 84 | deInsertDate | `DateTime` | De Insert Date |
| 85 | deInsertUser | `Float` | De Insert User |
| 86 | deUpdateDate | `DateTime` | De Update Date |
| 87 | deUpdateUser | `Float` | De Update User |
| 88 | deletedFlag | `String` | Deleted Flag |
| 89 | discountAmount | `Float` | Discount Amount |
| 90 | discountCode | `String` | Discount Code |
| 91 | discountCodeDescription | `String` | Discount Code Description |
| 92 | discountPercent | `Float` | Discount Percent |
| 93 | dmlSeqNumber | `Float` | Dml Sequence No |
| 94 | doNotMoveYn | `String` | Do not move room flag. |
| 95 | dueOutYn | `String` | Due Out Y/N |
| 96 | effectiveRate | `Float` | Effective Rate |
| 97 | eligibilityCode | `String` | Membership Points Eligibility Code. |
| 98 | exchangePostingType | `String` | Exchange Posting Type |
| 99 | exchangeRate | `Float` | Exchange Rate |
| 100 | extSegNo | `Float` | Not used |
| 101 | extSeqNumber | `Float` | Not used |
| 102 | externalReference | `String` | External Reference |
| 103 | extraBeds | `Float` | Extra Beds |
| 104 | fixedRateYN | `String` | Fixed Rate YN |
| 105 | grossRateAmt | `Float` | Not used. |
| 106 | group | `String` | Group |
| 107 | groupId | `Float` | Group ID |
| 108 | guaranteeCode | `String` | Guarantee Code |
| 109 | housekeepingExpectedServiceTime | `String` | Housekeeping Expected Service Time |
| 110 | iATANumber | `String` | HOLIDEX validated IATA number |
| 111 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 112 | insertDate | `DateTime` | Insert Date |
| 113 | insertUser | `Float` | Insert User |
| 114 | jRNUpdateDate | `Date` | JRN Update Date |
| 115 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 116 | lastShareCalculation | `String` | Calculation method used to distribute the total room rate between shares: [S]plit [Z]ero [F]ull and [P]ercentage. |
| 117 | marketCode | `String` | Market Code |
| 118 | marketCodeDescription | `String` | Market Code Description |
| 119 | membershipPoints | `Float` | Indicates if the Revenue Type is valid for calculating Membership Points. |
| 120 | netRoomAmt | `Float` | Not used. |
| 121 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 122 | originalBaseRate | `Float` | Not used. |
| 123 | packageAmt | `Float` | Not used. |
| 124 | physicalQuantity | `Float` | Physical Quantity |
| 125 | physicalRooms | `Float` | Physical Rooms |
| 126 | pkgTax | `Float` | Not used. |
| 127 | points | `Float` | Points |
| 128 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 129 | property | `String` | Code to uniquely identify the Property |
| 130 | quantity | `Float` | Quantity |
| 131 | rate | `Float` | Rate |
| 132 | rateCode | `String` | Rate Code |
| 133 | rateCodeDescription | `String` | Event Reservation Rate Code Description |
| 134 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 135 | reservationContactId | `Float` | Resv Contact ID |
| 136 | reservationNameId | `Float` | Resv Name ID |
| 137 | resvDailyElSequence | `Float` | Reservation Daily El Seq |
| 138 | resvStatus | `String` | Reservation Status |
| 139 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 140 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 141 | room | `String` | Room |
| 142 | roomCategory | `String` | Room Category |
| 143 | roomClass | `String` | Room Class |
| 144 | roomCost | `Float` | Room Cost |
| 145 | roomInstructions | `String` | Room Instructions |
| 146 | roomTax | `Float` | Room Tax |
| 147 | roomType | `String` | Room Type |
| 148 | roomTypeDescription | `String` | Room Type Description |
| 149 | roomTypeToCharge | `String` | Room Type To Charge |
| 150 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 151 | scheduledMoveComments | `String` | Scheduled Move Comments |
| 152 | scheduledMoveInRoomType | `String` | Scheduled Move In Room Type |
| 153 | scheduledMoveOutRoom | `String` | Scheduled Move Out Room |
| 154 | scheduledMoveOutRoomType | `String` | Scheduled Move Out Room Type |
| 155 | scheduledMoveStatus | `String` | Scheduled Move Status |
| 156 | scheduledMoveTime | `Date` | Scheduled Move Time |
| 157 | scheduledMoveInRoom | `String` | Scheduled Move in Room |
| 158 | scheduledMoveInRoomCat | `String` | Scheduled Move in Room Cat |
| 159 | shareAmountOriginal | `Float` | The original rate amount for the reservation date. |
| 160 | sharePaymentType | `String` | Not used. |
| 161 | sharePrcnt | `Float` | Not used. |
| 162 | sharePriority | `Float` | Not used. |
| 163 | source | `String` | Source |
| 164 | sourceCode | `String` | Source Code |
| 165 | sourceCodeDescription | `String` | Description of the Origin of Booking code. |
| 166 | sourceId | `Float` | Source ID |
| 167 | sourceNumber | `String` | Source Number |
| 168 | stayDate | `Date` | Stay Date |
| 169 | travelAgent | `String` | Travel Agent |
| 170 | travelAgentId | `Float` | Travel Agent ID |
| 171 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 172 | updateDate | `DateTime` | Update Date |
| 173 | updateUser | `Float` | Update User |
| 174 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationEcouponsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | autoAttachedYn | `String` | Indicates if the eCoupon was attached during check-in based on the attached rate code. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | ecouponCode | `String` | Ecoupon Code |
| 5 | ecouponDescription | `String` | Ecoupon Description |
| 6 | ecouponId | `Float` | Primary Key based on Sequence. |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | locationID | `String` | Internal ID to uniquely identify the Property |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Code to uniquely identify the Property |
| 15 | qtyUsed | `Float` | Used quantity of eCoupons. |
| 16 | quantity | `Float` | Allocated minus Used from legacy. |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | rateCode | `String` | Rate Code |
| 20 | reason | `String` | Free format text. |
| 21 | reservationNameId | `Float` | Resv Name ID |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |
| 24 | welcomeOfferModeYn | `String` | The welcome offer mode indicator associated with this eCoupon. |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationItemsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | basedOnRule | `String` | Based On Rule |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | endDate | `DateTime` | End Date |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | itemCode | `String` | Item Code |
| 9 | itemDescription | `String` | Item Description |
| 10 | itemId | `Float` | Item ID |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | locationID | `String` | Internal ID to uniquely identify the Property |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | productCode | `String` | Product Code |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | quantity | `Float` | Quantity |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | rateCode | `String` | Rate Code |
| 22 | reservationItemId | `Float` | Primary Key from Sequence. |
| 23 | reservationNameId | `Float` | Resv Name ID |
| 24 | reservationProductId | `Float` | Reservation Product ID |
| 25 | startDate | `DateTime` | Start Date |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |
| 28 | welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationPreferenceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | basedOnRule | `String` | Based On Rule |
| 2 | comments | `String` | Comments |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedflag | `String` | Deleted Flag |
| 5 | dmlSeqNumber | `Float` | Dml Sequence No |
| 6 | externalPreferenceId | `String` | Unique ID in External System. |
| 7 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | internalPreferenceid | `Float` | Preferenceid |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | locationID | `String` | Internal ID to uniquely identify the Property |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | preArrivalDt | `Date` | This date flags if and when the record was added from pre-arrival screen. |
| 16 | preference | `String` | Preference |
| 17 | preferenceDescription | `String` | Preference Description |
| 18 | preferenceGroup | `String` | Preference Group |
| 19 | preferenceGroupDescription | `String` | Preference Group Description |
| 20 | preferenceId | `Float` | Internal Id of the preference |
| 21 | preferencecomment | `String` | Preferencecomment |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | reservationNameId | `Float` | Resv Name ID |
| 27 | reservationid | `Float` | Reservationid |
| 28 | reservationpreferenceid | `String` | Reservation Preference ID |
| 29 | resvbegindate | `Date` | Resvbegindate |
| 30 | resvenddate | `Date` | Resvenddate |
| 31 | source | `String` | Source |
| 32 | transactionid | `Float` | Transactionid |
| 33 | transportCode | `String` | Transport Code |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationProductsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | awardCode | `String` | Award Code |
| 2 | basedOnRule | `String` | Based On Rule |
| 3 | calculatedQuantity | `Float` | Calculated Quantity |
| 4 | calculationRule | `String` | Calculation Rule |
| 5 | cateringYn | `String` | Catering Y/N |
| 6 | centralPackageCode | `String` | Central Package Code |
| 7 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 8 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 9 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 10 | centralPrice | `Float` | Central Price |
| 11 | currencyCode | `String` | Currency Code |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | deliveryTime | `Date` | Delivery Time |
| 15 | dmlSeqNumber | `Float` | Dml Sequence No |
| 16 | endDate | `Date` | End Date |
| 17 | excludedQuantity | `Float` | Excluded Quantity |
| 18 | fixedPackageYn | `String` | Fixing the package rates at the package level. This will not refresh the prices / allowances from configuration when manually refreshed. |
| 19 | forecastNextDayYN | `String` | Forecast Next Day YN |
| 20 | formula | `String` | Formula |
| 21 | fromValidTime | `Date` | From Valid Time |
| 22 | includedInRateYN | `String` | Included In Rate YN |
| 23 | includesItemYN | `String` | Includes Item YN |
| 24 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | insertUserName | `String` | The name of the user who created the record. |
| 28 | jRNUpdateDate | `Date` | JRN Update Date |
| 29 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 30 | locationID | `String` | Internal ID to uniquely identify the Property |
| 31 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 32 | overrideFixedRateYn | `String` | Override Fixed Rate Y/N |
| 33 | packageCode | `String` | Package Code |
| 34 | packageDescription | `String` | Package Description |
| 35 | packageForecastGroup | `String` | Package Forecast Group |
| 36 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 37 | points | `Float` | Points |
| 38 | posAccountYn | `String` | Pos Account Y/N |
| 39 | posNextDayYn | `String` | Pos Next Day Y/N |
| 40 | postingRhythm | `String` | Posting Rhythm |
| 41 | price | `Float` | Price |
| 42 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 43 | printSeparateYn | `String` | Print Separate Y/N |
| 44 | productGroup | `String` | Product Group |
| 45 | productSource | `String` | Product Source |
| 46 | property | `String` | Code to uniquely identify the Property |
| 47 | quantity | `Float` | Quantity |
| 48 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 49 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 50 | rateCode | `String` | Rate Code |
| 51 | reservationNameId | `Float` | Resv Name ID |
| 52 | reservationProductId | `Float` | Reservation Product ID |
| 53 | startDate | `Date` | Start Date |
| 54 | ticketsYn | `String` | Indicates a Reservation Ticket Package. |
| 55 | toValidTime | `Date` | To Valid Time |
| 56 | updateDate | `DateTime` | Update Date |
| 57 | updateUser | `Float` | Update User |
| 58 | updateUserName | `String` | Update User Name |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationPromotionsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | basedOnRule | `String` | Based On Rule |
| 2 | centralPromotionCode | `String` | Central Promotion Code |
| 3 | centralPromotionDescription | `String` | Central Promotion Description |
| 4 | chainCode | `String` | Chain Code |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | locationID | `String` | Internal ID to uniquely identify the Property |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | pPromoCode | `String` | P Promo Code |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | promotionCode | `String` | Promotion Code |
| 16 | promotionDescription | `String` | Promotion Name. |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | reservationNameId | `Float` | Resv Name ID |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationStatus | `String` | Reservation Status |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationThresholdsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | complimentary | `Float` | The quantity to be diverted to a designated Posting Master. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | diverted | `Float` | Diverted |
| 5 | inactiveDate | `DateTime` | Inactive Date |
| 6 | inactiveYN | `String` | Inactive YN |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | minimumRequired | `Float` | The quantity required by the rule before the posting can be diverted to a designated Posting Master. |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | posted | `Float` | Posted |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Code to uniquely identify the Property |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | reservationNameId | `Float` | Resv Name ID |
| 19 | reservationThresholdId | `Float` | Sequence to Identify the row. |
| 20 | sequence | `Float` | Sequence |
| 21 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 22 | thresholdEntityType | `String` | Threshold Entity Type |
| 23 | transactionDiversionCalculation | `String` | Indicates the scope or applicability of the threshold as PER STAY or PER DAY. |
| 24 | transactionDiversionCode | `String` | User configured diversion code. |
| 25 | transactionDiversionNotes | `String` | Transaction Diversion Notes |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationPropertyPropertyDetailsType

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

### BookingsReservationPropertyServiceRequestsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionTaken | `String` | Description of the action for completion. |
| 2 | closeBusinessDateTime | `Date` | The business date this service request was closed. |
| 3 | closedBy | `String` | User ID who closed this service request. |
| 4 | closedByUserName | `String` | Name of the hotel employee who closed this Service Request. |
| 5 | closureActionTaken | `String` | Followed up Description. |
| 6 | completionBusinessDateTime | `Date` | The business date this service request was completed. |
| 7 | confirmationNumber | `String` | Confirmation Number |
| 8 | contactMethod | `String` | Communication method picked from guest profile. |
| 9 | contactMethodDescription | `String` | Contact Method Description |
| 10 | contactedBy | `String` | Name of the hotel employee who guaranteed this Service Request completion. |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | dateClosed | `Date` | Date Closed |
| 13 | dateCompleted | `Date` | Date Completed |
| 14 | dateOpened | `Date` | Date Opened |
| 15 | deletedFlag | `String` | Deleted Flag |
| 16 | department | `String` | Department |
| 17 | departmentDescription | `String` | Department Description |
| 18 | guestName | `String` | Guest Name |
| 19 | inactiveDate | `Date` | Inactive Date |
| 20 | insertDate | `DateTime` | Insert Date |
| 21 | insertUser | `String` | Insert User |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | nameId | `Float` | Name ID |
| 26 | openBusinessDateTime | `Date` | The business date this service request was created. |
| 27 | openedBy | `String` | User ID who opened this service request. |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | priority | `String` | Priority |
| 31 | priorityDescription | `String` | Priority Description |
| 32 | property | `String` | Code to uniquely identify the Property |
| 33 | remarks | `String` | Remarks |
| 34 | repDepartmentDescription | `String` | Reporting Department Desc |
| 35 | reportingDeptId | `String` | Rep Dept ID |
| 36 | reservationNameId | `Float` | Resv Name ID |
| 37 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 38 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 39 | roomNumber | `String` | Room Number |
| 40 | serviceRequestCode | `String` | Service request classification code. |
| 41 | serviceRequestDescription | `String` | Service Request Description |
| 42 | serviceRequestId | `Float` | Sequence generated no Identifier for service request. |
| 43 | serviceType | `String` | Service Type |
| 44 | status | `String` | Status |
| 45 | timeClosed | `String` | Time Closed |
| 46 | timeCompleted | `String` | Time Completed |
| 47 | timeOpened | `String` | Time Opened |
| 48 | updateDate | `DateTime` | Update Date |
| 49 | updateUser | `String` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationCommentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralNotificationArea | `String` | Central Notification Area |
| 2 | centralNotificationAreaDescription | `String` | Central Notification Area Description |
| 3 | comment | `String` | Comment |
| 4 | commentType | `String` | Type of the comment on the reservation |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | dmlSeqNumber | `Float` | Dml Sequence No |
| 8 | externalCommentId | `String` | Unique ID in External System. |
| 9 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | internalYN | `String` | Internal YN |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | locationID | `String` | Internal ID to uniquely identify the Property |
| 16 | noteResort | `String` | Note Property |
| 17 | noteTitle | `String` | Note Title |
| 18 | noteTypeDescription | `String` | Note Type Description |
| 19 | notificationArea | `String` | Notification Area |
| 20 | notificationAreaDescription | `String` | Notification Area Description |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | reservationCommentId | `Float` | Part of the primary key for this table. |
| 27 | reservationNameId | `Float` | Resv Name ID |
| 28 | updateDate | `DateTime` | Update Date |
| 29 | updateUser | `Float` | Update User |
| 30 | userModifiableYn | `String` | Indicates if a useris allowed to modify this record after it has been created. NULL will be treated as Y. |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationConfirmationLetterDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressId | `Float` | Address ID |
| 2 | customizeYn | `String` | Customize Y/N |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | deliveryMethod | `String` | Delivery Method is Primary Method of reservation Book. |
| 6 | destination | `String` | Destination |
| 7 | destinationId | `String` | Destination ID |
| 8 | dmlSeqNumber | `Float` | Dml Sequence No |
| 9 | emailId | `Float` | Email ID |
| 10 | emailLastAttempted | `Date` | Email: Last Date Attempted. |
| 11 | emailLastStatus | `String` | Email - Last Status: PENDING or SUCCEEDED |
| 12 | emailSuccessfulTries | `Float` | Email: Successful Tries. |
| 13 | failureReason | `String` | Failure Reason |
| 14 | faxId | `Float` | Fax ID |
| 15 | faxLastAttempted | `Date` | Fax: Last Date/Time Attempted. |
| 16 | faxLastStatus | `String` | Fax - Last Status: PENDING or SUCCEEDED |
| 17 | faxSuccessfulTries | `Float` | Fax: Successful Tries. |
| 18 | fromEmail | `String` | From Email |
| 19 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 20 | insertDate | `DateTime` | Insert Date |
| 21 | insertUser | `String` | Insert User |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | lastTimeAttempted | `Date` | Date and time the last confirmation was attempted |
| 25 | locationID | `String` | Internal ID to uniquely identify the Property |
| 26 | mobileId | `Float` | Mobile ID |
| 27 | moduleId | `Float` | Module ID |
| 28 | numberOfSuccessfulTries | `Float` | Number of times the confirmation was successful |
| 29 | optionalEmail | `String` | Optional E-Mail address for the confirmation to be sent to. |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | personalizeText | `String` | Additional text entered by the user to add to the confirmation |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | property | `String` | Code to uniquely identify the Property |
| 34 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 35 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 36 | reservationConfLetterId | `Float` | Internal |
| 37 | reservationNameId | `Float` | Resv Name ID |
| 38 | sendTo | `String` | Name Type. |
| 39 | smsLastAttempted | `Date` | Sms Last Attempted |
| 40 | smsLastStatus | `String` | Sms Last Status |
| 41 | smsSuccessfulTries | `Float` | Sms Successful Tries |
| 42 | status | `String` | Status of the confirmation |
| 43 | toNameId | `Float` | Name ID to whom the contract is sent. |
| 44 | updateDate | `DateTime` | Update Date |
| 45 | updateUser | `String` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationDepositScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activityDeposit | `Float` | Deposit Amount for the Activity. Populated by Concept system currently. |
| 2 | cActivityDeposit | `Float` | Central Activity Deposit |
| 3 | cCancelPnltyAmount | `Float` | Central Cancel Pnlty Amount |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | cForeignDepositAmount | `Float` | Central Foreign Deposit Amount |
| 7 | cancelDeadline | `Date` | Date the reservation can be cancelled |
| 8 | cancelPnltyAmount | `Float` | Amount to be charged for a cancellation |
| 9 | centralDepositAmountOutstanding | `Float` | Central Deposit Amount Outstanding |
| 10 | centralDepositAmountRequested | `Float` | Central Deposit Amount Requested |
| 11 | centralTotalDepositPayments | `Float` | Central Total Deposit Payments |
| 12 | comments | `String` | Comments |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | deletedFlag | `String` | Deleted Flag |
| 15 | depositAmountOutstanding | `Float` | Deposit Amount Outstanding |
| 16 | depositAmountRequested | `Float` | Deposit Amount Requested |
| 17 | depositDueDate | `Date` | Deposit Due Date |
| 18 | depositPercentage | `Float` | Deposit Percentage |
| 19 | depositReqLinkId | `Float` | ID will be populated for reversal records to link the main deposit request. |
| 20 | depositReqReceiptNo | `Float` | Deposit Req Receipt Number |
| 21 | depositReqReversalYn | `String` | Identifies if this record is a deposit request reversal. |
| 22 | depositRule | `String` | Deposit Rule |
| 23 | depositRuleDescription | `String` | Deposit Rule Description |
| 24 | depositRuleType | `String` | Deposit Rule Type |
| 25 | depositScheduleReservationNameId | `Float` | Deposit Schedule Resv Name ID |
| 26 | depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| 27 | dmlSeqNumber | `Float` | Dml Sequence No |
| 28 | exchangeRateInfo | `String` | Exchange Rate info used for cancelation penalty if Rate code is in a difference currency. |
| 29 | externalId | `String` | External ID |
| 30 | foreignDepositAmount | `Float` | Deposit Amount in Foreign currency if Rate code is in a different currency. |
| 31 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 32 | insertDate | `DateTime` | Insert Date |
| 33 | insertUser | `Float` | Insert User |
| 34 | jRNUpdateDate | `Date` | JRN Update Date |
| 35 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 36 | locationID | `String` | Internal ID to uniquely identify the Property |
| 37 | manualYn | `String` | Manual Y/N |
| 38 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 39 | paymentFlag | `String` | Not used |
| 40 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 41 | processedYn | `String` | Processed Y/N |
| 42 | productId | `String` | Product ID |
| 43 | property | `String` | Code to uniquely identify the Property |
| 44 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 45 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 46 | rateDcSeq | `Float` | Rate Dc Sequence |
| 47 | reservationDepositScheduleId | `Float` | Resv Deposit Schedule ID |
| 48 | roomDeposit | `Float` | Deposit Amount due to pure room charges. |
| 49 | totalDepositPayments | `Float` | Amount of the transaction that resulted in the form being required |
| 50 | trxDate | `Date` | Transaction Date |
| 51 | updateDate | `DateTime` | Update Date |
| 52 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationPaymentMethodsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | authorizationAmount | `Float` | Authorization Amount |
| 2 | authorizationDescription | `String` | Authorization Description |
| 3 | authorizationRule | `Float` | Authorization Rule |
| 4 | bonusCheckId | `Float` | Bonus Check ID |
| 5 | centralPaymentMethodType | `String` | Central Payment Method Type |
| 6 | centralPaymentMethodTypeDescription | `String` | Central Payment Method Type Description |
| 7 | creditCardAuthorizationDate | `DateTime` | Credit Card Authorization Date |
| 8 | creditCardId | `Float` | Credit Card ID |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 12 | emailAddress | `String` | Email Address |
| 13 | emailFolioYn | `String` | Email Folio Y/N |
| 14 | insertUser | `Float` | Insert User |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | paymentMethodType | `String` | Payment Method Type |
| 19 | paymentMethodTypeDescription | `String` | Payment Method Type Description |
| 20 | paymentWindow | `Float` | Payment Window |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Code to uniquely identify the Property |
| 23 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 24 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 25 | reservationNameId | `Float` | Resv Name ID |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationProductsTicketsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cExchangeDate | `Date` | Central Xchange Date |
| 2 | cExchangeRate | `Float` | Central Xchange Rate |
| 3 | centralPrice | `Float` | Central Price |
| 4 | consumptionDate | `Date` | Consumption Date |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | issueDate | `Date` | Date when certificate was issued. |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | postingRhythm | `String` | Posting Rhythm |
| 15 | price | `Float` | Price |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | quantity | `Float` | Quantity |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | rateCode | `String` | Rate Code |
| 22 | reference | `String` | Reference |
| 23 | reservationNameId | `Float` | Resv Name ID |
| 24 | reservationProductId | `Float` | Reservation Product ID |
| 25 | ticketId | `Float` | Internal ticket id. |
| 26 | ticketNumber | `String` | The Ticket Number issued for this Package. |
| 27 | ticketPackageCode | `String` | Ticket Package Code |
| 28 | ticketPackageDescription | `String` | Ticket Package Description |
| 29 | updateDate | `DateTime` | Update Date |
| 30 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationRoomCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessibleRoomType | `String` | Indicates if this room type is accessibility compliant. |
| 2 | activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| 3 | activeflag | `Date` | Activeflag |
| 4 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 5 | autoPopulate | `String` | Include room type in the rate header for Myfidelio rates. |
| 6 | autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| 7 | bedType | `String` | Bed Type |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cIncrements | `Float` | Central Increments |
| 11 | cInitialRoundUp | `Float` | Central Initial Round Up |
| 12 | cORMSDrtier1 | `Float` | Central Orms Drtier1 |
| 13 | cORMSDrtier2 | `Float` | Central Orms Drtier2 |
| 14 | cORMSDrtier3 | `Float` | Central Orms Drtier3 |
| 15 | cORMSDrxtra2ndAdult | `Float` | Central Orms Drxtra 2nd Adult |
| 16 | cORMSDrxtraAdult | `Float` | Central Orms Drxtra Adult |
| 17 | cORMSDrxtraChild | `Float` | Central Orms Drxtra Child |
| 18 | cORMSUpsellAmount | `Float` | Central Orms Upsell Amt |
| 19 | cRateAmount | `Float` | Central Rate Amount |
| 20 | cRateFloor | `Float` | Central Rate Floor |
| 21 | cRSDescription | `String` | CRS Description |
| 22 | canDeleteYn | `String` | Can Delete Y/N |
| 23 | centralRoomClass | `String` | Central Room Class |
| 24 | centralRoomClassDescription | `String` | Central Room Class Description |
| 25 | centralRoomType | `String` | Central Room Type |
| 26 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 27 | compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| 28 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 29 | defaultOccupancy | `Float` | Default occupancy for the room type |
| 30 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 31 | defaultRateDesc | `String` | Default Rate Description |
| 32 | defaultratecodeid | `String` | Defaultratecodeid |
| 33 | deletedFlag | `String` | Deleted Flag |
| 34 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 35 | genericYN | `String` | Generic YN |
| 36 | housekeeping | `String` | Room type shows in housekeeping Y/N |
| 37 | imageId | `Float` | Image ID |
| 38 | inactiveDate | `DateTime` | Inactive Date |
| 39 | inactiveflag | `String` | Inactive Flag |
| 40 | increments | `Float` | Increment value for rates by day by LOS. |
| 41 | initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| 42 | insertDate | `DateTime` | Insert Date |
| 43 | insertUser | `Float` | Insert User |
| 44 | internalDeletedflag | `String` | Deleted Flag |
| 45 | jRNUpdateDate | `Date` | JRN Update Date |
| 46 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 47 | label | `String` | Label |
| 48 | locationID | `String` | Internal ID to uniquely identify the Property |
| 49 | longDescription | `String` | Long Description |
| 50 | maintenance | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| 51 | maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| 52 | maxRollaways | `Float` | Not used |
| 53 | maximumAdults | `Float` | The maximum occupancy of adults for this room category. |
| 54 | maximumChildren | `Float` | The maximum occupancy of children for this room category. |
| 55 | maximumOccupancy | `Float` | Maximum Occupancy |
| 56 | meetingRoomYN | `String` | Meeting Room YN |
| 57 | memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| 58 | minimumOccupancy | `Float` | Minimum Occupancy |
| 59 | numberOfRooms | `Float` | Number of Rooms |
| 60 | oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| 61 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 62 | ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| 63 | ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| 64 | ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| 65 | ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| 66 | ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| 67 | ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| 68 | ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| 69 | ownerroomflag | `String` | Ownerroomflag |
| 70 | physical | `String` | Physical |
| 71 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 72 | productClass | `String` | Product Class |
| 73 | property | `String` | Code to uniquely identify the Property |
| 74 | pseudoRoomType | `String` | Pseudo Room Type |
| 75 | pseudoRoomYN | `String` | Pseudo Room YN |
| 76 | rateAmount | `Float` | Rate Amount |
| 77 | rateCategory | `String` | Rate Category |
| 78 | rateCategoryDesc | `String` | Rate Category Description |
| 79 | rateCode | `String` | Rate Code |
| 80 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 81 | ratecategoryid | `String` | Ratecategoryid |
| 82 | repItem | `String` | Reporting Item |
| 83 | repItemName | `String` | Reporting Item Name |
| 84 | repItemOrderby | `Float` | Reporting Item Orderby |
| 85 | repOrderBy | `Float` | Reporting Order By |
| 86 | repRateCategory | `String` | Reporting Rate Category |
| 87 | repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| 88 | repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| 89 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 90 | replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| 91 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 92 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 93 | roomClass | `String` | Room Class |
| 94 | roomClassDescription | `String` | Room Class Description |
| 95 | roomInfoURL | `String` | URL where room information is stored. |
| 96 | roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| 97 | roomType | `String` | Room Type |
| 98 | roomTypeDescription | `String` | Charged Room Type Description |
| 99 | roomcategoryid | `String` | Roomcategoryid |
| 100 | roomcategorypmsref | `String` | Roomcategorypmsref |
| 101 | roomclassid | `String` | Roomclassid |
| 102 | rotationGroup | `String` | Rotation Group |
| 103 | sLabel | `String` | S Label |
| 104 | salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| 105 | sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| 106 | sendIFC | `String` | Room type sent to interface Y/N |
| 107 | sequence | `Float` | Sequence |
| 108 | smoking | `String` | Smoking |
| 109 | smokingPrefDesc | `String` | Smoking Pref Description |
| 110 | suiteYN | `String` | Suite YN |
| 111 | updateDate | `DateTime` | Update Date |
| 112 | updateUser | `Float` | Update User |
| 113 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 114 | yieldStatus | `String` | Yield Status |

[⬆ Back to Query](#query)

---

### BookingsReservationBookedRoomCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessibleRoomType | `String` | Indicates if this room type is accessibility compliant. |
| 2 | activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| 3 | activeflag | `Date` | Activeflag |
| 4 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 5 | autoPopulate | `String` | Include room type in the rate header for Myfidelio rates. |
| 6 | autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| 7 | bedType | `String` | Bed Type |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cIncrements | `Float` | Central Increments |
| 11 | cInitialRoundUp | `Float` | Central Initial Round Up |
| 12 | cORMSDrtier1 | `Float` | Central Orms Drtier1 |
| 13 | cORMSDrtier2 | `Float` | Central Orms Drtier2 |
| 14 | cORMSDrtier3 | `Float` | Central Orms Drtier3 |
| 15 | cORMSDrxtra2ndAdult | `Float` | Central Orms Drxtra 2nd Adult |
| 16 | cORMSDrxtraAdult | `Float` | Central Orms Drxtra Adult |
| 17 | cORMSDrxtraChild | `Float` | Central Orms Drxtra Child |
| 18 | cORMSUpsellAmount | `Float` | Central Orms Upsell Amt |
| 19 | cRateAmount | `Float` | Central Rate Amount |
| 20 | cRateFloor | `Float` | Central Rate Floor |
| 21 | cRSDescription | `String` | CRS Description |
| 22 | canDeleteYn | `String` | Can Delete Y/N |
| 23 | centralRoomClass | `String` | Central Room Class |
| 24 | centralRoomClassDescription | `String` | Central Room Class Description |
| 25 | centralRoomType | `String` | Central Room Type |
| 26 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 27 | chargedRoomTypeDescription | `String` | Charged Room Type Description |
| 28 | compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| 29 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 30 | defaultOccupancy | `Float` | Default occupancy for the room type |
| 31 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 32 | defaultRateDesc | `String` | Default Rate Description |
| 33 | defaultratecodeid | `String` | Defaultratecodeid |
| 34 | deletedFlag | `String` | Deleted Flag |
| 35 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 36 | genericYN | `String` | Generic YN |
| 37 | housekeeping | `String` | Room type shows in housekeeping Y/N |
| 38 | imageId | `Float` | Image ID |
| 39 | inactiveDate | `Date` | Inactive Date |
| 40 | inactiveflag | `String` | Inactive Flag |
| 41 | increments | `Float` | Increment value for rates by day by LOS. |
| 42 | initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| 43 | insertDate | `DateTime` | Insert Date |
| 44 | insertUser | `Float` | Insert User |
| 45 | internalDeletedflag | `String` | Deleted Flag |
| 46 | jRNUpdateDate | `Date` | JRN Update Date |
| 47 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 48 | label | `String` | Label |
| 49 | locationID | `String` | Internal ID to uniquely identify the Property |
| 50 | longDescription | `String` | Long Description |
| 51 | maintenance | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| 52 | maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| 53 | maxRollaways | `Float` | Not used |
| 54 | maximumAdults | `Float` | The maximum occupancy of adults for this room category. |
| 55 | maximumChildren | `Float` | The maximum occupancy of children for this room category. |
| 56 | maximumOccupancy | `Float` | Maximum Occupancy |
| 57 | meetingRoomYN | `String` | Meeting Room YN |
| 58 | memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| 59 | minimumOccupancy | `Float` | Minimum Occupancy |
| 60 | numberOfRooms | `Float` | Number of Rooms |
| 61 | oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| 62 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 63 | ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| 64 | ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| 65 | ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| 66 | ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| 67 | ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| 68 | ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| 69 | ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| 70 | ownerroomflag | `String` | Ownerroomflag |
| 71 | physical | `String` | Physical |
| 72 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 73 | productClass | `String` | Product Class |
| 74 | property | `String` | Code to uniquely identify the Property |
| 75 | pseudoRoomType | `String` | Pseudo Room Type |
| 76 | pseudoRoomYN | `String` | Pseudo Room YN |
| 77 | rateAmount | `Float` | Rate Amount |
| 78 | rateCategory | `String` | Rate Category |
| 79 | rateCategoryDesc | `String` | Rate Category Description |
| 80 | rateCode | `String` | Rate Code |
| 81 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 82 | ratecategoryid | `String` | Ratecategoryid |
| 83 | repItem | `String` | Reporting Item |
| 84 | repItemName | `String` | Reporting Item Name |
| 85 | repItemOrderby | `Float` | Reporting Item Orderby |
| 86 | repOrderBy | `Float` | Reporting Order By |
| 87 | repRateCategory | `String` | Reporting Rate Category |
| 88 | repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| 89 | repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| 90 | repUpdateDate | `Date` | Reporting Updatedate |
| 91 | replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| 92 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 93 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 94 | roomCategoryID | `String` | Room Category ID |
| 95 | roomCategoryPMSRef | `String` | Room Category PMS Ref |
| 96 | roomClass | `String` | Room Class |
| 97 | roomClassDescription | `String` | Room Class Description |
| 98 | roomInfoURL | `String` | URL where room information is stored. |
| 99 | roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| 100 | roomType | `String` | Room Type |
| 101 | roomclassid | `String` | Roomclassid |
| 102 | rotationGroup | `String` | Rotation Group |
| 103 | sLabel | `String` | S Label |
| 104 | salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| 105 | sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| 106 | sendIFC | `String` | Room type sent to interface Y/N |
| 107 | sequence | `Float` | Sequence |
| 108 | smoking | `String` | Smoking |
| 109 | smokingPrefDesc | `String` | Smoking Pref Description |
| 110 | suiteYN | `String` | Suite YN |
| 111 | updateDate | `DateTime` | Update Date |
| 112 | updateUser | `Float` | Update User |
| 113 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 114 | yieldStatus | `String` | Yield Status |

[⬆ Back to Query](#query)

---

### BookingsReservationRoutingInstructionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `String` | Account Code |
| 2 | addTransactionYN | `String` | Add Trx Y/N |
| 3 | addressId | `Float` | Address ID |
| 4 | authemployeeid | `Float` | Authemployeeid |
| 5 | authorizerId | `Float` | Authorizer ID |
| 6 | basedOnRate | `String` | Rate Code that is the source for this routing instruction. |
| 7 | billingInstrnCode | `Float` | Billing Instruction Code. |
| 8 | billtoprofileid | `Float` | Billtoprofileid |
| 9 | cCompPreApprovalAmount | `Float` | Central Comp Pre Approval Amt |
| 10 | cExchangeDate | `Date` | Central Xchange Date |
| 11 | cExchangeRate | `Float` | Central Xchange Rate |
| 12 | centralExtendedInstructionSummary | `String` | Central Extended Instruction Summary |
| 13 | centralInstructionSummary | `String` | Central Instruction Summary |
| 14 | centralRoutingAmountLimit | `Float` | Central Routing Amount Limit |
| 15 | centralRoutingLimitUsed | `Float` | Central Routing Limit Used |
| 16 | centralRoutingTransactionCode | `String` | Central Routing Transaction Code |
| 17 | centralRoutingTransactionCodeDescription | `String` | Central Routing Transaction Code Description |
| 18 | comments | `String` | Comments |
| 19 | compAuthorizer | `String` | Comp Authorizer |
| 20 | compPreApprovalAmt | `Float` | Amount for which the comp pre approval is sought. |
| 21 | compPreApprovalCode | `String` | Approval Code from PTS system. |
| 22 | compPreApprovalDate | `Date` | Approval Date from PTS system. |
| 23 | compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| 24 | compTypeCode | `String` | Comp Type Code |
| 25 | compVoucherNo | `String` | Comp Voucher Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | dailyYn | `String` | Daily Y/N |
| 28 | dayString | `String` | Concatenated string of all the days. This is also used part of the unique key. |
| 29 | declinedBy | `Float` | User ID of user that declined comp routing request |
| 30 | declinedYn | `String` | Used to decline comp routing requests |
| 31 | deletedFlag | `String` | Deleted Flag |
| 32 | endDate | `DateTime` | End Date |
| 33 | extendedInstructionSummary | `String` | Extended Instruction Summary |
| 34 | folio | `Float` | Folio |
| 35 | fridayYN | `String` | Friday YN |
| 36 | insertDate | `DateTime` | Insert Date |
| 37 | insertUser | `Float` | Insert User |
| 38 | instructionSummary | `String` | Instruction Summary |
| 39 | internalDeletedflag | `String` | Deleted Flag |
| 40 | internalMembershipid | `Float` | Membershipid |
| 41 | jRNUpdateDate | `Date` | JRN Update Date |
| 42 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 43 | locationID | `String` | Internal ID to uniquely identify the Property |
| 44 | membershipId | `Float` | Membership ID |
| 45 | mondayYN | `String` | Monday YN |
| 46 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 47 | payeeFirstName | `String` | First name of the guest paying the bill |
| 48 | payeeLastName | `String` | Nirst name of the guest paying the bill |
| 49 | payeeNameID | `Float` | Name Id to which it should be routed. |
| 50 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 51 | printReceiptYn | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| 52 | property | `String` | Code to uniquely identify the Property |
| 53 | requestedBy | `String` | Application user who requested the report. |
| 54 | reservationNameId | `Float` | Resv Name ID |
| 55 | reservationid | `Float` | Reservationid |
| 56 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 57 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 58 | routedToRoomNo | `String` | Routed To Room Number |
| 59 | routingAmountLimit | `Float` | Routing Amount Limit |
| 60 | routingBeginDate | `DateTime` | Routing Begin Date |
| 61 | routingCode | `String` | Routing Code |
| 62 | routingCodeDescription | `String` | Routing Code Description |
| 63 | routingCoversLimit | `Float` | No. of covers for this routing instruction. |
| 64 | routingDateRange | `String` | Routing Date Range |
| 65 | routingDaysOfWeek | `String` | Routing Days of Week |
| 66 | routingInstructionsId | `Float` | Number to identify the entry. |
| 67 | routingLimitType | `String` | Identifies whether this routing instruction has a limit amount or limit percent. |
| 68 | routingLimitUsed | `Float` | Amount of credit used for this routing instruction |
| 69 | routingLinkId | `Float` | Value used to group routing instructions. Taken from Sequence ROUTING_LINK_ID_SEQ. |
| 70 | routingPercentageLimit | `Float` | Routing Percentage Limit |
| 71 | routingTransactionCode | `String` | Routing Transaction Code |
| 72 | routingTransactionCodeDescription | `String` | Routing Transaction Code Description |
| 73 | routingType | `String` | To specify whether it is a package routing or not |
| 74 | routingTypeDesc | `String` | Routing Type Desc |
| 75 | routinginstructid | `Float` | Routinginstructid |
| 76 | saturdayYN | `String` | Saturday YN |
| 77 | sundayYN | `String` | Sunday YN |
| 78 | tcGroup | `String` | Transaction Code Group |
| 79 | tcSubgroup | `String` | Transaction Code Subgroup |
| 80 | thursdayYN | `String` | Thursday YN |
| 81 | toReservationNameId | `Float` | To Resv Name ID |
| 82 | toreservationid | `Float` | Toreservationid |
| 83 | transcodearrangementid | `Float` | Transcodearrangementid |
| 84 | transcodeid | `String` | Transcodeid |
| 85 | transgroupid | `String` | Transgroupid |
| 86 | transsubgroupid | `String` | Transsubgroupid |
| 87 | trxServiceType | `String` | Transaction Service Type |
| 88 | tuesdayYN | `String` | Tuesday YN |
| 89 | updateDate | `DateTime` | Update Date |
| 90 | updateUser | `Float` | Update User |
| 91 | wednesdayYN | `String` | Wednesday YN |

[⬆ Back to Query](#query)

---

### BookingsReservationSourceTableDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralSequence | `Float` | Central Sequence |
| 2 | centralSourceCode | `String` | Central Source Code |
| 3 | centralSourceDescription | `String` | Central Source Description |
| 4 | centralSourceGroupCode | `String` | Central Source Group Code |
| 5 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | inactiveDate | `Date` | Inactive Date |
| 10 | inactiveFlagYN | `String` | Inactive YN |
| 11 | inactiveYn | `String` | Inactive Y/N |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | lastuseddatetime | `DateTime` | Lastuseddatetime |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | parentsourceid | `String` | Parentsourceid |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | repItem | `String` | Reporting Item |
| 24 | repItemName | `String` | Reporting Item Name |
| 25 | repItemOrderby | `Float` | Reporting Item Orderby |
| 26 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | sequence | `Float` | Sequence |
| 30 | sourceCode | `String` | Source Code |
| 31 | sourceDescription | `String` | Source Description |
| 32 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 33 | sourceGroupCode | `String` | Source group of the source code |
| 34 | sourceGroupDescription | `String` | Source Group Description |
| 35 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 36 | sourceid | `String` | Sourceid |
| 37 | tempYn | `String` | Temp Y/N |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationTrackitItemsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionCode | `String` | Action Code |
| 2 | actionDate | `Date` | Follow up date. |
| 3 | actionDescription | `String` | Action Description |
| 4 | assignedTo | `Float` | Assigned To |
| 5 | assignedUser | `String` | Assigned User |
| 6 | assignedYN | `String` | Is the extension assigned |
| 7 | businessDateCreated | `Date` | Business Date Created |
| 8 | businessDateResolved | `Date` | Business date the item was resolved. |
| 9 | closedYN | `String` | Close Bracket |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | externalId | `String` | External ID |
| 13 | guestNameId | `Float` | Guest Name ID |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | locationCode | `String` | Location Code |
| 19 | locationDescription | `String` | Location Description |
| 20 | locationID | `String` | Internal ID to uniquely identify the Property |
| 21 | msgid | `Float` | Msgid |
| 22 | openYN | `String` | Open YN |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | property | `String` | Code to uniquely identify the Property |
| 26 | quantity | `Float` | Quantity |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | reference | `String` | Reference number. |
| 30 | reservationNameId | `Float` | Resv Name ID |
| 31 | resolvedUser | `Float` | User ID who resolved the item. |
| 32 | status | `String` | Status |
| 33 | trackItDescription | `String` | Track It Description |
| 34 | trackItGroup | `String` | Trackit Group. |
| 35 | trackItNumber | `String` | Ticket Number. |
| 36 | trackitId | `Float` | Unique Trackit ID. |
| 37 | typeCode | `String` | Trackit type. |
| 38 | typeDescription | `String` | Type Description |
| 39 | unassignedYN | `String` | Unassigned YN |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationGuestReservationTracesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | completedBy | `String` | Completed By |
| 2 | completedDate | `Date` | Completed Date |
| 3 | completedTime | `String` | Completed Time |
| 4 | completedYN | `String` | Completed YN |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | department | `String` | Department |
| 8 | departmentDescription | `String` | Description of the department |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | itemId | `Float` | Item ID |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | noteCode | `String` | Note Code |
| 15 | noteResort | `String` | Note Property |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | property | `String` | Code to uniquely identify the Property |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | reservationNameId | `Float` | Resv Name ID |
| 22 | reservationTraceId | `Float` | Unique record ID. |
| 23 | statusFlag | `String` | Status Flag |
| 24 | time | `String` | Time |
| 25 | traceDate | `Date` | Date of the trace. |
| 26 | traceId | `Float` | Trace ID |
| 27 | traceStatus | `String` | Trace Status |
| 28 | traceText | `String` | Trace Text |
| 29 | updateDate | `DateTime` | Update Date |
| 30 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingsReservationRotationPointAdjustmentsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentDate | `Date` | Adjustment Date |
| 2 | adjustmentDescription | `String` | Adjustment Description |
| 3 | adjustmentQuantity | `Float` | Adjustment Quantity |
| 4 | amount | `Float` | Amount |
| 5 | beginDate | `Date` | Begin Date |
| 6 | businessDate | `Date` | Business Date |
| 7 | cPoints | `Float` | C Points |
| 8 | confirmationNumber | `String` | Confirmation Number |
| 9 | dSI | `Float` | DSI |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | displayName | `String` | Display Name |
| 12 | endDate | `Date` | End Date |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | nCNT | `Float` | NCNT |
| 16 | numberOfNights | `Float` | Number of Nights |
| 17 | organizationID | `Float` | Organization ID |
| 18 | pKID | `Float` | PKID |
| 19 | points | `Float` | Points |
| 20 | property | `String` | Property |
| 21 | rCNT | `Float` | RCNT |
| 22 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 23 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 24 | rateCode | `String` | Rate Code |
| 25 | reservtionNameID | `Float` | Reservtion Name ID |
| 26 | room | `String` | Room |
| 27 | rotationBeginDate | `Date` | Rotation Begin Date |
| 28 | rotationEndDate | `Date` | Rotation End Date |
| 29 | rotationID | `Float` | Rotation ID |
| 30 | sCNT | `Float` | SCNT |
| 31 | type | `String` | Type |

[⬆ Back to Query](#query)

---

### BookingsReservationRotationOverridesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | action | `String` | Action |
| 2 | dSI | `Float` | DSI |
| 3 | date | `DateTime` | Date |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | organizationID | `Float` | Organization ID |
| 8 | overrideRoom | `String` | Override Room |
| 9 | overrideRoomPoints | `Float` | Override Room Points |
| 10 | pKID | `Float` | PKID |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | reasonCode | `String` | Reason Code |
| 15 | reasonDescription | `String` | Reason Description |
| 16 | reservationNameID | `Float` | Reservation Name ID |
| 17 | room | `String` | Room |
| 18 | rotationOverrideDate | `Date` | Rotation Override Date |
| 19 | rotationRoom | `String` | Rotation Room |
| 20 | rotationRoomPoints | `Float` | Rotation Room Points |
| 21 | time | `String` | Time |
| 22 | user | `String` | User |

[⬆ Back to Query](#query)

---

### BookingsReservationLinkedReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `Date` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `Date` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `Date` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `Date` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `Date` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `Date` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `Date` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | channelDescription | `String` | Channel Description |
| 152 | channelOrderBy | `Float` | Channel Order By |
| 153 | channelid | `String` | Channelid |
| 154 | checkInInitiatedBy | `String` | Check In Initiated By |
| 155 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 156 | childBucket1 | `Float` | Child Bucket 1 |
| 157 | childBucket4 | `Float` | Child Bucket 4 |
| 158 | childBucket5 | `Float` | Child Bucket 5 |
| 159 | children | `Float` | Children |
| 160 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 161 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 162 | childrenAges | `String` | Children Ages |
| 163 | commissionCode | `String` | Commission Code |
| 164 | commissionDescription | `String` | Commission Description |
| 165 | commissionHoldCode | `String` | Commission Hold Code |
| 166 | commissionPaid | `Float` | Commission Paid |
| 167 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 168 | commissionableYN | `String` | Commissionable YN |
| 169 | commissionid | `String` | Commissionid |
| 170 | compHouse | `String` | Comp House |
| 171 | compTypeCode | `String` | Comp Type Code |
| 172 | companyCity | `String` | Company City |
| 173 | companyCountry | `String` | Company Country |
| 174 | companyID | `Float` | Company ID |
| 175 | companyName | `String` | Company Name |
| 176 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 177 | companyProfileID | `Float` | Company Profile ID |
| 178 | complimentaryYN | `String` | Complimentary YN |
| 179 | compreasonid | `String` | Compreasonid |
| 180 | computedResvStatus | `String` | Calculated reservation status. |
| 181 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 182 | confirmationNo | `String` | Shared Confirmation Number |
| 183 | consumerYn | `String` | Consumer Y/N |
| 184 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 185 | contactProfileID | `Float` | Contact Profile ID |
| 186 | contactProfileName | `String` | Contact Profile Name |
| 187 | createdBy | `String` | The name of the user who created the record. |
| 188 | createdByDefaultResort | `String` | Created By Default Property |
| 189 | createdDate | `Date` | Created Date |
| 190 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 191 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 192 | creditCardId | `Float` | Credit Card ID |
| 193 | creditLimit | `Float` | Credit Limit |
| 194 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 195 | cribs | `Float` | Cribs |
| 196 | currencyCode | `String` | Currency Code |
| 197 | customReferenceNumber | `String` | Custom Reference Number |
| 198 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 199 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 200 | deletedFlag | `String` | Deleted Flag |
| 201 | departtransportid | `String` | Departtransportid |
| 202 | departureComments | `String` | Departure Comments |
| 203 | departureDate | `Date` | Departure Date |
| 204 | departureDateTime | `Date` | Departure Date Time |
| 205 | departureTime | `String` | Departure Time |
| 206 | departureTransportCode | `String` | Departure Transport Code |
| 207 | departureTransportationYN | `String` | Departure Transportation YN |
| 208 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 209 | detatchedDate | `Date` | Detatched Date |
| 210 | detatchedYN | `String` | Detatched YN |
| 211 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 212 | directbillauthby | `Float` | Directbillauthby |
| 213 | discountAmount | `Float` | Discount Amount |
| 214 | discountAmt | `Float` | Discount Amount |
| 215 | discountPercent | `Float` | Discount Percentage. |
| 216 | discountPrcnt | `Float` | Discount Prcnt |
| 217 | discountReason | `String` | Discount Reason |
| 218 | discountReasonDescription | `String` | Discount Reason Description |
| 219 | discountreasonid | `String` | Discountreasonid |
| 220 | displayColor | `String` | Display Color |
| 221 | dmlSeqNumber | `Float` | Dml Sequence No |
| 222 | doNotMoveRoom | `String` | Do Not Move Room |
| 223 | doNotMoveYN | `String` | Do not move room flag. |
| 224 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 225 | dropOffDate | `Date` | Drop Off Date |
| 226 | dropOffStation | `String` | Drop Off Station |
| 227 | dropOffTime | `String` | Drop Off Time |
| 228 | dropOffType | `String` | Drop Off Type |
| 229 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 230 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 231 | effectiveRateAmount | `Float` | Not used. |
| 232 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 233 | emailAddress | `String` | Email Address |
| 234 | emailFolioYn | `String` | Email Folio Y/N |
| 235 | emailId | `Float` | Email ID |
| 236 | emailYn | `String` | Email Y/N |
| 237 | endCity | `String` | End City |
| 238 | endDatetime | `Date` | End Datetime |
| 239 | endDistrict | `String` | End District |
| 240 | endState | `String` | End State |
| 241 | endbusinessdate | `Date` | Endbusinessdate |
| 242 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 243 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 244 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 245 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 246 | eventId | `Float` | Event ID |
| 247 | exchangePostingType | `String` | Exchange Posting Type |
| 248 | exchangeRate | `Float` | Exchange Rate |
| 249 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 250 | expectedTimeOfReturnETR | `Date` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 251 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 252 | extSegNo | `Float` | Not used |
| 253 | extSeqNumber | `Float` | Not used |
| 254 | extensionId | `Float` | Internal extension number for the main reservation |
| 255 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 256 | externalReference | `String` | External Reference |
| 257 | externalReferencesList | `String` | External References List |
| 258 | extraBeds | `Float` | Extra Beds |
| 259 | fBRevenue | `Float` | FB Revenue |
| 260 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 261 | faxId | `Float` | Fax ID |
| 262 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 263 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 264 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 265 | fixedCharge | `Float` | Not used. |
| 266 | fixedRateYN | `String` | Fixed Rate YN |
| 267 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 268 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 269 | folioNumber | `String` | Folio Number |
| 270 | folioText1 | `String` | Folio Text1 |
| 271 | folioText2 | `String` | Folio Text2 |
| 272 | foreignCurrencyID | `String` | Foreign Currency ID |
| 273 | freeChild | `Float` | Free Child |
| 274 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 275 | grossRateFuture | `Float` | Gross Rate Future |
| 276 | grossRatePast | `Float` | Gross Rate Past |
| 277 | groupName | `String` | Group Name |
| 278 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 279 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 280 | groupProfileClientID | `String` | Group Profile Client ID |
| 281 | groupProfileID | `Float` | Group Profile ID |
| 282 | groupProfileName | `String` | Group Profile Name |
| 283 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 284 | guaranteecodeid | `String` | Guaranteecodeid |
| 285 | guestFirstName | `String` | Guest First Name |
| 286 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 287 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 288 | guestSignature | `String` | Signature of the guest |
| 289 | guestStatus | `String` | Used for Police/Tourist Export |
| 290 | guestType | `String` | Guest Type |
| 291 | guestprofileid | `Float` | Guestprofileid |
| 292 | gueststatusid | `String` | Gueststatusid |
| 293 | guesttypeid | `String` | Guesttypeid |
| 294 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 295 | hurdle | `Float` | Hurdle |
| 296 | hurdleOverride | `String` | Hurdle Override |
| 297 | iDByMembershipClass | `String` | ID by Membership Class |
| 298 | iDByMembershipType | `String` | ID by Membership Type |
| 299 | individualCity | `String` | Guest Address. |
| 300 | individualCountry | `String` | Country of the guest |
| 301 | individualFirstName | `String` | Individual First Name |
| 302 | individualLastName | `String` | Individual Last Name |
| 303 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 304 | insertDate | `DateTime` | Insert Date |
| 305 | insertDateTime | `DateTime` | Insert DateTime |
| 306 | insertUser | `Float` | Insert User |
| 307 | intermediaryYn | `String` | Intermediary Y/N |
| 308 | internalAwardMembershipId | `Float` | Award Membership ID |
| 309 | internalBaseratecode | `String` | Baseratecode |
| 310 | internalBlockId | `Float` | Block ID. |
| 311 | internalCompanyprofileid | `Float` | Companyprofileid |
| 312 | internalGroupprofileid | `Float` | Groupprofileid |
| 313 | internalSourceprofileid | `Float` | Sourceprofileid |
| 314 | itemsQuantities | `String` | Items and Quantities |
| 315 | jRNUpdateDate | `Date` | JRN Update Date |
| 316 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 317 | keyValidUntil | `Date` | Key Valid Until |
| 318 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 319 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the Periodic Batch Folios option |
| 320 | lastRoomNumber | `String` | Not used. |
| 321 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the Direct Bill Batch Folios option |
| 322 | leadTimeDays | `Float` | Lead Time for ordering |
| 323 | lengthOfStay | `Float` | Length of Stay |
| 324 | linkedArrivalDate | `Date` | Linked Arrival Date |
| 325 | linkedDepartureDate | `Date` | Linked Departure Date |
| 326 | linkedRoomType | `String` | Linked Room Type |
| 327 | listOfMembershipID | `String` | Membership ID |
| 328 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 329 | locationID | `String` | Internal ID to uniquely identify the Property |
| 330 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 331 | mailYn | `String` | Mail Y/N |
| 332 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 333 | marketCode | `String` | Market Code |
| 334 | marketid | `String` | Marketid |
| 335 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 336 | mcGenBeginState | `String` | Mc Gen Begin State |
| 337 | mcGenEndDistrict | `String` | Mc Gen End District |
| 338 | mcGenEndState | `String` | Mc Gen End State |
| 339 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 340 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 341 | memberDescription | `String` | Member Description |
| 342 | memberLevel | `String` | Member Level |
| 343 | memberNumber | `String` | Member Number |
| 344 | membershipClass | `String` | Membership Class |
| 345 | membershipClassDescription | `String` | Membership Class Description |
| 346 | membershipCode | `String` | Membership Code |
| 347 | membershipId | `Float` | Membership ID |
| 348 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 349 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 350 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 351 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 352 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 353 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 354 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 355 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 356 | name | `String` | Name |
| 357 | nameUsageType | `String` | Name Usage Type |
| 358 | nextCountry | `String` | Next Country |
| 359 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 360 | numberOfRooms | `Float` | No of Rooms |
| 361 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 362 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 363 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 364 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 365 | originCode | `String` | Origin Code |
| 366 | originOfBooking | `String` | Origin Of Booking |
| 367 | originalBaseRate | `Float` | Not used. |
| 368 | originalEndDate | `Date` | Original End Date |
| 369 | originalStartDate | `Date` | Original Start Date |
| 370 | ownerFfFlag | `String` | Owner Ff Flag |
| 371 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 372 | packageCode | `String` | Package Code |
| 373 | packageCodeDescription | `String` | Package Code Description |
| 374 | packageForecastGroup | `String` | Package Forecast Group |
| 375 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 376 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 377 | parentreservationid | `Float` | Parentreservationid |
| 378 | partAllotment | `String` | Part Allotment |
| 379 | partyCode | `String` | Party Code |
| 380 | paxNo | `Float` | Pax Number |
| 381 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 382 | paymentMethod | `String` | Payment Method |
| 383 | paymentmethodid | `String` | Paymentmethodid |
| 384 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 385 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 386 | phoneId | `Float` | Phone ID |
| 387 | physicalQuantity | `Float` | Physical Quantity |
| 388 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 389 | pickUpDate | `Date` | Pick Up Date |
| 390 | pickUpStation | `String` | Pick Up Station |
| 391 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 392 | pickUpType | `String` | Pick Up Type |
| 393 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 394 | pickUpTime | `String` | Pick-Up Time |
| 395 | pickupRequiredYN | `String` | Pickup Required YN |
| 396 | points | `Float` | Points |
| 397 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 398 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 399 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 400 | postingAllowedYN | `String` | Posting Allowed YN |
| 401 | preArrReviewedDt | `Date` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 402 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 403 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 404 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 405 | preference | `String` | Preference |
| 406 | preferenceType | `String` | Preference Type |
| 407 | preferredRoomType | `String` | Preferred Room Type |
| 408 | previousCountry | `String` | Previous Country |
| 409 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 410 | primaryShare | `String` | Primary Share |
| 411 | printRateYN | `String` | Print Rate YN |
| 412 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 413 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 414 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 415 | promotionCode | `String` | Promotion Code |
| 416 | promotionDescription | `String` | Promotion Description |
| 417 | property | `String` | Indicates if the value set for the specific property. |
| 418 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 419 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 420 | purgeDate | `DateTime` | Purge Date |
| 421 | purposeOfStay | `String` | Purpose of stay. |
| 422 | quantity | `Float` | Number of Rooms |
| 423 | queuePriority | `Float` | Queue priority of the reservation. |
| 424 | queueWaitTime | `Float` | Queue Wait Time |
| 425 | quoteId | `String` | Quote ID provided by external system. |
| 426 | rateAmount | `Float` | Rate Amount |
| 427 | rateCode | `String` | Rate Code |
| 428 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 429 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 430 | rateableValue | `Float` | Stay rateable value. |
| 431 | ratecodeid | `String` | Ratecodeid |
| 432 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 433 | rdResvStatus | `String` | Rd Reservation Status |
| 434 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 435 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 436 | rdenReservationDate | `Date` | Rden Reservation Date |
| 437 | rdenResort | `String` | Rden Property |
| 438 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 439 | registrationCardNo | `String` | Registration Card Number |
| 440 | registrationNumber | `Float` | Registration Number |
| 441 | reinstateDate | `Date` | Reinstate Date |
| 442 | repChannel | `String` | Reporting Channel |
| 443 | repChannelDescription | `String` | Reporting Channel Description |
| 444 | reportId | `String` | Report ID |
| 445 | resInsertSource | `String` | Reservation Insert Source |
| 446 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 447 | reservationContactId | `Float` | Resv Contact ID |
| 448 | reservationDate | `DateTime` | Reservation Date |
| 449 | reservationNameID | `Float` | Reservation Name ID |
| 450 | reservationStatus | `String` | Reservation Status |
| 451 | reservationType | `String` | Reservation Type |
| 452 | reservationTypeDescription | `String` | Reservation Type Description |
| 453 | reservationid | `Float` | Reservationid |
| 454 | resort | `String` | Property |
| 455 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 456 | restrictionOverride | `String` | Restriction Override |
| 457 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 458 | resvNameid | `Float` | Reservation Nameid |
| 459 | resvNumber | `Float` | Not used in PMS currently. |
| 460 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 461 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 462 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 463 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 464 | rhRoomFeatures | `String` | Rh Room Features |
| 465 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 466 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 467 | room | `String` | Room |
| 468 | roomCategory | `String` | Room Category |
| 469 | roomClass | `String` | Room Class |
| 470 | roomCost | `Float` | Room Cost |
| 471 | roomInstructions | `String` | Room Instructions |
| 472 | roomResort | `String` | Meeting Room Property |
| 473 | roomRevenue | `Float` | Room Revenue |
| 474 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 475 | roomServiceTime | `String` | This is the Turndown room service time. |
| 476 | roomTypeDescription | `String` | Room Type Description |
| 477 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 478 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 479 | roomcategoryid | `String` | Roomcategoryid |
| 480 | roomid | `String` | Roomid |
| 481 | routingYN | `String` | Routing YN |
| 482 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 483 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 484 | sguestName | `String` | Sguest Name |
| 485 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 486 | shareId | `Float` | Share ID. |
| 487 | shareName | `String` | Share Name |
| 488 | sharePrcnt | `Float` | Not used. |
| 489 | shareSeqNumber | `Float` | Type of revenue |
| 490 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 491 | sharedGuestName | `String` | Shared Guest Name |
| 492 | sharedProfileID | `Float` | Shared Profile ID |
| 493 | sharedReservationStatus | `String` | Shared Reservation Status |
| 494 | sharingYN | `String` | Sharing YN |
| 495 | sourceCity | `String` | Source City |
| 496 | sourceCode | `String` | Source Code |
| 497 | sourceCountry | `String` | Source Country |
| 498 | sourceName | `String` | Source Name |
| 499 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 500 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 501 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 502 | sourceProfileID | `Float` | Source Profile ID |
| 503 | sourceProfileName | `String` | Source Profile Name |
| 504 | sourceid | `String` | Sourceid |
| 505 | specialRequest | `String` | Special Request |
| 506 | specialRequestDescription | `String` | Special Request Description |
| 507 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 508 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 509 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 510 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 511 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 512 | splitfromreservationid | `Float` | Splitfromreservationid |
| 513 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 514 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 515 | stayRecordId | `Float` | Stay Record ID |
| 516 | suiteNumber | `String` | Suite Number |
| 517 | superSearchIndexText | `String` | Super Search Index Text |
| 518 | taRecordLocator | `String` | Ta Record Locator |
| 519 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 520 | taxNumberOfStays | `Float` | Tax No of Stays |
| 521 | taxType | `String` | Tax Type |
| 522 | taxTypeDescription | `String` | Tax Type Description |
| 523 | taxtypeid | `String` | Taxtypeid |
| 524 | tiad | `String` | Tiad |
| 525 | ticketNos | `String` | Ticket Nos |
| 526 | totalCostOfStay | `Float` | Total Cost of Stay |
| 527 | totalRevenue | `Float` | Total Revenue |
| 528 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 529 | totalRoomRate | `Float` | Total Room Rate |
| 530 | trackItGroups | `String` | Track It Groups |
| 531 | trackItTypes | `String` | Track It Types |
| 532 | transactionid | `Float` | Transactionid |
| 533 | travelAgentCity | `String` | Travel Agent Address. |
| 534 | travelAgentCountry | `String` | Travel Agent Country |
| 535 | travelAgentID | `Float` | Travel Agent ID |
| 536 | travelAgentName | `String` | Travel Agent Name |
| 537 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 538 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 539 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 540 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 541 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 542 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 543 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 544 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 545 | uDFC01 | `String` | UDFC01 |
| 546 | uDFC02 | `String` | UDFC02 |
| 547 | uDFC03 | `String` | UDFC03 |
| 548 | uDFC04 | `String` | UDFC04 |
| 549 | uDFC05 | `String` | UDFC05 |
| 550 | uDFC06 | `String` | UDFC06 |
| 551 | uDFC07 | `String` | UDFC07 |
| 552 | uDFC08 | `String` | UDFC08 |
| 553 | uDFC09 | `String` | UDFC09 |
| 554 | uDFC10 | `String` | UDFC10 |
| 555 | uDFC11 | `String` | UDFC11 |
| 556 | uDFC12 | `String` | UDFC12 |
| 557 | uDFC13 | `String` | UDFC13 |
| 558 | uDFC14 | `String` | UDFC14 |
| 559 | uDFC15 | `String` | UDFC15 |
| 560 | uDFC16 | `String` | UDFC16 |
| 561 | uDFC17 | `String` | UDFC17 |
| 562 | uDFC18 | `String` | UDFC18 |
| 563 | uDFC19 | `String` | UDFC19 |
| 564 | uDFC20 | `String` | UDFC20 |
| 565 | uDFC21 | `String` | UDFC21 |
| 566 | uDFC22 | `String` | UDFC22 |
| 567 | uDFC23 | `String` | UDFC23 |
| 568 | uDFC24 | `String` | UDFC24 |
| 569 | uDFC25 | `String` | UDFC25 |
| 570 | uDFC26 | `String` | UDFC26 |
| 571 | uDFC27 | `String` | UDFC27 |
| 572 | uDFC28 | `String` | UDFC28 |
| 573 | uDFC29 | `String` | UDFC29 |
| 574 | uDFC30 | `String` | UDFC30 |
| 575 | uDFC31 | `String` | UDFC31 |
| 576 | uDFC32 | `String` | UDFC32 |
| 577 | uDFC33 | `String` | UDFC33 |
| 578 | uDFC34 | `String` | UDFC34 |
| 579 | uDFC35 | `String` | UDFC35 |
| 580 | uDFC36 | `String` | UDFC36 |
| 581 | uDFC37 | `String` | UDFC37 |
| 582 | uDFC38 | `String` | UDFC38 |
| 583 | uDFC39 | `String` | UDFC39 |
| 584 | uDFC40 | `String` | UDFC40 |
| 585 | uDFD01 | `Date` | UDFD01 |
| 586 | uDFD02 | `Date` | UDFD02 |
| 587 | uDFD03 | `Date` | UDFD03 |
| 588 | uDFD04 | `Date` | UDFD04 |
| 589 | uDFD05 | `Date` | UDFD05 |
| 590 | uDFD06 | `Date` | UDFD06 |
| 591 | uDFD07 | `Date` | UDFD07 |
| 592 | uDFD08 | `Date` | UDFD08 |
| 593 | uDFD09 | `Date` | UDFD09 |
| 594 | uDFD10 | `Date` | UDFD10 |
| 595 | uDFD11 | `Date` | UDFD11 |
| 596 | uDFD12 | `Date` | UDFD12 |
| 597 | uDFD13 | `Date` | UDFD13 |
| 598 | uDFD14 | `Date` | UDFD14 |
| 599 | uDFD15 | `Date` | UDFD15 |
| 600 | uDFD16 | `Date` | UDFD16 |
| 601 | uDFD17 | `Date` | UDFD17 |
| 602 | uDFD18 | `Date` | UDFD18 |
| 603 | uDFD19 | `Date` | UDFD19 |
| 604 | uDFD20 | `Date` | UDFD20 |
| 605 | uDFN01 | `Float` | UDFN01 |
| 606 | uDFN02 | `Float` | UDFN02 |
| 607 | uDFN03 | `Float` | UDFN03 |
| 608 | uDFN04 | `Float` | UDFN04 |
| 609 | uDFN05 | `Float` | UDFN05 |
| 610 | uDFN06 | `Float` | UDFN06 |
| 611 | uDFN07 | `Float` | UDFN07 |
| 612 | uDFN08 | `Float` | UDFN08 |
| 613 | uDFN09 | `Float` | UDFN09 |
| 614 | uDFN10 | `Float` | UDFN10 |
| 615 | uDFN11 | `Float` | UDFN11 |
| 616 | uDFN12 | `Float` | UDFN12 |
| 617 | uDFN13 | `Float` | UDFN13 |
| 618 | uDFN14 | `Float` | UDFN14 |
| 619 | uDFN15 | `Float` | UDFN15 |
| 620 | uDFN16 | `Float` | UDFN16 |
| 621 | uDFN17 | `Float` | UDFN17 |
| 622 | uDFN18 | `Float` | UDFN18 |
| 623 | uDFN19 | `Float` | UDFN19 |
| 624 | uDFN20 | `Float` | UDFN20 |
| 625 | uDFN21 | `Float` | UDFN21 |
| 626 | uDFN22 | `Float` | UDFN22 |
| 627 | uDFN23 | `Float` | UDFN23 |
| 628 | uDFN24 | `Float` | UDFN24 |
| 629 | uDFN25 | `Float` | UDFN25 |
| 630 | uDFN26 | `Float` | UDFN26 |
| 631 | uDFN27 | `Float` | UDFN27 |
| 632 | uDFN28 | `Float` | UDFN28 |
| 633 | uDFN29 | `Float` | UDFN29 |
| 634 | uDFN30 | `Float` | UDFN30 |
| 635 | uDFN31 | `Float` | UDFN31 |
| 636 | uDFN32 | `Float` | UDFN32 |
| 637 | uDFN33 | `Float` | UDFN33 |
| 638 | uDFN34 | `Float` | UDFN34 |
| 639 | uDFN35 | `Float` | UDFN35 |
| 640 | uDFN36 | `Float` | UDFN36 |
| 641 | uDFN37 | `Float` | UDFN37 |
| 642 | uDFN38 | `Float` | UDFN38 |
| 643 | uDFN39 | `Float` | UDFN39 |
| 644 | uDFN40 | `Float` | UDFN40 |
| 645 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 646 | updateDate | `DateTime` | Update Date |
| 647 | updateDatetime | `DateTime` | Update Datetime |
| 648 | updateUser | `Float` | Update User |
| 649 | updatedBy | `String` | Updated By |
| 650 | updatedByDefaultResort | `String` | Updated By Default Property |
| 651 | updatedDate | `Date` | Updated Date |
| 652 | updatedTime | `String` | Updated Time |
| 653 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 654 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 655 | visaExpiryDate | `Date` | Visa Expiry Date |
| 656 | visaIssueDate | `Date` | Visa Issue Date |
| 657 | visaNumber | `String` | Visa Number |
| 658 | waitlistComment | `String` | Waitlist Comment |
| 659 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 660 | waitlistPriority | `String` | Waitlist Priority |
| 661 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 662 | waitlistReason | `String` | Waitlist Reason |
| 663 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 664 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 665 | waitlistreasonid | `String` | Waitlistreasonid |
| 666 | walkInYN | `String` | Walk-In YN |
| 667 | yieldableYn | `String` | Yieldable Y/N |
| 668 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingsReservationSharedReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `Date` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `Date` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `Date` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `Date` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `Date` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `Date` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `Date` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | channelDescription | `String` | Channel Description |
| 152 | channelOrderBy | `Float` | Channel Order By |
| 153 | channelid | `String` | Channelid |
| 154 | checkInInitiatedBy | `String` | Check In Initiated By |
| 155 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 156 | childBucket1 | `Float` | Child Bucket 1 |
| 157 | childBucket4 | `Float` | Child Bucket 4 |
| 158 | childBucket5 | `Float` | Child Bucket 5 |
| 159 | children | `Float` | Children |
| 160 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 161 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 162 | childrenAges | `String` | Children Ages |
| 163 | commissionCode | `String` | Commission Code |
| 164 | commissionDescription | `String` | Commission Description |
| 165 | commissionHoldCode | `String` | Commission Hold Code |
| 166 | commissionPaid | `Float` | Commission Paid |
| 167 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 168 | commissionableYN | `String` | Commissionable YN |
| 169 | commissionid | `String` | Commissionid |
| 170 | compHouse | `String` | Comp House |
| 171 | compTypeCode | `String` | Comp Type Code |
| 172 | companyCity | `String` | Company City |
| 173 | companyCountry | `String` | Company Country |
| 174 | companyID | `Float` | Company ID |
| 175 | companyName | `String` | Company Name |
| 176 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 177 | companyProfileID | `Float` | Company Profile ID |
| 178 | complimentaryYN | `String` | Complimentary YN |
| 179 | compreasonid | `String` | Compreasonid |
| 180 | computedResvStatus | `String` | Calculated reservation status. |
| 181 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 182 | confirmationNo | `String` | Shared Confirmation Number |
| 183 | consumerYn | `String` | Consumer Y/N |
| 184 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 185 | contactProfileID | `Float` | Contact Profile ID |
| 186 | contactProfileName | `String` | Contact Profile Name |
| 187 | createdBy | `String` | The name of the user who created the record. |
| 188 | createdByDefaultResort | `String` | Created By Default Property |
| 189 | createdDate | `Date` | Created Date |
| 190 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 191 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 192 | creditCardId | `Float` | Credit Card ID |
| 193 | creditLimit | `Float` | Credit Limit |
| 194 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 195 | cribs | `Float` | Cribs |
| 196 | currencyCode | `String` | Currency Code |
| 197 | customReferenceNumber | `String` | Custom Reference Number |
| 198 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 199 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 200 | deletedFlag | `String` | Deleted Flag |
| 201 | departtransportid | `String` | Departtransportid |
| 202 | departureComments | `String` | Departure Comments |
| 203 | departureDate | `Date` | Departure Date |
| 204 | departureDateTime | `Date` | Departure Date Time |
| 205 | departureTime | `String` | Departure Time |
| 206 | departureTransportCode | `String` | Departure Transport Code |
| 207 | departureTransportationYN | `String` | Departure Transportation YN |
| 208 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 209 | detatchedDate | `Date` | Detatched Date |
| 210 | detatchedYN | `String` | Detatched YN |
| 211 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 212 | directbillauthby | `Float` | Directbillauthby |
| 213 | discountAmount | `Float` | Discount Amount |
| 214 | discountAmt | `Float` | Discount Amount |
| 215 | discountPercent | `Float` | Discount Percentage. |
| 216 | discountPrcnt | `Float` | Discount Prcnt |
| 217 | discountReason | `String` | Discount Reason |
| 218 | discountReasonDescription | `String` | Discount Reason Description |
| 219 | discountreasonid | `String` | Discountreasonid |
| 220 | displayColor | `String` | Display Color |
| 221 | dmlSeqNumber | `Float` | Dml Sequence No |
| 222 | doNotMoveRoom | `String` | Do Not Move Room |
| 223 | doNotMoveYN | `String` | Do not move room flag. |
| 224 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 225 | dropOffDate | `Date` | Drop Off Date |
| 226 | dropOffStation | `String` | Drop Off Station |
| 227 | dropOffTime | `String` | Drop Off Time |
| 228 | dropOffType | `String` | Drop Off Type |
| 229 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 230 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 231 | effectiveRateAmount | `Float` | Not used. |
| 232 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 233 | emailAddress | `String` | Email Address |
| 234 | emailFolioYn | `String` | Email Folio Y/N |
| 235 | emailId | `Float` | Email ID |
| 236 | emailYn | `String` | Email Y/N |
| 237 | endCity | `String` | End City |
| 238 | endDatetime | `Date` | End Datetime |
| 239 | endDistrict | `String` | End District |
| 240 | endState | `String` | End State |
| 241 | endbusinessdate | `Date` | Endbusinessdate |
| 242 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 243 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 244 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 245 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 246 | eventId | `Float` | Event ID |
| 247 | exchangePostingType | `String` | Exchange Posting Type |
| 248 | exchangeRate | `Float` | Exchange Rate |
| 249 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 250 | expectedTimeOfReturnETR | `Date` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 251 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 252 | extSegNo | `Float` | Not used |
| 253 | extSeqNumber | `Float` | Not used |
| 254 | extensionId | `Float` | Internal extension number for the main reservation |
| 255 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 256 | externalReference | `String` | External Reference |
| 257 | externalReferencesList | `String` | External References List |
| 258 | extraBeds | `Float` | Extra Beds |
| 259 | fBRevenue | `Float` | FB Revenue |
| 260 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 261 | faxId | `Float` | Fax ID |
| 262 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 263 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 264 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 265 | fixedCharge | `Float` | Not used. |
| 266 | fixedRateYN | `String` | Fixed Rate YN |
| 267 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 268 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 269 | folioNumber | `String` | Folio Number |
| 270 | folioText1 | `String` | Folio Text1 |
| 271 | folioText2 | `String` | Folio Text2 |
| 272 | foreignCurrencyID | `String` | Foreign Currency ID |
| 273 | freeChild | `Float` | Free Child |
| 274 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 275 | grossRateFuture | `Float` | Gross Rate Future |
| 276 | grossRatePast | `Float` | Gross Rate Past |
| 277 | groupName | `String` | Group Name |
| 278 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 279 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 280 | groupProfileClientID | `String` | Group Profile Client ID |
| 281 | groupProfileID | `Float` | Group Profile ID |
| 282 | groupProfileName | `String` | Group Profile Name |
| 283 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 284 | guaranteecodeid | `String` | Guaranteecodeid |
| 285 | guestFirstName | `String` | Guest First Name |
| 286 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 287 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 288 | guestSignature | `String` | Signature of the guest |
| 289 | guestStatus | `String` | Used for Police/Tourist Export |
| 290 | guestType | `String` | Guest Type |
| 291 | guestprofileid | `Float` | Guestprofileid |
| 292 | gueststatusid | `String` | Gueststatusid |
| 293 | guesttypeid | `String` | Guesttypeid |
| 294 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 295 | hurdle | `Float` | Hurdle |
| 296 | hurdleOverride | `String` | Hurdle Override |
| 297 | iDByMembershipClass | `String` | ID by Membership Class |
| 298 | iDByMembershipType | `String` | ID by Membership Type |
| 299 | individualCity | `String` | Guest Address. |
| 300 | individualCountry | `String` | Country of the guest |
| 301 | individualFirstName | `String` | Individual First Name |
| 302 | individualLastName | `String` | Individual Last Name |
| 303 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 304 | insertDate | `DateTime` | Insert Date |
| 305 | insertDateTime | `DateTime` | Insert DateTime |
| 306 | insertUser | `Float` | Insert User |
| 307 | intermediaryYn | `String` | Intermediary Y/N |
| 308 | internalAwardMembershipId | `Float` | Award Membership ID |
| 309 | internalBaseratecode | `String` | Baseratecode |
| 310 | internalBlockId | `Float` | Block ID. |
| 311 | internalCompanyprofileid | `Float` | Companyprofileid |
| 312 | internalGroupprofileid | `Float` | Groupprofileid |
| 313 | internalSourceprofileid | `Float` | Sourceprofileid |
| 314 | itemsQuantities | `String` | Items and Quantities |
| 315 | jRNUpdateDate | `Date` | JRN Update Date |
| 316 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 317 | keyValidUntil | `Date` | Key Valid Until |
| 318 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 319 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the Periodic Batch Folios option |
| 320 | lastRoomNumber | `String` | Not used. |
| 321 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the Direct Bill Batch Folios option |
| 322 | leadTimeDays | `Float` | Lead Time for ordering |
| 323 | lengthOfStay | `Float` | Length of Stay |
| 324 | linkedArrivalDate | `Date` | Linked Arrival Date |
| 325 | linkedDepartureDate | `Date` | Linked Departure Date |
| 326 | linkedRoomType | `String` | Linked Room Type |
| 327 | listOfMembershipID | `String` | Membership ID |
| 328 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 329 | locationID | `String` | Internal ID to uniquely identify the Property |
| 330 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 331 | mailYn | `String` | Mail Y/N |
| 332 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 333 | marketCode | `String` | Market Code |
| 334 | marketid | `String` | Marketid |
| 335 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 336 | mcGenBeginState | `String` | Mc Gen Begin State |
| 337 | mcGenEndDistrict | `String` | Mc Gen End District |
| 338 | mcGenEndState | `String` | Mc Gen End State |
| 339 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 340 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 341 | memberDescription | `String` | Member Description |
| 342 | memberLevel | `String` | Member Level |
| 343 | memberNumber | `String` | Member Number |
| 344 | membershipClass | `String` | Membership Class |
| 345 | membershipClassDescription | `String` | Membership Class Description |
| 346 | membershipCode | `String` | Membership Code |
| 347 | membershipId | `Float` | Membership ID |
| 348 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 349 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 350 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 351 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 352 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 353 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 354 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 355 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 356 | name | `String` | Name |
| 357 | nameUsageType | `String` | Name Usage Type |
| 358 | nextCountry | `String` | Next Country |
| 359 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 360 | numberOfRooms | `Float` | No of Rooms |
| 361 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 362 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 363 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 364 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 365 | originCode | `String` | Origin Code |
| 366 | originOfBooking | `String` | Origin Of Booking |
| 367 | originalBaseRate | `Float` | Not used. |
| 368 | originalEndDate | `Date` | Original End Date |
| 369 | originalStartDate | `Date` | Original Start Date |
| 370 | ownerFfFlag | `String` | Owner Ff Flag |
| 371 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 372 | packageCode | `String` | Package Code |
| 373 | packageCodeDescription | `String` | Package Code Description |
| 374 | packageForecastGroup | `String` | Package Forecast Group |
| 375 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 376 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 377 | parentreservationid | `Float` | Parentreservationid |
| 378 | partAllotment | `String` | Part Allotment |
| 379 | partyCode | `String` | Party Code |
| 380 | paxNo | `Float` | Pax Number |
| 381 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 382 | paymentMethod | `String` | Payment Method |
| 383 | paymentmethodid | `String` | Paymentmethodid |
| 384 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 385 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 386 | phoneId | `Float` | Phone ID |
| 387 | physicalQuantity | `Float` | Physical Quantity |
| 388 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 389 | pickUpDate | `Date` | Pick Up Date |
| 390 | pickUpStation | `String` | Pick Up Station |
| 391 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 392 | pickUpType | `String` | Pick Up Type |
| 393 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 394 | pickUpTime | `String` | Pick-Up Time |
| 395 | pickupRequiredYN | `String` | Pickup Required YN |
| 396 | points | `Float` | Points |
| 397 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 398 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 399 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 400 | postingAllowedYN | `String` | Posting Allowed YN |
| 401 | preArrReviewedDt | `Date` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 402 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 403 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 404 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 405 | preference | `String` | Preference |
| 406 | preferenceType | `String` | Preference Type |
| 407 | preferredRoomType | `String` | Preferred Room Type |
| 408 | previousCountry | `String` | Previous Country |
| 409 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 410 | primaryShare | `String` | Primary Share |
| 411 | printRateYN | `String` | Print Rate YN |
| 412 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 413 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 414 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 415 | promotionCode | `String` | Promotion Code |
| 416 | promotionDescription | `String` | Promotion Description |
| 417 | property | `String` | Indicates if the value set for the specific property. |
| 418 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 419 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 420 | purgeDate | `DateTime` | Purge Date |
| 421 | purposeOfStay | `String` | Purpose of stay. |
| 422 | quantity | `Float` | Number of Rooms |
| 423 | queuePriority | `Float` | Queue priority of the reservation. |
| 424 | queueWaitTime | `Float` | Queue Wait Time |
| 425 | quoteId | `String` | Quote ID provided by external system. |
| 426 | rateAmount | `Float` | Rate Amount |
| 427 | rateCode | `String` | Rate Code |
| 428 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 429 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 430 | rateableValue | `Float` | Stay rateable value. |
| 431 | ratecodeid | `String` | Ratecodeid |
| 432 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 433 | rdResvStatus | `String` | Rd Reservation Status |
| 434 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 435 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 436 | rdenReservationDate | `Date` | Rden Reservation Date |
| 437 | rdenResort | `String` | Rden Property |
| 438 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 439 | registrationCardNo | `String` | Registration Card Number |
| 440 | registrationNumber | `Float` | Registration Number |
| 441 | reinstateDate | `Date` | Reinstate Date |
| 442 | repChannel | `String` | Reporting Channel |
| 443 | repChannelDescription | `String` | Reporting Channel Description |
| 444 | reportId | `String` | Report ID |
| 445 | resInsertSource | `String` | Reservation Insert Source |
| 446 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 447 | reservationContactId | `Float` | Resv Contact ID |
| 448 | reservationDate | `DateTime` | Reservation Date |
| 449 | reservationNameID | `Float` | Reservation Name ID |
| 450 | reservationStatus | `String` | Reservation Status |
| 451 | reservationType | `String` | Reservation Type |
| 452 | reservationTypeDescription | `String` | Reservation Type Description |
| 453 | reservationid | `Float` | Reservationid |
| 454 | resort | `String` | Property |
| 455 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 456 | restrictionOverride | `String` | Restriction Override |
| 457 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 458 | resvNameid | `Float` | Reservation Nameid |
| 459 | resvNumber | `Float` | Not used in PMS currently. |
| 460 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 461 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 462 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 463 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 464 | rhRoomFeatures | `String` | Rh Room Features |
| 465 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 466 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 467 | room | `String` | Room |
| 468 | roomCategory | `String` | Room Category |
| 469 | roomClass | `String` | Room Class |
| 470 | roomCost | `Float` | Room Cost |
| 471 | roomInstructions | `String` | Room Instructions |
| 472 | roomResort | `String` | Meeting Room Property |
| 473 | roomRevenue | `Float` | Room Revenue |
| 474 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 475 | roomServiceTime | `String` | This is the Turndown room service time. |
| 476 | roomTypeDescription | `String` | Room Type Description |
| 477 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 478 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 479 | roomcategoryid | `String` | Roomcategoryid |
| 480 | roomid | `String` | Roomid |
| 481 | routingYN | `String` | Routing YN |
| 482 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 483 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 484 | sguestName | `String` | Sguest Name |
| 485 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 486 | shareId | `Float` | Share ID. |
| 487 | shareName | `String` | Share Name |
| 488 | sharePrcnt | `Float` | Not used. |
| 489 | shareSeqNumber | `Float` | Type of revenue |
| 490 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 491 | sharedGuestName | `String` | Shared Guest Name |
| 492 | sharedProfileID | `Float` | Shared Profile ID |
| 493 | sharedReservationStatus | `String` | Shared Reservation Status |
| 494 | sharingYN | `String` | Sharing YN |
| 495 | sourceCity | `String` | Source City |
| 496 | sourceCode | `String` | Source Code |
| 497 | sourceCountry | `String` | Source Country |
| 498 | sourceName | `String` | Source Name |
| 499 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 500 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 501 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 502 | sourceProfileID | `Float` | Source Profile ID |
| 503 | sourceProfileName | `String` | Source Profile Name |
| 504 | sourceid | `String` | Sourceid |
| 505 | specialRequest | `String` | Special Request |
| 506 | specialRequestDescription | `String` | Special Request Description |
| 507 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 508 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 509 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 510 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 511 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 512 | splitfromreservationid | `Float` | Splitfromreservationid |
| 513 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 514 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 515 | stayRecordId | `Float` | Stay Record ID |
| 516 | suiteNumber | `String` | Suite Number |
| 517 | superSearchIndexText | `String` | Super Search Index Text |
| 518 | taRecordLocator | `String` | Ta Record Locator |
| 519 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 520 | taxNumberOfStays | `Float` | Tax No of Stays |
| 521 | taxType | `String` | Tax Type |
| 522 | taxTypeDescription | `String` | Tax Type Description |
| 523 | taxtypeid | `String` | Taxtypeid |
| 524 | tiad | `String` | Tiad |
| 525 | ticketNos | `String` | Ticket Nos |
| 526 | totalCostOfStay | `Float` | Total Cost of Stay |
| 527 | totalRevenue | `Float` | Total Revenue |
| 528 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 529 | totalRoomRate | `Float` | Total Room Rate |
| 530 | trackItGroups | `String` | Track It Groups |
| 531 | trackItTypes | `String` | Track It Types |
| 532 | transactionid | `Float` | Transactionid |
| 533 | travelAgentCity | `String` | Travel Agent Address. |
| 534 | travelAgentCountry | `String` | Travel Agent Country |
| 535 | travelAgentID | `Float` | Travel Agent ID |
| 536 | travelAgentName | `String` | Travel Agent Name |
| 537 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 538 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 539 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 540 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 541 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 542 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 543 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 544 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 545 | uDFC01 | `String` | UDFC01 |
| 546 | uDFC02 | `String` | UDFC02 |
| 547 | uDFC03 | `String` | UDFC03 |
| 548 | uDFC04 | `String` | UDFC04 |
| 549 | uDFC05 | `String` | UDFC05 |
| 550 | uDFC06 | `String` | UDFC06 |
| 551 | uDFC07 | `String` | UDFC07 |
| 552 | uDFC08 | `String` | UDFC08 |
| 553 | uDFC09 | `String` | UDFC09 |
| 554 | uDFC10 | `String` | UDFC10 |
| 555 | uDFC11 | `String` | UDFC11 |
| 556 | uDFC12 | `String` | UDFC12 |
| 557 | uDFC13 | `String` | UDFC13 |
| 558 | uDFC14 | `String` | UDFC14 |
| 559 | uDFC15 | `String` | UDFC15 |
| 560 | uDFC16 | `String` | UDFC16 |
| 561 | uDFC17 | `String` | UDFC17 |
| 562 | uDFC18 | `String` | UDFC18 |
| 563 | uDFC19 | `String` | UDFC19 |
| 564 | uDFC20 | `String` | UDFC20 |
| 565 | uDFC21 | `String` | UDFC21 |
| 566 | uDFC22 | `String` | UDFC22 |
| 567 | uDFC23 | `String` | UDFC23 |
| 568 | uDFC24 | `String` | UDFC24 |
| 569 | uDFC25 | `String` | UDFC25 |
| 570 | uDFC26 | `String` | UDFC26 |
| 571 | uDFC27 | `String` | UDFC27 |
| 572 | uDFC28 | `String` | UDFC28 |
| 573 | uDFC29 | `String` | UDFC29 |
| 574 | uDFC30 | `String` | UDFC30 |
| 575 | uDFC31 | `String` | UDFC31 |
| 576 | uDFC32 | `String` | UDFC32 |
| 577 | uDFC33 | `String` | UDFC33 |
| 578 | uDFC34 | `String` | UDFC34 |
| 579 | uDFC35 | `String` | UDFC35 |
| 580 | uDFC36 | `String` | UDFC36 |
| 581 | uDFC37 | `String` | UDFC37 |
| 582 | uDFC38 | `String` | UDFC38 |
| 583 | uDFC39 | `String` | UDFC39 |
| 584 | uDFC40 | `String` | UDFC40 |
| 585 | uDFD01 | `Date` | UDFD01 |
| 586 | uDFD02 | `Date` | UDFD02 |
| 587 | uDFD03 | `Date` | UDFD03 |
| 588 | uDFD04 | `Date` | UDFD04 |
| 589 | uDFD05 | `Date` | UDFD05 |
| 590 | uDFD06 | `Date` | UDFD06 |
| 591 | uDFD07 | `Date` | UDFD07 |
| 592 | uDFD08 | `Date` | UDFD08 |
| 593 | uDFD09 | `Date` | UDFD09 |
| 594 | uDFD10 | `Date` | UDFD10 |
| 595 | uDFD11 | `Date` | UDFD11 |
| 596 | uDFD12 | `Date` | UDFD12 |
| 597 | uDFD13 | `Date` | UDFD13 |
| 598 | uDFD14 | `Date` | UDFD14 |
| 599 | uDFD15 | `Date` | UDFD15 |
| 600 | uDFD16 | `Date` | UDFD16 |
| 601 | uDFD17 | `Date` | UDFD17 |
| 602 | uDFD18 | `Date` | UDFD18 |
| 603 | uDFD19 | `Date` | UDFD19 |
| 604 | uDFD20 | `Date` | UDFD20 |
| 605 | uDFN01 | `Float` | UDFN01 |
| 606 | uDFN02 | `Float` | UDFN02 |
| 607 | uDFN03 | `Float` | UDFN03 |
| 608 | uDFN04 | `Float` | UDFN04 |
| 609 | uDFN05 | `Float` | UDFN05 |
| 610 | uDFN06 | `Float` | UDFN06 |
| 611 | uDFN07 | `Float` | UDFN07 |
| 612 | uDFN08 | `Float` | UDFN08 |
| 613 | uDFN09 | `Float` | UDFN09 |
| 614 | uDFN10 | `Float` | UDFN10 |
| 615 | uDFN11 | `Float` | UDFN11 |
| 616 | uDFN12 | `Float` | UDFN12 |
| 617 | uDFN13 | `Float` | UDFN13 |
| 618 | uDFN14 | `Float` | UDFN14 |
| 619 | uDFN15 | `Float` | UDFN15 |
| 620 | uDFN16 | `Float` | UDFN16 |
| 621 | uDFN17 | `Float` | UDFN17 |
| 622 | uDFN18 | `Float` | UDFN18 |
| 623 | uDFN19 | `Float` | UDFN19 |
| 624 | uDFN20 | `Float` | UDFN20 |
| 625 | uDFN21 | `Float` | UDFN21 |
| 626 | uDFN22 | `Float` | UDFN22 |
| 627 | uDFN23 | `Float` | UDFN23 |
| 628 | uDFN24 | `Float` | UDFN24 |
| 629 | uDFN25 | `Float` | UDFN25 |
| 630 | uDFN26 | `Float` | UDFN26 |
| 631 | uDFN27 | `Float` | UDFN27 |
| 632 | uDFN28 | `Float` | UDFN28 |
| 633 | uDFN29 | `Float` | UDFN29 |
| 634 | uDFN30 | `Float` | UDFN30 |
| 635 | uDFN31 | `Float` | UDFN31 |
| 636 | uDFN32 | `Float` | UDFN32 |
| 637 | uDFN33 | `Float` | UDFN33 |
| 638 | uDFN34 | `Float` | UDFN34 |
| 639 | uDFN35 | `Float` | UDFN35 |
| 640 | uDFN36 | `Float` | UDFN36 |
| 641 | uDFN37 | `Float` | UDFN37 |
| 642 | uDFN38 | `Float` | UDFN38 |
| 643 | uDFN39 | `Float` | UDFN39 |
| 644 | uDFN40 | `Float` | UDFN40 |
| 645 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 646 | updateDate | `DateTime` | Update Date |
| 647 | updateDatetime | `DateTime` | Update Datetime |
| 648 | updateUser | `Float` | Update User |
| 649 | updatedBy | `String` | Updated By |
| 650 | updatedByDefaultResort | `String` | Updated By Default Property |
| 651 | updatedDate | `Date` | Updated Date |
| 652 | updatedTime | `String` | Updated Time |
| 653 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 654 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 655 | visaExpiryDate | `Date` | Visa Expiry Date |
| 656 | visaIssueDate | `Date` | Visa Issue Date |
| 657 | visaNumber | `String` | Visa Number |
| 658 | waitlistComment | `String` | Waitlist Comment |
| 659 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 660 | waitlistPriority | `String` | Waitlist Priority |
| 661 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 662 | waitlistReason | `String` | Waitlist Reason |
| 663 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 664 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 665 | waitlistreasonid | `String` | Waitlistreasonid |
| 666 | walkInYN | `String` | Walk-In YN |
| 667 | yieldableYn | `String` | Yieldable Y/N |
| 668 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingsReservationReservationMembershipDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 2 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | earningPreference | `String` | Earning Preference |
| 6 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 7 | hostBusinessDate | `Date` | Business date when the host-multiplier relationship was set. |
| 8 | hostCardinality | `Float` | Number of multipliers attached if a host-multiplier relationship exists. |
| 9 | hostFlag | `String` | Indicator whether the current membership for the rervation is a (H)ost membership detail |
| 10 | iDByMembershipClass | `String` | ID by Membership Class |
| 11 | iDByMembershipType | `String` | ID by Membership Type |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | internalMembershipid | `Float` | Membershipid |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | levelByMembershipType | `String` | Level by Membership Type |
| 18 | listOfMembershipIDs | `Float` | Membership ID |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 21 | mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| 22 | membershipCardNo | `String` | Membership Card Number |
| 23 | membershipCardNumber | `String` | Membership Card Number |
| 24 | membershipClass | `String` | Membership Class |
| 25 | membershipClassDescription | `String` | Membership Class Description |
| 26 | membershipCode | `String` | Membership Code |
| 27 | membershipDescription | `String` | Membership Description |
| 28 | membershipId | `Float` | Membership ID |
| 29 | membershipLevel | `String` | Membership Level |
| 30 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 31 | membershipType | `String` | Membership Type |
| 32 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 33 | multiplierInstance | `Float` | Multiplier instance number if a host-multiplier relationship exists. |
| 34 | nameId | `Float` | Name ID |
| 35 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 36 | pointsMultiplier | `Float` | Indicates any multiplier for the points accumulated. |
| 37 | populationMethod | `String` | Population Method |
| 38 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 39 | processedDate | `Date` | Processed Date |
| 40 | processedYn | `String` | Processed Y/N |
| 41 | profileid | `Float` | Profileid |
| 42 | property | `String` | Code to uniquely identify the Property |
| 43 | rankValue | `Float` | Rank Value |
| 44 | reservationNameId | `Float` | Resv Name ID |
| 45 | reservationid | `Float` | Reservationid |
| 46 | reservationmembershipid | `Float` | Reservationmembershipid |
| 47 | resvenddate | `Date` | Resvenddate |
| 48 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 49 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 50 | updateDate | `DateTime` | Update Date |
| 51 | updateUser | `Float` | Update User |

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

### BookingsReservationQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| reservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsAllotmentid | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsTruncBeginDate | `DateInput` | Arrival Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsBillingContactId | `FloatInput` | Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsAllotmentHeaderId | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsBusinessDateCreated | `DateInput` | Business Date Created<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsCXchangeDate | `DateInput` | Central Xchange Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsCancellationNo | `StringInput` | Cancellation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| reservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsCreditCardId | `FloatInput` | Credit Card ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationDetailsTruncEndDate | `DateInput` | Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsEnddatetime | `DateTimeInput` | End Datetime<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsEventId | `FloatInput` | Event ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed.<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationDetailsGuestprofileid | `FloatInput` | Guestprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsInsertDate | `DateTimeInput` | Insert Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsInsertUser | `FloatInput` | Insert User<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsEndDate | `DateTimeInput` | Linked Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationDetailsOriginalEndDate | `DateInput` | Original End Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsParentreservationid | `FloatInput` | Parentreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationDetailsQuoteId | `StringInput` | Quote ID provided by external system.<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsResvContactId | `FloatInput` | Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsResvNameId | `FloatInput` | Reservation Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsResvStatus | `StringInput` | Reservation Status |
| reservationDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationDetailsReservationid | `FloatInput` | Reservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsResort | `StringInput` | Property<br>`@conditionalInputPair(pair: 1)` |
| reservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationDetailsResvNameid | `FloatInput` | Reservation Nameid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsRoomCategory | `StringInput` | Room Category |
| reservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| reservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationDetailsSguestName | `StringInput` | Sguest Name |
| reservationDetailsNameId | `FloatInput` | Shared Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off.<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component.<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes.<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsUpdateDate | `DateTimeInput` | Update Date<br>`@conditionalInputPair(pair: 2)` |
| reservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime<br>`@conditionalInputPair(pair: 2)` |
| accompanyingguestDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accompanyingguestDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| accompanyingguestDetailsLast | `StringInput` | Last Name |
| accompanyingguestDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accompanyingguestDetailsPkid | `FloatInput` | Primary Key ID |
| accompanyingguestDetailsResort | `StringInput` | Code to uniquely identify the Property |
| accompanyingguestDetailsResvNameId | `FloatInput` | Resv Name ID |
| channelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| channelDetailsEntityName | `StringInput` | Entity Name |
| channelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| channelDetailsLanguageCode | `StringInput` | Language Code |
| channelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| channelDetailsAttributeCode | `StringInput` | Origin Code |
| channelDetailsTitleSuffix | `FloatInput` | Title Suffix |
| externalreferencesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| externalreferencesDetailsExternalReference | `StringInput` | External Reference Number |
| externalreferencesDetailsExternalReferenceType | `StringInput` | Type of external reference depending from what external system the number was passed. |
| externalreferencesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| externalreferencesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| externalreferencesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| externalreferencesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| externalreferencesDetailsResvNameId | `FloatInput` | Resv Name ID |
| externalreferencesDetailsUpperExternalReference | `StringInput` | External reference stored in upper case. |
| fixedchargesDetailsAccountCode | `FloatInput` | Account Code |
| fixedchargesDetailsAccountid | `FloatInput` | Accountid |
| fixedchargesDetailsFixedchargestartdate | `DateInput` | Business Date |
| fixedchargesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| fixedchargesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fixedchargesDetailsFixedchargeenddate | `DateInput` | End Date |
| fixedchargesDetailsFixedChargesId | `FloatInput` | Unique number to identify the entry. |
| fixedchargesDetailsFixedchargespmsref | `FloatInput` | Fixedchargespmsref |
| fixedchargesDetailsFixedchargesid | `FloatInput` | Fixedchargesid |
| fixedchargesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fixedchargesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| fixedchargesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fixedchargesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| fixedchargesDetailsResvNameId | `FloatInput` | Resv Name ID |
| fixedchargesDetailsReservationid | `FloatInput` | Reservationid |
| fixedchargesDetailsTransactionCode | `StringInput` | Rate transaction code |
| fixedchargesDetailsTranscodeid | `StringInput` | Transcodeid |
| guestrsvmessagesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| guestrsvmessagesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| guestrsvmessagesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| guestrsvmessagesDetailsMsgid | `FloatInput` | Msgid |
| guestrsvmessagesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| guestrsvmessagesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| guestrsvmessagesDetailsResvNameId | `FloatInput` | Resv Name ID |
| guestrsvmessagesDetailsStatusFlag | `StringInput` | Status Flag |
| locatorsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| locatorsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| locatorsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| locatorsDetailsLocatorId | `FloatInput` | Internal locator id |
| locatorsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| locatorsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| locatorsDetailsResvNameId | `FloatInput` | Resv Name ID |
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
| profileallDetailsNameId | `FloatInput` | The primary key for this table. |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not. |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| profileallDetailsChainCode | `StringInput` | Chain Code |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profileallDetailsIndexName | `StringInput` | Index Name |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileallDetailsNameType | `StringInput` | The type of Profile. |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table. |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| reservationprofileaccountscompanyDetailsProfileId | `FloatInput` | Account ID |
| reservationprofileaccountscompanyDetailsActiveYn | `StringInput` | Active Flag |
| reservationprofileaccountscompanyDetailsChainCode | `StringInput` | Chain Code |
| reservationprofileaccountscompanyDetailsCompany | `StringInput` | Company |
| reservationprofileaccountscompanyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationprofileaccountscompanyDetailsHistoryYn | `StringInput` | History Y/N |
| reservationprofileaccountscompanyDetailsNameCode | `StringInput` | IATA Number |
| reservationprofileaccountscompanyDetailsInactiveDate | `DateInput` | Inactive Date |
| reservationprofileaccountscompanyDetailsOrganizationId | `FloatInput` | Organization ID |
| reservationprofileaccountscompanyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationprofileaccountscompanyDetailsLast | `StringInput` | Last |
| reservationprofileaccountscompanyDetailsNameId | `FloatInput` | Name ID |
| reservationprofileaccountscompanyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationprofileaccountscompanyDetailsProfileType | `StringInput` | Profile Type |
| reservationprofileaccountscompanyDetailsNameType | `StringInput` | Profile Type Code |
| reservationprofileaccountscompanyDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| reservationprofileaccountscompanyDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| reservationprofileaccountscompanyDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| reservationprofileaccountscompanyDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| reservationprofileaccountscompanyDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| reservationprofileaccountscompanyDetailsUpdateDate | `DateTimeInput` | Update Date |
| profileaccountstravelagentDetailsProfileId | `FloatInput` | Account ID |
| profileaccountstravelagentDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountstravelagentDetailsChainCode | `StringInput` | Chain Code |
| profileaccountstravelagentDetailsCompany | `StringInput` | Company |
| profileaccountstravelagentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountstravelagentDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountstravelagentDetailsNameCode | `StringInput` | IATA Number |
| profileaccountstravelagentDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountstravelagentDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountstravelagentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountstravelagentDetailsLast | `StringInput` | Last |
| profileaccountstravelagentDetailsNameId | `FloatInput` | Name ID |
| profileaccountstravelagentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountstravelagentDetailsProfileType | `StringInput` | Profile Type |
| profileaccountstravelagentDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountstravelagentDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountstravelagentDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountstravelagentDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountstravelagentDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountstravelagentDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountstravelagentDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationprofileaccountssourceDetailsProfileId | `FloatInput` | Account ID |
| reservationprofileaccountssourceDetailsActiveYn | `StringInput` | Active Flag |
| reservationprofileaccountssourceDetailsChainCode | `StringInput` | Chain Code |
| reservationprofileaccountssourceDetailsCompany | `StringInput` | Company |
| reservationprofileaccountssourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationprofileaccountssourceDetailsHistoryYn | `StringInput` | History Y/N |
| reservationprofileaccountssourceDetailsNameCode | `StringInput` | IATA Number |
| reservationprofileaccountssourceDetailsInactiveDate | `DateInput` | Inactive Date |
| reservationprofileaccountssourceDetailsOrganizationId | `FloatInput` | Organization ID |
| reservationprofileaccountssourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationprofileaccountssourceDetailsLast | `StringInput` | Last |
| reservationprofileaccountssourceDetailsNameId | `FloatInput` | Name ID |
| reservationprofileaccountssourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationprofileaccountssourceDetailsProfileType | `StringInput` | Profile Type |
| reservationprofileaccountssourceDetailsNameType | `StringInput` | Profile Type Code |
| reservationprofileaccountssourceDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| reservationprofileaccountssourceDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| reservationprofileaccountssourceDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| reservationprofileaccountssourceDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| reservationprofileaccountssourceDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| reservationprofileaccountssourceDetailsUpdateDate | `DateTimeInput` | Update Date |
| ratecodeDetailsBaseRateCode | `StringInput` | Base Rate Code |
| ratecodeDetailsBeginBookingDate | `DateInput` | Business Date |
| ratecodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| ratecodeDetailsCommissionCode | `StringInput` | Commission Code |
| ratecodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecodeDetailsDailyRatesYn | `StringInput` | Daily Rates Y/N |
| ratecodeDetailsDbaseRateCode | `StringInput` | The rate code on which this rate shedule is dynamically based on. |
| ratecodeDetailsSellSequence | `FloatInput` | Display Sequence |
| ratecodeDetailsEndBookingDate | `DateInput` | End Date |
| ratecodeDetailsGroupCode | `StringInput` | Group Code |
| ratecodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| ratecodeDetailsMarketCode | `StringInput` | Market Code |
| ratecodeDetailsMaxDvanceBooking | `FloatInput` | Maximum Days Advance Booking |
| ratecodeDetailsMaxLos | `FloatInput` | Maximum Length of Stay |
| ratecodeDetailsMaxOccupancy | `FloatInput` | Maximum Occupancy |
| ratecodeDetailsMinAdvanceBooking | `FloatInput` | Minimum Days Advance Booking |
| ratecodeDetailsMinOccupancy | `FloatInput` | Minimum Occupancy |
| ratecodeDetailsOrderBy | `FloatInput` | Order By |
| ratecodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecodeDetailsRateCode | `StringInput` | Original Rate Code |
| ratecodeDetailsOrsSellSequence | `FloatInput` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| ratecodeDetailsPendingApprovalYn | `StringInput` | Indicates whether the rate code is pending for approval or not |
| ratecodeDetailsResort | `StringInput` | Code to uniquely identify the Property |
| ratecodeDetailsRateBucket | `StringInput` | Yield rate bucket |
| ratecodeDetailsRateCodeId | `StringInput` | Rate Code ID |
| ratecodeDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |
| ratecodeDetailsSourceCode | `StringInput` | Source Code |
| ratecodeDetailsTransactionCode | `StringInput` | Rate transaction code |
| ratecodeDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| reservationalertsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationalertsDetailsExternalAlertId | `StringInput` | Unique ID in External System. |
| reservationalertsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationalertsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationalertsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationalertsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationalertsDetailsQueryId | `FloatInput` | Query ID |
| reservationalertsDetailsResvAlertId | `FloatInput` | Resv Alert ID |
| reservationalertsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationcancelpolicyDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationcancelpolicyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationcancelpolicyDetailsExternalId | `StringInput` | External ID |
| reservationcancelpolicyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationcancelpolicyDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationcancelpolicyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationcancelpolicyDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationcancelpolicyDetailsResvCancelPolicyId | `FloatInput` | Internal |
| reservationcancelpolicyDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationdetailDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| reservationdetailDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationdetailDetailsBlockId | `FloatInput` | Block ID. |
| reservationdetailDetailsBlockResort | `StringInput` | Property this block belongs to. |
| reservationdetailDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationdetailDetailsCompanyId | `FloatInput` | Company ID |
| reservationdetailDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationdetailDetailsDueOutYn | `StringInput` | Due Out Y/N |
| reservationdetailDetailsExtSegNo | `FloatInput` | Not used |
| reservationdetailDetailsExternalReference | `StringInput` | External Reference |
| reservationdetailDetailsGroupId | `FloatInput` | Group ID |
| reservationdetailDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationdetailDetailsMarketCode | `StringInput` | Market Code |
| reservationdetailDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationdetailDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationdetailDetailsRateCode | `StringInput` | Rate Code |
| reservationdetailDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationdetailDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationdetailDetailsResvDailyElSeq | `FloatInput` | Reservation Daily El Seq |
| reservationdetailDetailsResvStatus | `StringInput` | Reservation Status |
| reservationdetailDetailsRoom | `StringInput` | Room |
| reservationdetailDetailsRoomCategory | `StringInput` | Room Category |
| reservationdetailDetailsSourceId | `FloatInput` | Source ID |
| reservationdetailDetailsReservationDate | `DateInput` | Stay Date |
| reservationdetailDetailsTravelAgentId | `FloatInput` | Travel Agent ID |
| reservationecouponsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationecouponsDetailsEcouponCode | `StringInput` | Ecoupon Code |
| reservationecouponsDetailsEcouponId | `FloatInput` | Primary Key based on Sequence. |
| reservationecouponsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationecouponsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationecouponsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationecouponsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationecouponsDetailsRateCode | `StringInput` | Rate Code |
| reservationecouponsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationitemsDetailsBasedOnRule | `StringInput` | Based On Rule |
| reservationitemsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationitemsDetailsItemId | `FloatInput` | Item ID |
| reservationitemsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationitemsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationitemsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationitemsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationitemsDetailsReservationItemId | `FloatInput` | Primary Key from Sequence. |
| reservationitemsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationprefDetailsBasedOnRule | `StringInput` | Based On Rule |
| reservationprefDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationprefDetailsExternalPreferenceId | `StringInput` | Unique ID in External System. |
| reservationprefDetailsPreferenceid | `FloatInput` | Preferenceid |
| reservationprefDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationprefDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationprefDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationprefDetailsPreference | `StringInput` | Preference |
| reservationprefDetailsPreferenceType | `StringInput` | Preference Group |
| reservationprefDetailsPreferenceId | `FloatInput` | Internal Id of the preference |
| reservationprefDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationprefDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationprefDetailsReservationid | `FloatInput` | Reservationid |
| reservationprefDetailsReservationpreferenceid | `StringInput` | Reservation Preference ID |
| reservationproductsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationproductsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationproductsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationproductsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationproductsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationproductsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationproductsDetailsReservationProductId | `FloatInput` | Reservation Product ID |
| reservationpromotionsDetailsBasedOnRule | `StringInput` | Based On Rule |
| reservationpromotionsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationpromotionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationpromotionsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationpromotionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationpromotionsDetailsPromoCode | `StringInput` | Promotion Code |
| reservationpromotionsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationpromotionsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationthresholdsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationthresholdsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationthresholdsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationthresholdsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationthresholdsDetailsResvNameId | `FloatInput` | Resv Name ID |
| reservationthresholdsDetailsResvThresholdId | `FloatInput` | Sequence to Identify the row. |
| reservationthresholdsDetailsThresholdDiversionId | `FloatInput` | Threshold Diversion ID |
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
| resortservicerequestsDetailsCloseBusinessDateTime | `DateInput` | The business date this service request was closed. |
| resortservicerequestsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortservicerequestsDetailsInsertDate | `DateTimeInput` | Insert Date |
| resortservicerequestsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortservicerequestsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resortservicerequestsDetailsNameId | `FloatInput` | Name ID |
| resortservicerequestsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortservicerequestsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resortservicerequestsDetailsResvNameId | `FloatInput` | Resv Name ID |
| resortservicerequestsDetailsRoom | `StringInput` | Room Number |
| resortservicerequestsDetailsServiceRequestCode | `StringInput` | Service request classification code. |
| resortservicerequestsDetailsServiceRequestId | `FloatInput` | Sequence generated no Identifier for service request. |
| resortservicerequestsDetailsStatus | `StringInput` | Status |
| resvcommentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvcommentDetailsExternalCommentId | `StringInput` | Unique ID in External System. |
| resvcommentDetailsInternalYn | `StringInput` | Internal YN |
| resvcommentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvcommentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvcommentDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvcommentDetailsResvCommentId | `FloatInput` | Part of the primary key for this table. |
| resvcommentDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvconfletterDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvconfletterDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvconfletterDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resvconfletterDetailsModuleId | `FloatInput` | Module ID |
| resvconfletterDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvconfletterDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvconfletterDetailsResvConfLetterId | `FloatInput` | Internal |
| resvconfletterDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvconfletterDetailsToNameId | `FloatInput` | Name ID to whom the contract is sent. |
| resvdepositscheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| resvdepositscheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdepositscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdepositscheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resvdepositscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdepositscheduleDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvdepositscheduleDetailsResvDepositScheduleId | `FloatInput` | Resv Deposit Schedule ID |
| resvpaymentmethodsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| resvpaymentmethodsDetailsCreditCardId | `FloatInput` | Credit Card ID |
| resvpaymentmethodsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvpaymentmethodsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvpaymentmethodsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvpaymentmethodsDetailsFolioView | `FloatInput` | Payment Window |
| resvpaymentmethodsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvpaymentmethodsDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvproductsticketsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| resvproductsticketsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvproductsticketsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvproductsticketsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resvproductsticketsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvproductsticketsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvproductsticketsDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvproductsticketsDetailsReservationProductId | `FloatInput` | Reservation Product ID |
| resvproductsticketsDetailsTicketId | `FloatInput` | Internal ticket id. |
| resvproductsticketsDetailsProductId | `StringInput` | Ticket Package Code |
| roomcategoryDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| roomcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomcategoryDetailsLabel | `StringInput` | Label |
| roomcategoryDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomcategoryDetailsYieldCategory | `StringInput` | Product Class |
| roomcategoryDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomcategoryDetailsRoomCategory | `StringInput` | Room Type |
| roomcategoryDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| roomcategoryDetailsRoomcategorypmsref | `StringInput` | Roomcategorypmsref |
| roomcategoryDetailsRoomclassid | `StringInput` | Roomclassid |
| bookedroomcategoryDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| bookedroomcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bookedroomcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bookedroomcategoryDetailsLabel | `StringInput` | Label |
| bookedroomcategoryDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| bookedroomcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| bookedroomcategoryDetailsYieldCategory | `StringInput` | Product Class |
| bookedroomcategoryDetailsResort | `StringInput` | Code to uniquely identify the Property |
| bookedroomcategoryDetailsRoomcategoryid | `StringInput` | Room Category ID |
| bookedroomcategoryDetailsRoomcategorypmsref | `StringInput` | Room Category PMS Ref |
| bookedroomcategoryDetailsRoomCategory | `StringInput` | Room Type |
| bookedroomcategoryDetailsRoomclassid | `StringInput` | Roomclassid |
| routinginstructionDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| routinginstructionDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| routinginstructionDetailsBillingInstrnCode | `FloatInput` | Billing Instruction Code. |
| routinginstructionDetailsBilltoprofileid | `FloatInput` | Billtoprofileid |
| routinginstructionDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| routinginstructionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| routinginstructionDetailsDayString | `StringInput` | Concatenated string of all the days. This is also used part of the unique key. |
| routinginstructionDetailsFolioView | `FloatInput` | Folio |
| routinginstructionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| routinginstructionDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| routinginstructionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| routinginstructionDetailsBillToNameId | `FloatInput` | Name Id to which it should be routed. |
| routinginstructionDetailsRequestedBy | `StringInput` | Application user who requested the report. |
| routinginstructionDetailsResvNameId | `FloatInput` | Resv Name ID |
| routinginstructionDetailsReservationid | `FloatInput` | Reservationid |
| routinginstructionDetailsRoutingInstructionsId | `FloatInput` | Number to identify the entry. |
| routinginstructionDetailsTrxCode | `StringInput` | Routing Transaction Code |
| routinginstructionDetailsRoutinginstructid | `FloatInput` | Routinginstructid |
| routinginstructionDetailsTcGroup | `StringInput` | Transaction Code Group |
| routinginstructionDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| routinginstructionDetailsToResvNameId | `FloatInput` | To Resv Name ID |
| routinginstructionDetailsToreservationid | `FloatInput` | Toreservationid |
| routinginstructionDetailsTranscodearrangementid | `FloatInput` | Transcodearrangementid |
| routinginstructionDetailsTranscodeid | `StringInput` | Transcodeid |
| routinginstructionDetailsTransgroupid | `StringInput` | Transgroupid |
| routinginstructionDetailsTranssubgroupid | `StringInput` | Transsubgroupid |
| sourcetableDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sourcetableDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sourcetableDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| sourcetableDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sourcetableDetailsResort | `StringInput` | Property |
| sourcetableDetailsSourceCode | `StringInput` | Source Code |
| sourcetableDetailsSourceid | `StringInput` | Sourceid |
| trackititemsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trackititemsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trackititemsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| trackititemsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trackititemsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| trackititemsDetailsTrackitId | `FloatInput` | Unique Trackit ID. |
| guestrsvtracesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rotationpointadjustmentDetailsBegindate | `DateInput` | Begin Date |
| rotationpointadjustmentDetailsBusinessdate | `DateInput` | Business Date |
| rotationpointadjustmentDetailsDsi | `FloatInput` | DSI |
| rotationpointadjustmentDetailsEnddate | `DateInput` | End Date |
| rotationpointadjustmentDetailsJrnupdatedateandtime | `DateTimeInput` | JRN Update Date and Time |
| rotationpointadjustmentDetailsOrganizationid | `FloatInput` | Organization ID |
| rotationpointadjustmentDetailsProperty | `StringInput` | Property |
| rotationpointadjustmentDetailsReservtionnameid | `FloatInput` | Reservtion Name ID |
| rotationpointadjustmentDetailsRoom | `StringInput` | Room |
| rotationpointadjustmentDetailsRotationid | `FloatInput` | Rotation ID |
| rotationpointadjustmentDetailsType | `StringInput` | Type |
| rotationoverridesDetailsDsi | `FloatInput` | DSI |
| rotationoverridesDetailsInsertdate | `DateTimeInput` | Date |
| rotationoverridesDetailsJRrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rotationoverridesDetailsOrganizationid | `FloatInput` | Organization ID |
| rotationoverridesDetailsOverrideroom | `StringInput` | Override Room |
| rotationoverridesDetailsResort | `StringInput` | Property |
| rotationoverridesDetailsCode | `StringInput` | Reason Code |
| rotationoverridesDetailsResvnameid | `FloatInput` | Reservation Name ID |
| rotationoverridesDetailsRotationroom | `StringInput` | Rotation Room |
| reservationlinkedDetailsActualCheckInDateTime | `DateInput` | Actual Check In Date Time |
| reservationlinkedDetailsActualCheckOutDateTime | `DateInput` | Actual Check Out Date Time |
| reservationlinkedDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| reservationlinkedDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationlinkedDetailsTruncBeginDate | `DateInput` | Arrival Date |
| reservationlinkedDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationlinkedDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| reservationlinkedDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationlinkedDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationlinkedDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationlinkedDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| reservationlinkedDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationlinkedDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| reservationlinkedDetailsCreditCardId | `FloatInput` | Credit Card ID |
| reservationlinkedDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationlinkedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationlinkedDetailsTruncEndDate | `DateInput` | Departure Date |
| reservationlinkedDetailsEnddatetime | `DateInput` | End Datetime |
| reservationlinkedDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| reservationlinkedDetailsEventId | `FloatInput` | Event ID |
| reservationlinkedDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationlinkedDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationlinkedDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| reservationlinkedDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| reservationlinkedDetailsInsertDate | `DateTimeInput` | Insert Date |
| reservationlinkedDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| reservationlinkedDetailsInsertUser | `FloatInput` | Insert User |
| reservationlinkedDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationlinkedDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationlinkedDetailsEndDate | `DateInput` | Linked Departure Date |
| reservationlinkedDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationlinkedDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationlinkedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationlinkedDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationlinkedDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationlinkedDetailsParentreservationid | `FloatInput` | Parentreservationid |
| reservationlinkedDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationlinkedDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationlinkedDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationlinkedDetailsResvNameId | `FloatInput` | Reservation Name ID |
| reservationlinkedDetailsResvStatus | `StringInput` | Reservation Status |
| reservationlinkedDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationlinkedDetailsReservationid | `FloatInput` | Reservationid |
| reservationlinkedDetailsResort | `StringInput` | Property |
| reservationlinkedDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationlinkedDetailsResvNameid | `FloatInput` | Reservation Nameid |
| reservationlinkedDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| reservationlinkedDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| reservationlinkedDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| reservationlinkedDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationlinkedDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationlinkedDetailsSguestName | `StringInput` | Sguest Name |
| reservationlinkedDetailsNameId | `FloatInput` | Shared Profile ID |
| reservationlinkedDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationlinkedDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationlinkedDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| reservationlinkedDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationlinkedDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationlinkedDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationlinkedDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |
| reservationlsharedDetailsActualCheckInDateTime | `DateInput` | Actual Check In Date Time |
| reservationlsharedDetailsActualCheckOutDateTime | `DateInput` | Actual Check Out Date Time |
| reservationlsharedDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| reservationlsharedDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationlsharedDetailsTruncBeginDate | `DateInput` | Arrival Date |
| reservationlsharedDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationlsharedDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| reservationlsharedDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationlsharedDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationlsharedDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationlsharedDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| reservationlsharedDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationlsharedDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| reservationlsharedDetailsCreditCardId | `FloatInput` | Credit Card ID |
| reservationlsharedDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationlsharedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationlsharedDetailsTruncEndDate | `DateInput` | Departure Date |
| reservationlsharedDetailsEnddatetime | `DateInput` | End Datetime |
| reservationlsharedDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| reservationlsharedDetailsEventId | `FloatInput` | Event ID |
| reservationlsharedDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationlsharedDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationlsharedDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| reservationlsharedDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| reservationlsharedDetailsInsertDate | `DateTimeInput` | Insert Date |
| reservationlsharedDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| reservationlsharedDetailsInsertUser | `FloatInput` | Insert User |
| reservationlsharedDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationlsharedDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationlsharedDetailsEndDate | `DateInput` | Linked Departure Date |
| reservationlsharedDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationlsharedDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationlsharedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationlsharedDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationlsharedDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationlsharedDetailsParentreservationid | `FloatInput` | Parentreservationid |
| reservationlsharedDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationlsharedDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationlsharedDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationlsharedDetailsResvNameId | `FloatInput` | Reservation Name ID |
| reservationlsharedDetailsResvStatus | `StringInput` | Reservation Status |
| reservationlsharedDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationlsharedDetailsReservationid | `FloatInput` | Reservationid |
| reservationlsharedDetailsResort | `StringInput` | Property |
| reservationlsharedDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationlsharedDetailsResvNameid | `FloatInput` | Reservation Nameid |
| reservationlsharedDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| reservationlsharedDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| reservationlsharedDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| reservationlsharedDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationlsharedDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationlsharedDetailsSguestName | `StringInput` | Sguest Name |
| reservationlsharedDetailsNameId | `FloatInput` | Shared Profile ID |
| reservationlsharedDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationlsharedDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationlsharedDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| reservationlsharedDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationlsharedDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationlsharedDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationlsharedDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |
| resvmembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- reservationDetailsChainCode
- reservationDetailsResort

**`conditionalInputPair(pair: 2)`**
- reservationDetailsActualCheckInDateTime
- reservationDetailsActualCheckOutDateTime
- reservationDetailsActualCheckOutDate
- reservationDetailsAddresseeNameId
- reservationDetailsAllotmentid
- reservationDetailsTruncBeginDate
- reservationDetailsBillingContactId
- reservationDetailsBillingcontactprofileid
- reservationDetailsAllotmentHeaderId
- reservationDetailsBonusCheckId
- reservationDetailsBusinessDateCreated
- reservationDetailsCXchangeDate
- reservationDetailsCancellationDate
- reservationDetailsCancellationNo
- reservationDetailsConfirmationNo
- reservationDetailsCreditCardId
- reservationDetailsTruncEndDate
- reservationDetailsEnddatetime
- reservationDetailsEndbusinessdate
- reservationDetailsEventId
- reservationDetailsFolioCloseDate
- reservationDetailsGuestprofileid
- reservationDetailsInsertActionInstanceId
- reservationDetailsInsertDate
- reservationDetailsInsertdatetime
- reservationDetailsInsertUser
- reservationDetailsAwardMembershipId
- reservationDetailsJrnupdatedttm
- reservationDetailsEndDate
- reservationDetailsLocationid
- reservationDetailsOriginalEndDate
- reservationDetailsParentResvNameId
- reservationDetailsParentreservationid
- reservationDetailsQuoteId
- reservationDetailsResvContactId
- reservationDetailsResvNameId
- reservationDetailsReservationid
- reservationDetailsResvNameid
- reservationDetailsResvcontactprofileid
- reservationDetailsRhBillingContactId
- reservationDetailsRhResvContactId
- reservationDetailsNameId
- reservationDetailsSplitFromResvNameId
- reservationDetailsSplitfromreservationid
- reservationDetailsTruncActualCheckOutDate
- reservationDetailsUniCardId
- reservationDetailsUpdateDate
- reservationDetailsUpdatedatetime


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query bookingsReservation($input: BookingsReservationQueryArgumentsType!) {
  bookingsReservation(input: $input) @stream {
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
    accompanyingGuestDetails {
      activeYN
      alternateEnvelopeGreeting
      alternateFirstName
      alternateLanguage
      alternateLastName
      alternateSalutation
      attachDateTime
      autoenrollMemberYN
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      cashBlInd
      centralNationality
      centralNationalityDescription
      centralTitle
      clientID
      contactFlag
      dSI
      detachDateTime
      detachedYN
      email
      emailYN
      envelopeGreeting
      firstName
      gender
      guestPrivYN
      inactiveReason
      inactiveReasonCode
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      languageDescription
      lastName
      mailActionCodes
      mailActionDesc
      mailList
      marketResearchYN
      markets
      marketsDesc
      middleName
      nameID
      nationality
      nationalityDescription
      organizationID
      parentReservationNameId
      phone
      phoneYN
      primaryKeyID
      profilePrivacyFlag
      property
      rNAInsertDate
      rNAUpdateDate
      repInactiveReason
      repInactiveReasonCode
      repMailActionCodes
      repMailActionDesc
      repMarkets
      repMarketsDesc
      repVIPName
      repVIPStatus
      reservationNameId
      restrictedRule
      sMSYN
      salutation
      tax1No
      tax2No
      thirdPartyYN
      title
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
      vIPName
      vIPStatus
    }
    channelDetails {
      businessTitle
      canDeleteYn
      centralOriginCode
      centralOriginDescription
      centralSequence
      chainCode
      channelid
      comments
      dSI
      deletedFlag
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      masterSubKeywordYn
      organizationID
      originCode
      originDescription
      originDisplaySequence
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      titleSuffix
      updateDate
      updateUser
    }
    externalReferencesDetails {
      dSI
      deletedFlag
      extCancellationNo
      externalReferenceLegNumber
      externalReferenceNumber
      externalReferenceType
      externalStatus
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      revisionToken
      updateDate
      updateUser
      upperExternalReference
    }
    fixedChargesDetails {
      accountCode
      accountid
      amountOrPercentage
      amountOrPercentageFlag
      articleId
      beginDateNullable
      businessDate
      cExchangeDate
      cExchangeRate
      cPrice
      centralTransactionCode
      centralTransactionCodeDescription
      dSI
      daytoexecute
      deletedFlag
      endDate
      endDateNullable
      fixedChargesId
      fixedchargespmsref
      frequency
      insertDate
      insertUser
      insertUserName
      internalArticleid
      internalFixedchargesid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      percentage
      price
      primaryKeyID
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationid
      resvenddate
      roomnights
      supplement
      transactionCode
      transactionCodeDescription
      transactionCodeGroup
      transactionCodeSubGroup
      transactionCodeType
      transcodeid
      updateUser
      updatedate
      yearlyfixedchargedate
    }
    guestReservationMessagesDetails {
      dSI
      deletedFlag
      description
      guestMessage
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      messagePrintedDate
      msgid
      organizationID
      primaryKeyID
      printMessageYN
      printedStatus
      property
      rNAInsertDate
      rNAUpdateDate
      receivedBy
      recipientName
      reservationNameId
      sentToRoomYN
      smsSentBy
      statusDate
      statusFlag
      textSentDate
      textYN
    }
    locatorsDetails {
      beginDate
      dSI
      deletedFlag
      endDate
      enteredBy
      enteredOn
      fromDatetime
      fromTime
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      locationText
      locatorId
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      toDatetime
      toTime
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
    profileAllInformationDetails {
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
      dSI
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
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
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
    reservationProfileAccountsCompanyDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    profileAccountsTravelAgentDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    reservationProfileAccountsSourceDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    rateCodeDetails {
      aSBRateCycle
      addition
      advBaseRateCode
      advBaseRounding
      advanceBaseCompareYN
      advanceDailyBaseYN
      advanceDailyRateYN
      alternateRateCode
      availabilityUpdateYn
      backToBackYN
      baseAmount
      baseFltPct
      baseRateCode
      baseRounding
      baseType
      bbarBaseAmount
      bbarBaseFltPct
      bbarBaseRounding
      bbarBasedYn
      bbarCompareYn
      bbarYn
      blockName
      breakfastInclYn
      breakfastPrice
      businessDate
      bypassHurdleYn
      bypassRankCheckYn
      cBaseAmount
      cBbarBaseAmount
      cBreakfastPrice
      cDbaseAmount
      cDiscountRateAmount
      cDoubleRoomSupplementPrice
      cExchangeDate
      cExchangeRate
      cRateFloor
      cRateLevel
      cRodBaseAmount
      cRoomAssignmentValue
      catPackageCode
      cateringPackageYN
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralRateBucket
      centralRateBucketDescription
      centralRateCategory
      centralRateCategoryDescription
      centralRateClass
      centralRateClassDescription
      centralRoomType
      centralRoomTypeDescription
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      changeState
      commissionPercent
      commissionCode
      commissionYn
      commissionablePerc
      commissionableYn
      complimentaryYN
      currCodeDecimalPos
      currencyCode
      dSI
      dailyRatesYn
      dayUseYN
      daysWhenClosedToArrival
      dbaseAmount
      dbaseCompareYn
      dbaseFltPct
      dbaseRateCode
      dbaseRounding
      dblRoomSupplementPrice
      defaultToHighestBarYn
      deletedFlag
      depositMaturityPreference
      deptCode
      discountRateAmount
      discountRatePercentageYn
      discountYN
      displaySequence
      displaySet
      distributeYn
      doubleRoomSupplementYN
      endDate
      eventProperty
      exchangeType
      externallyControlledYN
      extraPersonChargeBegins
      fitDiscountLevel
      fitDiscountPerc
      flatYN
      folioText
      frequentFlyerYN
      gDSAllowedYN
      groupCode
      highlightRateAmountYn
      houseUseYN
      inactiveDate
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      longInfo
      loyaltyProgramYN
      mandateResvProfiles
      marketCode
      marketDescription
      marketGroupCode
      marketGroupDescription
      marshaRateProgram
      maximumDaysAdvanceBooking
      maximumLengthOfStay
      maximumOccupancy
      mfnUploadYn
      minimumDaysAdvanceBooking
      minimumOccupancy
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      multiplication
      myFidelioUploadYN
      negotiatedYN
      occupancyBasedYn
      occupancyLevel
      operatorType
      orderBy
      organizationID
      originalRateCode
      orsSellSequence
      overridePackageYn
      ownerRateYN
      packageTransactionCode
      packageTransactionCodeWeekend
      packageTransactionTaxInclYN
      packageTransactionTaxIncludedYN
      packageTransactionWkTaxInclYN
      packageYN
      packages
      pendingApprovalYn
      postingRhythm
      postingRhythmNights
      primaryKeyID
      printRateYn
      privilegedRestrictionYn
      privilegedYn
      profitTransactionCode
      property
      propertyName
      rankAdjustmentFactor
      rankValue
      rateBucket
      rateBucketDescription
      rateCalendarYn
      rateCategory
      rateCategoryDescription
      rateClass
      rateClassDescription
      rateCodeId
      rateCodeLockedYn
      rateFloor
      rateFloorOverrideYn
      rateIncludesTaxYn
      rateLabel
      rateLevel
      rateUpdateYN
      rateinfoUrl
      redemptionRateYN
      regionalAvailabilityYN
      repeatPostingRhythmYn
      rnaInsertDate
      rnaUpdateDate
      rodBaseAmount
      rodBaseFltPct
      rodBaseRounding
      rodBasedYn
      rodYn
      roomAssignmentValue
      roomType
      roomTypeDescription
      sdowBeginBookingDate
      sdowEndBookingDate
      serviceInclYn
      servicePerc
      shortInfo
      showRateAmountYn
      sourceCode
      sourceDescription
      sourceGroupCode
      sourceGroupDescription
      taxIncludedPerc
      taxIncludedYn
      tieredYN
      transactionCode
      transactionCodeWeekend
      transactionTaxWeekendIncludedYN
      unitOfLengthOfStay
      updateDate
      updateUser
      upsellYn
      voucherBenefitRateYn
      weekendDays
      wkDeptCode
      yieldAs
      yieldableYN
      ymCode
    }
    reservationAlertsDetails {
      alertCode
      alertDescription
      alertText
      area
      brandStayCnt
      comments
      dSI
      deletedFlag
      department
      displayAlertYN
      emailAddress
      emailYn
      externalAlertId
      hasTagsYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      lastStayDate
      lastStayLocation
      locationID
      membershipAlertYn
      membershipCardNo
      orderBy
      organizationID
      pref1
      pref2
      pref3
      primaryKeyID
      printAlertYN
      printerName
      property
      propertyStayCnt
      propertyStayDate
      queryId
      rNAInsertDate
      rNAUpdateDate
      reportName
      reservationAlertId
      reservationNameId
      skipGuestOverviewYn
      smsNumber
      smsYn
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
      updateDate
      updateUser
      validationAlertYn
      validationOverridePermission
      valueRating
      vipStatus
      welcomeOfferCode
      welcomeOfferYn
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
    reservationDetailDetails {
      adults
      adultsTaxFree
      allotmentHeaderId
      allotmentRecordType
      autoPostAmount
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardNumber
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      baseRateAmount
      basedOnRule
      billing
      billingContactId
      blockCode
      blockId
      blockResort
      bookedRoomCategory
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cExchangeDate
      cExchangeRate
      cGrossRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRoomCost
      cRoomTax
      cShareAmount
      cShareAmountOriginal
      cUpsellCharge
      cancellationCode
      cancellationDate
      cancellationNo
      cancellationReasonDesc
      centralDiscountAmount
      centralDiscountCode
      centralDiscountCodeDescription
      centralEffectiveRate
      centralMarketCode
      centralMarketCodeDescription
      centralRoomType
      centralRoomTypeDescription
      centralRoomTypeToCharge
      centralRoomTypeToChargeDescription
      centralSourceCode
      centralSourceCodeDescription
      child
      childrenTaxFree
      children1
      children2
      children3
      children4
      children5
      commissionCode
      commissionPaid
      commissionableYn
      company
      companyId
      contact
      corpID
      cribs
      currencyCode
      dSI
      dayUseYn
      deAdults
      deBaseRateAmount
      deCBaseRateAmount
      deCExchangeDate
      deCExchangeRate
      deChildren
      deDmlSeqNumber
      deInsertActionInstanceId
      deInsertDate
      deInsertUser
      deUpdateDate
      deUpdateUser
      deletedFlag
      discountAmount
      discountCode
      discountCodeDescription
      discountPercent
      dmlSeqNumber
      doNotMoveYn
      dueOutYn
      effectiveRate
      eligibilityCode
      exchangePostingType
      exchangeRate
      extSegNo
      extSeqNumber
      externalReference
      extraBeds
      fixedRateYN
      grossRateAmt
      group
      groupId
      guaranteeCode
      housekeepingExpectedServiceTime
      iATANumber
      insertActionInstanceId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastShareCalculation
      marketCode
      marketCodeDescription
      membershipPoints
      netRoomAmt
      organizationID
      originalBaseRate
      packageAmt
      physicalQuantity
      physicalRooms
      pkgTax
      points
      primaryKeyID
      property
      quantity
      rate
      rateCode
      rateCodeDescription
      referralYn
      reservationContactId
      reservationNameId
      resvDailyElSequence
      resvStatus
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomTax
      roomType
      roomTypeDescription
      roomTypeToCharge
      roomTypeToChargeDescription
      scheduledMoveComments
      scheduledMoveInRoomType
      scheduledMoveOutRoom
      scheduledMoveOutRoomType
      scheduledMoveStatus
      scheduledMoveTime
      scheduledMoveInRoom
      scheduledMoveInRoomCat
      shareAmountOriginal
      sharePaymentType
      sharePrcnt
      sharePriority
      source
      sourceCode
      sourceCodeDescription
      sourceId
      sourceNumber
      stayDate
      travelAgent
      travelAgentId
      turndownStatus
      updateDate
      updateUser
      upsellCharge
    }
    reservationEcouponsDetails {
      autoAttachedYn
      dSI
      deletedFlag
      ecouponCode
      ecouponDescription
      ecouponId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      qtyUsed
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reason
      reservationNameId
      updateDate
      updateUser
      welcomeOfferModeYn
    }
    reservationItemsDetails {
      allotmentHeaderId
      basedOnRule
      dSI
      deletedFlag
      endDate
      insertDate
      insertUser
      itemCode
      itemDescription
      itemId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      productCode
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reservationItemId
      reservationNameId
      reservationProductId
      startDate
      updateDate
      updateUser
      welcomeOfferYn
    }
    reservationPreferenceDetails {
      basedOnRule
      comments
      dSI
      deletedflag
      dmlSeqNumber
      externalPreferenceId
      insertActionInstanceId
      insertDate
      insertUser
      internalPreferenceid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      preArrivalDt
      preference
      preferenceDescription
      preferenceGroup
      preferenceGroupDescription
      preferenceId
      preferencecomment
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationid
      reservationpreferenceid
      resvbegindate
      resvenddate
      source
      transactionid
      transportCode
      updateDate
      updateUser
    }
    reservationProductsDetails {
      awardCode
      basedOnRule
      calculatedQuantity
      calculationRule
      cateringYn
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPrice
      currencyCode
      dSI
      deletedFlag
      deliveryTime
      dmlSeqNumber
      endDate
      excludedQuantity
      fixedPackageYn
      forecastNextDayYN
      formula
      fromValidTime
      includedInRateYN
      includesItemYN
      insertActionInstanceId
      insertDate
      insertUser
      insertUserName
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      overrideFixedRateYn
      packageCode
      packageDescription
      packageForecastGroup
      packageForecastGroupDescription
      points
      posAccountYn
      posNextDayYn
      postingRhythm
      price
      primaryKeyID
      printSeparateYn
      productGroup
      productSource
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reservationNameId
      reservationProductId
      startDate
      ticketsYn
      toValidTime
      updateDate
      updateUser
      updateUserName
    }
    reservationPromotionsDetails {
      basedOnRule
      centralPromotionCode
      centralPromotionDescription
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      pPromoCode
      primaryKeyID
      promotionCode
      promotionDescription
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
    }
    reservationStatusDetails {
      reservationStatus
    }
    reservationThresholdsDetails {
      complimentary
      dSI
      deletedFlag
      diverted
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      minimumRequired
      organizationID
      posted
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationThresholdId
      sequence
      thresholdDiversionId
      thresholdEntityType
      transactionDiversionCalculation
      transactionDiversionCode
      transactionDiversionNotes
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
    propertyServiceRequestsDetails {
      actionTaken
      closeBusinessDateTime
      closedBy
      closedByUserName
      closureActionTaken
      completionBusinessDateTime
      confirmationNumber
      contactMethod
      contactMethodDescription
      contactedBy
      dSI
      dateClosed
      dateCompleted
      dateOpened
      deletedFlag
      department
      departmentDescription
      guestName
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      nameId
      openBusinessDateTime
      openedBy
      organizationID
      primaryKeyID
      priority
      priorityDescription
      property
      remarks
      repDepartmentDescription
      reportingDeptId
      reservationNameId
      rnaInsertDate
      rnaUpdateDate
      roomNumber
      serviceRequestCode
      serviceRequestDescription
      serviceRequestId
      serviceType
      status
      timeClosed
      timeCompleted
      timeOpened
      updateDate
      updateUser
    }
    reservationCommentDetails {
      centralNotificationArea
      centralNotificationAreaDescription
      comment
      commentType
      dSI
      deletedFlag
      dmlSeqNumber
      externalCommentId
      insertActionInstanceId
      insertDate
      insertUser
      internalYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      noteResort
      noteTitle
      noteTypeDescription
      notificationArea
      notificationAreaDescription
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationCommentId
      reservationNameId
      updateDate
      updateUser
      userModifiableYn
    }
    reservationConfirmationLetterDetails {
      addressId
      customizeYn
      dSI
      deletedFlag
      deliveryMethod
      destination
      destinationId
      dmlSeqNumber
      emailId
      emailLastAttempted
      emailLastStatus
      emailSuccessfulTries
      failureReason
      faxId
      faxLastAttempted
      faxLastStatus
      faxSuccessfulTries
      fromEmail
      insertActionInstanceId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastTimeAttempted
      locationID
      mobileId
      moduleId
      numberOfSuccessfulTries
      optionalEmail
      organizationID
      personalizeText
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationConfLetterId
      reservationNameId
      sendTo
      smsLastAttempted
      smsLastStatus
      smsSuccessfulTries
      status
      toNameId
      updateDate
      updateUser
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
    reservationPaymentMethodsDetails {
      authorizationAmount
      authorizationDescription
      authorizationRule
      bonusCheckId
      centralPaymentMethodType
      centralPaymentMethodTypeDescription
      creditCardAuthorizationDate
      creditCardId
      dSI
      deletedFlag
      directBillVerifyResponse
      emailAddress
      emailFolioYn
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      paymentMethodType
      paymentMethodTypeDescription
      paymentWindow
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      updateDate
      updateUser
    }
    reservationProductsTicketsDetails {
      cExchangeDate
      cExchangeRate
      centralPrice
      consumptionDate
      dSI
      deletedFlag
      insertDate
      insertUser
      issueDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      postingRhythm
      price
      primaryKeyID
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reference
      reservationNameId
      reservationProductId
      ticketId
      ticketNumber
      ticketPackageCode
      ticketPackageDescription
      updateDate
      updateUser
    }
    roomCategoryDetails {
      accessibleRoomType
      activeDate
      activeflag
      autoCheckinYn
      autoPopulate
      autoRoomAssignYn
      bedType
      cExchangeDate
      cExchangeRate
      cIncrements
      cInitialRoundUp
      cORMSDrtier1
      cORMSDrtier2
      cORMSDrtier3
      cORMSDrxtra2ndAdult
      cORMSDrxtraAdult
      cORMSDrxtraChild
      cORMSUpsellAmount
      cRateAmount
      cRateFloor
      cRSDescription
      canDeleteYn
      centralRoomClass
      centralRoomClassDescription
      centralRoomType
      centralRoomTypeDescription
      compiled
      dSI
      defaultOccupancy
      defaultRateCode
      defaultRateDesc
      defaultratecodeid
      deletedFlag
      evisitorFacilityId
      genericYN
      housekeeping
      imageId
      inactiveDate
      inactiveflag
      increments
      initialRoundUp
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      locationID
      longDescription
      maintenance
      maxFixBedOccupancy
      maxRollaways
      maximumAdults
      maximumChildren
      maximumOccupancy
      meetingRoomYN
      memberAwardRoomGrp
      minimumOccupancy
      numberOfRooms
      oRMSUpsellAmt
      organizationID
      ormsDrtier1
      ormsDrtier2
      ormsDrtier3
      ormsDrxtra2ndAdult
      ormsDrxtraAdult
      ormsDrxtraChild
      ormsUpsellRank
      ownerroomflag
      physical
      primaryKeyID
      productClass
      property
      pseudoRoomType
      pseudoRoomYN
      rateAmount
      rateCategory
      rateCategoryDesc
      rateCode
      rateFloor
      ratecategoryid
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repRateCategory
      repRateCategoryDescription
      repSmokingPrefDescription
      repUpdateDate
      replacesCategory
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomClassDescription
      roomInfoURL
      roomPool
      roomType
      roomTypeDescription
      roomcategoryid
      roomcategorypmsref
      roomclassid
      rotationGroup
      sLabel
      salesFlag
      sellThruRuleYn
      sendIFC
      sequence
      smoking
      smokingPrefDesc
      suiteYN
      updateDate
      updateUser
      upsellYn
      yieldStatus
    }
    bookedRoomCategoryDetails {
      accessibleRoomType
      activeDate
      activeflag
      autoCheckinYn
      autoPopulate
      autoRoomAssignYn
      bedType
      cExchangeDate
      cExchangeRate
      cIncrements
      cInitialRoundUp
      cORMSDrtier1
      cORMSDrtier2
      cORMSDrtier3
      cORMSDrxtra2ndAdult
      cORMSDrxtraAdult
      cORMSDrxtraChild
      cORMSUpsellAmount
      cRateAmount
      cRateFloor
      cRSDescription
      canDeleteYn
      centralRoomClass
      centralRoomClassDescription
      centralRoomType
      centralRoomTypeDescription
      chargedRoomTypeDescription
      compiled
      dSI
      defaultOccupancy
      defaultRateCode
      defaultRateDesc
      defaultratecodeid
      deletedFlag
      evisitorFacilityId
      genericYN
      housekeeping
      imageId
      inactiveDate
      inactiveflag
      increments
      initialRoundUp
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      locationID
      longDescription
      maintenance
      maxFixBedOccupancy
      maxRollaways
      maximumAdults
      maximumChildren
      maximumOccupancy
      meetingRoomYN
      memberAwardRoomGrp
      minimumOccupancy
      numberOfRooms
      oRMSUpsellAmt
      organizationID
      ormsDrtier1
      ormsDrtier2
      ormsDrtier3
      ormsDrxtra2ndAdult
      ormsDrxtraAdult
      ormsDrxtraChild
      ormsUpsellRank
      ownerroomflag
      physical
      primaryKeyID
      productClass
      property
      pseudoRoomType
      pseudoRoomYN
      rateAmount
      rateCategory
      rateCategoryDesc
      rateCode
      rateFloor
      ratecategoryid
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repRateCategory
      repRateCategoryDescription
      repSmokingPrefDescription
      repUpdateDate
      replacesCategory
      rnaInsertDate
      rnaUpdateDate
      roomCategoryID
      roomCategoryPMSRef
      roomClass
      roomClassDescription
      roomInfoURL
      roomPool
      roomType
      roomclassid
      rotationGroup
      sLabel
      salesFlag
      sellThruRuleYn
      sendIFC
      sequence
      smoking
      smokingPrefDesc
      suiteYN
      updateDate
      updateUser
      upsellYn
      yieldStatus
    }
    routingInstructionDetails {
      accountCode
      addTransactionYN
      addressId
      authemployeeid
      authorizerId
      basedOnRate
      billingInstrnCode
      billtoprofileid
      cCompPreApprovalAmount
      cExchangeDate
      cExchangeRate
      centralExtendedInstructionSummary
      centralInstructionSummary
      centralRoutingAmountLimit
      centralRoutingLimitUsed
      centralRoutingTransactionCode
      centralRoutingTransactionCodeDescription
      comments
      compAuthorizer
      compPreApprovalAmt
      compPreApprovalCode
      compPreApprovalDate
      compPreApprovalRequiredYn
      compTypeCode
      compVoucherNo
      dSI
      dailyYn
      dayString
      declinedBy
      declinedYn
      deletedFlag
      endDate
      extendedInstructionSummary
      folio
      fridayYN
      insertDate
      insertUser
      instructionSummary
      internalDeletedflag
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      membershipId
      mondayYN
      organizationID
      payeeFirstName
      payeeLastName
      payeeNameID
      primaryKeyID
      printReceiptYn
      property
      requestedBy
      reservationNameId
      reservationid
      rnaInsertDate
      rnaUpdateDate
      routedToRoomNo
      routingAmountLimit
      routingBeginDate
      routingCode
      routingCodeDescription
      routingCoversLimit
      routingDateRange
      routingDaysOfWeek
      routingInstructionsId
      routingLimitType
      routingLimitUsed
      routingLinkId
      routingPercentageLimit
      routingTransactionCode
      routingTransactionCodeDescription
      routingType
      routingTypeDesc
      routinginstructid
      saturdayYN
      sundayYN
      tcGroup
      tcSubgroup
      thursdayYN
      toReservationNameId
      toreservationid
      transcodearrangementid
      transcodeid
      transgroupid
      transsubgroupid
      trxServiceType
      tuesdayYN
      updateDate
      updateUser
      wednesdayYN
    }
    sourceTableDetails {
      centralSequence
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      dSI
      deletedYn
      deletedflag
      inactiveDate
      inactiveFlagYN
      inactiveYn
      insertDate
      insertUser
      internetSalesYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastuseddatetime
      locationID
      organizationID
      parentsourceid
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      sourceCode
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      tempYn
      updateDate
      updateUser
    }
    trackitItemsDetails {
      actionCode
      actionDate
      actionDescription
      assignedTo
      assignedUser
      assignedYN
      businessDateCreated
      businessDateResolved
      closedYN
      dSI
      deletedFlag
      externalId
      guestNameId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationCode
      locationDescription
      locationID
      msgid
      openYN
      organizationID
      primaryKeyID
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      reference
      reservationNameId
      resolvedUser
      status
      trackItDescription
      trackItGroup
      trackItNumber
      trackitId
      typeCode
      typeDescription
      unassignedYN
      updateDate
      updateUser
    }
    guestReservationTracesDetails {
      completedBy
      completedDate
      completedTime
      completedYN
      dSI
      deletedFlag
      department
      departmentDescription
      insertDate
      insertUser
      itemId
      jRNUpdateDate
      jRNUpdateDateAndTime
      noteCode
      noteResort
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationTraceId
      statusFlag
      time
      traceDate
      traceId
      traceStatus
      traceText
      updateDate
      updateUser
    }
    rotationPointAdjustments {
      adjustmentDate
      adjustmentDescription
      adjustmentQuantity
      amount
      beginDate
      businessDate
      cPoints
      confirmationNumber
      dSI
      deletedFlag
      displayName
      endDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      nCNT
      numberOfNights
      organizationID
      pKID
      points
      property
      rCNT
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reservtionNameID
      room
      rotationBeginDate
      rotationEndDate
      rotationID
      sCNT
      type
    }
    rotationOverrides {
      action
      dSI
      date
      deletedFlag
      jRNUpdateDateAndTime
      jRNUpdateDate
      organizationID
      overrideRoom
      overrideRoomPoints
      pKID
      property
      rNAInsertDate
      rNAUpdateDate
      reasonCode
      reasonDescription
      reservationNameID
      room
      rotationOverrideDate
      rotationRoom
      rotationRoomPoints
      time
      user
    }
    linkedReservationDetails {
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
    sharedReservationDetails {
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
    reservationMembershipDetails {
      cardNumberByMembershipClass
      cardNumberByMembershipType
      dSI
      deletedFlag
      earningPreference
      frequentFlyerMembershipYN
      hostBusinessDate
      hostCardinality
      hostFlag
      iDByMembershipClass
      iDByMembershipType
      insertDate
      insertUser
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      levelByMembershipType
      listOfMembershipIDs
      locationID
      loyaltySchemeMembershipYN
      mbrprefChangedDate
      membershipCardNo
      membershipCardNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipDescription
      membershipId
      membershipLevel
      membershipLevelByMembershipClass
      membershipType
      membershipTypeByMembershipClass
      multiplierInstance
      nameId
      organizationID
      pointsMultiplier
      populationMethod
      primaryKeyID
      processedDate
      processedYn
      profileid
      property
      rankValue
      reservationNameId
      reservationid
      reservationmembershipid
      resvenddate
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
accompanying_guest_details_schema = {
    'activeYN': pl.Utf8,
    'alternateEnvelopeGreeting': pl.Utf8,
    'alternateFirstName': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLastName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'attachDateTime': pl.Utf8,
    'autoenrollMemberYN': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'cashBlInd': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityDescription': pl.Utf8,
    'centralTitle': pl.Utf8,
    'clientID': pl.Utf8,
    'contactFlag': pl.Utf8,
    'dSI': pl.Int64,
    'detachDateTime': pl.Utf8,
    'detachedYN': pl.Utf8,
    'email': pl.Utf8,
    'emailYN': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'firstName': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYN': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonCode': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'languageDescription': pl.Utf8,
    'lastName': pl.Utf8,
    'mailActionCodes': pl.Utf8,
    'mailActionDesc': pl.Utf8,
    'mailList': pl.Utf8,
    'marketResearchYN': pl.Utf8,
    'markets': pl.Utf8,
    'marketsDesc': pl.Utf8,
    'middleName': pl.Utf8,
    'nameID': pl.Float64,
    'nationality': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'parentReservationNameId': pl.Float64,
    'phone': pl.Utf8,
    'phoneYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'profilePrivacyFlag': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repInactiveReasonCode': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repMarkets': pl.Utf8,
    'repMarketsDesc': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'reservationNameId': pl.Float64,
    'restrictedRule': pl.Utf8,
    'sMSYN': pl.Utf8,
    'salutation': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'thirdPartyYN': pl.Utf8,
    'title': pl.Utf8,
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
    'vIPName': pl.Utf8,
    'vIPStatus': pl.Utf8,
}
```
```python
channel_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'channelid': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originDisplaySequence': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
external_references_details_schema = {
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'extCancellationNo': pl.Utf8,
    'externalReferenceLegNumber': pl.Float64,
    'externalReferenceNumber': pl.Utf8,
    'externalReferenceType': pl.Utf8,
    'externalStatus': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'revisionToken': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upperExternalReference': pl.Utf8,
}
```
```python
fixed_charges_details_schema = {
    'accountCode': pl.Float64,
    'accountid': pl.Float64,
    'amountOrPercentage': pl.Float64,
    'amountOrPercentageFlag': pl.Utf8,
    'articleId': pl.Float64,
    'beginDateNullable': pl.Utf8,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cPrice': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeDescription': pl.Utf8,
    'dSI': pl.Int64,
    'daytoexecute': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateNullable': pl.Utf8,
    'fixedChargesId': pl.Float64,
    'fixedchargespmsref': pl.Float64,
    'frequency': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'internalArticleid': pl.Float64,
    'internalFixedchargesid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'price': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'roomnights': pl.Float64,
    'supplement': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroup': pl.Float64,
    'transactionCodeSubGroup': pl.Float64,
    'transactionCodeType': pl.Utf8,
    'transcodeid': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedate': pl.Utf8,
    'yearlyfixedchargedate': pl.Utf8,
}
```
```python
guest_reservation_messages_details_schema = {
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'guestMessage': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'messagePrintedDate': pl.Utf8,
    'msgid': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'printMessageYN': pl.Utf8,
    'printedStatus': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'receivedBy': pl.Utf8,
    'recipientName': pl.Utf8,
    'reservationNameId': pl.Float64,
    'sentToRoomYN': pl.Utf8,
    'smsSentBy': pl.Utf8,
    'statusDate': pl.Utf8,
    'statusFlag': pl.Utf8,
    'textSentDate': pl.Utf8,
    'textYN': pl.Utf8,
}
```
```python
locators_details_schema = {
    'beginDate': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'enteredBy': pl.Utf8,
    'enteredOn': pl.Utf8,
    'fromDatetime': pl.Utf8,
    'fromTime': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'locationText': pl.Utf8,
    'locatorId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'toDatetime': pl.Utf8,
    'toTime': pl.Utf8,
}
```
```python
market_details_schema = {
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketgroupid': pl.Utf8,
    'marketid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'printGroup': pl.Utf8,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repMarketSellSequence': pl.Float64,
    'repParentSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'scOrderby': pl.Float64,
    'trxCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_all_information_details_schema = {
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
    'dSI': pl.Int64,
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
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
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
reservation_profile_accounts_company_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
profile_accounts_travel_agent_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
reservation_profile_accounts_source_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
rate_code_details_schema = {
    'aSBRateCycle': pl.Utf8,
    'addition': pl.Utf8,
    'advBaseRateCode': pl.Utf8,
    'advBaseRounding': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'advanceDailyBaseYN': pl.Utf8,
    'advanceDailyRateYN': pl.Utf8,
    'alternateRateCode': pl.Utf8,
    'availabilityUpdateYn': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'baseAmount': pl.Float64,
    'baseFltPct': pl.Utf8,
    'baseRateCode': pl.Utf8,
    'baseRounding': pl.Utf8,
    'baseType': pl.Utf8,
    'bbarBaseAmount': pl.Float64,
    'bbarBaseFltPct': pl.Utf8,
    'bbarBaseRounding': pl.Utf8,
    'bbarBasedYn': pl.Utf8,
    'bbarCompareYn': pl.Utf8,
    'bbarYn': pl.Utf8,
    'blockName': pl.Utf8,
    'breakfastInclYn': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'businessDate': pl.Utf8,
    'bypassHurdleYn': pl.Utf8,
    'bypassRankCheckYn': pl.Utf8,
    'cBaseAmount': pl.Float64,
    'cBbarBaseAmount': pl.Float64,
    'cBreakfastPrice': pl.Float64,
    'cDbaseAmount': pl.Float64,
    'cDiscountRateAmount': pl.Float64,
    'cDoubleRoomSupplementPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRateFloor': pl.Float64,
    'cRateLevel': pl.Float64,
    'cRodBaseAmount': pl.Float64,
    'cRoomAssignmentValue': pl.Float64,
    'catPackageCode': pl.Utf8,
    'cateringPackageYN': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralRateBucket': pl.Utf8,
    'centralRateBucketDescription': pl.Utf8,
    'centralRateCategory': pl.Utf8,
    'centralRateCategoryDescription': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'changeState': pl.Utf8,
    'commissionPercent': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionYn': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'complimentaryYN': pl.Utf8,
    'currCodeDecimalPos': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRatesYn': pl.Utf8,
    'dayUseYN': pl.Utf8,
    'daysWhenClosedToArrival': pl.Utf8,
    'dbaseAmount': pl.Float64,
    'dbaseCompareYn': pl.Utf8,
    'dbaseFltPct': pl.Utf8,
    'dbaseRateCode': pl.Utf8,
    'dbaseRounding': pl.Utf8,
    'dblRoomSupplementPrice': pl.Float64,
    'defaultToHighestBarYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositMaturityPreference': pl.Utf8,
    'deptCode': pl.Utf8,
    'discountRateAmount': pl.Float64,
    'discountRatePercentageYn': pl.Utf8,
    'discountYN': pl.Utf8,
    'displaySequence': pl.Float64,
    'displaySet': pl.Utf8,
    'distributeYn': pl.Utf8,
    'doubleRoomSupplementYN': pl.Utf8,
    'endDate': pl.Utf8,
    'eventProperty': pl.Utf8,
    'exchangeType': pl.Utf8,
    'externallyControlledYN': pl.Utf8,
    'extraPersonChargeBegins': pl.Float64,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'flatYN': pl.Utf8,
    'folioText': pl.Utf8,
    'frequentFlyerYN': pl.Utf8,
    'gDSAllowedYN': pl.Utf8,
    'groupCode': pl.Utf8,
    'highlightRateAmountYn': pl.Utf8,
    'houseUseYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'longInfo': pl.Utf8,
    'loyaltyProgramYN': pl.Utf8,
    'mandateResvProfiles': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marshaRateProgram': pl.Utf8,
    'maximumDaysAdvanceBooking': pl.Float64,
    'maximumLengthOfStay': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'mfnUploadYn': pl.Utf8,
    'minimumDaysAdvanceBooking': pl.Float64,
    'minimumOccupancy': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'multiplication': pl.Utf8,
    'myFidelioUploadYN': pl.Utf8,
    'negotiatedYN': pl.Utf8,
    'occupancyBasedYn': pl.Utf8,
    'occupancyLevel': pl.Float64,
    'operatorType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'originalRateCode': pl.Utf8,
    'orsSellSequence': pl.Float64,
    'overridePackageYn': pl.Utf8,
    'ownerRateYN': pl.Utf8,
    'packageTransactionCode': pl.Utf8,
    'packageTransactionCodeWeekend': pl.Utf8,
    'packageTransactionTaxInclYN': pl.Utf8,
    'packageTransactionTaxIncludedYN': pl.Utf8,
    'packageTransactionWkTaxInclYN': pl.Utf8,
    'packageYN': pl.Utf8,
    'packages': pl.Utf8,
    'pendingApprovalYn': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingRhythmNights': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRateYn': pl.Utf8,
    'privilegedRestrictionYn': pl.Utf8,
    'privilegedYn': pl.Utf8,
    'profitTransactionCode': pl.Utf8,
    'property': pl.Utf8,
    'propertyName': pl.Utf8,
    'rankAdjustmentFactor': pl.Float64,
    'rankValue': pl.Float64,
    'rateBucket': pl.Utf8,
    'rateBucketDescription': pl.Utf8,
    'rateCalendarYn': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCategoryDescription': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateClassDescription': pl.Utf8,
    'rateCodeId': pl.Utf8,
    'rateCodeLockedYn': pl.Utf8,
    'rateFloor': pl.Float64,
    'rateFloorOverrideYn': pl.Utf8,
    'rateIncludesTaxYn': pl.Utf8,
    'rateLabel': pl.Utf8,
    'rateLevel': pl.Float64,
    'rateUpdateYN': pl.Utf8,
    'rateinfoUrl': pl.Utf8,
    'redemptionRateYN': pl.Utf8,
    'regionalAvailabilityYN': pl.Utf8,
    'repeatPostingRhythmYn': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rodBaseAmount': pl.Float64,
    'rodBaseFltPct': pl.Utf8,
    'rodBaseRounding': pl.Utf8,
    'rodBasedYn': pl.Utf8,
    'rodYn': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'sdowBeginBookingDate': pl.Utf8,
    'sdowEndBookingDate': pl.Utf8,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shortInfo': pl.Utf8,
    'showRateAmountYn': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'tieredYN': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeWeekend': pl.Utf8,
    'transactionTaxWeekendIncludedYN': pl.Utf8,
    'unitOfLengthOfStay': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'voucherBenefitRateYn': pl.Utf8,
    'weekendDays': pl.Utf8,
    'wkDeptCode': pl.Utf8,
    'yieldAs': pl.Utf8,
    'yieldableYN': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
reservation_alerts_details_schema = {
    'alertCode': pl.Utf8,
    'alertDescription': pl.Utf8,
    'alertText': pl.Utf8,
    'area': pl.Utf8,
    'brandStayCnt': pl.Float64,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'displayAlertYN': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailYn': pl.Utf8,
    'externalAlertId': pl.Utf8,
    'hasTagsYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'lastStayDate': pl.Utf8,
    'lastStayLocation': pl.Utf8,
    'locationID': pl.Utf8,
    'membershipAlertYn': pl.Utf8,
    'membershipCardNo': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'pref1': pl.Utf8,
    'pref2': pl.Utf8,
    'pref3': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printAlertYN': pl.Utf8,
    'printerName': pl.Utf8,
    'property': pl.Utf8,
    'propertyStayCnt': pl.Float64,
    'propertyStayDate': pl.Utf8,
    'queryId': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reportName': pl.Utf8,
    'reservationAlertId': pl.Float64,
    'reservationNameId': pl.Float64,
    'skipGuestOverviewYn': pl.Utf8,
    'smsNumber': pl.Utf8,
    'smsYn': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validationAlertYn': pl.Utf8,
    'validationOverridePermission': pl.Utf8,
    'valueRating': pl.Utf8,
    'vipStatus': pl.Utf8,
    'welcomeOfferCode': pl.Utf8,
    'welcomeOfferYn': pl.Utf8,
}
```
```python
reservation_cancel_policy_details_schema = {
    'percentCancellation': pl.Float64,
    'percentDue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForeignCancelAmount': pl.Float64,
    'cancellationDate': pl.Utf8,
    'cancellationPenalty': pl.Utf8,
    'cancellationPenaltyAmount': pl.Float64,
    'cancellationPenaltyType': pl.Utf8,
    'cancellationRuleDescription': pl.Utf8,
    'centralCancellationPenaltyAmount': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'exchangeRateInfo': pl.Utf8,
    'externalId': pl.Utf8,
    'foreignCancelAmount': pl.Float64,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'processedYn': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateDcSeq': pl.Float64,
    'reservationCancelPolicyId': pl.Float64,
    'reservationNameId': pl.Float64,
    'roomNights': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_detail_details_schema = {
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'allotmentHeaderId': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'autoPostAmount': pl.Float64,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardNumber': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'baseRateAmount': pl.Float64,
    'basedOnRule': pl.Utf8,
    'billing': pl.Utf8,
    'billingContactId': pl.Float64,
    'blockCode': pl.Utf8,
    'blockId': pl.Float64,
    'blockResort': pl.Utf8,
    'bookedRoomCategory': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmount': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancellationCode': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationNo': pl.Float64,
    'cancellationReasonDesc': pl.Utf8,
    'centralDiscountAmount': pl.Float64,
    'centralDiscountCode': pl.Utf8,
    'centralDiscountCodeDescription': pl.Utf8,
    'centralEffectiveRate': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketCodeDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToCharge': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceCodeDescription': pl.Utf8,
    'child': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionableYn': pl.Utf8,
    'company': pl.Utf8,
    'companyId': pl.Float64,
    'contact': pl.Utf8,
    'corpID': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dayUseYn': pl.Utf8,
    'deAdults': pl.Float64,
    'deBaseRateAmount': pl.Float64,
    'deCBaseRateAmount': pl.Float64,
    'deCExchangeDate': pl.Utf8,
    'deCExchangeRate': pl.Float64,
    'deChildren': pl.Float64,
    'deDmlSeqNumber': pl.Float64,
    'deInsertActionInstanceId': pl.Float64,
    'deInsertDate': pl.Utf8,
    'deInsertUser': pl.Float64,
    'deUpdateDate': pl.Utf8,
    'deUpdateUser': pl.Float64,
    'deletedFlag': pl.Utf8,
    'discountAmount': pl.Float64,
    'discountCode': pl.Utf8,
    'discountCodeDescription': pl.Utf8,
    'discountPercent': pl.Float64,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveYn': pl.Utf8,
    'dueOutYn': pl.Utf8,
    'effectiveRate': pl.Float64,
    'eligibilityCode': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'externalReference': pl.Utf8,
    'extraBeds': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'grossRateAmt': pl.Float64,
    'group': pl.Utf8,
    'groupId': pl.Float64,
    'guaranteeCode': pl.Utf8,
    'housekeepingExpectedServiceTime': pl.Utf8,
    'iATANumber': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastShareCalculation': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketCodeDescription': pl.Utf8,
    'membershipPoints': pl.Float64,
    'netRoomAmt': pl.Float64,
    'organizationID': pl.Int64,
    'originalBaseRate': pl.Float64,
    'packageAmt': pl.Float64,
    'physicalQuantity': pl.Float64,
    'physicalRooms': pl.Float64,
    'pkgTax': pl.Float64,
    'points': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rate': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'referralYn': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationNameId': pl.Float64,
    'resvDailyElSequence': pl.Float64,
    'resvStatus': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomTax': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToCharge': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'scheduledMoveComments': pl.Utf8,
    'scheduledMoveInRoomType': pl.Utf8,
    'scheduledMoveOutRoom': pl.Utf8,
    'scheduledMoveOutRoomType': pl.Utf8,
    'scheduledMoveStatus': pl.Utf8,
    'scheduledMoveTime': pl.Utf8,
    'scheduledMoveInRoom': pl.Utf8,
    'scheduledMoveInRoomCat': pl.Utf8,
    'shareAmountOriginal': pl.Float64,
    'sharePaymentType': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'sharePriority': pl.Float64,
    'source': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceId': pl.Float64,
    'sourceNumber': pl.Utf8,
    'stayDate': pl.Utf8,
    'travelAgent': pl.Utf8,
    'travelAgentId': pl.Float64,
    'turndownStatus': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellCharge': pl.Float64,
}
```
```python
reservation_ecoupons_details_schema = {
    'autoAttachedYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'ecouponCode': pl.Utf8,
    'ecouponDescription': pl.Utf8,
    'ecouponId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'qtyUsed': pl.Float64,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reason': pl.Utf8,
    'reservationNameId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'welcomeOfferModeYn': pl.Utf8,
}
```
```python
reservation_items_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'basedOnRule': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'itemCode': pl.Utf8,
    'itemDescription': pl.Utf8,
    'itemId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'productCode': pl.Utf8,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reservationItemId': pl.Float64,
    'reservationNameId': pl.Float64,
    'reservationProductId': pl.Float64,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'welcomeOfferYn': pl.Utf8,
}
```
```python
reservation_preference_details_schema = {
    'basedOnRule': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'externalPreferenceId': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalPreferenceid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'preArrivalDt': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceDescription': pl.Utf8,
    'preferenceGroup': pl.Utf8,
    'preferenceGroupDescription': pl.Utf8,
    'preferenceId': pl.Float64,
    'preferencecomment': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'reservationpreferenceid': pl.Utf8,
    'resvbegindate': pl.Utf8,
    'resvenddate': pl.Utf8,
    'source': pl.Utf8,
    'transactionid': pl.Float64,
    'transportCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_products_details_schema = {
    'awardCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'calculatedQuantity': pl.Float64,
    'calculationRule': pl.Utf8,
    'cateringYn': pl.Utf8,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPrice': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'deliveryTime': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'endDate': pl.Utf8,
    'excludedQuantity': pl.Float64,
    'fixedPackageYn': pl.Utf8,
    'forecastNextDayYN': pl.Utf8,
    'formula': pl.Utf8,
    'fromValidTime': pl.Utf8,
    'includedInRateYN': pl.Utf8,
    'includesItemYN': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideFixedRateYn': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'points': pl.Float64,
    'posAccountYn': pl.Utf8,
    'posNextDayYn': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'price': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printSeparateYn': pl.Utf8,
    'productGroup': pl.Utf8,
    'productSource': pl.Utf8,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationProductId': pl.Float64,
    'startDate': pl.Utf8,
    'ticketsYn': pl.Utf8,
    'toValidTime': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'updateUserName': pl.Utf8,
}
```
```python
reservation_promotions_details_schema = {
    'basedOnRule': pl.Utf8,
    'centralPromotionCode': pl.Utf8,
    'centralPromotionDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'pPromoCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
}
```
```python
reservation_status_details_schema = {
    'reservationStatus': pl.Utf8,
}
```
```python
reservation_thresholds_details_schema = {
    'complimentary': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'diverted': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'minimumRequired': pl.Float64,
    'organizationID': pl.Int64,
    'posted': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationThresholdId': pl.Float64,
    'sequence': pl.Float64,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'transactionDiversionCalculation': pl.Utf8,
    'transactionDiversionCode': pl.Utf8,
    'transactionDiversionNotes': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
property_service_requests_details_schema = {
    'actionTaken': pl.Utf8,
    'closeBusinessDateTime': pl.Utf8,
    'closedBy': pl.Utf8,
    'closedByUserName': pl.Utf8,
    'closureActionTaken': pl.Utf8,
    'completionBusinessDateTime': pl.Utf8,
    'confirmationNumber': pl.Utf8,
    'contactMethod': pl.Utf8,
    'contactMethodDescription': pl.Utf8,
    'contactedBy': pl.Utf8,
    'dSI': pl.Int64,
    'dateClosed': pl.Utf8,
    'dateCompleted': pl.Utf8,
    'dateOpened': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'departmentDescription': pl.Utf8,
    'guestName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'openBusinessDateTime': pl.Utf8,
    'openedBy': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'property': pl.Utf8,
    'remarks': pl.Utf8,
    'repDepartmentDescription': pl.Utf8,
    'reportingDeptId': pl.Utf8,
    'reservationNameId': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNumber': pl.Utf8,
    'serviceRequestCode': pl.Utf8,
    'serviceRequestDescription': pl.Utf8,
    'serviceRequestId': pl.Float64,
    'serviceType': pl.Utf8,
    'status': pl.Utf8,
    'timeClosed': pl.Utf8,
    'timeCompleted': pl.Utf8,
    'timeOpened': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_comment_details_schema = {
    'centralNotificationArea': pl.Utf8,
    'centralNotificationAreaDescription': pl.Utf8,
    'comment': pl.Utf8,
    'commentType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'externalCommentId': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'noteResort': pl.Utf8,
    'noteTitle': pl.Utf8,
    'noteTypeDescription': pl.Utf8,
    'notificationArea': pl.Utf8,
    'notificationAreaDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationCommentId': pl.Float64,
    'reservationNameId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userModifiableYn': pl.Utf8,
}
```
```python
reservation_confirmation_letter_details_schema = {
    'addressId': pl.Float64,
    'customizeYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'deliveryMethod': pl.Utf8,
    'destination': pl.Utf8,
    'destinationId': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'emailId': pl.Float64,
    'emailLastAttempted': pl.Utf8,
    'emailLastStatus': pl.Utf8,
    'emailSuccessfulTries': pl.Float64,
    'failureReason': pl.Utf8,
    'faxId': pl.Float64,
    'faxLastAttempted': pl.Utf8,
    'faxLastStatus': pl.Utf8,
    'faxSuccessfulTries': pl.Float64,
    'fromEmail': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastTimeAttempted': pl.Utf8,
    'locationID': pl.Utf8,
    'mobileId': pl.Float64,
    'moduleId': pl.Float64,
    'numberOfSuccessfulTries': pl.Float64,
    'optionalEmail': pl.Utf8,
    'organizationID': pl.Int64,
    'personalizeText': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationConfLetterId': pl.Float64,
    'reservationNameId': pl.Float64,
    'sendTo': pl.Utf8,
    'smsLastAttempted': pl.Utf8,
    'smsLastStatus': pl.Utf8,
    'smsSuccessfulTries': pl.Float64,
    'status': pl.Utf8,
    'toNameId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_deposit_schedule_details_schema = {
    'activityDeposit': pl.Float64,
    'cActivityDeposit': pl.Float64,
    'cCancelPnltyAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForeignDepositAmount': pl.Float64,
    'cancelDeadline': pl.Utf8,
    'cancelPnltyAmount': pl.Float64,
    'centralDepositAmountOutstanding': pl.Float64,
    'centralDepositAmountRequested': pl.Float64,
    'centralTotalDepositPayments': pl.Float64,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'depositAmountOutstanding': pl.Float64,
    'depositAmountRequested': pl.Float64,
    'depositDueDate': pl.Utf8,
    'depositPercentage': pl.Float64,
    'depositReqLinkId': pl.Float64,
    'depositReqReceiptNo': pl.Float64,
    'depositReqReversalYn': pl.Utf8,
    'depositRule': pl.Utf8,
    'depositRuleDescription': pl.Utf8,
    'depositRuleType': pl.Utf8,
    'depositScheduleReservationNameId': pl.Float64,
    'depositType': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'exchangeRateInfo': pl.Utf8,
    'externalId': pl.Utf8,
    'foreignDepositAmount': pl.Float64,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualYn': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentFlag': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'processedYn': pl.Utf8,
    'productId': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateDcSeq': pl.Float64,
    'reservationDepositScheduleId': pl.Float64,
    'roomDeposit': pl.Float64,
    'totalDepositPayments': pl.Float64,
    'trxDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_payment_methods_details_schema = {
    'authorizationAmount': pl.Float64,
    'authorizationDescription': pl.Utf8,
    'authorizationRule': pl.Float64,
    'bonusCheckId': pl.Float64,
    'centralPaymentMethodType': pl.Utf8,
    'centralPaymentMethodTypeDescription': pl.Utf8,
    'creditCardAuthorizationDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentMethodType': pl.Utf8,
    'paymentMethodTypeDescription': pl.Utf8,
    'paymentWindow': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_products_tickets_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralPrice': pl.Float64,
    'consumptionDate': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'issueDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'postingRhythm': pl.Utf8,
    'price': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reference': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationProductId': pl.Float64,
    'ticketId': pl.Float64,
    'ticketNumber': pl.Utf8,
    'ticketPackageCode': pl.Utf8,
    'ticketPackageDescription': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
room_category_details_schema = {
    'accessibleRoomType': pl.Utf8,
    'activeDate': pl.Utf8,
    'activeflag': pl.Utf8,
    'autoCheckinYn': pl.Utf8,
    'autoPopulate': pl.Utf8,
    'autoRoomAssignYn': pl.Utf8,
    'bedType': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cIncrements': pl.Float64,
    'cInitialRoundUp': pl.Float64,
    'cORMSDrtier1': pl.Float64,
    'cORMSDrtier2': pl.Float64,
    'cORMSDrtier3': pl.Float64,
    'cORMSDrxtra2ndAdult': pl.Float64,
    'cORMSDrxtraAdult': pl.Float64,
    'cORMSDrxtraChild': pl.Float64,
    'cORMSUpsellAmount': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRateFloor': pl.Float64,
    'cRSDescription': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'compiled': pl.Utf8,
    'dSI': pl.Int64,
    'defaultOccupancy': pl.Float64,
    'defaultRateCode': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'defaultratecodeid': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'genericYN': pl.Utf8,
    'housekeeping': pl.Utf8,
    'imageId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'increments': pl.Float64,
    'initialRoundUp': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'locationID': pl.Utf8,
    'longDescription': pl.Utf8,
    'maintenance': pl.Utf8,
    'maxFixBedOccupancy': pl.Float64,
    'maxRollaways': pl.Float64,
    'maximumAdults': pl.Float64,
    'maximumChildren': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'meetingRoomYN': pl.Utf8,
    'memberAwardRoomGrp': pl.Utf8,
    'minimumOccupancy': pl.Float64,
    'numberOfRooms': pl.Float64,
    'oRMSUpsellAmt': pl.Float64,
    'organizationID': pl.Int64,
    'ormsDrtier1': pl.Float64,
    'ormsDrtier2': pl.Float64,
    'ormsDrtier3': pl.Float64,
    'ormsDrxtra2ndAdult': pl.Float64,
    'ormsDrxtraAdult': pl.Float64,
    'ormsDrxtraChild': pl.Float64,
    'ormsUpsellRank': pl.Float64,
    'ownerroomflag': pl.Utf8,
    'physical': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'productClass': pl.Utf8,
    'property': pl.Utf8,
    'pseudoRoomType': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCategory': pl.Utf8,
    'rateCategoryDesc': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateFloor': pl.Float64,
    'ratecategoryid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repRateCategory': pl.Utf8,
    'repRateCategoryDescription': pl.Utf8,
    'repSmokingPrefDescription': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'replacesCategory': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomInfoURL': pl.Utf8,
    'roomPool': pl.Utf8,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomcategorypmsref': pl.Utf8,
    'roomclassid': pl.Utf8,
    'rotationGroup': pl.Utf8,
    'sLabel': pl.Utf8,
    'salesFlag': pl.Utf8,
    'sellThruRuleYn': pl.Utf8,
    'sendIFC': pl.Utf8,
    'sequence': pl.Float64,
    'smoking': pl.Utf8,
    'smokingPrefDesc': pl.Utf8,
    'suiteYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'yieldStatus': pl.Utf8,
}
```
```python
booked_room_category_details_schema = {
    'accessibleRoomType': pl.Utf8,
    'activeDate': pl.Utf8,
    'activeflag': pl.Utf8,
    'autoCheckinYn': pl.Utf8,
    'autoPopulate': pl.Utf8,
    'autoRoomAssignYn': pl.Utf8,
    'bedType': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cIncrements': pl.Float64,
    'cInitialRoundUp': pl.Float64,
    'cORMSDrtier1': pl.Float64,
    'cORMSDrtier2': pl.Float64,
    'cORMSDrtier3': pl.Float64,
    'cORMSDrxtra2ndAdult': pl.Float64,
    'cORMSDrxtraAdult': pl.Float64,
    'cORMSDrxtraChild': pl.Float64,
    'cORMSUpsellAmount': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRateFloor': pl.Float64,
    'cRSDescription': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'chargedRoomTypeDescription': pl.Utf8,
    'compiled': pl.Utf8,
    'dSI': pl.Int64,
    'defaultOccupancy': pl.Float64,
    'defaultRateCode': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'defaultratecodeid': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'genericYN': pl.Utf8,
    'housekeeping': pl.Utf8,
    'imageId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'increments': pl.Float64,
    'initialRoundUp': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'locationID': pl.Utf8,
    'longDescription': pl.Utf8,
    'maintenance': pl.Utf8,
    'maxFixBedOccupancy': pl.Float64,
    'maxRollaways': pl.Float64,
    'maximumAdults': pl.Float64,
    'maximumChildren': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'meetingRoomYN': pl.Utf8,
    'memberAwardRoomGrp': pl.Utf8,
    'minimumOccupancy': pl.Float64,
    'numberOfRooms': pl.Float64,
    'oRMSUpsellAmt': pl.Float64,
    'organizationID': pl.Int64,
    'ormsDrtier1': pl.Float64,
    'ormsDrtier2': pl.Float64,
    'ormsDrtier3': pl.Float64,
    'ormsDrxtra2ndAdult': pl.Float64,
    'ormsDrxtraAdult': pl.Float64,
    'ormsDrxtraChild': pl.Float64,
    'ormsUpsellRank': pl.Float64,
    'ownerroomflag': pl.Utf8,
    'physical': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'productClass': pl.Utf8,
    'property': pl.Utf8,
    'pseudoRoomType': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCategory': pl.Utf8,
    'rateCategoryDesc': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateFloor': pl.Float64,
    'ratecategoryid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repRateCategory': pl.Utf8,
    'repRateCategoryDescription': pl.Utf8,
    'repSmokingPrefDescription': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'replacesCategory': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCategoryID': pl.Utf8,
    'roomCategoryPMSRef': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomInfoURL': pl.Utf8,
    'roomPool': pl.Utf8,
    'roomType': pl.Utf8,
    'roomclassid': pl.Utf8,
    'rotationGroup': pl.Utf8,
    'sLabel': pl.Utf8,
    'salesFlag': pl.Utf8,
    'sellThruRuleYn': pl.Utf8,
    'sendIFC': pl.Utf8,
    'sequence': pl.Float64,
    'smoking': pl.Utf8,
    'smokingPrefDesc': pl.Utf8,
    'suiteYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'yieldStatus': pl.Utf8,
}
```
```python
routing_instruction_details_schema = {
    'accountCode': pl.Utf8,
    'addTransactionYN': pl.Utf8,
    'addressId': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizerId': pl.Float64,
    'basedOnRate': pl.Utf8,
    'billingInstrnCode': pl.Float64,
    'billtoprofileid': pl.Float64,
    'cCompPreApprovalAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralExtendedInstructionSummary': pl.Utf8,
    'centralInstructionSummary': pl.Utf8,
    'centralRoutingAmountLimit': pl.Float64,
    'centralRoutingLimitUsed': pl.Float64,
    'centralRoutingTransactionCode': pl.Utf8,
    'centralRoutingTransactionCodeDescription': pl.Utf8,
    'comments': pl.Utf8,
    'compAuthorizer': pl.Utf8,
    'compPreApprovalAmt': pl.Float64,
    'compPreApprovalCode': pl.Utf8,
    'compPreApprovalDate': pl.Utf8,
    'compPreApprovalRequiredYn': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'compVoucherNo': pl.Utf8,
    'dSI': pl.Int64,
    'dailyYn': pl.Utf8,
    'dayString': pl.Utf8,
    'declinedBy': pl.Float64,
    'declinedYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'extendedInstructionSummary': pl.Utf8,
    'folio': pl.Float64,
    'fridayYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'instructionSummary': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'membershipId': pl.Float64,
    'mondayYN': pl.Utf8,
    'organizationID': pl.Int64,
    'payeeFirstName': pl.Utf8,
    'payeeLastName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printReceiptYn': pl.Utf8,
    'property': pl.Utf8,
    'requestedBy': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'routedToRoomNo': pl.Utf8,
    'routingAmountLimit': pl.Float64,
    'routingBeginDate': pl.Utf8,
    'routingCode': pl.Utf8,
    'routingCodeDescription': pl.Utf8,
    'routingCoversLimit': pl.Float64,
    'routingDateRange': pl.Utf8,
    'routingDaysOfWeek': pl.Utf8,
    'routingInstructionsId': pl.Float64,
    'routingLimitType': pl.Utf8,
    'routingLimitUsed': pl.Float64,
    'routingLinkId': pl.Float64,
    'routingPercentageLimit': pl.Float64,
    'routingTransactionCode': pl.Utf8,
    'routingTransactionCodeDescription': pl.Utf8,
    'routingType': pl.Utf8,
    'routingTypeDesc': pl.Utf8,
    'routinginstructid': pl.Float64,
    'saturdayYN': pl.Utf8,
    'sundayYN': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'thursdayYN': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'toreservationid': pl.Float64,
    'transcodearrangementid': pl.Float64,
    'transcodeid': pl.Utf8,
    'transgroupid': pl.Utf8,
    'transsubgroupid': pl.Utf8,
    'trxServiceType': pl.Utf8,
    'tuesdayYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'wednesdayYN': pl.Utf8,
}
```
```python
source_table_details_schema = {
    'centralSequence': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedYn': pl.Utf8,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlagYN': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internetSalesYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastuseddatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'parentsourceid': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'tempYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
trackit_items_details_schema = {
    'actionCode': pl.Utf8,
    'actionDate': pl.Utf8,
    'actionDescription': pl.Utf8,
    'assignedTo': pl.Float64,
    'assignedUser': pl.Utf8,
    'assignedYN': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDateResolved': pl.Utf8,
    'closedYN': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'externalId': pl.Utf8,
    'guestNameId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationCode': pl.Utf8,
    'locationDescription': pl.Utf8,
    'locationID': pl.Utf8,
    'msgid': pl.Float64,
    'openYN': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reference': pl.Utf8,
    'reservationNameId': pl.Float64,
    'resolvedUser': pl.Float64,
    'status': pl.Utf8,
    'trackItDescription': pl.Utf8,
    'trackItGroup': pl.Utf8,
    'trackItNumber': pl.Utf8,
    'trackitId': pl.Float64,
    'typeCode': pl.Utf8,
    'typeDescription': pl.Utf8,
    'unassignedYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
guest_reservation_traces_details_schema = {
    'completedBy': pl.Utf8,
    'completedDate': pl.Utf8,
    'completedTime': pl.Utf8,
    'completedYN': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'departmentDescription': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'itemId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'noteCode': pl.Utf8,
    'noteResort': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationTraceId': pl.Float64,
    'statusFlag': pl.Utf8,
    'time': pl.Utf8,
    'traceDate': pl.Utf8,
    'traceId': pl.Float64,
    'traceStatus': pl.Utf8,
    'traceText': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
rotation_point_adjustments_schema = {
    'adjustmentDate': pl.Utf8,
    'adjustmentDescription': pl.Utf8,
    'adjustmentQuantity': pl.Float64,
    'amount': pl.Float64,
    'beginDate': pl.Utf8,
    'businessDate': pl.Utf8,
    'cPoints': pl.Float64,
    'confirmationNumber': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayName': pl.Utf8,
    'endDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'nCNT': pl.Float64,
    'numberOfNights': pl.Float64,
    'organizationID': pl.Int64,
    'pKID': pl.Float64,
    'points': pl.Float64,
    'property': pl.Utf8,
    'rCNT': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reservtionNameID': pl.Float64,
    'room': pl.Utf8,
    'rotationBeginDate': pl.Utf8,
    'rotationEndDate': pl.Utf8,
    'rotationID': pl.Float64,
    'sCNT': pl.Float64,
    'type': pl.Utf8,
}
```
```python
rotation_overrides_schema = {
    'action': pl.Utf8,
    'dSI': pl.Int64,
    'date': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideRoom': pl.Utf8,
    'overrideRoomPoints': pl.Float64,
    'pKID': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reasonCode': pl.Utf8,
    'reasonDescription': pl.Utf8,
    'reservationNameID': pl.Float64,
    'room': pl.Utf8,
    'rotationOverrideDate': pl.Utf8,
    'rotationRoom': pl.Utf8,
    'rotationRoomPoints': pl.Float64,
    'time': pl.Utf8,
    'user': pl.Utf8,
}
```
```python
linked_reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
shared_reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
reservation_membership_details_schema = {
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'earningPreference': pl.Utf8,
    'frequentFlyerMembershipYN': pl.Utf8,
    'hostBusinessDate': pl.Utf8,
    'hostCardinality': pl.Float64,
    'hostFlag': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelByMembershipType': pl.Utf8,
    'listOfMembershipIDs': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mbrprefChangedDate': pl.Utf8,
    'membershipCardNo': pl.Utf8,
    'membershipCardNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipDescription': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipType': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'multiplierInstance': pl.Float64,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'pointsMultiplier': pl.Float64,
    'populationMethod': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'processedDate': pl.Utf8,
    'processedYn': pl.Utf8,
    'profileid': pl.Float64,
    'property': pl.Utf8,
    'rankValue': pl.Float64,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'reservationmembershipid': pl.Float64,
    'resvenddate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```