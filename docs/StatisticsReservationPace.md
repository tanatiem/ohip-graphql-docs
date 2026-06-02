# StatisticsReservationPace
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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