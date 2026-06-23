# ChangesLog
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `changesLog`
> Provides detailed information on actions and the users who completed the action including date time activity type and description. Also providing the capability to combine with reservation block and profile data
  
**Return:** [`[ChangesLogType]`](#changeslogtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ChangesLogQueryArgumentsType!`](#changeslogqueryargumentstype) |  |

## Object Types

### ChangesLogType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionDetails | [`ChangesLogActionDetailsType`](#changeslogactiondetailstype) | Action Details |
| 2 | actionGroupDetails | [`ChangesLogActionGroupDetailsType`](#changeslogactiongroupdetailstype) | Action Group Details |
| 3 | reservationDetails | [`ChangesLogReservationDetailsType`](#changeslogreservationdetailstype) | Reservation Details |
| 4 | blockDetails | [`ChangesLogBlockDetailsType`](#changeslogblockdetailstype) | Block |
| 5 | eventDetails | [`ChangesLogEventDetailsType`](#changeslogeventdetailstype) | Event Details |
| 6 | workOrdersDetails | [`ChangesLogWorkOrdersDetailsType`](#changeslogworkordersdetailstype) | Work Orders Details |
| 7 | profileAllInformationDetails | [`ChangesLogProfileAllInformationDetailsType`](#changeslogprofileallinformationdetailstype) | Profile All Details |
| 8 | propertyPropertyDetails | [`ChangesLogPropertyPropertyDetailsType`](#changeslogpropertypropertydetailstype) | Resort Details |
| 9 | changesLogRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ChangesLogActionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionDate | `Date` | Action Date |
| 2 | actionID | `Float` | Action ID |
| 3 | actionTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 4 | actionType | `String` | Action Type |
| 5 | activityID | `Float` | Activity ID that logs the changes. |
| 6 | blockID | `Float` | Block ID |
| 7 | bookId | `Float` | Book ID |
| 8 | cateringEventId | `Float` | OPERA Event ID. |
| 9 | chainCode | `String` | Chain Code |
| 10 | changeGroup | `String` | Change Group |
| 11 | commissionNameId | `Float` | Commission Name ID |
| 12 | commissionReservationNameId | `Float` | Commission Resv Name ID |
| 13 | configurationRateCode | `String` | Configuration Rate Code |
| 14 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 15 | deletedFlag | `String` | Deleted Flag |
| 16 | description | `String` | Description |
| 17 | eventID | `Float` | Event ID |
| 18 | financialActionId | `Float` | Action Id. |
| 19 | ipAddress | `String` | Ip Address |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | machine | `String` | Machine |
| 23 | menuId | `Float` | Menu ID |
| 24 | module | `String` | Module |
| 25 | moduleType | `String` | Module Type |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | parentActionInstanceId | `Float` | Parent Action Instance ID |
| 28 | permissionAppUserId | `Float` | The user ID to/from whom a permission was granted/revoked. |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | productId | `String` | Product ID |
| 31 | profileID | `Float` | Profile ID |
| 32 | property | `String` | Code to uniquely identify the Property |
| 33 | rateCategory | `String` | Rate Category |
| 34 | rateClass | `String` | Rate Class |
| 35 | rateCode | `String` | Rate Code |
| 36 | rateSetId | `Float` | Rate Set ID |
| 37 | reservationNameId | `Float` | Internal |
| 38 | resourceId | `Float` | Resource ID |
| 39 | restrictionId | `Float` | Internal restriction id |
| 40 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 41 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 42 | room | `String` | Room |
| 43 | roomCategory | `String` | Room Category |
| 44 | roomClass | `String` | Room Class |
| 45 | seasonCode | `String` | Season Code |
| 46 | serviceRequestId | `Float` | Sequence generated no Identifier for service request. |
| 47 | srNameId | `Float` | Sr Name ID |
| 48 | srReservationNameId | `Float` | Sr Resv Name ID |
| 49 | srRoom | `String` | Sr Room |
| 50 | terminal | `String` | Terminal |
| 51 | userID | `Float` | User ID |
| 52 | userName | `String` | User Name |
| 53 | yieldCategory | `String` | Yield Category |

[⬆ Back to Query](#query)

---

### ChangesLogActionGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionGroup | `String` | Action Group |

[⬆ Back to Query](#query)

---

### ChangesLogReservationDetailsType

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

### ChangesLogBlockDetailsType

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

### ChangesLogEventDetailsType

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

### ChangesLogWorkOrdersDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountAll | `String` | Account All |
| 2 | activityAmount | `Float` | Total amount for the specific Activity. |
| 3 | activityClass | `String` | Activity Class |
| 4 | activityCompleted | `String` | Activity Completed |
| 5 | activityCompletedBy | `String` | Activity Completed By |
| 6 | activityCompletionDate | `Float` | Activity Completion Date |
| 7 | activityCreatedBy | `String` | Activity Created By |
| 8 | activityCreatedOn | `DateTime` | Activity Created On |
| 9 | activityEndDate | `DateTime` | Activity End Date |
| 10 | activityID | `Float` | Activity ID |
| 11 | activityName | `String` | Description of the Problem reported |
| 12 | activityNotes | `String` | Activity Notes |
| 13 | activityOwnerCode | `DateTime` | Activity Owner Code |
| 14 | activityPriority | `String` | Activity Priority |
| 15 | activityResult | `String` | Activity Result |
| 16 | activityStartDate | `DateTime` | Activity Start Date |
| 17 | activityTraceCode | `String` | Activity Trace Code |
| 18 | activityType | `String` | Activity Type |
| 19 | activityTypeDescription | `String` | Activity Type Description |
| 20 | activityUpdatedBy | `String` | Activity Updated By |
| 21 | activityUpdatedOn | `DateTime` | Activity Updated On |
| 22 | activityUserNameID | `String` | Activity User Name ID |
| 23 | assignedBy | `Float` | User who assigned the task. |
| 24 | assignedOnDate | `DateTime` | Date on which this work order was assigned to someone else |
| 25 | attachmentLocation | `String` | Attachment Location |
| 26 | attachmentOwner | `String` | Owner who created this attachment. [ACCOUNT CONTACT ACTIVITY or BOOKING] |
| 27 | attendees | `Float` | Attendees |
| 28 | author | `Float` | Author |
| 29 | blockAll | `String` | Block All |
| 30 | cActivityAmount | `Float` | Central Activity Amount |
| 31 | cDepositAmount | `Float` | Central Deposit Amount |
| 32 | cEstCateringRevenue | `Float` | Central Est Cat Revenue |
| 33 | cEstOtherRevenue | `Float` | Central Est Other Revenue |
| 34 | cEstRoomRevenue | `Float` | Central Est Rm Revenue |
| 35 | cExchangeDate | `Date` | Central Xchange Date |
| 36 | cExchangeRate | `Float` | Central Xchange Rate |
| 37 | cTotalLaborCost | `Float` | Central Total Labor Cost |
| 38 | cTotalPartsCost | `Float` | Central Total Parts Cost |
| 39 | campaignStatusCode | `String` | Stores the status codes for Campaign Management |
| 40 | categoryCode | `String` | Category Code |
| 41 | centralActivityType | `String` | Central Activity Type |
| 42 | centralActivityTypeDescription | `String` | Central Activity Type Description |
| 43 | chainCode | `String` | Chain Code |
| 44 | completedBy | `Float` | Completed By |
| 45 | contactAll | `String` | Contact All |
| 46 | createdBy | `Float` | Created By |
| 47 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 48 | databaseId | `String` | Database ID |
| 49 | deletedFlag | `String` | Deleted Flag |
| 50 | dependingOnWoNumber | `Float` | This defines the oprder of execution between two sub work orders as one of them may be dependent on the other. |
| 51 | depositAmount | `Float` | Deposit Amount |
| 52 | depositOwner | `String` | Owner of the Deposit. It can be Opera (O) or Cencept (C). |
| 53 | deptOfAction | `String` | Dept to which the employee who created the work order belongs |
| 54 | downloadDate | `DateTime` | Download Date |
| 55 | downloadResort | `String` | Download Property |
| 56 | downloadSrep | `Float` | Download Srep |
| 57 | dueDate | `DateTime` | Due Date |
| 58 | endTime | `String` | End Time |
| 59 | estCatRevenue | `Float` | Estimated revenue. |
| 60 | estOtherRevenue | `Float` | Estimated others revenue. |
| 61 | estRoomNights | `Float` | Estimated room nights. |
| 62 | estRoomRevenue | `Float` | Estimated room revenue. |
| 63 | estTimeToComplete | `Float` | Time estimated to complete the work order |
| 64 | estUotCode | `String` | Est Uot Code |
| 65 | externalSystem | `String` | External System |
| 66 | externalSystemId | `String` | External System ID. |
| 67 | foRoomStatus | `String` | Room status at the tome of creation of work order if it happens to be in a room |
| 68 | fullName | `String` | Full Name |
| 69 | generatedByCampaign | `String` | Indicates if a Campain generated this activity. |
| 70 | generatedByFreqId | `Float` | The frequency ID which generated this activity. |
| 71 | globalYn | `String` | Global Y/N |
| 72 | guestOriginatedYn | `String` | Whether the work order is guest originated or not |
| 73 | guestRoomYn | `String` | Whether this location is a a guest room or not |
| 74 | guestType | `String` | Guest Type |
| 75 | highPriorityYn | `String` | Whether the work order is having high priority or not. |
| 76 | inactiveDate | `DateTime` | Inactive Date |
| 77 | insertDate | `DateTime` | Insert Date |
| 78 | insertUser | `Float` | Insert User |
| 79 | internalYn | `String` | Internal Y/N |
| 80 | jRNUpdateDate | `Date` | JRN Update Date |
| 81 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 82 | laptopChange | `Float` | Laptop Change |
| 83 | locationCode | `String` | Location Code |
| 84 | locationID | `String` | Internal ID to uniquely identify the Property |
| 85 | masterSub | `String` | Decides whether a particular workorder is a master or sub or none. |
| 86 | minutesBeforeAlert | `Float` | Number of minutes before the activity start time when the alert will be raised. (Default value) |
| 87 | nameID | `Float` | Name ID |
| 88 | notifiedYn | `String` | Has the user been notified about this activity ? |
| 89 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 90 | origWoNumber | `Float` | Stores the original WORK_NUMBER prior to a migration. |
| 91 | ownerEmail | `String` | Owner Email |
| 92 | ownerPhone | `String` | Phone no. |
| 93 | ownerTitle | `String` | Owner Title |
| 94 | parentWoNumber | `Float` | Wo_number to which current work order is a sub work ordergenerated work_order number |
| 95 | plantItemCode | `String` | Plant Item Code |
| 96 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 97 | priorityChangedYn | `String` | Whether the priority was manually changed or not |
| 98 | privateYn | `String` | Private Y/N |
| 99 | property | `String` | Code to uniquely identify the Property |
| 100 | proposalSentDate | `DateTime` | Proposal Sent Date |
| 101 | proposalViewToken | `String` | Proposal View Token |
| 102 | reasonCode | `String` | Reason Code |
| 103 | releasedBy | `Float` | Emp number of the person who has released this workorder |
| 104 | releasedDate | `DateTime` | Date on which a work orderwas released |
| 105 | requestTemplateId | `Float` | Stores the request template ID for Campaign Management. |
| 106 | requestTypeId | `String` | Request type that need to be generated. |
| 107 | requestTypeTemplatesId | `Float` | Stores the Campaign Type Template ID used for a campaign. |
| 108 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 109 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 110 | room | `String` | Room |
| 111 | sendMethod | `String` | Default method for sending a Request Type. |
| 112 | showOn | `DateTime` | Scheduled workorder .reminder to display on date |
| 113 | startTime | `String` | Start Time |
| 114 | statusCode | `String` | Status Code |
| 115 | surveyId | `Float` | Linked Survey ID |
| 116 | takenBy | `Float` | Empnumber of the person who has accepted this workorder |
| 117 | takenDate | `DateTime` | Date on which an employee has accepted this workorder |
| 118 | taskCode | `Float` | Task Code |
| 119 | taskitemNumber | `Float` | Taskitem Number |
| 120 | timezoneConvertedYn | `String` | Indicated if the activity times are converted to database time zone. |
| 121 | totalLaborCost | `Float` | Calculated Labor cost spent for this workorder |
| 122 | totalPartsCost | `Float` | Calculate total parts cost spent for this workorder |
| 123 | typeCode | `String` | Type Code |
| 124 | updateUser | `Float` | Update User |
| 125 | uploadDate | `DateTime` | Upload Date |
| 126 | userExt | `String` | Extension of the user |

[⬆ Back to Query](#query)

---

### ChangesLogProfileAllInformationDetailsType

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

### ChangesLogPropertyPropertyDetailsType

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

### ChangesLogQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| actionDetailsInsertDate | `DateInput!` | Action Date<br>`@mandatoryInput` |
| actionDetailsActionId | `FloatInput` | Action ID |
| actionDetailsActionType | `StringInput` | Action Type |
| actionDetailsActivityId | `FloatInput` | Activity ID that logs the changes. |
| actionDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| actionDetailsBookId | `FloatInput` | Book ID |
| actionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| actionDetailsEventId | `FloatInput` | Event ID |
| actionDetailsFinActionId | `FloatInput` | Action Id. |
| actionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| actionDetailsModuleType | `StringInput` | Module Type |
| actionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| actionDetailsParentActionInstanceId | `FloatInput` | Parent Action Instance ID |
| actionDetailsNameId | `FloatInput` | Profile ID |
| actionDetailsRateCode | `StringInput` | Rate Code |
| reservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |
| reservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |
| reservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| reservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationDetailsAllotmentid | `FloatInput` | Block ID |
| reservationDetailsTruncBeginDate | `DateInput` | Arrival Date |
| reservationDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| reservationDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| reservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| reservationDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationDetailsChainCode | `StringInput` | Chain Code |
| reservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| reservationDetailsCreditCardId | `FloatInput` | Credit Card ID |
| reservationDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationDetailsTruncEndDate | `DateInput` | Departure Date |
| reservationDetailsEnddatetime | `DateTimeInput` | End Datetime |
| reservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| reservationDetailsEventId | `FloatInput` | Event ID |
| reservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| reservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| reservationDetailsInsertDate | `DateTimeInput` | Insert Date |
| reservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| reservationDetailsInsertUser | `FloatInput` | Insert User |
| reservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationDetailsEndDate | `DateTimeInput` | Linked Departure Date |
| reservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationDetailsParentreservationid | `FloatInput` | Parentreservationid |
| reservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationDetailsResvNameId | `FloatInput` | Reservation Name ID |
| reservationDetailsResvStatus | `StringInput` | Reservation Status |
| reservationDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationDetailsReservationid | `FloatInput` | Reservationid |
| reservationDetailsResort | `StringInput` | Property |
| reservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationDetailsResvNameid | `FloatInput` | Reservation Nameid |
| reservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| reservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| reservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| reservationDetailsRoomCategory | `StringInput` | Room Category |
| reservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| reservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationDetailsSguestName | `StringInput` | Sguest Name |
| reservationDetailsNameId | `FloatInput` | Shared Profile ID |
| reservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| reservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |
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
| workordersDetailsCompletedYn | `StringInput` | Activity Completed |
| workordersDetailsCreatedDate | `DateTimeInput` | Activity Created On |
| workordersDetailsEndDate | `DateTimeInput` | Activity End Date |
| workordersDetailsWoNumber | `FloatInput` | Activity ID |
| workordersDetailsProblemDesc | `StringInput` | Description of the Problem reported |
| workordersDetailsPriorityCode | `StringInput` | Activity Priority |
| workordersDetailsStartDate | `DateTimeInput` | Activity Start Date |
| workordersDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| workordersDetailsEstUotCode | `StringInput` | Est Uot Code |
| workordersDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| workordersDetailsLocationCode | `StringInput` | Location Code |
| workordersDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| workordersDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| workordersDetailsParentWoNumber | `FloatInput` | Wo_number to which current work order is a sub work ordergenerated work_order number |
| workordersDetailsPlantItemCode | `StringInput` | Plant Item Code |
| workordersDetailsResort | `StringInput` | Code to uniquely identify the Property |
| workordersDetailsReasonCode | `StringInput` | Reason Code |
| workordersDetailsRequestTypeId | `StringInput` | Request type that need to be generated. |
| workordersDetailsRequestTypeTemplatesId | `FloatInput` | Stores the Campaign Type Template ID used for a campaign. |
| workordersDetailsStatusCode | `StringInput` | Status Code |
| workordersDetailsSurveyId | `FloatInput` | Linked Survey ID |
| workordersDetailsTaskCode | `FloatInput` | Task Code |
| workordersDetailsTaskitemNumber | `FloatInput` | Taskitem Number |
| workordersDetailsTypeCode | `StringInput` | Type Code |
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

**`mandatoryInput`**
- actionDetailsInsertDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query changesLog($input: ChangesLogQueryArgumentsType!) {
  changesLog(input: $input) @stream {
    actionDetails {
      actionDate
      actionID
      actionTime
      actionType
      activityID
      blockID
      bookId
      cateringEventId
      chainCode
      changeGroup
      commissionNameId
      commissionReservationNameId
      configurationRateCode
      dSI
      deletedFlag
      description
      eventID
      financialActionId
      ipAddress
      jRNUpdateDate
      jRNUpdateDateAndTime
      machine
      menuId
      module
      moduleType
      organizationID
      parentActionInstanceId
      permissionAppUserId
      primaryKeyID
      productId
      profileID
      property
      rateCategory
      rateClass
      rateCode
      rateSetId
      reservationNameId
      resourceId
      restrictionId
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      seasonCode
      serviceRequestId
      srNameId
      srReservationNameId
      srRoom
      terminal
      userID
      userName
      yieldCategory
    }
    actionGroupDetails {
      actionGroup
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
    workOrdersDetails {
      accountAll
      activityAmount
      activityClass
      activityCompleted
      activityCompletedBy
      activityCompletionDate
      activityCreatedBy
      activityCreatedOn
      activityEndDate
      activityID
      activityName
      activityNotes
      activityOwnerCode
      activityPriority
      activityResult
      activityStartDate
      activityTraceCode
      activityType
      activityTypeDescription
      activityUpdatedBy
      activityUpdatedOn
      activityUserNameID
      assignedBy
      assignedOnDate
      attachmentLocation
      attachmentOwner
      attendees
      author
      blockAll
      cActivityAmount
      cDepositAmount
      cEstCateringRevenue
      cEstOtherRevenue
      cEstRoomRevenue
      cExchangeDate
      cExchangeRate
      cTotalLaborCost
      cTotalPartsCost
      campaignStatusCode
      categoryCode
      centralActivityType
      centralActivityTypeDescription
      chainCode
      completedBy
      contactAll
      createdBy
      dSI
      databaseId
      deletedFlag
      dependingOnWoNumber
      depositAmount
      depositOwner
      deptOfAction
      downloadDate
      downloadResort
      downloadSrep
      dueDate
      endTime
      estCatRevenue
      estOtherRevenue
      estRoomNights
      estRoomRevenue
      estTimeToComplete
      estUotCode
      externalSystem
      externalSystemId
      foRoomStatus
      fullName
      generatedByCampaign
      generatedByFreqId
      globalYn
      guestOriginatedYn
      guestRoomYn
      guestType
      highPriorityYn
      inactiveDate
      insertDate
      insertUser
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationCode
      locationID
      masterSub
      minutesBeforeAlert
      nameID
      notifiedYn
      organizationID
      origWoNumber
      ownerEmail
      ownerPhone
      ownerTitle
      parentWoNumber
      plantItemCode
      primaryKeyID
      priorityChangedYn
      privateYn
      property
      proposalSentDate
      proposalViewToken
      reasonCode
      releasedBy
      releasedDate
      requestTemplateId
      requestTypeId
      requestTypeTemplatesId
      rnaInsertDate
      rnaUpdateDate
      room
      sendMethod
      showOn
      startTime
      statusCode
      surveyId
      takenBy
      takenDate
      taskCode
      taskitemNumber
      timezoneConvertedYn
      totalLaborCost
      totalPartsCost
      typeCode
      updateUser
      uploadDate
      userExt
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
action_details_schema = {
    'actionDate': pl.Utf8,
    'actionID': pl.Float64,
    'actionTime': pl.Utf8,
    'actionType': pl.Utf8,
    'activityID': pl.Float64,
    'blockID': pl.Float64,
    'bookId': pl.Float64,
    'cateringEventId': pl.Float64,
    'chainCode': pl.Utf8,
    'changeGroup': pl.Utf8,
    'commissionNameId': pl.Float64,
    'commissionReservationNameId': pl.Float64,
    'configurationRateCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'eventID': pl.Float64,
    'financialActionId': pl.Float64,
    'ipAddress': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'machine': pl.Utf8,
    'menuId': pl.Float64,
    'module': pl.Utf8,
    'moduleType': pl.Utf8,
    'organizationID': pl.Int64,
    'parentActionInstanceId': pl.Float64,
    'permissionAppUserId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'productId': pl.Utf8,
    'profileID': pl.Float64,
    'property': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateSetId': pl.Float64,
    'reservationNameId': pl.Float64,
    'resourceId': pl.Float64,
    'restrictionId': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'seasonCode': pl.Utf8,
    'serviceRequestId': pl.Float64,
    'srNameId': pl.Float64,
    'srReservationNameId': pl.Float64,
    'srRoom': pl.Utf8,
    'terminal': pl.Utf8,
    'userID': pl.Float64,
    'userName': pl.Utf8,
    'yieldCategory': pl.Utf8,
}
```
```python
action_group_details_schema = {
    'actionGroup': pl.Utf8,
}
```
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
work_orders_details_schema = {
    'accountAll': pl.Utf8,
    'activityAmount': pl.Float64,
    'activityClass': pl.Utf8,
    'activityCompleted': pl.Utf8,
    'activityCompletedBy': pl.Utf8,
    'activityCompletionDate': pl.Float64,
    'activityCreatedBy': pl.Utf8,
    'activityCreatedOn': pl.Utf8,
    'activityEndDate': pl.Utf8,
    'activityID': pl.Float64,
    'activityName': pl.Utf8,
    'activityNotes': pl.Utf8,
    'activityOwnerCode': pl.Utf8,
    'activityPriority': pl.Utf8,
    'activityResult': pl.Utf8,
    'activityStartDate': pl.Utf8,
    'activityTraceCode': pl.Utf8,
    'activityType': pl.Utf8,
    'activityTypeDescription': pl.Utf8,
    'activityUpdatedBy': pl.Utf8,
    'activityUpdatedOn': pl.Utf8,
    'activityUserNameID': pl.Utf8,
    'assignedBy': pl.Float64,
    'assignedOnDate': pl.Utf8,
    'attachmentLocation': pl.Utf8,
    'attachmentOwner': pl.Utf8,
    'attendees': pl.Float64,
    'author': pl.Float64,
    'blockAll': pl.Utf8,
    'cActivityAmount': pl.Float64,
    'cDepositAmount': pl.Float64,
    'cEstCateringRevenue': pl.Float64,
    'cEstOtherRevenue': pl.Float64,
    'cEstRoomRevenue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cTotalLaborCost': pl.Float64,
    'cTotalPartsCost': pl.Float64,
    'campaignStatusCode': pl.Utf8,
    'categoryCode': pl.Utf8,
    'centralActivityType': pl.Utf8,
    'centralActivityTypeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'completedBy': pl.Float64,
    'contactAll': pl.Utf8,
    'createdBy': pl.Float64,
    'dSI': pl.Int64,
    'databaseId': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'dependingOnWoNumber': pl.Float64,
    'depositAmount': pl.Float64,
    'depositOwner': pl.Utf8,
    'deptOfAction': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'endTime': pl.Utf8,
    'estCatRevenue': pl.Float64,
    'estOtherRevenue': pl.Float64,
    'estRoomNights': pl.Float64,
    'estRoomRevenue': pl.Float64,
    'estTimeToComplete': pl.Float64,
    'estUotCode': pl.Utf8,
    'externalSystem': pl.Utf8,
    'externalSystemId': pl.Utf8,
    'foRoomStatus': pl.Utf8,
    'fullName': pl.Utf8,
    'generatedByCampaign': pl.Utf8,
    'generatedByFreqId': pl.Float64,
    'globalYn': pl.Utf8,
    'guestOriginatedYn': pl.Utf8,
    'guestRoomYn': pl.Utf8,
    'guestType': pl.Utf8,
    'highPriorityYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSub': pl.Utf8,
    'minutesBeforeAlert': pl.Float64,
    'nameID': pl.Float64,
    'notifiedYn': pl.Utf8,
    'organizationID': pl.Int64,
    'origWoNumber': pl.Float64,
    'ownerEmail': pl.Utf8,
    'ownerPhone': pl.Utf8,
    'ownerTitle': pl.Utf8,
    'parentWoNumber': pl.Float64,
    'plantItemCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'priorityChangedYn': pl.Utf8,
    'privateYn': pl.Utf8,
    'property': pl.Utf8,
    'proposalSentDate': pl.Utf8,
    'proposalViewToken': pl.Utf8,
    'reasonCode': pl.Utf8,
    'releasedBy': pl.Float64,
    'releasedDate': pl.Utf8,
    'requestTemplateId': pl.Float64,
    'requestTypeId': pl.Utf8,
    'requestTypeTemplatesId': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'sendMethod': pl.Utf8,
    'showOn': pl.Utf8,
    'startTime': pl.Utf8,
    'statusCode': pl.Utf8,
    'surveyId': pl.Float64,
    'takenBy': pl.Float64,
    'takenDate': pl.Utf8,
    'taskCode': pl.Float64,
    'taskitemNumber': pl.Float64,
    'timezoneConvertedYn': pl.Utf8,
    'totalLaborCost': pl.Float64,
    'totalPartsCost': pl.Float64,
    'typeCode': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'userExt': pl.Utf8,
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