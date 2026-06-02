# ProfilesNotes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `profilesNotes`
> Profile note types and note details including internal and confidential flags and the profile details they are associated with.
  
**Return:** [`[ProfilesNotesType]`](#profilesnotestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesNotesQueryArgumentsType!`](#profilesnotesqueryargumentstype) |  |

## Object Types

### ProfilesNotesType

| Field | Type | Description |
| --- | --- | --- |
| profileNoteDetails | [`ProfilesNotesProfileNoteDetailsType`](#profilesnotesprofilenotedetailstype) | Profile Note Details |
| profileAllInformationDetails | [`ProfilesNotesProfileAllInformationDetailsType`](#profilesnotesprofileallinformationdetailstype) | Profile All Details |
| profilesNotesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesNotesProfileNoteDetailsType

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

### ProfilesNotesProfileAllInformationDetailsType

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

## Input Types

### DateInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Date` |  |  |
| _ne | `Date` |  |  |
| _in | `[Date]` |  |  |
| _nin | `[Date]` |  |  |
| _gt | `Date` |  |  |
| _lt | `Date` |  |  |
| _gte | `Date` |  |  |
| _lte | `Date` |  |  |
| _btn | [`DateRangeInput`](#daterangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Date!` |  |  |
| end | `Date!` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `DateTime` |  |  |
| _ne | `DateTime` |  |  |
| _in | `[DateTime]` |  |  |
| _nin | `[DateTime]` |  |  |
| _gt | `DateTime` |  |  |
| _lt | `DateTime` |  |  |
| _gte | `DateTime` |  |  |
| _lte | `DateTime` |  |  |
| _btn | [`DateTimeRangeInput`](#datetimerangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `DateTime!` |  |  |
| end | `DateTime!` |  |  |

[⬆ Back to Query](#query)

---

### StringInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `String` |  |  |
| _ne | `String` |  |  |
| _in | `[String]` |  |  |
| _nin | `[String]` |  |  |
| _gt | `String` |  |  |
| _lt | `String` |  |  |
| _gte | `String` |  |  |
| _lte | `String` |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Float` |  |  |
| _ne | `Float` |  |  |
| _in | `[Float]` |  |  |
| _nin | `[Float]` |  |  |
| _gt | `Float` |  |  |
| _lt | `Float` |  |  |
| _gte | `Float` |  |  |
| _lte | `Float` |  |  |
| _btn | [`FloatRangeInput`](#floatrangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Float!` |  |  |
| end | `Float!` |  |  |

[⬆ Back to Query](#query)

---

### ProfilesNotesQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| profilenoteDetailsActionDueDate | `DateInput` | Activity Due Date |  |
| profilenoteDetailsActionType | `StringInput` | Activity Type |  |
| profilenoteDetailsChainCode | `StringInput!` | ASP chain code. | `mandatoryInput` |
| profilenoteDetailsConfidentialYn | `StringInput` | Indicates if this note is confidential. |  |
| profilenoteDetailsInsertUser | `FloatInput` | The user that created the record |  |
| profilenoteDetailsInsertDate | `DateTimeInput` | The date the record was created |  |
| profilenoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| profilenoteDetailsDeletedFlag | `StringInput` | Deleted Flag |  |
| profilenoteDetailsExternalNoteId | `StringInput` | Unique ID in External System. |  |
| profilenoteDetailsGlobalNoteYn | `StringInput` | Global Note Y/N |  |
| profilenoteDetailsGlobalYn | `StringInput` | Can a global note be created for this note code or not. |  |
| profilenoteDetailsInactiveDate | `DateInput` | Inactive date of the record. This indicates that record is no longer in use and can be purged in by purge routine. |  |
| profilenoteDetailsInactiveFlag | `StringInput` | Inactive Flag |  |
| profilenoteDetailsDeletedflag | `StringInput` | Deleted Flag |  |
| profilenoteDetailsInactiveflag | `StringInput` | Inactive Flag |  |
| profilenoteDetailsLocationId | `StringInput` | Location Id |  |
| profilenoteDetailsOrganizationId | `FloatInput` | Organization ID |  |
| profilenoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| profilenoteDetailsLaptopChange | `FloatInput` | Indicator for Laptop change. |  |
| profilenoteDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| profilenoteDetailsNameId | `FloatInput` | Parent Name_id refers Name table. |  |
| profilenoteDetailsNameType | `StringInput` | The type of Profile. |  |
| profilenoteDetailsNoteCode | `StringInput` | Indicates the Type of Note. |  |
| profilenoteDetailsNoteCodeDescription | `StringInput` | Description of Note Code |  |
| profilenoteDetailsNoteId | `FloatInput` | Primary Key for the Table |  |
| profilenoteDetailsInternalYn | `StringInput` | Indicates if this note should be shown to guest. Future use. |  |
| profilenoteDetailsNoteTitle | `StringInput` | Title of the Note |  |
| profilenoteDetailsNotes | `StringInput` | The actual Note. |  |
| profilenoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| profilenoteDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |  |
| profilenoteDetailsProfileId | `FloatInput` | Parent Name_id refers Name table. |  |
| profilenoteDetailsProfileNoteId | `FloatInput` | Profile Note ID |  |
| profilenoteDetailsResort | `StringInput` | Property |  |
| profilenoteDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |  |
| profilenoteDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |  |
| profilenoteDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |
| profilenoteDetailsUpdateUser | `FloatInput` | The user that modified the record |  |
| profileallDetailsNameId | `FloatInput` | The primary key for this table. |  |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not. |  |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |  |
| profileallDetailsChainCode | `StringInput` | Chain Code |  |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |  |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |  |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |  |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |  |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |  |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |  |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |  |
| profileallDetailsIndexName | `StringInput` | Index Name |  |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID |  |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| profileallDetailsNameType | `StringInput` | The type of Profile. |  |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table. |  |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |  |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |  |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |  |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company. |  |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |  |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name. |  |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module |  |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |  |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesNotes($input: ProfilesNotesQueryArgumentsType!) {
  profilesNotes(input: $input) @stream {
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
  }
}
```