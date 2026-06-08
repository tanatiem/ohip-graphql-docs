# StatisticsForecastSummary
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| forecastSummaryDetails | [`StatisticsForecastSummaryForecastSummaryDetailsType`](#statisticsforecastsummaryforecastsummarydetailstype) | Forecast Summary Details |
| parentCompanyProfileDeatils | [`StatisticsForecastSummaryParentCompanyProfileDeatilsType`](#statisticsforecastsummaryparentcompanyprofiledeatilstype) | Parent Company Details |
| fiscalCalendarDetails | [`StatisticsForecastSummaryFiscalCalendarDetailsType`](#statisticsforecastsummaryfiscalcalendardetailstype) | Fiscal Calendar |
| gregerianCalendarDetails | [`StatisticsForecastSummaryGregerianCalendarDetailsType`](#statisticsforecastsummarygregeriancalendardetailstype) | Gregerian Calendar |
| rateSeasonDayDetails | [`StatisticsForecastSummaryRateSeasonDayDetailsType`](#statisticsforecastsummaryrateseasondaydetailstype) | Rate Season Daily Details |
| foreignCurrencyDetails | [`StatisticsForecastSummaryForeignCurrencyDetailsType`](#statisticsforecastsummaryforeigncurrencydetailstype) | Foreign Currency Details |
| roomClassDetails | [`StatisticsForecastSummaryRoomClassDetailsType`](#statisticsforecastsummaryroomclassdetailstype) | Room Class Details |
| propertyPropertyDetails | [`StatisticsForecastSummaryPropertyPropertyDetailsType`](#statisticsforecastsummarypropertypropertydetailstype) | Resort Details |
| marketDetails | [`StatisticsForecastSummaryMarketDetailsType`](#statisticsforecastsummarymarketdetailstype) | Market Details |
| rateClassesDetails | [`StatisticsForecastSummaryRateClassesDetailsType`](#statisticsforecastsummaryrateclassesdetailstype) | Rate Classes Details |
| sourceTableDetails | [`StatisticsForecastSummarySourceTableDetailsType`](#statisticsforecastsummarysourcetabledetailstype) | Source Table Details |
| bookingStatusDetails | [`StatisticsForecastSummaryBookingStatusDetailsType`](#statisticsforecastsummarybookingstatusdetailstype) | Booking Status Details |
| nationalityDetails | [`StatisticsForecastSummaryNationalityDetailsType`](#statisticsforecastsummarynationalitydetailstype) | Nationality Details |
| rateCategoriesDetails | [`StatisticsForecastSummaryRateCategoriesDetailsType`](#statisticsforecastsummaryratecategoriesdetailstype) | Rate Categories Details |
| rateCodeDetails | [`StatisticsForecastSummaryRateCodeDetailsType`](#statisticsforecastsummaryratecodedetailstype) | Rate Code Details |
| roomCategoryDetails | [`StatisticsForecastSummaryRoomCategoryDetailsType`](#statisticsforecastsummaryroomcategorydetailstype) | Room Category Details |
| countryDetails | [`StatisticsForecastSummaryCountryDetailsType`](#statisticsforecastsummarycountrydetailstype) | Country Details |
| channelDetails | [`StatisticsForecastSummaryChannelDetailsType`](#statisticsforecastsummarychanneldetailstype) | Channel Details |
| regionDetails | [`StatisticsForecastSummaryRegionDetailsType`](#statisticsforecastsummaryregiondetailstype) | Region Details |
| statisticsForecastSummaryRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryForecastSummaryDetailsType

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

### StatisticsForecastSummaryParentCompanyProfileDeatilsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRNumberCentral | `String` | AR Number (Central) |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountBillingContact | `String` | Billing contact person in PARENTCOMPANYPROFILE. |
| accountSource | `String` | Account Source |
| accountType | `String` | Account Type |
| actionCode | `String` | Action Code |
| activeYN | `String` | Active YN |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allOwnerCodes | `String` | All Owner Codes |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateMiddleName | `String` | Alternate Middle Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| autoPopRouting | `String` | Auto Pop Routing |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| availabilityOverride | `String` | Does profile have Availability Override Y/N |
| billingCode | `String` | The billing code for this name record. |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthCountry | `String` | Country of birth. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessTitle | `String` | Business Title |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | The unique identifier of the CRS |
| cashBlInd | `String` | Cash Bl Individual |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountType | `String` | Central Account Type |
| centralCorporateIDType | `String` | Central Corporate ID Type |
| centralDefaultKeyword | `String` | Central Default Keyword |
| centralNationality | `String` | Central Nationality |
| centralNationalityCode | `String` | Central Nationality Code |
| centralPriority | `String` | Central Priority |
| centralStateCode | `String` | Central State Code |
| centralTerritory | `String` | Central Territory |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| communicationType1 | `String` | Communication Type 1 |
| communicationType2 | `String` | Communication Type 2 |
| communicationType3 | `String` | Communication Type 3 |
| communicationValue1 | `String` | Communication Value 1 |
| communicationValue2 | `String` | Communication Value 2 |
| communicationValue3 | `String` | Communication Value 3 |
| competition | `String` | Competition |
| contractNo | `String` | Contract Number (used for customers). |
| contractRecvDate | `Date` | The date the group contract was received. |
| corporateID | `String` | Corporate ID |
| corporateIDType | `String` | Specified whether Name_Code column has PARENTCOMPANYPROFILE # or IATA #. For PARENTCOMPANYPROFILE # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultKeyword | `String` | Default Keyword |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Department |
| deptId | `String` | Dept ID |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| email | `String` | Email |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| externalReferenceRequ | `String` | Not Used. |
| externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| fMembershipCardNumbers | `String` | F Membership Card Numbers |
| fMembershipClassDesc | `String` | F Membership Class Description |
| fMembershipClasses | `String` | F Membership Classes |
| fMembershipCodes | `String` | F Membership Codes |
| fMembershipDescriptions | `String` | F Membership Descriptions |
| fMembershipIds | `String` | F Membership Ids |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNumber | `String` | Fax Number |
| first | `String` | First |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Gender |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYN | `String` | History YN |
| holdCode | `String` | Hold Code |
| iataConsortia | `String` | IATA Consortia |
| idCountry | `String` | ID Country |
| idDate | `Date` | ID Date |
| idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| idNumber | `String` | ID Number |
| idPlace | `String` | ID Place |
| idType | `String` | ID Type |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason why record was inactivated. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| incognitoFirstName | `String` | Incognito First Name |
| incognitoLastName | `String` | Incognito Last Name |
| indexName | `String` | Index Name |
| industryCode | `String` | Industry Code |
| influence | `String` | Influence |
| insertDate | `DateTime` | Insert Date |
| insertUser | `String` | Insert User |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| languageCode | `String` | Language Code |
| laptopChange | `Float` | Laptop Change |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| lastUpdatedResort | `String` | Last property that updated this record. |
| letterGreeting | `String` | Letter Greeting |
| mailListYN | `String` | Mail List YN |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| markets | `String` | Markets |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| middle | `String` | Middle |
| name | `String` | Name |
| name2 | `String` | Name 2 |
| name3 | `String` | Name 3 |
| nameComment | `String` | Not Used. |
| nameTaxType | `String` | Name Tax Type |
| nameWithTitle | `String` | Name With Title |
| nationality | `String` | Nationality |
| nationalityCode | `String` | Nationality Code |
| negotiatedRateCodes | `String` | Negotiated Rate Codes |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| passport | `String` | Passport |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| paymentMethodsCode | `String` | Payment Methods Code |
| paymentMethodsDesc | `String` | Payment Methods Description |
| phoneNumber | `String` | Phone no. |
| phoneYn | `String` | Phone Y/N |
| postalCode | `String` | Postal Code |
| preferredRoomNo | `String` | Preferred Room Number |
| primaryAddressId | `Float` | Not used. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryNameId | `Float` | Not Used. |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| primaryPhoneId | `Float` | Not used. |
| priority | `String` | Priority |
| privateYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileArrCodes | `String` | Profile Arrangement Codes |
| profileArrangementDesc | `String` | Profile Arr Description |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileType | `String` | Profile Type |
| propertyRegistered | `String` | Resort for which Job is registered. |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | Region |
| repAccountTypeDescription | `String` | Reporting Account Type Description |
| repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| repCompetitionDescription | `String` | Reporting Competition Desc |
| repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| repInactiveReason | `String` | Reporting Inactive Reason |
| repInactiveReasonCode | `String` | Reporting Inactive Reason Code |
| repIndustryDescription | `String` | Reporting Industry Desc |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionDescription | `String` | Reporting Mail Action Desc |
| repMarketsDescription | `String` | Reporting Markets Desc |
| repNameType | `String` | Reporting Name Type |
| repNameTypeDescription | `String` | Reporting Name Type Description |
| repPriorityDescription | `String` | Reporting Priority Desc |
| repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| repScopeCityDescription | `String` | Reporting Scope City Desc |
| repScopeDescription | `String` | Reporting Scope Desc |
| repStateDescription | `String` | Reporting State Desc |
| repTerritoryDescription | `String` | Reporting Territory Desc |
| repTitle | `String` | Reporting Title |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resvContact | `String` | Reservation Contact person. |
| roomsPotential | `String` | Rooms Potential |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| searchName | `String` | The Uppercase value of Last or PARENTCOMPANYPROFILE. |
| searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sfirst | `String` | Uppercase value of First Name. |
| smsYn | `String` | Use this alert to text a notification. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| srepCode | `String` | Srep Code |
| state | `String` | State |
| stateCode | `String` | State Code |
| suffix | `String` | Suffix |
| summRefCc | `String` | Summ Ref Cc |
| superSearchIndexText | `String` | Super Search Index Text |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxID1 | `String` | Tax ID 1 |
| taxID2 | `String` | Tax ID 2 |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| territory | `String` | Territory |
| thirdPartyYn | `String` | Third Party Y/N |
| title | `String` | Title |
| titleSuffix | `Float` | Title Suffix |
| totalArrivals | `Float` | Total Arrivals |
| totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| totalCancelledReservations | `Float` | Total Cancelled Reservations |
| totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| totalCancelledRooms | `Float` | Total Cancelled Rooms |
| totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| totalDayUseReservations | `Float` | Total Day Use Reservations |
| totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| totalDayUseRooms | `Float` | Total Day Use Rooms |
| totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| totalNoShowReservations | `Float` | Total Number Show Reservations |
| totalNoShowRooms | `Float` | Total Number Show Rooms |
| totalNonRevenue | `Float` | Total Non Revenue |
| totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| totalReservationNights | `Float` | Total Reservation Nights |
| totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueLastyear | `Float` | Total Revenue Last Year |
| totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| totalStaysLastyear | `Float` | Total Stays Last Year |
| tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| traceCode | `String` | Trace Code |
| typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
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
| uploadDate | `Date` | Upload Date |
| vendorId | `Float` | Vendor ID |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryFiscalCalendarDetailsType

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

### StatisticsForecastSummaryGregerianCalendarDetailsType

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

### StatisticsForecastSummaryRateSeasonDayDetailsType

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

### StatisticsForecastSummaryForeignCurrencyDetailsType

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

### StatisticsForecastSummaryRoomClassDetailsType

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

### StatisticsForecastSummaryPropertyPropertyDetailsType

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

### StatisticsForecastSummaryMarketDetailsType

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

### StatisticsForecastSummaryRateClassesDetailsType

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

### StatisticsForecastSummarySourceTableDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralSequence | `Float` | Central Sequence |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| deletedflag | `String` | Deleted Flag |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlagYN | `String` | Inactive YN |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastuseddatetime | `DateTime` | Lastuseddatetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentsourceid | `String` | Parentsourceid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source group of the source code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceid | `String` | Sourceid |
| tempYn | `String` | Temp Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryBookingStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowPickupYN | `String` | Allow Pickup YN |
| bookingstatusid | `String` | Bookingstatusid |
| cateringStatusType | `String` | Catering Status Type |
| cateringdeductinvflag | `String` | Cateringdeductinvflag |
| centralDescription | `String` | Central Description |
| centralEventStatus | `String` | Central Event Status |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deductinventoryflag | `String` | Deductinventoryflag |
| defaultReservationType | `String` | Default reservation type |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| diaryYN | `String` | Show the booking status in the diary |
| displayColor | `String` | Display Color |
| fitStatusYn | `String` | Indicates an FIT statuscode. |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| leadStatusYn | `String` | Indicates if this Booking Status is an Initial Lead status. |
| logCateringYn | `String` | Will store the information whether the details_ok_yn flag of allotment_header will be set to Y. This operation is done at trigger level. |
| oRMSYN | `String` | Indicates that the blocks in this status will be considered by ORMS for forecasting. |
| oldBlockStatus | `String` | Old Block Status |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reasonType | `String` | Type of the reason for the booking status |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| returnInventoryYN | `String` | Return Inventory YN |
| roomStatusType | `String` | Room Status Type |
| sequence | `Float` | Sequence |
| startingYN | `String` | Booking starting status (intial pickup) |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryNationalityDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralDescription | `String` | Central Description |
| centralNationalityCode | `String` | Central Nationality Code |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| nationalityid | `String` | Nationalityid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryRateCategoriesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessDate | `Date` | Business Date |
| centralDescription | `String` | Central Description |
| centralRateCategory | `String` | Central Rate Category |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| centralSequence | `Float` | Central Sequence |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayDefaultYn | `String` | Display the rate category Y/N |
| displaySet | `String` | Display Set |
| endDate | `Date` | End Date |
| exportBucketCode | `String` | Export Bucket Code |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rateCategory | `String` | Rate Category |
| rateCategoryDescription | `String` | Rate Category Description |
| rateClass | `String` | Rate Class |
| rateClassDescription | `String` | Rate Class Description |
| rateTier | `String` | Rate Tier |
| ratecategoryid | `String` | Ratecategoryid |
| ratetierid | `String` | Ratetierid |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryRateCodeDetailsType

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
| backToBackYN | `String` | Back To Back YN |
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
| blockName | `String` | Block Name |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastPrice | `Float` | Breakfast Price |
| businessDate | `Date` | Business Date |
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
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralRateBucket | `String` | Central Rate Bucket |
| centralRateBucketDescription | `String` | Central Rate Bucket Description |
| centralRateCategory | `String` | Central Rate Category |
| centralRateCategoryDescription | `String` | Central Rate Category Description |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| commissionPercent | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| commissionCode | `String` | Commission Code |
| commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| complimentaryYN | `String` | Complimentary YN |
| currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRatesYn | `String` | Daily Rates Y/N |
| dayUseYN | `String` | Day use reservation Y/N. |
| daysWhenClosedToArrival | `String` | Days the rate restriction is not available for arrival |
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
| discountYN | `String` | Discount Flag. |
| displaySequence | `Float` | Display Sequence |
| displaySet | `String` | Display Set |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| endDate | `Date` | End Date |
| eventProperty | `String` | Indicates if the value set for the specific property. |
| exchangeType | `String` | Exchange Type |
| externallyControlledYN | `String` | Externally Controlled YN |
| extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| flatYN | `String` | Flat YN |
| folioText | `String` | Text displayed on the Folio |
| frequentFlyerYN | `String` | Frequent Flyer YN |
| gDSAllowedYN | `String` | Is this rate code available for GDS |
| groupCode | `String` | Group Code |
| highlightRateAmountYn | `String` | To highlight on the rate query |
| houseUseYN | `String` | House-Use YN |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| loyaltyProgramYN | `String` | Flag to indicate if this is a loyalty program |
| mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| maximumDaysAdvanceBooking | `Float` | Maximum Days Advance Booking |
| maximumLengthOfStay | `Float` | Maximum Length of Stay |
| maximumOccupancy | `Float` | Maximum Occupancy |
| mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| minimumDaysAdvanceBooking | `Float` | Minimum Days Advance Booking |
| minimumOccupancy | `Float` | Minimum Occupancy |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| myFidelioUploadYN | `String` | MyFidelio Upload YN |
| negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalRateCode | `String` | Original Rate Code |
| orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| ownerRateYN | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| packageTransactionCode | `String` | Package Transaction Code |
| packageTransactionCodeWeekend | `String` | Package Transaction Code Weekend |
| packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| packageTransactionTaxIncludedYN | `String` | Transaction code is inclusive of tax Y/N |
| packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| packageYN | `String` | Package YN |
| packages | `String` | Packages |
| pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| postingRhythm | `String` | Posting Rhythm |
| postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRateYn | `String` | Print Rate Y/N |
| privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| privilegedYn | `String` | Indicates if rate is privileged or not. |
| profitTransactionCode | `String` | Profit Transaction Code |
| property | `String` | Code to uniquely identify the Property |
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
| rateCodeId | `String` | Rate Code ID |
| rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| rateLabel | `String` | Rate Label |
| rateLevel | `Float` | Rate Level this rate code belongs to. |
| rateUpdateYN | `String` | Needs to send this rate to GDS or not. |
| rateinfoUrl | `String` | Rateinfo Url |
| redemptionRateYN | `String` | Redemption Rate YN |
| regionalAvailabilityYN | `String` | Regional Availability YN |
| repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rodBaseAmount | `Float` | Rod Base Amount |
| rodBaseFltPct | `String` | Rod Base Flt Pct |
| rodBaseRounding | `String` | Rod Base Rounding |
| rodBasedYn | `String` | Is the group code rate of day based |
| rodYn | `String` | Rod Y/N |
| roomAssignmentValue | `Float` | Room Assignment Value |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
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
| tieredYN | `String` | Indicates if the rate is a tiered rate. |
| transactionCode | `String` | Rate transaction code |
| transactionCodeWeekend | `String` | Transaction Code Weekend |
| transactionTaxWeekendIncludedYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| unitOfLengthOfStay | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| wkDeptCode | `String` | Wk Dept Code |
| yieldAs | `String` | Yield As |
| yieldableYN | `String` | Yieldable YN |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryRoomCategoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessibleRoomType | `String` | Indicates if this room type is accessibility compliant. |
| activeDate | `Date` | The date this record becomes valid for use by the system.  User enterable |
| activeflag | `Date` | Activeflag |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoPopulate | `String` | Include room type in the rate header for Myfidelio rates. |
| autoRoomAssignYn | `String` | A setting of Y will automatically assign an available room number to any reservation that is made for this room type. |
| bedType | `String` | Bed Type |
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
| defaultOccupancy | `Float` | Default occupancy for the room type |
| defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| defaultRateDesc | `String` | Default Rate Description |
| defaultratecodeid | `String` | Defaultratecodeid |
| deletedFlag | `String` | Deleted Flag |
| evisitorFacilityId | `String` | Facility ID for eVisitor. |
| genericYN | `String` | Generic YN |
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
| maintenance | `String` | Indicates if rooms of this room type will be available for Room Maintenance functionality. |
| maxFixBedOccupancy | `Float` | Maximum number of persons that can be accommodated in this room type without providing an extra bed. |
| maxRollaways | `Float` | Not used |
| maximumAdults | `Float` | The maximum occupancy of adults for this room category. |
| maximumChildren | `Float` | The maximum occupancy of children for this room category. |
| maximumOccupancy | `Float` | Maximum Occupancy |
| meetingRoomYN | `String` | Meeting Room YN |
| memberAwardRoomGrp | `String` | Specifies which membership award room group the room category belongs to. |
| minimumOccupancy | `Float` | Minimum Occupancy |
| numberOfRooms | `Float` | Number of Rooms |
| oRMSUpsellAmt | `Float` | Relative amount increase per room category per yield category. Used only in ADF10. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ormsDrtier1 | `Float` | The extra charge on child in age tier1 |
| ormsDrtier2 | `Float` | The extra charge on child in age tier2 |
| ormsDrtier3 | `Float` | The extra charge on child in age tier3 |
| ormsDrxtra2ndAdult | `Float` | The extra charge on 2nd adult. |
| ormsDrxtraAdult | `Float` | Daily Rate extra adult additional charge for this room type. |
| ormsDrxtraChild | `Float` | Daily Rate extra children additional charge for this room type. |
| ormsUpsellRank | `Float` | Relative rank (low to high) of the room category per yield category. |
| ownerroomflag | `String` | Ownerroomflag |
| physical | `String` | Physical |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| productClass | `String` | Product Class |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomType | `String` | Pseudo Room Type |
| pseudoRoomYN | `String` | Pseudo Room YN |
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
| roomInfoURL | `String` | URL where room information is stored. |
| roomPool | `String` | Room Pool that this room type belongs to. (Used in Marriott mode). |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Charged Room Type Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomcategorypmsref | `String` | Roomcategorypmsref |
| roomclassid | `String` | Roomclassid |
| rotationGroup | `String` | Rotation Group |
| sLabel | `String` | S Label |
| salesFlag | `String` | Sales strategy flag for Room Types: L=Lead U=Upsell A=Alternate. |
| sellThruRuleYn | `String` | Sell Thru Rule Y/N |
| sendIFC | `String` | Room type sent to interface Y/N |
| sequence | `Float` | Sequence |
| smoking | `String` | Smoking |
| smokingPrefDesc | `String` | Smoking Pref Description |
| suiteYN | `String` | Suite YN |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| yieldStatus | `String` | Yield Status |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryCountryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressdoctorMode | `String` | Defines the mode used to invoke Addressdoctor service [INTERACTIVE or FASTCOMPLETION] |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryMainGroup | `String` | Country Main Group |
| countryid | `String` | Countryid |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayCountryFlagYn | `String` | Indicates if the Country Flag should be displayed on the front end. |
| guestAddressFormat | `String` | Guest Address Format Codes. For Confirmation Letters. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| isoCode | `String` | ISO standard code for the country |
| isoName | `String` | ISO standard name for the country |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| name | `String` | Name |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printSequence | `Float` | Print Sequence |
| propertyAddressFormat | `String` | Property Address Format Codes. For Confirmation Letters. |
| regionCode | `String` | Region Code |
| regionid | `String` | Regionid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| showSequence | `Float` | Display sequence for LOVs |
| statisticCode | `String` | Internal |
| status | `String` | Status |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryChannelDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
| centralSequence | `Float` | Central Sequence |
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
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| originDisplaySequence | `Float` | Origin Display Sequence |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### StatisticsForecastSummaryRegionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| regionDescription | `String` | Region Description |
| regionid | `String` | Regionid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Utf8,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
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

rate_season_day_details_schema = {
    'centralSeasonCode': pl.Utf8,
    'centralSeasonDescription': pl.Utf8,
    'dSI': pl.Float64,
    'dayKey': pl.Utf8,
    'deletedYn': pl.Utf8,
    'displayColor': pl.Utf8,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

foreign_currency_details_schema = {
    'abbreviation': pl.Utf8,
    'activeYN': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'currencyActionId': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dSI': pl.Float64,
    'decimals': pl.Float64,
    'deletedFlag': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'formatMask': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mobileYn': pl.Utf8,
    'multiply': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Float64,
    'previousLocalCurrencyYn': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellCurrency': pl.Utf8,
    'trianMethodYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'usedForCcPaymentsYn': pl.Utf8,
}

room_class_details_schema = {
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

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

source_table_details_schema = {
    'centralSequence': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedYn': pl.Utf8,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlagYN': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internetSalesYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastuseddatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'parentsourceid': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

booking_status_details_schema = {
    'allowPickupYN': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringdeductinvflag': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralEventStatus': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deductinventoryflag': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'diaryYN': pl.Utf8,
    'displayColor': pl.Utf8,
    'fitStatusYn': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'leadStatusYn': pl.Utf8,
    'logCateringYn': pl.Utf8,
    'oRMSYN': pl.Utf8,
    'oldBlockStatus': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

nationality_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'nationalityid': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

rate_categories_details_schema = {
    'businessDate': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralRateCategory': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'dSI': pl.Float64,
    'deletedflag': pl.Utf8,
    'displayDefaultYn': pl.Utf8,
    'displaySet': pl.Utf8,
    'endDate': pl.Utf8,
    'exportBucketCode': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'upsellYn': pl.Utf8,
    'voucherBenefitRateYn': pl.Utf8,
    'weekendDays': pl.Utf8,
    'wkDeptCode': pl.Utf8,
    'yieldAs': pl.Utf8,
    'yieldableYN': pl.Utf8,
    'ymCode': pl.Utf8,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
    'ormsDrtier1': pl.Float64,
    'ormsDrtier2': pl.Float64,
    'ormsDrtier3': pl.Float64,
    'ormsDrxtra2ndAdult': pl.Float64,
    'ormsDrxtraAdult': pl.Float64,
    'ormsDrxtraChild': pl.Float64,
    'ormsUpsellRank': pl.Float64,
    'ownerroomflag': pl.Utf8,
    'physical': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'upsellYn': pl.Utf8,
    'yieldStatus': pl.Utf8,
}

country_details_schema = {
    'addressdoctorMode': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryMainGroup': pl.Utf8,
    'countryid': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'displayCountryFlagYn': pl.Utf8,
    'guestAddressFormat': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'isoCode': pl.Utf8,
    'isoName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

channel_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'channelid': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Float64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originDisplaySequence': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}

region_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Float64,
    'deletedflag': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'regionDescription': pl.Utf8,
    'regionid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

```