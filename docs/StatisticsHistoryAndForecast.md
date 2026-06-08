# StatisticsHistoryAndForecast
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| Field | Type | Description |
| --- | --- | --- |
| historyForecastDetails | [`StatisticsHistoryAndForecastHistoryForecastDetailsType`](#statisticshistoryandforecasthistoryforecastdetailstype) | History Forecast Details |
| fiscalCalendarDetails | [`StatisticsHistoryAndForecastFiscalCalendarDetailsType`](#statisticshistoryandforecastfiscalcalendardetailstype) | Fiscal Calendar |
| gregerianCalendarDetails | [`StatisticsHistoryAndForecastGregerianCalendarDetailsType`](#statisticshistoryandforecastgregeriancalendardetailstype) | Gregerian Calendar |
| reservationProfileAccountsSourceDetails | [`StatisticsHistoryAndForecastReservationProfileAccountsSourceDetailsType`](#statisticshistoryandforecastreservationprofileaccountssourcedetailstype) | Reservation Profile Accounts Source Details |
| marketDetails | [`StatisticsHistoryAndForecastMarketDetailsType`](#statisticshistoryandforecastmarketdetailstype) | Market Details |
| propertyPropertyDetails | [`StatisticsHistoryAndForecastPropertyPropertyDetailsType`](#statisticshistoryandforecastpropertypropertydetailstype) | Resort Details |
| profileAccountsTravelAgentDetails | [`StatisticsHistoryAndForecastProfileAccountsTravelAgentDetailsType`](#statisticshistoryandforecastprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| reservationProfileAccountsCompanyDetails | [`StatisticsHistoryAndForecastReservationProfileAccountsCompanyDetailsType`](#statisticshistoryandforecastreservationprofileaccountscompanydetailstype) | Reservation Profile Accounts Company Details |
| statisticsHistoryAndForecastRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastHistoryForecastDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adults | `Float` | Adults |
| agentId | `Float` | Agent ID |
| arrivalPersons | `Float` | Arrival Persons |
| arrivalRooms | `Float` | Arrival Rooms |
| averageRate | `Float` | Average Rate |
| blockStatus | `String` | Block Status |
| bookingStatus | `String` | Booking Status |
| bookingStatusDescription | `String` | Booking Status Description |
| businessDate | `Date` | Filter Date |
| cAverageRate | `Float` | Central Average Rate |
| cExtraRevenue | `Float` | Central Extra Revenue |
| cGrossRateAmount | `Float` | Central Gross Rate Amount |
| cNetRoomRevenueAmount | `Float` | Central Net Room Revenue Amount |
| cancelledRooms | `Float` | Cancelled Rooms |
| cashRoomNights | `Float` | Cash Room Nights |
| centralBookingStatus | `String` | Central Booking Status |
| centralBookingStatusDescription | `String` | Central Booking Status Description |
| centralDayUseExtraRevenue | `Float` | Central Day Use Extra Revenue |
| centralDayUseGrossRate | `Float` | Central Day Use Gross Rate |
| centralFoodRevenue | `Float` | Central Food Revenue |
| centralGrossRate | `Float` | Central Gross Rate |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketDisplaySequence | `Float` | Central Market Display Sequence |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
| centralOriginDisplaySequence | `Float` | Central Origin Display Sequence |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralRateCategory | `String` | Central Rate Category |
| centralRoomClass | `String` | Central Room Class |
| centralRoomClassDescription | `String` | Central Room Class Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceDisplaySequence | `Float` | Central Source Display Sequence |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| centralSourceGroupDisplaySequence | `Float` | Central Source Group Display Sequence |
| centralTotalRevenue | `Float` | Central Total Revenue |
| children | `Float` | Children |
| complimentaryRoomNights | `Float` | Complimentary Room Nights |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| cribs | `Float` | Cribs |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUseExtraRevenue | `Float` | Day Use Extra Revenue |
| dayUseGrossRate | `Float` | Day Use Gross Rate |
| dayUseNetRoomRevenue | `Float` | Day Use Net Room Revenue |
| dayUsePersons | `Float` | Day Use Persons |
| dayUseRooms | `Float` | Day Use Rooms |
| dayUseYn | `String` | Day Use Y/N |
| deductGroupRooms | `Float` | Deduct Group Rooms |
| deductIndividualRooms | `Float` | Deduct Individual Rooms |
| departurePersons | `Float` | Departure Persons |
| departureRooms | `Float` | Departure Rooms |
| eventType | `String` | Event Type |
| extraBeds | `Float` | Extra Beds |
| extraRevenue | `Float` | Extra Revenue |
| foodRevenue | `Float` | Food Revenue |
| grossRate | `Float` | Gross Rate |
| grossRateAmount | `Float` | Gross Rate Amount |
| historyForecast | `String` | History Forecast |
| houseUse | `Float` | House Use |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market group attached to the market code |
| marketGroupDescription | `String` | Market Group Description |
| multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| netRoomRevenue | `Float` | Net Room Revenue |
| netRoomRevenueAmount | `Float` | Net Room Revenue Amount |
| noShowRooms | `Float` | No-Show Rooms |
| nonDeductGroupRooms | `Float` | Non-Deduct Group Rooms |
| nonDeductIndividualRooms | `Float` | Non-Deduct Individual Rooms |
| numberRooms | `Float` | Number Rooms |
| numberOfGuests | `Float` | Number of Guests |
| numberOfRooms | `Float` | Number of Rooms |
| occupancyPerc | `Float` | Occupancy Perc |
| oooCount | `Float` | Ooo Count |
| oooRooms | `Float` | Number of Rooms marked as Out of Order for today |
| oooRoomsType | `Float` | Ooo Rooms Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| originDisplaySequence | `Float` | Origin Display Sequence |
| otherRevenue | `Float` | Other Revenue |
| parentCompanyId | `Float` | Parent Company ID |
| pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| rateCategory | `String` | Rate Category |
| rateCode | `String` | Rate Code |
| regionCode | `String` | Region Code |
| regionDescription | `String` | Region Description |
| remainingBlockRooms | `Float` | Remaining Block Rooms |
| reservationInventoryType | `String` | Reservation Inventory Type |
| reservationType | `String` | Reservation Type |
| resortNumberRooms | `Float` | Property Number Rooms |
| resortPhyNumRooms | `Float` | Property Phy Num Rooms |
| resortPhysicalNumberRooms | `Float` | Property Physical Number Rooms |
| resortPhysicalNumberRoomsCount | `Float` | Property Physical Number Rooms Count |
| roomCatPhyNumRooms | `Float` | Room Catering Phy Num Rooms |
| roomCatPhysicalNumberRooms | `Float` | Room Catering Physical Number Rooms |
| roomCatPhysicalNumberRoomsCount | `Float` | Room Catering Physical Number Rooms Count |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomNights | `Float` | Room Nights |
| roomRevenue | `Float` | Room Revenue |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source group of the source code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceProfId | `Float` | Source Prof ID |
| totalCount | `Float` | Total Count |
| totalOccupancy | `Float` | Total Occupancy |
| totalPhyResortRooms | `Float` | Tot Phy Property Rooms |
| totalPhyResortRoomsCount | `Float` | Tot Phy Property Rooms Count |
| totalPhyRooms | `Float` | Total Phy Rooms |
| totalPhyRoomsCount | `Float` | Total Phy Rooms Count |
| totalRevenue | `Float` | Total Revenue |
| waitlistPersons | `Float` | Waitlist Persons |
| waitlistRooms | `Float` | Waitlist Rooms |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastFiscalCalendarDetailsType

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

### StatisticsHistoryAndForecastGregerianCalendarDetailsType

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

### StatisticsHistoryAndForecastReservationProfileAccountsSourceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastMarketDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market group attached to the market code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketgroupid | `String` | Marketgroupid |
| marketid | `String` | Marketid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printGroup | `String` | Print Group for Nationality Report |
| property | `String` | Property |
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

### StatisticsHistoryAndForecastPropertyPropertyDetailsType

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

### StatisticsHistoryAndForecastProfileAccountsTravelAgentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### StatisticsHistoryAndForecastReservationProfileAccountsCompanyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originDisplaySequence': pl.Float64,
    'otherRevenue': pl.Float64,
    'parentCompanyId': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
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
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```