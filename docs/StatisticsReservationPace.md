# StatisticsReservationPace
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `statisticsReservationPace`
> The Reservation Pace subject area contains daily rooms and revenue information on reservations on the books as of specific dates in the past (snapshot dates) summarized by Property PACERATECODE Room Type Channel and Rate Code.
  
**Return:** [`[StatisticsReservationPaceType]`](#statisticsreservationpacetype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsReservationPaceQueryArgumentsType!`](#statisticsreservationpacequeryargumentstype) |  |

## Object Types

### StatisticsReservationPaceType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationPaceFactDetails | [`StatisticsReservationPaceReservationPaceFactDetailsType`](#statisticsreservationpacereservationpacefactdetailstype) | Reservation Pace Fact |
| 2 | paceStayDateDetails | [`StatisticsReservationPacePaceStayDateDetailsType`](#statisticsreservationpacepacestaydatedetailstype) | Pace Stay Date Details |
| 3 | paceMarketDetails | [`StatisticsReservationPacePaceMarketDetailsType`](#statisticsreservationpacepacemarketdetailstype) | Pace Market Details |
| 4 | paceRateCodeDetails | [`StatisticsReservationPacePaceRateCodeDetailsType`](#statisticsreservationpacepaceratecodedetailstype) | Pace Rate Code Details |
| 5 | pacePropertyDetails | [`StatisticsReservationPacePacePropertyDetailsType`](#statisticsreservationpacepacepropertydetailstype) | Pace Property |
| 6 | paceRoomTypeDetails | [`StatisticsReservationPacePaceRoomTypeDetailsType`](#statisticsreservationpacepaceroomtypedetailstype) | Pace Room Type Details |
| 7 | paceChannelDetails | [`StatisticsReservationPacePaceChannelDetailsType`](#statisticsreservationpacepacechanneldetailstype) | Pace Channel Details |
| 8 | reservationPaceSnapshotDetails | [`StatisticsReservationPaceReservationPaceSnapshotDetailsType`](#statisticsreservationpacereservationpacesnapshotdetailstype) | Reservation Pace Snapshot |
| 9 | statisticsReservationPaceRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsReservationPaceReservationPaceFactDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrAdults | `Float` | Arrangement Adults |
| 2 | arrChildren | `Float` | Arrangement Children |
| 3 | arrRooms | `Float` | Arrangement Rooms |
| 4 | budgetAmt | `Float` | Amount. |
| 5 | budgetRooms | `Float` | Budget Rooms |
| 6 | cBudgetRevenue | `Float` | Central Budget Revenue |
| 7 | cDAGRevenueDed | `Float` | C DAG Revenue Ded |
| 8 | cDAGRevenueNdd | `Float` | C DAG Revenue Ndd |
| 9 | cForecastRevenue | `Float` | Central Forecast Revenue |
| 10 | cLastYearActualRevenue | `Float` | Central Ly Actual Revenue |
| 11 | cLastYearRevenue | `Float` | Central Last Year Revenue |
| 12 | cLastYearRevenueNdd | `Float` | Central Ly Revenue Ndd |
| 13 | cLastYearRoomRevenueBlockDed | `Float` | Central Ly Room Revenue Blk Ded |
| 14 | cLastYearRoomRevenueBlockNdd | `Float` | Central Ly Room Revenue Blk Ndd |
| 15 | cLastYearRoomRevenueReservationBlockDed | `Float` | Central Ly Room Revenue Res Blk Ded |
| 16 | cLastYearRoomRevenueReservationBlockNdd | `Float` | Central Ly Room Revenue Res Blk Ndd |
| 17 | cLastYearRoomRevenueReservationIndividualDed | `Float` | Central Ly Room Revenue Res Ind Ded |
| 18 | cLastYearRoomRevenueReservationIndividualNdd | `Float` | Central Ly Room Revenue Res Ind Ndd |
| 19 | cLywarvd | `Float` | Central Lywarvd |
| 20 | cLywarvn | `Float` | Central Lywarvn |
| 21 | cPotentialRevenue | `Float` | Central Potential Revenue |
| 22 | cRevenue | `Float` | Central Revenue |
| 23 | cRevenueBlock | `Float` | Central Revenue Block |
| 24 | cRevenueNonDeduct | `Float` | Central Revenue (N) |
| 25 | cRevenueReservationTransient | `Float` | Central Revenue Resv Transient |
| 26 | cRoomRevenueBlockNdd | `Float` | Central Room Revenue Blk Ndd |
| 27 | cRoomRevenueReservationBlockDed | `Float` | Central Room Revenue Res Blk Ded |
| 28 | cRoomRevenueReservationBlockNdd | `Float` | Central Room Revenue Res Blk Ndd |
| 29 | cRoomRevenueReservationIndividualNdd | `Float` | Central Room Revenue Res Ind Ndd |
| 30 | cWGORevenueDed | `Float` | C WGO Revenue Ded |
| 31 | cWGORevenueNdd | `Float` | C WGO Revenue Ndd |
| 32 | cYGORevenueDed | `Float` | C YGO Revenue Ded |
| 33 | cYGORevenueNdd | `Float` | C YGO Revenue Ndd |
| 34 | cYWGORevenueDed | `Float` | C YWGO Revenue Ded |
| 35 | cYWGORevenueNdd | `Float` | C YWGO Revenue Ndd |
| 36 | channel | `String` | Channel |
| 37 | dSnapshotDate | `Date` | D Snapshot Date |
| 38 | dGORevenueDed | `Float` | DGO Revenue Ded |
| 39 | dGORevenueNdd | `Float` | DGO Revenue Ndd |
| 40 | dGORoomsDed | `Float` | DGO Rooms Ded |
| 41 | dGORoomsNdd | `Float` | DGO Rooms Ndd |
| 42 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 43 | forecastAmt | `Float` | Forecast Amount |
| 44 | forecastRooms | `Float` | Forecast Rooms |
| 45 | lastYearArrAdults | `Float` | Ly Arrangement Adults |
| 46 | lastYearArrChildren | `Float` | Ly Arrangement Children |
| 47 | lastYearArrRooms | `Float` | Ly Arrangement Rooms |
| 48 | lastYearRevenue | `Float` | Last Year Revenue |
| 49 | lastYearRoomRevenueBlkDed | `Float` | Ly Room Revenue Block Ded |
| 50 | lastYearRoomRevenueBlkNdd | `Float` | Ly Room Revenue Block Ndd |
| 51 | lastYearRoomRevenueResBlockDed | `Float` | Ly Room Revenue Reservation Blk Ded |
| 52 | lastYearRoomRevenueResBlockNdd | `Float` | Ly Room Revenue Reservation Blk Ndd |
| 53 | lastYearRoomRevenueResIndividualDed | `Float` | Ly Room Revenue Reservation Ind Ded |
| 54 | lastYearRoomRevenueResIndividualNdd | `Float` | Ly Room Revenue Reservation Ind Ndd |
| 55 | lastYearStayRoomsBlkDed | `Float` | Ly Stay Rooms Block Ded |
| 56 | lastYearStayRoomsBlkNdd | `Float` | Ly Stay Rooms Block Ndd |
| 57 | lastYearStayRoomsResBlockDed | `Float` | Ly Stay Rooms Reservation Blk Ded |
| 58 | lastYearStayRoomsResBlockNdd | `Float` | Ly Stay Rooms Reservation Blk Ndd |
| 59 | lastYearStayRoomsResIndividualDed | `Float` | Ly Stay Rooms Reservation Ind Ded |
| 60 | lastYearStayRoomsResIndividualNdd | `Float` | Ly Stay Rooms Reservation Ind Ndd |
| 61 | lyActualRooms | `Float` | Last Year Actual Rooms |
| 62 | lyCompRoomNts | `Float` | Last Year Comp Room Nts |
| 63 | lyOoRooms | `Float` | Last Year Oo Rooms |
| 64 | lyRevenueDed | `Float` | Last Year Revenue Ded |
| 65 | lyRevenueNdd | `Float` | Last Year Revenue Ndd |
| 66 | lyRoomsDed | `Float` | Last Year Rooms Ded |
| 67 | lyRoomsNdd | `Float` | Last Year Rooms Ndd |
| 68 | lywarmd | `Float` | Lywarmd |
| 69 | lywarmn | `Float` | Lywarmn |
| 70 | lywarvd | `Float` | Lywarvd |
| 71 | lywarvn | `Float` | Lywarvn |
| 72 | marketCode | `String` | Market Code |
| 73 | ooRooms | `Float` | Oo Rooms |
| 74 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 75 | physicalRooms | `Float` | Physical Rooms |
| 76 | potentialRevenue | `Float` | Potential Revenue |
| 77 | property | `String` | Code to uniquely identify the Property |
| 78 | rateCode | `String` | Rate Code |
| 79 | revenue | `Float` | Revenue |
| 80 | revenueN | `Float` | Revenue Non Deduct |
| 81 | revenueBlock | `Float` | Revenue Block |
| 82 | revenueResvTransient | `Float` | Revenue Reservation Transient |
| 83 | room | `Float` | Room |
| 84 | roomN | `Float` | Room Non Deduct |
| 85 | roomBlock | `Float` | Room Block |
| 86 | roomCategory | `String` | Room Category |
| 87 | roomReservationTransient | `Float` | Room Reservation Transient |
| 88 | roomRevenueBlkNdd | `Float` | Room Revenue Block Ndd |
| 89 | roomRevenueResBlockDed | `Float` | Room Revenue Reservation Blk Ded |
| 90 | roomRevenueResBlockNdd | `Float` | Room Revenue Reservation Blk Ndd |
| 91 | roomRevenueResIndividualNdd | `Float` | Room Revenue Reservation Ind Ndd |
| 92 | roomsToSell | `Float` | Rooms To Sell |
| 93 | rowcount | `Float` | Rowcount |
| 94 | snapshotDate | `Date` | Date the Snapshot was created |
| 95 | stayDate | `Date` | Stay Date |
| 96 | stayExchangeRate | `Float` | Stay Exchange Rate |
| 97 | stayRoomsBlkNdd | `Float` | Stay Rooms Block Ndd |
| 98 | stayRoomsResBlockDed | `Float` | Stay Rooms Reservation Blk Ded |
| 99 | stayRoomsResBlockNdd | `Float` | Stay Rooms Reservation Blk Ndd |
| 100 | stayRoomsResIndividualNdd | `Float` | Stay Rooms Reservation Ind Ndd |
| 101 | wGORevenueDed | `Float` | WGO Revenue Ded |
| 102 | wGORevenueNdd | `Float` | WGO Revenue Ndd |
| 103 | wGORoomsDed | `Float` | WGO Rooms Ded |
| 104 | wGORoomsNdd | `Float` | WGO Rooms Ndd |
| 105 | yGORevenueDed | `Float` | YGO Revenue Ded |
| 106 | yGORevenueNdd | `Float` | YGO Revenue Ndd |
| 107 | yGORoomsDed | `Float` | YGO Rooms Ded |
| 108 | yGORoomsNdd | `Float` | YGO Rooms Ndd |
| 109 | yWGORevenueDed | `Float` | YWGO Revenue Ded |
| 110 | yWGORevenueNdd | `Float` | YWGO Revenue Ndd |
| 111 | yWGORoomsDed | `Float` | YWGO Rooms Ded |
| 112 | yWGORoomsNdd | `Float` | YWGO Rooms Ndd |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceStayDateDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dayDesc | `String` | Day Description. |
| 2 | dayEndDate | `Date` | Day End Date. |
| 3 | dayNumberOfMonth | `Float` | Day number of the month. |
| 4 | dayNumberOfQuarter | `Float` | Day number of the quarter. |
| 5 | dayNumberOfWeek | `String` | Day number of the week. |
| 6 | dayOfYear | `Float` | Day of the Year. |
| 7 | dayTimespan | `Float` | Day Timespan. |
| 8 | daysOfMonth | `Float` | Month Timespan. |
| 9 | daysOfQuarter | `Float` | Quarter Timespan. |
| 10 | daysOfYear | `Float` | Year Timespan. |
| 11 | internalMonthkey | `Float` | Monthkey |
| 12 | isoWeekOfYear | `String` | Iso Week of Year |
| 13 | julianDaykey | `String` | Julian Daykey |
| 14 | lastYearDaykey | `Date` | Last Year Daykey |
| 15 | monthComparison | `String` | Month Description. |
| 16 | monthEndDate | `Date` | Month End Date. |
| 17 | monthKey | `String` | Month Key |
| 18 | monthName | `String` | Month Name. |
| 19 | monthNumber | `Float` | Month of the year. |
| 20 | monthOfQuarter | `Float` | Month of the quarter. |
| 21 | monthYrKey | `String` | Month Year Key |
| 22 | priorJulianDaykey | `String` | Prior Julian Daykey |
| 23 | priorMonthKey | `String` | Prior Month Key |
| 24 | priorWeekKey | `String` | Prior Week Key |
| 25 | priorYearDaykey | `Date` | Prior Year Daykey |
| 26 | priorYearKey | `String` | Prior Year Key |
| 27 | priorYearMonthKey | `String` | Prior Year Month Key |
| 28 | priorYearQuarterKey | `String` | Prior Year Quarter Key |
| 29 | priorYearWeekKey | `String` | Prior Year Week Key |
| 30 | quarter | `String` | Quarter Description. |
| 31 | quarterEndDate | `Date` | Quarter End Date. |
| 32 | quarterKey | `String` | Quarter Key |
| 33 | quarterNumber | `String` | Quarter of the year. |
| 34 | stayDate | `Date` | Stay Date |
| 35 | weekDay | `String` | Week Day |
| 36 | weekDsc | `String` | Week Dsc |
| 37 | weekEndDate | `Date` | End date of the week. |
| 38 | weekEndDsc | `String` | Week End Dsc |
| 39 | weekEndKey | `String` | Week End Key |
| 40 | weekEndMonthDsc | `String` | Week End Month Dsc |
| 41 | weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| 42 | weekKey | `String` | Week Key |
| 43 | weekNumber | `String` | Week of the year. |
| 44 | weekOfMonth | `String` | Week of the month. |
| 45 | weekTimespan | `Float` | Week Timespan. |
| 46 | yearComparison | `Float` | Year Comparison |
| 47 | yearDsc | `String` | Year description. |
| 48 | yearEndDate | `Date` | Year End Date. |
| 49 | yearKey | `String` | Year Key |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceMarketDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralMarketCode | `String` | Central Market Code |
| 2 | centralMarketDescription | `String` | Central Market Description |
| 3 | centralMarketGroup | `String` | Central Market Group |
| 4 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | displayColor | `String` | Display Color |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveflag | `String` | Inactive Flag |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | internalDeletedflag | `String` | Deleted Flag |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | locationID | `String` | Internal ID to uniquely identify the Property |
| 16 | marketCode | `String` | Market Code |
| 17 | marketDescription | `String` | Market Description |
| 18 | marketGroup | `String` | Market group attached to the market code |
| 19 | marketGroupDescription | `String` | Market Group Description |
| 20 | marketGroupOrderBy | `Float` | Market Group Order By |
| 21 | marketOrderBy | `Float` | Market Order By |
| 22 | marketgroupid | `String` | Marketgroupid |
| 23 | marketid | `String` | Marketid |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | printGroup | `String` | Print Group for Nationality Report |
| 27 | property | `String` | Code to uniquely identify the Property |
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

### StatisticsReservationPacePaceRateCodeDetailsType

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
| 10 | backToBackYn | `String` | Back To Back Y/N |
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
| 22 | beginBookingDate | `Date` | Begin Booking Date |
| 23 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 24 | breakfastPrice | `Float` | Breakfast Price |
| 25 | bypassHurdleYn | `String` | In case of ORMS when this flag is Y system ignore this rate code from Hurdle Check. |
| 26 | bypassRankCheckYn | `String` | Indicates that this rate code will not go through rank validations if value is 'Y'. |
| 27 | cBaseAmount | `Float` | Central Base Amount |
| 28 | cBbarBaseAmount | `Float` | Central Bbar Base Amount |
| 29 | cBreakfastPrice | `Float` | Central Bfst Price |
| 30 | cDbaseAmount | `Float` | Central Dbase Amount |
| 31 | cDiscountRateAmount | `Float` | Central Discount Rate Amount |
| 32 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 33 | cExchangeDate | `Date` | Central Xchange Date |
| 34 | cExchangeRate | `Float` | Central Xchange Rate |
| 35 | cRateFloor | `Float` | Central Rate Floor |
| 36 | cRateLevel | `Float` | Central Rate Level |
| 37 | cRodBaseAmount | `Float` | Central Rod Base Amount |
| 38 | cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| 39 | catPackageCode | `String` | Stores the catering package code linked to this rate code. |
| 40 | cateringPackageYN | `String` | Specifies if a catering package is linked to this rate code. |
| 41 | centralRateCategory | `String` | Central Rate Category |
| 42 | centralRateCategoryDescription | `String` | Central Rate Category Description |
| 43 | centralRateClass | `String` | Central Rate Class |
| 44 | centralRateClassDescription | `String` | Central Rate Class Description |
| 45 | changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| 46 | closedToArrival | `String` | Days the rate restriction is not available for arrival |
| 47 | commissionCode | `String` | Commission Code |
| 48 | commissionPct | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| 49 | commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| 50 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 51 | commissionableYn | `String` | Commissionable Y/N |
| 52 | complimentaryYn | `String` | Complimentary Y/N |
| 53 | currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| 54 | currencyCode | `String` | Currency Code |
| 55 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 56 | dailyRatesYn | `String` | Daily Rates Y/N |
| 57 | dayuseYn | `String` | Day use reservation Y/N. |
| 58 | dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| 59 | dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| 60 | dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| 61 | dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| 62 | dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| 63 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 64 | defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| 65 | deletedFlag | `String` | Deleted Flag |
| 66 | depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| 67 | deptCode | `String` | Department code for the transaction. |
| 68 | discountRateAmount | `Float` | Discount rate amount value. |
| 69 | discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| 70 | discountYn | `String` | Discount Flag. |
| 71 | displayRegional | `String` | Display Regional |
| 72 | displaySet | `String` | Display Set |
| 73 | distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| 74 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 75 | endBookingDate | `Date` | End Booking Date |
| 76 | exchangePostingType | `String` | Exchange Posting Type |
| 77 | externalLockedYn | `String` | External Locked Y/N |
| 78 | extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| 79 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 80 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 81 | flatOrPercentage | `String` | Flat Or Percentage |
| 82 | folioText | `String` | Text displayed on the Folio |
| 83 | frequentFlyerYn | `String` | Frequent Flyer Y/N |
| 84 | gDSAllowedYn | `String` | Is this rate code available for GDS |
| 85 | groupCode | `String` | Group Code |
| 86 | highlightRateAmountYn | `String` | To highlight on the rate query |
| 87 | houseUseYn | `String` | House Use Y/N |
| 88 | inactiveDate | `DateTime` | Inactive Date |
| 89 | insertDate | `DateTime` | Insert Date |
| 90 | insertUser | `Float` | Insert User |
| 91 | internalLocationId | `String` | Location ID |
| 92 | internalOrganizationId | `Float` | Organization ID |
| 93 | jRNUpdateDate | `Date` | JRN Update Date |
| 94 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 95 | label | `String` | Label |
| 96 | locationID | `String` | Internal ID to uniquely identify the Property |
| 97 | longInfo | `String` | Long Info |
| 98 | losUnit | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| 99 | loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| 100 | mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| 101 | marketCode | `String` | Market Code |
| 102 | marketDescription | `String` | Market Description |
| 103 | marketGroupCode | `String` | Market Group Code |
| 104 | marketGroupDescription | `String` | Market Group Description |
| 105 | marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| 106 | maxDvanceBooking | `Float` | Max Dvance Booking |
| 107 | maxLos | `Float` | Max Los |
| 108 | maxOccupancy | `Float` | Max Occupancy |
| 109 | mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| 110 | minAdvanceBooking | `Float` | Minimum Advance Booking |
| 111 | minOccupancy | `Float` | Minimum Occupancy |
| 112 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 113 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 114 | multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| 115 | myfideliouploadflag | `String` | Myfideliouploadflag |
| 116 | negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| 117 | occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| 118 | occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| 119 | operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| 120 | orderBy | `Float` | Order By |
| 121 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 122 | orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| 123 | overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| 124 | ownerRateYn | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| 125 | packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| 126 | packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| 127 | packageYn | `String` | Package Y/N |
| 128 | packages | `String` | Packages |
| 129 | pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| 130 | pkgTransactionCode | `String` | Package Transaction Code |
| 131 | pkgTransactionCodeWk | `String` | Package Transaction Code Wk |
| 132 | postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| 133 | postingRhythum | `String` | Posting Rhythum |
| 134 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 135 | printRateYn | `String` | Print Rate Y/N |
| 136 | privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| 137 | privilegedYn | `String` | Indicates if rate is privileged or not. |
| 138 | profitTransactionCode | `String` | Profit Transaction Code |
| 139 | property | `String` | Indicates if the value set for the specific property. |
| 140 | propertyName | `String` | Property Name |
| 141 | rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| 142 | rankValue | `Float` | Rank Value |
| 143 | rateBucket | `String` | Yield rate bucket |
| 144 | rateBucketDescription | `String` | Rate Bucket Description |
| 145 | rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| 146 | rateCategory | `String` | Rate Category |
| 147 | rateCategoryDescription | `String` | Rate Category Description |
| 148 | rateClass | `String` | Rate Class |
| 149 | rateClassDescription | `String` | Rate Class Description |
| 150 | rateCode | `String` | Rate Code |
| 151 | rateCodeDescription | `String` | Rate Code Description |
| 152 | rateCodeId | `String` | Rate Code ID |
| 153 | rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| 154 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 155 | rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| 156 | rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| 157 | rateLevel | `Float` | Rate Level this rate code belongs to. |
| 158 | rateinfoUrl | `String` | Rateinfo Url |
| 159 | ratesToGDSYn | `String` | Needs to send this rate to GDS or not. |
| 160 | redemptionRateYn | `String` | Redemption Rate Y/N |
| 161 | repMarketCode | `String` | Reporting Market Code |
| 162 | repMarketDescription | `String` | Reporting Market Description |
| 163 | repMarketGroupCode | `String` | Reporting Market Group Code |
| 164 | repMarketGroupDescription | `String` | Reporting Market Group Description |
| 165 | repRateBucket | `String` | Reporting Rate Bucket |
| 166 | repRateBucketDescription | `String` | Reporting Rate Bucket Description |
| 167 | repRoomTypeDescs | `String` | Reporting Room Type Descs |
| 168 | repRoomTypes | `String` | Reporting Room Types |
| 169 | repSourceCode | `String` | Reporting Source Code |
| 170 | repSourceDescription | `String` | Reporting Source Description |
| 171 | repSourceGroupCode | `String` | Reporting Source Group Code |
| 172 | repSourceGroupDescription | `String` | Reporting Source Group Description |
| 173 | repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| 174 | resort | `String` | Property |
| 175 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 176 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 177 | rodBaseAmount | `Float` | Rod Base Amount |
| 178 | rodBaseFltPct | `String` | Rod Base Flt Pct |
| 179 | rodBaseRounding | `String` | Rod Base Rounding |
| 180 | rodBasedYn | `String` | Is the group code rate of day based |
| 181 | rodYn | `String` | Rod Y/N |
| 182 | roomAssignmentValue | `Float` | Room Assignment Value |
| 183 | roomTypeDescs | `String` | Room Type Descs |
| 184 | roomTypes | `String` | Room Types |
| 185 | sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| 186 | sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| 187 | sellSequence | `Float` | Sell Sequence |
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
| 198 | tieredYn | `String` | Indicates if the rate is a tiered rate. |
| 199 | transactionCode | `String` | Rate transaction code |
| 200 | transactionCodeWk | `String` | Transaction Code Wk |
| 201 | transactionTaxInclYN | `String` | Transaction code is inclusive of tax Y/N |
| 202 | transactionWkTaxInclYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| 203 | updateDate | `DateTime` | Update Date |
| 204 | updateUser | `Float` | Update User |
| 205 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 206 | voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| 207 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 208 | wkDeptCode | `String` | Wk Dept Code |
| 209 | yieldAs | `String` | Yield As |
| 210 | yieldableYn | `String` | Yieldable Y/N |
| 211 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePacePropertyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| 2 | aRBalanceTrxCode | `String` | Internal |
| 3 | aRCreditTrxCode | `String` | Internal |
| 4 | accessCode | `String` | Access Code |
| 5 | agingLevel1 | `Float` | Aging bucket 1 |
| 6 | agingLevel2 | `Float` | Aging bucket 2 |
| 7 | agingLevel3 | `Float` | Aging bucket 3 |
| 8 | agingLevel4 | `Float` | Aging bucket 4 |
| 9 | agingLevel5 | `Float` | Aging bucket 5 |
| 10 | airport | `String` | The Airport Code for the airport near the property |
| 11 | airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| 12 | airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| 13 | allContacts | `String` | All Contacts |
| 14 | allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| 15 | allowancePeriodAdj | `String` | Period for the allowance |
| 16 | alternateYn | `String` | Property is alternate or actual search. |
| 17 | arAccountNumberFormat | `String` | Number format of AR account no. |
| 18 | arAgent | `String` | Default Account Type for an Agent for the Property |
| 19 | arCompany | `String` | Default Account Type for a Company for the Property |
| 20 | arGroups | `String` | Default Account Type for a Group for the Property |
| 21 | arIndividuals | `String` | Default Account Type for Individual for the Property |
| 22 | arSettleCode | `String` | Internal |
| 23 | arTypewriter | `String` | Internal |
| 24 | awardsTimeout | `Float` | Internal |
| 25 | baseLanguage | `String` | The base language of the Hotel |
| 26 | beginDate | `DateTime` | Begin Date |
| 27 | blackoutPeriodNotes | `String` | Blackout period notes defaulted onto the FIT Contract at time of creation. |
| 28 | block | `String` | Block |
| 29 | bookYn | `String` | Book Y/N |
| 30 | brArea | `String` | Ball Room Area |
| 31 | brSeats | `Float` | No of Ballroom Seats |
| 32 | brandCode | `String` | Brand Code |
| 33 | budgetMonth | `Float` | Financial Year of the Property |
| 34 | busblockType | `String` | Busblock Type |
| 35 | businessId | `String` | Business ID |
| 36 | businessRegCode | `String` | Business Reg Code |
| 37 | cCreditLimit | `Float` | Central Credit Limit |
| 38 | cDoubleRate2 | `Float` | Central Dbl Rate2 |
| 39 | cDoubleRate1 | `Float` | Central Dbl Rate1 |
| 40 | cExchangeDate | `Date` | Central Xchange Date |
| 41 | cExchangeRate | `Float` | Central Xchange Rate |
| 42 | cSglRate2 | `Float` | Central Sgl Rate2 |
| 43 | cSglRate1 | `Float` | Central Sgl Rate1 |
| 44 | cSuiRate2 | `Float` | Central Sui Rate2 |
| 45 | cSuiRate1 | `Float` | Central Sui Rate1 |
| 46 | cTplRate2 | `Float` | Central Tpl Rate2 |
| 47 | cTplRate1 | `Float` | Central Tpl Rate1 |
| 48 | cWarningAmount | `Float` | Central Warning Amount |
| 49 | cROCode | `String` | CRO Code |
| 50 | cRSResort | `String` | Not used |
| 51 | cashShiftDrop | `String` | Internal |
| 52 | cashYn | `String` | Cash Y/N |
| 53 | cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| 54 | cateringCurrencyFormat | `String` | Catering currency format. |
| 55 | centralCurrencyCode | `String` | Central Currency Code |
| 56 | centralCurrencyDescription | `String` | Central Currency Description |
| 57 | centralPropertyType | `String` | Central Property Type |
| 58 | chainCode | `String` | Chain Code |
| 59 | chainDescription | `String` | Chain Description |
| 60 | chainMode | `String` | Chain Mode |
| 61 | checkExgPaidout | `String` | Internal |
| 62 | checkInTime | `DateTime` | The Hotel official check intime |
| 63 | checkOutTime | `DateTime` | The Hotel official check out time |
| 64 | checkShiftDrop | `String` | Internal |
| 65 | checkTrxcode | `String` | Internal |
| 66 | city | `String` | City |
| 67 | cityDescription | `String` | City Description. |
| 68 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 69 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 70 | comNameXrefId | `Float` | Internal |
| 71 | companyAddressType | `String` | Internal |
| 72 | companyPhoneType | `String` | Internal |
| 73 | configYn | `String` | Config Y/N |
| 74 | configurationMode | `String` | Internal |
| 75 | confirmRegcardPrinter | `String` | Internal |
| 76 | copies | `Float` | Copies |
| 77 | countryCode | `String` | Country Code |
| 78 | countryMode | `String` | Country Mode |
| 79 | countryName | `String` | Country Name |
| 80 | creditLimit | `Float` | Credit Limit |
| 81 | currencyCode | `String` | Currency Code |
| 82 | currencyDecimals | `Float` | Number of decimals to designate currency |
| 83 | currencyDescription | `String` | Currency Description |
| 84 | currencyExgPaidout | `String` | Not used |
| 85 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 86 | curtainColor | `String` | Color that of the background |
| 87 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 88 | dateForAging | `String` | Date the aging should begin |
| 89 | dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| 90 | dblNum | `String` | Not used |
| 91 | dblRate2 | `Float` | Not used |
| 92 | dblRate1 | `Float` | Not used |
| 93 | decimalPlaces | `Float` | Number of places for the default currency |
| 94 | decimalSeparator | `String` | Type of decimal separator |
| 95 | defaultCommissionPercentage | `String` | Not used |
| 96 | defaultFaxType | `String` | Not used |
| 97 | defaultFolioStyle | `Float` | Folio style to be used for all guests |
| 98 | defaultGroupsRateCode | `String` | Not used |
| 99 | defaultGuestAddress | `String` | Default guest address format. |
| 100 | defaultMembershipType | `String` | Future use |
| 101 | defaultPostingRoom | `String` | Future use |
| 102 | defaultPrepaidComm | `String` | Not used. |
| 103 | defaultPrinter | `String` | Not Used |
| 104 | defaultPropertyAddress | `String` | Default property address format. |
| 105 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 106 | defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| 107 | defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| 108 | defaultRegistrationCard | `String` | Default registration card for the property. |
| 109 | defaultReservationType | `String` | The Default reservation type for this property |
| 110 | defaultTrxCommissionCode | `String` | Not used. |
| 111 | deletedFlag | `String` | Deleted Flag |
| 112 | depositLedgerTrxCode | `String` | Future use |
| 113 | destinationId | `String` | Destination ID |
| 114 | dfltPkgTranCode | `String` | Future use |
| 115 | dfltTranCodeRateCode | `String` | Future use |
| 116 | directions | `String` | Internal |
| 117 | dirsales | `String` | Future use |
| 118 | disableLoginYn | `String` | LOGIN into the application is disabled. |
| 119 | downloadRestYn | `String` | Download Rest Y/N |
| 120 | dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| 121 | email | `String` | Email |
| 122 | endDate | `DateTime` | End Date |
| 123 | exchangePostingType | `String` | Exchange Posting Type |
| 124 | expHotelCode | `String` | Hotel code used for third party exports |
| 125 | expiryDate | `Date` | Expiry Date |
| 126 | extExpFileLocation | `String` | Future use |
| 127 | extPropertyCode | `String` | Future use |
| 128 | externalScYn | `String` | Indicates that the property uses an external SC system. |
| 129 | fax | `String` | Fax |
| 130 | faxNoFormat | `String` | Fax number formats. |
| 131 | fileTransferFormat | `String` | Not used. |
| 132 | fiscalEndDate | `Date` | Future use |
| 133 | fiscalPeriodType | `String` | Future use |
| 134 | fiscalStartDate | `Date` | Future use |
| 135 | fiscalStartMonth | `Float` | Fiscal Start Month |
| 136 | fiscalStartYear | `Float` | Fiscal Start Year |
| 137 | flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| 138 | floorNumExecutiveFloor | `String` | Floor number of executive floor. |
| 139 | flowCode | `String` | Future use |
| 140 | fnsTier | `String` | Property Free Nights Stay Tier. |
| 141 | folioLanguage1 | `String` | Other languages |
| 142 | folioLanguage2 | `String` | Other languages |
| 143 | folioLanguage3 | `String` | Other languages |
| 144 | folioLanguage4 | `String` | Other languages |
| 145 | font | `Float` | Not used |
| 146 | genmgr | `String` | Future use |
| 147 | groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| 148 | guestLookupTimeout | `Float` | Future use |
| 149 | hotelCode | `String` | Property Code. |
| 150 | hotelFc | `String` | Future use |
| 151 | hotelId | `String` | Hotel ID |
| 152 | hotelType | `String` | Hotel Type |
| 153 | imgDirectionId | `Float` | Future use |
| 154 | imgHotelId | `Float` | Future use |
| 155 | imgMapId | `Float` | Future use |
| 156 | inactiveDaysForGuestProfil | `Float` | Future use |
| 157 | inactiveFlag | `String` | Inactive Flag |
| 158 | individualAddressType | `String` | Future use |
| 159 | individualPhoneType | `String` | Future use |
| 160 | individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| 161 | insertDate | `DateTime` | Insert Date |
| 162 | insertUser | `Float` | Insert User |
| 163 | intTaxIncludedYn | `String` | Int Tax Included Y/N |
| 164 | internalLocationId | `String` | Location ID |
| 165 | internalOrganizationId | `Float` | Organization ID |
| 166 | inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| 167 | jRNUpdateDate | `Date` | JRN Update Date |
| 168 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 169 | keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| 170 | latitude | `Float` | Latitude of the property in decimal |
| 171 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 172 | legalOwner | `String` | The owner who owns this property |
| 173 | licenseCode | `String` | License Code |
| 174 | localCurrencyFormat | `String` | Format for the local currency. |
| 175 | locationID | `String` | Internal ID to uniquely identify the Property |
| 176 | longDateFormat | `String` | Long date format for the property. |
| 177 | longStayControl | `Float` | The default length of stay |
| 178 | longitude | `Float` | Longitude of the property in decimal |
| 179 | maxAdultsFamilyRoom | `Float` | Maximum adults in family rooms. |
| 180 | maxChildrenFamilyRoom | `Float` | Maximum children in family rooms. |
| 181 | maxNoNights | `Float` | Not used |
| 182 | maxOccupancy | `Float` | Max Occupancy |
| 183 | maxcreditdays | `Float` | Maxcreditdays |
| 184 | mbsSupportedYn | `String` | Indicates if the property supports MBS. Used in some file exports. |
| 185 | meetRooms | `Float` | Future use |
| 186 | meetSeats | `Float` | Future use |
| 187 | meetSpace | `Float` | Future use |
| 188 | meetingFc | `String` | Future use |
| 189 | minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| 190 | nameIdLink | `Float` | Internal |
| 191 | nightAuditCashierId | `String` | Future use |
| 192 | notes | `String` | Notes |
| 193 | numberBeds | `Float` | Total number of beds in this property |
| 194 | numberFloors | `Float` | Total number of floors in this property |
| 195 | numberRooms | `Float` | Number Rooms |
| 196 | opsMhotYn | `String` | Ops Mhot Y/N |
| 197 | opsMht2Yn | `String` | Ops Mht2 Y/N |
| 198 | opusCurrencyCode | `String` | Future use |
| 199 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 200 | ownership | `String` | Future use |
| 201 | packageLoss | `String` | Package Loss code for a particular package |
| 202 | packageProfit | `String` | Package Profit code for a particular Package |
| 203 | passerbyMarket | `String` | Market code for passerby |
| 204 | passerbySource | `String` | Source code for passerby |
| 205 | path | `String` | Path |
| 206 | pathId | `Float` | This is the value used in Interfaces to map  to a Resort Code. |
| 207 | paymentDate | `DateTime` | Payment Date |
| 208 | perReservationRoomLimit | `Float` | Future use |
| 209 | pmsActiveYn | `String` | Indicate if PMS was active on that date or not. |
| 210 | postCode | `String` | Post Code |
| 211 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 212 | proinfoUrl | `String` | Proinfo Url |
| 213 | propMapUrl | `String` | Property MAP URL. |
| 214 | propPicUrl | `String` | Property picture URL. |
| 215 | property | `String` | Property |
| 216 | propertyName | `String` | Property Name |
| 217 | propertyType | `String` | Property Type |
| 218 | qtyConnectingRooms | `Float` | Number of connecting rooms. |
| 219 | qtyDoubleRooms | `Float` | Number of double rooms. |
| 220 | qtyFamilyRooms | `Float` | Number of family rooms. |
| 221 | qtyGuestElevators | `Float` | Number of guest elevators. |
| 222 | qtyGuestRoomFloors | `Float` | Total of guest rooms floors. |
| 223 | qtyHandicappedRooms | `Float` | Number of handicapped rooms. |
| 224 | qtyNonSmokingRooms | `Float` | Number of non smoking rooms. |
| 225 | qtySingleRooms | `Float` | Number of single rooms. |
| 226 | qtySuites | `Float` | Number of suites. |
| 227 | qtyTwinRooms | `Float` | Number of twin rooms. |
| 228 | quotedCurrency | `String` | Future use |
| 229 | rateTierYn | `String` | Rate Tier Y/N |
| 230 | reconcileDate | `DateTime` | Records the date on which the reconciliation is done |
| 231 | regionCode | `String` | Region Code |
| 232 | regionDescription | `String` | Region Description |
| 233 | repPasserbyMarket | `String` | Reporting Passerby Market |
| 234 | repPasserbySource | `String` | Reporting Passerby Source |
| 235 | repState | `String` | Reporting State |
| 236 | repStateDescription | `String` | Reporting State Desc |
| 237 | reportYn | `String` | Report Y/N |
| 238 | reservationYN | `String` | Indicates if this menu item depends on the reservation. |
| 239 | restaurant | `Float` | Future use |
| 240 | rhythmSheets | `Float` | Total number of Sheets |
| 241 | rhythmTowels | `Float` | Total number of Towels |
| 242 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 243 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 244 | roomAmenity | `String` | Room amenity. |
| 245 | saveProfiles | `Float` | To store number of days before deleting the gest profile |
| 246 | scActiveYn | `String` | Sc Active Y/N |
| 247 | scriptId | `Float` | Script ID |
| 248 | season1 | `String` | Future use |
| 249 | season2 | `String` | Future use |
| 250 | season3 | `String` | Future use |
| 251 | season4 | `String` | Future use |
| 252 | season5 | `String` | Future use |
| 253 | sendLeadAsBooking | `String` | Send Lead As Booking |
| 254 | sfaActiveYn | `String` | Sfa Active Y/N |
| 255 | sglNum | `String` | Future use |
| 256 | sglRate1 | `Float` | Future use |
| 257 | sglRate2 | `Float` | Future use |
| 258 | shopDescription | `String` | Shop description. |
| 259 | shortDateFormat | `String` | Short date format for the property. |
| 260 | sourceCommission | `String` | For default commission percentage |
| 261 | state | `String` | State |
| 262 | stateDesc | `String` | State Description of the Guest of Payee |
| 263 | street | `String` | The street of the property. |
| 264 | suiNum | `String` | Future use |
| 265 | suiRate1 | `Float` | Future use |
| 266 | suiRate2 | `Float` | Future use |
| 267 | summCurrencyCode | `String` | Internal |
| 268 | taCommission | `String` | For default commission percentage |
| 269 | telephone | `String` | The direct dial phone number of this property |
| 270 | telephoneNoFormat | `String` | Formats for telephone number |
| 271 | thousandSeparator | `String` | Separator for monetory values |
| 272 | timeFormat | `String` | Default time format for the property. |
| 273 | timezoneRegion | `String` | Time zone region selected by the employee. |
| 274 | tollfree | `String` | Toll free telephone number. |
| 275 | totalRooms | `Float` | Future use |
| 276 | touristNumber | `String` | Tourist Number |
| 277 | tplNum | `String` | Future use |
| 278 | tplRate1 | `Float` | Future use |
| 279 | tplRate2 | `Float` | Future use |
| 280 | translateMulticharYn | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| 281 | turnawayCode | `String` | Turnaway Code |
| 282 | updateDate | `DateTime` | Update Date |
| 283 | updateUser | `Float` | Update User |
| 284 | vatId | `String` | VAT ID of this property. |
| 285 | videoCoStart | `DateTime` | Video check out start time. |
| 286 | videoCoStop | `DateTime` | Video check out end time. |
| 287 | videocheckoutPrinter | `String` | Future use |
| 288 | vosActiveYn | `String` | Vos Active Y/N |
| 289 | wakeUpDelay | `Float` | Future use |
| 290 | warningAmount | `Float` | Amount at which warning is raised. |
| 291 | webaddress | `String` | Webaddress of the property |
| 292 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 293 | xresortNumber | `Float` | Numbers (1 thru 10) given to the resorts in the schema to print the tax collected by that resort in the gstfolio when proper merge codes are selected. |
| 294 | zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceRoomTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessibleYn | `String` | Indicates if this room type is accessibility compliant. |
| 2 | activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| 3 | activeflag | `Date` | Activeflag |
| 4 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 5 | autoIncludeYn | `String` | Include room type in the rate header for Myfidelio rates. |
| 6 | autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | cIncrements | `Float` | Central Increments |
| 10 | cInitialRoundUp | `Float` | Central Initial Round Up |
| 11 | cORMSDrtier1 | `Float` | Central Orms Drtier1 |
| 12 | cORMSDrtier2 | `Float` | Central Orms Drtier2 |
| 13 | cORMSDrtier3 | `Float` | Central Orms Drtier3 |
| 14 | cORMSDrxtra2ndAdult | `Float` | Central Orms Drxtra 2nd Adult |
| 15 | cORMSDrxtraAdult | `Float` | Central Orms Drxtra Adult |
| 16 | cORMSDrxtraChild | `Float` | Central Orms Drxtra Child |
| 17 | cORMSUpsellAmount | `Float` | Central Orms Upsell Amt |
| 18 | cRateAmount | `Float` | Central Rate Amount |
| 19 | cRateFloor | `Float` | Central Rate Floor |
| 20 | cRSDescription | `String` | CRS Description |
| 21 | canDeleteYn | `String` | Can Delete Y/N |
| 22 | centralRoomClass | `String` | Central Room Class |
| 23 | centralRoomClassDescription | `String` | Central Room Class Description |
| 24 | centralRoomType | `String` | Central Room Type |
| 25 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 26 | compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| 27 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 28 | defOccupancy | `Float` | Default occupancy for the room type |
| 29 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 30 | defaultRateDesc | `String` | Default Rate Description |
| 31 | defaultratecodeid | `String` | Defaultratecodeid |
| 32 | deletedFlag | `String` | Deleted Flag |
| 33 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 34 | genericroomflag | `String` | Genericroomflag |
| 35 | housekeeping | `String` | Room type shows in housekeeping Y/N |
| 36 | imageId | `Float` | Image ID |
| 37 | inactiveDate | `DateTime` | Inactive Date |
| 38 | inactiveflag | `String` | Inactive Flag |
| 39 | increments | `Float` | Increment value for rates by day by LOS. |
| 40 | initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| 41 | insertDate | `DateTime` | Insert Date |
| 42 | insertUser | `Float` | Insert User |
| 43 | internalDeletedflag | `String` | Deleted Flag |
| 44 | jRNUpdateDate | `Date` | JRN Update Date |
| 45 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 46 | label | `String` | Label |
| 47 | locationID | `String` | Internal ID to uniquely identify the Property |
| 48 | longDescription | `String` | Long Description |
| 49 | maintenanceYn | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| 50 | maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| 51 | maxOccupancy | `Float` | Max Occupancy |
| 52 | maxOccupancyAdults | `Float` | The maximum occupancy of adults for this room category. |
| 53 | maxOccupancyChildren | `Float` | The maximum occupancy of children for this room category. |
| 54 | maxRollaways | `Float` | Not used |
| 55 | meetingroomflag | `String` | Meetingroomflag |
| 56 | memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| 57 | minOccupancy | `Float` | Minimum Occupancy |
| 58 | numberRooms | `Float` | Number Rooms |
| 59 | oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| 60 | orderBy | `Float` | Order By |
| 61 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 62 | ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| 63 | ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| 64 | ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| 65 | ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| 66 | ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| 67 | ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| 68 | ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| 69 | ownerroomflag | `String` | Ownerroomflag |
| 70 | physicalRoomYn | `String` | Physical Room Y/N |
| 71 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 72 | property | `String` | Code to uniquely identify the Property |
| 73 | pseudoRoomYN | `String` | Pseudo Room YN |
| 74 | psuedoRoomType | `String` | Psuedo Room Type |
| 75 | rateAmount | `Float` | Rate Amount |
| 76 | rateCategory | `String` | Rate Category |
| 77 | rateCategoryDesc | `String` | Rate Category Description |
| 78 | rateCode | `String` | Rate Code |
| 79 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 80 | ratecategoryid | `String` | Ratecategoryid |
| 81 | repItem | `String` | Reporting Item |
| 82 | repItemName | `String` | Reporting Item Name |
| 83 | repItemOrderby | `Float` | Reporting Item Orderby |
| 84 | repOrderBy | `Float` | Reporting Order By |
| 85 | repRateCategory | `String` | Reporting Rate Category |
| 86 | repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| 87 | repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| 88 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 89 | replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| 90 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 91 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 92 | roomClass | `String` | Room Class |
| 93 | roomClassDescription | `String` | Room Class Description |
| 94 | roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| 95 | roomType | `String` | Room Type |
| 96 | roomTypeDescription | `String` | Room Type Description |
| 97 | roomcategoryid | `String` | Roomcategoryid |
| 98 | roomcategorypmsref | `String` | Roomcategorypmsref |
| 99 | roomclassid | `String` | Roomclassid |
| 100 | roominfoUrl | `String` | URL where room information is stored. |
| 101 | rotationGroup | `String` | Rotation Group |
| 102 | sBedtype | `String` | S Bedtype |
| 103 | sLabel | `String` | S Label |
| 104 | salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| 105 | sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| 106 | sendToInterfaceYn | `String` | Room type sent to interface Y/N |
| 107 | smokingPrefDesc | `String` | Smoking Pref Description |
| 108 | smokingPreference | `String` | Smoking Preference |
| 109 | suiteroomflag | `String` | Suiteroomflag |
| 110 | updateDate | `DateTime` | Update Date |
| 111 | updateUser | `Float` | Update User |
| 112 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 113 | yieldCategory | `String` | Yield Category |
| 114 | yieldableroomflag | `String` | Yieldableroomflag |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceChannelDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralOriginCode | `String` | Central Origin Code |
| 4 | centralOriginDescription | `String` | Central Origin Description |
| 5 | chainCode | `String` | Chain Code |
| 6 | channelid | `String` | Channelid |
| 7 | comments | `String` | Comments |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | displayColor | `String` | Display Color |
| 11 | entityName | `String` | Entity Name |
| 12 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 13 | inactiveDate | `DateTime` | Inactive Date |
| 14 | inactiveflag | `String` | Inactive Flag |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | internalDeletedflag | `String` | Deleted Flag |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | languageCode | `String` | Language Code |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | orderBy | `Float` | Order By |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | originCode | `String` | Origin Code |
| 26 | originDescription | `String` | Origin Description |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | ranking | `Float` | Ranking |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationPaceReservationPaceSnapshotDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dayDesc | `String` | Day Description. |
| 2 | dayEndDate | `Date` | Day End Date. |
| 3 | dayNumberOfMonth | `Float` | Day number of the month. |
| 4 | dayNumberOfQuarter | `Float` | Day number of the quarter. |
| 5 | dayNumberOfWeek | `String` | Day number of the week. |
| 6 | dayOfYear | `Float` | Day of the Year. |
| 7 | dayTimespan | `Float` | Day Timespan. |
| 8 | internalMonthkey | `Float` | Monthkey |
| 9 | internalYearkey | `Float` | Yearkey |
| 10 | isoWeekOfYear | `String` | Iso Week of Year |
| 11 | julianDaykey | `String` | Julian Daykey |
| 12 | lastYearDaykey | `Date` | Last Year Daykey |
| 13 | monthDsc | `String` | Month Description. |
| 14 | monthEndDate | `Date` | Month End Date. |
| 15 | monthKey | `String` | Month Key |
| 16 | monthName | `String` | Month Name. |
| 17 | monthNumber | `Float` | Month of the year. |
| 18 | monthOfQuarter | `Float` | Month of the quarter. |
| 19 | monthTimespan | `Float` | Month Timespan. |
| 20 | monthYrKey | `String` | Month Year Key |
| 21 | priorJulianDaykey | `String` | Prior Julian Daykey |
| 22 | priorMonthKey | `String` | Prior Month Key |
| 23 | priorWeekKey | `String` | Prior Week Key |
| 24 | priorYearDaykey | `Date` | Prior Year Daykey |
| 25 | priorYearKey | `String` | Prior Year Key |
| 26 | priorYearMonthKey | `String` | Prior Year Month Key |
| 27 | priorYearQuarterKey | `String` | Prior Year Quarter Key |
| 28 | priorYearWeekKey | `String` | Prior Year Week Key |
| 29 | quarterDsc | `String` | Quarter Description. |
| 30 | quarterEndDate | `Date` | Quarter End Date. |
| 31 | quarterKey | `String` | Quarter Key |
| 32 | quarterNumber | `String` | Quarter of the year. |
| 33 | quarterTimespan | `Float` | Quarter Timespan. |
| 34 | snapshotDateComparison | `Date` | Snapshot Date Comparison |
| 35 | weekDay | `String` | Week Day |
| 36 | weekDsc | `String` | Week Dsc |
| 37 | weekEndDate | `Date` | End date of the week. |
| 38 | weekEndDsc | `String` | Week End Dsc |
| 39 | weekEndKey | `String` | Week End Key |
| 40 | weekEndMonthDsc | `String` | Week End Month Dsc |
| 41 | weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| 42 | weekKey | `String` | Week Key |
| 43 | weekNumber | `String` | Week of the year. |
| 44 | weekOfMonth | `String` | Week of the month. |
| 45 | weekTimespan | `Float` | Week Timespan. |
| 46 | yearDsc | `String` | Year description. |
| 47 | yearEndDate | `Date` | Year End Date. |
| 48 | yearKey | `String` | Year Key |
| 49 | yearTimespan | `Float` | Year Timespan. |

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

### StatisticsReservationPaceQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| resvpacefactDetailsChannel | `StringInput` | Channel |
| resvpacefactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvpacefactDetailsMarketCode | `StringInput` | Market Code |
| resvpacefactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvpacefactDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| resvpacefactDetailsRateCode | `StringInput` | Rate Code |
| resvpacefactDetailsRoomCategory | `StringInput` | Room Category |
| resvpacefactDetailsSnapshotDate | `DateInput!` | Date the Snapshot was created<br>`@mandatoryInput` |
| resvpacefactDetailsStayDate | `DateInput!` | Stay Date<br>`@mandatoryInput` |
| pacestaydateDetailsDaykey | `DateInput` | Stay Date |
| pacemarketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| pacemarketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| pacemarketDetailsMarketCode | `StringInput` | Market Code |
| pacemarketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| pacemarketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| pacemarketDetailsResort | `StringInput` | Code to uniquely identify the Property |
| paceratecodeDetailsBaseRateCode | `StringInput` | Base Rate Code |
| paceratecodeDetailsBeginBookingDate | `DateInput` | Begin Booking Date |
| paceratecodeDetailsCommissionCode | `StringInput` | Commission Code |
| paceratecodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| paceratecodeDetailsDailyRatesYn | `StringInput` | Daily Rates Y/N |
| paceratecodeDetailsDbaseRateCode | `StringInput` | The rate code on which this rate shedule is dynamically based on. |
| paceratecodeDetailsEndBookingDate | `DateInput` | End Booking Date |
| paceratecodeDetailsGroupCode | `StringInput` | Group Code |
| paceratecodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| paceratecodeDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| paceratecodeDetailsMarketCode | `StringInput` | Market Code |
| paceratecodeDetailsMaxLos | `FloatInput` | Max Los |
| paceratecodeDetailsMaxOccupancy | `FloatInput` | Max Occupancy |
| paceratecodeDetailsMinOccupancy | `FloatInput` | Minimum Occupancy |
| paceratecodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| paceratecodeDetailsOrsSellSequence | `FloatInput` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| paceratecodeDetailsPendingApprovalYn | `StringInput` | Indicates whether the rate code is pending for approval or not |
| paceratecodeDetailsRateBucket | `StringInput` | Yield rate bucket |
| paceratecodeDetailsRateCode | `StringInput` | Rate Code |
| paceratecodeDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |
| paceratecodeDetailsResort | `StringInput` | Property |
| paceratecodeDetailsSellSequence | `FloatInput` | Sell Sequence |
| paceratecodeDetailsSourceCode | `StringInput` | Source Code |
| paceresortDetailsCrsResort | `StringInput` | Not used |
| paceresortDetailsCountryCode | `StringInput` | Country Code |
| paceresortDetailsCurrencyCode | `StringInput` | Currency Code |
| paceresortDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| paceresortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| paceresortDetailsNameIdLink | `FloatInput` | Internal |
| paceresortDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| paceresortDetailsResort | `StringInput` | Property |
| paceresortDetailsResortType | `StringInput` | Property Type |
| paceroomtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| paceroomtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| paceroomtypeDetailsLabel | `StringInput` | Label |
| paceroomtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| paceroomtypeDetailsResort | `StringInput` | Code to uniquely identify the Property |
| paceroomtypeDetailsRoomClass | `StringInput` | Room Class |
| paceroomtypeDetailsRoomCategory | `StringInput` | Room Type |
| paceroomtypeDetailsYieldCategory | `StringInput` | Yield Category |
| pacechannelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| pacechannelDetailsEntityName | `StringInput` | Entity Name |
| pacechannelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| pacechannelDetailsLanguageCode | `StringInput` | Language Code |
| pacechannelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| pacechannelDetailsAttributeCode | `StringInput` | Origin Code |
| pacechannelDetailsTitleSuffix | `FloatInput` | Title Suffix |
| resvpacesnapshotdimDetailsDaykey | `DateInput` | Snapshot Date Comparison |
#### Validation Rules

**`mandatoryInput`**
- resvpacefactDetailsResort
- resvpacefactDetailsSnapshotDate
- resvpacefactDetailsStayDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsReservationPace($input: StatisticsReservationPaceQueryArgumentsType!) {
  statisticsReservationPace(input: $input) @stream {
    reservationPaceFactDetails {
      arrAdults
      arrChildren
      arrRooms
      budgetAmt
      budgetRooms
      cBudgetRevenue
      cDAGRevenueDed
      cDAGRevenueNdd
      cForecastRevenue
      cLastYearActualRevenue
      cLastYearRevenue
      cLastYearRevenueNdd
      cLastYearRoomRevenueBlockDed
      cLastYearRoomRevenueBlockNdd
      cLastYearRoomRevenueReservationBlockDed
      cLastYearRoomRevenueReservationBlockNdd
      cLastYearRoomRevenueReservationIndividualDed
      cLastYearRoomRevenueReservationIndividualNdd
      cLywarvd
      cLywarvn
      cPotentialRevenue
      cRevenue
      cRevenueBlock
      cRevenueNonDeduct
      cRevenueReservationTransient
      cRoomRevenueBlockNdd
      cRoomRevenueReservationBlockDed
      cRoomRevenueReservationBlockNdd
      cRoomRevenueReservationIndividualNdd
      cWGORevenueDed
      cWGORevenueNdd
      cYGORevenueDed
      cYGORevenueNdd
      cYWGORevenueDed
      cYWGORevenueNdd
      channel
      dSnapshotDate
      dGORevenueDed
      dGORevenueNdd
      dGORoomsDed
      dGORoomsNdd
      dSI
      forecastAmt
      forecastRooms
      lastYearArrAdults
      lastYearArrChildren
      lastYearArrRooms
      lastYearRevenue
      lastYearRoomRevenueBlkDed
      lastYearRoomRevenueBlkNdd
      lastYearRoomRevenueResBlockDed
      lastYearRoomRevenueResBlockNdd
      lastYearRoomRevenueResIndividualDed
      lastYearRoomRevenueResIndividualNdd
      lastYearStayRoomsBlkDed
      lastYearStayRoomsBlkNdd
      lastYearStayRoomsResBlockDed
      lastYearStayRoomsResBlockNdd
      lastYearStayRoomsResIndividualDed
      lastYearStayRoomsResIndividualNdd
      lyActualRooms
      lyCompRoomNts
      lyOoRooms
      lyRevenueDed
      lyRevenueNdd
      lyRoomsDed
      lyRoomsNdd
      lywarmd
      lywarmn
      lywarvd
      lywarvn
      marketCode
      ooRooms
      organizationID
      physicalRooms
      potentialRevenue
      property
      rateCode
      revenue
      revenueN
      revenueBlock
      revenueResvTransient
      room
      roomN
      roomBlock
      roomCategory
      roomReservationTransient
      roomRevenueBlkNdd
      roomRevenueResBlockDed
      roomRevenueResBlockNdd
      roomRevenueResIndividualNdd
      roomsToSell
      rowcount
      snapshotDate
      stayDate
      stayExchangeRate
      stayRoomsBlkNdd
      stayRoomsResBlockDed
      stayRoomsResBlockNdd
      stayRoomsResIndividualNdd
      wGORevenueDed
      wGORevenueNdd
      wGORoomsDed
      wGORoomsNdd
      yGORevenueDed
      yGORevenueNdd
      yGORoomsDed
      yGORoomsNdd
      yWGORevenueDed
      yWGORevenueNdd
      yWGORoomsDed
      yWGORoomsNdd
    }
    paceStayDateDetails {
      dayDesc
      dayEndDate
      dayNumberOfMonth
      dayNumberOfQuarter
      dayNumberOfWeek
      dayOfYear
      dayTimespan
      daysOfMonth
      daysOfQuarter
      daysOfYear
      internalMonthkey
      isoWeekOfYear
      julianDaykey
      lastYearDaykey
      monthComparison
      monthEndDate
      monthKey
      monthName
      monthNumber
      monthOfQuarter
      monthYrKey
      priorJulianDaykey
      priorMonthKey
      priorWeekKey
      priorYearDaykey
      priorYearKey
      priorYearMonthKey
      priorYearQuarterKey
      priorYearWeekKey
      quarter
      quarterEndDate
      quarterKey
      quarterNumber
      stayDate
      weekDay
      weekDsc
      weekEndDate
      weekEndDsc
      weekEndKey
      weekEndMonthDsc
      weekEndMonthEndDate
      weekKey
      weekNumber
      weekOfMonth
      weekTimespan
      yearComparison
      yearDsc
      yearEndDate
      yearKey
    }
    paceMarketDetails {
      centralMarketCode
      centralMarketDescription
      centralMarketGroup
      centralMarketGroupDescription
      dSI
      deletedFlag
      displayColor
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketDescription
      marketGroup
      marketGroupDescription
      marketGroupOrderBy
      marketOrderBy
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
    paceRateCodeDetails {
      aSBRateCycle
      addition
      advBaseRateCode
      advBaseRounding
      advanceBaseCompareYN
      advanceDailyBaseYN
      advanceDailyRateYN
      alternateRateCode
      availabilityUpdateYn
      backToBackYn
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
      beginBookingDate
      breakfastInclYn
      breakfastPrice
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
      centralRateCategory
      centralRateCategoryDescription
      centralRateClass
      centralRateClassDescription
      changeState
      closedToArrival
      commissionCode
      commissionPct
      commissionYn
      commissionablePerc
      commissionableYn
      complimentaryYn
      currCodeDecimalPos
      currencyCode
      dSI
      dailyRatesYn
      dayuseYn
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
      discountYn
      displayRegional
      displaySet
      distributeYn
      doubleRoomSupplementYN
      endBookingDate
      exchangePostingType
      externalLockedYn
      extraPersonChargeBegins
      fitDiscountLevel
      fitDiscountPerc
      flatOrPercentage
      folioText
      frequentFlyerYn
      gDSAllowedYn
      groupCode
      highlightRateAmountYn
      houseUseYn
      inactiveDate
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      locationID
      longInfo
      losUnit
      loyaltyProgramYn
      mandateResvProfiles
      marketCode
      marketDescription
      marketGroupCode
      marketGroupDescription
      marshaRateProgram
      maxDvanceBooking
      maxLos
      maxOccupancy
      mfnUploadYn
      minAdvanceBooking
      minOccupancy
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      multiplication
      myfideliouploadflag
      negotiatedYN
      occupancyBasedYn
      occupancyLevel
      operatorType
      orderBy
      organizationID
      orsSellSequence
      overridePackageYn
      ownerRateYn
      packageTransactionTaxInclYN
      packageTransactionWkTaxInclYN
      packageYn
      packages
      pendingApprovalYn
      pkgTransactionCode
      pkgTransactionCodeWk
      postingRhythmNights
      postingRhythum
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
      rateCode
      rateCodeDescription
      rateCodeId
      rateCodeLockedYn
      rateFloor
      rateFloorOverrideYn
      rateIncludesTaxYn
      rateLevel
      rateinfoUrl
      ratesToGDSYn
      redemptionRateYn
      repMarketCode
      repMarketDescription
      repMarketGroupCode
      repMarketGroupDescription
      repRateBucket
      repRateBucketDescription
      repRoomTypeDescs
      repRoomTypes
      repSourceCode
      repSourceDescription
      repSourceGroupCode
      repSourceGroupDescription
      repeatPostingRhythmYn
      resort
      rnaInsertDate
      rnaUpdateDate
      rodBaseAmount
      rodBaseFltPct
      rodBaseRounding
      rodBasedYn
      rodYn
      roomAssignmentValue
      roomTypeDescs
      roomTypes
      sdowBeginBookingDate
      sdowEndBookingDate
      sellSequence
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
      tieredYn
      transactionCode
      transactionCodeWk
      transactionTaxInclYN
      transactionWkTaxInclYN
      updateDate
      updateUser
      upsellYn
      voucherBenefitRateYn
      weekendDays
      wkDeptCode
      yieldAs
      yieldableYn
      ymCode
    }
    pacePropertyDetails {
      aRAccountNumberMandYN
      aRBalanceTrxCode
      aRCreditTrxCode
      accessCode
      agingLevel1
      agingLevel2
      agingLevel3
      agingLevel4
      agingLevel5
      airport
      airportDistance
      airportTime
      allContacts
      allowLoginYn
      allowancePeriodAdj
      alternateYn
      arAccountNumberFormat
      arAgent
      arCompany
      arGroups
      arIndividuals
      arSettleCode
      arTypewriter
      awardsTimeout
      baseLanguage
      beginDate
      blackoutPeriodNotes
      block
      bookYn
      brArea
      brSeats
      brandCode
      budgetMonth
      busblockType
      businessId
      businessRegCode
      cCreditLimit
      cDoubleRate2
      cDoubleRate1
      cExchangeDate
      cExchangeRate
      cSglRate2
      cSglRate1
      cSuiRate2
      cSuiRate1
      cTplRate2
      cTplRate1
      cWarningAmount
      cROCode
      cRSResort
      cashShiftDrop
      cashYn
      cateringCurrencyCode
      cateringCurrencyFormat
      centralCurrencyCode
      centralCurrencyDescription
      centralPropertyType
      chainCode
      chainDescription
      chainMode
      checkExgPaidout
      checkInTime
      checkOutTime
      checkShiftDrop
      checkTrxcode
      city
      cityDescription
      comAddress
      comMethod
      comNameXrefId
      companyAddressType
      companyPhoneType
      configYn
      configurationMode
      confirmRegcardPrinter
      copies
      countryCode
      countryMode
      countryName
      creditLimit
      currencyCode
      currencyDecimals
      currencyDescription
      currencyExgPaidout
      currencySymbol
      curtainColor
      dSI
      dateForAging
      dateSeparator
      dblNum
      dblRate2
      dblRate1
      decimalPlaces
      decimalSeparator
      defaultCommissionPercentage
      defaultFaxType
      defaultFolioStyle
      defaultGroupsRateCode
      defaultGuestAddress
      defaultMembershipType
      defaultPostingRoom
      defaultPrepaidComm
      defaultPrinter
      defaultPropertyAddress
      defaultRateCode
      defaultRatecodePcr
      defaultRatecodeRack
      defaultRegistrationCard
      defaultReservationType
      defaultTrxCommissionCode
      deletedFlag
      depositLedgerTrxCode
      destinationId
      dfltPkgTranCode
      dfltTranCodeRateCode
      directions
      dirsales
      disableLoginYn
      downloadRestYn
      dutyManagerPager
      email
      endDate
      exchangePostingType
      expHotelCode
      expiryDate
      extExpFileLocation
      extPropertyCode
      externalScYn
      fax
      faxNoFormat
      fileTransferFormat
      fiscalEndDate
      fiscalPeriodType
      fiscalStartDate
      fiscalStartMonth
      fiscalStartYear
      flags
      floorNumExecutiveFloor
      flowCode
      fnsTier
      folioLanguage1
      folioLanguage2
      folioLanguage3
      folioLanguage4
      font
      genmgr
      groupRoomWarning
      guestLookupTimeout
      hotelCode
      hotelFc
      hotelId
      hotelType
      imgDirectionId
      imgHotelId
      imgMapId
      inactiveDaysForGuestProfil
      inactiveFlag
      individualAddressType
      individualPhoneType
      individualRoomWarning
      insertDate
      insertUser
      intTaxIncludedYn
      internalLocationId
      internalOrganizationId
      inventoryYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepAvailability
      latitude
      leadsend
      legalOwner
      licenseCode
      localCurrencyFormat
      locationID
      longDateFormat
      longStayControl
      longitude
      maxAdultsFamilyRoom
      maxChildrenFamilyRoom
      maxNoNights
      maxOccupancy
      maxcreditdays
      mbsSupportedYn
      meetRooms
      meetSeats
      meetSpace
      meetingFc
      minDaysBet2ReminderLetter
      nameIdLink
      nightAuditCashierId
      notes
      numberBeds
      numberFloors
      numberRooms
      opsMhotYn
      opsMht2Yn
      opusCurrencyCode
      organizationID
      ownership
      packageLoss
      packageProfit
      passerbyMarket
      passerbySource
      path
      pathId
      paymentDate
      perReservationRoomLimit
      pmsActiveYn
      postCode
      primaryKeyID
      proinfoUrl
      propMapUrl
      propPicUrl
      property
      propertyName
      propertyType
      qtyConnectingRooms
      qtyDoubleRooms
      qtyFamilyRooms
      qtyGuestElevators
      qtyGuestRoomFloors
      qtyHandicappedRooms
      qtyNonSmokingRooms
      qtySingleRooms
      qtySuites
      qtyTwinRooms
      quotedCurrency
      rateTierYn
      reconcileDate
      regionCode
      regionDescription
      repPasserbyMarket
      repPasserbySource
      repState
      repStateDescription
      reportYn
      reservationYN
      restaurant
      rhythmSheets
      rhythmTowels
      rnaInsertDate
      rnaUpdateDate
      roomAmenity
      saveProfiles
      scActiveYn
      scriptId
      season1
      season2
      season3
      season4
      season5
      sendLeadAsBooking
      sfaActiveYn
      sglNum
      sglRate1
      sglRate2
      shopDescription
      shortDateFormat
      sourceCommission
      state
      stateDesc
      street
      suiNum
      suiRate1
      suiRate2
      summCurrencyCode
      taCommission
      telephone
      telephoneNoFormat
      thousandSeparator
      timeFormat
      timezoneRegion
      tollfree
      totalRooms
      touristNumber
      tplNum
      tplRate1
      tplRate2
      translateMulticharYn
      turnawayCode
      updateDate
      updateUser
      vatId
      videoCoStart
      videoCoStop
      videocheckoutPrinter
      vosActiveYn
      wakeUpDelay
      warningAmount
      webaddress
      weekendDays
      xresortNumber
      zeroInvPurDays
    }
    paceRoomTypeDetails {
      accessibleYn
      activeDate
      activeflag
      autoCheckinYn
      autoIncludeYn
      autoRoomAssignYn
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
      defOccupancy
      defaultRateCode
      defaultRateDesc
      defaultratecodeid
      deletedFlag
      evisitorFacilityId
      genericroomflag
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
      maintenanceYn
      maxFixBedOccupancy
      maxOccupancy
      maxOccupancyAdults
      maxOccupancyChildren
      maxRollaways
      meetingroomflag
      memberAwardRoomGrp
      minOccupancy
      numberRooms
      oRMSUpsellAmt
      orderBy
      organizationID
      ormsDrtier1
      ormsDrtier2
      ormsDrtier3
      ormsDrxtra2ndAdult
      ormsDrxtraAdult
      ormsDrxtraChild
      ormsUpsellRank
      ownerroomflag
      physicalRoomYn
      primaryKeyID
      property
      pseudoRoomYN
      psuedoRoomType
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
      roomPool
      roomType
      roomTypeDescription
      roomcategoryid
      roomcategorypmsref
      roomclassid
      roominfoUrl
      rotationGroup
      sBedtype
      sLabel
      salesFlag
      sellThruRuleYn
      sendToInterfaceYn
      smokingPrefDesc
      smokingPreference
      suiteroomflag
      updateDate
      updateUser
      upsellYn
      yieldCategory
      yieldableroomflag
    }
    paceChannelDetails {
      businessTitle
      canDeleteYn
      centralOriginCode
      centralOriginDescription
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
      locationID
      masterSubKeywordYn
      orderBy
      organizationID
      originCode
      originDescription
      primaryKeyID
      ranking
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      titleSuffix
      updateDate
      updateUser
    }
    reservationPaceSnapshotDetails {
      dayDesc
      dayEndDate
      dayNumberOfMonth
      dayNumberOfQuarter
      dayNumberOfWeek
      dayOfYear
      dayTimespan
      internalMonthkey
      internalYearkey
      isoWeekOfYear
      julianDaykey
      lastYearDaykey
      monthDsc
      monthEndDate
      monthKey
      monthName
      monthNumber
      monthOfQuarter
      monthTimespan
      monthYrKey
      priorJulianDaykey
      priorMonthKey
      priorWeekKey
      priorYearDaykey
      priorYearKey
      priorYearMonthKey
      priorYearQuarterKey
      priorYearWeekKey
      quarterDsc
      quarterEndDate
      quarterKey
      quarterNumber
      quarterTimespan
      snapshotDateComparison
      weekDay
      weekDsc
      weekEndDate
      weekEndDsc
      weekEndKey
      weekEndMonthDsc
      weekEndMonthEndDate
      weekKey
      weekNumber
      weekOfMonth
      weekTimespan
      yearDsc
      yearEndDate
      yearKey
      yearTimespan
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
reservation_pace_fact_details_schema = {
    'arrAdults': pl.Float64,
    'arrChildren': pl.Float64,
    'arrRooms': pl.Float64,
    'budgetAmt': pl.Float64,
    'budgetRooms': pl.Float64,
    'cBudgetRevenue': pl.Float64,
    'cDAGRevenueDed': pl.Float64,
    'cDAGRevenueNdd': pl.Float64,
    'cForecastRevenue': pl.Float64,
    'cLastYearActualRevenue': pl.Float64,
    'cLastYearRevenue': pl.Float64,
    'cLastYearRevenueNdd': pl.Float64,
    'cLastYearRoomRevenueBlockDed': pl.Float64,
    'cLastYearRoomRevenueBlockNdd': pl.Float64,
    'cLastYearRoomRevenueReservationBlockDed': pl.Float64,
    'cLastYearRoomRevenueReservationBlockNdd': pl.Float64,
    'cLastYearRoomRevenueReservationIndividualDed': pl.Float64,
    'cLastYearRoomRevenueReservationIndividualNdd': pl.Float64,
    'cLywarvd': pl.Float64,
    'cLywarvn': pl.Float64,
    'cPotentialRevenue': pl.Float64,
    'cRevenue': pl.Float64,
    'cRevenueBlock': pl.Float64,
    'cRevenueNonDeduct': pl.Float64,
    'cRevenueReservationTransient': pl.Float64,
    'cRoomRevenueBlockNdd': pl.Float64,
    'cRoomRevenueReservationBlockDed': pl.Float64,
    'cRoomRevenueReservationBlockNdd': pl.Float64,
    'cRoomRevenueReservationIndividualNdd': pl.Float64,
    'cWGORevenueDed': pl.Float64,
    'cWGORevenueNdd': pl.Float64,
    'cYGORevenueDed': pl.Float64,
    'cYGORevenueNdd': pl.Float64,
    'cYWGORevenueDed': pl.Float64,
    'cYWGORevenueNdd': pl.Float64,
    'channel': pl.Utf8,
    'dSnapshotDate': pl.Utf8,
    'dGORevenueDed': pl.Float64,
    'dGORevenueNdd': pl.Float64,
    'dGORoomsDed': pl.Float64,
    'dGORoomsNdd': pl.Float64,
    'dSI': pl.Int64,
    'forecastAmt': pl.Float64,
    'forecastRooms': pl.Float64,
    'lastYearArrAdults': pl.Float64,
    'lastYearArrChildren': pl.Float64,
    'lastYearArrRooms': pl.Float64,
    'lastYearRevenue': pl.Float64,
    'lastYearRoomRevenueBlkDed': pl.Float64,
    'lastYearRoomRevenueBlkNdd': pl.Float64,
    'lastYearRoomRevenueResBlockDed': pl.Float64,
    'lastYearRoomRevenueResBlockNdd': pl.Float64,
    'lastYearRoomRevenueResIndividualDed': pl.Float64,
    'lastYearRoomRevenueResIndividualNdd': pl.Float64,
    'lastYearStayRoomsBlkDed': pl.Float64,
    'lastYearStayRoomsBlkNdd': pl.Float64,
    'lastYearStayRoomsResBlockDed': pl.Float64,
    'lastYearStayRoomsResBlockNdd': pl.Float64,
    'lastYearStayRoomsResIndividualDed': pl.Float64,
    'lastYearStayRoomsResIndividualNdd': pl.Float64,
    'lyActualRooms': pl.Float64,
    'lyCompRoomNts': pl.Float64,
    'lyOoRooms': pl.Float64,
    'lyRevenueDed': pl.Float64,
    'lyRevenueNdd': pl.Float64,
    'lyRoomsDed': pl.Float64,
    'lyRoomsNdd': pl.Float64,
    'lywarmd': pl.Float64,
    'lywarmn': pl.Float64,
    'lywarvd': pl.Float64,
    'lywarvn': pl.Float64,
    'marketCode': pl.Utf8,
    'ooRooms': pl.Float64,
    'organizationID': pl.Int64,
    'physicalRooms': pl.Float64,
    'potentialRevenue': pl.Float64,
    'property': pl.Utf8,
    'rateCode': pl.Utf8,
    'revenue': pl.Float64,
    'revenueN': pl.Float64,
    'revenueBlock': pl.Float64,
    'revenueResvTransient': pl.Float64,
    'room': pl.Float64,
    'roomN': pl.Float64,
    'roomBlock': pl.Float64,
    'roomCategory': pl.Utf8,
    'roomReservationTransient': pl.Float64,
    'roomRevenueBlkNdd': pl.Float64,
    'roomRevenueResBlockDed': pl.Float64,
    'roomRevenueResBlockNdd': pl.Float64,
    'roomRevenueResIndividualNdd': pl.Float64,
    'roomsToSell': pl.Float64,
    'rowcount': pl.Float64,
    'snapshotDate': pl.Utf8,
    'stayDate': pl.Utf8,
    'stayExchangeRate': pl.Float64,
    'stayRoomsBlkNdd': pl.Float64,
    'stayRoomsResBlockDed': pl.Float64,
    'stayRoomsResBlockNdd': pl.Float64,
    'stayRoomsResIndividualNdd': pl.Float64,
    'wGORevenueDed': pl.Float64,
    'wGORevenueNdd': pl.Float64,
    'wGORoomsDed': pl.Float64,
    'wGORoomsNdd': pl.Float64,
    'yGORevenueDed': pl.Float64,
    'yGORevenueNdd': pl.Float64,
    'yGORoomsDed': pl.Float64,
    'yGORoomsNdd': pl.Float64,
    'yWGORevenueDed': pl.Float64,
    'yWGORevenueNdd': pl.Float64,
    'yWGORoomsDed': pl.Float64,
    'yWGORoomsNdd': pl.Float64,
}
```
```python
pace_stay_date_details_schema = {
    'dayDesc': pl.Utf8,
    'dayEndDate': pl.Utf8,
    'dayNumberOfMonth': pl.Float64,
    'dayNumberOfQuarter': pl.Float64,
    'dayNumberOfWeek': pl.Utf8,
    'dayOfYear': pl.Float64,
    'dayTimespan': pl.Float64,
    'daysOfMonth': pl.Float64,
    'daysOfQuarter': pl.Float64,
    'daysOfYear': pl.Float64,
    'internalMonthkey': pl.Float64,
    'isoWeekOfYear': pl.Utf8,
    'julianDaykey': pl.Utf8,
    'lastYearDaykey': pl.Utf8,
    'monthComparison': pl.Utf8,
    'monthEndDate': pl.Utf8,
    'monthKey': pl.Utf8,
    'monthName': pl.Utf8,
    'monthNumber': pl.Float64,
    'monthOfQuarter': pl.Float64,
    'monthYrKey': pl.Utf8,
    'priorJulianDaykey': pl.Utf8,
    'priorMonthKey': pl.Utf8,
    'priorWeekKey': pl.Utf8,
    'priorYearDaykey': pl.Utf8,
    'priorYearKey': pl.Utf8,
    'priorYearMonthKey': pl.Utf8,
    'priorYearQuarterKey': pl.Utf8,
    'priorYearWeekKey': pl.Utf8,
    'quarter': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterKey': pl.Utf8,
    'quarterNumber': pl.Utf8,
    'stayDate': pl.Utf8,
    'weekDay': pl.Utf8,
    'weekDsc': pl.Utf8,
    'weekEndDate': pl.Utf8,
    'weekEndDsc': pl.Utf8,
    'weekEndKey': pl.Utf8,
    'weekEndMonthDsc': pl.Utf8,
    'weekEndMonthEndDate': pl.Utf8,
    'weekKey': pl.Utf8,
    'weekNumber': pl.Utf8,
    'weekOfMonth': pl.Utf8,
    'weekTimespan': pl.Float64,
    'yearComparison': pl.Float64,
    'yearDsc': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearKey': pl.Utf8,
}
```
```python
pace_market_details_schema = {
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroup': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroup': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupOrderBy': pl.Float64,
    'marketOrderBy': pl.Float64,
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
pace_rate_code_details_schema = {
    'aSBRateCycle': pl.Utf8,
    'addition': pl.Utf8,
    'advBaseRateCode': pl.Utf8,
    'advBaseRounding': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'advanceDailyBaseYN': pl.Utf8,
    'advanceDailyRateYN': pl.Utf8,
    'alternateRateCode': pl.Utf8,
    'availabilityUpdateYn': pl.Utf8,
    'backToBackYn': pl.Utf8,
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
    'beginBookingDate': pl.Utf8,
    'breakfastInclYn': pl.Utf8,
    'breakfastPrice': pl.Float64,
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
    'centralRateCategory': pl.Utf8,
    'centralRateCategoryDescription': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'changeState': pl.Utf8,
    'closedToArrival': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionPct': pl.Float64,
    'commissionYn': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'complimentaryYn': pl.Utf8,
    'currCodeDecimalPos': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRatesYn': pl.Utf8,
    'dayuseYn': pl.Utf8,
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
    'discountYn': pl.Utf8,
    'displayRegional': pl.Utf8,
    'displaySet': pl.Utf8,
    'distributeYn': pl.Utf8,
    'doubleRoomSupplementYN': pl.Utf8,
    'endBookingDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'externalLockedYn': pl.Utf8,
    'extraPersonChargeBegins': pl.Float64,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'flatOrPercentage': pl.Utf8,
    'folioText': pl.Utf8,
    'frequentFlyerYn': pl.Utf8,
    'gDSAllowedYn': pl.Utf8,
    'groupCode': pl.Utf8,
    'highlightRateAmountYn': pl.Utf8,
    'houseUseYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'locationID': pl.Utf8,
    'longInfo': pl.Utf8,
    'losUnit': pl.Float64,
    'loyaltyProgramYn': pl.Utf8,
    'mandateResvProfiles': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marshaRateProgram': pl.Utf8,
    'maxDvanceBooking': pl.Float64,
    'maxLos': pl.Float64,
    'maxOccupancy': pl.Float64,
    'mfnUploadYn': pl.Utf8,
    'minAdvanceBooking': pl.Float64,
    'minOccupancy': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'multiplication': pl.Utf8,
    'myfideliouploadflag': pl.Utf8,
    'negotiatedYN': pl.Utf8,
    'occupancyBasedYn': pl.Utf8,
    'occupancyLevel': pl.Float64,
    'operatorType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'orsSellSequence': pl.Float64,
    'overridePackageYn': pl.Utf8,
    'ownerRateYn': pl.Utf8,
    'packageTransactionTaxInclYN': pl.Utf8,
    'packageTransactionWkTaxInclYN': pl.Utf8,
    'packageYn': pl.Utf8,
    'packages': pl.Utf8,
    'pendingApprovalYn': pl.Utf8,
    'pkgTransactionCode': pl.Utf8,
    'pkgTransactionCodeWk': pl.Utf8,
    'postingRhythmNights': pl.Float64,
    'postingRhythum': pl.Utf8,
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
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateCodeId': pl.Utf8,
    'rateCodeLockedYn': pl.Utf8,
    'rateFloor': pl.Float64,
    'rateFloorOverrideYn': pl.Utf8,
    'rateIncludesTaxYn': pl.Utf8,
    'rateLevel': pl.Float64,
    'rateinfoUrl': pl.Utf8,
    'ratesToGDSYn': pl.Utf8,
    'redemptionRateYn': pl.Utf8,
    'repMarketCode': pl.Utf8,
    'repMarketDescription': pl.Utf8,
    'repMarketGroupCode': pl.Utf8,
    'repMarketGroupDescription': pl.Utf8,
    'repRateBucket': pl.Utf8,
    'repRateBucketDescription': pl.Utf8,
    'repRoomTypeDescs': pl.Utf8,
    'repRoomTypes': pl.Utf8,
    'repSourceCode': pl.Utf8,
    'repSourceDescription': pl.Utf8,
    'repSourceGroupCode': pl.Utf8,
    'repSourceGroupDescription': pl.Utf8,
    'repeatPostingRhythmYn': pl.Utf8,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rodBaseAmount': pl.Float64,
    'rodBaseFltPct': pl.Utf8,
    'rodBaseRounding': pl.Utf8,
    'rodBasedYn': pl.Utf8,
    'rodYn': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'roomTypeDescs': pl.Utf8,
    'roomTypes': pl.Utf8,
    'sdowBeginBookingDate': pl.Utf8,
    'sdowEndBookingDate': pl.Utf8,
    'sellSequence': pl.Float64,
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
    'tieredYn': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeWk': pl.Utf8,
    'transactionTaxInclYN': pl.Utf8,
    'transactionWkTaxInclYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'voucherBenefitRateYn': pl.Utf8,
    'weekendDays': pl.Utf8,
    'wkDeptCode': pl.Utf8,
    'yieldAs': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
pace_property_details_schema = {
    'aRAccountNumberMandYN': pl.Utf8,
    'aRBalanceTrxCode': pl.Utf8,
    'aRCreditTrxCode': pl.Utf8,
    'accessCode': pl.Utf8,
    'agingLevel1': pl.Float64,
    'agingLevel2': pl.Float64,
    'agingLevel3': pl.Float64,
    'agingLevel4': pl.Float64,
    'agingLevel5': pl.Float64,
    'airport': pl.Utf8,
    'airportDistance': pl.Utf8,
    'airportTime': pl.Utf8,
    'allContacts': pl.Utf8,
    'allowLoginYn': pl.Utf8,
    'allowancePeriodAdj': pl.Utf8,
    'alternateYn': pl.Utf8,
    'arAccountNumberFormat': pl.Utf8,
    'arAgent': pl.Utf8,
    'arCompany': pl.Utf8,
    'arGroups': pl.Utf8,
    'arIndividuals': pl.Utf8,
    'arSettleCode': pl.Utf8,
    'arTypewriter': pl.Utf8,
    'awardsTimeout': pl.Float64,
    'baseLanguage': pl.Utf8,
    'beginDate': pl.Utf8,
    'blackoutPeriodNotes': pl.Utf8,
    'block': pl.Utf8,
    'bookYn': pl.Utf8,
    'brArea': pl.Utf8,
    'brSeats': pl.Float64,
    'brandCode': pl.Utf8,
    'budgetMonth': pl.Float64,
    'busblockType': pl.Utf8,
    'businessId': pl.Utf8,
    'businessRegCode': pl.Utf8,
    'cCreditLimit': pl.Float64,
    'cDoubleRate2': pl.Float64,
    'cDoubleRate1': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cSglRate2': pl.Float64,
    'cSglRate1': pl.Float64,
    'cSuiRate2': pl.Float64,
    'cSuiRate1': pl.Float64,
    'cTplRate2': pl.Float64,
    'cTplRate1': pl.Float64,
    'cWarningAmount': pl.Float64,
    'cROCode': pl.Utf8,
    'cRSResort': pl.Utf8,
    'cashShiftDrop': pl.Utf8,
    'cashYn': pl.Utf8,
    'cateringCurrencyCode': pl.Utf8,
    'cateringCurrencyFormat': pl.Utf8,
    'centralCurrencyCode': pl.Utf8,
    'centralCurrencyDescription': pl.Utf8,
    'centralPropertyType': pl.Utf8,
    'chainCode': pl.Utf8,
    'chainDescription': pl.Utf8,
    'chainMode': pl.Utf8,
    'checkExgPaidout': pl.Utf8,
    'checkInTime': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'checkShiftDrop': pl.Utf8,
    'checkTrxcode': pl.Utf8,
    'city': pl.Utf8,
    'cityDescription': pl.Utf8,
    'comAddress': pl.Utf8,
    'comMethod': pl.Utf8,
    'comNameXrefId': pl.Float64,
    'companyAddressType': pl.Utf8,
    'companyPhoneType': pl.Utf8,
    'configYn': pl.Utf8,
    'configurationMode': pl.Utf8,
    'confirmRegcardPrinter': pl.Utf8,
    'copies': pl.Float64,
    'countryCode': pl.Utf8,
    'countryMode': pl.Utf8,
    'countryName': pl.Utf8,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDecimals': pl.Float64,
    'currencyDescription': pl.Utf8,
    'currencyExgPaidout': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'curtainColor': pl.Utf8,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'dateSeparator': pl.Utf8,
    'dblNum': pl.Utf8,
    'dblRate2': pl.Float64,
    'dblRate1': pl.Float64,
    'decimalPlaces': pl.Float64,
    'decimalSeparator': pl.Utf8,
    'defaultCommissionPercentage': pl.Utf8,
    'defaultFaxType': pl.Utf8,
    'defaultFolioStyle': pl.Float64,
    'defaultGroupsRateCode': pl.Utf8,
    'defaultGuestAddress': pl.Utf8,
    'defaultMembershipType': pl.Utf8,
    'defaultPostingRoom': pl.Utf8,
    'defaultPrepaidComm': pl.Utf8,
    'defaultPrinter': pl.Utf8,
    'defaultPropertyAddress': pl.Utf8,
    'defaultRateCode': pl.Utf8,
    'defaultRatecodePcr': pl.Utf8,
    'defaultRatecodeRack': pl.Utf8,
    'defaultRegistrationCard': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'defaultTrxCommissionCode': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositLedgerTrxCode': pl.Utf8,
    'destinationId': pl.Utf8,
    'dfltPkgTranCode': pl.Utf8,
    'dfltTranCodeRateCode': pl.Utf8,
    'directions': pl.Utf8,
    'dirsales': pl.Utf8,
    'disableLoginYn': pl.Utf8,
    'downloadRestYn': pl.Utf8,
    'dutyManagerPager': pl.Utf8,
    'email': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'expHotelCode': pl.Utf8,
    'expiryDate': pl.Utf8,
    'extExpFileLocation': pl.Utf8,
    'extPropertyCode': pl.Utf8,
    'externalScYn': pl.Utf8,
    'fax': pl.Utf8,
    'faxNoFormat': pl.Utf8,
    'fileTransferFormat': pl.Utf8,
    'fiscalEndDate': pl.Utf8,
    'fiscalPeriodType': pl.Utf8,
    'fiscalStartDate': pl.Utf8,
    'fiscalStartMonth': pl.Float64,
    'fiscalStartYear': pl.Float64,
    'flags': pl.Utf8,
    'floorNumExecutiveFloor': pl.Utf8,
    'flowCode': pl.Utf8,
    'fnsTier': pl.Utf8,
    'folioLanguage1': pl.Utf8,
    'folioLanguage2': pl.Utf8,
    'folioLanguage3': pl.Utf8,
    'folioLanguage4': pl.Utf8,
    'font': pl.Float64,
    'genmgr': pl.Utf8,
    'groupRoomWarning': pl.Float64,
    'guestLookupTimeout': pl.Float64,
    'hotelCode': pl.Utf8,
    'hotelFc': pl.Utf8,
    'hotelId': pl.Utf8,
    'hotelType': pl.Utf8,
    'imgDirectionId': pl.Float64,
    'imgHotelId': pl.Float64,
    'imgMapId': pl.Float64,
    'inactiveDaysForGuestProfil': pl.Float64,
    'inactiveFlag': pl.Utf8,
    'individualAddressType': pl.Utf8,
    'individualPhoneType': pl.Utf8,
    'individualRoomWarning': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'intTaxIncludedYn': pl.Utf8,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'inventoryYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepAvailability': pl.Float64,
    'latitude': pl.Float64,
    'leadsend': pl.Utf8,
    'legalOwner': pl.Utf8,
    'licenseCode': pl.Utf8,
    'localCurrencyFormat': pl.Utf8,
    'locationID': pl.Utf8,
    'longDateFormat': pl.Utf8,
    'longStayControl': pl.Float64,
    'longitude': pl.Float64,
    'maxAdultsFamilyRoom': pl.Float64,
    'maxChildrenFamilyRoom': pl.Float64,
    'maxNoNights': pl.Float64,
    'maxOccupancy': pl.Float64,
    'maxcreditdays': pl.Float64,
    'mbsSupportedYn': pl.Utf8,
    'meetRooms': pl.Float64,
    'meetSeats': pl.Float64,
    'meetSpace': pl.Float64,
    'meetingFc': pl.Utf8,
    'minDaysBet2ReminderLetter': pl.Float64,
    'nameIdLink': pl.Float64,
    'nightAuditCashierId': pl.Utf8,
    'notes': pl.Utf8,
    'numberBeds': pl.Float64,
    'numberFloors': pl.Float64,
    'numberRooms': pl.Float64,
    'opsMhotYn': pl.Utf8,
    'opsMht2Yn': pl.Utf8,
    'opusCurrencyCode': pl.Utf8,
    'organizationID': pl.Int64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'path': pl.Utf8,
    'pathId': pl.Float64,
    'paymentDate': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'pmsActiveYn': pl.Utf8,
    'postCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'proinfoUrl': pl.Utf8,
    'propMapUrl': pl.Utf8,
    'propPicUrl': pl.Utf8,
    'property': pl.Utf8,
    'propertyName': pl.Utf8,
    'propertyType': pl.Utf8,
    'qtyConnectingRooms': pl.Float64,
    'qtyDoubleRooms': pl.Float64,
    'qtyFamilyRooms': pl.Float64,
    'qtyGuestElevators': pl.Float64,
    'qtyGuestRoomFloors': pl.Float64,
    'qtyHandicappedRooms': pl.Float64,
    'qtyNonSmokingRooms': pl.Float64,
    'qtySingleRooms': pl.Float64,
    'qtySuites': pl.Float64,
    'qtyTwinRooms': pl.Float64,
    'quotedCurrency': pl.Utf8,
    'rateTierYn': pl.Utf8,
    'reconcileDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionDescription': pl.Utf8,
    'repPasserbyMarket': pl.Utf8,
    'repPasserbySource': pl.Utf8,
    'repState': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'reportYn': pl.Utf8,
    'reservationYN': pl.Utf8,
    'restaurant': pl.Float64,
    'rhythmSheets': pl.Float64,
    'rhythmTowels': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomAmenity': pl.Utf8,
    'saveProfiles': pl.Float64,
    'scActiveYn': pl.Utf8,
    'scriptId': pl.Float64,
    'season1': pl.Utf8,
    'season2': pl.Utf8,
    'season3': pl.Utf8,
    'season4': pl.Utf8,
    'season5': pl.Utf8,
    'sendLeadAsBooking': pl.Utf8,
    'sfaActiveYn': pl.Utf8,
    'sglNum': pl.Utf8,
    'sglRate1': pl.Float64,
    'sglRate2': pl.Float64,
    'shopDescription': pl.Utf8,
    'shortDateFormat': pl.Utf8,
    'sourceCommission': pl.Utf8,
    'state': pl.Utf8,
    'stateDesc': pl.Utf8,
    'street': pl.Utf8,
    'suiNum': pl.Utf8,
    'suiRate1': pl.Float64,
    'suiRate2': pl.Float64,
    'summCurrencyCode': pl.Utf8,
    'taCommission': pl.Utf8,
    'telephone': pl.Utf8,
    'telephoneNoFormat': pl.Utf8,
    'thousandSeparator': pl.Utf8,
    'timeFormat': pl.Utf8,
    'timezoneRegion': pl.Utf8,
    'tollfree': pl.Utf8,
    'totalRooms': pl.Float64,
    'touristNumber': pl.Utf8,
    'tplNum': pl.Utf8,
    'tplRate1': pl.Float64,
    'tplRate2': pl.Float64,
    'translateMulticharYn': pl.Utf8,
    'turnawayCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatId': pl.Utf8,
    'videoCoStart': pl.Utf8,
    'videoCoStop': pl.Utf8,
    'videocheckoutPrinter': pl.Utf8,
    'vosActiveYn': pl.Utf8,
    'wakeUpDelay': pl.Float64,
    'warningAmount': pl.Float64,
    'webaddress': pl.Utf8,
    'weekendDays': pl.Utf8,
    'xresortNumber': pl.Float64,
    'zeroInvPurDays': pl.Float64,
}
```
```python
pace_room_type_details_schema = {
    'accessibleYn': pl.Utf8,
    'activeDate': pl.Utf8,
    'activeflag': pl.Utf8,
    'autoCheckinYn': pl.Utf8,
    'autoIncludeYn': pl.Utf8,
    'autoRoomAssignYn': pl.Utf8,
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
    'defOccupancy': pl.Float64,
    'defaultRateCode': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'defaultratecodeid': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'genericroomflag': pl.Utf8,
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
    'maintenanceYn': pl.Utf8,
    'maxFixBedOccupancy': pl.Float64,
    'maxOccupancy': pl.Float64,
    'maxOccupancyAdults': pl.Float64,
    'maxOccupancyChildren': pl.Float64,
    'maxRollaways': pl.Float64,
    'meetingroomflag': pl.Utf8,
    'memberAwardRoomGrp': pl.Utf8,
    'minOccupancy': pl.Float64,
    'numberRooms': pl.Float64,
    'oRMSUpsellAmt': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'ormsDrtier1': pl.Float64,
    'ormsDrtier2': pl.Float64,
    'ormsDrtier3': pl.Float64,
    'ormsDrxtra2ndAdult': pl.Float64,
    'ormsDrxtraAdult': pl.Float64,
    'ormsDrxtraChild': pl.Float64,
    'ormsUpsellRank': pl.Float64,
    'ownerroomflag': pl.Utf8,
    'physicalRoomYn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'psuedoRoomType': pl.Utf8,
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
    'roomPool': pl.Utf8,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomcategorypmsref': pl.Utf8,
    'roomclassid': pl.Utf8,
    'roominfoUrl': pl.Utf8,
    'rotationGroup': pl.Utf8,
    'sBedtype': pl.Utf8,
    'sLabel': pl.Utf8,
    'salesFlag': pl.Utf8,
    'sellThruRuleYn': pl.Utf8,
    'sendToInterfaceYn': pl.Utf8,
    'smokingPrefDesc': pl.Utf8,
    'smokingPreference': pl.Utf8,
    'suiteroomflag': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'yieldCategory': pl.Utf8,
    'yieldableroomflag': pl.Utf8,
}
```
```python
pace_channel_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
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
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_pace_snapshot_details_schema = {
    'dayDesc': pl.Utf8,
    'dayEndDate': pl.Utf8,
    'dayNumberOfMonth': pl.Float64,
    'dayNumberOfQuarter': pl.Float64,
    'dayNumberOfWeek': pl.Utf8,
    'dayOfYear': pl.Float64,
    'dayTimespan': pl.Float64,
    'internalMonthkey': pl.Float64,
    'internalYearkey': pl.Float64,
    'isoWeekOfYear': pl.Utf8,
    'julianDaykey': pl.Utf8,
    'lastYearDaykey': pl.Utf8,
    'monthDsc': pl.Utf8,
    'monthEndDate': pl.Utf8,
    'monthKey': pl.Utf8,
    'monthName': pl.Utf8,
    'monthNumber': pl.Float64,
    'monthOfQuarter': pl.Float64,
    'monthTimespan': pl.Float64,
    'monthYrKey': pl.Utf8,
    'priorJulianDaykey': pl.Utf8,
    'priorMonthKey': pl.Utf8,
    'priorWeekKey': pl.Utf8,
    'priorYearDaykey': pl.Utf8,
    'priorYearKey': pl.Utf8,
    'priorYearMonthKey': pl.Utf8,
    'priorYearQuarterKey': pl.Utf8,
    'priorYearWeekKey': pl.Utf8,
    'quarterDsc': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterKey': pl.Utf8,
    'quarterNumber': pl.Utf8,
    'quarterTimespan': pl.Float64,
    'snapshotDateComparison': pl.Utf8,
    'weekDay': pl.Utf8,
    'weekDsc': pl.Utf8,
    'weekEndDate': pl.Utf8,
    'weekEndDsc': pl.Utf8,
    'weekEndKey': pl.Utf8,
    'weekEndMonthDsc': pl.Utf8,
    'weekEndMonthEndDate': pl.Utf8,
    'weekKey': pl.Utf8,
    'weekNumber': pl.Utf8,
    'weekOfMonth': pl.Utf8,
    'weekTimespan': pl.Float64,
    'yearDsc': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearKey': pl.Utf8,
    'yearTimespan': pl.Float64,
}
```