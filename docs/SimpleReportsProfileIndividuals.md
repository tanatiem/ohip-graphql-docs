# SimpleReportsProfileIndividuals
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `simpleReportsProfileIndividuals`
> The Simple Reports Profile-Individuals Subject Area simplifies creating and building adhoc reports including the ability to create new reports
  
**Return:** [`[SimpleReportsProfileIndividualsType]`](#simplereportsprofileindividualstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`SimpleReportsProfileIndividualsQueryArgumentsType!`](#simplereportsprofileindividualsqueryargumentstype) |  |

## Object Types

### SimpleReportsProfileIndividualsType

| Field | Type | Description |
| --- | --- | --- |
| profileDetails | [`SimpleReportsProfileIndividualsProfileDetailsType`](#simplereportsprofileindividualsprofiledetailstype) | Profile |
| profilePropertyDetails | [`SimpleReportsProfileIndividualsProfilePropertyDetailsType`](#simplereportsprofileindividualsprofilepropertydetailstype) | Profile Property |
| simpleReportsProfileIndividualsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SimpleReportsProfileIndividualsProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| accountType | `String` | Account Type |
| accountsource | `String` | Accountsource |
| acctContact | `String` | Billing contact person in company. |
| activeYn | `String` | Active Y/N |
| addrCleansedDatetime | `Date` | Addr Cleansed Datetime |
| addrCleansedErrormsg | `String` | Addr Cleansed Errormsg |
| addrCleansedStatus | `String` | Addr Cleansed Status |
| addrCleansedValstatus | `String` | Addr Cleansed Valstatus |
| addrLanguageCode | `String` | Addr Language Code |
| addrLanguageDesc | `String` | Addr Language Description |
| addressId | `Float` | Address ID |
| addressType | `String` | Address Type |
| addressTypeDesc | `String` | Address Type Description |
| address1 | `String` | Address1 |
| address2 | `String` | Address2 |
| address3 | `String` | Address3 |
| address4 | `String` | Address4 |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allOwners | `String` | All Owners |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDesc | `String` | Xlanguage Description |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| anonymizationDate | `Date` | System Date when the guest was anonymized in OPERA. |
| anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| availoverYn | `String` | Availover Y/N |
| barcode | `String` | Barcode |
| birthCountry | `String` | Country of birth. |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessExtension | `String` | Business Extension |
| businessPhoneId | `Float` | Business Phone ID |
| businessPhoneNumber | `String` | Business Phone Number |
| businessTitle | `String` | Business Title |
| cRSNameid | `Float` | The unique identifier of the CRS |
| cblInd | `String` | Cbl Individual |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| comm1CountryDialingCode | `Float` | Comm1 Country Dialing Code |
| comm1Id | `Float` | Comm1 ID |
| comm1PhoneCountryCode | `String` | Comm1 Phone Country Code |
| comm1Type | `String` | Comm1 Type |
| comm1ValidYn | `String` | Comm1 Valid Y/N |
| comm1ValidateDate | `Date` | Comm1 Validate Date |
| comm1ValidateStatus | `String` | Comm1 Validate Status |
| comm1Value | `String` | Comm1 Value |
| comm2CountryDialingCode | `Float` | Comm2 Country Dialing Code |
| comm2Id | `Float` | Comm2 ID |
| comm2PhoneCountryCode | `String` | Comm2 Phone Country Code |
| comm2Type | `String` | Comm2 Type |
| comm2ValidYn | `String` | Comm2 Valid Y/N |
| comm2ValidateDate | `Date` | Comm2 Validate Date |
| comm2ValidateStatus | `String` | Comm2 Validate Status |
| comm2Value | `String` | Comm2 Value |
| comm3CountryDialingCode | `Float` | Comm3 Country Dialing Code |
| comm3Id | `Float` | Comm3 ID |
| comm3PhoneCountryCode | `String` | Comm3 Phone Country Code |
| comm3Type | `String` | Comm3 Type |
| comm3ValidYn | `String` | Comm3 Valid Y/N |
| comm3ValidateDate | `Date` | Comm3 Validate Date |
| comm3ValidateStatus | `String` | Comm3 Validate Status |
| comm3Value | `String` | Comm3 Value |
| commissionAccountId | `Float` | Commission Account ID |
| commissionAccountName | `String` | Commission Account Name |
| compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| company | `String` | Company |
| companyGroupId | `String` | Linked internal ID for booker. |
| contactYn | `String` | Contact Y/N |
| contractNo | `String` | Contract Number (used for customers). |
| contractRecvDate | `Date` | The date the group contract was received. |
| country | `String` | Country |
| countryDesc | `String` | Country Description |
| creditRating | `String` | Credit Rating |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| department | `String` | Department |
| deptId | `String` | Dept ID |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| eMail | `String` | E Mail |
| eMailId | `Float` | E Mail ID |
| emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| emailValidateDate | `Date` | Email Validate Date |
| emailValidateStatus | `String` | Email Validate Status |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| faxCountryCode | `String` | Fax Country Code |
| faxCountryDialingCode | `Float` | Fax Country Dialing Code |
| faxId | `Float` | Fax ID |
| faxNo | `String` | Fax Number |
| faxValidYn | `String` | Fax Valid Y/N |
| first | `String` | First |
| folioAddressId | `Float` | Folio Address ID |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| hasnotes | `String` | Hasnotes |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| homePhoneId | `Float` | Home Phone ID |
| homePhoneNumber | `String` | Home Phone Number |
| iataCompType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| iataConsortia | `String` | IATA Consortia |
| iataCorpNumber | `String` | IATA Corp No |
| idCountry | `String` | ID Country |
| idDate | `Date` | ID Date |
| idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| idExpirationDate | `Date` | ID Expiration Date |
| idPlace | `String` | ID Place |
| idType | `String` | ID Type |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `Date` | Inactive Date |
| inactiveReason | `String` | Reason why record was inactivated. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| incognitoDisplayname | `String` | Incognito Displayname |
| incognitoFirst | `String` | Incognito First |
| incognitoName | `String` | Incognito Name |
| incognitoYn | `String` | Incognito Y/N |
| industryCode | `String` | Industry Code |
| influence | `String` | Influence |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| internalPrimaryKeyIDToUniquelyIdentifyTheRow | `Float` | Primary Key ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| language | `String` | Language |
| languageDesc | `String` | Description for each language code. |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| loggedSrepCode | `String` | Logged Srep Code |
| loyaltySegmentCodes | `String` | Loyalty Segment Codes |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| markets | `String` | Markets |
| membershipExpirationDate | `Date` | Membership Expiration Date |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipNameOnCard | `String` | Membership Name On Card |
| membershipNumber | `String` | Membership Number |
| membershipStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| membershipType | `String` | Membership Type |
| middle | `String` | Middle |
| mobilePhoneId | `Float` | Mobile Phone ID |
| mobilePhoneNumber | `String` | Mobile Phone Number |
| multipleAddressYn | `String` | Multiple Address Y/N |
| multipleCommentsYn | `String` | Not used. |
| multiplePhonesYn | `String` | Multiple Phones Y/N |
| name | `String` | Name |
| nameComment | `String` | Not Used. |
| nameId | `Float` | Name ID |
| nameKeywords | `String` | Name Keywords |
| nameType | `String` | Name Type |
| nameTypeDesc | `String` | Name Type Description |
| name2 | `String` | Name2 |
| name3 | `String` | Name3 |
| nationality | `String` | Nationality |
| nationalityDesc | `String` | Nationality Description |
| nextStay | `Date` | Next Stay |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| phoneCountryCode | `String` | Phone Country Code |
| phoneCountryDialingCode | `Float` | Phone Country Dialing Code |
| phoneExtension | `String` | Phone Extension |
| phoneId | `Float` | Phone ID |
| phoneNo | `String` | Phone no. |
| phoneType | `String` | Phone Type |
| phoneValidYn | `String` | Phone Valid Y/N |
| phoneYn | `String` | Phone Y/N |
| preferredRoomNo | `String` | Preferred Room Number |
| profession | `String` | Profession of the guest |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| propertyActionCode | `String` | Property Action Code |
| propertyCompetitionCode | `String` | Property Competition Code |
| propertyPriority | `String` | Property Priority |
| propertyRoomsPotential | `String` | Property Rooms Potential |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| repAccountType | `String` | Reporting Account Type |
| repAccountsource | `String` | Reporting Accountsource |
| repActionCode | `String` | Reporting Actioncode |
| repIATACompType | `String` | Reporting Iata Comp Type |
| repInactiveReason | `String` | Reporting Inactive Reason |
| repIndustryCode | `String` | Reporting Industry Code |
| repInfluence | `String` | Reporting Influence |
| repKeyword | `String` | Reporting Keyword |
| repMarkets | `String` | Reporting Markets |
| repNameType | `String` | Reporting Name Type |
| repNationality | `String` | Reporting Nationality |
| repNationalityDescription | `String` | Reporting Nationality Desc |
| repPropertyPriority | `String` | Reporting Property Priority |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repState | `String` | Reporting State |
| repStateDescription | `String` | Reporting State Desc |
| repTaxType | `String` | Reporting Tax Type |
| repTerritory | `String` | Reporting Territory |
| repTitle | `String` | Reporting Title |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restrictReasonCode | `String` | Restrict Reason Code |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| salesrep | `String` | Sales Representative Code for this profile. |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| sfirst | `String` | Uppercase value of First Name. |
| smsYn | `String` | Use this alert to text a notification. |
| sname | `String` | The Uppercase value of Last or Company. |
| srepCode | `String` | Srep Code |
| srepId | `Float` | Srep ID |
| state | `String` | State |
| stateDesc | `String` | State Description of the Guest of Payee |
| suffix | `String` | Suffix |
| summRefCc | `String` | Summ Ref Cc |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| territory | `String` | Territory |
| thirdPartyYn | `String` | Third Party Y/N |
| title | `String` | Title |
| titleName | `String` | Title Name |
| titleSuffix | `Float` | Title Suffix |
| totalStay | `Float` | Total Stay |
| tracecode | `String` | Tracecode |
| udfc01 | `String` | Udfc01 |
| udfc02 | `String` | Udfc02 |
| udfc03 | `String` | Udfc03 |
| udfc04 | `String` | Udfc04 |
| udfc05 | `String` | Udfc05 |
| udfc06 | `String` | Udfc06 |
| udfc07 | `String` | Udfc07 |
| udfc08 | `String` | Udfc08 |
| udfc09 | `String` | Udfc09 |
| udfc10 | `String` | Udfc10 |
| udfc11 | `String` | Udfc11 |
| udfc12 | `String` | Udfc12 |
| udfc13 | `String` | Udfc13 |
| udfc14 | `String` | Udfc14 |
| udfc15 | `String` | Udfc15 |
| udfc16 | `String` | Udfc16 |
| udfc17 | `String` | Udfc17 |
| udfc18 | `String` | Udfc18 |
| udfc19 | `String` | Udfc19 |
| udfc20 | `String` | Udfc20 |
| udfc21 | `String` | Udfc21 |
| udfc22 | `String` | Udfc22 |
| udfc23 | `String` | Udfc23 |
| udfc24 | `String` | Udfc24 |
| udfc25 | `String` | Udfc25 |
| udfc26 | `String` | Udfc26 |
| udfc27 | `String` | Udfc27 |
| udfc28 | `String` | Udfc28 |
| udfc29 | `String` | Udfc29 |
| udfc30 | `String` | Udfc30 |
| udfc31 | `String` | Udfc31 |
| udfc32 | `String` | Udfc32 |
| udfc33 | `String` | Udfc33 |
| udfc34 | `String` | Udfc34 |
| udfc35 | `String` | Udfc35 |
| udfc36 | `String` | Udfc36 |
| udfc37 | `String` | Udfc37 |
| udfc38 | `String` | Udfc38 |
| udfc39 | `String` | Udfc39 |
| udfc40 | `String` | Udfc40 |
| udfd01 | `Date` | Udfd01 |
| udfd02 | `Date` | Udfd02 |
| udfd03 | `Date` | Udfd03 |
| udfd04 | `Date` | Udfd04 |
| udfd05 | `Date` | Udfd05 |
| udfd06 | `Date` | Udfd06 |
| udfd07 | `Date` | Udfd07 |
| udfd08 | `Date` | Udfd08 |
| udfd09 | `Date` | Udfd09 |
| udfd10 | `Date` | Udfd10 |
| udfd11 | `Date` | Udfd11 |
| udfd12 | `Date` | Udfd12 |
| udfd13 | `Date` | Udfd13 |
| udfd14 | `Date` | Udfd14 |
| udfd15 | `Date` | Udfd15 |
| udfd16 | `Date` | Udfd16 |
| udfd17 | `Date` | Udfd17 |
| udfd18 | `Date` | Udfd18 |
| udfd19 | `Date` | Udfd19 |
| udfd20 | `Date` | Udfd20 |
| udfn01 | `Float` | Udfn01 |
| udfn02 | `Float` | Udfn02 |
| udfn03 | `Float` | Udfn03 |
| udfn04 | `Float` | Udfn04 |
| udfn05 | `Float` | Udfn05 |
| udfn06 | `Float` | Udfn06 |
| udfn07 | `Float` | Udfn07 |
| udfn08 | `Float` | Udfn08 |
| udfn09 | `Float` | Udfn09 |
| udfn10 | `Float` | Udfn10 |
| udfn11 | `Float` | Udfn11 |
| udfn12 | `Float` | Udfn12 |
| udfn13 | `Float` | Udfn13 |
| udfn14 | `Float` | Udfn14 |
| udfn15 | `Float` | Udfn15 |
| udfn16 | `Float` | Udfn16 |
| udfn17 | `Float` | Udfn17 |
| udfn18 | `Float` | Udfn18 |
| udfn19 | `Float` | Udfn19 |
| udfn20 | `Float` | Udfn20 |
| udfn21 | `Float` | Udfn21 |
| udfn22 | `Float` | Udfn22 |
| udfn23 | `Float` | Udfn23 |
| udfn24 | `Float` | Udfn24 |
| udfn25 | `Float` | Udfn25 |
| udfn26 | `Float` | Udfn26 |
| udfn27 | `Float` | Udfn27 |
| udfn28 | `Float` | Udfn28 |
| udfn29 | `Float` | Udfn29 |
| udfn30 | `Float` | Udfn30 |
| udfn31 | `Float` | Udfn31 |
| udfn32 | `Float` | Udfn32 |
| udfn33 | `Float` | Udfn33 |
| udfn34 | `Float` | Udfn34 |
| udfn35 | `Float` | Udfn35 |
| udfn36 | `Float` | Udfn36 |
| udfn37 | `Float` | Udfn37 |
| udfn38 | `Float` | Udfn38 |
| udfn39 | `Float` | Udfn39 |
| udfn40 | `Float` | Udfn40 |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| updateUserName | `String` | Update User Name |
| uploadDate | `Date` | Upload Date |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| webPage | `String` | Web Page |
| webPageId | `Float` | Web Page ID |
| xdisplayName | `String` | Xdisplay Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xmiddleName | `String` | Extended Byte middle name. |
| xname | `String` | Xname |
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### SimpleReportsProfileIndividualsProfilePropertyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionCode | `String` | Action Code |
| arNumber | `String` | AR No |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| billingInstruction | `String` | Billing Instruction |
| birGuestType | `String` | Guest type in PH country mode. Further used for showing proper adjustment options. |
| businessId | `String` | Business ID |
| businessRegistration | `String` | This column stores the BUSINESS REGISTRATION for a Profile for this property. |
| commissionCode | `String` | Commission Code |
| competitionCode | `String` | Competition Code |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| departmentNote | `String` | Department Note |
| electronicFiscalFlag | `String` | Indicates if a Profile can be marked to Generate Fiscal Folio/Payload. |
| features | `String` | Features |
| guestType | `Float` | Guest Type |
| internalPrimaryKeyIDToUniquelyIdentifyTheRow | `Float` | Primary Key ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastPrivacyPromptDate | `Date` | Last date the guest was prompted for privacy option. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentMethod | `String` | Payment Method |
| potentialNights | `Float` | Potential Nights |
| potentialRevenue | `Float` | Potential Revenue |
| priority | `String` | Priority |
| productInterest | `String` | Product Interest |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| repActionCode | `String` | Reporting Actioncode |
| repCompetitionCode | `String` | Reporting Competition Code |
| repPriority | `String` | Reporting Priority |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| roomsPotential | `String` | Rooms Potential |
| specials | `String` | Specials |
| taxPerc1 | `Float` | Tax Perc1 |
| taxPerc2 | `Float` | Tax Perc2 |
| taxPerc3 | `Float` | Tax Perc3 |
| taxPerc4 | `Float` | Tax Perc4 |
| taxPerc5 | `Float` | Tax Perc5 |
| vatOffsetYn | `String` | Vat Offset Y/N |

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

### SimpleReportsProfileIndividualsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| nameDetailsAnonymizationStatus | `StringInput` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| nameDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |
| nameDetailsChainCode | `StringInput!` | Chain Code<br>`@mandatoryInput` |
| nameDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |
| nameDetailsContactYn | `StringInput` | Contact Y/N |
| nameDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| nameDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| nameDetailsHistoryYn | `StringInput` | History Y/N |
| nameDetailsIataCorpNo | `StringInput` | IATA Corp No |
| nameDetailsInactiveDate | `DateInput` | Inactive Date |
| nameDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| nameDetailsNameId | `FloatInput` | Name ID |
| nameDetailsNameType | `StringInput` | Name Type |
| nameDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| nameDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| nameDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| nameDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| nameDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| nameDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| nameDetailsUpdateDate | `DateTimeInput` | Update Date |
| nameresortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query simpleReportsProfileIndividuals($input: SimpleReportsProfileIndividualsQueryArgumentsType!) {
  simpleReportsProfileIndividuals(input: $input) @stream {
    profileDetails {
      aRCreditLimitYN
      accountType
      accountsource
      acctContact
      activeYn
      addrCleansedDatetime
      addrCleansedErrormsg
      addrCleansedStatus
      addrCleansedValstatus
      addrLanguageCode
      addrLanguageDesc
      addressId
      addressType
      addressTypeDesc
      address1
      address2
      address3
      address4
      alienRegistrationNo
      allOwners
      alternateLanguage
      alternateLanguageDesc
      alternateSalutation
      alternateTitle
      anonymizationDate
      anonymizationStatus
      arNumberCentral
      autoenrollMemberYn
      availoverYn
      barcode
      birthCountry
      birthPlace
      blMsg
      businessExtension
      businessPhoneId
      businessPhoneNumber
      businessTitle
      cRSNameid
      cblInd
      chainCode
      city
      cityExt
      commPayCentral
      comm1CountryDialingCode
      comm1Id
      comm1PhoneCountryCode
      comm1Type
      comm1ValidYn
      comm1ValidateDate
      comm1ValidateStatus
      comm1Value
      comm2CountryDialingCode
      comm2Id
      comm2PhoneCountryCode
      comm2Type
      comm2ValidYn
      comm2ValidateDate
      comm2ValidateStatus
      comm2Value
      comm3CountryDialingCode
      comm3Id
      comm3PhoneCountryCode
      comm3Type
      comm3ValidYn
      comm3ValidateDate
      comm3ValidateStatus
      comm3Value
      commissionAccountId
      commissionAccountName
      compPreApprovalRequiredYn
      company
      companyGroupId
      contactYn
      contractNo
      contractRecvDate
      country
      countryDesc
      creditRating
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      department
      deptId
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      eMail
      eMailId
      emailFormat
      emailValidateDate
      emailValidateStatus
      emailYn
      envelopeGreeting
      faxCountryCode
      faxCountryDialingCode
      faxId
      faxNo
      faxValidYn
      first
      folioAddressId
      gender
      guestPrivYn
      hasnotes
      historyYn
      holdCode
      homePhoneId
      homePhoneNumber
      iataCompType
      iataConsortia
      iataCorpNumber
      idCountry
      idDate
      idDocumentAttachId
      idExpirationDate
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveReason
      includeInTax1099Yn
      incognitoDisplayname
      incognitoFirst
      incognitoName
      incognitoYn
      industryCode
      influence
      insertDate
      insertUser
      insertUserName
      interest
      internalBillYn
      internalPrimaryKeyIDToUniquelyIdentifyTheRow
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      language
      languageDesc
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      loggedSrepCode
      loyaltySegmentCodes
      mailList
      mailType
      mailYn
      marketResearchYn
      markets
      membershipExpirationDate
      membershipId
      membershipLevel
      membershipNameOnCard
      membershipNumber
      membershipStatus
      membershipType
      middle
      mobilePhoneId
      mobilePhoneNumber
      multipleAddressYn
      multipleCommentsYn
      multiplePhonesYn
      name
      nameComment
      nameId
      nameKeywords
      nameType
      nameTypeDesc
      name2
      name3
      nationality
      nationalityDesc
      nextStay
      organizationID
      paymentDueDays
      phoneCountryCode
      phoneCountryDialingCode
      phoneExtension
      phoneId
      phoneNo
      phoneType
      phoneValidYn
      phoneYn
      preferredRoomNo
      profession
      profileCreditLimit
      profilePrivacyFlg
      propertyActionCode
      propertyCompetitionCode
      propertyPriority
      propertyRoomsPotential
      protected
      psuedoProfileYn
      repAccountType
      repAccountsource
      repActionCode
      repIATACompType
      repInactiveReason
      repIndustryCode
      repInfluence
      repKeyword
      repMarkets
      repNameType
      repNationality
      repNationalityDescription
      repPropertyPriority
      repRoomsPotential
      repScope
      repScopeCity
      repState
      repStateDescription
      repTaxType
      repTerritory
      repTitle
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restrictReasonCode
      rnaInsertDate
      rnaUpdateDate
      salesrep
      salutation
      scope
      scopeCity
      sfirst
      smsYn
      sname
      srepCode
      srepId
      state
      stateDesc
      suffix
      summRefCc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxOffice
      taxType
      territory
      thirdPartyYn
      title
      titleName
      titleSuffix
      totalStay
      tracecode
      udfc01
      udfc02
      udfc03
      udfc04
      udfc05
      udfc06
      udfc07
      udfc08
      udfc09
      udfc10
      udfc11
      udfc12
      udfc13
      udfc14
      udfc15
      udfc16
      udfc17
      udfc18
      udfc19
      udfc20
      udfc21
      udfc22
      udfc23
      udfc24
      udfc25
      udfc26
      udfc27
      udfc28
      udfc29
      udfc30
      udfc31
      udfc32
      udfc33
      udfc34
      udfc35
      udfc36
      udfc37
      udfc38
      udfc39
      udfc40
      udfd01
      udfd02
      udfd03
      udfd04
      udfd05
      udfd06
      udfd07
      udfd08
      udfd09
      udfd10
      udfd11
      udfd12
      udfd13
      udfd14
      udfd15
      udfd16
      udfd17
      udfd18
      udfd19
      udfd20
      udfn01
      udfn02
      udfn03
      udfn04
      udfn05
      udfn06
      udfn07
      udfn08
      udfn09
      udfn10
      udfn11
      udfn12
      udfn13
      udfn14
      udfn15
      udfn16
      udfn17
      udfn18
      udfn19
      udfn20
      udfn21
      udfn22
      udfn23
      udfn24
      udfn25
      udfn26
      udfn27
      udfn28
      udfn29
      udfn30
      udfn31
      udfn32
      udfn33
      udfn34
      udfn35
      udfn36
      udfn37
      udfn38
      udfn39
      udfn40
      updateDate
      updateUser
      updateUserName
      uploadDate
      vipName
      vipStatus
      visaValidityType
      webPage
      webPageId
      xdisplayName
      xenvelopeGreeting
      xfirstName
      xmiddleName
      xname
      zipCode
    }
    profilePropertyDetails {
      actionCode
      arNumber
      autoPopulateRoutingYn
      billingInstruction
      birGuestType
      businessId
      businessRegistration
      commissionCode
      competitionCode
      currencyCode
      dSI
      departmentNote
      electronicFiscalFlag
      features
      guestType
      internalPrimaryKeyIDToUniquelyIdentifyTheRow
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastPrivacyPromptDate
      nameId
      nameTaxType
      organizationID
      paymentMethod
      potentialNights
      potentialRevenue
      priority
      productInterest
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      repActionCode
      repCompetitionCode
      repPriority
      repRoomsPotential
      roomsPotential
      specials
      taxPerc1
      taxPerc2
      taxPerc3
      taxPerc4
      taxPerc5
      vatOffsetYn
    }
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

profile_details_schema = {
    'aRCreditLimitYN': pl.Utf8,
    'accountType': pl.Utf8,
    'accountsource': pl.Utf8,
    'acctContact': pl.Utf8,
    'activeYn': pl.Utf8,
    'addrCleansedDatetime': pl.Utf8,
    'addrCleansedErrormsg': pl.Utf8,
    'addrCleansedStatus': pl.Utf8,
    'addrCleansedValstatus': pl.Utf8,
    'addrLanguageCode': pl.Utf8,
    'addrLanguageDesc': pl.Utf8,
    'addressId': pl.Float64,
    'addressType': pl.Utf8,
    'addressTypeDesc': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allOwners': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDesc': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'anonymizationDate': pl.Utf8,
    'anonymizationStatus': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'availoverYn': pl.Utf8,
    'barcode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessExtension': pl.Utf8,
    'businessPhoneId': pl.Float64,
    'businessPhoneNumber': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cRSNameid': pl.Float64,
    'cblInd': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'comm1CountryDialingCode': pl.Float64,
    'comm1Id': pl.Float64,
    'comm1PhoneCountryCode': pl.Utf8,
    'comm1Type': pl.Utf8,
    'comm1ValidYn': pl.Utf8,
    'comm1ValidateDate': pl.Utf8,
    'comm1ValidateStatus': pl.Utf8,
    'comm1Value': pl.Utf8,
    'comm2CountryDialingCode': pl.Float64,
    'comm2Id': pl.Float64,
    'comm2PhoneCountryCode': pl.Utf8,
    'comm2Type': pl.Utf8,
    'comm2ValidYn': pl.Utf8,
    'comm2ValidateDate': pl.Utf8,
    'comm2ValidateStatus': pl.Utf8,
    'comm2Value': pl.Utf8,
    'comm3CountryDialingCode': pl.Float64,
    'comm3Id': pl.Float64,
    'comm3PhoneCountryCode': pl.Utf8,
    'comm3Type': pl.Utf8,
    'comm3ValidYn': pl.Utf8,
    'comm3ValidateDate': pl.Utf8,
    'comm3ValidateStatus': pl.Utf8,
    'comm3Value': pl.Utf8,
    'commissionAccountId': pl.Float64,
    'commissionAccountName': pl.Utf8,
    'compPreApprovalRequiredYn': pl.Utf8,
    'company': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'contactYn': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'country': pl.Utf8,
    'countryDesc': pl.Utf8,
    'creditRating': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Float64,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'eMail': pl.Utf8,
    'eMailId': pl.Float64,
    'emailFormat': pl.Utf8,
    'emailValidateDate': pl.Utf8,
    'emailValidateStatus': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'faxCountryCode': pl.Utf8,
    'faxCountryDialingCode': pl.Float64,
    'faxId': pl.Float64,
    'faxNo': pl.Utf8,
    'faxValidYn': pl.Utf8,
    'first': pl.Utf8,
    'folioAddressId': pl.Float64,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'hasnotes': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'homePhoneId': pl.Float64,
    'homePhoneNumber': pl.Utf8,
    'iataCompType': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'iataCorpNumber': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idExpirationDate': pl.Utf8,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'incognitoDisplayname': pl.Utf8,
    'incognitoFirst': pl.Utf8,
    'incognitoName': pl.Utf8,
    'incognitoYn': pl.Utf8,
    'industryCode': pl.Utf8,
    'influence': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUserName': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalPrimaryKeyIDToUniquelyIdentifyTheRow': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'language': pl.Utf8,
    'languageDesc': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'loggedSrepCode': pl.Utf8,
    'loyaltySegmentCodes': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'markets': pl.Utf8,
    'membershipExpirationDate': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipNameOnCard': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipStatus': pl.Utf8,
    'membershipType': pl.Utf8,
    'middle': pl.Utf8,
    'mobilePhoneId': pl.Float64,
    'mobilePhoneNumber': pl.Utf8,
    'multipleAddressYn': pl.Utf8,
    'multipleCommentsYn': pl.Utf8,
    'multiplePhonesYn': pl.Utf8,
    'name': pl.Utf8,
    'nameComment': pl.Utf8,
    'nameId': pl.Float64,
    'nameKeywords': pl.Utf8,
    'nameType': pl.Utf8,
    'nameTypeDesc': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityDesc': pl.Utf8,
    'nextStay': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phoneCountryCode': pl.Utf8,
    'phoneCountryDialingCode': pl.Float64,
    'phoneExtension': pl.Utf8,
    'phoneId': pl.Float64,
    'phoneNo': pl.Utf8,
    'phoneType': pl.Utf8,
    'phoneValidYn': pl.Utf8,
    'phoneYn': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'profession': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profilePrivacyFlg': pl.Utf8,
    'propertyActionCode': pl.Utf8,
    'propertyCompetitionCode': pl.Utf8,
    'propertyPriority': pl.Utf8,
    'propertyRoomsPotential': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'repAccountType': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repActionCode': pl.Utf8,
    'repIATACompType': pl.Utf8,
    'repInactiveReason': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repKeyword': pl.Utf8,
    'repMarkets': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNationality': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repPropertyPriority': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repState': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxType': pl.Utf8,
    'repTerritory': pl.Utf8,
    'repTitle': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restrictReasonCode': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'salesrep': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'sfirst': pl.Utf8,
    'smsYn': pl.Utf8,
    'sname': pl.Utf8,
    'srepCode': pl.Utf8,
    'srepId': pl.Float64,
    'state': pl.Utf8,
    'stateDesc': pl.Utf8,
    'suffix': pl.Utf8,
    'summRefCc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'title': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalStay': pl.Float64,
    'tracecode': pl.Utf8,
    'udfc01': pl.Utf8,
    'udfc02': pl.Utf8,
    'udfc03': pl.Utf8,
    'udfc04': pl.Utf8,
    'udfc05': pl.Utf8,
    'udfc06': pl.Utf8,
    'udfc07': pl.Utf8,
    'udfc08': pl.Utf8,
    'udfc09': pl.Utf8,
    'udfc10': pl.Utf8,
    'udfc11': pl.Utf8,
    'udfc12': pl.Utf8,
    'udfc13': pl.Utf8,
    'udfc14': pl.Utf8,
    'udfc15': pl.Utf8,
    'udfc16': pl.Utf8,
    'udfc17': pl.Utf8,
    'udfc18': pl.Utf8,
    'udfc19': pl.Utf8,
    'udfc20': pl.Utf8,
    'udfc21': pl.Utf8,
    'udfc22': pl.Utf8,
    'udfc23': pl.Utf8,
    'udfc24': pl.Utf8,
    'udfc25': pl.Utf8,
    'udfc26': pl.Utf8,
    'udfc27': pl.Utf8,
    'udfc28': pl.Utf8,
    'udfc29': pl.Utf8,
    'udfc30': pl.Utf8,
    'udfc31': pl.Utf8,
    'udfc32': pl.Utf8,
    'udfc33': pl.Utf8,
    'udfc34': pl.Utf8,
    'udfc35': pl.Utf8,
    'udfc36': pl.Utf8,
    'udfc37': pl.Utf8,
    'udfc38': pl.Utf8,
    'udfc39': pl.Utf8,
    'udfc40': pl.Utf8,
    'udfd01': pl.Utf8,
    'udfd02': pl.Utf8,
    'udfd03': pl.Utf8,
    'udfd04': pl.Utf8,
    'udfd05': pl.Utf8,
    'udfd06': pl.Utf8,
    'udfd07': pl.Utf8,
    'udfd08': pl.Utf8,
    'udfd09': pl.Utf8,
    'udfd10': pl.Utf8,
    'udfd11': pl.Utf8,
    'udfd12': pl.Utf8,
    'udfd13': pl.Utf8,
    'udfd14': pl.Utf8,
    'udfd15': pl.Utf8,
    'udfd16': pl.Utf8,
    'udfd17': pl.Utf8,
    'udfd18': pl.Utf8,
    'udfd19': pl.Utf8,
    'udfd20': pl.Utf8,
    'udfn01': pl.Float64,
    'udfn02': pl.Float64,
    'udfn03': pl.Float64,
    'udfn04': pl.Float64,
    'udfn05': pl.Float64,
    'udfn06': pl.Float64,
    'udfn07': pl.Float64,
    'udfn08': pl.Float64,
    'udfn09': pl.Float64,
    'udfn10': pl.Float64,
    'udfn11': pl.Float64,
    'udfn12': pl.Float64,
    'udfn13': pl.Float64,
    'udfn14': pl.Float64,
    'udfn15': pl.Float64,
    'udfn16': pl.Float64,
    'udfn17': pl.Float64,
    'udfn18': pl.Float64,
    'udfn19': pl.Float64,
    'udfn20': pl.Float64,
    'udfn21': pl.Float64,
    'udfn22': pl.Float64,
    'udfn23': pl.Float64,
    'udfn24': pl.Float64,
    'udfn25': pl.Float64,
    'udfn26': pl.Float64,
    'udfn27': pl.Float64,
    'udfn28': pl.Float64,
    'udfn29': pl.Float64,
    'udfn30': pl.Float64,
    'udfn31': pl.Float64,
    'udfn32': pl.Float64,
    'udfn33': pl.Float64,
    'udfn34': pl.Float64,
    'udfn35': pl.Float64,
    'udfn36': pl.Float64,
    'udfn37': pl.Float64,
    'udfn38': pl.Float64,
    'udfn39': pl.Float64,
    'udfn40': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'updateUserName': pl.Utf8,
    'uploadDate': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'webPage': pl.Utf8,
    'webPageId': pl.Float64,
    'xdisplayName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xmiddleName': pl.Utf8,
    'xname': pl.Utf8,
    'zipCode': pl.Utf8,
}

profile_property_details_schema = {
    'actionCode': pl.Utf8,
    'arNumber': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'birGuestType': pl.Utf8,
    'businessId': pl.Utf8,
    'businessRegistration': pl.Utf8,
    'commissionCode': pl.Utf8,
    'competitionCode': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Float64,
    'departmentNote': pl.Utf8,
    'electronicFiscalFlag': pl.Utf8,
    'features': pl.Utf8,
    'guestType': pl.Float64,
    'internalPrimaryKeyIDToUniquelyIdentifyTheRow': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastPrivacyPromptDate': pl.Utf8,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentMethod': pl.Utf8,
    'potentialNights': pl.Float64,
    'potentialRevenue': pl.Float64,
    'priority': pl.Utf8,
    'productInterest': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'repActionCode': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repPriority': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'specials': pl.Utf8,
    'taxPerc1': pl.Float64,
    'taxPerc2': pl.Float64,
    'taxPerc3': pl.Float64,
    'taxPerc4': pl.Float64,
    'taxPerc5': pl.Float64,
    'vatOffsetYn': pl.Utf8,
}

```