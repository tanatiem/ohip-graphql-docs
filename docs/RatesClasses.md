# RatesClasses
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `ratesClasses`
> Rate class definition with begin and end date.
  
**Return:** [`[RatesClassesType]`](#ratesclassestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`RatesClassesQueryArgumentsType!`](#ratesclassesqueryargumentstype) |  |

## Object Types

### RatesClassesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | rateClassesDetails | [`RatesClassesRateClassesDetailsType`](#ratesclassesrateclassesdetailstype) | Rate Classes Details |
| 2 | propertyPropertyDetails | [`RatesClassesPropertyPropertyDetailsType`](#ratesclassespropertypropertydetailstype) | Resort Details |
| 3 | reservationSummaryDetails | [`RatesClassesReservationSummaryDetailsType`](#ratesclassesreservationsummarydetailstype) | Reservation Summary |
| 4 | forecastSummaryDetails | [`RatesClassesForecastSummaryDetailsType`](#ratesclassesforecastsummarydetailstype) | Forecast Summary Details |
| 5 | ratesClassesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RatesClassesRateClassesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralRateClass | `String` | Central Rate Class |
| 2 | centralRateClassDescription | `String` | Central Rate Class Description |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedflag | `String` | Deleted Flag |
| 5 | displaySequence | `Float` | Display Sequence |
| 6 | endDate | `Date` | End Date |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | internalLocationId | `String` | Location ID |
| 11 | internalOrganizationId | `Float` | Organization ID |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | locationID | `String` | Internal ID to uniquely identify the Property |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rateClass | `String` | Rate Class |
| 19 | rateClassDescription | `String` | Rate Class Description |
| 20 | rateClassId | `String` | Rate Class ID |
| 21 | repItem | `String` | Reporting Item |
| 22 | repItemName | `String` | Reporting Item Name |
| 23 | repItemOrderby | `Float` | Reporting Item Orderby |
| 24 | repSellSequence | `Float` | Reporting Sell Sequence |
| 25 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 26 | resortResort | `String` | Property code |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | startDate | `Date` | Start Date |
| 30 | updateDate | `DateTime` | Update Date |
| 31 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### RatesClassesPropertyPropertyDetailsType

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

### RatesClassesReservationSummaryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | agentId | `Float` | Agent ID |
| 4 | allotmentHeaderId | `Float` | Allotment Header ID |
| 5 | allotmentid | `Float` | Block ID |
| 6 | arrivalPersons | `Float` | Arrival Persons |
| 7 | arrivalRooms | `Float` | Arrival Rooms |
| 8 | blockEndDate | `Date` | Block End Date |
| 9 | blockStatus | `String` | Block Status |
| 10 | bookedRoomCategory | `String` | Booked Room Category |
| 11 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 12 | bookingStatus | `String` | Booking Status |
| 13 | bookingStatusDescription | `String` | Booking Status Description |
| 14 | bookingstatusid | `String` | Bookingstatusid |
| 15 | businessDateCreated | `Date` | Business Date Created |
| 16 | cExchangeDate | `Date` | Central Xchange Date |
| 17 | cExchangeRate | `Float` | Central Xchange Rate |
| 18 | cFCExtraRevenue | `Float` | Central Fc Extra Revenue |
| 19 | cFCFoodRevenue | `Float` | Central Fc Food Revenue |
| 20 | cFCFoodRevenueTax | `Float` | Central Fc Food Revenue Tax |
| 21 | cFCGrossRate | `Float` | Central Fc Gross Rate |
| 22 | cFCNetRoomRevenue | `Float` | Central Fc Net Room Revenue |
| 23 | cFCNonRevenue | `Float` | Central Fc Non Revenue |
| 24 | cFCNonRevenueTax | `Float` | Central Fc Non Revenue Tax |
| 25 | cFCOtherRevenue | `Float` | Central Fc Other Revenue |
| 26 | cFCOtherRevenueTax | `Float` | Central Fc Other Revenue Tax |
| 27 | cFCRoomRevenue | `Float` | Central Fc Room Revenue |
| 28 | cFCRoomRevenueTax | `Float` | Central Fc Room Revenue Tax |
| 29 | cFCTotalRevenue | `Float` | Central Fc Total Revenue |
| 30 | cFCTotalRevenueTax | `Float` | Central Fc Total Revenue Tax |
| 31 | cFoodRevenueTax | `Float` | Central Food Revenue Tax |
| 32 | cNonRevenueTax | `Float` | Central Non Revenue Tax |
| 33 | cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 34 | cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 35 | cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 36 | cRSExchangeRate | `Float` | CRS Exchange Rate |
| 37 | centralBookingStatus | `String` | Central Booking Status |
| 38 | centralBookingStatusDescription | `String` | Central Booking Status Description |
| 39 | centralCurrencyCode | `String` | Central Currency Code |
| 40 | centralExtraRevenue | `Float` | Central Extra Revenue |
| 41 | centralFoodRevenue | `Float` | Central Food Revenue |
| 42 | centralGrossRate | `Float` | Central Gross Rate |
| 43 | centralNationalityCode | `String` | Central Nationality Code |
| 44 | centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| 45 | centralNonRevenue | `Float` | Central Non Revenue |
| 46 | centralOtherRevenue | `Float` | Central Other Revenue |
| 47 | centralRateCategory | `String` | Central Rate Category |
| 48 | centralRateClass | `String` | Central Rate Class |
| 49 | centralRoomClass | `String` | Central Room Class |
| 50 | centralRoomRevenue | `Float` | Central Room Revenue |
| 51 | centralRoomType | `String` | Central Room Type |
| 52 | centralTotalRevenue | `Float` | Central Total Revenue |
| 53 | centralcurrencyid | `String` | Centralcurrencyid |
| 54 | channelid | `String` | Channelid |
| 55 | children | `Float` | Children |
| 56 | childrenTaxFree | `Float` | Children Tax Free |
| 57 | children1 | `Float` | Children1 |
| 58 | children2 | `Float` | Children2 |
| 59 | children3 | `Float` | Children3 |
| 60 | children4 | `Float` | Children4 |
| 61 | children5 | `Float` | Children5 |
| 62 | city | `String` | City |
| 63 | consideredDate | `Date` | Considered Date |
| 64 | country | `String` | Country |
| 65 | countryCode | `String` | Country Code |
| 66 | countryid | `String` | Countryid |
| 67 | cribs | `Float` | Cribs |
| 68 | currencyCode | `String` | Currency Code |
| 69 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 70 | dayUsePersons | `Float` | Day Use Persons |
| 71 | dayUseRooms | `Float` | Day Use Rooms |
| 72 | dayUseYN | `String` | Day Use YN |
| 73 | departurePersons | `Float` | Departure Persons |
| 74 | departureRooms | `Float` | Departure Rooms |
| 75 | district | `String` | District |
| 76 | endDate | `Date` | End Date |
| 77 | eventID | `String` | Event ID |
| 78 | eventType | `String` | Event Type |
| 79 | exchangeDate | `Date` | Exchange Date |
| 80 | extraBeds | `Float` | Extra Beds |
| 81 | extraRevenue | `Float` | Extra Revenue |
| 82 | fcExtraRevenue | `Float` | FC Extra Revenue |
| 83 | fcFoodRevenue | `Float` | FC Food Revenue |
| 84 | fcFoodRevenueTax | `Float` | FC Food Revenue Tax |
| 85 | fcGrossRate | `Float` | FC Gross Rate |
| 86 | fcNetRoomRevenue | `Float` | FC Net Room Revenue |
| 87 | fcNonRevenue | `Float` | FC Non Revenue |
| 88 | fcNonRevenueTax | `Float` | FC Non Revenue Tax |
| 89 | fcOtherRevenue | `Float` | FC Other Revenue |
| 90 | fcOtherRevenueTax | `Float` | FC Other Revenue Tax |
| 91 | fcRoomRevenue | `Float` | FC Room Revenue |
| 92 | fcRoomRevenueTax | `Float` | FC Room Revenue Tax |
| 93 | fcTotalRevenue | `Float` | FC Total Revenue |
| 94 | fcTotalRevenueTax | `Float` | FC Total Revenue Tax |
| 95 | foodRevenue | `Float` | Food Revenue |
| 96 | foodRevenueTax | `Float` | Food Revenue Tax |
| 97 | gender | `String` | Gender |
| 98 | grossRate | `Float` | Gross Rate |
| 99 | groupId | `Float` | Group ID |
| 100 | id | `Float` | ID |
| 101 | internalConsidereddate | `Date` | Considereddate |
| 102 | jRNUpdateDate | `Date` | JRN Update Date |
| 103 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 104 | locationID | `String` | Internal ID to uniquely identify the Property |
| 105 | marketCode | `String` | Market Code |
| 106 | marketid | `String` | Marketid |
| 107 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 108 | nationalityCode | `String` | Nationality Code |
| 109 | nationalityid | `String` | Nationalityid |
| 110 | netRoomRevenue | `Float` | Net Room Revenue |
| 111 | nonRevenue | `Float` | Non Revenue |
| 112 | nonRevenueTax | `Float` | Non Revenue Tax |
| 113 | numberOfRooms | `Float` | Number of Rooms |
| 114 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 115 | originCode | `String` | Origin Code |
| 116 | otherRevenue | `Float` | Other Revenue |
| 117 | otherRevenueTax | `Float` | Other Revenue Tax |
| 118 | outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 119 | outOfServiceRooms | `Float` | Out of Service Rooms |
| 120 | ownerFfFlag | `String` | Owner Ff Flag |
| 121 | ownerRentalFlag | `String` | Owner Rental Flag |
| 122 | parentCompanyId | `Float` | Parent Company ID |
| 123 | parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| 124 | pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| 125 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 126 | property | `String` | Property |
| 127 | pseudoRoomYN | `String` | Pseudo Room YN |
| 128 | quantity | `Float` | Quantity |
| 129 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 130 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 131 | rateCategory | `String` | Rate Category |
| 132 | rateClass | `String` | Rate Class |
| 133 | rateCode | `String` | Rate Code |
| 134 | ratecategoryid | `String` | Ratecategoryid |
| 135 | rateclassid | `String` | Rateclassid |
| 136 | ratecodeid | `String` | Ratecodeid |
| 137 | regionCode | `String` | Region Code |
| 138 | regionDescription | `String` | Region Description |
| 139 | regionid | `String` | Regionid |
| 140 | remainingBlockRooms | `Float` | Remaining Block Rooms |
| 141 | resInsertSource | `String` | Reservation Insert Source |
| 142 | reservationInventoryType | `String` | Reservation Inventory Type |
| 143 | reservationStatus | `String` | Reservation Status |
| 144 | reservationType | `String` | Reservation Type |
| 145 | reservationdailytotalid | `Float` | Reservation Daily Total ID |
| 146 | reservationid | `Float` | Reservationid |
| 147 | roomCategoryNo | `String` | Room Category Number |
| 148 | roomClass | `String` | Room Class |
| 149 | roomRevenue | `Float` | Room Revenue |
| 150 | roomRevenueTax | `Float` | Room Revenue Tax |
| 151 | roomType | `String` | Room Type |
| 152 | roomcategoryid | `String` | Roomcategoryid |
| 153 | roomclassid | `String` | Roomclassid |
| 154 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 155 | sourceCode | `String` | Source Code |
| 156 | sourceProfId | `Float` | Source Prof ID |
| 157 | sourceid | `String` | Sourceid |
| 158 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 159 | startDate | `Date` | Start Date |
| 160 | state | `String` | State |
| 161 | systemDate | `DateTime` | System Date |
| 162 | totalRevenue | `Float` | Total Revenue |
| 163 | totalRevenueTax | `Float` | Total Revenue Tax |
| 164 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 165 | updateBusinessDate | `Date` | Update Business Date |
| 166 | vipStatus | `String` | VIP Status |
| 167 | vipgueststatusid | `String` | Vipgueststatusid |
| 168 | waitlistPersons | `Float` | Waitlist Persons |
| 169 | waitlistRooms | `Float` | Waitlist Rooms |
| 170 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### RatesClassesForecastSummaryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | agentId | `Float` | Agent ID |
| 4 | allotmentHeaderId | `Float` | Allotment Header ID |
| 5 | allotmentid | `Float` | Block ID |
| 6 | arrivalPersons | `Float` | Arrival Persons |
| 7 | arrivalRooms | `Float` | Arrival Rooms |
| 8 | blockStatus | `String` | Block Status |
| 9 | bookedRoomCategory | `String` | Booked Room Category |
| 10 | bookingStatus | `String` | Booking Status |
| 11 | bookingstatusid | `String` | Bookingstatusid |
| 12 | businessDateCreated | `Date` | Business Date Created |
| 13 | cDayUseNetRoomRevenue | `Float` | Central Day Use Net Room Revenue |
| 14 | cExchangeDate | `Date` | Central Xchange Date |
| 15 | cExchangeRate | `Float` | Central Xchange Rate |
| 16 | cFCExtraRevenue | `Float` | Central Fc Extra Revenue |
| 17 | cFCFoodRevenue | `Float` | Central Fc Food Revenue |
| 18 | cFCFoodRevenueTax | `Float` | Central Fc Food Revenue Tax |
| 19 | cFCGrossRate | `Float` | Central Fc Gross Rate |
| 20 | cFCNetRoomRevenue | `Float` | Central Fc Net Room Revenue |
| 21 | cFCNonRevenue | `Float` | Central Fc Non Revenue |
| 22 | cFCNonRevenueTax | `Float` | Central Fc Non Revenue Tax |
| 23 | cFCOtherRevenue | `Float` | Central Fc Other Revenue |
| 24 | cFCOtherRevenueTax | `Float` | Central Fc Other Revenue Tax |
| 25 | cFCRoomRevenue | `Float` | Central Fc Room Revenue |
| 26 | cFCRoomRevenueTax | `Float` | Central Fc Room Revenue Tax |
| 27 | cFCTotalRevenue | `Float` | Central Fc Total Revenue |
| 28 | cFCTotalRevenueTax | `Float` | Central Fc Total Revenue Tax |
| 29 | cFoodRevenueTax | `Float` | Central Food Revenue Tax |
| 30 | cNonRevenueTax | `Float` | Central Non Revenue Tax |
| 31 | cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 32 | cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 33 | cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 34 | centralCurrencyCode | `String` | Central Currency Code |
| 35 | centralDayUseExtraRevenue | `Float` | Central Day Use Extra Revenue |
| 36 | centralDayUseGrossRate | `Float` | Central Day Use Gross Rate |
| 37 | centralExchangeRate | `Float` | Central Exchange Rate |
| 38 | centralExtraRevenue | `Float` | Central Extra Revenue |
| 39 | centralFoodRevenue | `Float` | Central Food Revenue |
| 40 | centralGrossRate | `Float` | Central Gross Rate |
| 41 | centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| 42 | centralNonRevenue | `Float` | Central Non Revenue |
| 43 | centralOtherRevenue | `Float` | Central Other Revenue |
| 44 | centralRoomRevenue | `Float` | Central Room Revenue |
| 45 | centralRoomType | `String` | Central Room Type |
| 46 | centralTotalRevenue | `Float` | Central Total Revenue |
| 47 | centralWaitlistExtraRevenue | `Float` | Central Waitlist Extra Revenue |
| 48 | centralWaitlistGrossRate | `Float` | Central Waitlist Gross Rate |
| 49 | centralWaitlistNetRoomRevenue | `Float` | Central Waitlist Net Room Revenue |
| 50 | centralcurrencyid | `String` | Centralcurrencyid |
| 51 | channel | `String` | Channel |
| 52 | channelid | `String` | Channelid |
| 53 | children | `Float` | Children |
| 54 | childrenTaxFree | `Float` | Children Tax Free |
| 55 | children1 | `Float` | Children1 |
| 56 | children2 | `Float` | Children2 |
| 57 | children3 | `Float` | Children3 |
| 58 | children4 | `Float` | Children4 |
| 59 | children5 | `Float` | Children5 |
| 60 | city | `String` | City |
| 61 | considereddate | `Date` | Considereddate |
| 62 | country | `String` | Country |
| 63 | countryid | `String` | Countryid |
| 64 | cribs | `Float` | Cribs |
| 65 | currencyCode | `String` | Currency Code |
| 66 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 67 | dayUseExtraRevenue | `Float` | Day Use Extra Revenue |
| 68 | dayUseGrossRate | `Float` | Day Use Gross Rate |
| 69 | dayUseNetRoomRevenue | `Float` | Day Use Net Room Revenue |
| 70 | dayUsePersons | `Float` | Day Use Persons |
| 71 | dayUseRooms | `Float` | Day Use Rooms |
| 72 | dayUseYn | `String` | Day Use Y/N |
| 73 | departurePersons | `Float` | Departure Persons |
| 74 | departureRooms | `Float` | Departure Rooms |
| 75 | district | `String` | District |
| 76 | eventType | `String` | Event Type |
| 77 | exchangeDate | `Date` | Exchange Date |
| 78 | extraBeds | `Float` | Extra Beds |
| 79 | extraRevenue | `Float` | Extra Revenue |
| 80 | fcExtraRevenue | `Float` | FC Extra Revenue |
| 81 | fcFoodRevenue | `Float` | FC Food Revenue |
| 82 | fcFoodRevenueTax | `Float` | FC Food Revenue Tax |
| 83 | fcGrossRate | `Float` | FC Gross Rate |
| 84 | fcNetRoomRevenue | `Float` | FC Net Room Revenue |
| 85 | fcNonRevenue | `Float` | FC Non Revenue |
| 86 | fcNonRevenueTax | `Float` | FC Non Revenue Tax |
| 87 | fcOtherRevenue | `Float` | FC Other Revenue |
| 88 | fcOtherRevenueTax | `Float` | FC Other Revenue Tax |
| 89 | fcRoomRevenue | `Float` | FC Room Revenue |
| 90 | fcRoomRevenueTax | `Float` | FC Room Revenue Tax |
| 91 | fcTotalRevenue | `Float` | FC Total Revenue |
| 92 | fcTotalRevenueTax | `Float` | FC Total Revenue Tax |
| 93 | foodRevenue | `Float` | Food Revenue |
| 94 | foodRevenueTax | `Float` | Food Revenue Tax |
| 95 | gender | `String` | Gender |
| 96 | grossRate | `Float` | Gross Rate |
| 97 | groupId | `Float` | Group ID |
| 98 | id | `Float` | ID |
| 99 | jRNUpdateDate | `Date` | JRN Update Date |
| 100 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 101 | locationID | `String` | Internal ID to uniquely identify the Property |
| 102 | marketCode | `String` | Market Code |
| 103 | marketid | `String` | Marketid |
| 104 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 105 | nationality | `String` | Nationality |
| 106 | nationalityid | `String` | Nationalityid |
| 107 | netRoomRevenue | `Float` | Net Room Revenue |
| 108 | nonRevenue | `Float` | Non Revenue |
| 109 | nonRevenueTax | `Float` | Non Revenue Tax |
| 110 | numberOfGuests | `Float` | Number of Guests |
| 111 | numberOfRooms | `Float` | Number of Rooms |
| 112 | oooRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 113 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 114 | osRooms | `Float` | Os Rooms |
| 115 | otherRevenue | `Float` | Other Revenue |
| 116 | otherRevenueTax | `Float` | Other Revenue Tax |
| 117 | ownerFfFlag | `String` | Owner Ff Flag |
| 118 | ownerRentalFlag | `String` | Owner Rental Flag |
| 119 | parentCompanyId | `Float` | Parent Company ID |
| 120 | parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| 121 | pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| 122 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 123 | property | `String` | Code to uniquely identify the Property |
| 124 | pseudoRoomYN | `String` | Pseudo Room YN |
| 125 | quantity | `Float` | Quantity |
| 126 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 127 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 128 | rateCategory | `String` | Rate Category |
| 129 | rateClass | `String` | Rate Class |
| 130 | rateCode | `String` | Rate Code |
| 131 | ratecategoryid | `String` | Ratecategoryid |
| 132 | rateclassid | `String` | Rateclassid |
| 133 | ratecodeid | `String` | Ratecodeid |
| 134 | regionCode | `String` | Region Code |
| 135 | regionid | `String` | Regionid |
| 136 | remainingBlockRooms | `Float` | Remaining Block Rooms |
| 137 | resInsertSource | `String` | Reservation Insert Source |
| 138 | reservationInventoryType | `String` | Reservation Inventory Type |
| 139 | reservationType | `String` | Reservation Type |
| 140 | reservationdailytotalid | `Float` | Reservation Daily Total ID |
| 141 | reservationid | `String` | Reservationid |
| 142 | resvStatus | `String` | Reservation Status |
| 143 | roomCategory | `String` | Room Category |
| 144 | roomClass | `String` | Room Class |
| 145 | roomRevenue | `Float` | Room Revenue |
| 146 | roomRevenueTax | `Float` | Room Revenue Tax |
| 147 | roomType | `String` | Room Type |
| 148 | roomclassid | `String` | Roomclassid |
| 149 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 150 | sourceCode | `String` | Source Code |
| 151 | sourceProfId | `Float` | Source Prof ID |
| 152 | sourceid | `String` | Sourceid |
| 153 | state | `String` | State |
| 154 | stayDate | `Date` | Stay Date |
| 155 | totalRevenue | `Float` | Total Revenue |
| 156 | totalRevenueTax | `Float` | Total Revenue Tax |
| 157 | truncEndDate | `Date` | Trunc End Date |
| 158 | truncStartDate | `Date` | Trunc Start Date |
| 159 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 160 | updateBusinessDate | `Date` | Update Business Date |
| 161 | updateDate | `DateTime` | Update Date |
| 162 | vipStatus | `String` | VIP Status |
| 163 | waitlistExtraRevenue | `Float` | Waitlist Extra Revenue |
| 164 | waitlistGrossRate | `Float` | Waitlist Gross Rate |
| 165 | waitlistNetRoomRevenue | `Float` | Waitlist Net Room Revenue |
| 166 | waitlistPersons | `Float` | Waitlist Persons |
| 167 | waitlistRooms | `Float` | Waitlist Rooms |
| 168 | zipCode | `String` | Zipcode Code |

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

### RatesClassesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| rateclassesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| rateclassesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rateclassesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| rateclassesDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| rateclassesDetailsRateClass | `StringInput` | Rate Class |
| rateclassesDetailsResortResort | `StringInput` | Property code |
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
| resvsummaryDetailsConsideredDate | `DateInput` | Considered Date |
| resvsummaryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvsummaryDetailsEventType | `StringInput` | Event Type |
| resvsummaryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvsummaryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvsummaryDetailsResort | `StringInput` | Property |
| resvsummaryDetailsRoomCategory | `StringInput` | Room Type |
| forecastsummaryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| forecastsummaryDetailsEventType | `StringInput` | Event Type |
| forecastsummaryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| forecastsummaryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| forecastsummaryDetailsResort | `StringInput` | Code to uniquely identify the Property |
| forecastsummaryDetailsRoomCategory | `StringInput` | Room Category |
| forecastsummaryDetailsConsideredDate | `DateInput` | Stay Date |
#### Validation Rules

**`mandatoryInput`**
- rateclassesDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query ratesClasses($input: RatesClassesQueryArgumentsType!) {
  ratesClasses(input: $input) @stream {
    rateClassesDetails {
      centralRateClass
      centralRateClassDescription
      dSI
      deletedflag
      displaySequence
      endDate
      inactiveDate
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rateClass
      rateClassDescription
      rateClassId
      repItem
      repItemName
      repItemOrderby
      repSellSequence
      repUpdateDate
      resortResort
      rnaInsertDate
      rnaUpdateDate
      startDate
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
    reservationSummaryDetails {
      adults
      adultsTaxFree
      agentId
      allotmentHeaderId
      allotmentid
      arrivalPersons
      arrivalRooms
      blockEndDate
      blockStatus
      bookedRoomCategory
      bookedroomcategoryid
      bookingStatus
      bookingStatusDescription
      bookingstatusid
      businessDateCreated
      cExchangeDate
      cExchangeRate
      cFCExtraRevenue
      cFCFoodRevenue
      cFCFoodRevenueTax
      cFCGrossRate
      cFCNetRoomRevenue
      cFCNonRevenue
      cFCNonRevenueTax
      cFCOtherRevenue
      cFCOtherRevenueTax
      cFCRoomRevenue
      cFCRoomRevenueTax
      cFCTotalRevenue
      cFCTotalRevenueTax
      cFoodRevenueTax
      cNonRevenueTax
      cOtherRevenueTax
      cRoomRevenueTax
      cTotalRevenueTax
      cRSExchangeRate
      centralBookingStatus
      centralBookingStatusDescription
      centralCurrencyCode
      centralExtraRevenue
      centralFoodRevenue
      centralGrossRate
      centralNationalityCode
      centralNetRoomRevenue
      centralNonRevenue
      centralOtherRevenue
      centralRateCategory
      centralRateClass
      centralRoomClass
      centralRoomRevenue
      centralRoomType
      centralTotalRevenue
      centralcurrencyid
      channelid
      children
      childrenTaxFree
      children1
      children2
      children3
      children4
      children5
      city
      consideredDate
      country
      countryCode
      countryid
      cribs
      currencyCode
      dSI
      dayUsePersons
      dayUseRooms
      dayUseYN
      departurePersons
      departureRooms
      district
      endDate
      eventID
      eventType
      exchangeDate
      extraBeds
      extraRevenue
      fcExtraRevenue
      fcFoodRevenue
      fcFoodRevenueTax
      fcGrossRate
      fcNetRoomRevenue
      fcNonRevenue
      fcNonRevenueTax
      fcOtherRevenue
      fcOtherRevenueTax
      fcRoomRevenue
      fcRoomRevenueTax
      fcTotalRevenue
      fcTotalRevenueTax
      foodRevenue
      foodRevenueTax
      gender
      grossRate
      groupId
      id
      internalConsidereddate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketid
      multipleOccupancyRooms
      nationalityCode
      nationalityid
      netRoomRevenue
      nonRevenue
      nonRevenueTax
      numberOfRooms
      organizationID
      originCode
      otherRevenue
      otherRevenueTax
      outOfOrderRooms
      outOfServiceRooms
      ownerFfFlag
      ownerRentalFlag
      parentCompanyId
      parentcompanyprofileid
      pickedUpBlockRooms
      primaryKeyID
      property
      pseudoRoomYN
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCategory
      rateClass
      rateCode
      ratecategoryid
      rateclassid
      ratecodeid
      regionCode
      regionDescription
      regionid
      remainingBlockRooms
      resInsertSource
      reservationInventoryType
      reservationStatus
      reservationType
      reservationdailytotalid
      reservationid
      roomCategoryNo
      roomClass
      roomRevenue
      roomRevenueTax
      roomType
      roomcategoryid
      roomclassid
      singleOccupancyRooms
      sourceCode
      sourceProfId
      sourceid
      sourceprofprofileid
      startDate
      state
      systemDate
      totalRevenue
      totalRevenueTax
      turndownStatus
      updateBusinessDate
      vipStatus
      vipgueststatusid
      waitlistPersons
      waitlistRooms
      zipCode
    }
    forecastSummaryDetails {
      adults
      adultsTaxFree
      agentId
      allotmentHeaderId
      allotmentid
      arrivalPersons
      arrivalRooms
      blockStatus
      bookedRoomCategory
      bookingStatus
      bookingstatusid
      businessDateCreated
      cDayUseNetRoomRevenue
      cExchangeDate
      cExchangeRate
      cFCExtraRevenue
      cFCFoodRevenue
      cFCFoodRevenueTax
      cFCGrossRate
      cFCNetRoomRevenue
      cFCNonRevenue
      cFCNonRevenueTax
      cFCOtherRevenue
      cFCOtherRevenueTax
      cFCRoomRevenue
      cFCRoomRevenueTax
      cFCTotalRevenue
      cFCTotalRevenueTax
      cFoodRevenueTax
      cNonRevenueTax
      cOtherRevenueTax
      cRoomRevenueTax
      cTotalRevenueTax
      centralCurrencyCode
      centralDayUseExtraRevenue
      centralDayUseGrossRate
      centralExchangeRate
      centralExtraRevenue
      centralFoodRevenue
      centralGrossRate
      centralNetRoomRevenue
      centralNonRevenue
      centralOtherRevenue
      centralRoomRevenue
      centralRoomType
      centralTotalRevenue
      centralWaitlistExtraRevenue
      centralWaitlistGrossRate
      centralWaitlistNetRoomRevenue
      centralcurrencyid
      channel
      channelid
      children
      childrenTaxFree
      children1
      children2
      children3
      children4
      children5
      city
      considereddate
      country
      countryid
      cribs
      currencyCode
      dSI
      dayUseExtraRevenue
      dayUseGrossRate
      dayUseNetRoomRevenue
      dayUsePersons
      dayUseRooms
      dayUseYn
      departurePersons
      departureRooms
      district
      eventType
      exchangeDate
      extraBeds
      extraRevenue
      fcExtraRevenue
      fcFoodRevenue
      fcFoodRevenueTax
      fcGrossRate
      fcNetRoomRevenue
      fcNonRevenue
      fcNonRevenueTax
      fcOtherRevenue
      fcOtherRevenueTax
      fcRoomRevenue
      fcRoomRevenueTax
      fcTotalRevenue
      fcTotalRevenueTax
      foodRevenue
      foodRevenueTax
      gender
      grossRate
      groupId
      id
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketid
      multipleOccupancyRooms
      nationality
      nationalityid
      netRoomRevenue
      nonRevenue
      nonRevenueTax
      numberOfGuests
      numberOfRooms
      oooRooms
      organizationID
      osRooms
      otherRevenue
      otherRevenueTax
      ownerFfFlag
      ownerRentalFlag
      parentCompanyId
      parentcompanyprofileid
      pickedUpBlockRooms
      primaryKeyID
      property
      pseudoRoomYN
      quantity
      rNAInsertDate
      rNAUpdateDate
      rateCategory
      rateClass
      rateCode
      ratecategoryid
      rateclassid
      ratecodeid
      regionCode
      regionid
      remainingBlockRooms
      resInsertSource
      reservationInventoryType
      reservationType
      reservationdailytotalid
      reservationid
      resvStatus
      roomCategory
      roomClass
      roomRevenue
      roomRevenueTax
      roomType
      roomclassid
      singleOccupancyRooms
      sourceCode
      sourceProfId
      sourceid
      state
      stayDate
      totalRevenue
      totalRevenueTax
      truncEndDate
      truncStartDate
      turndownStatus
      updateBusinessDate
      updateDate
      vipStatus
      waitlistExtraRevenue
      waitlistGrossRate
      waitlistNetRoomRevenue
      waitlistPersons
      waitlistRooms
      zipCode
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
rate_classes_details_schema = {
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displaySequence': pl.Float64,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateClassDescription': pl.Utf8,
    'rateClassId': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'resortResort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'startDate': pl.Utf8,
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
reservation_summary_details_schema = {
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'agentId': pl.Float64,
    'allotmentHeaderId': pl.Float64,
    'allotmentid': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalRooms': pl.Float64,
    'blockEndDate': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'bookingStatus': pl.Utf8,
    'bookingStatusDescription': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFCExtraRevenue': pl.Float64,
    'cFCFoodRevenue': pl.Float64,
    'cFCFoodRevenueTax': pl.Float64,
    'cFCGrossRate': pl.Float64,
    'cFCNetRoomRevenue': pl.Float64,
    'cFCNonRevenue': pl.Float64,
    'cFCNonRevenueTax': pl.Float64,
    'cFCOtherRevenue': pl.Float64,
    'cFCOtherRevenueTax': pl.Float64,
    'cFCRoomRevenue': pl.Float64,
    'cFCRoomRevenueTax': pl.Float64,
    'cFCTotalRevenue': pl.Float64,
    'cFCTotalRevenueTax': pl.Float64,
    'cFoodRevenueTax': pl.Float64,
    'cNonRevenueTax': pl.Float64,
    'cOtherRevenueTax': pl.Float64,
    'cRoomRevenueTax': pl.Float64,
    'cTotalRevenueTax': pl.Float64,
    'cRSExchangeRate': pl.Float64,
    'centralBookingStatus': pl.Utf8,
    'centralBookingStatusDescription': pl.Utf8,
    'centralCurrencyCode': pl.Utf8,
    'centralExtraRevenue': pl.Float64,
    'centralFoodRevenue': pl.Float64,
    'centralGrossRate': pl.Float64,
    'centralNationalityCode': pl.Utf8,
    'centralNetRoomRevenue': pl.Float64,
    'centralNonRevenue': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRateCategory': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomType': pl.Utf8,
    'centralTotalRevenue': pl.Float64,
    'centralcurrencyid': pl.Utf8,
    'channelid': pl.Utf8,
    'children': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'city': pl.Utf8,
    'consideredDate': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryid': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dayUsePersons': pl.Float64,
    'dayUseRooms': pl.Float64,
    'dayUseYN': pl.Utf8,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'district': pl.Utf8,
    'endDate': pl.Utf8,
    'eventID': pl.Utf8,
    'eventType': pl.Utf8,
    'exchangeDate': pl.Utf8,
    'extraBeds': pl.Float64,
    'extraRevenue': pl.Float64,
    'fcExtraRevenue': pl.Float64,
    'fcFoodRevenue': pl.Float64,
    'fcFoodRevenueTax': pl.Float64,
    'fcGrossRate': pl.Float64,
    'fcNetRoomRevenue': pl.Float64,
    'fcNonRevenue': pl.Float64,
    'fcNonRevenueTax': pl.Float64,
    'fcOtherRevenue': pl.Float64,
    'fcOtherRevenueTax': pl.Float64,
    'fcRoomRevenue': pl.Float64,
    'fcRoomRevenueTax': pl.Float64,
    'fcTotalRevenue': pl.Float64,
    'fcTotalRevenueTax': pl.Float64,
    'foodRevenue': pl.Float64,
    'foodRevenueTax': pl.Float64,
    'gender': pl.Utf8,
    'grossRate': pl.Float64,
    'groupId': pl.Float64,
    'id': pl.Float64,
    'internalConsidereddate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'multipleOccupancyRooms': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityid': pl.Utf8,
    'netRoomRevenue': pl.Float64,
    'nonRevenue': pl.Float64,
    'nonRevenueTax': pl.Float64,
    'numberOfRooms': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'outOfOrderRooms': pl.Float64,
    'outOfServiceRooms': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerRentalFlag': pl.Utf8,
    'parentCompanyId': pl.Float64,
    'parentcompanyprofileid': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecategoryid': pl.Utf8,
    'rateclassid': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionDescription': pl.Utf8,
    'regionid': pl.Utf8,
    'remainingBlockRooms': pl.Float64,
    'resInsertSource': pl.Utf8,
    'reservationInventoryType': pl.Utf8,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationdailytotalid': pl.Float64,
    'reservationid': pl.Float64,
    'roomCategoryNo': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'roomType': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomclassid': pl.Utf8,
    'singleOccupancyRooms': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceProfId': pl.Float64,
    'sourceid': pl.Utf8,
    'sourceprofprofileid': pl.Float64,
    'startDate': pl.Utf8,
    'state': pl.Utf8,
    'systemDate': pl.Utf8,
    'totalRevenue': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'turndownStatus': pl.Utf8,
    'updateBusinessDate': pl.Utf8,
    'vipStatus': pl.Utf8,
    'vipgueststatusid': pl.Utf8,
    'waitlistPersons': pl.Float64,
    'waitlistRooms': pl.Float64,
    'zipCode': pl.Utf8,
}
```
```python
forecast_summary_details_schema = {
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'agentId': pl.Float64,
    'allotmentHeaderId': pl.Float64,
    'allotmentid': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalRooms': pl.Float64,
    'blockStatus': pl.Utf8,
    'bookedRoomCategory': pl.Utf8,
    'bookingStatus': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'cDayUseNetRoomRevenue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFCExtraRevenue': pl.Float64,
    'cFCFoodRevenue': pl.Float64,
    'cFCFoodRevenueTax': pl.Float64,
    'cFCGrossRate': pl.Float64,
    'cFCNetRoomRevenue': pl.Float64,
    'cFCNonRevenue': pl.Float64,
    'cFCNonRevenueTax': pl.Float64,
    'cFCOtherRevenue': pl.Float64,
    'cFCOtherRevenueTax': pl.Float64,
    'cFCRoomRevenue': pl.Float64,
    'cFCRoomRevenueTax': pl.Float64,
    'cFCTotalRevenue': pl.Float64,
    'cFCTotalRevenueTax': pl.Float64,
    'cFoodRevenueTax': pl.Float64,
    'cNonRevenueTax': pl.Float64,
    'cOtherRevenueTax': pl.Float64,
    'cRoomRevenueTax': pl.Float64,
    'cTotalRevenueTax': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralDayUseExtraRevenue': pl.Float64,
    'centralDayUseGrossRate': pl.Float64,
    'centralExchangeRate': pl.Float64,
    'centralExtraRevenue': pl.Float64,
    'centralFoodRevenue': pl.Float64,
    'centralGrossRate': pl.Float64,
    'centralNetRoomRevenue': pl.Float64,
    'centralNonRevenue': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomType': pl.Utf8,
    'centralTotalRevenue': pl.Float64,
    'centralWaitlistExtraRevenue': pl.Float64,
    'centralWaitlistGrossRate': pl.Float64,
    'centralWaitlistNetRoomRevenue': pl.Float64,
    'centralcurrencyid': pl.Utf8,
    'channel': pl.Utf8,
    'channelid': pl.Utf8,
    'children': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'city': pl.Utf8,
    'considereddate': pl.Utf8,
    'country': pl.Utf8,
    'countryid': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dayUseExtraRevenue': pl.Float64,
    'dayUseGrossRate': pl.Float64,
    'dayUseNetRoomRevenue': pl.Float64,
    'dayUsePersons': pl.Float64,
    'dayUseRooms': pl.Float64,
    'dayUseYn': pl.Utf8,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'district': pl.Utf8,
    'eventType': pl.Utf8,
    'exchangeDate': pl.Utf8,
    'extraBeds': pl.Float64,
    'extraRevenue': pl.Float64,
    'fcExtraRevenue': pl.Float64,
    'fcFoodRevenue': pl.Float64,
    'fcFoodRevenueTax': pl.Float64,
    'fcGrossRate': pl.Float64,
    'fcNetRoomRevenue': pl.Float64,
    'fcNonRevenue': pl.Float64,
    'fcNonRevenueTax': pl.Float64,
    'fcOtherRevenue': pl.Float64,
    'fcOtherRevenueTax': pl.Float64,
    'fcRoomRevenue': pl.Float64,
    'fcRoomRevenueTax': pl.Float64,
    'fcTotalRevenue': pl.Float64,
    'fcTotalRevenueTax': pl.Float64,
    'foodRevenue': pl.Float64,
    'foodRevenueTax': pl.Float64,
    'gender': pl.Utf8,
    'grossRate': pl.Float64,
    'groupId': pl.Float64,
    'id': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'multipleOccupancyRooms': pl.Float64,
    'nationality': pl.Utf8,
    'nationalityid': pl.Utf8,
    'netRoomRevenue': pl.Float64,
    'nonRevenue': pl.Float64,
    'nonRevenueTax': pl.Float64,
    'numberOfGuests': pl.Float64,
    'numberOfRooms': pl.Float64,
    'oooRooms': pl.Float64,
    'organizationID': pl.Int64,
    'osRooms': pl.Float64,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerRentalFlag': pl.Utf8,
    'parentCompanyId': pl.Float64,
    'parentcompanyprofileid': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecategoryid': pl.Utf8,
    'rateclassid': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionid': pl.Utf8,
    'remainingBlockRooms': pl.Float64,
    'resInsertSource': pl.Utf8,
    'reservationInventoryType': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationdailytotalid': pl.Float64,
    'reservationid': pl.Utf8,
    'resvStatus': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'roomType': pl.Utf8,
    'roomclassid': pl.Utf8,
    'singleOccupancyRooms': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceProfId': pl.Float64,
    'sourceid': pl.Utf8,
    'state': pl.Utf8,
    'stayDate': pl.Utf8,
    'totalRevenue': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'truncEndDate': pl.Utf8,
    'truncStartDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'updateBusinessDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'vipStatus': pl.Utf8,
    'waitlistExtraRevenue': pl.Float64,
    'waitlistGrossRate': pl.Float64,
    'waitlistNetRoomRevenue': pl.Float64,
    'waitlistPersons': pl.Float64,
    'waitlistRooms': pl.Float64,
    'zipCode': pl.Utf8,
}
```