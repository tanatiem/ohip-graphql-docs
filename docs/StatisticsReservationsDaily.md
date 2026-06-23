# StatisticsReservationsDaily
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `statisticsReservationsDaily`
> Detailed information on past reservations including occupancy and revenue figures with all profile data broken down by Market Rate code room type and periods of time.
  
**Return:** [`[StatisticsReservationsDailyType]`](#statisticsreservationsdailytype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsReservationsDailyQueryArgumentsType!`](#statisticsreservationsdailyqueryargumentstype) |  |

## Object Types

### StatisticsReservationsDailyType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | reservationDailyStatisticsDetails | [`StatisticsReservationsDailyReservationDailyStatisticsDetailsType`](#statisticsreservationsdailyreservationdailystatisticsdetailstype) | Reservation Daily Statistics |
| 2 | parentCompanyProfileDeatils | [`StatisticsReservationsDailyParentCompanyProfileDeatilsType`](#statisticsreservationsdailyparentcompanyprofiledeatilstype) | Parent Company Details |
| 3 | fiscalCalendarDetails | [`StatisticsReservationsDailyFiscalCalendarDetailsType`](#statisticsreservationsdailyfiscalcalendardetailstype) | Fiscal Calendar |
| 4 | gregerianCalendarDetails | [`StatisticsReservationsDailyGregerianCalendarDetailsType`](#statisticsreservationsdailygregeriancalendardetailstype) | Gregerian Calendar |
| 5 | reservationDetails | [`StatisticsReservationsDailyReservationDetailsType`](#statisticsreservationsdailyreservationdetailstype) | Reservation Details |
| 6 | foreignCurrencyDetails | [`StatisticsReservationsDailyForeignCurrencyDetailsType`](#statisticsreservationsdailyforeigncurrencydetailstype) | Foreign Currency Details |
| 7 | roomClassDetails | [`StatisticsReservationsDailyRoomClassDetailsType`](#statisticsreservationsdailyroomclassdetailstype) | Room Class Details |
| 8 | propertyPropertyDetails | [`StatisticsReservationsDailyPropertyPropertyDetailsType`](#statisticsreservationsdailypropertypropertydetailstype) | Resort Details |
| 9 | marketDetails | [`StatisticsReservationsDailyMarketDetailsType`](#statisticsreservationsdailymarketdetailstype) | Market Details |
| 10 | guestProfileAllInformationDetails | [`StatisticsReservationsDailyGuestProfileAllInformationDetailsType`](#statisticsreservationsdailyguestprofileallinformationdetailstype) | Profile All Details |
| 11 | nationalityDetails | [`StatisticsReservationsDailyNationalityDetailsType`](#statisticsreservationsdailynationalitydetailstype) | Nationality Details |
| 12 | rateCodeDetails | [`StatisticsReservationsDailyRateCodeDetailsType`](#statisticsreservationsdailyratecodedetailstype) | Rate Code Details |
| 13 | roomCategoryDetails | [`StatisticsReservationsDailyRoomCategoryDetailsType`](#statisticsreservationsdailyroomcategorydetailstype) | Room Category Details |
| 14 | countryDetails | [`StatisticsReservationsDailyCountryDetailsType`](#statisticsreservationsdailycountrydetailstype) | Country Details |
| 15 | channelDetails | [`StatisticsReservationsDailyChannelDetailsType`](#statisticsreservationsdailychanneldetailstype) | Channel Details |
| 16 | regionDetails | [`StatisticsReservationsDailyRegionDetailsType`](#statisticsreservationsdailyregiondetailstype) | Region Details |
| 17 | rateSeasonDayDetails | [`StatisticsReservationsDailyRateSeasonDayDetailsType`](#statisticsreservationsdailyrateseasondaydetailstype) | Rate Season Daily Details |
| 18 | roomDetails | [`StatisticsReservationsDailyRoomDetailsType`](#statisticsreservationsdailyroomdetailstype) | Room Details |
| 19 | guestStatusDetails | [`StatisticsReservationsDailyGuestStatusDetailsType`](#statisticsreservationsdailygueststatusdetailstype) | Guest Status Details |
| 20 | profileAccountsSourceDetails | [`StatisticsReservationsDailyProfileAccountsSourceDetailsType`](#statisticsreservationsdailyprofileaccountssourcedetailstype) | Profile Accounts Source Details |
| 21 | reservationStatisticsDetails | [`StatisticsReservationsDailyReservationStatisticsDetailsType`](#statisticsreservationsdailyreservationstatisticsdetailstype) | Reservation Statistics Details |
| 22 | bookedRoomCategoryDetails | [`StatisticsReservationsDailyBookedRoomCategoryDetailsType`](#statisticsreservationsdailybookedroomcategorydetailstype) | Booked Room Category Details |
| 23 | countryGroupDetails | [`StatisticsReservationsDailyCountryGroupDetailsType`](#statisticsreservationsdailycountrygroupdetailstype) | Country Group Details |
| 24 | profileAccountsTravelAgentDetails | [`StatisticsReservationsDailyProfileAccountsTravelAgentDetailsType`](#statisticsreservationsdailyprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| 25 | profileAccountsDetails | [`StatisticsReservationsDailyProfileAccountsDetailsType`](#statisticsreservationsdailyprofileaccountsdetailstype) | Profile Accounts Details |
| 26 | stateDetails | [`StatisticsReservationsDailyStateDetailsType`](#statisticsreservationsdailystatedetailstype) | State Details |
| 27 | groupDetails | [`StatisticsReservationsDailyGroupDetailsType`](#statisticsreservationsdailygroupdetailstype) | Group Profile Details |
| 28 | cityDetails | [`StatisticsReservationsDailyCityDetailsType`](#statisticsreservationsdailycitydetailstype) | City Details |
| 29 | promotionDetails | [`StatisticsReservationsDailyPromotionDetailsType`](#statisticsreservationsdailypromotiondetailstype) | Promotion Details |
| 30 | companyDetails | [`StatisticsReservationsDailyCompanyDetailsType`](#statisticsreservationsdailycompanydetailstype) | Company Details |
| 31 | blockDetails | [`StatisticsReservationsDailyBlockDetailsType`](#statisticsreservationsdailyblockdetailstype) | Block |
| 32 | travelAgentDetails | [`StatisticsReservationsDailyTravelAgentDetailsType`](#statisticsreservationsdailytravelagentdetailstype) | Travel Agent Details |
| 33 | allotmentStatisticsDetails | [`StatisticsReservationsDailyAllotmentStatisticsDetailsType`](#statisticsreservationsdailyallotmentstatisticsdetailstype) | Allotment Statistics Details |
| 34 | contactDetails | [`StatisticsReservationsDailyContactDetailsType`](#statisticsreservationsdailycontactdetailstype) | Contact Details |
| 35 | statisticsReservationsDailyRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyReservationDailyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | agentId | `Float` | Agent ID |
| 4 | agentprofileid | `Float` | Agentprofileid |
| 5 | allotmentHeaderId | `Float` | Allotment Header ID |
| 6 | allotmentid | `Float` | Block ID |
| 7 | arrivalPersons | `Float` | Arrival Persons |
| 8 | arrivalRooms | `Float` | Arrival Rooms |
| 9 | beginDate | `Date` | Begin Date |
| 10 | biReservationNameId | `Float` | Bi Resv Name ID |
| 11 | birthDate | `Date` | Birth Date |
| 12 | bookedRoomCategory | `String` | Booked Room Category |
| 13 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 14 | businessDate | `Date` | Business Date |
| 15 | businessDateCreated | `Date` | Business Date Created |
| 16 | cAdvanceTotalOtherTax | `Float` | Central Adv Total Other Tax |
| 17 | cCashRoomRevenue | `Float` | Central Cash Room Revenue |
| 18 | cCompRoomRevenue | `Float` | Central Comp Room Revenue |
| 19 | cExchangeDate | `Date` | Central Xchange Date |
| 20 | cExchangeRate | `Float` | Central Xchange Rate |
| 21 | cFlaggedFoodRevenue | `Float` | Central Flgd Food Revenue |
| 22 | cFlaggedNonRevenue | `Float` | Central Flgd Non Revenue |
| 23 | cFlaggedOtherRevenue | `Float` | Central Flgd Other Revenue |
| 24 | cFlaggedRoomRevenue | `Float` | Central Flgd Room Revenue |
| 25 | cFlaggedTotalFoodTax | `Float` | Central Flgd Total Food Tax |
| 26 | cFlaggedTotalNonRevenueTax | `Float` | Central Flgd Total Non Revenue Tax |
| 27 | cFlaggedTotalOtherTax | `Float` | Central Flgd Total Other Tax |
| 28 | cFlaggedTotalRevenue | `Float` | Central Flgd Total Revenue |
| 29 | cFlaggedTotalRoomTax | `Float` | Central Flgd Total Room Tax |
| 30 | cFlaggedTotalTax | `Float` | Central Flgd Total Tax |
| 31 | cPrAdvanceTotalFoodTax | `Float` | Central Pr Adv Total Food Tax |
| 32 | cRateAmount | `Float` | Central Rate Amount |
| 33 | cRsAdvanceFoodRevenue | `Float` | Central Rs Adv Food Revenue |
| 34 | cRsAdvanceFoodTax | `Float` | Central Rs Adv Food Tax |
| 35 | cRsAdvanceNonRevenue | `Float` | Central Rs Adv Non Revenue |
| 36 | cRsAdvanceNonRevenueTax | `Float` | Central Rs Adv Non Revenue Tax |
| 37 | cRsAdvanceOtherRevenue | `Float` | Central Rs Adv Other Revenue |
| 38 | cRsAdvanceOtherTax | `Float` | Central Rs Adv Other Tax |
| 39 | cRsAdvanceRoomRevenue | `Float` | Central Rs Adv Room Revenue |
| 40 | cRsAdvanceRoomTax | `Float` | Central Rs Adv Room Tax |
| 41 | cRsAdvanceTotalRevenue | `Float` | Central Rs Adv Total Revenue |
| 42 | cRsAdvanceTotalTax | `Float` | Central Rs Adv Total Tax |
| 43 | cUpsoldRevenue | `Float` | Central Upsold Revenue |
| 44 | cancellationDate | `DateTime` | Cancellation Date |
| 45 | cancelledPersons | `Float` | Cancelled Persons |
| 46 | cancelledReservations | `Float` | Cancelled Reservations |
| 47 | cancelledRooms | `Float` | Cancelled Rooms |
| 48 | cashRoomNts | `Float` | Cash Room Nts |
| 49 | cashRoomRevenue | `Float` | Cash Room Revenue |
| 50 | centralCurrencyCode | `String` | Central Currency Code |
| 51 | centralDistributedFoodRevenue | `Float` | Central Distributed Food Revenue |
| 52 | centralDistributedFoodRevenueAsPayee | `Float` | Central Distributed Food Revenue (as Payee |
| 53 | centralDistributedNonRevenue | `Float` | Central Distributed Non Revenue |
| 54 | centralDistributedNonRevenueAsPayee | `Float` | Central Distributed Non-Revenue (as Payee |
| 55 | centralDistributedOtherRevenue | `Float` | Central Distributed Other Revenue |
| 56 | centralDistributedOtherRevenueAsPayee | `Float` | Central Distributed Other Revenue (as Payee |
| 57 | centralDistributedRoomRevenue | `Float` | Central Distributed Room Revenue |
| 58 | centralDistributedRoomRevenueAsPayee | `Float` | Central Distributed Room Revenue (as Payee |
| 59 | centralDistributedTotalFoodTaxAsPayee | `Float` | Central Distributed Total Food Tax (as Payee |
| 60 | centralDistributedTotalNonRevenueTax | `Float` | Central Distributed Total Non Revenue Tax |
| 61 | centralDistributedTotalNonRevenueTaxAsPayee | `Float` | Central Distributed Total Non-Revenue Tax (as Payee |
| 62 | centralDistributedTotalOtherTaxAsPayee | `Float` | Central Distributed Total Other Tax (as Payee |
| 63 | centralDistributedTotalRevenue | `Float` | Central Distributed Total Revenue |
| 64 | centralDistributedTotalRevenueAsPayee | `Float` | Central Distributed Total Revenue (as Payee |
| 65 | centralDistributedTotalRoomTax | `Float` | Central Distributed Total Room Tax |
| 66 | centralDistributedTotalRoomTaxAsPayee | `Float` | Central Distributed Total Room Tax (as Payee |
| 67 | centralDistributedTotalTax | `Float` | Central Distributed Total Tax |
| 68 | centralDistributedTotalTaxAsPayee | `Float` | Central Distributed Total Tax (as Payee |
| 69 | centralExchangeRate | `Float` | Central Exchange Rate |
| 70 | centralFoodRevenue | `Float` | Central Food Revenue |
| 71 | centralFoodRevenueAsPayee | `Float` | Central Food Revenue (as Payee |
| 72 | centralMarketCode | `String` | Central Market Code |
| 73 | centralMarketDescription | `String` | Central Market Description |
| 74 | centralMarketGroupCode | `String` | Central Market Group Code |
| 75 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 76 | centralNonRevenue | `Float` | Central Non Revenue |
| 77 | centralNonRevenueAsPayee | `Float` | Central Non-Revenue (as Payee |
| 78 | centralOriginCode | `String` | Central Origin Code |
| 79 | centralOriginDescription | `String` | Central Origin Description |
| 80 | centralOriginalRoomType | `String` | Central Original Room Type |
| 81 | centralOtherRevenue | `Float` | Central Other Revenue |
| 82 | centralOtherRevenueAsPayee | `Float` | Central Other Revenue (as Payee |
| 83 | centralPackageFoodRevenue | `Float` | Central Package Food Revenue |
| 84 | centralPackageFoodRevenueAsPayee | `Float` | Central Package Food Revenue (as Payee |
| 85 | centralPackageNonRevenue | `Float` | Central Package Non Revenue |
| 86 | centralPackageNonRevenueAsPayee | `Float` | Central Package Non-Revenue (as Payee |
| 87 | centralPackageOtherRevenue | `Float` | Central Package Other Revenue |
| 88 | centralPackageOtherRevenueAsPayee | `Float` | Central Package Other Revenue (as Payee |
| 89 | centralPackageRoomRevenue | `Float` | Central Package Room Revenue |
| 90 | centralPackageRoomRevenueAsPayee | `Float` | Central Package Room Revenue (as Payee |
| 91 | centralRateCategory | `String` | Central Rate Category |
| 92 | centralRoomRevenue | `Float` | Central Room Revenue |
| 93 | centralRoomRevenueAsPayee | `Float` | Central Room Revenue (as Payee |
| 94 | centralSourceCode | `String` | Central Source Code |
| 95 | centralSourceDescription | `String` | Central Source Description |
| 96 | centralSourceGroupCode | `String` | Central Source Group Code |
| 97 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 98 | centralTotalFoodTax | `Float` | Central Total Food Tax |
| 99 | centralTotalFoodTaxGeneratedAsPayee | `Float` | Central Total Food Tax Generated (as Payee |
| 100 | centralTotalNonRevenueTax | `Float` | Central Total Non Revenue Tax |
| 101 | centralTotalNonRevenueTaxAsPayee | `Float` | Central Total Non-Revenue Tax (as Payee |
| 102 | centralTotalOtherTax | `Float` | Central Total Other Tax |
| 103 | centralTotalOtherTaxAsPayee | `Float` | Central Total Other Tax (as Payee |
| 104 | centralTotalPackageRevenue | `Float` | Central Total Package Revenue |
| 105 | centralTotalPackageRevenueAsPayee | `Float` | Central Total Package Revenue (as Payee |
| 106 | centralTotalRevenue | `Float` | Central Total Revenue |
| 107 | centralTotalRevenueAsPayee | `Float` | Central Total Revenue (as Payee |
| 108 | centralTotalRoomTax | `Float` | Central Total Room Tax |
| 109 | centralTotalRoomTaxAsPayee | `Float` | Central Total Room Tax (as Payee |
| 110 | centralTotalTax | `Float` | Central Total Tax |
| 111 | centralTotalTaxAsPayee | `Float` | Central Total Tax (as Payee |
| 112 | centralcurrencyid | `String` | Centralcurrencyid |
| 113 | channelid | `String` | Channelid |
| 114 | children | `Float` | Children |
| 115 | childrenTaxFree | `Float` | Children Tax Free |
| 116 | children1 | `Float` | Children1 |
| 117 | children2 | `Float` | Children2 |
| 118 | children3 | `Float` | Children3 |
| 119 | children4 | `Float` | Children4 |
| 120 | children5 | `Float` | Children5 |
| 121 | city | `String` | City |
| 122 | cityid | `String` | Cityid |
| 123 | compRoomNts | `Float` | Comp Room Nts |
| 124 | compRoomRevenue | `Float` | Comp Room Revenue |
| 125 | companyId | `Float` | Company ID |
| 126 | companyProfileID | `Float` | Company Profile ID |
| 127 | companyProfileName | `String` | Company Profile Name |
| 128 | compflag | `String` | Compflag |
| 129 | complimentaryYN | `String` | Complimentary YN |
| 130 | contactId | `Float` | Contact ID |
| 131 | contactProfileID | `Float` | Contact Profile ID |
| 132 | contactflag | `String` | Contactflag |
| 133 | country | `String` | Country |
| 134 | countryMainGroup | `String` | Country Main Group |
| 135 | countryName | `String` | Country Name |
| 136 | countrygroupid | `String` | Countrygroupid |
| 137 | countryid | `String` | Countryid |
| 138 | cribs | `Float` | Cribs |
| 139 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 140 | dayUsePersons | `Float` | Day Use Persons |
| 141 | dayUseReservations | `Float` | Day Use Reservations |
| 142 | dayUseRooms | `Float` | Day Use Rooms |
| 143 | deletedFlag | `String` | Deleted Flag |
| 144 | departurePersons | `Float` | Departure Persons |
| 145 | departureRooms | `Float` | Departure Rooms |
| 146 | distributedFoodRevenue | `Float` | Distributed Food Revenue |
| 147 | distributedFoodRevenueAsPayee | `Float` | Distributed Food Revenue (as Payee |
| 148 | distributedNonRevenue | `Float` | Distributed Non Revenue |
| 149 | distributedNonRevenueAsPayee | `Float` | Distributed Non-Revenue (as Payee |
| 150 | distributedOtherRevenue | `Float` | Distributed Other Revenue |
| 151 | distributedOtherRevenueAsPayee | `Float` | Distributed Other Revenue (as Payee |
| 152 | distributedRoomRevenue | `Float` | Distributed Room Revenue |
| 153 | distributedRoomRevenueAsPayee | `Float` | Distributed Room Revenue (as Payee |
| 154 | distributedTotalFoodTaxAsPayee | `Float` | Distributed Total Food Tax as Payee |
| 155 | distributedTotalNonRevenueTax | `Float` | Distributed Total Non Revenue Tax |
| 156 | distributedTotalNonRevenueTaxAsPayee | `Float` | Distributed Total Non-Revenue Tax (as Payee |
| 157 | distributedTotalOtherTax | `Float` | Distributed Total Other Tax |
| 158 | distributedTotalOtherTaxAsPayee | `Float` | Distributed Total Other Tax (as Payee |
| 159 | distributedTotalRevenue | `Float` | Distributed Total Revenue |
| 160 | distributedTotalRevenueAsPayee | `Float` | Distributed Total Revenue (as Payee |
| 161 | distributedTotalRoomTax | `Float` | Distributed Total Room Tax |
| 162 | distributedTotalRoomTaxAsPayee | `Float` | Distributed Total Room Tax (as Payee |
| 163 | distributedTotalTax | `Float` | Distributed Total Tax |
| 164 | distributedTotalTaxAsPayee | `Float` | Distributed Total Tax (as Payee |
| 165 | district | `String` | District |
| 166 | dueOutYn | `String` | Due Out Y/N |
| 167 | dueoutflag | `String` | Dueoutflag |
| 168 | endDate | `Date` | End Date |
| 169 | endbusinessdate | `Date` | Endbusinessdate |
| 170 | extendedStayTier | `Float` | Extended stay tier of the reservation on the business date. Based on the length of stay and the rate tier configuration if active or OPERA standard rate tiers. |
| 171 | extraBeds | `Float` | Extra Beds |
| 172 | fiscalregioncode | `String` | Fiscalregioncode |
| 173 | flgdFoodRevenue | `Float` | Flagged Food Revenue |
| 174 | flgdNonRevenue | `Float` | Flagged Non Revenue |
| 175 | flgdOtherRevenue | `Float` | Flagged Other Revenue |
| 176 | flgdRoomRevenue | `Float` | Flagged Room Revenue |
| 177 | flgdTotalFoodTax | `Float` | Flagged Total Food Tax |
| 178 | flgdTotalNonRevenueTax | `Float` | Flagged Total Non Revenue Tax |
| 179 | flgdTotalOtherTax | `Float` | Flagged Total Other Tax |
| 180 | flgdTotalRevenue | `Float` | Flagged Total Revenue |
| 181 | flgdTotalRoomTax | `Float` | Flagged Total Room Tax |
| 182 | flgdTotalTax | `Float` | Flagged Total Tax |
| 183 | foodRevenue | `Float` | Food Revenue |
| 184 | foodRevenueAsPayee | `Float` | Food Revenue (as Payee |
| 185 | freqflyermembtype | `String` | Freqflyermembtype |
| 186 | freqguestmembtype | `String` | Freqguestmembtype |
| 187 | groupId | `Float` | Group ID |
| 188 | groupProfileID | `Float` | Group Profile ID |
| 189 | groupProfileName | `String` | Group Profile Name |
| 190 | guestProfileID | `Float` | Guest Profile ID |
| 191 | gueststatusid | `String` | Gueststatusid |
| 192 | houseUseYn | `String` | House Use Y/N |
| 193 | houseuseflag | `String` | Houseuseflag |
| 194 | insertDate | `DateTime` | Insert Date |
| 195 | internalCompanyprofileid | `Float` | Companyprofileid |
| 196 | internalContactprofileid | `Float` | Contactprofileid |
| 197 | internalDeletedflag | `String` | Deleted Flag |
| 198 | internalGroupprofileid | `Float` | Groupprofileid |
| 199 | internalMembershipid | `Float` | Membershipid |
| 200 | internalReservationNameId | `Float` | Resv Name ID |
| 201 | jRNUpdateDate | `Date` | JRN Update Date |
| 202 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 203 | locationID | `String` | Internal ID to uniquely identify the Property |
| 204 | marketCode | `String` | Market Code |
| 205 | marketDescription | `String` | Market Description |
| 206 | marketDisplaySequence | `Float` | Market Display Sequence |
| 207 | marketGroupCode | `String` | Market Group Code |
| 208 | marketGroupDescription | `String` | Market Group Description |
| 209 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 210 | marketgroupid | `String` | Marketgroupid |
| 211 | marketid | `String` | Marketid |
| 212 | membershipCardNo | `String` | Membership Card Number |
| 213 | membershipId | `Float` | Membership ID |
| 214 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 215 | nationality | `String` | Nationality |
| 216 | nationalityCode | `String` | Nationality Code |
| 217 | nationalityid | `String` | Nationalityid |
| 218 | nights | `Float` | Nights |
| 219 | noShowReservations | `Float` | Number Show Reservations |
| 220 | noShowPersons | `Float` | No-Show Persons |
| 221 | noShowRooms | `Float` | No-Show Rooms |
| 222 | nonRevenue | `Float` | Non Revenue |
| 223 | nonRevenueAsPayee | `Float` | Non-Revenue (as Payee |
| 224 | numberOfStays | `Float` | No of Stays |
| 225 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 226 | originCode | `String` | Origin Code |
| 227 | originDescription | `String` | Origin Description |
| 228 | originalEndDate | `Date` | Original End Date |
| 229 | originalRoomCategory | `String` | Stores the room type associated with the reservation at the moment of booking. |
| 230 | otherRevenue | `Float` | Other Revenue |
| 231 | otherRevenueAsPayee | `Float` | Other Revenue (as Payee |
| 232 | outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 233 | outOfServiceRooms | `Float` | Out of Service Rooms |
| 234 | ownerRentalYn | `String` | Owner Rental Y/N |
| 235 | ownerfriendfamilyflag | `String` | Ownerfriendfamilyflag |
| 236 | ownerrentalflag | `String` | Ownerrentalflag |
| 237 | packageFoodRevenue | `Float` | Package Food Revenue |
| 238 | packageFoodRevenueAsPayee | `Float` | Package Food Revenue (as Payee |
| 239 | packageNonRevenue | `Float` | Package Non Revenue |
| 240 | packageNonRevenueAsPayee | `Float` | Package Non-Revenue (as Payee |
| 241 | packageOtherRevenue | `Float` | Package Other Revenue |
| 242 | packageOtherRevenueAsPayee | `Float` | Package Other Revenue (as Payee |
| 243 | packageRoomRevenue | `Float` | Package Room Revenue |
| 244 | packageRoomRevenueAsPayee | `Float` | Package Room Revenue (as Payee |
| 245 | parentCompanyId | `Float` | Parent Company ID |
| 246 | parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| 247 | physicalQuantity | `Float` | Physical Quantity |
| 248 | physicalRooms | `Float` | Physical Rooms |
| 249 | prAdvTotalFoodTax | `Float` | Pr Advance Total Food Tax |
| 250 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 251 | primaryYn | `Float` | Primary Y/N |
| 252 | primaryflag | `Float` | Primaryflag |
| 253 | profiledailytotalid | `Float` | Profiledailytotalid |
| 254 | profileid | `Float` | Profileid |
| 255 | promotionCode | `String` | Promotion Code |
| 256 | promotionCodeDesc | `String` | Promotion Code Description |
| 257 | promotionid | `String` | Promotionid |
| 258 | property | `String` | Code to uniquely identify the Property |
| 259 | pseudoRoomYN | `String` | Pseudo Room YN |
| 260 | pseudoroomflag | `String` | Pseudoroomflag |
| 261 | quantity | `Float` | Quantity |
| 262 | rateAmount | `Float` | Rate Amount |
| 263 | rateCategory | `String` | Rate Category |
| 264 | rateCode | `String` | Rate Code |
| 265 | ratecategoryid | `String` | Ratecategoryid |
| 266 | ratecodeid | `String` | Ratecodeid |
| 267 | regionCode | `String` | Region Code |
| 268 | regionid | `String` | Regionid |
| 269 | repPromotionCode | `String` | Reporting Promotion Code |
| 270 | repPromotionCodeDescription | `String` | Reporting Promotion Code Desc |
| 271 | reservationArrivals | `Float` | Reservation Arrivals |
| 272 | reservationDate | `Date` | Reservation Date |
| 273 | reservationNameID | `Float` | Reservation Name ID |
| 274 | reservationNights | `Float` | Reservation Nights |
| 275 | reservationNumberOfStays | `Float` | Reservation No of Stays |
| 276 | reservationStatus | `String` | Reservation Status |
| 277 | reservationid | `Float` | Reservationid |
| 278 | resvenddate | `Date` | Resvenddate |
| 279 | resvinsertsource | `String` | Resvinsertsource |
| 280 | resvinsertsourcetype | `String` | Resvinsertsourcetype |
| 281 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 282 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 283 | room | `String` | Room |
| 284 | roomAdults | `Float` | Room Adults |
| 285 | roomCategory | `String` | Room Category |
| 286 | roomChildren | `Float` | Room Children |
| 287 | roomClass | `String` | Room Class |
| 288 | roomNights | `Float` | Room Nights |
| 289 | roomReservationStatus | `String` | Room Reservation Status |
| 290 | roomRevenue | `Float` | Room Revenue |
| 291 | roomRevenueAsPayee | `Float` | Room Revenue (as Payee |
| 292 | roomcategoryid | `String` | Roomcategoryid |
| 293 | roomclassid | `String` | Roomclassid |
| 294 | roomid | `String` | Roomid |
| 295 | rsAdvFoodRevenue | `Float` | Distributed food revenue generated as staying guest. |
| 296 | rsAdvFoodTax | `Float` | Distributed food tax generated as staying guest. |
| 297 | rsAdvNonRevenue | `Float` | Distributed non revenue generated as staying guest. |
| 298 | rsAdvNonRevenueTax | `Float` | Distributed non-revenue tax generated as staying guest |
| 299 | rsAdvOtherRevenue | `Float` | Distributed other revenue generated as staying guest. |
| 300 | rsAdvOtherTax | `Float` | Distributed other tax generated as staying guest. |
| 301 | rsAdvRoomRevenue | `Float` | Distributed room revenue generated as staying guest. |
| 302 | rsAdvRoomTax | `Float` | Distributed room tax generated as staying guest. |
| 303 | rsAdvTotalRevenue | `Float` | Distributed total revenue generated as staying guest. |
| 304 | rsAdvTotalTax | `Float` | Distributed total tax amount generated as staying guest. |
| 305 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 306 | sourceCode | `String` | Source Code |
| 307 | sourceDescription | `String` | Source Description |
| 308 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 309 | sourceGroupCode | `String` | Source Group Code |
| 310 | sourceGroupDescription | `String` | Source Group Description |
| 311 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 312 | sourceProfId | `Float` | Source Prof ID |
| 313 | sourceProfileID | `Float` | Source Profile ID |
| 314 | sourcegroupid | `String` | Sourcegroupid |
| 315 | sourceid | `String` | Sourceid |
| 316 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 317 | stateCode | `String` | State Code |
| 318 | stateid | `String` | Stateid |
| 319 | stayAdults | `Float` | Stay Adults |
| 320 | stayChildren | `Float` | Stay Children |
| 321 | stayPersons | `Float` | Stay Persons |
| 322 | totalFoodTax | `Float` | Total Food Tax |
| 323 | totalFoodTaxGeneratedAsPayee | `Float` | Total Food Tax Generated (as Payee |
| 324 | totalNonRevenueTax | `Float` | Total Non Revenue Tax |
| 325 | totalNonRevenueTaxAsPayee | `Float` | Total Non-Revenue Tax (as Payee |
| 326 | totalOtherTax | `Float` | Total Other Tax |
| 327 | totalOtherTaxAsPayee | `Float` | Total Other Tax (as Payee |
| 328 | totalPackageRevenue | `Float` | Total Package Revenue |
| 329 | totalPackageRevenueAsPayee | `Float` | Total Package Revenue (as Payee |
| 330 | totalRevenue | `Float` | Total Revenue |
| 331 | totalRevenueAsPayee | `Float` | Total Revenue (as Payee |
| 332 | totalRoomTax | `Float` | Total Room Tax |
| 333 | totalRoomTaxAsPayee | `Float` | Total Room Tax (as Payee |
| 334 | totalTax | `Float` | Total Tax |
| 335 | totalTaxAsPayee | `Float` | Total Tax (as Payee |
| 336 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 337 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 338 | updateDate | `DateTime` | Update Date |
| 339 | upsoldRevenue | `Float` | Upsold Revenue |
| 340 | vIPStatus | `String` | VIP Status |
| 341 | walkinYn | `String` | Walkin Y/N |
| 342 | walkinflag | `String` | Walkinflag |
| 343 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyParentCompanyProfileDeatilsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRNumberCentral | `String` | AR Number (Central) |
| 3 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 4 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 5 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 6 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 7 | accountBillingContact | `String` | Billing contact person in PARENTCOMPANYPROFILE. |
| 8 | accountSource | `String` | Account Source |
| 9 | accountType | `String` | Account Type |
| 10 | actionCode | `String` | Action Code |
| 11 | activeYN | `String` | Active YN |
| 12 | address1 | `String` | Address 1 |
| 13 | address2 | `String` | Address 2 |
| 14 | address3 | `String` | Address 3 |
| 15 | address4 | `String` | Address 4 |
| 16 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 17 | allOwnerCodes | `String` | All Owner Codes |
| 18 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 19 | alternateMiddleName | `String` | Alternate Middle Name |
| 20 | alternateSalutation | `String` | Alternate Salutation |
| 21 | alternateTitle | `String` | Alternate Title |
| 22 | autoPopRouting | `String` | Auto Pop Routing |
| 23 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 24 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 25 | billingCode | `String` | The billing code for this name record. |
| 26 | billingInstruction | `String` | Billing Instruction |
| 27 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 28 | birthCountry | `String` | Country of birth. |
| 29 | birthDate | `Date` | Birth Date |
| 30 | birthDateStr | `String` | Birth Date Str |
| 31 | birthPlace | `String` | Place of birth. |
| 32 | blMsg | `String` | Bl Msg |
| 33 | businessTitle | `String` | Business Title |
| 34 | cExchangeDate | `Date` | Central Xchange Date |
| 35 | cExchangeRate | `Float` | Central Xchange Rate |
| 36 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 37 | cRSNameid | `Float` | The unique identifier of the CRS |
| 38 | cashBlInd | `String` | Cash Bl Individual |
| 39 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 40 | centralAccountType | `String` | Central Account Type |
| 41 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 42 | centralDefaultKeyword | `String` | Central Default Keyword |
| 43 | centralNationality | `String` | Central Nationality |
| 44 | centralNationalityCode | `String` | Central Nationality Code |
| 45 | centralPriority | `String` | Central Priority |
| 46 | centralStateCode | `String` | Central State Code |
| 47 | centralTerritory | `String` | Central Territory |
| 48 | chainCode | `String` | Chain Code |
| 49 | city | `String` | City |
| 50 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 51 | combinedName | `String` | Combined Name |
| 52 | commissionCode | `String` | Commission Code |
| 53 | communicationType1 | `String` | Communication Type 1 |
| 54 | communicationType2 | `String` | Communication Type 2 |
| 55 | communicationType3 | `String` | Communication Type 3 |
| 56 | communicationValue1 | `String` | Communication Value 1 |
| 57 | communicationValue2 | `String` | Communication Value 2 |
| 58 | communicationValue3 | `String` | Communication Value 3 |
| 59 | competition | `String` | Competition |
| 60 | contractNo | `String` | Contract Number (used for customers). |
| 61 | contractRecvDate | `Date` | The date the group contract was received. |
| 62 | corporateID | `String` | Corporate ID |
| 63 | corporateIDType | `String` | Specified whether Name_Code column has PARENTCOMPANYPROFILE # or IATA #. For PARENTCOMPANYPROFILE # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 64 | country | `String` | Country |
| 65 | countryCode | `String` | Country Code |
| 66 | creditCardName | `String` | Credit Card Name |
| 67 | creditCardType | `String` | Credit Card Type |
| 68 | creditRating | `String` | Credit Rating |
| 69 | currencyCode | `String` | Currency Code |
| 70 | currencyDescription | `String` | Currency Description |
| 71 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 72 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 73 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 74 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 75 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 76 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 77 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 78 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 79 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 80 | defaultKeyword | `String` | Default Keyword |
| 81 | deletedFlag | `String` | Deleted Flag |
| 82 | department | `String` | Department |
| 83 | deptId | `String` | Dept ID |
| 84 | directBillBatchType | `String` | Direct Bill Batch Type |
| 85 | displayName | `String` | Display Name |
| 86 | downloadDate | `Date` | Download Date |
| 87 | downloadResort | `String` | Download Property |
| 88 | downloadSrep | `Float` | Download Srep |
| 89 | eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| 90 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 91 | email | `String` | Email |
| 92 | emailYn | `String` | Email Y/N |
| 93 | envelopeGreeting | `String` | Envelope Greeting |
| 94 | externalId | `String` | External ID |
| 95 | externalReferenceRequ | `String` | Not Used. |
| 96 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 97 | fMembershipCardNumbers | `String` | F Membership Card Numbers |
| 98 | fMembershipClassDesc | `String` | F Membership Class Description |
| 99 | fMembershipClasses | `String` | F Membership Classes |
| 100 | fMembershipCodes | `String` | F Membership Codes |
| 101 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 102 | fMembershipIds | `String` | F Membership Ids |
| 103 | fSubscriptionDb | `String` | F Subscription Db |
| 104 | fSubscriptionYn | `String` | F Subscription Y/N |
| 105 | faxNumber | `String` | Fax Number |
| 106 | first | `String` | First |
| 107 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 108 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 109 | gDSTransactionNo | `String` | Not used. |
| 110 | gender | `String` | Gender |
| 111 | geographicRegion | `String` | Not used. |
| 112 | guestClassification | `String` | Not used. |
| 113 | guestPrivYn | `String` | Guest Priv Y/N |
| 114 | historyYN | `String` | History YN |
| 115 | holdCode | `String` | Hold Code |
| 116 | iataConsortia | `String` | IATA Consortia |
| 117 | idCountry | `String` | ID Country |
| 118 | idDate | `Date` | ID Date |
| 119 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 120 | idNumber | `String` | ID Number |
| 121 | idPlace | `String` | ID Place |
| 122 | idType | `String` | ID Type |
| 123 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 124 | inactiveDate | `Date` | Inactive Date |
| 125 | inactiveFlag | `String` | Inactive Flag |
| 126 | inactiveReason | `String` | Reason why record was inactivated. |
| 127 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 128 | incognitoFirstName | `String` | Incognito First Name |
| 129 | incognitoLastName | `String` | Incognito Last Name |
| 130 | indexName | `String` | Index Name |
| 131 | industryCode | `String` | Industry Code |
| 132 | influence | `String` | Influence |
| 133 | insertDate | `DateTime` | Insert Date |
| 134 | insertUser | `String` | Insert User |
| 135 | interest | `String` | Interest Code. |
| 136 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 137 | internalDeletedflag | `String` | Deleted Flag |
| 138 | internalInactiveflag | `String` | Inactive Flag |
| 139 | internalOrganizationId | `Float` | Organization ID |
| 140 | jRNUpdateDate | `Date` | JRN Update Date |
| 141 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 142 | language | `String` | Language |
| 143 | languageCode | `String` | Language Code |
| 144 | laptopChange | `Float` | Laptop Change |
| 145 | last | `String` | Last |
| 146 | lastGroup | `String` | Last Group |
| 147 | lastRate | `Float` | Last Rate |
| 148 | lastRoom | `String` | Not used. |
| 149 | lastSource | `String` | Last Source |
| 150 | lastStay | `Date` | Last Stay |
| 151 | lastUpdatedResort | `String` | Last property that updated this record. |
| 152 | letterGreeting | `String` | Letter Greeting |
| 153 | mailListYN | `String` | Mail List YN |
| 154 | mailType | `String` | The type of mail this user should be sent. |
| 155 | mailYn | `String` | Mail Y/N |
| 156 | marketResearchYn | `String` | Market Research Y/N |
| 157 | markets | `String` | Markets |
| 158 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 159 | middle | `String` | Middle |
| 160 | name | `String` | Name |
| 161 | name2 | `String` | Name 2 |
| 162 | name3 | `String` | Name 3 |
| 163 | nameComment | `String` | Not Used. |
| 164 | nameTaxType | `String` | Name Tax Type |
| 165 | nameWithTitle | `String` | Name With Title |
| 166 | nationality | `String` | Nationality |
| 167 | nationalityCode | `String` | Nationality Code |
| 168 | negotiatedRateCodes | `String` | Negotiated Rate Codes |
| 169 | nextStay | `Date` | Next Stay |
| 170 | nickname | `String` | The nickname of this individual. |
| 171 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 172 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 173 | passport | `String` | Passport |
| 174 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 175 | paymentMethodsCode | `String` | Payment Methods Code |
| 176 | paymentMethodsDesc | `String` | Payment Methods Description |
| 177 | phoneNumber | `String` | Phone no. |
| 178 | phoneYn | `String` | Phone Y/N |
| 179 | postalCode | `String` | Postal Code |
| 180 | preferredRoomNo | `String` | Preferred Room Number |
| 181 | primaryAddressId | `Float` | Not used. |
| 182 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 183 | primaryNameId | `Float` | Not Used. |
| 184 | primaryOwner | `String` | Primary Owner |
| 185 | primaryOwnerCode | `String` | Primary Owner Code |
| 186 | primaryPhoneId | `Float` | Not used. |
| 187 | priority | `String` | Priority |
| 188 | privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 189 | productInterest | `String` | Product Interest |
| 190 | profession | `String` | Profession of the guest |
| 191 | profileArrCodes | `String` | Profile Arrangement Codes |
| 192 | profileArrangementDesc | `String` | Profile Arr Description |
| 193 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 194 | profileType | `String` | Profile Type |
| 195 | propertyRegistered | `String` | Resort for which Job is registered. |
| 196 | protected | `String` | Protected |
| 197 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 198 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 199 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 200 | rateStructure | `String` | The default rate structure for this name. |
| 201 | region | `String` | Region |
| 202 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 203 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 204 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 205 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 206 | repInactiveReason | `String` | Reporting Inactive Reason |
| 207 | repInactiveReasonCode | `String` | Reporting Inactive Reason Code |
| 208 | repIndustryDescription | `String` | Reporting Industry Desc |
| 209 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 210 | repMailActionDescription | `String` | Reporting Mail Action Desc |
| 211 | repMarketsDescription | `String` | Reporting Markets Desc |
| 212 | repNameType | `String` | Reporting Name Type |
| 213 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 214 | repPriorityDescription | `String` | Reporting Priority Desc |
| 215 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 216 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 217 | repScopeDescription | `String` | Reporting Scope Desc |
| 218 | repStateDescription | `String` | Reporting State Desc |
| 219 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 220 | repTitle | `String` | Reporting Title |
| 221 | repTitleName | `String` | Reporting Title Name |
| 222 | repVIPName | `String` | Reporting Vip Name |
| 223 | repVIPStatus | `String` | Reporting Vip Status |
| 224 | repeatGuestId | `String` | The primary membership # for this guest. |
| 225 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 226 | resvContact | `String` | Reservation Contact person. |
| 227 | roomsPotential | `String` | Rooms Potential |
| 228 | salutation | `String` | Salutation Greeting |
| 229 | scope | `String` | Scope |
| 230 | scopeCity | `String` | Scope City |
| 231 | searchName | `String` | The Uppercase value of Last or PARENTCOMPANYPROFILE. |
| 232 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 233 | sfirst | `String` | Uppercase value of First Name. |
| 234 | smsYn | `String` | Use this alert to text a notification. |
| 235 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 236 | srepCode | `String` | Srep Code |
| 237 | state | `String` | State |
| 238 | stateCode | `String` | State Code |
| 239 | suffix | `String` | Suffix |
| 240 | summRefCc | `String` | Summ Ref Cc |
| 241 | superSearchIndexText | `String` | Super Search Index Text |
| 242 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 243 | taxCategory | `String` | Tax Category |
| 244 | taxExemptStatus | `String` | Not used. |
| 245 | taxID1 | `String` | Tax ID 1 |
| 246 | taxID2 | `String` | Tax ID 2 |
| 247 | taxOffice | `String` | Tax Office Name |
| 248 | taxType | `String` | Tax Type |
| 249 | territory | `String` | Territory |
| 250 | thirdPartyYn | `String` | Third Party Y/N |
| 251 | title | `String` | Title |
| 252 | titleSuffix | `Float` | Title Suffix |
| 253 | totalArrivals | `Float` | Total Arrivals |
| 254 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 255 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 256 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 257 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 258 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 259 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 260 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 261 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 262 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 263 | totalFbRevenue | `Float` | Total FB Revenue |
| 264 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 265 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 266 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 267 | totalNonRevenue | `Float` | Total Non Revenue |
| 268 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 269 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 270 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 271 | totalOtherRevenue | `Float` | Total Other Revenue |
| 272 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 273 | totalReservationNights | `Float` | Total Reservation Nights |
| 274 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 275 | totalRevenue | `Float` | Total Revenue |
| 276 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 277 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 278 | totalRoomRevenue | `Float` | Total Room Revenue |
| 279 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 280 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 281 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 282 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 283 | traceCode | `String` | Trace Code |
| 284 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 285 | uDFC01 | `String` | UDFC01 |
| 286 | uDFC02 | `String` | UDFC02 |
| 287 | uDFC03 | `String` | UDFC03 |
| 288 | uDFC04 | `String` | UDFC04 |
| 289 | uDFC05 | `String` | UDFC05 |
| 290 | uDFC06 | `String` | UDFC06 |
| 291 | uDFC07 | `String` | UDFC07 |
| 292 | uDFC08 | `String` | UDFC08 |
| 293 | uDFC09 | `String` | UDFC09 |
| 294 | uDFC10 | `String` | UDFC10 |
| 295 | uDFC11 | `String` | UDFC11 |
| 296 | uDFC12 | `String` | UDFC12 |
| 297 | uDFC13 | `String` | UDFC13 |
| 298 | uDFC14 | `String` | UDFC14 |
| 299 | uDFC15 | `String` | UDFC15 |
| 300 | uDFC16 | `String` | UDFC16 |
| 301 | uDFC17 | `String` | UDFC17 |
| 302 | uDFC18 | `String` | UDFC18 |
| 303 | uDFC19 | `String` | UDFC19 |
| 304 | uDFC20 | `String` | UDFC20 |
| 305 | uDFC21 | `String` | UDFC21 |
| 306 | uDFC22 | `String` | UDFC22 |
| 307 | uDFC23 | `String` | UDFC23 |
| 308 | uDFC24 | `String` | UDFC24 |
| 309 | uDFC25 | `String` | UDFC25 |
| 310 | uDFC26 | `String` | UDFC26 |
| 311 | uDFC27 | `String` | UDFC27 |
| 312 | uDFC28 | `String` | UDFC28 |
| 313 | uDFC29 | `String` | UDFC29 |
| 314 | uDFC30 | `String` | UDFC30 |
| 315 | uDFC31 | `String` | UDFC31 |
| 316 | uDFC32 | `String` | UDFC32 |
| 317 | uDFC33 | `String` | UDFC33 |
| 318 | uDFC34 | `String` | UDFC34 |
| 319 | uDFC35 | `String` | UDFC35 |
| 320 | uDFC36 | `String` | UDFC36 |
| 321 | uDFC37 | `String` | UDFC37 |
| 322 | uDFC38 | `String` | UDFC38 |
| 323 | uDFC39 | `String` | UDFC39 |
| 324 | uDFC40 | `String` | UDFC40 |
| 325 | uDFD01 | `Date` | UDFD01 |
| 326 | uDFD02 | `Date` | UDFD02 |
| 327 | uDFD03 | `Date` | UDFD03 |
| 328 | uDFD04 | `Date` | UDFD04 |
| 329 | uDFD05 | `Date` | UDFD05 |
| 330 | uDFD06 | `Date` | UDFD06 |
| 331 | uDFD07 | `Date` | UDFD07 |
| 332 | uDFD08 | `Date` | UDFD08 |
| 333 | uDFD09 | `Date` | UDFD09 |
| 334 | uDFD10 | `Date` | UDFD10 |
| 335 | uDFD11 | `Date` | UDFD11 |
| 336 | uDFD12 | `Date` | UDFD12 |
| 337 | uDFD13 | `Date` | UDFD13 |
| 338 | uDFD14 | `Date` | UDFD14 |
| 339 | uDFD15 | `Date` | UDFD15 |
| 340 | uDFD16 | `Date` | UDFD16 |
| 341 | uDFD17 | `Date` | UDFD17 |
| 342 | uDFD18 | `Date` | UDFD18 |
| 343 | uDFD19 | `Date` | UDFD19 |
| 344 | uDFD20 | `Date` | UDFD20 |
| 345 | uDFN01 | `Float` | UDFN01 |
| 346 | uDFN02 | `Float` | UDFN02 |
| 347 | uDFN03 | `Float` | UDFN03 |
| 348 | uDFN04 | `Float` | UDFN04 |
| 349 | uDFN05 | `Float` | UDFN05 |
| 350 | uDFN06 | `Float` | UDFN06 |
| 351 | uDFN07 | `Float` | UDFN07 |
| 352 | uDFN08 | `Float` | UDFN08 |
| 353 | uDFN09 | `Float` | UDFN09 |
| 354 | uDFN10 | `Float` | UDFN10 |
| 355 | uDFN11 | `Float` | UDFN11 |
| 356 | uDFN12 | `Float` | UDFN12 |
| 357 | uDFN13 | `Float` | UDFN13 |
| 358 | uDFN14 | `Float` | UDFN14 |
| 359 | uDFN15 | `Float` | UDFN15 |
| 360 | uDFN16 | `Float` | UDFN16 |
| 361 | uDFN17 | `Float` | UDFN17 |
| 362 | uDFN18 | `Float` | UDFN18 |
| 363 | uDFN19 | `Float` | UDFN19 |
| 364 | uDFN20 | `Float` | UDFN20 |
| 365 | uDFN21 | `Float` | UDFN21 |
| 366 | uDFN22 | `Float` | UDFN22 |
| 367 | uDFN23 | `Float` | UDFN23 |
| 368 | uDFN24 | `Float` | UDFN24 |
| 369 | uDFN25 | `Float` | UDFN25 |
| 370 | uDFN26 | `Float` | UDFN26 |
| 371 | uDFN27 | `Float` | UDFN27 |
| 372 | uDFN28 | `Float` | UDFN28 |
| 373 | uDFN29 | `Float` | UDFN29 |
| 374 | uDFN30 | `Float` | UDFN30 |
| 375 | uDFN31 | `Float` | UDFN31 |
| 376 | uDFN32 | `Float` | UDFN32 |
| 377 | uDFN33 | `Float` | UDFN33 |
| 378 | uDFN34 | `Float` | UDFN34 |
| 379 | uDFN35 | `Float` | UDFN35 |
| 380 | uDFN36 | `Float` | UDFN36 |
| 381 | uDFN37 | `Float` | UDFN37 |
| 382 | uDFN38 | `Float` | UDFN38 |
| 383 | uDFN39 | `Float` | UDFN39 |
| 384 | uDFN40 | `Float` | UDFN40 |
| 385 | updateDate | `DateTime` | Update Date |
| 386 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 387 | updateUser | `String` | Update User |
| 388 | uploadDate | `Date` | Upload Date |
| 389 | vendorId | `Float` | Vendor ID |
| 390 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 391 | vipAuthorization | `String` | Not Used. |
| 392 | vipName | `String` | VIP Name |
| 393 | vipStatus | `String` | VIP Status |
| 394 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 395 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 396 | xfirstName | `String` | Xfirst Name |
| 397 | xlastName | `String` | Xlast Name |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyFiscalCalendarDetailsType

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

### StatisticsReservationsDailyGregerianCalendarDetailsType

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

### StatisticsReservationsDailyReservationDetailsType

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

### StatisticsReservationsDailyForeignCurrencyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | abbreviation | `String` | Abbreviation |
| 2 | activeYN | `String` | Active YN |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | chainCode | `String` | Chain Code |
| 5 | currencyActionId | `Float` | Curr Action ID |
| 6 | currencyCode | `String` | Currency Code |
| 7 | currencyDescription | `String` | Currency Description |
| 8 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | decimals | `Float` | Decimals |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | foreignCurrencyID | `String` | Foreign Currency ID |
| 13 | formatMask | `String` | Format Mask |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | internalDeletedflag | `String` | Deleted Flag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | mobileYn | `String` | Indicates if this Currency Exchange Rate is available for consumer mobility. |
| 22 | multiply | `Float` | Multiply |
| 23 | orderBy | `Float` | Order By |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | previousLocalCurrencyYn | `String` | This will be significant after EURO conversion. The currency before the Euro conversion gets a value Y. |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | sellCurrency | `String` | Indicates whether this currency code can be sold though currency exchange. |
| 30 | trianMethodYn | `String` | Indicates whether the currency is Euro participant. |
| 31 | updateDate | `DateTime` | Update Date |
| 32 | updateUser | `Float` | Update User |
| 33 | usedForCcPaymentsYn | `String` | Indicates if this currency can be used for Credit Card payments. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyRoomClassDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | centralRoomClass | `String` | Central Room Class |
| 3 | centralRoomClassDescription | `String` | Central Room Class Description |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedflag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | inactiveflag | `String` | Inactive Flag |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Code to uniquely identify the Property |
| 16 | repItem | `String` | Reporting Item |
| 17 | repItemName | `String` | Reporting Item Name |
| 18 | repItemOrderby | `Float` | Reporting Item Orderby |
| 19 | repSellSequence | `Float` | Reporting Sell Sequence |
| 20 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 21 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 22 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 23 | roomClass | `String` | Room Class |
| 24 | roomClassDescription | `String` | Room Class Description |
| 25 | roomclassid | `String` | Roomclassid |
| 26 | sellSequence | `Float` | Sell Sequence |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyPropertyPropertyDetailsType

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

### StatisticsReservationsDailyMarketDetailsType

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

### StatisticsReservationsDailyGuestProfileAllInformationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | guestProfileID | `Float` | The primary key for this table. |
| 2 | aRNumber | `String` | Account number. |
| 3 | aRNumberCentral | `String` | Account Receivable No. of this profile. |
| 4 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 5 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 6 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 7 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 8 | accountBillingContact | `String` | Billing contact person in company. |
| 9 | accountSource | `String` | Used in S&C Module. |
| 10 | accountType | `String` | Account Type of this Profile |
| 11 | accountTypeDescription | `String` | The description of this value. |
| 12 | accountsourceDesc | `String` | The description of this value. |
| 13 | actionCode | `String` | Mailing action codes. |
| 14 | activeYN | `String` | Profile is active or not. |
| 15 | address1 | `String` | The first line of street address. |
| 16 | address2 | `String` | The second line of street address. |
| 17 | address3 | `String` | The third line of street address. |
| 18 | address4 | `String` | The fourth line of street address. |
| 19 | addressId | `Float` | The primary key for this table. |
| 20 | addressLangCodeDesc | `String` | Description for each language code. |
| 21 | addressLanguageCode | `String` | Address Language Code |
| 22 | addressType | `String` | The type of address. |
| 23 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 24 | allResorts | `String` | All Resorts |
| 25 | alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
| 26 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 27 | alternateLanguageDescription | `String` | Description for each language code. |
| 28 | alternateSalutation | `String` | Alternate Salutation |
| 29 | autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| 30 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 31 | billingCode | `String` | The billing code for this name record. |
| 32 | billingInstruction | `String` | Billing Instruction |
| 33 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 34 | birthCountry | `String` | Country of Birth |
| 35 | birthDate | `Date` | Date of Birth of the Individual Profiles. |
| 36 | birthDateStr | `String` | Stores the encrypted birth date. |
| 37 | birthPlace | `String` | Place of Birth |
| 38 | blMsg | `String` | Any Message for the Restricted profile. |
| 39 | businessSegment | `String` | Used in S&C Module. |
| 40 | businessSegmentDescription | `String` | The description of this value. |
| 41 | businessTitle | `String` | The business title for this individual. |
| 42 | cExchangeDate | `Date` | Central Xchange Date |
| 43 | cExchangeRate | `Float` | Central Xchange Rate |
| 44 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 45 | cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| 46 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 47 | centralAccountType | `String` | Central Account Type |
| 48 | centralBusinessSegment | `String` | Central Business Segment |
| 49 | centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| 50 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 51 | centralDefaultKeyword | `String` | The keyword to search on. |
| 52 | centralGuestTitleCode | `String` | Central Guest Title Code |
| 53 | centralInactiveReason | `String` | Central Inactive Reason |
| 54 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 55 | centralMailActionDescription | `String` | Central Mail Action Description |
| 56 | centralMailingActionCode | `String` | Central Mailing Action Code |
| 57 | centralPriority | `String` | Central Priority |
| 58 | centralStateCode | `String` | Central State Code |
| 59 | centralTerritory | `String` | Central Territory |
| 60 | centralVIPCode | `String` | Central VIP Code |
| 61 | centralVIPDescription | `String` | Central VIP Description |
| 62 | chainCode | `String` | Chain Code |
| 63 | city | `String` | The city for this address. |
| 64 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 65 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 66 | combinedName | `String` | Combined Name |
| 67 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 68 | comments | `String` | Not Used. |
| 69 | commissionCode | `String` | Commission Code for the Commission Percentage. |
| 70 | commissionCodes | `String` | Code for the commission for Travel Agent |
| 71 | commissionCurrencyId | `String` | Comm Curr ID |
| 72 | commissionid | `String` | Commission Code for the Commission Percentage. |
| 73 | communicationRole1 | `String` | Role in which this phone type belongs to. |
| 74 | communicationRole2 | `String` | Role in which this phone type belongs to. |
| 75 | communicationRole3 | `String` | Role in which this phone type belongs to. |
| 76 | communicationType1 | `String` | The type of this phone number. |
| 77 | communicationType2 | `String` | The type of this phone number. |
| 78 | communicationType3 | `String` | The type of this phone number. |
| 79 | communicationValue1 | `String` | The phone number for this record |
| 80 | communicationValue2 | `String` | The phone number for this record |
| 81 | communicationValue3 | `String` | The phone number for this record |
| 82 | companyAlternate | `String` | Extended Byte Company Name |
| 83 | companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| 84 | companyNameId | `Float` | Not used. |
| 85 | competition | `String` | Competaion code . |
| 86 | competitionDesc | `String` | The description of this value. |
| 87 | contactYN | `String` | Used in S&C Module. |
| 88 | contractNo | `String` | Group Contract number. |
| 89 | contractRecvDate | `Date` | The date the group contract was received. |
| 90 | corpTypeDesc | `String` | Corp Type Description |
| 91 | corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 92 | country | `String` | Country name. |
| 93 | countryCode | `String` | Country . |
| 94 | createdByUser | `String` | The user that created the record |
| 95 | createdOnDate | `DateTime` | The date the record was created |
| 96 | creditRating | `String` | Credit rating. |
| 97 | currencyCode | `String` | Currency Code |
| 98 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 99 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 100 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 101 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 102 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 103 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 104 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 105 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 106 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 107 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 108 | debtorName | `String` | Debtor Name |
| 109 | decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| 110 | defaultKeyword | `String` | The keyword to search on. |
| 111 | deletedFlag | `String` | Deleted Flag |
| 112 | department | `String` | Used in S&C Module. |
| 113 | deptId | `String` | Used in S&C Module. |
| 114 | description | `String` | Used in QMS Module |
| 115 | directBillBatchType | `String` | Direct Bill Batch Type |
| 116 | displayName | `String` | Display Name |
| 117 | downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| 118 | downloadResort | `String` | REsort name which has downloaded on the laptop. |
| 119 | downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| 120 | eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| 121 | eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| 122 | email | `String` | The phone number for this record |
| 123 | emailYN | `String` | Email YN |
| 124 | envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| 125 | externalDisplayName | `String` | External Display Name |
| 126 | externalFirstName | `String` | The first name of an individual. |
| 127 | externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| 128 | externalName | `String` | The last name of the individual profile. |
| 129 | externalReferenceRequ | `String` | Not Used. |
| 130 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 131 | fMembershipCardNumbers | `String` | Membership Card Number. |
| 132 | fMembershipClassDesc | `String` | Descripion of membership class |
| 133 | fMembershipClasses | `String` | F Membership Classes |
| 134 | fMembershipCodes | `String` | F Membership Codes |
| 135 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 136 | fMembershipIds | `String` | Primary Key for this table. |
| 137 | fMembershipType | `String` | Type of the Membership. |
| 138 | fSubscriptionDb | `String` | The ID of the external Database. |
| 139 | fSubscriptionYn | `String` | The ID of the external Database. |
| 140 | faxNumber | `String` | The phone number for this record |
| 141 | firstName | `String` | The first name of an individual name. |
| 142 | firstNameAlternate | `String` | First Name Alternate |
| 143 | firstNameIncognito | `String` | The keyword to search on. |
| 144 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 145 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 146 | gDSTransactionNo | `String` | Not used. |
| 147 | gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| 148 | geographicRegion | `String` | Not used. |
| 149 | guestClassification | `String` | Not used. |
| 150 | guestCountry | `String` | Country name. |
| 151 | guestCurrencyCode | `String` | Currency code for the Commission payment. |
| 152 | guestLanguageCode | `String` | Description for each language code. |
| 153 | guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 154 | guestMiddleName | `String` | The middle name of this individual. |
| 155 | guestNameSuffix | `String` | Guest Name Suffix |
| 156 | guestPrivilegeYN | `String` | Guest Privilege YN |
| 157 | guestTitleCode | `String` | The title of the individual. |
| 158 | hasRequestedMailYN | `String` | Has Requested Mail YN |
| 159 | historyYN | `String` | Keep guest in history Y/N |
| 160 | holdCode | `String` | Hold code for the Commission handling purposes. |
| 161 | iataConsortia | `String` | Consortia for the IATA number. |
| 162 | idCountry | `String` | The country where ID was issued |
| 163 | idDate | `Date` | Issued date of Identification |
| 164 | idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| 165 | idPlace | `String` | The place where ID was issued |
| 166 | idType | `String` | Identification Type. Eg Passport Driving License etc |
| 167 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 168 | inactiveDate | `Date` | The date the record was marked as inactive |
| 169 | inactiveFlag | `String` | Inactive Flag |
| 170 | inactiveReason | `String` | Reason why record was inactivated. |
| 171 | inactiveReasonDescription | `String` | The description of this value. |
| 172 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 173 | indexName | `String` | Index Name |
| 174 | industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| 175 | industryDesc | `String` | The description of this value. |
| 176 | influence | `String` | Used in S&C Module. |
| 177 | influenceDesc | `String` | The description of this value. |
| 178 | interest | `String` | Interest Code. |
| 179 | internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| 180 | internalDeletedflag | `String` | Deleted Flag |
| 181 | internalInactiveflag | `String` | Inactive Flag |
| 182 | internalOrganizationId | `Float` | Organization ID |
| 183 | jRNUpdateDate | `Date` | JRN Update Date |
| 184 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 185 | languageCode | `String` | Primary language used for the profile. |
| 186 | laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| 187 | lastGroup | `String` | Last Group |
| 188 | lastNameAlternate | `String` | Last Name Alternate |
| 189 | lastNameIncognito | `String` | The keyword to search on. |
| 190 | lastRate | `Float` | Last Rate |
| 191 | lastRateCode | `String` | Last Rate Code |
| 192 | lastRoom | `String` | The room that is booked for this reservation leg. |
| 193 | lastRoomProperty | `String` | Last Room Property |
| 194 | lastSource | `String` | Last Source |
| 195 | lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| 196 | lastUpdatedResort | `String` | Last property that updated this record. |
| 197 | legalCompany | `String` | The legal company name for this company. |
| 198 | letterGreeting | `String` | Used in S&C Module. |
| 199 | mailActionDescription | `String` | The description of this value. |
| 200 | mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| 201 | mailType | `String` | The type of mail this user should be sent. |
| 202 | mailingActionCode | `String` | Mailing action codes. |
| 203 | marketResearchYN | `String` | Market Research YN |
| 204 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 205 | nameTaxType | `String` | Not used. |
| 206 | nameType | `String` | The type of Profile. |
| 207 | nameTypeDescription | `String` | The description of this value. |
| 208 | name2 | `String` | Not Used. |
| 209 | name3 | `String` | Not used. |
| 210 | nationality | `String` | Nationality |
| 211 | nationalityCode | `String` | Nationality of the individual. |
| 212 | negotiatedRateCodes | `String` | The rate code for which this record applies. |
| 213 | nextStay | `Date` | This is a begin_date  with no  time component. |
| 214 | nickname | `String` | The nickname of this individual. |
| 215 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 216 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 217 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 218 | phone | `String` | The phone number for this record |
| 219 | phoneWeb | `String` | The phone number for this record |
| 220 | phoneYN | `String` | Phone YN |
| 221 | postalCode | `String` | The postal code of this address. |
| 222 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 223 | preferredRoomNo | `String` | Preferred Room Number |
| 224 | primaryAddressId | `Float` | Not used. |
| 225 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 226 | primaryNameId | `Float` | Not Used. |
| 227 | primaryOwner | `String` | Primary Owner |
| 228 | primaryOwnerCode | `String` | Primary Owner Code |
| 229 | primaryPhoneId | `Float` | Not used. |
| 230 | priority | `String` | Priority of the account |
| 231 | priorityDesc | `String` | The description of this value. |
| 232 | privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 233 | productInterest | `String` | Preference Code. Part of the Primary Key. |
| 234 | profession | `String` | The profession of the Individual |
| 235 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 236 | profileId | `Float` | The primary key for this table. |
| 237 | profileType | `String` | The type of Profile. |
| 238 | propertyRegistered | `String` | Resort for which Job is registered. |
| 239 | protected | `String` | Protected |
| 240 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 241 | rateStructure | `String` | The default rate structure for this name. |
| 242 | region | `String` | The region for this name. |
| 243 | regionid | `String` | The region for this name. |
| 244 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 245 | repAccountsource | `String` | Reporting Accountsource |
| 246 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 247 | repCompetitionCode | `String` | Reporting Competition Code |
| 248 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 249 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 250 | repIndustryCode | `String` | Reporting Industry Code |
| 251 | repIndustryDescription | `String` | Reporting Industry Desc |
| 252 | repInfluence | `String` | Reporting Influence |
| 253 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 254 | repNameType | `String` | Reporting Name Type |
| 255 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 256 | repNationalityCode | `String` | Rep Nationality Code |
| 257 | repNationalityDescription | `String` | Rep Nationality Description |
| 258 | repPriorityDescription | `String` | Reporting Priority Desc |
| 259 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 260 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 261 | repScope | `String` | Reporting Scope |
| 262 | repScopeCity | `String` | Reporting Scope City |
| 263 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 264 | repScopeDescription | `String` | Reporting Scope Desc |
| 265 | repStateDescription | `String` | Reporting State Desc |
| 266 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 267 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 268 | repTitleName | `String` | Reporting Title Name |
| 269 | repeatGuestId | `String` | The primary membership # for this guest. |
| 270 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 271 | requestType | `String` | This column store the Name of the Company Profiles. |
| 272 | restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| 273 | restrictedRule | `String` | The description of this value. |
| 274 | resvContact | `String` | Reservation Contact person. |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomsPotential | `String` | Potential no of rooms per year for a account |
| 278 | roomsPotentialDesc | `String` | The description of this value. |
| 279 | sMSYN | `String` | Use this alert to text a notification. |
| 280 | salutation | `String` | Salutation Greeting |
| 281 | scope | `String` | Scope of the account |
| 282 | scopeCity | `String` | Scope City |
| 283 | scopeCityDesc | `String` | The description of this value. |
| 284 | scopeDesc | `String` | The description of this value. |
| 285 | searchName | `String` | The Uppercase value of Last or Company. |
| 286 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 287 | sfirst | `String` | Uppercase value of First Name. |
| 288 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 289 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 290 | srepCode | `String` | Used in QMS Module |
| 291 | state | `String` | The state of this address. |
| 292 | stateCode | `String` | State Code |
| 293 | stateDescription | `String` | Description of the state. |
| 294 | summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| 295 | summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| 296 | superSearchIndexText | `String` | Used in Oracle Text Index. |
| 297 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 298 | taxCategory | `String` | Tax Category |
| 299 | taxExemptStatus | `String` | Not used. |
| 300 | taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| 301 | taxID2 | `String` | Tax No |
| 302 | taxOffice | `String` | Tax Office Name |
| 303 | taxType | `String` | Tax Type |
| 304 | territory | `String` | TERRITORY of  a account |
| 305 | territoryDesc | `String` | The description of this value. |
| 306 | thirdPartyYN | `String` | Third Party YN |
| 307 | titleAlternate | `String` | Title Alternate |
| 308 | titleName | `String` | The description of this value. |
| 309 | titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| 310 | totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| 311 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 312 | traceCode | `String` | Code to Trace a record for all Triggered actions. |
| 313 | tracecodeDesc | `String` | Description |
| 314 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 315 | uDFC01 | `String` | User defined character field. |
| 316 | uDFC02 | `String` | User defined character field. |
| 317 | uDFC03 | `String` | User defined character field. |
| 318 | uDFC04 | `String` | User defined character field. |
| 319 | uDFC05 | `String` | User defined character field. |
| 320 | uDFC06 | `String` | User defined character field. |
| 321 | uDFC07 | `String` | User defined character field. |
| 322 | uDFC08 | `String` | User defined character field. |
| 323 | uDFC09 | `String` | User defined character field. |
| 324 | uDFC10 | `String` | User defined character field. |
| 325 | uDFC11 | `String` | User defined character field. |
| 326 | uDFC12 | `String` | User defined character field. |
| 327 | uDFC13 | `String` | User defined character field. |
| 328 | uDFC14 | `String` | User defined character field. |
| 329 | uDFC15 | `String` | User defined character field. |
| 330 | uDFC16 | `String` | User defined character field. |
| 331 | uDFC17 | `String` | User defined character field. |
| 332 | uDFC18 | `String` | User defined character field. |
| 333 | uDFC19 | `String` | User defined character field. |
| 334 | uDFC20 | `String` | User defined character field. |
| 335 | uDFC21 | `String` | User defined character field. |
| 336 | uDFC22 | `String` | User defined character field. |
| 337 | uDFC23 | `String` | User defined character field. |
| 338 | uDFC24 | `String` | User defined character field. |
| 339 | uDFC25 | `String` | User defined character field. |
| 340 | uDFC26 | `String` | User defined character field. |
| 341 | uDFC27 | `String` | User defined character field. |
| 342 | uDFC28 | `String` | User defined character field. |
| 343 | uDFC29 | `String` | User defined character field. |
| 344 | uDFC30 | `String` | User defined character field. |
| 345 | uDFC31 | `String` | User defined character field. |
| 346 | uDFC32 | `String` | User defined character field. |
| 347 | uDFC33 | `String` | User defined character field. |
| 348 | uDFC34 | `String` | User defined character field. |
| 349 | uDFC35 | `String` | User defined character field. |
| 350 | uDFC36 | `String` | User defined character field. |
| 351 | uDFC37 | `String` | User defined character field. |
| 352 | uDFC38 | `String` | User defined character field. |
| 353 | uDFC39 | `String` | User defined character field. |
| 354 | uDFC40 | `String` | User defined character field. |
| 355 | uDFD01 | `Date` | User defined date field. |
| 356 | uDFD02 | `Date` | User defined date field. |
| 357 | uDFD03 | `Date` | User defined date field. |
| 358 | uDFD04 | `Date` | User defined date field. |
| 359 | uDFD05 | `Date` | User defined date field. |
| 360 | uDFD06 | `Date` | User defined date field. |
| 361 | uDFD07 | `Date` | User defined date field. |
| 362 | uDFD08 | `Date` | User defined date field. |
| 363 | uDFD09 | `Date` | User defined date field. |
| 364 | uDFD10 | `Date` | User defined date field. |
| 365 | uDFD11 | `Date` | User defined date field. |
| 366 | uDFD12 | `Date` | User defined date field. |
| 367 | uDFD13 | `Date` | User defined date field. |
| 368 | uDFD14 | `Date` | User defined date field. |
| 369 | uDFD15 | `Date` | User defined date field. |
| 370 | uDFD16 | `Date` | User defined date field. |
| 371 | uDFD17 | `Date` | User defined date field. |
| 372 | uDFD18 | `Date` | User defined date field. |
| 373 | uDFD19 | `Date` | User defined date field. |
| 374 | uDFD20 | `Date` | User defined date field. |
| 375 | uDFN01 | `Float` | User defined number field. |
| 376 | uDFN02 | `Float` | User defined number field. |
| 377 | uDFN03 | `Float` | User defined number field. |
| 378 | uDFN04 | `Float` | User defined number field. |
| 379 | uDFN05 | `Float` | User defined number field. |
| 380 | uDFN06 | `Float` | User defined number field. |
| 381 | uDFN07 | `Float` | User defined number field. |
| 382 | uDFN08 | `Float` | User defined number field. |
| 383 | uDFN09 | `Float` | User defined number field. |
| 384 | uDFN10 | `Float` | User defined number field. |
| 385 | uDFN11 | `Float` | User defined number field. |
| 386 | uDFN12 | `Float` | User defined number field. |
| 387 | uDFN13 | `Float` | User defined number field. |
| 388 | uDFN14 | `Float` | User defined number field. |
| 389 | uDFN15 | `Float` | User defined number field. |
| 390 | uDFN16 | `Float` | User defined number field. |
| 391 | uDFN17 | `Float` | User defined number field. |
| 392 | uDFN18 | `Float` | User defined number field. |
| 393 | uDFN19 | `Float` | User defined number field. |
| 394 | uDFN20 | `Float` | User defined number field. |
| 395 | uDFN21 | `Float` | User defined number field. |
| 396 | uDFN22 | `Float` | User defined number field. |
| 397 | uDFN23 | `Float` | User defined number field. |
| 398 | uDFN24 | `Float` | User defined number field. |
| 399 | uDFN25 | `Float` | User defined number field. |
| 400 | uDFN26 | `Float` | User defined number field. |
| 401 | uDFN27 | `Float` | User defined number field. |
| 402 | uDFN28 | `Float` | User defined number field. |
| 403 | uDFN29 | `Float` | User defined number field. |
| 404 | uDFN30 | `Float` | User defined number field. |
| 405 | uDFN31 | `Float` | User defined number field. |
| 406 | uDFN32 | `Float` | User defined number field. |
| 407 | uDFN33 | `Float` | User defined number field. |
| 408 | uDFN34 | `Float` | User defined number field. |
| 409 | uDFN35 | `Float` | User defined number field. |
| 410 | uDFN36 | `Float` | User defined number field. |
| 411 | uDFN37 | `Float` | User defined number field. |
| 412 | uDFN38 | `Float` | User defined number field. |
| 413 | uDFN39 | `Float` | User defined number field. |
| 414 | uDFN40 | `Float` | User defined number field. |
| 415 | updateDate | `DateTime` | The date the record was modified |
| 416 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 417 | updateUser | `String` | The user that modified the record |
| 418 | uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| 419 | vIPCode | `String` | VIP Status of the Individual. |
| 420 | vIPDescription | `String` | The description of this value. |
| 421 | vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| 422 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 423 | vipAuthorization | `String` | Not Used. |
| 424 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 425 | xdisplayName | `String` | Xdisplay Name |
| 426 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyNationalityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralDescription | `String` | Central Description |
| 4 | centralNationalityCode | `String` | Central Nationality Code |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | locationID | `String` | Internal ID to uniquely identify the Property |
| 24 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 25 | nationalityid | `String` | Nationalityid |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | titleSuffix | `Float` | Title Suffix |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyRateCodeDetailsType

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

### StatisticsReservationsDailyRoomCategoryDetailsType

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

### StatisticsReservationsDailyCountryDetailsType

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

### StatisticsReservationsDailyChannelDetailsType

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

### StatisticsReservationsDailyRegionDetailsType

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

### StatisticsReservationsDailyRateSeasonDayDetailsType

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

### StatisticsReservationsDailyRoomDetailsType

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

### StatisticsReservationsDailyGuestStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | guestStatus | `String` | Used for Police/Tourist Export |
| 16 | gueststatusid | `String` | Gueststatusid |
| 17 | inactiveDate | `DateTime` | Inactive Date |
| 18 | inactiveflag | `String` | Inactive Flag |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | internalDeletedflag | `String` | Deleted Flag |
| 22 | internalEntityname | `String` | Entityname |
| 23 | jRNUpdateDate | `Date` | JRN Update Date |
| 24 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 25 | languageCode | `String` | Language Code |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | property | `String` | Property |
| 31 | ranking | `Float` | Ranking |
| 32 | repItem | `String` | Reporting Item |
| 33 | repItemName | `String` | Reporting Item Name |
| 34 | repItemOrderby | `Float` | Reporting Item Orderby |
| 35 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 36 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 37 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 38 | sequence | `Float` | Sequence |
| 39 | statustype | `Float` | Statustype |
| 40 | titleSuffix | `Float` | Title Suffix |
| 41 | updateDate | `DateTime` | Update Date |
| 42 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyProfileAccountsSourceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `Date` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | referenceCurrency | `String` | Reference Currency |
| 170 | repInfluence | `String` | Reporting Influence |
| 171 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 172 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 173 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 174 | repNationalityCode | `String` | Reporting Nationality Code |
| 175 | repNationalityDescription | `String` | Reporting Nationality Description |
| 176 | repStateDescription | `String` | Reporting State Desc |
| 177 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 178 | repTitleName | `String` | Reporting Title Name |
| 179 | repVIPName | `String` | Reporting Vip Name |
| 180 | repVIPStatus | `String` | Reporting Vip Status |
| 181 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 182 | resortRegistered | `String` | Resort for which Job is registered. |
| 183 | restricted | `String` | Restricted |
| 184 | restrictedRule | `String` | Restricted Rule |
| 185 | salutation | `String` | Salutation Greeting |
| 186 | scope | `String` | Scope |
| 187 | scopeCity | `String` | Scope City |
| 188 | scopeCityDecription | `String` | Scope City Decription |
| 189 | scopeDescription | `String` | Scope Description |
| 190 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 191 | sfirst | `String` | Uppercase value of First Name. |
| 192 | state | `String` | State |
| 193 | stateCode | `String` | State Code |
| 194 | stateDesc | `String` | State Description of the Guest of Payee |
| 195 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 196 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 197 | tax1No | `String` | Tax1 Number |
| 198 | tax2No | `String` | Tax2 Number |
| 199 | taxCategory | `String` | Tax Category |
| 200 | taxType | `String` | Tax Type |
| 201 | taxTypeDescription | `String` | Tax Type Description |
| 202 | territory | `String` | Territory |
| 203 | territoryDescription | `String` | Territory Description |
| 204 | thirdPartyYn | `String` | Third Party Y/N |
| 205 | traceCode | `String` | Trace Code |
| 206 | traceCodeDescription | `String` | Trace Code Description |
| 207 | uDFC01 | `String` | UDFC01 |
| 208 | uDFC02 | `String` | UDFC02 |
| 209 | uDFC03 | `String` | UDFC03 |
| 210 | uDFC04 | `String` | UDFC04 |
| 211 | uDFC05 | `String` | UDFC05 |
| 212 | uDFC06 | `String` | UDFC06 |
| 213 | uDFC07 | `String` | UDFC07 |
| 214 | uDFC08 | `String` | UDFC08 |
| 215 | uDFC09 | `String` | UDFC09 |
| 216 | uDFC10 | `String` | UDFC10 |
| 217 | uDFC11 | `String` | UDFC11 |
| 218 | uDFC12 | `String` | UDFC12 |
| 219 | uDFC13 | `String` | UDFC13 |
| 220 | uDFC14 | `String` | UDFC14 |
| 221 | uDFC15 | `String` | UDFC15 |
| 222 | uDFC16 | `String` | UDFC16 |
| 223 | uDFC17 | `String` | UDFC17 |
| 224 | uDFC18 | `String` | UDFC18 |
| 225 | uDFC19 | `String` | UDFC19 |
| 226 | uDFC20 | `String` | UDFC20 |
| 227 | uDFC21 | `String` | UDFC21 |
| 228 | uDFC22 | `String` | UDFC22 |
| 229 | uDFC23 | `String` | UDFC23 |
| 230 | uDFC24 | `String` | UDFC24 |
| 231 | uDFC25 | `String` | UDFC25 |
| 232 | uDFC26 | `String` | UDFC26 |
| 233 | uDFC27 | `String` | UDFC27 |
| 234 | uDFC28 | `String` | UDFC28 |
| 235 | uDFC29 | `String` | UDFC29 |
| 236 | uDFC30 | `String` | UDFC30 |
| 237 | uDFC31 | `String` | UDFC31 |
| 238 | uDFC32 | `String` | UDFC32 |
| 239 | uDFC33 | `String` | UDFC33 |
| 240 | uDFC34 | `String` | UDFC34 |
| 241 | uDFC35 | `String` | UDFC35 |
| 242 | uDFC36 | `String` | UDFC36 |
| 243 | uDFC37 | `String` | UDFC37 |
| 244 | uDFC38 | `String` | UDFC38 |
| 245 | uDFC39 | `String` | UDFC39 |
| 246 | uDFC40 | `String` | UDFC40 |
| 247 | uDFD01 | `Date` | UDFD01 |
| 248 | uDFD02 | `Date` | UDFD02 |
| 249 | uDFD03 | `Date` | UDFD03 |
| 250 | uDFD04 | `Date` | UDFD04 |
| 251 | uDFD05 | `Date` | UDFD05 |
| 252 | uDFD06 | `Date` | UDFD06 |
| 253 | uDFD07 | `Date` | UDFD07 |
| 254 | uDFD08 | `Date` | UDFD08 |
| 255 | uDFD09 | `Date` | UDFD09 |
| 256 | uDFD10 | `Date` | UDFD10 |
| 257 | uDFD11 | `Date` | UDFD11 |
| 258 | uDFD12 | `Date` | UDFD12 |
| 259 | uDFD13 | `Date` | UDFD13 |
| 260 | uDFD14 | `Date` | UDFD14 |
| 261 | uDFD15 | `Date` | UDFD15 |
| 262 | uDFD16 | `Date` | UDFD16 |
| 263 | uDFD17 | `Date` | UDFD17 |
| 264 | uDFD18 | `Date` | UDFD18 |
| 265 | uDFD19 | `Date` | UDFD19 |
| 266 | uDFD20 | `Date` | UDFD20 |
| 267 | uDFN01 | `Float` | UDFN01 |
| 268 | uDFN02 | `Float` | UDFN02 |
| 269 | uDFN03 | `Float` | UDFN03 |
| 270 | uDFN04 | `Float` | UDFN04 |
| 271 | uDFN05 | `Float` | UDFN05 |
| 272 | uDFN06 | `Float` | UDFN06 |
| 273 | uDFN07 | `Float` | UDFN07 |
| 274 | uDFN08 | `Float` | UDFN08 |
| 275 | uDFN09 | `Float` | UDFN09 |
| 276 | uDFN10 | `Float` | UDFN10 |
| 277 | uDFN11 | `Float` | UDFN11 |
| 278 | uDFN12 | `Float` | UDFN12 |
| 279 | uDFN13 | `Float` | UDFN13 |
| 280 | uDFN14 | `Float` | UDFN14 |
| 281 | uDFN15 | `Float` | UDFN15 |
| 282 | uDFN16 | `Float` | UDFN16 |
| 283 | uDFN17 | `Float` | UDFN17 |
| 284 | uDFN18 | `Float` | UDFN18 |
| 285 | uDFN19 | `Float` | UDFN19 |
| 286 | uDFN20 | `Float` | UDFN20 |
| 287 | uDFN21 | `Float` | UDFN21 |
| 288 | uDFN22 | `Float` | UDFN22 |
| 289 | uDFN23 | `Float` | UDFN23 |
| 290 | uDFN24 | `Float` | UDFN24 |
| 291 | uDFN25 | `Float` | UDFN25 |
| 292 | uDFN26 | `Float` | UDFN26 |
| 293 | uDFN27 | `Float` | UDFN27 |
| 294 | uDFN28 | `Float` | UDFN28 |
| 295 | uDFN29 | `Float` | UDFN29 |
| 296 | uDFN30 | `Float` | UDFN30 |
| 297 | uDFN31 | `Float` | UDFN31 |
| 298 | uDFN32 | `Float` | UDFN32 |
| 299 | uDFN33 | `Float` | UDFN33 |
| 300 | uDFN34 | `Float` | UDFN34 |
| 301 | uDFN35 | `Float` | UDFN35 |
| 302 | uDFN36 | `Float` | UDFN36 |
| 303 | uDFN37 | `Float` | UDFN37 |
| 304 | uDFN38 | `Float` | UDFN38 |
| 305 | uDFN39 | `Float` | UDFN39 |
| 306 | uDFN40 | `Float` | UDFN40 |
| 307 | updateDate | `DateTime` | Update Date |
| 308 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 309 | updateUser | `String` | Update User |
| 310 | vipName | `String` | VIP Name |
| 311 | vipStatus | `String` | VIP Status |
| 312 | xcompanyName | `String` | Extended Byte Company Name |
| 313 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 314 | xfirstName | `String` | Xfirst Name |
| 315 | xlastName | `String` | Xlast Name |
| 316 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyReservationStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `Date` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `Date` | Actual Check Out Date Time |
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
| 26 | arrivalDateTime | `Date` | Arrival Date Time |
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
| 53 | balance | `Float` | Balance on the account. |
| 54 | baseRateAmount | `Float` | Base Rate Amount |
| 55 | baseRateCode | `String` | Base Rate Code |
| 56 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 57 | basedOnRule | `String` | Based On Rule |
| 58 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 59 | beginCity | `String` | Begin City |
| 60 | beginDistrict | `String` | Begin District |
| 61 | beginState | `String` | Begin State |
| 62 | beginSystemDateTime | `Date` | Stores the actual guest check in date and time. |
| 63 | billNumber | `String` | Bill Number |
| 64 | billingContact | `String` | Billing Contact |
| 65 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 66 | billingContactId | `Float` | Billing Contact ID |
| 67 | billingContactName | `String` | Billing Contact Name |
| 68 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 69 | blockCode | `String` | Block Code |
| 70 | blockCreateDate | `Date` | Block Create Date |
| 71 | blockID | `Float` | Block ID |
| 72 | blockName | `String` | Block Name |
| 73 | blockResort | `String` | Property this block belongs to. |
| 74 | blockStatus | `String` | Block Status |
| 75 | bonusCheckId | `Float` | Bonus Check ID |
| 76 | bookedRoomCategory | `String` | Booked Room Category |
| 77 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 78 | businessDateCreated | `Date` | Business Date Created |
| 79 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 80 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 81 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 82 | cDiscountAmount | `Float` | C Discount Amount |
| 83 | cDiscountAmt | `Float` | C Discount Amt |
| 84 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 85 | cExchangeDate | `Date` | Central Xchange Date |
| 86 | cExchangeRate | `Float` | Central Xchange Rate |
| 87 | cFixedCharge | `Float` | Central Fixed Charge |
| 88 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 89 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 90 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 91 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 92 | cPackageAmount | `Float` | Central Pkg Amt |
| 93 | cPackageTax | `Float` | Central Pkg Tax |
| 94 | cRateAmount | `Float` | C Rate Amount |
| 95 | cRoomCost | `Float` | Central Room Cost |
| 96 | cRoomTax | `Float` | Central Room Tax |
| 97 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 98 | cUpsellCharge | `Float` | Central Upsell Charge |
| 99 | cancelDate | `Date` | Cancel Date |
| 100 | cancelReason | `String` | Cancel Reason |
| 101 | cancelTime | `String` | Cancel Time |
| 102 | cancellationDate | `Date` | Cancellation Date |
| 103 | cancellationNumber | `String` | Cancellation Number |
| 104 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 105 | cancellationreasonid | `String` | Cancellationreasonid |
| 106 | cancelledBy | `String` | The user who canceled this Reservation. |
| 107 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 108 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 109 | centralApprovalAmount | `Float` | Central Approval Amount |
| 110 | centralCancelReason | `String` | Central Cancel Reason |
| 111 | centralCommissionCode | `String` | Central Commission Code |
| 112 | centralCommissionDescription | `String` | Central Commission Description |
| 113 | centralCreditLimit | `Float` | Central Credit Limit |
| 114 | centralDiscountReason | `String` | Central Discount Reason |
| 115 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 116 | centralFBRevenue | `Float` | Central FB Revenue |
| 117 | centralGuestType | `String` | Central Guest Type |
| 118 | centralHurdle | `Float` | Central Hurdle |
| 119 | centralPackageCode | `String` | Central Package Code |
| 120 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 121 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 122 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 123 | centralPaymentAmount | `Float` | Central Payment Amount |
| 124 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 125 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 126 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 127 | centralPromotionDescription | `String` | Central Promotion Description |
| 128 | centralRateableValue | `Float` | Central Rateable Value |
| 129 | centralReservationType | `String` | Central Reservation Type |
| 130 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 131 | centralRoomRevenue | `Float` | Central Room Revenue |
| 132 | centralRoomTypeCode | `String` | Central Room Type Code |
| 133 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 134 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 135 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 136 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 137 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 138 | centralTaxType | `String` | Central Tax Type |
| 139 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 140 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 141 | centralTotalRevenue | `Float` | Central Total Revenue |
| 142 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 143 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 144 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 145 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 146 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 147 | channelDescription | `String` | Channel Description |
| 148 | channelOrderBy | `Float` | Channel Order By |
| 149 | channelid | `String` | Channelid |
| 150 | checkInInitiatedBy | `String` | Check In Initiated By |
| 151 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 152 | childBucket1 | `Float` | Child Bucket 1 |
| 153 | childBucket4 | `Float` | Child Bucket 4 |
| 154 | childBucket5 | `Float` | Child Bucket 5 |
| 155 | children | `Float` | Children |
| 156 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 157 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 158 | childrenAges | `String` | Children Ages |
| 159 | commissionCode | `String` | Commission Code |
| 160 | commissionDescription | `String` | Commission Description |
| 161 | commissionHoldCode | `String` | Commission Hold Code |
| 162 | commissionPaid | `Float` | Commission Paid |
| 163 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 164 | commissionableYN | `String` | Commissionable YN |
| 165 | commissionid | `String` | Commissionid |
| 166 | compTypeCode | `String` | Comp Type Code |
| 167 | companyCity | `String` | Company City |
| 168 | companyCountry | `String` | Company Country |
| 169 | companyID | `Float` | Company ID |
| 170 | companyName | `String` | Company Name |
| 171 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 172 | companyProfileID | `Float` | Company Profile ID |
| 173 | complimentaryYN | `String` | Complimentary YN |
| 174 | compreasonid | `String` | Compreasonid |
| 175 | computedResvStatus | `String` | Calculated reservation status. |
| 176 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 177 | consumerYn | `String` | Consumer Y/N |
| 178 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 179 | contactProfileID | `Float` | Contact Profile ID |
| 180 | contactProfileName | `String` | Contact Profile Name |
| 181 | createdBy | `String` | The name of the user who created the record. |
| 182 | createdByDefaultResort | `String` | Created By Default Property |
| 183 | createdDate | `Date` | Created Date |
| 184 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 185 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 186 | creditCardId | `Float` | Credit Card ID |
| 187 | creditLimit | `Float` | Credit Limit |
| 188 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 189 | cribs | `Float` | Cribs |
| 190 | currencyCode | `String` | Currency Code |
| 191 | customReferenceNumber | `String` | Custom Reference Number |
| 192 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 193 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 194 | deletedFlag | `String` | Deleted Flag |
| 195 | departtransportid | `String` | Departtransportid |
| 196 | departureComments | `String` | Departure Comments |
| 197 | departureDate | `Date` | Departure Date |
| 198 | departureDateTime | `Date` | Departure Date Time |
| 199 | departureTime | `String` | Departure Time |
| 200 | departureTransportCode | `String` | Departure Transport Code |
| 201 | departureTransportationYN | `String` | Departure Transportation YN |
| 202 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 203 | detatchedDate | `Date` | Detatched Date |
| 204 | detatchedYN | `String` | Detatched YN |
| 205 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 206 | directbillauthby | `Float` | Directbillauthby |
| 207 | discountAmount | `Float` | Discount Amount |
| 208 | discountAmt | `Float` | Discount Amount |
| 209 | discountPercent | `Float` | Discount Percentage. |
| 210 | discountPrcnt | `Float` | Discount Prcnt |
| 211 | discountReason | `String` | Discount Reason |
| 212 | discountReasonDescription | `String` | Discount Reason Description |
| 213 | discountreasonid | `String` | Discountreasonid |
| 214 | displayColor | `String` | Display Color |
| 215 | dmlSeqNumber | `Float` | Dml Sequence No |
| 216 | doNotMoveRoom | `String` | Do Not Move Room |
| 217 | doNotMoveYN | `String` | Do not move room flag. |
| 218 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 219 | dropOffDate | `Date` | Drop Off Date |
| 220 | dropOffStation | `String` | Drop Off Station |
| 221 | dropOffTime | `String` | Drop Off Time |
| 222 | dropOffType | `String` | Drop Off Type |
| 223 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 224 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 225 | effectiveRateAmount | `Float` | Not used. |
| 226 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 227 | emailAddress | `String` | Email Address |
| 228 | emailFolioYn | `String` | Email Folio Y/N |
| 229 | emailId | `Float` | Email ID |
| 230 | emailYn | `String` | Email Y/N |
| 231 | endCity | `String` | End City |
| 232 | endDistrict | `String` | End District |
| 233 | endState | `String` | End State |
| 234 | endbusinessdate | `Date` | Endbusinessdate |
| 235 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 236 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 237 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 238 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 239 | eventId | `Float` | Event ID |
| 240 | exchangePostingType | `String` | Exchange Posting Type |
| 241 | exchangeRate | `Float` | Exchange Rate |
| 242 | expectedTimeOfReturnETR | `Date` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 243 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 244 | extSegNo | `Float` | Not used |
| 245 | extSeqNumber | `Float` | Not used |
| 246 | extensionId | `Float` | Internal extension number for the main reservation |
| 247 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 248 | externalReference | `String` | External Reference |
| 249 | externalReferencesList | `String` | External References List |
| 250 | extraBeds | `Float` | Extra Beds |
| 251 | fBRevenue | `Float` | FB Revenue |
| 252 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 253 | faxId | `Float` | Fax ID |
| 254 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 255 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 256 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 257 | fixedCharge | `Float` | Not used. |
| 258 | fixedRateYN | `String` | Fixed Rate YN |
| 259 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 260 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 261 | folioNumber | `String` | Folio Number |
| 262 | folioText1 | `String` | Folio Text1 |
| 263 | folioText2 | `String` | Folio Text2 |
| 264 | foreignCurrencyID | `String` | Foreign Currency ID |
| 265 | freeChild | `Float` | Free Child |
| 266 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 267 | grossRateFuture | `Float` | Gross Rate Future |
| 268 | grossRatePast | `Float` | Gross Rate Past |
| 269 | groupName | `String` | Group Name |
| 270 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 271 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 272 | groupProfileClientID | `String` | Group Profile Client ID |
| 273 | groupProfileID | `Float` | Group Profile ID |
| 274 | groupProfileName | `String` | Group Profile Name |
| 275 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 276 | guaranteecodeid | `String` | Guaranteecodeid |
| 277 | guestFirstName | `String` | Guest First Name |
| 278 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 279 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 280 | guestSignature | `String` | Signature of the guest |
| 281 | guestStatus | `String` | Used for Police/Tourist Export |
| 282 | guestType | `String` | Guest Type |
| 283 | guestprofileid | `Float` | Guestprofileid |
| 284 | gueststatusid | `String` | Gueststatusid |
| 285 | guesttypeid | `String` | Guesttypeid |
| 286 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 287 | hurdle | `Float` | Hurdle |
| 288 | hurdleOverride | `String` | Hurdle Override |
| 289 | iDByMembershipClass | `String` | ID by Membership Class |
| 290 | iDByMembershipType | `String` | ID by Membership Type |
| 291 | individualCity | `String` | Guest Address. |
| 292 | individualCountry | `String` | Country of the guest |
| 293 | individualFirstName | `String` | Individual First Name |
| 294 | individualLastName | `String` | Individual Last Name |
| 295 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 296 | insertDate | `DateTime` | Insert Date |
| 297 | insertUser | `Float` | Insert User |
| 298 | intermediaryYn | `String` | Intermediary Y/N |
| 299 | internalAwardMembershipId | `Float` | Award Membership ID |
| 300 | internalBaseratecode | `String` | Baseratecode |
| 301 | internalBlockId | `Float` | Block ID. |
| 302 | internalCompanyprofileid | `Float` | Companyprofileid |
| 303 | internalGroupprofileid | `Float` | Groupprofileid |
| 304 | internalSourceprofileid | `Float` | Sourceprofileid |
| 305 | itemsQuantities | `String` | Items and Quantities |
| 306 | jRNUpdateDate | `Date` | JRN Update Date |
| 307 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 308 | keyValidUntil | `Date` | Key Valid Until |
| 309 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 310 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 311 | lastRoomNumber | `String` | Not used. |
| 312 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 313 | leadTimeDays | `Float` | Lead Time for ordering |
| 314 | lengthOfStay | `Float` | Length of Stay |
| 315 | linkedArrivalDate | `Date` | Linked Arrival Date |
| 316 | linkedDepartureDate | `Date` | Linked Departure Date |
| 317 | linkedRoomType | `String` | Linked Room Type |
| 318 | listOfMembershipID | `String` | Membership ID |
| 319 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 320 | locationID | `String` | Internal ID to uniquely identify the Property |
| 321 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 322 | mailYn | `String` | Mail Y/N |
| 323 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 324 | marketCode | `String` | Market Code |
| 325 | marketid | `String` | Marketid |
| 326 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 327 | mcGenBeginState | `String` | Mc Gen Begin State |
| 328 | mcGenEndDistrict | `String` | Mc Gen End District |
| 329 | mcGenEndState | `String` | Mc Gen End State |
| 330 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 331 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 332 | memberDescription | `String` | Member Description |
| 333 | memberLevel | `String` | Member Level |
| 334 | memberNumber | `String` | Member Number |
| 335 | membershipClass | `String` | Membership Class |
| 336 | membershipClassDescription | `String` | Membership Class Description |
| 337 | membershipCode | `String` | Membership Code |
| 338 | membershipId | `Float` | Membership ID |
| 339 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 340 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 341 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 342 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 343 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 344 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 345 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 346 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 347 | name | `String` | Name |
| 348 | nameUsageType | `String` | Name Usage Type |
| 349 | nextCountry | `String` | Next Country |
| 350 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 351 | numberOfRooms | `Float` | No of Rooms |
| 352 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 353 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 354 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 355 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 356 | originCode | `String` | Origin Code |
| 357 | originOfBooking | `String` | Origin Of Booking |
| 358 | originalBaseRate | `Float` | Not used. |
| 359 | originalEndDate | `Date` | Original End Date |
| 360 | originalStartDate | `Date` | Original Start Date |
| 361 | ownerFfFlag | `String` | Owner Ff Flag |
| 362 | packageCode | `String` | Package Code |
| 363 | packageCodeDescription | `String` | Package Code Description |
| 364 | packageForecastGroup | `String` | Package Forecast Group |
| 365 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 366 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 367 | parentreservationid | `Float` | Parentreservationid |
| 368 | partAllotment | `String` | Part Allotment |
| 369 | partyCode | `String` | Party Code |
| 370 | paxNo | `Float` | Pax Number |
| 371 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 372 | paymentMethod | `String` | Payment Method |
| 373 | paymentmethodid | `String` | Paymentmethodid |
| 374 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 375 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 376 | phoneId | `Float` | Phone ID |
| 377 | physicalQuantity | `Float` | Physical Quantity |
| 378 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 379 | pickUpDate | `Date` | Pick Up Date |
| 380 | pickUpStation | `String` | Pick Up Station |
| 381 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 382 | pickUpType | `String` | Pick Up Type |
| 383 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 384 | pickUpTime | `String` | Pick-Up Time |
| 385 | pickupRequiredYN | `String` | Pickup Required YN |
| 386 | points | `Float` | Points |
| 387 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 388 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 389 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 390 | postingAllowedYN | `String` | Posting Allowed YN |
| 391 | preArrReviewedDt | `Date` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 392 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 393 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 394 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 395 | preference | `String` | Preference |
| 396 | preferenceType | `String` | Preference Type |
| 397 | preferredRoomType | `String` | Preferred Room Type |
| 398 | previousCountry | `String` | Previous Country |
| 399 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 400 | primaryShare | `String` | Primary Share |
| 401 | printRateYN | `String` | Print Rate YN |
| 402 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 403 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 404 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 405 | promotionCode | `String` | Promotion Code |
| 406 | promotionDescription | `String` | Promotion Description |
| 407 | property | `String` | Indicates if the value set for the specific property. |
| 408 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 409 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 410 | purgeDate | `Date` | Purge Date |
| 411 | purposeOfStay | `String` | Purpose of stay. |
| 412 | quantity | `Float` | Number of Rooms |
| 413 | queuePriority | `Float` | Queue priority of the reservation. |
| 414 | queueWaitTime | `Float` | Queue Wait Time |
| 415 | quoteId | `String` | Quote ID provided by external system. |
| 416 | rateAmount | `Float` | Rate Amount |
| 417 | rateCode | `String` | Rate Code |
| 418 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 419 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 420 | rateableValue | `Float` | Stay rateable value. |
| 421 | ratecodeid | `String` | Ratecodeid |
| 422 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 423 | rdResvStatus | `String` | Rd Reservation Status |
| 424 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 425 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 426 | rdenReservationDate | `Date` | Rden Reservation Date |
| 427 | rdenResort | `String` | Rden Property |
| 428 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 429 | registrationCardNo | `String` | Registration Card Number |
| 430 | registrationNumber | `Float` | Registration Number |
| 431 | reinstateDate | `Date` | Reinstate Date |
| 432 | repChannel | `String` | Reporting Channel |
| 433 | repChannelDescription | `String` | Reporting Channel Description |
| 434 | reportId | `String` | Report ID |
| 435 | resInsertSource | `String` | Reservation Insert Source |
| 436 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 437 | reservationContactId | `Float` | Resv Contact ID |
| 438 | reservationDate | `Date` | Reservation Date |
| 439 | reservationNameID | `Float` | Reservation Name ID |
| 440 | reservationStatus | `String` | Reservation Status |
| 441 | reservationType | `String` | Reservation Type |
| 442 | reservationTypeDescription | `String` | Reservation Type Description |
| 443 | reservationid | `Float` | Reservationid |
| 444 | resort | `String` | Property |
| 445 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 446 | restrictionOverride | `String` | Restriction Override |
| 447 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 448 | resvNameid | `Float` | Reservation Nameid |
| 449 | resvNumber | `Float` | Not used in PMS currently. |
| 450 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 451 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 452 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 453 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 454 | rhRoomFeatures | `String` | Rh Room Features |
| 455 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 456 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 457 | room | `String` | Room |
| 458 | roomCategory | `String` | Room Category |
| 459 | roomClass | `String` | Room Class |
| 460 | roomCost | `Float` | Room Cost |
| 461 | roomInstructions | `String` | Room Instructions |
| 462 | roomResort | `String` | Meeting Room Property |
| 463 | roomRevenue | `Float` | Room Revenue |
| 464 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 465 | roomServiceTime | `String` | This is the Turndown room service time. |
| 466 | roomTypeDescription | `String` | Room Type Description |
| 467 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 468 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 469 | roomcategoryid | `String` | Roomcategoryid |
| 470 | roomid | `String` | Roomid |
| 471 | routingYN | `String` | Routing YN |
| 472 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 473 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 474 | sguestName | `String` | Sguest Name |
| 475 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 476 | shareId | `Float` | Share ID. |
| 477 | shareName | `String` | Share Name |
| 478 | sharePrcnt | `Float` | Not used. |
| 479 | shareSeqNumber | `Float` | Type of revenue |
| 480 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 481 | sharedConfirmationNo | `String` | Shared Confirmation Number |
| 482 | sharedGuestName | `String` | Shared Guest Name |
| 483 | sharedProfileID | `Float` | Shared Profile ID |
| 484 | sharedReservationStatus | `String` | Shared Reservation Status |
| 485 | sharingYN | `String` | Sharing YN |
| 486 | sourceCity | `String` | Source City |
| 487 | sourceCode | `String` | Source Code |
| 488 | sourceCountry | `String` | Source Country |
| 489 | sourceName | `String` | Source Name |
| 490 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 491 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 492 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 493 | sourceProfileID | `Float` | Source Profile ID |
| 494 | sourceProfileName | `String` | Source Profile Name |
| 495 | sourceid | `String` | Sourceid |
| 496 | specialRequest | `String` | Special Request |
| 497 | specialRequestDescription | `String` | Special Request Description |
| 498 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 499 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 500 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 501 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 502 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 503 | splitfromreservationid | `Float` | Splitfromreservationid |
| 504 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 505 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 506 | stayRecordId | `Float` | Stay Record ID |
| 507 | suiteNumber | `String` | Suite Number |
| 508 | superSearchIndexText | `String` | Super Search Index Text |
| 509 | taRecordLocator | `String` | Ta Record Locator |
| 510 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 511 | taxNumberOfStays | `Float` | Tax No of Stays |
| 512 | taxType | `String` | Tax Type |
| 513 | taxTypeDescription | `String` | Tax Type Description |
| 514 | taxtypeid | `String` | Taxtypeid |
| 515 | tiad | `String` | Tiad |
| 516 | ticketNos | `String` | Ticket Nos |
| 517 | totalCostOfStay | `Float` | Total Cost of Stay |
| 518 | totalRevenue | `Float` | Total Revenue |
| 519 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 520 | totalRoomRate | `Float` | Total Room Rate |
| 521 | trackItGroups | `String` | Track It Groups |
| 522 | trackItTypes | `String` | Track It Types |
| 523 | transactionid | `Float` | Transactionid |
| 524 | travelAgentCity | `String` | Travel Agent Address. |
| 525 | travelAgentCountry | `String` | Travel Agent Country |
| 526 | travelAgentID | `Float` | Travel Agent ID |
| 527 | travelAgentName | `String` | Travel Agent Name |
| 528 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 529 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 530 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 531 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 532 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 533 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 534 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 535 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 536 | uDFC01 | `String` | UDFC01 |
| 537 | uDFC02 | `String` | UDFC02 |
| 538 | uDFC03 | `String` | UDFC03 |
| 539 | uDFC04 | `String` | UDFC04 |
| 540 | uDFC05 | `String` | UDFC05 |
| 541 | uDFC06 | `String` | UDFC06 |
| 542 | uDFC07 | `String` | UDFC07 |
| 543 | uDFC08 | `String` | UDFC08 |
| 544 | uDFC09 | `String` | UDFC09 |
| 545 | uDFC10 | `String` | UDFC10 |
| 546 | uDFC11 | `String` | UDFC11 |
| 547 | uDFC12 | `String` | UDFC12 |
| 548 | uDFC13 | `String` | UDFC13 |
| 549 | uDFC14 | `String` | UDFC14 |
| 550 | uDFC15 | `String` | UDFC15 |
| 551 | uDFC16 | `String` | UDFC16 |
| 552 | uDFC17 | `String` | UDFC17 |
| 553 | uDFC18 | `String` | UDFC18 |
| 554 | uDFC19 | `String` | UDFC19 |
| 555 | uDFC20 | `String` | UDFC20 |
| 556 | uDFC21 | `String` | UDFC21 |
| 557 | uDFC22 | `String` | UDFC22 |
| 558 | uDFC23 | `String` | UDFC23 |
| 559 | uDFC24 | `String` | UDFC24 |
| 560 | uDFC25 | `String` | UDFC25 |
| 561 | uDFC26 | `String` | UDFC26 |
| 562 | uDFC27 | `String` | UDFC27 |
| 563 | uDFC28 | `String` | UDFC28 |
| 564 | uDFC29 | `String` | UDFC29 |
| 565 | uDFC30 | `String` | UDFC30 |
| 566 | uDFC31 | `String` | UDFC31 |
| 567 | uDFC32 | `String` | UDFC32 |
| 568 | uDFC33 | `String` | UDFC33 |
| 569 | uDFC34 | `String` | UDFC34 |
| 570 | uDFC35 | `String` | UDFC35 |
| 571 | uDFC36 | `String` | UDFC36 |
| 572 | uDFC37 | `String` | UDFC37 |
| 573 | uDFC38 | `String` | UDFC38 |
| 574 | uDFC39 | `String` | UDFC39 |
| 575 | uDFC40 | `String` | UDFC40 |
| 576 | uDFD01 | `Date` | UDFD01 |
| 577 | uDFD02 | `Date` | UDFD02 |
| 578 | uDFD03 | `Date` | UDFD03 |
| 579 | uDFD04 | `Date` | UDFD04 |
| 580 | uDFD05 | `Date` | UDFD05 |
| 581 | uDFD06 | `Date` | UDFD06 |
| 582 | uDFD07 | `Date` | UDFD07 |
| 583 | uDFD08 | `Date` | UDFD08 |
| 584 | uDFD09 | `Date` | UDFD09 |
| 585 | uDFD10 | `Date` | UDFD10 |
| 586 | uDFD11 | `Date` | UDFD11 |
| 587 | uDFD12 | `Date` | UDFD12 |
| 588 | uDFD13 | `Date` | UDFD13 |
| 589 | uDFD14 | `Date` | UDFD14 |
| 590 | uDFD15 | `Date` | UDFD15 |
| 591 | uDFD16 | `Date` | UDFD16 |
| 592 | uDFD17 | `Date` | UDFD17 |
| 593 | uDFD18 | `Date` | UDFD18 |
| 594 | uDFD19 | `Date` | UDFD19 |
| 595 | uDFD20 | `Date` | UDFD20 |
| 596 | uDFN01 | `Float` | UDFN01 |
| 597 | uDFN02 | `Float` | UDFN02 |
| 598 | uDFN03 | `Float` | UDFN03 |
| 599 | uDFN04 | `Float` | UDFN04 |
| 600 | uDFN05 | `Float` | UDFN05 |
| 601 | uDFN06 | `Float` | UDFN06 |
| 602 | uDFN07 | `Float` | UDFN07 |
| 603 | uDFN08 | `Float` | UDFN08 |
| 604 | uDFN09 | `Float` | UDFN09 |
| 605 | uDFN10 | `Float` | UDFN10 |
| 606 | uDFN11 | `Float` | UDFN11 |
| 607 | uDFN12 | `Float` | UDFN12 |
| 608 | uDFN13 | `Float` | UDFN13 |
| 609 | uDFN14 | `Float` | UDFN14 |
| 610 | uDFN15 | `Float` | UDFN15 |
| 611 | uDFN16 | `Float` | UDFN16 |
| 612 | uDFN17 | `Float` | UDFN17 |
| 613 | uDFN18 | `Float` | UDFN18 |
| 614 | uDFN19 | `Float` | UDFN19 |
| 615 | uDFN20 | `Float` | UDFN20 |
| 616 | uDFN21 | `Float` | UDFN21 |
| 617 | uDFN22 | `Float` | UDFN22 |
| 618 | uDFN23 | `Float` | UDFN23 |
| 619 | uDFN24 | `Float` | UDFN24 |
| 620 | uDFN25 | `Float` | UDFN25 |
| 621 | uDFN26 | `Float` | UDFN26 |
| 622 | uDFN27 | `Float` | UDFN27 |
| 623 | uDFN28 | `Float` | UDFN28 |
| 624 | uDFN29 | `Float` | UDFN29 |
| 625 | uDFN30 | `Float` | UDFN30 |
| 626 | uDFN31 | `Float` | UDFN31 |
| 627 | uDFN32 | `Float` | UDFN32 |
| 628 | uDFN33 | `Float` | UDFN33 |
| 629 | uDFN34 | `Float` | UDFN34 |
| 630 | uDFN35 | `Float` | UDFN35 |
| 631 | uDFN36 | `Float` | UDFN36 |
| 632 | uDFN37 | `Float` | UDFN37 |
| 633 | uDFN38 | `Float` | UDFN38 |
| 634 | uDFN39 | `Float` | UDFN39 |
| 635 | uDFN40 | `Float` | UDFN40 |
| 636 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 637 | updateDate | `DateTime` | Update Date |
| 638 | updateUser | `Float` | Update User |
| 639 | updatedBy | `String` | Updated By |
| 640 | updatedByDefaultResort | `String` | Updated By Default Property |
| 641 | updatedDate | `Date` | Updated Date |
| 642 | updatedTime | `String` | Updated Time |
| 643 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 644 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 645 | visaExpiryDate | `Date` | Visa Expiry Date |
| 646 | visaIssueDate | `Date` | Visa Issue Date |
| 647 | visaNumber | `String` | Visa Number |
| 648 | waitlistComment | `String` | Waitlist Comment |
| 649 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 650 | waitlistPriority | `String` | Waitlist Priority |
| 651 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 652 | waitlistReason | `String` | Waitlist Reason |
| 653 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 654 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 655 | waitlistreasonid | `String` | Waitlistreasonid |
| 656 | walkInYN | `String` | Walk-In YN |
| 657 | yieldableYn | `String` | Yieldable Y/N |
| 658 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyBookedRoomCategoryDetailsType

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
| 27 | chargedRoomTypeDescription | `String` | Charged Room Type Description |
| 28 | compiled | `String` | Has this room category's long and short description been compiled from the feature list? Y/N |
| 29 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 30 | defaultOccupancy | `Float` | Default occupancy for the room type |
| 31 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 32 | defaultRateDesc | `String` | Default Rate Description |
| 33 | defaultratecodeid | `String` | Defaultratecodeid |
| 34 | deletedFlag | `String` | Deleted Flag |
| 35 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 36 | genericYN | `String` | Generic YN |
| 37 | housekeeping | `String` | Room type shows in housekeeping Y/N |
| 38 | imageId | `Float` | Image ID |
| 39 | inactiveDate | `Date` | Inactive Date |
| 40 | inactiveflag | `String` | Inactive Flag |
| 41 | increments | `Float` | Increment value for rates by day by LOS. |
| 42 | initialRoundUp | `Float` | Initial round up value for rates by day by LOS. |
| 43 | insertDate | `DateTime` | Insert Date |
| 44 | insertUser | `Float` | Insert User |
| 45 | internalDeletedflag | `String` | Deleted Flag |
| 46 | jRNUpdateDate | `Date` | JRN Update Date |
| 47 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 48 | label | `String` | Label |
| 49 | locationID | `String` | Internal ID to uniquely identify the Property |
| 50 | longDescription | `String` | Long Description |
| 51 | maintenance | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| 52 | maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| 53 | maxRollaways | `Float` | Not used |
| 54 | maximumAdults | `Float` | The maximum occupancy of adults for this room category. |
| 55 | maximumChildren | `Float` | The maximum occupancy of children for this room category. |
| 56 | maximumOccupancy | `Float` | Maximum Occupancy |
| 57 | meetingRoomYN | `String` | Meeting Room YN |
| 58 | memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| 59 | minimumOccupancy | `Float` | Minimum Occupancy |
| 60 | numberOfRooms | `Float` | Number of Rooms |
| 61 | oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| 62 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 63 | ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| 64 | ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| 65 | ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| 66 | ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| 67 | ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| 68 | ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| 69 | ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| 70 | ownerroomflag | `String` | Ownerroomflag |
| 71 | physical | `String` | Physical |
| 72 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 73 | productClass | `String` | Product Class |
| 74 | property | `String` | Code to uniquely identify the Property |
| 75 | pseudoRoomType | `String` | Pseudo Room Type |
| 76 | pseudoRoomYN | `String` | Pseudo Room YN |
| 77 | rateAmount | `Float` | Rate Amount |
| 78 | rateCategory | `String` | Rate Category |
| 79 | rateCategoryDesc | `String` | Rate Category Description |
| 80 | rateCode | `String` | Rate Code |
| 81 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 82 | ratecategoryid | `String` | Ratecategoryid |
| 83 | repItem | `String` | Reporting Item |
| 84 | repItemName | `String` | Reporting Item Name |
| 85 | repItemOrderby | `Float` | Reporting Item Orderby |
| 86 | repOrderBy | `Float` | Reporting Order By |
| 87 | repRateCategory | `String` | Reporting Rate Category |
| 88 | repRateCategoryDescription | `String` | Reporting Rate Category Desc |
| 89 | repSmokingPrefDescription | `String` | Reporting Smoking Pref Desc |
| 90 | repUpdateDate | `Date` | Reporting Updatedate |
| 91 | replacesCategory | `String` | When room categories are renamed this flag indicates which room category this category replaces. |
| 92 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 93 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 94 | roomCategoryID | `String` | Room Category ID |
| 95 | roomCategoryPMSRef | `String` | Room Category PMS Ref |
| 96 | roomClass | `String` | Room Class |
| 97 | roomClassDescription | `String` | Room Class Description |
| 98 | roomInfoURL | `String` | URL where room information is stored. |
| 99 | roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| 100 | roomType | `String` | Room Type |
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

### StatisticsReservationsDailyCountryGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | comments | `String` | Comments |
| 8 | countryGroup | `String` | Country Group |
| 9 | countryGroupCode | `String` | Country Group Code |
| 10 | countrygroupid | `String` | Countrygroupid |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | displayColor | `String` | Display Color |
| 14 | entityName | `String` | Entity Name |
| 15 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 16 | inactiveDate | `DateTime` | Inactive Date |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | internalDeletedflag | `String` | Deleted Flag |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | languageCode | `String` | Language Code |
| 24 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | property | `String` | Property |
| 28 | ranking | `Float` | Ranking |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 34 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 35 | sequence | `Float` | Sequence |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyProfileAccountsTravelAgentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `Date` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | referenceCurrency | `String` | Reference Currency |
| 170 | repInfluence | `String` | Reporting Influence |
| 171 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 172 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 173 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 174 | repNationalityCode | `String` | Reporting Nationality Code |
| 175 | repNationalityDescription | `String` | Reporting Nationality Description |
| 176 | repStateDescription | `String` | Reporting State Desc |
| 177 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 178 | repTitleName | `String` | Reporting Title Name |
| 179 | repVIPName | `String` | Reporting Vip Name |
| 180 | repVIPStatus | `String` | Reporting Vip Status |
| 181 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 182 | resortRegistered | `String` | Resort for which Job is registered. |
| 183 | restricted | `String` | Restricted |
| 184 | restrictedRule | `String` | Restricted Rule |
| 185 | salutation | `String` | Salutation Greeting |
| 186 | scope | `String` | Scope |
| 187 | scopeCity | `String` | Scope City |
| 188 | scopeCityDecription | `String` | Scope City Decription |
| 189 | scopeDescription | `String` | Scope Description |
| 190 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 191 | sfirst | `String` | Uppercase value of First Name. |
| 192 | state | `String` | State |
| 193 | stateCode | `String` | State Code |
| 194 | stateDesc | `String` | State Description of the Guest of Payee |
| 195 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 196 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 197 | tax1No | `String` | Tax1 Number |
| 198 | tax2No | `String` | Tax2 Number |
| 199 | taxCategory | `String` | Tax Category |
| 200 | taxType | `String` | Tax Type |
| 201 | taxTypeDescription | `String` | Tax Type Description |
| 202 | territory | `String` | Territory |
| 203 | territoryDescription | `String` | Territory Description |
| 204 | thirdPartyYn | `String` | Third Party Y/N |
| 205 | traceCode | `String` | Trace Code |
| 206 | traceCodeDescription | `String` | Trace Code Description |
| 207 | uDFC01 | `String` | UDFC01 |
| 208 | uDFC02 | `String` | UDFC02 |
| 209 | uDFC03 | `String` | UDFC03 |
| 210 | uDFC04 | `String` | UDFC04 |
| 211 | uDFC05 | `String` | UDFC05 |
| 212 | uDFC06 | `String` | UDFC06 |
| 213 | uDFC07 | `String` | UDFC07 |
| 214 | uDFC08 | `String` | UDFC08 |
| 215 | uDFC09 | `String` | UDFC09 |
| 216 | uDFC10 | `String` | UDFC10 |
| 217 | uDFC11 | `String` | UDFC11 |
| 218 | uDFC12 | `String` | UDFC12 |
| 219 | uDFC13 | `String` | UDFC13 |
| 220 | uDFC14 | `String` | UDFC14 |
| 221 | uDFC15 | `String` | UDFC15 |
| 222 | uDFC16 | `String` | UDFC16 |
| 223 | uDFC17 | `String` | UDFC17 |
| 224 | uDFC18 | `String` | UDFC18 |
| 225 | uDFC19 | `String` | UDFC19 |
| 226 | uDFC20 | `String` | UDFC20 |
| 227 | uDFC21 | `String` | UDFC21 |
| 228 | uDFC22 | `String` | UDFC22 |
| 229 | uDFC23 | `String` | UDFC23 |
| 230 | uDFC24 | `String` | UDFC24 |
| 231 | uDFC25 | `String` | UDFC25 |
| 232 | uDFC26 | `String` | UDFC26 |
| 233 | uDFC27 | `String` | UDFC27 |
| 234 | uDFC28 | `String` | UDFC28 |
| 235 | uDFC29 | `String` | UDFC29 |
| 236 | uDFC30 | `String` | UDFC30 |
| 237 | uDFC31 | `String` | UDFC31 |
| 238 | uDFC32 | `String` | UDFC32 |
| 239 | uDFC33 | `String` | UDFC33 |
| 240 | uDFC34 | `String` | UDFC34 |
| 241 | uDFC35 | `String` | UDFC35 |
| 242 | uDFC36 | `String` | UDFC36 |
| 243 | uDFC37 | `String` | UDFC37 |
| 244 | uDFC38 | `String` | UDFC38 |
| 245 | uDFC39 | `String` | UDFC39 |
| 246 | uDFC40 | `String` | UDFC40 |
| 247 | uDFD01 | `Date` | UDFD01 |
| 248 | uDFD02 | `Date` | UDFD02 |
| 249 | uDFD03 | `Date` | UDFD03 |
| 250 | uDFD04 | `Date` | UDFD04 |
| 251 | uDFD05 | `Date` | UDFD05 |
| 252 | uDFD06 | `Date` | UDFD06 |
| 253 | uDFD07 | `Date` | UDFD07 |
| 254 | uDFD08 | `Date` | UDFD08 |
| 255 | uDFD09 | `Date` | UDFD09 |
| 256 | uDFD10 | `Date` | UDFD10 |
| 257 | uDFD11 | `Date` | UDFD11 |
| 258 | uDFD12 | `Date` | UDFD12 |
| 259 | uDFD13 | `Date` | UDFD13 |
| 260 | uDFD14 | `Date` | UDFD14 |
| 261 | uDFD15 | `Date` | UDFD15 |
| 262 | uDFD16 | `Date` | UDFD16 |
| 263 | uDFD17 | `Date` | UDFD17 |
| 264 | uDFD18 | `Date` | UDFD18 |
| 265 | uDFD19 | `Date` | UDFD19 |
| 266 | uDFD20 | `Date` | UDFD20 |
| 267 | uDFN01 | `Float` | UDFN01 |
| 268 | uDFN02 | `Float` | UDFN02 |
| 269 | uDFN03 | `Float` | UDFN03 |
| 270 | uDFN04 | `Float` | UDFN04 |
| 271 | uDFN05 | `Float` | UDFN05 |
| 272 | uDFN06 | `Float` | UDFN06 |
| 273 | uDFN07 | `Float` | UDFN07 |
| 274 | uDFN08 | `Float` | UDFN08 |
| 275 | uDFN09 | `Float` | UDFN09 |
| 276 | uDFN10 | `Float` | UDFN10 |
| 277 | uDFN11 | `Float` | UDFN11 |
| 278 | uDFN12 | `Float` | UDFN12 |
| 279 | uDFN13 | `Float` | UDFN13 |
| 280 | uDFN14 | `Float` | UDFN14 |
| 281 | uDFN15 | `Float` | UDFN15 |
| 282 | uDFN16 | `Float` | UDFN16 |
| 283 | uDFN17 | `Float` | UDFN17 |
| 284 | uDFN18 | `Float` | UDFN18 |
| 285 | uDFN19 | `Float` | UDFN19 |
| 286 | uDFN20 | `Float` | UDFN20 |
| 287 | uDFN21 | `Float` | UDFN21 |
| 288 | uDFN22 | `Float` | UDFN22 |
| 289 | uDFN23 | `Float` | UDFN23 |
| 290 | uDFN24 | `Float` | UDFN24 |
| 291 | uDFN25 | `Float` | UDFN25 |
| 292 | uDFN26 | `Float` | UDFN26 |
| 293 | uDFN27 | `Float` | UDFN27 |
| 294 | uDFN28 | `Float` | UDFN28 |
| 295 | uDFN29 | `Float` | UDFN29 |
| 296 | uDFN30 | `Float` | UDFN30 |
| 297 | uDFN31 | `Float` | UDFN31 |
| 298 | uDFN32 | `Float` | UDFN32 |
| 299 | uDFN33 | `Float` | UDFN33 |
| 300 | uDFN34 | `Float` | UDFN34 |
| 301 | uDFN35 | `Float` | UDFN35 |
| 302 | uDFN36 | `Float` | UDFN36 |
| 303 | uDFN37 | `Float` | UDFN37 |
| 304 | uDFN38 | `Float` | UDFN38 |
| 305 | uDFN39 | `Float` | UDFN39 |
| 306 | uDFN40 | `Float` | UDFN40 |
| 307 | updateDate | `DateTime` | Update Date |
| 308 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 309 | updateUser | `String` | Update User |
| 310 | vipName | `String` | VIP Name |
| 311 | vipStatus | `String` | VIP Status |
| 312 | xcompanyName | `String` | Extended Byte Company Name |
| 313 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 314 | xfirstName | `String` | Xfirst Name |
| 315 | xlastName | `String` | Xlast Name |
| 316 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyProfileAccountsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `DateTime` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 170 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 171 | referenceCurrency | `String` | Reference Currency |
| 172 | repInfluence | `String` | Reporting Influence |
| 173 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 174 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 175 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 176 | repNationalityCode | `String` | Reporting Nationality Code |
| 177 | repNationalityDescription | `String` | Reporting Nationality Description |
| 178 | repStateDescription | `String` | Reporting State Desc |
| 179 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 180 | repTitleName | `String` | Reporting Title Name |
| 181 | repVIPName | `String` | Reporting Vip Name |
| 182 | repVIPStatus | `String` | Reporting Vip Status |
| 183 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 184 | resortRegistered | `String` | Resort for which Job is registered. |
| 185 | restricted | `String` | Restricted |
| 186 | restrictedRule | `String` | Restricted Rule |
| 187 | salutation | `String` | Salutation Greeting |
| 188 | scope | `String` | Scope |
| 189 | scopeCity | `String` | Scope City |
| 190 | scopeCityDecription | `String` | Scope City Decription |
| 191 | scopeDescription | `String` | Scope Description |
| 192 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 193 | sfirst | `String` | Uppercase value of First Name. |
| 194 | state | `String` | State |
| 195 | stateCode | `String` | State Code |
| 196 | stateDesc | `String` | State Description of the Guest of Payee |
| 197 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 198 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 199 | tax1No | `String` | Tax1 Number |
| 200 | tax2No | `String` | Tax2 Number |
| 201 | taxCategory | `String` | Tax Category |
| 202 | taxType | `String` | Tax Type |
| 203 | taxTypeDescription | `String` | Tax Type Description |
| 204 | territory | `String` | Territory |
| 205 | territoryDescription | `String` | Territory Description |
| 206 | thirdPartyYn | `String` | Third Party Y/N |
| 207 | traceCode | `String` | Trace Code |
| 208 | traceCodeDescription | `String` | Trace Code Description |
| 209 | uDFC01 | `String` | UDFC01 |
| 210 | uDFC02 | `String` | UDFC02 |
| 211 | uDFC03 | `String` | UDFC03 |
| 212 | uDFC04 | `String` | UDFC04 |
| 213 | uDFC05 | `String` | UDFC05 |
| 214 | uDFC06 | `String` | UDFC06 |
| 215 | uDFC07 | `String` | UDFC07 |
| 216 | uDFC08 | `String` | UDFC08 |
| 217 | uDFC09 | `String` | UDFC09 |
| 218 | uDFC10 | `String` | UDFC10 |
| 219 | uDFC11 | `String` | UDFC11 |
| 220 | uDFC12 | `String` | UDFC12 |
| 221 | uDFC13 | `String` | UDFC13 |
| 222 | uDFC14 | `String` | UDFC14 |
| 223 | uDFC15 | `String` | UDFC15 |
| 224 | uDFC16 | `String` | UDFC16 |
| 225 | uDFC17 | `String` | UDFC17 |
| 226 | uDFC18 | `String` | UDFC18 |
| 227 | uDFC19 | `String` | UDFC19 |
| 228 | uDFC20 | `String` | UDFC20 |
| 229 | uDFC21 | `String` | UDFC21 |
| 230 | uDFC22 | `String` | UDFC22 |
| 231 | uDFC23 | `String` | UDFC23 |
| 232 | uDFC24 | `String` | UDFC24 |
| 233 | uDFC25 | `String` | UDFC25 |
| 234 | uDFC26 | `String` | UDFC26 |
| 235 | uDFC27 | `String` | UDFC27 |
| 236 | uDFC28 | `String` | UDFC28 |
| 237 | uDFC29 | `String` | UDFC29 |
| 238 | uDFC30 | `String` | UDFC30 |
| 239 | uDFC31 | `String` | UDFC31 |
| 240 | uDFC32 | `String` | UDFC32 |
| 241 | uDFC33 | `String` | UDFC33 |
| 242 | uDFC34 | `String` | UDFC34 |
| 243 | uDFC35 | `String` | UDFC35 |
| 244 | uDFC36 | `String` | UDFC36 |
| 245 | uDFC37 | `String` | UDFC37 |
| 246 | uDFC38 | `String` | UDFC38 |
| 247 | uDFC39 | `String` | UDFC39 |
| 248 | uDFC40 | `String` | UDFC40 |
| 249 | uDFD01 | `Date` | UDFD01 |
| 250 | uDFD02 | `Date` | UDFD02 |
| 251 | uDFD03 | `Date` | UDFD03 |
| 252 | uDFD04 | `Date` | UDFD04 |
| 253 | uDFD05 | `Date` | UDFD05 |
| 254 | uDFD06 | `Date` | UDFD06 |
| 255 | uDFD07 | `Date` | UDFD07 |
| 256 | uDFD08 | `Date` | UDFD08 |
| 257 | uDFD09 | `Date` | UDFD09 |
| 258 | uDFD10 | `Date` | UDFD10 |
| 259 | uDFD11 | `Date` | UDFD11 |
| 260 | uDFD12 | `Date` | UDFD12 |
| 261 | uDFD13 | `Date` | UDFD13 |
| 262 | uDFD14 | `Date` | UDFD14 |
| 263 | uDFD15 | `Date` | UDFD15 |
| 264 | uDFD16 | `Date` | UDFD16 |
| 265 | uDFD17 | `Date` | UDFD17 |
| 266 | uDFD18 | `Date` | UDFD18 |
| 267 | uDFD19 | `Date` | UDFD19 |
| 268 | uDFD20 | `Date` | UDFD20 |
| 269 | uDFN01 | `Float` | UDFN01 |
| 270 | uDFN02 | `Float` | UDFN02 |
| 271 | uDFN03 | `Float` | UDFN03 |
| 272 | uDFN04 | `Float` | UDFN04 |
| 273 | uDFN05 | `Float` | UDFN05 |
| 274 | uDFN06 | `Float` | UDFN06 |
| 275 | uDFN07 | `Float` | UDFN07 |
| 276 | uDFN08 | `Float` | UDFN08 |
| 277 | uDFN09 | `Float` | UDFN09 |
| 278 | uDFN10 | `Float` | UDFN10 |
| 279 | uDFN11 | `Float` | UDFN11 |
| 280 | uDFN12 | `Float` | UDFN12 |
| 281 | uDFN13 | `Float` | UDFN13 |
| 282 | uDFN14 | `Float` | UDFN14 |
| 283 | uDFN15 | `Float` | UDFN15 |
| 284 | uDFN16 | `Float` | UDFN16 |
| 285 | uDFN17 | `Float` | UDFN17 |
| 286 | uDFN18 | `Float` | UDFN18 |
| 287 | uDFN19 | `Float` | UDFN19 |
| 288 | uDFN20 | `Float` | UDFN20 |
| 289 | uDFN21 | `Float` | UDFN21 |
| 290 | uDFN22 | `Float` | UDFN22 |
| 291 | uDFN23 | `Float` | UDFN23 |
| 292 | uDFN24 | `Float` | UDFN24 |
| 293 | uDFN25 | `Float` | UDFN25 |
| 294 | uDFN26 | `Float` | UDFN26 |
| 295 | uDFN27 | `Float` | UDFN27 |
| 296 | uDFN28 | `Float` | UDFN28 |
| 297 | uDFN29 | `Float` | UDFN29 |
| 298 | uDFN30 | `Float` | UDFN30 |
| 299 | uDFN31 | `Float` | UDFN31 |
| 300 | uDFN32 | `Float` | UDFN32 |
| 301 | uDFN33 | `Float` | UDFN33 |
| 302 | uDFN34 | `Float` | UDFN34 |
| 303 | uDFN35 | `Float` | UDFN35 |
| 304 | uDFN36 | `Float` | UDFN36 |
| 305 | uDFN37 | `Float` | UDFN37 |
| 306 | uDFN38 | `Float` | UDFN38 |
| 307 | uDFN39 | `Float` | UDFN39 |
| 308 | uDFN40 | `Float` | UDFN40 |
| 309 | updateDate | `DateTime` | Update Date |
| 310 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 311 | updateUser | `String` | Update User |
| 312 | vipName | `String` | VIP Name |
| 313 | vipStatus | `String` | VIP Status |
| 314 | xcompanyName | `String` | Extended Byte Company Name |
| 315 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 316 | xfirstName | `String` | Xfirst Name |
| 317 | xlastName | `String` | Xlast Name |
| 318 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyStateDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | country | `String` | Country |
| 4 | countryid | `String` | Countryid |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedflag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveflag | `String` | Inactive Flag |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | repDescription | `String` | Reporting Description |
| 17 | repItem | `String` | Reporting Item |
| 18 | repItemName | `String` | Reporting Item Name |
| 19 | repItemOrderby | `Float` | Reporting Item Orderby |
| 20 | repOrderBy | `Float` | Reporting Order By |
| 21 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 22 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 23 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 24 | sequence | `Float` | Sequence |
| 25 | stateCode | `String` | State Code |
| 26 | stateid | `String` | Stateid |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRNumberCentral | `String` | AR Number (Central) |
| 3 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 4 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 5 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 6 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 7 | accountBillingContact | `String` | Billing contact person in company. |
| 8 | accountSource | `String` | Account Source |
| 9 | accountType | `String` | Account Type |
| 10 | activeYN | `String` | Active YN |
| 11 | address1 | `String` | Address 1 |
| 12 | address2 | `String` | Address 2 |
| 13 | address3 | `String` | Address 3 |
| 14 | address4 | `String` | Address 4 |
| 15 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 16 | allOwnerCodes | `String` | All Owner Codes |
| 17 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 18 | alternateSalutation | `String` | Alternate Salutation |
| 19 | alternateTitle | `String` | Alternate Title |
| 20 | autoPopRouting | `String` | Auto Pop Routing |
| 21 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 22 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 23 | billingCode | `String` | The billing code for this name record. |
| 24 | billingInstruction | `String` | Billing Instruction |
| 25 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 26 | birthCountry | `String` | Country of birth. |
| 27 | birthDate | `Date` | Birth Date |
| 28 | birthDateStr | `String` | Birth Date Str |
| 29 | birthPlace | `String` | Place of birth. |
| 30 | blMsg | `String` | Bl Msg |
| 31 | businessTitle | `String` | Business Title |
| 32 | cExchangeDate | `Date` | Central Xchange Date |
| 33 | cExchangeRate | `Float` | Central Xchange Rate |
| 34 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 35 | cRSNameid | `Float` | The unique identifier of the CRS |
| 36 | cashBlInd | `String` | Cash Bl Individual |
| 37 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 38 | centralAccountType | `String` | Central Account Type |
| 39 | centralDefaultKeyword | `String` | Central Default Keyword |
| 40 | centralNationality | `String` | Central Nationality |
| 41 | centralNationalityCode | `String` | Central Nationality Code |
| 42 | centralPriority | `String` | Central Priority |
| 43 | centralStateCode | `String` | Central State Code |
| 44 | centralTerritory | `String` | Central Territory |
| 45 | chainCode | `String` | Chain Code |
| 46 | city | `String` | City |
| 47 | clientID | `String` | Client ID |
| 48 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 49 | combinedName | `String` | Combined Name |
| 50 | commissionCode | `String` | Commission Code |
| 51 | communicationType1 | `String` | Communication Type 1 |
| 52 | communicationType2 | `String` | Communication Type 2 |
| 53 | communicationType3 | `String` | Communication Type 3 |
| 54 | communicationValue1 | `String` | Communication Value 1 |
| 55 | communicationValue2 | `String` | Communication Value 2 |
| 56 | communicationValue3 | `String` | Communication Value 3 |
| 57 | companyAlternate | `String` | Extended Byte Company Name |
| 58 | companyGroupId | `String` | Linked internal ID for booker. |
| 59 | companyNameId | `Float` | Company Name ID |
| 60 | competition | `String` | Competition |
| 61 | contractNo | `String` | Contract Number (used for customers). |
| 62 | contractRecvDate | `Date` | The date the group contract was received. |
| 63 | country | `String` | Country |
| 64 | countryCode | `String` | Country Code |
| 65 | creditCardName | `String` | Credit Card Name |
| 66 | creditCardType | `String` | Credit Card Type |
| 67 | creditRating | `String` | Credit Rating |
| 68 | currencyCode | `String` | Currency Code |
| 69 | currencyDescription | `String` | Currency Description |
| 70 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 71 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 72 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 73 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 74 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 75 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 76 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 77 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 78 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 79 | defaultKeyword | `String` | Default Keyword |
| 80 | deletedFlag | `String` | Deleted Flag |
| 81 | department | `String` | Department |
| 82 | deptId | `String` | Dept ID |
| 83 | description | `String` | Description |
| 84 | directBillBatchType | `String` | Direct Bill Batch Type |
| 85 | downloadDate | `Date` | Download Date |
| 86 | downloadResort | `String` | Download Property |
| 87 | downloadSrep | `Float` | Download Srep |
| 88 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 89 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 90 | email | `String` | Email |
| 91 | emailYn | `String` | Email Y/N |
| 92 | envelopeGreeting | `String` | Envelope Greeting |
| 93 | externalId | `String` | External ID |
| 94 | externalReferenceRequ | `String` | Not Used. |
| 95 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 96 | fMembershipCardNumbers | `String` | F Membership Card Numbers |
| 97 | fMembershipClassDesc | `String` | F Membership Class Description |
| 98 | fMembershipClasses | `String` | F Membership Classes |
| 99 | fMembershipCodes | `String` | F Membership Codes |
| 100 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 101 | fMembershipIds | `String` | F Membership Ids |
| 102 | fSubscriptionDb | `String` | F Subscription Db |
| 103 | fSubscriptionYn | `String` | F Subscription Y/N |
| 104 | faxNumber | `String` | Fax Number |
| 105 | first | `String` | First |
| 106 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 107 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 108 | gDSTransactionNo | `String` | Not used. |
| 109 | gender | `String` | Gender |
| 110 | geographicRegion | `String` | Not used. |
| 111 | groupProfileName | `String` | Group Profile Name |
| 112 | guestClassification | `String` | Not used. |
| 113 | guestPrivYn | `String` | Guest Priv Y/N |
| 114 | historyYN | `String` | History YN |
| 115 | holdCode | `String` | Hold Code |
| 116 | iataCompType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 117 | iataConsortia | `String` | IATA Consortia |
| 118 | idCountry | `String` | ID Country |
| 119 | idDate | `Date` | ID Date |
| 120 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 121 | idNumber | `String` | ID Number |
| 122 | idPlace | `String` | ID Place |
| 123 | idType | `String` | ID Type |
| 124 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 125 | inactiveDate | `DateTime` | Inactive Date |
| 126 | inactiveFlag | `String` | Inactive Flag |
| 127 | inactiveReason | `String` | Reason why record was inactivated. |
| 128 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 129 | incognitoFirstName | `String` | Incognito First Name |
| 130 | incognitoLastName | `String` | Incognito Last Name |
| 131 | indexName | `String` | Index Name |
| 132 | industryCode | `String` | Industry Code |
| 133 | influence | `String` | Influence |
| 134 | insertDate | `DateTime` | Insert Date |
| 135 | insertUser | `String` | Insert User |
| 136 | interest | `String` | Interest Code. |
| 137 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 138 | internalDeletedflag | `String` | Deleted Flag |
| 139 | internalInactiveflag | `String` | Inactive Flag |
| 140 | internalOrganizationId | `Float` | Organization ID |
| 141 | internalProfileId | `Float` | Profile ID |
| 142 | jRNUpdateDate | `Date` | JRN Update Date |
| 143 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 144 | language | `String` | Language |
| 145 | languageCode | `String` | Language Code |
| 146 | laptopChange | `Float` | Laptop Change |
| 147 | last | `String` | Last |
| 148 | lastGroup | `String` | Last Group |
| 149 | lastRate | `Float` | Last Rate |
| 150 | lastRoom | `String` | Not used. |
| 151 | lastSource | `String` | Last Source |
| 152 | lastStay | `Date` | Last Stay |
| 153 | lastUpdatedResort | `String` | Last property that updated this record. |
| 154 | legalCompany | `String` | Legal Company |
| 155 | letterGreeting | `String` | Letter Greeting |
| 156 | mailListYN | `String` | Mail List YN |
| 157 | mailType | `String` | The type of mail this user should be sent. |
| 158 | mailYn | `String` | Mail Y/N |
| 159 | mailingActionCode | `String` | Mailing Action Code |
| 160 | marketResearchYn | `String` | Market Research Y/N |
| 161 | markets | `String` | Markets |
| 162 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 163 | middle | `String` | Middle |
| 164 | nameComment | `String` | Not Used. |
| 165 | nameTaxType | `String` | Name Tax Type |
| 166 | nameWithTitle | `String` | Name With Title |
| 167 | name2 | `String` | Name2 |
| 168 | name3 | `String` | Name3 |
| 169 | nationality | `String` | Nationality |
| 170 | nationalityCode | `String` | Nationality Code |
| 171 | negotiatedRateCodes | `String` | Negotiated Rate Codes |
| 172 | nextStay | `Date` | Next Stay |
| 173 | nickname | `String` | The nickname of this individual. |
| 174 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 175 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 176 | passport | `String` | Passport |
| 177 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 178 | paymentMethodsCode | `String` | Payment Methods Code |
| 179 | paymentMethodsDesc | `String` | Payment Methods Description |
| 180 | phoneNumber | `String` | Phone no. |
| 181 | phoneYn | `String` | Phone Y/N |
| 182 | postalCode | `String` | Postal Code |
| 183 | preferredRoomNo | `String` | Preferred Room Number |
| 184 | primaryAddressId | `Float` | Not used. |
| 185 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 186 | primaryNameId | `Float` | Not Used. |
| 187 | primaryOwner | `String` | Primary Owner |
| 188 | primaryOwnerCode | `String` | Primary Owner Code |
| 189 | primaryPhoneId | `Float` | Not used. |
| 190 | priority | `String` | Priority |
| 191 | privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 192 | productInterest | `String` | Product Interest |
| 193 | profession | `String` | Profession of the guest |
| 194 | profileArrCodes | `String` | Profile Arrangement Codes |
| 195 | profileArrangementDesc | `String` | Profile Arr Description |
| 196 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 197 | profileID | `Float` | Profile ID |
| 198 | profileType | `String` | Profile Type |
| 199 | propertyRegistered | `String` | Resort for which Job is registered. |
| 200 | protected | `String` | Protected |
| 201 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 202 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 203 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 204 | rateStructure | `String` | The default rate structure for this name. |
| 205 | region | `String` | Region |
| 206 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 207 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 208 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 209 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 210 | repIATACompType | `String` | Reporting Iata Comp Type |
| 211 | repInactiveReason | `String` | Reporting Inactive Reason |
| 212 | repInactiveReasonCode | `String` | Reporting Inactive Reason Code |
| 213 | repIndustryDescription | `String` | Reporting Industry Desc |
| 214 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 215 | repMailActionDescription | `String` | Reporting Mail Action Desc |
| 216 | repMarketsDescription | `String` | Reporting Markets Desc |
| 217 | repNameType | `String` | Reporting Name Type |
| 218 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 219 | repPriorityDescription | `String` | Reporting Priority Desc |
| 220 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 221 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 222 | repScopeDescription | `String` | Reporting Scope Desc |
| 223 | repStateDescription | `String` | Reporting State Desc |
| 224 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 225 | repTitle | `String` | Reporting Title |
| 226 | repTitleName | `String` | Reporting Title Name |
| 227 | repVIPName | `String` | Reporting Vip Name |
| 228 | repVIPStatus | `String` | Reporting Vip Status |
| 229 | repeatGuestId | `String` | The primary membership # for this guest. |
| 230 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 231 | resvContact | `String` | Reservation Contact person. |
| 232 | roomsPotential | `String` | Rooms Potential |
| 233 | salutation | `String` | Salutation Greeting |
| 234 | scope | `String` | Scope |
| 235 | scopeCity | `String` | Scope City |
| 236 | searchName | `String` | The Uppercase value of Last or Company. |
| 237 | searchNameAlternate | `String` | Search Name Alternate |
| 238 | sfirst | `String` | Uppercase value of First Name. |
| 239 | smsYn | `String` | Use this alert to text a notification. |
| 240 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 241 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 242 | srepCode | `String` | Srep Code |
| 243 | state | `String` | State |
| 244 | stateCode | `String` | State Code |
| 245 | suffix | `String` | Suffix |
| 246 | summRefCc | `String` | Summ Ref Cc |
| 247 | superSearchIndexText | `String` | Super Search Index Text |
| 248 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 249 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 250 | taxCategory | `String` | Tax Category |
| 251 | taxExemptStatus | `String` | Not used. |
| 252 | taxID1 | `String` | Tax ID 1 |
| 253 | taxID2 | `String` | Tax ID 2 |
| 254 | taxOffice | `String` | Tax Office Name |
| 255 | taxType | `String` | Tax Type |
| 256 | territory | `String` | Territory |
| 257 | thirdPartyYn | `String` | Third Party Y/N |
| 258 | title | `String` | Title |
| 259 | titleSuffix | `Float` | Title Suffix |
| 260 | totalArrivals | `Float` | Total Arrivals |
| 261 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 262 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 263 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 264 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 265 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 266 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 267 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 268 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 269 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 270 | totalFbRevenue | `Float` | Total FB Revenue |
| 271 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 272 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 273 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 274 | totalNonRevenue | `Float` | Total Non Revenue |
| 275 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 276 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 277 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 278 | totalOtherRevenue | `Float` | Total Other Revenue |
| 279 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 280 | totalReservationNights | `Float` | Total Reservation Nights |
| 281 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 282 | totalRevenue | `Float` | Total Revenue |
| 283 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 284 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 285 | totalRoomRevenue | `Float` | Total Room Revenue |
| 286 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 287 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 288 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 289 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 290 | traceCode | `String` | Trace Code |
| 291 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 292 | uDFC01 | `String` | UDFC01 |
| 293 | uDFC02 | `String` | UDFC02 |
| 294 | uDFC03 | `String` | UDFC03 |
| 295 | uDFC04 | `String` | UDFC04 |
| 296 | uDFC05 | `String` | UDFC05 |
| 297 | uDFC06 | `String` | UDFC06 |
| 298 | uDFC07 | `String` | UDFC07 |
| 299 | uDFC08 | `String` | UDFC08 |
| 300 | uDFC09 | `String` | UDFC09 |
| 301 | uDFC10 | `String` | UDFC10 |
| 302 | uDFC11 | `String` | UDFC11 |
| 303 | uDFC12 | `String` | UDFC12 |
| 304 | uDFC13 | `String` | UDFC13 |
| 305 | uDFC14 | `String` | UDFC14 |
| 306 | uDFC15 | `String` | UDFC15 |
| 307 | uDFC16 | `String` | UDFC16 |
| 308 | uDFC17 | `String` | UDFC17 |
| 309 | uDFC18 | `String` | UDFC18 |
| 310 | uDFC19 | `String` | UDFC19 |
| 311 | uDFC20 | `String` | UDFC20 |
| 312 | uDFC21 | `String` | UDFC21 |
| 313 | uDFC22 | `String` | UDFC22 |
| 314 | uDFC23 | `String` | UDFC23 |
| 315 | uDFC24 | `String` | UDFC24 |
| 316 | uDFC25 | `String` | UDFC25 |
| 317 | uDFC26 | `String` | UDFC26 |
| 318 | uDFC27 | `String` | UDFC27 |
| 319 | uDFC28 | `String` | UDFC28 |
| 320 | uDFC29 | `String` | UDFC29 |
| 321 | uDFC30 | `String` | UDFC30 |
| 322 | uDFC31 | `String` | UDFC31 |
| 323 | uDFC32 | `String` | UDFC32 |
| 324 | uDFC33 | `String` | UDFC33 |
| 325 | uDFC34 | `String` | UDFC34 |
| 326 | uDFC35 | `String` | UDFC35 |
| 327 | uDFC36 | `String` | UDFC36 |
| 328 | uDFC37 | `String` | UDFC37 |
| 329 | uDFC38 | `String` | UDFC38 |
| 330 | uDFC39 | `String` | UDFC39 |
| 331 | uDFC40 | `String` | UDFC40 |
| 332 | uDFD01 | `Date` | UDFD01 |
| 333 | uDFD02 | `Date` | UDFD02 |
| 334 | uDFD03 | `Date` | UDFD03 |
| 335 | uDFD04 | `Date` | UDFD04 |
| 336 | uDFD05 | `Date` | UDFD05 |
| 337 | uDFD06 | `Date` | UDFD06 |
| 338 | uDFD07 | `Date` | UDFD07 |
| 339 | uDFD08 | `Date` | UDFD08 |
| 340 | uDFD09 | `Date` | UDFD09 |
| 341 | uDFD10 | `Date` | UDFD10 |
| 342 | uDFD11 | `Date` | UDFD11 |
| 343 | uDFD12 | `Date` | UDFD12 |
| 344 | uDFD13 | `Date` | UDFD13 |
| 345 | uDFD14 | `Date` | UDFD14 |
| 346 | uDFD15 | `Date` | UDFD15 |
| 347 | uDFD16 | `Date` | UDFD16 |
| 348 | uDFD17 | `Date` | UDFD17 |
| 349 | uDFD18 | `Date` | UDFD18 |
| 350 | uDFD19 | `Date` | UDFD19 |
| 351 | uDFD20 | `Date` | UDFD20 |
| 352 | uDFN01 | `Float` | UDFN01 |
| 353 | uDFN02 | `Float` | UDFN02 |
| 354 | uDFN03 | `Float` | UDFN03 |
| 355 | uDFN04 | `Float` | UDFN04 |
| 356 | uDFN05 | `Float` | UDFN05 |
| 357 | uDFN06 | `Float` | UDFN06 |
| 358 | uDFN07 | `Float` | UDFN07 |
| 359 | uDFN08 | `Float` | UDFN08 |
| 360 | uDFN09 | `Float` | UDFN09 |
| 361 | uDFN10 | `Float` | UDFN10 |
| 362 | uDFN11 | `Float` | UDFN11 |
| 363 | uDFN12 | `Float` | UDFN12 |
| 364 | uDFN13 | `Float` | UDFN13 |
| 365 | uDFN14 | `Float` | UDFN14 |
| 366 | uDFN15 | `Float` | UDFN15 |
| 367 | uDFN16 | `Float` | UDFN16 |
| 368 | uDFN17 | `Float` | UDFN17 |
| 369 | uDFN18 | `Float` | UDFN18 |
| 370 | uDFN19 | `Float` | UDFN19 |
| 371 | uDFN20 | `Float` | UDFN20 |
| 372 | uDFN21 | `Float` | UDFN21 |
| 373 | uDFN22 | `Float` | UDFN22 |
| 374 | uDFN23 | `Float` | UDFN23 |
| 375 | uDFN24 | `Float` | UDFN24 |
| 376 | uDFN25 | `Float` | UDFN25 |
| 377 | uDFN26 | `Float` | UDFN26 |
| 378 | uDFN27 | `Float` | UDFN27 |
| 379 | uDFN28 | `Float` | UDFN28 |
| 380 | uDFN29 | `Float` | UDFN29 |
| 381 | uDFN30 | `Float` | UDFN30 |
| 382 | uDFN31 | `Float` | UDFN31 |
| 383 | uDFN32 | `Float` | UDFN32 |
| 384 | uDFN33 | `Float` | UDFN33 |
| 385 | uDFN34 | `Float` | UDFN34 |
| 386 | uDFN35 | `Float` | UDFN35 |
| 387 | uDFN36 | `Float` | UDFN36 |
| 388 | uDFN37 | `Float` | UDFN37 |
| 389 | uDFN38 | `Float` | UDFN38 |
| 390 | uDFN39 | `Float` | UDFN39 |
| 391 | uDFN40 | `Float` | UDFN40 |
| 392 | updateDate | `DateTime` | Update Date |
| 393 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 394 | updateUser | `String` | Update User |
| 395 | uploadDate | `Date` | Upload Date |
| 396 | vendorId | `Float` | Vendor ID |
| 397 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 398 | vipAuthorization | `String` | Not Used. |
| 399 | vipName | `String` | VIP Name |
| 400 | vipStatus | `String` | VIP Status |
| 401 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 402 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 403 | xfirstName | `String` | Xfirst Name |
| 404 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyCityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attributeCode | `String` | Attribute Code |
| 2 | businessTitle | `String` | Business Title |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | chainCode | `String` | Chain Code |
| 5 | cityid | `String` | Cityid |
| 6 | comments | `String` | Comments |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | description | `String` | Description |
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
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
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

### StatisticsReservationsDailyPromotionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | authorizerId | `Float` | Authorizer ID |
| 2 | bookingEndDate | `Date` | Last Date Bookings can be made using the promotion. |
| 3 | bookingStartDate | `Date` | First Date Bookings can be made using the promotion. |
| 4 | category | `String` | Category |
| 5 | centralDescription | `String` | Promotion Name. |
| 6 | chainCode | `String` | Chain Code |
| 7 | checkInTime | `Date` | CheckIn Time for Promotion. |
| 8 | checkOutTime | `Date` | Check Out Time for Promotion. |
| 9 | code | `String` | Code |
| 10 | couponExChars | `String` | Exclude Characters while generating custom coupons. |
| 11 | couponGenFormat | `String` | Format for Custom based Random Generation option. 9 :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper). |
| 12 | couponGenOption | `String` | Generation option. N :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper) C  :  Custom Format. |
| 13 | couponLength | `Float` | Length of coupon code. |
| 14 | couponPrefix | `String` | Any Prefix to be appended to custom coupons. |
| 15 | couponSuffix | `String` | Any Suffix to be appended to custom coupons. |
| 16 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 17 | deletedflag | `String` | Deleted Flag |
| 18 | description | `String` | Description |
| 19 | group | `String` | Group |
| 20 | idRequiredDescription | `String` | Description of id requirements. |
| 21 | idRequiredYN | `String` | Indicates if an id is required for the promotion. |
| 22 | inactiveDate | `Date` | Inactive Date |
| 23 | inactiveflag | `String` | Inactive Flag |
| 24 | information | `String` | Information for the promotion. |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | instructions | `String` | Promotion Instructions for the property. |
| 28 | jRNUpdateDate | `Date` | JRN Update Date |
| 29 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 30 | limitedTimePromotionYn | `String` | Indicate if promotion is limited time use. |
| 31 | locationID | `String` | Internal ID to uniquely identify the Property |
| 32 | lockedByCode | `String` | Code of the system that is managing this record: local system application name or external system database id |
| 33 | lockedByType | `String` | Type of the system that is managing this record: L for local and E for external system. |
| 34 | longDescription | `String` | Description of Promotion. |
| 35 | mktgprogramid | `String` | Mktgprogramid |
| 36 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 37 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 38 | promoSequenceId | `Float` | Promo Seq ID |
| 39 | promotionid | `String` | Promotionid |
| 40 | property | `String` | Property |
| 41 | repItem | `String` | Reporting Item |
| 42 | repItemName | `String` | Reporting Item Name |
| 43 | repUpdateDate | `Date` | Reporting Updatedate |
| 44 | reportingPromoSequenceId | `String` | Rep Promo Seq ID |
| 45 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 46 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 47 | setOrAccountFlag | `String` | Indicates if set(S) or account (a) is required for booking. |
| 48 | stayEndDate | `Date` | End Date a guest can stay for the promotion. |
| 49 | stayStartDate | `Date` | First Date a guest can stay for the promotion. |
| 50 | updateDate | `DateTime` | Update Date |
| 51 | updateOutsideBookingDatesYN | `String` | Indicates if reservations with this promotion can be updated outside the promotion booking dates. |
| 52 | updateUser | `Float` | Update User |
| 53 | upgradeAllowedYN | `String` | Indicates if upgrades are allowed for the promotion. |
| 54 | voucherBenefitCode | `String` | Voucher Benefit Code |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyCompanyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRNumberCentral | `String` | AR Number (Central) |
| 3 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 4 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 5 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 6 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 7 | accountBillingContact | `String` | Billing contact person in company. |
| 8 | accountSource | `String` | Account Source |
| 9 | accountType | `String` | Account Type |
| 10 | actionCode | `String` | Action Code |
| 11 | activeYN | `String` | Active YN |
| 12 | address1 | `String` | Address 1 |
| 13 | address2 | `String` | Address 2 |
| 14 | address3 | `String` | Address 3 |
| 15 | address4 | `String` | Address 4 |
| 16 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 17 | allOwnerCodes | `String` | All Owner Codes |
| 18 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 19 | alternateSalutation | `String` | Alternate Salutation |
| 20 | alternateTitle | `String` | Alternate Title |
| 21 | autoPopRouting | `String` | Auto Pop Routing |
| 22 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 23 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 24 | billingCode | `String` | The billing code for this name record. |
| 25 | billingInstruction | `String` | Billing Instruction |
| 26 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 27 | birthCountry | `String` | Country of birth. |
| 28 | birthDate | `Date` | Birth Date |
| 29 | birthDateStr | `String` | Birth Date Str |
| 30 | birthPlace | `String` | Place of birth. |
| 31 | blMsg | `String` | Bl Msg |
| 32 | businessTitle | `String` | Business Title |
| 33 | cExchangeDate | `Date` | Central Xchange Date |
| 34 | cExchangeRate | `Float` | Central Xchange Rate |
| 35 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 36 | cRSNameid | `Float` | The unique identifier of the CRS |
| 37 | cashBlInd | `String` | Cash Bl Individual |
| 38 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 39 | centralAccountType | `String` | Central Account Type |
| 40 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 41 | centralDefaultKeyword | `String` | Central Default Keyword |
| 42 | centralNationality | `String` | Central Nationality |
| 43 | centralNationalityCode | `String` | Central Nationality Code |
| 44 | centralPriority | `String` | Central Priority |
| 45 | centralStateCode | `String` | Central State Code |
| 46 | centralTerritory | `String` | Central Territory |
| 47 | chainCode | `String` | Chain Code |
| 48 | city | `String` | City |
| 49 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 50 | combinedName | `String` | Combined Name |
| 51 | commissionCode | `String` | Commission Code |
| 52 | communicationType1 | `String` | Communication Type 1 |
| 53 | communicationType2 | `String` | Communication Type 2 |
| 54 | communicationType3 | `String` | Communication Type 3 |
| 55 | communicationValue1 | `String` | Communication Value 1 |
| 56 | communicationValue2 | `String` | Communication Value 2 |
| 57 | communicationValue3 | `String` | Communication Value 3 |
| 58 | company | `String` | Company |
| 59 | companyAlternate | `String` | Extended Byte Company Name |
| 60 | companyGroupId | `String` | Linked internal ID for booker. |
| 61 | companyNameId | `Float` | Company Name ID |
| 62 | companyProfileID | `Float` | Company Profile ID |
| 63 | competition | `String` | Competition |
| 64 | contractNo | `String` | Contract Number (used for customers). |
| 65 | contractRecvDate | `Date` | The date the group contract was received. |
| 66 | corporateID | `String` | Corporate ID |
| 67 | corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 68 | country | `String` | Country |
| 69 | countryCode | `String` | Country Code |
| 70 | creditCardName | `String` | Credit Card Name |
| 71 | creditCardType | `String` | Credit Card Type |
| 72 | creditRating | `String` | Credit Rating |
| 73 | currencyCode | `String` | Currency Code |
| 74 | currencyDescription | `String` | Currency Description |
| 75 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 76 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 77 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 78 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 79 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 80 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 81 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 82 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 83 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 84 | defaultKeyword | `String` | Default Keyword |
| 85 | deletedFlag | `String` | Deleted Flag |
| 86 | department | `String` | Department |
| 87 | deptId | `String` | Dept ID |
| 88 | directBillBatchType | `String` | Direct Bill Batch Type |
| 89 | displayName | `String` | Display Name |
| 90 | downloadDate | `Date` | Download Date |
| 91 | downloadResort | `String` | Download Property |
| 92 | downloadSrep | `Float` | Download Srep |
| 93 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 94 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 95 | email | `String` | Email |
| 96 | emailYn | `String` | Email Y/N |
| 97 | envelopeGreeting | `String` | Envelope Greeting |
| 98 | externalId | `String` | External ID |
| 99 | externalReferenceRequ | `String` | Not Used. |
| 100 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 101 | fMembershipCardNumbers | `String` | F Membership Card Numbers |
| 102 | fMembershipClassDesc | `String` | F Membership Class Description |
| 103 | fMembershipClasses | `String` | F Membership Classes |
| 104 | fMembershipCodes | `String` | F Membership Codes |
| 105 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 106 | fMembershipIds | `String` | F Membership Ids |
| 107 | fSubscriptionDb | `String` | F Subscription Db |
| 108 | fSubscriptionYn | `String` | F Subscription Y/N |
| 109 | faxNumber | `String` | Fax Number |
| 110 | first | `String` | First |
| 111 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 112 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 113 | gDSTransactionNo | `String` | Not used. |
| 114 | gender | `String` | Gender |
| 115 | geographicRegion | `String` | Not used. |
| 116 | guestClassification | `String` | Not used. |
| 117 | guestPrivYn | `String` | Guest Priv Y/N |
| 118 | historyYN | `String` | History YN |
| 119 | holdCode | `String` | Hold Code |
| 120 | iataConsortia | `String` | IATA Consortia |
| 121 | idCountry | `String` | ID Country |
| 122 | idDate | `Date` | ID Date |
| 123 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 124 | idNumber | `String` | ID Number |
| 125 | idPlace | `String` | ID Place |
| 126 | idType | `String` | ID Type |
| 127 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 128 | inactiveDate | `DateTime` | Inactive Date |
| 129 | inactiveFlag | `String` | Inactive Flag |
| 130 | inactiveReason | `String` | Reason why record was inactivated. |
| 131 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 132 | incognitoFirstName | `String` | Incognito First Name |
| 133 | incognitoLastName | `String` | Incognito Last Name |
| 134 | indexName | `String` | Index Name |
| 135 | industryCode | `String` | Industry Code |
| 136 | influence | `String` | Influence |
| 137 | insertDate | `DateTime` | Insert Date |
| 138 | insertUser | `String` | Insert User |
| 139 | interest | `String` | Interest Code. |
| 140 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 141 | internalDeletedflag | `String` | Deleted Flag |
| 142 | internalInactiveflag | `String` | Inactive Flag |
| 143 | internalOrganizationId | `Float` | Organization ID |
| 144 | jRNUpdateDate | `Date` | JRN Update Date |
| 145 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 146 | language | `String` | Language |
| 147 | languageCode | `String` | Language Code |
| 148 | laptopChange | `Float` | Laptop Change |
| 149 | last | `String` | Last |
| 150 | lastGroup | `String` | Last Group |
| 151 | lastRate | `Float` | Last Rate |
| 152 | lastRoom | `String` | Not used. |
| 153 | lastSource | `String` | Last Source |
| 154 | lastStay | `Date` | Last Stay |
| 155 | lastUpdatedResort | `String` | Last property that updated this record. |
| 156 | legalCompany | `String` | Legal Company |
| 157 | letterGreeting | `String` | Letter Greeting |
| 158 | mailListYN | `String` | Mail List YN |
| 159 | mailType | `String` | The type of mail this user should be sent. |
| 160 | mailYn | `String` | Mail Y/N |
| 161 | marketResearchYn | `String` | Market Research Y/N |
| 162 | markets | `String` | Markets |
| 163 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 164 | middle | `String` | Middle |
| 165 | name | `String` | Name |
| 166 | name2 | `String` | Name 2 |
| 167 | name3 | `String` | Name 3 |
| 168 | nameComment | `String` | Not Used. |
| 169 | nameTaxType | `String` | Name Tax Type |
| 170 | nameWithTitle | `String` | Name With Title |
| 171 | nationality | `String` | Nationality |
| 172 | nationalityCode | `String` | Nationality Code |
| 173 | negotiatedRateCodes | `String` | Negotiated Rate Codes |
| 174 | nextStay | `Date` | Next Stay |
| 175 | nickname | `String` | The nickname of this individual. |
| 176 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 177 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 178 | passport | `String` | Passport |
| 179 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 180 | paymentMethodsCode | `String` | Payment Methods Code |
| 181 | paymentMethodsDesc | `String` | Payment Methods Description |
| 182 | phoneNumber | `String` | Phone no. |
| 183 | phoneYn | `String` | Phone Y/N |
| 184 | postalCode | `String` | Postal Code |
| 185 | preferredRoomNo | `String` | Preferred Room Number |
| 186 | primaryAddressId | `Float` | Not used. |
| 187 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 188 | primaryNameId | `Float` | Not Used. |
| 189 | primaryOwner | `String` | Primary Owner |
| 190 | primaryOwnerCode | `String` | Primary Owner Code |
| 191 | primaryPhoneId | `Float` | Not used. |
| 192 | priority | `String` | Priority |
| 193 | privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 194 | productInterest | `String` | Product Interest |
| 195 | profession | `String` | Profession of the guest |
| 196 | profileArrCodes | `String` | Profile Arrangement Codes |
| 197 | profileArrangementDesc | `String` | Profile Arr Description |
| 198 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 199 | profileId | `Float` | Profile ID |
| 200 | profileType | `String` | Profile Type |
| 201 | propertyRegistered | `String` | Resort for which Job is registered. |
| 202 | protected | `String` | Protected |
| 203 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 204 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 205 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 206 | rateStructure | `String` | The default rate structure for this name. |
| 207 | region | `String` | Region |
| 208 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 209 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 210 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 211 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 212 | repInactiveReason | `String` | Reporting Inactive Reason |
| 213 | repInactiveReasonCode | `String` | Reporting Inactive Reason Code |
| 214 | repIndustryDescription | `String` | Reporting Industry Desc |
| 215 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 216 | repMailActionDescription | `String` | Reporting Mail Action Desc |
| 217 | repMarketsDescription | `String` | Reporting Markets Desc |
| 218 | repNameType | `String` | Reporting Name Type |
| 219 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 220 | repPriorityDescription | `String` | Reporting Priority Desc |
| 221 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 222 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 223 | repScopeDescription | `String` | Reporting Scope Desc |
| 224 | repStateDescription | `String` | Reporting State Desc |
| 225 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 226 | repTitle | `String` | Reporting Title |
| 227 | repTitleName | `String` | Reporting Title Name |
| 228 | repVIPName | `String` | Reporting Vip Name |
| 229 | repVIPStatus | `String` | Reporting Vip Status |
| 230 | repeatGuestId | `String` | The primary membership # for this guest. |
| 231 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 232 | resvContact | `String` | Reservation Contact person. |
| 233 | roomsPotential | `String` | Rooms Potential |
| 234 | salutation | `String` | Salutation Greeting |
| 235 | scope | `String` | Scope |
| 236 | scopeCity | `String` | Scope City |
| 237 | searchName | `String` | The Uppercase value of Last or Company. |
| 238 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 239 | sfirst | `String` | Uppercase value of First Name. |
| 240 | smsYn | `String` | Use this alert to text a notification. |
| 241 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 242 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 243 | srepCode | `String` | Srep Code |
| 244 | state | `String` | State |
| 245 | stateCode | `String` | State Code |
| 246 | suffix | `String` | Suffix |
| 247 | summRefCc | `String` | Summ Ref Cc |
| 248 | superSearchIndexText | `String` | Super Search Index Text |
| 249 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 250 | taxCategory | `String` | Tax Category |
| 251 | taxExemptStatus | `String` | Not used. |
| 252 | taxID1 | `String` | Tax ID 1 |
| 253 | taxID2 | `String` | Tax ID 2 |
| 254 | taxOffice | `String` | Tax Office Name |
| 255 | taxType | `String` | Tax Type |
| 256 | territory | `String` | Territory |
| 257 | thirdPartyYn | `String` | Third Party Y/N |
| 258 | title | `String` | Title |
| 259 | titleSuffix | `Float` | Title Suffix |
| 260 | totalArrivals | `Float` | Total Arrivals |
| 261 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 262 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 263 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 264 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 265 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 266 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 267 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 268 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 269 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 270 | totalFbRevenue | `Float` | Total FB Revenue |
| 271 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 272 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 273 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 274 | totalNonRevenue | `Float` | Total Non Revenue |
| 275 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 276 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 277 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 278 | totalOtherRevenue | `Float` | Total Other Revenue |
| 279 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 280 | totalReservationNights | `Float` | Total Reservation Nights |
| 281 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 282 | totalRevenue | `Float` | Total Revenue |
| 283 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 284 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 285 | totalRoomRevenue | `Float` | Total Room Revenue |
| 286 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 287 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 288 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 289 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 290 | traceCode | `String` | Trace Code |
| 291 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 292 | uDFC01 | `String` | UDFC01 |
| 293 | uDFC02 | `String` | UDFC02 |
| 294 | uDFC03 | `String` | UDFC03 |
| 295 | uDFC04 | `String` | UDFC04 |
| 296 | uDFC05 | `String` | UDFC05 |
| 297 | uDFC06 | `String` | UDFC06 |
| 298 | uDFC07 | `String` | UDFC07 |
| 299 | uDFC08 | `String` | UDFC08 |
| 300 | uDFC09 | `String` | UDFC09 |
| 301 | uDFC10 | `String` | UDFC10 |
| 302 | uDFC11 | `String` | UDFC11 |
| 303 | uDFC12 | `String` | UDFC12 |
| 304 | uDFC13 | `String` | UDFC13 |
| 305 | uDFC14 | `String` | UDFC14 |
| 306 | uDFC15 | `String` | UDFC15 |
| 307 | uDFC16 | `String` | UDFC16 |
| 308 | uDFC17 | `String` | UDFC17 |
| 309 | uDFC18 | `String` | UDFC18 |
| 310 | uDFC19 | `String` | UDFC19 |
| 311 | uDFC20 | `String` | UDFC20 |
| 312 | uDFC21 | `String` | UDFC21 |
| 313 | uDFC22 | `String` | UDFC22 |
| 314 | uDFC23 | `String` | UDFC23 |
| 315 | uDFC24 | `String` | UDFC24 |
| 316 | uDFC25 | `String` | UDFC25 |
| 317 | uDFC26 | `String` | UDFC26 |
| 318 | uDFC27 | `String` | UDFC27 |
| 319 | uDFC28 | `String` | UDFC28 |
| 320 | uDFC29 | `String` | UDFC29 |
| 321 | uDFC30 | `String` | UDFC30 |
| 322 | uDFC31 | `String` | UDFC31 |
| 323 | uDFC32 | `String` | UDFC32 |
| 324 | uDFC33 | `String` | UDFC33 |
| 325 | uDFC34 | `String` | UDFC34 |
| 326 | uDFC35 | `String` | UDFC35 |
| 327 | uDFC36 | `String` | UDFC36 |
| 328 | uDFC37 | `String` | UDFC37 |
| 329 | uDFC38 | `String` | UDFC38 |
| 330 | uDFC39 | `String` | UDFC39 |
| 331 | uDFC40 | `String` | UDFC40 |
| 332 | uDFD01 | `Date` | UDFD01 |
| 333 | uDFD02 | `Date` | UDFD02 |
| 334 | uDFD03 | `Date` | UDFD03 |
| 335 | uDFD04 | `Date` | UDFD04 |
| 336 | uDFD05 | `Date` | UDFD05 |
| 337 | uDFD06 | `Date` | UDFD06 |
| 338 | uDFD07 | `Date` | UDFD07 |
| 339 | uDFD08 | `Date` | UDFD08 |
| 340 | uDFD09 | `Date` | UDFD09 |
| 341 | uDFD10 | `Date` | UDFD10 |
| 342 | uDFD11 | `Date` | UDFD11 |
| 343 | uDFD12 | `Date` | UDFD12 |
| 344 | uDFD13 | `Date` | UDFD13 |
| 345 | uDFD14 | `Date` | UDFD14 |
| 346 | uDFD15 | `Date` | UDFD15 |
| 347 | uDFD16 | `Date` | UDFD16 |
| 348 | uDFD17 | `Date` | UDFD17 |
| 349 | uDFD18 | `Date` | UDFD18 |
| 350 | uDFD19 | `Date` | UDFD19 |
| 351 | uDFD20 | `Date` | UDFD20 |
| 352 | uDFN01 | `Float` | UDFN01 |
| 353 | uDFN02 | `Float` | UDFN02 |
| 354 | uDFN03 | `Float` | UDFN03 |
| 355 | uDFN04 | `Float` | UDFN04 |
| 356 | uDFN05 | `Float` | UDFN05 |
| 357 | uDFN06 | `Float` | UDFN06 |
| 358 | uDFN07 | `Float` | UDFN07 |
| 359 | uDFN08 | `Float` | UDFN08 |
| 360 | uDFN09 | `Float` | UDFN09 |
| 361 | uDFN10 | `Float` | UDFN10 |
| 362 | uDFN11 | `Float` | UDFN11 |
| 363 | uDFN12 | `Float` | UDFN12 |
| 364 | uDFN13 | `Float` | UDFN13 |
| 365 | uDFN14 | `Float` | UDFN14 |
| 366 | uDFN15 | `Float` | UDFN15 |
| 367 | uDFN16 | `Float` | UDFN16 |
| 368 | uDFN17 | `Float` | UDFN17 |
| 369 | uDFN18 | `Float` | UDFN18 |
| 370 | uDFN19 | `Float` | UDFN19 |
| 371 | uDFN20 | `Float` | UDFN20 |
| 372 | uDFN21 | `Float` | UDFN21 |
| 373 | uDFN22 | `Float` | UDFN22 |
| 374 | uDFN23 | `Float` | UDFN23 |
| 375 | uDFN24 | `Float` | UDFN24 |
| 376 | uDFN25 | `Float` | UDFN25 |
| 377 | uDFN26 | `Float` | UDFN26 |
| 378 | uDFN27 | `Float` | UDFN27 |
| 379 | uDFN28 | `Float` | UDFN28 |
| 380 | uDFN29 | `Float` | UDFN29 |
| 381 | uDFN30 | `Float` | UDFN30 |
| 382 | uDFN31 | `Float` | UDFN31 |
| 383 | uDFN32 | `Float` | UDFN32 |
| 384 | uDFN33 | `Float` | UDFN33 |
| 385 | uDFN34 | `Float` | UDFN34 |
| 386 | uDFN35 | `Float` | UDFN35 |
| 387 | uDFN36 | `Float` | UDFN36 |
| 388 | uDFN37 | `Float` | UDFN37 |
| 389 | uDFN38 | `Float` | UDFN38 |
| 390 | uDFN39 | `Float` | UDFN39 |
| 391 | uDFN40 | `Float` | UDFN40 |
| 392 | updateDate | `DateTime` | Update Date |
| 393 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 394 | updateUser | `String` | Update User |
| 395 | uploadDate | `Date` | Upload Date |
| 396 | vendorId | `Float` | Vendor ID |
| 397 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 398 | vipAuthorization | `String` | Not Used. |
| 399 | vipName | `String` | VIP Name |
| 400 | vipStatus | `String` | VIP Status |
| 401 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 402 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 403 | xfirstName | `String` | Xfirst Name |
| 404 | xlastName | `String` | Xlast Name |
| 405 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyBlockDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionId | `Float` | Action ID |
| 2 | actualAverageRoomRate | `Float` | Actual Average Room Rate |
| 3 | actualFBRevenue | `Float` | Actual F&B Revenue |
| 4 | actualOtherRevenue | `Float` | Other revenue |
| 5 | actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| 6 | actualRoomRevenue | `Float` | Actual revenue of the room |
| 7 | addInfo | `String` | Add Info |
| 8 | agentContactNameId | `Float` | Agent Contact Name ID |
| 9 | agentNameId | `Float` | Agent Name ID |
| 10 | agentprofileid | `Float` | Agentprofileid |
| 11 | allAliases | `String` | All Aliases |
| 12 | allBlockOwners | `String` | All Block Owners |
| 13 | allCateringOwners | `String` | All Catering Owners |
| 14 | allCompanyContacts | `String` | All Company Contacts |
| 15 | allRateCodes | `String` | All Rate Codes |
| 16 | allRoomOwners | `String` | All Room Owners |
| 17 | allRoomPools | `String` | All Room Pools |
| 18 | allRoomTypes | `String` | All Room Types |
| 19 | allSourceContacts | `String` | All Source Contacts |
| 20 | allTravelAgentContacts | `String` | All Travel Agent Contacts |
| 21 | allotmentOrigin | `String` | Allotment Origin |
| 22 | allotmentType | `String` | Type of Block alloted for the group. |
| 23 | allotmentcurrencyid | `String` | Allotmentcurrencyid |
| 24 | allotmentid | `Float` | Block ID |
| 25 | allowPickup | `String` | Allow a pickup for a group with this booking status |
| 26 | alternateBlockName | `String` | Multi Byte Description Field |
| 27 | alternateDates | `String` | Alternate Dates |
| 28 | arrivalTime | `DateTime` | Arrival Time |
| 29 | attachmentURL | `String` | URL pointing to Lead Attachments. |
| 30 | attendeesGuaranteed | `Float` | Attendees Guaranteed |
| 31 | autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| 32 | averageRate | `Float` | Average Rate |
| 33 | bEOLastPrint | `DateTime` | Date when the BEO report was last printed for this business block. |
| 34 | beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| 35 | blockAlias | `String` | Block Alias |
| 36 | blockCode | `String` | Block Code |
| 37 | blockDateActual | `Date` | Block Date Actual |
| 38 | blockDateDefinite | `DateTime` | Block Date Definite |
| 39 | blockDateProspect | `DateTime` | Block Date Prospect |
| 40 | blockDateTentative | `DateTime` | Block Date Tentative |
| 41 | blockDescription | `String` | Block Description |
| 42 | blockID | `Float` | Block ID |
| 43 | blockMode | `String` | Classifies this allotment record: MASTER_ALLOCATION SUB_ALLOCATION SUB_BOOKING SUB_TOUR SUB_ITINERARY |
| 44 | blockOwnerCode | `String` | Block Owner Code |
| 45 | blockOwnerFullName | `String` | Block Owner Full Name |
| 46 | blockPackage | `String` | Block Package |
| 47 | blockPackageDescription | `String` | Block Package Description |
| 48 | blockStatus | `String` | Block Status |
| 49 | blockStatusDescription | `String` | Block Status Description |
| 50 | blockTypeCode | `String` | Block Type Code |
| 51 | blockTypeCodeDescription | `String` | Block Type Code Description |
| 52 | blockpackageid | `String` | Blockpackageid |
| 53 | bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| 54 | bookingMethodOrderBy | `Float` | Booking Method Order By |
| 55 | bookingStatusOrder | `Float` | Booking Status Order |
| 56 | bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| 57 | bookingTypeDescription | `String` | Booking Type Description |
| 58 | bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| 59 | bookingsourceid | `String` | Bookingsourceid |
| 60 | bookingstatusid | `String` | Bookingstatusid |
| 61 | bookingtypeid | `String` | Bookingtypeid |
| 62 | breakfastDescription | `String` | Breakfast Description |
| 63 | breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| 64 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 65 | breakfastIncluded | `String` | Breakfast Included |
| 66 | breakfastPrice | `Float` | Breakfast Price |
| 67 | bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| 68 | bwiUrl | `String` | URL populated bu CRS. |
| 69 | cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| 70 | cBreakfastPrice | `Float` | Central Bfst Price |
| 71 | cCompRoomValue | `Float` | Central Comp Room Value |
| 72 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 73 | cExchangeDate | `Date` | Central Xchange Date |
| 74 | cExchangeRate | `Float` | Central Xchange Rate |
| 75 | cFBCommission1 | `Float` | Central Fb Commission 1 |
| 76 | cFBCommission2 | `Float` | Central Fb Commission 2 |
| 77 | cPorteragePrice | `Float` | Central Porterage Price |
| 78 | cRoomCommission1 | `Float` | Central Rm Commission 1 |
| 79 | cRoomCommission2 | `Float` | Central Rm Commission 2 |
| 80 | cServiceCharge | `Float` | Central Service Charge |
| 81 | cServiceFee | `Float` | Central Service Fee |
| 82 | cRSGtdYn | `String` | CRS Guaranteed Y/N |
| 83 | cancelRule | `String` | Not Used |
| 84 | canceldestinationid | `String` | Canceldestinationid |
| 85 | cancellationDestination | `String` | Cancellation Destination |
| 86 | cancellationDestinationDescription | `String` | Cancellation Destination Description |
| 87 | cancellationNumber | `Float` | Cancellation Number |
| 88 | cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| 89 | cancellationreasonid | `String` | Cancellationreasonid |
| 90 | catCutoff | `Date` | Catering Cutoff |
| 91 | catDateProspect | `DateTime` | Cat Date Prospect |
| 92 | catOwner | `Float` | Catering Owner |
| 93 | catOwnerProperty | `String` | Property of Catering Owner |
| 94 | catReturnToInventory | `String` | Cat Return To Inventory |
| 95 | catStartingStatus | `String` | Cat Starting Status |
| 96 | catcurrencyid | `String` | Catcurrencyid |
| 97 | cateringCancellationDate | `Date` | Catering Cancellation Date |
| 98 | cateringCancellationDescription | `String` | Catering Cancellation Description |
| 99 | cateringCancellationNumber | `Float` | Catering Cancellation Number |
| 100 | cateringCancellationReason | `String` | Catering Cancellation Reason |
| 101 | cateringCurrency | `String` | Catering Currency |
| 102 | cateringDateActual | `Date` | Catering Date Actual |
| 103 | cateringDecisionDate | `Date` | Catering Decision Date |
| 104 | cateringDeductInventory | `String` | Catering Deduct Inventory |
| 105 | cateringExchangeRate | `Float` | Catering Exchange Rate |
| 106 | cateringFollowupDate | `Date` | Catering Followup Date |
| 107 | cateringOnlyYN | `String` | Catering only Revenue. |
| 108 | cateringOrderBy | `Float` | Catering Order By |
| 109 | cateringOwnerCode | `String` | Catering Owner Code |
| 110 | cateringOwnerFullName | `String` | Catering Owner Full Name |
| 111 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 112 | cateringQuoteCurrency | `String` | Catering Quote Currency |
| 113 | cateringStatus | `String` | Catering Status |
| 114 | cateringStatusColor | `String` | Catering Status Color |
| 115 | cateringStatusDescription | `String` | Catering Status Description |
| 116 | cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 117 | cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| 118 | cateringcurrencyid | `String` | Cateringcurrencyid |
| 119 | cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| 120 | cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| 121 | cateringstatusid | `String` | Cateringstatusid |
| 122 | cenralFBRevenue | `Float` | Cenral FB Revenue |
| 123 | centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| 124 | centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| 125 | centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| 126 | centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| 127 | centralAverageRoomRate | `Float` | Central Average Room Rate |
| 128 | centralBlockPackage | `String` | Central Block Package |
| 129 | centralBlockPackageDescription | `String` | Central Block Package Description |
| 130 | centralBlockStatus | `String` | Central Block Status |
| 131 | centralBlockStatusDescription | `String` | Central Block Status Description |
| 132 | centralBlockTypeCode | `String` | Central Block Type Code |
| 133 | centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| 134 | centralBookingType | `String` | Central Booking Type |
| 135 | centralBookingTypeDescription | `String` | Central Booking Type Description |
| 136 | centralCancellationDestination | `String` | Central Cancellation Destination |
| 137 | centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| 138 | centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| 139 | centralCateringStatus | `String` | Central Catering Status |
| 140 | centralCateringStatusDescription | `String` | Central Catering Status Description |
| 141 | centralConversionCode | `String` | Central Conversion Code |
| 142 | centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| 143 | centralIndustryCode | `String` | Central Industry Code |
| 144 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 145 | centralItemsForThisBlock | `String` | Central Items for this Block |
| 146 | centralMarketDescription | `String` | Central Market Description |
| 147 | centralMarketCode | `String` | Central Market code |
| 148 | centralMeetingBudget | `Float` | Central Meeting Budget |
| 149 | centralMeetingRevenue | `Float` | Central Meeting Revenue |
| 150 | centralOriginCode | `String` | Central Origin Code |
| 151 | centralOriginCodeDescription | `String` | Central Origin Code Description |
| 152 | centralOtherRevenue | `Float` | Central Other Revenue |
| 153 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 154 | centralPayment | `String` | Central Payment |
| 155 | centralPaymentDescription | `String` | Central Payment Description |
| 156 | centralRankingCode | `String` | Central Ranking Code |
| 157 | centralRankingCodeDescription | `String` | Central Ranking Code Description |
| 158 | centralReservationMethodCode | `String` | Central Reservation Method Code |
| 159 | centralReservationMethodDescription | `String` | Central Reservation Method Description |
| 160 | centralReservationType | `String` | Central Reservation Type |
| 161 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 162 | centralRoomRevenue | `Float` | Central Room Revenue |
| 163 | centralSourceCode | `String` | Central Source Code |
| 164 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 165 | centralTaxAmount | `Float` | Central Tax Amount |
| 166 | chainCode | `String` | Chain Code |
| 167 | channelid | `String` | Channelid |
| 168 | code | `String` | Code |
| 169 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 170 | comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| 171 | comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| 172 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 173 | comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 174 | comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 175 | commissionAmount | `String` | Commission Amount |
| 176 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 177 | commissionableYn | `String` | Commissionable Y/N |
| 178 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 179 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 180 | compRooms | `Float` | Number of complimentary Rooms |
| 181 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 182 | companyAll | `String` | Company All |
| 183 | companyNameId | `Float` | Company Name ID |
| 184 | companyprofileid | `Float` | Companyprofileid |
| 185 | competition | `String` | Competition |
| 186 | contactNameId | `Float` | Contact Name ID |
| 187 | contactprofileid | `Float` | Contactprofileid |
| 188 | contractNumber | `String` | Contract Number |
| 189 | controlBlockLocally | `String` | Control Block Y/N |
| 190 | conversionCode | `String` | Conversion Code |
| 191 | coversionCodeDescription | `String` | Coversion Code Description |
| 192 | createdBy | `String` | The name of the user who created the record. |
| 193 | createdDate | `DateTime` | Created Date |
| 194 | createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| 195 | creditCardId | `Float` | Credit Card ID |
| 196 | currency | `String` | Currency |
| 197 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 198 | dateAcl | `Date` | Date Acl |
| 199 | dateCfl | `Date` | Date Cfl |
| 200 | dateDefinite | `DateTime` | Date Definite |
| 201 | dateLsl | `Date` | Date Lsl |
| 202 | dateOpenedForPickup | `Date` | Date Opened for Pickup |
| 203 | datePel | `DateTime` | Date Pel |
| 204 | dateTdl | `DateTime` | Date Tdl |
| 205 | dateTentative | `DateTime` | Date Tentative |
| 206 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 207 | deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| 208 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 209 | deletedflag | `String` | Deleted Flag |
| 210 | departureTime | `DateTime` | Departure Time |
| 211 | description | `String` | Description |
| 212 | distributed | `String` | Distributed |
| 213 | distributedDate | `DateTime` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| 214 | dmlSeqNumber | `Float` | Dml Sequence No |
| 215 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 216 | downloadDate | `Date` | Download Date |
| 217 | downloadResort | `String` | Download Property |
| 218 | downloadSrep | `Float` | Download Srep |
| 219 | dueDate | `Date` | Due Date |
| 220 | dueDateOrd | `Date` | Due Date Sorting Column. |
| 221 | endDate | `Date` | End Date |
| 222 | endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| 223 | endbusinessdate | `Date` | Endbusinessdate |
| 224 | eventAttendees | `Float` | Event Attendees |
| 225 | exchangePostingType | `String` | Exchange Posting Type |
| 226 | exchangeRate | `Float` | Exchange Rate |
| 227 | exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| 228 | externalReference | `String` | External Reference |
| 229 | externalRfpId | `String` | External RFP ID. |
| 230 | externalRfpSystem | `String` | External RFP System Identification Code. |
| 231 | externallyLocked | `String` | Externally Locked |
| 232 | fBRevenue | `Float` | Projected F&B Revenue. |
| 233 | fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| 234 | fbCommission1 | `Float` | stores FB commission for Agent 1 |
| 235 | fbCommission2 | `Float` | stores FB commission for Agent 2 |
| 236 | fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| 237 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 238 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 239 | fitdiscounttype | `String` | Fitdiscounttype |
| 240 | flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| 241 | followupDate | `Date` | Followup Date |
| 242 | fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| 243 | functionType | `String` | Function Type |
| 244 | giid | `String` | Group IATA Number. |
| 245 | greekContractNr | `String` | Greek Contract Number. |
| 246 | groupAccountID | `Float` | Group Account ID |
| 247 | guaranteecodeid | `String` | Guaranteecodeid |
| 248 | guaranteedRate | `String` | Rate Guaranteed Y/N. |
| 249 | guaranteedYN | `String` | Guaranteed YN |
| 250 | hideacctinfoflag | `String` | Hideacctinfoflag |
| 251 | hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| 252 | hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| 253 | hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| 254 | hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| 255 | hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| 256 | hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| 257 | hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| 258 | hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| 259 | hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| 260 | inactiveDate | `Date` | Inactive Date |
| 261 | inactiveflag | `String` | Inactive Flag |
| 262 | industryCode | `String` | Indicates the Non-Compete code of a block. |
| 263 | industryCodeDescription | `String` | Industry Code Description |
| 264 | info | `String` | Not Used |
| 265 | informationBoard | `String` | Information Board |
| 266 | insertUser | `Float` | Insert User |
| 267 | inventoryControl | `String` | Inventory Control |
| 268 | inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| 269 | inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| 270 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 271 | items | `String` | Items |
| 272 | itemsForThisBlock | `String` | Items for this Block |
| 273 | jRNUpdateDate | `Date` | JRN Update Date |
| 274 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 275 | keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| 276 | laptopChange | `Float` | Laptop Change |
| 277 | leadOrigin | `String` | Lead Origin |
| 278 | leadSentYN | `String` | Lead Sent YN |
| 279 | leadSource | `String` | Lead Source |
| 280 | leadType | `String` | Lead Type |
| 281 | leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| 282 | leaderrorflag | `String` | Leaderrorflag |
| 283 | leadisnewflag | `String` | Leadisnewflag |
| 284 | leadoriginid | `String` | Leadoriginid |
| 285 | leadreceivedflag | `String` | Leadreceivedflag |
| 286 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 287 | leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| 288 | leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| 289 | leadserverpendingflag | `String` | Leadserverpendingflag |
| 290 | leadsourceid | `String` | Leadsourceid |
| 291 | leadstatus | `String` | Leadstatus |
| 292 | linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 293 | locationID | `String` | Internal ID to uniquely identify the Property |
| 294 | lostTo | `String` | Competitor to whom the booking was lost. |
| 295 | mainmarket | `String` | Mainmarket |
| 296 | mainmarketid | `String` | Mainmarketid |
| 297 | manuallyCutoffYN | `String` | Block was cutoff manullay |
| 298 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 299 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 300 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 301 | marketCode | `String` | Market  Code |
| 302 | marketDescription | `String` | Market Description |
| 303 | marketid | `String` | Marketid |
| 304 | masterBlockID | `Float` | Parent Block ID |
| 305 | masterBlockProperty | `String` | Parent Resort |
| 306 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 307 | meetingBudget | `Float` | Meeting Budget |
| 308 | meetingRevenue | `Float` | Meeting Revenue for SFA |
| 309 | offsetType | `String` | Offset Type |
| 310 | orderBy | `Float` | Order By |
| 311 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 312 | origAllotmentHeaderId | `Float` | Stores the original ALLOTMENT_HEADER_ID prior to a migration. |
| 313 | originCode | `String` | Origin Code |
| 314 | originCodeDescription | `String` | Origin Code Description |
| 315 | originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| 316 | originalEndDate | `Date` | Original End Date |
| 317 | originalRateCode | `String` | Not used |
| 318 | originalStartDate | `Date` | Original Start Date |
| 319 | originalratecodeid | `String` | Originalratecodeid |
| 320 | ormsBlockClass | `String` | ORMS Block Class |
| 321 | ormsFinalBlock | `String` | ORMS Final Block |
| 322 | ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| 323 | ormsTransientBlock | `String` | ORMS Transient Block |
| 324 | otherRevenue | `Float` | Projected Other Revenue. |
| 325 | owner | `Float` | Owner |
| 326 | ownerResort | `String` | Owner Property |
| 327 | owneremployeeid | `Float` | Owneremployeeid |
| 328 | ownerlocationd | `String` | Ownerlocationd |
| 329 | parentallotmentid | `Float` | Parentallotmentid |
| 330 | payment | `String` | Payment |
| 331 | paymentDescription | `String` | Payment Description |
| 332 | paymentmethodid | `String` | Paymentmethodid |
| 333 | personsPerRoom | `Float` | Persons Per Room |
| 334 | porterageIncluded | `String` | Porterage Included |
| 335 | porteragePrice | `Float` | Porterage Price |
| 336 | potAverageRoomRate | `Float` | Pot Average Room Rate |
| 337 | potFbRevenue1 | `Float` | Pot FB Revenue1 |
| 338 | potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| 339 | potRoomNights | `Float` | Projected Room Nights. |
| 340 | potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| 341 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 342 | printRate | `String` | Print Rate |
| 343 | profileId | `Float` | Profile ID |
| 344 | program | `String` | Program |
| 345 | property | `String` | Code to uniquely identify the Property |
| 346 | proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| 347 | proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| 348 | proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| 349 | proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| 350 | proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| 351 | proposalSentDate | `DateTime` | Proposal Sent Date |
| 352 | proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| 353 | proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| 354 | proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| 355 | proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| 356 | proposalViewToken | `String` | Proposal View Token |
| 357 | publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| 358 | rankingCode | `String` | Indicates the ranking of a block. |
| 359 | rankingCodeDescription | `String` | Ranking Code Description |
| 360 | rateCode | `String` | Rate Code |
| 361 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 362 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 363 | rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 364 | rateTier | `Float` | Rate Tier |
| 365 | ratecodeid | `String` | Ratecodeid |
| 366 | readyForDistribution | `String` | Ready for Distribution |
| 367 | regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| 368 | repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| 369 | repBsOrderBy | `Float` | Rep Bs Order By |
| 370 | repCatOrderBy | `Float` | Rep Cat Order By |
| 371 | replDate | `DateTime` | Reply Date |
| 372 | replVia | `String` | Reply Communication Method |
| 373 | replstatus | `String` | Lead Replystatus [ACL|TDL] |
| 374 | replyBy | `Float` | Reply By |
| 375 | representative | `String` | Representative |
| 376 | reservationMethod | `String` | Reservation Method |
| 377 | reservationType | `String` | Reservation Type |
| 378 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 379 | reservationid | `Float` | Reservationid |
| 380 | reserveInventoryYN | `String` | Reserve Inventory YN |
| 381 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 382 | resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| 383 | respTime | `Float` | Response Time. |
| 384 | respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| 385 | returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| 386 | rivMarketSegment | `String` | Not used |
| 387 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 388 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 389 | roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| 390 | roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| 391 | roomNightsSold | `Float` | Room Nights Sold |
| 392 | roomOwnerCode | `String` | Room Owner Code |
| 393 | roomOwnerFullName | `String` | Room Owner Full Name |
| 394 | roomRevenue | `Float` | Projected Room Revenue. |
| 395 | roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| 396 | roomStatus | `String` | Room Status |
| 397 | roomingListDue | `Date` | Rooming List Due |
| 398 | roomingListRules | `String` | Stores Rooming List Rules. |
| 399 | roomsCancellationDate | `Date` | Rooms Cancellation Date |
| 400 | roomsCancellationReason | `String` | Rooms Cancellation Reason |
| 401 | roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| 402 | roomsCurrency | `String` | Rooms Currency |
| 403 | roomsDecisionDate | `Date` | Rooms Decision Date |
| 404 | roomsExchangeRate | `Float` | Rooms Exchange Rate |
| 405 | roomsOwner | `Float` | Rooms Owner |
| 406 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 407 | roomsPerDay | `Float` | Rooms Per Day |
| 408 | roomsQuoteCurrency | `String` | Rooms Quote Currency |
| 409 | roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| 410 | salesId | `String` | Not used |
| 411 | sbegindate | `Date` | Sbegindate |
| 412 | scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| 413 | sellThruYn | `String` | Sell Thru Indicator. |
| 414 | sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| 415 | senddate | `Date` | Senddate |
| 416 | sentBy | `Float` | Sent By |
| 417 | sentDate | `DateTime` | Sent Date |
| 418 | sentVia | `String` | Sent Via |
| 419 | serviceCharge | `Float` | Service Charge |
| 420 | serviceFee | `Float` | Service Fee Amount per room/night |
| 421 | serviceFeeYn | `String` | Service Fee applies? |
| 422 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 423 | servicePerc | `Float` | Service Percentage included. |
| 424 | shoulderEnd | `Date` | Shoulder End |
| 425 | shoulderStart | `Date` | Shoulder Start |
| 426 | showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 427 | snapshotSetup | `String` | Snapshot has been created |
| 428 | sourceCode | `String` | Source Code |
| 429 | sourceCodeDescription | `String` | Source Code Description |
| 430 | sourceContactAll | `String` | Source Contact All |
| 431 | sourceNameId | `Float` | Source Name ID |
| 432 | sourceid | `Float` | Sourceid |
| 433 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 434 | startDate | `Date` | Start Date |
| 435 | startingStatus | `String` | Booking starting status (intial pickup) |
| 436 | status | `String` | Status |
| 437 | statusColor | `String` | Status Color |
| 438 | statusType | `String` | Type of booking status (initial) |
| 439 | subAllocationYN | `String` | Sub Allocation YN |
| 440 | superSearchIndexText | `String` | Super Search Index Text |
| 441 | suppressRate | `String` | Suppress Rate |
| 442 | syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the allotment_detail trigger. |
| 443 | synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| 444 | taxAmount | `Float` | Tax Amount |
| 445 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 446 | taxIncludedYn | `String` | Tax is included in this rate. |
| 447 | taxType | `String` | Tax Type |
| 448 | taxtypeid | `String` | Taxtypeid |
| 449 | tbdRates | `String` | To be Determined Rates |
| 450 | tdlReason | `String` | Tdl Reason |
| 451 | tentativeLevel | `Float` | Not used |
| 452 | tlpResponseid | `String` | Stores the TLPe - Response ID |
| 453 | tlpUrl | `String` | Stores the TLPe - Result URL. |
| 454 | tourCode | `String` | Tour Code. |
| 455 | traceCode | `String` | Trace Code |
| 456 | traceDescription | `String` | Trace Description |
| 457 | trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 458 | travelAgentAll | `String` | Travel Agent All |
| 459 | travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| 460 | turndownreasonid | `Float` | Turndownreasonid |
| 461 | uDFC01 | `String` | UDFC01 |
| 462 | uDFC02 | `String` | UDFC02 |
| 463 | uDFC03 | `String` | UDFC03 |
| 464 | uDFC04 | `String` | UDFC04 |
| 465 | uDFC05 | `String` | UDFC05 |
| 466 | uDFC06 | `String` | UDFC06 |
| 467 | uDFC07 | `String` | UDFC07 |
| 468 | uDFC08 | `String` | UDFC08 |
| 469 | uDFC09 | `String` | UDFC09 |
| 470 | uDFC10 | `String` | UDFC10 |
| 471 | uDFC11 | `String` | UDFC11 |
| 472 | uDFC12 | `String` | UDFC12 |
| 473 | uDFC13 | `String` | UDFC13 |
| 474 | uDFC14 | `String` | UDFC14 |
| 475 | uDFC15 | `String` | UDFC15 |
| 476 | uDFC16 | `String` | UDFC16 |
| 477 | uDFC17 | `String` | UDFC17 |
| 478 | uDFC18 | `String` | UDFC18 |
| 479 | uDFC19 | `String` | UDFC19 |
| 480 | uDFC20 | `String` | UDFC20 |
| 481 | uDFC21 | `String` | UDFC21 |
| 482 | uDFC22 | `String` | UDFC22 |
| 483 | uDFC23 | `String` | UDFC23 |
| 484 | uDFC24 | `String` | UDFC24 |
| 485 | uDFC25 | `String` | UDFC25 |
| 486 | uDFC26 | `String` | UDFC26 |
| 487 | uDFC27 | `String` | UDFC27 |
| 488 | uDFC28 | `String` | UDFC28 |
| 489 | uDFC29 | `String` | UDFC29 |
| 490 | uDFC30 | `String` | UDFC30 |
| 491 | uDFC31 | `String` | UDFC31 |
| 492 | uDFC32 | `String` | UDFC32 |
| 493 | uDFC33 | `String` | UDFC33 |
| 494 | uDFC34 | `String` | UDFC34 |
| 495 | uDFC35 | `String` | UDFC35 |
| 496 | uDFC36 | `String` | UDFC36 |
| 497 | uDFC37 | `String` | UDFC37 |
| 498 | uDFC38 | `String` | UDFC38 |
| 499 | uDFC39 | `String` | UDFC39 |
| 500 | uDFC40 | `String` | UDFC40 |
| 501 | uDFD01 | `Date` | UDFD01 |
| 502 | uDFD02 | `Date` | UDFD02 |
| 503 | uDFD03 | `Date` | UDFD03 |
| 504 | uDFD04 | `Date` | UDFD04 |
| 505 | uDFD05 | `Date` | UDFD05 |
| 506 | uDFD06 | `Date` | UDFD06 |
| 507 | uDFD07 | `Date` | UDFD07 |
| 508 | uDFD08 | `Date` | UDFD08 |
| 509 | uDFD09 | `Date` | UDFD09 |
| 510 | uDFD10 | `Date` | UDFD10 |
| 511 | uDFD11 | `Date` | UDFD11 |
| 512 | uDFD12 | `Date` | UDFD12 |
| 513 | uDFD13 | `Date` | UDFD13 |
| 514 | uDFD14 | `Date` | UDFD14 |
| 515 | uDFD15 | `Date` | UDFD15 |
| 516 | uDFD16 | `Date` | UDFD16 |
| 517 | uDFD17 | `Date` | UDFD17 |
| 518 | uDFD18 | `Date` | UDFD18 |
| 519 | uDFD19 | `Date` | UDFD19 |
| 520 | uDFD20 | `Date` | UDFD20 |
| 521 | uDFN01 | `Float` | UDFN01 |
| 522 | uDFN02 | `Float` | UDFN02 |
| 523 | uDFN03 | `Float` | UDFN03 |
| 524 | uDFN04 | `Float` | UDFN04 |
| 525 | uDFN05 | `Float` | UDFN05 |
| 526 | uDFN06 | `Float` | UDFN06 |
| 527 | uDFN07 | `Float` | UDFN07 |
| 528 | uDFN08 | `Float` | UDFN08 |
| 529 | uDFN09 | `Float` | UDFN09 |
| 530 | uDFN10 | `Float` | UDFN10 |
| 531 | uDFN11 | `Float` | UDFN11 |
| 532 | uDFN12 | `Float` | UDFN12 |
| 533 | uDFN13 | `Float` | UDFN13 |
| 534 | uDFN14 | `Float` | UDFN14 |
| 535 | uDFN15 | `Float` | UDFN15 |
| 536 | uDFN16 | `Float` | UDFN16 |
| 537 | uDFN17 | `Float` | UDFN17 |
| 538 | uDFN18 | `Float` | UDFN18 |
| 539 | uDFN19 | `Float` | UDFN19 |
| 540 | uDFN20 | `Float` | UDFN20 |
| 541 | uDFN21 | `Float` | UDFN21 |
| 542 | uDFN22 | `Float` | UDFN22 |
| 543 | uDFN23 | `Float` | UDFN23 |
| 544 | uDFN24 | `Float` | UDFN24 |
| 545 | uDFN25 | `Float` | UDFN25 |
| 546 | uDFN26 | `Float` | UDFN26 |
| 547 | uDFN27 | `Float` | UDFN27 |
| 548 | uDFN28 | `Float` | UDFN28 |
| 549 | uDFN29 | `Float` | UDFN29 |
| 550 | uDFN30 | `Float` | UDFN30 |
| 551 | uDFN31 | `Float` | UDFN31 |
| 552 | uDFN32 | `Float` | UDFN32 |
| 553 | uDFN33 | `Float` | UDFN33 |
| 554 | uDFN34 | `Float` | UDFN34 |
| 555 | uDFN35 | `Float` | UDFN35 |
| 556 | uDFN36 | `Float` | UDFN36 |
| 557 | uDFN37 | `Float` | UDFN37 |
| 558 | uDFN38 | `Float` | UDFN38 |
| 559 | uDFN39 | `Float` | UDFN39 |
| 560 | uDFN40 | `Float` | UDFN40 |
| 561 | ualias | `String` | Not in use. |
| 562 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 563 | updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| 564 | updateUser | `Float` | Update User |
| 565 | updatedBy | `String` | Updated By |
| 566 | updatedDate | `DateTime` | Updated Date |
| 567 | uploadDate | `Date` | Upload Date |
| 568 | webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| 569 | webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| 570 | xudescription | `String` | Multi Byte Description in uppercase |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyTravelAgentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRNumberCentral | `String` | AR Number (Central) |
| 3 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 4 | accountBillingContact | `String` | Billing contact person in company. |
| 5 | accountSource | `String` | Account Source |
| 6 | accountType | `String` | Account Type |
| 7 | activeYN | `String` | Active YN |
| 8 | address1 | `String` | Address 1 |
| 9 | address2 | `String` | Address 2 |
| 10 | address3 | `String` | Address 3 |
| 11 | address4 | `String` | Address 4 |
| 12 | allOwnerCodes | `String` | All Owner Codes |
| 13 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 14 | alternateSalutation | `String` | Alternate Salutation |
| 15 | alternateTitle | `String` | Alternate Title |
| 16 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 17 | billingInstruction | `String` | Billing Instruction |
| 18 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 19 | birthDate | `Date` | Birth Date |
| 20 | birthDateStr | `String` | Birth Date Str |
| 21 | birthPlace | `String` | Place of birth. |
| 22 | businessTitle | `String` | Business Title |
| 23 | cExchangeDate | `Date` | Central Xchange Date |
| 24 | cExchangeRate | `Float` | Central Xchange Rate |
| 25 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 26 | centralDefaultKeyword | `String` | Central Default Keyword |
| 27 | centralIATANumberType | `String` | Central IATA Number Type |
| 28 | centralNationality | `String` | Central Nationality |
| 29 | centralNationalityCode | `String` | Central Nationality Code |
| 30 | chainCode | `String` | Chain Code |
| 31 | city | `String` | City |
| 32 | combinedName | `String` | Combined Name |
| 33 | communicationType1 | `String` | Communication Type 1 |
| 34 | communicationType2 | `String` | Communication Type 2 |
| 35 | communicationType3 | `String` | Communication Type 3 |
| 36 | communicationValue1 | `String` | Communication Value 1 |
| 37 | communicationValue2 | `String` | Communication Value 2 |
| 38 | communicationValue3 | `String` | Communication Value 3 |
| 39 | companyAlternate | `String` | Extended Byte Company Name |
| 40 | competition | `String` | Competition |
| 41 | country | `String` | Country |
| 42 | countryCode | `String` | Country Code |
| 43 | creditCardName | `String` | Credit Card Name |
| 44 | creditCardType | `String` | Credit Card Type |
| 45 | creditRating | `String` | Credit Rating |
| 46 | currencyCode | `String` | Currency Code |
| 47 | currencyDescription | `String` | Currency Description |
| 48 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 49 | defaultKeyword | `String` | Default Keyword |
| 50 | deletedFlag | `String` | Deleted Flag |
| 51 | displayName | `String` | Display Name |
| 52 | email | `String` | Email |
| 53 | emailYn | `String` | Email Y/N |
| 54 | envelopeGreeting | `String` | Envelope Greeting |
| 55 | externalId | `String` | External ID |
| 56 | fSubscriptionYn | `String` | F Subscription Y/N |
| 57 | faxNumber | `String` | Fax Number |
| 58 | first | `String` | First |
| 59 | gender | `String` | Gender |
| 60 | guestPrivYn | `String` | Guest Priv Y/N |
| 61 | historyYN | `String` | History YN |
| 62 | holdCode | `String` | Hold Code |
| 63 | iATANumber | `String` | IATA Number |
| 64 | iATANumberType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 65 | iataConsortia | `String` | IATA Consortia |
| 66 | inactiveDate | `DateTime` | Inactive Date |
| 67 | inactiveFlag | `String` | Inactive Flag |
| 68 | industryCode | `String` | Industry Code |
| 69 | insertDate | `DateTime` | Insert Date |
| 70 | insertUser | `String` | Insert User |
| 71 | interest | `String` | Interest Code. |
| 72 | internalDeletedflag | `String` | Deleted Flag |
| 73 | internalInactiveflag | `String` | Inactive Flag |
| 74 | internalOrganizationId | `Float` | Organization ID |
| 75 | internalProfileId | `Float` | Profile ID |
| 76 | jRNUpdateDate | `Date` | JRN Update Date |
| 77 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 78 | languageCode | `String` | Language Code |
| 79 | languageDescription | `String` | Language Description |
| 80 | last | `String` | Last |
| 81 | lastGroup | `String` | Last Group |
| 82 | lastRate | `Float` | Last Rate |
| 83 | lastRoom | `String` | Not used. |
| 84 | lastSource | `String` | Last Source |
| 85 | lastStay | `Date` | Last Stay |
| 86 | legalCompany | `String` | Legal Company |
| 87 | letterGreeting | `String` | Letter Greeting |
| 88 | mailListYN | `String` | Mail List YN |
| 89 | mailType | `String` | The type of mail this user should be sent. |
| 90 | mailYn | `String` | Mail Y/N |
| 91 | mailingActionCode | `String` | Mailing Action Code |
| 92 | marketResearchYn | `String` | Market Research Y/N |
| 93 | markets | `String` | Markets |
| 94 | middle | `String` | Middle |
| 95 | name | `String` | Name |
| 96 | name2 | `String` | Name 2 |
| 97 | name3 | `String` | Name 3 |
| 98 | nationality | `String` | Nationality |
| 99 | nationalityCode | `String` | Nationality Code |
| 100 | negotiatedRateCodes | `String` | Negotiated Rate Codes |
| 101 | nextStay | `Date` | Next Stay |
| 102 | nickname | `String` | The nickname of this individual. |
| 103 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 104 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 105 | phoneNumber | `String` | Phone no. |
| 106 | postalCode | `String` | Postal Code |
| 107 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 108 | primaryOwner | `String` | Primary Owner |
| 109 | primaryOwnerCode | `String` | Primary Owner Code |
| 110 | priority | `String` | Priority |
| 111 | privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 112 | productInterest | `String` | Product Interest |
| 113 | profession | `String` | Profession of the guest |
| 114 | profileID | `Float` | Profile ID |
| 115 | profileType | `String` | Profile Type |
| 116 | propertyRegistered | `String` | Resort for which Job is registered. |
| 117 | protected | `String` | Protected |
| 118 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 119 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 120 | repAccountType | `String` | Reporting Account Type |
| 121 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 122 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 123 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 124 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 125 | repInactiveReason | `String` | Reporting Inactive Reason |
| 126 | repInactiveReasonCode | `String` | Reporting Inactive Reason Code |
| 127 | repIndustryDescription | `String` | Reporting Industry Desc |
| 128 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 129 | repMailActionDescription | `String` | Reporting Mail Action Desc |
| 130 | repMarketsDescription | `String` | Reporting Markets Desc |
| 131 | repNameType | `String` | Reporting Name Type |
| 132 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 133 | repPriority | `String` | Reporting Priority |
| 134 | repPriorityDescription | `String` | Reporting Priority Desc |
| 135 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 136 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 137 | repScopeDescription | `String` | Reporting Scope Desc |
| 138 | repStateCode | `String` | Reporting State Code |
| 139 | repStateDescription | `String` | Reporting State Desc |
| 140 | repTerritory | `String` | Reporting Territory |
| 141 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 142 | repTitle | `String` | Reporting Title |
| 143 | repTitleName | `String` | Reporting Title Name |
| 144 | repVIPName | `String` | Reporting Vip Name |
| 145 | repVIPStatus | `String` | Reporting Vip Status |
| 146 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 147 | salutation | `String` | Salutation Greeting |
| 148 | scope | `String` | Scope |
| 149 | scopeCity | `String` | Scope City |
| 150 | searchName | `String` | The Uppercase value of Last or Company. |
| 151 | searchNameAlternate | `String` | Search Name Alternate |
| 152 | sfirst | `String` | Uppercase value of First Name. |
| 153 | state | `String` | State |
| 154 | stateCode | `String` | State Code |
| 155 | subscribedProperties | `String` | Subscribed Properties |
| 156 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 157 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 158 | taxCategory | `String` | Tax Category |
| 159 | taxID1 | `String` | Tax ID 1 |
| 160 | taxID2 | `String` | Tax ID 2 |
| 161 | taxType | `String` | Tax Type |
| 162 | territory | `String` | Territory |
| 163 | thirdPartyYn | `String` | Third Party Y/N |
| 164 | title | `String` | Title |
| 165 | totalArrivals | `Float` | Total Arrivals |
| 166 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 167 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 168 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 169 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 170 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 171 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 172 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 173 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 174 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 175 | totalFbRevenue | `Float` | Total FB Revenue |
| 176 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 177 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 178 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 179 | totalNonRevenue | `Float` | Total Non Revenue |
| 180 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 181 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 182 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 183 | totalOtherRevenue | `Float` | Total Other Revenue |
| 184 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 185 | totalReservationNights | `Float` | Total Reservation Nights |
| 186 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 187 | totalRevenue | `Float` | Total Revenue |
| 188 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 189 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 190 | totalRoomRevenue | `Float` | Total Room Revenue |
| 191 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 192 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 193 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 194 | traceCode | `String` | Trace Code |
| 195 | uDFC01 | `String` | UDFC01 |
| 196 | uDFC02 | `String` | UDFC02 |
| 197 | uDFC03 | `String` | UDFC03 |
| 198 | uDFC04 | `String` | UDFC04 |
| 199 | uDFC05 | `String` | UDFC05 |
| 200 | uDFC06 | `String` | UDFC06 |
| 201 | uDFC07 | `String` | UDFC07 |
| 202 | uDFC08 | `String` | UDFC08 |
| 203 | uDFC09 | `String` | UDFC09 |
| 204 | uDFC10 | `String` | UDFC10 |
| 205 | uDFC11 | `String` | UDFC11 |
| 206 | uDFC12 | `String` | UDFC12 |
| 207 | uDFC13 | `String` | UDFC13 |
| 208 | uDFC14 | `String` | UDFC14 |
| 209 | uDFC15 | `String` | UDFC15 |
| 210 | uDFC16 | `String` | UDFC16 |
| 211 | uDFC17 | `String` | UDFC17 |
| 212 | uDFC18 | `String` | UDFC18 |
| 213 | uDFC19 | `String` | UDFC19 |
| 214 | uDFC20 | `String` | UDFC20 |
| 215 | uDFC21 | `String` | UDFC21 |
| 216 | uDFC22 | `String` | UDFC22 |
| 217 | uDFC23 | `String` | UDFC23 |
| 218 | uDFC24 | `String` | UDFC24 |
| 219 | uDFC25 | `String` | UDFC25 |
| 220 | uDFC26 | `String` | UDFC26 |
| 221 | uDFC27 | `String` | UDFC27 |
| 222 | uDFC28 | `String` | UDFC28 |
| 223 | uDFC29 | `String` | UDFC29 |
| 224 | uDFC30 | `String` | UDFC30 |
| 225 | uDFC31 | `String` | UDFC31 |
| 226 | uDFC32 | `String` | UDFC32 |
| 227 | uDFC33 | `String` | UDFC33 |
| 228 | uDFC34 | `String` | UDFC34 |
| 229 | uDFC35 | `String` | UDFC35 |
| 230 | uDFC36 | `String` | UDFC36 |
| 231 | uDFC37 | `String` | UDFC37 |
| 232 | uDFC38 | `String` | UDFC38 |
| 233 | uDFC39 | `String` | UDFC39 |
| 234 | uDFC40 | `String` | UDFC40 |
| 235 | uDFD01 | `Date` | UDFD01 |
| 236 | uDFD02 | `Date` | UDFD02 |
| 237 | uDFD03 | `Date` | UDFD03 |
| 238 | uDFD04 | `Date` | UDFD04 |
| 239 | uDFD05 | `Date` | UDFD05 |
| 240 | uDFD06 | `Date` | UDFD06 |
| 241 | uDFD07 | `Date` | UDFD07 |
| 242 | uDFD08 | `Date` | UDFD08 |
| 243 | uDFD09 | `Date` | UDFD09 |
| 244 | uDFD10 | `Date` | UDFD10 |
| 245 | uDFD11 | `Date` | UDFD11 |
| 246 | uDFD12 | `Date` | UDFD12 |
| 247 | uDFD13 | `Date` | UDFD13 |
| 248 | uDFD14 | `Date` | UDFD14 |
| 249 | uDFD15 | `Date` | UDFD15 |
| 250 | uDFD16 | `Date` | UDFD16 |
| 251 | uDFD17 | `Date` | UDFD17 |
| 252 | uDFD18 | `Date` | UDFD18 |
| 253 | uDFD19 | `Date` | UDFD19 |
| 254 | uDFD20 | `Date` | UDFD20 |
| 255 | uDFN01 | `Float` | UDFN01 |
| 256 | uDFN02 | `Float` | UDFN02 |
| 257 | uDFN03 | `Float` | UDFN03 |
| 258 | uDFN04 | `Float` | UDFN04 |
| 259 | uDFN05 | `Float` | UDFN05 |
| 260 | uDFN06 | `Float` | UDFN06 |
| 261 | uDFN07 | `Float` | UDFN07 |
| 262 | uDFN08 | `Float` | UDFN08 |
| 263 | uDFN09 | `Float` | UDFN09 |
| 264 | uDFN10 | `Float` | UDFN10 |
| 265 | uDFN11 | `Float` | UDFN11 |
| 266 | uDFN12 | `Float` | UDFN12 |
| 267 | uDFN13 | `Float` | UDFN13 |
| 268 | uDFN14 | `Float` | UDFN14 |
| 269 | uDFN15 | `Float` | UDFN15 |
| 270 | uDFN16 | `Float` | UDFN16 |
| 271 | uDFN17 | `Float` | UDFN17 |
| 272 | uDFN18 | `Float` | UDFN18 |
| 273 | uDFN19 | `Float` | UDFN19 |
| 274 | uDFN20 | `Float` | UDFN20 |
| 275 | uDFN21 | `Float` | UDFN21 |
| 276 | uDFN22 | `Float` | UDFN22 |
| 277 | uDFN23 | `Float` | UDFN23 |
| 278 | uDFN24 | `Float` | UDFN24 |
| 279 | uDFN25 | `Float` | UDFN25 |
| 280 | uDFN26 | `Float` | UDFN26 |
| 281 | uDFN27 | `Float` | UDFN27 |
| 282 | uDFN28 | `Float` | UDFN28 |
| 283 | uDFN29 | `Float` | UDFN29 |
| 284 | uDFN30 | `Float` | UDFN30 |
| 285 | uDFN31 | `Float` | UDFN31 |
| 286 | uDFN32 | `Float` | UDFN32 |
| 287 | uDFN33 | `Float` | UDFN33 |
| 288 | uDFN34 | `Float` | UDFN34 |
| 289 | uDFN35 | `Float` | UDFN35 |
| 290 | uDFN36 | `Float` | UDFN36 |
| 291 | uDFN37 | `Float` | UDFN37 |
| 292 | uDFN38 | `Float` | UDFN38 |
| 293 | uDFN39 | `Float` | UDFN39 |
| 294 | uDFN40 | `Float` | UDFN40 |
| 295 | updateDate | `DateTime` | Update Date |
| 296 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 297 | updateUser | `String` | Update User |
| 298 | vipName | `String` | VIP Name |
| 299 | vipStatus | `String` | VIP Status |
| 300 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 301 | xfirstName | `String` | Xfirst Name |
| 302 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyAllotmentStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionId | `Float` | Action ID |
| 2 | actualAverageRoomRate | `Float` | Actual Average Room Rate |
| 3 | actualFBRevenue | `Float` | Actual F&B Revenue |
| 4 | actualOtherRevenue | `Float` | Other revenue |
| 5 | actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| 6 | actualRoomRevenue | `Float` | Actual revenue of the room |
| 7 | addInfo | `String` | Add Info |
| 8 | agentContactNameId | `Float` | Agent Contact Name ID |
| 9 | agentNameId | `Float` | Agent Name ID |
| 10 | agentprofileid | `Float` | Agentprofileid |
| 11 | allAliases | `String` | All Aliases |
| 12 | allBlockOwners | `String` | All Block Owners |
| 13 | allCateringOwners | `String` | All Catering Owners |
| 14 | allCompanyContacts | `String` | All Company Contacts |
| 15 | allRateCodes | `String` | All Rate Codes |
| 16 | allRoomOwners | `String` | All Room Owners |
| 17 | allRoomPools | `String` | All Room Pools |
| 18 | allRoomTypes | `String` | All Room Types |
| 19 | allSourceContacts | `String` | All Source Contacts |
| 20 | allTravelAgentContacts | `String` | All Travel Agent Contacts |
| 21 | allowPickup | `String` | Allow a pickup for a group with this booking status |
| 22 | alternateBlockName | `String` | Multi Byte Description Field |
| 23 | alternateDates | `String` | Alternate Dates |
| 24 | arrivalTime | `Date` | Arrival Time |
| 25 | attachmentURL | `String` | URL pointing to Lead Attachments. |
| 26 | attendeesGuaranteed | `Float` | Attendees Guaranteed |
| 27 | autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| 28 | averageRate | `Float` | Average Rate |
| 29 | bEOLastPrint | `Date` | Date when the BEO report was last printed for this business block. |
| 30 | beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| 31 | blockAlias | `String` | Block Alias |
| 32 | blockDateActual | `Date` | Block Date Actual |
| 33 | blockDateDefinite | `Date` | Block Date Definite |
| 34 | blockDateProspect | `Date` | Block Date Prospect |
| 35 | blockDateTentative | `Date` | Block Date Tentative |
| 36 | blockDescription | `String` | Block Description |
| 37 | blockOwnerCode | `String` | Block Owner Code |
| 38 | blockOwnerFullName | `String` | Block Owner Full Name |
| 39 | blockPackage | `String` | Block Package |
| 40 | blockPackageDescription | `String` | Block Package Description |
| 41 | blockStatus | `String` | Block Status |
| 42 | blockStatusDescription | `String` | Block Status Description |
| 43 | blockTypeCode | `String` | Block Type Code |
| 44 | blockTypeCodeDescription | `String` | Block Type Code Description |
| 45 | blockpackageid | `String` | Blockpackageid |
| 46 | bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| 47 | bookingMethodOrderBy | `Float` | Booking Method Order By |
| 48 | bookingStatusOrder | `Float` | Booking Status Order |
| 49 | bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| 50 | bookingTypeDescription | `String` | Booking Type Description |
| 51 | bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| 52 | bookingsourceid | `String` | Bookingsourceid |
| 53 | bookingstatusid | `String` | Bookingstatusid |
| 54 | bookingtypeid | `String` | Bookingtypeid |
| 55 | breakfastDescription | `String` | Breakfast Description |
| 56 | breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| 57 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 58 | breakfastIncluded | `String` | Breakfast Included |
| 59 | breakfastPrice | `Float` | Breakfast Price |
| 60 | bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| 61 | bwiUrl | `String` | URL populated bu CRS. |
| 62 | cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| 63 | cBreakfastPrice | `Float` | Central Bfst Price |
| 64 | cCompRoomValue | `Float` | Central Comp Room Value |
| 65 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 66 | cExchangeDate | `Date` | Central Xchange Date |
| 67 | cExchangeRate | `Float` | Central Xchange Rate |
| 68 | cFBCommission1 | `Float` | Central Fb Commission 1 |
| 69 | cFBCommission2 | `Float` | Central Fb Commission 2 |
| 70 | cPorteragePrice | `Float` | Central Porterage Price |
| 71 | cRoomCommission1 | `Float` | Central Rm Commission 1 |
| 72 | cRoomCommission2 | `Float` | Central Rm Commission 2 |
| 73 | cServiceCharge | `Float` | Central Service Charge |
| 74 | cServiceFee | `Float` | Central Service Fee |
| 75 | cRSGtdYn | `String` | CRS Guaranteed Y/N |
| 76 | cancelRule | `String` | Not Used |
| 77 | canceldestinationid | `String` | Canceldestinationid |
| 78 | cancellationDestination | `String` | Cancellation Destination |
| 79 | cancellationDestinationDescription | `String` | Cancellation Destination Description |
| 80 | cancellationNumber | `Float` | Cancellation Number |
| 81 | cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| 82 | cancellationreasonid | `String` | Cancellationreasonid |
| 83 | catCutoff | `Date` | Catering Cutoff |
| 84 | catDateProspect | `Date` | Cat Date Prospect |
| 85 | catOwner | `Float` | Catering Owner |
| 86 | catOwnerProperty | `String` | Property of Catering Owner |
| 87 | catReturnToInventory | `String` | Cat Return To Inventory |
| 88 | catStartingStatus | `String` | Cat Starting Status |
| 89 | catcurrencyid | `String` | Catcurrencyid |
| 90 | cateringCancellationDate | `Date` | Catering Cancellation Date |
| 91 | cateringCancellationDescription | `String` | Catering Cancellation Description |
| 92 | cateringCancellationNumber | `Float` | Catering Cancellation Number |
| 93 | cateringCancellationReason | `String` | Catering Cancellation Reason |
| 94 | cateringCurrency | `String` | Catering Currency |
| 95 | cateringDateActual | `Date` | Catering Date Actual |
| 96 | cateringDecisionDate | `Date` | Catering Decision Date |
| 97 | cateringDeductInventory | `String` | Catering Deduct Inventory |
| 98 | cateringExchangeRate | `Float` | Catering Exchange Rate |
| 99 | cateringFollowupDate | `Date` | Catering Followup Date |
| 100 | cateringOnlyYN | `String` | Catering only Revenue. |
| 101 | cateringOrderBy | `Float` | Catering Order By |
| 102 | cateringOwnerCode | `String` | Catering Owner Code |
| 103 | cateringOwnerFullName | `String` | Catering Owner Full Name |
| 104 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 105 | cateringQuoteCurrency | `String` | Catering Quote Currency |
| 106 | cateringStatus | `String` | Catering Status |
| 107 | cateringStatusColor | `String` | Catering Status Color |
| 108 | cateringStatusDescription | `String` | Catering Status Description |
| 109 | cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 110 | cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| 111 | cateringcurrencyid | `String` | Cateringcurrencyid |
| 112 | cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| 113 | cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| 114 | cateringstatusid | `String` | Cateringstatusid |
| 115 | cenralFBRevenue | `Float` | Cenral FB Revenue |
| 116 | centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| 117 | centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| 118 | centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| 119 | centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| 120 | centralAverageRoomRate | `Float` | Central Average Room Rate |
| 121 | centralBlockPackage | `String` | Central Block Package |
| 122 | centralBlockPackageDescription | `String` | Central Block Package Description |
| 123 | centralBlockStatus | `String` | Central Block Status |
| 124 | centralBlockStatusDescription | `String` | Central Block Status Description |
| 125 | centralBlockTypeCode | `String` | Central Block Type Code |
| 126 | centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| 127 | centralBookingType | `String` | Central Booking Type |
| 128 | centralBookingTypeDescription | `String` | Central Booking Type Description |
| 129 | centralCancellationDestination | `String` | Central Cancellation Destination |
| 130 | centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| 131 | centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| 132 | centralCateringStatus | `String` | Central Catering Status |
| 133 | centralCateringStatusDescription | `String` | Central Catering Status Description |
| 134 | centralConversionCode | `String` | Central Conversion Code |
| 135 | centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| 136 | centralIndustryCode | `String` | Central Industry Code |
| 137 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 138 | centralMarketDescription | `String` | Central Market Description |
| 139 | centralMarketCode | `String` | Central Market code |
| 140 | centralMeetingBudget | `Float` | Central Meeting Budget |
| 141 | centralMeetingRevenue | `Float` | Central Meeting Revenue |
| 142 | centralOriginCode | `String` | Central Origin Code |
| 143 | centralOriginCodeDescription | `String` | Central Origin Code Description |
| 144 | centralOtherRevenue | `Float` | Central Other Revenue |
| 145 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 146 | centralPayment | `String` | Central Payment |
| 147 | centralPaymentDescription | `String` | Central Payment Description |
| 148 | centralRankingCode | `String` | Central Ranking Code |
| 149 | centralRankingCodeDescription | `String` | Central Ranking Code Description |
| 150 | centralReservationMethodCode | `String` | Central Reservation Method Code |
| 151 | centralReservationMethodDescription | `String` | Central Reservation Method Description |
| 152 | centralReservationType | `String` | Central Reservation Type |
| 153 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 154 | centralRoomRevenue | `Float` | Central Room Revenue |
| 155 | centralSourceCode | `String` | Central Source Code |
| 156 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 157 | centralTaxAmount | `Float` | Central Tax Amount |
| 158 | channelid | `String` | Channelid |
| 159 | code | `String` | Code |
| 160 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 161 | comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| 162 | comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| 163 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 164 | comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 165 | comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 166 | commissionAmount | `String` | Commission Amount |
| 167 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 168 | commissionableYn | `String` | Commissionable Y/N |
| 169 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 170 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 171 | compRooms | `Float` | Number of complimentary Rooms |
| 172 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 173 | companyAll | `String` | Company All |
| 174 | companyNameId | `Float` | Company Name ID |
| 175 | companyprofileid | `Float` | Companyprofileid |
| 176 | competition | `String` | Competition |
| 177 | contactNameId | `Float` | Contact Name ID |
| 178 | contactprofileid | `Float` | Contactprofileid |
| 179 | contractNumber | `String` | Contract Number |
| 180 | controlBlockLocally | `String` | Control Block Y/N |
| 181 | conversionCode | `String` | Conversion Code |
| 182 | coversionCodeDescription | `String` | Coversion Code Description |
| 183 | createdBy | `String` | The name of the user who created the record. |
| 184 | createdDate | `DateTime` | Created Date |
| 185 | createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| 186 | creditCardId | `Float` | Credit Card ID |
| 187 | currency | `String` | Currency |
| 188 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 189 | dateAcl | `Date` | Date Acl |
| 190 | dateCfl | `Date` | Date Cfl |
| 191 | dateDefinite | `Date` | Date Definite |
| 192 | dateLsl | `Date` | Date Lsl |
| 193 | dateOpenedForPickup | `Date` | Date Opened for Pickup |
| 194 | datePel | `Date` | Date Pel |
| 195 | dateTdl | `Date` | Date Tdl |
| 196 | dateTentative | `Date` | Date Tentative |
| 197 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 198 | deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| 199 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 200 | deletedflag | `String` | Deleted Flag |
| 201 | departureTime | `Date` | Departure Time |
| 202 | description | `String` | Description |
| 203 | distributed | `String` | Distributed |
| 204 | distributedDate | `Date` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| 205 | dmlSeqNumber | `Float` | Dml Sequence No |
| 206 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 207 | downloadDate | `Date` | Download Date |
| 208 | downloadResort | `String` | Download Property |
| 209 | downloadSrep | `Float` | Download Srep |
| 210 | dueDate | `Date` | Due Date |
| 211 | dueDateOrd | `Date` | Due Date Sorting Column. |
| 212 | endDate | `Date` | End Date |
| 213 | endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| 214 | endbusinessdate | `Date` | Endbusinessdate |
| 215 | eventAttendees | `Float` | Event Attendees |
| 216 | exchangePostingType | `String` | Exchange Posting Type |
| 217 | exchangeRate | `Float` | Exchange Rate |
| 218 | exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| 219 | externalReference | `String` | External Reference |
| 220 | externalRfpId | `String` | External RFP ID. |
| 221 | externalRfpSystem | `String` | External RFP System Identification Code. |
| 222 | externallyLocked | `String` | Externally Locked |
| 223 | fBRevenue | `Float` | Projected F&B Revenue. |
| 224 | fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| 225 | fbCommission1 | `Float` | stores FB commission for Agent 1 |
| 226 | fbCommission2 | `Float` | stores FB commission for Agent 2 |
| 227 | fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| 228 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 229 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 230 | fitdiscounttype | `String` | Fitdiscounttype |
| 231 | flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| 232 | followupDate | `Date` | Followup Date |
| 233 | fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| 234 | functionType | `String` | Function Type |
| 235 | giid | `String` | Group IATA Number. |
| 236 | greekContractNr | `String` | Greek Contract Number. |
| 237 | groupAccountID | `Float` | Group Account ID |
| 238 | guaranteecodeid | `String` | Guaranteecodeid |
| 239 | guaranteedRate | `String` | Rate Guaranteed Y/N. |
| 240 | guaranteedYN | `String` | Guaranteed YN |
| 241 | hideacctinfoflag | `String` | Hideacctinfoflag |
| 242 | hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| 243 | hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| 244 | hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| 245 | hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| 246 | hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| 247 | hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| 248 | hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| 249 | hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| 250 | hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| 251 | inactiveDate | `Date` | Inactive Date |
| 252 | inactiveflag | `String` | Inactive Flag |
| 253 | industryCode | `String` | Indicates the Non-Compete code of a block. |
| 254 | industryCodeDescription | `String` | Industry Code Description |
| 255 | info | `String` | Not Used |
| 256 | informationBoard | `String` | Information Board |
| 257 | insertUser | `Float` | Insert User |
| 258 | inventoryControl | `String` | Inventory Control |
| 259 | inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| 260 | inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| 261 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 262 | items | `String` | Items |
| 263 | jRNUpdateDate | `Date` | JRN Update Date |
| 264 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 265 | keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| 266 | laptopChange | `Float` | Laptop Change |
| 267 | leadOrigin | `String` | Lead Origin |
| 268 | leadSentYN | `String` | Lead Sent YN |
| 269 | leadSource | `String` | Lead Source |
| 270 | leadType | `String` | Lead Type |
| 271 | leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| 272 | leaderrorflag | `String` | Leaderrorflag |
| 273 | leadisnewflag | `String` | Leadisnewflag |
| 274 | leadoriginid | `String` | Leadoriginid |
| 275 | leadreceivedflag | `String` | Leadreceivedflag |
| 276 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 277 | leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| 278 | leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| 279 | leadserverpendingflag | `String` | Leadserverpendingflag |
| 280 | leadsourceid | `String` | Leadsourceid |
| 281 | leadstatus | `String` | Leadstatus |
| 282 | linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 283 | locationID | `String` | Internal ID to uniquely identify the Property |
| 284 | lostTo | `String` | Competitor to whom the booking was lost. |
| 285 | mainmarket | `String` | Mainmarket |
| 286 | mainmarketid | `String` | Mainmarketid |
| 287 | manuallyCutoffYN | `String` | Block was cutoff manullay |
| 288 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 289 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 290 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 291 | marketCode | `String` | Market  Code |
| 292 | marketDescription | `String` | Market Description |
| 293 | marketid | `String` | Marketid |
| 294 | masterBlockID | `Float` | Parent Block ID |
| 295 | masterBlockProperty | `String` | Parent Resort |
| 296 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 297 | meetingBudget | `Float` | Meeting Budget |
| 298 | meetingRevenue | `Float` | Meeting Revenue for SFA |
| 299 | offsetType | `String` | Offset Type |
| 300 | orderBy | `Float` | Order By |
| 301 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 302 | originCode | `String` | Origin Code |
| 303 | originCodeDescription | `String` | Origin Code Description |
| 304 | originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| 305 | originalEndDate | `Date` | Original End Date |
| 306 | originalRateCode | `String` | Not used |
| 307 | originalStartDate | `Date` | Original Start Date |
| 308 | originalratecodeid | `String` | Originalratecodeid |
| 309 | ormsBlockClass | `String` | ORMS Block Class |
| 310 | ormsFinalBlock | `String` | ORMS Final Block |
| 311 | ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| 312 | ormsTransientBlock | `String` | ORMS Transient Block |
| 313 | otherRevenue | `Float` | Projected Other Revenue. |
| 314 | owner | `Float` | Owner |
| 315 | ownerResort | `String` | Owner Property |
| 316 | owneremployeeid | `Float` | Owneremployeeid |
| 317 | ownerlocationd | `String` | Ownerlocationd |
| 318 | payment | `String` | Payment |
| 319 | paymentDescription | `String` | Payment Description |
| 320 | paymentmethodid | `String` | Paymentmethodid |
| 321 | personsPerRoom | `Float` | Persons Per Room |
| 322 | porterageIncluded | `String` | Porterage Included |
| 323 | porteragePrice | `Float` | Porterage Price |
| 324 | potAverageRoomRate | `Float` | Pot Average Room Rate |
| 325 | potFbRevenue1 | `Float` | Pot FB Revenue1 |
| 326 | potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| 327 | potRoomNights | `Float` | Projected Room Nights. |
| 328 | potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| 329 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 330 | printRate | `String` | Print Rate |
| 331 | profileId | `Float` | Profile ID |
| 332 | program | `String` | Program |
| 333 | property | `String` | Code to uniquely identify the Property |
| 334 | proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| 335 | proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| 336 | proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| 337 | proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| 338 | proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| 339 | proposalSentDate | `Date` | Proposal Sent Date |
| 340 | proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| 341 | proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| 342 | proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| 343 | proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| 344 | proposalViewToken | `String` | Proposal View Token |
| 345 | publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| 346 | rankingCode | `String` | Indicates the ranking of a block. |
| 347 | rankingCodeDescription | `String` | Ranking Code Description |
| 348 | rateCode | `String` | Rate Code |
| 349 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 350 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 351 | rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 352 | rateTier | `Float` | Rate Tier |
| 353 | ratecodeid | `String` | Ratecodeid |
| 354 | readyForDistribution | `String` | Ready for Distribution |
| 355 | regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| 356 | repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| 357 | repBsOrderBy | `Float` | Rep Bs Order By |
| 358 | repCatOrderBy | `Float` | Rep Cat Order By |
| 359 | replDate | `Date` | Reply Date |
| 360 | replVia | `String` | Reply Communication Method |
| 361 | replstatus | `String` | Lead Replystatus [ACL|TDL] |
| 362 | replyBy | `Float` | Reply By |
| 363 | representative | `String` | Representative |
| 364 | reservationMethod | `String` | Reservation Method |
| 365 | reservationType | `String` | Reservation Type |
| 366 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 367 | reservationid | `Float` | Reservationid |
| 368 | reserveInventoryYN | `String` | Reserve Inventory YN |
| 369 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 370 | resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| 371 | respTime | `Float` | Response Time. |
| 372 | respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| 373 | returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| 374 | rivMarketSegment | `String` | Not used |
| 375 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 376 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 377 | roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| 378 | roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| 379 | roomNightsSold | `Float` | Room Nights Sold |
| 380 | roomOwnerCode | `String` | Room Owner Code |
| 381 | roomOwnerFullName | `String` | Room Owner Full Name |
| 382 | roomRevenue | `Float` | Projected Room Revenue. |
| 383 | roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| 384 | roomStatus | `String` | Room Status |
| 385 | roomingListDue | `Date` | Rooming List Due |
| 386 | roomingListRules | `String` | Stores Rooming List Rules. |
| 387 | roomsCancellationDate | `Date` | Rooms Cancellation Date |
| 388 | roomsCancellationReason | `String` | Rooms Cancellation Reason |
| 389 | roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| 390 | roomsCurrency | `String` | Rooms Currency |
| 391 | roomsDecisionDate | `Date` | Rooms Decision Date |
| 392 | roomsExchangeRate | `Float` | Rooms Exchange Rate |
| 393 | roomsOwner | `Float` | Rooms Owner |
| 394 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 395 | roomsPerDay | `Float` | Rooms Per Day |
| 396 | roomsQuoteCurrency | `String` | Rooms Quote Currency |
| 397 | roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| 398 | salesId | `String` | Not used |
| 399 | sbegindate | `Date` | Sbegindate |
| 400 | scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| 401 | sellThruYn | `String` | Sell Thru Indicator. |
| 402 | sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| 403 | senddate | `Date` | Senddate |
| 404 | sentBy | `Float` | Sent By |
| 405 | sentDate | `Date` | Sent Date |
| 406 | sentVia | `String` | Sent Via |
| 407 | serviceCharge | `Float` | Service Charge |
| 408 | serviceFee | `Float` | Service Fee Amount per room/night |
| 409 | serviceFeeYn | `String` | Service Fee applies? |
| 410 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 411 | servicePerc | `Float` | Service Percentage included. |
| 412 | shoulderEnd | `Date` | Shoulder End |
| 413 | shoulderStart | `Date` | Shoulder Start |
| 414 | showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 415 | snapshotSetup | `String` | Snapshot has been created |
| 416 | sourceCode | `String` | Source Code |
| 417 | sourceCodeDescription | `String` | Source Code Description |
| 418 | sourceContactAll | `String` | Source Contact All |
| 419 | sourceNameId | `Float` | Source Name ID |
| 420 | sourceid | `Float` | Sourceid |
| 421 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 422 | startDate | `Date` | Start Date |
| 423 | startingStatus | `String` | Booking starting status (intial pickup) |
| 424 | status | `String` | Status |
| 425 | statusColor | `String` | Status Color |
| 426 | statusType | `String` | Type of booking status (initial) |
| 427 | subAllocationYN | `String` | Sub Allocation YN |
| 428 | superSearchIndexText | `String` | Super Search Index Text |
| 429 | suppressRate | `String` | Suppress Rate |
| 430 | syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the ALLOTMENTSTATISTICS_detail trigger. |
| 431 | synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| 432 | taxAmount | `Float` | Tax Amount |
| 433 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 434 | taxIncludedYn | `String` | Tax is included in this rate. |
| 435 | taxType | `String` | Tax Type |
| 436 | taxtypeid | `String` | Taxtypeid |
| 437 | tbdRates | `String` | To be Determined Rates |
| 438 | tdlReason | `String` | Tdl Reason |
| 439 | tentativeLevel | `Float` | Not used |
| 440 | tlpResponseid | `String` | Stores the TLPe - Response ID |
| 441 | tlpUrl | `String` | Stores the TLPe - Result URL. |
| 442 | tourCode | `String` | Tour Code. |
| 443 | traceCode | `String` | Trace Code |
| 444 | traceDescription | `String` | Trace Description |
| 445 | trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 446 | travelAgentAll | `String` | Travel Agent All |
| 447 | travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| 448 | turndownreasonid | `Float` | Turndownreasonid |
| 449 | uDFC01 | `String` | UDFC01 |
| 450 | uDFC02 | `String` | UDFC02 |
| 451 | uDFC03 | `String` | UDFC03 |
| 452 | uDFC04 | `String` | UDFC04 |
| 453 | uDFC05 | `String` | UDFC05 |
| 454 | uDFC06 | `String` | UDFC06 |
| 455 | uDFC07 | `String` | UDFC07 |
| 456 | uDFC08 | `String` | UDFC08 |
| 457 | uDFC09 | `String` | UDFC09 |
| 458 | uDFC10 | `String` | UDFC10 |
| 459 | uDFC11 | `String` | UDFC11 |
| 460 | uDFC12 | `String` | UDFC12 |
| 461 | uDFC13 | `String` | UDFC13 |
| 462 | uDFC14 | `String` | UDFC14 |
| 463 | uDFC15 | `String` | UDFC15 |
| 464 | uDFC16 | `String` | UDFC16 |
| 465 | uDFC17 | `String` | UDFC17 |
| 466 | uDFC18 | `String` | UDFC18 |
| 467 | uDFC19 | `String` | UDFC19 |
| 468 | uDFC20 | `String` | UDFC20 |
| 469 | uDFC21 | `String` | UDFC21 |
| 470 | uDFC22 | `String` | UDFC22 |
| 471 | uDFC23 | `String` | UDFC23 |
| 472 | uDFC24 | `String` | UDFC24 |
| 473 | uDFC25 | `String` | UDFC25 |
| 474 | uDFC26 | `String` | UDFC26 |
| 475 | uDFC27 | `String` | UDFC27 |
| 476 | uDFC28 | `String` | UDFC28 |
| 477 | uDFC29 | `String` | UDFC29 |
| 478 | uDFC30 | `String` | UDFC30 |
| 479 | uDFC31 | `String` | UDFC31 |
| 480 | uDFC32 | `String` | UDFC32 |
| 481 | uDFC33 | `String` | UDFC33 |
| 482 | uDFC34 | `String` | UDFC34 |
| 483 | uDFC35 | `String` | UDFC35 |
| 484 | uDFC36 | `String` | UDFC36 |
| 485 | uDFC37 | `String` | UDFC37 |
| 486 | uDFC38 | `String` | UDFC38 |
| 487 | uDFC39 | `String` | UDFC39 |
| 488 | uDFC40 | `String` | UDFC40 |
| 489 | uDFD01 | `Date` | UDFD01 |
| 490 | uDFD02 | `Date` | UDFD02 |
| 491 | uDFD03 | `Date` | UDFD03 |
| 492 | uDFD04 | `Date` | UDFD04 |
| 493 | uDFD05 | `Date` | UDFD05 |
| 494 | uDFD06 | `Date` | UDFD06 |
| 495 | uDFD07 | `Date` | UDFD07 |
| 496 | uDFD08 | `Date` | UDFD08 |
| 497 | uDFD09 | `Date` | UDFD09 |
| 498 | uDFD10 | `Date` | UDFD10 |
| 499 | uDFD11 | `Date` | UDFD11 |
| 500 | uDFD12 | `Date` | UDFD12 |
| 501 | uDFD13 | `Date` | UDFD13 |
| 502 | uDFD14 | `Date` | UDFD14 |
| 503 | uDFD15 | `Date` | UDFD15 |
| 504 | uDFD16 | `Date` | UDFD16 |
| 505 | uDFD17 | `Date` | UDFD17 |
| 506 | uDFD18 | `Date` | UDFD18 |
| 507 | uDFD19 | `Date` | UDFD19 |
| 508 | uDFD20 | `Date` | UDFD20 |
| 509 | uDFN01 | `Float` | UDFN01 |
| 510 | uDFN02 | `Float` | UDFN02 |
| 511 | uDFN03 | `Float` | UDFN03 |
| 512 | uDFN04 | `Float` | UDFN04 |
| 513 | uDFN05 | `Float` | UDFN05 |
| 514 | uDFN06 | `Float` | UDFN06 |
| 515 | uDFN07 | `Float` | UDFN07 |
| 516 | uDFN08 | `Float` | UDFN08 |
| 517 | uDFN09 | `Float` | UDFN09 |
| 518 | uDFN10 | `Float` | UDFN10 |
| 519 | uDFN11 | `Float` | UDFN11 |
| 520 | uDFN12 | `Float` | UDFN12 |
| 521 | uDFN13 | `Float` | UDFN13 |
| 522 | uDFN14 | `Float` | UDFN14 |
| 523 | uDFN15 | `Float` | UDFN15 |
| 524 | uDFN16 | `Float` | UDFN16 |
| 525 | uDFN17 | `Float` | UDFN17 |
| 526 | uDFN18 | `Float` | UDFN18 |
| 527 | uDFN19 | `Float` | UDFN19 |
| 528 | uDFN20 | `Float` | UDFN20 |
| 529 | uDFN21 | `Float` | UDFN21 |
| 530 | uDFN22 | `Float` | UDFN22 |
| 531 | uDFN23 | `Float` | UDFN23 |
| 532 | uDFN24 | `Float` | UDFN24 |
| 533 | uDFN25 | `Float` | UDFN25 |
| 534 | uDFN26 | `Float` | UDFN26 |
| 535 | uDFN27 | `Float` | UDFN27 |
| 536 | uDFN28 | `Float` | UDFN28 |
| 537 | uDFN29 | `Float` | UDFN29 |
| 538 | uDFN30 | `Float` | UDFN30 |
| 539 | uDFN31 | `Float` | UDFN31 |
| 540 | uDFN32 | `Float` | UDFN32 |
| 541 | uDFN33 | `Float` | UDFN33 |
| 542 | uDFN34 | `Float` | UDFN34 |
| 543 | uDFN35 | `Float` | UDFN35 |
| 544 | uDFN36 | `Float` | UDFN36 |
| 545 | uDFN37 | `Float` | UDFN37 |
| 546 | uDFN38 | `Float` | UDFN38 |
| 547 | uDFN39 | `Float` | UDFN39 |
| 548 | uDFN40 | `Float` | UDFN40 |
| 549 | ualias | `String` | Not in use. |
| 550 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 551 | updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| 552 | updateUser | `Float` | Update User |
| 553 | updatedBy | `String` | Updated By |
| 554 | updatedDate | `DateTime` | Updated Date |
| 555 | uploadDate | `Date` | Upload Date |
| 556 | webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| 557 | webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| 558 | xudescription | `String` | Multi Byte Description in uppercase |

[⬆ Back to Query](#query)

---

### StatisticsReservationsDailyContactDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 2 | aRNumber | `String` | AR Number |
| 3 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 4 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 5 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 6 | accountType | `String` | Account Type |
| 7 | accountsource | `String` | Accountsource |
| 8 | acctContact | `String` | Billing contact person in company. |
| 9 | actionCode | `String` | Action Code |
| 10 | activeFlag | `String` | Active Flag |
| 11 | addressType | `String` | Address Type |
| 12 | address1 | `String` | Address1 |
| 13 | address2 | `String` | Address2 |
| 14 | address3 | `String` | Address3 |
| 15 | address4 | `String` | Address4 |
| 16 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 17 | allProperties | `String` | All Properties |
| 18 | allSalesRepCodes | `String` | All Sales Reporting Codes |
| 19 | alternateFirstName | `String` | Alternate First Name |
| 20 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 21 | alternateLanguageDescription | `String` | Alternate Language Description |
| 22 | alternateName | `String` | Alternate Name |
| 23 | alternateTitle | `String` | Alternate Title |
| 24 | arNumberCentral | `String` | AR No Central |
| 25 | autoPopRouting | `String` | Auto Pop Routing |
| 26 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 27 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 28 | billingCode | `String` | The billing code for this name record. |
| 29 | billingInstruction | `String` | Billing Instruction |
| 30 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 31 | birthCountry | `String` | Country of birth. |
| 32 | birthDate | `Date` | Birth Date |
| 33 | birthDateStr | `String` | Birth Date Str |
| 34 | birthPlace | `String` | Place of birth. |
| 35 | businessSegment | `String` | Business Segment |
| 36 | businessSegmentDescription | `String` | Business Segment Description |
| 37 | businessTitle | `String` | Business Title |
| 38 | cRSNameid | `Float` | The unique identifier of the CRS |
| 39 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 40 | centralBusinessSegment | `String` | Central Business Segment |
| 41 | centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| 42 | centralInactiveReason | `String` | Central Inactive Reason |
| 43 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 44 | centralInfluence | `String` | Central Influence |
| 45 | centralInfluenceDescription | `String` | Central Influence Description |
| 46 | centralKeyword | `String` | Central Keyword |
| 47 | centralMailActionDescription | `String` | Central Mail Action Description |
| 48 | centralNationality | `String` | Central Nationality |
| 49 | centralNationalityDescription | `String` | Central Nationality Description |
| 50 | centralScope | `String` | Central Scope |
| 51 | centralScopeCity | `String` | Central Scope City |
| 52 | centralScopeCityDescription | `String` | Central Scope City Description |
| 53 | centralScopeDescription | `String` | Central Scope Description |
| 54 | centralTerritory | `String` | Central Territory |
| 55 | centralTerritoryDescription | `String` | Central Territory Description |
| 56 | centralTitle | `String` | Central Title |
| 57 | centralVIPCode | `String` | Central VIP Code |
| 58 | centralVIPCodeDescription | `String` | Central VIP Code Description |
| 59 | chainCode | `String` | Chain Code |
| 60 | city | `String` | City |
| 61 | cityExt | `String` | City Ext |
| 62 | clientID | `String` | Client ID |
| 63 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 64 | combinedName | `String` | Combined Name |
| 65 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 66 | commissionCode | `String` | Commission Code |
| 67 | commissionCurrencyId | `String` | Comm Curr ID |
| 68 | commissionid | `String` | Commissionid |
| 69 | communicationRole1 | `String` | Communication Role1 |
| 70 | communicationRole2 | `String` | Communication Role2 |
| 71 | communicationRole3 | `String` | Communication Role3 |
| 72 | communicationType1 | `String` | Communication Type1 |
| 73 | communicationType2 | `String` | Communication Type2 |
| 74 | communicationType3 | `String` | Communication Type3 |
| 75 | communicationValue1 | `String` | Communication Value1 |
| 76 | communicationValue2 | `String` | Communication Value2 |
| 77 | communicationValue3 | `String` | Communication Value3 |
| 78 | company | `String` | Company |
| 79 | companyGroupId | `String` | Linked internal ID for booker. |
| 80 | companyNameId | `Float` | Company Name ID |
| 81 | competitionCode | `String` | Competition Code |
| 82 | contactEmailPrimary | `String` | Contact Email Primary |
| 83 | contactPhonePrimary | `String` | Phone no. |
| 84 | contactProfileID | `Float` | Contact Profile ID |
| 85 | contactYN | `String` | Contact YN |
| 86 | contractNo | `String` | Contract Number (used for customers). |
| 87 | contractRecvDate | `Date` | The date the group contract was received. |
| 88 | country | `String` | Country |
| 89 | countryCode | `String` | Country Code |
| 90 | countryDesc | `String` | Country Description |
| 91 | createdByUser | `String` | Created by User |
| 92 | createdOnDate | `DateTime` | Created on Date |
| 93 | creditCardName | `String` | Credit Card Name |
| 94 | creditCardType | `String` | Credit Card Type |
| 95 | creditRating | `String` | Credit Rating |
| 96 | currencyCode | `String` | Currency Code |
| 97 | currencyDescription | `String` | Currency Description |
| 98 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 99 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 100 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 101 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 102 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 103 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 104 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 105 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 106 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 107 | deletedFlag | `String` | Deleted Flag |
| 108 | department | `String` | Department |
| 109 | deptId | `String` | Dept ID |
| 110 | directBillBatchType | `String` | Direct Bill Batch Type |
| 111 | displayName | `String` | Display Name |
| 112 | downloadDate | `Date` | Download Date |
| 113 | downloadResort | `String` | Download Property |
| 114 | downloadSrep | `Float` | Download Srep |
| 115 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 116 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 117 | emailYn | `String` | Email Y/N |
| 118 | envelopeGreeting | `String` | Envelope Greeting |
| 119 | envelopeGreetingAlternate | `String` | Envelope Greeting Alternate |
| 120 | externalDisplayName | `String` | External Display Name |
| 121 | externalFirstName | `String` | External First Name |
| 122 | externalId | `String` | External ID |
| 123 | externalName | `String` | External Name |
| 124 | externalReferenceRequ | `String` | Not Used. |
| 125 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 126 | fMembershipCardNumbers | `String` | F Membership Card Numbers |
| 127 | fMembershipClassDesc | `String` | F Membership Class Description |
| 128 | fMembershipClasses | `String` | F Membership Classes |
| 129 | fMembershipCodes | `String` | F Membership Codes |
| 130 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 131 | fMembershipIds | `String` | F Membership Ids |
| 132 | fSubscriptionDb | `String` | F Subscription Db |
| 133 | fSubscriptionYn | `String` | F Subscription Y/N |
| 134 | faxNo | `String` | Fax Number |
| 135 | firstName | `String` | First Name |
| 136 | firstNameIncognito | `String` | First Name Incognito |
| 137 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 138 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 139 | gDSTransactionNo | `String` | Not used. |
| 140 | gender | `String` | Gender |
| 141 | geographicRegion | `String` | Not used. |
| 142 | guestClassification | `String` | Not used. |
| 143 | guestPrivYn | `String` | Guest Priv Y/N |
| 144 | historyYN | `String` | History YN |
| 145 | holdCode | `String` | Hold Code |
| 146 | iataCompType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 147 | iataConsortia | `String` | IATA Consortia |
| 148 | idCountry | `String` | ID Country |
| 149 | idDate | `Date` | ID Date |
| 150 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 151 | idNumber | `String` | ID Number |
| 152 | idPlace | `String` | ID Place |
| 153 | idType | `String` | ID Type |
| 154 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 155 | inactiveDate | `DateTime` | Inactive Date |
| 156 | inactiveFlag | `String` | Inactive Flag |
| 157 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 158 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 159 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 160 | indexName | `String` | Index Name |
| 161 | industryCode | `String` | Industry Code |
| 162 | influence | `String` | Influence |
| 163 | influenceDescription | `String` | Influence Description |
| 164 | interest | `String` | Interest Code. |
| 165 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 166 | internalDeletedflag | `String` | Deleted Flag |
| 167 | internalInactiveflag | `String` | Inactive Flag |
| 168 | internalOrganizationId | `Float` | Organization ID |
| 169 | jRNUpdateDate | `Date` | JRN Update Date |
| 170 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 171 | keyword | `String` | Keyword |
| 172 | language | `String` | Language |
| 173 | languageDescription | `String` | Language Description |
| 174 | laptopChange | `Float` | Laptop Change |
| 175 | lastGroup | `String` | Last Group |
| 176 | lastName | `String` | Last Name |
| 177 | lastNameAlternate | `String` | Last Name Alternate |
| 178 | lastNameIncognito | `String` | Last Name Incognito |
| 179 | lastRate | `Float` | Last Rate |
| 180 | lastRoom | `String` | Not used. |
| 181 | lastRoomResort | `String` | Last Room Property |
| 182 | lastSource | `String` | Last Source |
| 183 | lastStay | `Date` | Last Stay |
| 184 | lastUpdatedResort | `String` | Last property that updated this record. |
| 185 | legalCompany | `String` | Legal Company |
| 186 | letterGreeting | `String` | Letter Greeting |
| 187 | mailActionDescription | `String` | Mail Action Description |
| 188 | mailListYN | `String` | Mail List YN |
| 189 | mailType | `String` | The type of mail this user should be sent. |
| 190 | mailYn | `String` | Mail Y/N |
| 191 | mailingActionCode | `String` | Mailing Action Code |
| 192 | marketResearchYn | `String` | Market Research Y/N |
| 193 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 194 | middleName | `String` | Middle Name |
| 195 | name | `String` | Name |
| 196 | nameComment | `String` | Not Used. |
| 197 | nameTaxType | `String` | Name Tax Type |
| 198 | nameWithTitle | `String` | Name With Title |
| 199 | name2 | `String` | Name2 |
| 200 | name3 | `String` | Name3 |
| 201 | nationalityCode | `String` | Nationality Code |
| 202 | nationalityDescription | `String` | Nationality Description |
| 203 | negotiatedRateCodes | `String` | Negotiated Rate Codes |
| 204 | nextStay | `Date` | Next Stay |
| 205 | nickname | `String` | The nickname of this individual. |
| 206 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 207 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 208 | passport | `String` | Passport |
| 209 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 210 | paymentMethodsCode | `String` | Payment Methods Code |
| 211 | paymentMethodsDesc | `String` | Payment Methods Description |
| 212 | phoneYn | `String` | Phone Y/N |
| 213 | preferredRoomNo | `String` | Preferred Room Number |
| 214 | primaryAddressId | `Float` | Not used. |
| 215 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 216 | primaryNameId | `Float` | Not Used. |
| 217 | primaryOwner | `String` | Primary Owner |
| 218 | primaryOwnerCode | `String` | Primary Owner Code |
| 219 | primaryPhoneId | `Float` | Not used. |
| 220 | priority | `String` | Priority |
| 221 | privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 222 | productInterest | `String` | Product Interest |
| 223 | profession | `String` | Profession of the guest |
| 224 | profileArrCodes | `String` | Profile Arrangement Codes |
| 225 | profileArrangementDesc | `String` | Profile Arr Description |
| 226 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 227 | profileId | `Float` | Profile ID |
| 228 | profileType | `String` | Profile Type |
| 229 | protected | `String` | Protected |
| 230 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 231 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 232 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 233 | rateStructure | `String` | The default rate structure for this name. |
| 234 | region | `String` | Region |
| 235 | regionid | `String` | Regionid |
| 236 | repAccountType | `String` | Reporting Account Type |
| 237 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 238 | repAccountsource | `String` | Reporting Accountsource |
| 239 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 240 | repCompetitionCode | `String` | Reporting Competition Code |
| 241 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 242 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 243 | repIATACompType | `String` | Reporting Iata Comp Type |
| 244 | repIndustryCode | `String` | Reporting Industry Code |
| 245 | repIndustryDescription | `String` | Reporting Industry Desc |
| 246 | repMailActionCodes | `String` | Reporting Mail Action Codes |
| 247 | repNameType | `String` | Reporting Name Type |
| 248 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 249 | repPriority | `String` | Reporting Priority |
| 250 | repPriorityDescription | `String` | Reporting Priority Desc |
| 251 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 252 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 253 | repStateCode | `String` | Reporting State Code |
| 254 | repStateDescription | `String` | Reporting State Desc |
| 255 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 256 | repTitleName | `String` | Reporting Title Name |
| 257 | repeatGuestId | `String` | The primary membership # for this guest. |
| 258 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 259 | resortRegistered | `String` | Resort for which Job is registered. |
| 260 | restricted | `String` | Restricted |
| 261 | restrictedRule | `String` | Restricted Rule |
| 262 | resvContact | `String` | Reservation Contact person. |
| 263 | roomsPotential | `String` | Rooms Potential |
| 264 | salesRep | `String` | Sales Reporting |
| 265 | salesRepCode | `String` | Sales Reporting Code |
| 266 | salutation | `String` | Salutation Greeting |
| 267 | salutationAlternate | `String` | Salutation Alternate |
| 268 | scope | `String` | Scope |
| 269 | scopeCity | `String` | Scope City |
| 270 | scopeCityDescription | `String` | Scope City Description |
| 271 | scopeDescription | `String` | Scope Description |
| 272 | searchName | `String` | The Uppercase value of Last or Company. |
| 273 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 274 | sfirst | `String` | Uppercase value of First Name. |
| 275 | smsYn | `String` | Use this alert to text a notification. |
| 276 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 277 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 278 | srepCode | `String` | Srep Code |
| 279 | state | `String` | State |
| 280 | stateCode | `String` | State Code |
| 281 | stateDesc | `String` | State Description of the Guest of Payee |
| 282 | stateDescription | `String` | State Description |
| 283 | suffix | `String` | Suffix |
| 284 | summRefCc | `String` | Summ Ref Cc |
| 285 | summRefCurrencyId | `String` | Summ Ref Curr ID |
| 286 | superSearchIndexText | `String` | Super Search Index Text |
| 287 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 288 | taxCategory | `String` | Tax Category |
| 289 | taxExemptStatus | `String` | Not used. |
| 290 | taxID1 | `String` | Tax ID 1 |
| 291 | taxID2 | `String` | Tax ID 2 |
| 292 | taxOffice | `String` | Tax Office Name |
| 293 | taxType | `String` | Tax Type |
| 294 | taxTypeDescription | `String` | Tax Type Description |
| 295 | territory | `String` | Territory |
| 296 | territoryDescription | `String` | Territory Description |
| 297 | thirdPartyYn | `String` | Third Party Y/N |
| 298 | title | `String` | Title |
| 299 | titleSuffix | `Float` | Title Suffix |
| 300 | totalArrivals | `Float` | Total Arrivals |
| 301 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 302 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 303 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 304 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 305 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 306 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 307 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 308 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 309 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 310 | totalFbRevenue | `Float` | Total FB Revenue |
| 311 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 312 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 313 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 314 | totalNonRevenue | `Float` | Total Non Revenue |
| 315 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 316 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 317 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 318 | totalOtherRevenue | `Float` | Total Other Revenue |
| 319 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 320 | totalReservationNights | `Float` | Total Reservation Nights |
| 321 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 322 | totalRevenue | `Float` | Total Revenue |
| 323 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 324 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 325 | totalRoomRevenue | `Float` | Total Room Revenue |
| 326 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 327 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 328 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 329 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 330 | traceCode | `String` | Trace Code |
| 331 | traceCodeDescription | `String` | Trace Code Description |
| 332 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 333 | uDFC01 | `String` | UDFC01 |
| 334 | uDFC02 | `String` | UDFC02 |
| 335 | uDFC03 | `String` | UDFC03 |
| 336 | uDFC04 | `String` | UDFC04 |
| 337 | uDFC05 | `String` | UDFC05 |
| 338 | uDFC06 | `String` | UDFC06 |
| 339 | uDFC07 | `String` | UDFC07 |
| 340 | uDFC08 | `String` | UDFC08 |
| 341 | uDFC09 | `String` | UDFC09 |
| 342 | uDFC10 | `String` | UDFC10 |
| 343 | uDFC11 | `String` | UDFC11 |
| 344 | uDFC12 | `String` | UDFC12 |
| 345 | uDFC13 | `String` | UDFC13 |
| 346 | uDFC14 | `String` | UDFC14 |
| 347 | uDFC15 | `String` | UDFC15 |
| 348 | uDFC16 | `String` | UDFC16 |
| 349 | uDFC17 | `String` | UDFC17 |
| 350 | uDFC18 | `String` | UDFC18 |
| 351 | uDFC19 | `String` | UDFC19 |
| 352 | uDFC20 | `String` | UDFC20 |
| 353 | uDFC21 | `String` | UDFC21 |
| 354 | uDFC22 | `String` | UDFC22 |
| 355 | uDFC23 | `String` | UDFC23 |
| 356 | uDFC24 | `String` | UDFC24 |
| 357 | uDFC25 | `String` | UDFC25 |
| 358 | uDFC26 | `String` | UDFC26 |
| 359 | uDFC27 | `String` | UDFC27 |
| 360 | uDFC28 | `String` | UDFC28 |
| 361 | uDFC29 | `String` | UDFC29 |
| 362 | uDFC30 | `String` | UDFC30 |
| 363 | uDFC31 | `String` | UDFC31 |
| 364 | uDFC32 | `String` | UDFC32 |
| 365 | uDFC33 | `String` | UDFC33 |
| 366 | uDFC34 | `String` | UDFC34 |
| 367 | uDFC35 | `String` | UDFC35 |
| 368 | uDFC36 | `String` | UDFC36 |
| 369 | uDFC37 | `String` | UDFC37 |
| 370 | uDFC38 | `String` | UDFC38 |
| 371 | uDFC39 | `String` | UDFC39 |
| 372 | uDFC40 | `String` | UDFC40 |
| 373 | uDFD01 | `Date` | UDFD01 |
| 374 | uDFD02 | `Date` | UDFD02 |
| 375 | uDFD03 | `Date` | UDFD03 |
| 376 | uDFD04 | `Date` | UDFD04 |
| 377 | uDFD05 | `Date` | UDFD05 |
| 378 | uDFD06 | `Date` | UDFD06 |
| 379 | uDFD07 | `Date` | UDFD07 |
| 380 | uDFD08 | `Date` | UDFD08 |
| 381 | uDFD09 | `Date` | UDFD09 |
| 382 | uDFD10 | `Date` | UDFD10 |
| 383 | uDFD11 | `Date` | UDFD11 |
| 384 | uDFD12 | `Date` | UDFD12 |
| 385 | uDFD13 | `Date` | UDFD13 |
| 386 | uDFD14 | `Date` | UDFD14 |
| 387 | uDFD15 | `Date` | UDFD15 |
| 388 | uDFD16 | `Date` | UDFD16 |
| 389 | uDFD17 | `Date` | UDFD17 |
| 390 | uDFD18 | `Date` | UDFD18 |
| 391 | uDFD19 | `Date` | UDFD19 |
| 392 | uDFD20 | `Date` | UDFD20 |
| 393 | uDFN01 | `Float` | UDFN01 |
| 394 | uDFN02 | `Float` | UDFN02 |
| 395 | uDFN03 | `Float` | UDFN03 |
| 396 | uDFN04 | `Float` | UDFN04 |
| 397 | uDFN05 | `Float` | UDFN05 |
| 398 | uDFN06 | `Float` | UDFN06 |
| 399 | uDFN07 | `Float` | UDFN07 |
| 400 | uDFN08 | `Float` | UDFN08 |
| 401 | uDFN09 | `Float` | UDFN09 |
| 402 | uDFN10 | `Float` | UDFN10 |
| 403 | uDFN11 | `Float` | UDFN11 |
| 404 | uDFN12 | `Float` | UDFN12 |
| 405 | uDFN13 | `Float` | UDFN13 |
| 406 | uDFN14 | `Float` | UDFN14 |
| 407 | uDFN15 | `Float` | UDFN15 |
| 408 | uDFN16 | `Float` | UDFN16 |
| 409 | uDFN17 | `Float` | UDFN17 |
| 410 | uDFN18 | `Float` | UDFN18 |
| 411 | uDFN19 | `Float` | UDFN19 |
| 412 | uDFN20 | `Float` | UDFN20 |
| 413 | uDFN21 | `Float` | UDFN21 |
| 414 | uDFN22 | `Float` | UDFN22 |
| 415 | uDFN23 | `Float` | UDFN23 |
| 416 | uDFN24 | `Float` | UDFN24 |
| 417 | uDFN25 | `Float` | UDFN25 |
| 418 | uDFN26 | `Float` | UDFN26 |
| 419 | uDFN27 | `Float` | UDFN27 |
| 420 | uDFN28 | `Float` | UDFN28 |
| 421 | uDFN29 | `Float` | UDFN29 |
| 422 | uDFN30 | `Float` | UDFN30 |
| 423 | uDFN31 | `Float` | UDFN31 |
| 424 | uDFN32 | `Float` | UDFN32 |
| 425 | uDFN33 | `Float` | UDFN33 |
| 426 | uDFN34 | `Float` | UDFN34 |
| 427 | uDFN35 | `Float` | UDFN35 |
| 428 | uDFN36 | `Float` | UDFN36 |
| 429 | uDFN37 | `Float` | UDFN37 |
| 430 | uDFN38 | `Float` | UDFN38 |
| 431 | uDFN39 | `Float` | UDFN39 |
| 432 | uDFN40 | `Float` | UDFN40 |
| 433 | updateDate | `DateTime` | Update Date |
| 434 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 435 | updateUser | `String` | Update User |
| 436 | uploadDate | `Date` | Upload Date |
| 437 | vIPCode | `String` | VIP Code |
| 438 | vIPCodeDescription | `String` | VIP Code Description |
| 439 | vendorId | `Float` | Vendor ID |
| 440 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 441 | vipAuthorization | `String` | Not Used. |
| 442 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 443 | xcompanyName | `String` | Extended Byte Company Name |
| 444 | xmiddleName | `String` | Extended Byte middle name. |
| 445 | zipCode | `String` | Zipcode Code |

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

### StatisticsReservationsDailyQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| resvdailystatsDetailsAgentId | `FloatInput` | Agent ID |
| resvdailystatsDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| resvdailystatsDetailsBiResvNameId | `FloatInput` | Bi Resv Name ID |
| resvdailystatsDetailsBusinessDate | `DateInput!` | Business Date<br>`@mandatoryInput` |
| resvdailystatsDetailsCompanyId | `FloatInput` | Company ID |
| resvdailystatsDetailsContactId | `FloatInput` | Contact ID |
| resvdailystatsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdailystatsDetailsGroupId | `FloatInput` | Group ID |
| resvdailystatsDetailsNameId | `FloatInput` | Guest Profile ID |
| resvdailystatsDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvdailystatsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdailystatsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdailystatsDetailsParentCompanyId | `FloatInput` | Parent Company ID |
| resvdailystatsDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| resvdailystatsDetailsRateCode | `StringInput` | Rate Code |
| resvdailystatsDetailsRoom | `StringInput` | Room |
| resvdailystatsDetailsSourceProfId | `FloatInput` | Source Prof ID |
| resvdailystatsDetailsUpdateDate | `DateTimeInput` | Update Date |
| parentcompanyprofileDetailsActiveYn | `StringInput` | Active YN |
| parentcompanyprofileDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| parentcompanyprofileDetailsNameCode | `StringInput` | Corporate ID |
| parentcompanyprofileDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| parentcompanyprofileDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| parentcompanyprofileDetailsHistoryYn | `StringInput` | History YN |
| parentcompanyprofileDetailsInactiveDate | `DateInput` | Inactive Date |
| parentcompanyprofileDetailsIndexName | `StringInput` | Index Name |
| parentcompanyprofileDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| parentcompanyprofileDetailsLast | `StringInput` | Last |
| parentcompanyprofileDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| parentcompanyprofileDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| parentcompanyprofileDetailsSname | `StringInput` | The Uppercase value of Last or PARENTCOMPANYPROFILE. |
| parentcompanyprofileDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| parentcompanyprofileDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| parentcompanyprofileDetailsSrepCode | `StringInput` | Srep Code |
| parentcompanyprofileDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| parentcompanyprofileDetailsUpdateDate | `DateTimeInput` | Update Date |
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
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
| guestprofileallDetailsNameId | `FloatInput` | The primary key for this table. |
| guestprofileallDetailsActiveYn | `StringInput` | Profile is active or not. |
| guestprofileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| guestprofileallDetailsChainCode | `StringInput` | Chain Code |
| guestprofileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| guestprofileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |
| guestprofileallDetailsContactFlag | `StringInput` | Used in S&C Module. |
| guestprofileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| guestprofileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| guestprofileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| guestprofileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| guestprofileallDetailsInactiveDate | `DateInput` | The date the record was marked as inactive |
| guestprofileallDetailsIndexName | `StringInput` | Index Name |
| guestprofileallDetailsOrganizationId | `FloatInput` | Organization ID |
| guestprofileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| guestprofileallDetailsNameType | `StringInput` | The type of Profile. |
| guestprofileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| guestprofileallDetailsProfileId | `FloatInput` | The primary key for this table. |
| guestprofileallDetailsProfileType | `StringInput` | The type of Profile. |
| guestprofileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| guestprofileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| guestprofileallDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| guestprofileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| guestprofileallDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| guestprofileallDetailsSrepCode | `StringInput` | Used in QMS Module |
| guestprofileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| guestprofileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| nationalityDetailsAttributeCode | `StringInput` | Code |
| nationalityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| nationalityDetailsEntityName | `StringInput` | Entity Name |
| nationalityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| nationalityDetailsLanguageCode | `StringInput` | Language Code |
| nationalityDetailsNationalityid | `StringInput` | Nationalityid |
| nationalityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| nationalityDetailsTitleSuffix | `FloatInput` | Title Suffix |
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
| gueststatusDetailsAttributeCode | `StringInput` | Code |
| gueststatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| gueststatusDetailsEntityName | `StringInput` | Entity Name |
| gueststatusDetailsEntityname | `StringInput` | Entityname |
| gueststatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| gueststatusDetailsLanguageCode | `StringInput` | Language Code |
| gueststatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| gueststatusDetailsTitleSuffix | `FloatInput` | Title Suffix |
| profileaccountssourceDetailsProfileId | `FloatInput` | Account ID |
| profileaccountssourceDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountssourceDetailsChainCode | `StringInput` | Chain Code |
| profileaccountssourceDetailsCompany | `StringInput` | Company |
| profileaccountssourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountssourceDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountssourceDetailsNameCode | `StringInput` | IATA Number |
| profileaccountssourceDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountssourceDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountssourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountssourceDetailsLast | `StringInput` | Last |
| profileaccountssourceDetailsNameId | `FloatInput` | Name ID |
| profileaccountssourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountssourceDetailsProfileType | `StringInput` | Profile Type |
| profileaccountssourceDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountssourceDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountssourceDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountssourceDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountssourceDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountssourceDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountssourceDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationstatisticsDetailsActualCheckInDateTime | `DateInput` | Actual Check In Date Time |
| reservationstatisticsDetailsActualCheckOutDateTime | `DateInput` | Actual Check Out Date Time |
| reservationstatisticsDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| reservationstatisticsDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationstatisticsDetailsTruncBeginDate | `DateInput` | Arrival Date |
| reservationstatisticsDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationstatisticsDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| reservationstatisticsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationstatisticsDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationstatisticsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationstatisticsDetailsCancellationDate | `DateInput` | Cancellation Date |
| reservationstatisticsDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationstatisticsDetailsCreditCardId | `FloatInput` | Credit Card ID |
| reservationstatisticsDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationstatisticsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationstatisticsDetailsTruncEndDate | `DateInput` | Departure Date |
| reservationstatisticsDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| reservationstatisticsDetailsEventId | `FloatInput` | Event ID |
| reservationstatisticsDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationstatisticsDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationstatisticsDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| reservationstatisticsDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| reservationstatisticsDetailsInsertDate | `DateTimeInput` | Insert Date |
| reservationstatisticsDetailsInsertUser | `FloatInput` | Insert User |
| reservationstatisticsDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationstatisticsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationstatisticsDetailsEndDate | `DateInput` | Linked Departure Date |
| reservationstatisticsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationstatisticsDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationstatisticsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationstatisticsDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationstatisticsDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationstatisticsDetailsParentreservationid | `FloatInput` | Parentreservationid |
| reservationstatisticsDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationstatisticsDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationstatisticsDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationstatisticsDetailsResvNameId | `FloatInput` | Reservation Name ID |
| reservationstatisticsDetailsResvStatus | `StringInput` | Reservation Status |
| reservationstatisticsDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationstatisticsDetailsReservationid | `FloatInput` | Reservationid |
| reservationstatisticsDetailsResort | `StringInput` | Property |
| reservationstatisticsDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationstatisticsDetailsResvNameid | `FloatInput` | Reservation Nameid |
| reservationstatisticsDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| reservationstatisticsDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| reservationstatisticsDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| reservationstatisticsDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationstatisticsDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationstatisticsDetailsSguestName | `StringInput` | Sguest Name |
| reservationstatisticsDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| reservationstatisticsDetailsNameId | `FloatInput` | Shared Profile ID |
| reservationstatisticsDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationstatisticsDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationstatisticsDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| reservationstatisticsDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationstatisticsDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationstatisticsDetailsUpdateDate | `DateTimeInput` | Update Date |
| bookedroomcategoryDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| bookedroomcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bookedroomcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bookedroomcategoryDetailsLabel | `StringInput` | Label |
| bookedroomcategoryDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| bookedroomcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| bookedroomcategoryDetailsYieldCategory | `StringInput` | Product Class |
| bookedroomcategoryDetailsResort | `StringInput` | Code to uniquely identify the Property |
| bookedroomcategoryDetailsRoomcategoryid | `StringInput` | Room Category ID |
| bookedroomcategoryDetailsRoomcategorypmsref | `StringInput` | Room Category PMS Ref |
| bookedroomcategoryDetailsRoomCategory | `StringInput` | Room Type |
| bookedroomcategoryDetailsRoomclassid | `StringInput` | Roomclassid |
| countrygroupDetailsAttributeCode | `StringInput` | Country Group Code |
| countrygroupDetailsCountrygroupid | `StringInput` | Countrygroupid |
| countrygroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| countrygroupDetailsEntityName | `StringInput` | Entity Name |
| countrygroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| countrygroupDetailsLanguageCode | `StringInput` | Language Code |
| countrygroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| countrygroupDetailsTitleSuffix | `FloatInput` | Title Suffix |
| profileaccountstravelagentDetailsProfileId | `FloatInput` | Account ID |
| profileaccountstravelagentDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountstravelagentDetailsChainCode | `StringInput` | Chain Code |
| profileaccountstravelagentDetailsCompany | `StringInput` | Company |
| profileaccountstravelagentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountstravelagentDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountstravelagentDetailsNameCode | `StringInput` | IATA Number |
| profileaccountstravelagentDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountstravelagentDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountstravelagentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountstravelagentDetailsLast | `StringInput` | Last |
| profileaccountstravelagentDetailsNameId | `FloatInput` | Name ID |
| profileaccountstravelagentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountstravelagentDetailsProfileType | `StringInput` | Profile Type |
| profileaccountstravelagentDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountstravelagentDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountstravelagentDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountstravelagentDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountstravelagentDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountstravelagentDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountstravelagentDetailsUpdateDate | `DateTimeInput` | Update Date |
| profileaccountsDetailsProfileId | `FloatInput` | Account ID |
| profileaccountsDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountsDetailsChainCode | `StringInput` | Chain Code |
| profileaccountsDetailsCompany | `StringInput` | Company |
| profileaccountsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountsDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountsDetailsNameCode | `StringInput` | IATA Number |
| profileaccountsDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| profileaccountsDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountsDetailsLast | `StringInput` | Last |
| profileaccountsDetailsNameId | `FloatInput` | Name ID |
| profileaccountsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountsDetailsProfileType | `StringInput` | Profile Type |
| profileaccountsDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountsDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountsDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountsDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountsDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountsDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountsDetailsUpdateDate | `DateTimeInput` | Update Date |
| stateDetailsStateCode | `StringInput` | Code |
| stateDetailsCountryCode | `StringInput` | Country |
| stateDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| stateDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| stateDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| stateDetailsStateid | `StringInput` | Stateid |
| groupDetailsActiveYn | `StringInput` | Active YN |
| groupDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| groupDetailsNameCode | `StringInput` | Client ID |
| groupDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |
| groupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| groupDetailsCompany | `StringInput` | Description |
| groupDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| groupDetailsHistoryYn | `StringInput` | History YN |
| groupDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| groupDetailsIndexName | `StringInput` | Index Name |
| groupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| groupDetailsLast | `StringInput` | Last |
| groupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| groupDetailsNameId | `FloatInput` | Profile ID |
| groupDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| groupDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| groupDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| groupDetailsSrepCode | `StringInput` | Srep Code |
| groupDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| groupDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| groupDetailsUpdateDate | `DateTimeInput` | Update Date |
| cityDetailsAttributeCode | `StringInput` | Attribute Code |
| cityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| cityDetailsEntityName | `StringInput` | Entity Name |
| cityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| cityDetailsLanguageCode | `StringInput` | Language Code |
| cityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cityDetailsTitleSuffix | `FloatInput` | Title Suffix |
| promotionDetailsPromoCode | `StringInput` | Code |
| promotionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| promotionDetailsMpcode | `StringInput` | Group |
| promotionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| promotionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| promotionDetailsPromoSeqId | `FloatInput` | Promo Seq ID |
| promotionDetailsResort | `StringInput` | Property |
| companyDetailsActiveYn | `StringInput` | Active YN |
| companyDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| companyDetailsCompany | `StringInput` | Company |
| companyDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |
| companyDetailsNameId | `FloatInput` | Company Profile ID |
| companyDetailsNameCode | `StringInput` | Corporate ID |
| companyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| companyDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| companyDetailsHistoryYn | `StringInput` | History YN |
| companyDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| companyDetailsIndexName | `StringInput` | Index Name |
| companyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| companyDetailsLast | `StringInput` | Last |
| companyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| companyDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| companyDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| companyDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| companyDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| companyDetailsSrepCode | `StringInput` | Srep Code |
| companyDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| companyDetailsUpdateDate | `DateTimeInput` | Update Date |
| allotmentDetailsAgentContactNameId | `FloatInput` | Agent Contact Name ID |
| allotmentDetailsAgentNameId | `FloatInput` | Agent Name ID |
| allotmentDetailsAllotmentCode | `StringInput` | Block Code |
| allotmentDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| allotmentDetailsOwnerCode | `StringInput` | Block Owner Code |
| allotmentDetailsBookingId | `StringInput` | External S&C vendor booking ID and used in HYATT-mode. |
| allotmentDetailsBookingStatusOrder | `FloatInput` | Booking Status Order |
| allotmentDetailsBlockType | `StringInput` | Determines block being [G] - Group or [W] - Wholesale. |
| allotmentDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| allotmentDetailsChainCode | `StringInput` | Chain Code |
| allotmentDetailsCompanyNameId | `FloatInput` | Company Name ID |
| allotmentDetailsContactNameId | `FloatInput` | Contact Name ID |
| allotmentDetailsInsertDate | `DateTimeInput` | Created Date |
| allotmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| allotmentDetailsDueDateOrd | `DateInput` | Due Date Sorting Column. |
| allotmentDetailsEndDate | `DateInput` | End Date |
| allotmentDetailsInsertUser | `FloatInput` | Insert User |
| allotmentDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |
| allotmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| allotmentDetailsMarketCode | `StringInput` | Market  Code |
| allotmentDetailsSuperBlockId | `FloatInput` | Parent Block ID |
| allotmentDetailsSuperBlockResort | `StringInput` | Parent Resort |
| allotmentDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| allotmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| allotmentDetailsOrmsBlockClass | `StringInput` | ORMS Block Class |
| allotmentDetailsOwner | `FloatInput` | Owner |
| allotmentDetailsResort | `StringInput` | Code to uniquely identify the Property |
| allotmentDetailsRateCode | `StringInput` | Rate Code |
| allotmentDetailsGuaranteeCode | `StringInput` | Reservation Type |
| allotmentDetailsBookingStatus | `StringInput` | Room Status |
| allotmentDetailsShoulderEndDate | `DateInput` | Shoulder End |
| allotmentDetailsShoulderBeginDate | `DateInput` | Shoulder Start |
| allotmentDetailsSourceNameId | `FloatInput` | Source Name ID |
| allotmentDetailsBeginDate | `DateInput` | Start Date |
| allotmentDetailsTourcode | `StringInput` | Tour Code. |
| allotmentDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |
| allotmentDetailsUpdateDate | `DateTimeInput` | Updated Date |
| allotmentDetailsXudescription | `StringInput` | Multi Byte Description in uppercase |
| travelagentDetailsActiveYn | `StringInput` | Active YN |
| travelagentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| travelagentDetailsHistoryYn | `StringInput` | History YN |
| travelagentDetailsNameCode | `StringInput` | IATA Number |
| travelagentDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| travelagentDetailsOrganizationId | `FloatInput` | Organization ID |
| travelagentDetailsProfileId | `FloatInput` | Profile ID |
| travelagentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| travelagentDetailsLast | `StringInput` | Last |
| travelagentDetailsCompany | `StringInput` | Name |
| travelagentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| travelagentDetailsNameId | `FloatInput` | Profile ID |
| travelagentDetailsProfileType | `StringInput` | Profile Type |
| travelagentDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| travelagentDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| travelagentDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| travelagentDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| travelagentDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| travelagentDetailsUpdateDate | `DateTimeInput` | Update Date |
| allotmentstatisticsDetailsAgentContactNameId | `FloatInput` | Agent Contact Name ID |
| allotmentstatisticsDetailsAgentNameId | `FloatInput` | Agent Name ID |
| allotmentstatisticsDetailsOwnerCode | `StringInput` | Block Owner Code |
| allotmentstatisticsDetailsBookingId | `StringInput` | External S&C vendor booking ID and used in HYATT-mode. |
| allotmentstatisticsDetailsBookingStatusOrder | `FloatInput` | Booking Status Order |
| allotmentstatisticsDetailsBlockType | `StringInput` | Determines block being [G] - Group or [W] - Wholesale. |
| allotmentstatisticsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| allotmentstatisticsDetailsCompanyNameId | `FloatInput` | Company Name ID |
| allotmentstatisticsDetailsContactNameId | `FloatInput` | Contact Name ID |
| allotmentstatisticsDetailsInsertDate | `DateTimeInput` | Created Date |
| allotmentstatisticsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| allotmentstatisticsDetailsDueDateOrd | `DateInput` | Due Date Sorting Column. |
| allotmentstatisticsDetailsEndDate | `DateInput` | End Date |
| allotmentstatisticsDetailsInsertUser | `FloatInput` | Insert User |
| allotmentstatisticsDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |
| allotmentstatisticsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| allotmentstatisticsDetailsMarketCode | `StringInput` | Market  Code |
| allotmentstatisticsDetailsSuperBlockId | `FloatInput` | Parent Block ID |
| allotmentstatisticsDetailsSuperBlockResort | `StringInput` | Parent Resort |
| allotmentstatisticsDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| allotmentstatisticsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| allotmentstatisticsDetailsOrmsBlockClass | `StringInput` | ORMS Block Class |
| allotmentstatisticsDetailsOwner | `FloatInput` | Owner |
| allotmentstatisticsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| allotmentstatisticsDetailsRateCode | `StringInput` | Rate Code |
| allotmentstatisticsDetailsGuaranteeCode | `StringInput` | Reservation Type |
| allotmentstatisticsDetailsBookingStatus | `StringInput` | Room Status |
| allotmentstatisticsDetailsShoulderEndDate | `DateInput` | Shoulder End |
| allotmentstatisticsDetailsShoulderBeginDate | `DateInput` | Shoulder Start |
| allotmentstatisticsDetailsSourceNameId | `FloatInput` | Source Name ID |
| allotmentstatisticsDetailsBeginDate | `DateInput` | Start Date |
| allotmentstatisticsDetailsTourcode | `StringInput` | Tour Code. |
| allotmentstatisticsDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |
| allotmentstatisticsDetailsUpdateDate | `DateTimeInput` | Updated Date |
| allotmentstatisticsDetailsXudescription | `StringInput` | Multi Byte Description in uppercase |
| contactDetailsActiveYn | `StringInput` | Active Flag |
| contactDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| contactDetailsChainCode | `StringInput` | Chain Code |
| contactDetailsNameCode | `StringInput` | Client ID |
| contactDetailsCompany | `StringInput` | Company |
| contactDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |
| contactDetailsNameId | `FloatInput` | Contact Profile ID |
| contactDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| contactDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| contactDetailsHistoryYn | `StringInput` | History YN |
| contactDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| contactDetailsIndexName | `StringInput` | Index Name |
| contactDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| contactDetailsLast | `StringInput` | Last Name |
| contactDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| contactDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| contactDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| contactDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| contactDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| contactDetailsSrepCode | `StringInput` | Srep Code |
| contactDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| contactDetailsUpdateDate | `DateTimeInput` | Update Date |
#### Validation Rules

**`mandatoryInput`**
- resvdailystatsDetailsBusinessDate
- resvdailystatsDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsReservationsDaily($input: StatisticsReservationsDailyQueryArgumentsType!) {
  statisticsReservationsDaily(input: $input) @stream {
    reservationDailyStatisticsDetails {
      adults
      adultsTaxFree
      agentId
      agentprofileid
      allotmentHeaderId
      allotmentid
      arrivalPersons
      arrivalRooms
      beginDate
      biReservationNameId
      birthDate
      bookedRoomCategory
      bookedroomcategoryid
      businessDate
      businessDateCreated
      cAdvanceTotalOtherTax
      cCashRoomRevenue
      cCompRoomRevenue
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
      cPrAdvanceTotalFoodTax
      cRateAmount
      cRsAdvanceFoodRevenue
      cRsAdvanceFoodTax
      cRsAdvanceNonRevenue
      cRsAdvanceNonRevenueTax
      cRsAdvanceOtherRevenue
      cRsAdvanceOtherTax
      cRsAdvanceRoomRevenue
      cRsAdvanceRoomTax
      cRsAdvanceTotalRevenue
      cRsAdvanceTotalTax
      cUpsoldRevenue
      cancellationDate
      cancelledPersons
      cancelledReservations
      cancelledRooms
      cashRoomNts
      cashRoomRevenue
      centralCurrencyCode
      centralDistributedFoodRevenue
      centralDistributedFoodRevenueAsPayee
      centralDistributedNonRevenue
      centralDistributedNonRevenueAsPayee
      centralDistributedOtherRevenue
      centralDistributedOtherRevenueAsPayee
      centralDistributedRoomRevenue
      centralDistributedRoomRevenueAsPayee
      centralDistributedTotalFoodTaxAsPayee
      centralDistributedTotalNonRevenueTax
      centralDistributedTotalNonRevenueTaxAsPayee
      centralDistributedTotalOtherTaxAsPayee
      centralDistributedTotalRevenue
      centralDistributedTotalRevenueAsPayee
      centralDistributedTotalRoomTax
      centralDistributedTotalRoomTaxAsPayee
      centralDistributedTotalTax
      centralDistributedTotalTaxAsPayee
      centralExchangeRate
      centralFoodRevenue
      centralFoodRevenueAsPayee
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNonRevenue
      centralNonRevenueAsPayee
      centralOriginCode
      centralOriginDescription
      centralOriginalRoomType
      centralOtherRevenue
      centralOtherRevenueAsPayee
      centralPackageFoodRevenue
      centralPackageFoodRevenueAsPayee
      centralPackageNonRevenue
      centralPackageNonRevenueAsPayee
      centralPackageOtherRevenue
      centralPackageOtherRevenueAsPayee
      centralPackageRoomRevenue
      centralPackageRoomRevenueAsPayee
      centralRateCategory
      centralRoomRevenue
      centralRoomRevenueAsPayee
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      centralTotalFoodTax
      centralTotalFoodTaxGeneratedAsPayee
      centralTotalNonRevenueTax
      centralTotalNonRevenueTaxAsPayee
      centralTotalOtherTax
      centralTotalOtherTaxAsPayee
      centralTotalPackageRevenue
      centralTotalPackageRevenueAsPayee
      centralTotalRevenue
      centralTotalRevenueAsPayee
      centralTotalRoomTax
      centralTotalRoomTaxAsPayee
      centralTotalTax
      centralTotalTaxAsPayee
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
      cityid
      compRoomNts
      compRoomRevenue
      companyId
      companyProfileID
      companyProfileName
      compflag
      complimentaryYN
      contactId
      contactProfileID
      contactflag
      country
      countryMainGroup
      countryName
      countrygroupid
      countryid
      cribs
      dSI
      dayUsePersons
      dayUseReservations
      dayUseRooms
      deletedFlag
      departurePersons
      departureRooms
      distributedFoodRevenue
      distributedFoodRevenueAsPayee
      distributedNonRevenue
      distributedNonRevenueAsPayee
      distributedOtherRevenue
      distributedOtherRevenueAsPayee
      distributedRoomRevenue
      distributedRoomRevenueAsPayee
      distributedTotalFoodTaxAsPayee
      distributedTotalNonRevenueTax
      distributedTotalNonRevenueTaxAsPayee
      distributedTotalOtherTax
      distributedTotalOtherTaxAsPayee
      distributedTotalRevenue
      distributedTotalRevenueAsPayee
      distributedTotalRoomTax
      distributedTotalRoomTaxAsPayee
      distributedTotalTax
      distributedTotalTaxAsPayee
      district
      dueOutYn
      dueoutflag
      endDate
      endbusinessdate
      extendedStayTier
      extraBeds
      fiscalregioncode
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
      foodRevenueAsPayee
      freqflyermembtype
      freqguestmembtype
      groupId
      groupProfileID
      groupProfileName
      guestProfileID
      gueststatusid
      houseUseYn
      houseuseflag
      insertDate
      internalCompanyprofileid
      internalContactprofileid
      internalDeletedflag
      internalGroupprofileid
      internalMembershipid
      internalReservationNameId
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
      membershipCardNo
      membershipId
      multipleOccupancyRooms
      nationality
      nationalityCode
      nationalityid
      nights
      noShowReservations
      noShowPersons
      noShowRooms
      nonRevenue
      nonRevenueAsPayee
      numberOfStays
      organizationID
      originCode
      originDescription
      originalEndDate
      originalRoomCategory
      otherRevenue
      otherRevenueAsPayee
      outOfOrderRooms
      outOfServiceRooms
      ownerRentalYn
      ownerfriendfamilyflag
      ownerrentalflag
      packageFoodRevenue
      packageFoodRevenueAsPayee
      packageNonRevenue
      packageNonRevenueAsPayee
      packageOtherRevenue
      packageOtherRevenueAsPayee
      packageRoomRevenue
      packageRoomRevenueAsPayee
      parentCompanyId
      parentcompanyprofileid
      physicalQuantity
      physicalRooms
      prAdvTotalFoodTax
      primaryKeyID
      primaryYn
      primaryflag
      profiledailytotalid
      profileid
      promotionCode
      promotionCodeDesc
      promotionid
      property
      pseudoRoomYN
      pseudoroomflag
      quantity
      rateAmount
      rateCategory
      rateCode
      ratecategoryid
      ratecodeid
      regionCode
      regionid
      repPromotionCode
      repPromotionCodeDescription
      reservationArrivals
      reservationDate
      reservationNameID
      reservationNights
      reservationNumberOfStays
      reservationStatus
      reservationid
      resvenddate
      resvinsertsource
      resvinsertsourcetype
      rnaInsertDate
      rnaUpdateDate
      room
      roomAdults
      roomCategory
      roomChildren
      roomClass
      roomNights
      roomReservationStatus
      roomRevenue
      roomRevenueAsPayee
      roomcategoryid
      roomclassid
      roomid
      rsAdvFoodRevenue
      rsAdvFoodTax
      rsAdvNonRevenue
      rsAdvNonRevenueTax
      rsAdvOtherRevenue
      rsAdvOtherTax
      rsAdvRoomRevenue
      rsAdvRoomTax
      rsAdvTotalRevenue
      rsAdvTotalTax
      singleOccupancyRooms
      sourceCode
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceProfId
      sourceProfileID
      sourcegroupid
      sourceid
      sourceprofprofileid
      stateCode
      stateid
      stayAdults
      stayChildren
      stayPersons
      totalFoodTax
      totalFoodTaxGeneratedAsPayee
      totalNonRevenueTax
      totalNonRevenueTaxAsPayee
      totalOtherTax
      totalOtherTaxAsPayee
      totalPackageRevenue
      totalPackageRevenueAsPayee
      totalRevenue
      totalRevenueAsPayee
      totalRoomTax
      totalRoomTaxAsPayee
      totalTax
      totalTaxAsPayee
      travelAgentProfileID
      travelAgentProfileName
      updateDate
      upsoldRevenue
      vIPStatus
      walkinYn
      walkinflag
      zipCode
    }
    parentCompanyProfileDeatils {
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      actionCode
      activeYN
      address1
      address2
      address3
      address4
      alienRegistrationNo
      allOwnerCodes
      alternateLanguage
      alternateMiddleName
      alternateSalutation
      alternateTitle
      autoPopRouting
      autoenrollMemberYn
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      cashBlInd
      ccProfileYn
      centralAccountType
      centralCorporateIDType
      centralDefaultKeyword
      centralNationality
      centralNationalityCode
      centralPriority
      centralStateCode
      centralTerritory
      chainCode
      city
      collectionUserId
      combinedName
      commissionCode
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      competition
      contractNo
      contractRecvDate
      corporateID
      corporateIDType
      country
      countryCode
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      defaultKeyword
      deletedFlag
      department
      deptId
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYn
      envelopeGreeting
      externalId
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      first
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestPrivYn
      historyYN
      holdCode
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idNumber
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      includeInTax1099Yn
      incognitoFirstName
      incognitoLastName
      indexName
      industryCode
      influence
      insertDate
      insertUser
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      languageCode
      laptopChange
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      lastUpdatedResort
      letterGreeting
      mailListYN
      mailType
      mailYn
      marketResearchYn
      markets
      masterAccountYn
      middle
      name
      name2
      name3
      nameComment
      nameTaxType
      nameWithTitle
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      passport
      paymentDueDays
      paymentMethodsCode
      paymentMethodsDesc
      phoneNumber
      phoneYn
      postalCode
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      privateYN
      productInterest
      profession
      profileArrCodes
      profileArrangementDesc
      profileCreditLimit
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rNAInsertDate
      rNAUpdateDate
      rateStructure
      region
      repAccountTypeDescription
      repAccountsourceDescription
      repCompetitionDescription
      repCorpTypeDescription
      repInactiveReason
      repInactiveReasonCode
      repIndustryDescription
      repInfluenceDescription
      repMailActionDescription
      repMarketsDescription
      repNameType
      repNameTypeDescription
      repPriorityDescription
      repRoomsPotentialDescription
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTerritoryDescription
      repTitle
      repTitleName
      repVIPName
      repVIPStatus
      repeatGuestId
      replaceAddress
      resvContact
      roomsPotential
      salutation
      scope
      scopeCity
      searchName
      searchNameAlternate
      sfirst
      smsYn
      soundExLast
      srepCode
      state
      stateCode
      suffix
      summRefCc
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      thirdPartyYn
      title
      titleSuffix
      totalArrivals
      totalArrivalsLastyear
      totalCancelledReservations
      totalCancelledResvLastYear
      totalCancelledRooms
      totalCancelledRoomsLastyear
      totalDayUseReservations
      totalDayUseResvLastYear
      totalDayUseRooms
      totalDayUseRoomsLastyear
      totalFbRevenue
      totalFbRevenueLastYear
      totalNoShowReservations
      totalNoShowRooms
      totalNonRevenue
      totalNonRevenueLastyear
      totalNumberShowResvLastYear
      totalNumberShowRoomsLastyear
      totalOtherRevenue
      totalOtherRevenueLastyear
      totalReservationNights
      totalResvNightsLastYear
      totalRevenue
      totalRevenueLastyear
      totalRoomNightsLastyear
      totalRoomRevenue
      totalRoomRevenueLastyear
      totalStays
      totalStaysLastyear
      tourOperatorType
      traceCode
      typeOfTax1099
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
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vendorId
      vendorSiteId
      vipAuthorization
      vipName
      vipStatus
      visaValidityType
      xenvelopeGreeting
      xfirstName
      xlastName
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
    guestProfileAllInformationDetails {
      guestProfileID
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      accountTypeDescription
      accountsourceDesc
      actionCode
      activeYN
      address1
      address2
      address3
      address4
      addressId
      addressLangCodeDesc
      addressLanguageCode
      addressType
      alienRegistrationNo
      allResorts
      alternateEnvelopeGreeting
      alternateLanguage
      alternateLanguageDescription
      alternateSalutation
      autoEnrollMemberYN
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessSegment
      businessSegmentDescription
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      ccProfileYn
      centralAccountType
      centralBusinessSegment
      centralBusinessSegmentDescription
      centralCorporateIDType
      centralDefaultKeyword
      centralGuestTitleCode
      centralInactiveReason
      centralInactiveReasonDescription
      centralMailActionDescription
      centralMailingActionCode
      centralPriority
      centralStateCode
      centralTerritory
      centralVIPCode
      centralVIPDescription
      chainCode
      city
      clientID
      collectionUserId
      combinedName
      commPayCentral
      comments
      commissionCode
      commissionCodes
      commissionCurrencyId
      commissionid
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      companyAlternate
      companyGroupId
      companyNameId
      competition
      competitionDesc
      contactYN
      contractNo
      contractRecvDate
      corpTypeDesc
      corporateIDType
      country
      countryCode
      createdByUser
      createdOnDate
      creditRating
      currencyCode
      currencySymbol
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      debtorName
      decimalPositions
      defaultKeyword
      deletedFlag
      department
      deptId
      description
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYN
      envelopeGreeting
      externalDisplayName
      externalFirstName
      externalId
      externalName
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fMembershipType
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      firstName
      firstNameAlternate
      firstNameIncognito
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestCountry
      guestCurrencyCode
      guestLanguageCode
      guestLastName
      guestMiddleName
      guestNameSuffix
      guestPrivilegeYN
      guestTitleCode
      hasRequestedMailYN
      historyYN
      holdCode
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      includeInTax1099Yn
      indexName
      industryCode
      industryDesc
      influence
      influenceDesc
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      laptopChange
      lastGroup
      lastNameAlternate
      lastNameIncognito
      lastRate
      lastRateCode
      lastRoom
      lastRoomProperty
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailActionDescription
      mailList
      mailType
      mailingActionCode
      marketResearchYN
      masterAccountYn
      nameTaxType
      nameType
      nameTypeDescription
      name2
      name3
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      paymentDueDays
      phone
      phoneWeb
      phoneYN
      postalCode
      postalCodeExtension
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      priorityDesc
      privacyFlagYN
      productInterest
      profession
      profileCreditLimit
      profileId
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rateStructure
      region
      regionid
      repAccountTypeDescription
      repAccountsource
      repAccountsourceDescription
      repCompetitionCode
      repCompetitionDescription
      repCorpTypeDescription
      repIndustryCode
      repIndustryDescription
      repInfluence
      repInfluenceDescription
      repNameType
      repNameTypeDescription
      repNationalityCode
      repNationalityDescription
      repPriorityDescription
      repRoomsPotential
      repRoomsPotentialDescription
      repScope
      repScopeCity
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTaxTypeDescription
      repTerritoryDescription
      repTitleName
      repeatGuestId
      replaceAddress
      requestType
      restricted
      restrictedRule
      resvContact
      rnaInsertDate
      rnaUpdateDate
      roomsPotential
      roomsPotentialDesc
      sMSYN
      salutation
      scope
      scopeCity
      scopeCityDesc
      scopeDesc
      searchName
      searchNameAlternate
      sfirst
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      stateDescription
      summRefCc
      summRefCurrencyId
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      territoryDesc
      thirdPartyYN
      titleAlternate
      titleName
      titleSuffix
      totalStay
      tourOperatorType
      traceCode
      tracecodeDesc
      typeOfTax1099
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
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vIPCode
      vIPDescription
      vendorId
      vendorSiteId
      vipAuthorization
      visaValidityType
      xdisplayName
      xmiddleName
    }
    nationalityDetails {
      businessTitle
      canDeleteYn
      centralDescription
      centralNationalityCode
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
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
      nationalityid
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      titleSuffix
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
    guestStatusDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      guestStatus
      gueststatusid
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      internalEntityname
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      statustype
      titleSuffix
      updateDate
      updateUser
    }
    profileAccountsSourceDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      updateDate
      updateFaxDate
      updateUser
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    reservationStatisticsDetails {
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
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
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
      sharedConfirmationNo
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
    bookedRoomCategoryDetails {
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
      chargedRoomTypeDescription
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
      roomCategoryID
      roomCategoryPMSRef
      roomClass
      roomClassDescription
      roomInfoURL
      roomPool
      roomType
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
    countryGroupDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      comments
      countryGroup
      countryGroupCode
      countrygroupid
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
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    profileAccountsTravelAgentDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      updateDate
      updateFaxDate
      updateUser
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    profileAccountsDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      rNAInsertDate
      rNAUpdateDate
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      updateDate
      updateFaxDate
      updateUser
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    stateDetails {
      chainCode
      code
      country
      countryid
      dSI
      deletedflag
      description
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      stateCode
      stateid
      updateDate
      updateUser
    }
    groupDetails {
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      activeYN
      address1
      address2
      address3
      address4
      alienRegistrationNo
      allOwnerCodes
      alternateLanguage
      alternateSalutation
      alternateTitle
      autoPopRouting
      autoenrollMemberYn
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      cashBlInd
      ccProfileYn
      centralAccountType
      centralDefaultKeyword
      centralNationality
      centralNationalityCode
      centralPriority
      centralStateCode
      centralTerritory
      chainCode
      city
      clientID
      collectionUserId
      combinedName
      commissionCode
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      companyAlternate
      companyGroupId
      companyNameId
      competition
      contractNo
      contractRecvDate
      country
      countryCode
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      defaultKeyword
      deletedFlag
      department
      deptId
      description
      directBillBatchType
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYn
      envelopeGreeting
      externalId
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      first
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      groupProfileName
      guestClassification
      guestPrivYn
      historyYN
      holdCode
      iataCompType
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idNumber
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      includeInTax1099Yn
      incognitoFirstName
      incognitoLastName
      indexName
      industryCode
      influence
      insertDate
      insertUser
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      internalProfileId
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      languageCode
      laptopChange
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailListYN
      mailType
      mailYn
      mailingActionCode
      marketResearchYn
      markets
      masterAccountYn
      middle
      nameComment
      nameTaxType
      nameWithTitle
      name2
      name3
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      passport
      paymentDueDays
      paymentMethodsCode
      paymentMethodsDesc
      phoneNumber
      phoneYn
      postalCode
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      privateYN
      productInterest
      profession
      profileArrCodes
      profileArrangementDesc
      profileCreditLimit
      profileID
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rNAInsertDate
      rNAUpdateDate
      rateStructure
      region
      repAccountTypeDescription
      repAccountsourceDescription
      repCompetitionDescription
      repCorpTypeDescription
      repIATACompType
      repInactiveReason
      repInactiveReasonCode
      repIndustryDescription
      repInfluenceDescription
      repMailActionDescription
      repMarketsDescription
      repNameType
      repNameTypeDescription
      repPriorityDescription
      repRoomsPotentialDescription
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTerritoryDescription
      repTitle
      repTitleName
      repVIPName
      repVIPStatus
      repeatGuestId
      replaceAddress
      resvContact
      roomsPotential
      salutation
      scope
      scopeCity
      searchName
      searchNameAlternate
      sfirst
      smsYn
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      suffix
      summRefCc
      superSearchIndexText
      sxfirstName
      sxname
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      thirdPartyYn
      title
      titleSuffix
      totalArrivals
      totalArrivalsLastyear
      totalCancelledReservations
      totalCancelledResvLastYear
      totalCancelledRooms
      totalCancelledRoomsLastyear
      totalDayUseReservations
      totalDayUseResvLastYear
      totalDayUseRooms
      totalDayUseRoomsLastyear
      totalFbRevenue
      totalFbRevenueLastYear
      totalNoShowReservations
      totalNoShowRooms
      totalNonRevenue
      totalNonRevenueLastyear
      totalNumberShowResvLastYear
      totalNumberShowRoomsLastyear
      totalOtherRevenue
      totalOtherRevenueLastyear
      totalReservationNights
      totalResvNightsLastYear
      totalRevenue
      totalRevenueLastyear
      totalRoomNightsLastyear
      totalRoomRevenue
      totalRoomRevenueLastyear
      totalStays
      totalStaysLastyear
      tourOperatorType
      traceCode
      typeOfTax1099
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
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vendorId
      vendorSiteId
      vipAuthorization
      vipName
      vipStatus
      visaValidityType
      xenvelopeGreeting
      xfirstName
      xmiddleName
    }
    cityDetails {
      attributeCode
      businessTitle
      canDeleteYn
      chainCode
      cityid
      comments
      dSI
      deletedFlag
      description
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
      primaryKeyID
      ranking
      repAttributeCode
      repDescription
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
    promotionDetails {
      authorizerId
      bookingEndDate
      bookingStartDate
      category
      centralDescription
      chainCode
      checkInTime
      checkOutTime
      code
      couponExChars
      couponGenFormat
      couponGenOption
      couponLength
      couponPrefix
      couponSuffix
      dSI
      deletedflag
      description
      group
      idRequiredDescription
      idRequiredYN
      inactiveDate
      inactiveflag
      information
      insertDate
      insertUser
      instructions
      jRNUpdateDate
      jRNUpdateDateAndTime
      limitedTimePromotionYn
      locationID
      lockedByCode
      lockedByType
      longDescription
      mktgprogramid
      organizationID
      primaryKeyID
      promoSequenceId
      promotionid
      property
      repItem
      repItemName
      repUpdateDate
      reportingPromoSequenceId
      rnaInsertDate
      rnaUpdateDate
      setOrAccountFlag
      stayEndDate
      stayStartDate
      updateDate
      updateOutsideBookingDatesYN
      updateUser
      upgradeAllowedYN
      voucherBenefitCode
    }
    companyDetails {
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      actionCode
      activeYN
      address1
      address2
      address3
      address4
      alienRegistrationNo
      allOwnerCodes
      alternateLanguage
      alternateSalutation
      alternateTitle
      autoPopRouting
      autoenrollMemberYn
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      cashBlInd
      ccProfileYn
      centralAccountType
      centralCorporateIDType
      centralDefaultKeyword
      centralNationality
      centralNationalityCode
      centralPriority
      centralStateCode
      centralTerritory
      chainCode
      city
      collectionUserId
      combinedName
      commissionCode
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      companyAlternate
      companyGroupId
      companyNameId
      companyProfileID
      competition
      contractNo
      contractRecvDate
      corporateID
      corporateIDType
      country
      countryCode
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      defaultKeyword
      deletedFlag
      department
      deptId
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYn
      envelopeGreeting
      externalId
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      first
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestPrivYn
      historyYN
      holdCode
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idNumber
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      includeInTax1099Yn
      incognitoFirstName
      incognitoLastName
      indexName
      industryCode
      influence
      insertDate
      insertUser
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      languageCode
      laptopChange
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailListYN
      mailType
      mailYn
      marketResearchYn
      markets
      masterAccountYn
      middle
      name
      name2
      name3
      nameComment
      nameTaxType
      nameWithTitle
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      passport
      paymentDueDays
      paymentMethodsCode
      paymentMethodsDesc
      phoneNumber
      phoneYn
      postalCode
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      privateYN
      productInterest
      profession
      profileArrCodes
      profileArrangementDesc
      profileCreditLimit
      profileId
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rNAInsertDate
      rNAUpdateDate
      rateStructure
      region
      repAccountTypeDescription
      repAccountsourceDescription
      repCompetitionDescription
      repCorpTypeDescription
      repInactiveReason
      repInactiveReasonCode
      repIndustryDescription
      repInfluenceDescription
      repMailActionDescription
      repMarketsDescription
      repNameType
      repNameTypeDescription
      repPriorityDescription
      repRoomsPotentialDescription
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTerritoryDescription
      repTitle
      repTitleName
      repVIPName
      repVIPStatus
      repeatGuestId
      replaceAddress
      resvContact
      roomsPotential
      salutation
      scope
      scopeCity
      searchName
      searchNameAlternate
      sfirst
      smsYn
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      suffix
      summRefCc
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      thirdPartyYn
      title
      titleSuffix
      totalArrivals
      totalArrivalsLastyear
      totalCancelledReservations
      totalCancelledResvLastYear
      totalCancelledRooms
      totalCancelledRoomsLastyear
      totalDayUseReservations
      totalDayUseResvLastYear
      totalDayUseRooms
      totalDayUseRoomsLastyear
      totalFbRevenue
      totalFbRevenueLastYear
      totalNoShowReservations
      totalNoShowRooms
      totalNonRevenue
      totalNonRevenueLastyear
      totalNumberShowResvLastYear
      totalNumberShowRoomsLastyear
      totalOtherRevenue
      totalOtherRevenueLastyear
      totalReservationNights
      totalResvNightsLastYear
      totalRevenue
      totalRevenueLastyear
      totalRoomNightsLastyear
      totalRoomRevenue
      totalRoomRevenueLastyear
      totalStays
      totalStaysLastyear
      tourOperatorType
      traceCode
      typeOfTax1099
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
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vendorId
      vendorSiteId
      vipAuthorization
      vipName
      vipStatus
      visaValidityType
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
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
    travelAgentDetails {
      aRNumber
      aRNumberCentral
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      activeYN
      address1
      address2
      address3
      address4
      allOwnerCodes
      alternateLanguage
      alternateSalutation
      alternateTitle
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      centralDefaultKeyword
      centralIATANumberType
      centralNationality
      centralNationalityCode
      chainCode
      city
      combinedName
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      companyAlternate
      competition
      country
      countryCode
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      defaultKeyword
      deletedFlag
      displayName
      email
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionYn
      faxNumber
      first
      gender
      guestPrivYn
      historyYN
      holdCode
      iATANumber
      iATANumberType
      iataConsortia
      inactiveDate
      inactiveFlag
      industryCode
      insertDate
      insertUser
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      internalProfileId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      languageDescription
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailListYN
      mailType
      mailYn
      mailingActionCode
      marketResearchYn
      markets
      middle
      name
      name2
      name3
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      paymentDueDays
      phoneNumber
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      privateYN
      productInterest
      profession
      profileID
      profileType
      propertyRegistered
      protected
      rNAInsertDate
      rNAUpdateDate
      repAccountType
      repAccountTypeDescription
      repAccountsourceDescription
      repCompetitionDescription
      repCorpTypeDescription
      repInactiveReason
      repInactiveReasonCode
      repIndustryDescription
      repInfluenceDescription
      repMailActionDescription
      repMarketsDescription
      repNameType
      repNameTypeDescription
      repPriority
      repPriorityDescription
      repRoomsPotentialDescription
      repScopeCityDescription
      repScopeDescription
      repStateCode
      repStateDescription
      repTerritory
      repTerritoryDescription
      repTitle
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      salutation
      scope
      scopeCity
      searchName
      searchNameAlternate
      sfirst
      state
      stateCode
      subscribedProperties
      sxfirstName
      sxname
      taxCategory
      taxID1
      taxID2
      taxType
      territory
      thirdPartyYn
      title
      totalArrivals
      totalArrivalsLastyear
      totalCancelledReservations
      totalCancelledResvLastYear
      totalCancelledRooms
      totalCancelledRoomsLastyear
      totalDayUseReservations
      totalDayUseResvLastYear
      totalDayUseRooms
      totalDayUseRoomsLastyear
      totalFbRevenue
      totalFbRevenueLastYear
      totalNoShowReservations
      totalNoShowRooms
      totalNonRevenue
      totalNonRevenueLastyear
      totalNumberShowResvLastYear
      totalNumberShowRoomsLastyear
      totalOtherRevenue
      totalOtherRevenueLastyear
      totalReservationNights
      totalResvNightsLastYear
      totalRevenue
      totalRevenueLastyear
      totalRoomNightsLastyear
      totalRoomRevenue
      totalRoomRevenueLastyear
      totalStays
      totalStaysLastyear
      traceCode
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
      updateDate
      updateFaxDate
      updateUser
      vipName
      vipStatus
      xenvelopeGreeting
      xfirstName
      xmiddleName
    }
    allotmentStatisticsDetails {
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
      blockDateActual
      blockDateDefinite
      blockDateProspect
      blockDateTentative
      blockDescription
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
    contactDetails {
      aRCreditLimitYN
      aRNumber
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountType
      accountsource
      acctContact
      actionCode
      activeFlag
      addressType
      address1
      address2
      address3
      address4
      alienRegistrationNo
      allProperties
      allSalesRepCodes
      alternateFirstName
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateTitle
      arNumberCentral
      autoPopRouting
      autoenrollMemberYn
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      businessSegment
      businessSegmentDescription
      businessTitle
      cRSNameid
      ccProfileYn
      centralBusinessSegment
      centralBusinessSegmentDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralInfluence
      centralInfluenceDescription
      centralKeyword
      centralMailActionDescription
      centralNationality
      centralNationalityDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralTerritory
      centralTerritoryDescription
      centralTitle
      centralVIPCode
      centralVIPCodeDescription
      chainCode
      city
      cityExt
      clientID
      collectionUserId
      combinedName
      commPayCentral
      commissionCode
      commissionCurrencyId
      commissionid
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      companyGroupId
      companyNameId
      competitionCode
      contactEmailPrimary
      contactPhonePrimary
      contactProfileID
      contactYN
      contractNo
      contractRecvDate
      country
      countryCode
      countryDesc
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      deletedFlag
      department
      deptId
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      emailYn
      envelopeGreeting
      envelopeGreetingAlternate
      externalDisplayName
      externalFirstName
      externalId
      externalName
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      firstName
      firstNameIncognito
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestPrivYn
      historyYN
      holdCode
      iataCompType
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idNumber
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      includeInTax1099Yn
      indexName
      industryCode
      influence
      influenceDescription
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      language
      languageDescription
      laptopChange
      lastGroup
      lastName
      lastNameAlternate
      lastNameIncognito
      lastRate
      lastRoom
      lastRoomResort
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailActionDescription
      mailListYN
      mailType
      mailYn
      mailingActionCode
      marketResearchYn
      masterAccountYn
      middleName
      name
      nameComment
      nameTaxType
      nameWithTitle
      name2
      name3
      nationalityCode
      nationalityDescription
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      passport
      paymentDueDays
      paymentMethodsCode
      paymentMethodsDesc
      phoneYn
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      privateYN
      productInterest
      profession
      profileArrCodes
      profileArrangementDesc
      profileCreditLimit
      profileId
      profileType
      protected
      psuedoProfileYn
      rNAInsertDate
      rNAUpdateDate
      rateStructure
      region
      regionid
      repAccountType
      repAccountTypeDescription
      repAccountsource
      repAccountsourceDescription
      repCompetitionCode
      repCompetitionDescription
      repCorpTypeDescription
      repIATACompType
      repIndustryCode
      repIndustryDescription
      repMailActionCodes
      repNameType
      repNameTypeDescription
      repPriority
      repPriorityDescription
      repRoomsPotential
      repRoomsPotentialDescription
      repStateCode
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repeatGuestId
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      resvContact
      roomsPotential
      salesRep
      salesRepCode
      salutation
      salutationAlternate
      scope
      scopeCity
      scopeCityDescription
      scopeDescription
      searchName
      searchNameAlternate
      sfirst
      smsYn
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      stateDesc
      stateDescription
      suffix
      summRefCc
      summRefCurrencyId
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      title
      titleSuffix
      totalArrivals
      totalArrivalsLastyear
      totalCancelledReservations
      totalCancelledResvLastYear
      totalCancelledRooms
      totalCancelledRoomsLastyear
      totalDayUseReservations
      totalDayUseResvLastYear
      totalDayUseRooms
      totalDayUseRoomsLastyear
      totalFbRevenue
      totalFbRevenueLastYear
      totalNoShowReservations
      totalNoShowRooms
      totalNonRevenue
      totalNonRevenueLastyear
      totalNumberShowResvLastYear
      totalNumberShowRoomsLastyear
      totalOtherRevenue
      totalOtherRevenueLastyear
      totalReservationNights
      totalResvNightsLastYear
      totalRevenue
      totalRevenueLastyear
      totalRoomNightsLastyear
      totalRoomRevenue
      totalRoomRevenueLastyear
      totalStays
      totalStaysLastyear
      tourOperatorType
      traceCode
      traceCodeDescription
      typeOfTax1099
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
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vIPCode
      vIPCodeDescription
      vendorId
      vendorSiteId
      vipAuthorization
      visaValidityType
      xcompanyName
      xmiddleName
      zipCode
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
reservation_daily_statistics_details_schema = {
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'agentId': pl.Float64,
    'agentprofileid': pl.Float64,
    'allotmentHeaderId': pl.Float64,
    'allotmentid': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalRooms': pl.Float64,
    'beginDate': pl.Utf8,
    'biReservationNameId': pl.Float64,
    'birthDate': pl.Utf8,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDate': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'cAdvanceTotalOtherTax': pl.Float64,
    'cCashRoomRevenue': pl.Float64,
    'cCompRoomRevenue': pl.Float64,
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
    'cPrAdvanceTotalFoodTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRsAdvanceFoodRevenue': pl.Float64,
    'cRsAdvanceFoodTax': pl.Float64,
    'cRsAdvanceNonRevenue': pl.Float64,
    'cRsAdvanceNonRevenueTax': pl.Float64,
    'cRsAdvanceOtherRevenue': pl.Float64,
    'cRsAdvanceOtherTax': pl.Float64,
    'cRsAdvanceRoomRevenue': pl.Float64,
    'cRsAdvanceRoomTax': pl.Float64,
    'cRsAdvanceTotalRevenue': pl.Float64,
    'cRsAdvanceTotalTax': pl.Float64,
    'cUpsoldRevenue': pl.Float64,
    'cancellationDate': pl.Utf8,
    'cancelledPersons': pl.Float64,
    'cancelledReservations': pl.Float64,
    'cancelledRooms': pl.Float64,
    'cashRoomNts': pl.Float64,
    'cashRoomRevenue': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralDistributedFoodRevenue': pl.Float64,
    'centralDistributedFoodRevenueAsPayee': pl.Float64,
    'centralDistributedNonRevenue': pl.Float64,
    'centralDistributedNonRevenueAsPayee': pl.Float64,
    'centralDistributedOtherRevenue': pl.Float64,
    'centralDistributedOtherRevenueAsPayee': pl.Float64,
    'centralDistributedRoomRevenue': pl.Float64,
    'centralDistributedRoomRevenueAsPayee': pl.Float64,
    'centralDistributedTotalFoodTaxAsPayee': pl.Float64,
    'centralDistributedTotalNonRevenueTax': pl.Float64,
    'centralDistributedTotalNonRevenueTaxAsPayee': pl.Float64,
    'centralDistributedTotalOtherTaxAsPayee': pl.Float64,
    'centralDistributedTotalRevenue': pl.Float64,
    'centralDistributedTotalRevenueAsPayee': pl.Float64,
    'centralDistributedTotalRoomTax': pl.Float64,
    'centralDistributedTotalRoomTaxAsPayee': pl.Float64,
    'centralDistributedTotalTax': pl.Float64,
    'centralDistributedTotalTaxAsPayee': pl.Float64,
    'centralExchangeRate': pl.Float64,
    'centralFoodRevenue': pl.Float64,
    'centralFoodRevenueAsPayee': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNonRevenue': pl.Float64,
    'centralNonRevenueAsPayee': pl.Float64,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
    'centralOriginalRoomType': pl.Utf8,
    'centralOtherRevenue': pl.Float64,
    'centralOtherRevenueAsPayee': pl.Float64,
    'centralPackageFoodRevenue': pl.Float64,
    'centralPackageFoodRevenueAsPayee': pl.Float64,
    'centralPackageNonRevenue': pl.Float64,
    'centralPackageNonRevenueAsPayee': pl.Float64,
    'centralPackageOtherRevenue': pl.Float64,
    'centralPackageOtherRevenueAsPayee': pl.Float64,
    'centralPackageRoomRevenue': pl.Float64,
    'centralPackageRoomRevenueAsPayee': pl.Float64,
    'centralRateCategory': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomRevenueAsPayee': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'centralTotalFoodTax': pl.Float64,
    'centralTotalFoodTaxGeneratedAsPayee': pl.Float64,
    'centralTotalNonRevenueTax': pl.Float64,
    'centralTotalNonRevenueTaxAsPayee': pl.Float64,
    'centralTotalOtherTax': pl.Float64,
    'centralTotalOtherTaxAsPayee': pl.Float64,
    'centralTotalPackageRevenue': pl.Float64,
    'centralTotalPackageRevenueAsPayee': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRevenueAsPayee': pl.Float64,
    'centralTotalRoomTax': pl.Float64,
    'centralTotalRoomTaxAsPayee': pl.Float64,
    'centralTotalTax': pl.Float64,
    'centralTotalTaxAsPayee': pl.Float64,
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
    'cityid': pl.Utf8,
    'compRoomNts': pl.Float64,
    'compRoomRevenue': pl.Float64,
    'companyId': pl.Float64,
    'companyProfileID': pl.Float64,
    'companyProfileName': pl.Utf8,
    'compflag': pl.Utf8,
    'complimentaryYN': pl.Utf8,
    'contactId': pl.Float64,
    'contactProfileID': pl.Float64,
    'contactflag': pl.Utf8,
    'country': pl.Utf8,
    'countryMainGroup': pl.Utf8,
    'countryName': pl.Utf8,
    'countrygroupid': pl.Utf8,
    'countryid': pl.Utf8,
    'cribs': pl.Float64,
    'dSI': pl.Int64,
    'dayUsePersons': pl.Float64,
    'dayUseReservations': pl.Float64,
    'dayUseRooms': pl.Float64,
    'deletedFlag': pl.Utf8,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'distributedFoodRevenue': pl.Float64,
    'distributedFoodRevenueAsPayee': pl.Float64,
    'distributedNonRevenue': pl.Float64,
    'distributedNonRevenueAsPayee': pl.Float64,
    'distributedOtherRevenue': pl.Float64,
    'distributedOtherRevenueAsPayee': pl.Float64,
    'distributedRoomRevenue': pl.Float64,
    'distributedRoomRevenueAsPayee': pl.Float64,
    'distributedTotalFoodTaxAsPayee': pl.Float64,
    'distributedTotalNonRevenueTax': pl.Float64,
    'distributedTotalNonRevenueTaxAsPayee': pl.Float64,
    'distributedTotalOtherTax': pl.Float64,
    'distributedTotalOtherTaxAsPayee': pl.Float64,
    'distributedTotalRevenue': pl.Float64,
    'distributedTotalRevenueAsPayee': pl.Float64,
    'distributedTotalRoomTax': pl.Float64,
    'distributedTotalRoomTaxAsPayee': pl.Float64,
    'distributedTotalTax': pl.Float64,
    'distributedTotalTaxAsPayee': pl.Float64,
    'district': pl.Utf8,
    'dueOutYn': pl.Utf8,
    'dueoutflag': pl.Utf8,
    'endDate': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'extendedStayTier': pl.Float64,
    'extraBeds': pl.Float64,
    'fiscalregioncode': pl.Utf8,
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
    'foodRevenueAsPayee': pl.Float64,
    'freqflyermembtype': pl.Utf8,
    'freqguestmembtype': pl.Utf8,
    'groupId': pl.Float64,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guestProfileID': pl.Float64,
    'gueststatusid': pl.Utf8,
    'houseUseYn': pl.Utf8,
    'houseuseflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'internalCompanyprofileid': pl.Float64,
    'internalContactprofileid': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'internalGroupprofileid': pl.Float64,
    'internalMembershipid': pl.Float64,
    'internalReservationNameId': pl.Float64,
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
    'membershipCardNo': pl.Utf8,
    'membershipId': pl.Float64,
    'multipleOccupancyRooms': pl.Float64,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'nationalityid': pl.Utf8,
    'nights': pl.Float64,
    'noShowReservations': pl.Float64,
    'noShowPersons': pl.Float64,
    'noShowRooms': pl.Float64,
    'nonRevenue': pl.Float64,
    'nonRevenueAsPayee': pl.Float64,
    'numberOfStays': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originalEndDate': pl.Utf8,
    'originalRoomCategory': pl.Utf8,
    'otherRevenue': pl.Float64,
    'otherRevenueAsPayee': pl.Float64,
    'outOfOrderRooms': pl.Float64,
    'outOfServiceRooms': pl.Float64,
    'ownerRentalYn': pl.Utf8,
    'ownerfriendfamilyflag': pl.Utf8,
    'ownerrentalflag': pl.Utf8,
    'packageFoodRevenue': pl.Float64,
    'packageFoodRevenueAsPayee': pl.Float64,
    'packageNonRevenue': pl.Float64,
    'packageNonRevenueAsPayee': pl.Float64,
    'packageOtherRevenue': pl.Float64,
    'packageOtherRevenueAsPayee': pl.Float64,
    'packageRoomRevenue': pl.Float64,
    'packageRoomRevenueAsPayee': pl.Float64,
    'parentCompanyId': pl.Float64,
    'parentcompanyprofileid': pl.Float64,
    'physicalQuantity': pl.Float64,
    'physicalRooms': pl.Float64,
    'prAdvTotalFoodTax': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryYn': pl.Float64,
    'primaryflag': pl.Float64,
    'profiledailytotalid': pl.Float64,
    'profileid': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionCodeDesc': pl.Utf8,
    'promotionid': pl.Utf8,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'pseudoroomflag': pl.Utf8,
    'quantity': pl.Float64,
    'rateAmount': pl.Float64,
    'rateCategory': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecategoryid': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionid': pl.Utf8,
    'repPromotionCode': pl.Utf8,
    'repPromotionCodeDescription': pl.Utf8,
    'reservationArrivals': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationNights': pl.Float64,
    'reservationNumberOfStays': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'resvinsertsource': pl.Utf8,
    'resvinsertsourcetype': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomAdults': pl.Float64,
    'roomCategory': pl.Utf8,
    'roomChildren': pl.Float64,
    'roomClass': pl.Utf8,
    'roomNights': pl.Float64,
    'roomReservationStatus': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueAsPayee': pl.Float64,
    'roomcategoryid': pl.Utf8,
    'roomclassid': pl.Utf8,
    'roomid': pl.Utf8,
    'rsAdvFoodRevenue': pl.Float64,
    'rsAdvFoodTax': pl.Float64,
    'rsAdvNonRevenue': pl.Float64,
    'rsAdvNonRevenueTax': pl.Float64,
    'rsAdvOtherRevenue': pl.Float64,
    'rsAdvOtherTax': pl.Float64,
    'rsAdvRoomRevenue': pl.Float64,
    'rsAdvRoomTax': pl.Float64,
    'rsAdvTotalRevenue': pl.Float64,
    'rsAdvTotalTax': pl.Float64,
    'singleOccupancyRooms': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceProfId': pl.Float64,
    'sourceProfileID': pl.Float64,
    'sourcegroupid': pl.Utf8,
    'sourceid': pl.Utf8,
    'sourceprofprofileid': pl.Float64,
    'stateCode': pl.Utf8,
    'stateid': pl.Utf8,
    'stayAdults': pl.Float64,
    'stayChildren': pl.Float64,
    'stayPersons': pl.Float64,
    'totalFoodTax': pl.Float64,
    'totalFoodTaxGeneratedAsPayee': pl.Float64,
    'totalNonRevenueTax': pl.Float64,
    'totalNonRevenueTaxAsPayee': pl.Float64,
    'totalOtherTax': pl.Float64,
    'totalOtherTaxAsPayee': pl.Float64,
    'totalPackageRevenue': pl.Float64,
    'totalPackageRevenueAsPayee': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueAsPayee': pl.Float64,
    'totalRoomTax': pl.Float64,
    'totalRoomTaxAsPayee': pl.Float64,
    'totalTax': pl.Float64,
    'totalTaxAsPayee': pl.Float64,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'updateDate': pl.Utf8,
    'upsoldRevenue': pl.Float64,
    'vIPStatus': pl.Utf8,
    'walkinYn': pl.Utf8,
    'walkinflag': pl.Utf8,
    'zipCode': pl.Utf8,
}
```
```python
parent_company_profile_deatils_schema = {
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allOwnerCodes': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateMiddleName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'autoPopRouting': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'cashBlInd': pl.Utf8,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'competition': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corporateID': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'first': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idNumber': pl.Utf8,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'incognitoFirstName': pl.Utf8,
    'incognitoLastName': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'influence': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailListYN': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'markets': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'middle': pl.Utf8,
    'name': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameWithTitle': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneNumber': pl.Utf8,
    'phoneYn': pl.Utf8,
    'postalCode': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'privateYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileArrCodes': pl.Utf8,
    'profileArrangementDesc': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repInactiveReasonCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionDescription': pl.Utf8,
    'repMarketsDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitle': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resvContact': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalArrivals': pl.Float64,
    'totalArrivalsLastyear': pl.Float64,
    'totalCancelledReservations': pl.Float64,
    'totalCancelledResvLastYear': pl.Float64,
    'totalCancelledRooms': pl.Float64,
    'totalCancelledRoomsLastyear': pl.Float64,
    'totalDayUseReservations': pl.Float64,
    'totalDayUseResvLastYear': pl.Float64,
    'totalDayUseRooms': pl.Float64,
    'totalDayUseRoomsLastyear': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueLastYear': pl.Float64,
    'totalNoShowReservations': pl.Float64,
    'totalNoShowRooms': pl.Float64,
    'totalNonRevenue': pl.Float64,
    'totalNonRevenueLastyear': pl.Float64,
    'totalNumberShowResvLastYear': pl.Float64,
    'totalNumberShowRoomsLastyear': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueLastyear': pl.Float64,
    'totalReservationNights': pl.Float64,
    'totalResvNightsLastYear': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueLastyear': pl.Float64,
    'totalRoomNightsLastyear': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueLastyear': pl.Float64,
    'totalStays': pl.Float64,
    'totalStaysLastyear': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
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
guest_profile_all_information_details_schema = {
    'guestProfileID': pl.Float64,
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountsourceDesc': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressId': pl.Float64,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allResorts': pl.Utf8,
    'alternateEnvelopeGreeting': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'autoEnrollMemberYN': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessSegmentDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralBusinessSegmentDescription': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralGuestTitleCode': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralMailingActionCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'comments': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodes': pl.Utf8,
    'commissionCurrencyId': pl.Utf8,
    'commissionid': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'competitionDesc': pl.Utf8,
    'contactYN': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corpTypeDesc': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'debtorName': pl.Utf8,
    'decimalPositions': pl.Float64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYN': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalDisplayName': pl.Utf8,
    'externalFirstName': pl.Utf8,
    'externalId': pl.Utf8,
    'externalName': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fMembershipType': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'firstName': pl.Utf8,
    'firstNameAlternate': pl.Utf8,
    'firstNameIncognito': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestCountry': pl.Utf8,
    'guestCurrencyCode': pl.Utf8,
    'guestLanguageCode': pl.Utf8,
    'guestLastName': pl.Utf8,
    'guestMiddleName': pl.Utf8,
    'guestNameSuffix': pl.Utf8,
    'guestPrivilegeYN': pl.Utf8,
    'guestTitleCode': pl.Utf8,
    'hasRequestedMailYN': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryDesc': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDesc': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastGroup': pl.Utf8,
    'lastNameAlternate': pl.Utf8,
    'lastNameIncognito': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRateCode': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastRoomProperty': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYN': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'priorityDesc': pl.Utf8,
    'privacyFlagYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'requestType': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'roomsPotentialDesc': pl.Utf8,
    'sMSYN': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDesc': pl.Utf8,
    'scopeDesc': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDescription': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDesc': pl.Utf8,
    'thirdPartyYN': pl.Utf8,
    'titleAlternate': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalStay': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'tracecodeDesc': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vIPCode': pl.Utf8,
    'vIPDescription': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xdisplayName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
nationality_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
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
    'nationalityid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
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
```python
guest_status_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'guestStatus': pl.Utf8,
    'gueststatusid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalEntityname': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'statustype': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_accounts_source_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
reservation_statistics_details_schema = {
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
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
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
    'sharedConfirmationNo': pl.Utf8,
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
```python
booked_room_category_details_schema = {
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
    'chargedRoomTypeDescription': pl.Utf8,
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
    'roomCategoryID': pl.Utf8,
    'roomCategoryPMSRef': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomInfoURL': pl.Utf8,
    'roomPool': pl.Utf8,
    'roomType': pl.Utf8,
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
country_group_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'countryGroup': pl.Utf8,
    'countryGroupCode': pl.Utf8,
    'countrygroupid': pl.Utf8,
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
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_accounts_travel_agent_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
profile_accounts_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
state_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'country': pl.Utf8,
    'countryid': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'stateCode': pl.Utf8,
    'stateid': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
group_details_schema = {
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allOwnerCodes': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'autoPopRouting': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'cashBlInd': pl.Utf8,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'first': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'groupProfileName': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataCompType': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idNumber': pl.Utf8,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'incognitoFirstName': pl.Utf8,
    'incognitoLastName': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'influence': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailListYN': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'markets': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameWithTitle': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneNumber': pl.Utf8,
    'phoneYn': pl.Utf8,
    'postalCode': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'privateYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileArrCodes': pl.Utf8,
    'profileArrangementDesc': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileID': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIATACompType': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repInactiveReasonCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionDescription': pl.Utf8,
    'repMarketsDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitle': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resvContact': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalArrivals': pl.Float64,
    'totalArrivalsLastyear': pl.Float64,
    'totalCancelledReservations': pl.Float64,
    'totalCancelledResvLastYear': pl.Float64,
    'totalCancelledRooms': pl.Float64,
    'totalCancelledRoomsLastyear': pl.Float64,
    'totalDayUseReservations': pl.Float64,
    'totalDayUseResvLastYear': pl.Float64,
    'totalDayUseRooms': pl.Float64,
    'totalDayUseRoomsLastyear': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueLastYear': pl.Float64,
    'totalNoShowReservations': pl.Float64,
    'totalNoShowRooms': pl.Float64,
    'totalNonRevenue': pl.Float64,
    'totalNonRevenueLastyear': pl.Float64,
    'totalNumberShowResvLastYear': pl.Float64,
    'totalNumberShowRoomsLastyear': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueLastyear': pl.Float64,
    'totalReservationNights': pl.Float64,
    'totalResvNightsLastYear': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueLastyear': pl.Float64,
    'totalRoomNightsLastyear': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueLastyear': pl.Float64,
    'totalStays': pl.Float64,
    'totalStaysLastyear': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
city_details_schema = {
    'attributeCode': pl.Utf8,
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'cityid': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
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
    'primaryKeyID': pl.Int64,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
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
promotion_details_schema = {
    'authorizerId': pl.Float64,
    'bookingEndDate': pl.Utf8,
    'bookingStartDate': pl.Utf8,
    'category': pl.Utf8,
    'centralDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'checkInTime': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'code': pl.Utf8,
    'couponExChars': pl.Utf8,
    'couponGenFormat': pl.Utf8,
    'couponGenOption': pl.Utf8,
    'couponLength': pl.Float64,
    'couponPrefix': pl.Utf8,
    'couponSuffix': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'group': pl.Utf8,
    'idRequiredDescription': pl.Utf8,
    'idRequiredYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'information': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'instructions': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'limitedTimePromotionYn': pl.Utf8,
    'locationID': pl.Utf8,
    'lockedByCode': pl.Utf8,
    'lockedByType': pl.Utf8,
    'longDescription': pl.Utf8,
    'mktgprogramid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'promoSequenceId': pl.Float64,
    'promotionid': pl.Utf8,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'reportingPromoSequenceId': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'setOrAccountFlag': pl.Utf8,
    'stayEndDate': pl.Utf8,
    'stayStartDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateOutsideBookingDatesYN': pl.Utf8,
    'updateUser': pl.Int64,
    'upgradeAllowedYN': pl.Utf8,
    'voucherBenefitCode': pl.Utf8,
}
```
```python
company_details_schema = {
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allOwnerCodes': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'autoPopRouting': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'cashBlInd': pl.Utf8,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'companyProfileID': pl.Float64,
    'competition': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corporateID': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'first': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idNumber': pl.Utf8,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'incognitoFirstName': pl.Utf8,
    'incognitoLastName': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'influence': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailListYN': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'markets': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'middle': pl.Utf8,
    'name': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameWithTitle': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneNumber': pl.Utf8,
    'phoneYn': pl.Utf8,
    'postalCode': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'privateYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileArrCodes': pl.Utf8,
    'profileArrangementDesc': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repInactiveReasonCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionDescription': pl.Utf8,
    'repMarketsDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitle': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resvContact': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalArrivals': pl.Float64,
    'totalArrivalsLastyear': pl.Float64,
    'totalCancelledReservations': pl.Float64,
    'totalCancelledResvLastYear': pl.Float64,
    'totalCancelledRooms': pl.Float64,
    'totalCancelledRoomsLastyear': pl.Float64,
    'totalDayUseReservations': pl.Float64,
    'totalDayUseResvLastYear': pl.Float64,
    'totalDayUseRooms': pl.Float64,
    'totalDayUseRoomsLastyear': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueLastYear': pl.Float64,
    'totalNoShowReservations': pl.Float64,
    'totalNoShowRooms': pl.Float64,
    'totalNonRevenue': pl.Float64,
    'totalNonRevenueLastyear': pl.Float64,
    'totalNumberShowResvLastYear': pl.Float64,
    'totalNumberShowRoomsLastyear': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueLastyear': pl.Float64,
    'totalReservationNights': pl.Float64,
    'totalResvNightsLastYear': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueLastyear': pl.Float64,
    'totalRoomNightsLastyear': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueLastyear': pl.Float64,
    'totalStays': pl.Float64,
    'totalStaysLastyear': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
block_details_schema = {
    'actionId': pl.Float64,
    'actualAverageRoomRate': pl.Float64,
    'actualFBRevenue': pl.Float64,
    'actualOtherRevenue': pl.Float64,
    'actualRoomNightsSold': pl.Float64,
    'actualRoomRevenue': pl.Float64,
    'addInfo': pl.Utf8,
    'agentContactNameId': pl.Float64,
    'agentNameId': pl.Float64,
    'agentprofileid': pl.Float64,
    'allAliases': pl.Utf8,
    'allBlockOwners': pl.Utf8,
    'allCateringOwners': pl.Utf8,
    'allCompanyContacts': pl.Utf8,
    'allRateCodes': pl.Utf8,
    'allRoomOwners': pl.Utf8,
    'allRoomPools': pl.Utf8,
    'allRoomTypes': pl.Utf8,
    'allSourceContacts': pl.Utf8,
    'allTravelAgentContacts': pl.Utf8,
    'allotmentOrigin': pl.Utf8,
    'allotmentType': pl.Utf8,
    'allotmentcurrencyid': pl.Utf8,
    'allotmentid': pl.Float64,
    'allowPickup': pl.Utf8,
    'alternateBlockName': pl.Utf8,
    'alternateDates': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'attachmentURL': pl.Utf8,
    'attendeesGuaranteed': pl.Float64,
    'autoLoadForecastYn': pl.Utf8,
    'averageRate': pl.Float64,
    'bEOLastPrint': pl.Utf8,
    'beginDateOriginal': pl.Utf8,
    'blockAlias': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockDateActual': pl.Utf8,
    'blockDateDefinite': pl.Utf8,
    'blockDateProspect': pl.Utf8,
    'blockDateTentative': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockID': pl.Float64,
    'blockMode': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockOwnerFullName': pl.Utf8,
    'blockPackage': pl.Utf8,
    'blockPackageDescription': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockStatusDescription': pl.Utf8,
    'blockTypeCode': pl.Utf8,
    'blockTypeCodeDescription': pl.Utf8,
    'blockpackageid': pl.Utf8,
    'bookingId': pl.Utf8,
    'bookingMethodOrderBy': pl.Float64,
    'bookingStatusOrder': pl.Float64,
    'bookingType': pl.Utf8,
    'bookingTypeDescription': pl.Utf8,
    'bookingmethodInactiveDate': pl.Utf8,
    'bookingsourceid': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'bookingtypeid': pl.Utf8,
    'breakfastDescription': pl.Utf8,
    'breakfastInclPrice': pl.Float64,
    'breakfastInclYn': pl.Utf8,
    'breakfastIncluded': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'bwiLeadId': pl.Utf8,
    'bwiUrl': pl.Utf8,
    'cBreakfastInclPrice': pl.Float64,
    'cBreakfastPrice': pl.Float64,
    'cCompRoomValue': pl.Float64,
    'cDoubleRoomSupplementPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFBCommission1': pl.Float64,
    'cFBCommission2': pl.Float64,
    'cPorteragePrice': pl.Float64,
    'cRoomCommission1': pl.Float64,
    'cRoomCommission2': pl.Float64,
    'cServiceCharge': pl.Float64,
    'cServiceFee': pl.Float64,
    'cRSGtdYn': pl.Utf8,
    'cancelRule': pl.Utf8,
    'canceldestinationid': pl.Utf8,
    'cancellationDestination': pl.Utf8,
    'cancellationDestinationDescription': pl.Utf8,
    'cancellationNumber': pl.Float64,
    'cancellationPenaltyAmount': pl.Float64,
    'cancellationreasonid': pl.Utf8,
    'catCutoff': pl.Utf8,
    'catDateProspect': pl.Utf8,
    'catOwner': pl.Float64,
    'catOwnerProperty': pl.Utf8,
    'catReturnToInventory': pl.Utf8,
    'catStartingStatus': pl.Utf8,
    'catcurrencyid': pl.Utf8,
    'cateringCancellationDate': pl.Utf8,
    'cateringCancellationDescription': pl.Utf8,
    'cateringCancellationNumber': pl.Float64,
    'cateringCancellationReason': pl.Utf8,
    'cateringCurrency': pl.Utf8,
    'cateringDateActual': pl.Utf8,
    'cateringDecisionDate': pl.Utf8,
    'cateringDeductInventory': pl.Utf8,
    'cateringExchangeRate': pl.Float64,
    'cateringFollowupDate': pl.Utf8,
    'cateringOnlyYN': pl.Utf8,
    'cateringOrderBy': pl.Float64,
    'cateringOwnerCode': pl.Utf8,
    'cateringOwnerFullName': pl.Utf8,
    'cateringPkgsYn': pl.Utf8,
    'cateringQuoteCurrency': pl.Utf8,
    'cateringStatus': pl.Utf8,
    'cateringStatusColor': pl.Utf8,
    'cateringStatusDescription': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringcancelreasonid': pl.Float64,
    'cateringcurrencyid': pl.Utf8,
    'cateringowneremployeeid': pl.Float64,
    'cateringquotecurrencyid': pl.Utf8,
    'cateringstatusid': pl.Utf8,
    'cenralFBRevenue': pl.Float64,
    'centralActualAverageRoomRate': pl.Float64,
    'centralActualFBRevenue': pl.Float64,
    'centralActualOtherRevenue': pl.Float64,
    'centralActualRoomRevenue': pl.Float64,
    'centralAverageRoomRate': pl.Float64,
    'centralBlockPackage': pl.Utf8,
    'centralBlockPackageDescription': pl.Utf8,
    'centralBlockStatus': pl.Utf8,
    'centralBlockStatusDescription': pl.Utf8,
    'centralBlockTypeCode': pl.Utf8,
    'centralBlockTypeCodeDescription': pl.Utf8,
    'centralBookingType': pl.Utf8,
    'centralBookingTypeDescription': pl.Utf8,
    'centralCancellationDestination': pl.Utf8,
    'centralCancellationDestinationDescription': pl.Utf8,
    'centralCancellationPenaltyAmount': pl.Float64,
    'centralCateringStatus': pl.Utf8,
    'centralCateringStatusDescription': pl.Utf8,
    'centralConversionCode': pl.Utf8,
    'centralCoversionCodeDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralItemsForThisBlock': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMeetingBudget': pl.Float64,
    'centralMeetingRevenue': pl.Float64,
    'centralOriginCode': pl.Utf8,
    'centralOriginCodeDescription': pl.Utf8,
    'centralOtherRevenue': pl.Float64,
    'centralOwner': pl.Utf8,
    'centralPayment': pl.Utf8,
    'centralPaymentDescription': pl.Utf8,
    'centralRankingCode': pl.Utf8,
    'centralRankingCodeDescription': pl.Utf8,
    'centralReservationMethodCode': pl.Utf8,
    'centralReservationMethodDescription': pl.Utf8,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceCodeDescription': pl.Utf8,
    'centralTaxAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'channelid': pl.Utf8,
    'code': pl.Utf8,
    'comAddress': pl.Utf8,
    'comAddress2': pl.Utf8,
    'comAddress3': pl.Utf8,
    'comMethod': pl.Utf8,
    'comMethod2': pl.Utf8,
    'comMethod3': pl.Utf8,
    'commissionAmount': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'compPerStayYn': pl.Utf8,
    'compRoomValue': pl.Float64,
    'compRooms': pl.Float64,
    'compRoomsFixedYn': pl.Utf8,
    'companyAll': pl.Utf8,
    'companyNameId': pl.Float64,
    'companyprofileid': pl.Float64,
    'competition': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactprofileid': pl.Float64,
    'contractNumber': pl.Utf8,
    'controlBlockLocally': pl.Utf8,
    'conversionCode': pl.Utf8,
    'coversionCodeDescription': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdAsOpportunityYN': pl.Utf8,
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'dateAcl': pl.Utf8,
    'dateCfl': pl.Utf8,
    'dateDefinite': pl.Utf8,
    'dateLsl': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'datePel': pl.Utf8,
    'dateTdl': pl.Utf8,
    'dateTentative': pl.Utf8,
    'dblRoomSupplementPrice': pl.Float64,
    'deductInventory': pl.Utf8,
    'defaultPmReservationNameId': pl.Float64,
    'deletedflag': pl.Utf8,
    'departureTime': pl.Utf8,
    'description': pl.Utf8,
    'distributed': pl.Utf8,
    'distributedDate': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doubleRoomSupplementYN': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'dueDateOrd': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateOriginal': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'eventAttendees': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exclusionMessage': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalRfpId': pl.Utf8,
    'externalRfpSystem': pl.Utf8,
    'externallyLocked': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fbAgendaCurrency': pl.Utf8,
    'fbCommission1': pl.Float64,
    'fbCommission2': pl.Float64,
    'fitContractMode': pl.Utf8,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'fitdiscounttype': pl.Utf8,
    'flatRateYn': pl.Utf8,
    'followupDate': pl.Utf8,
    'fsOverbookingYn': pl.Utf8,
    'functionType': pl.Utf8,
    'giid': pl.Utf8,
    'greekContractNr': pl.Utf8,
    'groupAccountID': pl.Float64,
    'guaranteecodeid': pl.Utf8,
    'guaranteedRate': pl.Utf8,
    'guaranteedYN': pl.Utf8,
    'hideacctinfoflag': pl.Utf8,
    'hlxCanxNoticeDays': pl.Float64,
    'hlxCommissionableYn': pl.Utf8,
    'hlxDdSecuredYn': pl.Utf8,
    'hlxDepositDays': pl.Float64,
    'hlxDiSecuredYn': pl.Utf8,
    'hlxHousinginfoSecuredYn': pl.Utf8,
    'hlxRateAllSecuredYn': pl.Utf8,
    'hlxRatesGnrSecuredYn': pl.Utf8,
    'hlxReturnEachDayYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'info': pl.Utf8,
    'informationBoard': pl.Utf8,
    'insertUser': pl.Int64,
    'inventoryControl': pl.Utf8,
    'inventoryCutOffDate': pl.Utf8,
    'inventoryCutOffDays': pl.Float64,
    'isacOpptyId': pl.Utf8,
    'items': pl.Utf8,
    'itemsForThisBlock': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepLeadControlYN': pl.Utf8,
    'laptopChange': pl.Float64,
    'leadOrigin': pl.Utf8,
    'leadSentYN': pl.Utf8,
    'leadSource': pl.Utf8,
    'leadType': pl.Utf8,
    'leadchangeBypropertyYn': pl.Utf8,
    'leaderrorflag': pl.Utf8,
    'leadisnewflag': pl.Utf8,
    'leadoriginid': pl.Utf8,
    'leadreceivedflag': pl.Utf8,
    'leadsend': pl.Utf8,
    'leadsend2': pl.Utf8,
    'leadsend3': pl.Utf8,
    'leadserverpendingflag': pl.Utf8,
    'leadsourceid': pl.Utf8,
    'leadstatus': pl.Utf8,
    'linkDate': pl.Utf8,
    'locationID': pl.Utf8,
    'lostTo': pl.Utf8,
    'mainmarket': pl.Utf8,
    'mainmarketid': pl.Utf8,
    'manuallyCutoffYN': pl.Utf8,
    'marEventType': pl.Utf8,
    'marHouseProtectYn': pl.Utf8,
    'marRollEndDateYn': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketid': pl.Utf8,
    'masterBlockID': pl.Float64,
    'masterBlockProperty': pl.Utf8,
    'masterNameId': pl.Float64,
    'meetingBudget': pl.Float64,
    'meetingRevenue': pl.Float64,
    'offsetType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'origAllotmentHeaderId': pl.Float64,
    'originCode': pl.Utf8,
    'originCodeDescription': pl.Utf8,
    'originalBeginDateHolidex': pl.Utf8,
    'originalEndDate': pl.Utf8,
    'originalRateCode': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'originalratecodeid': pl.Utf8,
    'ormsBlockClass': pl.Utf8,
    'ormsFinalBlock': pl.Utf8,
    'ormsForecastReviewReason': pl.Utf8,
    'ormsTransientBlock': pl.Utf8,
    'otherRevenue': pl.Float64,
    'owner': pl.Float64,
    'ownerResort': pl.Utf8,
    'owneremployeeid': pl.Float64,
    'ownerlocationd': pl.Utf8,
    'parentallotmentid': pl.Float64,
    'payment': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'personsPerRoom': pl.Float64,
    'porterageIncluded': pl.Utf8,
    'porteragePrice': pl.Float64,
    'potAverageRoomRate': pl.Float64,
    'potFbRevenue1': pl.Float64,
    'potOtherRevenue1': pl.Float64,
    'potRoomNights': pl.Float64,
    'potRoomRevenue1': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRate': pl.Utf8,
    'profileId': pl.Float64,
    'program': pl.Utf8,
    'property': pl.Utf8,
    'proposalCombineEventsYn': pl.Utf8,
    'proposalDecisionSelection': pl.Utf8,
    'proposalFollowupSelection': pl.Utf8,
    'proposalInclAltNamesYn': pl.Utf8,
    'proposalOwnerSelection': pl.Utf8,
    'proposalSentDate': pl.Utf8,
    'proposalShowEventpriceYn': pl.Utf8,
    'proposalShowPmsRoomTypeYn': pl.Utf8,
    'proposalShowSpacenameYn': pl.Utf8,
    'proposalSpaceMeasurement': pl.Utf8,
    'proposalViewToken': pl.Utf8,
    'publishRatesYn': pl.Utf8,
    'rankingCode': pl.Utf8,
    'rankingCodeDescription': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateOverride': pl.Utf8,
    'rateOverrideReason': pl.Utf8,
    'rateProtect': pl.Utf8,
    'rateTier': pl.Float64,
    'ratecodeid': pl.Utf8,
    'readyForDistribution': pl.Utf8,
    'regeneratedLeadYn': pl.Utf8,
    'repBookingmethodOrderby': pl.Float64,
    'repBsOrderBy': pl.Float64,
    'repCatOrderBy': pl.Float64,
    'replDate': pl.Utf8,
    'replVia': pl.Utf8,
    'replstatus': pl.Utf8,
    'replyBy': pl.Float64,
    'representative': pl.Utf8,
    'reservationMethod': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'reserveInventoryYN': pl.Utf8,
    'resortBooked': pl.Utf8,
    'resourceDiscountPercent': pl.Float64,
    'respTime': pl.Float64,
    'respTimeCode': pl.Utf8,
    'returnToInventory': pl.Utf8,
    'rivMarketSegment': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCommission1': pl.Float64,
    'roomCommission2': pl.Float64,
    'roomNightsSold': pl.Float64,
    'roomOwnerCode': pl.Utf8,
    'roomOwnerFullName': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTransactionCode': pl.Utf8,
    'roomStatus': pl.Utf8,
    'roomingListDue': pl.Utf8,
    'roomingListRules': pl.Utf8,
    'roomsCancellationDate': pl.Utf8,
    'roomsCancellationReason': pl.Utf8,
    'roomsCancellationReasonDescription': pl.Utf8,
    'roomsCurrency': pl.Utf8,
    'roomsDecisionDate': pl.Utf8,
    'roomsExchangeRate': pl.Float64,
    'roomsOwner': pl.Float64,
    'roomsOwnerResort': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'roomsQuoteCurrency': pl.Utf8,
    'roomsowneremployeeid': pl.Float64,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'scQuoteId': pl.Utf8,
    'sellThruYn': pl.Utf8,
    'sendToCentralYn': pl.Utf8,
    'senddate': pl.Utf8,
    'sentBy': pl.Float64,
    'sentDate': pl.Utf8,
    'sentVia': pl.Utf8,
    'serviceCharge': pl.Float64,
    'serviceFee': pl.Float64,
    'serviceFeeYn': pl.Utf8,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'showRateAmountYN': pl.Utf8,
    'snapshotSetup': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceContactAll': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceid': pl.Float64,
    'sourceprofprofileid': pl.Float64,
    'startDate': pl.Utf8,
    'startingStatus': pl.Utf8,
    'status': pl.Utf8,
    'statusColor': pl.Utf8,
    'statusType': pl.Utf8,
    'subAllocationYN': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'suppressRate': pl.Utf8,
    'syncContractYn': pl.Utf8,
    'synchronize': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'taxType': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tbdRates': pl.Utf8,
    'tdlReason': pl.Utf8,
    'tentativeLevel': pl.Float64,
    'tlpResponseid': pl.Utf8,
    'tlpUrl': pl.Utf8,
    'tourCode': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceDescription': pl.Utf8,
    'trackChangesYN': pl.Utf8,
    'travelAgentAll': pl.Utf8,
    'travelAgentRecordLocator': pl.Utf8,
    'turndownreasonid': pl.Float64,
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
    'ualias': pl.Utf8,
    'udescription': pl.Utf8,
    'updateDateExternal': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'webBookable': pl.Utf8,
    'webOverbookYN': pl.Utf8,
    'xudescription': pl.Utf8,
}
```
```python
travel_agent_details_schema = {
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'allOwnerCodes': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'centralDefaultKeyword': pl.Utf8,
    'centralIATANumberType': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'combinedName': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'competition': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'displayName': pl.Utf8,
    'email': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iATANumberType': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'industryCode': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'languageDescription': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailListYN': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'markets': pl.Utf8,
    'middle': pl.Utf8,
    'name': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'phoneNumber': pl.Utf8,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'privateYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileID': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repAccountType': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repInactiveReasonCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionDescription': pl.Utf8,
    'repMarketsDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repPriority': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateCode': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTerritory': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitle': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'subscribedProperties': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'totalArrivals': pl.Float64,
    'totalArrivalsLastyear': pl.Float64,
    'totalCancelledReservations': pl.Float64,
    'totalCancelledResvLastYear': pl.Float64,
    'totalCancelledRooms': pl.Float64,
    'totalCancelledRoomsLastyear': pl.Float64,
    'totalDayUseReservations': pl.Float64,
    'totalDayUseResvLastYear': pl.Float64,
    'totalDayUseRooms': pl.Float64,
    'totalDayUseRoomsLastyear': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueLastYear': pl.Float64,
    'totalNoShowReservations': pl.Float64,
    'totalNoShowRooms': pl.Float64,
    'totalNonRevenue': pl.Float64,
    'totalNonRevenueLastyear': pl.Float64,
    'totalNumberShowResvLastYear': pl.Float64,
    'totalNumberShowRoomsLastyear': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueLastyear': pl.Float64,
    'totalReservationNights': pl.Float64,
    'totalResvNightsLastYear': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueLastyear': pl.Float64,
    'totalRoomNightsLastyear': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueLastyear': pl.Float64,
    'totalStays': pl.Float64,
    'totalStaysLastyear': pl.Float64,
    'traceCode': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
allotment_statistics_details_schema = {
    'actionId': pl.Float64,
    'actualAverageRoomRate': pl.Float64,
    'actualFBRevenue': pl.Float64,
    'actualOtherRevenue': pl.Float64,
    'actualRoomNightsSold': pl.Float64,
    'actualRoomRevenue': pl.Float64,
    'addInfo': pl.Utf8,
    'agentContactNameId': pl.Float64,
    'agentNameId': pl.Float64,
    'agentprofileid': pl.Float64,
    'allAliases': pl.Utf8,
    'allBlockOwners': pl.Utf8,
    'allCateringOwners': pl.Utf8,
    'allCompanyContacts': pl.Utf8,
    'allRateCodes': pl.Utf8,
    'allRoomOwners': pl.Utf8,
    'allRoomPools': pl.Utf8,
    'allRoomTypes': pl.Utf8,
    'allSourceContacts': pl.Utf8,
    'allTravelAgentContacts': pl.Utf8,
    'allowPickup': pl.Utf8,
    'alternateBlockName': pl.Utf8,
    'alternateDates': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'attachmentURL': pl.Utf8,
    'attendeesGuaranteed': pl.Float64,
    'autoLoadForecastYn': pl.Utf8,
    'averageRate': pl.Float64,
    'bEOLastPrint': pl.Utf8,
    'beginDateOriginal': pl.Utf8,
    'blockAlias': pl.Utf8,
    'blockDateActual': pl.Utf8,
    'blockDateDefinite': pl.Utf8,
    'blockDateProspect': pl.Utf8,
    'blockDateTentative': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockOwnerFullName': pl.Utf8,
    'blockPackage': pl.Utf8,
    'blockPackageDescription': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockStatusDescription': pl.Utf8,
    'blockTypeCode': pl.Utf8,
    'blockTypeCodeDescription': pl.Utf8,
    'blockpackageid': pl.Utf8,
    'bookingId': pl.Utf8,
    'bookingMethodOrderBy': pl.Float64,
    'bookingStatusOrder': pl.Float64,
    'bookingType': pl.Utf8,
    'bookingTypeDescription': pl.Utf8,
    'bookingmethodInactiveDate': pl.Utf8,
    'bookingsourceid': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'bookingtypeid': pl.Utf8,
    'breakfastDescription': pl.Utf8,
    'breakfastInclPrice': pl.Float64,
    'breakfastInclYn': pl.Utf8,
    'breakfastIncluded': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'bwiLeadId': pl.Utf8,
    'bwiUrl': pl.Utf8,
    'cBreakfastInclPrice': pl.Float64,
    'cBreakfastPrice': pl.Float64,
    'cCompRoomValue': pl.Float64,
    'cDoubleRoomSupplementPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFBCommission1': pl.Float64,
    'cFBCommission2': pl.Float64,
    'cPorteragePrice': pl.Float64,
    'cRoomCommission1': pl.Float64,
    'cRoomCommission2': pl.Float64,
    'cServiceCharge': pl.Float64,
    'cServiceFee': pl.Float64,
    'cRSGtdYn': pl.Utf8,
    'cancelRule': pl.Utf8,
    'canceldestinationid': pl.Utf8,
    'cancellationDestination': pl.Utf8,
    'cancellationDestinationDescription': pl.Utf8,
    'cancellationNumber': pl.Float64,
    'cancellationPenaltyAmount': pl.Float64,
    'cancellationreasonid': pl.Utf8,
    'catCutoff': pl.Utf8,
    'catDateProspect': pl.Utf8,
    'catOwner': pl.Float64,
    'catOwnerProperty': pl.Utf8,
    'catReturnToInventory': pl.Utf8,
    'catStartingStatus': pl.Utf8,
    'catcurrencyid': pl.Utf8,
    'cateringCancellationDate': pl.Utf8,
    'cateringCancellationDescription': pl.Utf8,
    'cateringCancellationNumber': pl.Float64,
    'cateringCancellationReason': pl.Utf8,
    'cateringCurrency': pl.Utf8,
    'cateringDateActual': pl.Utf8,
    'cateringDecisionDate': pl.Utf8,
    'cateringDeductInventory': pl.Utf8,
    'cateringExchangeRate': pl.Float64,
    'cateringFollowupDate': pl.Utf8,
    'cateringOnlyYN': pl.Utf8,
    'cateringOrderBy': pl.Float64,
    'cateringOwnerCode': pl.Utf8,
    'cateringOwnerFullName': pl.Utf8,
    'cateringPkgsYn': pl.Utf8,
    'cateringQuoteCurrency': pl.Utf8,
    'cateringStatus': pl.Utf8,
    'cateringStatusColor': pl.Utf8,
    'cateringStatusDescription': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringcancelreasonid': pl.Float64,
    'cateringcurrencyid': pl.Utf8,
    'cateringowneremployeeid': pl.Float64,
    'cateringquotecurrencyid': pl.Utf8,
    'cateringstatusid': pl.Utf8,
    'cenralFBRevenue': pl.Float64,
    'centralActualAverageRoomRate': pl.Float64,
    'centralActualFBRevenue': pl.Float64,
    'centralActualOtherRevenue': pl.Float64,
    'centralActualRoomRevenue': pl.Float64,
    'centralAverageRoomRate': pl.Float64,
    'centralBlockPackage': pl.Utf8,
    'centralBlockPackageDescription': pl.Utf8,
    'centralBlockStatus': pl.Utf8,
    'centralBlockStatusDescription': pl.Utf8,
    'centralBlockTypeCode': pl.Utf8,
    'centralBlockTypeCodeDescription': pl.Utf8,
    'centralBookingType': pl.Utf8,
    'centralBookingTypeDescription': pl.Utf8,
    'centralCancellationDestination': pl.Utf8,
    'centralCancellationDestinationDescription': pl.Utf8,
    'centralCancellationPenaltyAmount': pl.Float64,
    'centralCateringStatus': pl.Utf8,
    'centralCateringStatusDescription': pl.Utf8,
    'centralConversionCode': pl.Utf8,
    'centralCoversionCodeDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMeetingBudget': pl.Float64,
    'centralMeetingRevenue': pl.Float64,
    'centralOriginCode': pl.Utf8,
    'centralOriginCodeDescription': pl.Utf8,
    'centralOtherRevenue': pl.Float64,
    'centralOwner': pl.Utf8,
    'centralPayment': pl.Utf8,
    'centralPaymentDescription': pl.Utf8,
    'centralRankingCode': pl.Utf8,
    'centralRankingCodeDescription': pl.Utf8,
    'centralReservationMethodCode': pl.Utf8,
    'centralReservationMethodDescription': pl.Utf8,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceCodeDescription': pl.Utf8,
    'centralTaxAmount': pl.Float64,
    'channelid': pl.Utf8,
    'code': pl.Utf8,
    'comAddress': pl.Utf8,
    'comAddress2': pl.Utf8,
    'comAddress3': pl.Utf8,
    'comMethod': pl.Utf8,
    'comMethod2': pl.Utf8,
    'comMethod3': pl.Utf8,
    'commissionAmount': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'compPerStayYn': pl.Utf8,
    'compRoomValue': pl.Float64,
    'compRooms': pl.Float64,
    'compRoomsFixedYn': pl.Utf8,
    'companyAll': pl.Utf8,
    'companyNameId': pl.Float64,
    'companyprofileid': pl.Float64,
    'competition': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactprofileid': pl.Float64,
    'contractNumber': pl.Utf8,
    'controlBlockLocally': pl.Utf8,
    'conversionCode': pl.Utf8,
    'coversionCodeDescription': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdAsOpportunityYN': pl.Utf8,
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'dateAcl': pl.Utf8,
    'dateCfl': pl.Utf8,
    'dateDefinite': pl.Utf8,
    'dateLsl': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'datePel': pl.Utf8,
    'dateTdl': pl.Utf8,
    'dateTentative': pl.Utf8,
    'dblRoomSupplementPrice': pl.Float64,
    'deductInventory': pl.Utf8,
    'defaultPmReservationNameId': pl.Float64,
    'deletedflag': pl.Utf8,
    'departureTime': pl.Utf8,
    'description': pl.Utf8,
    'distributed': pl.Utf8,
    'distributedDate': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doubleRoomSupplementYN': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'dueDateOrd': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateOriginal': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'eventAttendees': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exclusionMessage': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalRfpId': pl.Utf8,
    'externalRfpSystem': pl.Utf8,
    'externallyLocked': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fbAgendaCurrency': pl.Utf8,
    'fbCommission1': pl.Float64,
    'fbCommission2': pl.Float64,
    'fitContractMode': pl.Utf8,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'fitdiscounttype': pl.Utf8,
    'flatRateYn': pl.Utf8,
    'followupDate': pl.Utf8,
    'fsOverbookingYn': pl.Utf8,
    'functionType': pl.Utf8,
    'giid': pl.Utf8,
    'greekContractNr': pl.Utf8,
    'groupAccountID': pl.Float64,
    'guaranteecodeid': pl.Utf8,
    'guaranteedRate': pl.Utf8,
    'guaranteedYN': pl.Utf8,
    'hideacctinfoflag': pl.Utf8,
    'hlxCanxNoticeDays': pl.Float64,
    'hlxCommissionableYn': pl.Utf8,
    'hlxDdSecuredYn': pl.Utf8,
    'hlxDepositDays': pl.Float64,
    'hlxDiSecuredYn': pl.Utf8,
    'hlxHousinginfoSecuredYn': pl.Utf8,
    'hlxRateAllSecuredYn': pl.Utf8,
    'hlxRatesGnrSecuredYn': pl.Utf8,
    'hlxReturnEachDayYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'info': pl.Utf8,
    'informationBoard': pl.Utf8,
    'insertUser': pl.Int64,
    'inventoryControl': pl.Utf8,
    'inventoryCutOffDate': pl.Utf8,
    'inventoryCutOffDays': pl.Float64,
    'isacOpptyId': pl.Utf8,
    'items': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepLeadControlYN': pl.Utf8,
    'laptopChange': pl.Float64,
    'leadOrigin': pl.Utf8,
    'leadSentYN': pl.Utf8,
    'leadSource': pl.Utf8,
    'leadType': pl.Utf8,
    'leadchangeBypropertyYn': pl.Utf8,
    'leaderrorflag': pl.Utf8,
    'leadisnewflag': pl.Utf8,
    'leadoriginid': pl.Utf8,
    'leadreceivedflag': pl.Utf8,
    'leadsend': pl.Utf8,
    'leadsend2': pl.Utf8,
    'leadsend3': pl.Utf8,
    'leadserverpendingflag': pl.Utf8,
    'leadsourceid': pl.Utf8,
    'leadstatus': pl.Utf8,
    'linkDate': pl.Utf8,
    'locationID': pl.Utf8,
    'lostTo': pl.Utf8,
    'mainmarket': pl.Utf8,
    'mainmarketid': pl.Utf8,
    'manuallyCutoffYN': pl.Utf8,
    'marEventType': pl.Utf8,
    'marHouseProtectYn': pl.Utf8,
    'marRollEndDateYn': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketid': pl.Utf8,
    'masterBlockID': pl.Float64,
    'masterBlockProperty': pl.Utf8,
    'masterNameId': pl.Float64,
    'meetingBudget': pl.Float64,
    'meetingRevenue': pl.Float64,
    'offsetType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originCodeDescription': pl.Utf8,
    'originalBeginDateHolidex': pl.Utf8,
    'originalEndDate': pl.Utf8,
    'originalRateCode': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'originalratecodeid': pl.Utf8,
    'ormsBlockClass': pl.Utf8,
    'ormsFinalBlock': pl.Utf8,
    'ormsForecastReviewReason': pl.Utf8,
    'ormsTransientBlock': pl.Utf8,
    'otherRevenue': pl.Float64,
    'owner': pl.Float64,
    'ownerResort': pl.Utf8,
    'owneremployeeid': pl.Float64,
    'ownerlocationd': pl.Utf8,
    'payment': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'personsPerRoom': pl.Float64,
    'porterageIncluded': pl.Utf8,
    'porteragePrice': pl.Float64,
    'potAverageRoomRate': pl.Float64,
    'potFbRevenue1': pl.Float64,
    'potOtherRevenue1': pl.Float64,
    'potRoomNights': pl.Float64,
    'potRoomRevenue1': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRate': pl.Utf8,
    'profileId': pl.Float64,
    'program': pl.Utf8,
    'property': pl.Utf8,
    'proposalCombineEventsYn': pl.Utf8,
    'proposalDecisionSelection': pl.Utf8,
    'proposalFollowupSelection': pl.Utf8,
    'proposalInclAltNamesYn': pl.Utf8,
    'proposalOwnerSelection': pl.Utf8,
    'proposalSentDate': pl.Utf8,
    'proposalShowEventpriceYn': pl.Utf8,
    'proposalShowPmsRoomTypeYn': pl.Utf8,
    'proposalShowSpacenameYn': pl.Utf8,
    'proposalSpaceMeasurement': pl.Utf8,
    'proposalViewToken': pl.Utf8,
    'publishRatesYn': pl.Utf8,
    'rankingCode': pl.Utf8,
    'rankingCodeDescription': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateOverride': pl.Utf8,
    'rateOverrideReason': pl.Utf8,
    'rateProtect': pl.Utf8,
    'rateTier': pl.Float64,
    'ratecodeid': pl.Utf8,
    'readyForDistribution': pl.Utf8,
    'regeneratedLeadYn': pl.Utf8,
    'repBookingmethodOrderby': pl.Float64,
    'repBsOrderBy': pl.Float64,
    'repCatOrderBy': pl.Float64,
    'replDate': pl.Utf8,
    'replVia': pl.Utf8,
    'replstatus': pl.Utf8,
    'replyBy': pl.Float64,
    'representative': pl.Utf8,
    'reservationMethod': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'reserveInventoryYN': pl.Utf8,
    'resortBooked': pl.Utf8,
    'resourceDiscountPercent': pl.Float64,
    'respTime': pl.Float64,
    'respTimeCode': pl.Utf8,
    'returnToInventory': pl.Utf8,
    'rivMarketSegment': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCommission1': pl.Float64,
    'roomCommission2': pl.Float64,
    'roomNightsSold': pl.Float64,
    'roomOwnerCode': pl.Utf8,
    'roomOwnerFullName': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTransactionCode': pl.Utf8,
    'roomStatus': pl.Utf8,
    'roomingListDue': pl.Utf8,
    'roomingListRules': pl.Utf8,
    'roomsCancellationDate': pl.Utf8,
    'roomsCancellationReason': pl.Utf8,
    'roomsCancellationReasonDescription': pl.Utf8,
    'roomsCurrency': pl.Utf8,
    'roomsDecisionDate': pl.Utf8,
    'roomsExchangeRate': pl.Float64,
    'roomsOwner': pl.Float64,
    'roomsOwnerResort': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'roomsQuoteCurrency': pl.Utf8,
    'roomsowneremployeeid': pl.Float64,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'scQuoteId': pl.Utf8,
    'sellThruYn': pl.Utf8,
    'sendToCentralYn': pl.Utf8,
    'senddate': pl.Utf8,
    'sentBy': pl.Float64,
    'sentDate': pl.Utf8,
    'sentVia': pl.Utf8,
    'serviceCharge': pl.Float64,
    'serviceFee': pl.Float64,
    'serviceFeeYn': pl.Utf8,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'showRateAmountYN': pl.Utf8,
    'snapshotSetup': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceContactAll': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceid': pl.Float64,
    'sourceprofprofileid': pl.Float64,
    'startDate': pl.Utf8,
    'startingStatus': pl.Utf8,
    'status': pl.Utf8,
    'statusColor': pl.Utf8,
    'statusType': pl.Utf8,
    'subAllocationYN': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'suppressRate': pl.Utf8,
    'syncContractYn': pl.Utf8,
    'synchronize': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'taxType': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tbdRates': pl.Utf8,
    'tdlReason': pl.Utf8,
    'tentativeLevel': pl.Float64,
    'tlpResponseid': pl.Utf8,
    'tlpUrl': pl.Utf8,
    'tourCode': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceDescription': pl.Utf8,
    'trackChangesYN': pl.Utf8,
    'travelAgentAll': pl.Utf8,
    'travelAgentRecordLocator': pl.Utf8,
    'turndownreasonid': pl.Float64,
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
    'ualias': pl.Utf8,
    'udescription': pl.Utf8,
    'updateDateExternal': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'webBookable': pl.Utf8,
    'webOverbookYN': pl.Utf8,
    'xudescription': pl.Utf8,
}
```
```python
contact_details_schema = {
    'aRCreditLimitYN': pl.Utf8,
    'aRNumber': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountType': pl.Utf8,
    'accountsource': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'addressType': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allProperties': pl.Utf8,
    'allSalesRepCodes': pl.Utf8,
    'alternateFirstName': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoPopRouting': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessSegmentDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cRSNameid': pl.Float64,
    'ccProfileYn': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralBusinessSegmentDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralInfluence': pl.Utf8,
    'centralInfluenceDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralNationality': pl.Utf8,
    'centralNationalityDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'centralTitle': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPCodeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCurrencyId': pl.Utf8,
    'commissionid': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competitionCode': pl.Utf8,
    'contactEmailPrimary': pl.Utf8,
    'contactPhonePrimary': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactYN': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryDesc': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'envelopeGreetingAlternate': pl.Utf8,
    'externalDisplayName': pl.Utf8,
    'externalFirstName': pl.Utf8,
    'externalId': pl.Utf8,
    'externalName': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'firstName': pl.Utf8,
    'firstNameIncognito': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataCompType': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idNumber': pl.Utf8,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'language': pl.Utf8,
    'languageDescription': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastGroup': pl.Utf8,
    'lastName': pl.Utf8,
    'lastNameAlternate': pl.Utf8,
    'lastNameIncognito': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastRoomResort': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailListYN': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'middleName': pl.Utf8,
    'name': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameWithTitle': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneYn': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'privateYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileArrCodes': pl.Utf8,
    'profileArrangementDesc': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountType': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIATACompType': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repPriority': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repStateCode': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'salesRep': pl.Utf8,
    'salesRepCode': pl.Utf8,
    'salutation': pl.Utf8,
    'salutationAlternate': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDescription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'stateDescription': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalArrivals': pl.Float64,
    'totalArrivalsLastyear': pl.Float64,
    'totalCancelledReservations': pl.Float64,
    'totalCancelledResvLastYear': pl.Float64,
    'totalCancelledRooms': pl.Float64,
    'totalCancelledRoomsLastyear': pl.Float64,
    'totalDayUseReservations': pl.Float64,
    'totalDayUseResvLastYear': pl.Float64,
    'totalDayUseRooms': pl.Float64,
    'totalDayUseRoomsLastyear': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueLastYear': pl.Float64,
    'totalNoShowReservations': pl.Float64,
    'totalNoShowRooms': pl.Float64,
    'totalNonRevenue': pl.Float64,
    'totalNonRevenueLastyear': pl.Float64,
    'totalNumberShowResvLastYear': pl.Float64,
    'totalNumberShowRoomsLastyear': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueLastyear': pl.Float64,
    'totalReservationNights': pl.Float64,
    'totalResvNightsLastYear': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueLastyear': pl.Float64,
    'totalRoomNightsLastyear': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueLastyear': pl.Float64,
    'totalStays': pl.Float64,
    'totalStaysLastyear': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vIPCode': pl.Utf8,
    'vIPCodeDescription': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xmiddleName': pl.Utf8,
    'zipCode': pl.Utf8,
}
```