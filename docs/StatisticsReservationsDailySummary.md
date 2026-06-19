# StatisticsReservationsDailySummary
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `statisticsReservationsDailySummary`
> Summarized information on past reservations including number of persons rooms and revenue figures broken down by room type market code rate code and periods of time.
  
**Return:** [`[StatisticsReservationsDailySummaryType]`](#statisticsreservationsdailysummarytype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsReservationsDailySummaryQueryArgumentsType!`](#statisticsreservationsdailysummaryqueryargumentstype) |  |

## Object Types

### StatisticsReservationsDailySummaryType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationDailySummaryDetails | [`StatisticsReservationsDailySummaryReservationDailySummaryDetailsType`](#statisticsreservationsdailysummaryreservationdailysummarydetailstype) | Reservation Daily Summary |
| 2 | fiscalCalendarDetails | [`StatisticsReservationsDailySummaryFiscalCalendarDetailsType`](#statisticsreservationsdailysummaryfiscalcalendardetailstype) | Fiscal Calendar |
| 3 | gregerianCalendarDetails | [`StatisticsReservationsDailySummaryGregerianCalendarDetailsType`](#statisticsreservationsdailysummarygregeriancalendardetailstype) | Gregerian Calendar |
| 4 | propertyPropertyDetails | [`StatisticsReservationsDailySummaryPropertyPropertyDetailsType`](#statisticsreservationsdailysummarypropertypropertydetailstype) | Resort Details |
| 5 | marketDetails | [`StatisticsReservationsDailySummaryMarketDetailsType`](#statisticsreservationsdailysummarymarketdetailstype) | Market Details |
| 6 | sourceTableDetails | [`StatisticsReservationsDailySummarySourceTableDetailsType`](#statisticsreservationsdailysummarysourcetabledetailstype) | Source Table Details |
| 7 | rateCodeDetails | [`StatisticsReservationsDailySummaryRateCodeDetailsType`](#statisticsreservationsdailysummaryratecodedetailstype) | Rate Code Details |
| 8 | roomCategoryDetails | [`StatisticsReservationsDailySummaryRoomCategoryDetailsType`](#statisticsreservationsdailysummaryroomcategorydetailstype) | Room Category Details |
| 9 | countryDetails | [`StatisticsReservationsDailySummaryCountryDetailsType`](#statisticsreservationsdailysummarycountrydetailstype) | Country Details |
| 10 | channelDetails | [`StatisticsReservationsDailySummaryChannelDetailsType`](#statisticsreservationsdailysummarychanneldetailstype) | Channel Details |
| 11 | regionDetails | [`StatisticsReservationsDailySummaryRegionDetailsType`](#statisticsreservationsdailysummaryregiondetailstype) | Region Details |
| 12 | rateSeasonDayDetails | [`StatisticsReservationsDailySummaryRateSeasonDayDetailsType`](#statisticsreservationsdailysummaryrateseasondaydetailstype) | Rate Season Daily Details |
| 13 | roomDetails | [`StatisticsReservationsDailySummaryRoomDetailsType`](#statisticsreservationsdailysummaryroomdetailstype) | Room Details |
| 14 | statisticsReservationsDailySummaryRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryReservationDailySummaryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adultsTaxFree | `Float` | Adults Tax Free |
| 2 | advFoodRevenue | `Float` | Advance Food Revenue |
| 3 | advNonRevenue | `Float` | Advance Non Revenue |
| 4 | advOtherRevenue | `Float` | Advance Other Revenue |
| 5 | advRoomRevenue | `Float` | Advance Room Revenue |
| 6 | advTotalFoodTax | `Float` | Advance Total Food Tax |
| 7 | advTotalNonRevenueTax | `Float` | Advance Total Non Revenue Tax |
| 8 | advTotalOtherTax | `Float` | Advance Total Other Tax |
| 9 | advTotalRevenue | `Float` | Advance Total Revenue |
| 10 | advTotalRoomTax | `Float` | Advance Total Room Tax |
| 11 | advTotalTax | `Float` | Advance Total Tax |
| 12 | arrivalPersons | `Float` | Arrival Persons |
| 13 | arrivalRooms | `Float` | Arrival Rooms |
| 14 | businessDate | `Date` | Business Date |
| 15 | cAdvanceFoodRevenue | `Float` | Central Adv Food Revenue |
| 16 | cAdvanceNonRevenue | `Float` | Central Adv Non Revenue |
| 17 | cAdvanceOtherRevenue | `Float` | Central Adv Other Revenue |
| 18 | cAdvanceRoomRevenue | `Float` | Central Adv Room Revenue |
| 19 | cAdvanceTotalFoodTax | `Float` | Central Adv Total Food Tax |
| 20 | cAdvanceTotalNonRevenueTax | `Float` | Central Adv Total Non Revenue Tax |
| 21 | cAdvanceTotalOtherTax | `Float` | Central Adv Total Other Tax |
| 22 | cAdvanceTotalRevenue | `Float` | Central Adv Total Revenue |
| 23 | cAdvanceTotalRoomTax | `Float` | Central Adv Total Room Tax |
| 24 | cAdvanceTotalTax | `Float` | Central Adv Total Tax |
| 25 | cExchangeDate | `Date` | Central Xchange Date |
| 26 | cExchangeRate | `Float` | Central Xchange Rate |
| 27 | cFlaggedFoodRevenue | `Float` | Central Flgd Food Revenue |
| 28 | cFlaggedNonRevenue | `Float` | Central Flgd Non Revenue |
| 29 | cFlaggedOtherRevenue | `Float` | Central Flgd Other Revenue |
| 30 | cFlaggedRoomRevenue | `Float` | Central Flgd Room Revenue |
| 31 | cFlaggedTotalFoodTax | `Float` | Central Flgd Total Food Tax |
| 32 | cFlaggedTotalNonRevenueTax | `Float` | Central Flgd Total Non Revenue Tax |
| 33 | cFlaggedTotalOtherTax | `Float` | Central Flgd Total Other Tax |
| 34 | cFlaggedTotalRevenue | `Float` | Central Flgd Total Revenue |
| 35 | cFlaggedTotalRoomTax | `Float` | Central Flgd Total Room Tax |
| 36 | cFlaggedTotalTax | `Float` | Central Flgd Total Tax |
| 37 | cancelledPersons | `Float` | Cancelled Persons |
| 38 | cancelledRooms | `Float` | Cancelled Rooms |
| 39 | cashRoomNights | `Float` | Cash Room Nights |
| 40 | cashRoomRevenue | `Float` | Cash Room Revenue |
| 41 | centralCashRoomRevenue | `Float` | Central Cash Room Revenue |
| 42 | centralComplimentaryRoomRevenue | `Float` | Central Complimentary Room Revenue |
| 43 | centralFoodRevenue | `Float` | Central Food Revenue |
| 44 | centralFoodTax | `Float` | Central Food Tax |
| 45 | centralNonRevenue | `Float` | Central Non Revenue |
| 46 | centralNonRevenueTax | `Float` | Central Non Revenue Tax |
| 47 | centralOtherRevenue | `Float` | Central Other Revenue |
| 48 | centralOtherTax | `Float` | Central Other Tax |
| 49 | centralPackageFoodRevenue | `Float` | Central Package Food Revenue |
| 50 | centralPackageNonRevenue | `Float` | Central Package Non Revenue |
| 51 | centralPackageOtherRevenue | `Float` | Central Package Other Revenue |
| 52 | centralPackageRoomRevenue | `Float` | Central Package Room Revenue |
| 53 | centralPackageTotalRevenue | `Float` | Central Package Total Revenue |
| 54 | centralRoomRevenue | `Float` | Central Room Revenue |
| 55 | centralRoomTax | `Float` | Central Room Tax |
| 56 | centralTotalRevenue | `Float` | Central Total Revenue |
| 57 | centralTotalTax | `Float` | Central Total Tax |
| 58 | channel | `String` | Channel |
| 59 | channelid | `String` | Channelid |
| 60 | childrenAgeGroup1 | `Float` | Children Age Group 1) |
| 61 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 62 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 63 | childrenAgeGroup4 | `Float` | Children Age Group 4) |
| 64 | childrenAgeGroup5 | `Float` | Children Age Group 5) |
| 65 | childrenTaxFree | `Float` | Children Tax Free |
| 66 | complimentaryRoomNights | `Float` | Complimentary Room Nights |
| 67 | complimentaryRoomRevenue | `Float` | Complimentary Room Revenue |
| 68 | country | `String` | Country |
| 69 | countryid | `String` | Countryid |
| 70 | cribs | `Float` | Cribs |
| 71 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 72 | dayUsePersons | `Float` | Day Use Persons |
| 73 | dayUseRooms | `Float` | Day Use Rooms |
| 74 | departurePersons | `Float` | Departure Persons |
| 75 | departureRooms | `Float` | Departure Rooms |
| 76 | extraBeds | `Float` | Extra Beds |
| 77 | flgdFoodRevenue | `Float` | Flagged Food Revenue |
| 78 | flgdNonRevenue | `Float` | Flagged Non Revenue |
| 79 | flgdOtherRevenue | `Float` | Flagged Other Revenue |
| 80 | flgdRoomRevenue | `Float` | Flagged Room Revenue |
| 81 | flgdTotalFoodTax | `Float` | Flagged Total Food Tax |
| 82 | flgdTotalNonRevenueTax | `Float` | Flagged Total Non Revenue Tax |
| 83 | flgdTotalOtherTax | `Float` | Flagged Total Other Tax |
| 84 | flgdTotalRevenue | `Float` | Flagged Total Revenue |
| 85 | flgdTotalRoomTax | `Float` | Flagged Total Room Tax |
| 86 | flgdTotalTax | `Float` | Flagged Total Tax |
| 87 | foodRevenue | `Float` | Food Revenue |
| 88 | foodTax | `Float` | Total tax amount earned through food/beverage charges for the current record's key value. |
| 89 | jRNUpdateDate | `Date` | JRN Update Date |
| 90 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 91 | locationID | `String` | Internal ID to uniquely identify the Property |
| 92 | marketCode | `String` | Market Code |
| 93 | marketMainGroup | `String` | Market Main Group |
| 94 | marketid | `String` | Marketid |
| 95 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 96 | noShowPersons | `Float` | No-Show Persons |
| 97 | noShowRooms | `Float` | No-Show Rooms |
| 98 | nonRevenue | `Float` | Non Revenue |
| 99 | nonRevenueTax | `Float` | Non Revenue Tax |
| 100 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 101 | otherRevenue | `Float` | Other Revenue |
| 102 | otherTax | `Float` | Total tax amount of all postings today where the Transaction Code is marked as Revenue and the Transaction Code Type is  not Lodging Food and Beverage Tax or Non Hotel Supplies |
| 103 | outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 104 | outOfServiceRooms | `Float` | Out of Service Rooms |
| 105 | packageFoodRevenue | `Float` | Package Food Revenue |
| 106 | packageNonRevenue | `Float` | Package Non Revenue |
| 107 | packageOtherRevenue | `Float` | Package Other Revenue |
| 108 | packageRoomRevenue | `Float` | Package Room Revenue |
| 109 | packageTotalRevenue | `Float` | Total revenue earned through packages for the current record's key value. |
| 110 | physicalRooms | `Float` | Physical Rooms |
| 111 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 112 | property | `String` | Code to uniquely identify the Property |
| 113 | pseudoRoomYN | `String` | Pseudo Room YN |
| 114 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 115 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 116 | rateCategory | `String` | Rate Category |
| 117 | rateCode | `String` | Rate Code |
| 118 | ratecodeid | `String` | Ratecodeid |
| 119 | regionCode | `String` | Region Code |
| 120 | regionid | `String` | Regionid |
| 121 | roomCategory | `String` | Room Category |
| 122 | roomClass | `String` | Room Class |
| 123 | roomNights | `Float` | Room Nights |
| 124 | roomRevenue | `Float` | Room Revenue |
| 125 | roomTax | `Float` | Room Tax |
| 126 | roomcategoryid | `String` | Roomcategoryid |
| 127 | roomcatratemktsrctotalid | `Float` | Room Category Rate Market Source Total ID |
| 128 | roomclassid | `String` | Roomclassid |
| 129 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 130 | sourceCode | `String` | Source Code |
| 131 | sourceMainGroup | `String` | Source Main Group |
| 132 | sourceid | `String` | Sourceid |
| 133 | stayAdults | `Float` | Stay Adults |
| 134 | stayChildren | `Float` | Stay Children |
| 135 | stayPersons | `Float` | Stay Persons |
| 136 | totalRevenue | `Float` | Total Revenue |
| 137 | totalTax | `Float` | Total Tax |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryFiscalCalendarDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | calendar | `String` | Calendar |
| 3 | calendarDescription | `String` | Calendar Description |
| 4 | calendarpkid | `Float` | Calendarpkid |
| 5 | calendartype | `String` | Calendartype |
| 6 | daydesc | `String` | Daydesc |
| 7 | dayenddate | `Date` | Dayenddate |
| 8 | daytimespan | `Float` | Daytimespan |
| 9 | defaultCalendarYn | `String` | Default Calendar Y/N |
| 10 | monthDescription | `String` | Month Description |
| 11 | period | `String` | Period |
| 12 | periodEndDate | `Date` | Period End Date |
| 13 | periodStartDate | `Date` | Period Start Date |
| 14 | periodpkid | `Float` | Periodpkid |
| 15 | periodtimespan | `Float` | Periodtimespan |
| 16 | quarter | `String` | Quarter |
| 17 | quarterDescription | `String` | Quarter Description |
| 18 | quarterEndDate | `Date` | Quarter End Date |
| 19 | quarterStartDate | `Date` | Quarter Start Date |
| 20 | quarterpkid | `Float` | Quarterpkid |
| 21 | quartertimespan | `Float` | Quartertimespan |
| 22 | weekcode | `String` | Weekcode |
| 23 | weekdesc | `String` | Weekdesc |
| 24 | weekenddate | `Date` | Weekenddate |
| 25 | weekkey | `String` | Weekkey |
| 26 | weekstartdate | `Date` | Weekstartdate |
| 27 | weektimespan | `Float` | Weektimespan |
| 28 | year | `Float` | Year |
| 29 | yearDescription | `String` | Year Description |
| 30 | yearEndDate | `Date` | Year End Date |
| 31 | yearStartDate | `Date` | Year Start Date |
| 32 | yearpkid | `Float` | Yearpkid |
| 33 | yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryGregerianCalendarDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | calendar | `String` | Calendar |
| 3 | calendarDescription | `String` | Calendar Description |
| 4 | calendarpkid | `Float` | Calendarpkid |
| 5 | calendartype | `String` | Calendartype |
| 6 | daydesc | `String` | Daydesc |
| 7 | dayenddate | `Date` | Dayenddate |
| 8 | daytimespan | `Float` | Daytimespan |
| 9 | defaultCalendarYn | `String` | Default Calendar Y/N |
| 10 | monthDescription | `String` | Month Description |
| 11 | period | `String` | Period |
| 12 | periodEndDate | `Date` | Period End Date |
| 13 | periodStartDate | `Date` | Period Start Date |
| 14 | periodpkid | `Float` | Periodpkid |
| 15 | periodtimespan | `Float` | Periodtimespan |
| 16 | quarter | `String` | Quarter |
| 17 | quarterDescription | `String` | Quarter Description |
| 18 | quarterEndDate | `Date` | Quarter End Date |
| 19 | quarterStartDate | `Date` | Quarter Start Date |
| 20 | quarterpkid | `Float` | Quarterpkid |
| 21 | quartertimespan | `Float` | Quartertimespan |
| 22 | weekcode | `String` | Weekcode |
| 23 | weekdesc | `String` | Weekdesc |
| 24 | weekenddate | `Date` | Weekenddate |
| 25 | weekkey | `String` | Weekkey |
| 26 | weekstartdate | `Date` | Weekstartdate |
| 27 | weektimespan | `Float` | Weektimespan |
| 28 | year | `Float` | Year |
| 29 | yearDescription | `String` | Year Description |
| 30 | yearEndDate | `Date` | Year End Date |
| 31 | yearStartDate | `Date` | Year Start Date |
| 32 | yearpkid | `Float` | Yearpkid |
| 33 | yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryPropertyPropertyDetailsType

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

### StatisticsReservationsDailySummaryMarketDetailsType

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

### StatisticsReservationsDailySummarySourceTableDetailsType

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

### StatisticsReservationsDailySummaryRateCodeDetailsType

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

### StatisticsReservationsDailySummaryRoomCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessibleRoomType | `String` | Indicates if this room type is accessibility compliant. |
| 2 | activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| 3 | activeflag | `Date` | Activeflag |
| 4 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 5 | autoPopulate | `String` | Include room type in the rate header for Myfidelio rates. |
| 6 | autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| 7 | bedType | `String` | Bed Type |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | cIncrements | `Float` | Central Increments |
| 11 | cInitialRoundUp | `Float` | Central Initial Round Up |
| 12 | cORMSDrtier1 | `Float` | Central Orms Drtier1 |
| 13 | cORMSDrtier2 | `Float` | Central Orms Drtier2 |
| 14 | cORMSDrtier3 | `Float` | Central Orms Drtier3 |
| 15 | cORMSDrxtra2ndAdult | `Float` | Central Orms Drxtra 2nd Adult |
| 16 | cORMSDrxtraAdult | `Float` | Central Orms Drxtra Adult |
| 17 | cORMSDrxtraChild | `Float` | Central Orms Drxtra Child |
| 18 | cORMSUpsellAmount | `Float` | Central Orms Upsell Amt |
| 19 | cRateAmount | `Float` | Central Rate Amount |
| 20 | cRateFloor | `Float` | Central Rate Floor |
| 21 | cRSDescription | `String` | CRS Description |
| 22 | canDeleteYn | `String` | Can Delete Y/N |
| 23 | centralRoomClass | `String` | Central Room Class |
| 24 | centralRoomClassDescription | `String` | Central Room Class Description |
| 25 | centralRoomType | `String` | Central Room Type |
| 26 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 27 | compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| 28 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 29 | defaultOccupancy | `Float` | Default occupancy for the room type |
| 30 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 31 | defaultRateDesc | `String` | Default Rate Description |
| 32 | defaultratecodeid | `String` | Defaultratecodeid |
| 33 | deletedFlag | `String` | Deleted Flag |
| 34 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 35 | genericYN | `String` | Generic YN |
| 36 | housekeeping | `String` | Room type shows in housekeeping Y/N |
| 37 | imageId | `Float` | Image ID |
| 38 | inactiveDate | `DateTime` | Inactive Date |
| 39 | inactiveflag | `String` | Inactive Flag |
| 40 | increments | `Float` | Increment value for rates by day by LOS. |
| 41 | initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| 42 | insertDate | `DateTime` | Insert Date |
| 43 | insertUser | `Float` | Insert User |
| 44 | internalDeletedflag | `String` | Deleted Flag |
| 45 | jRNUpdateDate | `Date` | JRN Update Date |
| 46 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 47 | label | `String` | Label |
| 48 | locationID | `String` | Internal ID to uniquely identify the Property |
| 49 | longDescription | `String` | Long Description |
| 50 | maintenance | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| 51 | maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| 52 | maxRollaways | `Float` | Not used |
| 53 | maximumAdults | `Float` | The maximum occupancy of adults for this room category. |
| 54 | maximumChildren | `Float` | The maximum occupancy of children for this room category. |
| 55 | maximumOccupancy | `Float` | Maximum Occupancy |
| 56 | meetingRoomYN | `String` | Meeting Room YN |
| 57 | memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| 58 | minimumOccupancy | `Float` | Minimum Occupancy |
| 59 | numberOfRooms | `Float` | Number of Rooms |
| 60 | oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| 61 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 62 | ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| 63 | ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| 64 | ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| 65 | ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| 66 | ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| 67 | ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| 68 | ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| 69 | ownerroomflag | `String` | Ownerroomflag |
| 70 | physical | `String` | Physical |
| 71 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 72 | productClass | `String` | Product Class |
| 73 | property | `String` | Code to uniquely identify the Property |
| 74 | pseudoRoomType | `String` | Pseudo Room Type |
| 75 | pseudoRoomYN | `String` | Pseudo Room YN |
| 76 | rateAmount | `Float` | Rate Amount |
| 77 | rateCategory | `String` | Rate Category |
| 78 | rateCategoryDesc | `String` | Rate Category Description |
| 79 | rateCode | `String` | Rate Code |
| 80 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 81 | ratecategoryid | `String` | Ratecategoryid |
| 82 | repItem | `String` | Reporting Item |
| 83 | repItemName | `String` | Reporting Item Name |
| 84 | repItemOrderby | `Float` | Reporting Item Orderby |
| 85 | repOrderBy | `Float` | Reporting Order By |
| 86 | repRateCategory | `String` | Reporting Rate Category |
| 87 | repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| 88 | repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| 89 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 90 | replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| 91 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 92 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 93 | roomClass | `String` | Room Class |
| 94 | roomClassDescription | `String` | Room Class Description |
| 95 | roomInfoURL | `String` | URL where room information is stored. |
| 96 | roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| 97 | roomType | `String` | Room Type |
| 98 | roomTypeDescription | `String` | Charged Room Type Description |
| 99 | roomcategoryid | `String` | Roomcategoryid |
| 100 | roomcategorypmsref | `String` | Roomcategorypmsref |
| 101 | roomclassid | `String` | Roomclassid |
| 102 | rotationGroup | `String` | Rotation Group |
| 103 | sLabel | `String` | S Label |
| 104 | salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| 105 | sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| 106 | sendIFC | `String` | Room type sent to interface Y/N |
| 107 | sequence | `Float` | Sequence |
| 108 | smoking | `String` | Smoking |
| 109 | smokingPrefDesc | `String` | Smoking Pref Description |
| 110 | suiteYN | `String` | Suite YN |
| 111 | updateDate | `DateTime` | Update Date |
| 112 | updateUser | `Float` | Update User |
| 113 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 114 | yieldStatus | `String` | Yield Status |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryCountryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressdoctorMode | `String` | Defines the mode used to invoke Addressdoctor service [INTERACTIVE or FASTCOMPLETION] |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | country | `String` | Country |
| 5 | countryCode | `String` | Country Code |
| 6 | countryMainGroup | `String` | Country Main Group |
| 7 | countryid | `String` | Countryid |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | displayCountryFlagYn | `String` | Indicates if the Country Flag should be displayed on the front end. |
| 11 | guestAddressFormat | `String` | Guest Address Format Codes. For Confirmation Letters. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalDeletedflag | `String` | Deleted Flag |
| 17 | isoCode | `String` | ISO standard code for the country |
| 18 | isoName | `String` | ISO standard name for the country |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | name | `String` | Name |
| 22 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 23 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 24 | printSequence | `Float` | Print Sequence |
| 25 | propertyAddressFormat | `String` | Property Address Format Codes. For Confirmation Letters. |
| 26 | regionCode | `String` | Region Code |
| 27 | regionid | `String` | Regionid |
| 28 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 29 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 30 | showSequence | `Float` | Display sequence for LOVs |
| 31 | statisticCode | `String` | Internal |
| 32 | status | `String` | Status |
| 33 | updateDate | `DateTime` | Update Date |
| 34 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryChannelDetailsType

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

### StatisticsReservationsDailySummaryRegionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedflag | `String` | Deleted Flag |
| 5 | inactiveflag | `String` | Inactive Flag |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | regionDescription | `String` | Region Description |
| 13 | regionid | `String` | Regionid |
| 14 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 15 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 16 | sequence | `Float` | Sequence |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryRateSeasonDayDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralSeasonCode | `String` | Central Season Code |
| 2 | centralSeasonDescription | `String` | Central Season Description |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | dayKey | `Date` | Day Key |
| 5 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 6 | displayColor | `String` | Display Color |
| 7 | endDate | `Date` | End Date |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveYn | `String` | Inactive Y/N |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | locationID | `String` | Internal ID to uniquely identify the Property |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rateCode | `String` | Rate Code |
| 19 | ratecodeid | `String` | Ratecodeid |
| 20 | rateseasonid | `String` | Rateseasonid |
| 21 | repItem | `String` | Reporting Item |
| 22 | repItemName | `String` | Reporting Item Name |
| 23 | repItemOrderby | `Float` | Reporting Item Orderby |
| 24 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 25 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 26 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 27 | seasonCode | `String` | Season Code |
| 28 | seasonDescription | `String` | Season Description |
| 29 | startDate | `Date` | Start Date |
| 30 | updateDate | `DateTime` | Update Date |
| 31 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailySummaryRoomDetailsType

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

### StatisticsReservationsDailySummaryQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| resvdailysummaryDetailsBusinessDate | `DateInput!` | Business Date<br>`@mandatoryInput` |
| resvdailysummaryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdailysummaryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdailysummaryDetailsMarketCode | `StringInput` | Market Code |
| resvdailysummaryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdailysummaryDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| resvdailysummaryDetailsRateCode | `StringInput` | Rate Code |
| resvdailysummaryDetailsRoomCategory | `StringInput` | Room Category |
| resvdailysummaryDetailsSourceCode | `StringInput` | Source Code |
| fiscalcalendarDetailsDaykey | `DateInput` | Business Date |
| fiscalcalendarDetailsCalendarcode | `StringInput` | Calendar |
| fiscalcalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| fiscalcalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| fiscalcalendarDetailsQuartercode | `StringInput` | Quarter |
| fiscalcalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| fiscalcalendarDetailsYearcode | `FloatInput` | Year |
| fiscalcalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| gregeriancalendarDetailsDaykey | `DateInput` | Business Date |
| gregeriancalendarDetailsCalendarcode | `StringInput` | Calendar |
| gregeriancalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| gregeriancalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| gregeriancalendarDetailsQuartercode | `StringInput` | Quarter |
| gregeriancalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| gregeriancalendarDetailsYearcode | `FloatInput` | Year |
| gregeriancalendarDetailsYearpkid | `FloatInput` | Yearpkid |
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
| roomcategoryDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| roomcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomcategoryDetailsLabel | `StringInput` | Label |
| roomcategoryDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomcategoryDetailsYieldCategory | `StringInput` | Product Class |
| roomcategoryDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomcategoryDetailsRoomCategory | `StringInput` | Room Type |
| roomcategoryDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| roomcategoryDetailsRoomcategorypmsref | `StringInput` | Roomcategorypmsref |
| roomcategoryDetailsRoomclassid | `StringInput` | Roomclassid |
| countryDetailsCountryCode | `StringInput` | Country Code |
| countryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| countryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| countryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| channelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| channelDetailsEntityName | `StringInput` | Entity Name |
| channelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| channelDetailsLanguageCode | `StringInput` | Language Code |
| channelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| channelDetailsAttributeCode | `StringInput` | Origin Code |
| channelDetailsTitleSuffix | `FloatInput` | Title Suffix |
| regionDetailsRegionCode | `StringInput` | Code |
| regionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| regionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| regionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| regionDetailsRegionid | `StringInput` | Regionid |
| rateseasondayDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| rateseasondayDetailsEndDate | `DateInput` | End Date |
| rateseasondayDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rateseasondayDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| rateseasondayDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| rateseasondayDetailsResort | `StringInput` | Code to uniquely identify the Property |
| rateseasondayDetailsRateCode | `StringInput` | Rate Code |
| rateseasondayDetailsRateseasonid | `StringInput` | Rateseasonid |
| rateseasondayDetailsSeason | `StringInput` | Season Code |
| rateseasondayDetailsBeginDate | `DateInput` | Start Date |
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
#### Validation Rules

**`mandatoryInput`**
- resvdailysummaryDetailsBusinessDate
- resvdailysummaryDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsReservationsDailySummary($input: StatisticsReservationsDailySummaryQueryArgumentsType!) {
  statisticsReservationsDailySummary(input: $input) @stream {
    reservationDailySummaryDetails {
      adultsTaxFree
      advFoodRevenue
      advNonRevenue
      advOtherRevenue
      advRoomRevenue
      advTotalFoodTax
      advTotalNonRevenueTax
      advTotalOtherTax
      advTotalRevenue
      advTotalRoomTax
      advTotalTax
      arrivalPersons
      arrivalRooms
      businessDate
      cAdvanceFoodRevenue
      cAdvanceNonRevenue
      cAdvanceOtherRevenue
      cAdvanceRoomRevenue
      cAdvanceTotalFoodTax
      cAdvanceTotalNonRevenueTax
      cAdvanceTotalOtherTax
      cAdvanceTotalRevenue
      cAdvanceTotalRoomTax
      cAdvanceTotalTax
      cExchangeDate
      cExchangeRate
      cFlaggedFoodRevenue
      cFlaggedNonRevenue
      cFlaggedOtherRevenue
      cFlaggedRoomRevenue
      cFlaggedTotalFoodTax
      cFlaggedTotalNonRevenueTax
      cFlaggedTotalOtherTax
      cFlaggedTotalRevenue
      cFlaggedTotalRoomTax
      cFlaggedTotalTax
      cancelledPersons
      cancelledRooms
      cashRoomNights
      cashRoomRevenue
      centralCashRoomRevenue
      centralComplimentaryRoomRevenue
      centralFoodRevenue
      centralFoodTax
      centralNonRevenue
      centralNonRevenueTax
      centralOtherRevenue
      centralOtherTax
      centralPackageFoodRevenue
      centralPackageNonRevenue
      centralPackageOtherRevenue
      centralPackageRoomRevenue
      centralPackageTotalRevenue
      centralRoomRevenue
      centralRoomTax
      centralTotalRevenue
      centralTotalTax
      channel
      channelid
      childrenAgeGroup1
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAgeGroup4
      childrenAgeGroup5
      childrenTaxFree
      complimentaryRoomNights
      complimentaryRoomRevenue
      country
      countryid
      cribs
      dSI
      dayUsePersons
      dayUseRooms
      departurePersons
      departureRooms
      extraBeds
      flgdFoodRevenue
      flgdNonRevenue
      flgdOtherRevenue
      flgdRoomRevenue
      flgdTotalFoodTax
      flgdTotalNonRevenueTax
      flgdTotalOtherTax
      flgdTotalRevenue
      flgdTotalRoomTax
      flgdTotalTax
      foodRevenue
      foodTax
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketMainGroup
      marketid
      multipleOccupancyRooms
      noShowPersons
      noShowRooms
      nonRevenue
      nonRevenueTax
      organizationID
      otherRevenue
      otherTax
      outOfOrderRooms
      outOfServiceRooms
      packageFoodRevenue
      packageNonRevenue
      packageOtherRevenue
      packageRoomRevenue
      packageTotalRevenue
      physicalRooms
      primaryKeyID
      property
      pseudoRoomYN
      rNAInsertDate
      rNAUpdateDate
      rateCategory
      rateCode
      ratecodeid
      regionCode
      regionid
      roomCategory
      roomClass
      roomNights
      roomRevenue
      roomTax
      roomcategoryid
      roomcatratemktsrctotalid
      roomclassid
      singleOccupancyRooms
      sourceCode
      sourceMainGroup
      sourceid
      stayAdults
      stayChildren
      stayPersons
      totalRevenue
      totalTax
    }
    fiscalCalendarDetails {
      businessDate
      calendar
      calendarDescription
      calendarpkid
      calendartype
      daydesc
      dayenddate
      daytimespan
      defaultCalendarYn
      monthDescription
      period
      periodEndDate
      periodStartDate
      periodpkid
      periodtimespan
      quarter
      quarterDescription
      quarterEndDate
      quarterStartDate
      quarterpkid
      quartertimespan
      weekcode
      weekdesc
      weekenddate
      weekkey
      weekstartdate
      weektimespan
      year
      yearDescription
      yearEndDate
      yearStartDate
      yearpkid
      yeartimespan
    }
    gregerianCalendarDetails {
      businessDate
      calendar
      calendarDescription
      calendarpkid
      calendartype
      daydesc
      dayenddate
      daytimespan
      defaultCalendarYn
      monthDescription
      period
      periodEndDate
      periodStartDate
      periodpkid
      periodtimespan
      quarter
      quarterDescription
      quarterEndDate
      quarterStartDate
      quarterpkid
      quartertimespan
      weekcode
      weekdesc
      weekenddate
      weekkey
      weekstartdate
      weektimespan
      year
      yearDescription
      yearEndDate
      yearStartDate
      yearpkid
      yeartimespan
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
    roomCategoryDetails {
      accessibleRoomType
      activeDate
      activeflag
      autoCheckinYn
      autoPopulate
      autoRoomAssignYn
      bedType
      cExchangeDate
      cExchangeRate
      cIncrements
      cInitialRoundUp
      cORMSDrtier1
      cORMSDrtier2
      cORMSDrtier3
      cORMSDrxtra2ndAdult
      cORMSDrxtraAdult
      cORMSDrxtraChild
      cORMSUpsellAmount
      cRateAmount
      cRateFloor
      cRSDescription
      canDeleteYn
      centralRoomClass
      centralRoomClassDescription
      centralRoomType
      centralRoomTypeDescription
      compiled
      dSI
      defaultOccupancy
      defaultRateCode
      defaultRateDesc
      defaultratecodeid
      deletedFlag
      evisitorFacilityId
      genericYN
      housekeeping
      imageId
      inactiveDate
      inactiveflag
      increments
      initialRoundUp
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      locationID
      longDescription
      maintenance
      maxFixBedOccupancy
      maxRollaways
      maximumAdults
      maximumChildren
      maximumOccupancy
      meetingRoomYN
      memberAwardRoomGrp
      minimumOccupancy
      numberOfRooms
      oRMSUpsellAmt
      organizationID
      ormsDrtier1
      ormsDrtier2
      ormsDrtier3
      ormsDrxtra2ndAdult
      ormsDrxtraAdult
      ormsDrxtraChild
      ormsUpsellRank
      ownerroomflag
      physical
      primaryKeyID
      productClass
      property
      pseudoRoomType
      pseudoRoomYN
      rateAmount
      rateCategory
      rateCategoryDesc
      rateCode
      rateFloor
      ratecategoryid
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repRateCategory
      repRateCategoryDescription
      repSmokingPrefDescription
      repUpdateDate
      replacesCategory
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomClassDescription
      roomInfoURL
      roomPool
      roomType
      roomTypeDescription
      roomcategoryid
      roomcategorypmsref
      roomclassid
      rotationGroup
      sLabel
      salesFlag
      sellThruRuleYn
      sendIFC
      sequence
      smoking
      smokingPrefDesc
      suiteYN
      updateDate
      updateUser
      upsellYn
      yieldStatus
    }
    countryDetails {
      addressdoctorMode
      canDeleteYn
      chainCode
      country
      countryCode
      countryMainGroup
      countryid
      dSI
      deletedFlag
      displayCountryFlagYn
      guestAddressFormat
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      isoCode
      isoName
      jRNUpdateDate
      jRNUpdateDateAndTime
      name
      organizationID
      primaryKeyID
      printSequence
      propertyAddressFormat
      regionCode
      regionid
      rnaInsertDate
      rnaUpdateDate
      showSequence
      statisticCode
      status
      updateDate
      updateUser
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
    regionDetails {
      chainCode
      code
      dSI
      deletedflag
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      regionDescription
      regionid
      rnaInsertDate
      rnaUpdateDate
      sequence
      updateDate
      updateUser
    }
    rateSeasonDayDetails {
      centralSeasonCode
      centralSeasonDescription
      dSI
      dayKey
      deletedYn
      displayColor
      endDate
      inactiveDate
      inactiveYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rateCode
      ratecodeid
      rateseasonid
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      seasonCode
      seasonDescription
      startDate
      updateDate
      updateUser
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
reservation_daily_summary_details_schema = {
    'adultsTaxFree': pl.Float64,
    'advFoodRevenue': pl.Float64,
    'advNonRevenue': pl.Float64,
    'advOtherRevenue': pl.Float64,
    'advRoomRevenue': pl.Float64,
    'advTotalFoodTax': pl.Float64,
    'advTotalNonRevenueTax': pl.Float64,
    'advTotalOtherTax': pl.Float64,
    'advTotalRevenue': pl.Float64,
    'advTotalRoomTax': pl.Float64,
    'advTotalTax': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalRooms': pl.Float64,
    'businessDate': pl.Utf8,
    'cAdvanceFoodRevenue': pl.Float64,
    'cAdvanceNonRevenue': pl.Float64,
    'cAdvanceOtherRevenue': pl.Float64,
    'cAdvanceRoomRevenue': pl.Float64,
    'cAdvanceTotalFoodTax': pl.Float64,
    'cAdvanceTotalNonRevenueTax': pl.Float64,
    'cAdvanceTotalOtherTax': pl.Float64,
    'cAdvanceTotalRevenue': pl.Float64,
    'cAdvanceTotalRoomTax': pl.Float64,
    'cAdvanceTotalTax': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFlaggedFoodRevenue': pl.Float64,
    'cFlaggedNonRevenue': pl.Float64,
    'cFlaggedOtherRevenue': pl.Float64,
    'cFlaggedRoomRevenue': pl.Float64,
    'cFlaggedTotalFoodTax': pl.Float64,
    'cFlaggedTotalNonRevenueTax': pl.Float64,
    'cFlaggedTotalOtherTax': pl.Float64,
    'cFlaggedTotalRevenue': pl.Float64,
    'cFlaggedTotalRoomTax': pl.Float64,
    'cFlaggedTotalTax': pl.Float64,
    'cancelledPersons': pl.Float64,
    'cancelledRooms': pl.Float64,
    'cashRoomNights': pl.Float64,
    'cashRoomRevenue': pl.Float64,
    'centralCashRoomRevenue': pl.Float64,
    'centralComplimentaryRoomRevenue': pl.Float64,
    'centralFoodRevenue': pl.Float64,
    'centralFoodTax': pl.Float64,
    'centralNonRevenue': pl.Float64,
    'centralNonRevenueTax': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralOtherTax': pl.Float64,
    'centralPackageFoodRevenue': pl.Float64,
    'centralPackageNonRevenue': pl.Float64,
    'centralPackageOtherRevenue': pl.Float64,
    'centralPackageRoomRevenue': pl.Float64,
    'centralPackageTotalRevenue': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTax': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalTax': pl.Float64,
    'channel': pl.Utf8,
    'channelid': pl.Utf8,
    'childrenAgeGroup1': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAgeGroup4': pl.Float64,
    'childrenAgeGroup5': pl.Float64,
    'childrenTaxFree': pl.Float64,
    'complimentaryRoomNights': pl.Float64,
    'complimentaryRoomRevenue': pl.Float64,
    'country': pl.Utf8,
    'countryid': pl.Utf8,
    'cribs': pl.Float64,
    'dSI': pl.Int64,
    'dayUsePersons': pl.Float64,
    'dayUseRooms': pl.Float64,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'extraBeds': pl.Float64,
    'flgdFoodRevenue': pl.Float64,
    'flgdNonRevenue': pl.Float64,
    'flgdOtherRevenue': pl.Float64,
    'flgdRoomRevenue': pl.Float64,
    'flgdTotalFoodTax': pl.Float64,
    'flgdTotalNonRevenueTax': pl.Float64,
    'flgdTotalOtherTax': pl.Float64,
    'flgdTotalRevenue': pl.Float64,
    'flgdTotalRoomTax': pl.Float64,
    'flgdTotalTax': pl.Float64,
    'foodRevenue': pl.Float64,
    'foodTax': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketMainGroup': pl.Utf8,
    'marketid': pl.Utf8,
    'multipleOccupancyRooms': pl.Float64,
    'noShowPersons': pl.Float64,
    'noShowRooms': pl.Float64,
    'nonRevenue': pl.Float64,
    'nonRevenueTax': pl.Float64,
    'organizationID': pl.Int64,
    'otherRevenue': pl.Float64,
    'otherTax': pl.Float64,
    'outOfOrderRooms': pl.Float64,
    'outOfServiceRooms': pl.Float64,
    'packageFoodRevenue': pl.Float64,
    'packageNonRevenue': pl.Float64,
    'packageOtherRevenue': pl.Float64,
    'packageRoomRevenue': pl.Float64,
    'packageTotalRevenue': pl.Float64,
    'physicalRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionid': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenue': pl.Float64,
    'roomTax': pl.Float64,
    'roomcategoryid': pl.Utf8,
    'roomcatratemktsrctotalid': pl.Float64,
    'roomclassid': pl.Utf8,
    'singleOccupancyRooms': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceMainGroup': pl.Utf8,
    'sourceid': pl.Utf8,
    'stayAdults': pl.Float64,
    'stayChildren': pl.Float64,
    'stayPersons': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalTax': pl.Float64,
}
```
```python
fiscal_calendar_details_schema = {
    'businessDate': pl.Utf8,
    'calendar': pl.Utf8,
    'calendarDescription': pl.Utf8,
    'calendarpkid': pl.Float64,
    'calendartype': pl.Utf8,
    'daydesc': pl.Utf8,
    'dayenddate': pl.Utf8,
    'daytimespan': pl.Float64,
    'defaultCalendarYn': pl.Utf8,
    'monthDescription': pl.Utf8,
    'period': pl.Utf8,
    'periodEndDate': pl.Utf8,
    'periodStartDate': pl.Utf8,
    'periodpkid': pl.Float64,
    'periodtimespan': pl.Float64,
    'quarter': pl.Utf8,
    'quarterDescription': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterStartDate': pl.Utf8,
    'quarterpkid': pl.Float64,
    'quartertimespan': pl.Float64,
    'weekcode': pl.Utf8,
    'weekdesc': pl.Utf8,
    'weekenddate': pl.Utf8,
    'weekkey': pl.Utf8,
    'weekstartdate': pl.Utf8,
    'weektimespan': pl.Float64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearStartDate': pl.Utf8,
    'yearpkid': pl.Float64,
    'yeartimespan': pl.Float64,
}
```
```python
gregerian_calendar_details_schema = {
    'businessDate': pl.Utf8,
    'calendar': pl.Utf8,
    'calendarDescription': pl.Utf8,
    'calendarpkid': pl.Float64,
    'calendartype': pl.Utf8,
    'daydesc': pl.Utf8,
    'dayenddate': pl.Utf8,
    'daytimespan': pl.Float64,
    'defaultCalendarYn': pl.Utf8,
    'monthDescription': pl.Utf8,
    'period': pl.Utf8,
    'periodEndDate': pl.Utf8,
    'periodStartDate': pl.Utf8,
    'periodpkid': pl.Float64,
    'periodtimespan': pl.Float64,
    'quarter': pl.Utf8,
    'quarterDescription': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterStartDate': pl.Utf8,
    'quarterpkid': pl.Float64,
    'quartertimespan': pl.Float64,
    'weekcode': pl.Utf8,
    'weekdesc': pl.Utf8,
    'weekenddate': pl.Utf8,
    'weekkey': pl.Utf8,
    'weekstartdate': pl.Utf8,
    'weektimespan': pl.Float64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearStartDate': pl.Utf8,
    'yearpkid': pl.Float64,
    'yeartimespan': pl.Float64,
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
room_category_details_schema = {
    'accessibleRoomType': pl.Utf8,
    'activeDate': pl.Utf8,
    'activeflag': pl.Utf8,
    'autoCheckinYn': pl.Utf8,
    'autoPopulate': pl.Utf8,
    'autoRoomAssignYn': pl.Utf8,
    'bedType': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cIncrements': pl.Float64,
    'cInitialRoundUp': pl.Float64,
    'cORMSDrtier1': pl.Float64,
    'cORMSDrtier2': pl.Float64,
    'cORMSDrtier3': pl.Float64,
    'cORMSDrxtra2ndAdult': pl.Float64,
    'cORMSDrxtraAdult': pl.Float64,
    'cORMSDrxtraChild': pl.Float64,
    'cORMSUpsellAmount': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRateFloor': pl.Float64,
    'cRSDescription': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'compiled': pl.Utf8,
    'dSI': pl.Int64,
    'defaultOccupancy': pl.Float64,
    'defaultRateCode': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'defaultratecodeid': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'genericYN': pl.Utf8,
    'housekeeping': pl.Utf8,
    'imageId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'increments': pl.Float64,
    'initialRoundUp': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'locationID': pl.Utf8,
    'longDescription': pl.Utf8,
    'maintenance': pl.Utf8,
    'maxFixBedOccupancy': pl.Float64,
    'maxRollaways': pl.Float64,
    'maximumAdults': pl.Float64,
    'maximumChildren': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'meetingRoomYN': pl.Utf8,
    'memberAwardRoomGrp': pl.Utf8,
    'minimumOccupancy': pl.Float64,
    'numberOfRooms': pl.Float64,
    'oRMSUpsellAmt': pl.Float64,
    'organizationID': pl.Int64,
    'ormsDrtier1': pl.Float64,
    'ormsDrtier2': pl.Float64,
    'ormsDrtier3': pl.Float64,
    'ormsDrxtra2ndAdult': pl.Float64,
    'ormsDrxtraAdult': pl.Float64,
    'ormsDrxtraChild': pl.Float64,
    'ormsUpsellRank': pl.Float64,
    'ownerroomflag': pl.Utf8,
    'physical': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'productClass': pl.Utf8,
    'property': pl.Utf8,
    'pseudoRoomType': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCategory': pl.Utf8,
    'rateCategoryDesc': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateFloor': pl.Float64,
    'ratecategoryid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repRateCategory': pl.Utf8,
    'repRateCategoryDescription': pl.Utf8,
    'repSmokingPrefDescription': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'replacesCategory': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomInfoURL': pl.Utf8,
    'roomPool': pl.Utf8,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomcategorypmsref': pl.Utf8,
    'roomclassid': pl.Utf8,
    'rotationGroup': pl.Utf8,
    'sLabel': pl.Utf8,
    'salesFlag': pl.Utf8,
    'sellThruRuleYn': pl.Utf8,
    'sendIFC': pl.Utf8,
    'sequence': pl.Float64,
    'smoking': pl.Utf8,
    'smokingPrefDesc': pl.Utf8,
    'suiteYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'yieldStatus': pl.Utf8,
}
```
```python
country_details_schema = {
    'addressdoctorMode': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryMainGroup': pl.Utf8,
    'countryid': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayCountryFlagYn': pl.Utf8,
    'guestAddressFormat': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'isoCode': pl.Utf8,
    'isoName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'printSequence': pl.Float64,
    'propertyAddressFormat': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'showSequence': pl.Float64,
    'statisticCode': pl.Utf8,
    'status': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
```python
region_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'regionDescription': pl.Utf8,
    'regionid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
rate_season_day_details_schema = {
    'centralSeasonCode': pl.Utf8,
    'centralSeasonDescription': pl.Utf8,
    'dSI': pl.Int64,
    'dayKey': pl.Utf8,
    'deletedYn': pl.Utf8,
    'displayColor': pl.Utf8,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'rateseasonid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'seasonCode': pl.Utf8,
    'seasonDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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