# RevenueFixedCharges
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `revenueFixedCharges`
> Details on fixed charges including amount frequency and transaction code and the linked reservations.
  
**Return:** [`[RevenueFixedChargesType]`](#revenuefixedchargestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`RevenueFixedChargesQueryArgumentsType!`](#revenuefixedchargesqueryargumentstype) |  |

## Object Types

### RevenueFixedChargesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | fixedChargesDetails | [`RevenueFixedChargesFixedChargesDetailsType`](#revenuefixedchargesfixedchargesdetailstype) | Fixed Charges Details |
| 2 | propertyPropertyDetails | [`RevenueFixedChargesPropertyPropertyDetailsType`](#revenuefixedchargespropertypropertydetailstype) | Resort Details |
| 3 | reservationDetails | [`RevenueFixedChargesReservationDetailsType`](#revenuefixedchargesreservationdetailstype) | Reservation Details |
| 4 | revenueFixedChargesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RevenueFixedChargesFixedChargesDetailsType

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

### RevenueFixedChargesPropertyPropertyDetailsType

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

### RevenueFixedChargesReservationDetailsType

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

### RevenueFixedChargesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| fixedchargesDetailsAccountCode | `FloatInput` | Account Code |
| fixedchargesDetailsAccountid | `FloatInput` | Accountid |
| fixedchargesDetailsFixedchargestartdate | `DateInput!` | Business Date<br>`@mandatoryInput` |
| fixedchargesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| fixedchargesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fixedchargesDetailsFixedchargeenddate | `DateInput!` | End Date<br>`@mandatoryInput` |
| fixedchargesDetailsFixedChargesId | `FloatInput` | Unique number to identify the entry. |
| fixedchargesDetailsFixedchargespmsref | `FloatInput` | Fixedchargespmsref |
| fixedchargesDetailsFixedchargesid | `FloatInput` | Fixedchargesid |
| fixedchargesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fixedchargesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| fixedchargesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fixedchargesDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| fixedchargesDetailsResvNameId | `FloatInput` | Resv Name ID |
| fixedchargesDetailsReservationid | `FloatInput` | Reservationid |
| fixedchargesDetailsTransactionCode | `StringInput` | Rate transaction code |
| fixedchargesDetailsTranscodeid | `StringInput` | Transcodeid |
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
#### Validation Rules

**`mandatoryInput`**
- fixedchargesDetailsFixedchargestartdate
- fixedchargesDetailsFixedchargeenddate
- fixedchargesDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query revenueFixedCharges($input: RevenueFixedChargesQueryArgumentsType!) {
  revenueFixedCharges(input: $input) @stream {
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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