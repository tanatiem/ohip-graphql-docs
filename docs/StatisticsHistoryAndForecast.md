# StatisticsHistoryAndForecast
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `statisticsHistoryAndForecast`
> Detailed information on past and future reservations including occupancy and revenue figures with all profile data broken down by Market Rate code Room type and Periods of time.
  
**Return:** [`[StatisticsHistoryAndForecastType]`](#statisticshistoryandforecasttype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsHistoryAndForecastQueryArgumentsType!`](#statisticshistoryandforecastqueryargumentstype) |  |

## Object Types

### StatisticsHistoryAndForecastType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | historyForecastDetails | [`StatisticsHistoryAndForecastHistoryForecastDetailsType`](#statisticshistoryandforecasthistoryforecastdetailstype) | History Forecast Details |
| 2 | fiscalCalendarDetails | [`StatisticsHistoryAndForecastFiscalCalendarDetailsType`](#statisticshistoryandforecastfiscalcalendardetailstype) | Fiscal Calendar |
| 3 | gregerianCalendarDetails | [`StatisticsHistoryAndForecastGregerianCalendarDetailsType`](#statisticshistoryandforecastgregeriancalendardetailstype) | Gregerian Calendar |
| 4 | reservationProfileAccountsSourceDetails | [`StatisticsHistoryAndForecastReservationProfileAccountsSourceDetailsType`](#statisticshistoryandforecastreservationprofileaccountssourcedetailstype) | Reservation Profile Accounts Source Details |
| 5 | marketDetails | [`StatisticsHistoryAndForecastMarketDetailsType`](#statisticshistoryandforecastmarketdetailstype) | Market Details |
| 6 | propertyPropertyDetails | [`StatisticsHistoryAndForecastPropertyPropertyDetailsType`](#statisticshistoryandforecastpropertypropertydetailstype) | Resort Details |
| 7 | profileAccountsTravelAgentDetails | [`StatisticsHistoryAndForecastProfileAccountsTravelAgentDetailsType`](#statisticshistoryandforecastprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| 8 | reservationProfileAccountsCompanyDetails | [`StatisticsHistoryAndForecastReservationProfileAccountsCompanyDetailsType`](#statisticshistoryandforecastreservationprofileaccountscompanydetailstype) | Reservation Profile Accounts Company Details |
| 9 | statisticsHistoryAndForecastRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastHistoryForecastDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | agentId | `Float` | Agent ID |
| 3 | arrivalPersons | `Float` | Arrival Persons |
| 4 | arrivalRooms | `Float` | Arrival Rooms |
| 5 | averageRate | `Float` | Average Rate |
| 6 | blockStatus | `String` | Block Status |
| 7 | bookingStatus | `String` | Booking Status |
| 8 | bookingStatusDescription | `String` | Booking Status Description |
| 9 | businessDate | `Date` | Filter Date |
| 10 | cAverageRate | `Float` | Central Average Rate |
| 11 | cExtraRevenue | `Float` | Central Extra Revenue |
| 12 | cGrossRateAmount | `Float` | Central Gross Rate Amount |
| 13 | cNetRoomRevenueAmount | `Float` | Central Net Room Revenue Amount |
| 14 | cancelledRooms | `Float` | Cancelled Rooms |
| 15 | cashRoomNights | `Float` | Cash Room Nights |
| 16 | centralBookingStatus | `String` | Central Booking Status |
| 17 | centralBookingStatusDescription | `String` | Central Booking Status Description |
| 18 | centralDayUseExtraRevenue | `Float` | Central Day Use Extra Revenue |
| 19 | centralDayUseGrossRate | `Float` | Central Day Use Gross Rate |
| 20 | centralFoodRevenue | `Float` | Central Food Revenue |
| 21 | centralGrossRate | `Float` | Central Gross Rate |
| 22 | centralMarketCode | `String` | Central Market Code |
| 23 | centralMarketDescription | `String` | Central Market Description |
| 24 | centralMarketDisplaySequence | `Float` | Central Market Display Sequence |
| 25 | centralMarketGroupCode | `String` | Central Market Group Code |
| 26 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 27 | centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| 28 | centralOriginCode | `String` | Central Origin Code |
| 29 | centralOriginDescription | `String` | Central Origin Description |
| 30 | centralOriginDisplaySequence | `Float` | Central Origin Display Sequence |
| 31 | centralOtherRevenue | `Float` | Central Other Revenue |
| 32 | centralRateCategory | `String` | Central Rate Category |
| 33 | centralRoomClass | `String` | Central Room Class |
| 34 | centralRoomClassDescription | `String` | Central Room Class Description |
| 35 | centralRoomRevenue | `Float` | Central Room Revenue |
| 36 | centralRoomType | `String` | Central Room Type |
| 37 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 38 | centralSourceCode | `String` | Central Source Code |
| 39 | centralSourceDescription | `String` | Central Source Description |
| 40 | centralSourceDisplaySequence | `Float` | Central Source Display Sequence |
| 41 | centralSourceGroupCode | `String` | Central Source Group Code |
| 42 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 43 | centralSourceGroupDisplaySequence | `Float` | Central Source Group Display Sequence |
| 44 | centralTotalRevenue | `Float` | Central Total Revenue |
| 45 | children | `Float` | Children |
| 46 | complimentaryRoomNights | `Float` | Complimentary Room Nights |
| 47 | country | `String` | Country |
| 48 | countryCode | `String` | Country Code |
| 49 | cribs | `Float` | Cribs |
| 50 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 51 | dayUseExtraRevenue | `Float` | Day Use Extra Revenue |
| 52 | dayUseGrossRate | `Float` | Day Use Gross Rate |
| 53 | dayUseNetRoomRevenue | `Float` | Day Use Net Room Revenue |
| 54 | dayUsePersons | `Float` | Day Use Persons |
| 55 | dayUseRooms | `Float` | Day Use Rooms |
| 56 | dayUseYn | `String` | Day Use Y/N |
| 57 | deductGroupRooms | `Float` | Deduct Group Rooms |
| 58 | deductIndividualRooms | `Float` | Deduct Individual Rooms |
| 59 | departurePersons | `Float` | Departure Persons |
| 60 | departureRooms | `Float` | Departure Rooms |
| 61 | eventType | `String` | Event Type |
| 62 | extraBeds | `Float` | Extra Beds |
| 63 | extraRevenue | `Float` | Extra Revenue |
| 64 | foodRevenue | `Float` | Food Revenue |
| 65 | grossRate | `Float` | Gross Rate |
| 66 | grossRateAmount | `Float` | Gross Rate Amount |
| 67 | historyForecast | `String` | History Forecast |
| 68 | houseUse | `Float` | House Use |
| 69 | locationID | `String` | Internal ID to uniquely identify the Property |
| 70 | marketCode | `String` | Market Code |
| 71 | marketDescription | `String` | Market Description |
| 72 | marketDisplaySequence | `Float` | Market Display Sequence |
| 73 | marketGroupCode | `String` | Market group attached to the market code |
| 74 | marketGroupDescription | `String` | Market Group Description |
| 75 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 76 | netRoomRevenue | `Float` | Net Room Revenue |
| 77 | netRoomRevenueAmount | `Float` | Net Room Revenue Amount |
| 78 | noShowRooms | `Float` | No-Show Rooms |
| 79 | nonDeductGroupRooms | `Float` | Non-Deduct Group Rooms |
| 80 | nonDeductIndividualRooms | `Float` | Non-Deduct Individual Rooms |
| 81 | numberRooms | `Float` | Number Rooms |
| 82 | numberOfGuests | `Float` | Number of Guests |
| 83 | numberOfRooms | `Float` | Number of Rooms |
| 84 | occupancyPerc | `Float` | Occupancy Perc |
| 85 | oooCount | `Float` | Ooo Count |
| 86 | oooRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 87 | oooRoomsType | `Float` | Ooo Rooms Type |
| 88 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 89 | originCode | `String` | Origin Code |
| 90 | originDescription | `String` | Origin Description |
| 91 | originDisplaySequence | `Float` | Origin Display Sequence |
| 92 | otherRevenue | `Float` | Other Revenue |
| 93 | parentCompanyId | `Float` | Parent Company ID |
| 94 | pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| 95 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 96 | property | `String` | Code to uniquely identify the Property |
| 97 | pseudoRoomYN | `String` | Pseudo Room YN |
| 98 | rateCategory | `String` | Rate Category |
| 99 | rateCode | `String` | Rate Code |
| 100 | regionCode | `String` | Region Code |
| 101 | regionDescription | `String` | Region Description |
| 102 | remainingBlockRooms | `Float` | Remaining Block Rooms |
| 103 | reservationInventoryType | `String` | Reservation Inventory Type |
| 104 | reservationType | `String` | Reservation Type |
| 105 | resortNumberRooms | `Float` | Property Number Rooms |
| 106 | resortPhyNumRooms | `Float` | Property Phy Num Rooms |
| 107 | resortPhysicalNumberRooms | `Float` | Property Physical Number Rooms |
| 108 | resortPhysicalNumberRoomsCount | `Float` | Property Physical Number Rooms Count |
| 109 | roomCatPhyNumRooms | `Float` | Room Catering Phy Num Rooms |
| 110 | roomCatPhysicalNumberRooms | `Float` | Room Catering Physical Number Rooms |
| 111 | roomCatPhysicalNumberRoomsCount | `Float` | Room Catering Physical Number Rooms Count |
| 112 | roomCategory | `String` | Room Category |
| 113 | roomClass | `String` | Room Class |
| 114 | roomClassDescription | `String` | Room Class Description |
| 115 | roomNights | `Float` | Room Nights |
| 116 | roomRevenue | `Float` | Room Revenue |
| 117 | roomType | `String` | Room Type |
| 118 | roomTypeDescription | `String` | Room Type Description |
| 119 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 120 | sourceCode | `String` | Source Code |
| 121 | sourceDescription | `String` | Source Description |
| 122 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 123 | sourceGroupCode | `String` | Source group of the source code |
| 124 | sourceGroupDescription | `String` | Source Group Description |
| 125 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 126 | sourceProfId | `Float` | Source Prof ID |
| 127 | totalCount | `Float` | Total Count |
| 128 | totalOccupancy | `Float` | Total Occupancy |
| 129 | totalPhyResortRooms | `Float` | Tot Phy Property Rooms |
| 130 | totalPhyResortRoomsCount | `Float` | Tot Phy Property Rooms Count |
| 131 | totalPhyRooms | `Float` | Total Phy Rooms |
| 132 | totalPhyRoomsCount | `Float` | Total Phy Rooms Count |
| 133 | totalRevenue | `Float` | Total Revenue |
| 134 | waitlistPersons | `Float` | Waitlist Persons |
| 135 | waitlistRooms | `Float` | Waitlist Rooms |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastFiscalCalendarDetailsType

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

### StatisticsHistoryAndForecastGregerianCalendarDetailsType

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

### StatisticsHistoryAndForecastReservationProfileAccountsSourceDetailsType

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

### StatisticsHistoryAndForecastMarketDetailsType

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

### StatisticsHistoryAndForecastPropertyPropertyDetailsType

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

### StatisticsHistoryAndForecastProfileAccountsTravelAgentDetailsType

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

### StatisticsHistoryAndForecastReservationProfileAccountsCompanyDetailsType

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

### StatisticsHistoryAndForecastQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| historyforecastDetailsBlockStatus | `StringInput` | Block Status |
| historyforecastDetailsBookingStatus | `StringInput` | Booking Status |
| historyforecastDetailsBookingStatusDescription | `StringInput` | Booking Status Description |
| historyforecastDetailsFilterDate | `DateInput!` | Filter Date<br>`@mandatoryInput` |
| historyforecastDetailsRepBookingStatus | `StringInput` | Central Booking Status |
| historyforecastDetailsRepBookingStatusDescription | `StringInput` | Central Booking Status Description |
| historyforecastDetailsRepMarketCode | `StringInput` | Central Market Code |
| historyforecastDetailsRepMarketCodeDescription | `StringInput` | Central Market Description |
| historyforecastDetailsRepParentMarketCode | `StringInput` | Central Market Group Code |
| historyforecastDetailsRepParentMarketCodeDesc | `StringInput` | Central Market Group Description |
| historyforecastDetailsRepChannel | `StringInput` | Central Origin Code |
| historyforecastDetailsRepChannelDescription | `StringInput` | Central Origin Description |
| historyforecastDetailsRepRateCategory | `StringInput` | Central Rate Category |
| historyforecastDetailsRepRoomClass | `StringInput` | Central Room Class |
| historyforecastDetailsRepRoomClassDescription | `StringInput` | Central Room Class Description |
| historyforecastDetailsRepRoomCategoryCode | `StringInput` | Central Room Type |
| historyforecastDetailsRepRoomCategoryDescription | `StringInput` | Central Room Type Description |
| historyforecastDetailsRepSourceCode | `StringInput` | Central Source Code |
| historyforecastDetailsRepSourceDescription | `StringInput` | Central Source Description |
| historyforecastDetailsRepParentSourceCode | `StringInput` | Central Source Group Code |
| historyforecastDetailsRepParentSourceCodeDesc | `StringInput` | Central Source Group Description |
| historyforecastDetailsCountryName | `StringInput` | Country |
| historyforecastDetailsCountry | `StringInput` | Country Code |
| historyforecastDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| historyforecastDetailsDayUseYn | `StringInput` | Day Use Y/N |
| historyforecastDetailsEventType | `StringInput` | Event Type |
| historyforecastDetailsHistoryForecast | `StringInput` | History Forecast |
| historyforecastDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| historyforecastDetailsMarketCode | `StringInput` | Market Code |
| historyforecastDetailsMarketCodeDeacription | `StringInput` | Market Description |
| historyforecastDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| historyforecastDetailsParentMarketCodeDesc | `StringInput` | Market Group Description |
| historyforecastDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| historyforecastDetailsChannel | `StringInput` | Origin Code |
| historyforecastDetailsChannelDescription | `StringInput` | Origin Description |
| historyforecastDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| historyforecastDetailsPsuedoRoomYn | `StringInput` | Pseudo Room YN |
| historyforecastDetailsRateCategory | `StringInput` | Rate Category |
| historyforecastDetailsRateCode | `StringInput` | Rate Code |
| historyforecastDetailsRegionCode | `StringInput` | Region Code |
| historyforecastDetailsRegionDescription | `StringInput` | Region Description |
| historyforecastDetailsResvInvType | `StringInput` | Reservation Inventory Type |
| historyforecastDetailsResvType | `StringInput` | Reservation Type |
| historyforecastDetailsRoomCategory | `StringInput` | Room Category |
| historyforecastDetailsRoomClass | `StringInput` | Room Class |
| historyforecastDetailsRoomClassDescription | `StringInput` | Room Class Description |
| historyforecastDetailsRoomCategoryCode | `StringInput` | Room Type |
| historyforecastDetailsRoomCategoryDescription | `StringInput` | Room Type Description |
| historyforecastDetailsSourceCode | `StringInput` | Source Code |
| historyforecastDetailsSourceDescription | `StringInput` | Source Description |
| historyforecastDetailsParentSourceCode | `StringInput` | Source group of the source code |
| historyforecastDetailsParentSourceCodeDesc | `StringInput` | Source Group Description |
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
| reservationprofileaccountssourceDetailsProfileId | `FloatInput` | Account ID |
| reservationprofileaccountssourceDetailsActiveYn | `StringInput` | Active Flag |
| reservationprofileaccountssourceDetailsChainCode | `StringInput` | Chain Code |
| reservationprofileaccountssourceDetailsCompany | `StringInput` | Company |
| reservationprofileaccountssourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationprofileaccountssourceDetailsHistoryYn | `StringInput` | History Y/N |
| reservationprofileaccountssourceDetailsNameCode | `StringInput` | IATA Number |
| reservationprofileaccountssourceDetailsInactiveDate | `DateInput` | Inactive Date |
| reservationprofileaccountssourceDetailsOrganizationId | `FloatInput` | Organization ID |
| reservationprofileaccountssourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationprofileaccountssourceDetailsLast | `StringInput` | Last |
| reservationprofileaccountssourceDetailsNameId | `FloatInput` | Name ID |
| reservationprofileaccountssourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationprofileaccountssourceDetailsProfileType | `StringInput` | Profile Type |
| reservationprofileaccountssourceDetailsNameType | `StringInput` | Profile Type Code |
| reservationprofileaccountssourceDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| reservationprofileaccountssourceDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| reservationprofileaccountssourceDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| reservationprofileaccountssourceDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| reservationprofileaccountssourceDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| reservationprofileaccountssourceDetailsUpdateDate | `DateTimeInput` | Update Date |
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
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
| reservationprofileaccountscompanyDetailsProfileId | `FloatInput` | Account ID |
| reservationprofileaccountscompanyDetailsActiveYn | `StringInput` | Active Flag |
| reservationprofileaccountscompanyDetailsChainCode | `StringInput` | Chain Code |
| reservationprofileaccountscompanyDetailsCompany | `StringInput` | Company |
| reservationprofileaccountscompanyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationprofileaccountscompanyDetailsHistoryYn | `StringInput` | History Y/N |
| reservationprofileaccountscompanyDetailsNameCode | `StringInput` | IATA Number |
| reservationprofileaccountscompanyDetailsInactiveDate | `DateInput` | Inactive Date |
| reservationprofileaccountscompanyDetailsOrganizationId | `FloatInput` | Organization ID |
| reservationprofileaccountscompanyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationprofileaccountscompanyDetailsLast | `StringInput` | Last |
| reservationprofileaccountscompanyDetailsNameId | `FloatInput` | Name ID |
| reservationprofileaccountscompanyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationprofileaccountscompanyDetailsProfileType | `StringInput` | Profile Type |
| reservationprofileaccountscompanyDetailsNameType | `StringInput` | Profile Type Code |
| reservationprofileaccountscompanyDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| reservationprofileaccountscompanyDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| reservationprofileaccountscompanyDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| reservationprofileaccountscompanyDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| reservationprofileaccountscompanyDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| reservationprofileaccountscompanyDetailsUpdateDate | `DateTimeInput` | Update Date |
#### Validation Rules

**`mandatoryInput`**
- historyforecastDetailsFilterDate
- historyforecastDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsHistoryAndForecast($input: StatisticsHistoryAndForecastQueryArgumentsType!) {
  statisticsHistoryAndForecast(input: $input) @stream {
    historyForecastDetails {
      adults
      agentId
      arrivalPersons
      arrivalRooms
      averageRate
      blockStatus
      bookingStatus
      bookingStatusDescription
      businessDate
      cAverageRate
      cExtraRevenue
      cGrossRateAmount
      cNetRoomRevenueAmount
      cancelledRooms
      cashRoomNights
      centralBookingStatus
      centralBookingStatusDescription
      centralDayUseExtraRevenue
      centralDayUseGrossRate
      centralFoodRevenue
      centralGrossRate
      centralMarketCode
      centralMarketDescription
      centralMarketDisplaySequence
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetRoomRevenue
      centralOriginCode
      centralOriginDescription
      centralOriginDisplaySequence
      centralOtherRevenue
      centralRateCategory
      centralRoomClass
      centralRoomClassDescription
      centralRoomRevenue
      centralRoomType
      centralRoomTypeDescription
      centralSourceCode
      centralSourceDescription
      centralSourceDisplaySequence
      centralSourceGroupCode
      centralSourceGroupDescription
      centralSourceGroupDisplaySequence
      centralTotalRevenue
      children
      complimentaryRoomNights
      country
      countryCode
      cribs
      dSI
      dayUseExtraRevenue
      dayUseGrossRate
      dayUseNetRoomRevenue
      dayUsePersons
      dayUseRooms
      dayUseYn
      deductGroupRooms
      deductIndividualRooms
      departurePersons
      departureRooms
      eventType
      extraBeds
      extraRevenue
      foodRevenue
      grossRate
      grossRateAmount
      historyForecast
      houseUse
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      multipleOccupancyRooms
      netRoomRevenue
      netRoomRevenueAmount
      noShowRooms
      nonDeductGroupRooms
      nonDeductIndividualRooms
      numberRooms
      numberOfGuests
      numberOfRooms
      occupancyPerc
      oooCount
      oooRooms
      oooRoomsType
      organizationID
      originCode
      originDescription
      originDisplaySequence
      otherRevenue
      parentCompanyId
      pickedUpBlockRooms
      primaryKeyID
      property
      pseudoRoomYN
      rateCategory
      rateCode
      regionCode
      regionDescription
      remainingBlockRooms
      reservationInventoryType
      reservationType
      resortNumberRooms
      resortPhyNumRooms
      resortPhysicalNumberRooms
      resortPhysicalNumberRoomsCount
      roomCatPhyNumRooms
      roomCatPhysicalNumberRooms
      roomCatPhysicalNumberRoomsCount
      roomCategory
      roomClass
      roomClassDescription
      roomNights
      roomRevenue
      roomType
      roomTypeDescription
      singleOccupancyRooms
      sourceCode
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceProfId
      totalCount
      totalOccupancy
      totalPhyResortRooms
      totalPhyResortRoomsCount
      totalPhyRooms
      totalPhyRoomsCount
      totalRevenue
      waitlistPersons
      waitlistRooms
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
    reservationProfileAccountsSourceDetails {
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
    reservationProfileAccountsCompanyDetails {
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
history_forecast_details_schema = {
    'adults': pl.Float64,
    'agentId': pl.Float64,
    'arrivalPersons': pl.Float64,
    'arrivalRooms': pl.Float64,
    'averageRate': pl.Float64,
    'blockStatus': pl.Utf8,
    'bookingStatus': pl.Utf8,
    'bookingStatusDescription': pl.Utf8,
    'businessDate': pl.Utf8,
    'cAverageRate': pl.Float64,
    'cExtraRevenue': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cNetRoomRevenueAmount': pl.Float64,
    'cancelledRooms': pl.Float64,
    'cashRoomNights': pl.Float64,
    'centralBookingStatus': pl.Utf8,
    'centralBookingStatusDescription': pl.Utf8,
    'centralDayUseExtraRevenue': pl.Float64,
    'centralDayUseGrossRate': pl.Float64,
    'centralFoodRevenue': pl.Float64,
    'centralGrossRate': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketDisplaySequence': pl.Float64,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetRoomRevenue': pl.Float64,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
    'centralOriginDisplaySequence': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRateCategory': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceDisplaySequence': pl.Float64,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'centralSourceGroupDisplaySequence': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'children': pl.Float64,
    'complimentaryRoomNights': pl.Float64,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'cribs': pl.Float64,
    'dSI': pl.Int64,
    'dayUseExtraRevenue': pl.Float64,
    'dayUseGrossRate': pl.Float64,
    'dayUseNetRoomRevenue': pl.Float64,
    'dayUsePersons': pl.Float64,
    'dayUseRooms': pl.Float64,
    'dayUseYn': pl.Utf8,
    'deductGroupRooms': pl.Float64,
    'deductIndividualRooms': pl.Float64,
    'departurePersons': pl.Float64,
    'departureRooms': pl.Float64,
    'eventType': pl.Utf8,
    'extraBeds': pl.Float64,
    'extraRevenue': pl.Float64,
    'foodRevenue': pl.Float64,
    'grossRate': pl.Float64,
    'grossRateAmount': pl.Float64,
    'historyForecast': pl.Utf8,
    'houseUse': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'multipleOccupancyRooms': pl.Float64,
    'netRoomRevenue': pl.Float64,
    'netRoomRevenueAmount': pl.Float64,
    'noShowRooms': pl.Float64,
    'nonDeductGroupRooms': pl.Float64,
    'nonDeductIndividualRooms': pl.Float64,
    'numberRooms': pl.Float64,
    'numberOfGuests': pl.Float64,
    'numberOfRooms': pl.Float64,
    'occupancyPerc': pl.Float64,
    'oooCount': pl.Float64,
    'oooRooms': pl.Float64,
    'oooRoomsType': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originDisplaySequence': pl.Float64,
    'otherRevenue': pl.Float64,
    'parentCompanyId': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCode': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionDescription': pl.Utf8,
    'remainingBlockRooms': pl.Float64,
    'reservationInventoryType': pl.Utf8,
    'reservationType': pl.Utf8,
    'resortNumberRooms': pl.Float64,
    'resortPhyNumRooms': pl.Float64,
    'resortPhysicalNumberRooms': pl.Float64,
    'resortPhysicalNumberRoomsCount': pl.Float64,
    'roomCatPhyNumRooms': pl.Float64,
    'roomCatPhysicalNumberRooms': pl.Float64,
    'roomCatPhysicalNumberRoomsCount': pl.Float64,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenue': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'singleOccupancyRooms': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceProfId': pl.Float64,
    'totalCount': pl.Float64,
    'totalOccupancy': pl.Float64,
    'totalPhyResortRooms': pl.Float64,
    'totalPhyResortRoomsCount': pl.Float64,
    'totalPhyRooms': pl.Float64,
    'totalPhyRoomsCount': pl.Float64,
    'totalRevenue': pl.Float64,
    'waitlistPersons': pl.Float64,
    'waitlistRooms': pl.Float64,
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
reservation_profile_accounts_source_details_schema = {
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
reservation_profile_accounts_company_details_schema = {
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