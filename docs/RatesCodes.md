# RatesCodes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `ratesCodes`
> Rate detail information including all rate header details  room type rate tiers and rate amounts per occupant.
  
**Return:** [`[RatesCodesType]`](#ratescodestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`RatesCodesQueryArgumentsType!`](#ratescodesqueryargumentstype) |  |

## Object Types

### RatesCodesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | rateCodeDetails | [`RatesCodesRateCodeDetailsType`](#ratescodesratecodedetailstype) | Rate Code Details |
| 2 | propertyPropertyDetails | [`RatesCodesPropertyPropertyDetailsType`](#ratescodespropertypropertydetailstype) | Resort Details |
| 3 | rateCodeDetailsDetails | [`RatesCodesRateCodeDetailsDetailsType`](#ratescodesratecodedetailsdetailstype) | Rate Code Details Details |
| 4 | blockDetails | [`RatesCodesBlockDetailsType`](#ratescodesblockdetailstype) | Block |
| 5 | financialTransactionDetails | [`RatesCodesFinancialTransactionDetailsType`](#ratescodesfinancialtransactiondetailstype) | Financial Transaction |
| 6 | ratesCodesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RatesCodesRateCodeDetailsType

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

### RatesCodesPropertyPropertyDetailsType

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

### RatesCodesRateCodeDetailsDetailsType

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

### RatesCodesBlockDetailsType

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

### RatesCodesFinancialTransactionDetailsType

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
| 75 | centralDepositAmountPaid | `Float` | Central Deposit Amount Paid |
| 76 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 77 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
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
| 243 | postedAmountInTransactionCurrency | `Float` | Posted Amount in Transaction Currency |
| 244 | postingDate | `DateTime` | Posting Date |
| 245 | postingRhythm | `String` | Posting Rhythm |
| 246 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 247 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 248 | postitNo | `Float` | Postit Number |
| 249 | postitYn | `String` | Postit Y/N |
| 250 | pricePerUnit | `Float` | Price Per Unit |
| 251 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 252 | processed8300YN | `String` | Processed 8300 YN |
| 253 | productid | `String` | Productid |
| 254 | profileid | `Float` | Profileid |
| 255 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 256 | proformaYn | `String` | Proforma Y/N |
| 257 | property | `String` | Code to uniquely identify the Property |
| 258 | propertyBillPrefix | `String` | Property Bill Prefix |
| 259 | quantity | `Float` | Quantity |
| 260 | queueName | `String` | Queue Name |
| 261 | rateCode | `String` | Rate Code |
| 262 | ratecodeid | `String` | Ratecodeid |
| 263 | receiptNumber | `Float` | Receipt Number |
| 264 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 265 | repTransactionCode | `String` | Reporting Trx Code |
| 266 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 267 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 268 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 269 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 270 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 271 | reservationid | `Float` | Reservationid |
| 272 | resvenddate | `Date` | Resvenddate |
| 273 | revenueAmount | `Float` | Revenue Amount. |
| 274 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 275 | revisionNo | `Float` | Revision Number |
| 276 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 277 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 278 | roomClass | `String` | Room Class |
| 279 | roomNts | `Float` | Room Nts |
| 280 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 281 | roomNumber | `String` | Room Number |
| 282 | roomid | `String` | Roomid |
| 283 | roundFactorYn | `String` | Round Factor Y/N |
| 284 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 285 | routedYn | `String` | Indicates if the transaction has been routed. |
| 286 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 287 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
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

### RatesCodesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
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
| ratecodeDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| ratecodeDetailsRateBucket | `StringInput` | Yield rate bucket |
| ratecodeDetailsRateCodeId | `StringInput` | Rate Code ID |
| ratecodeDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |
| ratecodeDetailsSourceCode | `StringInput` | Source Code |
| ratecodeDetailsTransactionCode | `StringInput` | Rate transaction code |
| ratecodeDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
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
| financialtransDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtransDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtransDetailsArState | `StringInput` | AR State |
| financialtransDetailsArNumber | `FloatInput` | Account Code |
| financialtransDetailsAccountid | `FloatInput` | Accountid |
| financialtransDetailsArticleId | `FloatInput` | Article ID |
| financialtransDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtransDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtransDetailsBusinessDate | `DateInput` | Business Date |
| financialtransDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtransDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtransDetailsCashierId | `FloatInput` | Cashier ID |
| financialtransDetailsChainCode | `StringInput` | Chain Code |
| financialtransDetailsChequeNumber | `StringInput` | Check Number |
| financialtransDetailsClosureNo | `FloatInput` | Closure Number |
| financialtransDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtransDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtransDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtransDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtransDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtransDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtransDetailsFintransid | `FloatInput` | Fintransid |
| financialtransDetailsBillNo | `FloatInput` | Folio Number |
| financialtransDetailsFolioView | `FloatInput` | Folio View |
| financialtransDetailsFolioid | `FloatInput` | Folioid |
| financialtransDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtransDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtransDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtransDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtransDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtransDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtransDetailsArticleid | `FloatInput` | Articleid |
| financialtransDetailsBusinessdate | `DateInput` | Businessdate |
| financialtransDetailsCashierid | `FloatInput` | Cashierid |
| financialtransDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtransDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtransDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtransDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtransDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtransDetailsNameId | `FloatInput` | Name ID |
| financialtransDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtransDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtransDetailsOriginalRoom | `StringInput` | Original Room |
| financialtransDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtransDetailsProduct | `StringInput` | Package |
| financialtransDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtransDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtransDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtransDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtransDetailsPostitNo | `FloatInput` | Postit Number |
| financialtransDetailsProductid | `StringInput` | Productid |
| financialtransDetailsProfileid | `FloatInput` | Profileid |
| financialtransDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtransDetailsRateCode | `StringInput` | Rate Code |
| financialtransDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtransDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtransDetailsReservationid | `FloatInput` | Reservationid |
| financialtransDetailsRoom | `StringInput` | Room Number |
| financialtransDetailsRoomid | `StringInput` | Roomid |
| financialtransDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtransDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtransDetailsTaxElements | `StringInput` | Tax Elements |
| financialtransDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtransDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtransDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtransDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtransDetailsTrxDate | `DateInput` | Transaction Date |
| financialtransDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtransDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtransDetailsTrxCode | `StringInput` | Transaction Code |
| financialtransDetailsTrxNo | `FloatInput` | Trx Number |
| financialtransDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtransDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtransDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtransDetailsAuthorizerId | `FloatInput` | User ID |
#### Validation Rules

**`mandatoryInput`**
- ratecodeDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query ratesCodes($input: RatesCodesQueryArgumentsType!) {
  ratesCodes(input: $input) @stream {
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
financial_transaction_details_schema = {
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
    'centralDepositAmountPaid': pl.Float64,
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
    'postedAmountInTransactionCurrency': pl.Float64,
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