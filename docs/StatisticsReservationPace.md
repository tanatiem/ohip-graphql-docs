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

| Field | Type | Description |
| --- | --- | --- |
| reservationPaceFactDetails | [`StatisticsReservationPaceReservationPaceFactDetailsType`](#statisticsreservationpacereservationpacefactdetailstype) | Reservation Pace Fact |
| paceStayDateDetails | [`StatisticsReservationPacePaceStayDateDetailsType`](#statisticsreservationpacepacestaydatedetailstype) | Pace Stay Date Details |
| paceMarketDetails | [`StatisticsReservationPacePaceMarketDetailsType`](#statisticsreservationpacepacemarketdetailstype) | Pace Market Details |
| paceRateCodeDetails | [`StatisticsReservationPacePaceRateCodeDetailsType`](#statisticsreservationpacepaceratecodedetailstype) | Pace Rate Code Details |
| pacePropertyDetails | [`StatisticsReservationPacePacePropertyDetailsType`](#statisticsreservationpacepacepropertydetailstype) | Pace Property |
| paceRoomTypeDetails | [`StatisticsReservationPacePaceRoomTypeDetailsType`](#statisticsreservationpacepaceroomtypedetailstype) | Pace Room Type Details |
| paceChannelDetails | [`StatisticsReservationPacePaceChannelDetailsType`](#statisticsreservationpacepacechanneldetailstype) | Pace Channel Details |
| reservationPaceSnapshotDetails | [`StatisticsReservationPaceReservationPaceSnapshotDetailsType`](#statisticsreservationpacereservationpacesnapshotdetailstype) | Reservation Pace Snapshot |
| statisticsReservationPaceRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsReservationPaceReservationPaceFactDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrAdults | `Float` | Arrangement Adults |
| arrChildren | `Float` | Arrangement Children |
| arrRooms | `Float` | Arrangement Rooms |
| budgetAmt | `Float` | Amount. |
| budgetRooms | `Float` | Budget Rooms |
| cBudgetRevenue | `Float` | Central Budget Revenue |
| cDAGRevenueDed | `Float` | C DAG Revenue Ded |
| cDAGRevenueNdd | `Float` | C DAG Revenue Ndd |
| cForecastRevenue | `Float` | Central Forecast Revenue |
| cLastYearActualRevenue | `Float` | Central Ly Actual Revenue |
| cLastYearRevenue | `Float` | Central Last Year Revenue |
| cLastYearRevenueNdd | `Float` | Central Ly Revenue Ndd |
| cLastYearRoomRevenueBlockDed | `Float` | Central Ly Room Revenue Blk Ded |
| cLastYearRoomRevenueBlockNdd | `Float` | Central Ly Room Revenue Blk Ndd |
| cLastYearRoomRevenueReservationBlockDed | `Float` | Central Ly Room Revenue Res Blk Ded |
| cLastYearRoomRevenueReservationBlockNdd | `Float` | Central Ly Room Revenue Res Blk Ndd |
| cLastYearRoomRevenueReservationIndividualDed | `Float` | Central Ly Room Revenue Res Ind Ded |
| cLastYearRoomRevenueReservationIndividualNdd | `Float` | Central Ly Room Revenue Res Ind Ndd |
| cLywarvd | `Float` | Central Lywarvd |
| cLywarvn | `Float` | Central Lywarvn |
| cPotentialRevenue | `Float` | Central Potential Revenue |
| cRevenue | `Float` | Central Revenue |
| cRevenueBlock | `Float` | Central Revenue Block |
| cRevenueNonDeduct | `Float` | Central Revenue (N) |
| cRevenueReservationTransient | `Float` | Central Revenue Resv Transient |
| cRoomRevenueBlockNdd | `Float` | Central Room Revenue Blk Ndd |
| cRoomRevenueReservationBlockDed | `Float` | Central Room Revenue Res Blk Ded |
| cRoomRevenueReservationBlockNdd | `Float` | Central Room Revenue Res Blk Ndd |
| cRoomRevenueReservationIndividualNdd | `Float` | Central Room Revenue Res Ind Ndd |
| cWGORevenueDed | `Float` | C WGO Revenue Ded |
| cWGORevenueNdd | `Float` | C WGO Revenue Ndd |
| cYGORevenueDed | `Float` | C YGO Revenue Ded |
| cYGORevenueNdd | `Float` | C YGO Revenue Ndd |
| cYWGORevenueDed | `Float` | C YWGO Revenue Ded |
| cYWGORevenueNdd | `Float` | C YWGO Revenue Ndd |
| channel | `String` | Channel |
| dSnapshotDate | `Date` | D Snapshot Date |
| dGORevenueDed | `Float` | DGO Revenue Ded |
| dGORevenueNdd | `Float` | DGO Revenue Ndd |
| dGORoomsDed | `Float` | DGO Rooms Ded |
| dGORoomsNdd | `Float` | DGO Rooms Ndd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| forecastAmt | `Float` | Forecast Amount |
| forecastRooms | `Float` | Forecast Rooms |
| lastYearArrAdults | `Float` | Ly Arrangement Adults |
| lastYearArrChildren | `Float` | Ly Arrangement Children |
| lastYearArrRooms | `Float` | Ly Arrangement Rooms |
| lastYearRevenue | `Float` | Last Year Revenue |
| lastYearRoomRevenueBlkDed | `Float` | Ly Room Revenue Block Ded |
| lastYearRoomRevenueBlkNdd | `Float` | Ly Room Revenue Block Ndd |
| lastYearRoomRevenueResBlockDed | `Float` | Ly Room Revenue Reservation Blk Ded |
| lastYearRoomRevenueResBlockNdd | `Float` | Ly Room Revenue Reservation Blk Ndd |
| lastYearRoomRevenueResIndividualDed | `Float` | Ly Room Revenue Reservation Ind Ded |
| lastYearRoomRevenueResIndividualNdd | `Float` | Ly Room Revenue Reservation Ind Ndd |
| lastYearStayRoomsBlkDed | `Float` | Ly Stay Rooms Block Ded |
| lastYearStayRoomsBlkNdd | `Float` | Ly Stay Rooms Block Ndd |
| lastYearStayRoomsResBlockDed | `Float` | Ly Stay Rooms Reservation Blk Ded |
| lastYearStayRoomsResBlockNdd | `Float` | Ly Stay Rooms Reservation Blk Ndd |
| lastYearStayRoomsResIndividualDed | `Float` | Ly Stay Rooms Reservation Ind Ded |
| lastYearStayRoomsResIndividualNdd | `Float` | Ly Stay Rooms Reservation Ind Ndd |
| lyActualRooms | `Float` | Last Year Actual Rooms |
| lyCompRoomNts | `Float` | Last Year Comp Room Nts |
| lyOoRooms | `Float` | Last Year Oo Rooms |
| lyRevenueDed | `Float` | Last Year Revenue Ded |
| lyRevenueNdd | `Float` | Last Year Revenue Ndd |
| lyRoomsDed | `Float` | Last Year Rooms Ded |
| lyRoomsNdd | `Float` | Last Year Rooms Ndd |
| lywarmd | `Float` | Lywarmd |
| lywarmn | `Float` | Lywarmn |
| lywarvd | `Float` | Lywarvd |
| lywarvn | `Float` | Lywarvn |
| marketCode | `String` | Market Code |
| ooRooms | `Float` | Oo Rooms |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| physicalRooms | `Float` | Physical Rooms |
| potentialRevenue | `Float` | Potential Revenue |
| property | `String` | Code to uniquely identify the Property |
| rateCode | `String` | Rate Code |
| revenue | `Float` | Revenue |
| revenueN | `Float` | Revenue Non Deduct |
| revenueBlock | `Float` | Revenue Block |
| revenueResvTransient | `Float` | Revenue Reservation Transient |
| room | `Float` | Room |
| roomN | `Float` | Room Non Deduct |
| roomBlock | `Float` | Room Block |
| roomCategory | `String` | Room Category |
| roomReservationTransient | `Float` | Room Reservation Transient |
| roomRevenueBlkNdd | `Float` | Room Revenue Block Ndd |
| roomRevenueResBlockDed | `Float` | Room Revenue Reservation Blk Ded |
| roomRevenueResBlockNdd | `Float` | Room Revenue Reservation Blk Ndd |
| roomRevenueResIndividualNdd | `Float` | Room Revenue Reservation Ind Ndd |
| roomsToSell | `Float` | Rooms To Sell |
| rowcount | `Float` | Rowcount |
| snapshotDate | `Date` | Date the Snapshot was created |
| stayDate | `Date` | Stay Date |
| stayExchangeRate | `Float` | Stay Exchange Rate |
| stayRoomsBlkNdd | `Float` | Stay Rooms Block Ndd |
| stayRoomsResBlockDed | `Float` | Stay Rooms Reservation Blk Ded |
| stayRoomsResBlockNdd | `Float` | Stay Rooms Reservation Blk Ndd |
| stayRoomsResIndividualNdd | `Float` | Stay Rooms Reservation Ind Ndd |
| wGORevenueDed | `Float` | WGO Revenue Ded |
| wGORevenueNdd | `Float` | WGO Revenue Ndd |
| wGORoomsDed | `Float` | WGO Rooms Ded |
| wGORoomsNdd | `Float` | WGO Rooms Ndd |
| yGORevenueDed | `Float` | YGO Revenue Ded |
| yGORevenueNdd | `Float` | YGO Revenue Ndd |
| yGORoomsDed | `Float` | YGO Rooms Ded |
| yGORoomsNdd | `Float` | YGO Rooms Ndd |
| yWGORevenueDed | `Float` | YWGO Revenue Ded |
| yWGORevenueNdd | `Float` | YWGO Revenue Ndd |
| yWGORoomsDed | `Float` | YWGO Rooms Ded |
| yWGORoomsNdd | `Float` | YWGO Rooms Ndd |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceStayDateDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dayDesc | `String` | Day Description. |
| dayEndDate | `Date` | Day End Date. |
| dayNumberOfMonth | `Float` | Day number of the month. |
| dayNumberOfQuarter | `Float` | Day number of the quarter. |
| dayNumberOfWeek | `String` | Day number of the week. |
| dayOfYear | `Float` | Day of the Year. |
| dayTimespan | `Float` | Day Timespan. |
| daysOfMonth | `Float` | Month Timespan. |
| daysOfQuarter | `Float` | Quarter Timespan. |
| daysOfYear | `Float` | Year Timespan. |
| internalMonthkey | `Float` | Monthkey |
| isoWeekOfYear | `String` | Iso Week of Year |
| julianDaykey | `String` | Julian Daykey |
| lastYearDaykey | `Date` | Last Year Daykey |
| monthComparison | `String` | Month Description. |
| monthEndDate | `Date` | Month End Date. |
| monthKey | `String` | Month Key |
| monthName | `String` | Month Name. |
| monthNumber | `Float` | Month of the year. |
| monthOfQuarter | `Float` | Month of the quarter. |
| monthYrKey | `String` | Month Year Key |
| priorJulianDaykey | `String` | Prior Julian Daykey |
| priorMonthKey | `String` | Prior Month Key |
| priorWeekKey | `String` | Prior Week Key |
| priorYearDaykey | `Date` | Prior Year Daykey |
| priorYearKey | `String` | Prior Year Key |
| priorYearMonthKey | `String` | Prior Year Month Key |
| priorYearQuarterKey | `String` | Prior Year Quarter Key |
| priorYearWeekKey | `String` | Prior Year Week Key |
| quarter | `String` | Quarter Description. |
| quarterEndDate | `Date` | Quarter End Date. |
| quarterKey | `String` | Quarter Key |
| quarterNumber | `String` | Quarter of the year. |
| stayDate | `Date` | Stay Date |
| weekDay | `String` | Week Day |
| weekDsc | `String` | Week Dsc |
| weekEndDate | `Date` | End date of the week. |
| weekEndDsc | `String` | Week End Dsc |
| weekEndKey | `String` | Week End Key |
| weekEndMonthDsc | `String` | Week End Month Dsc |
| weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| weekKey | `String` | Week Key |
| weekNumber | `String` | Week of the year. |
| weekOfMonth | `String` | Week of the month. |
| weekTimespan | `Float` | Week Timespan. |
| yearComparison | `Float` | Year Comparison |
| yearDsc | `String` | Year description. |
| yearEndDate | `Date` | Year End Date. |
| yearKey | `String` | Year Key |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceMarketDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroup | `String` | Central Market Group |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroup | `String` | Market group attached to the market code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupOrderBy | `Float` | Market Group Order By |
| marketOrderBy | `Float` | Market Order By |
| marketgroupid | `String` | Marketgroupid |
| marketid | `String` | Marketid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printGroup | `String` | Print Group for Nationality Report |
| property | `String` | Code to uniquely identify the Property |
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

### StatisticsReservationPacePaceRateCodeDetailsType

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
| backToBackYn | `String` | Back To Back Y/N |
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
| beginBookingDate | `Date` | Begin Booking Date |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastPrice | `Float` | Breakfast Price |
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
| centralRateCategory | `String` | Central Rate Category |
| centralRateCategoryDescription | `String` | Central Rate Category Description |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| closedToArrival | `String` | Days the rate restriction is not available for arrival |
| commissionCode | `String` | Commission Code |
| commissionPct | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| complimentaryYn | `String` | Complimentary Y/N |
| currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRatesYn | `String` | Daily Rates Y/N |
| dayuseYn | `String` | Day use reservation Y/N. |
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
| discountYn | `String` | Discount Flag. |
| displayRegional | `String` | Display Regional |
| displaySet | `String` | Display Set |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| endBookingDate | `Date` | End Booking Date |
| exchangePostingType | `String` | Exchange Posting Type |
| externalLockedYn | `String` | External Locked Y/N |
| extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| flatOrPercentage | `String` | Flat Or Percentage |
| folioText | `String` | Text displayed on the Folio |
| frequentFlyerYn | `String` | Frequent Flyer Y/N |
| gDSAllowedYn | `String` | Is this rate code available for GDS |
| groupCode | `String` | Group Code |
| highlightRateAmountYn | `String` | To highlight on the rate query |
| houseUseYn | `String` | House Use Y/N |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| losUnit | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| maxDvanceBooking | `Float` | Max Dvance Booking |
| maxLos | `Float` | Max Los |
| maxOccupancy | `Float` | Max Occupancy |
| mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| minAdvanceBooking | `Float` | Minimum Advance Booking |
| minOccupancy | `Float` | Minimum Occupancy |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| myfideliouploadflag | `String` | Myfideliouploadflag |
| negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| ownerRateYn | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| packageYn | `String` | Package Y/N |
| packages | `String` | Packages |
| pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| pkgTransactionCode | `String` | Package Transaction Code |
| pkgTransactionCodeWk | `String` | Package Transaction Code Wk |
| postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| postingRhythum | `String` | Posting Rhythum |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRateYn | `String` | Print Rate Y/N |
| privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| privilegedYn | `String` | Indicates if rate is privileged or not. |
| profitTransactionCode | `String` | Profit Transaction Code |
| property | `String` | Indicates if the value set for the specific property. |
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
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateCodeId | `String` | Rate Code ID |
| rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| rateLevel | `Float` | Rate Level this rate code belongs to. |
| rateinfoUrl | `String` | Rateinfo Url |
| ratesToGDSYn | `String` | Needs to send this rate to GDS or not. |
| redemptionRateYn | `String` | Redemption Rate Y/N |
| repMarketCode | `String` | Reporting Market Code |
| repMarketDescription | `String` | Reporting Market Description |
| repMarketGroupCode | `String` | Reporting Market Group Code |
| repMarketGroupDescription | `String` | Reporting Market Group Description |
| repRateBucket | `String` | Reporting Rate Bucket |
| repRateBucketDescription | `String` | Reporting Rate Bucket Description |
| repRoomTypeDescs | `String` | Reporting Room Type Descs |
| repRoomTypes | `String` | Reporting Room Types |
| repSourceCode | `String` | Reporting Source Code |
| repSourceDescription | `String` | Reporting Source Description |
| repSourceGroupCode | `String` | Reporting Source Group Code |
| repSourceGroupDescription | `String` | Reporting Source Group Description |
| repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| resort | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rodBaseAmount | `Float` | Rod Base Amount |
| rodBaseFltPct | `String` | Rod Base Flt Pct |
| rodBaseRounding | `String` | Rod Base Rounding |
| rodBasedYn | `String` | Is the group code rate of day based |
| rodYn | `String` | Rod Y/N |
| roomAssignmentValue | `Float` | Room Assignment Value |
| roomTypeDescs | `String` | Room Type Descs |
| roomTypes | `String` | Room Types |
| sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| sellSequence | `Float` | Sell Sequence |
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
| tieredYn | `String` | Indicates if the rate is a tiered rate. |
| transactionCode | `String` | Rate transaction code |
| transactionCodeWk | `String` | Transaction Code Wk |
| transactionTaxInclYN | `String` | Transaction code is inclusive of tax Y/N |
| transactionWkTaxInclYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| wkDeptCode | `String` | Wk Dept Code |
| yieldAs | `String` | Yield As |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePacePropertyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| aRBalanceTrxCode | `String` | Internal |
| aRCreditTrxCode | `String` | Internal |
| accessCode | `String` | Access Code |
| agingLevel1 | `Float` | Aging bucket 1 |
| agingLevel2 | `Float` | Aging bucket 2 |
| agingLevel3 | `Float` | Aging bucket 3 |
| agingLevel4 | `Float` | Aging bucket 4 |
| agingLevel5 | `Float` | Aging bucket 5 |
| airport | `String` | The Airport Code for the airport near the property |
| airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| allContacts | `String` | All Contacts |
| allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| allowancePeriodAdj | `String` | Period for the allowance |
| alternateYn | `String` | Property is alternate or actual search. |
| arAccountNumberFormat | `String` | Number format of AR account no. |
| arAgent | `String` | Default Account Type for an Agent for the Property |
| arCompany | `String` | Default Account Type for a Company for the Property |
| arGroups | `String` | Default Account Type for a Group for the Property |
| arIndividuals | `String` | Default Account Type for Individual for the Property |
| arSettleCode | `String` | Internal |
| arTypewriter | `String` | Internal |
| awardsTimeout | `Float` | Internal |
| baseLanguage | `String` | The base language of the Hotel |
| beginDate | `DateTime` | Begin Date |
| blackoutPeriodNotes | `String` | Blackout period notes defaulted onto the FIT Contract at time of creation. |
| block | `String` | Block |
| bookYn | `String` | Book Y/N |
| brArea | `String` | Ball Room Area |
| brSeats | `Float` | No of Ballroom Seats |
| brandCode | `String` | Brand Code |
| budgetMonth | `Float` | Financial Year of the Property |
| busblockType | `String` | Busblock Type |
| businessId | `String` | Business ID |
| businessRegCode | `String` | Business Reg Code |
| cCreditLimit | `Float` | Central Credit Limit |
| cDoubleRate2 | `Float` | Central Dbl Rate2 |
| cDoubleRate1 | `Float` | Central Dbl Rate1 |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cSglRate2 | `Float` | Central Sgl Rate2 |
| cSglRate1 | `Float` | Central Sgl Rate1 |
| cSuiRate2 | `Float` | Central Sui Rate2 |
| cSuiRate1 | `Float` | Central Sui Rate1 |
| cTplRate2 | `Float` | Central Tpl Rate2 |
| cTplRate1 | `Float` | Central Tpl Rate1 |
| cWarningAmount | `Float` | Central Warning Amount |
| cROCode | `String` | CRO Code |
| cRSResort | `String` | Not used |
| cashShiftDrop | `String` | Internal |
| cashYn | `String` | Cash Y/N |
| cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| cateringCurrencyFormat | `String` | Catering currency format. |
| centralCurrencyCode | `String` | Central Currency Code |
| centralCurrencyDescription | `String` | Central Currency Description |
| centralPropertyType | `String` | Central Property Type |
| chainCode | `String` | Chain Code |
| chainDescription | `String` | Chain Description |
| chainMode | `String` | Chain Mode |
| checkExgPaidout | `String` | Internal |
| checkInTime | `DateTime` | The Hotel official check intime |
| checkOutTime | `DateTime` | The Hotel official check out time |
| checkShiftDrop | `String` | Internal |
| checkTrxcode | `String` | Internal |
| city | `String` | City |
| cityDescription | `String` | City Description. |
| comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| comNameXrefId | `Float` | Internal |
| companyAddressType | `String` | Internal |
| companyPhoneType | `String` | Internal |
| configYn | `String` | Config Y/N |
| configurationMode | `String` | Internal |
| confirmRegcardPrinter | `String` | Internal |
| copies | `Float` | Copies |
| countryCode | `String` | Country Code |
| countryMode | `String` | Country Mode |
| countryName | `String` | Country Name |
| creditLimit | `Float` | Credit Limit |
| currencyCode | `String` | Currency Code |
| currencyDecimals | `Float` | Number of decimals to designate currency |
| currencyDescription | `String` | Currency Description |
| currencyExgPaidout | `String` | Not used |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| curtainColor | `String` | Color that of the background |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateForAging | `String` | Date the aging should begin |
| dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| dblNum | `String` | Not used |
| dblRate2 | `Float` | Not used |
| dblRate1 | `Float` | Not used |
| decimalPlaces | `Float` | Number of places for the default currency |
| decimalSeparator | `String` | Type of decimal separator |
| defaultCommissionPercentage | `String` | Not used |
| defaultFaxType | `String` | Not used |
| defaultFolioStyle | `Float` | Folio style to be used for all guests |
| defaultGroupsRateCode | `String` | Not used |
| defaultGuestAddress | `String` | Default guest address format. |
| defaultMembershipType | `String` | Future use |
| defaultPostingRoom | `String` | Future use |
| defaultPrepaidComm | `String` | Not used. |
| defaultPrinter | `String` | Not Used |
| defaultPropertyAddress | `String` | Default property address format. |
| defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| defaultRegistrationCard | `String` | Default registration card for the property. |
| defaultReservationType | `String` | The Default reservation type for this property |
| defaultTrxCommissionCode | `String` | Not used. |
| deletedFlag | `String` | Deleted Flag |
| depositLedgerTrxCode | `String` | Future use |
| destinationId | `String` | Destination ID |
| dfltPkgTranCode | `String` | Future use |
| dfltTranCodeRateCode | `String` | Future use |
| directions | `String` | Internal |
| dirsales | `String` | Future use |
| disableLoginYn | `String` | LOGIN into the application is disabled. |
| downloadRestYn | `String` | Download Rest Y/N |
| dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| email | `String` | Email |
| endDate | `DateTime` | End Date |
| exchangePostingType | `String` | Exchange Posting Type |
| expHotelCode | `String` | Hotel code used for third party exports |
| expiryDate | `Date` | Expiry Date |
| extExpFileLocation | `String` | Future use |
| extPropertyCode | `String` | Future use |
| externalScYn | `String` | Indicates that the property uses an external SC system. |
| fax | `String` | Fax |
| faxNoFormat | `String` | Fax number formats. |
| fileTransferFormat | `String` | Not used. |
| fiscalEndDate | `Date` | Future use |
| fiscalPeriodType | `String` | Future use |
| fiscalStartDate | `Date` | Future use |
| fiscalStartMonth | `Float` | Fiscal Start Month |
| fiscalStartYear | `Float` | Fiscal Start Year |
| flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| floorNumExecutiveFloor | `String` | Floor number of executive floor. |
| flowCode | `String` | Future use |
| fnsTier | `String` | Property Free Nights Stay Tier. |
| folioLanguage1 | `String` | Other languages |
| folioLanguage2 | `String` | Other languages |
| folioLanguage3 | `String` | Other languages |
| folioLanguage4 | `String` | Other languages |
| font | `Float` | Not used |
| genmgr | `String` | Future use |
| groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| guestLookupTimeout | `Float` | Future use |
| hotelCode | `String` | Property Code. |
| hotelFc | `String` | Future use |
| hotelId | `String` | Hotel ID |
| hotelType | `String` | Hotel Type |
| imgDirectionId | `Float` | Future use |
| imgHotelId | `Float` | Future use |
| imgMapId | `Float` | Future use |
| inactiveDaysForGuestProfil | `Float` | Future use |
| inactiveFlag | `String` | Inactive Flag |
| individualAddressType | `String` | Future use |
| individualPhoneType | `String` | Future use |
| individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| intTaxIncludedYn | `String` | Int Tax Included Y/N |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| latitude | `Float` | Latitude of the property in decimal |
| leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| legalOwner | `String` | The owner who owns this property |
| licenseCode | `String` | License Code |
| localCurrencyFormat | `String` | Format for the local currency. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longDateFormat | `String` | Long date format for the property. |
| longStayControl | `Float` | The default length of stay |
| longitude | `Float` | Longitude of the property in decimal |
| maxAdultsFamilyRoom | `Float` | Maximum adults in family rooms. |
| maxChildrenFamilyRoom | `Float` | Maximum children in family rooms. |
| maxNoNights | `Float` | Not used |
| maxOccupancy | `Float` | Max Occupancy |
| maxcreditdays | `Float` | Maxcreditdays |
| mbsSupportedYn | `String` | Indicates if the property supports MBS. Used in some file exports. |
| meetRooms | `Float` | Future use |
| meetSeats | `Float` | Future use |
| meetSpace | `Float` | Future use |
| meetingFc | `String` | Future use |
| minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| nameIdLink | `Float` | Internal |
| nightAuditCashierId | `String` | Future use |
| notes | `String` | Notes |
| numberBeds | `Float` | Total number of beds in this property |
| numberFloors | `Float` | Total number of floors in this property |
| numberRooms | `Float` | Number Rooms |
| opsMhotYn | `String` | Ops Mhot Y/N |
| opsMht2Yn | `String` | Ops Mht2 Y/N |
| opusCurrencyCode | `String` | Future use |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownership | `String` | Future use |
| packageLoss | `String` | Package Loss code for a particular package |
| packageProfit | `String` | Package Profit code for a particular Package |
| passerbyMarket | `String` | Market code for passerby |
| passerbySource | `String` | Source code for passerby |
| path | `String` | Path |
| pathId | `Float` | This is the value used in Interfaces to map  to a Resort Code. |
| paymentDate | `DateTime` | Payment Date |
| perReservationRoomLimit | `Float` | Future use |
| pmsActiveYn | `String` | Indicate if PMS was active on that date or not. |
| postCode | `String` | Post Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| proinfoUrl | `String` | Proinfo Url |
| propMapUrl | `String` | Property MAP URL. |
| propPicUrl | `String` | Property picture URL. |
| property | `String` | Property |
| propertyName | `String` | Property Name |
| propertyType | `String` | Property Type |
| qtyConnectingRooms | `Float` | Number of connecting rooms. |
| qtyDoubleRooms | `Float` | Number of double rooms. |
| qtyFamilyRooms | `Float` | Number of family rooms. |
| qtyGuestElevators | `Float` | Number of guest elevators. |
| qtyGuestRoomFloors | `Float` | Total of guest rooms floors. |
| qtyHandicappedRooms | `Float` | Number of handicapped rooms. |
| qtyNonSmokingRooms | `Float` | Number of non smoking rooms. |
| qtySingleRooms | `Float` | Number of single rooms. |
| qtySuites | `Float` | Number of suites. |
| qtyTwinRooms | `Float` | Number of twin rooms. |
| quotedCurrency | `String` | Future use |
| rateTierYn | `String` | Rate Tier Y/N |
| reconcileDate | `DateTime` | Records the date on which the reconciliation is done |
| regionCode | `String` | Region Code |
| regionDescription | `String` | Region Description |
| repPasserbyMarket | `String` | Reporting Passerby Market |
| repPasserbySource | `String` | Reporting Passerby Source |
| repState | `String` | Reporting State |
| repStateDescription | `String` | Reporting State Desc |
| reportYn | `String` | Report Y/N |
| reservationYN | `String` | Indicates if this menu item depends on the reservation. |
| restaurant | `Float` | Future use |
| rhythmSheets | `Float` | Total number of Sheets |
| rhythmTowels | `Float` | Total number of Towels |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomAmenity | `String` | Room amenity. |
| saveProfiles | `Float` | To store number of days before deleting the gest profile |
| scActiveYn | `String` | Sc Active Y/N |
| scriptId | `Float` | Script ID |
| season1 | `String` | Future use |
| season2 | `String` | Future use |
| season3 | `String` | Future use |
| season4 | `String` | Future use |
| season5 | `String` | Future use |
| sendLeadAsBooking | `String` | Send Lead As Booking |
| sfaActiveYn | `String` | Sfa Active Y/N |
| sglNum | `String` | Future use |
| sglRate1 | `Float` | Future use |
| sglRate2 | `Float` | Future use |
| shopDescription | `String` | Shop description. |
| shortDateFormat | `String` | Short date format for the property. |
| sourceCommission | `String` | For default commission percentage |
| state | `String` | State |
| stateDesc | `String` | State Description of the Guest of Payee |
| street | `String` | The street of the property. |
| suiNum | `String` | Future use |
| suiRate1 | `Float` | Future use |
| suiRate2 | `Float` | Future use |
| summCurrencyCode | `String` | Internal |
| taCommission | `String` | For default commission percentage |
| telephone | `String` | The direct dial phone number of this property |
| telephoneNoFormat | `String` | Formats for telephone number |
| thousandSeparator | `String` | Separator for monetory values |
| timeFormat | `String` | Default time format for the property. |
| timezoneRegion | `String` | Time zone region selected by the employee. |
| tollfree | `String` | Toll free telephone number. |
| totalRooms | `Float` | Future use |
| touristNumber | `String` | Tourist Number |
| tplNum | `String` | Future use |
| tplRate1 | `Float` | Future use |
| tplRate2 | `Float` | Future use |
| translateMulticharYn | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| turnawayCode | `String` | Turnaway Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vatId | `String` | VAT ID of this property. |
| videoCoStart | `DateTime` | Video check out start time. |
| videoCoStop | `DateTime` | Video check out end time. |
| videocheckoutPrinter | `String` | Future use |
| vosActiveYn | `String` | Vos Active Y/N |
| wakeUpDelay | `Float` | Future use |
| warningAmount | `Float` | Amount at which warning is raised. |
| webaddress | `String` | Webaddress of the property |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| xresortNumber | `Float` | Numbers (1 thru 10) given to the resorts in the schema to print the tax collected by that resort in the gstfolio when proper merge codes are selected. |
| zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceRoomTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessibleYn | `String` | Indicates if this room type is accessibility compliant. |
| activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| activeflag | `Date` | Activeflag |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoIncludeYn | `String` | Include room type in the rate header for Myfidelio rates. |
| autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cIncrements | `Float` | Central Increments |
| cInitialRoundUp | `Float` | Central Initial Round Up |
| cORMSDrtier1 | `Float` | Central Orms Drtier1 |
| cORMSDrtier2 | `Float` | Central Orms Drtier2 |
| cORMSDrtier3 | `Float` | Central Orms Drtier3 |
| cORMSDrxtra2ndAdult | `Float` | Central Orms Drxtra 2nd Adult |
| cORMSDrxtraAdult | `Float` | Central Orms Drxtra Adult |
| cORMSDrxtraChild | `Float` | Central Orms Drxtra Child |
| cORMSUpsellAmount | `Float` | Central Orms Upsell Amt |
| cRateAmount | `Float` | Central Rate Amount |
| cRateFloor | `Float` | Central Rate Floor |
| cRSDescription | `String` | CRS Description |
| canDeleteYn | `String` | Can Delete Y/N |
| centralRoomClass | `String` | Central Room Class |
| centralRoomClassDescription | `String` | Central Room Class Description |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defOccupancy | `Float` | Default occupancy for the room type |
| defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| defaultRateDesc | `String` | Default Rate Description |
| defaultratecodeid | `String` | Defaultratecodeid |
| deletedFlag | `String` | Deleted Flag |
| evisitorFacilityId | `String` | Facility ID for eVisitor. |
| genericroomflag | `String` | Genericroomflag |
| housekeeping | `String` | Room type shows in housekeeping Y/N |
| imageId | `Float` | Image ID |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| increments | `Float` | Increment value for rates by day by LOS. |
| initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longDescription | `String` | Long Description |
| maintenanceYn | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| maxOccupancy | `Float` | Max Occupancy |
| maxOccupancyAdults | `Float` | The maximum occupancy of adults for this room category. |
| maxOccupancyChildren | `Float` | The maximum occupancy of children for this room category. |
| maxRollaways | `Float` | Not used |
| meetingroomflag | `String` | Meetingroomflag |
| memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| minOccupancy | `Float` | Minimum Occupancy |
| numberRooms | `Float` | Number Rooms |
| oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| ownerroomflag | `String` | Ownerroomflag |
| physicalRoomYn | `String` | Physical Room Y/N |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| psuedoRoomType | `String` | Psuedo Room Type |
| rateAmount | `Float` | Rate Amount |
| rateCategory | `String` | Rate Category |
| rateCategoryDesc | `String` | Rate Category Description |
| rateCode | `String` | Rate Code |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| ratecategoryid | `String` | Ratecategoryid |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repRateCategory | `String` | Reporting Rate Category |
| repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomcategorypmsref | `String` | Roomcategorypmsref |
| roomclassid | `String` | Roomclassid |
| roominfoUrl | `String` | URL where room information is stored. |
| rotationGroup | `String` | Rotation Group |
| sBedtype | `String` | S Bedtype |
| sLabel | `String` | S Label |
| salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| sendToInterfaceYn | `String` | Room type sent to interface Y/N |
| smokingPrefDesc | `String` | Smoking Pref Description |
| smokingPreference | `String` | Smoking Preference |
| suiteroomflag | `String` | Suiteroomflag |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| yieldCategory | `String` | Yield Category |
| yieldableroomflag | `String` | Yieldableroomflag |

[⬆ Back to Query](#query)

---

### StatisticsReservationPacePaceChannelDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
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
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationPaceReservationPaceSnapshotDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dayDesc | `String` | Day Description. |
| dayEndDate | `Date` | Day End Date. |
| dayNumberOfMonth | `Float` | Day number of the month. |
| dayNumberOfQuarter | `Float` | Day number of the quarter. |
| dayNumberOfWeek | `String` | Day number of the week. |
| dayOfYear | `Float` | Day of the Year. |
| dayTimespan | `Float` | Day Timespan. |
| internalMonthkey | `Float` | Monthkey |
| internalYearkey | `Float` | Yearkey |
| isoWeekOfYear | `String` | Iso Week of Year |
| julianDaykey | `String` | Julian Daykey |
| lastYearDaykey | `Date` | Last Year Daykey |
| monthDsc | `String` | Month Description. |
| monthEndDate | `Date` | Month End Date. |
| monthKey | `String` | Month Key |
| monthName | `String` | Month Name. |
| monthNumber | `Float` | Month of the year. |
| monthOfQuarter | `Float` | Month of the quarter. |
| monthTimespan | `Float` | Month Timespan. |
| monthYrKey | `String` | Month Year Key |
| priorJulianDaykey | `String` | Prior Julian Daykey |
| priorMonthKey | `String` | Prior Month Key |
| priorWeekKey | `String` | Prior Week Key |
| priorYearDaykey | `Date` | Prior Year Daykey |
| priorYearKey | `String` | Prior Year Key |
| priorYearMonthKey | `String` | Prior Year Month Key |
| priorYearQuarterKey | `String` | Prior Year Quarter Key |
| priorYearWeekKey | `String` | Prior Year Week Key |
| quarterDsc | `String` | Quarter Description. |
| quarterEndDate | `Date` | Quarter End Date. |
| quarterKey | `String` | Quarter Key |
| quarterNumber | `String` | Quarter of the year. |
| quarterTimespan | `Float` | Quarter Timespan. |
| snapshotDateComparison | `Date` | Snapshot Date Comparison |
| weekDay | `String` | Week Day |
| weekDsc | `String` | Week Dsc |
| weekEndDate | `Date` | End date of the week. |
| weekEndDsc | `String` | Week End Dsc |
| weekEndKey | `String` | Week End Key |
| weekEndMonthDsc | `String` | Week End Month Dsc |
| weekEndMonthEndDate | `Date` | Week End Date of the Month. |
| weekKey | `String` | Week Key |
| weekNumber | `String` | Week of the year. |
| weekOfMonth | `String` | Week of the month. |
| weekTimespan | `Float` | Week Timespan. |
| yearDsc | `String` | Year description. |
| yearEndDate | `Date` | Year End Date. |
| yearKey | `String` | Year Key |
| yearTimespan | `Float` | Year Timespan. |

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