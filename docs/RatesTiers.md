# RatesTiers
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `ratesTiers`
> Rate tier definition by length of stays.
  
**Return:** [`[RatesTiersType]`](#ratestierstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`RatesTiersQueryArgumentsType!`](#ratestiersqueryargumentstype) |  |

## Object Types

### RatesTiersType

| Field | Type | Description |
| --- | --- | --- |
| rateTierDetails | [`RatesTiersRateTierDetailsType`](#ratestiersratetierdetailstype) | Rate Tier Details |
| propertyPropertyDetails | [`RatesTiersPropertyPropertyDetailsType`](#ratestierspropertypropertydetailstype) | Resort Details |
| rateCodeDetailsDetails | [`RatesTiersRateCodeDetailsDetailsType`](#ratestiersratecodedetailsdetailstype) | Rate Code Details Details |
| ratesTiersRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RatesTiersRateTierDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| fromLengthOfStay | `Float` | LOS start day for the tier. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| ratetierid | `Float` | Ratetierid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| tierID | `Float` | Tier ID for the Rate Detail. |
| toLengthOfStay | `Float` | LOS end day for the tier except for the last day. |

[⬆ Back to Query](#query)

---

### RatesTiersPropertyPropertyDetailsType

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

### RatesTiersRateCodeDetailsDetailsType

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

### RatesTiersQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| ratetierDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratetierDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratetierDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratetierDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| ratetierDetailsTierId | `FloatInput` | Tier ID for the Rate Detail. |
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

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query ratesTiers($input: RatesTiersQueryArgumentsType!) {
  ratesTiers(input: $input) @stream {
    rateTierDetails {
      dSI
      deletedflag
      fromLengthOfStay
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      ratetierid
      rnaInsertDate
      rnaUpdateDate
      tierID
      toLengthOfStay
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
  }
}
```