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

| Field | Type | Description |
| --- | --- | --- |
| rateClassesDetails | [`RatesClassesRateClassesDetailsType`](#ratesclassesrateclassesdetailstype) | Rate Classes Details |
| propertyPropertyDetails | [`RatesClassesPropertyPropertyDetailsType`](#ratesclassespropertypropertydetailstype) | Resort Details |
| reservationSummaryDetails | [`RatesClassesReservationSummaryDetailsType`](#ratesclassesreservationsummarydetailstype) | Reservation Summary |
| forecastSummaryDetails | [`RatesClassesForecastSummaryDetailsType`](#ratesclassesforecastsummarydetailstype) | Forecast Summary Details |
| ratesClassesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### RatesClassesRateClassesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displaySequence | `Float` | Display Sequence |
| endDate | `Date` | End Date |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rateClass | `String` | Rate Class |
| rateClassDescription | `String` | Rate Class Description |
| rateClassId | `String` | Rate Class ID |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repSellSequence | `Float` | Reporting Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| resortResort | `String` | Property code |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### RatesClassesPropertyPropertyDetailsType

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

### RatesClassesReservationSummaryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| agentId | `Float` | Agent ID |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentid | `Float` | Block ID |
| arrivalPersons | `Float` | Arrival Persons |
| arrivalRooms | `Float` | Arrival Rooms |
| blockEndDate | `Date` | Block End Date |
| blockStatus | `String` | Block Status |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| bookingStatus | `String` | Booking Status |
| bookingStatusDescription | `String` | Booking Status Description |
| bookingstatusid | `String` | Bookingstatusid |
| businessDateCreated | `Date` | Business Date Created |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFCExtraRevenue | `Float` | Central Fc Extra Revenue |
| cFCFoodRevenue | `Float` | Central Fc Food Revenue |
| cFCFoodRevenueTax | `Float` | Central Fc Food Revenue Tax |
| cFCGrossRate | `Float` | Central Fc Gross Rate |
| cFCNetRoomRevenue | `Float` | Central Fc Net Room Revenue |
| cFCNonRevenue | `Float` | Central Fc Non Revenue |
| cFCNonRevenueTax | `Float` | Central Fc Non Revenue Tax |
| cFCOtherRevenue | `Float` | Central Fc Other Revenue |
| cFCOtherRevenueTax | `Float` | Central Fc Other Revenue Tax |
| cFCRoomRevenue | `Float` | Central Fc Room Revenue |
| cFCRoomRevenueTax | `Float` | Central Fc Room Revenue Tax |
| cFCTotalRevenue | `Float` | Central Fc Total Revenue |
| cFCTotalRevenueTax | `Float` | Central Fc Total Revenue Tax |
| cFoodRevenueTax | `Float` | Central Food Revenue Tax |
| cNonRevenueTax | `Float` | Central Non Revenue Tax |
| cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| cRSExchangeRate | `Float` | CRS Exchange Rate |
| centralBookingStatus | `String` | Central Booking Status |
| centralBookingStatusDescription | `String` | Central Booking Status Description |
| centralCurrencyCode | `String` | Central Currency Code |
| centralExtraRevenue | `Float` | Central Extra Revenue |
| centralFoodRevenue | `Float` | Central Food Revenue |
| centralGrossRate | `Float` | Central Gross Rate |
| centralNationalityCode | `String` | Central Nationality Code |
| centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| centralNonRevenue | `Float` | Central Non Revenue |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralRateCategory | `String` | Central Rate Category |
| centralRateClass | `String` | Central Rate Class |
| centralRoomClass | `String` | Central Room Class |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomType | `String` | Central Room Type |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralcurrencyid | `String` | Centralcurrencyid |
| channelid | `String` | Channelid |
| children | `Float` | Children |
| childrenTaxFree | `Float` | Children Tax Free |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| city | `String` | City |
| consideredDate | `Date` | Considered Date |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryid | `String` | Countryid |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUsePersons | `Float` | Day Use Persons |
| dayUseRooms | `Float` | Day Use Rooms |
| dayUseYN | `String` | Day Use YN |
| departurePersons | `Float` | Departure Persons |
| departureRooms | `Float` | Departure Rooms |
| district | `String` | District |
| endDate | `Date` | End Date |
| eventID | `String` | Event ID |
| eventType | `String` | Event Type |
| exchangeDate | `Date` | Exchange Date |
| extraBeds | `Float` | Extra Beds |
| extraRevenue | `Float` | Extra Revenue |
| fcExtraRevenue | `Float` | FC Extra Revenue |
| fcFoodRevenue | `Float` | FC Food Revenue |
| fcFoodRevenueTax | `Float` | FC Food Revenue Tax |
| fcGrossRate | `Float` | FC Gross Rate |
| fcNetRoomRevenue | `Float` | FC Net Room Revenue |
| fcNonRevenue | `Float` | FC Non Revenue |
| fcNonRevenueTax | `Float` | FC Non Revenue Tax |
| fcOtherRevenue | `Float` | FC Other Revenue |
| fcOtherRevenueTax | `Float` | FC Other Revenue Tax |
| fcRoomRevenue | `Float` | FC Room Revenue |
| fcRoomRevenueTax | `Float` | FC Room Revenue Tax |
| fcTotalRevenue | `Float` | FC Total Revenue |
| fcTotalRevenueTax | `Float` | FC Total Revenue Tax |
| foodRevenue | `Float` | Food Revenue |
| foodRevenueTax | `Float` | Food Revenue Tax |
| gender | `String` | Gender |
| grossRate | `Float` | Gross Rate |
| groupId | `Float` | Group ID |
| id | `Float` | ID |
| internalConsidereddate | `Date` | Considereddate |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| nationalityCode | `String` | Nationality Code |
| nationalityid | `String` | Nationalityid |
| netRoomRevenue | `Float` | Net Room Revenue |
| nonRevenue | `Float` | Non Revenue |
| nonRevenueTax | `Float` | Non Revenue Tax |
| numberOfRooms | `Float` | Number of Rooms |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| otherRevenue | `Float` | Other Revenue |
| otherRevenueTax | `Float` | Other Revenue Tax |
| outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| outOfServiceRooms | `Float` | Out of Service Rooms |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerRentalFlag | `String` | Owner Rental Flag |
| parentCompanyId | `Float` | Parent Company ID |
| parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| quantity | `Float` | Quantity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCategory | `String` | Rate Category |
| rateClass | `String` | Rate Class |
| rateCode | `String` | Rate Code |
| ratecategoryid | `String` | Ratecategoryid |
| rateclassid | `String` | Rateclassid |
| ratecodeid | `String` | Ratecodeid |
| regionCode | `String` | Region Code |
| regionDescription | `String` | Region Description |
| regionid | `String` | Regionid |
| remainingBlockRooms | `Float` | Remaining Block Rooms |
| resInsertSource | `String` | Reservation Insert Source |
| reservationInventoryType | `String` | Reservation Inventory Type |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationdailytotalid | `Float` | Reservation Daily Total ID |
| reservationid | `Float` | Reservationid |
| roomCategoryNo | `String` | Room Category Number |
| roomClass | `String` | Room Class |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueTax | `Float` | Room Revenue Tax |
| roomType | `String` | Room Type |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| sourceCode | `String` | Source Code |
| sourceProfId | `Float` | Source Prof ID |
| sourceid | `String` | Sourceid |
| sourceprofprofileid | `Float` | Sourceprofprofileid |
| startDate | `Date` | Start Date |
| state | `String` | State |
| systemDate | `DateTime` | System Date |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueTax | `Float` | Total Revenue Tax |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| updateBusinessDate | `Date` | Update Business Date |
| vipStatus | `String` | VIP Status |
| vipgueststatusid | `String` | Vipgueststatusid |
| waitlistPersons | `Float` | Waitlist Persons |
| waitlistRooms | `Float` | Waitlist Rooms |
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### RatesClassesForecastSummaryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| agentId | `Float` | Agent ID |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentid | `Float` | Block ID |
| arrivalPersons | `Float` | Arrival Persons |
| arrivalRooms | `Float` | Arrival Rooms |
| blockStatus | `String` | Block Status |
| bookedRoomCategory | `String` | Booked Room Category |
| bookingStatus | `String` | Booking Status |
| bookingstatusid | `String` | Bookingstatusid |
| businessDateCreated | `Date` | Business Date Created |
| cDayUseNetRoomRevenue | `Float` | Central Day Use Net Room Revenue |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFCExtraRevenue | `Float` | Central Fc Extra Revenue |
| cFCFoodRevenue | `Float` | Central Fc Food Revenue |
| cFCFoodRevenueTax | `Float` | Central Fc Food Revenue Tax |
| cFCGrossRate | `Float` | Central Fc Gross Rate |
| cFCNetRoomRevenue | `Float` | Central Fc Net Room Revenue |
| cFCNonRevenue | `Float` | Central Fc Non Revenue |
| cFCNonRevenueTax | `Float` | Central Fc Non Revenue Tax |
| cFCOtherRevenue | `Float` | Central Fc Other Revenue |
| cFCOtherRevenueTax | `Float` | Central Fc Other Revenue Tax |
| cFCRoomRevenue | `Float` | Central Fc Room Revenue |
| cFCRoomRevenueTax | `Float` | Central Fc Room Revenue Tax |
| cFCTotalRevenue | `Float` | Central Fc Total Revenue |
| cFCTotalRevenueTax | `Float` | Central Fc Total Revenue Tax |
| cFoodRevenueTax | `Float` | Central Food Revenue Tax |
| cNonRevenueTax | `Float` | Central Non Revenue Tax |
| cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| centralCurrencyCode | `String` | Central Currency Code |
| centralDayUseExtraRevenue | `Float` | Central Day Use Extra Revenue |
| centralDayUseGrossRate | `Float` | Central Day Use Gross Rate |
| centralExchangeRate | `Float` | Central Exchange Rate |
| centralExtraRevenue | `Float` | Central Extra Revenue |
| centralFoodRevenue | `Float` | Central Food Revenue |
| centralGrossRate | `Float` | Central Gross Rate |
| centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| centralNonRevenue | `Float` | Central Non Revenue |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomType | `String` | Central Room Type |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralWaitlistExtraRevenue | `Float` | Central Waitlist Extra Revenue |
| centralWaitlistGrossRate | `Float` | Central Waitlist Gross Rate |
| centralWaitlistNetRoomRevenue | `Float` | Central Waitlist Net Room Revenue |
| centralcurrencyid | `String` | Centralcurrencyid |
| channel | `String` | Channel |
| channelid | `String` | Channelid |
| children | `Float` | Children |
| childrenTaxFree | `Float` | Children Tax Free |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| city | `String` | City |
| considereddate | `Date` | Considereddate |
| country | `String` | Country |
| countryid | `String` | Countryid |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUseExtraRevenue | `Float` | Day Use Extra Revenue |
| dayUseGrossRate | `Float` | Day Use Gross Rate |
| dayUseNetRoomRevenue | `Float` | Day Use Net Room Revenue |
| dayUsePersons | `Float` | Day Use Persons |
| dayUseRooms | `Float` | Day Use Rooms |
| dayUseYn | `String` | Day Use Y/N |
| departurePersons | `Float` | Departure Persons |
| departureRooms | `Float` | Departure Rooms |
| district | `String` | District |
| eventType | `String` | Event Type |
| exchangeDate | `Date` | Exchange Date |
| extraBeds | `Float` | Extra Beds |
| extraRevenue | `Float` | Extra Revenue |
| fcExtraRevenue | `Float` | FC Extra Revenue |
| fcFoodRevenue | `Float` | FC Food Revenue |
| fcFoodRevenueTax | `Float` | FC Food Revenue Tax |
| fcGrossRate | `Float` | FC Gross Rate |
| fcNetRoomRevenue | `Float` | FC Net Room Revenue |
| fcNonRevenue | `Float` | FC Non Revenue |
| fcNonRevenueTax | `Float` | FC Non Revenue Tax |
| fcOtherRevenue | `Float` | FC Other Revenue |
| fcOtherRevenueTax | `Float` | FC Other Revenue Tax |
| fcRoomRevenue | `Float` | FC Room Revenue |
| fcRoomRevenueTax | `Float` | FC Room Revenue Tax |
| fcTotalRevenue | `Float` | FC Total Revenue |
| fcTotalRevenueTax | `Float` | FC Total Revenue Tax |
| foodRevenue | `Float` | Food Revenue |
| foodRevenueTax | `Float` | Food Revenue Tax |
| gender | `String` | Gender |
| grossRate | `Float` | Gross Rate |
| groupId | `Float` | Group ID |
| id | `Float` | ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| nationality | `String` | Nationality |
| nationalityid | `String` | Nationalityid |
| netRoomRevenue | `Float` | Net Room Revenue |
| nonRevenue | `Float` | Non Revenue |
| nonRevenueTax | `Float` | Non Revenue Tax |
| numberOfGuests | `Float` | Number of Guests |
| numberOfRooms | `Float` | Number of Rooms |
| oooRooms | `Float` | Number of Rooms marked as Out of Order for today |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| osRooms | `Float` | Os Rooms |
| otherRevenue | `Float` | Other Revenue |
| otherRevenueTax | `Float` | Other Revenue Tax |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerRentalFlag | `String` | Owner Rental Flag |
| parentCompanyId | `Float` | Parent Company ID |
| parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| quantity | `Float` | Quantity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCategory | `String` | Rate Category |
| rateClass | `String` | Rate Class |
| rateCode | `String` | Rate Code |
| ratecategoryid | `String` | Ratecategoryid |
| rateclassid | `String` | Rateclassid |
| ratecodeid | `String` | Ratecodeid |
| regionCode | `String` | Region Code |
| regionid | `String` | Regionid |
| remainingBlockRooms | `Float` | Remaining Block Rooms |
| resInsertSource | `String` | Reservation Insert Source |
| reservationInventoryType | `String` | Reservation Inventory Type |
| reservationType | `String` | Reservation Type |
| reservationdailytotalid | `Float` | Reservation Daily Total ID |
| reservationid | `String` | Reservationid |
| resvStatus | `String` | Reservation Status |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueTax | `Float` | Room Revenue Tax |
| roomType | `String` | Room Type |
| roomclassid | `String` | Roomclassid |
| singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| sourceCode | `String` | Source Code |
| sourceProfId | `Float` | Source Prof ID |
| sourceid | `String` | Sourceid |
| state | `String` | State |
| stayDate | `Date` | Stay Date |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueTax | `Float` | Total Revenue Tax |
| truncEndDate | `Date` | Trunc End Date |
| truncStartDate | `Date` | Trunc Start Date |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| updateBusinessDate | `Date` | Update Business Date |
| updateDate | `DateTime` | Update Date |
| vipStatus | `String` | VIP Status |
| waitlistExtraRevenue | `Float` | Waitlist Extra Revenue |
| waitlistGrossRate | `Float` | Waitlist Gross Rate |
| waitlistNetRoomRevenue | `Float` | Waitlist Net Room Revenue |
| waitlistPersons | `Float` | Waitlist Persons |
| waitlistRooms | `Float` | Waitlist Rooms |
| zipCode | `String` | Zipcode Code |

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
    'dSI': pl.Float64,
    'deletedflag': pl.Utf8,
    'displaySequence': pl.Float64,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'osRooms': pl.Float64,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerRentalFlag': pl.Utf8,
    'parentCompanyId': pl.Float64,
    'parentcompanyprofileid': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Float64,
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