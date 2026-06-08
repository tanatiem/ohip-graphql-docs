# ProfilesContacts
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesContacts`
> The Contacts subject area contains Room Night and Revenue statistics broken down between booked and stays reservations and can be summarized by Property Stay Date Business Segment and Owner.
  
**Return:** [`[ProfilesContactsType]`](#profilescontactstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesContactsQueryArgumentsType!`](#profilescontactsqueryargumentstype) |  |

## Object Types

### ProfilesContactsType

| Field | Type | Description |
| --- | --- | --- |
| contactDetails | [`ProfilesContactsContactDetailsType`](#profilescontactscontactdetailstype) | Contact Details |
| profileAddressDetails | [`ProfilesContactsProfileAddressDetailsType`](#profilescontactsprofileaddressdetailstype) | Profile Address Details |
| profileCommunicationDetails | [`ProfilesContactsProfileCommunicationDetailsType`](#profilescontactsprofilecommunicationdetailstype) | Profile Communication Details |
| profilePreferenceDetails | [`ProfilesContactsProfilePreferenceDetailsType`](#profilescontactsprofilepreferencedetailstype) | Profile Preference Details |
| profileMembershipDetails | [`ProfilesContactsProfileMembershipDetailsType`](#profilescontactsprofilemembershipdetailstype) | Profile Membership Details |
| profileNoteDetails | [`ProfilesContactsProfileNoteDetailsType`](#profilescontactsprofilenotedetailstype) | Profile Note Details |
| profileRelationshipDetails | [`ProfilesContactsProfileRelationshipDetailsType`](#profilescontactsprofilerelationshipdetailstype) | Profile Relationship Details |
| profileOwnerDetails | [`ProfilesContactsProfileOwnerDetailsType`](#profilescontactsprofileownerdetailstype) | Profile Owner Details |
| contactDailyStatisticsDetails | [`ProfilesContactsContactDailyStatisticsDetailsType`](#profilescontactscontactdailystatisticsdetailstype) | Contact Daily Statistics |
| contactMonthlyStatisticsDetails | [`ProfilesContactsContactMonthlyStatisticsDetailsType`](#profilescontactscontactmonthlystatisticsdetailstype) | Contact Monthly Statistics |
| contactYearlyStatisticsDetails | [`ProfilesContactsContactYearlyStatisticsDetailsType`](#profilescontactscontactyearlystatisticsdetailstype) | Contact Yearly Statistics |
| profilesContactsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesContactsContactDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRNumber | `String` | AR Number |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountType | `String` | Account Type |
| accountsource | `String` | Accountsource |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| addressType | `String` | Address Type |
| address1 | `String` | Address1 |
| address2 | `String` | Address2 |
| address3 | `String` | Address3 |
| address4 | `String` | Address4 |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allProperties | `String` | All Properties |
| allSalesRepCodes | `String` | All Sales Reporting Codes |
| alternateFirstName | `String` | Alternate First Name |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
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
| businessSegment | `String` | Business Segment |
| businessSegmentDescription | `String` | Business Segment Description |
| businessTitle | `String` | Business Title |
| cRSNameid | `Float` | The unique identifier of the CRS |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralBusinessSegment | `String` | Central Business Segment |
| centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralInfluence | `String` | Central Influence |
| centralInfluenceDescription | `String` | Central Influence Description |
| centralKeyword | `String` | Central Keyword |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralNationality | `String` | Central Nationality |
| centralNationalityDescription | `String` | Central Nationality Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| centralTitle | `String` | Central Title |
| centralVIPCode | `String` | Central VIP Code |
| centralVIPCodeDescription | `String` | Central VIP Code Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| clientID | `String` | Client ID |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| commissionCode | `String` | Commission Code |
| commissionCurrencyId | `String` | Comm Curr ID |
| commissionid | `String` | Commissionid |
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
| companyGroupId | `String` | Linked internal ID for booker. |
| companyNameId | `Float` | Company Name ID |
| competitionCode | `String` | Competition Code |
| contactEmailPrimary | `String` | Contact Email Primary |
| contactPhonePrimary | `String` | Phone no. |
| contactProfileID | `Float` | Contact Profile ID |
| contactYN | `String` | Contact YN |
| contractNo | `String` | Contract Number (used for customers). |
| contractRecvDate | `Date` | The date the group contract was received. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryDesc | `String` | Country Description |
| createdByUser | `String` | Created by User |
| createdOnDate | `DateTime` | Created on Date |
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
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Department |
| deptId | `String` | Dept ID |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| envelopeGreetingAlternate | `String` | Envelope Greeting Alternate |
| externalDisplayName | `String` | External Display Name |
| externalFirstName | `String` | External First Name |
| externalId | `String` | External ID |
| externalName | `String` | External Name |
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
| faxNo | `String` | Fax Number |
| firstName | `String` | First Name |
| firstNameIncognito | `String` | First Name Incognito |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Gender |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYN | `String` | History YN |
| holdCode | `String` | Hold Code |
| iataCompType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| iataConsortia | `String` | IATA Consortia |
| idCountry | `String` | ID Country |
| idDate | `Date` | ID Date |
| idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| idNumber | `String` | ID Number |
| idPlace | `String` | ID Place |
| idType | `String` | ID Type |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| indexName | `String` | Index Name |
| industryCode | `String` | Industry Code |
| influence | `String` | Influence |
| influenceDescription | `String` | Influence Description |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| language | `String` | Language |
| languageDescription | `String` | Language Description |
| laptopChange | `Float` | Laptop Change |
| lastGroup | `String` | Last Group |
| lastName | `String` | Last Name |
| lastNameAlternate | `String` | Last Name Alternate |
| lastNameIncognito | `String` | Last Name Incognito |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastRoomResort | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailActionDescription | `String` | Mail Action Description |
| mailListYN | `String` | Mail List YN |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| mailingActionCode | `String` | Mailing Action Code |
| marketResearchYn | `String` | Market Research Y/N |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| middleName | `String` | Middle Name |
| name | `String` | Name |
| nameComment | `String` | Not Used. |
| nameTaxType | `String` | Name Tax Type |
| nameWithTitle | `String` | Name With Title |
| name2 | `String` | Name2 |
| name3 | `String` | Name3 |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRateCodes | `String` | Negotiated Rate Codes |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| passport | `String` | Passport |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| paymentMethodsCode | `String` | Payment Methods Code |
| paymentMethodsDesc | `String` | Payment Methods Description |
| phoneYn | `String` | Phone Y/N |
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
| profileId | `Float` | Profile ID |
| profileType | `String` | Profile Type |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | Region |
| regionid | `String` | Regionid |
| repAccountType | `String` | Reporting Account Type |
| repAccountTypeDescription | `String` | Reporting Account Type Description |
| repAccountsource | `String` | Reporting Accountsource |
| repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| repCompetitionCode | `String` | Reporting Competition Code |
| repCompetitionDescription | `String` | Reporting Competition Desc |
| repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| repIATACompType | `String` | Reporting Iata Comp Type |
| repIndustryCode | `String` | Reporting Industry Code |
| repIndustryDescription | `String` | Reporting Industry Desc |
| repMailActionCodes | `String` | Reporting Mail Action Codes |
| repNameType | `String` | Reporting Name Type |
| repNameTypeDescription | `String` | Reporting Name Type Description |
| repPriority | `String` | Reporting Priority |
| repPriorityDescription | `String` | Reporting Priority Desc |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| repStateCode | `String` | Reporting State Code |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| resvContact | `String` | Reservation Contact person. |
| roomsPotential | `String` | Rooms Potential |
| salesRep | `String` | Sales Reporting |
| salesRepCode | `String` | Sales Reporting Code |
| salutation | `String` | Salutation Greeting |
| salutationAlternate | `String` | Salutation Alternate |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDescription | `String` | Scope City Description |
| scopeDescription | `String` | Scope Description |
| searchName | `String` | The Uppercase value of Last or Company. |
| searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sfirst | `String` | Uppercase value of First Name. |
| smsYn | `String` | Use this alert to text a notification. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| srepCode | `String` | Srep Code |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| stateDescription | `String` | State Description |
| suffix | `String` | Suffix |
| summRefCc | `String` | Summ Ref Cc |
| summRefCurrencyId | `String` | Summ Ref Curr ID |
| superSearchIndexText | `String` | Super Search Index Text |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxID1 | `String` | Tax ID 1 |
| taxID2 | `String` | Tax ID 2 |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
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
| traceCodeDescription | `String` | Trace Code Description |
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
| vIPCode | `String` | VIP Code |
| vIPCodeDescription | `String` | VIP Code Description |
| vendorId | `Float` | Vendor ID |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xcompanyName | `String` | Extended Byte Company Name |
| xmiddleName | `String` | Extended Byte middle name. |
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileAddressDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | The first line of street address. |
| address2 | `String` | The second line of street address. |
| address3 | `String` | The third line of street address. |
| address4 | `String` | The fourth line of street address. |
| addressID | `Float` | The primary key for this table. |
| addressLanguage | `String` | Address Language |
| addressLanguageDescription | `String` | Description for each language code. |
| addressType | `String` | The type of address. |
| addressTypeDesc | `String` | The description of this value. |
| barcode | `String` | The postal barcode for the address. |
| beginDate | `Date` | Not used. |
| centralState | `String` | Central State |
| centralStateDescription | `String` | Central State Description |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| city | `String` | The city for this address. |
| cleansedDatetime | `DateTime` | The Timestamp when this record was cleansed. |
| cleansedErrormsg | `String` | The error message why this record was not cleansed. |
| cleansedMatchstatus | `String` | Specifies how the address elements match with the postal reference data. |
| cleansedStatus | `String` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| cleansedValidationstatus | `String` | Validation Status as returned by the Address Cleansing System. |
| clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| countryCode | `String` | Country . |
| countryDescription | `String` | Country name. |
| createdByUser | `Float` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYN | `String` | Deleted Y/n |
| endDate | `Date` | Not used. |
| firstName | `String` | The first name of an individual name. |
| foreignCountry | `String` | Not used. |
| inCareOf | `String` | Not used. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveYN | `String` | Inactive Y/n |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Code to synchronize with Laptop. (not used) |
| lastUpdatedResort | `String` | Last property that updated this record. |
| name | `String` | Name |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| postalCode | `String` | The postal code of this address. |
| postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| profileAddressId | `Float` | The primary key for this table. |
| profileId | `Float` | The reference to the NAME record that owns this address. |
| profileIdx | `Float` | The reference to the NAME record that owns this address. |
| province | `String` | Province. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| state | `String` | State |
| stateCode | `String` | The state of this address. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileCommunicationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressId | `Float` | Not used. |
| beginDate | `Date` | Not used. |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| communicationID | `Float` | The primary key for this table. |
| communicationRole | `String` | Role in which this phone type belongs to. |
| communicationValue | `String` | The phone number for this record |
| countryCode | `String` | Country Code of the phone number. |
| countryDialingCode | `Float` | Numeric phone dialing prefix code for the country. |
| countryId | `String` | Country Code of the phone number. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultMethodYN | `String` | Phone_role to be used for default confirmation. |
| deletedFlag | `String` | Deleted Flag |
| displaySequence | `Float` | Order in which the phone numbers should be displayed. |
| emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| emailLanguage | `String` | Optional language for e-mail. |
| endDate | `Date` | The date this record becomes invalid for use in the system. User enterable. |
| extension | `String` | Telephone Extension. |
| firstName | `String` | The first name of an individual name. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| indexPhone | `String` | Index Phone |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `Float` | The user that created the record |
| internalOrganizationId | `Float` | Organization ID |
| internalProfileId | `Float` | The reference to the name that owns this phone. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Code to synchronize with Laptop |
| lastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneId | `Float` | The primary key for this table. |
| phoneType | `String` | The type of this phone number. |
| phoneTypeDescription | `String` | Description of Phone Types. |
| phoneTypeId | `String` | The type of this phone number. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| profileID | `Float` | The reference to the name that owns this phone. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| shareEmailYn | `String` | Used for uploading the email to holidex if the value is Y. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |
| validYn | `String` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfilePreferenceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| centralPreferenceCode | `String` | Central Preference Code |
| centralPreferenceDescription | `String` | Central Preference Description |
| centralPreferenceGroup | `String` | Central Preference Group |
| chainCode | `String` | ASP chain code. |
| chargeYn | `String` | Not used. |
| createdByUser | `Float` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displaySequence | `Float` | The display sequence  of the Preferences. |
| externalPreferenceId | `String` | Unique ID in External System. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change Indicator |
| locationID | `String` | The property that the record belongs to |
| mpcode | `String` | Not Used. |
| nameId | `Float` | Reference to the name that owns this record. |
| noteProperty | `String` | The property that the record belongs to |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| preferenceCode | `String` | Preference Code. Part of the Primary Key. |
| preferenceDescription | `String` | Description of the Preference. |
| preferenceGroup | `String` | Description of the Preference Type. |
| preferenceId | `String` | Preference Code. |
| preferenceTypeCode | `String` | Preference Type. |
| preferenceTypeId | `String` | Preference Type. |
| preferenceValue | `String` | Preference Code. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| profileId | `Float` | Reference to the name that owns this record. |
| profilePreferenceId | `String` | Preference Code. |
| property | `String` | The property that the record belongs to |
| repOrderby | `Float` | Reporting Orderby |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileMembershipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cCreditLimit | `Float` | Central Credit Limit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| chainCode | `String` | Chain code. |
| comments | `String` | Used by EIS Module. |
| creditLimit | `Float` | Used in the EIS Module. |
| currentPoints | `Float` | Used in the EIS Module. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| deviceCode | `String` | Encoded string on the device. |
| deviceDisableDate | `Date` | Date when device was disabled. |
| earningPreference | `String` | Points or miles earning preference. |
| enrollmentCode | `String` | Code to indicate source used to enroll the member. |
| enrollmentProperty | `String` | Resort/CRO where enrollment is done. |
| enrollmentSource | `String` | Source from where the enrollment is done. |
| excludeFromBatch | `String` | Flag to determine member actions to include in the fulfillment extract |
| expirationDate | `Date` | Expiration date of the Card. |
| gracePeriodIndicator | `String` | Grace Period Indicator |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `String` | The unique name of application user |
| internalMembershipid | `Float` | Primary Key for this table. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| joinedDate | `Date` | Used by EIS Module. |
| mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| memberIndicator | `String` | Used in the EIS Module. |
| memberSubtype | `String` | Used in the EIS Module. |
| membergueststatusid | `String` | Membergueststatusid |
| membershipActiveYN | `String` | Membership Active YN |
| membershipClass | `String` | Primary key of this table |
| membershipID | `Float` | Primary Key for this table. |
| membershipLevel | `String` | Level of this Membership Type. |
| membershipLevelDescription | `String` | Membership Level Description |
| membershipNumber | `String` | Membership Card Number. |
| membershipStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| membershipType | `String` | Type of the Membership. |
| membershipTypeDescription | `String` | Description of membership program type. |
| membershipenrollid | `String` | Membershipenrollid |
| membershiplevelid | `String` | Level of this Membership Type. |
| membershiptypeid | `String` | Type of the Membership. |
| nameId | `Float` | Reference to the name that owns this record. |
| nameOnCard | `String` | Name as appeared on the Membership Card. |
| orderBy | `Float` | The display sequence of the membership cards held by this profile if there are multiple membership cards. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| partnerMembershipId | `Float` | Membership ID that accrues Miles. |
| pointflag | `String` | Used in the EIS Module. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryMembershipYN | `String` | Primary Membership YN |
| primaryairlineflag | `String` | Used in the EIS Module. |
| processExpirationDate | `Date` | Used in the EIS Module. |
| profileid | `Float` | Reference to the name that owns this record. |
| ranking | `Float` | Current membership ranking value for this profile possible values: 1-10. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| trackData | `String` | Stores key track information for a universal card that may be different than the membership number. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `String` | The unique name of application user |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileNoteDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activityDueDate | `Date` | Activity Due Date |
| activityType | `String` | Activity Type |
| chainCode | `String` | ASP chain code. |
| confidentialYN | `String` | Indicates if this note is confidential. |
| createdByUser | `Float` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| externalNoteId | `String` | Unique ID in External System. |
| globalNoteYn | `String` | Global Note Y/N |
| globalYn | `String` | Can a global note be created for this note code or not. |
| inactiveDate | `Date` | Inactive date of the record. This indicates that record is no longer in use and can be purged in by purge routine. |
| inactiveFlag | `String` | Inactive Flag |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalLocationId | `String` | Location Id |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Indicator for Laptop change. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameId | `Float` | Parent Name_id refers Name table. |
| nameType | `String` | The type of Profile. |
| noteCode | `String` | Indicates the Type of Note. |
| noteCodeDescription | `String` | Description of Note Code |
| noteId | `Float` | Primary Key for the Table |
| noteInternalYN | `String` | Indicates if this note should be shown to guest. Future use. |
| noteTitle | `String` | Title of the Note |
| notes | `String` | The actual Note. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| profileId | `Float` | Parent Name_id refers Name table. |
| profileNoteId | `Float` | Profile Note ID |
| resort | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileRelationshipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| company | `String` | This column store the Name of the Company Profiles. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromProfileID | `Float` | The reference to the name that owns this relationship. |
| guestName | `String` | Guest Name |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `Float` | The user that created the record |
| internalLocationId | `String` | The property that the record belongs to |
| internalOrganizationId | `Float` | Organization ID |
| internalRelationshipId | `String` | The type of relationship this name id has to the relationship_to_name_id. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Changed by laptop Y or N |
| locationID | `String` | The property that the record belongs to |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerProfileId | `Float` | The reference to the name that owns this relationship. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Indicates the Primary relationship where Multiple Relationships are attached to a profile. |
| profilerelationshipId | `Float` | The primary key for this table. |
| property | `String` | The property that the record belongs to |
| relationshipCode | `String` | The type of relationship this name id has to the relationship_to_name_id. |
| relationshipDescription | `String` | Description of the relationship. |
| relationshipID | `Float` | The primary key for this table. |
| relationshipRole | `String` | Used in S&C Module |
| relationshipTo | `String` | Relationship To |
| relationshipToNameID | `Float` | The reference to the name that the "Name_id" is related to. |
| resort | `String` | The property that the record belongs to |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| toProfileID | `Float` | The reference to the name that the "Name_id" is related to. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesContactsProfileOwnerDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountOwner | `String` | Account Owner |
| accountOwnerCode | `String` | Account Owner Code |
| accountOwnerEmail | `String` | Account Owner Email |
| accountOwnerPhone | `String` | Phone no. |
| accountOwnerTitle | `String` | Account Owner Title |
| accountSrepCode | `String` | Account Srep Code |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationId | `String` | Location ID |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerProfileId | `Float` | Owner Profile ID |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| profileOwnerId | `Float` | Profile Owner ID |
| property | `String` | Indicates if the value set for the specific property. |
| relationship | `String` | Relationship |
| relationshipid | `String` | Relationshipid |
| resort | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userId | `Float` | User ID |

[⬆ Back to Query](#query)

---

### ProfilesContactsContactDailyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookedAdr | `Float` | Booked Average Daily Rate |
| bookedCancels | `Float` | Booked Cancels |
| bookedFBRevenue | `Float` | Booked FB Revenue |
| bookedFBRevenueTax | `Float` | Booked FB Revenue Tax |
| bookedGrpAverageDailyRate | `Float` | Booked Group Adr |
| bookedGrpFBRevenue | `Float` | Booked Group Fb Revenue |
| bookedGrpFBRevenueTax | `Float` | Booked Group Fb Revenue Tax |
| bookedGrpNumberCancels | `Float` | Booked Group Number Cancels |
| bookedGrpNumberNights | `Float` | Booked Group Number Nights |
| bookedGrpNumberNumberShows | `Float` | Booked Group Number No Shows |
| bookedGrpNumberStays | `Float` | Booked Group Number Stays |
| bookedGrpOtherRevenue | `Float` | Booked Group Other Revenue |
| bookedGrpOtherRevenueTax | `Float` | Booked Group Other Revenue Tax |
| bookedGrpRoomRevenue | `Float` | Booked Group Room Revenue |
| bookedGrpRoomRevenueTax | `Float` | Booked Group Room Revenue Tax |
| bookedGrpTotalRevenue | `Float` | Booked Group Total Revenue |
| bookedGrpTotalRevenueTax | `Float` | Booked Group Total Revenue Tax |
| bookedNoShows | `Float` | Booked Number Shows |
| bookedNumberCancels | `Float` | Booked Number Cancels |
| bookedNumberNights | `Float` | Booked Number Nights |
| bookedNumberNoShows | `Float` | Booked Number Number Shows |
| bookedNumberStays | `Float` | Booked Number Stays |
| bookedOtherRevenue | `Float` | Booked Other Revenue |
| bookedOtherRevenueTax | `Float` | Booked Other Revenue Tax |
| bookedRoomNights | `Float` | Booked Room Nights |
| bookedRoomRevenue | `Float` | Booked Room Revenue |
| bookedRoomRevenueTax | `Float` | Booked Room Revenue Tax |
| bookedStays | `Float` | Booked Stays |
| bookedTotalAdr | `Float` | Booked Total Average Daily Rate |
| bookedTotalFbRevenue | `Float` | Booked Total FB Revenue |
| bookedTotalFbRevenueTax | `Float` | Booked Total FB Revenue Tax |
| bookedTotalOtherRevenue | `Float` | Booked Total Other Revenue |
| bookedTotalOtherRevenueTax | `Float` | Booked Total Other Revenue Tax |
| bookedTotalRevenue | `Float` | Booked Total Revenue |
| bookedTotalRevenueTax | `Float` | Booked Total Revenue Tax |
| bookedTotalRoomRevenue | `Float` | Booked Total Room Revenue |
| bookedTotalRoomRevenueTax | `Float` | Booked Total Room Revenue Tax |
| bookedTotalTotalRevenue | `Float` | Booked Total Total Revenue |
| bookedTotalTotalRevenueTax | `Float` | Booked Total Total Revenue Tax |
| cBookedGroupFBRevenue | `Float` | Central Booked Grp Fb Revenue |
| cBookedGroupFBRevenueTax | `Float` | Central Booked Grp Fb Revenue Tax |
| cBookedGroupOtherRevenue | `Float` | Central Booked Grp Other Revenue |
| cBookedGroupOtherRevenueTax | `Float` | Central Booked Grp Other Revenue Tax |
| cBookedGroupRoomRevenue | `Float` | Central Booked Grp Room Revenue |
| cBookedGroupRoomRevenueTax | `Float` | Central Booked Grp Room Revenue Tax |
| cBookedGroupTotalRevenue | `Float` | Central Booked Grp Total Revenue |
| cBookedGroupTotalRevenueTax | `Float` | Central Booked Grp Total Revenue Tax |
| cBookedTotalFBRevenue | `Float` | Central Booked Total Fb Revenue |
| cBookedTotalFBRevenueTax | `Float` | Central Booked Total Fb Revenue Tax |
| cBookedTotalOtherRevenue | `Float` | Central Booked Total Other Revenue |
| cBookedTotalOtherRevenueTax | `Float` | Central Booked Total Other Revenue Tax |
| cBookedTotalRoomRevenue | `Float` | Central Booked Total Room Revenue |
| cBookedTotalRoomRevenueTax | `Float` | Central Booked Total Room Revenue Tax |
| cBookedTotalTotalRevenue | `Float` | Central Booked Total Total Revenue |
| cBookedTotalTotalRevenueTax | `Float` | Central Booked Total Total Revenue Tax |
| cStayedGroupFBRevenue | `Float` | Central Stayed Grp Fb Revenue |
| cStayedGroupFBRevenueTax | `Float` | Central Stayed Grp Fb Revenue Tax |
| cStayedGroupOtherRevenue | `Float` | Central Stayed Grp Other Revenue |
| cStayedGroupOtherRevenueTax | `Float` | Central Stayed Grp Other Revenue Tax |
| cStayedGroupRoomRevenue | `Float` | Central Stayed Grp Room Revenue |
| cStayedGroupRoomRevenueTax | `Float` | Central Stayed Grp Room Revenue Tax |
| cStayedGroupTotalRevenue | `Float` | Central Stayed Grp Total Revenue |
| cStayedGroupTotalRevenueTax | `Float` | Central Stayed Grp Total Revenue Tax |
| cStayedTotalFBRevenue | `Float` | Central Stayed Total Fb Revenue |
| cStayedTotalFBRevenueTax | `Float` | Central Stayed Total Fb Revenue Tax |
| cStayedTotalOtherRevenue | `Float` | Central Stayed Total Other Revenue |
| cStayedTotalOtherRevenueTax | `Float` | Central Stayed Total Other Revenue Tax |
| cStayedTotalRevenue | `Float` | Central Stayed Total Revenue |
| cStayedTotalRevenueTax | `Float` | Central Stayed Total Revenue Tax |
| cStayedTotalRoomRevenue | `Float` | Central Stayed Total Room Revenue |
| cStayedTotalRoomRevenueTax | `Float` | Central Stayed Total Room Revenue Tax |
| cStayedTotalTotalRevenue | `Float` | Central Stayed Total Total Revenue |
| cStayedTotalTotalRevenueTax | `Float` | Central Stayed Total Total Revenue Tax |
| cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| cTotalOtherRevenue | `Float` | Central Total Other Revenue |
| cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| cTotalRevenue | `Float` | Central Total Revenue |
| cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| cancels | `Float` | Cancels |
| centralBookedFBRevenue | `Float` | Central Booked FB Revenue |
| centralBookedFBRevenueTax | `Float` | Central Booked FB Revenue Tax |
| centralBookedOtherRevenue | `Float` | Central Booked Other Revenue |
| centralBookedOtherRevenueTax | `Float` | Central Booked Other Revenue Tax |
| centralBookedRoomRevenue | `Float` | Central Booked Room Revenue |
| centralBookedRoomRevenueTax | `Float` | Central Booked Room Revenue Tax |
| centralBookedTotalRevenue | `Float` | Central Booked Total Revenue |
| centralBookedTotalRevenueTax | `Float` | Central Booked Total Revenue Tax |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| centralStayedFBRevenue | `Float` | Central Stayed FB Revenue |
| centralStayedFBRevenueTax | `Float` | Central Stayed FB Revenue Tax |
| centralStayedOtherRevenue | `Float` | Central Stayed Other Revenue |
| centralStayedOtherRevenueTax | `Float` | Central Stayed Other Revenue Tax |
| centralStayedRoomRevenue | `Float` | Central Stayed Room Revenue |
| centralStayedRoomRevenueTax | `Float` | Central Stayed Room Revenue Tax |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenue | `Float` | FB Revenue |
| fBRevenueTax | `Float` | F&B Revenue Tax. |
| grpAverageDailyRate | `Float` | Group Adr |
| grpFBRevenue | `Float` | Group F&B Revenue. |
| grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| grpNumberCancels | `Float` | Group Number of Cancellations. |
| grpNumberNights | `Float` | Group Number of Nights. |
| grpNumberNumberShows | `Float` | Group Number of No Shows. |
| grpNumberStays | `Float` | Group Number of Stays. |
| grpOtherRevenue | `Float` | Group Other Revenue. |
| grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| grpRoomRevenue | `Float` | Group Room Revenue. |
| grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| grpTotalRevenue | `Float` | Group Total Revenue. |
| grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jrnFilerba | `Float` | Journal Filerba |
| jrnFileseqno | `Float` | Journal Fileseqno |
| jrnFlag | `String` | Journal Flag |
| jrnScn | `Float` | Journal Scn |
| jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| localCurrency | `String` | Local Currency Code. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameId | `Float` | Name ID |
| nameType | `String` | Name Type |
| noShows | `Float` | Number Shows |
| numberCancels | `Float` | Number Cancels |
| numberNights | `Float` | Number Nights |
| numberNoShows | `Float` | Number Number Shows |
| numberStays | `Float` | Number Stays |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otherRevenue | `Float` | Other Revenue |
| otherRevenueTax | `Float` | Other Revenue Tax |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueTax | `Float` | Room Revenue Tax |
| stayDate | `Date` | Stay Date |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| stayedAdr | `Float` | Stayed Average Daily Rate |
| stayedCancels | `Float` | Stayed Cancels |
| stayedFBRevenue | `Float` | Stayed FB Revenue |
| stayedFBRevenueTax | `Float` | Stayed FB Revenue Tax |
| stayedGrpAverageDailyRate | `Float` | Stayed Group Adr |
| stayedGrpFBRevenue | `Float` | Stayed Group Fb Revenue |
| stayedGrpFBRevenueTax | `Float` | Stayed Group Fb Revenue Tax |
| stayedGrpNumberCancels | `Float` | Stayed Group Number Cancels |
| stayedGrpNumberNights | `Float` | Stayed Group Number Nights |
| stayedGrpNumberNumberShows | `Float` | Stayed Group Number No Shows |
| stayedGrpNumberStays | `Float` | Stayed Group Number Stays |
| stayedGrpOtherRevenue | `Float` | Stayed Group Other Revenue |
| stayedGrpOtherRevenueTax | `Float` | Stayed Group Other Revenue Tax |
| stayedGrpRoomRevenue | `Float` | Stayed Group Room Revenue |
| stayedGrpRoomRevenueTax | `Float` | Stayed Group Room Revenue Tax |
| stayedGrpTotalRevenue | `Float` | Stayed Group Total Revenue |
| stayedGrpTotalRevenueTax | `Float` | Stayed Group Total Revenue Tax |
| stayedNoShows | `Float` | Stayed Number Shows |
| stayedNumberCancels | `Float` | Stayed Number Cancels |
| stayedNumberNights | `Float` | Stayed Number Nights |
| stayedNumberNoShows | `Float` | Stayed Number Number Shows |
| stayedNumberStays | `Float` | Stayed Number Stays |
| stayedOtherRevenue | `Float` | Stayed Other Revenue |
| stayedOtherRevenueTax | `Float` | Stayed Other Revenue Tax |
| stayedRoomNights | `Float` | Stayed Room Nights |
| stayedRoomRevenue | `Float` | Stayed Room Revenue |
| stayedRoomRevenueTax | `Float` | Stayed Room Revenue Tax |
| stayedStays | `Float` | Stayed Stays |
| stayedTotalAdr | `Float` | Stayed Total Average Daily Rate |
| stayedTotalFbRevenue | `Float` | Stayed Total FB Revenue |
| stayedTotalFbRevenueTax | `Float` | Stayed Total FB Revenue Tax |
| stayedTotalOtherRevenue | `Float` | Stayed Total Other Revenue |
| stayedTotalOtherRevenueTax | `Float` | Stayed Total Other Revenue Tax |
| stayedTotalRevenue | `Float` | Stayed Total Revenue |
| stayedTotalRevenueTax | `Float` | Stayed Total Revenue Tax |
| stayedTotalRoomRevenue | `Float` | Stayed Total Room Revenue |
| stayedTotalRoomRevenueTax | `Float` | Stayed Total Room Revenue Tax |
| stayedTotalTotalRevenue | `Float` | Stayed Total Total Revenue |
| stayedTotalTotalRevenueTax | `Float` | Stayed Total Total Revenue Tax |
| stays | `Float` | Stays |
| totalAdr | `Float` | Total Average Daily Rate |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| totalNumberNights | `Float` | Total Number Nights |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueTax | `Float` | Total Revenue Tax |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| totalTotalRevenue | `Float` | Total Total Revenue |
| totalTotalRevenueTax | `Float` | Total Total Revenue Tax |

[⬆ Back to Query](#query)

---

### ProfilesContactsContactMonthlyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adr | `Float` | Average Daily Rate |
| bookedFBRevenue | `Float` | Booked FB Revenue |
| bookedRoomRevenue | `Float` | Booked Room Revenue |
| bookedRoomRevenueTax | `Float` | Booked Room Revenue Tax |
| bookedStays | `Float` | Booked Stays |
| cCcFBRevenue | `Float` | Central Cc Fb Revenue |
| cCcFBRevenueTax | `Float` | Central Cc Fb Revenue Tax |
| cCcGroupFBRevenue | `Float` | Central Cc Grp Fb Revenue |
| cCcGroupFBRevenueTax | `Float` | Central Cc Grp Fb Revenue Tax |
| cCcGroupMiscellaneousRevenue | `Float` | Central Cc Grp Misc Revenue |
| cCcGroupMiscellaneousRevenueTax | `Float` | Central Cc Grp Misc Revenue Tax |
| cCcGroupOtherRevenue | `Float` | Central Cc Grp Other Revenue |
| cCcGroupOtherRevenueTax | `Float` | Central Cc Grp Other Revenue Tax |
| cCcGroupRoomRevenue | `Float` | Central Cc Grp Room Revenue |
| cCcGroupRoomRevenueTax | `Float` | Central Cc Grp Room Revenue Tax |
| cCcGroupTotalRevenue | `Float` | Central Cc Grp Total Revenue |
| cCcGroupTotalRevenueTax | `Float` | Central Cc Grp Total Revenue Tax |
| cCcMiscellaneousRevenue | `Float` | Central Cc Misc Revenue |
| cCcMiscellaneousRevenueTax | `Float` | Central Cc Misc Revenue Tax |
| cCcOtherRevenue | `Float` | Central Cc Other Revenue |
| cCcOtherRevenueTax | `Float` | Central Cc Other Revenue Tax |
| cCcRoomRevenue | `Float` | Central Cc Room Revenue |
| cCcRoomRevenueTax | `Float` | Central Cc Room Revenue Tax |
| cCcTotalRevenue | `Float` | Central Cc Total Revenue |
| cCcTotalRevenueTax | `Float` | Central Cc Total Revenue Tax |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| cTotalFBRevenue | `Float` | Central Total Fb Revenue |
| cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| cTotalOtherRevenue | `Float` | Central Total Other Revenue |
| cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| cTotalRoomRevenue | `Float` | Central Total Room Revenue |
| cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| cTotalTotalRevenue | `Float` | Central Total Total Revenue |
| cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| ccFbRevenue | `Float` | Central Currency F&B Revenue. |
| ccFbRevenueTax | `Float` | Central Currency F&B Revenue Tax. |
| ccGrpFBRevenue | `Float` | Central Currency Group F&B Revenue. |
| ccGrpFBRevenueTax | `Float` | Central Currency Group F&B Revenue Tax. |
| ccGrpMiscellaneousRevenue | `Float` | Central Currency Group Misc. Revenue Tax. |
| ccGrpMiscellaneousRevenueTax | `Float` | Central Currency Group Misc. Revenue Tax. |
| ccGrpOtherRevenue | `Float` | Central Currency Group Other Revenue. |
| ccGrpOtherRevenueTax | `Float` | Central Currency Group Other Revenue Tax. |
| ccGrpRoomRevenue | `Float` | Central Currency Group Room Revenue. |
| ccGrpRoomRevenueTax | `Float` | Central Currency Group Room Revenue Tax. |
| ccGrpTotalRevenue | `Float` | Central Currency Group Total Revenue. |
| ccGrpTotalRevenueTax | `Float` | Central Currency Group Total Revenue Tax. |
| ccMiscRevenue | `Float` | Central Currency Miscelleanous Revenue. |
| ccMiscRevenueTax | `Float` | Central Currency Misc. Revenue Tax. |
| ccOtherRevenue | `Float` | Central Currency Other Revenue. |
| ccOtherRevenueTax | `Float` | Central Currency Other Revenue Tax. |
| ccRoomRevenue | `Float` | Central Currency Room Revenue. |
| ccRoomRevenueTax | `Float` | Central Currency Room Revenue Tax. |
| ccTotalRevenue | `Float` | Central Currency Total Revenue. |
| ccTotalRevenueTax | `Float` | Central Currency Total Revenue Tax. |
| centralBookedFBRevenue | `Float` | Central Booked FB Revenue |
| centralBookedFBRevenueTax | `Float` | Central Booked FB Revenue Tax |
| centralBookedOtherRevenueTax | `Float` | Central Booked Other Revenue Tax |
| centralCurrencyCode | `String` | Central Currency Code |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralStayedRoomRevenue | `Float` | Central Stayed Room Revenue |
| centralStayedRoomRevenueTax | `Float` | Central Stayed Room Revenue Tax |
| centralStayedTotalRevenue | `Float` | Central Stayed Total Revenue |
| centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| grpAverageDailyRate | `Float` | Group Adr |
| grpFBRevenue | `Float` | Group F&B Revenue. |
| grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| grpNumberCancels | `Float` | Group Number of Cancellations. |
| grpNumberNights | `Float` | Group Number of Nights. |
| grpNumberNumberShows | `Float` | Group Number of No Shows. |
| grpNumberStays | `Float` | Group Number of Stays. |
| grpOtherRevenue | `Float` | Group Other Revenue. |
| grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| grpRoomRevenue | `Float` | Group Room Revenue. |
| grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| grpTotalRevenue | `Float` | Group Total Revenue. |
| grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jrnFilerba | `Float` | Journal Filerba |
| jrnFileseqno | `Float` | Journal Fileseqno |
| jrnFlag | `String` | Journal Flag |
| jrnScn | `Float` | Journal Scn |
| jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| localCurrency | `String` | Local Currency Code. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameId | `Float` | Name ID |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otherRevenue | `Float` | Other Revenue |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| stayedBooked | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| stayedCancels | `Float` | Stayed Cancels |
| stayedFBRevenueTax | `Float` | F&B Revenue Tax. |
| stayedNoShows | `Float` | Stayed Number Shows |
| stayedOtherRevenueTax | `Float` | Stayed Other Revenue Tax |
| stayedTotalRevenue | `Float` | Stayed Total Revenue |
| totalAdr | `Float` | Total Average Daily Rate |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| totalNumberCancels | `Float` | Total Number Cancels |
| totalNumberNights | `Float` | Total Number Nights |
| totalNumberNoShows | `Float` | Total Number Number Shows |
| totalNumberStays | `Float` | Total Number Stays |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| totalRevenueTax | `Float` | Total Revenue Tax |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| totalTotalRevenue | `Float` | Total Total Revenue |
| totalTotalRevenueTax | `Float` | Total Total Revenue Tax |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesContactsContactYearlyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adr | `Float` | Average Daily Rate |
| bookedCancels | `Float` | Booked Cancels |
| bookedFBRevenueTax | `Float` | F&B Revenue Tax. |
| bookedNoShows | `Float` | Booked Number Shows |
| bookedOtherRevenueTax | `Float` | Booked Other Revenue Tax |
| cCcFBRevenue | `Float` | Central Cc Fb Revenue |
| cCcFBRevenueTax | `Float` | Central Cc Fb Revenue Tax |
| cCcGroupFBRevenue | `Float` | Central Cc Grp Fb Revenue |
| cCcGroupFBRevenueTax | `Float` | Central Cc Grp Fb Revenue Tax |
| cCcGroupMiscellaneousRevenue | `Float` | Central Cc Grp Misc Revenue |
| cCcGroupMiscellaneousRevenueTax | `Float` | Central Cc Grp Misc Revenue Tax |
| cCcGroupOtherRevenue | `Float` | Central Cc Grp Other Revenue |
| cCcGroupOtherRevenueTax | `Float` | Central Cc Grp Other Revenue Tax |
| cCcGroupRoomRevenue | `Float` | Central Cc Grp Room Revenue |
| cCcGroupRoomRevenueTax | `Float` | Central Cc Grp Room Revenue Tax |
| cCcGroupTotalRevenue | `Float` | Central Cc Grp Total Revenue |
| cCcGroupTotalRevenueTax | `Float` | Central Cc Grp Total Revenue Tax |
| cCcMiscellaneousRevenue | `Float` | Central Cc Misc Revenue |
| cCcMiscellaneousRevenueTax | `Float` | Central Cc Misc Revenue Tax |
| cCcOtherRevenue | `Float` | Central Cc Other Revenue |
| cCcOtherRevenueTax | `Float` | Central Cc Other Revenue Tax |
| cCcRoomRevenue | `Float` | Central Cc Room Revenue |
| cCcRoomRevenueTax | `Float` | Central Cc Room Revenue Tax |
| cCcTotalRevenue | `Float` | Central Cc Total Revenue |
| cCcTotalRevenueTax | `Float` | Central Cc Total Revenue Tax |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| cTotalFBRevenue | `Float` | Central Total Fb Revenue |
| cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| cTotalOtherRevenue | `Float` | Central Total Other Revenue |
| cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| cTotalRoomRevenue | `Float` | Central Total Room Revenue |
| cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| cTotalTotalRevenue | `Float` | Central Total Total Revenue |
| cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| ccFbRevenue | `Float` | Central Currency F&B Revenue. |
| ccFbRevenueTax | `Float` | Central Currency F&B Revenue Tax. |
| ccGrpFBRevenue | `Float` | Central Currency Group F&B Revenue. |
| ccGrpFBRevenueTax | `Float` | Central Currency Group F&B Revenue Tax. |
| ccGrpMiscellaneousRevenue | `Float` | Central Currency Group Misc. Revenue Tax. |
| ccGrpMiscellaneousRevenueTax | `Float` | Central Currency Group Misc. Revenue Tax. |
| ccGrpOtherRevenue | `Float` | Central Currency Group Other Revenue. |
| ccGrpOtherRevenueTax | `Float` | Central Currency Group Other Revenue Tax. |
| ccGrpRoomRevenue | `Float` | Central Currency Group Room Revenue. |
| ccGrpRoomRevenueTax | `Float` | Central Currency Group Room Revenue Tax. |
| ccGrpTotalRevenue | `Float` | Central Currency Group Total Revenue. |
| ccGrpTotalRevenueTax | `Float` | Central Currency Group Total Revenue Tax. |
| ccMiscRevenue | `Float` | Central Currency Miscelleanous Revenue. |
| ccMiscRevenueTax | `Float` | Central Currency Misc. Revenue Tax. |
| ccOtherRevenue | `Float` | Central Currency Other Revenue. |
| ccOtherRevenueTax | `Float` | Central Currency Other Revenue Tax. |
| ccRoomRevenue | `Float` | Central Currency Room Revenue. |
| ccRoomRevenueTax | `Float` | Central Currency Room Revenue Tax. |
| ccTotalRevenue | `Float` | Central Currency Total Revenue. |
| ccTotalRevenueTax | `Float` | Central Currency Total Revenue Tax. |
| centralBookedRoomRevenueTax | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| centralBookedTotalRevenueTax | `Float` | Central Booked Total Revenue Tax |
| centralCurrencyCode | `String` | Central Currency Code |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| centralStayedOtherRevenueTax | `Float` | Central Stayed Other Revenue Tax |
| centralStayedTotalRevenue | `Float` | Central Stayed Total Revenue |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenue | `Float` | FB Revenue |
| grpAverageDailyRate | `Float` | Group Adr |
| grpFBRevenue | `Float` | Group F&B Revenue. |
| grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| grpNumberCancels | `Float` | Group Number of Cancellations. |
| grpNumberNights | `Float` | Group Number of Nights. |
| grpNumberNumberShows | `Float` | Group Number of No Shows. |
| grpNumberStays | `Float` | Group Number of Stays. |
| grpOtherRevenue | `Float` | Group Other Revenue. |
| grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| grpRoomRevenue | `Float` | Group Room Revenue. |
| grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| grpTotalRevenue | `Float` | Group Total Revenue. |
| grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jrnFilerba | `Float` | Journal Filerba |
| jrnFileseqno | `Float` | Journal Fileseqno |
| jrnFlag | `String` | Journal Flag |
| jrnScn | `Float` | Journal Scn |
| jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| localCurrency | `String` | Local Currency Code. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameId | `Float` | Name ID |
| nameType | `String` | Name Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueTax | `Float` | Room Revenue Tax |
| stayYear | `Float` | Year of Summary. |
| stayedOtherRevenue | `Float` | Stayed Other Revenue |
| stayedRoomNights | `Float` | Stayed Room Nights |
| stayedTotalRevenue | `Float` | Stayed Total Revenue |
| stayedTotalRevenueTax | `Float` | Stayed Total Revenue Tax |
| stays | `Float` | Stays |
| totalAdr | `Float` | Total Average Daily Rate |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| totalNumberCancels | `Float` | Total Number Cancels |
| totalNumberNights | `Float` | Total Number Nights |
| totalNumberNoShows | `Float` | Total Number Number Shows |
| totalNumberStays | `Float` | Total Number Stays |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| totalTotalRevenue | `Float` | Total Total Revenue |
| totalTotalRevenueTax | `Float` | Total Total Revenue Tax |
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

### ProfilesContactsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| contactDetailsActiveYn | `StringInput` | Active Flag |
| contactDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| contactDetailsChainCode | `StringInput!` | Chain Code<br>`@mandatoryInput` |
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
| profileaddressDetailsAddress1 | `StringInput` | The first line of street address. |
| profileaddressDetailsAddress2 | `StringInput` | The second line of street address. |
| profileaddressDetailsAddress3 | `StringInput` | The third line of street address. |
| profileaddressDetailsAddress4 | `StringInput` | The fourth line of street address. |
| profileaddressDetailsAddressId | `FloatInput` | The primary key for this table. |
| profileaddressDetailsLanguageCode | `StringInput` | Address Language |
| profileaddressDetailsLanguageDesc | `StringInput` | Description for each language code. |
| profileaddressDetailsAddressType | `StringInput` | The type of address. |
| profileaddressDetailsAddressTypeDesc | `StringInput` | The description of this value. |
| profileaddressDetailsBarcode | `StringInput` | The postal barcode for the address. |
| profileaddressDetailsBeginDate | `DateInput` | Not used. |
| profileaddressDetailsRepStateCode | `StringInput` | Central State |
| profileaddressDetailsRepState | `StringInput` | Central State Description |
| profileaddressDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profileaddressDetailsCity | `StringInput` | The city for this address. |
| profileaddressDetailsCleansedDatetime | `DateTimeInput` | The Timestamp when this record was cleansed. |
| profileaddressDetailsCleansedErrormsg | `StringInput` | The error message why this record was not cleansed. |
| profileaddressDetailsCleansedMatchstatus | `StringInput` | Specifies how the address elements match with the postal reference data. |
| profileaddressDetailsCleansedStatus | `StringInput` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| profileaddressDetailsCleansedValidationstatus | `StringInput` | Validation Status as returned by the Address Cleansing System. |
| profileaddressDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| profileaddressDetailsCountryCode | `StringInput` | Country . |
| profileaddressDetailsCountry | `StringInput` | Country name. |
| profileaddressDetailsInsertUser | `FloatInput` | The user that created the record |
| profileaddressDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profileaddressDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaddressDetailsDeletedFlag | `StringInput` | Deleted Y/n |
| profileaddressDetailsEndDate | `DateInput` | Not used. |
| profileaddressDetailsFirst | `StringInput` | The first name of an individual name. |
| profileaddressDetailsForeignCountry | `StringInput` | Not used. |
| profileaddressDetailsInCareOf | `StringInput` | Not used. |
| profileaddressDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profileaddressDetailsInactiveFlag | `StringInput` | Inactive Y/n |
| profileaddressDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaddressDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaddressDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop. (not used) |
| profileaddressDetailsLastUpdatedResort | `StringInput` | Last property that updated this record. |
| profileaddressDetailsName | `StringInput` | Name |
| profileaddressDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaddressDetailsZipCode | `StringInput` | The postal code of this address. |
| profileaddressDetailsCityExt | `StringInput` | City Extension mainly used for UK addresses. |
| profileaddressDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profileaddressDetailsPrimaryYn | `StringInput` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| profileaddressDetailsProfileAddressId | `FloatInput` | The primary key for this table. |
| profileaddressDetailsNameId | `FloatInput` | The reference to the NAME record that owns this address. |
| profileaddressDetailsProfileId | `FloatInput` | The reference to the NAME record that owns this address. |
| profileaddressDetailsProvince | `StringInput` | Province. |
| profileaddressDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profileaddressDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profileaddressDetailsState | `StringInput` | State |
| profileaddressDetailsStateCode | `StringInput` | The state of this address. |
| profileaddressDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profileaddressDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilecommunicationDetailsAddressId | `FloatInput` | Not used. |
| profilecommunicationDetailsBeginDate | `DateInput` | Not used. |
| profilecommunicationDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profilecommunicationDetailsPmsPhoneId | `FloatInput` | The primary key for this table. |
| profilecommunicationDetailsRole | `StringInput` | Role in which this phone type belongs to. |
| profilecommunicationDetailsPhoneNumber | `StringInput` | The phone number for this record |
| profilecommunicationDetailsCountryCode | `StringInput` | Country Code of the phone number. |
| profilecommunicationDetailsCountryDialingCode | `FloatInput` | Numeric phone dialing prefix code for the country. |
| profilecommunicationDetailsCountryId | `StringInput` | Country Code of the phone number. |
| profilecommunicationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilecommunicationDetailsDefaultMethodFlag | `StringInput` | Phone_role to be used for default confirmation. |
| profilecommunicationDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilecommunicationDetailsOrderby | `FloatInput` | Order in which the phone numbers should be displayed. |
| profilecommunicationDetailsEmailFormat | `StringInput` | Format type for email messages: HTML PLAIN text. |
| profilecommunicationDetailsEmailLanguage | `StringInput` | Optional language for e-mail. |
| profilecommunicationDetailsEndDate | `DateInput` | The date this record becomes invalid for use in the system. User enterable. |
| profilecommunicationDetailsExtension | `StringInput` | Telephone Extension. |
| profilecommunicationDetailsFirst | `StringInput` | The first name of an individual name. |
| profilecommunicationDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilecommunicationDetailsInactiveFlag | `StringInput` | Inactive Flag |
| profilecommunicationDetailsIndexPhone | `StringInput` | Index Phone |
| profilecommunicationDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilecommunicationDetailsInsertUser | `FloatInput` | The user that created the record |
| profilecommunicationDetailsOrganizationId | `FloatInput` | Organization ID |
| profilecommunicationDetailsProfileId | `FloatInput` | The reference to the name that owns this phone. |
| profilecommunicationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilecommunicationDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop |
| profilecommunicationDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profilecommunicationDetailsMobileAudioKeyYn | `StringInput` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| profilecommunicationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilecommunicationDetailsPhoneId | `FloatInput` | The primary key for this table. |
| profilecommunicationDetailsPhoneType | `StringInput` | The type of this phone number. |
| profilecommunicationDetailsPhoneTypeDescription | `StringInput` | Description of Phone Types. |
| profilecommunicationDetailsPhoneTypeId | `StringInput` | The type of this phone number. |
| profilecommunicationDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilecommunicationDetailsPrimaryYn | `StringInput` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| profilecommunicationDetailsNameId | `FloatInput` | The reference to the name that owns this phone. |
| profilecommunicationDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilecommunicationDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilecommunicationDetailsShareEmailYn | `StringInput` | Used for uploading the email to holidex if the value is Y. |
| profilecommunicationDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilecommunicationDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilecommunicationDetailsValidYn | `StringInput` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |
| profilepreferenceDetailsCanDeleteYn | `StringInput` | Can Delete Y/N |
| profilepreferenceDetailsRepPreferenceTypeCode | `StringInput` | Central Preference Code |
| profilepreferenceDetailsRepDescription | `StringInput` | Central Preference Description |
| profilepreferenceDetailsRepPreferenceType | `StringInput` | Central Preference Group |
| profilepreferenceDetailsChainCode | `StringInput` | ASP chain code. |
| profilepreferenceDetailsChargeYn | `StringInput` | Not used. |
| profilepreferenceDetailsInsertUser | `FloatInput` | The user that created the record |
| profilepreferenceDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilepreferenceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilepreferenceDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilepreferenceDetailsOrderby | `FloatInput` | The display sequence  of the Preferences. |
| profilepreferenceDetailsExternalPreferenceId | `StringInput` | Unique ID in External System. |
| profilepreferenceDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilepreferenceDetailsInactiveFlag | `StringInput` | Inactive Flag |
| profilepreferenceDetailsOrganizationId | `FloatInput` | Organization ID |
| profilepreferenceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilepreferenceDetailsLaptopChange | `FloatInput` | Laptop Change Indicator |
| profilepreferenceDetailsLocationid | `StringInput` | The property that the record belongs to |
| profilepreferenceDetailsMpcode | `StringInput` | Not Used. |
| profilepreferenceDetailsNameId | `FloatInput` | Reference to the name that owns this record. |
| profilepreferenceDetailsLocationId | `StringInput` | The property that the record belongs to |
| profilepreferenceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilepreferenceDetailsPreference | `StringInput` | Preference Code. Part of the Primary Key. |
| profilepreferenceDetailsDescription | `StringInput` | Description of the Preference. |
| profilepreferenceDetailsPreferenceType | `StringInput` | Description of the Preference Type. |
| profilepreferenceDetailsPreferenceId | `StringInput` | Preference Code. |
| profilepreferenceDetailsPreferenceTypeCode | `StringInput` | Preference Type. |
| profilepreferenceDetailsPreferenceTypeId | `StringInput` | Preference Type. |
| profilepreferenceDetailsPreferenceValue | `StringInput` | Preference Code. |
| profilepreferenceDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilepreferenceDetailsProfileId | `FloatInput` | Reference to the name that owns this record. |
| profilepreferenceDetailsProfilePreferenceId | `StringInput` | Preference Code. |
| profilepreferenceDetailsResort | `StringInput` | The property that the record belongs to |
| profilepreferenceDetailsRepOrderby | `FloatInput` | Reporting Orderby |
| profilepreferenceDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilepreferenceDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilepreferenceDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilepreferenceDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilemembershipDetailsCCreditLimit | `FloatInput` | Central Credit Limit |
| profilemembershipDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| profilemembershipDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| profilemembershipDetailsChainCode | `StringInput` | Chain code. |
| profilemembershipDetailsComments | `StringInput` | Used by EIS Module. |
| profilemembershipDetailsCreditLimit | `FloatInput` | Used in the EIS Module. |
| profilemembershipDetailsCurrentPoints | `FloatInput` | Used in the EIS Module. |
| profilemembershipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilemembershipDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilemembershipDetailsDeviceCode | `StringInput` | Encoded string on the device. |
| profilemembershipDetailsDeviceDisableDate | `DateInput` | Date when device was disabled. |
| profilemembershipDetailsEarningPreference | `StringInput` | Points or miles earning preference. |
| profilemembershipDetailsEnrollmentCode | `StringInput` | Code to indicate source used to enroll the member. |
| profilemembershipDetailsEnrolledAt | `StringInput` | Resort/CRO where enrollment is done. |
| profilemembershipDetailsEnrollmentSource | `StringInput` | Source from where the enrollment is done. |
| profilemembershipDetailsExcludeFromBatch | `StringInput` | Flag to determine member actions to include in the fulfillment extract |
| profilemembershipDetailsExpirationDate | `DateInput` | Expiration date of the Card. |
| profilemembershipDetailsGracePeriodIndicator | `StringInput` | Grace Period Indicator |
| profilemembershipDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilemembershipDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilemembershipDetailsInsertUser | `StringInput` | The unique name of application user |
| profilemembershipDetailsMembershipid | `FloatInput` | Primary Key for this table. |
| profilemembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilemembershipDetailsJoinedDate | `DateInput` | Used by EIS Module. |
| profilemembershipDetailsMbrprefChangedDate | `DateInput` | Last Date Earning Preference was changed. |
| profilemembershipDetailsMemberIndicator | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsMemberSubtype | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsMembergueststatusid | `StringInput` | Membergueststatusid |
| profilemembershipDetailsInactiveflag | `StringInput` | Membership Active YN |
| profilemembershipDetailsMembershipClass | `StringInput` | Primary key of this table |
| profilemembershipDetailsMembershipId | `FloatInput` | Primary Key for this table. |
| profilemembershipDetailsMembershipLevel | `StringInput` | Level of this Membership Type. |
| profilemembershipDetailsMembershipLevelDesc | `StringInput` | Membership Level Description |
| profilemembershipDetailsMembershipCardNo | `StringInput` | Membership Card Number. |
| profilemembershipDetailsMembershipStatus | `StringInput` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| profilemembershipDetailsMembershipType | `StringInput` | Type of the Membership. |
| profilemembershipDetailsMembershipTypeDesc | `StringInput` | Description of membership program type. |
| profilemembershipDetailsMembershipenrollid | `StringInput` | Membershipenrollid |
| profilemembershipDetailsMembershiplevelid | `StringInput` | Level of this Membership Type. |
| profilemembershipDetailsMembershiptypeid | `StringInput` | Type of the Membership. |
| profilemembershipDetailsNameId | `FloatInput` | Reference to the name that owns this record. |
| profilemembershipDetailsNameOnCard | `StringInput` | Name as appeared on the Membership Card. |
| profilemembershipDetailsOrderBy | `FloatInput` | The display sequence of the membership cards held by this profile if there are multiple membership cards. |
| profilemembershipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilemembershipDetailsPartnerMembershipId | `FloatInput` | Membership ID that accrues Miles. |
| profilemembershipDetailsPointflag | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilemembershipDetailsPrimaryMembershipYn | `StringInput` | Primary Membership YN |
| profilemembershipDetailsPrimaryairlineflag | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsProcessExpirationDate | `DateInput` | Used in the EIS Module. |
| profilemembershipDetailsProfileid | `FloatInput` | Reference to the name that owns this record. |
| profilemembershipDetailsRankValue | `FloatInput` | Current membership ranking value for this profile possible values: 1-10. |
| profilemembershipDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilemembershipDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilemembershipDetailsTrackData | `StringInput` | Stores key track information for a universal card that may be different than the membership number. |
| profilemembershipDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilemembershipDetailsUpdateUser | `StringInput` | The unique name of application user |
| profilenoteDetailsActionDueDate | `DateInput` | Activity Due Date |
| profilenoteDetailsActionType | `StringInput` | Activity Type |
| profilenoteDetailsChainCode | `StringInput` | ASP chain code. |
| profilenoteDetailsConfidentialYn | `StringInput` | Indicates if this note is confidential. |
| profilenoteDetailsInsertUser | `FloatInput` | The user that created the record |
| profilenoteDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilenoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilenoteDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilenoteDetailsExternalNoteId | `StringInput` | Unique ID in External System. |
| profilenoteDetailsGlobalNoteYn | `StringInput` | Global Note Y/N |
| profilenoteDetailsGlobalYn | `StringInput` | Can a global note be created for this note code or not. |
| profilenoteDetailsInactiveDate | `DateInput` | Inactive date of the record. This indicates that record is no longer in use and can be purged in by purge routine. |
| profilenoteDetailsInactiveFlag | `StringInput` | Inactive Flag |
| profilenoteDetailsDeletedflag | `StringInput` | Deleted Flag |
| profilenoteDetailsInactiveflag | `StringInput` | Inactive Flag |
| profilenoteDetailsLocationId | `StringInput` | Location Id |
| profilenoteDetailsOrganizationId | `FloatInput` | Organization ID |
| profilenoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilenoteDetailsLaptopChange | `FloatInput` | Indicator for Laptop change. |
| profilenoteDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| profilenoteDetailsNameId | `FloatInput` | Parent Name_id refers Name table. |
| profilenoteDetailsNameType | `StringInput` | The type of Profile. |
| profilenoteDetailsNoteCode | `StringInput` | Indicates the Type of Note. |
| profilenoteDetailsNoteCodeDescription | `StringInput` | Description of Note Code |
| profilenoteDetailsNoteId | `FloatInput` | Primary Key for the Table |
| profilenoteDetailsInternalYn | `StringInput` | Indicates if this note should be shown to guest. Future use. |
| profilenoteDetailsNoteTitle | `StringInput` | Title of the Note |
| profilenoteDetailsNotes | `StringInput` | The actual Note. |
| profilenoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilenoteDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilenoteDetailsProfileId | `FloatInput` | Parent Name_id refers Name table. |
| profilenoteDetailsProfileNoteId | `FloatInput` | Profile Note ID |
| profilenoteDetailsResort | `StringInput` | Property |
| profilenoteDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilenoteDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilenoteDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilenoteDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilerelationshipDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profilerelationshipDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| profilerelationshipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilerelationshipDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilerelationshipDetailsOwnerProfileNo | `FloatInput` | The reference to the name that owns this relationship. |
| profilerelationshipDetailsGuestName | `StringInput` | Guest Name |
| profilerelationshipDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilerelationshipDetailsInactiveFlag | `StringInput` | Inactive Flag |
| profilerelationshipDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilerelationshipDetailsInsertUser | `FloatInput` | The user that created the record |
| profilerelationshipDetailsLocationId | `StringInput` | The property that the record belongs to |
| profilerelationshipDetailsOrganizationId | `FloatInput` | Organization ID |
| profilerelationshipDetailsRelationshipId | `StringInput` | The type of relationship this name id has to the relationship_to_name_id. |
| profilerelationshipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilerelationshipDetailsLaptopChange | `FloatInput` | Changed by laptop Y or N |
| profilerelationshipDetailsLocationid | `StringInput` | The property that the record belongs to |
| profilerelationshipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilerelationshipDetailsOwnerProfileId | `FloatInput` | The reference to the name that owns this relationship. |
| profilerelationshipDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilerelationshipDetailsPrimaryFlag | `StringInput` | Indicates the Primary relationship where Multiple Relationships are attached to a profile. |
| profilerelationshipDetailsProfilerelationshipId | `FloatInput` | The primary key for this table. |
| profilerelationshipDetailsProperty | `StringInput` | The property that the record belongs to |
| profilerelationshipDetailsRelationshipTypeCode | `StringInput` | The type of relationship this name id has to the relationship_to_name_id. |
| profilerelationshipDetailsRelationshipDesc | `StringInput` | Description of the relationship. |
| profilerelationshipDetailsRelationshipCode | `FloatInput` | The primary key for this table. |
| profilerelationshipDetailsRelationshipRole | `StringInput` | Used in S&C Module |
| profilerelationshipDetailsRelatedToProfileName | `StringInput` | Relationship To |
| profilerelationshipDetailsRelatedToProfileId | `FloatInput` | The reference to the name that the "Name_id" is related to. |
| profilerelationshipDetailsResort | `StringInput` | The property that the record belongs to |
| profilerelationshipDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilerelationshipDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilerelationshipDetailsRelatedProfileNo | `FloatInput` | The reference to the name that the "Name_id" is related to. |
| profilerelationshipDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilerelationshipDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profileownerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileownerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileownerDetailsNameId | `FloatInput` | Name ID |
| profileownerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileownerDetailsResort | `StringInput` | Property |
| profileownerDetailsUserId | `FloatInput` | User ID |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesContacts($input: ProfilesContactsQueryArgumentsType!) {
  profilesContacts(input: $input) @stream {
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
    profileAddressDetails {
      address1
      address2
      address3
      address4
      addressID
      addressLanguage
      addressLanguageDescription
      addressType
      addressTypeDesc
      barcode
      beginDate
      centralState
      centralStateDescription
      chainCode
      city
      cleansedDatetime
      cleansedErrormsg
      cleansedMatchstatus
      cleansedStatus
      cleansedValidationstatus
      clientID
      countryCode
      countryDescription
      createdByUser
      createdOnDate
      dSI
      deletedYN
      endDate
      firstName
      foreignCountry
      inCareOf
      inactiveDate
      inactiveYN
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      lastUpdatedResort
      name
      organizationID
      postalCode
      postalCodeExtension
      primaryKeyID
      primaryYN
      profileAddressId
      profileId
      profileIdx
      province
      rnaInsertDate
      rnaUpdateDate
      state
      stateCode
      updateDate
      updateUser
    }
    profileCommunicationDetails {
      addressId
      beginDate
      chainCode
      communicationID
      communicationRole
      communicationValue
      countryCode
      countryDialingCode
      countryId
      dSI
      defaultMethodYN
      deletedFlag
      displaySequence
      emailFormat
      emailLanguage
      endDate
      extension
      firstName
      inactiveDate
      inactiveFlag
      indexPhone
      insertDate
      insertUser
      internalOrganizationId
      internalProfileId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      lastName
      mobileAudioKeyYn
      organizationID
      phoneId
      phoneType
      phoneTypeDescription
      phoneTypeId
      primaryKeyID
      primaryYN
      profileID
      rnaInsertDate
      rnaUpdateDate
      shareEmailYn
      updateDate
      updateUser
      validYn
    }
    profilePreferenceDetails {
      canDeleteYn
      centralPreferenceCode
      centralPreferenceDescription
      centralPreferenceGroup
      chainCode
      chargeYn
      createdByUser
      createdOnDate
      dSI
      deletedFlag
      displaySequence
      externalPreferenceId
      inactiveDate
      inactiveFlag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      mpcode
      nameId
      noteProperty
      organizationID
      preferenceCode
      preferenceDescription
      preferenceGroup
      preferenceId
      preferenceTypeCode
      preferenceTypeId
      preferenceValue
      primaryKeyID
      profileId
      profilePreferenceId
      property
      repOrderby
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    profileMembershipDetails {
      cCreditLimit
      cExchangeDate
      cExchangeRate
      chainCode
      comments
      creditLimit
      currentPoints
      dSI
      deletedFlag
      deviceCode
      deviceDisableDate
      earningPreference
      enrollmentCode
      enrollmentProperty
      enrollmentSource
      excludeFromBatch
      expirationDate
      gracePeriodIndicator
      inactiveDate
      insertDate
      insertUser
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      joinedDate
      mbrprefChangedDate
      memberIndicator
      memberSubtype
      membergueststatusid
      membershipActiveYN
      membershipClass
      membershipID
      membershipLevel
      membershipLevelDescription
      membershipNumber
      membershipStatus
      membershipType
      membershipTypeDescription
      membershipenrollid
      membershiplevelid
      membershiptypeid
      nameId
      nameOnCard
      orderBy
      organizationID
      partnerMembershipId
      pointflag
      primaryKeyID
      primaryMembershipYN
      primaryairlineflag
      processExpirationDate
      profileid
      ranking
      rnaInsertDate
      rnaUpdateDate
      trackData
      updateDate
      updateUser
    }
    profileNoteDetails {
      activityDueDate
      activityType
      chainCode
      confidentialYN
      createdByUser
      createdOnDate
      dSI
      deletedFlag
      externalNoteId
      globalNoteYn
      globalYn
      inactiveDate
      inactiveFlag
      internalDeletedflag
      internalInactiveflag
      internalLocationId
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      nameId
      nameType
      noteCode
      noteCodeDescription
      noteId
      noteInternalYN
      noteTitle
      notes
      organizationID
      primaryKeyID
      profileId
      profileNoteId
      resort
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    profileRelationshipDetails {
      chainCode
      company
      dSI
      deletedFlag
      fromProfileID
      guestName
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      internalRelationshipId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      organizationID
      ownerProfileId
      primaryKeyID
      primaryYN
      profilerelationshipId
      property
      relationshipCode
      relationshipDescription
      relationshipID
      relationshipRole
      relationshipTo
      relationshipToNameID
      resort
      rnaInsertDate
      rnaUpdateDate
      toProfileID
      updateDate
      updateUser
    }
    profileOwnerDetails {
      accountOwner
      accountOwnerCode
      accountOwnerEmail
      accountOwnerPhone
      accountOwnerTitle
      accountSrepCode
      centralAccountOwnerTitle
      chainCode
      dSI
      deletedFlag
      description
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationId
      nameId
      organizationID
      ownerProfileId
      primaryKeyID
      primaryYN
      profileOwnerId
      property
      relationship
      relationshipid
      resort
      rnaInsertDate
      rnaUpdateDate
      toType
      updateDate
      updateUser
      userId
    }
    contactDailyStatisticsDetails {
      bookedAdr
      bookedCancels
      bookedFBRevenue
      bookedFBRevenueTax
      bookedGrpAverageDailyRate
      bookedGrpFBRevenue
      bookedGrpFBRevenueTax
      bookedGrpNumberCancels
      bookedGrpNumberNights
      bookedGrpNumberNumberShows
      bookedGrpNumberStays
      bookedGrpOtherRevenue
      bookedGrpOtherRevenueTax
      bookedGrpRoomRevenue
      bookedGrpRoomRevenueTax
      bookedGrpTotalRevenue
      bookedGrpTotalRevenueTax
      bookedNoShows
      bookedNumberCancels
      bookedNumberNights
      bookedNumberNoShows
      bookedNumberStays
      bookedOtherRevenue
      bookedOtherRevenueTax
      bookedRoomNights
      bookedRoomRevenue
      bookedRoomRevenueTax
      bookedStays
      bookedTotalAdr
      bookedTotalFbRevenue
      bookedTotalFbRevenueTax
      bookedTotalOtherRevenue
      bookedTotalOtherRevenueTax
      bookedTotalRevenue
      bookedTotalRevenueTax
      bookedTotalRoomRevenue
      bookedTotalRoomRevenueTax
      bookedTotalTotalRevenue
      bookedTotalTotalRevenueTax
      cBookedGroupFBRevenue
      cBookedGroupFBRevenueTax
      cBookedGroupOtherRevenue
      cBookedGroupOtherRevenueTax
      cBookedGroupRoomRevenue
      cBookedGroupRoomRevenueTax
      cBookedGroupTotalRevenue
      cBookedGroupTotalRevenueTax
      cBookedTotalFBRevenue
      cBookedTotalFBRevenueTax
      cBookedTotalOtherRevenue
      cBookedTotalOtherRevenueTax
      cBookedTotalRoomRevenue
      cBookedTotalRoomRevenueTax
      cBookedTotalTotalRevenue
      cBookedTotalTotalRevenueTax
      cStayedGroupFBRevenue
      cStayedGroupFBRevenueTax
      cStayedGroupOtherRevenue
      cStayedGroupOtherRevenueTax
      cStayedGroupRoomRevenue
      cStayedGroupRoomRevenueTax
      cStayedGroupTotalRevenue
      cStayedGroupTotalRevenueTax
      cStayedTotalFBRevenue
      cStayedTotalFBRevenueTax
      cStayedTotalOtherRevenue
      cStayedTotalOtherRevenueTax
      cStayedTotalRevenue
      cStayedTotalRevenueTax
      cStayedTotalRoomRevenue
      cStayedTotalRoomRevenueTax
      cStayedTotalTotalRevenue
      cStayedTotalTotalRevenueTax
      cTotalFBRevenueTax
      cTotalOtherRevenue
      cTotalOtherRevenueTax
      cTotalRevenue
      cTotalRevenueTax
      cTotalRoomRevenueTax
      cancels
      centralBookedFBRevenue
      centralBookedFBRevenueTax
      centralBookedOtherRevenue
      centralBookedOtherRevenueTax
      centralBookedRoomRevenue
      centralBookedRoomRevenueTax
      centralBookedTotalRevenue
      centralBookedTotalRevenueTax
      centralFBRevenue
      centralFBRevenueTax
      centralOtherRevenue
      centralOtherRevenueTax
      centralRoomRevenue
      centralRoomRevenueTax
      centralStayedFBRevenue
      centralStayedFBRevenueTax
      centralStayedOtherRevenue
      centralStayedOtherRevenueTax
      centralStayedRoomRevenue
      centralStayedRoomRevenueTax
      centralTotalRevenue
      centralTotalRevenueTax
      contextCd
      dSI
      deletedFlag
      fBRevenue
      fBRevenueTax
      grpAverageDailyRate
      grpFBRevenue
      grpFBRevenueTax
      grpNumberCancels
      grpNumberNights
      grpNumberNumberShows
      grpNumberStays
      grpOtherRevenue
      grpOtherRevenueTax
      grpRoomRevenue
      grpRoomRevenueTax
      grpTotalRevenue
      grpTotalRevenueTax
      jRNUpdateDate
      jrnFilerba
      jrnFileseqno
      jrnFlag
      jrnScn
      jrnSlicingTs
      jrnUpdateDttm
      localCurrency
      locationID
      nameId
      nameType
      noShows
      numberCancels
      numberNights
      numberNoShows
      numberStays
      organizationID
      otherRevenue
      otherRevenueTax
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      roomRevenue
      roomRevenueTax
      stayDate
      stayMonth
      stayYear
      stayedAdr
      stayedCancels
      stayedFBRevenue
      stayedFBRevenueTax
      stayedGrpAverageDailyRate
      stayedGrpFBRevenue
      stayedGrpFBRevenueTax
      stayedGrpNumberCancels
      stayedGrpNumberNights
      stayedGrpNumberNumberShows
      stayedGrpNumberStays
      stayedGrpOtherRevenue
      stayedGrpOtherRevenueTax
      stayedGrpRoomRevenue
      stayedGrpRoomRevenueTax
      stayedGrpTotalRevenue
      stayedGrpTotalRevenueTax
      stayedNoShows
      stayedNumberCancels
      stayedNumberNights
      stayedNumberNoShows
      stayedNumberStays
      stayedOtherRevenue
      stayedOtherRevenueTax
      stayedRoomNights
      stayedRoomRevenue
      stayedRoomRevenueTax
      stayedStays
      stayedTotalAdr
      stayedTotalFbRevenue
      stayedTotalFbRevenueTax
      stayedTotalOtherRevenue
      stayedTotalOtherRevenueTax
      stayedTotalRevenue
      stayedTotalRevenueTax
      stayedTotalRoomRevenue
      stayedTotalRoomRevenueTax
      stayedTotalTotalRevenue
      stayedTotalTotalRevenueTax
      stays
      totalAdr
      totalFbRevenue
      totalFbRevenueTax
      totalNumberNights
      totalOtherRevenue
      totalOtherRevenueTax
      totalRevenue
      totalRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
    }
    contactMonthlyStatisticsDetails {
      adr
      bookedFBRevenue
      bookedRoomRevenue
      bookedRoomRevenueTax
      bookedStays
      cCcFBRevenue
      cCcFBRevenueTax
      cCcGroupFBRevenue
      cCcGroupFBRevenueTax
      cCcGroupMiscellaneousRevenue
      cCcGroupMiscellaneousRevenueTax
      cCcGroupOtherRevenue
      cCcGroupOtherRevenueTax
      cCcGroupRoomRevenue
      cCcGroupRoomRevenueTax
      cCcGroupTotalRevenue
      cCcGroupTotalRevenueTax
      cCcMiscellaneousRevenue
      cCcMiscellaneousRevenueTax
      cCcOtherRevenue
      cCcOtherRevenueTax
      cCcRoomRevenue
      cCcRoomRevenueTax
      cCcTotalRevenue
      cCcTotalRevenueTax
      cExchangeDate
      cExchangeRate
      cGroupFBRevenue
      cGroupFBRevenueTax
      cGroupOtherRevenue
      cGroupOtherRevenueTax
      cGroupRoomRevenue
      cGroupRoomRevenueTax
      cGroupTotalRevenue
      cGroupTotalRevenueTax
      cTotalFBRevenue
      cTotalFBRevenueTax
      cTotalOtherRevenue
      cTotalOtherRevenueTax
      cTotalRoomRevenue
      cTotalRoomRevenueTax
      cTotalTotalRevenue
      cTotalTotalRevenueTax
      ccFbRevenue
      ccFbRevenueTax
      ccGrpFBRevenue
      ccGrpFBRevenueTax
      ccGrpMiscellaneousRevenue
      ccGrpMiscellaneousRevenueTax
      ccGrpOtherRevenue
      ccGrpOtherRevenueTax
      ccGrpRoomRevenue
      ccGrpRoomRevenueTax
      ccGrpTotalRevenue
      ccGrpTotalRevenueTax
      ccMiscRevenue
      ccMiscRevenueTax
      ccOtherRevenue
      ccOtherRevenueTax
      ccRoomRevenue
      ccRoomRevenueTax
      ccTotalRevenue
      ccTotalRevenueTax
      centralBookedFBRevenue
      centralBookedFBRevenueTax
      centralBookedOtherRevenueTax
      centralCurrencyCode
      centralOtherRevenue
      centralStayedRoomRevenue
      centralStayedRoomRevenueTax
      centralStayedTotalRevenue
      centralTotalRevenueTax
      contextCd
      dSI
      deletedFlag
      grpAverageDailyRate
      grpFBRevenue
      grpFBRevenueTax
      grpNumberCancels
      grpNumberNights
      grpNumberNumberShows
      grpNumberStays
      grpOtherRevenue
      grpOtherRevenueTax
      grpRoomRevenue
      grpRoomRevenueTax
      grpTotalRevenue
      grpTotalRevenueTax
      insertDate
      insertUser
      jRNUpdateDate
      jrnFilerba
      jrnFileseqno
      jrnFlag
      jrnScn
      jrnSlicingTs
      jrnUpdateDttm
      localCurrency
      locationID
      nameId
      nameType
      organizationID
      otherRevenue
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      stayMonth
      stayYear
      stayedBooked
      stayedCancels
      stayedFBRevenueTax
      stayedNoShows
      stayedOtherRevenueTax
      stayedTotalRevenue
      totalAdr
      totalFbRevenue
      totalFbRevenueTax
      totalNumberCancels
      totalNumberNights
      totalNumberNoShows
      totalNumberStays
      totalOtherRevenue
      totalOtherRevenueTax
      totalRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
      updateDate
      updateUser
    }
    contactYearlyStatisticsDetails {
      adr
      bookedCancels
      bookedFBRevenueTax
      bookedNoShows
      bookedOtherRevenueTax
      cCcFBRevenue
      cCcFBRevenueTax
      cCcGroupFBRevenue
      cCcGroupFBRevenueTax
      cCcGroupMiscellaneousRevenue
      cCcGroupMiscellaneousRevenueTax
      cCcGroupOtherRevenue
      cCcGroupOtherRevenueTax
      cCcGroupRoomRevenue
      cCcGroupRoomRevenueTax
      cCcGroupTotalRevenue
      cCcGroupTotalRevenueTax
      cCcMiscellaneousRevenue
      cCcMiscellaneousRevenueTax
      cCcOtherRevenue
      cCcOtherRevenueTax
      cCcRoomRevenue
      cCcRoomRevenueTax
      cCcTotalRevenue
      cCcTotalRevenueTax
      cExchangeDate
      cExchangeRate
      cGroupFBRevenue
      cGroupFBRevenueTax
      cGroupOtherRevenue
      cGroupOtherRevenueTax
      cGroupRoomRevenue
      cGroupRoomRevenueTax
      cGroupTotalRevenue
      cGroupTotalRevenueTax
      cTotalFBRevenue
      cTotalFBRevenueTax
      cTotalOtherRevenue
      cTotalOtherRevenueTax
      cTotalRoomRevenue
      cTotalRoomRevenueTax
      cTotalTotalRevenue
      cTotalTotalRevenueTax
      ccFbRevenue
      ccFbRevenueTax
      ccGrpFBRevenue
      ccGrpFBRevenueTax
      ccGrpMiscellaneousRevenue
      ccGrpMiscellaneousRevenueTax
      ccGrpOtherRevenue
      ccGrpOtherRevenueTax
      ccGrpRoomRevenue
      ccGrpRoomRevenueTax
      ccGrpTotalRevenue
      ccGrpTotalRevenueTax
      ccMiscRevenue
      ccMiscRevenueTax
      ccOtherRevenue
      ccOtherRevenueTax
      ccRoomRevenue
      ccRoomRevenueTax
      ccTotalRevenue
      ccTotalRevenueTax
      centralBookedRoomRevenueTax
      centralBookedTotalRevenueTax
      centralCurrencyCode
      centralFBRevenue
      centralFBRevenueTax
      centralOtherRevenue
      centralRoomRevenue
      centralRoomRevenueTax
      centralStayedOtherRevenueTax
      centralStayedTotalRevenue
      contextCd
      dSI
      deletedFlag
      fBRevenue
      grpAverageDailyRate
      grpFBRevenue
      grpFBRevenueTax
      grpNumberCancels
      grpNumberNights
      grpNumberNumberShows
      grpNumberStays
      grpOtherRevenue
      grpOtherRevenueTax
      grpRoomRevenue
      grpRoomRevenueTax
      grpTotalRevenue
      grpTotalRevenueTax
      insertDate
      insertUser
      jRNUpdateDate
      jrnFilerba
      jrnFileseqno
      jrnFlag
      jrnScn
      jrnSlicingTs
      jrnUpdateDttm
      localCurrency
      locationID
      nameId
      nameType
      organizationID
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomRevenue
      roomRevenueTax
      stayYear
      stayedOtherRevenue
      stayedRoomNights
      stayedTotalRevenue
      stayedTotalRevenueTax
      stays
      totalAdr
      totalFbRevenue
      totalFbRevenueTax
      totalNumberCancels
      totalNumberNights
      totalNumberNoShows
      totalNumberStays
      totalOtherRevenue
      totalOtherRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneYn': pl.Utf8,
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
    'updateUser': pl.Utf8,
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
```python
profile_address_details_schema = {
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressID': pl.Float64,
    'addressLanguage': pl.Utf8,
    'addressLanguageDescription': pl.Utf8,
    'addressType': pl.Utf8,
    'addressTypeDesc': pl.Utf8,
    'barcode': pl.Utf8,
    'beginDate': pl.Utf8,
    'centralState': pl.Utf8,
    'centralStateDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cleansedDatetime': pl.Utf8,
    'cleansedErrormsg': pl.Utf8,
    'cleansedMatchstatus': pl.Utf8,
    'cleansedStatus': pl.Utf8,
    'cleansedValidationstatus': pl.Utf8,
    'clientID': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Float64,
    'deletedYN': pl.Utf8,
    'endDate': pl.Utf8,
    'firstName': pl.Utf8,
    'foreignCountry': pl.Utf8,
    'inCareOf': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastUpdatedResort': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Float64,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profileAddressId': pl.Float64,
    'profileId': pl.Float64,
    'profileIdx': pl.Float64,
    'province': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
profile_communication_details_schema = {
    'addressId': pl.Float64,
    'beginDate': pl.Utf8,
    'chainCode': pl.Utf8,
    'communicationID': pl.Float64,
    'communicationRole': pl.Utf8,
    'communicationValue': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryDialingCode': pl.Float64,
    'countryId': pl.Utf8,
    'dSI': pl.Float64,
    'defaultMethodYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'displaySequence': pl.Float64,
    'emailFormat': pl.Utf8,
    'emailLanguage': pl.Utf8,
    'endDate': pl.Utf8,
    'extension': pl.Utf8,
    'firstName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'indexPhone': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastName': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'organizationID': pl.Float64,
    'phoneId': pl.Float64,
    'phoneType': pl.Utf8,
    'phoneTypeDescription': pl.Utf8,
    'phoneTypeId': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profileID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'shareEmailYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'validYn': pl.Utf8,
}
```
```python
profile_preference_details_schema = {
    'canDeleteYn': pl.Utf8,
    'centralPreferenceCode': pl.Utf8,
    'centralPreferenceDescription': pl.Utf8,
    'centralPreferenceGroup': pl.Utf8,
    'chainCode': pl.Utf8,
    'chargeYn': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'displaySequence': pl.Float64,
    'externalPreferenceId': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'mpcode': pl.Utf8,
    'nameId': pl.Float64,
    'noteProperty': pl.Utf8,
    'organizationID': pl.Float64,
    'preferenceCode': pl.Utf8,
    'preferenceDescription': pl.Utf8,
    'preferenceGroup': pl.Utf8,
    'preferenceId': pl.Utf8,
    'preferenceTypeCode': pl.Utf8,
    'preferenceTypeId': pl.Utf8,
    'preferenceValue': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'profileId': pl.Float64,
    'profilePreferenceId': pl.Utf8,
    'property': pl.Utf8,
    'repOrderby': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
profile_membership_details_schema = {
    'cCreditLimit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'creditLimit': pl.Float64,
    'currentPoints': pl.Float64,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'deviceCode': pl.Utf8,
    'deviceDisableDate': pl.Utf8,
    'earningPreference': pl.Utf8,
    'enrollmentCode': pl.Utf8,
    'enrollmentProperty': pl.Utf8,
    'enrollmentSource': pl.Utf8,
    'excludeFromBatch': pl.Utf8,
    'expirationDate': pl.Utf8,
    'gracePeriodIndicator': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Utf8,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'joinedDate': pl.Utf8,
    'mbrprefChangedDate': pl.Utf8,
    'memberIndicator': pl.Utf8,
    'memberSubtype': pl.Utf8,
    'membergueststatusid': pl.Utf8,
    'membershipActiveYN': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipID': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipLevelDescription': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipStatus': pl.Utf8,
    'membershipType': pl.Utf8,
    'membershipTypeDescription': pl.Utf8,
    'membershipenrollid': pl.Utf8,
    'membershiplevelid': pl.Utf8,
    'membershiptypeid': pl.Utf8,
    'nameId': pl.Float64,
    'nameOnCard': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Float64,
    'partnerMembershipId': pl.Float64,
    'pointflag': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryMembershipYN': pl.Utf8,
    'primaryairlineflag': pl.Utf8,
    'processExpirationDate': pl.Utf8,
    'profileid': pl.Float64,
    'ranking': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'trackData': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Utf8,
}
```
```python
profile_note_details_schema = {
    'activityDueDate': pl.Utf8,
    'activityType': pl.Utf8,
    'chainCode': pl.Utf8,
    'confidentialYN': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'externalNoteId': pl.Utf8,
    'globalNoteYn': pl.Utf8,
    'globalYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'noteCode': pl.Utf8,
    'noteCodeDescription': pl.Utf8,
    'noteId': pl.Float64,
    'noteInternalYN': pl.Utf8,
    'noteTitle': pl.Utf8,
    'notes': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'profileId': pl.Float64,
    'profileNoteId': pl.Float64,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
profile_relationship_details_schema = {
    'chainCode': pl.Utf8,
    'company': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fromProfileID': pl.Float64,
    'guestName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalRelationshipId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profilerelationshipId': pl.Float64,
    'property': pl.Utf8,
    'relationshipCode': pl.Utf8,
    'relationshipDescription': pl.Utf8,
    'relationshipID': pl.Float64,
    'relationshipRole': pl.Utf8,
    'relationshipTo': pl.Utf8,
    'relationshipToNameID': pl.Float64,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toProfileID': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
profile_owner_details_schema = {
    'accountOwner': pl.Utf8,
    'accountOwnerCode': pl.Utf8,
    'accountOwnerEmail': pl.Utf8,
    'accountOwnerPhone': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountSrepCode': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationId': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profileOwnerId': pl.Float64,
    'property': pl.Utf8,
    'relationship': pl.Utf8,
    'relationshipid': pl.Utf8,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'userId': pl.Float64,
}
```
```python
contact_daily_statistics_details_schema = {
    'bookedAdr': pl.Float64,
    'bookedCancels': pl.Float64,
    'bookedFBRevenue': pl.Float64,
    'bookedFBRevenueTax': pl.Float64,
    'bookedGrpAverageDailyRate': pl.Float64,
    'bookedGrpFBRevenue': pl.Float64,
    'bookedGrpFBRevenueTax': pl.Float64,
    'bookedGrpNumberCancels': pl.Float64,
    'bookedGrpNumberNights': pl.Float64,
    'bookedGrpNumberNumberShows': pl.Float64,
    'bookedGrpNumberStays': pl.Float64,
    'bookedGrpOtherRevenue': pl.Float64,
    'bookedGrpOtherRevenueTax': pl.Float64,
    'bookedGrpRoomRevenue': pl.Float64,
    'bookedGrpRoomRevenueTax': pl.Float64,
    'bookedGrpTotalRevenue': pl.Float64,
    'bookedGrpTotalRevenueTax': pl.Float64,
    'bookedNoShows': pl.Float64,
    'bookedNumberCancels': pl.Float64,
    'bookedNumberNights': pl.Float64,
    'bookedNumberNoShows': pl.Float64,
    'bookedNumberStays': pl.Float64,
    'bookedOtherRevenue': pl.Float64,
    'bookedOtherRevenueTax': pl.Float64,
    'bookedRoomNights': pl.Float64,
    'bookedRoomRevenue': pl.Float64,
    'bookedRoomRevenueTax': pl.Float64,
    'bookedStays': pl.Float64,
    'bookedTotalAdr': pl.Float64,
    'bookedTotalFbRevenue': pl.Float64,
    'bookedTotalFbRevenueTax': pl.Float64,
    'bookedTotalOtherRevenue': pl.Float64,
    'bookedTotalOtherRevenueTax': pl.Float64,
    'bookedTotalRevenue': pl.Float64,
    'bookedTotalRevenueTax': pl.Float64,
    'bookedTotalRoomRevenue': pl.Float64,
    'bookedTotalRoomRevenueTax': pl.Float64,
    'bookedTotalTotalRevenue': pl.Float64,
    'bookedTotalTotalRevenueTax': pl.Float64,
    'cBookedGroupFBRevenue': pl.Float64,
    'cBookedGroupFBRevenueTax': pl.Float64,
    'cBookedGroupOtherRevenue': pl.Float64,
    'cBookedGroupOtherRevenueTax': pl.Float64,
    'cBookedGroupRoomRevenue': pl.Float64,
    'cBookedGroupRoomRevenueTax': pl.Float64,
    'cBookedGroupTotalRevenue': pl.Float64,
    'cBookedGroupTotalRevenueTax': pl.Float64,
    'cBookedTotalFBRevenue': pl.Float64,
    'cBookedTotalFBRevenueTax': pl.Float64,
    'cBookedTotalOtherRevenue': pl.Float64,
    'cBookedTotalOtherRevenueTax': pl.Float64,
    'cBookedTotalRoomRevenue': pl.Float64,
    'cBookedTotalRoomRevenueTax': pl.Float64,
    'cBookedTotalTotalRevenue': pl.Float64,
    'cBookedTotalTotalRevenueTax': pl.Float64,
    'cStayedGroupFBRevenue': pl.Float64,
    'cStayedGroupFBRevenueTax': pl.Float64,
    'cStayedGroupOtherRevenue': pl.Float64,
    'cStayedGroupOtherRevenueTax': pl.Float64,
    'cStayedGroupRoomRevenue': pl.Float64,
    'cStayedGroupRoomRevenueTax': pl.Float64,
    'cStayedGroupTotalRevenue': pl.Float64,
    'cStayedGroupTotalRevenueTax': pl.Float64,
    'cStayedTotalFBRevenue': pl.Float64,
    'cStayedTotalFBRevenueTax': pl.Float64,
    'cStayedTotalOtherRevenue': pl.Float64,
    'cStayedTotalOtherRevenueTax': pl.Float64,
    'cStayedTotalRevenue': pl.Float64,
    'cStayedTotalRevenueTax': pl.Float64,
    'cStayedTotalRoomRevenue': pl.Float64,
    'cStayedTotalRoomRevenueTax': pl.Float64,
    'cStayedTotalTotalRevenue': pl.Float64,
    'cStayedTotalTotalRevenueTax': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenue': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRevenue': pl.Float64,
    'cTotalRevenueTax': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cancels': pl.Float64,
    'centralBookedFBRevenue': pl.Float64,
    'centralBookedFBRevenueTax': pl.Float64,
    'centralBookedOtherRevenue': pl.Float64,
    'centralBookedOtherRevenueTax': pl.Float64,
    'centralBookedRoomRevenue': pl.Float64,
    'centralBookedRoomRevenueTax': pl.Float64,
    'centralBookedTotalRevenue': pl.Float64,
    'centralBookedTotalRevenueTax': pl.Float64,
    'centralFBRevenue': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralOtherRevenueTax': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralStayedFBRevenue': pl.Float64,
    'centralStayedFBRevenueTax': pl.Float64,
    'centralStayedOtherRevenue': pl.Float64,
    'centralStayedOtherRevenueTax': pl.Float64,
    'centralStayedRoomRevenue': pl.Float64,
    'centralStayedRoomRevenueTax': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRevenueTax': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fBRevenueTax': pl.Float64,
    'grpAverageDailyRate': pl.Float64,
    'grpFBRevenue': pl.Float64,
    'grpFBRevenueTax': pl.Float64,
    'grpNumberCancels': pl.Float64,
    'grpNumberNights': pl.Float64,
    'grpNumberNumberShows': pl.Float64,
    'grpNumberStays': pl.Float64,
    'grpOtherRevenue': pl.Float64,
    'grpOtherRevenueTax': pl.Float64,
    'grpRoomRevenue': pl.Float64,
    'grpRoomRevenueTax': pl.Float64,
    'grpTotalRevenue': pl.Float64,
    'grpTotalRevenueTax': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jrnFilerba': pl.Float64,
    'jrnFileseqno': pl.Float64,
    'jrnFlag': pl.Utf8,
    'jrnScn': pl.Float64,
    'jrnSlicingTs': pl.Utf8,
    'jrnUpdateDttm': pl.Utf8,
    'localCurrency': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'noShows': pl.Float64,
    'numberCancels': pl.Float64,
    'numberNights': pl.Float64,
    'numberNoShows': pl.Float64,
    'numberStays': pl.Float64,
    'organizationID': pl.Float64,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayDate': pl.Utf8,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'stayedAdr': pl.Float64,
    'stayedCancels': pl.Float64,
    'stayedFBRevenue': pl.Float64,
    'stayedFBRevenueTax': pl.Float64,
    'stayedGrpAverageDailyRate': pl.Float64,
    'stayedGrpFBRevenue': pl.Float64,
    'stayedGrpFBRevenueTax': pl.Float64,
    'stayedGrpNumberCancels': pl.Float64,
    'stayedGrpNumberNights': pl.Float64,
    'stayedGrpNumberNumberShows': pl.Float64,
    'stayedGrpNumberStays': pl.Float64,
    'stayedGrpOtherRevenue': pl.Float64,
    'stayedGrpOtherRevenueTax': pl.Float64,
    'stayedGrpRoomRevenue': pl.Float64,
    'stayedGrpRoomRevenueTax': pl.Float64,
    'stayedGrpTotalRevenue': pl.Float64,
    'stayedGrpTotalRevenueTax': pl.Float64,
    'stayedNoShows': pl.Float64,
    'stayedNumberCancels': pl.Float64,
    'stayedNumberNights': pl.Float64,
    'stayedNumberNoShows': pl.Float64,
    'stayedNumberStays': pl.Float64,
    'stayedOtherRevenue': pl.Float64,
    'stayedOtherRevenueTax': pl.Float64,
    'stayedRoomNights': pl.Float64,
    'stayedRoomRevenue': pl.Float64,
    'stayedRoomRevenueTax': pl.Float64,
    'stayedStays': pl.Float64,
    'stayedTotalAdr': pl.Float64,
    'stayedTotalFbRevenue': pl.Float64,
    'stayedTotalFbRevenueTax': pl.Float64,
    'stayedTotalOtherRevenue': pl.Float64,
    'stayedTotalOtherRevenueTax': pl.Float64,
    'stayedTotalRevenue': pl.Float64,
    'stayedTotalRevenueTax': pl.Float64,
    'stayedTotalRoomRevenue': pl.Float64,
    'stayedTotalRoomRevenueTax': pl.Float64,
    'stayedTotalTotalRevenue': pl.Float64,
    'stayedTotalTotalRevenueTax': pl.Float64,
    'stays': pl.Float64,
    'totalAdr': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
    'totalNumberNights': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueTax': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueTax': pl.Float64,
    'totalTotalRevenue': pl.Float64,
    'totalTotalRevenueTax': pl.Float64,
}
```
```python
contact_monthly_statistics_details_schema = {
    'adr': pl.Float64,
    'bookedFBRevenue': pl.Float64,
    'bookedRoomRevenue': pl.Float64,
    'bookedRoomRevenueTax': pl.Float64,
    'bookedStays': pl.Float64,
    'cCcFBRevenue': pl.Float64,
    'cCcFBRevenueTax': pl.Float64,
    'cCcGroupFBRevenue': pl.Float64,
    'cCcGroupFBRevenueTax': pl.Float64,
    'cCcGroupMiscellaneousRevenue': pl.Float64,
    'cCcGroupMiscellaneousRevenueTax': pl.Float64,
    'cCcGroupOtherRevenue': pl.Float64,
    'cCcGroupOtherRevenueTax': pl.Float64,
    'cCcGroupRoomRevenue': pl.Float64,
    'cCcGroupRoomRevenueTax': pl.Float64,
    'cCcGroupTotalRevenue': pl.Float64,
    'cCcGroupTotalRevenueTax': pl.Float64,
    'cCcMiscellaneousRevenue': pl.Float64,
    'cCcMiscellaneousRevenueTax': pl.Float64,
    'cCcOtherRevenue': pl.Float64,
    'cCcOtherRevenueTax': pl.Float64,
    'cCcRoomRevenue': pl.Float64,
    'cCcRoomRevenueTax': pl.Float64,
    'cCcTotalRevenue': pl.Float64,
    'cCcTotalRevenueTax': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGroupFBRevenue': pl.Float64,
    'cGroupFBRevenueTax': pl.Float64,
    'cGroupOtherRevenue': pl.Float64,
    'cGroupOtherRevenueTax': pl.Float64,
    'cGroupRoomRevenue': pl.Float64,
    'cGroupRoomRevenueTax': pl.Float64,
    'cGroupTotalRevenue': pl.Float64,
    'cGroupTotalRevenueTax': pl.Float64,
    'cTotalFBRevenue': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenue': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRoomRevenue': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cTotalTotalRevenue': pl.Float64,
    'cTotalTotalRevenueTax': pl.Float64,
    'ccFbRevenue': pl.Float64,
    'ccFbRevenueTax': pl.Float64,
    'ccGrpFBRevenue': pl.Float64,
    'ccGrpFBRevenueTax': pl.Float64,
    'ccGrpMiscellaneousRevenue': pl.Float64,
    'ccGrpMiscellaneousRevenueTax': pl.Float64,
    'ccGrpOtherRevenue': pl.Float64,
    'ccGrpOtherRevenueTax': pl.Float64,
    'ccGrpRoomRevenue': pl.Float64,
    'ccGrpRoomRevenueTax': pl.Float64,
    'ccGrpTotalRevenue': pl.Float64,
    'ccGrpTotalRevenueTax': pl.Float64,
    'ccMiscRevenue': pl.Float64,
    'ccMiscRevenueTax': pl.Float64,
    'ccOtherRevenue': pl.Float64,
    'ccOtherRevenueTax': pl.Float64,
    'ccRoomRevenue': pl.Float64,
    'ccRoomRevenueTax': pl.Float64,
    'ccTotalRevenue': pl.Float64,
    'ccTotalRevenueTax': pl.Float64,
    'centralBookedFBRevenue': pl.Float64,
    'centralBookedFBRevenueTax': pl.Float64,
    'centralBookedOtherRevenueTax': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralOtherRevenue': pl.Float64,
    'centralStayedRoomRevenue': pl.Float64,
    'centralStayedRoomRevenueTax': pl.Float64,
    'centralStayedTotalRevenue': pl.Float64,
    'centralTotalRevenueTax': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'grpAverageDailyRate': pl.Float64,
    'grpFBRevenue': pl.Float64,
    'grpFBRevenueTax': pl.Float64,
    'grpNumberCancels': pl.Float64,
    'grpNumberNights': pl.Float64,
    'grpNumberNumberShows': pl.Float64,
    'grpNumberStays': pl.Float64,
    'grpOtherRevenue': pl.Float64,
    'grpOtherRevenueTax': pl.Float64,
    'grpRoomRevenue': pl.Float64,
    'grpRoomRevenueTax': pl.Float64,
    'grpTotalRevenue': pl.Float64,
    'grpTotalRevenueTax': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jrnFilerba': pl.Float64,
    'jrnFileseqno': pl.Float64,
    'jrnFlag': pl.Utf8,
    'jrnScn': pl.Float64,
    'jrnSlicingTs': pl.Utf8,
    'jrnUpdateDttm': pl.Utf8,
    'localCurrency': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'organizationID': pl.Float64,
    'otherRevenue': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'stayedBooked': pl.Utf8,
    'stayedCancels': pl.Float64,
    'stayedFBRevenueTax': pl.Float64,
    'stayedNoShows': pl.Float64,
    'stayedOtherRevenueTax': pl.Float64,
    'stayedTotalRevenue': pl.Float64,
    'totalAdr': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
    'totalNumberCancels': pl.Float64,
    'totalNumberNights': pl.Float64,
    'totalNumberNoShows': pl.Float64,
    'totalNumberStays': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueTax': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueTax': pl.Float64,
    'totalTotalRevenue': pl.Float64,
    'totalTotalRevenueTax': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
contact_yearly_statistics_details_schema = {
    'adr': pl.Float64,
    'bookedCancels': pl.Float64,
    'bookedFBRevenueTax': pl.Float64,
    'bookedNoShows': pl.Float64,
    'bookedOtherRevenueTax': pl.Float64,
    'cCcFBRevenue': pl.Float64,
    'cCcFBRevenueTax': pl.Float64,
    'cCcGroupFBRevenue': pl.Float64,
    'cCcGroupFBRevenueTax': pl.Float64,
    'cCcGroupMiscellaneousRevenue': pl.Float64,
    'cCcGroupMiscellaneousRevenueTax': pl.Float64,
    'cCcGroupOtherRevenue': pl.Float64,
    'cCcGroupOtherRevenueTax': pl.Float64,
    'cCcGroupRoomRevenue': pl.Float64,
    'cCcGroupRoomRevenueTax': pl.Float64,
    'cCcGroupTotalRevenue': pl.Float64,
    'cCcGroupTotalRevenueTax': pl.Float64,
    'cCcMiscellaneousRevenue': pl.Float64,
    'cCcMiscellaneousRevenueTax': pl.Float64,
    'cCcOtherRevenue': pl.Float64,
    'cCcOtherRevenueTax': pl.Float64,
    'cCcRoomRevenue': pl.Float64,
    'cCcRoomRevenueTax': pl.Float64,
    'cCcTotalRevenue': pl.Float64,
    'cCcTotalRevenueTax': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGroupFBRevenue': pl.Float64,
    'cGroupFBRevenueTax': pl.Float64,
    'cGroupOtherRevenue': pl.Float64,
    'cGroupOtherRevenueTax': pl.Float64,
    'cGroupRoomRevenue': pl.Float64,
    'cGroupRoomRevenueTax': pl.Float64,
    'cGroupTotalRevenue': pl.Float64,
    'cGroupTotalRevenueTax': pl.Float64,
    'cTotalFBRevenue': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenue': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRoomRevenue': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cTotalTotalRevenue': pl.Float64,
    'cTotalTotalRevenueTax': pl.Float64,
    'ccFbRevenue': pl.Float64,
    'ccFbRevenueTax': pl.Float64,
    'ccGrpFBRevenue': pl.Float64,
    'ccGrpFBRevenueTax': pl.Float64,
    'ccGrpMiscellaneousRevenue': pl.Float64,
    'ccGrpMiscellaneousRevenueTax': pl.Float64,
    'ccGrpOtherRevenue': pl.Float64,
    'ccGrpOtherRevenueTax': pl.Float64,
    'ccGrpRoomRevenue': pl.Float64,
    'ccGrpRoomRevenueTax': pl.Float64,
    'ccGrpTotalRevenue': pl.Float64,
    'ccGrpTotalRevenueTax': pl.Float64,
    'ccMiscRevenue': pl.Float64,
    'ccMiscRevenueTax': pl.Float64,
    'ccOtherRevenue': pl.Float64,
    'ccOtherRevenueTax': pl.Float64,
    'ccRoomRevenue': pl.Float64,
    'ccRoomRevenueTax': pl.Float64,
    'ccTotalRevenue': pl.Float64,
    'ccTotalRevenueTax': pl.Float64,
    'centralBookedRoomRevenueTax': pl.Utf8,
    'centralBookedTotalRevenueTax': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralStayedOtherRevenueTax': pl.Float64,
    'centralStayedTotalRevenue': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenue': pl.Float64,
    'grpAverageDailyRate': pl.Float64,
    'grpFBRevenue': pl.Float64,
    'grpFBRevenueTax': pl.Float64,
    'grpNumberCancels': pl.Float64,
    'grpNumberNights': pl.Float64,
    'grpNumberNumberShows': pl.Float64,
    'grpNumberStays': pl.Float64,
    'grpOtherRevenue': pl.Float64,
    'grpOtherRevenueTax': pl.Float64,
    'grpRoomRevenue': pl.Float64,
    'grpRoomRevenueTax': pl.Float64,
    'grpTotalRevenue': pl.Float64,
    'grpTotalRevenueTax': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jrnFilerba': pl.Float64,
    'jrnFileseqno': pl.Float64,
    'jrnFlag': pl.Utf8,
    'jrnScn': pl.Float64,
    'jrnSlicingTs': pl.Utf8,
    'jrnUpdateDttm': pl.Utf8,
    'localCurrency': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayYear': pl.Float64,
    'stayedOtherRevenue': pl.Float64,
    'stayedRoomNights': pl.Float64,
    'stayedTotalRevenue': pl.Float64,
    'stayedTotalRevenueTax': pl.Float64,
    'stays': pl.Float64,
    'totalAdr': pl.Float64,
    'totalFbRevenue': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
    'totalNumberCancels': pl.Float64,
    'totalNumberNights': pl.Float64,
    'totalNumberNoShows': pl.Float64,
    'totalNumberStays': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueTax': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueTax': pl.Float64,
    'totalTotalRevenue': pl.Float64,
    'totalTotalRevenueTax': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```