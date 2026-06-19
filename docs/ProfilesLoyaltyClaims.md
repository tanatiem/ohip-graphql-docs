# ProfilesLoyaltyClaims
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesLoyaltyClaims`
> Detailed information on the Loyalty Program providing details on the Membership Profiles Stay Information and the ability to track Claims.
  
**Return:** [`[ProfilesLoyaltyClaimsType]`](#profilesloyaltyclaimstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesLoyaltyClaimsQueryArgumentsType!`](#profilesloyaltyclaimsqueryargumentstype) |  |

## Object Types

### ProfilesLoyaltyClaimsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | membershipClaimDetails | [`ProfilesLoyaltyClaimsMembershipClaimDetailsType`](#profilesloyaltyclaimsmembershipclaimdetailstype) | Membership Claim Details |
| 2 | rateCodeDetails | [`ProfilesLoyaltyClaimsRateCodeDetailsType`](#profilesloyaltyclaimsratecodedetailstype) | Rate Code Details |
| 3 | marketDetails | [`ProfilesLoyaltyClaimsMarketDetailsType`](#profilesloyaltyclaimsmarketdetailstype) | Market Details |
| 4 | sourceTableDetails | [`ProfilesLoyaltyClaimsSourceTableDetailsType`](#profilesloyaltyclaimssourcetabledetailstype) | Source Table Details |
| 5 | reservationPromotionsDetails | [`ProfilesLoyaltyClaimsReservationPromotionsDetailsType`](#profilesloyaltyclaimsreservationpromotionsdetailstype) | Reservation Promotions Details |
| 6 | roomDetails | [`ProfilesLoyaltyClaimsRoomDetailsType`](#profilesloyaltyclaimsroomdetailstype) | Room Details |
| 7 | membershipClaimsHistoryDetails | [`ProfilesLoyaltyClaimsMembershipClaimsHistoryDetailsType`](#profilesloyaltyclaimsmembershipclaimshistorydetailstype) | Membership Claims History Details |
| 8 | channelDetails | [`ProfilesLoyaltyClaimsChannelDetailsType`](#profilesloyaltyclaimschanneldetailstype) | Channel Details |
| 9 | profilesLoyaltyClaimsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsMembershipClaimDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | approvalStatus | `String` | Approval Status |
| 2 | approveReject | `String` | Approve/Reject/None |
| 3 | arrivalDate | `Date` | Arrival Date |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | cMembershipBaseRevenue | `Float` | Central Membership Base Revenue |
| 7 | cMembershipBonusRevenue | `Float` | Central Membership Bonus Revenue |
| 8 | callerInformation | `String` | Information about the caller. |
| 9 | callerName | `String` | name of the person who called. |
| 10 | chainCode | `String` | Chain Code |
| 11 | channel | `String` | Channel |
| 12 | claimAdjLimitCode | `String` | Claim Adj Limit Code |
| 13 | claimDate | `Date` | Date claim was posted in the database. |
| 14 | claimNumber | `Float` | Primary key. |
| 15 | claimOrigin | `String` | User defined origin of claim. |
| 16 | claimOwner | `Float` | Claim Owner |
| 17 | claimSource | `String` | Source of the Claim |
| 18 | claimStatus | `String` | Status of the claim. |
| 19 | claimType | `String` | User Defined Claim Types |
| 20 | closeDate | `Date` | Date and time cashier was closed. |
| 21 | comments | `String` | Comments |
| 22 | confirmationNumber | `String` | Confirmation Number |
| 23 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 24 | deletedFlag | `String` | Deleted Flag |
| 25 | departureDate | `Date` | Departure Date |
| 26 | externalReferenceNumber | `String` | External Reference Number |
| 27 | insertDate | `DateTime` | Insert Date |
| 28 | insertUser | `Float` | Insert User |
| 29 | jRNUpdateDate | `Date` | JRN Update Date |
| 30 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 31 | marketCode | `String` | Market Code |
| 32 | membershipBaseNights | `Float` | Membership Base Nights |
| 33 | membershipBaseRevenue | `Float` | Membership Base Revenue |
| 34 | membershipBaseStay | `Float` | Membership Base Stay |
| 35 | membershipBonusNights | `Float` | Membership Bonus Nights |
| 36 | membershipBonusRevenue | `Float` | Membership Bonus Revenue |
| 37 | membershipBonusStay | `Float` | Membership Bonus Stay |
| 38 | membershipClaimProperty | `String` | Membership Claim Property |
| 39 | membershipId | `Float` | Membership ID |
| 40 | membershipNumber | `String` | Membership Number |
| 41 | membershipTransactionId | `Float` | Membership Trx ID |
| 42 | membershipType | `String` | Membership Type |
| 43 | name | `String` | Name |
| 44 | nameId | `Float` | Name ID |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | originOfBooking | `String` | Origin of Booking |
| 47 | owner | `String` | Owner |
| 48 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 49 | purposeOfStay | `String` | Purpose of stay. |
| 50 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 51 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 52 | rateCode | `String` | Rate Code |
| 53 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 54 | recordType | `String` | Record Type |
| 55 | replyBy | `Date` | Date when the user gets a response to his/her claim. |
| 56 | reservationNameID | `Float` | Reservation Name ID |
| 57 | reservationStatus | `String` | Reservation Status |
| 58 | room | `String` | Room |
| 59 | submitter | `String` | Submitter |
| 60 | totalBasePoints | `Float` | Total Base Points |
| 61 | totalBonusPoints | `Float` | Total Bonus Points |
| 62 | totalMiscPoints | `Float` | Total Miscellaneous Points |
| 63 | updateDate | `DateTime` | Update Date |
| 64 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsRateCodeDetailsType

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

### ProfilesLoyaltyClaimsMarketDetailsType

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

### ProfilesLoyaltyClaimsSourceTableDetailsType

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

### ProfilesLoyaltyClaimsReservationPromotionsDetailsType

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

### ProfilesLoyaltyClaimsRoomDetailsType

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

### ProfilesLoyaltyClaimsMembershipClaimsHistoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activity | `String` | Code to indicate the activity ocuured in the transaction (i.e. OPEN CLOSE) |
| 2 | chainCode | `String` | Chain Code |
| 3 | comments | `String` | Comments |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | date | `Date` | Date claim was posted in the database. |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | membershipClaimId | `Float` | Primary key. |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | sequence | `Float` | Sequence |
| 17 | submitter | `String` | The name of the user who created the record. |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsChannelDetailsType

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

### ProfilesLoyaltyClaimsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| membershipclaimDetailsApprovalStatus | `StringInput` | Approval Status |
| membershipclaimDetailsApproveReject | `StringInput` | Approve/Reject/None |
| membershipclaimDetailsArrivalDate | `DateInput` | Arrival Date |
| membershipclaimDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershipclaimDetailsCallerInformation | `StringInput` | Information about the caller. |
| membershipclaimDetailsCallerName | `StringInput` | name of the person who called. |
| membershipclaimDetailsChainCode | `StringInput` | Chain Code |
| membershipclaimDetailsChannel | `StringInput` | Channel |
| membershipclaimDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |
| membershipclaimDetailsClaimDate | `DateInput!` | Date claim was posted in the database.<br>`@mandatoryInput` |
| membershipclaimDetailsMembershipClaimId | `FloatInput` | Primary key. |
| membershipclaimDetailsClaimOrigin | `StringInput` | User defined origin of claim. |
| membershipclaimDetailsClaimSource | `StringInput` | Source of the Claim |
| membershipclaimDetailsClaimStatus | `StringInput` | Status of the claim. |
| membershipclaimDetailsClaimType | `StringInput` | User Defined Claim Types |
| membershipclaimDetailsCloseDate | `DateInput` | Date and time cashier was closed. |
| membershipclaimDetailsComments | `StringInput` | Comments |
| membershipclaimDetailsPmsResvNo | `StringInput` | Confirmation Number |
| membershipclaimDetailsDeletedFlag | `StringInput` | Deleted Flag |
| membershipclaimDetailsDepartureDate | `DateInput` | Departure Date |
| membershipclaimDetailsCrsBookNo | `StringInput` | External Reference Number |
| membershipclaimDetailsInsertDate | `DateTimeInput` | Insert Date |
| membershipclaimDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipclaimDetailsMarketCode | `StringInput` | Market Code |
| membershipclaimDetailsResort | `StringInput!` | Membership Claim Property<br>`@mandatoryInput` |
| membershipclaimDetailsMembershipId | `FloatInput` | Membership ID |
| membershipclaimDetailsMembershipCardNo | `StringInput` | Membership Number |
| membershipclaimDetailsMembershipTrxId | `FloatInput` | Membership Trx ID |
| membershipclaimDetailsMembershipType | `StringInput` | Membership Type |
| membershipclaimDetailsName | `StringInput` | Name |
| membershipclaimDetailsNameId | `FloatInput` | Name ID |
| membershipclaimDetailsOriginOfBooking | `StringInput` | Origin of Booking |
| membershipclaimDetailsClaimOwnerName | `StringInput` | Owner |
| membershipclaimDetailsPurposeOfStay | `StringInput` | Purpose of stay. |
| membershipclaimDetailsRateCode | `StringInput` | Rate Code |
| membershipclaimDetailsRecordType | `StringInput` | Record Type |
| membershipclaimDetailsReplyByDate | `DateInput` | Date when the user gets a response to his/her claim. |
| membershipclaimDetailsResvStatus | `StringInput` | Reservation Status |
| membershipclaimDetailsRoom | `StringInput` | Room |
| membershipclaimDetailsSubmitter | `StringInput` | Submitter |
| membershipclaimDetailsUpdateDate | `DateTimeInput` | Update Date |
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
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
| sourcetableDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sourcetableDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sourcetableDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| sourcetableDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sourcetableDetailsResort | `StringInput` | Property |
| sourcetableDetailsSourceCode | `StringInput` | Source Code |
| sourcetableDetailsSourceid | `StringInput` | Sourceid |
| reservationpromotionsDetailsBasedOnRule | `StringInput` | Based On Rule |
| reservationpromotionsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationpromotionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationpromotionsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationpromotionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationpromotionsDetailsPromoCode | `StringInput` | Promotion Code |
| reservationpromotionsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| reservationpromotionsDetailsResvNameId | `FloatInput` | Resv Name ID |
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
| membershipclaimshistoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| channelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| channelDetailsEntityName | `StringInput` | Entity Name |
| channelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| channelDetailsLanguageCode | `StringInput` | Language Code |
| channelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| channelDetailsAttributeCode | `StringInput` | Origin Code |
| channelDetailsTitleSuffix | `FloatInput` | Title Suffix |
#### Validation Rules

**`mandatoryInput`**
- membershipclaimDetailsClaimDate
- membershipclaimDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesLoyaltyClaims($input: ProfilesLoyaltyClaimsQueryArgumentsType!) {
  profilesLoyaltyClaims(input: $input) @stream {
    membershipClaimDetails {
      approvalStatus
      approveReject
      arrivalDate
      cExchangeDate
      cExchangeRate
      cMembershipBaseRevenue
      cMembershipBonusRevenue
      callerInformation
      callerName
      chainCode
      channel
      claimAdjLimitCode
      claimDate
      claimNumber
      claimOrigin
      claimOwner
      claimSource
      claimStatus
      claimType
      closeDate
      comments
      confirmationNumber
      dSI
      deletedFlag
      departureDate
      externalReferenceNumber
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketCode
      membershipBaseNights
      membershipBaseRevenue
      membershipBaseStay
      membershipBonusNights
      membershipBonusRevenue
      membershipBonusStay
      membershipClaimProperty
      membershipId
      membershipNumber
      membershipTransactionId
      membershipType
      name
      nameId
      organizationID
      originOfBooking
      owner
      primaryKeyID
      purposeOfStay
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateTier
      recordType
      replyBy
      reservationNameID
      reservationStatus
      room
      submitter
      totalBasePoints
      totalBonusPoints
      totalMiscPoints
      updateDate
      updateUser
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
    membershipClaimsHistoryDetails {
      activity
      chainCode
      comments
      dSI
      date
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipClaimId
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      sequence
      submitter
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
membership_claim_details_schema = {
    'approvalStatus': pl.Utf8,
    'approveReject': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMembershipBaseRevenue': pl.Float64,
    'cMembershipBonusRevenue': pl.Float64,
    'callerInformation': pl.Utf8,
    'callerName': pl.Utf8,
    'chainCode': pl.Utf8,
    'channel': pl.Utf8,
    'claimAdjLimitCode': pl.Utf8,
    'claimDate': pl.Utf8,
    'claimNumber': pl.Float64,
    'claimOrigin': pl.Utf8,
    'claimOwner': pl.Float64,
    'claimSource': pl.Utf8,
    'claimStatus': pl.Utf8,
    'claimType': pl.Utf8,
    'closeDate': pl.Utf8,
    'comments': pl.Utf8,
    'confirmationNumber': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'departureDate': pl.Utf8,
    'externalReferenceNumber': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketCode': pl.Utf8,
    'membershipBaseNights': pl.Float64,
    'membershipBaseRevenue': pl.Float64,
    'membershipBaseStay': pl.Float64,
    'membershipBonusNights': pl.Float64,
    'membershipBonusRevenue': pl.Float64,
    'membershipBonusStay': pl.Float64,
    'membershipClaimProperty': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipNumber': pl.Utf8,
    'membershipTransactionId': pl.Float64,
    'membershipType': pl.Utf8,
    'name': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'originOfBooking': pl.Utf8,
    'owner': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'purposeOfStay': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateTier': pl.Float64,
    'recordType': pl.Utf8,
    'replyBy': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'room': pl.Utf8,
    'submitter': pl.Utf8,
    'totalBasePoints': pl.Float64,
    'totalBonusPoints': pl.Float64,
    'totalMiscPoints': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
membership_claims_history_details_schema = {
    'activity': pl.Utf8,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'date': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipClaimId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'submitter': pl.Utf8,
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