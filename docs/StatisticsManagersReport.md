# StatisticsManagersReport
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `statisticsManagersReport`
> Past statistics including rooms and revenue figures arrivals departures and occupancy broken out by multiple time periods.
  
**Return:** [`[StatisticsManagersReportType]`](#statisticsmanagersreporttype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsManagersReportQueryArgumentsType!`](#statisticsmanagersreportqueryargumentstype) |  |

## Object Types

### StatisticsManagersReportType

| Field | Type | Description |
| --- | --- | --- |
| managersReportDetails | [`StatisticsManagersReportManagersReportDetailsType`](#statisticsmanagersreportmanagersreportdetailstype) | Managers Report Details |
| gregerianCalendarDetails | [`StatisticsManagersReportGregerianCalendarDetailsType`](#statisticsmanagersreportgregeriancalendardetailstype) | Gregerian Calendar |
| fiscalCalendarDetails | [`StatisticsManagersReportFiscalCalendarDetailsType`](#statisticsmanagersreportfiscalcalendardetailstype) | Fiscal Calendar |
| rateSeasonDayDetails | [`StatisticsManagersReportRateSeasonDayDetailsType`](#statisticsmanagersreportrateseasondaydetailstype) | Rate Season Daily Details |
| foreignCurrencyDetails | [`StatisticsManagersReportForeignCurrencyDetailsType`](#statisticsmanagersreportforeigncurrencydetailstype) | Foreign Currency Details |
| roomClassDetails | [`StatisticsManagersReportRoomClassDetailsType`](#statisticsmanagersreportroomclassdetailstype) | Room Class Details |
| propertyPropertyDetails | [`StatisticsManagersReportPropertyPropertyDetailsType`](#statisticsmanagersreportpropertypropertydetailstype) | Resort Details |
| statisticsManagersReportRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportManagersReportDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adultsFree | `Float` | Not Used |
| adultsInHouse | `Float` | Number of Adults in House. |
| advFoodRevenue | `Float` | Advance Food Revenue |
| advNonRevenue | `Float` | Advance Non Revenue |
| advOtherRevenue | `Float` | Advance Other Revenue |
| advRoomRevenue | `Float` | Advance Room Revenue |
| advTotalFoodTax | `Float` | Advance Total Food Tax |
| advTotalNonRevenueTax | `Float` | Advance Total Non Revenue Tax |
| advTotalOtherTax | `Float` | Advance Total Other Tax |
| advTotalRevenue | `Float` | Advance Total Revenue |
| advTotalRoomTax | `Float` | Advance Total Room Tax |
| advTotalTax | `Float` | Advance Total Tax |
| agentRoomRevenue | `Float` | Total amount of postings today where the transaction code is marked as room revenue for reservations that have a travel agent profile attached to the reservation. |
| agentRoomTax | `Float` | Total tax amount of postings today where the transaction code is marked as room revenue for reservations that have a travel agent profile attached to the reservation. |
| agentRooms | `Float` | Number of rooms in house that have a Travel Agent attached to the reservation. |
| agentTotalRevenue | `Float` | Total amount of postings today where the transaction code is marked as revenue for reservations that have a travel agent profile attached to the reservation. |
| agentTotalTax | `Float` | Total tax amount of postings today where the transaction code is marked as revenue for reservations that have a travel agent profile attached to the reservation. |
| arrivalPersons | `Float` | Number of adults and children arriving today |
| arrivalReservations | `Float` | Number of reservations with an arrival date of today. |
| arrivalRooms | `Float` | Number of Rooms with an arrival date today |
| availableRooms | `Float` | Total rooms in hotel minus rooms occupied |
| averageAgeToday | `Float` | Not Used |
| averageDailyRateMinusComplimentaryHouseUse | `Float` | Average Daily Rate without Comp & House |
| averageDailyRevenue | `Float` | Not used |
| bedsAvailable | `Float` | Not Used |
| birthdays | `Float` | Number of rooms with birthday field equal to today |
| blockMemLosNights | `Float` | Number of Nights for all reservations that are considered for Rooms Occupied a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. Used for Calculation of Average Length of Stay. |
| blockMemRoomRevenue | `Float` | Total amount of all postings today where the transaction code is marked as Revenue and the transaction type is Lodging a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| blockMemRoomRevenueTax | `Float` | Total tax amount of all postings today where the transaction code is marked as Revenue and the transaction type is Lodging a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| blockMemRooms | `Float` | Number of rooms with a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| blockMemTotalRevenue | `Float` | Total amount of all postings today where the transaction code is marked as Revenue a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| blockMemTotalRevenueTax | `Float` | Total tax amount of all postings today where the transaction code is marked as Revenue a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| blockMembershipLosResv | `Float` | Counts all reservations that are considered for Rooms Occupied a membership number of the default membership type attached to the reserveration with a block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. Used for Calculation of Average Length of Stay. |
| businessDate | `Date` | Business Date |
| cAdvanceFoodRevenue | `Float` | Central Adv Food Revenue |
| cAdvanceNonRevenue | `Float` | Central Adv Non Revenue |
| cAdvanceOtherRevenue | `Float` | Central Adv Other Revenue |
| cAdvanceRoomRevenue | `Float` | Central Adv Room Revenue |
| cAdvanceTotalFoodTax | `Float` | Central Adv Total Food Tax |
| cAdvanceTotalNonRevenueTax | `Float` | Central Adv Total Non Revenue Tax |
| cAdvanceTotalOtherTax | `Float` | Central Adv Total Other Tax |
| cAdvanceTotalRevenue | `Float` | Central Adv Total Revenue |
| cAdvanceTotalRoomTax | `Float` | Central Adv Total Room Tax |
| cAdvanceTotalTax | `Float` | Central Adv Total Tax |
| cAgentRoomRevenue | `Float` | Central Agent Room Revenue |
| cAgentRoomTax | `Float` | Central Agent Room Tax |
| cAgentTotalRevenue | `Float` | Central Agent Total Revenue |
| cAgentTotalTax | `Float` | Central Agent Total Tax |
| cBlockMembershipRoomRevenue | `Float` | Central Blk Mem Room Revenue |
| cBlockMembershipRoomRevenueTax | `Float` | Central Blk Mem Room Revenue Tax |
| cBlockMembershipTotalRevenue | `Float` | Central Blk Mem Total Revenue |
| cBlockMembershipTotalRevenueTax | `Float` | Central Blk Mem Total Revenue Tax |
| cCompanyRoomRevenue | `Float` | Central Company Room Revenue |
| cCompanyRoomTax | `Float` | Central Company Room Tax |
| cCompanyTotalRevenue | `Float` | Central Company Total Revenue |
| cCompanyTotalTax | `Float` | Central Company Total Tax |
| cExchangeDate | `Date` | Central Xchange Date |
| cExtendedStayAdvanceFoodRevenue | `Float` | Central Es Adv Food Revenue |
| cExtendedStayAdvanceFoodTax | `Float` | Central Es Adv Food Tax |
| cExtendedStayAdvanceNonRevenue | `Float` | Central Es Adv Non Revenue |
| cExtendedStayAdvanceNonRevenueTax | `Float` | Central Es Adv Non Revenue Tax |
| cExtendedStayAdvanceOtherRevenue | `Float` | Central Es Adv Other Revenue |
| cExtendedStayAdvanceOtherTax | `Float` | Central Es Adv Other Tax |
| cExtendedStayAdvanceRoomRevenue | `Float` | Central Es Adv Room Revenue |
| cExtendedStayAdvanceRoomTax | `Float` | Central Es Adv Room Tax |
| cExtendedStayAdvanceTotalRevenue | `Float` | Central Es Adv Total Revenue |
| cExtendedStayAdvanceTotalTax | `Float` | Central Es Adv Total Tax |
| cExtendedStayFoodRevenue | `Float` | Central Es Food Revenue |
| cExtendedStayFoodTax | `Float` | Central Es Food Tax |
| cExtendedStayNonRevenue | `Float` | Central Es Non Revenue |
| cExtendedStayNonRevenueTax | `Float` | Central Es Non Revenue Tax |
| cExtendedStayOtherRevenue | `Float` | Central Es Other Revenue |
| cExtendedStayOtherTax | `Float` | Central Es Other Tax |
| cExtendedStayRoomRevenue | `Float` | Central Es Room Revenue |
| cExtendedStayRoomTax | `Float` | Central Es Room Tax |
| cExtendedStayTotalRevenue | `Float` | Central Es Total Revenue |
| cExtendedStayTotalTax | `Float` | Central Es Total Tax |
| cFfFoodBevRevenue | `Float` | Central Ff Food Bev Revenue |
| cFfOtherRevenue | `Float` | Central Ff Other Revenue |
| cFfRentFoodBevRevenue | `Float` | Central Ff Rent Food Bev Rev |
| cFfRentOtherRevenue | `Float` | Central Ff Rent Other Rev |
| cFfRentRoomRevenue | `Float` | Central Ff Rent Room Rev |
| cFfRoomRevenue | `Float` | Central Ff Room Revenue |
| cFitMembershipRoomRevenue | `Float` | Central Fit Mem Room Revenue |
| cFitMembershipRoomRevenueTax | `Float` | Central Fit Mem Room Revenue Tax |
| cFitMembershipTotalRevenue | `Float` | Central Fit Mem Total Revenue |
| cFitMembershipTotalRevenueTax | `Float` | Central Fit Mem Total Revenue Tax |
| cFlaggedFoodRevenue | `Float` | Central Flgd Food Revenue |
| cFlaggedNonRevenue | `Float` | Central Flgd Non Revenue |
| cFlaggedOtherRevenue | `Float` | Central Flgd Other Revenue |
| cFlaggedPayment | `Float` | Central Flgd Payment |
| cFlaggedRoomRevenue | `Float` | Central Flgd Room Revenue |
| cFlaggedTotalFoodTax | `Float` | Central Flgd Total Food Tax |
| cFlaggedTotalNonRevenueTax | `Float` | Central Flgd Total Non Revenue Tax |
| cFlaggedTotalOtherTax | `Float` | Central Flgd Total Other Tax |
| cFlaggedTotalRevenue | `Float` | Central Flgd Total Revenue |
| cFlaggedTotalRoomTax | `Float` | Central Flgd Total Room Tax |
| cFlaggedTotalTax | `Float` | Central Flgd Total Tax |
| cOwnerFoodBevRevenue | `Float` | Central Owner Food Bev Revenue |
| cOwnerOtherRevenue | `Float` | Central Owner Other Revenue |
| cOwnerRentFoodBevRevenue | `Float` | Central Owner Rent Food Bev Rev |
| cOwnerRentOtherRevenue | `Float` | Central Owner Rent Other Rev |
| cOwnerRentRoomRevenue | `Float` | Central Owner Rent Room Rev |
| cOwnerRoomRevenue | `Float` | Central Owner Room Revenue |
| cPayment | `Float` | Central Payment |
| cRepeatRoomRevenue | `Float` | Central Repeat Room Revenue |
| cRepeatRoomTax | `Float` | Central Repeat Room Tax |
| cRepeatTotalRevenue | `Float` | Central Repeat Total Revenue |
| cRepeatTotalTax | `Float` | Central Repeat Total Tax |
| cancelReservation | `Float` | Number of cancelled reservations with an arrival date today. |
| cancelRooms | `Float` | Number of cancelled rooms with an arrival date today. |
| cancellationsMadeToday | `Float` | Number of Cancellations that were taken today for any date |
| centralAverageDailyRateMinusComplimentaryHouseUse | `Float` | Central Average Daily Rate (minus Complimentary and House Use) |
| centralAverageDailyRevenue | `Float` | Central Average Daily Revenue |
| centralCurrencyCode | `String` | Central Currency Code |
| centralExchangeRate | `Float` | Central Exchange Rate |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralFBTax | `Float` | Central FB Tax |
| centralGroupRevenue | `Float` | Central Group Revenue |
| centralGroupRoomRevenue | `Float` | Central Group Room Revenue |
| centralGroupRoomTax | `Float` | Central Group Room Tax |
| centralGroupTax | `Float` | Central Group Tax |
| centralIndividualRevenue | `Float` | Central Individual Revenue |
| centralIndividualRoomRevenue | `Float` | Central Individual Room Revenue |
| centralMembershipRevenue | `Float` | Central Membership Revenue |
| centralMembershipTotalTax | `Float` | Central Membership Total Tax |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralOtherTax | `Float` | Central Other Tax |
| centralRackRateTotalForAllRooms | `Float` | Central Rack Rate Total for All Rooms |
| centralRackRateTotalForOccupiedRooms | `Float` | Central Rack Rate Total for Occupied Rooms |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomTax | `Float` | Central Room Tax |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalTax | `Float` | Central Total Tax |
| centralYieldForAllRooms | `Float` | Central Yield for All Rooms |
| centralYieldForOccupiedRooms | `Float` | Central Yield for Occupied Rooms |
| centralcurrencyid | `String` | Centralcurrencyid |
| childrenFree | `Float` | Not Used |
| childrenInHouse | `Float` | Children in House. |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| cleanRooms | `Float` | Number of clean rooms |
| compAdults | `Float` | Total adults of reservations with a rate code marked as complimentary |
| compBeds | `Float` | Total beds in rooms that have a rate code marked as comp |
| compChildren | `Float` | Total children of reservations with a rate code marked as complimentary |
| compNext31Days | `Float` | Total number of rooms reserved having a rate code marked as comp starting tomorrow for 31 days. |
| compNext365Days | `Float` | Total number of rooms reserved having a rate code marked as comp starting tomorrow for 365 days. |
| compRestOfMonth | `Float` | Total number of rooms reserved having a rate code marked as comp starting tomorrow for the remainder of the current calendar month. |
| compRestOfYear | `Float` | Total number of rooms reserved having a rate code marked as comp starting tomorrow for the remainder of the current calendar year. |
| compTomorrow | `Float` | Total number of rooms reserved having a rate code marked as comp for tomorrow. |
| compWeek | `Float` | Total number of rooms reserved having a rate code marked as comp starting tomorrow for 7 days. |
| companyRoomRevenue | `Float` | Total amount of postings today where the transaction code is marked as room revenue for reservations that have a company profile attached to the reservation. |
| companyRoomTax | `Float` | Total tax amount of postings today where the transaction code is marked as room revenue for reservations that have a company profile attached to the reservation. |
| companyRooms | `Float` | Number of rooms that have a company profile attached to the reservation |
| companyTotalRevenue | `Float` | Total amount of postings today where the transaction code is marked as revenue for reservations that have a company profile attached to the reservation. |
| companyTotalTax | `Float` | Total tax amount of postings today where the transaction code is marked as revenue for reservations that have a company profile attached to the reservation. |
| complimentaryRooms | `Float` | Number of rooms that have a rate code marked as comp |
| contextCd | `String` | Context Cd |
| cribs | `Float` | Not Used |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUseReservations | `Float` | Day Use Reservations |
| dayUseRooms | `Float` | Number of reservations where the arrival date and departure date equal today |
| dayuseAdults | `Float` | Total number of adults of day-use reservations. |
| dayuseChildren | `Float` | Total number of children of day-use reservations. |
| dayuseMonth | `Float` | Total number of day-use rooms reserved starting tomorrow for 1 calendar month |
| dayuseNext31Days | `Float` | Total number of day-use rooms reserved starting tomorrow for 31 days. |
| dayuseNext365Days | `Float` | Total number of day-use rooms reserved starting tomorrow for 365 days. |
| dayuseRestOfMonth | `Float` | Total number of day-use rooms reserved starting tomorrow for the remainder of the current calendar month. |
| dayuseRestOfYear | `Float` | Total number of day-use rooms reserved starting tomorrow for the remainder of the current calendar year. |
| dayuseTomorrow | `Float` | Total number of day-use rooms reserved for tomorrow. |
| dayuseWeek | `Float` | Total number of day-use rooms reserved starting tomorrow for 7 days. |
| dayuseYear | `Float` | Total number of day-use rooms reserved starting tomorrow for 1 calendar year. |
| definiteArrivalRooms | `Float` | Number of rooms with an arrival date euqal to today with a reservation type of deduct |
| deletedFlag | `String` | Deleted Flag |
| departurePersons | `Float` | Number of persons with a departure date equal to today |
| departureRooms | `Float` | Number of rooms with a departure date equal to today |
| dirtyRooms | `Float` | Number of rooms with a houskeeping status of DI |
| doublesAsSingles | `Float` | Number of rooms where each room has occupancy max greater than 1 and numbe of persons in-house is 1 |
| earlyDeparturePersons | `Float` | Number of persons for checked out rooms with an original departure date greater than today |
| earlyDepartureRooms | `Float` | Number of  checked out rooms with an original departure date greater than today |
| exchangeRate | `Float` | Exchange Rate |
| extNoshowCRSRes | `Float` | Number of CRS Reservations Arrival extended to next day due to No Show counting share reservations as one. |
| extNoshowPrs | `Float` | Number of Persons Arrival extended to next day due to No Show. |
| extNoshowRes | `Float` | Number of Reservations Arrival extended to next day due to No Show. |
| extNoshowRoom | `Float` | Number of Rooms Arrival extended to next day due to No Show. |
| extendedStayAdvFoodRevenue | `Float` | Extended stay distributed food and beverage revenue. |
| extendedStayAdvFoodTax | `Float` | Extended stay distributed food and beverage taxes. |
| extendedStayAdvNonRevenue | `Float` | Extended stay distributed non-revenue. |
| extendedStayAdvNonRevenueTax | `Float` | Extended stay distributed non-revenue taxes. |
| extendedStayAdvOtherRevenue | `Float` | Extended stay distributed other revenue. |
| extendedStayAdvOtherTax | `Float` | Extended stay distributed other taxes. |
| extendedStayAdvRoomRevenue | `Float` | Extended stay distributed room revenue. |
| extendedStayAdvRoomTax | `Float` | Extended stay distributed room taxes. |
| extendedStayAdvTotalRevenue | `Float` | Extended stay distributed total revenue. |
| extendedStayAdvTotalTax | `Float` | Extended stay distributed total taxes. |
| extendedStayCompRooms | `Float` | Extended stay complimentary rooms. |
| extendedStayFoodRevenue | `Float` | Extended stay food and beverage revenue. |
| extendedStayFoodTax | `Float` | Extended stay food and beverage taxes. |
| extendedStayHouseUseRooms | `Float` | Extended stay house-use rooms. |
| extendedStayNonRevenue | `Float` | Extended stay non-revenue. |
| extendedStayNonRevenueTax | `Float` | Extended stay non-revenue taxes. |
| extendedStayOccupancyRooms | `Float` | Extended stay occupied rooms. |
| extendedStayOtherRevenue | `Float` | Extended stay other revenue. |
| extendedStayOtherTax | `Float` | Extended stay other taxes. |
| extendedStayPersons | `Float` | Number of persons where an original departure date equal to today |
| extendedStayRoom | `Float` | Number of rooms  where an original departure date equal to today |
| extendedStayRoomRevenue | `Float` | Extended stay room revenue. |
| extendedStayRoomTax | `Float` | Extended stay room taxes. |
| extendedStayTotalRevenue | `Float` | Extended stay total revenue. |
| extendedStayTotalTax | `Float` | Extended stay total taxes. |
| fBRevenue | `Float` | Total amount of all postings today where the Transaction Code is marked as Revenue and the Transaction Type is  Food and Beverage . |
| fBTax | `Float` | Total tax amount of all postings today where the Transaction Code is marked as Revenue and the Transaction Type is  Food and Beverage . |
| ffFoodBevRevenue | `Float` | Food and Beverage Revenue generated by Authorized Users who are in rooms that are not part of the Rental Program where the Transaction Code is marked as 'Revenue' and the Transaction Type is 'Food and Beverage'. |
| ffOtherRevenue | `Float` | Revenue generated by Authorized Users who are in rooms that are not part of the Rental Program where the transaction Codes are defined as 'other'. |
| ffRentFoodBevRev | `Float` | Food and Beverage Revenue generated by Authorized Users who are in rooms that are part of the Rental Program where the Transaction Code is marked as 'Revenue' and the Transaction Type is 'Food and Beverage'. |
| ffRentOtherRev | `Float` | Revenue generated by Authorized Users who are in rooms that are part of the Rental Program where the transaction Codes are defined as 'other'. |
| ffRentRoomRev | `Float` | Lodging Revenue generated by Authorized Users who are in rooms that are part of the Rental Program. (Revenue defined as lodging) |
| ffRentRooms | `Float` | Authorized Users who are in rooms that are part of the Rental Program. |
| ffRoomRevenue | `Float` | Lodging Revenue generated by Authorized Users who are in rooms that are not part of the Rental Program. (Revenue defined as lodging) |
| ffRooms | `Float` | Authorized Users who are in rooms that are not part of the Rental Program. |
| fitMemLosNights | `Float` | Number of nights for all reservations that are considered for Rooms Occupied a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. Used for Calculation of Average Length of Stay. |
| fitMemRoomRevenue | `Float` | Total amount of all postings today where the transaction code is marked as Revenue and the transaction type is Lodging a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| fitMemRoomRevenueTax | `Float` | Total tax amount of all postings today where the transaction code is marked as Revenue and the transaction type is Lodging a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| fitMemRooms | `Float` | Number of rooms with a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| fitMemTotalRevenue | `Float` | Total amount of all postings today where the transaction code is marked as Revenue a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| fitMemTotalRevenueTax | `Float` | Total tax amount of all postings today where the transaction code is marked as Revenue a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| fitMembershipLosResv | `Float` | Counts all reservations that are considered for Rooms Occupied a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. Used for Calculation of Average Length of Stay. |
| flgdFoodRevenue | `Float` | Flagged Food Revenue |
| flgdNonRevenue | `Float` | Flagged Non Revenue |
| flgdOtherRevenue | `Float` | Flagged Other Revenue |
| flgdPayment | `Float` | Flagged Total Payments. |
| flgdRoomRevenue | `Float` | Flagged Room Revenue |
| flgdTotalFoodTax | `Float` | Flagged Total Food Tax |
| flgdTotalNonRevenueTax | `Float` | Flagged Total Non Revenue Tax |
| flgdTotalOtherTax | `Float` | Flagged Total Other Tax |
| flgdTotalRevenue | `Float` | Flagged Total Revenue |
| flgdTotalRoomTax | `Float` | Flagged Total Room Tax |
| flgdTotalTax | `Float` | Flagged Total Tax |
| groupPrs | `Float` | Number of Adults and Children for Rooms In-House with a Block code attached to the reservation |
| groupRevenue | `Float` | Total amount of postings today where the Transaction Code is marked as Revenue for reservations that have a Block Code attached |
| groupRoom | `Float` | Number of Rooms that have a block code attached to the reservation. |
| groupRoomRevenue | `Float` | Total amount of postings today where the Transaction Code is marked as Revenue  and a Transaction Code Type is Lodging for reservations that have a Block Code attached |
| groupRoomTax | `Float` | Total tax amount of postings today where the Transaction Code is marked as Revenue  and a Transaction Code Type is Lodging for reservations that have a Block Code attached |
| groupRooms | `Float` | Number of Rooms that have a Group profile attached to the reservation. |
| groupTax | `Float` | Total tax  amount of postings today where the Transaction Code is marked as Revenue for reservations that have a Block Code attached |
| guestsInHouse | `Float` | Number of Adults and Children for Rooms In-House |
| houseUseAdults | `Float` | Total adults of reservations with a rate code marked as house use |
| houseUseBeds | `Float` | Total beds in rooms that have a rate code marked as house use |
| houseUseChildren | `Float` | Total children of reservations with a rate code marked as house use |
| houseUseNext31Days | `Float` | Total number of rooms reserved having a rate code marked as house-use starting tomorrow for 31 days. |
| houseUseNext365Days | `Float` | Total number of rooms reserved having a rate code marked as house-use starting tomorrow for 365 days. |
| houseUseRestOfMonth | `Float` | Total number of rooms reserved having a rate code marked as house-use starting tomorrow for the remainder of the current calendar month. |
| houseUseRestOfYear | `Float` | Total number of rooms reserved having a rate code marked as house-use starting tomorrow for the remainder of the current calendar year. |
| houseUseTomorrow | `Float` | Total number of rooms reserved having a rate code marked as house-use for tomorrow. |
| houseUseWeek | `Float` | Total number of rooms reserved having a rate code marked as house-use starting tomorrow for 7 days. |
| houseUseRooms | `Float` | Number of Rooms In-House that have a rate code marked as House Use |
| inHouseMaximumOccupancy | `Float` | Amount of all MAX_OCCUPANCY columns from all rooms. |
| individualDeparturePersons | `Float` | Number of persons with a departure date equal to today and no block code attached |
| individualDepartureRooms | `Float` | Number of Rooms with a Departure Date equal to today and no block code attached to the reservation. |
| individualGuests | `Float` | Number of Adults and Children for Rooms In-House with no Block code attached to the reservation |
| individualMembershipDeparturePersons | `Float` | Number of Adults and Children with a Departure Date equal to today a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| individualMembershipDepartureRooms | `Float` | Number of Rooms with a Departure Date equal to today a membership number of the default membership type attached to the reserveration with no block code attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| individualRevenue | `Float` | Total amount of postings today where the Transaction Code is marked as Revenue for reservations that do not have a Block Code attached |
| individualRoomRevenue | `Float` | Total amount of postings today where the Transaction Code is marked as Revenue  and a Transaction Code Type is Lodging for reservations that do not have a Block Code attached |
| individualRooms | `Float` | Number of Rooms that do not have a block code attached to the reservation. |
| inspectedRooms | `Float` | Number of Rooms that have a Housekeeping Status of IP |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lateCancelReservation | `Float` | Number of Reservations that were cancelled today with an arrival date equal to today. |
| lateCancelRooms | `Float` | Number of rooms that were cancelled today with an arrival date equal to today. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| membershipDeparturePersons | `Float` | Number of Adults and Children with a Departure Date equal to today and a membership number of the default membership type attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| membershipDepartureRooms | `Float` | Number of Rooms with a Departure Date equal to today and a membership number of the default membership type attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| membershipInHousePersons | `Float` | Number of Adults and Children for Rooms In-House with a membership number of the default membership type attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| membershipRevenue | `Float` | Total amount of postings today where the Transaction Code is marked as Revenue  for reservations that have a membership number of the default membership type attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| membershipTotalTax | `Float` | Total tax amount of postings today where the Transaction Code is marked as Revenue  for reservations that have a membership number of the default membership type attached to the reservation. If no default membership type is defined then any membership attached to the reservation will be considered. |
| multipleOccupancyRooms | `Float` | All rooms with guests greater than 1 |
| noShowPersons | `Float` | Number of Adults and Children with a Reservation Status of No Show |
| noShowRooms | `Float` | Number of Rooms with a Reservation Status of No Show |
| nonDeductibleArrivals | `Float` | Number of arrivals with a previous status of non-deduct prior to check-in. |
| noshowReservations | `Float` | Number of noshow reservations with an arrival date of today. |
| numberOfGroup | `Float` | Number of Blocks where todays date falls between the start date and end date |
| occupancy | `Float` | Occupancy |
| occupancyBeds | `Float` | Total beds in occupied rooms |
| occupancyNext31Days | `Float` | Total number of rooms reserved starting tomorrow for 31 days. |
| occupancyNext365Days | `Float` | Total number of rooms reserved starting tomorrow for 365 days. |
| occupancyRestOfMonth | `Float` | Total number of rooms reserved starting tomorrow for the remainder of the current calendar month. |
| occupancyRestOfYear | `Float` | Total number of rooms reserved starting tomorrow for the remainder of the current calendar year. |
| occupiedRooms | `Float` | Number of rooms In-House with a Front Office status of OCC |
| occupiedRoomsMonth | `Float` | Total number of rooms reserved starting tomorrow for 1 calendar month. |
| occupiedRoomsTomorrow | `Float` | Number of Rooms Occupied tomorrow divided by Total Rooms in Hotel multiplied by 100 |
| occupiedRoomsWeek | `Float` | Total number of rooms reserved starting tomorrow for 7 days. |
| occupiedRoomsYear | `Float` | Total number of rooms reserved starting tomorrow for 1 calendar year. |
| oooBeds | `Float` | Total beds in rooms marked as out of order for today |
| oooRoomsNext31Days | `Float` | Total number of rooms marked as Out of Order starting tomorrow for 31 days. |
| oooRoomsNext365Days | `Float` | Total number of rooms marked as Out of Order starting tomorrow for 365 days. |
| oooRoomsRestOfMonth | `Float` | Total number of rooms marked as Out of Order starting tomorrow for the remainder of the current calendar month. |
| oooRoomsRestOfYear | `Float` | Total number of rooms marked as Out of Order starting tomorrow for the remainder of the current calendar year. |
| oooRoomsTomorrow | `Float` | Total number of rooms marked as Out of Order for tomorrow. |
| oooRoomsWeek | `Float` | Total number of rooms marked as Out of Order starting tomorrow for 7 days. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| osBeds | `Float` | Total beds in rooms marked as out of service for today |
| osRoomsNext31Days | `Float` | Total number of rooms marked as Out of Service starting tomorrow for 31 days. |
| osRoomsNext365Days | `Float` | Total number of rooms marked as Out of Service starting tomorrow for 365 days. |
| osRoomsRestOfMonth | `Float` | Total number of rooms marked as Out of Service starting tomorrow for the remainder of the current calendar month. |
| osRoomsRestOfYear | `Float` | Total number of rooms marked as Out of Service starting tomorrow for the remainder of the current calendar year. |
| osRoomsTomorrow | `Float` | Total number of rooms marked as Out of Service for tomorrow. |
| osRoomsWeek | `Float` | Total number of rooms marked as Out of Service starting tomorrow for 7 days. |
| otherRevenue | `Float` | Other Revenue |
| otherTax | `Float` | Total tax amount of all postings today where the Transaction Code is marked as Revenue and the Transaction Code Type is  not Lodging Food and Beverage Tax or Non Hotel Supplies |
| outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| outOfServiceRooms | `Float` | Out of Service Rooms |
| ownerFoodBevRevenue | `Float` | Food and Beverage Revenue generated by an owner who is not in the Rental Program where the transaction code is marked as 'Revenue' and the Transaction Type is 'Food and Beverage'. |
| ownerOtherRevenue | `Float` | Other Revenue generated by an owner who is not in the Rental Program where the transaction codes are defined as 'other'. |
| ownerRentFoodBevRev | `Float` | Food and Beverage Revenue generated by an owner who is in the Rental Program where the transaction code is marked as 'Revenue' and the Transaction Type is 'Food and Beverage'. |
| ownerRentOtherRev | `Float` | Other Revenue generated by an owner who is in the Rental Program where the transaction codes are defined as 'other'. |
| ownerRentRoomRev | `Float` | Lodging Revenue generated by owners who are in the Rental Program. (Revenue defined as lodging) |
| ownerRentRooms | `Float` | Owners who are in rooms that are part of the Rental Program. |
| ownerRentRoomsOoo | `Float` | Rooms that are part of the Rental Program that are out of order. |
| ownerRoomRevenue | `Float` | Lodging Revenue generated by owners who are not in the Rental Program. (Revenue defined as lodging) |
| ownerRooms | `Float` | Owners who are in rooms that are not part of the Rental Program. |
| ownerRoomsInHotel | `Float` | Number of Rooms in Hotel that are linked to an active OVOS contract. |
| ownerRoomsOoo | `Float` | Rooms that are not part of the Rental Program that are out of order. |
| payment | `Float` | Total amount of postings today that have a Transaction Code linked to a Group of Payment |
| pcOccupancy1 | `Float` | Pc Occupancy 1 |
| pcOccupancy2 | `Float` | Pc Occupancy 2 |
| perOccupancy | `Float` | Rooms Occupied divided by Total Rooms in Hotel multiplied by 100 |
| perOccupancyWoCompHouse | `Float` | Rooms Occupied minus Comp & House divided by Total Rooms in Hotel multiplied by 100 |
| perOccupancyWoCompHouseOo | `Float` | Rooms Occupied minus Comp House and Out of Order divided by Total Rooms in Hotel multiplied by 100 |
| physicalBeds | `Float` | Total beds of all rooms in the property |
| physicalRooms | `Float` | Rooms in the Hotel |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rackRateTotalForAllRooms | `Float` | Amount of Brochure Rate on each room |
| rackRateTotalForOccupiedRooms | `Float` | Amount of Brochure Rate on each room with a Front Office status of OCC |
| repRoomClass | `String` | Reporting Room Class |
| repRoomClassDescription | `String` | Reporting Room Class Description |
| repeatPersons | `Float` | Number of persons in-house that are repeating guests |
| repeatRoomRevenue | `Float` | Total amount of postings today where the transaction code is marked as room revenue for reservations made by a repeating guest. |
| repeatRoomTax | `Float` | Total tax amount of postings today where the transaction code is marked as room revenue for reservations made by a repeating guest. |
| repeatRooms | `Float` | Number of rooms occupied by a repeating guest |
| repeatTotalRevenue | `Float` | Total amount of postings today where the transaction code is marked as revenue for reservations made by a repeating guest. |
| repeatTotalTax | `Float` | Total tax amount of postings today where the transaction code is marked as revenue for reservations made by a repeating guest. |
| reservation | `Float` | Number of Reservations that were created today for any date. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rollaways | `Float` | Not Used |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomNightsReservedToday | `Float` | Total number of nights from all Reservations Made Today |
| roomRevenue | `Float` | Room Revenue |
| roomTax | `Float` | Room Tax |
| roomclassdailytotalid | `String` | Roomclassdailytotalid |
| roomclassid | `String` | Roomclassid |
| roomsCancelledToday | `Float` | Number of rooms that were cancelled today for any date. |
| singleOccupancyRooms | `Float` | All rooms with total of 1 guest |
| sourceRooms | `Float` | Number of Rooms that have a Source profile attached to the reservation. |
| tomorrowArrivalPersons | `Float` | Number of Adults and Children with an Arrival Date equal to tomorrow |
| tomorrowArrivalRooms | `Float` | Number of Rooms with an Arrival Date equal to tomorrow |
| tomorrowDeparturePersons | `Float` | Number of Adults and Children with a Departure Date equal to tomorrow |
| tomorrowDepartureRooms | `Float` | Number of Rooms with a Departure Date equal to tomorrow |
| totalRevenue | `Float` | Total Revenue |
| totalTax | `Float` | Total Tax |
| turnaway | `Float` | Number of Turnaways recorded today for any date. |
| vIPGuest | `Float` | Number of Adults and Children for Rooms In-House with a VIP code attached to the profile. |
| walkInPersons | `Float` | Number of Adults and Children where the Walk-In button was used to make the reservation. |
| walkInRooms | `Float` | Number of Rooms where the Walk-In button was used to make the reservation. |
| yieldForAllRooms | `Float` | Amount of Room Revenue divided by Brochure Rate on each room multiplied by 100 |
| yieldForOccupiedRooms | `Float` | Amount of Room Revenue divided by Brochure Rate on each room listed as a Front Office status of OCC multiplied by 100 |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportGregerianCalendarDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessDate | `Date` | Business Date |
| calendar | `String` | Calendar |
| calendarDescription | `String` | Calendar Description |
| calendarpkid | `Float` | Calendarpkid |
| calendartype | `String` | Calendartype |
| daydesc | `String` | Daydesc |
| dayenddate | `Date` | Dayenddate |
| daytimespan | `Float` | Daytimespan |
| defaultCalendarYn | `String` | Default Calendar Y/N |
| monthDescription | `String` | Month Description |
| period | `String` | Period |
| periodEndDate | `Date` | Period End Date |
| periodStartDate | `Date` | Period Start Date |
| periodpkid | `Float` | Periodpkid |
| periodtimespan | `Float` | Periodtimespan |
| quarter | `String` | Quarter |
| quarterDescription | `String` | Quarter Description |
| quarterEndDate | `Date` | Quarter End Date |
| quarterStartDate | `Date` | Quarter Start Date |
| quarterpkid | `Float` | Quarterpkid |
| quartertimespan | `Float` | Quartertimespan |
| weekcode | `String` | Weekcode |
| weekdesc | `String` | Weekdesc |
| weekenddate | `Date` | Weekenddate |
| weekkey | `String` | Weekkey |
| weekstartdate | `Date` | Weekstartdate |
| weektimespan | `Float` | Weektimespan |
| year | `Float` | Year |
| yearDescription | `String` | Year Description |
| yearEndDate | `Date` | Year End Date |
| yearStartDate | `Date` | Year Start Date |
| yearpkid | `Float` | Yearpkid |
| yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportFiscalCalendarDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessDate | `Date` | Business Date |
| calendar | `String` | Calendar |
| calendarDescription | `String` | Calendar Description |
| calendarpkid | `Float` | Calendarpkid |
| calendartype | `String` | Calendartype |
| daydesc | `String` | Daydesc |
| dayenddate | `Date` | Dayenddate |
| daytimespan | `Float` | Daytimespan |
| defaultCalendarYn | `String` | Default Calendar Y/N |
| monthDescription | `String` | Month Description |
| period | `String` | Period |
| periodEndDate | `Date` | Period End Date |
| periodStartDate | `Date` | Period Start Date |
| periodpkid | `Float` | Periodpkid |
| periodtimespan | `Float` | Periodtimespan |
| quarter | `String` | Quarter |
| quarterDescription | `String` | Quarter Description |
| quarterEndDate | `Date` | Quarter End Date |
| quarterStartDate | `Date` | Quarter Start Date |
| quarterpkid | `Float` | Quarterpkid |
| quartertimespan | `Float` | Quartertimespan |
| weekcode | `String` | Weekcode |
| weekdesc | `String` | Weekdesc |
| weekenddate | `Date` | Weekenddate |
| weekkey | `String` | Weekkey |
| weekstartdate | `Date` | Weekstartdate |
| weektimespan | `Float` | Weektimespan |
| year | `Float` | Year |
| yearDescription | `String` | Year Description |
| yearEndDate | `Date` | Year End Date |
| yearStartDate | `Date` | Year Start Date |
| yearpkid | `Float` | Yearpkid |
| yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportRateSeasonDayDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralSeasonCode | `String` | Central Season Code |
| centralSeasonDescription | `String` | Central Season Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayKey | `Date` | Day Key |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| displayColor | `String` | Display Color |
| endDate | `Date` | End Date |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rateCode | `String` | Rate Code |
| ratecodeid | `String` | Ratecodeid |
| rateseasonid | `String` | Rateseasonid |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| seasonCode | `String` | Season Code |
| seasonDescription | `String` | Season Description |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportForeignCurrencyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| abbreviation | `String` | Abbreviation |
| activeYN | `String` | Active YN |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| currencyActionId | `Float` | Curr Action ID |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| decimals | `Float` | Decimals |
| deletedFlag | `String` | Deleted Flag |
| foreignCurrencyID | `String` | Foreign Currency ID |
| formatMask | `String` | Format Mask |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| mobileYn | `String` | Indicates if this Currency Exchange Rate is available for consumer mobility. |
| multiply | `Float` | Multiply |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| previousLocalCurrencyYn | `String` | This will be significant after EURO conversion. The currency before the Euro conversion gets a value Y. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sellCurrency | `String` | Indicates whether this currency code can be sold though currency exchange. |
| trianMethodYn | `String` | Indicates whether the currency is Euro participant. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| usedForCcPaymentsYn | `String` | Indicates if this currency can be used for Credit Card payments. |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportRoomClassDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| centralRoomClass | `String` | Central Room Class |
| centralRoomClassDescription | `String` | Central Room Class Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repSellSequence | `Float` | Reporting Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomclassid | `String` | Roomclassid |
| sellSequence | `Float` | Sell Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsManagersReportPropertyPropertyDetailsType

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

### StatisticsManagersReportQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| managersreportDetailsBusinessDate | `DateInput!` | Business Date<br>`@mandatoryInput` |
| managersreportDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| managersreportDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| managersreportDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| managersreportDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| managersreportDetailsRoomClass | `StringInput` | Room Class |
| gregeriancalendarDetailsDaykey | `DateInput` | Business Date |
| gregeriancalendarDetailsCalendarcode | `StringInput` | Calendar |
| gregeriancalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| gregeriancalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| gregeriancalendarDetailsQuartercode | `StringInput` | Quarter |
| gregeriancalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| gregeriancalendarDetailsYearcode | `FloatInput` | Year |
| gregeriancalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| fiscalcalendarDetailsDaykey | `DateInput` | Business Date |
| fiscalcalendarDetailsCalendarcode | `StringInput` | Calendar |
| fiscalcalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| fiscalcalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| fiscalcalendarDetailsQuartercode | `StringInput` | Quarter |
| fiscalcalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| fiscalcalendarDetailsYearcode | `FloatInput` | Year |
| fiscalcalendarDetailsYearpkid | `FloatInput` | Yearpkid |
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
| foreigncurrencyDetailsCurrencyCode | `StringInput` | Currency Code |
| foreigncurrencyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foreigncurrencyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foreigncurrencyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomclassDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomclassDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomclassDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomclassDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomclassDetailsRoomClass | `StringInput` | Room Class |
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

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsManagersReport($input: StatisticsManagersReportQueryArgumentsType!) {
  statisticsManagersReport(input: $input) @stream {
    managersReportDetails {
      adultsFree
      adultsInHouse
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
      agentRoomRevenue
      agentRoomTax
      agentRooms
      agentTotalRevenue
      agentTotalTax
      arrivalPersons
      arrivalReservations
      arrivalRooms
      availableRooms
      averageAgeToday
      averageDailyRateMinusComplimentaryHouseUse
      averageDailyRevenue
      bedsAvailable
      birthdays
      blockMemLosNights
      blockMemRoomRevenue
      blockMemRoomRevenueTax
      blockMemRooms
      blockMemTotalRevenue
      blockMemTotalRevenueTax
      blockMembershipLosResv
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
      cAgentRoomRevenue
      cAgentRoomTax
      cAgentTotalRevenue
      cAgentTotalTax
      cBlockMembershipRoomRevenue
      cBlockMembershipRoomRevenueTax
      cBlockMembershipTotalRevenue
      cBlockMembershipTotalRevenueTax
      cCompanyRoomRevenue
      cCompanyRoomTax
      cCompanyTotalRevenue
      cCompanyTotalTax
      cExchangeDate
      cExtendedStayAdvanceFoodRevenue
      cExtendedStayAdvanceFoodTax
      cExtendedStayAdvanceNonRevenue
      cExtendedStayAdvanceNonRevenueTax
      cExtendedStayAdvanceOtherRevenue
      cExtendedStayAdvanceOtherTax
      cExtendedStayAdvanceRoomRevenue
      cExtendedStayAdvanceRoomTax
      cExtendedStayAdvanceTotalRevenue
      cExtendedStayAdvanceTotalTax
      cExtendedStayFoodRevenue
      cExtendedStayFoodTax
      cExtendedStayNonRevenue
      cExtendedStayNonRevenueTax
      cExtendedStayOtherRevenue
      cExtendedStayOtherTax
      cExtendedStayRoomRevenue
      cExtendedStayRoomTax
      cExtendedStayTotalRevenue
      cExtendedStayTotalTax
      cFfFoodBevRevenue
      cFfOtherRevenue
      cFfRentFoodBevRevenue
      cFfRentOtherRevenue
      cFfRentRoomRevenue
      cFfRoomRevenue
      cFitMembershipRoomRevenue
      cFitMembershipRoomRevenueTax
      cFitMembershipTotalRevenue
      cFitMembershipTotalRevenueTax
      cFlaggedFoodRevenue
      cFlaggedNonRevenue
      cFlaggedOtherRevenue
      cFlaggedPayment
      cFlaggedRoomRevenue
      cFlaggedTotalFoodTax
      cFlaggedTotalNonRevenueTax
      cFlaggedTotalOtherTax
      cFlaggedTotalRevenue
      cFlaggedTotalRoomTax
      cFlaggedTotalTax
      cOwnerFoodBevRevenue
      cOwnerOtherRevenue
      cOwnerRentFoodBevRevenue
      cOwnerRentOtherRevenue
      cOwnerRentRoomRevenue
      cOwnerRoomRevenue
      cPayment
      cRepeatRoomRevenue
      cRepeatRoomTax
      cRepeatTotalRevenue
      cRepeatTotalTax
      cancelReservation
      cancelRooms
      cancellationsMadeToday
      centralAverageDailyRateMinusComplimentaryHouseUse
      centralAverageDailyRevenue
      centralCurrencyCode
      centralExchangeRate
      centralFBRevenue
      centralFBTax
      centralGroupRevenue
      centralGroupRoomRevenue
      centralGroupRoomTax
      centralGroupTax
      centralIndividualRevenue
      centralIndividualRoomRevenue
      centralMembershipRevenue
      centralMembershipTotalTax
      centralOtherRevenue
      centralOtherTax
      centralRackRateTotalForAllRooms
      centralRackRateTotalForOccupiedRooms
      centralRoomRevenue
      centralRoomTax
      centralTotalRevenue
      centralTotalTax
      centralYieldForAllRooms
      centralYieldForOccupiedRooms
      centralcurrencyid
      childrenFree
      childrenInHouse
      children1
      children2
      children3
      children4
      children5
      cleanRooms
      compAdults
      compBeds
      compChildren
      compNext31Days
      compNext365Days
      compRestOfMonth
      compRestOfYear
      compTomorrow
      compWeek
      companyRoomRevenue
      companyRoomTax
      companyRooms
      companyTotalRevenue
      companyTotalTax
      complimentaryRooms
      contextCd
      cribs
      dSI
      dayUseReservations
      dayUseRooms
      dayuseAdults
      dayuseChildren
      dayuseMonth
      dayuseNext31Days
      dayuseNext365Days
      dayuseRestOfMonth
      dayuseRestOfYear
      dayuseTomorrow
      dayuseWeek
      dayuseYear
      definiteArrivalRooms
      deletedFlag
      departurePersons
      departureRooms
      dirtyRooms
      doublesAsSingles
      earlyDeparturePersons
      earlyDepartureRooms
      exchangeRate
      extNoshowCRSRes
      extNoshowPrs
      extNoshowRes
      extNoshowRoom
      extendedStayAdvFoodRevenue
      extendedStayAdvFoodTax
      extendedStayAdvNonRevenue
      extendedStayAdvNonRevenueTax
      extendedStayAdvOtherRevenue
      extendedStayAdvOtherTax
      extendedStayAdvRoomRevenue
      extendedStayAdvRoomTax
      extendedStayAdvTotalRevenue
      extendedStayAdvTotalTax
      extendedStayCompRooms
      extendedStayFoodRevenue
      extendedStayFoodTax
      extendedStayHouseUseRooms
      extendedStayNonRevenue
      extendedStayNonRevenueTax
      extendedStayOccupancyRooms
      extendedStayOtherRevenue
      extendedStayOtherTax
      extendedStayPersons
      extendedStayRoom
      extendedStayRoomRevenue
      extendedStayRoomTax
      extendedStayTotalRevenue
      extendedStayTotalTax
      fBRevenue
      fBTax
      ffFoodBevRevenue
      ffOtherRevenue
      ffRentFoodBevRev
      ffRentOtherRev
      ffRentRoomRev
      ffRentRooms
      ffRoomRevenue
      ffRooms
      fitMemLosNights
      fitMemRoomRevenue
      fitMemRoomRevenueTax
      fitMemRooms
      fitMemTotalRevenue
      fitMemTotalRevenueTax
      fitMembershipLosResv
      flgdFoodRevenue
      flgdNonRevenue
      flgdOtherRevenue
      flgdPayment
      flgdRoomRevenue
      flgdTotalFoodTax
      flgdTotalNonRevenueTax
      flgdTotalOtherTax
      flgdTotalRevenue
      flgdTotalRoomTax
      flgdTotalTax
      groupPrs
      groupRevenue
      groupRoom
      groupRoomRevenue
      groupRoomTax
      groupRooms
      groupTax
      guestsInHouse
      houseUseAdults
      houseUseBeds
      houseUseChildren
      houseUseNext31Days
      houseUseNext365Days
      houseUseRestOfMonth
      houseUseRestOfYear
      houseUseTomorrow
      houseUseWeek
      houseUseRooms
      inHouseMaximumOccupancy
      individualDeparturePersons
      individualDepartureRooms
      individualGuests
      individualMembershipDeparturePersons
      individualMembershipDepartureRooms
      individualRevenue
      individualRoomRevenue
      individualRooms
      inspectedRooms
      jRNUpdateDate
      jRNUpdateDateAndTime
      lateCancelReservation
      lateCancelRooms
      locationID
      membershipDeparturePersons
      membershipDepartureRooms
      membershipInHousePersons
      membershipRevenue
      membershipTotalTax
      multipleOccupancyRooms
      noShowPersons
      noShowRooms
      nonDeductibleArrivals
      noshowReservations
      numberOfGroup
      occupancy
      occupancyBeds
      occupancyNext31Days
      occupancyNext365Days
      occupancyRestOfMonth
      occupancyRestOfYear
      occupiedRooms
      occupiedRoomsMonth
      occupiedRoomsTomorrow
      occupiedRoomsWeek
      occupiedRoomsYear
      oooBeds
      oooRoomsNext31Days
      oooRoomsNext365Days
      oooRoomsRestOfMonth
      oooRoomsRestOfYear
      oooRoomsTomorrow
      oooRoomsWeek
      organizationID
      osBeds
      osRoomsNext31Days
      osRoomsNext365Days
      osRoomsRestOfMonth
      osRoomsRestOfYear
      osRoomsTomorrow
      osRoomsWeek
      otherRevenue
      otherTax
      outOfOrderRooms
      outOfServiceRooms
      ownerFoodBevRevenue
      ownerOtherRevenue
      ownerRentFoodBevRev
      ownerRentOtherRev
      ownerRentRoomRev
      ownerRentRooms
      ownerRentRoomsOoo
      ownerRoomRevenue
      ownerRooms
      ownerRoomsInHotel
      ownerRoomsOoo
      payment
      pcOccupancy1
      pcOccupancy2
      perOccupancy
      perOccupancyWoCompHouse
      perOccupancyWoCompHouseOo
      physicalBeds
      physicalRooms
      primaryKeyID
      property
      rackRateTotalForAllRooms
      rackRateTotalForOccupiedRooms
      repRoomClass
      repRoomClassDescription
      repeatPersons
      repeatRoomRevenue
      repeatRoomTax
      repeatRooms
      repeatTotalRevenue
      repeatTotalTax
      reservation
      rnaInsertDate
      rnaUpdateDate
      rollaways
      roomClass
      roomClassDescription
      roomNightsReservedToday
      roomRevenue
      roomTax
      roomclassdailytotalid
      roomclassid
      roomsCancelledToday
      singleOccupancyRooms
      sourceRooms
      tomorrowArrivalPersons
      tomorrowArrivalRooms
      tomorrowDeparturePersons
      tomorrowDepartureRooms
      totalRevenue
      totalTax
      turnaway
      vIPGuest
      walkInPersons
      walkInRooms
      yieldForAllRooms
      yieldForOccupiedRooms
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
    foreignCurrencyDetails {
      abbreviation
      activeYN
      canDeleteYn
      chainCode
      currencyActionId
      currencyCode
      currencyDescription
      currencySymbol
      dSI
      decimals
      deletedFlag
      foreignCurrencyID
      formatMask
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      mobileYn
      multiply
      orderBy
      organizationID
      previousLocalCurrencyYn
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      sellCurrency
      trianMethodYn
      updateDate
      updateUser
      usedForCcPaymentsYn
    }
    roomClassDetails {
      canDeleteYn
      centralRoomClass
      centralRoomClassDescription
      dSI
      deletedflag
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomClassDescription
      roomclassid
      sellSequence
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
managers_report_details_schema = {
    'adultsFree': pl.Float64,
    'adultsInHouse': pl.Float64,
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
    'agentRoomRevenue': pl.Float64,
    'agentRoomTax': pl.Float64,
    'agentRooms': pl.Float64,
    'agentTotalRevenue': pl.Float64,
    'agentTotalTax': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalReservations': pl.Float64,
    'arrivalRooms': pl.Float64,
    'availableRooms': pl.Float64,
    'averageAgeToday': pl.Float64,
    'averageDailyRateMinusComplimentaryHouseUse': pl.Float64,
    'averageDailyRevenue': pl.Float64,
    'bedsAvailable': pl.Float64,
    'birthdays': pl.Float64,
    'blockMemLosNights': pl.Float64,
    'blockMemRoomRevenue': pl.Float64,
    'blockMemRoomRevenueTax': pl.Float64,
    'blockMemRooms': pl.Float64,
    'blockMemTotalRevenue': pl.Float64,
    'blockMemTotalRevenueTax': pl.Float64,
    'blockMembershipLosResv': pl.Float64,
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
    'cAgentRoomRevenue': pl.Float64,
    'cAgentRoomTax': pl.Float64,
    'cAgentTotalRevenue': pl.Float64,
    'cAgentTotalTax': pl.Float64,
    'cBlockMembershipRoomRevenue': pl.Float64,
    'cBlockMembershipRoomRevenueTax': pl.Float64,
    'cBlockMembershipTotalRevenue': pl.Float64,
    'cBlockMembershipTotalRevenueTax': pl.Float64,
    'cCompanyRoomRevenue': pl.Float64,
    'cCompanyRoomTax': pl.Float64,
    'cCompanyTotalRevenue': pl.Float64,
    'cCompanyTotalTax': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExtendedStayAdvanceFoodRevenue': pl.Float64,
    'cExtendedStayAdvanceFoodTax': pl.Float64,
    'cExtendedStayAdvanceNonRevenue': pl.Float64,
    'cExtendedStayAdvanceNonRevenueTax': pl.Float64,
    'cExtendedStayAdvanceOtherRevenue': pl.Float64,
    'cExtendedStayAdvanceOtherTax': pl.Float64,
    'cExtendedStayAdvanceRoomRevenue': pl.Float64,
    'cExtendedStayAdvanceRoomTax': pl.Float64,
    'cExtendedStayAdvanceTotalRevenue': pl.Float64,
    'cExtendedStayAdvanceTotalTax': pl.Float64,
    'cExtendedStayFoodRevenue': pl.Float64,
    'cExtendedStayFoodTax': pl.Float64,
    'cExtendedStayNonRevenue': pl.Float64,
    'cExtendedStayNonRevenueTax': pl.Float64,
    'cExtendedStayOtherRevenue': pl.Float64,
    'cExtendedStayOtherTax': pl.Float64,
    'cExtendedStayRoomRevenue': pl.Float64,
    'cExtendedStayRoomTax': pl.Float64,
    'cExtendedStayTotalRevenue': pl.Float64,
    'cExtendedStayTotalTax': pl.Float64,
    'cFfFoodBevRevenue': pl.Float64,
    'cFfOtherRevenue': pl.Float64,
    'cFfRentFoodBevRevenue': pl.Float64,
    'cFfRentOtherRevenue': pl.Float64,
    'cFfRentRoomRevenue': pl.Float64,
    'cFfRoomRevenue': pl.Float64,
    'cFitMembershipRoomRevenue': pl.Float64,
    'cFitMembershipRoomRevenueTax': pl.Float64,
    'cFitMembershipTotalRevenue': pl.Float64,
    'cFitMembershipTotalRevenueTax': pl.Float64,
    'cFlaggedFoodRevenue': pl.Float64,
    'cFlaggedNonRevenue': pl.Float64,
    'cFlaggedOtherRevenue': pl.Float64,
    'cFlaggedPayment': pl.Float64,
    'cFlaggedRoomRevenue': pl.Float64,
    'cFlaggedTotalFoodTax': pl.Float64,
    'cFlaggedTotalNonRevenueTax': pl.Float64,
    'cFlaggedTotalOtherTax': pl.Float64,
    'cFlaggedTotalRevenue': pl.Float64,
    'cFlaggedTotalRoomTax': pl.Float64,
    'cFlaggedTotalTax': pl.Float64,
    'cOwnerFoodBevRevenue': pl.Float64,
    'cOwnerOtherRevenue': pl.Float64,
    'cOwnerRentFoodBevRevenue': pl.Float64,
    'cOwnerRentOtherRevenue': pl.Float64,
    'cOwnerRentRoomRevenue': pl.Float64,
    'cOwnerRoomRevenue': pl.Float64,
    'cPayment': pl.Float64,
    'cRepeatRoomRevenue': pl.Float64,
    'cRepeatRoomTax': pl.Float64,
    'cRepeatTotalRevenue': pl.Float64,
    'cRepeatTotalTax': pl.Float64,
    'cancelReservation': pl.Float64,
    'cancelRooms': pl.Float64,
    'cancellationsMadeToday': pl.Float64,
    'centralAverageDailyRateMinusComplimentaryHouseUse': pl.Float64,
    'centralAverageDailyRevenue': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralExchangeRate': pl.Float64,
    'centralFBRevenue': pl.Float64,
    'centralFBTax': pl.Float64,
    'centralGroupRevenue': pl.Float64,
    'centralGroupRoomRevenue': pl.Float64,
    'centralGroupRoomTax': pl.Float64,
    'centralGroupTax': pl.Float64,
    'centralIndividualRevenue': pl.Float64,
    'centralIndividualRoomRevenue': pl.Float64,
    'centralMembershipRevenue': pl.Float64,
    'centralMembershipTotalTax': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralOtherTax': pl.Float64,
    'centralRackRateTotalForAllRooms': pl.Float64,
    'centralRackRateTotalForOccupiedRooms': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTax': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalTax': pl.Float64,
    'centralYieldForAllRooms': pl.Float64,
    'centralYieldForOccupiedRooms': pl.Float64,
    'centralcurrencyid': pl.Utf8,
    'childrenFree': pl.Float64,
    'childrenInHouse': pl.Float64,
    'children1': pl.Float64,
    'children2': pl.Float64,
    'children3': pl.Float64,
    'children4': pl.Float64,
    'children5': pl.Float64,
    'cleanRooms': pl.Float64,
    'compAdults': pl.Float64,
    'compBeds': pl.Float64,
    'compChildren': pl.Float64,
    'compNext31Days': pl.Float64,
    'compNext365Days': pl.Float64,
    'compRestOfMonth': pl.Float64,
    'compRestOfYear': pl.Float64,
    'compTomorrow': pl.Float64,
    'compWeek': pl.Float64,
    'companyRoomRevenue': pl.Float64,
    'companyRoomTax': pl.Float64,
    'companyRooms': pl.Float64,
    'companyTotalRevenue': pl.Float64,
    'companyTotalTax': pl.Float64,
    'complimentaryRooms': pl.Float64,
    'contextCd': pl.Utf8,
    'cribs': pl.Float64,
    'dSI': pl.Int64,
    'dayUseReservations': pl.Float64,
    'dayUseRooms': pl.Float64,
    'dayuseAdults': pl.Float64,
    'dayuseChildren': pl.Float64,
    'dayuseMonth': pl.Float64,
    'dayuseNext31Days': pl.Float64,
    'dayuseNext365Days': pl.Float64,
    'dayuseRestOfMonth': pl.Float64,
    'dayuseRestOfYear': pl.Float64,
    'dayuseTomorrow': pl.Float64,
    'dayuseWeek': pl.Float64,
    'dayuseYear': pl.Float64,
    'definiteArrivalRooms': pl.Float64,
    'deletedFlag': pl.Utf8,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'dirtyRooms': pl.Float64,
    'doublesAsSingles': pl.Float64,
    'earlyDeparturePersons': pl.Float64,
    'earlyDepartureRooms': pl.Float64,
    'exchangeRate': pl.Float64,
    'extNoshowCRSRes': pl.Float64,
    'extNoshowPrs': pl.Float64,
    'extNoshowRes': pl.Float64,
    'extNoshowRoom': pl.Float64,
    'extendedStayAdvFoodRevenue': pl.Float64,
    'extendedStayAdvFoodTax': pl.Float64,
    'extendedStayAdvNonRevenue': pl.Float64,
    'extendedStayAdvNonRevenueTax': pl.Float64,
    'extendedStayAdvOtherRevenue': pl.Float64,
    'extendedStayAdvOtherTax': pl.Float64,
    'extendedStayAdvRoomRevenue': pl.Float64,
    'extendedStayAdvRoomTax': pl.Float64,
    'extendedStayAdvTotalRevenue': pl.Float64,
    'extendedStayAdvTotalTax': pl.Float64,
    'extendedStayCompRooms': pl.Float64,
    'extendedStayFoodRevenue': pl.Float64,
    'extendedStayFoodTax': pl.Float64,
    'extendedStayHouseUseRooms': pl.Float64,
    'extendedStayNonRevenue': pl.Float64,
    'extendedStayNonRevenueTax': pl.Float64,
    'extendedStayOccupancyRooms': pl.Float64,
    'extendedStayOtherRevenue': pl.Float64,
    'extendedStayOtherTax': pl.Float64,
    'extendedStayPersons': pl.Float64,
    'extendedStayRoom': pl.Float64,
    'extendedStayRoomRevenue': pl.Float64,
    'extendedStayRoomTax': pl.Float64,
    'extendedStayTotalRevenue': pl.Float64,
    'extendedStayTotalTax': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBTax': pl.Float64,
    'ffFoodBevRevenue': pl.Float64,
    'ffOtherRevenue': pl.Float64,
    'ffRentFoodBevRev': pl.Float64,
    'ffRentOtherRev': pl.Float64,
    'ffRentRoomRev': pl.Float64,
    'ffRentRooms': pl.Float64,
    'ffRoomRevenue': pl.Float64,
    'ffRooms': pl.Float64,
    'fitMemLosNights': pl.Float64,
    'fitMemRoomRevenue': pl.Float64,
    'fitMemRoomRevenueTax': pl.Float64,
    'fitMemRooms': pl.Float64,
    'fitMemTotalRevenue': pl.Float64,
    'fitMemTotalRevenueTax': pl.Float64,
    'fitMembershipLosResv': pl.Float64,
    'flgdFoodRevenue': pl.Float64,
    'flgdNonRevenue': pl.Float64,
    'flgdOtherRevenue': pl.Float64,
    'flgdPayment': pl.Float64,
    'flgdRoomRevenue': pl.Float64,
    'flgdTotalFoodTax': pl.Float64,
    'flgdTotalNonRevenueTax': pl.Float64,
    'flgdTotalOtherTax': pl.Float64,
    'flgdTotalRevenue': pl.Float64,
    'flgdTotalRoomTax': pl.Float64,
    'flgdTotalTax': pl.Float64,
    'groupPrs': pl.Float64,
    'groupRevenue': pl.Float64,
    'groupRoom': pl.Float64,
    'groupRoomRevenue': pl.Float64,
    'groupRoomTax': pl.Float64,
    'groupRooms': pl.Float64,
    'groupTax': pl.Float64,
    'guestsInHouse': pl.Float64,
    'houseUseAdults': pl.Float64,
    'houseUseBeds': pl.Float64,
    'houseUseChildren': pl.Float64,
    'houseUseNext31Days': pl.Float64,
    'houseUseNext365Days': pl.Float64,
    'houseUseRestOfMonth': pl.Float64,
    'houseUseRestOfYear': pl.Float64,
    'houseUseTomorrow': pl.Float64,
    'houseUseWeek': pl.Float64,
    'houseUseRooms': pl.Float64,
    'inHouseMaximumOccupancy': pl.Float64,
    'individualDeparturePersons': pl.Float64,
    'individualDepartureRooms': pl.Float64,
    'individualGuests': pl.Float64,
    'individualMembershipDeparturePersons': pl.Float64,
    'individualMembershipDepartureRooms': pl.Float64,
    'individualRevenue': pl.Float64,
    'individualRoomRevenue': pl.Float64,
    'individualRooms': pl.Float64,
    'inspectedRooms': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lateCancelReservation': pl.Float64,
    'lateCancelRooms': pl.Float64,
    'locationID': pl.Utf8,
    'membershipDeparturePersons': pl.Float64,
    'membershipDepartureRooms': pl.Float64,
    'membershipInHousePersons': pl.Float64,
    'membershipRevenue': pl.Float64,
    'membershipTotalTax': pl.Float64,
    'multipleOccupancyRooms': pl.Float64,
    'noShowPersons': pl.Float64,
    'noShowRooms': pl.Float64,
    'nonDeductibleArrivals': pl.Float64,
    'noshowReservations': pl.Float64,
    'numberOfGroup': pl.Float64,
    'occupancy': pl.Float64,
    'occupancyBeds': pl.Float64,
    'occupancyNext31Days': pl.Float64,
    'occupancyNext365Days': pl.Float64,
    'occupancyRestOfMonth': pl.Float64,
    'occupancyRestOfYear': pl.Float64,
    'occupiedRooms': pl.Float64,
    'occupiedRoomsMonth': pl.Float64,
    'occupiedRoomsTomorrow': pl.Float64,
    'occupiedRoomsWeek': pl.Float64,
    'occupiedRoomsYear': pl.Float64,
    'oooBeds': pl.Float64,
    'oooRoomsNext31Days': pl.Float64,
    'oooRoomsNext365Days': pl.Float64,
    'oooRoomsRestOfMonth': pl.Float64,
    'oooRoomsRestOfYear': pl.Float64,
    'oooRoomsTomorrow': pl.Float64,
    'oooRoomsWeek': pl.Float64,
    'organizationID': pl.Int64,
    'osBeds': pl.Float64,
    'osRoomsNext31Days': pl.Float64,
    'osRoomsNext365Days': pl.Float64,
    'osRoomsRestOfMonth': pl.Float64,
    'osRoomsRestOfYear': pl.Float64,
    'osRoomsTomorrow': pl.Float64,
    'osRoomsWeek': pl.Float64,
    'otherRevenue': pl.Float64,
    'otherTax': pl.Float64,
    'outOfOrderRooms': pl.Float64,
    'outOfServiceRooms': pl.Float64,
    'ownerFoodBevRevenue': pl.Float64,
    'ownerOtherRevenue': pl.Float64,
    'ownerRentFoodBevRev': pl.Float64,
    'ownerRentOtherRev': pl.Float64,
    'ownerRentRoomRev': pl.Float64,
    'ownerRentRooms': pl.Float64,
    'ownerRentRoomsOoo': pl.Float64,
    'ownerRoomRevenue': pl.Float64,
    'ownerRooms': pl.Float64,
    'ownerRoomsInHotel': pl.Float64,
    'ownerRoomsOoo': pl.Float64,
    'payment': pl.Float64,
    'pcOccupancy1': pl.Float64,
    'pcOccupancy2': pl.Float64,
    'perOccupancy': pl.Float64,
    'perOccupancyWoCompHouse': pl.Float64,
    'perOccupancyWoCompHouseOo': pl.Float64,
    'physicalBeds': pl.Float64,
    'physicalRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rackRateTotalForAllRooms': pl.Float64,
    'rackRateTotalForOccupiedRooms': pl.Float64,
    'repRoomClass': pl.Utf8,
    'repRoomClassDescription': pl.Utf8,
    'repeatPersons': pl.Float64,
    'repeatRoomRevenue': pl.Float64,
    'repeatRoomTax': pl.Float64,
    'repeatRooms': pl.Float64,
    'repeatTotalRevenue': pl.Float64,
    'repeatTotalTax': pl.Float64,
    'reservation': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rollaways': pl.Float64,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomNightsReservedToday': pl.Float64,
    'roomRevenue': pl.Float64,
    'roomTax': pl.Float64,
    'roomclassdailytotalid': pl.Utf8,
    'roomclassid': pl.Utf8,
    'roomsCancelledToday': pl.Float64,
    'singleOccupancyRooms': pl.Float64,
    'sourceRooms': pl.Float64,
    'tomorrowArrivalPersons': pl.Float64,
    'tomorrowArrivalRooms': pl.Float64,
    'tomorrowDeparturePersons': pl.Float64,
    'tomorrowDepartureRooms': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalTax': pl.Float64,
    'turnaway': pl.Float64,
    'vIPGuest': pl.Float64,
    'walkInPersons': pl.Float64,
    'walkInRooms': pl.Float64,
    'yieldForAllRooms': pl.Float64,
    'yieldForOccupiedRooms': pl.Float64,
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
foreign_currency_details_schema = {
    'abbreviation': pl.Utf8,
    'activeYN': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'currencyActionId': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dSI': pl.Int64,
    'decimals': pl.Float64,
    'deletedFlag': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'formatMask': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mobileYn': pl.Utf8,
    'multiply': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'previousLocalCurrencyYn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellCurrency': pl.Utf8,
    'trianMethodYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'usedForCcPaymentsYn': pl.Utf8,
}
```
```python
room_class_details_schema = {
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomclassid': pl.Utf8,
    'sellSequence': pl.Float64,
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