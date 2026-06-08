# ProfilesIndividuals
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesIndividuals`
> Guest profile data including contact information VIP codes memberships and stay statistics with room and revenue details.
  
**Return:** [`[ProfilesIndividualsType]`](#profilesindividualstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesIndividualsQueryArgumentsType!`](#profilesindividualsqueryargumentstype) |  |

## Object Types

### ProfilesIndividualsType

| Field | Type | Description |
| --- | --- | --- |
| profileAllInformationDetails | [`ProfilesIndividualsProfileAllInformationDetailsType`](#profilesindividualsprofileallinformationdetailstype) | Profile All Details |
| profileAddressDetails | [`ProfilesIndividualsProfileAddressDetailsType`](#profilesindividualsprofileaddressdetailstype) | Profile Address Details |
| profileCommunicationDetails | [`ProfilesIndividualsProfileCommunicationDetailsType`](#profilesindividualsprofilecommunicationdetailstype) | Profile Communication Details |
| profilePreferenceDetails | [`ProfilesIndividualsProfilePreferenceDetailsType`](#profilesindividualsprofilepreferencedetailstype) | Profile Preference Details |
| profileDocumentsDetails | [`ProfilesIndividualsProfileDocumentsDetailsType`](#profilesindividualsprofiledocumentsdetailstype) | Profile Documents Details |
| profileMembershipDetails | [`ProfilesIndividualsProfileMembershipDetailsType`](#profilesindividualsprofilemembershipdetailstype) | Profile Membership Details |
| profileNoteDetails | [`ProfilesIndividualsProfileNoteDetailsType`](#profilesindividualsprofilenotedetailstype) | Profile Note Details |
| profileRelationshipDetails | [`ProfilesIndividualsProfileRelationshipDetailsType`](#profilesindividualsprofilerelationshipdetailstype) | Profile Relationship Details |
| individualDailyStatisticsDetails | [`ProfilesIndividualsIndividualDailyStatisticsDetailsType`](#profilesindividualsindividualdailystatisticsdetailstype) | Individual Daily Statistics |
| profileKeywordsDetails | [`ProfilesIndividualsProfileKeywordsDetailsType`](#profilesindividualsprofilekeywordsdetailstype) | Profile Keywords |
| profileSubscriptionDetails | [`ProfilesIndividualsProfileSubscriptionDetailsType`](#profilesindividualsprofilesubscriptiondetailstype) | Profile Subscription Details |
| profilesIndividualsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileAllInformationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| guestProfileID | `Float` | The primary key for this table. |
| aRNumber | `String` | Account number. |
| aRNumberCentral | `String` | Account Receivable No. of this profile. |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountBillingContact | `String` | Billing contact person in company. |
| accountSource | `String` | Used in S&C Module. |
| accountType | `String` | Account Type of this Profile |
| accountTypeDescription | `String` | The description of this value. |
| accountsourceDesc | `String` | The description of this value. |
| actionCode | `String` | Mailing action codes. |
| activeYN | `String` | Profile is active or not. |
| address1 | `String` | The first line of street address. |
| address2 | `String` | The second line of street address. |
| address3 | `String` | The third line of street address. |
| address4 | `String` | The fourth line of street address. |
| addressId | `Float` | The primary key for this table. |
| addressLangCodeDesc | `String` | Description for each language code. |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | The type of address. |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allResorts | `String` | All Resorts |
| alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Description for each language code. |
| alternateSalutation | `String` | Alternate Salutation |
| autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| availabilityOverride | `String` | Does profile have Availability Override Y/N |
| billingCode | `String` | The billing code for this name record. |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthCountry | `String` | Country of Birth |
| birthDate | `Date` | Date of Birth of the Individual Profiles. |
| birthDateStr | `String` | Stores the encrypted birth date. |
| birthPlace | `String` | Place of Birth |
| blMsg | `String` | Any Message for the Restricted profile. |
| businessSegment | `String` | Used in S&C Module. |
| businessSegmentDescription | `String` | The description of this value. |
| businessTitle | `String` | The business title for this individual. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountType | `String` | Central Account Type |
| centralBusinessSegment | `String` | Central Business Segment |
| centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| centralCorporateIDType | `String` | Central Corporate ID Type |
| centralDefaultKeyword | `String` | The keyword to search on. |
| centralGuestTitleCode | `String` | Central Guest Title Code |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralMailingActionCode | `String` | Central Mailing Action Code |
| centralPriority | `String` | Central Priority |
| centralStateCode | `String` | Central State Code |
| centralTerritory | `String` | Central Territory |
| centralVIPCode | `String` | Central VIP Code |
| centralVIPDescription | `String` | Central VIP Description |
| chainCode | `String` | Chain Code |
| city | `String` | The city for this address. |
| clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| comments | `String` | Not Used. |
| commissionCode | `String` | Commission Code for the Commission Percentage. |
| commissionCodes | `String` | Code for the commission for Travel Agent |
| commissionCurrencyId | `String` | Comm Curr ID |
| commissionid | `String` | Commission Code for the Commission Percentage. |
| communicationRole1 | `String` | Role in which this phone type belongs to. |
| communicationRole2 | `String` | Role in which this phone type belongs to. |
| communicationRole3 | `String` | Role in which this phone type belongs to. |
| communicationType1 | `String` | The type of this phone number. |
| communicationType2 | `String` | The type of this phone number. |
| communicationType3 | `String` | The type of this phone number. |
| communicationValue1 | `String` | The phone number for this record |
| communicationValue2 | `String` | The phone number for this record |
| communicationValue3 | `String` | The phone number for this record |
| companyAlternate | `String` | Extended Byte Company Name |
| companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| companyNameId | `Float` | Not used. |
| competition | `String` | Competaion code . |
| competitionDesc | `String` | The description of this value. |
| contactYN | `String` | Used in S&C Module. |
| contractNo | `String` | Group Contract number. |
| contractRecvDate | `Date` | The date the group contract was received. |
| corpTypeDesc | `String` | Corp Type Description |
| corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country name. |
| countryCode | `String` | Country . |
| createdByUser | `String` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| creditRating | `String` | Credit rating. |
| currencyCode | `String` | Currency Code |
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
| debtorName | `String` | Debtor Name |
| decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| defaultKeyword | `String` | The keyword to search on. |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Used in S&C Module. |
| deptId | `String` | Used in S&C Module. |
| description | `String` | Used in QMS Module |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| downloadResort | `String` | REsort name which has downloaded on the laptop. |
| downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| email | `String` | The phone number for this record |
| emailYN | `String` | Email YN |
| envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| externalDisplayName | `String` | External Display Name |
| externalFirstName | `String` | The first name of an individual. |
| externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| externalName | `String` | The last name of the individual profile. |
| externalReferenceRequ | `String` | Not Used. |
| externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| fMembershipCardNumbers | `String` | Membership Card Number. |
| fMembershipClassDesc | `String` | Descripion of membership class |
| fMembershipClasses | `String` | F Membership Classes |
| fMembershipCodes | `String` | F Membership Codes |
| fMembershipDescriptions | `String` | F Membership Descriptions |
| fMembershipIds | `String` | Primary Key for this table. |
| fMembershipType | `String` | Type of the Membership. |
| fSubscriptionDb | `String` | The ID of the external Database. |
| fSubscriptionYn | `String` | The ID of the external Database. |
| faxNumber | `String` | The phone number for this record |
| firstName | `String` | The first name of an individual name. |
| firstNameAlternate | `String` | First Name Alternate |
| firstNameIncognito | `String` | The keyword to search on. |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestCountry | `String` | Country name. |
| guestCurrencyCode | `String` | Currency code for the Commission payment. |
| guestLanguageCode | `String` | Description for each language code. |
| guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| guestMiddleName | `String` | The middle name of this individual. |
| guestNameSuffix | `String` | Guest Name Suffix |
| guestPrivilegeYN | `String` | Guest Privilege YN |
| guestTitleCode | `String` | The title of the individual. |
| hasRequestedMailYN | `String` | Has Requested Mail YN |
| historyYN | `String` | Keep guest in history Y/N |
| holdCode | `String` | Hold code for the Commission handling purposes. |
| iataConsortia | `String` | Consortia for the IATA number. |
| idCountry | `String` | The country where ID was issued |
| idDate | `Date` | Issued date of Identification |
| idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| idPlace | `String` | The place where ID was issued |
| idType | `String` | Identification Type. Eg Passport Driving License etc |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason why record was inactivated. |
| inactiveReasonDescription | `String` | The description of this value. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| indexName | `String` | Index Name |
| industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| industryDesc | `String` | The description of this value. |
| influence | `String` | Used in S&C Module. |
| influenceDesc | `String` | The description of this value. |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Primary language used for the profile. |
| laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| lastGroup | `String` | Last Group |
| lastNameAlternate | `String` | Last Name Alternate |
| lastNameIncognito | `String` | The keyword to search on. |
| lastRate | `Float` | Last Rate |
| lastRateCode | `String` | Last Rate Code |
| lastRoom | `String` | The room that is booked for this reservation leg. |
| lastRoomProperty | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | The legal company name for this company. |
| letterGreeting | `String` | Used in S&C Module. |
| mailActionDescription | `String` | The description of this value. |
| mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| mailType | `String` | The type of mail this user should be sent. |
| mailingActionCode | `String` | Mailing action codes. |
| marketResearchYN | `String` | Market Research YN |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| nameTaxType | `String` | Not used. |
| nameType | `String` | The type of Profile. |
| nameTypeDescription | `String` | The description of this value. |
| name2 | `String` | Not Used. |
| name3 | `String` | Not used. |
| nationality | `String` | Nationality |
| nationalityCode | `String` | Nationality of the individual. |
| negotiatedRateCodes | `String` | The rate code for which this record applies. |
| nextStay | `Date` | This is a begin_date  with no  time component. |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| phone | `String` | The phone number for this record |
| phoneWeb | `String` | The phone number for this record |
| phoneYN | `String` | Phone YN |
| postalCode | `String` | The postal code of this address. |
| postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| preferredRoomNo | `String` | Preferred Room Number |
| primaryAddressId | `Float` | Not used. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryNameId | `Float` | Not Used. |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| primaryPhoneId | `Float` | Not used. |
| priority | `String` | Priority of the account |
| priorityDesc | `String` | The description of this value. |
| privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| productInterest | `String` | Preference Code. Part of the Primary Key. |
| profession | `String` | The profession of the Individual |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileId | `Float` | The primary key for this table. |
| profileType | `String` | The type of Profile. |
| propertyRegistered | `String` | Resort for which Job is registered. |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | The region for this name. |
| regionid | `String` | The region for this name. |
| repAccountTypeDescription | `String` | Reporting Account Type Description |
| repAccountsource | `String` | Reporting Accountsource |
| repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| repCompetitionCode | `String` | Reporting Competition Code |
| repCompetitionDescription | `String` | Reporting Competition Desc |
| repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| repIndustryCode | `String` | Reporting Industry Code |
| repIndustryDescription | `String` | Reporting Industry Desc |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repNameType | `String` | Reporting Name Type |
| repNameTypeDescription | `String` | Reporting Name Type Description |
| repNationalityCode | `String` | Rep Nationality Code |
| repNationalityDescription | `String` | Rep Nationality Description |
| repPriorityDescription | `String` | Reporting Priority Desc |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repScopeCityDescription | `String` | Reporting Scope City Desc |
| repScopeDescription | `String` | Reporting Scope Desc |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTerritoryDescription | `String` | Reporting Territory Desc |
| repTitleName | `String` | Reporting Title Name |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| requestType | `String` | This column store the Name of the Company Profiles. |
| restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| restrictedRule | `String` | The description of this value. |
| resvContact | `String` | Reservation Contact person. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotential | `String` | Potential no of rooms per year for a account |
| roomsPotentialDesc | `String` | The description of this value. |
| sMSYN | `String` | Use this alert to text a notification. |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope of the account |
| scopeCity | `String` | Scope City |
| scopeCityDesc | `String` | The description of this value. |
| scopeDesc | `String` | The description of this value. |
| searchName | `String` | The Uppercase value of Last or Company. |
| searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sfirst | `String` | Uppercase value of First Name. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| srepCode | `String` | Used in QMS Module |
| state | `String` | The state of this address. |
| stateCode | `String` | State Code |
| stateDescription | `String` | Description of the state. |
| summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| superSearchIndexText | `String` | Used in Oracle Text Index. |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| taxID2 | `String` | Tax No |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| territory | `String` | TERRITORY of  a account |
| territoryDesc | `String` | The description of this value. |
| thirdPartyYN | `String` | Third Party YN |
| titleAlternate | `String` | Title Alternate |
| titleName | `String` | The description of this value. |
| titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| traceCode | `String` | Code to Trace a record for all Triggered actions. |
| tracecodeDesc | `String` | Description |
| typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| uDFC01 | `String` | User defined character field. |
| uDFC02 | `String` | User defined character field. |
| uDFC03 | `String` | User defined character field. |
| uDFC04 | `String` | User defined character field. |
| uDFC05 | `String` | User defined character field. |
| uDFC06 | `String` | User defined character field. |
| uDFC07 | `String` | User defined character field. |
| uDFC08 | `String` | User defined character field. |
| uDFC09 | `String` | User defined character field. |
| uDFC10 | `String` | User defined character field. |
| uDFC11 | `String` | User defined character field. |
| uDFC12 | `String` | User defined character field. |
| uDFC13 | `String` | User defined character field. |
| uDFC14 | `String` | User defined character field. |
| uDFC15 | `String` | User defined character field. |
| uDFC16 | `String` | User defined character field. |
| uDFC17 | `String` | User defined character field. |
| uDFC18 | `String` | User defined character field. |
| uDFC19 | `String` | User defined character field. |
| uDFC20 | `String` | User defined character field. |
| uDFC21 | `String` | User defined character field. |
| uDFC22 | `String` | User defined character field. |
| uDFC23 | `String` | User defined character field. |
| uDFC24 | `String` | User defined character field. |
| uDFC25 | `String` | User defined character field. |
| uDFC26 | `String` | User defined character field. |
| uDFC27 | `String` | User defined character field. |
| uDFC28 | `String` | User defined character field. |
| uDFC29 | `String` | User defined character field. |
| uDFC30 | `String` | User defined character field. |
| uDFC31 | `String` | User defined character field. |
| uDFC32 | `String` | User defined character field. |
| uDFC33 | `String` | User defined character field. |
| uDFC34 | `String` | User defined character field. |
| uDFC35 | `String` | User defined character field. |
| uDFC36 | `String` | User defined character field. |
| uDFC37 | `String` | User defined character field. |
| uDFC38 | `String` | User defined character field. |
| uDFC39 | `String` | User defined character field. |
| uDFC40 | `String` | User defined character field. |
| uDFD01 | `Date` | User defined date field. |
| uDFD02 | `Date` | User defined date field. |
| uDFD03 | `Date` | User defined date field. |
| uDFD04 | `Date` | User defined date field. |
| uDFD05 | `Date` | User defined date field. |
| uDFD06 | `Date` | User defined date field. |
| uDFD07 | `Date` | User defined date field. |
| uDFD08 | `Date` | User defined date field. |
| uDFD09 | `Date` | User defined date field. |
| uDFD10 | `Date` | User defined date field. |
| uDFD11 | `Date` | User defined date field. |
| uDFD12 | `Date` | User defined date field. |
| uDFD13 | `Date` | User defined date field. |
| uDFD14 | `Date` | User defined date field. |
| uDFD15 | `Date` | User defined date field. |
| uDFD16 | `Date` | User defined date field. |
| uDFD17 | `Date` | User defined date field. |
| uDFD18 | `Date` | User defined date field. |
| uDFD19 | `Date` | User defined date field. |
| uDFD20 | `Date` | User defined date field. |
| uDFN01 | `Float` | User defined number field. |
| uDFN02 | `Float` | User defined number field. |
| uDFN03 | `Float` | User defined number field. |
| uDFN04 | `Float` | User defined number field. |
| uDFN05 | `Float` | User defined number field. |
| uDFN06 | `Float` | User defined number field. |
| uDFN07 | `Float` | User defined number field. |
| uDFN08 | `Float` | User defined number field. |
| uDFN09 | `Float` | User defined number field. |
| uDFN10 | `Float` | User defined number field. |
| uDFN11 | `Float` | User defined number field. |
| uDFN12 | `Float` | User defined number field. |
| uDFN13 | `Float` | User defined number field. |
| uDFN14 | `Float` | User defined number field. |
| uDFN15 | `Float` | User defined number field. |
| uDFN16 | `Float` | User defined number field. |
| uDFN17 | `Float` | User defined number field. |
| uDFN18 | `Float` | User defined number field. |
| uDFN19 | `Float` | User defined number field. |
| uDFN20 | `Float` | User defined number field. |
| uDFN21 | `Float` | User defined number field. |
| uDFN22 | `Float` | User defined number field. |
| uDFN23 | `Float` | User defined number field. |
| uDFN24 | `Float` | User defined number field. |
| uDFN25 | `Float` | User defined number field. |
| uDFN26 | `Float` | User defined number field. |
| uDFN27 | `Float` | User defined number field. |
| uDFN28 | `Float` | User defined number field. |
| uDFN29 | `Float` | User defined number field. |
| uDFN30 | `Float` | User defined number field. |
| uDFN31 | `Float` | User defined number field. |
| uDFN32 | `Float` | User defined number field. |
| uDFN33 | `Float` | User defined number field. |
| uDFN34 | `Float` | User defined number field. |
| uDFN35 | `Float` | User defined number field. |
| uDFN36 | `Float` | User defined number field. |
| uDFN37 | `Float` | User defined number field. |
| uDFN38 | `Float` | User defined number field. |
| uDFN39 | `Float` | User defined number field. |
| uDFN40 | `Float` | User defined number field. |
| updateDate | `DateTime` | The date the record was modified |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | The user that modified the record |
| uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| vIPCode | `String` | VIP Status of the Individual. |
| vIPDescription | `String` | The description of this value. |
| vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xdisplayName | `String` | Xdisplay Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileAddressDetailsType

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

### ProfilesIndividualsProfileCommunicationDetailsType

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

### ProfilesIndividualsProfilePreferenceDetailsType

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

### ProfilesIndividualsProfileDocumentsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| documentId | `Float` | Unique ID for this table. |
| guestIdentificationIDIssuePlace | `String` | The place where the ID was issued. |
| idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| identificationIDCountry | `String` | The country where the ID was issued |
| identificationIDExpirationDate | `Date` | Expiration date of the ID document. |
| identificationIDIssueDate | `Date` | Identification Issued date. |
| identificationIDNumber | `String` | Encrypted identification number. |
| identificationIDPrimaryYN | `String` | Indicates if this record is the primary one for the ID type. |
| identificationIDType | `String` | Identification type e.g: PASSPORT DRIVING LICENSE etc. |
| inactiveDate | `DateTime` | Date this record was inactivated. |
| insertDate | `DateTime` | The date the record was created. |
| insertUser | `Float` | The user that created the record. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | The property this record belongs to can be "_GLOBAL". |
| nameId | `Float` | The profile ID reference who owns this document. |
| orderBy | `Float` | Display Sequence. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | The property this record belongs to can be "_GLOBAL". |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sIdNumber | `String` | Internal indexed field to search for ID_NUMBER. |
| updateDate | `DateTime` | The date the record was modified. |
| updateUser | `Float` | The user that modified the record. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileMembershipDetailsType

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

### ProfilesIndividualsProfileNoteDetailsType

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

### ProfilesIndividualsProfileRelationshipDetailsType

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

### ProfilesIndividualsIndividualDailyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFBRevenue | `Float` | Central Fb Revenue |
| cFBRevenueTax | `Float` | Central Fb Revenue Tax |
| cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| cOtherRevenue | `Float` | Central Other Revenue |
| cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| cRoomRevenue | `Float` | Central Room Revenue |
| cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| cTotalRevenue | `Float` | Central Total Revenue |
| cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| cancels | `Float` | Cancels |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralTotalRevenue | `Float` | Central Total Revenue |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenue | `Float` | FB Revenue |
| fbRevenue | `Float` | FB Revenue |
| fbRevenueTax | `Float` | F&B Revenue Tax. |
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
| locationID | `String` | The property that the record belongs to |
| nameId | `Float` | The system-generated Internal numeric ID that corresponds to the Travel Agent for which the current record applies. Part of Primary Key. |
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
| property | `String` | The property that the record belongs to |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueTax | `Float` | Room Revenue Tax |
| stayDate | `Date` | The Business Date for which the current record applies. Part of Primary Key. |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| stays | `Float` | Stays |
| totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| totalOtherRevenue | `Float` | Total of All Revenue for the current record's key value that does not fall under Room/Food/Beverage category. |
| totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| totalRevenue | `Float` | Total Revenue Amount for the current record's key value. |
| totalRevenueTax | `Float` | Total Revenue Tax |
| totalRoomRevenue | `Float` | Total Room Revenue Amount for the current record's key value. |
| totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| totalTotalRevenue | `Float` | Total Total Revenue |
| totalTotalRevenueTax | `Float` | Total Total Revenue Tax |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileKeywordsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralKeywordType | `String` | Central Keyword Type |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| interfaceUpdatedYn | `String` | Interface  update status |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | The keyword to search on. |
| keywordSoundex | `String` | The soundex of this keyword. |
| keywordType | `String` | Derived value based on the Type of the profile for the Search purpose. |
| laptopChange | `Float` | Code to synchronize with Laptop. |
| nameId | `Float` | The name these keywords are derived from. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateAllowedYn | `String` | Update allowed status. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileSubscriptionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowDuplicateYn | `String` | Allow Duplicate Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| extDBNameID | `String` | Ext DB Name ID |
| externalDatabaseName | `String` | External Database Name |
| externalProfileId | `String` | External Profile ID |
| forceYn | `String` | Indicates if profile distribution should be forced. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastActivityDate | `Date` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| lastDistributeDate | `Date` | The data when profile was last distributed. |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pendingAction | `Float` | Indicates action is pending for queque. It can take values 124 |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| profileId | `Float` | Profile ID |
| profilesubscriptionId | `Float` | Profilesubscription ID |
| queryCode | `String` | Query Code |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
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

### ProfilesIndividualsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| profileallDetailsNameId | `FloatInput` | The primary key for this table.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsIndexName | `StringInput` | Index Name<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsNameType | `StringInput` | The type of Profile. |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified<br>`@conditionalInputPair(pair: 2)` |
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
| profiledocumentsDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profiledocumentsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profiledocumentsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profiledocumentsDetailsDocumentId | `FloatInput` | Unique ID for this table. |
| profiledocumentsDetailsIdPlace | `StringInput` | The place where the ID was issued. |
| profiledocumentsDetailsIdDocumentAttachId | `FloatInput` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| profiledocumentsDetailsIdCountry | `StringInput` | The country where the ID was issued |
| profiledocumentsDetailsIdExpirationDate | `DateInput` | Expiration date of the ID document. |
| profiledocumentsDetailsIdDate | `DateInput` | Identification Issued date. |
| profiledocumentsDetailsIdNumber | `StringInput` | Encrypted identification number. |
| profiledocumentsDetailsPrimaryYn | `StringInput` | Indicates if this record is the primary one for the ID type. |
| profiledocumentsDetailsIdType | `StringInput` | Identification type e.g: PASSPORT DRIVING LICENSE etc. |
| profiledocumentsDetailsInactiveDate | `DateTimeInput` | Date this record was inactivated. |
| profiledocumentsDetailsInsertDate | `DateTimeInput` | The date the record was created. |
| profiledocumentsDetailsInsertUser | `FloatInput` | The user that created the record. |
| profiledocumentsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profiledocumentsDetailsLocationid | `StringInput` | The property this record belongs to can be "_GLOBAL". |
| profiledocumentsDetailsNameId | `FloatInput` | The profile ID reference who owns this document. |
| profiledocumentsDetailsOrderBy | `FloatInput` | Display Sequence. |
| profiledocumentsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profiledocumentsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profiledocumentsDetailsResort | `StringInput` | The property this record belongs to can be "_GLOBAL". |
| profiledocumentsDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profiledocumentsDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profiledocumentsDetailsSIdNumber | `StringInput` | Internal indexed field to search for ID_NUMBER. |
| profiledocumentsDetailsUpdateDate | `DateTimeInput` | The date the record was modified. |
| profiledocumentsDetailsUpdateUser | `FloatInput` | The user that modified the record. |
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
| individualdailystatDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| individualdailystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| individualdailystatDetailsJrnUpdateDttm | `DateTimeInput` | Journal Update Dttm |
| individualdailystatDetailsNameId | `FloatInput` | The system-generated Internal numeric ID that corresponds to the Travel Agent for which the current record applies. Part of Primary Key. |
| individualdailystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| individualdailystatDetailsResort | `StringInput` | The property that the record belongs to |
| individualdailystatDetailsStayDate | `DateInput` | The Business Date for which the current record applies. Part of Primary Key. |
| namekeywordsDetailsRepKeywordType | `StringInput` | Central Keyword Type |
| namekeywordsDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| namekeywordsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| namekeywordsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| namekeywordsDetailsInterfaceUpdatedYn | `StringInput` | Interface  update status |
| namekeywordsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| namekeywordsDetailsKeyword | `StringInput` | The keyword to search on. |
| namekeywordsDetailsKeywordSoundex | `StringInput` | The soundex of this keyword. |
| namekeywordsDetailsKeywordType | `StringInput` | Derived value based on the Type of the profile for the Search purpose. |
| namekeywordsDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop. |
| namekeywordsDetailsNameId | `FloatInput` | The name these keywords are derived from. |
| namekeywordsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| namekeywordsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| namekeywordsDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| namekeywordsDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| namekeywordsDetailsUpdateAllowedYn | `StringInput` | Update allowed status. |
| profilesubscriptionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesIndividuals($input: ProfilesIndividualsQueryArgumentsType!) {
  profilesIndividuals(input: $input) @stream {
    profileAllInformationDetails {
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
    profileDocumentsDetails {
      chainCode
      dSI
      deletedFlag
      documentId
      guestIdentificationIDIssuePlace
      idDocumentAttachId
      identificationIDCountry
      identificationIDExpirationDate
      identificationIDIssueDate
      identificationIDNumber
      identificationIDPrimaryYN
      identificationIDType
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      nameId
      orderBy
      organizationID
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      sIdNumber
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
    individualDailyStatisticsDetails {
      cExchangeDate
      cExchangeRate
      cFBRevenue
      cFBRevenueTax
      cGroupFBRevenue
      cGroupFBRevenueTax
      cGroupOtherRevenue
      cGroupOtherRevenueTax
      cGroupRoomRevenue
      cGroupRoomRevenueTax
      cGroupTotalRevenue
      cGroupTotalRevenueTax
      cOtherRevenue
      cOtherRevenueTax
      cRoomRevenue
      cRoomRevenueTax
      cTotalFBRevenueTax
      cTotalOtherRevenueTax
      cTotalRevenue
      cTotalRevenueTax
      cTotalRoomRevenueTax
      cTotalTotalRevenueTax
      cancels
      centralFBRevenue
      centralOtherRevenue
      centralRoomRevenue
      centralTotalRevenue
      contextCd
      dSI
      deletedFlag
      fBRevenue
      fbRevenue
      fbRevenueTax
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
      stays
      totalFbRevenueTax
      totalOtherRevenue
      totalOtherRevenueTax
      totalRevenue
      totalRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
    }
    profileKeywordsDetails {
      centralKeywordType
      chainCode
      dSI
      deletedFlag
      interfaceUpdatedYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      keywordSoundex
      keywordType
      laptopChange
      nameId
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      updateAllowedYn
    }
    profileSubscriptionDetails {
      allowDuplicateYn
      chainCode
      dSI
      deletedFlag
      distributeYn
      extDBNameID
      externalDatabaseName
      externalProfileId
      forceYn
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastActivityDate
      lastDistributeDate
      nameId
      organizationID
      pendingAction
      primaryKeyID
      profileId
      profilesubscriptionId
      queryCode
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
profile_all_information_details_schema = {
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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
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
profile_documents_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'documentId': pl.Float64,
    'guestIdentificationIDIssuePlace': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'identificationIDCountry': pl.Utf8,
    'identificationIDExpirationDate': pl.Utf8,
    'identificationIDIssueDate': pl.Utf8,
    'identificationIDNumber': pl.Utf8,
    'identificationIDPrimaryYN': pl.Utf8,
    'identificationIDType': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sIdNumber': pl.Utf8,
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
individual_daily_statistics_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFBRevenue': pl.Float64,
    'cFBRevenueTax': pl.Float64,
    'cGroupFBRevenue': pl.Float64,
    'cGroupFBRevenueTax': pl.Float64,
    'cGroupOtherRevenue': pl.Float64,
    'cGroupOtherRevenueTax': pl.Float64,
    'cGroupRoomRevenue': pl.Float64,
    'cGroupRoomRevenueTax': pl.Float64,
    'cGroupTotalRevenue': pl.Float64,
    'cGroupTotalRevenueTax': pl.Float64,
    'cOtherRevenue': pl.Float64,
    'cOtherRevenueTax': pl.Float64,
    'cRoomRevenue': pl.Float64,
    'cRoomRevenueTax': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRevenue': pl.Float64,
    'cTotalRevenueTax': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cTotalTotalRevenueTax': pl.Float64,
    'cancels': pl.Float64,
    'centralFBRevenue': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fbRevenue': pl.Float64,
    'fbRevenueTax': pl.Float64,
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
    'stays': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
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
profile_keywords_details_schema = {
    'centralKeywordType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'interfaceUpdatedYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'keywordSoundex': pl.Utf8,
    'keywordType': pl.Utf8,
    'laptopChange': pl.Float64,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateAllowedYn': pl.Utf8,
}
```
```python
profile_subscription_details_schema = {
    'allowDuplicateYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'distributeYn': pl.Utf8,
    'extDBNameID': pl.Utf8,
    'externalDatabaseName': pl.Utf8,
    'externalProfileId': pl.Utf8,
    'forceYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastActivityDate': pl.Utf8,
    'lastDistributeDate': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'pendingAction': pl.Float64,
    'primaryKeyID': pl.Float64,
    'profileId': pl.Float64,
    'profilesubscriptionId': pl.Float64,
    'queryCode': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```