# ProfilesCommunications
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesCommunications`
> All associated communication details including communication types and roles which can be associated with the proper profile and profile type.
  
**Return:** [`[ProfilesCommunicationsType]`](#profilescommunicationstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesCommunicationsQueryArgumentsType!`](#profilescommunicationsqueryargumentstype) |  |

## Object Types

### ProfilesCommunicationsType

| Field | Type | Description |
| --- | --- | --- |
| profileCommunicationDetails | [`ProfilesCommunicationsProfileCommunicationDetailsType`](#profilescommunicationsprofilecommunicationdetailstype) | Profile Communication Details |
| profileInformationDetails | [`ProfilesCommunicationsProfileInformationDetailsType`](#profilescommunicationsprofileinformationdetailstype) | Profile Details |
| profilesCommunicationsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesCommunicationsProfileCommunicationDetailsType

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

### ProfilesCommunicationsProfileInformationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRNumber | `String` | AR Number |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerCode | `String` | Account Owner Code |
| accountPhonePrimary | `String` | Phone no. |
| accountSource | `String` | Account Source |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| accountsourceDesc | `String` | Accountsource Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressId | `Float` | Address ID |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allOwners | `String` | All Owners |
| allResorts | `String` | All Resorts |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| anonymizationDate | `Date` | System Date when the guest was anonymized in OPERA. |
| anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
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
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessSegement | `String` | Business Segement |
| businessTitle | `String` | Business Title |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | The unique identifier of the CRS |
| cashBlInd | `String` | Cash Bl Individual |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralIATANumber | `String` | Central IATA Number |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralSourceOwnerTitle | `String` | Central Source Owner Title |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| commissionCode | `String` | Commission Code |
| commissionCodes | `String` | Commission Codes |
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
| compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| company | `String` | Company |
| companyGroupId | `String` | Linked internal ID for booker. |
| companyNameId | `Float` | Company Name ID |
| competitionCode | `String` | Competition Code |
| competitionDesc | `String` | Competition Description |
| contactFlag | `String` | Contact Flag |
| contactOwnerCode | `String` | Contact Owner Code |
| contractNo | `String` | Contract Number (used for customers). |
| contractRecvDate | `Date` | The date the group contract was received. |
| corpID | `String` | Corp ID |
| corpTypeDesc | `String` | Corp Type Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryDesc | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| decimalPositions | `Float` | Decimal Positions |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Department |
| deptId | `String` | Dept ID |
| directBillBatchType | `String` | Direct Bill Batch Type |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
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
| fMembershipType | `String` | F Membership Type |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Gender |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
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
| inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| incognitoFirstName | `String` | Incognito First Name |
| incognitoLastName | `String` | Incognito Last Name |
| indexName | `String` | Index Name |
| industryCode | `String` | Industry Code |
| industryDesc | `String` | Industry Description |
| influence | `String` | Influence |
| influenceDesc | `String` | Influence Description |
| insertUserId | `Float` | Insert User ID |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| laptopChange | `Float` | Laptop Change |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRateCode | `String` | Last Rate Code |
| lastRoom | `String` | Not used. |
| lastRoomResort | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailActionCodes | `String` | Mail Action Codes |
| mailActionDesc | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| marketsDesc | `String` | Markets Description |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| middle | `String` | Middle |
| name | `String` | Name |
| nameComment | `String` | Not Used. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| nameTypeDescription | `String` | Name Type Description |
| nameWithTitle | `String` | Name With Title |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| passport | `String` | Passport |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| paymentMethodsCode | `String` | Payment Methods Code |
| paymentMethodsDesc | `String` | Payment Methods Description |
| phoneWeb | `String` | Phone Web |
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
| priorityDesc | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| productInterestCodes | `String` | Product Interest Codes |
| profession | `String` | Profession of the guest |
| profileArrCodes | `String` | Profile Arrangement Codes |
| profileArrangementDesc | `String` | Profile Arr Description |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileLanguage | `String` | Profile Language |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| protected | `String` | Protected |
| province | `String` | Province |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | Region |
| regionid | `String` | Regionid |
| repAccountType | `String` | Rep Account Type |
| repAccountsource | `String` | Reporting Accountsource |
| repCompetitionCode | `String` | Reporting Competition Code |
| repIataCompType | `String` | Rep IATA Comp Type |
| repIndustryCode | `String` | Reporting Industry Code |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Reporting Mail Action Codes |
| repMarkets | `String` | Reporting Markets |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repStateDescription | `String` | Reporting State Desc |
| repTaxType | `String` | Reporting Tax Type |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restrictedRule | `String` | Restricted Rule |
| resvContact | `String` | Reservation Contact person. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotentialDesc | `String` | Rooms Potential Description |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDesc | `String` | Scope City Description |
| scopeDesc | `String` | Scope Description |
| sfirst | `String` | Uppercase value of First Name. |
| smsYn | `String` | Use this alert to text a notification. |
| sname | `String` | The Uppercase value of Last or Company. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| sourceOwnerTitle | `String` | Source Owner Title |
| state | `String` | State |
| stateDesc | `String` | State Description of the Guest of Payee |
| stateDescription | `String` | State Description |
| suffix | `String` | Suffix |
| summRefCc | `String` | Summ Ref Cc |
| summRefCurrencyId | `String` | Summ Ref Curr ID |
| superSearchIndexText | `String` | Super Search Index Text |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| taxTypeDesc | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDesc | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| titleName | `String` | Title Name |
| titleSuffix | `Float` | Title Suffix |
| topAccountID | `Float` | Top Account ID |
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
| tracecodeDesc | `String` | Tracecode Description |
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
| updateUserId | `Float` | Update User ID |
| uploadDate | `Date` | Upload Date |
| vendorId | `Float` | Vendor ID |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
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

### ProfilesCommunicationsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| profilecommunicationDetailsAddressId | `FloatInput` | Not used. |
| profilecommunicationDetailsBeginDate | `DateInput` | Not used. |
| profilecommunicationDetailsChainCode | `StringInput!` | The Chain code of the chain for which this record belongs to.<br>`@mandatoryInput` |
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
| profileDetailsActiveYn | `StringInput` | Active Flag |
| profileDetailsAnonymizationStatus | `StringInput` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| profileDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| profileDetailsCompany | `StringInput` | Company |
| profileDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |
| profileDetailsContactFlag | `StringInput` | Contact Flag |
| profileDetailsSrepCode | `StringInput` | Contact Owner Code |
| profileDetailsNameCode | `StringInput` | Corp ID |
| profileDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| profileDetailsHistoryYn | `StringInput` | History Y/N |
| profileDetailsInactiveDate | `DateInput` | Inactive Date |
| profileDetailsIndexName | `StringInput` | Index Name |
| profileDetailsOrganizationId | `FloatInput` | Organization ID |
| profileDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileDetailsLast | `StringInput` | Last |
| profileDetailsNameId | `FloatInput` | Name ID |
| profileDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileDetailsProfileType | `StringInput` | Profile Type |
| profileDetailsNameType | `StringInput` | Profile Type Code |
| profileDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileDetailsProfileId | `FloatInput` | Top Account ID |
| profileDetailsUpdateDate | `DateTimeInput` | Update Date |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesCommunications($input: ProfilesCommunicationsQueryArgumentsType!) {
  profilesCommunications(input: $input) @stream {
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
    profileInformationDetails {
      aRCreditLimitYN
      aRNumber
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountEmailPrimary
      accountName
      accountName2
      accountName3
      accountOwnerCode
      accountPhonePrimary
      accountSource
      accountType
      accountTypeDescription
      accountsourceDesc
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressId
      addressLangCodeDesc
      addressLanguageCode
      addressType
      alienRegistrationNo
      allOwners
      allResorts
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      anonymizationDate
      anonymizationStatus
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
      blMsg
      businessPotential
      businessSegement
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      cashBlInd
      ccProfileYn
      centralAccountSourceDescription
      centralAccountTypeDescription
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralCompetitionCodeDescription
      centralCorporateTypeDescription
      centralIATANumber
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCodeDescription
      centralKeyword
      centralMailActionDescription
      centralPriority
      centralPriorityDescription
      centralProfileTypeDescription
      centralScopeCityDescription
      centralScopeDescription
      centralSourceOwnerTitle
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      collectionUserId
      combinedName
      commPayCentral
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
      compPreApprovalRequiredYn
      company
      companyGroupId
      companyNameId
      competitionCode
      competitionDesc
      contactFlag
      contactOwnerCode
      contractNo
      contractRecvDate
      corpID
      corpTypeDesc
      corporateType
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
      decimalPositions
      deletedFlag
      department
      deptId
      directBillBatchType
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      emailYn
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
      faxNo
      first
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestPrivYn
      historyYn
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
      inactiveReasonCode
      inactiveReasonDescription
      includeInTax1099Yn
      incognitoFirstName
      incognitoLastName
      indexName
      industryCode
      industryDesc
      influence
      influenceDesc
      insertUserId
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      laptopChange
      last
      lastGroup
      lastRate
      lastRateCode
      lastRoom
      lastRoomResort
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailActionCodes
      mailActionDesc
      mailList
      mailType
      mailYn
      marketResearchYn
      marketsDesc
      masterAccountYn
      middle
      name
      nameComment
      nameId
      nameTaxType
      nameTypeDescription
      nameWithTitle
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      origNameId
      passport
      paymentDueDays
      paymentMethodsCode
      paymentMethodsDesc
      phoneWeb
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
      priorityDesc
      productInterest
      productInterestCodes
      profession
      profileArrCodes
      profileArrangementDesc
      profileCreditLimit
      profileLanguage
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      protected
      province
      psuedoProfileYn
      rateStructure
      region
      regionid
      repAccountType
      repAccountsource
      repCompetitionCode
      repIataCompType
      repIndustryCode
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMarkets
      repNationalityCode
      repNationalityDescription
      repRoomsPotential
      repScope
      repScopeCity
      repStateDescription
      repTaxType
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      repeatGuestId
      replaceAddress
      resortRegistered
      restrictedRule
      resvContact
      rnaInsertDate
      rnaUpdateDate
      roomsPotentialDesc
      salutation
      scope
      scopeCity
      scopeCityDesc
      scopeDesc
      sfirst
      smsYn
      sname
      soundExCompany
      soundExLast
      sourceOwnerTitle
      state
      stateDesc
      stateDescription
      suffix
      summRefCc
      summRefCurrencyId
      superSearchIndexText
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxExemptStatus
      taxOffice
      taxType
      taxTypeDesc
      territory
      territoryDesc
      thirdPartyYn
      titleName
      titleSuffix
      topAccountID
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
      updateUserId
      uploadDate
      vendorId
      vendorSiteId
      vipAuthorization
      vipName
      vipStatus
      visaValidityType
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastName': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'organizationID': pl.Int64,
    'phoneId': pl.Float64,
    'phoneType': pl.Utf8,
    'phoneTypeDescription': pl.Utf8,
    'phoneTypeId': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYN': pl.Utf8,
    'profileID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'shareEmailYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validYn': pl.Utf8,
}
```
```python
profile_information_details_schema = {
    'aRCreditLimitYN': pl.Utf8,
    'aRNumber': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerCode': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountsourceDesc': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressId': pl.Float64,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allOwners': pl.Utf8,
    'allResorts': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'anonymizationDate': pl.Utf8,
    'anonymizationStatus': pl.Utf8,
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
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'cashBlInd': pl.Utf8,
    'ccProfileYn': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralIATANumber': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralSourceOwnerTitle': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
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
    'compPreApprovalRequiredYn': pl.Utf8,
    'company': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competitionCode': pl.Utf8,
    'competitionDesc': pl.Utf8,
    'contactFlag': pl.Utf8,
    'contactOwnerCode': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corpID': pl.Utf8,
    'corpTypeDesc': pl.Utf8,
    'corporateType': pl.Utf8,
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
    'decimalPositions': pl.Float64,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'emailYn': pl.Utf8,
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
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
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
    'inactiveReasonCode': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'incognitoFirstName': pl.Utf8,
    'incognitoLastName': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryDesc': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDesc': pl.Utf8,
    'insertUserId': pl.Float64,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'laptopChange': pl.Float64,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRateCode': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastRoomResort': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionCodes': pl.Utf8,
    'mailActionDesc': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'marketsDesc': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'middle': pl.Utf8,
    'name': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'nameWithTitle': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'passport': pl.Utf8,
    'paymentDueDays': pl.Float64,
    'paymentMethodsCode': pl.Utf8,
    'paymentMethodsDesc': pl.Utf8,
    'phoneWeb': pl.Utf8,
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
    'priorityDesc': pl.Utf8,
    'productInterest': pl.Utf8,
    'productInterestCodes': pl.Utf8,
    'profession': pl.Utf8,
    'profileArrCodes': pl.Utf8,
    'profileArrangementDesc': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileLanguage': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'protected': pl.Utf8,
    'province': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountType': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repIataCompType': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMarkets': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxType': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotentialDesc': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDesc': pl.Utf8,
    'scopeDesc': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'sname': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'sourceOwnerTitle': pl.Utf8,
    'state': pl.Utf8,
    'stateDesc': pl.Utf8,
    'stateDescription': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDesc': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDesc': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'topAccountID': pl.Float64,
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
    'updateUserId': pl.Float64,
    'uploadDate': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```