# BookingReservationExtended
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `bookingReservationExtended`
> Provide booking reservation information with extended or additional details such as blocks routing etc.
  
**Return:** [`[BookingReservationExtendedType]`](#bookingreservationextendedtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`BookingReservationExtendedQueryArgumentsType!`](#bookingreservationextendedqueryargumentstype) |  |

## Object Types

### BookingReservationExtendedType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationUnifiedDetails | [`BookingReservationExtendedReservationUnifiedDetailsType`](#bookingreservationextendedreservationunifieddetailstype) | Reservation Unified |
| 2 | profileAllInformationDetails | [`BookingReservationExtendedProfileAllInformationDetailsType`](#bookingreservationextendedprofileallinformationdetailstype) | Profile All Details |
| 3 | profileAccountsSourceDetails | [`BookingReservationExtendedProfileAccountsSourceDetailsType`](#bookingreservationextendedprofileaccountssourcedetailstype) | Profile Accounts Source Details |
| 4 | profileAccountsTravelAgentDetails | [`BookingReservationExtendedProfileAccountsTravelAgentDetailsType`](#bookingreservationextendedprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| 5 | externalReferencesDetails | [`BookingReservationExtendedExternalReferencesDetailsType`](#bookingreservationextendedexternalreferencesdetailstype) | External References Details |
| 6 | reservationMembershipDetails | [`BookingReservationExtendedReservationMembershipDetailsType`](#bookingreservationextendedreservationmembershipdetailstype) | Reservation Membership |
| 7 | reservationPaymentMethodsDetails | [`BookingReservationExtendedReservationPaymentMethodsDetailsType`](#bookingreservationextendedreservationpaymentmethodsdetailstype) | Reservation Payment Methods |
| 8 | profileAccountsDetails | [`BookingReservationExtendedProfileAccountsDetailsType`](#bookingreservationextendedprofileaccountsdetailstype) | Profile Accounts Details |
| 9 | reservationDepositScheduleDetails | [`BookingReservationExtendedReservationDepositScheduleDetailsType`](#bookingreservationextendedreservationdepositscheduledetailstype) | Reservation Deposit Schedule |
| 10 | rateCodeDetailsDetails | [`BookingReservationExtendedRateCodeDetailsDetailsType`](#bookingreservationextendedratecodedetailsdetailstype) | Rate Code Details Details |
| 11 | routingInstructionDetails | [`BookingReservationExtendedRoutingInstructionDetailsType`](#bookingreservationextendedroutinginstructiondetailstype) | Routing Instruction Details |
| 12 | folioTaxDetails | [`BookingReservationExtendedFolioTaxDetailsType`](#bookingreservationextendedfoliotaxdetailstype) | Folio Tax Details |
| 13 | financialUnifiedDetails | [`BookingReservationExtendedFinancialUnifiedDetailsType`](#bookingreservationextendedfinancialunifieddetailstype) | Financial Unified |
| 14 | propertyPropertyDetails | [`BookingReservationExtendedPropertyPropertyDetailsType`](#bookingreservationextendedpropertypropertydetailstype) | Resort Details |
| 15 | roomDetails | [`BookingReservationExtendedRoomDetailsType`](#bookingreservationextendedroomdetailstype) | Room Details |
| 16 | fixedChargesDetails | [`BookingReservationExtendedFixedChargesDetailsType`](#bookingreservationextendedfixedchargesdetailstype) | Fixed Charges Details |
| 17 | bookingReservationExtendedRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationUnifiedDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | actionId | `Float` | Action ID |
| 3 | actualCheckInDateTime | `String` | Actual Check In Date Time |
| 4 | actualCheckOutDateTime | `String` | Actual Check Out Date Time |
| 5 | actualCheckInDate | `Date` | Actual Check-In Date |
| 6 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 7 | addressId | `Float` | Address ID |
| 8 | addresseeNameId | `Float` | Addressee Name ID |
| 9 | adults | `Float` | Adults |
| 10 | adultsTaxFree | `Float` | Adults Tax Free |
| 11 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 12 | agencyprofileid | `Float` | Agencyprofileid |
| 13 | agentNameId | `Float` | Agent Name ID |
| 14 | allAliases | `String` | All Aliases |
| 15 | allBlockOwners | `String` | All Block Owners |
| 16 | allCateringOwners | `String` | All Catering Owners |
| 17 | allCompanyContacts | `String` | All Company Contacts |
| 18 | allRateCodes | `String` | All Rate Codes |
| 19 | allRoomOwners | `String` | All Room Owners |
| 20 | allRoomTypes | `String` | All Room Types |
| 21 | allSourceContacts | `String` | All Source Contacts |
| 22 | allTravelAgentContacts | `String` | All Travel Agent Contacts |
| 23 | allotmentOrigin | `String` | Allotment Origin |
| 24 | allotmentRecordType | `Float` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 25 | allotmentType | `String` | Type of Block alloted for the group. |
| 26 | allotmentid | `Float` | Block ID |
| 27 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 28 | amenityLevelCode | `String` | Amenity Level Code |
| 29 | amountPercent | `Float` | Amount Percent |
| 30 | approvalAmount | `Float` | Approval Amount |
| 31 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 32 | approvalCode | `String` | Approval Code |
| 33 | arrivalComments | `String` | Arrival Comments |
| 34 | arrivalDate | `DateTime` | Arrival Date |
| 35 | arrivalDateTime | `Date` | Arrival Date Time |
| 36 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 37 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 38 | authorizerId | `Float` | Authorizer ID |
| 39 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 40 | autoSettleDays | `String` | Auto Settle Days |
| 41 | autoSettleYN | `Float` | Auto Settle YN |
| 42 | averageRate | `Float` | Average Rate |
| 43 | awardCode | `String` | Award Code |
| 44 | awardCode1 | `String` | Award code 1 |
| 45 | awardCode2 | `String` | Award code 2 |
| 46 | awardCode3 | `String` | Award code 3 |
| 47 | awardCode4 | `String` | Award Code 4 |
| 48 | awardCode5 | `String` | Award code 5 |
| 49 | awardVoucher1 | `String` | Award Voucher number 1 |
| 50 | awardVoucher2 | `String` | Award Voucher number 2 |
| 51 | awardVoucher3 | `String` | Award Voucher number 3 |
| 52 | awardVoucher4 | `String` | Award Voucher number 4 |
| 53 | awardVoucher5 | `String` | Award Voucher number 5 |
| 54 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 55 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 56 | baseRateAmount | `Float` | Base Rate Amount |
| 57 | baseRateCode | `String` | Base Rate Code |
| 58 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginDatetime | `String` | Begin Datetime |
| 61 | beginSystemDateTime | `String` | Stores the actual guest check in date and time. |
| 62 | billingContactId | `Float` | Billing Contact ID |
| 63 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 64 | blockAlias | `String` | Block Alias |
| 65 | blockCode | `String` | Block Code |
| 66 | blockDescription | `String` | Block Description |
| 67 | blockDmlSeqNumber | `Float` | Block Dml Seq Number |
| 68 | blockEndbusinessdate | `Date` | Block Endbusinessdate |
| 69 | blockExchangePostingType | `String` | Block Exchange Posting Type |
| 70 | blockExchangeRate | `Float` | Block Exchange Rate |
| 71 | blockExternalReference | `String` | Block External Reference |
| 72 | blockID | `String` | Block ID |
| 73 | blockOwnerCode | `String` | Block Owner Code |
| 74 | blockResort | `String` | Property this block belongs to. |
| 75 | blockStatus | `String` | Block Status |
| 76 | blockStatusDescription | `String` | Block Status Description |
| 77 | blocksExternalReference | `String` | Blocks External Reference |
| 78 | bonusCheckId | `Float` | Bonus Check ID |
| 79 | bookedRoomCategory | `String` | Booked Room Category |
| 80 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 81 | businessDateCreated | `Date` | Business Date Created |
| 82 | cancelDate | `Date` | Cancel Date |
| 83 | cancelReason | `String` | Cancel Reason |
| 84 | cancelTime | `String` | Cancel Time |
| 85 | cancellationDate | `DateTime` | Cancellation Date |
| 86 | cancellationNumber | `String` | Cancellation Number |
| 87 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 88 | cancellationreasonid | `String` | Cancellationreasonid |
| 89 | centralApprovalAmount | `Float` | Central Approval Amount |
| 90 | changesLogCheckIn | `String` | Changes Log Check In |
| 91 | changesLogCheckOut | `String` | Changes Log Check Out |
| 92 | changesLogCloseFolio | `String` | Changes Log Close Folio |
| 93 | changesLogReopenFolio | `String` | Changes Log Reopen Folio |
| 94 | changesLogUpdateReservation | `String` | Changes Log Update Reservation |
| 95 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 96 | childBucket1 | `Float` | Child Bucket 1 |
| 97 | childBucket4 | `Float` | Child Bucket 4 |
| 98 | childBucket5 | `Float` | Child Bucket 5 |
| 99 | children | `Float` | Children |
| 100 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 101 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 102 | commissionCode | `String` | Commission Code |
| 103 | commissionHoldCode | `String` | Commission Hold Code |
| 104 | commissionPaid | `Float` | Commission Paid |
| 105 | commissionPayoutTo | `Float` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 106 | commissionableYN | `String` | Commissionable YN |
| 107 | commissionid | `String` | Commissionid |
| 108 | compTypeCode | `String` | Comp Type Code |
| 109 | companyAll | `String` | Company All |
| 110 | companyID | `Float` | Company ID |
| 111 | companyNameId | `Float` | Company Name ID |
| 112 | compreasonid | `String` | Compreasonid |
| 113 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 114 | confirmationNo | `String` | Shared Confirmation Number |
| 115 | consumerYn | `String` | Consumer Y/N |
| 116 | contactNameId | `Float` | Contact Name ID |
| 117 | contactProfileID | `Float` | Contact Profile ID |
| 118 | createdBy | `String` | The name of the user who created the record. |
| 119 | createdDate | `Date` | Created Date |
| 120 | creditCardId | `Float` | Credit Card ID |
| 121 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 122 | cribs | `Float` | Cribs |
| 123 | currencyCode | `String` | Currency Code |
| 124 | customReferenceNumber | `String` | Custom Reference Number |
| 125 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 126 | dateOfArrivalInCountry | `String` | Country Specific Requirement for Nigeria. |
| 127 | dateOpenedForPickup | `Date` | Date Opened for Pickup |
| 128 | departureComments | `String` | Departure Comments |
| 129 | departureDate | `Date` | Departure Date |
| 130 | departureDateTime | `Date` | Departure Date Time |
| 131 | departureTime | `String` | Departure Time |
| 132 | departureTransportCode | `String` | Departure Transport Code |
| 133 | departureTransportationYN | `String` | Departure Transportation YN |
| 134 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 135 | discountAmount | `Float` | Discount Amount |
| 136 | discountAmt | `Float` | Discount Amount |
| 137 | discountPercent | `Float` | Discount Percentage. |
| 138 | discountPrcnt | `Float` | Discount Prcnt |
| 139 | discountReason | `String` | Discount Reason |
| 140 | discountreasonid | `String` | Discountreasonid |
| 141 | displayColor | `String` | Display Color |
| 142 | dmlSeqNumber | `Float` | Dml Sequence No |
| 143 | doNotMoveRoom | `String` | Do Not Move Room |
| 144 | doNotMoveYN | `String` | Do not move room flag. |
| 145 | downloadDate | `Date` | Download Date |
| 146 | downloadResort | `String` | Download Property |
| 147 | downloadSrep | `Float` | Download Srep |
| 148 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 149 | dropOffDate | `Date` | Drop Off Date |
| 150 | dropOffStation | `String` | Drop Off Station |
| 151 | dropOffTime | `String` | Drop Off Time |
| 152 | eTRComments | `Date` | Comments related to Estimated Time of Return. |
| 153 | effectiveRateAmount | `Float` | Not used. |
| 154 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 155 | emailAddress | `String` | Email Address |
| 156 | emailFolioYn | `String` | Email Folio Y/N |
| 157 | emailId | `Float` | Email ID |
| 158 | emailYn | `String` | Email Y/N |
| 159 | endDate | `Date` | End Date |
| 160 | endbusinessdate | `Date` | Endbusinessdate |
| 161 | entryDate | `String` | Entry Date into the country. (Croatian Requirements) |
| 162 | entryPoint | `Float` | (Customized) Entry point into the country. (Croatian Requirements) |
| 163 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 164 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 165 | eventId | `Float` | Event ID |
| 166 | exchangePostingType | `String` | Exchange Posting Type |
| 167 | exchangeRate | `Float` | Exchange Rate |
| 168 | expectedTimeOfReturnETR | `String` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 169 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 170 | extBookingID | `String` | Ext Allotment ID |
| 171 | extSegNo | `Float` | Not used |
| 172 | extSeqNumber | `Float` | Not used |
| 173 | extensionId | `Float` | Internal extension number for the main reservation |
| 174 | externalEfolioYn | `Date` | Indicates if the guest has opted to receive Efolio through an external system. |
| 175 | externalReference | `String` | External Reference |
| 176 | externallyLocked | `String` | Externally Locked |
| 177 | extraBeds | `Float` | Extra Beds |
| 178 | faxId | `Float` | Fax ID |
| 179 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 180 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 181 | fixedRateYN | `String` | Fixed Rate YN |
| 182 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 183 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 184 | folioText1 | `Date` | Folio Text1 |
| 185 | folioText2 | `String` | Folio Text2 |
| 186 | foreignCurrencyID | `String` | Foreign Currency ID |
| 187 | freeChild | `Float` | Free Child |
| 188 | gUID | `String` | GUID |
| 189 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 190 | guaranteecodeid | `String` | Guaranteecodeid |
| 191 | guestFirstName | `String` | Guest First Name |
| 192 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 193 | guestLastNameSdx | `String` | Guest Last Name Sdx |
| 194 | guestSignature | `Float` | Signature of the guest |
| 195 | guestStatus | `String` | Used for Police/Tourist Export |
| 196 | guestType | `String` | Guest Type |
| 197 | guestprofileid | `Float` | Guestprofileid |
| 198 | gueststatusid | `String` | Gueststatusid |
| 199 | guesttypeid | `String` | Guesttypeid |
| 200 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 201 | hurdle | `Float` | Hurdle |
| 202 | hurdleOverride | `String` | Hurdle Override |
| 203 | inactiveDate | `Date` | Inactive Date |
| 204 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 205 | insertUser | `Float` | Insert User |
| 206 | interfaceID | `String` | This is the Interface_id of the System which sent/Received Allotment |
| 207 | intermediaryYn | `String` | Intermediary Y/N |
| 208 | internalAwardMembershipId | `Float` | Award Membership ID |
| 209 | internalBaseratecode | `String` | Baseratecode |
| 210 | internalBlockId | `String` | Block ID. |
| 211 | internalCompanyprofileid | `Float` | Companyprofileid |
| 212 | internalGroupprofileid | `Float` | Groupprofileid |
| 213 | internalSourceprofileid | `Float` | Sourceprofileid |
| 214 | keyValidUntil | `Float` | Key Valid Until |
| 215 | laptopChange | `Float` | Laptop Change |
| 216 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 217 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 218 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 219 | lengthOfStay | `Float` | Length of Stay |
| 220 | linkedArrivalDate | `Date` | Linked Arrival Date |
| 221 | linkedDepartureDate | `Date` | Linked Departure Date |
| 222 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 223 | mailYn | `String` | Mail Y/N |
| 224 | mainmarket | `String` | Mainmarket |
| 225 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 226 | marketCode | `String` | Market Code |
| 227 | marketDescription | `String` | Market Description |
| 228 | marketid | `String` | Marketid |
| 229 | masterBlockID | `Float` | Parent Block ID |
| 230 | masterBlockProperty | `String` | Parent Resort |
| 231 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 232 | membershipId | `Float` | Membership ID |
| 233 | mobileActionAlertIssued | `String` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 234 | mobileAudioKeyYn | `Float` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 235 | mobileCheckinAllowedYn | `Date` | Mobile Checkin Allowed Y/N |
| 236 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 237 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 238 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 239 | name | `String` | Name |
| 240 | nameUsageType | `String` | Name Usage Type |
| 241 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 242 | numberOfRooms | `Float` | No of Rooms |
| 243 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 244 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 245 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 246 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 247 | originCodeDescription | `String` | Origin Code Description |
| 248 | originOfBooking | `String` | Origin Of Booking |
| 249 | originalBaseRate | `Float` | Not used. |
| 250 | originalEndDate | `Date` | Original End Date |
| 251 | originalStartDate | `Date` | Original Start Date |
| 252 | owner | `Float` | Owner |
| 253 | ownerFfFlag | `String` | Owner Ff Flag |
| 254 | ownerResort | `String` | Owner Property |
| 255 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 256 | parentreservationid | `Float` | Parentreservationid |
| 257 | partAllotment | `String` | Part Allotment |
| 258 | partyCode | `String` | Party Code |
| 259 | payment | `String` | Payment |
| 260 | paymentDescription | `String` | Payment Description |
| 261 | paymentMethod | `String` | Payment Method |
| 262 | paymentmethodid | `String` | Paymentmethodid |
| 263 | periodicFolioFreq | `Date` | Frequency in number of days when folios should be printed for this reservation |
| 264 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 265 | phoneId | `Float` | Phone ID |
| 266 | physicalQuantity | `Float` | Physical Quantity |
| 267 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 268 | pickUpDate | `Date` | Pick Up Date |
| 269 | pickUpStation | `String` | Pick Up Station |
| 270 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 271 | pickUpTime | `String` | Pick-Up Time |
| 272 | pickupRequiredYN | `String` | Pickup Required YN |
| 273 | points | `Float` | Points |
| 274 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 275 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 276 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 277 | postingAllowedYN | `String` | Posting Allowed YN |
| 278 | preArrReviewedDt | `Date` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 279 | preArrReviewedUser | `Date` | User id who reviewed the record. |
| 280 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 281 | preRegisteredYn | `Date` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 282 | primaryShare | `String` | Primary Share |
| 283 | printRateYN | `String` | Print Rate YN |
| 284 | profileId | `String` | Profile ID |
| 285 | property | `String` | Indicates if the value set for the specific property. |
| 286 | pseudoMemTotalPoints | `String` | Total pseudo membership points accrued for the default membership type. |
| 287 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 288 | purgeDate | `Date` | Purge Date |
| 289 | purposeOfStay | `String` | Purpose of stay. |
| 290 | quantity | `Float` | Number of Rooms |
| 291 | quoteId | `String` | Quote ID provided by external system. |
| 292 | rateAmount | `String` | Rate Amount |
| 293 | rateCode | `String` | Rate Code |
| 294 | rateableValue | `Float` | Stay rateable value. |
| 295 | ratecodeid | `String` | Ratecodeid |
| 296 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 297 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 298 | rdenReservationDate | `Date` | Rden Reservation Date |
| 299 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 300 | registrationCardNo | `String` | Registration Card Number |
| 301 | registrationNumber | `String` | Registration Number |
| 302 | reinstateDate | `String` | Reinstate Date |
| 303 | reportId | `String` | Report ID |
| 304 | resInsertSource | `String` | Reservation Insert Source |
| 305 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 306 | reservationContactId | `Float` | Resv Contact ID |
| 307 | reservationNameID | `Float` | Reservation Name ID |
| 308 | reservationStatus | `String` | Reservation Status |
| 309 | reservationType | `String` | Reservation Type |
| 310 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 311 | reserveInventoryYN | `String` | Reserve Inventory YN |
| 312 | resort | `String` | Property |
| 313 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 314 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 315 | restrictionOverride | `String` | Restriction Override |
| 316 | resvNumber | `Float` | Not used in PMS currently. |
| 317 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 318 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 319 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 320 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 321 | rivMarketSegment | `String` | Not used |
| 322 | room | `String` | Room |
| 323 | roomCategory | `String` | Room Category |
| 324 | roomClass | `String` | Room Class |
| 325 | roomInstructions | `String` | Room Instructions |
| 326 | roomServiceTime | `String` | This is the Turndown room service time. |
| 327 | roomcategoryid | `String` | Roomcategoryid |
| 328 | roomid | `String` | Roomid |
| 329 | roomsPerDay | `Float` | Rooms Per Day |
| 330 | salesId | `String` | Not used |
| 331 | sbegindate | `Date` | Sbegindate |
| 332 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 333 | senddate | `Date` | Senddate |
| 334 | serviceCharge | `Float` | Service Charge |
| 335 | sguestFirstName | `String` | Sguest First Name |
| 336 | sguestName | `String` | Sguest Name |
| 337 | shareId | `Float` | Share ID. |
| 338 | shareSeqNumber | `String` | Type of revenue |
| 339 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 340 | sharedProfileID | `Float` | Shared Profile ID |
| 341 | sharedReservationStatus | `String` | Shared Reservation Status |
| 342 | shoulderEnd | `Date` | Shoulder End |
| 343 | shoulderStart | `Date` | Shoulder Start |
| 344 | sourceCodeDescription | `String` | Source Code Description |
| 345 | sourceContactAll | `String` | Source Contact All |
| 346 | sourceNameId | `Float` | Source Name ID |
| 347 | sourceid | `String` | Sourceid |
| 348 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 349 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 350 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 351 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 352 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 353 | splitfromreservationid | `Float` | Splitfromreservationid |
| 354 | startDate | `Date` | Start Date |
| 355 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 356 | statisticalRoomType | `String` | Room Type used to calculate statistics for export(DRS). |
| 357 | stayRecordId | `Float` | Stay Record ID |
| 358 | superSearchIndexText | `String` | Super Search Index Text |
| 359 | taxAmount | `Float` | Tax Amount |
| 360 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 361 | taxNumberOfStays | `Date` | Tax No of Stays |
| 362 | taxType | `String` | Tax Type |
| 363 | taxtypeid | `String` | Taxtypeid |
| 364 | tiad | `String` | Tiad |
| 365 | traceCode | `String` | Trace Code |
| 366 | transactionid | `Float` | Transactionid |
| 367 | travelAgentAll | `String` | Travel Agent All |
| 368 | travelAgentID | `Float` | Travel Agent ID |
| 369 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 370 | turndownStatus | `Float` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 371 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 372 | uDFC01 | `String` | UDFC01 |
| 373 | uDFC02 | `String` | UDFC02 |
| 374 | uDFC03 | `String` | UDFC03 |
| 375 | uDFC04 | `String` | UDFC04 |
| 376 | uDFC05 | `String` | UDFC05 |
| 377 | uDFC06 | `String` | UDFC06 |
| 378 | uDFC07 | `String` | UDFC07 |
| 379 | uDFC08 | `String` | UDFC08 |
| 380 | uDFC09 | `String` | UDFC09 |
| 381 | uDFC10 | `String` | UDFC10 |
| 382 | uDFC11 | `String` | UDFC11 |
| 383 | uDFC12 | `String` | UDFC12 |
| 384 | uDFC13 | `String` | UDFC13 |
| 385 | uDFC14 | `String` | UDFC14 |
| 386 | uDFC15 | `String` | UDFC15 |
| 387 | uDFC16 | `String` | UDFC16 |
| 388 | uDFC17 | `String` | UDFC17 |
| 389 | uDFC18 | `String` | UDFC18 |
| 390 | uDFC19 | `String` | UDFC19 |
| 391 | uDFC20 | `String` | UDFC20 |
| 392 | uDFC21 | `String` | UDFC21 |
| 393 | uDFC22 | `String` | UDFC22 |
| 394 | uDFC23 | `String` | UDFC23 |
| 395 | uDFC24 | `String` | UDFC24 |
| 396 | uDFC25 | `String` | UDFC25 |
| 397 | uDFC26 | `String` | UDFC26 |
| 398 | uDFC27 | `String` | UDFC27 |
| 399 | uDFC28 | `String` | UDFC28 |
| 400 | uDFC29 | `String` | UDFC29 |
| 401 | uDFC30 | `String` | UDFC30 |
| 402 | uDFC31 | `String` | UDFC31 |
| 403 | uDFC32 | `String` | UDFC32 |
| 404 | uDFC33 | `String` | UDFC33 |
| 405 | uDFC34 | `String` | UDFC34 |
| 406 | uDFC35 | `String` | UDFC35 |
| 407 | uDFC36 | `String` | UDFC36 |
| 408 | uDFC37 | `String` | UDFC37 |
| 409 | uDFC38 | `String` | UDFC38 |
| 410 | uDFC39 | `String` | UDFC39 |
| 411 | uDFC40 | `String` | UDFC40 |
| 412 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 413 | updateUser | `Float` | Update User |
| 414 | updatedBy | `String` | Updated By |
| 415 | updatedDate | `Date` | Updated Date |
| 416 | uploadDate | `Date` | Upload Date |
| 417 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 418 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 419 | visaExpiryDate | `Date` | Visa Expiry Date |
| 420 | visaIssueDate | `String` | Visa Issue Date |
| 421 | visaNumber | `Float` | Visa Number |
| 422 | waitlistComment | `String` | Waitlist Comment |
| 423 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 424 | walkInYN | `String` | Walk-In YN |
| 425 | yieldableYn | `String` | Yieldable Y/N |
| 426 | ymCode | `Float` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedProfileAllInformationDetailsType

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

### BookingReservationExtendedProfileAccountsSourceDetailsType

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

### BookingReservationExtendedProfileAccountsTravelAgentDetailsType

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

### BookingReservationExtendedExternalReferencesDetailsType

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

### BookingReservationExtendedReservationMembershipDetailsType

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

### BookingReservationExtendedReservationPaymentMethodsDetailsType

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

### BookingReservationExtendedProfileAccountsDetailsType

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
| 119 | inactiveDate | `DateTime` | Inactive Date |
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
| 169 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 170 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 171 | referenceCurrency | `String` | Reference Currency |
| 172 | repInfluence | `String` | Reporting Influence |
| 173 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 174 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 175 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 176 | repNationalityCode | `String` | Reporting Nationality Code |
| 177 | repNationalityDescription | `String` | Reporting Nationality Description |
| 178 | repStateDescription | `String` | Reporting State Desc |
| 179 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 180 | repTitleName | `String` | Reporting Title Name |
| 181 | repVIPName | `String` | Reporting Vip Name |
| 182 | repVIPStatus | `String` | Reporting Vip Status |
| 183 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 184 | resortRegistered | `String` | Resort for which Job is registered. |
| 185 | restricted | `String` | Restricted |
| 186 | restrictedRule | `String` | Restricted Rule |
| 187 | salutation | `String` | Salutation Greeting |
| 188 | scope | `String` | Scope |
| 189 | scopeCity | `String` | Scope City |
| 190 | scopeCityDecription | `String` | Scope City Decription |
| 191 | scopeDescription | `String` | Scope Description |
| 192 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 193 | sfirst | `String` | Uppercase value of First Name. |
| 194 | state | `String` | State |
| 195 | stateCode | `String` | State Code |
| 196 | stateDesc | `String` | State Description of the Guest of Payee |
| 197 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 198 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 199 | tax1No | `String` | Tax1 Number |
| 200 | tax2No | `String` | Tax2 Number |
| 201 | taxCategory | `String` | Tax Category |
| 202 | taxType | `String` | Tax Type |
| 203 | taxTypeDescription | `String` | Tax Type Description |
| 204 | territory | `String` | Territory |
| 205 | territoryDescription | `String` | Territory Description |
| 206 | thirdPartyYn | `String` | Third Party Y/N |
| 207 | traceCode | `String` | Trace Code |
| 208 | traceCodeDescription | `String` | Trace Code Description |
| 209 | uDFC01 | `String` | UDFC01 |
| 210 | uDFC02 | `String` | UDFC02 |
| 211 | uDFC03 | `String` | UDFC03 |
| 212 | uDFC04 | `String` | UDFC04 |
| 213 | uDFC05 | `String` | UDFC05 |
| 214 | uDFC06 | `String` | UDFC06 |
| 215 | uDFC07 | `String` | UDFC07 |
| 216 | uDFC08 | `String` | UDFC08 |
| 217 | uDFC09 | `String` | UDFC09 |
| 218 | uDFC10 | `String` | UDFC10 |
| 219 | uDFC11 | `String` | UDFC11 |
| 220 | uDFC12 | `String` | UDFC12 |
| 221 | uDFC13 | `String` | UDFC13 |
| 222 | uDFC14 | `String` | UDFC14 |
| 223 | uDFC15 | `String` | UDFC15 |
| 224 | uDFC16 | `String` | UDFC16 |
| 225 | uDFC17 | `String` | UDFC17 |
| 226 | uDFC18 | `String` | UDFC18 |
| 227 | uDFC19 | `String` | UDFC19 |
| 228 | uDFC20 | `String` | UDFC20 |
| 229 | uDFC21 | `String` | UDFC21 |
| 230 | uDFC22 | `String` | UDFC22 |
| 231 | uDFC23 | `String` | UDFC23 |
| 232 | uDFC24 | `String` | UDFC24 |
| 233 | uDFC25 | `String` | UDFC25 |
| 234 | uDFC26 | `String` | UDFC26 |
| 235 | uDFC27 | `String` | UDFC27 |
| 236 | uDFC28 | `String` | UDFC28 |
| 237 | uDFC29 | `String` | UDFC29 |
| 238 | uDFC30 | `String` | UDFC30 |
| 239 | uDFC31 | `String` | UDFC31 |
| 240 | uDFC32 | `String` | UDFC32 |
| 241 | uDFC33 | `String` | UDFC33 |
| 242 | uDFC34 | `String` | UDFC34 |
| 243 | uDFC35 | `String` | UDFC35 |
| 244 | uDFC36 | `String` | UDFC36 |
| 245 | uDFC37 | `String` | UDFC37 |
| 246 | uDFC38 | `String` | UDFC38 |
| 247 | uDFC39 | `String` | UDFC39 |
| 248 | uDFC40 | `String` | UDFC40 |
| 249 | uDFD01 | `Date` | UDFD01 |
| 250 | uDFD02 | `Date` | UDFD02 |
| 251 | uDFD03 | `Date` | UDFD03 |
| 252 | uDFD04 | `Date` | UDFD04 |
| 253 | uDFD05 | `Date` | UDFD05 |
| 254 | uDFD06 | `Date` | UDFD06 |
| 255 | uDFD07 | `Date` | UDFD07 |
| 256 | uDFD08 | `Date` | UDFD08 |
| 257 | uDFD09 | `Date` | UDFD09 |
| 258 | uDFD10 | `Date` | UDFD10 |
| 259 | uDFD11 | `Date` | UDFD11 |
| 260 | uDFD12 | `Date` | UDFD12 |
| 261 | uDFD13 | `Date` | UDFD13 |
| 262 | uDFD14 | `Date` | UDFD14 |
| 263 | uDFD15 | `Date` | UDFD15 |
| 264 | uDFD16 | `Date` | UDFD16 |
| 265 | uDFD17 | `Date` | UDFD17 |
| 266 | uDFD18 | `Date` | UDFD18 |
| 267 | uDFD19 | `Date` | UDFD19 |
| 268 | uDFD20 | `Date` | UDFD20 |
| 269 | uDFN01 | `Float` | UDFN01 |
| 270 | uDFN02 | `Float` | UDFN02 |
| 271 | uDFN03 | `Float` | UDFN03 |
| 272 | uDFN04 | `Float` | UDFN04 |
| 273 | uDFN05 | `Float` | UDFN05 |
| 274 | uDFN06 | `Float` | UDFN06 |
| 275 | uDFN07 | `Float` | UDFN07 |
| 276 | uDFN08 | `Float` | UDFN08 |
| 277 | uDFN09 | `Float` | UDFN09 |
| 278 | uDFN10 | `Float` | UDFN10 |
| 279 | uDFN11 | `Float` | UDFN11 |
| 280 | uDFN12 | `Float` | UDFN12 |
| 281 | uDFN13 | `Float` | UDFN13 |
| 282 | uDFN14 | `Float` | UDFN14 |
| 283 | uDFN15 | `Float` | UDFN15 |
| 284 | uDFN16 | `Float` | UDFN16 |
| 285 | uDFN17 | `Float` | UDFN17 |
| 286 | uDFN18 | `Float` | UDFN18 |
| 287 | uDFN19 | `Float` | UDFN19 |
| 288 | uDFN20 | `Float` | UDFN20 |
| 289 | uDFN21 | `Float` | UDFN21 |
| 290 | uDFN22 | `Float` | UDFN22 |
| 291 | uDFN23 | `Float` | UDFN23 |
| 292 | uDFN24 | `Float` | UDFN24 |
| 293 | uDFN25 | `Float` | UDFN25 |
| 294 | uDFN26 | `Float` | UDFN26 |
| 295 | uDFN27 | `Float` | UDFN27 |
| 296 | uDFN28 | `Float` | UDFN28 |
| 297 | uDFN29 | `Float` | UDFN29 |
| 298 | uDFN30 | `Float` | UDFN30 |
| 299 | uDFN31 | `Float` | UDFN31 |
| 300 | uDFN32 | `Float` | UDFN32 |
| 301 | uDFN33 | `Float` | UDFN33 |
| 302 | uDFN34 | `Float` | UDFN34 |
| 303 | uDFN35 | `Float` | UDFN35 |
| 304 | uDFN36 | `Float` | UDFN36 |
| 305 | uDFN37 | `Float` | UDFN37 |
| 306 | uDFN38 | `Float` | UDFN38 |
| 307 | uDFN39 | `Float` | UDFN39 |
| 308 | uDFN40 | `Float` | UDFN40 |
| 309 | updateDate | `DateTime` | Update Date |
| 310 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 311 | updateUser | `String` | Update User |
| 312 | vipName | `String` | VIP Name |
| 313 | vipStatus | `String` | VIP Status |
| 314 | xcompanyName | `String` | Extended Byte Company Name |
| 315 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 316 | xfirstName | `String` | Xfirst Name |
| 317 | xlastName | `String` | Xlast Name |
| 318 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationDepositScheduleDetailsType

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

### BookingReservationExtendedRateCodeDetailsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addAfterRounding | `Float` | Amount to be added after rounding |
| 2 | adultCharge | `Float` | Adult Charge |
| 3 | adultsThreshold | `Float` | Threshold for number of adults on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| 4 | adultsThresholdCharge | `Float` | Amount used to calculate price for adults when the number of adults on the reservation exceed the adult threshold. |
| 5 | advBaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the advanced dynamic base rate. |
| 6 | advBaseFltPct | `String` | Calculate as Flat [FLT] or Percentage [PCT] amount of the advanced dynamic base rate code. |
| 7 | advDailyBaseRateCode | `String` | Identifies the Advanced Daily Base Rate Code from which this rate detail was copied. |
| 8 | advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| 9 | ageRangeForBucket1 | `String` | Age Range for Bucket 1 |
| 10 | ageRangeForBucket2 | `String` | Age Range for Bucket 2 |
| 11 | ageRangeForBucket3 | `String` | Age Range for Bucket 3 |
| 12 | amount1Type | `String` | Indicate the amount type for the 1 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 13 | amount2Type | `String` | Indicate the amount type for the 2 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 14 | amount3Type | `String` | Indicate the amount type for the 3 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 15 | amount4Type | `String` | Indicate the amount type for the 4 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 16 | amount5Type | `String` | Indicate the amount type for the 5 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 17 | amountFor1Person | `Float` | Amount for 1 Person |
| 18 | amountFor2Persons | `Float` | Amount for 2 Persons |
| 19 | amountFor3Persons | `Float` | Amount for 3 Persons |
| 20 | amountFor4Persons | `Float` | Amount for 4 Persons |
| 21 | amountFor5Persons | `Float` | Amount for 5 adults |
| 22 | barAmount | `Float` | Stores the Percentage or Amount difference between BAR Rate code and this Rate Code. |
| 23 | barFltPct | `String` | Identifies if the amount column represents a Flat [FLT] or Percentage [PCT] value. |
| 24 | barRounding | `String` | Identifies the rounding formula for the BBAR Rate calculation. |
| 25 | barYn | `String` | Is this schedule applied to bar by los rate pushing also. |
| 26 | cAdultCharge | `Float` | Central Adult Charge |
| 27 | cAdultsThresholdCharge | `Float` | Central Adults Threshold Charge |
| 28 | cAdvanceBaseAmount | `Float` | Central Adv Base Amount |
| 29 | cAmount1 | `Float` | Central Amount 1 |
| 30 | cAmount2 | `Float` | Central Amount 2 |
| 31 | cAmount3 | `Float` | Central Amount 3 |
| 32 | cAmount4 | `Float` | Central Amount 4 |
| 33 | cAmount5 | `Float` | Central Amount 5 |
| 34 | cBarAmount | `Float` | Central Bar Amount |
| 35 | cChildCharge1 | `Float` | Central Child Charge 1 |
| 36 | cChildCharge2 | `Float` | Central Child Charge 2 |
| 37 | cChildCharge3 | `Float` | Central Child Charge 3 |
| 38 | cChildOwnCharge1 | `Float` | Central Child Own Charge 1 |
| 39 | cChildOwnCharge2 | `Float` | Central Child Own Charge 2 |
| 40 | cChildOwnCharge3 | `Float` | Central Child Own Charge 3 |
| 41 | cChildOwnCharge4 | `Float` | Central Child Own Charge 4 |
| 42 | cChildrenCharge | `Float` | Central Children Charge |
| 43 | cChildrenThresholdCharge | `Float` | Central Children Threshold Charge |
| 44 | cDifferenceAmount1 | `Float` | Central Diff Amount 1 |
| 45 | cDifferenceAmount2 | `Float` | Central Diff Amount 2 |
| 46 | cDifferenceAmount3 | `Float` | Central Diff Amount 3 |
| 47 | cDifferenceAmount4 | `Float` | Central Diff Amount 4 |
| 48 | cDifferenceAmount5 | `Float` | Central Diff Amount 5 |
| 49 | cDifferenceAmountExtraAdult | `Float` | Central Diff Amount Extra Adult |
| 50 | cExchangeDate | `Date` | Central Xchange Date |
| 51 | cExchangeRate | `Float` | Central Xchange Rate |
| 52 | cFlatIncrease | `Float` | Central Flat Increase |
| 53 | cLos1Amount | `Float` | Central Los1 Amt |
| 54 | cLos10Amount | `Float` | Central Los10 Amt |
| 55 | cLos11Amount | `Float` | Central Los11 Amt |
| 56 | cLos12Amount | `Float` | Central Los12 Amt |
| 57 | cLos13Amount | `Float` | Central Los13 Amt |
| 58 | cLos14Amount | `Float` | Central Los14 Amt |
| 59 | cLos2Amount | `Float` | Central Los2 Amt |
| 60 | cLos3Amount | `Float` | Central Los3 Amt |
| 61 | cLos4Amount | `Float` | Central Los4 Amt |
| 62 | cLos5Amount | `Float` | Central Los5 Amt |
| 63 | cLos6Amount | `Float` | Central Los6 Amt |
| 64 | cLos7Amount | `Float` | Central Los7 Amt |
| 65 | cLos8Amount | `Float` | Central Los8 Amt |
| 66 | cLos9Amount | `Float` | Central Los9 Amt |
| 67 | cMaximumAmount1 | `Float` | Central Maximum Amount 1 |
| 68 | cMaximumAmount2 | `Float` | Central Maximum Amount 2 |
| 69 | cMinimumAmount1 | `Float` | Central Minimum Amount 1 |
| 70 | cMinimumAmount2 | `Float` | Central Minimum Amount 2 |
| 71 | cOccupantsThresholdCharge | `Float` | Central Occupants Threshold Charge |
| 72 | cPackageRateStayOver | `Float` | Central Package Rate Stay Over |
| 73 | cRoomCost | `Float` | Central Room Cost |
| 74 | calculationFlag | `String` | Indicates Global rate update was (P)ercent or (F)lat |
| 75 | catPackagePriceCode | `String` | Stores the catering package price code for the package linked to the rate code in rate header. |
| 76 | centralMarketCode | `String` | Central Market Code |
| 77 | centralMarketDescription | `String` | Central Market Description |
| 78 | centralMarketGroupCode | `String` | Central Market Group Code |
| 79 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 80 | centralPackageCode | `String` | Central Package Code |
| 81 | centralRoomType | `String` | Central Room Type |
| 82 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 83 | centralSeasonCode | `String` | Central Season Code |
| 84 | centralSourceCode | `String` | Central Source Code |
| 85 | centralSourceDescription | `String` | Central Source Description |
| 86 | centralSourceGroupCode | `String` | Central Source Group Code |
| 87 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 88 | childExcThreshold1 | `String` | Indicates whether the child 1 count will be excluded while calculating the total occupants threshold excess amount. |
| 89 | childExcThreshold2 | `String` | Indicates whether the child 2 count will be excluded while calculating the total occupants threshold excess amount. |
| 90 | childExcThreshold3 | `String` | Indicates whether the child 3 count will be excluded while calculating the total occupants threshold excess amount. |
| 91 | childOwnCharge1 | `Float` | Child Own Charge 1 |
| 92 | childOwnCharge2 | `Float` | Child Own Charge 2 |
| 93 | childOwnCharge3 | `Float` | Child Own Charge 3 |
| 94 | childOwnCharge4 | `Float` | Child Own Charge 4 |
| 95 | childrenFreeStay | `Float` | Number of children that will stay free. |
| 96 | childrenCharge | `Float` | Children Charge |
| 97 | childrenThreshold | `Float` | Threshold for number of children on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| 98 | childrenThresholdCharge | `Float` | Amount used to calculate price for children when the number of children on the reservation exceed the children threshold. |
| 99 | currencyCode | `String` | Currency Code |
| 100 | currencyDescription | `String` | Currency Description |
| 101 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 102 | deletedflag | `String` | Deleted Flag |
| 103 | depositRequieredYn | `String` | Deposit required Y/N |
| 104 | differenceAmount1 | `Float` | Contains a flat/percentage value for 1 Adult differential. |
| 105 | differenceAmount2 | `Float` | Contains a flat/percentage value for 2 Adult differential. |
| 106 | differenceAmount3 | `Float` | Contains a flat/percentage value for 3 Adult differential. |
| 107 | differenceAmount4 | `Float` | Contains a flat/percentage value for 4 Adult differential. |
| 108 | differenceAmount5 | `Float` | Contains a flat/percentage value for 5 Adult differential. |
| 109 | differenceAmountExtraAdult | `Float` | Contains a flat/percentage value for Extra Adult differential. |
| 110 | differencePercentage1Yn | `String` | Indicate if percentage value for 1 Adult differential should be used. |
| 111 | differencePercentage2Yn | `String` | Indicate if percentage value for 2 Adult differential should be used. |
| 112 | differencePercentage3Yn | `String` | Indicate if percentage value for 3 Adult differential should be used. |
| 113 | differencePercentage4Yn | `String` | Indicate if percentage value for 4 Adult differential should be used. |
| 114 | differencePercentage5Yn | `String` | Indicate if percentage value for 5 Adult differential should be used. |
| 115 | differencePercentageExtraAdultYn | `String` | Indicate if percentage value for Extra Adult differential should be used. |
| 116 | endDate | `Date` | End Date |
| 117 | externalRateSetId | `Float` | This field is required by OXI to store the external system rate_set_id to be used for locating the record in rate_set table during an update. |
| 118 | extraAdultType | `String` | Indicate the amount type for the Extra Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| 119 | flatIncrease | `Float` | Flat Increase Amount |
| 120 | globalRateUpdateYn | `String` | Indicates if Rate set created by Global Rate Update |
| 121 | inactiveDate | `Date` | Inactive Date |
| 122 | inactiveflag | `String` | Inactive Flag |
| 123 | insertDate | `DateTime` | Insert Date |
| 124 | insertUser | `Float` | Insert User |
| 125 | internalLocationId | `String` | Location ID |
| 126 | internalOrganizationId | `Float` | Organization ID |
| 127 | internalRatesetid | `Float` | Ratesetid |
| 128 | jRNUpdateDate | `Date` | JRN Update Date |
| 129 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 130 | lengthOfStay1Amount | `Float` | LOS1 amount for prevailing rate code. |
| 131 | lengthOfStay10Amount | `Float` | LOS10 amount for prevailing rate code. |
| 132 | lengthOfStay11Amount | `Float` | LOS11 amount for prevailing rate code. |
| 133 | lengthOfStay12Amount | `Float` | LOS12 amount for prevailing rate code. |
| 134 | lengthOfStay13Amount | `Float` | LOS13 amount for prevailing rate code. |
| 135 | lengthOfStay14Amount | `Float` | LOS14 amount for prevailing rate code. |
| 136 | lengthOfStay2Amount | `Float` | LOS2 amount for prevailing rate code. |
| 137 | lengthOfStay3Amount | `Float` | LOS3 amount for prevailing rate code. |
| 138 | lengthOfStay4Amount | `Float` | LOS4 amount for prevailing rate code. |
| 139 | lengthOfStay5Amount | `Float` | LOS5 amount for prevailing rate code. |
| 140 | lengthOfStay6Amount | `Float` | LOS6 amount for prevailing rate code. |
| 141 | lengthOfStay7Amount | `Float` | LOS7 amount for prevailing rate code. |
| 142 | lengthOfStay8Amount | `Float` | LOS8 amount for prevailing rate code. |
| 143 | lengthOfStay9Amount | `Float` | LOS9 amount for prevailing rate code. |
| 144 | linkRateSetId | `Float` | Rate set id of the base rates rate set. |
| 145 | locationID | `String` | Internal ID to uniquely identify the Property |
| 146 | marketCode | `String` | Market Code |
| 147 | marketDescription | `String` | Market Description |
| 148 | marketGroupCode | `String` | Market Group Code |
| 149 | marketGroupDescription | `String` | Market Group Description |
| 150 | maximumAmount1 | `Float` | Maximum rate amount value for 1 adult. |
| 151 | maximumAmount2 | `Float` | Maximum rate amount value for 2 adults. |
| 152 | minChildrenForFreeStay | `Float` | Represents every x number of children to get free "num_children_stay_free" |
| 153 | minimumAmount1 | `Float` | Minimum rate amount value for 1 adult. |
| 154 | minimumAmount2 | `Float` | Minimum rate amount value for 2 adults. |
| 155 | minimumClosingProbability | `Float` | Not used |
| 156 | occupantsThreshold | `Float` | Threshold for number of occupants on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| 157 | occupantsThresholdCharge | `Float` | Amount used to calculate price for occupants when the number of occupants on the reservation exceed the occupant threshold. |
| 158 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 159 | packageAdultStayOver | `Float` | The amount to charge per extra adult on every additional day of stay for a package that extends beyo |
| 160 | packageChildrenStayOver | `Float` | The amount to charge per extra child on every additional day of stay for a package that extends beyo |
| 161 | packageCode | `String` | Package Code |
| 162 | packageRateStayOver | `Float` | The amount to charge extra on every additional day of stay for a package that extends beyond the inc |
| 163 | percentIncrease | `Float` | Not used |
| 164 | pointsRequired | `Float` | Points Required |
| 165 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 166 | property | `String` | Code to uniquely identify the Property |
| 167 | rateAvailableOnFridaysYN | `String` | Rate Available on Fridays YN |
| 168 | rateAvailableOnMondaysYN | `String` | Rate Available on Mondays YN |
| 169 | rateAvailableOnSaturdaysYN | `String` | Rate Available on Saturdays YN |
| 170 | rateAvailableOnSundaysYN | `String` | Rate Available on Sundays YN |
| 171 | rateAvailableOnThursdaysYN | `String` | Rate Available on Thursdays YN |
| 172 | rateAvailableOnTuesdaysYN | `String` | Rate Available on Tuesdays YN |
| 173 | rateAvailableOnWednesdaysYN | `String` | Rate Available on Wednesdays YN |
| 174 | rateCode | `String` | Rate Code |
| 175 | rateCodeDesc | `String` | Event Reservation Rate Code Description |
| 176 | rateCodeId | `String` | Rate Code ID |
| 177 | rateRule | `String` | Rate Rule |
| 178 | rateSetId | `Float` | Rate Set ID |
| 179 | rateForChildInAgeBucket1 | `Float` | Child charge for defined rate bucket 1. |
| 180 | rateForChildInAgeBucket2 | `Float` | Child charge for defined rate bucket 2. |
| 181 | rateForChildInAgeBucket3 | `Float` | Child charge for defined rate bucket 3. |
| 182 | ratesActiveYn | `String` | Indicates if the rate amounts are activated. |
| 183 | ratetierid | `Float` | Ratetierid |
| 184 | repSeasonDescription | `String` | Reporting Season Desc |
| 185 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 186 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 187 | roomCost | `Float` | Room Cost |
| 188 | roomType | `String` | Room Type |
| 189 | roomTypeDescription | `String` | Room Type Description |
| 190 | roundToNearest | `Float` | Type of rounding after rate_update |
| 191 | season | `String` | Season |
| 192 | seasonCode | `String` | Season Code |
| 193 | seasonDesc | `String` | User defined description for season. |
| 194 | sourceCode | `String` | Source Code |
| 195 | sourceDescription | `String` | Source Description |
| 196 | sourceGroupCode | `String` | Source Group Code |
| 197 | sourceGroupDescription | `String` | Source Group Description |
| 198 | startDate | `Date` | Start Date |
| 199 | tierId | `Float` | Tier ID for the Rate Detail. |
| 200 | updateDate | `DateTime` | Update Date |
| 201 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedRoutingInstructionDetailsType

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

### BookingReservationExtendedFolioTaxDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `Float` | Account Code |
| 2 | addresseeNameId | `Float` | Addressee Name ID |
| 3 | amountPostedFromAR | `Float` | This is to store amount posted from AR for a bill. In this case CLPAY will not have value if the bill is generated in AR |
| 4 | amountFromDirectBill | `Float` | The amount that has been paid using direct bill. |
| 5 | associatedBillDate | `Date` | Date on which the Original Bill was generated. This is used in case of Credit Bill. |
| 6 | associatedBillNumber | `String` | Associated Bill Number |
| 7 | associatedFiscalBillDate | `Date` | Associated Fiscal Bill number generation date. |
| 8 | associatedFiscalBillNumber | `String` | Associated Fiscal Bill number. |
| 9 | associatedFiscalBillNumberGenerationTime | `String` | Associated Fiscal Bill number generation time. |
| 10 | associatedSeqNumber | `Float` | Self referencing sequence number to gather information for other operations. |
| 11 | billGenerationDate | `Date` | Bill Generation Date |
| 12 | billNumber | `Float` | Bill Number |
| 13 | billPaymentTrxNumber | `Float` | Bill Payment Transaction No |
| 14 | billPrefix | `String` | Bill Prefix |
| 15 | billSequenceNumber | `Float` | Bill Sequence Number |
| 16 | billStartDate | `Date` | Date of the first charge in the bill. |
| 17 | billStatus | `String` | Bill Status |
| 18 | businessDate | `Date` | Business Date |
| 19 | businessId | `String` | Business ID |
| 20 | cCashpay | `Float` | Central Cashpay |
| 21 | cCcpay | `Float` | Central Ccpay |
| 22 | cClarpay | `Float` | Central Clarpay |
| 23 | cClpay | `Float` | Central Clpay |
| 24 | cCollectionTax1 | `Float` | Central Coll Tax1 |
| 25 | cCollectionTax2 | `Float` | Central Coll Tax2 |
| 26 | cCollectionTax3 | `Float` | Central Coll Tax3 |
| 27 | cCollectionTax4 | `Float` | Central Coll Tax4 |
| 28 | cCollectionTax5 | `Float` | Central Coll Tax5 |
| 29 | cDailyRunningTotal | `Float` | Central Daily Running Total |
| 30 | cDeposit | `Float` | Central Deposit |
| 31 | cExchangeDate | `Date` | Central Xchange Date |
| 32 | cExchangeRate | `Float` | Central Xchange Rate |
| 33 | cFiscalInvoiceCurrencyRate | `Float` | Central Fiscal Invoice Currency Rate |
| 34 | cNet1Amount | `Float` | Central Net1 Amt |
| 35 | cNet10Amount | `Float` | Central Net10 Amt |
| 36 | cNet11Amount | `Float` | Central Net11 Amt |
| 37 | cNet12Amount | `Float` | Central Net12 Amt |
| 38 | cNet13Amount | `Float` | Central Net13 Amt |
| 39 | cNet14Amount | `Float` | Central Net14 Amt |
| 40 | cNet15Amount | `Float` | Central Net15 Amt |
| 41 | cNet16Amount | `Float` | Central Net16 Amt |
| 42 | cNet17Amount | `Float` | Central Net17 Amt |
| 43 | cNet18Amount | `Float` | Central Net18 Amt |
| 44 | cNet19Amount | `Float` | Central Net19 Amt |
| 45 | cNet2Amount | `Float` | Central Net2 Amt |
| 46 | cNet20Amount | `Float` | Central Net20 Amt |
| 47 | cNet3Amount | `Float` | Central Net3 Amt |
| 48 | cNet4Amount | `Float` | Central Net4 Amt |
| 49 | cNet5Amount | `Float` | Central Net5 Amt |
| 50 | cNet6Amount | `Float` | Central Net6 Amt |
| 51 | cNet7Amount | `Float` | Central Net7 Amt |
| 52 | cNet8Amount | `Float` | Central Net8 Amt |
| 53 | cNet9Amount | `Float` | Central Net9 Amt |
| 54 | cPaidout | `Float` | Central Paidout |
| 55 | cPerpetualAmount | `Float` | Central Perpetual Amount |
| 56 | cPnet1Amount | `Float` | Central Pnet1 Amt |
| 57 | cPnet10Amount | `Float` | Central Pnet10 Amt |
| 58 | cPnet11Amount | `Float` | Central Pnet11 Amt |
| 59 | cPnet12Amount | `Float` | Central Pnet12 Amt |
| 60 | cPnet13Amount | `Float` | Central Pnet13 Amt |
| 61 | cPnet14Amount | `Float` | Central Pnet14 Amt |
| 62 | cPnet15Amount | `Float` | Central Pnet15 Amt |
| 63 | cPnet16Amount | `Float` | Central Pnet16 Amt |
| 64 | cPnet17Amount | `Float` | Central Pnet17 Amt |
| 65 | cPnet18Amount | `Float` | Central Pnet18 Amt |
| 66 | cPnet19Amount | `Float` | Central Pnet19 Amt |
| 67 | cPnet2Amount | `Float` | Central Pnet2 Amt |
| 68 | cPnet20Amount | `Float` | Central Pnet20 Amt |
| 69 | cPnet3Amount | `Float` | Central Pnet3 Amt |
| 70 | cPnet4Amount | `Float` | Central Pnet4 Amt |
| 71 | cPnet5Amount | `Float` | Central Pnet5 Amt |
| 72 | cPnet6Amount | `Float` | Central Pnet6 Amt |
| 73 | cPnet7Amount | `Float` | Central Pnet7 Amt |
| 74 | cPnet8Amount | `Float` | Central Pnet8 Amt |
| 75 | cPnet9Amount | `Float` | Central Pnet9 Amt |
| 76 | cPtax1Amount | `Float` | Central Ptax1 Amt |
| 77 | cPtax10Amount | `Float` | Central Ptax10 Amt |
| 78 | cPtax11Amount | `Float` | Central Ptax11 Amt |
| 79 | cPtax12Amount | `Float` | Central Ptax12 Amt |
| 80 | cPtax13Amount | `Float` | Central Ptax13 Amt |
| 81 | cPtax14Amount | `Float` | Central Ptax14 Amt |
| 82 | cPtax15Amount | `Float` | Central Ptax15 Amt |
| 83 | cPtax16Amount | `Float` | Central Ptax16 Amt |
| 84 | cPtax17Amount | `Float` | Central Ptax17 Amt |
| 85 | cPtax18Amount | `Float` | Central Ptax18 Amt |
| 86 | cPtax19Amount | `Float` | Central Ptax19 Amt |
| 87 | cPtax2Amount | `Float` | Central Ptax2 Amt |
| 88 | cPtax20Amount | `Float` | Central Ptax20 Amt |
| 89 | cPtax3Amount | `Float` | Central Ptax3 Amt |
| 90 | cPtax4Amount | `Float` | Central Ptax4 Amt |
| 91 | cPtax5Amount | `Float` | Central Ptax5 Amt |
| 92 | cPtax6Amount | `Float` | Central Ptax6 Amt |
| 93 | cPtax7Amount | `Float` | Central Ptax7 Amt |
| 94 | cPtax8Amount | `Float` | Central Ptax8 Amt |
| 95 | cPtax9Amount | `Float` | Central Ptax9 Amt |
| 96 | cPtotNonrevNonTaxable | `Float` | Central Ptot Nonrev Nontaxable |
| 97 | cPtotNonrevTaxable | `Float` | Central Ptot Nonrev Taxable |
| 98 | cPtotRevenueNonTaxable | `Float` | Central Ptot Rev Nontaxable |
| 99 | cPtotRevenueTaxable | `Float` | Central Ptot Rev Taxable |
| 100 | cRealPerpetualAmount | `Float` | Central Real Perpetual Amount |
| 101 | cTax1Amount | `Float` | Central Tax1 Amt |
| 102 | cTax2Amount | `Float` | Central Tax2 Amt |
| 103 | cTaxCode1 | `String` | Central Tax Code 1 |
| 104 | cTaxCode10 | `String` | Central Tax Code 10 |
| 105 | cTaxCode11 | `String` | Central Tax Code 11 |
| 106 | cTaxCode12 | `String` | Central Tax Code 12 |
| 107 | cTaxCode13 | `String` | Central Tax Code 13 |
| 108 | cTaxCode14 | `String` | Central Tax Code 14 |
| 109 | cTaxCode15 | `String` | Central Tax Code 15 |
| 110 | cTaxCode16 | `String` | Central Tax Code 16 |
| 111 | cTaxCode17 | `String` | Central Tax Code 17 |
| 112 | cTaxCode18 | `String` | Central Tax Code 18 |
| 113 | cTaxCode19 | `String` | Central Tax Code 19 |
| 114 | cTaxCode2 | `String` | Central Tax Code 2 |
| 115 | cTaxCode20 | `String` | Central Tax Code 20 |
| 116 | cTaxCode3 | `String` | Central Tax Code 3 |
| 117 | cTaxCode4 | `String` | Central Tax Code 4 |
| 118 | cTaxCode5 | `String` | Central Tax Code 5 |
| 119 | cTaxCode6 | `String` | Central Tax Code 6 |
| 120 | cTaxCode7 | `String` | Central Tax Code 7 |
| 121 | cTaxCode8 | `String` | Central Tax Code 8 |
| 122 | cTaxCode9 | `String` | Central Tax Code 9 |
| 123 | cTaxCodeDescription1 | `String` | Central Tax Code Desc 1 |
| 124 | cTaxCodeDescription10 | `String` | Central Tax Code Desc 10 |
| 125 | cTaxCodeDescription11 | `String` | Central Tax Code Desc 11 |
| 126 | cTaxCodeDescription12 | `String` | Central Tax Code Desc 12 |
| 127 | cTaxCodeDescription13 | `String` | Central Tax Code Desc 13 |
| 128 | cTaxCodeDescription14 | `String` | Central Tax Code Desc 14 |
| 129 | cTaxCodeDescription15 | `String` | Central Tax Code Desc 15 |
| 130 | cTaxCodeDescription16 | `String` | Central Tax Code Desc 16 |
| 131 | cTaxCodeDescription17 | `String` | Central Tax Code Desc 17 |
| 132 | cTaxCodeDescription18 | `String` | Central Tax Code Desc 18 |
| 133 | cTaxCodeDescription19 | `String` | Central Tax Code Desc 19 |
| 134 | cTaxCodeDescription2 | `String` | Central Tax Code Desc 2 |
| 135 | cTaxCodeDescription20 | `String` | Central Tax Code Desc 20 |
| 136 | cTaxCodeDescription3 | `String` | Central Tax Code Desc 3 |
| 137 | cTaxCodeDescription4 | `String` | Central Tax Code Desc 4 |
| 138 | cTaxCodeDescription5 | `String` | Central Tax Code Desc 5 |
| 139 | cTaxCodeDescription6 | `String` | Central Tax Code Desc 6 |
| 140 | cTaxCodeDescription7 | `String` | Central Tax Code Desc 7 |
| 141 | cTaxCodeDescription8 | `String` | Central Tax Code Desc 8 |
| 142 | cTaxCodeDescription9 | `String` | Central Tax Code Desc 9 |
| 143 | cTax10Amount | `Float` | Central Tax10 Amt |
| 144 | cTax11Amount | `Float` | Central Tax11 Amt |
| 145 | cTax12Amount | `Float` | Central Tax12 Amt |
| 146 | cTax13Amount | `Float` | Central Tax13 Amt |
| 147 | cTax14Amount | `Float` | Central Tax14 Amt |
| 148 | cTax15Amount | `Float` | Central Tax15 Amt |
| 149 | cTax16Amount | `Float` | Central Tax16 Amt |
| 150 | cTax17Amount | `Float` | Central Tax17 Amt |
| 151 | cTax18Amount | `Float` | Central Tax18 Amt |
| 152 | cTax19Amount | `Float` | Central Tax19 Amt |
| 153 | cTax20Amount | `Float` | Central Tax20 Amt |
| 154 | cTax3Amount | `Float` | Central Tax3 Amt |
| 155 | cTax4Amount | `Float` | Central Tax4 Amt |
| 156 | cTax5Amount | `Float` | Central Tax5 Amt |
| 157 | cTax6Amount | `Float` | Central Tax6 Amt |
| 158 | cTax7Amount | `Float` | Central Tax7 Amt |
| 159 | cTax8Amount | `Float` | Central Tax8 Amt |
| 160 | cTax9Amount | `Float` | Central Tax9 Amt |
| 161 | cTotalGross | `Float` | Central Total Gross |
| 162 | cTotalNet | `Float` | Central Total Net |
| 163 | cTotalNonTaxable | `Float` | Central Total Nontaxable |
| 164 | cTotalNonrevNonTaxable | `Float` | Central Tot Nonrev Nontaxable |
| 165 | cTotalNonrevTaxable | `Float` | Central Tot Nonrev Taxable |
| 166 | cTotalRevenueNonTaxable | `Float` | Central Tot Rev Nontaxable |
| 167 | cTotalRevenueTaxable | `Float` | Central Tot Rev Taxable |
| 168 | cTotalTax | `Float` | Central Total Tax |
| 169 | cXnet1Amount | `Float` | Central Xnet1 Amt |
| 170 | cXnet10Amount | `Float` | Central Xnet10 Amt |
| 171 | cXnet11Amount | `Float` | Central Xnet11 Amt |
| 172 | cXnet12Amount | `Float` | Central Xnet12 Amt |
| 173 | cXnet13Amount | `Float` | Central Xnet13 Amt |
| 174 | cXnet14Amount | `Float` | Central Xnet14 Amt |
| 175 | cXnet15Amount | `Float` | Central Xnet15 Amt |
| 176 | cXnet16Amount | `Float` | Central Xnet16 Amt |
| 177 | cXnet17Amount | `Float` | Central Xnet17 Amt |
| 178 | cXnet18Amount | `Float` | Central Xnet18 Amt |
| 179 | cXnet19Amount | `Float` | Central Xnet19 Amt |
| 180 | cXnet2Amount | `Float` | Central Xnet2 Amt |
| 181 | cXnet20Amount | `Float` | Central Xnet20 Amt |
| 182 | cXnet3Amount | `Float` | Central Xnet3 Amt |
| 183 | cXnet4Amount | `Float` | Central Xnet4 Amt |
| 184 | cXnet5Amount | `Float` | Central Xnet5 Amt |
| 185 | cXnet6Amount | `Float` | Central Xnet6 Amt |
| 186 | cXnet7Amount | `Float` | Central Xnet7 Amt |
| 187 | cXnet8Amount | `Float` | Central Xnet8 Amt |
| 188 | cXnet9Amount | `Float` | Central Xnet9 Amt |
| 189 | cXtax1Amount | `Float` | Central Xtax1 Amt |
| 190 | cXtax10Amount | `Float` | Central Xtax10 Amt |
| 191 | cXtax11Amount | `Float` | Central Xtax11 Amt |
| 192 | cXtax12Amount | `Float` | Central Xtax12 Amt |
| 193 | cXtax13Amount | `Float` | Central Xtax13 Amt |
| 194 | cXtax14Amount | `Float` | Central Xtax14 Amt |
| 195 | cXtax15Amount | `Float` | Central Xtax15 Amt |
| 196 | cXtax16Amount | `Float` | Central Xtax16 Amt |
| 197 | cXtax17Amount | `Float` | Central Xtax17 Amt |
| 198 | cXtax18Amount | `Float` | Central Xtax18 Amt |
| 199 | cXtax19Amount | `Float` | Central Xtax19 Amt |
| 200 | cXtax2Amount | `Float` | Central Xtax2 Amt |
| 201 | cXtax20Amount | `Float` | Central Xtax20 Amt |
| 202 | cXtax3Amount | `Float` | Central Xtax3 Amt |
| 203 | cXtax4Amount | `Float` | Central Xtax4 Amt |
| 204 | cXtax5Amount | `Float` | Central Xtax5 Amt |
| 205 | cXtax6Amount | `Float` | Central Xtax6 Amt |
| 206 | cXtax7Amount | `Float` | Central Xtax7 Amt |
| 207 | cXtax8Amount | `Float` | Central Xtax8 Amt |
| 208 | cXtax9Amount | `Float` | Central Xtax9 Amt |
| 209 | cashRegisterId | `String` | Cash Register ID |
| 210 | cashRegisterInvNumber | `Float` | Internal sequence number for the Cash Register ID. |
| 211 | cashTotal | `Float` | Total paid in cash |
| 212 | cashierID | `Float` | Cashier ID |
| 213 | centralTaxRate1 | `Float` | Central Tax Rate 1 |
| 214 | centralTaxRate10 | `Float` | Central Tax Rate 10 |
| 215 | centralTaxRate11 | `Float` | Central Tax Rate 11 |
| 216 | centralTaxRate12 | `Float` | Central Tax Rate 12 |
| 217 | centralTaxRate13 | `Float` | Central Tax Rate 13 |
| 218 | centralTaxRate14 | `Float` | Central Tax Rate 14 |
| 219 | centralTaxRate15 | `Float` | Central Tax Rate 15 |
| 220 | centralTaxRate16 | `Float` | Central Tax Rate 16 |
| 221 | centralTaxRate17 | `Float` | Central Tax Rate 17 |
| 222 | centralTaxRate18 | `Float` | Central Tax Rate 18 |
| 223 | centralTaxRate19 | `Float` | Central Tax Rate 19 |
| 224 | centralTaxRate2 | `Float` | Central Tax Rate 2 |
| 225 | centralTaxRate20 | `Float` | Central Tax Rate 20 |
| 226 | centralTaxRate3 | `Float` | Central Tax Rate 3 |
| 227 | centralTaxRate4 | `Float` | Central Tax Rate 4 |
| 228 | centralTaxRate5 | `Float` | Central Tax Rate 5 |
| 229 | centralTaxRate6 | `Float` | Central Tax Rate 6 |
| 230 | centralTaxRate7 | `Float` | Central Tax Rate 7 |
| 231 | centralTaxRate8 | `Float` | Central Tax Rate 8 |
| 232 | centralTaxRate9 | `Float` | Central Tax Rate 9 |
| 233 | city | `String` | City |
| 234 | cityLedgerYN | `String` | City Ledger YN |
| 235 | clTrxNumber | `Float` | Internal number given to the direct bill payment in financial_transactions. |
| 236 | collectionAgentTotalTax1 | `Float` | Collection Agent Total Tax 1 |
| 237 | collectionAgentTotalTax2 | `Float` | Collection Agent Total Tax 2 |
| 238 | collectionAgentTotalTax3 | `Float` | Collection Agent Total Tax 3 |
| 239 | collectionAgentTotalTax4 | `Float` | Collection Agent Total Tax 4 |
| 240 | collectionAgentTotalTax5 | `Float` | Collection Agent Total Tax 5 |
| 241 | companyFinancialValue | `String` | The financial value of the company. |
| 242 | companyName | `String` | Company Name |
| 243 | companyType | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| 244 | compressBillNo | `String` | To store the Compressed Bill No. and Converted Bill number information |
| 245 | creditBillGeneratedYN | `String` | Indicates if a credit bill has been generated for this folio. |
| 246 | creditBillNumber | `Float` | Credit Bill Number |
| 247 | creditCardTotal | `Float` | Total paid in the form of credit cards. |
| 248 | customNumber1 | `String` | Custom Number 1 |
| 249 | customNumber2 | `String` | Custom Number 2 |
| 250 | customNumber3 | `String` | Custom Number 3 |
| 251 | customNumber4 | `String` | Custom Number 4 |
| 252 | customNumber5 | `String` | Custom Number 5 |
| 253 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 254 | dailyRunningTotal | `Float` | Daily running total. |
| 255 | deletedFlag | `String` | Deleted Flag |
| 256 | deposit | `Float` | Total deposits. |
| 257 | depositReqReceiptNumber | `Float` | Deposit Req Receipt Number |
| 258 | documentCode | `String` | Unique Document Code |
| 259 | documentType | `String` | Document Type |
| 260 | eArchiveEttnNumber | `String` | Unique ETTN number for an E Archive invoice. |
| 261 | eArchiveNumber | `String` | E Archive number. |
| 262 | eArchiveReportNo | `String` | E Archive report number provided by external system e.g. PROTEL. |
| 263 | eArchiveStatus | `String` | E Archive status. |
| 264 | eInvoiceNumber | `String` | E-Invoice Number |
| 265 | eInvoiceStatus | `String` | E-Invoice number received from Portal+. This number be updated via Web Service call from Portal+. |
| 266 | fiscalBillCheckDigit | `Float` | Fiscal Bill Check Digit |
| 267 | fiscalBillGenerationDate | `Date` | Fiscal Bill Generation Date |
| 268 | fiscalBillGenerationTime | `String` | Fiscal Bill Generation Time |
| 269 | fiscalBillNumber | `String` | Fiscal Bill Number |
| 270 | fiscalInvoiceCurrency | `String` | Currency Code used by and sent to the Fiscal Service. |
| 271 | fiscalInvoiceCurrencyRate | `Float` | Exchange Rate of the Fiscal Invoice currency for settlement on the bill generation date. |
| 272 | fiscalSessionNo | `String` | Session number generated by the fiscal printer. This numbers gets reset during EOD. |
| 273 | fiscalUnitControlCode | `String` | Fiscal Unit Control Code |
| 274 | folioAddress | `String` | Folio Full Address. |
| 275 | folioAddressCorrectedYn | `String` | Indicates if the folio header was corrected. |
| 276 | folioAttachmentLinkId | `Float` | Folio Attachment Link ID |
| 277 | folioAttachmentStatus | `Float` | Folio Attachment Status |
| 278 | folioNo | `Float` | Folio Number |
| 279 | folioStyle | `String` | Folio Style |
| 280 | folioTaxSeqNumber | `Float` | Folio Tax Sequence No |
| 281 | folioTime | `String` | Folio Time |
| 282 | folioType | `String` | Folio Type |
| 283 | folioType1 | `String` | Folio Type 1 |
| 284 | folioTypeJoin | `String` | Folio Type Join |
| 285 | folioView | `Float` | Folio View |
| 286 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 287 | fullFolioNo | `String` | Full Folio Number |
| 288 | hasWatermarkYn | `String` | If PERMANENT FOLIO STORAGE is active this flag indicates whether the PDF file has the "Copy" watermark. |
| 289 | hotelName | `String` | Hotel name of the property at the time of bill generation. |
| 290 | insTimestamp | `DateTime` | Timestamp to capture the exact order of inserts. |
| 291 | insertDate | `DateTime` | Insert Date |
| 292 | invoiceNumber | `Float` | Invoice Number |
| 293 | jRNUpdateDate | `Date` | JRN Update Date |
| 294 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 295 | lastSignature | `String` | Last Signature |
| 296 | locationID | `String` | Internal ID to uniquely identify the Property |
| 297 | nRBusinessID | `String` | Business ID |
| 298 | nafApeHotelCode | `String` | NAF/APE code of the hotel at the time of bill generation. |
| 299 | nameId | `Float` | Name ID |
| 300 | nameTaxType | `String` | Name Tax Type |
| 301 | netAmount1 | `Float` | Net Amount 1 |
| 302 | netAmount10 | `Float` | Net Amount 10 |
| 303 | netAmount11 | `Float` | Net Amount 11 |
| 304 | netAmount12 | `Float` | Net Amount 12 |
| 305 | netAmount13 | `Float` | Net Amount 13 |
| 306 | netAmount14 | `Float` | Net Amount 14 |
| 307 | netAmount15 | `Float` | Net Amount 15 |
| 308 | netAmount16 | `Float` | Net Amount 16 |
| 309 | netAmount17 | `Float` | Net Amount 17 |
| 310 | netAmount18 | `Float` | Net Amount 18 |
| 311 | netAmount19 | `Float` | Net Amount 19 |
| 312 | netAmount2 | `Float` | Net Amount 2 |
| 313 | netAmount20 | `Float` | Net Amount 20 |
| 314 | netAmount3 | `Float` | Net Amount 3 |
| 315 | netAmount4 | `Float` | Net Amount 4 |
| 316 | netAmount5 | `Float` | Net Amount 5 |
| 317 | netAmount6 | `Float` | Net Amount 6 |
| 318 | netAmount7 | `Float` | Net Amount 7 |
| 319 | netAmount8 | `Float` | Net Amount 8 |
| 320 | netAmount9 | `Float` | Net Amount 9 |
| 321 | numberOfPages | `Float` | Number of pages for a given bill. |
| 322 | operaFiscalFolioStatus | `String` | This coulumn is used to store the status of Fiscal Folio /Payload Generation. The values will be SUCCESS - Payload has been sent successfully OFFLINE - User confirmed to generate Offline Folio i.e. Folio will be generated but Fiscal Folio/Payload not generated FAILURE - User do not want to create OFFLINE FOLIO but as FISCAL service is not available so the status is FAILURE i.e. in this case VOID Folio generated with FAILURE Fiscal Folio Status BLANK/NULL - Fiscal Printing is turned off or Past data after the upgrade. |
| 323 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 324 | pageNumber | `Float` | Stores the page number within the bill generation. |
| 325 | palmVideoFlag | `String` | Indicator to identify if the bill was generated from Video checkout or PALM.  (V->Video  P->PALM). |
| 326 | partnerFiscalFolioStatus | `String` | Partner Fiscal Folio Status |
| 327 | payeeAddress | `String` | Payee Address |
| 328 | payeeCountry | `String` | Payee Country |
| 329 | payeeFirstName | `String` | Payee First Name |
| 330 | payeeLastName | `String` | Payee Last Name |
| 331 | payeeName | `String` | Payee Name used for signature generation. |
| 332 | payeeNameID | `Float` | Payee Name ID |
| 333 | payeePostalCode | `String` | Payee Postal Code |
| 334 | payeeTaxID1 | `String` | Payee Tax ID 1 |
| 335 | payeeTaxID2 | `String` | Payee Tax ID 2 |
| 336 | payeeZipCode | `String` | Payee Zip Code used for signature generation. |
| 337 | paymentDate | `Date` | Payment Date |
| 338 | perpetualAmount | `Float` | Perpetual Amount. |
| 339 | pnet1Amt | `Float` | Parallel Net1 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 340 | pnet10Amt | `Float` | Parallel Net10 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 341 | pnet11Amt | `Float` | Parallel Net11 extension to the existing pnet amount. |
| 342 | pnet12Amt | `Float` | Parallel Net12 extension to the existing pnet amount. |
| 343 | pnet13Amt | `Float` | Parallel Net13 extension to the existing pnet amount. |
| 344 | pnet14Amt | `Float` | Parallel Net14 extension to the existing pnet amount. |
| 345 | pnet15Amt | `Float` | Parallel Net15 extension to the existing pnet amount. |
| 346 | pnet16Amt | `Float` | Parallel Net16 extension to the existing pnet amount. |
| 347 | pnet17Amt | `Float` | Parallel Net17 extension to the existing pnet amount. |
| 348 | pnet18Amt | `Float` | Parallel Net18 extension to the existing pnet amount. |
| 349 | pnet19Amt | `Float` | Parallel Net19 extension to the existing pnet amount. |
| 350 | pnet2Amt | `Float` | Parallel Net2 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 351 | pnet20Amt | `Float` | Parallel Net20 extension to the existing pnet amount. |
| 352 | pnet3Amt | `Float` | Parallel Net3 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 353 | pnet4Amt | `Float` | Parallel Net4 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 354 | pnet5Amt | `Float` | Parallel Net5 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 355 | pnet6Amt | `Float` | Parallel Net6 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 356 | pnet7Amt | `Float` | Parallel Net7 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 357 | pnet8Amt | `Float` | Parallel Net8 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 358 | pnet9Amt | `Float` | Parallel Net9 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 359 | postitSequenceNumber | `Float` | Postit Sequence Number |
| 360 | postitYN | `String` | Postit YN |
| 361 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 362 | printerQueueName | `String` | Printer Queue Name |
| 363 | profileTypeCode | `String` | Profile Type Code |
| 364 | promotionalText1 | `String` | Text returned by the credit card company |
| 365 | promotionalText2 | `String` | Text returned by the credit card company |
| 366 | property | `String` | Code to uniquely identify the Property |
| 367 | propertyBillPrefix | `String` | Property Bill Prefix |
| 368 | propertyTaxNumber | `String` | Property Tax Number |
| 369 | ptax1Amt | `Float` | Parallel Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 370 | ptax10Amt | `Float` | Parallel Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 371 | ptax11Amt | `Float` | Parallel Total tax11 amount extension to the existing ptax amounts. |
| 372 | ptax12Amt | `Float` | Parallel Total tax12 amount extension to the existing ptax amounts. |
| 373 | ptax13Amt | `Float` | Parallel Total tax13 amount extension to the existing ptax amounts. |
| 374 | ptax14Amt | `Float` | Parallel Total tax14 amount extension to the existing ptax amounts. |
| 375 | ptax15Amt | `Float` | Parallel Total tax15 amount extension to the existing ptax amounts. |
| 376 | ptax16Amt | `Float` | Parallel Total tax16 amount extension to the existing ptax amounts. |
| 377 | ptax17Amt | `Float` | Parallel Total tax17 amount extension to the existing ptax amounts. |
| 378 | ptax18Amt | `Float` | Parallel Total tax18 amount extension to the existing ptax amounts. |
| 379 | ptax19Amt | `Float` | Parallel Total tax19 amount extension to the existing ptax amounts. |
| 380 | ptax2Amt | `Float` | Parallel Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 381 | ptax20Amt | `Float` | Parallel Total tax20 amount extension to the existing ptax amounts. |
| 382 | ptax3Amt | `Float` | Parallel Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 383 | ptax4Amt | `Float` | Parallel Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 384 | ptax5Amt | `Float` | Parallel Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 385 | ptax6Amt | `Float` | Parallel Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 386 | ptax7Amt | `Float` | Parallel Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 387 | ptax8Amt | `Float` | Parallel Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 388 | ptax9Amt | `Float` | Parallel Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 389 | ptotNonrevNonTaxable | `Float` | Parallel total non revenue amount that is not taxable. |
| 390 | ptotNonrevTaxable | `Float` | Parallel total non revenue amount that is taxable. |
| 391 | ptotRevNonTaxable | `Float` | Parallel total revenue amount that is not taxable. |
| 392 | ptotRevTaxable | `Float` | Parallel total revenue amount that is taxable. |
| 393 | realPerpetualAmount | `Float` | Real perpetual amount at the time of generating the bill. |
| 394 | reservationNameId | `Float` | Resv Name ID |
| 395 | resortCity | `String` | City of the hotel at the time of bill generation. |
| 396 | resortCountry | `String` | Country of the hotel at the time of bill generation. |
| 397 | resortFullAddress | `String` | Property Full Address |
| 398 | resortZipcodeCode | `String` | Zipcode of the hotel at the time of bill generation. |
| 399 | revisionNo | `Float` | Revision Number |
| 400 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 401 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 402 | roomNumber | `String` | Room Number |
| 403 | seqNumber | `Float` | Sequence No |
| 404 | signature | `String` | Signature |
| 405 | signatureKeyVersion | `String` | Signature Key Version |
| 406 | softwareVersion | `String` | OPERA software version at the time of bill generation. |
| 407 | tax1RateType | `String` | Tax Rate Type 1 of the bill for which Tax Code 1 is attached as one of the taxes. |
| 408 | tax2RateType | `String` | Tax Rate Type 2 of the bill for which Tax Code 2 is attached as one of the taxes. |
| 409 | taxAmount1 | `Float` | Tax Amount 1 |
| 410 | taxAmount10 | `Float` | Tax Amount 10 |
| 411 | taxAmount11 | `Float` | Tax Amount 11 |
| 412 | taxAmount12 | `Float` | Tax Amount 12 |
| 413 | taxAmount13 | `Float` | Tax Amount 13 |
| 414 | taxAmount14 | `Float` | Tax Amount 14 |
| 415 | taxAmount15 | `Float` | Tax Amount 15 |
| 416 | taxAmount16 | `Float` | Tax Amount 16 |
| 417 | taxAmount17 | `Float` | Tax Amount 17 |
| 418 | taxAmount18 | `Float` | Tax Amount 18 |
| 419 | taxAmount19 | `Float` | Tax Amount 19 |
| 420 | taxAmount2 | `Float` | Tax Amount 2 |
| 421 | taxAmount20 | `Float` | Tax Amount 20 |
| 422 | taxAmount3 | `Float` | Tax Amount 3 |
| 423 | taxAmount4 | `Float` | Tax Amount 4 |
| 424 | taxAmount5 | `Float` | Tax Amount 5 |
| 425 | taxAmount6 | `Float` | Tax Amount 6 |
| 426 | taxAmount7 | `Float` | Tax Amount 7 |
| 427 | taxAmount8 | `Float` | Tax Amount 8 |
| 428 | taxAmount9 | `Float` | Tax Amount 9 |
| 429 | taxCode1 | `String` | Tax Code 1 |
| 430 | taxCode10 | `String` | Tax Code 10 |
| 431 | taxCode11 | `String` | Tax Code 11 |
| 432 | taxCode12 | `String` | Tax Code 12 |
| 433 | taxCode13 | `String` | Tax Code 13 |
| 434 | taxCode14 | `String` | Tax Code 14 |
| 435 | taxCode15 | `String` | Tax Code 15 |
| 436 | taxCode16 | `String` | Tax Code 16 |
| 437 | taxCode17 | `String` | Tax Code 17 |
| 438 | taxCode18 | `String` | Tax Code 18 |
| 439 | taxCode19 | `String` | Tax Code 19 |
| 440 | taxCode2 | `String` | Tax Code 2 |
| 441 | taxCode20 | `String` | Tax Code 20 |
| 442 | taxCode3 | `String` | Tax Code 3 |
| 443 | taxCode4 | `String` | Tax Code 4 |
| 444 | taxCode5 | `String` | Tax Code 5 |
| 445 | taxCode6 | `String` | Tax Code 6 |
| 446 | taxCode7 | `String` | Tax Code 7 |
| 447 | taxCode8 | `String` | Tax Code 8 |
| 448 | taxCode9 | `String` | Tax Code 9 |
| 449 | taxCodeDesc1 | `String` | Tax Code Description 1 |
| 450 | taxCodeDesc10 | `String` | Tax Code Description 10 |
| 451 | taxCodeDesc11 | `String` | Tax Code Description 11 |
| 452 | taxCodeDesc12 | `String` | Tax Code Description 12 |
| 453 | taxCodeDesc13 | `String` | Tax Code Description 13 |
| 454 | taxCodeDesc14 | `String` | Tax Code Description 14 |
| 455 | taxCodeDesc15 | `String` | Tax Code Description 15 |
| 456 | taxCodeDesc16 | `String` | Tax Code Description 16 |
| 457 | taxCodeDesc17 | `String` | Tax Code Description 17 |
| 458 | taxCodeDesc18 | `String` | Tax Code Description 18 |
| 459 | taxCodeDesc19 | `String` | Tax Code Description 19 |
| 460 | taxCodeDesc2 | `String` | Tax Code Description 2 |
| 461 | taxCodeDesc20 | `String` | Tax Code Description 20 |
| 462 | taxCodeDesc3 | `String` | Tax Code Description 3 |
| 463 | taxCodeDesc4 | `String` | Tax Code Description 4 |
| 464 | taxCodeDesc5 | `String` | Tax Code Description 5 |
| 465 | taxCodeDesc6 | `String` | Tax Code Description 6 |
| 466 | taxCodeDesc7 | `String` | Tax Code Description 7 |
| 467 | taxCodeDesc8 | `String` | Tax Code Description 8 |
| 468 | taxCodeDesc9 | `String` | Tax Code Description 9 |
| 469 | taxId | `String` | Tax ID |
| 470 | taxRate1 | `Float` | Tax Rate 1 amount of the bill for which Tax Code 1 is attached as one of the taxes. |
| 471 | taxRate10 | `Float` | Tax Rate 10 amount of the bill for which Tax Code 10  is attached as one of the taxes. |
| 472 | taxRate11 | `Float` | Tax Rate 11 amount of the bill for which Tax Code 11  is attached as one of the taxes. |
| 473 | taxRate12 | `Float` | Tax Rate 12 amount of the bill for which Tax Code 12 is attached as one of the taxes. |
| 474 | taxRate13 | `Float` | Tax Rate 13 amount of the bill for which Tax Code 13 is attached as one of the taxes. |
| 475 | taxRate14 | `Float` | Tax Rate 14 amount of the bill for which Tax Code 14 is attached as one of the taxes. |
| 476 | taxRate15 | `Float` | Tax Rate 15 amount of the bill for which Tax Code 15 is attached as one of the taxes. |
| 477 | taxRate16 | `Float` | Tax Rate 16 amount of the bill for which Tax Code 16 is attached as one of the taxes. |
| 478 | taxRate17 | `Float` | Tax Rate 17 amount of the bill for which Tax Code 17 is attached as one of the taxes. |
| 479 | taxRate18 | `Float` | Tax Rate 18 amount of the bill for which Tax Code 18 is attached as one of the taxes. |
| 480 | taxRate19 | `Float` | Tax Rate 19 amount of the bill for which Tax Code 19 is attached as one of the taxes. |
| 481 | taxRate2 | `Float` | Tax Rate 2 amount of the bill for which Tax Code 2 is attached as one of the taxes. |
| 482 | taxRate20 | `Float` | Tax Rate 20 amount of the bill for which Tax Code 20 is attached as one of the taxes. |
| 483 | taxRate3 | `Float` | Tax Rate 3 amount of the bill for which Tax Code 3 is attached as one of the taxes. |
| 484 | taxRate4 | `Float` | Tax Rate 4 amount of the bill for which Tax Code 4 is attached as one of the taxes. |
| 485 | taxRate5 | `Float` | Tax Rate 5 amount of the bill for which Tax Code 5 is attached as one of the taxes. |
| 486 | taxRate6 | `Float` | Tax Rate 6 amount of the bill for which Tax Code 6 is attached as one of the taxes. |
| 487 | taxRate7 | `Float` | Tax Rate 7 amount of the bill for which Tax Code 7 is attached as one of the taxes. |
| 488 | taxRate8 | `Float` | Tax Rate 8 amount of the bill for which Tax Code 8 is attached as one of the taxes. |
| 489 | taxRate9 | `Float` | Tax Rate 9 amount of the bill for which Tax Code 9 is attached as one of the taxes. |
| 490 | tax10RateType | `String` | Tax Rate Type 10 of the bill for which Tax Code 10 is attached as one of the taxes. |
| 491 | tax11RateType | `String` | Tax Rate Type 11 of the bill for which Tax Code 11 is attached as one of the taxes. |
| 492 | tax12RateType | `String` | Tax Rate Type 12 of the bill for which Tax Code 12 is attached as one of the taxes. |
| 493 | tax13RateType | `String` | Tax Rate Type 13 of the bill for which Tax Code 13 is attached as one of the taxes. |
| 494 | tax14RateType | `String` | Tax Rate Type 14 of the bill for which Tax Code 14 is attached as one of the taxes. |
| 495 | tax15RateType | `String` | Tax Rate Type 15 of the bill for which Tax Code 15 is attached as one of the taxes. |
| 496 | tax16RateType | `String` | Tax Rate Type 16 of the bill for which Tax Code 16 is attached as one of the taxes. |
| 497 | tax17RateType | `String` | Tax Rate Type 17 of the bill for which Tax Code 17 is attached as one of the taxes. |
| 498 | tax18RateType | `String` | Tax Rate Type 18 of the bill for which Tax Code 18 is attached as one of the taxes. |
| 499 | tax19RateType | `String` | Tax Rate Type 19 of the bill for which Tax Code 19 is attached as one of the taxes. |
| 500 | tax20RateType | `String` | Tax Rate Type 20 of the bill for which Tax Code 20 is attached as one of the taxes. |
| 501 | tax3RateType | `String` | Tax Rate Type 3 of the bill for which Tax Code 3 is attached as one of the taxes. |
| 502 | tax4RateType | `String` | Tax Rate Type 4 of the bill for which Tax Code 4 is attached as one of the taxes. |
| 503 | tax5RateType | `String` | Tax Rate Type 5 of the bill for which Tax Code 5 is attached as one of the taxes. |
| 504 | tax6RateType | `String` | Tax Rate Type 6 of the bill for which Tax Code 6 is attached as one of the taxes. |
| 505 | tax7RateType | `String` | Tax Rate Type 7 of the bill for which Tax Code 7 is attached as one of the taxes. |
| 506 | tax8RateType | `String` | Tax Rate Type 8 of the bill for which Tax Code 8 is attached as one of the taxes. |
| 507 | tax9RateType | `String` | Tax Rate Type 9 of the bill for which Tax Code 9 is attached as one of the taxes. |
| 508 | terminal | `String` | Terminal |
| 509 | totalGrossAmount | `Float` | Total Gross Amount |
| 510 | totalNetAmount | `Float` | Total Net Amount |
| 511 | totalNonRevenueNonTaxableAmount | `Float` | Total non revenue amount that is non taxable. |
| 512 | totalNonRevenueTaxableAmount | `Float` | Total non revenue amount that is not taxable. |
| 513 | totalNonTaxableAmount | `Float` | Total non taxable amount. |
| 514 | totalNonTaxableRevenue | `Float` | Total revenue amount that is non taxable. |
| 515 | totalPaidOuts | `Float` | Total paid outs. |
| 516 | totalTax | `Float` | Total Tax |
| 517 | totalTaxableRevenue | `Float` | Total revenue amount that is taxable. |
| 518 | transactLastSignatureHash | `String` | Last Signature for Transaction Totals. |
| 519 | transactSignatureHash | `String` | Signature hash for Transaction Totals. |
| 520 | transactSignatureKeyVersion | `String` | Signature key version for Transaction Totals. |
| 521 | transactionSignature | `String` | Transaction Signature Value. |
| 522 | trxServiceType | `String` | Transaction Service Type |
| 523 | uDFC01 | `String` | UDFC01 |
| 524 | uDFC02 | `String` | UDFC02 |
| 525 | uDFC03 | `String` | UDFC03 |
| 526 | uDFC04 | `String` | UDFC04 |
| 527 | uDFC05 | `String` | UDFC05 |
| 528 | uDFC06 | `String` | UDFC06 |
| 529 | uDFC07 | `String` | UDFC07 |
| 530 | uDFC08 | `String` | UDFC08 |
| 531 | uDFC09 | `String` | UDFC09 |
| 532 | uDFC10 | `String` | UDFC10 |
| 533 | uDFC11 | `String` | UDFC11 |
| 534 | uDFC12 | `String` | UDFC12 |
| 535 | uDFC13 | `String` | UDFC13 |
| 536 | uDFC14 | `String` | UDFC14 |
| 537 | uDFC15 | `String` | UDFC15 |
| 538 | uDFC16 | `String` | UDFC16 |
| 539 | uDFC17 | `String` | UDFC17 |
| 540 | uDFC18 | `String` | UDFC18 |
| 541 | uDFC19 | `String` | UDFC19 |
| 542 | uDFC20 | `String` | UDFC20 |
| 543 | uDFC21 | `String` | UDFC21 |
| 544 | uDFC22 | `String` | UDFC22 |
| 545 | uDFC23 | `String` | UDFC23 |
| 546 | uDFC24 | `String` | UDFC24 |
| 547 | uDFC25 | `String` | UDFC25 |
| 548 | uDFC26 | `String` | UDFC26 |
| 549 | uDFC27 | `String` | UDFC27 |
| 550 | uDFC28 | `String` | UDFC28 |
| 551 | uDFC29 | `String` | UDFC29 |
| 552 | uDFC30 | `String` | UDFC30 |
| 553 | uDFC31 | `String` | UDFC31 |
| 554 | uDFC32 | `String` | UDFC32 |
| 555 | uDFC33 | `String` | UDFC33 |
| 556 | uDFC34 | `String` | UDFC34 |
| 557 | uDFC35 | `String` | UDFC35 |
| 558 | uDFC36 | `String` | UDFC36 |
| 559 | uDFC37 | `String` | UDFC37 |
| 560 | uDFC38 | `String` | UDFC38 |
| 561 | uDFC39 | `String` | UDFC39 |
| 562 | uDFC40 | `String` | UDFC40 |
| 563 | uDFD01 | `Date` | UDFD01 |
| 564 | uDFD02 | `Date` | UDFD02 |
| 565 | uDFD03 | `Date` | UDFD03 |
| 566 | uDFD04 | `Date` | UDFD04 |
| 567 | uDFD05 | `Date` | UDFD05 |
| 568 | uDFD06 | `Date` | UDFD06 |
| 569 | uDFD07 | `Date` | UDFD07 |
| 570 | uDFD08 | `Date` | UDFD08 |
| 571 | uDFD09 | `Date` | UDFD09 |
| 572 | uDFD10 | `Date` | UDFD10 |
| 573 | uDFD11 | `Date` | UDFD11 |
| 574 | uDFD12 | `Date` | UDFD12 |
| 575 | uDFD13 | `Date` | UDFD13 |
| 576 | uDFD14 | `Date` | UDFD14 |
| 577 | uDFD15 | `Date` | UDFD15 |
| 578 | uDFD16 | `Date` | UDFD16 |
| 579 | uDFD17 | `Date` | UDFD17 |
| 580 | uDFD18 | `Date` | UDFD18 |
| 581 | uDFD19 | `Date` | UDFD19 |
| 582 | uDFD20 | `Date` | UDFD20 |
| 583 | uDFN01 | `Float` | UDFN01 |
| 584 | uDFN02 | `Float` | UDFN02 |
| 585 | uDFN03 | `Float` | UDFN03 |
| 586 | uDFN04 | `Float` | UDFN04 |
| 587 | uDFN05 | `Float` | UDFN05 |
| 588 | uDFN06 | `Float` | UDFN06 |
| 589 | uDFN07 | `Float` | UDFN07 |
| 590 | uDFN08 | `Float` | UDFN08 |
| 591 | uDFN09 | `Float` | UDFN09 |
| 592 | uDFN10 | `Float` | UDFN10 |
| 593 | uDFN11 | `Float` | UDFN11 |
| 594 | uDFN12 | `Float` | UDFN12 |
| 595 | uDFN13 | `Float` | UDFN13 |
| 596 | uDFN14 | `Float` | UDFN14 |
| 597 | uDFN15 | `Float` | UDFN15 |
| 598 | uDFN16 | `Float` | UDFN16 |
| 599 | uDFN17 | `Float` | UDFN17 |
| 600 | uDFN18 | `Float` | UDFN18 |
| 601 | uDFN19 | `Float` | UDFN19 |
| 602 | uDFN20 | `Float` | UDFN20 |
| 603 | uDFN21 | `Float` | UDFN21 |
| 604 | uDFN22 | `Float` | UDFN22 |
| 605 | uDFN23 | `Float` | UDFN23 |
| 606 | uDFN24 | `Float` | UDFN24 |
| 607 | uDFN25 | `Float` | UDFN25 |
| 608 | uDFN26 | `Float` | UDFN26 |
| 609 | uDFN27 | `Float` | UDFN27 |
| 610 | uDFN28 | `Float` | UDFN28 |
| 611 | uDFN29 | `Float` | UDFN29 |
| 612 | uDFN30 | `Float` | UDFN30 |
| 613 | uDFN31 | `Float` | UDFN31 |
| 614 | uDFN32 | `Float` | UDFN32 |
| 615 | uDFN33 | `Float` | UDFN33 |
| 616 | uDFN34 | `Float` | UDFN34 |
| 617 | uDFN35 | `Float` | UDFN35 |
| 618 | uDFN36 | `Float` | UDFN36 |
| 619 | uDFN37 | `Float` | UDFN37 |
| 620 | uDFN38 | `Float` | UDFN38 |
| 621 | uDFN39 | `Float` | UDFN39 |
| 622 | uDFN40 | `Float` | UDFN40 |
| 623 | updTimestamp | `DateTime` | Timestamp to capture the exact order of updates. |
| 624 | updateDate | `DateTime` | Update Date |
| 625 | updateUser | `Float` | Update User |
| 626 | userID | `Float` | User ID |
| 627 | userName | `String` | The name of the user who created the record. |
| 628 | voidNumber | `Float` | Void Number |
| 629 | voidReason | `String` | This column will store the reason for voiding the folio. |
| 630 | workingDocId | `Float` | Working Doc ID |
| 631 | xnet1Amt | `Float` | Xnet1 Amount |
| 632 | xnet10Amt | `Float` | Xnet10 Amount |
| 633 | xnet11Amt | `Float` | Xnet11 Amount |
| 634 | xnet12Amt | `Float` | Xnet12 Amount |
| 635 | xnet13Amt | `Float` | Xnet13 Amount |
| 636 | xnet14Amt | `Float` | Xnet14 Amount |
| 637 | xnet15Amt | `Float` | Xnet15 Amount |
| 638 | xnet16Amt | `Float` | Xnet16 Amount |
| 639 | xnet17Amt | `Float` | Xnet17 Amount |
| 640 | xnet18Amt | `Float` | Xnet18 Amount |
| 641 | xnet19Amt | `Float` | Xnet19 Amount |
| 642 | xnet2Amt | `Float` | Xnet2 Amount |
| 643 | xnet20Amt | `Float` | Xnet20 Amount |
| 644 | xnet3Amt | `Float` | Xnet3 Amount |
| 645 | xnet4Amt | `Float` | Xnet4 Amount |
| 646 | xnet5Amt | `Float` | Xnet5 Amount |
| 647 | xnet6Amt | `Float` | Xnet6 Amount |
| 648 | xnet7Amt | `Float` | Xnet7 Amount |
| 649 | xnet8Amt | `Float` | Xnet8 Amount |
| 650 | xnet9Amt | `Float` | Xnet9 Amount |
| 651 | xtax1Amt | `Float` | Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 652 | xtax10Amt | `Float` | Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 653 | xtax11Amt | `Float` | Total tax11 amount extension to the existing xtax amounts. |
| 654 | xtax12Amt | `Float` | Total tax12 amount extension to the existing xtax amounts. |
| 655 | xtax13Amt | `Float` | Total tax13 amount extension to the existing xtax amounts. |
| 656 | xtax14Amt | `Float` | Total tax14 amount extension to the existing xtax amounts. |
| 657 | xtax15Amt | `Float` | Total tax15 amount extension to the existing xtax amounts. |
| 658 | xtax16Amt | `Float` | Total tax16 amount extension to the existing xtax amounts. |
| 659 | xtax17Amt | `Float` | Total tax17 amount extension to the existing xtax amounts. |
| 660 | xtax18Amt | `Float` | Total tax18 amount extension to the existing xtax amounts. |
| 661 | xtax19Amt | `Float` | Total tax19 amount extension to the existing xtax amounts. |
| 662 | xtax2Amt | `Float` | Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 663 | xtax20Amt | `Float` | Total tax20 amount extension to the existing xtax amounts. |
| 664 | xtax3Amt | `Float` | Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 665 | xtax4Amt | `Float` | Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 666 | xtax5Amt | `Float` | Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 667 | xtax6Amt | `Float` | Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 668 | xtax7Amt | `Float` | Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 669 | xtax8Amt | `Float` | Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 670 | xtax9Amt | `Float` | Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedFinancialUnifiedDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 3 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 4 | aRState | `String` | AR State |
| 5 | aRTransferDate | `Date` | AR Transfer Date |
| 6 | accountCode | `Float` | Account Code |
| 7 | accountNumber | `String` | Account Number |
| 8 | addressId | `Float` | Address ID |
| 9 | advanceBillReversedYN | `String` | Identifies if this Advance Bill has been reversed. |
| 10 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 11 | advancedGenerateYN | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 12 | advgenTtransCodeID | `String` | Advgen Ttrans Code ID |
| 13 | arrangementCode | `String` | Arrangement Code |
| 14 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 15 | articleId | `Float` | Article ID |
| 16 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 17 | attachedToUser | `String` | Application User Name |
| 18 | authEmployeeID | `Float` | Auth Employee ID |
| 19 | authorizer | `String` | Authorizer |
| 20 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 21 | autoSettleYn | `String` | Auto Settle Y/N |
| 22 | businessDate | `Date` | Business Date |
| 23 | cCApproval | `String` | CC Approval Code |
| 24 | cashierCode | `Float` | Cashier Code |
| 25 | cashierCredit | `Float` | Cashier Credit |
| 26 | cashierDebit | `Float` | Cashier Debit |
| 27 | cashierID | `Float` | Cashier ID |
| 28 | cashierName | `String` | Cashier Name |
| 29 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 30 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 31 | changesLogCheckIn | `String` | Changes Log Check In |
| 32 | changesLogCheckOut | `String` | Changes Log Check Out |
| 33 | changesLogCloseFolio | `String` | Changes Log Close Folio |
| 34 | changesLogReopenFolio | `String` | Changes Log Reopen Folio |
| 35 | changesLogUpdateReservation | `String` | Changes Log Update Reservation |
| 36 | checkNumber | `String` | Check Number |
| 37 | closureNumber | `Float` | Closure Number |
| 38 | comments | `String` | Comments |
| 39 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 40 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 41 | compTypeCode | `String` | Comp Type Code |
| 42 | compressedYn | `String` | Compressed Y/N |
| 43 | covers | `String` | Covers |
| 44 | creditCardId | `Float` | Credit Card ID |
| 45 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 46 | creditYN | `String` | Credit YN |
| 47 | currencyCode | `String` | Currency Code |
| 48 | currencyDescription | `String` | Currency Description |
| 49 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 50 | debitYN | `String` | Debit YN |
| 51 | decimals | `Float` | Decimals |
| 52 | deferredYn | `String` | Deferred Y/N |
| 53 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 54 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 55 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 56 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 57 | depositTransactionId | `String` | Deposit Transaction ID |
| 58 | displayYN | `String` | Display YN |
| 59 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 60 | exchangeDate | `Date` | Exchange Date |
| 61 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 62 | exchangeRate | `Float` | Exchange Rate |
| 63 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 64 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 65 | fiscalBillNo | `String` | Fiscal Bill Number |
| 66 | fixedChargesYN | `String` | Fixed Charges YN |
| 67 | folio | `Float` | Folio |
| 68 | folioNo | `Float` | Folio Number |
| 69 | folioType | `String` | Folio Type |
| 70 | folioView | `Float` | Folio View |
| 71 | foreignCurrencyCode | `String` | Foreign Currency Code |
| 72 | fromReservationId | `Float` | From Resv ID |
| 73 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 74 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 75 | genCashierId | `Float` | General Cashier Id. |
| 76 | generalCashierYN | `String` | Determines whether the cashier is a General cashier. |
| 77 | grossAmount | `Float` | Gross Amount |
| 78 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 79 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 80 | inHouseCredit | `Float` | In-House Credit |
| 81 | inHouseDebit | `Float` | In-House Debit |
| 82 | insertDate | `DateTime` | Insert Date |
| 83 | insertUser | `Float` | Insert User |
| 84 | insertUserName | `String` | The name of the user who created the record. |
| 85 | interfaceCashierYN | `String` | Decides whether the cashier number is used in interfaces or not. The interface cashiers cannot have numbers more than 999. |
| 86 | internalArticleid | `Float` | Articleid |
| 87 | internalWindowId | `Float` | Internal Window ID |
| 88 | internalYN | `String` | Internal YN |
| 89 | invoiceCloseDate | `Date` | Invoice Close Date |
| 90 | invoiceNumber | `Float` | Invoice Number |
| 91 | invoiceType | `String` | Invoice Type |
| 92 | linkTrxNumber | `Float` | Link Transaction No |
| 93 | marketCode | `String` | Market Code |
| 94 | marketDescription | `String` | Market Description |
| 95 | membershipID | `Float` | Membership ID |
| 96 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 97 | nameTaxType | `String` | Name Tax Type |
| 98 | netAmount | `Float` | Net Amount |
| 99 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 100 | numberDialed | `String` | Number Dialed. |
| 101 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 102 | originalARLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 103 | originalBillNumber | `Float` | Stores original bill number after void. |
| 104 | originalFolioNumber | `String` | Stores original folio type after void. |
| 105 | originalReservationNameId | `Float` | Original Resv Name ID |
| 106 | originalRoom | `String` | Original Room |
| 107 | package | `String` | Package |
| 108 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 109 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 110 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 111 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 112 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 113 | passerByName | `String` | Passerby Name. |
| 114 | payeeNameID | `Float` | Name Id to which it should be routed. |
| 115 | payeeResvNameID | `Float` | Payee Resv Name ID |
| 116 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 117 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 118 | paymentType | `String` | Payment Type |
| 119 | paymentsReference | `String` | Payments-Reference |
| 120 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 121 | postedAmountInTransactionCurrency | `Float` | Posted Amount in Transaction Currency |
| 122 | postingDate | `DateTime` | Posting Date |
| 123 | postingRhythm | `String` | Posting Rhythm |
| 124 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 125 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 126 | postitNo | `Float` | Postit Number |
| 127 | postitYn | `String` | Postit Y/N |
| 128 | pricePerUnit | `Float` | Price Per Unit |
| 129 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 130 | profileID | `Float` | Profile ID |
| 131 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 132 | proformaYN | `String` | Proforma Y/N |
| 133 | property | `String` | Property |
| 134 | quantity | `Float` | Quantity |
| 135 | queueName | `String` | Queue Name |
| 136 | rateCode | `String` | Rate Code |
| 137 | receiptNumber | `Float` | Receipt Number |
| 138 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 139 | repTransactionCode | `String` | Reporting Trx Code |
| 140 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 141 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 142 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 143 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 144 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 145 | reservationNameID | `Float` | Reservation Name ID |
| 146 | revenueAmount | `Float` | Revenue Amount. |
| 147 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 148 | roomClass | `String` | Room Class |
| 149 | roomNts | `Float` | Room Nts |
| 150 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 151 | roomNumber | `String` | Room Number |
| 152 | roundFactorYn | `String` | Round Factor Y/N |
| 153 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 154 | routedYn | `String` | Indicates if the transaction has been routed. |
| 155 | routingCode | `String` | Routing Code |
| 156 | routingCodeDescription | `String` | Routing Code Description |
| 157 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 158 | routingIinstructionID | `Float` | Routing Iinstruction ID |
| 159 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 160 | routingType | `String` | To specify whether it is a package routing or not |
| 161 | settlementFlag | `String` | Settlement Flag |
| 162 | sourceCode | `String` | Source Code |
| 163 | sourceDescription | `String` | Source Description |
| 164 | supplement | `String` | Supplement |
| 165 | tRXCode | `String` | Transaction Code |
| 166 | targetResort | `String` | Target Property |
| 167 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 168 | taxElements | `String` | Tax Elements |
| 169 | taxGeneratedYN | `String` | Tax Generated YN |
| 170 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 171 | tcGroup | `String` | Transaction Code Group |
| 172 | tcSubgroup | `String` | Transaction Code Subgroup |
| 173 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 174 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 175 | thresholdEntityType | `String` | Threshold Entity Type |
| 176 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 177 | toReservationNameId | `Float` | To Resv Name ID |
| 178 | tranActionId | `Float` | Tran Action ID |
| 179 | transCodeArrangementID | `Float` | Trans Code Arrangement ID |
| 180 | transactionActivityDate | `Date` | Transaction Activity Date |
| 181 | transactionCodeDescription | `String` | Transaction Code Description |
| 182 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 183 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 184 | transactionDate | `Date` | Transaction Date |
| 185 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 186 | transactionPostingDate | `Date` | Transaction Posting Date |
| 187 | transactionPostingTime | `String` | Time transaction was posted. |
| 188 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 189 | transactionType | `String` | Transaction Type |
| 190 | transactionFromAccount | `Float` | Transaction from Account |
| 191 | transactionToAccount | `Float` | Transaction to Account |
| 192 | transferFromAccountID | `Float` | Transfer from Account ID |
| 193 | transferToAccountID | `Float` | Transfer to Account ID |
| 194 | trxNo | `Float` | Trx Number |
| 195 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 196 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 197 | trxNumberHeader | `Float` | Transaction No Header |
| 198 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 199 | trxServiceType | `String` | Transaction Service Type |
| 200 | updateDate | `DateTime` | Update Date |
| 201 | updateUser | `Float` | Update User |
| 202 | vatAmount | `Float` | Tax Amount for Commission. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedPropertyPropertyDetailsType

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

### BookingReservationExtendedRoomDetailsType

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

### BookingReservationExtendedFixedChargesDetailsType

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

### BookingReservationExtendedQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| reservationunifiedDetailsResvActualCheckInTime | `StringInput` | Actual Check In Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvActualCheckOutTime | `StringInput` | Actual Check Out Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvActualCheckOutDate | `DateInput` | Actual Check-Out Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvAddresseeNameId | `FloatInput` | Addressee Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsAgentNameId | `FloatInput` | Agent Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvAllotmentid | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvTruncBeginDate | `DateTimeInput` | Arrival Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBillingContactId | `FloatInput` | Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsAllotmentCode | `StringInput` | Block Code |
| reservationunifiedDetailsResvAllotmentHeaderId | `StringInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsOwnerCode | `StringInput` | Block Owner Code |
| reservationunifiedDetailsResvBonusCheckId | `FloatInput` | Bonus Check ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBusinessDateCreated | `DateInput` | Business Date Created<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCancellationDate | `DateTimeInput` | Cancellation Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCancellationNo | `StringInput` | Cancellation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsCompanyNameId | `FloatInput` | Company Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvConfirmationNo | `StringInput` | Shared Confirmation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsContactNameId | `FloatInput` | Contact Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsInsertDate | `DateInput` | Created Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCustomReference | `StringInput` | Custom Reference Number |
| reservationunifiedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationunifiedDetailsResvTruncEndDate | `DateInput` | Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsEndDate | `DateInput` | End Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEndbusinessdate | `DateInput` | Endbusinessdate<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEventId | `FloatInput` | Event ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBlocksExtAllotmentId | `StringInput` | Ext Allotment ID |
| reservationunifiedDetailsResvFolioCloseDate | `DateInput` | Date the folio was changed to closed.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationunifiedDetailsResvGuestprofileid | `FloatInput` | Guestprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvInsertActionInstanceId | `FloatInput` | Insert Action Instance ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsInsertUser | `FloatInput` | Insert User<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBlocksInterfaceId | `StringInput` | This is the Interface_id of the System which sent/Received Allotment |
| reservationunifiedDetailsResvAwardMembershipId | `FloatInput` | Award Membership ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEndDate | `DateInput` | Linked Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSuperBlockId | `FloatInput` | Parent Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSuperBlockResort | `StringInput` | Parent Resort |
| reservationunifiedDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvNameUsageType | `StringInput` | Name Usage Type |
| reservationunifiedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationunifiedDetailsResvOriginalEndDate | `DateInput` | Original End Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsOwner | `FloatInput` | Owner<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvParentResvNameId | `FloatInput` | Parent Resv Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvParentreservationid | `FloatInput` | Parentreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvQuoteId | `StringInput` | Quote ID provided by external system.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvResvContactId | `FloatInput` | Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvNameId | `FloatInput` | Reservation Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvResvStatus | `StringInput` | Reservation Status |
| reservationunifiedDetailsResvGuaranteeCode | `StringInput` | Reservation Type |
| reservationunifiedDetailsResort | `StringInput` | Property<br>`@conditionalInputPair(pair: 1)` |
| reservationunifiedDetailsResvResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationunifiedDetailsResvResvcontactprofileid | `FloatInput` | Resvcontactprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRhBillingContactId | `FloatInput` | Rh Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRhResvContactId | `FloatInput` | Rh Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRoomcategoryid | `StringInput` | Roomcategoryid |
| reservationunifiedDetailsResvSchedulecheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationunifiedDetailsResvSguestFirstname | `StringInput` | Sguest First Name |
| reservationunifiedDetailsResvSguestName | `StringInput` | Sguest Name |
| reservationunifiedDetailsResvNameNameId | `FloatInput` | Shared Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvReservationStatus | `StringInput` | Shared Reservation Status |
| reservationunifiedDetailsShoulderEndDate | `DateInput` | Shoulder End<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsShoulderBeginDate | `DateInput` | Shoulder Start<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSourceNameId | `FloatInput` | Source Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvSplitfromreservationid | `FloatInput` | Splitfromreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBeginDate | `DateInput` | Start Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsUpdateDate | `DateInput` | Updated Date<br>`@conditionalInputPair(pair: 2)` |
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
| profileaccountssourceDetailsProfileId | `FloatInput` | Account ID |
| profileaccountssourceDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountssourceDetailsChainCode | `StringInput` | Chain Code |
| profileaccountssourceDetailsCompany | `StringInput` | Company |
| profileaccountssourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountssourceDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountssourceDetailsNameCode | `StringInput` | IATA Number |
| profileaccountssourceDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountssourceDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountssourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountssourceDetailsLast | `StringInput` | Last |
| profileaccountssourceDetailsNameId | `FloatInput` | Name ID |
| profileaccountssourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountssourceDetailsProfileType | `StringInput` | Profile Type |
| profileaccountssourceDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountssourceDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountssourceDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountssourceDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountssourceDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountssourceDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountssourceDetailsUpdateDate | `DateTimeInput` | Update Date |
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
| externalreferencesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| externalreferencesDetailsExternalReference | `StringInput` | External Reference Number |
| externalreferencesDetailsExternalReferenceType | `StringInput` | Type of external reference depending from what external system the number was passed. |
| externalreferencesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| externalreferencesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| externalreferencesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| externalreferencesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| externalreferencesDetailsResvNameId | `FloatInput` | Resv Name ID |
| externalreferencesDetailsUpperExternalReference | `StringInput` | External reference stored in upper case. |
| resvmembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvpaymentmethodsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| resvpaymentmethodsDetailsCreditCardId | `FloatInput` | Credit Card ID |
| resvpaymentmethodsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvpaymentmethodsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvpaymentmethodsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvpaymentmethodsDetailsFolioView | `FloatInput` | Payment Window |
| resvpaymentmethodsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvpaymentmethodsDetailsResvNameId | `FloatInput` | Resv Name ID |
| profileaccountsDetailsProfileId | `FloatInput` | Account ID |
| profileaccountsDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountsDetailsChainCode | `StringInput` | Chain Code |
| profileaccountsDetailsCompany | `StringInput` | Company |
| profileaccountsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountsDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountsDetailsNameCode | `StringInput` | IATA Number |
| profileaccountsDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| profileaccountsDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountsDetailsLast | `StringInput` | Last |
| profileaccountsDetailsNameId | `FloatInput` | Name ID |
| profileaccountsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountsDetailsProfileType | `StringInput` | Profile Type |
| profileaccountsDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountsDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountsDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountsDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountsDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountsDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountsDetailsUpdateDate | `DateTimeInput` | Update Date |
| resvdepositscheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| resvdepositscheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdepositscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdepositscheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resvdepositscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdepositscheduleDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvdepositscheduleDetailsResvDepositScheduleId | `FloatInput` | Resv Deposit Schedule ID |
| ratecodedetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecodedetailsDetailsEndDate | `DateInput` | End Date |
| ratecodedetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecodedetailsDetailsLinkRateSetId | `FloatInput` | Rate set id of the base rates rate set. |
| ratecodedetailsDetailsMarketCode | `StringInput` | Market Code |
| ratecodedetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecodedetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| ratecodedetailsDetailsRateCode | `StringInput` | Rate Code |
| ratecodedetailsDetailsRateSetId | `FloatInput` | Rate Set ID |
| ratecodedetailsDetailsSeasonCode | `StringInput` | Season Code |
| ratecodedetailsDetailsSourceCode | `StringInput` | Source Code |
| ratecodedetailsDetailsBeginDate | `DateInput` | Start Date |
| ratecodedetailsDetailsTierId | `FloatInput` | Tier ID for the Rate Detail. |
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
| foliotaxDetailsAccountCode | `FloatInput` | Account Code |
| foliotaxDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| foliotaxDetailsAssociatedBillNo | `StringInput` | Associated Bill Number |
| foliotaxDetailsAssociatedSeqNo | `FloatInput` | Self referencing sequence number to gather information for other operations. |
| foliotaxDetailsBillGenerationDate | `DateInput` | Bill Generation Date |
| foliotaxDetailsBillNo | `FloatInput` | Bill Number |
| foliotaxDetailsBillPaymentTrxNo | `FloatInput` | Bill Payment Transaction No |
| foliotaxDetailsBillPrefix | `StringInput` | Bill Prefix |
| foliotaxDetailsBillSeqNo | `FloatInput` | Bill Sequence Number |
| foliotaxDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| foliotaxDetailsClTrxNo | `FloatInput` | Internal number given to the direct bill payment in financial_transactions. |
| foliotaxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foliotaxDetailsFolioAttachmentLinkId | `FloatInput` | Folio Attachment Link ID |
| foliotaxDetailsFolioNo | `FloatInput` | Folio Number |
| foliotaxDetailsFolioType | `StringInput` | Folio Type |
| foliotaxDetailsInsTimestamp | `DateTimeInput` | Timestamp to capture the exact order of inserts. |
| foliotaxDetailsInsertDate | `DateTimeInput` | Insert Date |
| foliotaxDetailsInvoiceNo | `FloatInput` | Invoice Number |
| foliotaxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foliotaxDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| foliotaxDetailsNameId | `FloatInput` | Name ID |
| foliotaxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foliotaxDetailsPayeeName | `StringInput` | Payee Name used for signature generation. |
| foliotaxDetailsPostitNo | `FloatInput` | Postit Sequence Number |
| foliotaxDetailsResort | `StringInput` | Code to uniquely identify the Property |
| foliotaxDetailsResvNameId | `FloatInput` | Resv Name ID |
| foliotaxDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| foliotaxDetailsSeqNo | `FloatInput` | Sequence No |
| financialunifiedDetailsFtArLedCredit | `FloatInput` | AR Ledger Credit |
| financialunifiedDetailsFtArLedDebit | `FloatInput` | AR Ledger Debit |
| financialunifiedDetailsFtArState | `StringInput` | AR State |
| financialunifiedDetailsFtArNumber | `FloatInput` | Account Code |
| financialunifiedDetailsFtArticleId | `FloatInput` | Article ID |
| financialunifiedDetailsFtBusinessDate | `DateInput` | Business Date |
| financialunifiedDetailsFtCashierId | `FloatInput` | Cashier ID |
| financialunifiedDetailsFtChequeNumber | `StringInput` | Check Number |
| financialunifiedDetailsFtClosureNo | `FloatInput` | Closure Number |
| financialunifiedDetailsFtCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialunifiedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialunifiedDetailsFtFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialunifiedDetailsFtBillNo | `FloatInput` | Folio Number |
| financialunifiedDetailsFtFolioView | `FloatInput` | Folio View |
| financialunifiedDetailsFromResvId | `FloatInput` | From Resv ID |
| financialunifiedDetailsFtFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialunifiedDetailsFtGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialunifiedDetailsFtGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialunifiedDetailsFtInsertDate | `DateTimeInput` | Insert Date |
| financialunifiedDetailsFtFolioNo | `FloatInput` | Internal Window ID |
| financialunifiedDetailsFtInvoiceNo | `FloatInput` | Invoice Number |
| financialunifiedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialunifiedDetailsFtOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialunifiedDetailsFtOriginalRoom | `StringInput` | Original Room |
| financialunifiedDetailsFtProduct | `StringInput` | Package |
| financialunifiedDetailsFtPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialunifiedDetailsFtPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialunifiedDetailsFtPostitNo | `FloatInput` | Postit Number |
| financialunifiedDetailsFtProfileid | `FloatInput` | Profile ID |
| financialunifiedDetailsResort | `StringInput` | Property |
| financialunifiedDetailsFtRateCode | `StringInput` | Rate Code |
| financialunifiedDetailsFtRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialunifiedDetailsResvNameId | `FloatInput` | Reservation Name ID |
| financialunifiedDetailsFtRoom | `StringInput` | Room Number |
| financialunifiedDetailsFtRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialunifiedDetailsFtRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialunifiedDetailsFtTaxElements | `StringInput` | Tax Elements |
| financialunifiedDetailsFtTcGroup | `StringInput` | Transaction Code Group |
| financialunifiedDetailsFtTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialunifiedDetailsFtTranActionId | `FloatInput` | Tran Action ID |
| financialunifiedDetailsFtTrxDate | `DateInput` | Transaction Date |
| financialunifiedDetailsFtTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialunifiedDetailsFtTrxNo | `FloatInput` | Trx Number |
| financialunifiedDetailsFtTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialunifiedDetailsFtTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialunifiedDetailsFtTrxNoHeader | `FloatInput` | Transaction No Header |
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
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
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
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- reservationunifiedDetailsResort

**`conditionalInputPair(pair: 2)`**
- reservationunifiedDetailsResvActualCheckInTime
- reservationunifiedDetailsResvActualCheckOutTime
- reservationunifiedDetailsResvActualCheckOutDate
- reservationunifiedDetailsResvAddresseeNameId
- reservationunifiedDetailsAgentNameId
- reservationunifiedDetailsResvAllotmentid
- reservationunifiedDetailsResvTruncBeginDate
- reservationunifiedDetailsResvBillingContactId
- reservationunifiedDetailsResvBillingcontactprofileid
- reservationunifiedDetailsResvAllotmentHeaderId
- reservationunifiedDetailsResvBonusCheckId
- reservationunifiedDetailsResvBusinessDateCreated
- reservationunifiedDetailsResvCancellationDate
- reservationunifiedDetailsResvCancellationNo
- reservationunifiedDetailsCompanyNameId
- reservationunifiedDetailsResvConfirmationNo
- reservationunifiedDetailsContactNameId
- reservationunifiedDetailsInsertDate
- reservationunifiedDetailsResvTruncEndDate
- reservationunifiedDetailsEndDate
- reservationunifiedDetailsResvEndbusinessdate
- reservationunifiedDetailsResvEventId
- reservationunifiedDetailsResvFolioCloseDate
- reservationunifiedDetailsResvGuestprofileid
- reservationunifiedDetailsResvInsertActionInstanceId
- reservationunifiedDetailsInsertUser
- reservationunifiedDetailsResvAwardMembershipId
- reservationunifiedDetailsResvEndDate
- reservationunifiedDetailsSuperBlockId
- reservationunifiedDetailsMasterNameId
- reservationunifiedDetailsResvOriginalEndDate
- reservationunifiedDetailsOwner
- reservationunifiedDetailsResvParentResvNameId
- reservationunifiedDetailsResvParentreservationid
- reservationunifiedDetailsResvQuoteId
- reservationunifiedDetailsResvResvContactId
- reservationunifiedDetailsResvNameId
- reservationunifiedDetailsResvResvcontactprofileid
- reservationunifiedDetailsResvRhBillingContactId
- reservationunifiedDetailsResvRhResvContactId
- reservationunifiedDetailsResvNameNameId
- reservationunifiedDetailsShoulderEndDate
- reservationunifiedDetailsShoulderBeginDate
- reservationunifiedDetailsSourceNameId
- reservationunifiedDetailsResvSplitFromResvNameId
- reservationunifiedDetailsResvSplitfromreservationid
- reservationunifiedDetailsBeginDate
- reservationunifiedDetailsResvTruncActualCheckOutDate
- reservationunifiedDetailsResvUniCardId
- reservationunifiedDetailsUpdateDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query bookingReservationExtended($input: BookingReservationExtendedQueryArgumentsType!) {
  bookingReservationExtended(input: $input) @stream {
    reservationUnifiedDetails {
      aSBProratedYn
      actionId
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckOutDate
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      agentNameId
      allAliases
      allBlockOwners
      allCateringOwners
      allCompanyContacts
      allRateCodes
      allRoomOwners
      allRoomTypes
      allSourceContacts
      allTravelAgentContacts
      allotmentOrigin
      allotmentRecordType
      allotmentType
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
      authorizedBy
      authorizerId
      autoCheckinYn
      autoSettleDays
      autoSettleYN
      averageRate
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
      baseRateCode
      baseRateCurrencyCode
      baseratecurrencyid
      beginDatetime
      beginSystemDateTime
      billingContactId
      billingcontactprofileid
      blockAlias
      blockCode
      blockDescription
      blockDmlSeqNumber
      blockEndbusinessdate
      blockExchangePostingType
      blockExchangeRate
      blockExternalReference
      blockID
      blockOwnerCode
      blockResort
      blockStatus
      blockStatusDescription
      blocksExternalReference
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      centralApprovalAmount
      changesLogCheckIn
      changesLogCheckOut
      changesLogCloseFolio
      changesLogReopenFolio
      changesLogUpdateReservation
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      commissionCode
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compTypeCode
      companyAll
      companyID
      companyNameId
      compreasonid
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactNameId
      contactProfileID
      createdBy
      createdDate
      creditCardId
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      dateOpenedForPickup
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      directBillVerifyResponse
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      downloadDate
      downloadResort
      downloadSrep
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endDate
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      expectedTimeOfReturnETR
      exportCheckinresId
      extBookingID
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externallyLocked
      extraBeds
      faxId
      faxYn
      financiallyResponsibleYn
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      gUID
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
      inactiveDate
      insertActionInstanceId
      insertUser
      interfaceID
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      keyValidUntil
      laptopChange
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastSettleDate
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      localBaseRateAmount
      mailYn
      mainmarket
      manualCheckoutStatus
      marketCode
      marketDescription
      marketid
      masterBlockID
      masterBlockProperty
      masterNameId
      membershipId
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCodeDescription
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      owner
      ownerFfFlag
      ownerResort
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      payment
      paymentDescription
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
      primaryShare
      printRateYN
      profileId
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      quoteId
      rateAmount
      rateCode
      rateableValue
      ratecodeid
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reserveInventoryYN
      resort
      resortBooked
      resortChargeNumber
      restrictionOverride
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rivMarketSegment
      room
      roomCategory
      roomClass
      roomInstructions
      roomServiceTime
      roomcategoryid
      roomid
      roomsPerDay
      salesId
      sbegindate
      scheduleCheckoutYn
      senddate
      serviceCharge
      sguestFirstName
      sguestName
      shareId
      shareSeqNumber
      shareOfRateAmount
      sharedProfileID
      sharedReservationStatus
      shoulderEnd
      shoulderStart
      sourceCodeDescription
      sourceContactAll
      sourceNameId
      sourceid
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      startDate
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      superSearchIndexText
      taxAmount
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxtypeid
      tiad
      traceCode
      transactionid
      travelAgentAll
      travelAgentID
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
      uniCardId
      updateUser
      updatedBy
      updatedDate
      uploadDate
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      walkInYN
      yieldableYn
      ymCode
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
    profileAccountsSourceDetails {
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
    profileAccountsDetails {
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
      rNAInsertDate
      rNAUpdateDate
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
    rateCodeDetailsDetails {
      addAfterRounding
      adultCharge
      adultsThreshold
      adultsThresholdCharge
      advBaseAmount
      advBaseFltPct
      advDailyBaseRateCode
      advanceBaseCompareYN
      ageRangeForBucket1
      ageRangeForBucket2
      ageRangeForBucket3
      amount1Type
      amount2Type
      amount3Type
      amount4Type
      amount5Type
      amountFor1Person
      amountFor2Persons
      amountFor3Persons
      amountFor4Persons
      amountFor5Persons
      barAmount
      barFltPct
      barRounding
      barYn
      cAdultCharge
      cAdultsThresholdCharge
      cAdvanceBaseAmount
      cAmount1
      cAmount2
      cAmount3
      cAmount4
      cAmount5
      cBarAmount
      cChildCharge1
      cChildCharge2
      cChildCharge3
      cChildOwnCharge1
      cChildOwnCharge2
      cChildOwnCharge3
      cChildOwnCharge4
      cChildrenCharge
      cChildrenThresholdCharge
      cDifferenceAmount1
      cDifferenceAmount2
      cDifferenceAmount3
      cDifferenceAmount4
      cDifferenceAmount5
      cDifferenceAmountExtraAdult
      cExchangeDate
      cExchangeRate
      cFlatIncrease
      cLos1Amount
      cLos10Amount
      cLos11Amount
      cLos12Amount
      cLos13Amount
      cLos14Amount
      cLos2Amount
      cLos3Amount
      cLos4Amount
      cLos5Amount
      cLos6Amount
      cLos7Amount
      cLos8Amount
      cLos9Amount
      cMaximumAmount1
      cMaximumAmount2
      cMinimumAmount1
      cMinimumAmount2
      cOccupantsThresholdCharge
      cPackageRateStayOver
      cRoomCost
      calculationFlag
      catPackagePriceCode
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralPackageCode
      centralRoomType
      centralRoomTypeDescription
      centralSeasonCode
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      childExcThreshold1
      childExcThreshold2
      childExcThreshold3
      childOwnCharge1
      childOwnCharge2
      childOwnCharge3
      childOwnCharge4
      childrenFreeStay
      childrenCharge
      childrenThreshold
      childrenThresholdCharge
      currencyCode
      currencyDescription
      dSI
      deletedflag
      depositRequieredYn
      differenceAmount1
      differenceAmount2
      differenceAmount3
      differenceAmount4
      differenceAmount5
      differenceAmountExtraAdult
      differencePercentage1Yn
      differencePercentage2Yn
      differencePercentage3Yn
      differencePercentage4Yn
      differencePercentage5Yn
      differencePercentageExtraAdultYn
      endDate
      externalRateSetId
      extraAdultType
      flatIncrease
      globalRateUpdateYn
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      internalRatesetid
      jRNUpdateDate
      jRNUpdateDateAndTime
      lengthOfStay1Amount
      lengthOfStay10Amount
      lengthOfStay11Amount
      lengthOfStay12Amount
      lengthOfStay13Amount
      lengthOfStay14Amount
      lengthOfStay2Amount
      lengthOfStay3Amount
      lengthOfStay4Amount
      lengthOfStay5Amount
      lengthOfStay6Amount
      lengthOfStay7Amount
      lengthOfStay8Amount
      lengthOfStay9Amount
      linkRateSetId
      locationID
      marketCode
      marketDescription
      marketGroupCode
      marketGroupDescription
      maximumAmount1
      maximumAmount2
      minChildrenForFreeStay
      minimumAmount1
      minimumAmount2
      minimumClosingProbability
      occupantsThreshold
      occupantsThresholdCharge
      organizationID
      packageAdultStayOver
      packageChildrenStayOver
      packageCode
      packageRateStayOver
      percentIncrease
      pointsRequired
      primaryKeyID
      property
      rateAvailableOnFridaysYN
      rateAvailableOnMondaysYN
      rateAvailableOnSaturdaysYN
      rateAvailableOnSundaysYN
      rateAvailableOnThursdaysYN
      rateAvailableOnTuesdaysYN
      rateAvailableOnWednesdaysYN
      rateCode
      rateCodeDesc
      rateCodeId
      rateRule
      rateSetId
      rateForChildInAgeBucket1
      rateForChildInAgeBucket2
      rateForChildInAgeBucket3
      ratesActiveYn
      ratetierid
      repSeasonDescription
      rnaInsertDate
      rnaUpdateDate
      roomCost
      roomType
      roomTypeDescription
      roundToNearest
      season
      seasonCode
      seasonDesc
      sourceCode
      sourceDescription
      sourceGroupCode
      sourceGroupDescription
      startDate
      tierId
      updateDate
      updateUser
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
    folioTaxDetails {
      accountCode
      addresseeNameId
      amountPostedFromAR
      amountFromDirectBill
      associatedBillDate
      associatedBillNumber
      associatedFiscalBillDate
      associatedFiscalBillNumber
      associatedFiscalBillNumberGenerationTime
      associatedSeqNumber
      billGenerationDate
      billNumber
      billPaymentTrxNumber
      billPrefix
      billSequenceNumber
      billStartDate
      billStatus
      businessDate
      businessId
      cCashpay
      cCcpay
      cClarpay
      cClpay
      cCollectionTax1
      cCollectionTax2
      cCollectionTax3
      cCollectionTax4
      cCollectionTax5
      cDailyRunningTotal
      cDeposit
      cExchangeDate
      cExchangeRate
      cFiscalInvoiceCurrencyRate
      cNet1Amount
      cNet10Amount
      cNet11Amount
      cNet12Amount
      cNet13Amount
      cNet14Amount
      cNet15Amount
      cNet16Amount
      cNet17Amount
      cNet18Amount
      cNet19Amount
      cNet2Amount
      cNet20Amount
      cNet3Amount
      cNet4Amount
      cNet5Amount
      cNet6Amount
      cNet7Amount
      cNet8Amount
      cNet9Amount
      cPaidout
      cPerpetualAmount
      cPnet1Amount
      cPnet10Amount
      cPnet11Amount
      cPnet12Amount
      cPnet13Amount
      cPnet14Amount
      cPnet15Amount
      cPnet16Amount
      cPnet17Amount
      cPnet18Amount
      cPnet19Amount
      cPnet2Amount
      cPnet20Amount
      cPnet3Amount
      cPnet4Amount
      cPnet5Amount
      cPnet6Amount
      cPnet7Amount
      cPnet8Amount
      cPnet9Amount
      cPtax1Amount
      cPtax10Amount
      cPtax11Amount
      cPtax12Amount
      cPtax13Amount
      cPtax14Amount
      cPtax15Amount
      cPtax16Amount
      cPtax17Amount
      cPtax18Amount
      cPtax19Amount
      cPtax2Amount
      cPtax20Amount
      cPtax3Amount
      cPtax4Amount
      cPtax5Amount
      cPtax6Amount
      cPtax7Amount
      cPtax8Amount
      cPtax9Amount
      cPtotNonrevNonTaxable
      cPtotNonrevTaxable
      cPtotRevenueNonTaxable
      cPtotRevenueTaxable
      cRealPerpetualAmount
      cTax1Amount
      cTax2Amount
      cTaxCode1
      cTaxCode10
      cTaxCode11
      cTaxCode12
      cTaxCode13
      cTaxCode14
      cTaxCode15
      cTaxCode16
      cTaxCode17
      cTaxCode18
      cTaxCode19
      cTaxCode2
      cTaxCode20
      cTaxCode3
      cTaxCode4
      cTaxCode5
      cTaxCode6
      cTaxCode7
      cTaxCode8
      cTaxCode9
      cTaxCodeDescription1
      cTaxCodeDescription10
      cTaxCodeDescription11
      cTaxCodeDescription12
      cTaxCodeDescription13
      cTaxCodeDescription14
      cTaxCodeDescription15
      cTaxCodeDescription16
      cTaxCodeDescription17
      cTaxCodeDescription18
      cTaxCodeDescription19
      cTaxCodeDescription2
      cTaxCodeDescription20
      cTaxCodeDescription3
      cTaxCodeDescription4
      cTaxCodeDescription5
      cTaxCodeDescription6
      cTaxCodeDescription7
      cTaxCodeDescription8
      cTaxCodeDescription9
      cTax10Amount
      cTax11Amount
      cTax12Amount
      cTax13Amount
      cTax14Amount
      cTax15Amount
      cTax16Amount
      cTax17Amount
      cTax18Amount
      cTax19Amount
      cTax20Amount
      cTax3Amount
      cTax4Amount
      cTax5Amount
      cTax6Amount
      cTax7Amount
      cTax8Amount
      cTax9Amount
      cTotalGross
      cTotalNet
      cTotalNonTaxable
      cTotalNonrevNonTaxable
      cTotalNonrevTaxable
      cTotalRevenueNonTaxable
      cTotalRevenueTaxable
      cTotalTax
      cXnet1Amount
      cXnet10Amount
      cXnet11Amount
      cXnet12Amount
      cXnet13Amount
      cXnet14Amount
      cXnet15Amount
      cXnet16Amount
      cXnet17Amount
      cXnet18Amount
      cXnet19Amount
      cXnet2Amount
      cXnet20Amount
      cXnet3Amount
      cXnet4Amount
      cXnet5Amount
      cXnet6Amount
      cXnet7Amount
      cXnet8Amount
      cXnet9Amount
      cXtax1Amount
      cXtax10Amount
      cXtax11Amount
      cXtax12Amount
      cXtax13Amount
      cXtax14Amount
      cXtax15Amount
      cXtax16Amount
      cXtax17Amount
      cXtax18Amount
      cXtax19Amount
      cXtax2Amount
      cXtax20Amount
      cXtax3Amount
      cXtax4Amount
      cXtax5Amount
      cXtax6Amount
      cXtax7Amount
      cXtax8Amount
      cXtax9Amount
      cashRegisterId
      cashRegisterInvNumber
      cashTotal
      cashierID
      centralTaxRate1
      centralTaxRate10
      centralTaxRate11
      centralTaxRate12
      centralTaxRate13
      centralTaxRate14
      centralTaxRate15
      centralTaxRate16
      centralTaxRate17
      centralTaxRate18
      centralTaxRate19
      centralTaxRate2
      centralTaxRate20
      centralTaxRate3
      centralTaxRate4
      centralTaxRate5
      centralTaxRate6
      centralTaxRate7
      centralTaxRate8
      centralTaxRate9
      city
      cityLedgerYN
      clTrxNumber
      collectionAgentTotalTax1
      collectionAgentTotalTax2
      collectionAgentTotalTax3
      collectionAgentTotalTax4
      collectionAgentTotalTax5
      companyFinancialValue
      companyName
      companyType
      compressBillNo
      creditBillGeneratedYN
      creditBillNumber
      creditCardTotal
      customNumber1
      customNumber2
      customNumber3
      customNumber4
      customNumber5
      dSI
      dailyRunningTotal
      deletedFlag
      deposit
      depositReqReceiptNumber
      documentCode
      documentType
      eArchiveEttnNumber
      eArchiveNumber
      eArchiveReportNo
      eArchiveStatus
      eInvoiceNumber
      eInvoiceStatus
      fiscalBillCheckDigit
      fiscalBillGenerationDate
      fiscalBillGenerationTime
      fiscalBillNumber
      fiscalInvoiceCurrency
      fiscalInvoiceCurrencyRate
      fiscalSessionNo
      fiscalUnitControlCode
      folioAddress
      folioAddressCorrectedYn
      folioAttachmentLinkId
      folioAttachmentStatus
      folioNo
      folioStyle
      folioTaxSeqNumber
      folioTime
      folioType
      folioType1
      folioTypeJoin
      folioView
      forexTaxYn
      fullFolioNo
      hasWatermarkYn
      hotelName
      insTimestamp
      insertDate
      invoiceNumber
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastSignature
      locationID
      nRBusinessID
      nafApeHotelCode
      nameId
      nameTaxType
      netAmount1
      netAmount10
      netAmount11
      netAmount12
      netAmount13
      netAmount14
      netAmount15
      netAmount16
      netAmount17
      netAmount18
      netAmount19
      netAmount2
      netAmount20
      netAmount3
      netAmount4
      netAmount5
      netAmount6
      netAmount7
      netAmount8
      netAmount9
      numberOfPages
      operaFiscalFolioStatus
      organizationID
      pageNumber
      palmVideoFlag
      partnerFiscalFolioStatus
      payeeAddress
      payeeCountry
      payeeFirstName
      payeeLastName
      payeeName
      payeeNameID
      payeePostalCode
      payeeTaxID1
      payeeTaxID2
      payeeZipCode
      paymentDate
      perpetualAmount
      pnet1Amt
      pnet10Amt
      pnet11Amt
      pnet12Amt
      pnet13Amt
      pnet14Amt
      pnet15Amt
      pnet16Amt
      pnet17Amt
      pnet18Amt
      pnet19Amt
      pnet2Amt
      pnet20Amt
      pnet3Amt
      pnet4Amt
      pnet5Amt
      pnet6Amt
      pnet7Amt
      pnet8Amt
      pnet9Amt
      postitSequenceNumber
      postitYN
      primaryKeyID
      printerQueueName
      profileTypeCode
      promotionalText1
      promotionalText2
      property
      propertyBillPrefix
      propertyTaxNumber
      ptax1Amt
      ptax10Amt
      ptax11Amt
      ptax12Amt
      ptax13Amt
      ptax14Amt
      ptax15Amt
      ptax16Amt
      ptax17Amt
      ptax18Amt
      ptax19Amt
      ptax2Amt
      ptax20Amt
      ptax3Amt
      ptax4Amt
      ptax5Amt
      ptax6Amt
      ptax7Amt
      ptax8Amt
      ptax9Amt
      ptotNonrevNonTaxable
      ptotNonrevTaxable
      ptotRevNonTaxable
      ptotRevTaxable
      realPerpetualAmount
      reservationNameId
      resortCity
      resortCountry
      resortFullAddress
      resortZipcodeCode
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomNumber
      seqNumber
      signature
      signatureKeyVersion
      softwareVersion
      tax1RateType
      tax2RateType
      taxAmount1
      taxAmount10
      taxAmount11
      taxAmount12
      taxAmount13
      taxAmount14
      taxAmount15
      taxAmount16
      taxAmount17
      taxAmount18
      taxAmount19
      taxAmount2
      taxAmount20
      taxAmount3
      taxAmount4
      taxAmount5
      taxAmount6
      taxAmount7
      taxAmount8
      taxAmount9
      taxCode1
      taxCode10
      taxCode11
      taxCode12
      taxCode13
      taxCode14
      taxCode15
      taxCode16
      taxCode17
      taxCode18
      taxCode19
      taxCode2
      taxCode20
      taxCode3
      taxCode4
      taxCode5
      taxCode6
      taxCode7
      taxCode8
      taxCode9
      taxCodeDesc1
      taxCodeDesc10
      taxCodeDesc11
      taxCodeDesc12
      taxCodeDesc13
      taxCodeDesc14
      taxCodeDesc15
      taxCodeDesc16
      taxCodeDesc17
      taxCodeDesc18
      taxCodeDesc19
      taxCodeDesc2
      taxCodeDesc20
      taxCodeDesc3
      taxCodeDesc4
      taxCodeDesc5
      taxCodeDesc6
      taxCodeDesc7
      taxCodeDesc8
      taxCodeDesc9
      taxId
      taxRate1
      taxRate10
      taxRate11
      taxRate12
      taxRate13
      taxRate14
      taxRate15
      taxRate16
      taxRate17
      taxRate18
      taxRate19
      taxRate2
      taxRate20
      taxRate3
      taxRate4
      taxRate5
      taxRate6
      taxRate7
      taxRate8
      taxRate9
      tax10RateType
      tax11RateType
      tax12RateType
      tax13RateType
      tax14RateType
      tax15RateType
      tax16RateType
      tax17RateType
      tax18RateType
      tax19RateType
      tax20RateType
      tax3RateType
      tax4RateType
      tax5RateType
      tax6RateType
      tax7RateType
      tax8RateType
      tax9RateType
      terminal
      totalGrossAmount
      totalNetAmount
      totalNonRevenueNonTaxableAmount
      totalNonRevenueTaxableAmount
      totalNonTaxableAmount
      totalNonTaxableRevenue
      totalPaidOuts
      totalTax
      totalTaxableRevenue
      transactLastSignatureHash
      transactSignatureHash
      transactSignatureKeyVersion
      transactionSignature
      trxServiceType
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
      updTimestamp
      updateDate
      updateUser
      userID
      userName
      voidNumber
      voidReason
      workingDocId
      xnet1Amt
      xnet10Amt
      xnet11Amt
      xnet12Amt
      xnet13Amt
      xnet14Amt
      xnet15Amt
      xnet16Amt
      xnet17Amt
      xnet18Amt
      xnet19Amt
      xnet2Amt
      xnet20Amt
      xnet3Amt
      xnet4Amt
      xnet5Amt
      xnet6Amt
      xnet7Amt
      xnet8Amt
      xnet9Amt
      xtax1Amt
      xtax10Amt
      xtax11Amt
      xtax12Amt
      xtax13Amt
      xtax14Amt
      xtax15Amt
      xtax16Amt
      xtax17Amt
      xtax18Amt
      xtax19Amt
      xtax2Amt
      xtax20Amt
      xtax3Amt
      xtax4Amt
      xtax5Amt
      xtax6Amt
      xtax7Amt
      xtax8Amt
      xtax9Amt
    }
    financialUnifiedDetails {
      aRChargeTransferFlagYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      accountCode
      accountNumber
      addressId
      advanceBillReversedYN
      advanceBillYn
      advancedGenerateYN
      advgenTtransCodeID
      arrangementCode
      arrangementDesc
      articleId
      associatedTrxNumber
      attachedToUser
      authEmployeeID
      authorizer
      autoCreditbillYn
      autoSettleYn
      businessDate
      cCApproval
      cashierCode
      cashierCredit
      cashierDebit
      cashierID
      cashierName
      cashierOpeningBalance
      ccRefundPosting
      changesLogCheckIn
      changesLogCheckOut
      changesLogCloseFolio
      changesLogReopenFolio
      changesLogUpdateReservation
      checkNumber
      closureNumber
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      compressedYn
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      currencyDescription
      dSI
      debitYN
      decimals
      deferredYn
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      displayYN
      euroExchangeRate
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      financialDmlSeqNumber
      fiscalBillNo
      fixedChargesYN
      folio
      folioNo
      folioType
      folioView
      foreignCurrencyCode
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      generalCashierYN
      grossAmount
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      inHouseCredit
      inHouseDebit
      insertDate
      insertUser
      insertUserName
      interfaceCashierYN
      internalArticleid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      linkTrxNumber
      marketCode
      marketDescription
      membershipID
      mtrxNoAgainstPackage
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      organizationID
      originalARLedgerDebit
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      passerByName
      payeeNameID
      payeeResvNameID
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
      profileID
      profitLossFlag
      proformaYN
      property
      quantity
      queueName
      rateCode
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationNameID
      revenueAmount
      reversePaymentTrxNumber
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingCode
      routingCodeDescription
      routingDate
      routingIinstructionID
      routingInstrnId
      routingType
      settlementFlag
      sourceCode
      sourceDescription
      supplement
      tRXCode
      targetResort
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      tcGroup
      tcSubgroup
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transCodeArrangementID
      transactionActivityDate
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionType
      transactionFromAccount
      transactionToAccount
      transferFromAccountID
      transferToAccountID
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      updateDate
      updateUser
      vatAmount
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
reservation_unified_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'actionId': pl.Float64,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'agentNameId': pl.Float64,
    'allAliases': pl.Utf8,
    'allBlockOwners': pl.Utf8,
    'allCateringOwners': pl.Utf8,
    'allCompanyContacts': pl.Utf8,
    'allRateCodes': pl.Utf8,
    'allRoomOwners': pl.Utf8,
    'allRoomTypes': pl.Utf8,
    'allSourceContacts': pl.Utf8,
    'allTravelAgentContacts': pl.Utf8,
    'allotmentOrigin': pl.Utf8,
    'allotmentRecordType': pl.Float64,
    'allotmentType': pl.Utf8,
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
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoSettleDays': pl.Utf8,
    'autoSettleYN': pl.Float64,
    'averageRate': pl.Float64,
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
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingcontactprofileid': pl.Float64,
    'blockAlias': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockDmlSeqNumber': pl.Float64,
    'blockEndbusinessdate': pl.Utf8,
    'blockExchangePostingType': pl.Utf8,
    'blockExchangeRate': pl.Float64,
    'blockExternalReference': pl.Utf8,
    'blockID': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockStatusDescription': pl.Utf8,
    'blocksExternalReference': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'changesLogCheckIn': pl.Utf8,
    'changesLogCheckOut': pl.Utf8,
    'changesLogCloseFolio': pl.Utf8,
    'changesLogReopenFolio': pl.Utf8,
    'changesLogUpdateReservation': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Float64,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyAll': pl.Utf8,
    'companyID': pl.Float64,
    'companyNameId': pl.Float64,
    'compreasonid': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactProfileID': pl.Float64,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endDate': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Float64,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extBookingID': pl.Utf8,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externallyLocked': pl.Utf8,
    'extraBeds': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'gUID': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Float64,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertUser': pl.Int64,
    'interfaceID': pl.Utf8,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Utf8,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'keyValidUntil': pl.Float64,
    'laptopChange': pl.Float64,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'mailYn': pl.Utf8,
    'mainmarket': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketid': pl.Utf8,
    'masterBlockID': pl.Float64,
    'masterBlockProperty': pl.Utf8,
    'masterNameId': pl.Float64,
    'membershipId': pl.Float64,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCodeDescription': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'owner': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerResort': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'payment': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Utf8,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Utf8,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'profileId': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Utf8,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Utf8,
    'reinstateDate': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reserveInventoryYN': pl.Utf8,
    'resort': pl.Utf8,
    'resortBooked': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rivMarketSegment': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomInstructions': pl.Utf8,
    'roomServiceTime': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'senddate': pl.Utf8,
    'serviceCharge': pl.Float64,
    'sguestFirstName': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareId': pl.Float64,
    'shareSeqNumber': pl.Utf8,
    'shareOfRateAmount': pl.Float64,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceContactAll': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceid': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'startDate': pl.Utf8,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Utf8,
    'stayRecordId': pl.Float64,
    'superSearchIndexText': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Utf8,
    'taxType': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'traceCode': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentAll': pl.Utf8,
    'travelAgentID': pl.Float64,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Float64,
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
    'uniCardId': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Float64,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Float64,
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
profile_accounts_source_details_schema = {
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
profile_accounts_details_schema = {
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
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
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
rate_code_details_details_schema = {
    'addAfterRounding': pl.Float64,
    'adultCharge': pl.Float64,
    'adultsThreshold': pl.Float64,
    'adultsThresholdCharge': pl.Float64,
    'advBaseAmount': pl.Float64,
    'advBaseFltPct': pl.Utf8,
    'advDailyBaseRateCode': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'ageRangeForBucket1': pl.Utf8,
    'ageRangeForBucket2': pl.Utf8,
    'ageRangeForBucket3': pl.Utf8,
    'amount1Type': pl.Utf8,
    'amount2Type': pl.Utf8,
    'amount3Type': pl.Utf8,
    'amount4Type': pl.Utf8,
    'amount5Type': pl.Utf8,
    'amountFor1Person': pl.Float64,
    'amountFor2Persons': pl.Float64,
    'amountFor3Persons': pl.Float64,
    'amountFor4Persons': pl.Float64,
    'amountFor5Persons': pl.Float64,
    'barAmount': pl.Float64,
    'barFltPct': pl.Utf8,
    'barRounding': pl.Utf8,
    'barYn': pl.Utf8,
    'cAdultCharge': pl.Float64,
    'cAdultsThresholdCharge': pl.Float64,
    'cAdvanceBaseAmount': pl.Float64,
    'cAmount1': pl.Float64,
    'cAmount2': pl.Float64,
    'cAmount3': pl.Float64,
    'cAmount4': pl.Float64,
    'cAmount5': pl.Float64,
    'cBarAmount': pl.Float64,
    'cChildCharge1': pl.Float64,
    'cChildCharge2': pl.Float64,
    'cChildCharge3': pl.Float64,
    'cChildOwnCharge1': pl.Float64,
    'cChildOwnCharge2': pl.Float64,
    'cChildOwnCharge3': pl.Float64,
    'cChildOwnCharge4': pl.Float64,
    'cChildrenCharge': pl.Float64,
    'cChildrenThresholdCharge': pl.Float64,
    'cDifferenceAmount1': pl.Float64,
    'cDifferenceAmount2': pl.Float64,
    'cDifferenceAmount3': pl.Float64,
    'cDifferenceAmount4': pl.Float64,
    'cDifferenceAmount5': pl.Float64,
    'cDifferenceAmountExtraAdult': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFlatIncrease': pl.Float64,
    'cLos1Amount': pl.Float64,
    'cLos10Amount': pl.Float64,
    'cLos11Amount': pl.Float64,
    'cLos12Amount': pl.Float64,
    'cLos13Amount': pl.Float64,
    'cLos14Amount': pl.Float64,
    'cLos2Amount': pl.Float64,
    'cLos3Amount': pl.Float64,
    'cLos4Amount': pl.Float64,
    'cLos5Amount': pl.Float64,
    'cLos6Amount': pl.Float64,
    'cLos7Amount': pl.Float64,
    'cLos8Amount': pl.Float64,
    'cLos9Amount': pl.Float64,
    'cMaximumAmount1': pl.Float64,
    'cMaximumAmount2': pl.Float64,
    'cMinimumAmount1': pl.Float64,
    'cMinimumAmount2': pl.Float64,
    'cOccupantsThresholdCharge': pl.Float64,
    'cPackageRateStayOver': pl.Float64,
    'cRoomCost': pl.Float64,
    'calculationFlag': pl.Utf8,
    'catPackagePriceCode': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralPackageCode': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralSeasonCode': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'childExcThreshold1': pl.Utf8,
    'childExcThreshold2': pl.Utf8,
    'childExcThreshold3': pl.Utf8,
    'childOwnCharge1': pl.Float64,
    'childOwnCharge2': pl.Float64,
    'childOwnCharge3': pl.Float64,
    'childOwnCharge4': pl.Float64,
    'childrenFreeStay': pl.Float64,
    'childrenCharge': pl.Float64,
    'childrenThreshold': pl.Float64,
    'childrenThresholdCharge': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'depositRequieredYn': pl.Utf8,
    'differenceAmount1': pl.Float64,
    'differenceAmount2': pl.Float64,
    'differenceAmount3': pl.Float64,
    'differenceAmount4': pl.Float64,
    'differenceAmount5': pl.Float64,
    'differenceAmountExtraAdult': pl.Float64,
    'differencePercentage1Yn': pl.Utf8,
    'differencePercentage2Yn': pl.Utf8,
    'differencePercentage3Yn': pl.Utf8,
    'differencePercentage4Yn': pl.Utf8,
    'differencePercentage5Yn': pl.Utf8,
    'differencePercentageExtraAdultYn': pl.Utf8,
    'endDate': pl.Utf8,
    'externalRateSetId': pl.Float64,
    'extraAdultType': pl.Utf8,
    'flatIncrease': pl.Float64,
    'globalRateUpdateYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalRatesetid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lengthOfStay1Amount': pl.Float64,
    'lengthOfStay10Amount': pl.Float64,
    'lengthOfStay11Amount': pl.Float64,
    'lengthOfStay12Amount': pl.Float64,
    'lengthOfStay13Amount': pl.Float64,
    'lengthOfStay14Amount': pl.Float64,
    'lengthOfStay2Amount': pl.Float64,
    'lengthOfStay3Amount': pl.Float64,
    'lengthOfStay4Amount': pl.Float64,
    'lengthOfStay5Amount': pl.Float64,
    'lengthOfStay6Amount': pl.Float64,
    'lengthOfStay7Amount': pl.Float64,
    'lengthOfStay8Amount': pl.Float64,
    'lengthOfStay9Amount': pl.Float64,
    'linkRateSetId': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'maximumAmount1': pl.Float64,
    'maximumAmount2': pl.Float64,
    'minChildrenForFreeStay': pl.Float64,
    'minimumAmount1': pl.Float64,
    'minimumAmount2': pl.Float64,
    'minimumClosingProbability': pl.Float64,
    'occupantsThreshold': pl.Float64,
    'occupantsThresholdCharge': pl.Float64,
    'organizationID': pl.Int64,
    'packageAdultStayOver': pl.Float64,
    'packageChildrenStayOver': pl.Float64,
    'packageCode': pl.Utf8,
    'packageRateStayOver': pl.Float64,
    'percentIncrease': pl.Float64,
    'pointsRequired': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateAvailableOnFridaysYN': pl.Utf8,
    'rateAvailableOnMondaysYN': pl.Utf8,
    'rateAvailableOnSaturdaysYN': pl.Utf8,
    'rateAvailableOnSundaysYN': pl.Utf8,
    'rateAvailableOnThursdaysYN': pl.Utf8,
    'rateAvailableOnTuesdaysYN': pl.Utf8,
    'rateAvailableOnWednesdaysYN': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDesc': pl.Utf8,
    'rateCodeId': pl.Utf8,
    'rateRule': pl.Utf8,
    'rateSetId': pl.Float64,
    'rateForChildInAgeBucket1': pl.Float64,
    'rateForChildInAgeBucket2': pl.Float64,
    'rateForChildInAgeBucket3': pl.Float64,
    'ratesActiveYn': pl.Utf8,
    'ratetierid': pl.Float64,
    'repSeasonDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCost': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roundToNearest': pl.Float64,
    'season': pl.Utf8,
    'seasonCode': pl.Utf8,
    'seasonDesc': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'tierId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
folio_tax_details_schema = {
    'accountCode': pl.Float64,
    'addresseeNameId': pl.Float64,
    'amountPostedFromAR': pl.Float64,
    'amountFromDirectBill': pl.Float64,
    'associatedBillDate': pl.Utf8,
    'associatedBillNumber': pl.Utf8,
    'associatedFiscalBillDate': pl.Utf8,
    'associatedFiscalBillNumber': pl.Utf8,
    'associatedFiscalBillNumberGenerationTime': pl.Utf8,
    'associatedSeqNumber': pl.Float64,
    'billGenerationDate': pl.Utf8,
    'billNumber': pl.Float64,
    'billPaymentTrxNumber': pl.Float64,
    'billPrefix': pl.Utf8,
    'billSequenceNumber': pl.Float64,
    'billStartDate': pl.Utf8,
    'billStatus': pl.Utf8,
    'businessDate': pl.Utf8,
    'businessId': pl.Utf8,
    'cCashpay': pl.Float64,
    'cCcpay': pl.Float64,
    'cClarpay': pl.Float64,
    'cClpay': pl.Float64,
    'cCollectionTax1': pl.Float64,
    'cCollectionTax2': pl.Float64,
    'cCollectionTax3': pl.Float64,
    'cCollectionTax4': pl.Float64,
    'cCollectionTax5': pl.Float64,
    'cDailyRunningTotal': pl.Float64,
    'cDeposit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFiscalInvoiceCurrencyRate': pl.Float64,
    'cNet1Amount': pl.Float64,
    'cNet10Amount': pl.Float64,
    'cNet11Amount': pl.Float64,
    'cNet12Amount': pl.Float64,
    'cNet13Amount': pl.Float64,
    'cNet14Amount': pl.Float64,
    'cNet15Amount': pl.Float64,
    'cNet16Amount': pl.Float64,
    'cNet17Amount': pl.Float64,
    'cNet18Amount': pl.Float64,
    'cNet19Amount': pl.Float64,
    'cNet2Amount': pl.Float64,
    'cNet20Amount': pl.Float64,
    'cNet3Amount': pl.Float64,
    'cNet4Amount': pl.Float64,
    'cNet5Amount': pl.Float64,
    'cNet6Amount': pl.Float64,
    'cNet7Amount': pl.Float64,
    'cNet8Amount': pl.Float64,
    'cNet9Amount': pl.Float64,
    'cPaidout': pl.Float64,
    'cPerpetualAmount': pl.Float64,
    'cPnet1Amount': pl.Float64,
    'cPnet10Amount': pl.Float64,
    'cPnet11Amount': pl.Float64,
    'cPnet12Amount': pl.Float64,
    'cPnet13Amount': pl.Float64,
    'cPnet14Amount': pl.Float64,
    'cPnet15Amount': pl.Float64,
    'cPnet16Amount': pl.Float64,
    'cPnet17Amount': pl.Float64,
    'cPnet18Amount': pl.Float64,
    'cPnet19Amount': pl.Float64,
    'cPnet2Amount': pl.Float64,
    'cPnet20Amount': pl.Float64,
    'cPnet3Amount': pl.Float64,
    'cPnet4Amount': pl.Float64,
    'cPnet5Amount': pl.Float64,
    'cPnet6Amount': pl.Float64,
    'cPnet7Amount': pl.Float64,
    'cPnet8Amount': pl.Float64,
    'cPnet9Amount': pl.Float64,
    'cPtax1Amount': pl.Float64,
    'cPtax10Amount': pl.Float64,
    'cPtax11Amount': pl.Float64,
    'cPtax12Amount': pl.Float64,
    'cPtax13Amount': pl.Float64,
    'cPtax14Amount': pl.Float64,
    'cPtax15Amount': pl.Float64,
    'cPtax16Amount': pl.Float64,
    'cPtax17Amount': pl.Float64,
    'cPtax18Amount': pl.Float64,
    'cPtax19Amount': pl.Float64,
    'cPtax2Amount': pl.Float64,
    'cPtax20Amount': pl.Float64,
    'cPtax3Amount': pl.Float64,
    'cPtax4Amount': pl.Float64,
    'cPtax5Amount': pl.Float64,
    'cPtax6Amount': pl.Float64,
    'cPtax7Amount': pl.Float64,
    'cPtax8Amount': pl.Float64,
    'cPtax9Amount': pl.Float64,
    'cPtotNonrevNonTaxable': pl.Float64,
    'cPtotNonrevTaxable': pl.Float64,
    'cPtotRevenueNonTaxable': pl.Float64,
    'cPtotRevenueTaxable': pl.Float64,
    'cRealPerpetualAmount': pl.Float64,
    'cTax1Amount': pl.Float64,
    'cTax2Amount': pl.Float64,
    'cTaxCode1': pl.Utf8,
    'cTaxCode10': pl.Utf8,
    'cTaxCode11': pl.Utf8,
    'cTaxCode12': pl.Utf8,
    'cTaxCode13': pl.Utf8,
    'cTaxCode14': pl.Utf8,
    'cTaxCode15': pl.Utf8,
    'cTaxCode16': pl.Utf8,
    'cTaxCode17': pl.Utf8,
    'cTaxCode18': pl.Utf8,
    'cTaxCode19': pl.Utf8,
    'cTaxCode2': pl.Utf8,
    'cTaxCode20': pl.Utf8,
    'cTaxCode3': pl.Utf8,
    'cTaxCode4': pl.Utf8,
    'cTaxCode5': pl.Utf8,
    'cTaxCode6': pl.Utf8,
    'cTaxCode7': pl.Utf8,
    'cTaxCode8': pl.Utf8,
    'cTaxCode9': pl.Utf8,
    'cTaxCodeDescription1': pl.Utf8,
    'cTaxCodeDescription10': pl.Utf8,
    'cTaxCodeDescription11': pl.Utf8,
    'cTaxCodeDescription12': pl.Utf8,
    'cTaxCodeDescription13': pl.Utf8,
    'cTaxCodeDescription14': pl.Utf8,
    'cTaxCodeDescription15': pl.Utf8,
    'cTaxCodeDescription16': pl.Utf8,
    'cTaxCodeDescription17': pl.Utf8,
    'cTaxCodeDescription18': pl.Utf8,
    'cTaxCodeDescription19': pl.Utf8,
    'cTaxCodeDescription2': pl.Utf8,
    'cTaxCodeDescription20': pl.Utf8,
    'cTaxCodeDescription3': pl.Utf8,
    'cTaxCodeDescription4': pl.Utf8,
    'cTaxCodeDescription5': pl.Utf8,
    'cTaxCodeDescription6': pl.Utf8,
    'cTaxCodeDescription7': pl.Utf8,
    'cTaxCodeDescription8': pl.Utf8,
    'cTaxCodeDescription9': pl.Utf8,
    'cTax10Amount': pl.Float64,
    'cTax11Amount': pl.Float64,
    'cTax12Amount': pl.Float64,
    'cTax13Amount': pl.Float64,
    'cTax14Amount': pl.Float64,
    'cTax15Amount': pl.Float64,
    'cTax16Amount': pl.Float64,
    'cTax17Amount': pl.Float64,
    'cTax18Amount': pl.Float64,
    'cTax19Amount': pl.Float64,
    'cTax20Amount': pl.Float64,
    'cTax3Amount': pl.Float64,
    'cTax4Amount': pl.Float64,
    'cTax5Amount': pl.Float64,
    'cTax6Amount': pl.Float64,
    'cTax7Amount': pl.Float64,
    'cTax8Amount': pl.Float64,
    'cTax9Amount': pl.Float64,
    'cTotalGross': pl.Float64,
    'cTotalNet': pl.Float64,
    'cTotalNonTaxable': pl.Float64,
    'cTotalNonrevNonTaxable': pl.Float64,
    'cTotalNonrevTaxable': pl.Float64,
    'cTotalRevenueNonTaxable': pl.Float64,
    'cTotalRevenueTaxable': pl.Float64,
    'cTotalTax': pl.Float64,
    'cXnet1Amount': pl.Float64,
    'cXnet10Amount': pl.Float64,
    'cXnet11Amount': pl.Float64,
    'cXnet12Amount': pl.Float64,
    'cXnet13Amount': pl.Float64,
    'cXnet14Amount': pl.Float64,
    'cXnet15Amount': pl.Float64,
    'cXnet16Amount': pl.Float64,
    'cXnet17Amount': pl.Float64,
    'cXnet18Amount': pl.Float64,
    'cXnet19Amount': pl.Float64,
    'cXnet2Amount': pl.Float64,
    'cXnet20Amount': pl.Float64,
    'cXnet3Amount': pl.Float64,
    'cXnet4Amount': pl.Float64,
    'cXnet5Amount': pl.Float64,
    'cXnet6Amount': pl.Float64,
    'cXnet7Amount': pl.Float64,
    'cXnet8Amount': pl.Float64,
    'cXnet9Amount': pl.Float64,
    'cXtax1Amount': pl.Float64,
    'cXtax10Amount': pl.Float64,
    'cXtax11Amount': pl.Float64,
    'cXtax12Amount': pl.Float64,
    'cXtax13Amount': pl.Float64,
    'cXtax14Amount': pl.Float64,
    'cXtax15Amount': pl.Float64,
    'cXtax16Amount': pl.Float64,
    'cXtax17Amount': pl.Float64,
    'cXtax18Amount': pl.Float64,
    'cXtax19Amount': pl.Float64,
    'cXtax2Amount': pl.Float64,
    'cXtax20Amount': pl.Float64,
    'cXtax3Amount': pl.Float64,
    'cXtax4Amount': pl.Float64,
    'cXtax5Amount': pl.Float64,
    'cXtax6Amount': pl.Float64,
    'cXtax7Amount': pl.Float64,
    'cXtax8Amount': pl.Float64,
    'cXtax9Amount': pl.Float64,
    'cashRegisterId': pl.Utf8,
    'cashRegisterInvNumber': pl.Float64,
    'cashTotal': pl.Float64,
    'cashierID': pl.Float64,
    'centralTaxRate1': pl.Float64,
    'centralTaxRate10': pl.Float64,
    'centralTaxRate11': pl.Float64,
    'centralTaxRate12': pl.Float64,
    'centralTaxRate13': pl.Float64,
    'centralTaxRate14': pl.Float64,
    'centralTaxRate15': pl.Float64,
    'centralTaxRate16': pl.Float64,
    'centralTaxRate17': pl.Float64,
    'centralTaxRate18': pl.Float64,
    'centralTaxRate19': pl.Float64,
    'centralTaxRate2': pl.Float64,
    'centralTaxRate20': pl.Float64,
    'centralTaxRate3': pl.Float64,
    'centralTaxRate4': pl.Float64,
    'centralTaxRate5': pl.Float64,
    'centralTaxRate6': pl.Float64,
    'centralTaxRate7': pl.Float64,
    'centralTaxRate8': pl.Float64,
    'centralTaxRate9': pl.Float64,
    'city': pl.Utf8,
    'cityLedgerYN': pl.Utf8,
    'clTrxNumber': pl.Float64,
    'collectionAgentTotalTax1': pl.Float64,
    'collectionAgentTotalTax2': pl.Float64,
    'collectionAgentTotalTax3': pl.Float64,
    'collectionAgentTotalTax4': pl.Float64,
    'collectionAgentTotalTax5': pl.Float64,
    'companyFinancialValue': pl.Utf8,
    'companyName': pl.Utf8,
    'companyType': pl.Utf8,
    'compressBillNo': pl.Utf8,
    'creditBillGeneratedYN': pl.Utf8,
    'creditBillNumber': pl.Float64,
    'creditCardTotal': pl.Float64,
    'customNumber1': pl.Utf8,
    'customNumber2': pl.Utf8,
    'customNumber3': pl.Utf8,
    'customNumber4': pl.Utf8,
    'customNumber5': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRunningTotal': pl.Float64,
    'deletedFlag': pl.Utf8,
    'deposit': pl.Float64,
    'depositReqReceiptNumber': pl.Float64,
    'documentCode': pl.Utf8,
    'documentType': pl.Utf8,
    'eArchiveEttnNumber': pl.Utf8,
    'eArchiveNumber': pl.Utf8,
    'eArchiveReportNo': pl.Utf8,
    'eArchiveStatus': pl.Utf8,
    'eInvoiceNumber': pl.Utf8,
    'eInvoiceStatus': pl.Utf8,
    'fiscalBillCheckDigit': pl.Float64,
    'fiscalBillGenerationDate': pl.Utf8,
    'fiscalBillGenerationTime': pl.Utf8,
    'fiscalBillNumber': pl.Utf8,
    'fiscalInvoiceCurrency': pl.Utf8,
    'fiscalInvoiceCurrencyRate': pl.Float64,
    'fiscalSessionNo': pl.Utf8,
    'fiscalUnitControlCode': pl.Utf8,
    'folioAddress': pl.Utf8,
    'folioAddressCorrectedYn': pl.Utf8,
    'folioAttachmentLinkId': pl.Float64,
    'folioAttachmentStatus': pl.Float64,
    'folioNo': pl.Float64,
    'folioStyle': pl.Utf8,
    'folioTaxSeqNumber': pl.Float64,
    'folioTime': pl.Utf8,
    'folioType': pl.Utf8,
    'folioType1': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'fullFolioNo': pl.Utf8,
    'hasWatermarkYn': pl.Utf8,
    'hotelName': pl.Utf8,
    'insTimestamp': pl.Utf8,
    'insertDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastSignature': pl.Utf8,
    'locationID': pl.Utf8,
    'nRBusinessID': pl.Utf8,
    'nafApeHotelCode': pl.Utf8,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount1': pl.Float64,
    'netAmount10': pl.Float64,
    'netAmount11': pl.Float64,
    'netAmount12': pl.Float64,
    'netAmount13': pl.Float64,
    'netAmount14': pl.Float64,
    'netAmount15': pl.Float64,
    'netAmount16': pl.Float64,
    'netAmount17': pl.Float64,
    'netAmount18': pl.Float64,
    'netAmount19': pl.Float64,
    'netAmount2': pl.Float64,
    'netAmount20': pl.Float64,
    'netAmount3': pl.Float64,
    'netAmount4': pl.Float64,
    'netAmount5': pl.Float64,
    'netAmount6': pl.Float64,
    'netAmount7': pl.Float64,
    'netAmount8': pl.Float64,
    'netAmount9': pl.Float64,
    'numberOfPages': pl.Float64,
    'operaFiscalFolioStatus': pl.Utf8,
    'organizationID': pl.Int64,
    'pageNumber': pl.Float64,
    'palmVideoFlag': pl.Utf8,
    'partnerFiscalFolioStatus': pl.Utf8,
    'payeeAddress': pl.Utf8,
    'payeeCountry': pl.Utf8,
    'payeeFirstName': pl.Utf8,
    'payeeLastName': pl.Utf8,
    'payeeName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'payeePostalCode': pl.Utf8,
    'payeeTaxID1': pl.Utf8,
    'payeeTaxID2': pl.Utf8,
    'payeeZipCode': pl.Utf8,
    'paymentDate': pl.Utf8,
    'perpetualAmount': pl.Float64,
    'pnet1Amt': pl.Float64,
    'pnet10Amt': pl.Float64,
    'pnet11Amt': pl.Float64,
    'pnet12Amt': pl.Float64,
    'pnet13Amt': pl.Float64,
    'pnet14Amt': pl.Float64,
    'pnet15Amt': pl.Float64,
    'pnet16Amt': pl.Float64,
    'pnet17Amt': pl.Float64,
    'pnet18Amt': pl.Float64,
    'pnet19Amt': pl.Float64,
    'pnet2Amt': pl.Float64,
    'pnet20Amt': pl.Float64,
    'pnet3Amt': pl.Float64,
    'pnet4Amt': pl.Float64,
    'pnet5Amt': pl.Float64,
    'pnet6Amt': pl.Float64,
    'pnet7Amt': pl.Float64,
    'pnet8Amt': pl.Float64,
    'pnet9Amt': pl.Float64,
    'postitSequenceNumber': pl.Float64,
    'postitYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printerQueueName': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'promotionalText1': pl.Utf8,
    'promotionalText2': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'propertyTaxNumber': pl.Utf8,
    'ptax1Amt': pl.Float64,
    'ptax10Amt': pl.Float64,
    'ptax11Amt': pl.Float64,
    'ptax12Amt': pl.Float64,
    'ptax13Amt': pl.Float64,
    'ptax14Amt': pl.Float64,
    'ptax15Amt': pl.Float64,
    'ptax16Amt': pl.Float64,
    'ptax17Amt': pl.Float64,
    'ptax18Amt': pl.Float64,
    'ptax19Amt': pl.Float64,
    'ptax2Amt': pl.Float64,
    'ptax20Amt': pl.Float64,
    'ptax3Amt': pl.Float64,
    'ptax4Amt': pl.Float64,
    'ptax5Amt': pl.Float64,
    'ptax6Amt': pl.Float64,
    'ptax7Amt': pl.Float64,
    'ptax8Amt': pl.Float64,
    'ptax9Amt': pl.Float64,
    'ptotNonrevNonTaxable': pl.Float64,
    'ptotNonrevTaxable': pl.Float64,
    'ptotRevNonTaxable': pl.Float64,
    'ptotRevTaxable': pl.Float64,
    'realPerpetualAmount': pl.Float64,
    'reservationNameId': pl.Float64,
    'resortCity': pl.Utf8,
    'resortCountry': pl.Utf8,
    'resortFullAddress': pl.Utf8,
    'resortZipcodeCode': pl.Utf8,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNumber': pl.Utf8,
    'seqNumber': pl.Float64,
    'signature': pl.Utf8,
    'signatureKeyVersion': pl.Utf8,
    'softwareVersion': pl.Utf8,
    'tax1RateType': pl.Utf8,
    'tax2RateType': pl.Utf8,
    'taxAmount1': pl.Float64,
    'taxAmount10': pl.Float64,
    'taxAmount11': pl.Float64,
    'taxAmount12': pl.Float64,
    'taxAmount13': pl.Float64,
    'taxAmount14': pl.Float64,
    'taxAmount15': pl.Float64,
    'taxAmount16': pl.Float64,
    'taxAmount17': pl.Float64,
    'taxAmount18': pl.Float64,
    'taxAmount19': pl.Float64,
    'taxAmount2': pl.Float64,
    'taxAmount20': pl.Float64,
    'taxAmount3': pl.Float64,
    'taxAmount4': pl.Float64,
    'taxAmount5': pl.Float64,
    'taxAmount6': pl.Float64,
    'taxAmount7': pl.Float64,
    'taxAmount8': pl.Float64,
    'taxAmount9': pl.Float64,
    'taxCode1': pl.Utf8,
    'taxCode10': pl.Utf8,
    'taxCode11': pl.Utf8,
    'taxCode12': pl.Utf8,
    'taxCode13': pl.Utf8,
    'taxCode14': pl.Utf8,
    'taxCode15': pl.Utf8,
    'taxCode16': pl.Utf8,
    'taxCode17': pl.Utf8,
    'taxCode18': pl.Utf8,
    'taxCode19': pl.Utf8,
    'taxCode2': pl.Utf8,
    'taxCode20': pl.Utf8,
    'taxCode3': pl.Utf8,
    'taxCode4': pl.Utf8,
    'taxCode5': pl.Utf8,
    'taxCode6': pl.Utf8,
    'taxCode7': pl.Utf8,
    'taxCode8': pl.Utf8,
    'taxCode9': pl.Utf8,
    'taxCodeDesc1': pl.Utf8,
    'taxCodeDesc10': pl.Utf8,
    'taxCodeDesc11': pl.Utf8,
    'taxCodeDesc12': pl.Utf8,
    'taxCodeDesc13': pl.Utf8,
    'taxCodeDesc14': pl.Utf8,
    'taxCodeDesc15': pl.Utf8,
    'taxCodeDesc16': pl.Utf8,
    'taxCodeDesc17': pl.Utf8,
    'taxCodeDesc18': pl.Utf8,
    'taxCodeDesc19': pl.Utf8,
    'taxCodeDesc2': pl.Utf8,
    'taxCodeDesc20': pl.Utf8,
    'taxCodeDesc3': pl.Utf8,
    'taxCodeDesc4': pl.Utf8,
    'taxCodeDesc5': pl.Utf8,
    'taxCodeDesc6': pl.Utf8,
    'taxCodeDesc7': pl.Utf8,
    'taxCodeDesc8': pl.Utf8,
    'taxCodeDesc9': pl.Utf8,
    'taxId': pl.Utf8,
    'taxRate1': pl.Float64,
    'taxRate10': pl.Float64,
    'taxRate11': pl.Float64,
    'taxRate12': pl.Float64,
    'taxRate13': pl.Float64,
    'taxRate14': pl.Float64,
    'taxRate15': pl.Float64,
    'taxRate16': pl.Float64,
    'taxRate17': pl.Float64,
    'taxRate18': pl.Float64,
    'taxRate19': pl.Float64,
    'taxRate2': pl.Float64,
    'taxRate20': pl.Float64,
    'taxRate3': pl.Float64,
    'taxRate4': pl.Float64,
    'taxRate5': pl.Float64,
    'taxRate6': pl.Float64,
    'taxRate7': pl.Float64,
    'taxRate8': pl.Float64,
    'taxRate9': pl.Float64,
    'tax10RateType': pl.Utf8,
    'tax11RateType': pl.Utf8,
    'tax12RateType': pl.Utf8,
    'tax13RateType': pl.Utf8,
    'tax14RateType': pl.Utf8,
    'tax15RateType': pl.Utf8,
    'tax16RateType': pl.Utf8,
    'tax17RateType': pl.Utf8,
    'tax18RateType': pl.Utf8,
    'tax19RateType': pl.Utf8,
    'tax20RateType': pl.Utf8,
    'tax3RateType': pl.Utf8,
    'tax4RateType': pl.Utf8,
    'tax5RateType': pl.Utf8,
    'tax6RateType': pl.Utf8,
    'tax7RateType': pl.Utf8,
    'tax8RateType': pl.Utf8,
    'tax9RateType': pl.Utf8,
    'terminal': pl.Utf8,
    'totalGrossAmount': pl.Float64,
    'totalNetAmount': pl.Float64,
    'totalNonRevenueNonTaxableAmount': pl.Float64,
    'totalNonRevenueTaxableAmount': pl.Float64,
    'totalNonTaxableAmount': pl.Float64,
    'totalNonTaxableRevenue': pl.Float64,
    'totalPaidOuts': pl.Float64,
    'totalTax': pl.Float64,
    'totalTaxableRevenue': pl.Float64,
    'transactLastSignatureHash': pl.Utf8,
    'transactSignatureHash': pl.Utf8,
    'transactSignatureKeyVersion': pl.Utf8,
    'transactionSignature': pl.Utf8,
    'trxServiceType': pl.Utf8,
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
    'updTimestamp': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userID': pl.Float64,
    'userName': pl.Utf8,
    'voidNumber': pl.Float64,
    'voidReason': pl.Utf8,
    'workingDocId': pl.Float64,
    'xnet1Amt': pl.Float64,
    'xnet10Amt': pl.Float64,
    'xnet11Amt': pl.Float64,
    'xnet12Amt': pl.Float64,
    'xnet13Amt': pl.Float64,
    'xnet14Amt': pl.Float64,
    'xnet15Amt': pl.Float64,
    'xnet16Amt': pl.Float64,
    'xnet17Amt': pl.Float64,
    'xnet18Amt': pl.Float64,
    'xnet19Amt': pl.Float64,
    'xnet2Amt': pl.Float64,
    'xnet20Amt': pl.Float64,
    'xnet3Amt': pl.Float64,
    'xnet4Amt': pl.Float64,
    'xnet5Amt': pl.Float64,
    'xnet6Amt': pl.Float64,
    'xnet7Amt': pl.Float64,
    'xnet8Amt': pl.Float64,
    'xnet9Amt': pl.Float64,
    'xtax1Amt': pl.Float64,
    'xtax10Amt': pl.Float64,
    'xtax11Amt': pl.Float64,
    'xtax12Amt': pl.Float64,
    'xtax13Amt': pl.Float64,
    'xtax14Amt': pl.Float64,
    'xtax15Amt': pl.Float64,
    'xtax16Amt': pl.Float64,
    'xtax17Amt': pl.Float64,
    'xtax18Amt': pl.Float64,
    'xtax19Amt': pl.Float64,
    'xtax2Amt': pl.Float64,
    'xtax20Amt': pl.Float64,
    'xtax3Amt': pl.Float64,
    'xtax4Amt': pl.Float64,
    'xtax5Amt': pl.Float64,
    'xtax6Amt': pl.Float64,
    'xtax7Amt': pl.Float64,
    'xtax8Amt': pl.Float64,
    'xtax9Amt': pl.Float64,
}
```
```python
financial_unified_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'accountCode': pl.Float64,
    'accountNumber': pl.Utf8,
    'addressId': pl.Float64,
    'advanceBillReversedYN': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYN': pl.Utf8,
    'advgenTtransCodeID': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'articleId': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'attachedToUser': pl.Utf8,
    'authEmployeeID': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCApproval': pl.Utf8,
    'cashierCode': pl.Float64,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierName': pl.Utf8,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'changesLogCheckIn': pl.Utf8,
    'changesLogCheckOut': pl.Utf8,
    'changesLogCloseFolio': pl.Utf8,
    'changesLogReopenFolio': pl.Utf8,
    'changesLogUpdateReservation': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'compressedYn': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'decimals': pl.Float64,
    'deferredYn': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'displayYN': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folio': pl.Float64,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioView': pl.Float64,
    'foreignCurrencyCode': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'generalCashierYN': pl.Utf8,
    'grossAmount': pl.Float64,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'interfaceCashierYN': pl.Utf8,
    'internalArticleid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'organizationID': pl.Int64,
    'originalARLedgerDebit': pl.Float64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'passerByName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'payeeResvNameID': pl.Float64,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postedAmountInTransactionCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'profileID': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYN': pl.Utf8,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationNameID': pl.Float64,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingCode': pl.Utf8,
    'routingCodeDescription': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingIinstructionID': pl.Float64,
    'routingInstrnId': pl.Float64,
    'routingType': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'supplement': pl.Utf8,
    'tRXCode': pl.Utf8,
    'targetResort': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transCodeArrangementID': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transferFromAccountID': pl.Float64,
    'transferToAccountID': pl.Float64,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatAmount': pl.Float64,
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