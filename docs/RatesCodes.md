# RatesCodes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| rateCodeDetails | [`RatesCodesRateCodeDetailsType`](#ratescodesratecodedetailstype) | Rate Code Details |
| propertyPropertyDetails | [`RatesCodesPropertyPropertyDetailsType`](#ratescodespropertypropertydetailstype) | Resort Details |
| rateCodeDetailsDetails | [`RatesCodesRateCodeDetailsDetailsType`](#ratescodesratecodedetailsdetailstype) | Rate Code Details Details |
| blockDetails | [`RatesCodesBlockDetailsType`](#ratescodesblockdetailstype) | Block |
| financialTransactionDetails | [`RatesCodesFinancialTransactionDetailsType`](#ratescodesfinancialtransactiondetailstype) | Financial Transaction |
| ratesCodesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RatesCodesRateCodeDetailsType

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

### RatesCodesPropertyPropertyDetailsType

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

### RatesCodesRateCodeDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addAfterRounding | `Float` | Amount to be added after rounding |
| adultCharge | `Float` | Adult Charge |
| adultsThreshold | `Float` | Threshold for number of adults on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| adultsThresholdCharge | `Float` | Amount used to calculate price for adults when the number of adults on the reservation exceed the adult threshold. |
| advBaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the advanced dynamic base rate. |
| advBaseFltPct | `String` | Calculate as Flat [FLT] or Percentage [PCT] amount of the advanced dynamic base rate code. |
| advDailyBaseRateCode | `String` | Identifies the Advanced Daily Base Rate Code from which this rate detail was copied. |
| advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| ageRangeForBucket1 | `String` | Age Range for Bucket 1 |
| ageRangeForBucket2 | `String` | Age Range for Bucket 2 |
| ageRangeForBucket3 | `String` | Age Range for Bucket 3 |
| amount1Type | `String` | Indicate the amount type for the 1 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount2Type | `String` | Indicate the amount type for the 2 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount3Type | `String` | Indicate the amount type for the 3 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount4Type | `String` | Indicate the amount type for the 4 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount5Type | `String` | Indicate the amount type for the 5 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amountFor1Person | `Float` | Amount for 1 Person |
| amountFor2Persons | `Float` | Amount for 2 Persons |
| amountFor3Persons | `Float` | Amount for 3 Persons |
| amountFor4Persons | `Float` | Amount for 4 Persons |
| amountFor5Persons | `Float` | Amount for 5 adults |
| barAmount | `Float` | Stores the Percentage or Amount difference between BAR Rate code and this Rate Code. |
| barFltPct | `String` | Identifies if the amount column represents a Flat [FLT] or Percentage [PCT] value. |
| barRounding | `String` | Identifies the rounding formula for the BBAR Rate calculation. |
| barYn | `String` | Is this schedule applied to bar by los rate pushing also. |
| cAdultCharge | `Float` | Central Adult Charge |
| cAdultsThresholdCharge | `Float` | Central Adults Threshold Charge |
| cAdvanceBaseAmount | `Float` | Central Adv Base Amount |
| cAmount1 | `Float` | Central Amount 1 |
| cAmount2 | `Float` | Central Amount 2 |
| cAmount3 | `Float` | Central Amount 3 |
| cAmount4 | `Float` | Central Amount 4 |
| cAmount5 | `Float` | Central Amount 5 |
| cBarAmount | `Float` | Central Bar Amount |
| cChildCharge1 | `Float` | Central Child Charge 1 |
| cChildCharge2 | `Float` | Central Child Charge 2 |
| cChildCharge3 | `Float` | Central Child Charge 3 |
| cChildOwnCharge1 | `Float` | Central Child Own Charge 1 |
| cChildOwnCharge2 | `Float` | Central Child Own Charge 2 |
| cChildOwnCharge3 | `Float` | Central Child Own Charge 3 |
| cChildOwnCharge4 | `Float` | Central Child Own Charge 4 |
| cChildrenCharge | `Float` | Central Children Charge |
| cChildrenThresholdCharge | `Float` | Central Children Threshold Charge |
| cDifferenceAmount1 | `Float` | Central Diff Amount 1 |
| cDifferenceAmount2 | `Float` | Central Diff Amount 2 |
| cDifferenceAmount3 | `Float` | Central Diff Amount 3 |
| cDifferenceAmount4 | `Float` | Central Diff Amount 4 |
| cDifferenceAmount5 | `Float` | Central Diff Amount 5 |
| cDifferenceAmountExtraAdult | `Float` | Central Diff Amount Extra Adult |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFlatIncrease | `Float` | Central Flat Increase |
| cLos1Amount | `Float` | Central Los1 Amt |
| cLos10Amount | `Float` | Central Los10 Amt |
| cLos11Amount | `Float` | Central Los11 Amt |
| cLos12Amount | `Float` | Central Los12 Amt |
| cLos13Amount | `Float` | Central Los13 Amt |
| cLos14Amount | `Float` | Central Los14 Amt |
| cLos2Amount | `Float` | Central Los2 Amt |
| cLos3Amount | `Float` | Central Los3 Amt |
| cLos4Amount | `Float` | Central Los4 Amt |
| cLos5Amount | `Float` | Central Los5 Amt |
| cLos6Amount | `Float` | Central Los6 Amt |
| cLos7Amount | `Float` | Central Los7 Amt |
| cLos8Amount | `Float` | Central Los8 Amt |
| cLos9Amount | `Float` | Central Los9 Amt |
| cMaximumAmount1 | `Float` | Central Maximum Amount 1 |
| cMaximumAmount2 | `Float` | Central Maximum Amount 2 |
| cMinimumAmount1 | `Float` | Central Minimum Amount 1 |
| cMinimumAmount2 | `Float` | Central Minimum Amount 2 |
| cOccupantsThresholdCharge | `Float` | Central Occupants Threshold Charge |
| cPackageRateStayOver | `Float` | Central Package Rate Stay Over |
| cRoomCost | `Float` | Central Room Cost |
| calculationFlag | `String` | Indicates Global rate update was (P)ercent or (F)lat |
| catPackagePriceCode | `String` | Stores the catering package price code for the package linked to the rate code in rate header. |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralPackageCode | `String` | Central Package Code |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSeasonCode | `String` | Central Season Code |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| childExcThreshold1 | `String` | Indicates whether the child 1 count will be excluded while calculating the total occupants threshold excess amount. |
| childExcThreshold2 | `String` | Indicates whether the child 2 count will be excluded while calculating the total occupants threshold excess amount. |
| childExcThreshold3 | `String` | Indicates whether the child 3 count will be excluded while calculating the total occupants threshold excess amount. |
| childOwnCharge1 | `Float` | Child Own Charge 1 |
| childOwnCharge2 | `Float` | Child Own Charge 2 |
| childOwnCharge3 | `Float` | Child Own Charge 3 |
| childOwnCharge4 | `Float` | Child Own Charge 4 |
| childrenFreeStay | `Float` | Number of children that will stay free. |
| childrenCharge | `Float` | Children Charge |
| childrenThreshold | `Float` | Threshold for number of children on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| childrenThresholdCharge | `Float` | Amount used to calculate price for children when the number of children on the reservation exceed the children threshold. |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| depositRequieredYn | `String` | Deposit required Y/N |
| differenceAmount1 | `Float` | Contains a flat/percentage value for 1 Adult differential. |
| differenceAmount2 | `Float` | Contains a flat/percentage value for 2 Adult differential. |
| differenceAmount3 | `Float` | Contains a flat/percentage value for 3 Adult differential. |
| differenceAmount4 | `Float` | Contains a flat/percentage value for 4 Adult differential. |
| differenceAmount5 | `Float` | Contains a flat/percentage value for 5 Adult differential. |
| differenceAmountExtraAdult | `Float` | Contains a flat/percentage value for Extra Adult differential. |
| differencePercentage1Yn | `String` | Indicate if percentage value for 1 Adult differential should be used. |
| differencePercentage2Yn | `String` | Indicate if percentage value for 2 Adult differential should be used. |
| differencePercentage3Yn | `String` | Indicate if percentage value for 3 Adult differential should be used. |
| differencePercentage4Yn | `String` | Indicate if percentage value for 4 Adult differential should be used. |
| differencePercentage5Yn | `String` | Indicate if percentage value for 5 Adult differential should be used. |
| differencePercentageExtraAdultYn | `String` | Indicate if percentage value for Extra Adult differential should be used. |
| endDate | `Date` | End Date |
| externalRateSetId | `Float` | This field is required by OXI to store the external system rate_set_id to be used for locating the record in rate_set table during an update. |
| extraAdultType | `String` | Indicate the amount type for the Extra Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| flatIncrease | `Float` | Flat Increase Amount |
| globalRateUpdateYn | `String` | Indicates if Rate set created by Global Rate Update |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| internalRatesetid | `Float` | Ratesetid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lengthOfStay1Amount | `Float` | LOS1 amount for prevailing rate code. |
| lengthOfStay10Amount | `Float` | LOS10 amount for prevailing rate code. |
| lengthOfStay11Amount | `Float` | LOS11 amount for prevailing rate code. |
| lengthOfStay12Amount | `Float` | LOS12 amount for prevailing rate code. |
| lengthOfStay13Amount | `Float` | LOS13 amount for prevailing rate code. |
| lengthOfStay14Amount | `Float` | LOS14 amount for prevailing rate code. |
| lengthOfStay2Amount | `Float` | LOS2 amount for prevailing rate code. |
| lengthOfStay3Amount | `Float` | LOS3 amount for prevailing rate code. |
| lengthOfStay4Amount | `Float` | LOS4 amount for prevailing rate code. |
| lengthOfStay5Amount | `Float` | LOS5 amount for prevailing rate code. |
| lengthOfStay6Amount | `Float` | LOS6 amount for prevailing rate code. |
| lengthOfStay7Amount | `Float` | LOS7 amount for prevailing rate code. |
| lengthOfStay8Amount | `Float` | LOS8 amount for prevailing rate code. |
| lengthOfStay9Amount | `Float` | LOS9 amount for prevailing rate code. |
| linkRateSetId | `Float` | Rate set id of the base rates rate set. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| maximumAmount1 | `Float` | Maximum rate amount value for 1 adult. |
| maximumAmount2 | `Float` | Maximum rate amount value for 2 adults. |
| minChildrenForFreeStay | `Float` | Represents every x number of children to get free "num_children_stay_free" |
| minimumAmount1 | `Float` | Minimum rate amount value for 1 adult. |
| minimumAmount2 | `Float` | Minimum rate amount value for 2 adults. |
| minimumClosingProbability | `Float` | Not used |
| occupantsThreshold | `Float` | Threshold for number of occupants on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| occupantsThresholdCharge | `Float` | Amount used to calculate price for occupants when the number of occupants on the reservation exceed the occupant threshold. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageAdultStayOver | `Float` | The amount to charge per extra adult on every additional day of stay for a package that extends beyo |
| packageChildrenStayOver | `Float` | The amount to charge per extra child on every additional day of stay for a package that extends beyo |
| packageCode | `String` | Package Code |
| packageRateStayOver | `Float` | The amount to charge extra on every additional day of stay for a package that extends beyond the inc |
| percentIncrease | `Float` | Not used |
| pointsRequired | `Float` | Points Required |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rateAvailableOnFridaysYN | `String` | Rate Available on Fridays YN |
| rateAvailableOnMondaysYN | `String` | Rate Available on Mondays YN |
| rateAvailableOnSaturdaysYN | `String` | Rate Available on Saturdays YN |
| rateAvailableOnSundaysYN | `String` | Rate Available on Sundays YN |
| rateAvailableOnThursdaysYN | `String` | Rate Available on Thursdays YN |
| rateAvailableOnTuesdaysYN | `String` | Rate Available on Tuesdays YN |
| rateAvailableOnWednesdaysYN | `String` | Rate Available on Wednesdays YN |
| rateCode | `String` | Rate Code |
| rateCodeDesc | `String` | Event Reservation Rate Code Description |
| rateCodeId | `String` | Rate Code ID |
| rateRule | `String` | Rate Rule |
| rateSetId | `Float` | Rate Set ID |
| rateForChildInAgeBucket1 | `Float` | Child charge for defined rate bucket 1. |
| rateForChildInAgeBucket2 | `Float` | Child charge for defined rate bucket 2. |
| rateForChildInAgeBucket3 | `Float` | Child charge for defined rate bucket 3. |
| ratesActiveYn | `String` | Indicates if the rate amounts are activated. |
| ratetierid | `Float` | Ratetierid |
| repSeasonDescription | `String` | Reporting Season Desc |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomCost | `Float` | Room Cost |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| roundToNearest | `Float` | Type of rounding after rate_update |
| season | `String` | Season |
| seasonCode | `String` | Season Code |
| seasonDesc | `String` | User defined description for season. |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| startDate | `Date` | Start Date |
| tierId | `Float` | Tier ID for the Rate Detail. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### RatesCodesBlockDetailsType

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

### RatesCodesFinancialTransactionDetailsType

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

### RatesCodesQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| ratecodeDetailsBaseRateCode | `StringInput` | Base Rate Code |  |
| ratecodeDetailsBeginBookingDate | `DateInput` | Business Date |  |
| ratecodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| ratecodeDetailsCommissionCode | `StringInput` | Commission Code |  |
| ratecodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| ratecodeDetailsDailyRatesYn | `StringInput` | Daily Rates Y/N |  |
| ratecodeDetailsDbaseRateCode | `StringInput` | The rate code on which this rate shedule is dynamically based on. |  |
| ratecodeDetailsSellSequence | `FloatInput` | Display Sequence |  |
| ratecodeDetailsEndBookingDate | `DateInput` | End Date |  |
| ratecodeDetailsGroupCode | `StringInput` | Group Code |  |
| ratecodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| ratecodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| ratecodeDetailsMarketCode | `StringInput` | Market Code |  |
| ratecodeDetailsMaxDvanceBooking | `FloatInput` | Maximum Days Advance Booking |  |
| ratecodeDetailsMaxLos | `FloatInput` | Maximum Length of Stay |  |
| ratecodeDetailsMaxOccupancy | `FloatInput` | Maximum Occupancy |  |
| ratecodeDetailsMinAdvanceBooking | `FloatInput` | Minimum Days Advance Booking |  |
| ratecodeDetailsMinOccupancy | `FloatInput` | Minimum Occupancy |  |
| ratecodeDetailsOrderBy | `FloatInput` | Order By |  |
| ratecodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| ratecodeDetailsRateCode | `StringInput` | Original Rate Code |  |
| ratecodeDetailsOrsSellSequence | `FloatInput` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |  |
| ratecodeDetailsPendingApprovalYn | `StringInput` | Indicates whether the rate code is pending for approval or not |  |
| ratecodeDetailsResort | `StringInput!` | Code to uniquely identify the Property | `mandatoryInput` |
| ratecodeDetailsRateBucket | `StringInput` | Yield rate bucket |  |
| ratecodeDetailsRateCodeId | `StringInput` | Rate Code ID |  |
| ratecodeDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |  |
| ratecodeDetailsSourceCode | `StringInput` | Source Code |  |
| ratecodeDetailsTransactionCode | `StringInput` | Rate transaction code |  |
| ratecodeDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |  |
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
| ratecodedetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| ratecodedetailsDetailsEndDate | `DateInput` | End Date |  |
| ratecodedetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| ratecodedetailsDetailsLinkRateSetId | `FloatInput` | Rate set id of the base rates rate set. |  |
| ratecodedetailsDetailsMarketCode | `StringInput` | Market Code |  |
| ratecodedetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| ratecodedetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| ratecodedetailsDetailsRateCode | `StringInput` | Rate Code |  |
| ratecodedetailsDetailsRateSetId | `FloatInput` | Rate Set ID |  |
| ratecodedetailsDetailsSeasonCode | `StringInput` | Season Code |  |
| ratecodedetailsDetailsSourceCode | `StringInput` | Source Code |  |
| ratecodedetailsDetailsBeginDate | `DateInput` | Start Date |  |
| ratecodedetailsDetailsTierId | `FloatInput` | Tier ID for the Rate Detail. |  |
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