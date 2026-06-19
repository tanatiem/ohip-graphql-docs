# StatisticsForecastSummary
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `statisticsForecastSummary`
> Future on the books information including rooms revenue and persons with breakdowns by room types market code source code and periods of time.
  
**Return:** [`[StatisticsForecastSummaryType]`](#statisticsforecastsummarytype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`StatisticsForecastSummaryQueryArgumentsType!`](#statisticsforecastsummaryqueryargumentstype) |  |

## Object Types

### StatisticsForecastSummaryType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | forecastSummaryDetails | [`StatisticsForecastSummaryForecastSummaryDetailsType`](#statisticsforecastsummaryforecastsummarydetailstype) | Forecast Summary Details |
| 2 | parentCompanyProfileDeatils | [`StatisticsForecastSummaryParentCompanyProfileDeatilsType`](#statisticsforecastsummaryparentcompanyprofiledeatilstype) | Parent Company Details |
| 3 | fiscalCalendarDetails | [`StatisticsForecastSummaryFiscalCalendarDetailsType`](#statisticsforecastsummaryfiscalcalendardetailstype) | Fiscal Calendar |
| 4 | gregerianCalendarDetails | [`StatisticsForecastSummaryGregerianCalendarDetailsType`](#statisticsforecastsummarygregeriancalendardetailstype) | Gregerian Calendar |
| 5 | rateSeasonDayDetails | [`StatisticsForecastSummaryRateSeasonDayDetailsType`](#statisticsforecastsummaryrateseasondaydetailstype) | Rate Season Daily Details |
| 6 | foreignCurrencyDetails | [`StatisticsForecastSummaryForeignCurrencyDetailsType`](#statisticsforecastsummaryforeigncurrencydetailstype) | Foreign Currency Details |
| 7 | roomClassDetails | [`StatisticsForecastSummaryRoomClassDetailsType`](#statisticsforecastsummaryroomclassdetailstype) | Room Class Details |
| 8 | propertyPropertyDetails | [`StatisticsForecastSummaryPropertyPropertyDetailsType`](#statisticsforecastsummarypropertypropertydetailstype) | Resort Details |
| 9 | marketDetails | [`StatisticsForecastSummaryMarketDetailsType`](#statisticsforecastsummarymarketdetailstype) | Market Details |
| 10 | rateClassesDetails | [`StatisticsForecastSummaryRateClassesDetailsType`](#statisticsforecastsummaryrateclassesdetailstype) | Rate Classes Details |
| 11 | sourceTableDetails | [`StatisticsForecastSummarySourceTableDetailsType`](#statisticsforecastsummarysourcetabledetailstype) | Source Table Details |
| 12 | bookingStatusDetails | [`StatisticsForecastSummaryBookingStatusDetailsType`](#statisticsforecastsummarybookingstatusdetailstype) | Booking Status Details |
| 13 | nationalityDetails | [`StatisticsForecastSummaryNationalityDetailsType`](#statisticsforecastsummarynationalitydetailstype) | Nationality Details |
| 14 | rateCategoriesDetails | [`StatisticsForecastSummaryRateCategoriesDetailsType`](#statisticsforecastsummaryratecategoriesdetailstype) | Rate Categories Details |
| 15 | rateCodeDetails | [`StatisticsForecastSummaryRateCodeDetailsType`](#statisticsforecastsummaryratecodedetailstype) | Rate Code Details |
| 16 | roomCategoryDetails | [`StatisticsForecastSummaryRoomCategoryDetailsType`](#statisticsforecastsummaryroomcategorydetailstype) | Room Category Details |
| 17 | countryDetails | [`StatisticsForecastSummaryCountryDetailsType`](#statisticsforecastsummarycountrydetailstype) | Country Details |
| 18 | channelDetails | [`StatisticsForecastSummaryChannelDetailsType`](#statisticsforecastsummarychanneldetailstype) | Channel Details |
| 19 | regionDetails | [`StatisticsForecastSummaryRegionDetailsType`](#statisticsforecastsummaryregiondetailstype) | Region Details |
| 20 | statisticsForecastSummaryRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryForecastSummaryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | agentId | `Float` | Agent ID |
| 4 | allotmentHeaderId | `Float` | Allotment Header ID |
| 5 | allotmentid | `Float` | Block ID |
| 6 | arrivalPersons | `Float` | Arrival Persons |
| 7 | arrivalRooms | `Float` | Arrival Rooms |
| 8 | blockStatus | `String` | Block Status |
| 9 | bookedRoomCategory | `String` | Booked Room Category |
| 10 | bookingStatus | `String` | Booking Status |
| 11 | bookingstatusid | `String` | Bookingstatusid |
| 12 | businessDateCreated | `Date` | Business Date Created |
| 13 | cDayUseNetRoomRevenue | `Float` | Central Day Use Net Room Revenue |
| 14 | cExchangeDate | `Date` | Central Xchange Date |
| 15 | cExchangeRate | `Float` | Central Xchange Rate |
| 16 | cFCExtraRevenue | `Float` | Central Fc Extra Revenue |
| 17 | cFCFoodRevenue | `Float` | Central Fc Food Revenue |
| 18 | cFCFoodRevenueTax | `Float` | Central Fc Food Revenue Tax |
| 19 | cFCGrossRate | `Float` | Central Fc Gross Rate |
| 20 | cFCNetRoomRevenue | `Float` | Central Fc Net Room Revenue |
| 21 | cFCNonRevenue | `Float` | Central Fc Non Revenue |
| 22 | cFCNonRevenueTax | `Float` | Central Fc Non Revenue Tax |
| 23 | cFCOtherRevenue | `Float` | Central Fc Other Revenue |
| 24 | cFCOtherRevenueTax | `Float` | Central Fc Other Revenue Tax |
| 25 | cFCRoomRevenue | `Float` | Central Fc Room Revenue |
| 26 | cFCRoomRevenueTax | `Float` | Central Fc Room Revenue Tax |
| 27 | cFCTotalRevenue | `Float` | Central Fc Total Revenue |
| 28 | cFCTotalRevenueTax | `Float` | Central Fc Total Revenue Tax |
| 29 | cFoodRevenueTax | `Float` | Central Food Revenue Tax |
| 30 | cNonRevenueTax | `Float` | Central Non Revenue Tax |
| 31 | cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 32 | cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 33 | cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 34 | centralCurrencyCode | `String` | Central Currency Code |
| 35 | centralDayUseExtraRevenue | `Float` | Central Day Use Extra Revenue |
| 36 | centralDayUseGrossRate | `Float` | Central Day Use Gross Rate |
| 37 | centralExchangeRate | `Float` | Central Exchange Rate |
| 38 | centralExtraRevenue | `Float` | Central Extra Revenue |
| 39 | centralFoodRevenue | `Float` | Central Food Revenue |
| 40 | centralGrossRate | `Float` | Central Gross Rate |
| 41 | centralNetRoomRevenue | `Float` | Central Net Room Revenue |
| 42 | centralNonRevenue | `Float` | Central Non Revenue |
| 43 | centralOtherRevenue | `Float` | Central Other Revenue |
| 44 | centralRoomRevenue | `Float` | Central Room Revenue |
| 45 | centralRoomType | `String` | Central Room Type |
| 46 | centralTotalRevenue | `Float` | Central Total Revenue |
| 47 | centralWaitlistExtraRevenue | `Float` | Central Waitlist Extra Revenue |
| 48 | centralWaitlistGrossRate | `Float` | Central Waitlist Gross Rate |
| 49 | centralWaitlistNetRoomRevenue | `Float` | Central Waitlist Net Room Revenue |
| 50 | centralcurrencyid | `String` | Centralcurrencyid |
| 51 | channel | `String` | Channel |
| 52 | channelid | `String` | Channelid |
| 53 | children | `Float` | Children |
| 54 | childrenTaxFree | `Float` | Children Tax Free |
| 55 | children1 | `Float` | Children1 |
| 56 | children2 | `Float` | Children2 |
| 57 | children3 | `Float` | Children3 |
| 58 | children4 | `Float` | Children4 |
| 59 | children5 | `Float` | Children5 |
| 60 | city | `String` | City |
| 61 | considereddate | `Date` | Considereddate |
| 62 | country | `String` | Country |
| 63 | countryid | `String` | Countryid |
| 64 | cribs | `Float` | Cribs |
| 65 | currencyCode | `String` | Currency Code |
| 66 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 67 | dayUseExtraRevenue | `Float` | Day Use Extra Revenue |
| 68 | dayUseGrossRate | `Float` | Day Use Gross Rate |
| 69 | dayUseNetRoomRevenue | `Float` | Day Use Net Room Revenue |
| 70 | dayUsePersons | `Float` | Day Use Persons |
| 71 | dayUseRooms | `Float` | Day Use Rooms |
| 72 | dayUseYn | `String` | Day Use Y/N |
| 73 | departurePersons | `Float` | Departure Persons |
| 74 | departureRooms | `Float` | Departure Rooms |
| 75 | district | `String` | District |
| 76 | eventType | `String` | Event Type |
| 77 | exchangeDate | `Date` | Exchange Date |
| 78 | extraBeds | `Float` | Extra Beds |
| 79 | extraRevenue | `Float` | Extra Revenue |
| 80 | fcExtraRevenue | `Float` | FC Extra Revenue |
| 81 | fcFoodRevenue | `Float` | FC Food Revenue |
| 82 | fcFoodRevenueTax | `Float` | FC Food Revenue Tax |
| 83 | fcGrossRate | `Float` | FC Gross Rate |
| 84 | fcNetRoomRevenue | `Float` | FC Net Room Revenue |
| 85 | fcNonRevenue | `Float` | FC Non Revenue |
| 86 | fcNonRevenueTax | `Float` | FC Non Revenue Tax |
| 87 | fcOtherRevenue | `Float` | FC Other Revenue |
| 88 | fcOtherRevenueTax | `Float` | FC Other Revenue Tax |
| 89 | fcRoomRevenue | `Float` | FC Room Revenue |
| 90 | fcRoomRevenueTax | `Float` | FC Room Revenue Tax |
| 91 | fcTotalRevenue | `Float` | FC Total Revenue |
| 92 | fcTotalRevenueTax | `Float` | FC Total Revenue Tax |
| 93 | foodRevenue | `Float` | Food Revenue |
| 94 | foodRevenueTax | `Float` | Food Revenue Tax |
| 95 | gender | `String` | Gender |
| 96 | grossRate | `Float` | Gross Rate |
| 97 | groupId | `Float` | Group ID |
| 98 | id | `Float` | ID |
| 99 | jRNUpdateDate | `Date` | JRN Update Date |
| 100 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 101 | locationID | `String` | Internal ID to uniquely identify the Property |
| 102 | marketCode | `String` | Market Code |
| 103 | marketid | `String` | Marketid |
| 104 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 105 | nationality | `String` | Nationality |
| 106 | nationalityid | `String` | Nationalityid |
| 107 | netRoomRevenue | `Float` | Net Room Revenue |
| 108 | nonRevenue | `Float` | Non Revenue |
| 109 | nonRevenueTax | `Float` | Non Revenue Tax |
| 110 | numberOfGuests | `Float` | Number of Guests |
| 111 | numberOfRooms | `Float` | Number of Rooms |
| 112 | oooRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 113 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 114 | osRooms | `Float` | Os Rooms |
| 115 | otherRevenue | `Float` | Other Revenue |
| 116 | otherRevenueTax | `Float` | Other Revenue Tax |
| 117 | ownerFfFlag | `String` | Owner Ff Flag |
| 118 | ownerRentalFlag | `String` | Owner Rental Flag |
| 119 | parentCompanyId | `Float` | Parent Company ID |
| 120 | parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| 121 | pickedUpBlockRooms | `Float` | Picked-Up Block Rooms |
| 122 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 123 | property | `String` | Code to uniquely identify the Property |
| 124 | pseudoRoomYN | `String` | Pseudo Room YN |
| 125 | quantity | `Float` | Quantity |
| 126 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 127 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 128 | rateCategory | `String` | Rate Category |
| 129 | rateClass | `String` | Rate Class |
| 130 | rateCode | `String` | Rate Code |
| 131 | ratecategoryid | `String` | Ratecategoryid |
| 132 | rateclassid | `String` | Rateclassid |
| 133 | ratecodeid | `String` | Ratecodeid |
| 134 | regionCode | `String` | Region Code |
| 135 | regionid | `String` | Regionid |
| 136 | remainingBlockRooms | `Float` | Remaining Block Rooms |
| 137 | resInsertSource | `String` | Reservation Insert Source |
| 138 | reservationInventoryType | `String` | Reservation Inventory Type |
| 139 | reservationType | `String` | Reservation Type |
| 140 | reservationdailytotalid | `Float` | Reservation Daily Total ID |
| 141 | reservationid | `String` | Reservationid |
| 142 | resvStatus | `String` | Reservation Status |
| 143 | roomCategory | `String` | Room Category |
| 144 | roomClass | `String` | Room Class |
| 145 | roomRevenue | `Float` | Room Revenue |
| 146 | roomRevenueTax | `Float` | Room Revenue Tax |
| 147 | roomType | `String` | Room Type |
| 148 | roomclassid | `String` | Roomclassid |
| 149 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 150 | sourceCode | `String` | Source Code |
| 151 | sourceProfId | `Float` | Source Prof ID |
| 152 | sourceid | `String` | Sourceid |
| 153 | state | `String` | State |
| 154 | stayDate | `Date` | Stay Date |
| 155 | totalRevenue | `Float` | Total Revenue |
| 156 | totalRevenueTax | `Float` | Total Revenue Tax |
| 157 | truncEndDate | `Date` | Trunc End Date |
| 158 | truncStartDate | `Date` | Trunc Start Date |
| 159 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 160 | updateBusinessDate | `Date` | Update Business Date |
| 161 | updateDate | `DateTime` | Update Date |
| 162 | vipStatus | `String` | VIP Status |
| 163 | waitlistExtraRevenue | `Float` | Waitlist Extra Revenue |
| 164 | waitlistGrossRate | `Float` | Waitlist Gross Rate |
| 165 | waitlistNetRoomRevenue | `Float` | Waitlist Net Room Revenue |
| 166 | waitlistPersons | `Float` | Waitlist Persons |
| 167 | waitlistRooms | `Float` | Waitlist Rooms |
| 168 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryParentCompanyProfileDeatilsType

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

### StatisticsForecastSummaryFiscalCalendarDetailsType

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

### StatisticsForecastSummaryGregerianCalendarDetailsType

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

### StatisticsForecastSummaryRateSeasonDayDetailsType

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

### StatisticsForecastSummaryForeignCurrencyDetailsType

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

### StatisticsForecastSummaryRoomClassDetailsType

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

### StatisticsForecastSummaryPropertyPropertyDetailsType

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

### StatisticsForecastSummaryMarketDetailsType

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

### StatisticsForecastSummaryRateClassesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralRateClass | `String` | Central Rate Class |
| 2 | centralRateClassDescription | `String` | Central Rate Class Description |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedflag | `String` | Deleted Flag |
| 5 | displaySequence | `Float` | Display Sequence |
| 6 | endDate | `Date` | End Date |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | internalLocationId | `String` | Location ID |
| 11 | internalOrganizationId | `Float` | Organization ID |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | locationID | `String` | Internal ID to uniquely identify the Property |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rateClass | `String` | Rate Class |
| 19 | rateClassDescription | `String` | Rate Class Description |
| 20 | rateClassId | `String` | Rate Class ID |
| 21 | repItem | `String` | Reporting Item |
| 22 | repItemName | `String` | Reporting Item Name |
| 23 | repItemOrderby | `Float` | Reporting Item Orderby |
| 24 | repSellSequence | `Float` | Reporting Sell Sequence |
| 25 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 26 | resortResort | `String` | Property code |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | startDate | `Date` | Start Date |
| 30 | updateDate | `DateTime` | Update Date |
| 31 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummarySourceTableDetailsType

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

### StatisticsForecastSummaryBookingStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowPickupYN | `String` | Allow Pickup YN |
| 2 | bookingstatusid | `String` | Bookingstatusid |
| 3 | cateringStatusType | `String` | Catering Status Type |
| 4 | cateringdeductinvflag | `String` | Cateringdeductinvflag |
| 5 | centralDescription | `String` | Central Description |
| 6 | centralEventStatus | `String` | Central Event Status |
| 7 | centralSequence | `Float` | Central Sequence |
| 8 | chainCode | `String` | Chain Code |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deductinventoryflag | `String` | Deductinventoryflag |
| 11 | defaultReservationType | `String` | Default reservation type |
| 12 | deletedflag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | diaryYN | `String` | Show the booking status in the diary |
| 15 | displayColor | `String` | Display Color |
| 16 | fitStatusYn | `String` | Indicates an FIT statuscode. |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | leadStatusYn | `String` | Indicates if this Booking Status is an Initial Lead status. |
| 23 | logCateringYn | `String` | Will store the information whether the details_ok_yn flag of allotment_header will be set to Y. This operation is done at trigger level. |
| 24 | oRMSYN | `String` | Indicates that the blocks in this status will be considered by ORMS for forecasting. |
| 25 | oldBlockStatus | `String` | Old Block Status |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | reasonType | `String` | Type of the reason for the booking status |
| 32 | repItem | `String` | Reporting Item |
| 33 | repItemName | `String` | Reporting Item Name |
| 34 | repItemOrderby | `Float` | Reporting Item Orderby |
| 35 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 36 | returnInventoryYN | `String` | Return Inventory YN |
| 37 | roomStatusType | `String` | Room Status Type |
| 38 | sequence | `Float` | Sequence |
| 39 | startingYN | `String` | Booking starting status (intial pickup) |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryNationalityDetailsType

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

### StatisticsForecastSummaryRateCategoriesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | centralDescription | `String` | Central Description |
| 3 | centralRateCategory | `String` | Central Rate Category |
| 4 | centralRateClass | `String` | Central Rate Class |
| 5 | centralRateClassDescription | `String` | Central Rate Class Description |
| 6 | centralSequence | `Float` | Central Sequence |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | displayDefaultYn | `String` | Display the rate category Y/N |
| 10 | displaySet | `String` | Display Set |
| 11 | endDate | `Date` | End Date |
| 12 | exportBucketCode | `String` | Export Bucket Code |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | property | `String` | Property |
| 22 | rateCategory | `String` | Rate Category |
| 23 | rateCategoryDescription | `String` | Rate Category Description |
| 24 | rateClass | `String` | Rate Class |
| 25 | rateClassDescription | `String` | Rate Class Description |
| 26 | rateTier | `String` | Rate Tier |
| 27 | ratecategoryid | `String` | Ratecategoryid |
| 28 | ratetierid | `String` | Ratetierid |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 34 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 35 | sequence | `Float` | Sequence |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryRateCodeDetailsType

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

### StatisticsForecastSummaryRoomCategoryDetailsType

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

### StatisticsForecastSummaryCountryDetailsType

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

### StatisticsForecastSummaryChannelDetailsType

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

### StatisticsForecastSummaryRegionDetailsType

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

### StatisticsForecastSummaryQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| forecastsummaryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| forecastsummaryDetailsEventType | `StringInput` | Event Type |
| forecastsummaryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| forecastsummaryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| forecastsummaryDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| forecastsummaryDetailsRoomCategory | `StringInput` | Room Category |
| forecastsummaryDetailsConsideredDate | `DateInput!` | Stay Date<br>`@mandatoryInput` |
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
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
| rateclassesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| rateclassesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rateclassesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| rateclassesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| rateclassesDetailsRateClass | `StringInput` | Rate Class |
| rateclassesDetailsResortResort | `StringInput` | Property code |
| sourcetableDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sourcetableDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sourcetableDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| sourcetableDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sourcetableDetailsResort | `StringInput` | Property |
| sourcetableDetailsSourceCode | `StringInput` | Source Code |
| sourcetableDetailsSourceid | `StringInput` | Sourceid |
| bookingstatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bookingstatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bookingstatusDetailsStatus | `StringInput` | Old Block Status |
| bookingstatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| nationalityDetailsAttributeCode | `StringInput` | Code |
| nationalityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| nationalityDetailsEntityName | `StringInput` | Entity Name |
| nationalityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| nationalityDetailsLanguageCode | `StringInput` | Language Code |
| nationalityDetailsNationalityid | `StringInput` | Nationalityid |
| nationalityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| nationalityDetailsTitleSuffix | `FloatInput` | Title Suffix |
| ratecategoriesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecategoriesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecategoriesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecategoriesDetailsResort | `StringInput` | Property |
| ratecategoriesDetailsRateCategory | `StringInput` | Rate Category |
| ratecategoriesDetailsRateClass | `StringInput` | Rate Class |
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
#### Validation Rules

**`mandatoryInput`**
- forecastsummaryDetailsResort
- forecastsummaryDetailsConsideredDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query statisticsForecastSummary($input: StatisticsForecastSummaryQueryArgumentsType!) {
  statisticsForecastSummary(input: $input) @stream {
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
    bookingStatusDetails {
      allowPickupYN
      bookingstatusid
      cateringStatusType
      cateringdeductinvflag
      centralDescription
      centralEventStatus
      centralSequence
      chainCode
      dSI
      deductinventoryflag
      defaultReservationType
      deletedflag
      description
      diaryYN
      displayColor
      fitStatusYn
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      leadStatusYn
      logCateringYn
      oRMSYN
      oldBlockStatus
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reasonType
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      returnInventoryYN
      roomStatusType
      sequence
      startingYN
      updateDate
      updateUser
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
    rateCategoriesDetails {
      businessDate
      centralDescription
      centralRateCategory
      centralRateClass
      centralRateClassDescription
      centralSequence
      dSI
      deletedflag
      displayDefaultYn
      displaySet
      endDate
      exportBucketCode
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rateCategory
      rateCategoryDescription
      rateClass
      rateClassDescription
      rateTier
      ratecategoryid
      ratetierid
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
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
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'osRooms': pl.Float64,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerRentalFlag': pl.Utf8,
    'parentCompanyId': pl.Float64,
    'parentcompanyprofileid': pl.Float64,
    'pickedUpBlockRooms': pl.Float64,
    'primaryKeyID': pl.Int64,
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
rate_classes_details_schema = {
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displaySequence': pl.Float64,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
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
booking_status_details_schema = {
    'allowPickupYN': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringdeductinvflag': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralEventStatus': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deductinventoryflag': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'diaryYN': pl.Utf8,
    'displayColor': pl.Utf8,
    'fitStatusYn': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'leadStatusYn': pl.Utf8,
    'logCateringYn': pl.Utf8,
    'oRMSYN': pl.Utf8,
    'oldBlockStatus': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reasonType': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'returnInventoryYN': pl.Utf8,
    'roomStatusType': pl.Utf8,
    'sequence': pl.Float64,
    'startingYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
rate_categories_details_schema = {
    'businessDate': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralRateCategory': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayDefaultYn': pl.Utf8,
    'displaySet': pl.Utf8,
    'endDate': pl.Utf8,
    'exportBucketCode': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCategoryDescription': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateClassDescription': pl.Utf8,
    'rateTier': pl.Utf8,
    'ratecategoryid': pl.Utf8,
    'ratetierid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
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