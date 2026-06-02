# ProfilesLoyaltyClaims
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| membershipClaimDetails | [`ProfilesLoyaltyClaimsMembershipClaimDetailsType`](#profilesloyaltyclaimsmembershipclaimdetailstype) | Membership Claim Details |
| rateCodeDetails | [`ProfilesLoyaltyClaimsRateCodeDetailsType`](#profilesloyaltyclaimsratecodedetailstype) | Rate Code Details |
| marketDetails | [`ProfilesLoyaltyClaimsMarketDetailsType`](#profilesloyaltyclaimsmarketdetailstype) | Market Details |
| sourceTableDetails | [`ProfilesLoyaltyClaimsSourceTableDetailsType`](#profilesloyaltyclaimssourcetabledetailstype) | Source Table Details |
| reservationPromotionsDetails | [`ProfilesLoyaltyClaimsReservationPromotionsDetailsType`](#profilesloyaltyclaimsreservationpromotionsdetailstype) | Reservation Promotions Details |
| roomDetails | [`ProfilesLoyaltyClaimsRoomDetailsType`](#profilesloyaltyclaimsroomdetailstype) | Room Details |
| membershipClaimsHistoryDetails | [`ProfilesLoyaltyClaimsMembershipClaimsHistoryDetailsType`](#profilesloyaltyclaimsmembershipclaimshistorydetailstype) | Membership Claims History Details |
| channelDetails | [`ProfilesLoyaltyClaimsChannelDetailsType`](#profilesloyaltyclaimschanneldetailstype) | Channel Details |
| profilesLoyaltyClaimsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsMembershipClaimDetailsType

| Field | Type | Description |
| --- | --- | --- |
| approvalStatus | `String` | Approval Status |
| approveReject | `String` | Approve/Reject/None |
| arrivalDate | `Date` | Arrival Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMembershipBaseRevenue | `Float` | Central Membership Base Revenue |
| cMembershipBonusRevenue | `Float` | Central Membership Bonus Revenue |
| callerInformation | `String` | Information about the caller. |
| callerName | `String` | name of the person who called. |
| chainCode | `String` | Chain Code |
| channel | `String` | Channel |
| claimAdjLimitCode | `String` | Claim Adj Limit Code |
| claimDate | `Date` | Date claim was posted in the database. |
| claimNumber | `Float` | Primary key. |
| claimOrigin | `String` | User defined origin of claim. |
| claimOwner | `Float` | Claim Owner |
| claimSource | `String` | Source of the Claim |
| claimStatus | `String` | Status of the claim. |
| claimType | `String` | User Defined Claim Types |
| closeDate | `Date` | Date and time cashier was closed. |
| comments | `String` | Comments |
| confirmationNumber | `String` | Confirmation Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| departureDate | `Date` | Departure Date |
| externalReferenceNumber | `String` | External Reference Number |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketCode | `String` | Market Code |
| membershipBaseNights | `Float` | Membership Base Nights |
| membershipBaseRevenue | `Float` | Membership Base Revenue |
| membershipBaseStay | `Float` | Membership Base Stay |
| membershipBonusNights | `Float` | Membership Bonus Nights |
| membershipBonusRevenue | `Float` | Membership Bonus Revenue |
| membershipBonusStay | `Float` | Membership Bonus Stay |
| membershipClaimProperty | `String` | Membership Claim Property |
| membershipId | `Float` | Membership ID |
| membershipNumber | `String` | Membership Number |
| membershipTransactionId | `Float` | Membership Trx ID |
| membershipType | `String` | Membership Type |
| name | `String` | Name |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originOfBooking | `String` | Origin of Booking |
| owner | `String` | Owner |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| purposeOfStay | `String` | Purpose of stay. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| recordType | `String` | Record Type |
| replyBy | `Date` | Date when the user gets a response to his/her claim. |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| room | `String` | Room |
| submitter | `String` | Submitter |
| totalBasePoints | `Float` | Total Base Points |
| totalBonusPoints | `Float` | Total Bonus Points |
| totalMiscPoints | `Float` | Total Miscellaneous Points |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsRateCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| addition | `String` | Amount to be added to the base rate when shown on rate query |
| advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| alternateRateCode | `String` | Alternative rate code if current rate is not available |
| availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| backToBackYN | `String` | Back To Back YN |
| baseAmount | `Float` | Base Amount |
| baseFltPct | `String` | Flat or Percentage of the Base Rate |
| baseRateCode | `String` | Base Rate Code |
| baseRounding | `String` | Indicates if rounding of rate is required |
| baseType | `String` | Indicating a rate type such as flat rate or percentage rate. Possible values are: FLAT DIFFERENTIAL and NULL. |
| bbarBaseAmount | `Float` | This column use to store Percentage or Amount difference between BAR Rate code and this Rate Code. |
| bbarBaseFltPct | `String` | This flag column identify that amount column represent Flat or Percentage value. |
| bbarBaseRounding | `String` | This column identify the rounding formula for the BBAR Rate calculation. |
| bbarBasedYn | `String` | This column will identify that Rate Code is Best BAR based rate code or not. Possible values are Y/N. |
| bbarCompareYn | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BBAR rate code. |
| bbarYn | `String` | Bbar Y/N |
| blockName | `String` | Block Name |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastPrice | `Float` | Breakfast Price |
| businessDate | `Date` | Business Date |
| bypassHurdleYn | `String` | In case of ORMS when this flag is Y system ignore this rate code from Hurdle Check. |
| bypassRankCheckYn | `String` | Indicates that this rate code will not go through rank validations if value is 'Y'. |
| cBaseAmount | `Float` | Central Base Amount |
| cBbarBaseAmount | `Float` | Central Bbar Base Amount |
| cBreakfastPrice | `Float` | Central Bfst Price |
| cDbaseAmount | `Float` | Central Dbase Amount |
| cDiscountRateAmount | `Float` | Central Discount Rate Amount |
| cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRateFloor | `Float` | Central Rate Floor |
| cRateLevel | `Float` | Central Rate Level |
| cRodBaseAmount | `Float` | Central Rod Base Amount |
| cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| catPackageCode | `String` | Stores the catering package code linked to this rate code. |
| cateringPackageYN | `String` | Specifies if a catering package is linked to this rate code. |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralRateBucket | `String` | Central Rate Bucket |
| centralRateBucketDescription | `String` | Central Rate Bucket Description |
| centralRateCategory | `String` | Central Rate Category |
| centralRateCategoryDescription | `String` | Central Rate Category Description |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| commissionPercent | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| commissionCode | `String` | Commission Code |
| commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| complimentaryYN | `String` | Complimentary YN |
| currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRatesYn | `String` | Daily Rates Y/N |
| dayUseYN | `String` | Day use reservation Y/N. |
| daysWhenClosedToArrival | `String` | Days the rate restriction is not available for arrival |
| dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| deletedFlag | `String` | Deleted Flag |
| depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| deptCode | `String` | Department code for the transaction. |
| discountRateAmount | `Float` | Discount rate amount value. |
| discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| discountYN | `String` | Discount Flag. |
| displaySequence | `Float` | Display Sequence |
| displaySet | `String` | Display Set |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| endDate | `Date` | End Date |
| eventProperty | `String` | Indicates if the value set for the specific property. |
| exchangeType | `String` | Exchange Type |
| externallyControlledYN | `String` | Externally Controlled YN |
| extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| flatYN | `String` | Flat YN |
| folioText | `String` | Text displayed on the Folio |
| frequentFlyerYN | `String` | Frequent Flyer YN |
| gDSAllowedYN | `String` | Is this rate code available for GDS |
| groupCode | `String` | Group Code |
| highlightRateAmountYn | `String` | To highlight on the rate query |
| houseUseYN | `String` | House-Use YN |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| loyaltyProgramYN | `String` | Flag to indicate if this is a loyalty program |
| mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| maximumDaysAdvanceBooking | `Float` | Maximum Days Advance Booking |
| maximumLengthOfStay | `Float` | Maximum Length of Stay |
| maximumOccupancy | `Float` | Maximum Occupancy |
| mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| minimumDaysAdvanceBooking | `Float` | Minimum Days Advance Booking |
| minimumOccupancy | `Float` | Minimum Occupancy |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| myFidelioUploadYN | `String` | MyFidelio Upload YN |
| negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalRateCode | `String` | Original Rate Code |
| orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| ownerRateYN | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| packageTransactionCode | `String` | Package Transaction Code |
| packageTransactionCodeWeekend | `String` | Package Transaction Code Weekend |
| packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| packageTransactionTaxIncludedYN | `String` | Transaction code is inclusive of tax Y/N |
| packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| packageYN | `String` | Package YN |
| packages | `String` | Packages |
| pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| postingRhythm | `String` | Posting Rhythm |
| postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRateYn | `String` | Print Rate Y/N |
| privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| privilegedYn | `String` | Indicates if rate is privileged or not. |
| profitTransactionCode | `String` | Profit Transaction Code |
| property | `String` | Code to uniquely identify the Property |
| propertyName | `String` | Property Name |
| rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| rankValue | `Float` | Rank Value |
| rateBucket | `String` | Yield rate bucket |
| rateBucketDescription | `String` | Rate Bucket Description |
| rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| rateCategory | `String` | Rate Category |
| rateCategoryDescription | `String` | Rate Category Description |
| rateClass | `String` | Rate Class |
| rateClassDescription | `String` | Rate Class Description |
| rateCodeId | `String` | Rate Code ID |
| rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| rateLabel | `String` | Rate Label |
| rateLevel | `Float` | Rate Level this rate code belongs to. |
| rateUpdateYN | `String` | Needs to send this rate to GDS or not. |
| rateinfoUrl | `String` | Rateinfo Url |
| redemptionRateYN | `String` | Redemption Rate YN |
| regionalAvailabilityYN | `String` | Regional Availability YN |
| repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rodBaseAmount | `Float` | Rod Base Amount |
| rodBaseFltPct | `String` | Rod Base Flt Pct |
| rodBaseRounding | `String` | Rod Base Rounding |
| rodBasedYn | `String` | Is the group code rate of day based |
| rodYn | `String` | Rod Y/N |
| roomAssignmentValue | `Float` | Room Assignment Value |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| servicePerc | `Float` | Service Percentage included. |
| shortInfo | `String` | Information to be used in the rate query |
| showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| taxIncludedPerc | `Float` | Percentage of included Tax. |
| taxIncludedYn | `String` | Tax is included in this rate. |
| tieredYN | `String` | Indicates if the rate is a tiered rate. |
| transactionCode | `String` | Rate transaction code |
| transactionCodeWeekend | `String` | Transaction Code Weekend |
| transactionTaxWeekendIncludedYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| unitOfLengthOfStay | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| wkDeptCode | `String` | Wk Dept Code |
| yieldAs | `String` | Yield As |
| yieldableYN | `String` | Yieldable YN |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsMarketDetailsType

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

### ProfilesLoyaltyClaimsSourceTableDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralSequence | `Float` | Central Sequence |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| deletedflag | `String` | Deleted Flag |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlagYN | `String` | Inactive YN |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastuseddatetime | `DateTime` | Lastuseddatetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentsourceid | `String` | Parentsourceid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source group of the source code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceid | `String` | Sourceid |
| tempYn | `String` | Temp Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsReservationPromotionsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| basedOnRule | `String` | Based On Rule |
| centralPromotionCode | `String` | Central Promotion Code |
| centralPromotionDescription | `String` | Central Promotion Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pPromoCode | `String` | P Promo Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| promotionCode | `String` | Promotion Code |
| promotionDescription | `String` | Promotion Name. |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsRoomDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessible | `String` | Accessible |
| areaF | `Float` | Area in sqft |
| areaM | `Float` | Area in sqm |
| assignAssignStatus | `String` | Assign Assign Status |
| assignDate | `DateTime` | Room assignment date |
| assignReasonDesc | `String` | Assign Reason Desc |
| assignType | `String` | Assign Type |
| assignemployeeid | `Float` | Assignemployeeid |
| assignreasonid | `String` | Assignreasonid |
| bedType | `String` | Bed Type |
| building | `String` | Building |
| buildingGroup | `String` | Building Group |
| businessDate | `Date` | Business Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMinimumRevenue | `Float` | Central Minimum Revenue |
| cRackRate | `Float` | Central Rack Rate |
| centralMeetingRoomType | `String` | Central Meeting Room Type |
| centralRoomClass | `String` | Central Room Class |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| combinationRoomYN | `String` | Combination Room YN |
| comments | `String` | Comments |
| componentRoom | `String` | Suite component room numbers |
| connectingRoomNumber | `String` | Connecting Room Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daySection | `String` | Indicates the section to which employee belongs. |
| deductYN | `String` | Deduct YN |
| defatulratecodeid | `String` | Defatulratecodeid |
| defaultRateDesc | `String` | Default Rate Description |
| deletedflag | `String` | Deleted Flag |
| departureCredits | `Float` | Credits associated with the task after departure. |
| description | `String` | Description |
| diaryName | `String` | Diary name to show room in |
| diarydisplayflag | `String` | Diarydisplayflag |
| discrepancy | `String` | Discrepancy |
| doors | `String` | Number of doors |
| eveningSection | `String` | Section the room belongs to for evening housekeeping |
| evisitorFacilityId | `String` | Facility ID for eVisitor. |
| excludedEventTypes | `String` | Stores event types which do not require alternate spaces. |
| facing | `String` | Direction room faces |
| floor | `String` | Floor |
| foPers | `Float` | The persons staying in room according to Front office. |
| forceAlternateYn | `String` | Defines if the function space needs an alternate space when booked. |
| frontDeskLocation | `String` | The front desk location this room should check in to. |
| frontOfficeStatus | `String` | Front Office Status of the room i.e.: Vacant or Occupied. |
| fullUtilizationTime | `Float` | Minutes occupied that define the room as 100% utilized. Maximum is 1440 minutes. |
| genericYN | `String` | Generic YN |
| handicapflag | `String` | Handicapflag |
| heightmaxF | `Float` | Max Height in ft |
| heightmaxM | `Float` | Max Height in m |
| heightminF | `Float` | Minumum heigth of room (feet) |
| heightminM | `Float` | Minumum heigth of room (meters) |
| holdDateTime | `DateTime` | Date and time when room will be released from hold. |
| holdType | `String` | Hold type from resort_assignment_reasons table. |
| holdUser | `Float` | User that is holding the room. |
| housekeepingAssignmentOrderBy | `Float` | Sequence for automatically generated task assignment. |
| housekeepingInspDate | `Date` | Housekeeping Inspected date |
| housekeepingInspEmpId | `String` | Houskeeping inspected employee id |
| housekeepingPers | `Float` | The number of persons staying in the room according to housekeeping |
| housekeepingStatus | `String` | The status of this room according to housekeeping |
| imageId | `Float` | Image ID |
| inactiveflag | `String` | Inactive Flag |
| includeInStatisticsYN | `String` | Include in Statistics YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalTempflag | `String` | Tempflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyCode | `String` | The current key code for this room.  Used to create keys for a room. |
| keyOptions | `String` | Privileges available for this key |
| lastCheckOutDate | `Date` | The last check out date for this room. |
| lastMeterReading | `Float` | The last meter reading for condos that track electrical usage of rented rooms. |
| lengthF | `Float` | Length (feet) |
| lengthM | `Float` | Length (meters) |
| light | `String` | Number of lights in the room |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loudspeakersflag | `String` | Loudspeakersflag |
| maxAdvance | `Float` | Maximum number of days before the catering event date  that the space can be booked on the web. |
| maxCapacity | `Float` | Function Space Maximum Capacity. |
| maxSharedGroups | `Float` | Maximum number of groups for a Shared function space allowed. |
| maximumOccupancy | `Float` | Maximum Occupancy |
| measurement | `String` | The unit of measurement for this square units (IE: Feet Meters etc) |
| meetingRoomType | `String` | Type of meeting room |
| meetingRoomYN | `String` | Meeting Room YN |
| meetingroomTypeDesc | `String` | Meetingroom Type Description |
| meetingroomTypeSeq | `Float` | Meetingroom Type Sequence |
| microphoneSocketTypes | `String` | Type of microphone sockets |
| microphoneSockets | `Float` | Number of microphone sockets |
| minAdvance | `Float` | Minimum number of days before the catering event date that the space can be booked on the web. |
| minCapacity | `Float` | Minimum Capacity |
| minimumRevenue | `Float` | Minimum Revenue |
| numberOfBeds | `Float` | Specifies the number of beds in this room. |
| occupancyCondition | `String` | Current room condition updated daily.(ie StayOverDueOutExpected etc) |
| occupantDiscrepancy | `Float` | Discrepancy between front desk and housekeeping |
| onlinePrintingYn | `String` | Used for pseudo rooms. If Y then this pseudo room will be included in Online Printing for reservation changes. |
| orderBy2 | `Float` | Display sequence 2 |
| orderBy3 | `Float` | Display sequence 3 |
| orderBy4 | `Float` | Display sequence 4 |
| orderBy5 | `Float` | Display sequence 5 |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ovosGradeCode | `String` | Stores a Grade associated with a unit to determine the room display order in Room Assignment and Room Plan screens. |
| ovosUnitYn | `String` | Room can be OVOS unit. |
| pcode | `String` | Not used |
| personDiscrepancy | `Float` | Person discrepancy between front desk and houskeeping |
| phoneNumber | `String` | Phone Number |
| physicalNumberOfRooms | `Float` | Physical Number of Rooms |
| pickupCredits | `Float` | Houskeeping credits for cleaning room in pickup status |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| publishedRateAmount | `Float` | Default rate for the room |
| publishedRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rating | `String` | Rating |
| repAssignReasonDescription | `String` | Reporting Assign Reason Desc |
| repBedTypeDescription | `String` | Reporting Bed Type Desc |
| repMeetingroomTypeDescription | `String` | Reporting Meetingroom Type Desc |
| repMeetingroomTypeSequence | `Float` | Reporting Meetingroom Type Seq |
| repRoomClassSellSequence | `Float` | Reporting Room Class Sell Seq |
| repRoomFeaturesDescs | `String` | Reporting Room Features Descs |
| repRoomStatusReason | `String` | Reporting Room Status Reason |
| repRoomStatusReasonDescription | `String` | Reporting Room Status Reason Desc |
| returnStatus | `String` | Room return status |
| room | `String` | Room |
| roomAssignmentRating | `Float` | Room Assignment Rating. |
| roomCategoryBedtype | `String` | Room Category Bedtype |
| roomCategoryDesc | `String` | Room Category Desc |
| roomClass | `String` | Room Class |
| roomClassCentralDescription | `String` | Room Class Central Description |
| roomClassDescription | `String` | Room Class Description |
| roomClassSequence | `Float` | Room Class Sequence |
| roomCondition | `String` | Room Condition |
| roomFeatureDescription | `String` | Room Feature Description |
| roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| roomNumber | `String` | Room Number |
| roomParity | `String` | Room Parity |
| roomStatus | `String` | Room Status |
| roomStatusDescription | `String` | Room Status Description |
| roomStatusFromDate | `Date` | The date as of which the room_status is valid. |
| roomStatusReason | `String` | Room Status Reason |
| roomStatusReasonDesc | `String` | Room Status Reason Description |
| roomStatusRemarks | `String` | Room status remarks |
| roomStatusToDate | `Date` | The date till which the room_status is valid.(Used during OO and OS status of rooms ) |
| roomType | `String` | Room Type |
| roomUseCount | `Float` | Total Count of the number of days the room was used. |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| roomid | `String` | Roomid |
| roomstatusreasonid | `String` | Roomstatusreasonid |
| sequence | `Float` | Sequence |
| serviceStatus | `String` | Current guest service status code for this room. Example: Service status can be DND (Do Not Disturb) or MUP (Make Up Room) |
| setupNotes | `String` | Notes for the setup of the room |
| shareableflag | `String` | Shareableflag |
| smoking | `String` | Smoking |
| smokingPreferences | `String` | Smoking Preferences |
| squareUnits | `Float` | The square units for this room (IE: if a condo in the US likely the square feet of this room) |
| stayoverCredits | `Float` | Stayover Credits |
| suiteType | `String` | Standard or Suite |
| suiteYN | `String` | Suite YN |
| supplement | `String` | Supplement |
| tempFlag | `String` | Temp Flag |
| translationboothNum | `Float` | Number for the booth |
| turnDown | `String` | Turn Down |
| turndownCredits | `Float` | Houskeeping credits for Turndown. |
| tvRadioSockets | `Float` | Number of TV or radio sockets |
| unit | `String` | Unit |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| visibleOnWebYn | `String` | Flag makes a Function Space visible on the web. |
| webBookingYn | `String` | Web Booking Y/N |
| weightF | `Float` | Room weigth (feet) |
| weightM | `Float` | Room weigth (meters) |
| widthF | `Float` | Width (feet) |
| widthM | `Float` | Width (meters) |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsMembershipClaimsHistoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activity | `String` | Code to indicate the activity ocuured in the transaction (i.e. OPEN CLOSE) |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| date | `Date` | Date claim was posted in the database. |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipClaimId | `Float` | Primary key. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| submitter | `String` | The name of the user who created the record. |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyClaimsChannelDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| channelid | `String` | Channelid |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| originDisplaySequence | `Float` | Origin Display Sequence |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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