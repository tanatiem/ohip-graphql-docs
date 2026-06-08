# ProfilesAccounts
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `profilesAccounts`
> The Profiles-Accounts subject area contains Account Room Night and Revenue statistics broken down between Group and Individual stays and can be summarized by Property Stay Date Business Segment Owner and Profile Type.
  
**Return:** [`[ProfilesAccountsType]`](#profilesaccountstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesAccountsQueryArgumentsType!`](#profilesaccountsqueryargumentstype) |  |

## Object Types

### ProfilesAccountsType

| Field | Type | Description |
| --- | --- | --- |
| profileAccountsDetails | [`ProfilesAccountsProfileAccountsDetailsType`](#profilesaccountsprofileaccountsdetailstype) | Profile Accounts Details |
| profileForecastDetails | [`ProfilesAccountsProfileForecastDetailsType`](#profilesaccountsprofileforecastdetailstype) | Profile Forecast Details |
| profileCommunicationDetails | [`ProfilesAccountsProfileCommunicationDetailsType`](#profilesaccountsprofilecommunicationdetailstype) | Profile Communication Details |
| profileCommissionDetails | [`ProfilesAccountsProfileCommissionDetailsType`](#profilesaccountsprofilecommissiondetailstype) | Profile Commission Details |
| profileRelationshipDetails | [`ProfilesAccountsProfileRelationshipDetailsType`](#profilesaccountsprofilerelationshipdetailstype) | Profile Relationship Details |
| accountMonthlyStatisticsDetails | [`ProfilesAccountsAccountMonthlyStatisticsDetailsType`](#profilesaccountsaccountmonthlystatisticsdetailstype) | Account Monthly Statistics |
| profileAddressDetails | [`ProfilesAccountsProfileAddressDetailsType`](#profilesaccountsprofileaddressdetailstype) | Profile Address Details |
| accountDailyStatisticsDetails | [`ProfilesAccountsAccountDailyStatisticsDetailsType`](#profilesaccountsaccountdailystatisticsdetailstype) | Account Daily Statistics |
| profileNoteDetails | [`ProfilesAccountsProfileNoteDetailsType`](#profilesaccountsprofilenotedetailstype) | Profile Note Details |
| profileRelationshipHierDetails | [`ProfilesAccountsProfileRelationshipHierDetailsType`](#profilesaccountsprofilerelationshiphierdetailstype) | Profile Relationship Hier Details |
| profilePreferenceDetails | [`ProfilesAccountsProfilePreferenceDetailsType`](#profilesaccountsprofilepreferencedetailstype) | Profile Preference Details |
| accountYearlyStatisticsDetails | [`ProfilesAccountsAccountYearlyStatisticsDetailsType`](#profilesaccountsaccountyearlystatisticsdetailstype) | Account Yearly Statistics |
| profileOwnerDetails | [`ProfilesAccountsProfileOwnerDetailsType`](#profilesaccountsprofileownerdetailstype) | Profile Owner Details |
| reservationDailyStatisticsDetails | [`ProfilesAccountsReservationDailyStatisticsDetailsType`](#profilesaccountsreservationdailystatisticsdetailstype) | Reservation Daily Statistics |
| saleProfileOwnerDetails | [`ProfilesAccountsSaleProfileOwnerDetailsType`](#profilesaccountssaleprofileownerdetailstype) | Sales Goals Profile Owner Details |
| blockDetails | [`ProfilesAccountsBlockDetailsType`](#profilesaccountsblockdetailstype) | Block |
| profilesAccountsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileAccountsDetailsType

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
| inactiveDate | `DateTime` | Inactive Date |
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
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
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

### ProfilesAccountsProfileForecastDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralForecastFBRevenue | `Float` | Central Forecast FB Revenue |
| centralForecastOtherRevenue | `Float` | Central Forecast Other Revenue |
| centralForecastRoomAverageRate | `Float` | Central Forecast Room Average Rate |
| centralForecastRoomRevenue | `Float` | Central Forecast Room Revenue |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| forecastFBRevenue | `Float` | Forecast FB Revenue |
| forecastInsertDate | `DateTime` | Forecast Insert Date |
| forecastInsertUser | `Float` | Forecast Insert User |
| forecastOtherRevenue | `Float` | Forecast Other Revenue |
| forecastPeriodCode | `String` | Forecast Period Code |
| forecastPeriodEnd | `Date` | Period End Date |
| forecastPeriodStart | `Date` | Period Start Date |
| forecastRoomAverageRate | `Float` | Average Room Rate |
| forecastRoomNights | `Float` | Forecast Room Nights |
| forecastRoomRevenue | `Float` | Forecast Room Revenue |
| forecastSplitMode | `String` | Specifies the forecast split mode. Possible values are: GROUP NON-GROUP and blank. |
| forecastType | `String` | Forecast Type |
| forecastUpdateDate | `DateTime` | Forecast Update Date |
| forecastUpdateUser | `Float` | Forecast Update User |
| inactiveDate | `DateTime` | Inactive Date |
| insertUserName | `String` | The name of the user who created the record. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| linkChainCode | `String` | Link Chain Code |
| linkId | `Float` | Link ID |
| linkInsertDate | `DateTime` | Link Insert Date |
| linkInsertUser | `Float` | Link Insert User |
| linkLaptopChange | `Float` | Link Laptop Change |
| linkType | `String` | Link Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| period | `String` | Period |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYn | `String` | Primary Y/N |
| profileId | `Float` | Profile ID |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| relationship | `String` | Relationship |
| toType | `String` | To Type |
| updateUserName | `String` | Update User Name |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileCommunicationDetailsType

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

### ProfilesAccountsProfileCommissionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountId | `Float` | Account ID |
| centralCommissionCode | `String` | Central Commission Code |
| centralCommissionCodeDescription | `String` | Central Commission Code Description |
| commissionCode | `String` | Commission Code |
| commissionCodeDescription | `String` | Commission Code Description |
| createdByUser | `Float` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileRelationshipDetailsType

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

### ProfilesAccountsAccountMonthlyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adr | `Float` | Average Daily Rate |
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
| cancels | `Float` | Cancels |
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
| centralCurrencyCode | `String` | Central Currency Code |
| centralFBRevenueNet | `Float` | Central FB Revenue Net |
| centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenueNet | `Float` | FB Revenue Net |
| fBRevenueTax | `Float` | FB Revenue Tax |
| groupCancels | `Float` | Group Number of Cancellations. |
| groupFBRevenueNet | `Float` | Group F&B Revenue. |
| groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| groupNoShows | `Float` | Group Number of No Shows. |
| groupOtherRevenueNet | `Float` | Group Other Revenue. |
| groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| groupRoomNights | `Float` | Group Number of Nights. |
| groupRoomRevenueNet | `Float` | Group Room Revenue. |
| groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| groupStays | `Float` | Group Number of Stays. |
| groupTotalRevenueNet | `Float` | Group Total Revenue. |
| groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| grpAverageDailyRate | `Float` | Group Adr |
| individualCancels | `Float` | Individual Cancels |
| individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| individualNoShows | `Float` | Individual Number Shows |
| individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| individualRoomNights | `Float` | Individual Room Nights |
| individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| individualStays | `Float` | Individual Stays |
| individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
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
| noShows | `Float` | Number Shows |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otherRevenueNet | `Float` | Other Revenue Net |
| otherRevenueTax | `Float` | Other Revenue Tax |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| roomRevenueNet | `Float` | Room Revenue Net |
| roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| stayedBooked | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| stays | `Float` | Stays |
| totalAdr | `Float` | Total Average Daily Rate |
| totalRevenueNet | `Float` | Total Revenue Net |
| totalRevenueTax | `Float` | Total Revenue Tax |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileAddressDetailsType

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

### ProfilesAccountsAccountDailyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adr | `Float` | Average Daily Rate |
| cancels | `Float` | Cancels |
| centralFBRevenueNet | `Float` | Central FB Revenue Net |
| centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| centralXchangeDate | `Date` | Central Exchange Date |
| centralXchangeRate | `Float` | Central Exchange Rate |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenueNet | `Float` | FB Revenue Net |
| fBRevenueTax | `Float` | FB Revenue Tax |
| groupCancels | `Float` | Group Number of Cancellations. |
| groupFBRevenueNet | `Float` | Group F&B Revenue. |
| groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| groupNoShows | `Float` | Group Number of No Shows. |
| groupOtherRevenueNet | `Float` | Group Other Revenue. |
| groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| groupRoomNights | `Float` | Group Number of Nights. |
| groupRoomRevenueNet | `Float` | Group Room Revenue. |
| groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| groupStays | `Float` | Group Number of Stays. |
| groupTotalRevenueNet | `Float` | Group Total Revenue. |
| groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| grpAverageDailyRate | `Float` | Group Adr |
| individualCancels | `Float` | Individual Cancels |
| individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| individualNoShows | `Float` | Individual Number Shows |
| individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| individualRoomNights | `Float` | Individual Room Nights |
| individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| individualStays | `Float` | Individual Stays |
| individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
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
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otherRevenueNet | `Float` | Other Revenue Net |
| otherRevenueTax | `Float` | Other Revenue Tax |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| roomRevenueNet | `Float` | Room Revenue Net |
| roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| stayDate | `Date` | Stay Date |
| stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| stayYear | `Float` | Year of Summary. |
| stays | `Float` | Stays |
| totalAdr | `Float` | Total Average Daily Rate |
| totalRevenueNet | `Float` | Total Revenue Net |
| totalRevenueTax | `Float` | Total Revenue Tax |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileNoteDetailsType

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

### ProfilesAccountsProfileRelationshipHierDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bottomId | `Float` | Level Ten Name ID. |
| bottomNameType | `String` | Lowest Level Name Type. |
| chainCode | `String` | Chain Code |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| relToType | `String` | Relationship with Type. |
| relType | `String` | Relationship Type. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| topId | `Float` | Master Name ID. |
| totalLevels | `Float` | Current Level or Record in relationship hierarchy. |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfilePreferenceDetailsType

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

### ProfilesAccountsAccountYearlyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adr | `Float` | Average Daily Rate |
| cCcRoomRevenueTax | `Float` | Central Cc Room Revenue Tax |
| cCcTotalRevenue | `Float` | Central Cc Total Revenue |
| cCcTotalRevenueTax | `Float` | Central Cc Total Revenue Tax |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cancels | `Float` | Cancels |
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
| centralCcFbRevenue | `Float` | Central Cc FB Revenue |
| centralCcFbRevenueTax | `Float` | Central Cc FB Revenue Tax |
| centralCcGrpFBRevenue | `Float` | Central Cc Group Fb Revenue |
| centralCcGrpFBRevenueTax | `Float` | Central Cc Group Fb Revenue Tax |
| centralCcGrpMiscellaneousRevenue | `Float` | Central Cc Group Misc Revenue |
| centralCcGrpMiscellaneousRevenueTax | `Float` | Central Cc Group Misc Revenue Tax |
| centralCcGrpOtherRevenue | `Float` | Central Cc Group Other Revenue |
| centralCcGrpOtherRevenueTax | `Float` | Central Cc Group Other Revenue Tax |
| centralCcGrpRoomRevenue | `Float` | Central Cc Group Room Revenue |
| centralCcGrpRoomRevenueTax | `Float` | Central Cc Group Room Revenue Tax |
| centralCcGrpTotalRevenue | `Float` | Central Cc Group Total Revenue |
| centralCcGrpTotalRevenueTax | `Float` | Central Cc Group Total Revenue Tax |
| centralCcMiscRevenue | `Float` | Central Cc Miscellaneous Revenue |
| centralCcMiscRevenueTax | `Float` | Central Cc Miscellaneous Revenue Tax |
| centralCcOtherRevenue | `Float` | Central Cc Other Revenue |
| centralCcOtherRevenueTax | `Float` | Central Cc Other Revenue Tax |
| centralCcRoomRevenue | `Float` | Central Cc Room Revenue |
| centralCurrencyCode | `String` | Central Currency Code |
| centralFBRevenueNet | `Float` | Central FB Revenue Net |
| centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| contextCd | `String` | Context Cd |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fBRevenueNet | `Float` | FB Revenue Net |
| fBRevenueTax | `Float` | FB Revenue Tax |
| groupCancels | `Float` | Group Number of Cancellations. |
| groupFBRevenueNet | `Float` | Group F&B Revenue. |
| groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| groupNoShows | `Float` | Group Number of No Shows. |
| groupOtherRevenueNet | `Float` | Group Other Revenue. |
| groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| groupRoomNights | `Float` | Group Number of Nights. |
| groupRoomRevenueNet | `Float` | Group Room Revenue. |
| groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| groupStays | `Float` | Group Number of Stays. |
| groupTotalRevenueNet | `Float` | Group Total Revenue. |
| groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| grpAverageDailyRate | `Float` | Group Adr |
| individualCancels | `Float` | Individual Cancels |
| individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| individualNoShows | `Float` | Individual Number Shows |
| individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| individualRoomNights | `Float` | Individual Room Nights |
| individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| individualStays | `Float` | Individual Stays |
| individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
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
| noShows | `Float` | Number Shows |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otherRevenueNet | `Float` | Other Revenue Net |
| otherRevenueTax | `Float` | Other Revenue Tax |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| roomRevenueNet | `Float` | Room Revenue Net |
| roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| stayYear | `Float` | Year of Summary. |
| stayedBooked | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| stays | `Float` | Stays |
| totalAdr | `Float` | Total Average Daily Rate |
| totalRevenueNet | `Float` | Total Revenue Net |
| totalRevenueTax | `Float` | Total Revenue Tax |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileOwnerDetailsType

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

### ProfilesAccountsReservationDailyStatisticsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| agentId | `Float` | Agent ID |
| agentprofileid | `Float` | Agentprofileid |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentid | `Float` | Block ID |
| arrivalPersons | `Float` | Arrival Persons |
| arrivalRooms | `Float` | Arrival Rooms |
| beginDate | `Date` | Begin Date |
| biReservationNameId | `Float` | Bi Resv Name ID |
| birthDate | `Date` | Birth Date |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDate | `Date` | Business Date |
| businessDateCreated | `Date` | Business Date Created |
| cAdvanceTotalOtherTax | `Float` | Central Adv Total Other Tax |
| cCashRoomRevenue | `Float` | Central Cash Room Revenue |
| cCompRoomRevenue | `Float` | Central Comp Room Revenue |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFlaggedFoodRevenue | `Float` | Central Flgd Food Revenue |
| cFlaggedNonRevenue | `Float` | Central Flgd Non Revenue |
| cFlaggedOtherRevenue | `Float` | Central Flgd Other Revenue |
| cFlaggedRoomRevenue | `Float` | Central Flgd Room Revenue |
| cFlaggedTotalFoodTax | `Float` | Central Flgd Total Food Tax |
| cFlaggedTotalNonRevenueTax | `Float` | Central Flgd Total Non Revenue Tax |
| cFlaggedTotalOtherTax | `Float` | Central Flgd Total Other Tax |
| cFlaggedTotalRevenue | `Float` | Central Flgd Total Revenue |
| cFlaggedTotalRoomTax | `Float` | Central Flgd Total Room Tax |
| cFlaggedTotalTax | `Float` | Central Flgd Total Tax |
| cPrAdvanceTotalFoodTax | `Float` | Central Pr Adv Total Food Tax |
| cRateAmount | `Float` | Central Rate Amount |
| cRsAdvanceFoodRevenue | `Float` | Central Rs Adv Food Revenue |
| cRsAdvanceFoodTax | `Float` | Central Rs Adv Food Tax |
| cRsAdvanceNonRevenue | `Float` | Central Rs Adv Non Revenue |
| cRsAdvanceNonRevenueTax | `Float` | Central Rs Adv Non Revenue Tax |
| cRsAdvanceOtherRevenue | `Float` | Central Rs Adv Other Revenue |
| cRsAdvanceOtherTax | `Float` | Central Rs Adv Other Tax |
| cRsAdvanceRoomRevenue | `Float` | Central Rs Adv Room Revenue |
| cRsAdvanceRoomTax | `Float` | Central Rs Adv Room Tax |
| cRsAdvanceTotalRevenue | `Float` | Central Rs Adv Total Revenue |
| cRsAdvanceTotalTax | `Float` | Central Rs Adv Total Tax |
| cUpsoldRevenue | `Float` | Central Upsold Revenue |
| cancellationDate | `DateTime` | Cancellation Date |
| cancelledPersons | `Float` | Cancelled Persons |
| cancelledReservations | `Float` | Cancelled Reservations |
| cancelledRooms | `Float` | Cancelled Rooms |
| cashRoomNts | `Float` | Cash Room Nts |
| cashRoomRevenue | `Float` | Cash Room Revenue |
| centralCurrencyCode | `String` | Central Currency Code |
| centralDistributedFoodRevenue | `Float` | Central Distributed Food Revenue |
| centralDistributedFoodRevenueAsPayee | `Float` | Central Distributed Food Revenue (as Payee |
| centralDistributedNonRevenue | `Float` | Central Distributed Non Revenue |
| centralDistributedNonRevenueAsPayee | `Float` | Central Distributed Non-Revenue (as Payee |
| centralDistributedOtherRevenue | `Float` | Central Distributed Other Revenue |
| centralDistributedOtherRevenueAsPayee | `Float` | Central Distributed Other Revenue (as Payee |
| centralDistributedRoomRevenue | `Float` | Central Distributed Room Revenue |
| centralDistributedRoomRevenueAsPayee | `Float` | Central Distributed Room Revenue (as Payee |
| centralDistributedTotalFoodTaxAsPayee | `Float` | Central Distributed Total Food Tax (as Payee |
| centralDistributedTotalNonRevenueTax | `Float` | Central Distributed Total Non Revenue Tax |
| centralDistributedTotalNonRevenueTaxAsPayee | `Float` | Central Distributed Total Non-Revenue Tax (as Payee |
| centralDistributedTotalOtherTaxAsPayee | `Float` | Central Distributed Total Other Tax (as Payee |
| centralDistributedTotalRevenue | `Float` | Central Distributed Total Revenue |
| centralDistributedTotalRevenueAsPayee | `Float` | Central Distributed Total Revenue (as Payee |
| centralDistributedTotalRoomTax | `Float` | Central Distributed Total Room Tax |
| centralDistributedTotalRoomTaxAsPayee | `Float` | Central Distributed Total Room Tax (as Payee |
| centralDistributedTotalTax | `Float` | Central Distributed Total Tax |
| centralDistributedTotalTaxAsPayee | `Float` | Central Distributed Total Tax (as Payee |
| centralExchangeRate | `Float` | Central Exchange Rate |
| centralFoodRevenue | `Float` | Central Food Revenue |
| centralFoodRevenueAsPayee | `Float` | Central Food Revenue (as Payee |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralNonRevenue | `Float` | Central Non Revenue |
| centralNonRevenueAsPayee | `Float` | Central Non-Revenue (as Payee |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
| centralOriginalRoomType | `String` | Central Original Room Type |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralOtherRevenueAsPayee | `Float` | Central Other Revenue (as Payee |
| centralPackageFoodRevenue | `Float` | Central Package Food Revenue |
| centralPackageFoodRevenueAsPayee | `Float` | Central Package Food Revenue (as Payee |
| centralPackageNonRevenue | `Float` | Central Package Non Revenue |
| centralPackageNonRevenueAsPayee | `Float` | Central Package Non-Revenue (as Payee |
| centralPackageOtherRevenue | `Float` | Central Package Other Revenue |
| centralPackageOtherRevenueAsPayee | `Float` | Central Package Other Revenue (as Payee |
| centralPackageRoomRevenue | `Float` | Central Package Room Revenue |
| centralPackageRoomRevenueAsPayee | `Float` | Central Package Room Revenue (as Payee |
| centralRateCategory | `String` | Central Rate Category |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomRevenueAsPayee | `Float` | Central Room Revenue (as Payee |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| centralTotalFoodTax | `Float` | Central Total Food Tax |
| centralTotalFoodTaxGeneratedAsPayee | `Float` | Central Total Food Tax Generated (as Payee |
| centralTotalNonRevenueTax | `Float` | Central Total Non Revenue Tax |
| centralTotalNonRevenueTaxAsPayee | `Float` | Central Total Non-Revenue Tax (as Payee |
| centralTotalOtherTax | `Float` | Central Total Other Tax |
| centralTotalOtherTaxAsPayee | `Float` | Central Total Other Tax (as Payee |
| centralTotalPackageRevenue | `Float` | Central Total Package Revenue |
| centralTotalPackageRevenueAsPayee | `Float` | Central Total Package Revenue (as Payee |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRevenueAsPayee | `Float` | Central Total Revenue (as Payee |
| centralTotalRoomTax | `Float` | Central Total Room Tax |
| centralTotalRoomTaxAsPayee | `Float` | Central Total Room Tax (as Payee |
| centralTotalTax | `Float` | Central Total Tax |
| centralTotalTaxAsPayee | `Float` | Central Total Tax (as Payee |
| centralcurrencyid | `String` | Centralcurrencyid |
| channelid | `String` | Channelid |
| children | `Float` | Children |
| childrenTaxFree | `Float` | Children Tax Free |
| children1 | `Float` | Children1 |
| children2 | `Float` | Children2 |
| children3 | `Float` | Children3 |
| children4 | `Float` | Children4 |
| children5 | `Float` | Children5 |
| city | `String` | City |
| cityid | `String` | Cityid |
| compRoomNts | `Float` | Comp Room Nts |
| compRoomRevenue | `Float` | Comp Room Revenue |
| companyId | `Float` | Company ID |
| companyProfileID | `Float` | Company Profile ID |
| companyProfileName | `String` | Company Profile Name |
| compflag | `String` | Compflag |
| complimentaryYN | `String` | Complimentary YN |
| contactId | `Float` | Contact ID |
| contactProfileID | `Float` | Contact Profile ID |
| contactflag | `String` | Contactflag |
| country | `String` | Country |
| countryMainGroup | `String` | Country Main Group |
| countryName | `String` | Country Name |
| countrygroupid | `String` | Countrygroupid |
| countryid | `String` | Countryid |
| cribs | `Float` | Cribs |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayUsePersons | `Float` | Day Use Persons |
| dayUseReservations | `Float` | Day Use Reservations |
| dayUseRooms | `Float` | Day Use Rooms |
| deletedFlag | `String` | Deleted Flag |
| departurePersons | `Float` | Departure Persons |
| departureRooms | `Float` | Departure Rooms |
| distributedFoodRevenue | `Float` | Distributed Food Revenue |
| distributedFoodRevenueAsPayee | `Float` | Distributed Food Revenue (as Payee |
| distributedNonRevenue | `Float` | Distributed Non Revenue |
| distributedNonRevenueAsPayee | `Float` | Distributed Non-Revenue (as Payee |
| distributedOtherRevenue | `Float` | Distributed Other Revenue |
| distributedOtherRevenueAsPayee | `Float` | Distributed Other Revenue (as Payee |
| distributedRoomRevenue | `Float` | Distributed Room Revenue |
| distributedRoomRevenueAsPayee | `Float` | Distributed Room Revenue (as Payee |
| distributedTotalFoodTaxAsPayee | `Float` | Distributed Total Food Tax as Payee |
| distributedTotalNonRevenueTax | `Float` | Distributed Total Non Revenue Tax |
| distributedTotalNonRevenueTaxAsPayee | `Float` | Distributed Total Non-Revenue Tax (as Payee |
| distributedTotalOtherTax | `Float` | Distributed Total Other Tax |
| distributedTotalOtherTaxAsPayee | `Float` | Distributed Total Other Tax (as Payee |
| distributedTotalRevenue | `Float` | Distributed Total Revenue |
| distributedTotalRevenueAsPayee | `Float` | Distributed Total Revenue (as Payee |
| distributedTotalRoomTax | `Float` | Distributed Total Room Tax |
| distributedTotalRoomTaxAsPayee | `Float` | Distributed Total Room Tax (as Payee |
| distributedTotalTax | `Float` | Distributed Total Tax |
| distributedTotalTaxAsPayee | `Float` | Distributed Total Tax (as Payee |
| district | `String` | District |
| dueOutYn | `String` | Due Out Y/N |
| dueoutflag | `String` | Dueoutflag |
| endDate | `Date` | End Date |
| endbusinessdate | `Date` | Endbusinessdate |
| extendedStayTier | `Float` | Extended stay tier of the reservation on the business date. Based on the length of stay and the rate tier configuration if active or OPERA standard rate tiers. |
| extraBeds | `Float` | Extra Beds |
| fiscalregioncode | `String` | Fiscalregioncode |
| flgdFoodRevenue | `Float` | Flagged Food Revenue |
| flgdNonRevenue | `Float` | Flagged Non Revenue |
| flgdOtherRevenue | `Float` | Flagged Other Revenue |
| flgdRoomRevenue | `Float` | Flagged Room Revenue |
| flgdTotalFoodTax | `Float` | Flagged Total Food Tax |
| flgdTotalNonRevenueTax | `Float` | Flagged Total Non Revenue Tax |
| flgdTotalOtherTax | `Float` | Flagged Total Other Tax |
| flgdTotalRevenue | `Float` | Flagged Total Revenue |
| flgdTotalRoomTax | `Float` | Flagged Total Room Tax |
| flgdTotalTax | `Float` | Flagged Total Tax |
| foodRevenue | `Float` | Food Revenue |
| foodRevenueAsPayee | `Float` | Food Revenue (as Payee |
| freqflyermembtype | `String` | Freqflyermembtype |
| freqguestmembtype | `String` | Freqguestmembtype |
| groupId | `Float` | Group ID |
| groupProfileID | `Float` | Group Profile ID |
| groupProfileName | `String` | Group Profile Name |
| guestProfileID | `Float` | Guest Profile ID |
| gueststatusid | `String` | Gueststatusid |
| houseUseYn | `String` | House Use Y/N |
| houseuseflag | `String` | Houseuseflag |
| insertDate | `DateTime` | Insert Date |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalContactprofileid | `Float` | Contactprofileid |
| internalDeletedflag | `String` | Deleted Flag |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalMembershipid | `Float` | Membershipid |
| internalReservationNameId | `Float` | Resv Name ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketgroupid | `String` | Marketgroupid |
| marketid | `String` | Marketid |
| membershipCardNo | `String` | Membership Card Number |
| membershipId | `Float` | Membership ID |
| multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| nationality | `String` | Nationality |
| nationalityCode | `String` | Nationality Code |
| nationalityid | `String` | Nationalityid |
| nights | `Float` | Nights |
| noShowReservations | `Float` | Number Show Reservations |
| noShowPersons | `Float` | No-Show Persons |
| noShowRooms | `Float` | No-Show Rooms |
| nonRevenue | `Float` | Non Revenue |
| nonRevenueAsPayee | `Float` | Non-Revenue (as Payee |
| numberOfStays | `Float` | No of Stays |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| originalEndDate | `Date` | Original End Date |
| originalRoomCategory | `String` | Stores the room type associated with the reservation at the moment of booking. |
| otherRevenue | `Float` | Other Revenue |
| otherRevenueAsPayee | `Float` | Other Revenue (as Payee |
| outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| outOfServiceRooms | `Float` | Out of Service Rooms |
| ownerRentalYn | `String` | Owner Rental Y/N |
| ownerfriendfamilyflag | `String` | Ownerfriendfamilyflag |
| ownerrentalflag | `String` | Ownerrentalflag |
| packageFoodRevenue | `Float` | Package Food Revenue |
| packageFoodRevenueAsPayee | `Float` | Package Food Revenue (as Payee |
| packageNonRevenue | `Float` | Package Non Revenue |
| packageNonRevenueAsPayee | `Float` | Package Non-Revenue (as Payee |
| packageOtherRevenue | `Float` | Package Other Revenue |
| packageOtherRevenueAsPayee | `Float` | Package Other Revenue (as Payee |
| packageRoomRevenue | `Float` | Package Room Revenue |
| packageRoomRevenueAsPayee | `Float` | Package Room Revenue (as Payee |
| parentCompanyId | `Float` | Parent Company ID |
| parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| physicalQuantity | `Float` | Physical Quantity |
| physicalRooms | `Float` | Physical Rooms |
| prAdvTotalFoodTax | `Float` | Pr Advance Total Food Tax |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYn | `Float` | Primary Y/N |
| primaryflag | `Float` | Primaryflag |
| profiledailytotalid | `Float` | Profiledailytotalid |
| profileid | `Float` | Profileid |
| promotionCode | `String` | Promotion Code |
| promotionCodeDesc | `String` | Promotion Code Description |
| promotionid | `String` | Promotionid |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| pseudoroomflag | `String` | Pseudoroomflag |
| quantity | `Float` | Quantity |
| rateAmount | `Float` | Rate Amount |
| rateCategory | `String` | Rate Category |
| rateCode | `String` | Rate Code |
| ratecategoryid | `String` | Ratecategoryid |
| ratecodeid | `String` | Ratecodeid |
| regionCode | `String` | Region Code |
| regionid | `String` | Regionid |
| repPromotionCode | `String` | Reporting Promotion Code |
| repPromotionCodeDescription | `String` | Reporting Promotion Code Desc |
| reservationArrivals | `Float` | Reservation Arrivals |
| reservationDate | `Date` | Reservation Date |
| reservationNameID | `Float` | Reservation Name ID |
| reservationNights | `Float` | Reservation Nights |
| reservationNumberOfStays | `Float` | Reservation No of Stays |
| reservationStatus | `String` | Reservation Status |
| reservationid | `Float` | Reservationid |
| resvenddate | `Date` | Resvenddate |
| resvinsertsource | `String` | Resvinsertsource |
| resvinsertsourcetype | `String` | Resvinsertsourcetype |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomAdults | `Float` | Room Adults |
| roomCategory | `String` | Room Category |
| roomChildren | `Float` | Room Children |
| roomClass | `String` | Room Class |
| roomNights | `Float` | Room Nights |
| roomReservationStatus | `String` | Room Reservation Status |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueAsPayee | `Float` | Room Revenue (as Payee |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| roomid | `String` | Roomid |
| rsAdvFoodRevenue | `Float` | Distributed food revenue generated as staying guest. |
| rsAdvFoodTax | `Float` | Distributed food tax generated as staying guest. |
| rsAdvNonRevenue | `Float` | Distributed non revenue generated as staying guest. |
| rsAdvNonRevenueTax | `Float` | Distributed non-revenue tax generated as staying guest |
| rsAdvOtherRevenue | `Float` | Distributed other revenue generated as staying guest. |
| rsAdvOtherTax | `Float` | Distributed other tax generated as staying guest. |
| rsAdvRoomRevenue | `Float` | Distributed room revenue generated as staying guest. |
| rsAdvRoomTax | `Float` | Distributed room tax generated as staying guest. |
| rsAdvTotalRevenue | `Float` | Distributed total revenue generated as staying guest. |
| rsAdvTotalTax | `Float` | Distributed total tax amount generated as staying guest. |
| singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceProfId | `Float` | Source Prof ID |
| sourceProfileID | `Float` | Source Profile ID |
| sourcegroupid | `String` | Sourcegroupid |
| sourceid | `String` | Sourceid |
| sourceprofprofileid | `Float` | Sourceprofprofileid |
| stateCode | `String` | State Code |
| stateid | `String` | Stateid |
| stayAdults | `Float` | Stay Adults |
| stayChildren | `Float` | Stay Children |
| stayPersons | `Float` | Stay Persons |
| totalFoodTax | `Float` | Total Food Tax |
| totalFoodTaxGeneratedAsPayee | `Float` | Total Food Tax Generated (as Payee |
| totalNonRevenueTax | `Float` | Total Non Revenue Tax |
| totalNonRevenueTaxAsPayee | `Float` | Total Non-Revenue Tax (as Payee |
| totalOtherTax | `Float` | Total Other Tax |
| totalOtherTaxAsPayee | `Float` | Total Other Tax (as Payee |
| totalPackageRevenue | `Float` | Total Package Revenue |
| totalPackageRevenueAsPayee | `Float` | Total Package Revenue (as Payee |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueAsPayee | `Float` | Total Revenue (as Payee |
| totalRoomTax | `Float` | Total Room Tax |
| totalRoomTaxAsPayee | `Float` | Total Room Tax (as Payee |
| totalTax | `Float` | Total Tax |
| totalTaxAsPayee | `Float` | Total Tax (as Payee |
| travelAgentProfileID | `Float` | Travel Agent Profile ID |
| travelAgentProfileName | `String` | Travel Agent Profile Name |
| updateDate | `DateTime` | Update Date |
| upsoldRevenue | `Float` | Upsold Revenue |
| vIPStatus | `String` | VIP Status |
| walkinYn | `String` | Walkin Y/N |
| walkinflag | `String` | Walkinflag |
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### ProfilesAccountsSaleProfileOwnerDetailsType

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
| inactiveDate | `Date` | Inactive Date |
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
| property | `String` | Indicates if the value set for the specific property. |
| relationship | `String` | Relationship |
| relationshipid | `String` | Relationshipid |
| resort | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| saleProfileOwnerId | `Float` | Sale Profile Owner ID |
| toType | `String` | To Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userId | `Float` | User ID |

[⬆ Back to Query](#query)

---

### ProfilesAccountsBlockDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionId | `Float` | Action ID |
| actualAverageRoomRate | `Float` | Actual Average Room Rate |
| actualFBRevenue | `Float` | Actual F&B Revenue |
| actualOtherRevenue | `Float` | Other revenue |
| actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| actualRoomRevenue | `Float` | Actual revenue of the room |
| addInfo | `String` | Add Info |
| agentContactNameId | `Float` | Agent Contact Name ID |
| agentNameId | `Float` | Agent Name ID |
| agentprofileid | `Float` | Agentprofileid |
| allAliases | `String` | All Aliases |
| allBlockOwners | `String` | All Block Owners |
| allCateringOwners | `String` | All Catering Owners |
| allCompanyContacts | `String` | All Company Contacts |
| allRateCodes | `String` | All Rate Codes |
| allRoomOwners | `String` | All Room Owners |
| allRoomPools | `String` | All Room Pools |
| allRoomTypes | `String` | All Room Types |
| allSourceContacts | `String` | All Source Contacts |
| allTravelAgentContacts | `String` | All Travel Agent Contacts |
| allotmentOrigin | `String` | Allotment Origin |
| allotmentType | `String` | Type of Block alloted for the group. |
| allotmentcurrencyid | `String` | Allotmentcurrencyid |
| allotmentid | `Float` | Block ID |
| allowPickup | `String` | Allow a pickup for a group with this booking status |
| alternateBlockName | `String` | Multi Byte Description Field |
| alternateDates | `String` | Alternate Dates |
| arrivalTime | `DateTime` | Arrival Time |
| attachmentURL | `String` | URL pointing to Lead Attachments. |
| attendeesGuaranteed | `Float` | Attendees Guaranteed |
| autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| averageRate | `Float` | Average Rate |
| bEOLastPrint | `DateTime` | Date when the BEO report was last printed for this business block. |
| beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| blockAlias | `String` | Block Alias |
| blockCode | `String` | Block Code |
| blockDateActual | `Date` | Block Date Actual |
| blockDateDefinite | `DateTime` | Block Date Definite |
| blockDateProspect | `DateTime` | Block Date Prospect |
| blockDateTentative | `DateTime` | Block Date Tentative |
| blockDescription | `String` | Block Description |
| blockID | `Float` | Block ID |
| blockMode | `String` | Classifies this allotment record: MASTER_ALLOCATION SUB_ALLOCATION SUB_BOOKING SUB_TOUR SUB_ITINERARY |
| blockOwnerCode | `String` | Block Owner Code |
| blockOwnerFullName | `String` | Block Owner Full Name |
| blockPackage | `String` | Block Package |
| blockPackageDescription | `String` | Block Package Description |
| blockStatus | `String` | Block Status |
| blockStatusDescription | `String` | Block Status Description |
| blockTypeCode | `String` | Block Type Code |
| blockTypeCodeDescription | `String` | Block Type Code Description |
| blockpackageid | `String` | Blockpackageid |
| bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| bookingMethodOrderBy | `Float` | Booking Method Order By |
| bookingStatusOrder | `Float` | Booking Status Order |
| bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| bookingTypeDescription | `String` | Booking Type Description |
| bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| bookingsourceid | `String` | Bookingsourceid |
| bookingstatusid | `String` | Bookingstatusid |
| bookingtypeid | `String` | Bookingtypeid |
| breakfastDescription | `String` | Breakfast Description |
| breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastIncluded | `String` | Breakfast Included |
| breakfastPrice | `Float` | Breakfast Price |
| bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| bwiUrl | `String` | URL populated bu CRS. |
| cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| cBreakfastPrice | `Float` | Central Bfst Price |
| cCompRoomValue | `Float` | Central Comp Room Value |
| cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFBCommission1 | `Float` | Central Fb Commission 1 |
| cFBCommission2 | `Float` | Central Fb Commission 2 |
| cPorteragePrice | `Float` | Central Porterage Price |
| cRoomCommission1 | `Float` | Central Rm Commission 1 |
| cRoomCommission2 | `Float` | Central Rm Commission 2 |
| cServiceCharge | `Float` | Central Service Charge |
| cServiceFee | `Float` | Central Service Fee |
| cRSGtdYn | `String` | CRS Guaranteed Y/N |
| cancelRule | `String` | Not Used |
| canceldestinationid | `String` | Canceldestinationid |
| cancellationDestination | `String` | Cancellation Destination |
| cancellationDestinationDescription | `String` | Cancellation Destination Description |
| cancellationNumber | `Float` | Cancellation Number |
| cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| cancellationreasonid | `String` | Cancellationreasonid |
| catCutoff | `Date` | Catering Cutoff |
| catDateProspect | `DateTime` | Cat Date Prospect |
| catOwner | `Float` | Catering Owner |
| catOwnerProperty | `String` | Property of Catering Owner |
| catReturnToInventory | `String` | Cat Return To Inventory |
| catStartingStatus | `String` | Cat Starting Status |
| catcurrencyid | `String` | Catcurrencyid |
| cateringCancellationDate | `Date` | Catering Cancellation Date |
| cateringCancellationDescription | `String` | Catering Cancellation Description |
| cateringCancellationNumber | `Float` | Catering Cancellation Number |
| cateringCancellationReason | `String` | Catering Cancellation Reason |
| cateringCurrency | `String` | Catering Currency |
| cateringDateActual | `Date` | Catering Date Actual |
| cateringDecisionDate | `Date` | Catering Decision Date |
| cateringDeductInventory | `String` | Catering Deduct Inventory |
| cateringExchangeRate | `Float` | Catering Exchange Rate |
| cateringFollowupDate | `Date` | Catering Followup Date |
| cateringOnlyYN | `String` | Catering only Revenue. |
| cateringOrderBy | `Float` | Catering Order By |
| cateringOwnerCode | `String` | Catering Owner Code |
| cateringOwnerFullName | `String` | Catering Owner Full Name |
| cateringPkgsYn | `String` | Catering Pkgs Y/N |
| cateringQuoteCurrency | `String` | Catering Quote Currency |
| cateringStatus | `String` | Catering Status |
| cateringStatusColor | `String` | Catering Status Color |
| cateringStatusDescription | `String` | Catering Status Description |
| cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| cateringcurrencyid | `String` | Cateringcurrencyid |
| cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| cateringstatusid | `String` | Cateringstatusid |
| cenralFBRevenue | `Float` | Cenral FB Revenue |
| centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| centralAverageRoomRate | `Float` | Central Average Room Rate |
| centralBlockPackage | `String` | Central Block Package |
| centralBlockPackageDescription | `String` | Central Block Package Description |
| centralBlockStatus | `String` | Central Block Status |
| centralBlockStatusDescription | `String` | Central Block Status Description |
| centralBlockTypeCode | `String` | Central Block Type Code |
| centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| centralBookingType | `String` | Central Booking Type |
| centralBookingTypeDescription | `String` | Central Booking Type Description |
| centralCancellationDestination | `String` | Central Cancellation Destination |
| centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| centralCateringStatus | `String` | Central Catering Status |
| centralCateringStatusDescription | `String` | Central Catering Status Description |
| centralConversionCode | `String` | Central Conversion Code |
| centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralItemsForThisBlock | `String` | Central Items for this Block |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketCode | `String` | Central Market code |
| centralMeetingBudget | `Float` | Central Meeting Budget |
| centralMeetingRevenue | `Float` | Central Meeting Revenue |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginCodeDescription | `String` | Central Origin Code Description |
| centralOtherRevenue | `Float` | Central Other Revenue |
| centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| centralPayment | `String` | Central Payment |
| centralPaymentDescription | `String` | Central Payment Description |
| centralRankingCode | `String` | Central Ranking Code |
| centralRankingCodeDescription | `String` | Central Ranking Code Description |
| centralReservationMethodCode | `String` | Central Reservation Method Code |
| centralReservationMethodDescription | `String` | Central Reservation Method Description |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralSourceCode | `String` | Central Source Code |
| centralSourceCodeDescription | `String` | Central Source Code Description |
| centralTaxAmount | `Float` | Central Tax Amount |
| chainCode | `String` | Chain Code |
| channelid | `String` | Channelid |
| code | `String` | Code |
| comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| commissionAmount | `String` | Commission Amount |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| compRooms | `Float` | Number of complimentary Rooms |
| compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| companyAll | `String` | Company All |
| companyNameId | `Float` | Company Name ID |
| companyprofileid | `Float` | Companyprofileid |
| competition | `String` | Competition |
| contactNameId | `Float` | Contact Name ID |
| contactprofileid | `Float` | Contactprofileid |
| contractNumber | `String` | Contract Number |
| controlBlockLocally | `String` | Control Block Y/N |
| conversionCode | `String` | Conversion Code |
| coversionCodeDescription | `String` | Coversion Code Description |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `DateTime` | Created Date |
| createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| creditCardId | `Float` | Credit Card ID |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateAcl | `Date` | Date Acl |
| dateCfl | `Date` | Date Cfl |
| dateDefinite | `DateTime` | Date Definite |
| dateLsl | `Date` | Date Lsl |
| dateOpenedForPickup | `Date` | Date Opened for Pickup |
| datePel | `DateTime` | Date Pel |
| dateTdl | `DateTime` | Date Tdl |
| dateTentative | `DateTime` | Date Tentative |
| dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| deletedflag | `String` | Deleted Flag |
| departureTime | `DateTime` | Departure Time |
| description | `String` | Description |
| distributed | `String` | Distributed |
| distributedDate | `DateTime` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| dueDate | `Date` | Due Date |
| dueDateOrd | `Date` | Due Date Sorting Column. |
| endDate | `Date` | End Date |
| endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| endbusinessdate | `Date` | Endbusinessdate |
| eventAttendees | `Float` | Event Attendees |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| externalReference | `String` | External Reference |
| externalRfpId | `String` | External RFP ID. |
| externalRfpSystem | `String` | External RFP System Identification Code. |
| externallyLocked | `String` | Externally Locked |
| fBRevenue | `Float` | Projected F&B Revenue. |
| fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| fbCommission1 | `Float` | stores FB commission for Agent 1 |
| fbCommission2 | `Float` | stores FB commission for Agent 2 |
| fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| fitdiscounttype | `String` | Fitdiscounttype |
| flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| followupDate | `Date` | Followup Date |
| fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| functionType | `String` | Function Type |
| giid | `String` | Group IATA Number. |
| greekContractNr | `String` | Greek Contract Number. |
| groupAccountID | `Float` | Group Account ID |
| guaranteecodeid | `String` | Guaranteecodeid |
| guaranteedRate | `String` | Rate Guaranteed Y/N. |
| guaranteedYN | `String` | Guaranteed YN |
| hideacctinfoflag | `String` | Hideacctinfoflag |
| hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| industryCode | `String` | Indicates the Non-Compete code of a block. |
| industryCodeDescription | `String` | Industry Code Description |
| info | `String` | Not Used |
| informationBoard | `String` | Information Board |
| insertUser | `Float` | Insert User |
| inventoryControl | `String` | Inventory Control |
| inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| items | `String` | Items |
| itemsForThisBlock | `String` | Items for this Block |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| laptopChange | `Float` | Laptop Change |
| leadOrigin | `String` | Lead Origin |
| leadSentYN | `String` | Lead Sent YN |
| leadSource | `String` | Lead Source |
| leadType | `String` | Lead Type |
| leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| leaderrorflag | `String` | Leaderrorflag |
| leadisnewflag | `String` | Leadisnewflag |
| leadoriginid | `String` | Leadoriginid |
| leadreceivedflag | `String` | Leadreceivedflag |
| leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| leadserverpendingflag | `String` | Leadserverpendingflag |
| leadsourceid | `String` | Leadsourceid |
| leadstatus | `String` | Leadstatus |
| linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lostTo | `String` | Competitor to whom the booking was lost. |
| mainmarket | `String` | Mainmarket |
| mainmarketid | `String` | Mainmarketid |
| manuallyCutoffYN | `String` | Block was cutoff manullay |
| marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| marketCode | `String` | Market  Code |
| marketDescription | `String` | Market Description |
| marketid | `String` | Marketid |
| masterBlockID | `Float` | Parent Block ID |
| masterBlockProperty | `String` | Parent Resort |
| masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| meetingBudget | `Float` | Meeting Budget |
| meetingRevenue | `Float` | Meeting Revenue for SFA |
| offsetType | `String` | Offset Type |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origAllotmentHeaderId | `Float` | Stores the original ALLOTMENT_HEADER_ID prior to a migration. |
| originCode | `String` | Origin Code |
| originCodeDescription | `String` | Origin Code Description |
| originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| originalEndDate | `Date` | Original End Date |
| originalRateCode | `String` | Not used |
| originalStartDate | `Date` | Original Start Date |
| originalratecodeid | `String` | Originalratecodeid |
| ormsBlockClass | `String` | ORMS Block Class |
| ormsFinalBlock | `String` | ORMS Final Block |
| ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| ormsTransientBlock | `String` | ORMS Transient Block |
| otherRevenue | `Float` | Projected Other Revenue. |
| owner | `Float` | Owner |
| ownerResort | `String` | Owner Property |
| owneremployeeid | `Float` | Owneremployeeid |
| ownerlocationd | `String` | Ownerlocationd |
| parentallotmentid | `Float` | Parentallotmentid |
| payment | `String` | Payment |
| paymentDescription | `String` | Payment Description |
| paymentmethodid | `String` | Paymentmethodid |
| personsPerRoom | `Float` | Persons Per Room |
| porterageIncluded | `String` | Porterage Included |
| porteragePrice | `Float` | Porterage Price |
| potAverageRoomRate | `Float` | Pot Average Room Rate |
| potFbRevenue1 | `Float` | Pot FB Revenue1 |
| potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| potRoomNights | `Float` | Projected Room Nights. |
| potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRate | `String` | Print Rate |
| profileId | `Float` | Profile ID |
| program | `String` | Program |
| property | `String` | Code to uniquely identify the Property |
| proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| proposalSentDate | `DateTime` | Proposal Sent Date |
| proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| proposalViewToken | `String` | Proposal View Token |
| publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| rankingCode | `String` | Indicates the ranking of a block. |
| rankingCodeDescription | `String` | Ranking Code Description |
| rateCode | `String` | Rate Code |
| rateOverride | `String` | Indicates if the rate code can be overridden. |
| rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| rateTier | `Float` | Rate Tier |
| ratecodeid | `String` | Ratecodeid |
| readyForDistribution | `String` | Ready for Distribution |
| regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| repBsOrderBy | `Float` | Rep Bs Order By |
| repCatOrderBy | `Float` | Rep Cat Order By |
| replDate | `DateTime` | Reply Date |
| replVia | `String` | Reply Communication Method |
| replstatus | `String` | Lead Replystatus [ACL|TDL] |
| replyBy | `Float` | Reply By |
| representative | `String` | Representative |
| reservationMethod | `String` | Reservation Method |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | The Description of the Guarantee code. |
| reservationid | `Float` | Reservationid |
| reserveInventoryYN | `String` | Reserve Inventory YN |
| resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| respTime | `Float` | Response Time. |
| respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| rivMarketSegment | `String` | Not used |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| roomNightsSold | `Float` | Room Nights Sold |
| roomOwnerCode | `String` | Room Owner Code |
| roomOwnerFullName | `String` | Room Owner Full Name |
| roomRevenue | `Float` | Projected Room Revenue. |
| roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| roomStatus | `String` | Room Status |
| roomingListDue | `Date` | Rooming List Due |
| roomingListRules | `String` | Stores Rooming List Rules. |
| roomsCancellationDate | `Date` | Rooms Cancellation Date |
| roomsCancellationReason | `String` | Rooms Cancellation Reason |
| roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| roomsCurrency | `String` | Rooms Currency |
| roomsDecisionDate | `Date` | Rooms Decision Date |
| roomsExchangeRate | `Float` | Rooms Exchange Rate |
| roomsOwner | `Float` | Rooms Owner |
| roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| roomsPerDay | `Float` | Rooms Per Day |
| roomsQuoteCurrency | `String` | Rooms Quote Currency |
| roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| salesId | `String` | Not used |
| sbegindate | `Date` | Sbegindate |
| scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| sellThruYn | `String` | Sell Thru Indicator. |
| sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| senddate | `Date` | Senddate |
| sentBy | `Float` | Sent By |
| sentDate | `DateTime` | Sent Date |
| sentVia | `String` | Sent Via |
| serviceCharge | `Float` | Service Charge |
| serviceFee | `Float` | Service Fee Amount per room/night |
| serviceFeeYn | `String` | Service Fee applies? |
| serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| servicePerc | `Float` | Service Percentage included. |
| shoulderEnd | `Date` | Shoulder End |
| shoulderStart | `Date` | Shoulder Start |
| showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| snapshotSetup | `String` | Snapshot has been created |
| sourceCode | `String` | Source Code |
| sourceCodeDescription | `String` | Source Code Description |
| sourceContactAll | `String` | Source Contact All |
| sourceNameId | `Float` | Source Name ID |
| sourceid | `Float` | Sourceid |
| sourceprofprofileid | `Float` | Sourceprofprofileid |
| startDate | `Date` | Start Date |
| startingStatus | `String` | Booking starting status (intial pickup) |
| status | `String` | Status |
| statusColor | `String` | Status Color |
| statusType | `String` | Type of booking status (initial) |
| subAllocationYN | `String` | Sub Allocation YN |
| superSearchIndexText | `String` | Super Search Index Text |
| suppressRate | `String` | Suppress Rate |
| syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the allotment_detail trigger. |
| synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| taxAmount | `Float` | Tax Amount |
| taxIncludedPerc | `Float` | Percentage of included Tax. |
| taxIncludedYn | `String` | Tax is included in this rate. |
| taxType | `String` | Tax Type |
| taxtypeid | `String` | Taxtypeid |
| tbdRates | `String` | To be Determined Rates |
| tdlReason | `String` | Tdl Reason |
| tentativeLevel | `Float` | Not used |
| tlpResponseid | `String` | Stores the TLPe - Response ID |
| tlpUrl | `String` | Stores the TLPe - Result URL. |
| tourCode | `String` | Tour Code. |
| traceCode | `String` | Trace Code |
| traceDescription | `String` | Trace Description |
| trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| travelAgentAll | `String` | Travel Agent All |
| travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| turndownreasonid | `Float` | Turndownreasonid |
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
| ualias | `String` | Not in use. |
| udescription | `String` | This is upper-case description of regular description column for fast search |
| updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `DateTime` | Updated Date |
| uploadDate | `Date` | Upload Date |
| webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| xudescription | `String` | Multi Byte Description in uppercase |

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

### ProfilesAccountsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| profileaccountsDetailsProfileId | `FloatInput` | Account ID<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsActiveYn | `StringInput` | Active Flag<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| profileaccountsDetailsCompany | `StringInput` | Company |
| profileaccountsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountsDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountsDetailsNameCode | `StringInput` | IATA Number |
| profileaccountsDetailsInactiveDate | `DateTimeInput` | Inactive Date<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsOrganizationId | `FloatInput` | Organization ID<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsLast | `StringInput` | Last |
| profileaccountsDetailsNameId | `FloatInput` | Name ID<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountsDetailsProfileType | `StringInput` | Profile Type |
| profileaccountsDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountsDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountsDetailsSname | `StringInput` | The Uppercase value of Last or Company.<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsSfirst | `StringInput` | Uppercase value of First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name.<br>`@conditionalInputPair(pair: 2)` |
| profileaccountsDetailsUpdateDate | `DateTimeInput` | Update Date<br>`@conditionalInputPair(pair: 2)` |
| profileforecastDetailsChainCode | `StringInput` | Chain Code |
| profileforecastDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileforecastDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileforecastDetailsLinkId | `FloatInput` | Link ID |
| profileforecastDetailsLinkType | `StringInput` | Link Type |
| profileforecastDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileforecastDetailsProfileId | `FloatInput` | Profile ID |
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
| profilecommissionDetailsAccountId | `FloatInput` | Account ID |
| profilecommissionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilecommissionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilecommissionDetailsNameId | `FloatInput` | Name ID |
| profilecommissionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilecommissionDetailsResort | `StringInput` | Code to uniquely identify the Property |
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
| accountmonthlystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accountmonthlystatDetailsNameId | `FloatInput` | Name ID |
| accountmonthlystatDetailsNameType | `StringInput` | Name Type |
| accountmonthlystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accountmonthlystatDetailsResort | `StringInput` | Code to uniquely identify the Property |
| accountmonthlystatDetailsStayMonth | `FloatInput` | Month of Summary. Stores Year and Month as YYYYMM. |
| accountmonthlystatDetailsStayYear | `FloatInput` | Year of Summary. |
| accountmonthlystatDetailsStayedBooked | `StringInput` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
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
| accountdailystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accountdailystatDetailsNameId | `FloatInput` | Name ID |
| accountdailystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accountdailystatDetailsResort | `StringInput` | Code to uniquely identify the Property |
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
| profilerelationshiphierDetailsBottomId | `FloatInput` | Level Ten Name ID. |
| profilerelationshiphierDetailsBottomNameType | `StringInput` | Lowest Level Name Type. |
| profilerelationshiphierDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilerelationshiphierDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilerelationshiphierDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilerelationshiphierDetailsTopId | `FloatInput` | Master Name ID. |
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
| accountyearlystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accountyearlystatDetailsNameId | `FloatInput` | Name ID |
| accountyearlystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accountyearlystatDetailsResort | `StringInput` | Code to uniquely identify the Property |
| accountyearlystatDetailsStayYear | `FloatInput` | Year of Summary. |
| accountyearlystatDetailsStayedBooked | `StringInput` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| profileownerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileownerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileownerDetailsNameId | `FloatInput` | Name ID |
| profileownerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileownerDetailsResort | `StringInput` | Property |
| profileownerDetailsUserId | `FloatInput` | User ID |
| resvdailystatsDetailsAgentId | `FloatInput` | Agent ID |
| resvdailystatsDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| resvdailystatsDetailsBiResvNameId | `FloatInput` | Bi Resv Name ID |
| resvdailystatsDetailsBusinessDate | `DateInput` | Business Date |
| resvdailystatsDetailsCompanyId | `FloatInput` | Company ID |
| resvdailystatsDetailsContactId | `FloatInput` | Contact ID |
| resvdailystatsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdailystatsDetailsGroupId | `FloatInput` | Group ID |
| resvdailystatsDetailsNameId | `FloatInput` | Guest Profile ID |
| resvdailystatsDetailsResvNameId | `FloatInput` | Resv Name ID |
| resvdailystatsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdailystatsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdailystatsDetailsParentCompanyId | `FloatInput` | Parent Company ID |
| resvdailystatsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvdailystatsDetailsRateCode | `StringInput` | Rate Code |
| resvdailystatsDetailsRoom | `StringInput` | Room |
| resvdailystatsDetailsSourceProfId | `FloatInput` | Source Prof ID |
| resvdailystatsDetailsUpdateDate | `DateTimeInput` | Update Date |
| saleprofileownerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| saleprofileownerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| saleprofileownerDetailsNameId | `FloatInput` | Name ID |
| saleprofileownerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| saleprofileownerDetailsResort | `StringInput` | Property |
| saleprofileownerDetailsUserId | `FloatInput` | User ID |
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

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesAccounts($input: ProfilesAccountsQueryArgumentsType!) {
  profilesAccounts(input: $input) @stream {
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
    profileForecastDetails {
      cExchangeDate
      cExchangeRate
      centralForecastFBRevenue
      centralForecastOtherRevenue
      centralForecastRoomAverageRate
      centralForecastRoomRevenue
      chainCode
      dSI
      deletedFlag
      description
      forecastFBRevenue
      forecastInsertDate
      forecastInsertUser
      forecastOtherRevenue
      forecastPeriodCode
      forecastPeriodEnd
      forecastPeriodStart
      forecastRoomAverageRate
      forecastRoomNights
      forecastRoomRevenue
      forecastSplitMode
      forecastType
      forecastUpdateDate
      forecastUpdateUser
      inactiveDate
      insertUserName
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      linkChainCode
      linkId
      linkInsertDate
      linkInsertUser
      linkLaptopChange
      linkType
      locationID
      organizationID
      period
      primaryKeyID
      primaryYn
      profileId
      property
      rNAInsertDate
      rNAUpdateDate
      relationship
      toType
      updateUserName
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
    profileCommissionDetails {
      accountId
      centralCommissionCode
      centralCommissionCodeDescription
      commissionCode
      commissionCodeDescription
      createdByUser
      createdOnDate
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      locationID
      nameId
      organizationID
      primaryKeyID
      property
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
    accountMonthlyStatisticsDetails {
      adr
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
      cancels
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
      centralCurrencyCode
      centralFBRevenueNet
      centralFBRevenueTax
      centralGroupFBRevenueNet
      centralGroupFBRevenueTax
      centralGroupOtherRevenueNet
      centralGroupOtherRevenueTax
      centralGroupRoomRevenueNet
      centralGroupRoomRevenueTax
      centralGroupTotalRevenueNet
      centralGroupTotalRevenueTax
      centralIndividualFBRevenueNet
      centralIndividualFBRevenueTax
      centralIndividualOtherRevenueNet
      centralIndividualOtherRevenueTax
      centralIndividualRoomRevenueNet
      centralIndividualRoomRevenueTax
      centralIndividualTotalRevenueNet
      centralIndividualTotalRevenueTax
      centralOtherRevenueNet
      centralOtherRevenueTax
      centralRoomRevenueNet
      centralRoomRevenueTax
      centralTotalRevenueNet
      centralTotalRevenueTax
      contextCd
      dSI
      deletedFlag
      fBRevenueNet
      fBRevenueTax
      groupCancels
      groupFBRevenueNet
      groupFBRevenueTax
      groupNoShows
      groupOtherRevenueNet
      groupOtherRevenueTax
      groupRoomNights
      groupRoomRevenueNet
      groupRoomRevenueTax
      groupStays
      groupTotalRevenueNet
      groupTotalRevenueTax
      grpAverageDailyRate
      individualCancels
      individualFBRevenueNet
      individualFBRevenueTax
      individualNoShows
      individualOtherRevenueNet
      individualOtherRevenueTax
      individualRoomNights
      individualRoomRevenueNet
      individualRoomRevenueTax
      individualStays
      individualTotalRevenueNet
      individualTotalRevenueTax
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
      noShows
      organizationID
      otherRevenueNet
      otherRevenueTax
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      roomRevenueNet
      roomRevenueTax
      stayMonth
      stayYear
      stayedBooked
      stays
      totalAdr
      totalRevenueNet
      totalRevenueTax
      updateDate
      updateUser
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
    accountDailyStatisticsDetails {
      adr
      cancels
      centralFBRevenueNet
      centralFBRevenueTax
      centralGroupFBRevenueNet
      centralGroupFBRevenueTax
      centralGroupOtherRevenueNet
      centralGroupOtherRevenueTax
      centralGroupRoomRevenueNet
      centralGroupRoomRevenueTax
      centralGroupTotalRevenueNet
      centralGroupTotalRevenueTax
      centralIndividualFBRevenueNet
      centralIndividualFBRevenueTax
      centralIndividualOtherRevenueNet
      centralIndividualOtherRevenueTax
      centralIndividualRoomRevenueNet
      centralIndividualRoomRevenueTax
      centralIndividualTotalRevenueNet
      centralIndividualTotalRevenueTax
      centralOtherRevenueNet
      centralOtherRevenueTax
      centralRoomRevenueNet
      centralRoomRevenueTax
      centralTotalRevenueNet
      centralTotalRevenueTax
      centralXchangeDate
      centralXchangeRate
      contextCd
      dSI
      deletedFlag
      fBRevenueNet
      fBRevenueTax
      groupCancels
      groupFBRevenueNet
      groupFBRevenueTax
      groupNoShows
      groupOtherRevenueNet
      groupOtherRevenueTax
      groupRoomNights
      groupRoomRevenueNet
      groupRoomRevenueTax
      groupStays
      groupTotalRevenueNet
      groupTotalRevenueTax
      grpAverageDailyRate
      individualCancels
      individualFBRevenueNet
      individualFBRevenueTax
      individualNoShows
      individualOtherRevenueNet
      individualOtherRevenueTax
      individualRoomNights
      individualRoomRevenueNet
      individualRoomRevenueTax
      individualStays
      individualTotalRevenueNet
      individualTotalRevenueTax
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
      organizationID
      otherRevenueNet
      otherRevenueTax
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      roomRevenueNet
      roomRevenueTax
      stayDate
      stayMonth
      stayYear
      stays
      totalAdr
      totalRevenueNet
      totalRevenueTax
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
    profileRelationshipHierDetails {
      bottomId
      bottomNameType
      chainCode
      contextCd
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      relToType
      relType
      rnaInsertDate
      rnaUpdateDate
      topId
      totalLevels
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
    accountYearlyStatisticsDetails {
      adr
      cCcRoomRevenueTax
      cCcTotalRevenue
      cCcTotalRevenueTax
      cExchangeDate
      cExchangeRate
      cancels
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
      centralCcFbRevenue
      centralCcFbRevenueTax
      centralCcGrpFBRevenue
      centralCcGrpFBRevenueTax
      centralCcGrpMiscellaneousRevenue
      centralCcGrpMiscellaneousRevenueTax
      centralCcGrpOtherRevenue
      centralCcGrpOtherRevenueTax
      centralCcGrpRoomRevenue
      centralCcGrpRoomRevenueTax
      centralCcGrpTotalRevenue
      centralCcGrpTotalRevenueTax
      centralCcMiscRevenue
      centralCcMiscRevenueTax
      centralCcOtherRevenue
      centralCcOtherRevenueTax
      centralCcRoomRevenue
      centralCurrencyCode
      centralFBRevenueNet
      centralFBRevenueTax
      centralGroupFBRevenueNet
      centralGroupFBRevenueTax
      centralGroupOtherRevenueNet
      centralGroupOtherRevenueTax
      centralGroupRoomRevenueNet
      centralGroupRoomRevenueTax
      centralGroupTotalRevenueNet
      centralGroupTotalRevenueTax
      centralIndividualFBRevenueNet
      centralIndividualFBRevenueTax
      centralIndividualOtherRevenueNet
      centralIndividualOtherRevenueTax
      centralIndividualRoomRevenueNet
      centralIndividualRoomRevenueTax
      centralIndividualTotalRevenueNet
      centralIndividualTotalRevenueTax
      centralOtherRevenueNet
      centralOtherRevenueTax
      centralRoomRevenueNet
      centralRoomRevenueTax
      centralTotalRevenueNet
      centralTotalRevenueTax
      contextCd
      dSI
      deletedFlag
      fBRevenueNet
      fBRevenueTax
      groupCancels
      groupFBRevenueNet
      groupFBRevenueTax
      groupNoShows
      groupOtherRevenueNet
      groupOtherRevenueTax
      groupRoomNights
      groupRoomRevenueNet
      groupRoomRevenueTax
      groupStays
      groupTotalRevenueNet
      groupTotalRevenueTax
      grpAverageDailyRate
      individualCancels
      individualFBRevenueNet
      individualFBRevenueTax
      individualNoShows
      individualOtherRevenueNet
      individualOtherRevenueTax
      individualRoomNights
      individualRoomRevenueNet
      individualRoomRevenueTax
      individualStays
      individualTotalRevenueNet
      individualTotalRevenueTax
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
      noShows
      organizationID
      otherRevenueNet
      otherRevenueTax
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      roomRevenueNet
      roomRevenueTax
      stayYear
      stayedBooked
      stays
      totalAdr
      totalRevenueNet
      totalRevenueTax
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
    saleProfileOwnerDetails {
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
      property
      relationship
      relationshipid
      resort
      rnaInsertDate
      rnaUpdateDate
      saleProfileOwnerId
      toType
      updateDate
      updateUser
      userId
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
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

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
    'updateUser': pl.Utf8,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}

profile_forecast_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralForecastFBRevenue': pl.Float64,
    'centralForecastOtherRevenue': pl.Float64,
    'centralForecastRoomAverageRate': pl.Float64,
    'centralForecastRoomRevenue': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'forecastFBRevenue': pl.Float64,
    'forecastInsertDate': pl.Utf8,
    'forecastInsertUser': pl.Float64,
    'forecastOtherRevenue': pl.Float64,
    'forecastPeriodCode': pl.Utf8,
    'forecastPeriodEnd': pl.Utf8,
    'forecastPeriodStart': pl.Utf8,
    'forecastRoomAverageRate': pl.Float64,
    'forecastRoomNights': pl.Float64,
    'forecastRoomRevenue': pl.Float64,
    'forecastSplitMode': pl.Utf8,
    'forecastType': pl.Utf8,
    'forecastUpdateDate': pl.Utf8,
    'forecastUpdateUser': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertUserName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'linkChainCode': pl.Utf8,
    'linkId': pl.Float64,
    'linkInsertDate': pl.Utf8,
    'linkInsertUser': pl.Float64,
    'linkLaptopChange': pl.Float64,
    'linkType': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'period': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryYn': pl.Utf8,
    'profileId': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'relationship': pl.Utf8,
    'toType': pl.Utf8,
    'updateUserName': pl.Utf8,
}

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

profile_commission_details_schema = {
    'accountId': pl.Float64,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionCodeDescription': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeDescription': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

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

account_monthly_statistics_details_schema = {
    'adr': pl.Float64,
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
    'cancels': pl.Float64,
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
    'centralCurrencyCode': pl.Utf8,
    'centralFBRevenueNet': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralGroupFBRevenueNet': pl.Float64,
    'centralGroupFBRevenueTax': pl.Float64,
    'centralGroupOtherRevenueNet': pl.Float64,
    'centralGroupOtherRevenueTax': pl.Float64,
    'centralGroupRoomRevenueNet': pl.Float64,
    'centralGroupRoomRevenueTax': pl.Float64,
    'centralGroupTotalRevenueNet': pl.Float64,
    'centralGroupTotalRevenueTax': pl.Float64,
    'centralIndividualFBRevenueNet': pl.Float64,
    'centralIndividualFBRevenueTax': pl.Float64,
    'centralIndividualOtherRevenueNet': pl.Float64,
    'centralIndividualOtherRevenueTax': pl.Float64,
    'centralIndividualRoomRevenueNet': pl.Float64,
    'centralIndividualRoomRevenueTax': pl.Float64,
    'centralIndividualTotalRevenueNet': pl.Float64,
    'centralIndividualTotalRevenueTax': pl.Float64,
    'centralOtherRevenueNet': pl.Float64,
    'centralOtherRevenueTax': pl.Float64,
    'centralRoomRevenueNet': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralTotalRevenueNet': pl.Float64,
    'centralTotalRevenueTax': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenueNet': pl.Float64,
    'fBRevenueTax': pl.Float64,
    'groupCancels': pl.Float64,
    'groupFBRevenueNet': pl.Float64,
    'groupFBRevenueTax': pl.Float64,
    'groupNoShows': pl.Float64,
    'groupOtherRevenueNet': pl.Float64,
    'groupOtherRevenueTax': pl.Float64,
    'groupRoomNights': pl.Float64,
    'groupRoomRevenueNet': pl.Float64,
    'groupRoomRevenueTax': pl.Float64,
    'groupStays': pl.Float64,
    'groupTotalRevenueNet': pl.Float64,
    'groupTotalRevenueTax': pl.Float64,
    'grpAverageDailyRate': pl.Float64,
    'individualCancels': pl.Float64,
    'individualFBRevenueNet': pl.Float64,
    'individualFBRevenueTax': pl.Float64,
    'individualNoShows': pl.Float64,
    'individualOtherRevenueNet': pl.Float64,
    'individualOtherRevenueTax': pl.Float64,
    'individualRoomNights': pl.Float64,
    'individualRoomRevenueNet': pl.Float64,
    'individualRoomRevenueTax': pl.Float64,
    'individualStays': pl.Float64,
    'individualTotalRevenueNet': pl.Float64,
    'individualTotalRevenueTax': pl.Float64,
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
    'noShows': pl.Float64,
    'organizationID': pl.Float64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenueNet': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'stayedBooked': pl.Utf8,
    'stays': pl.Float64,
    'totalAdr': pl.Float64,
    'totalRevenueNet': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

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

account_daily_statistics_details_schema = {
    'adr': pl.Float64,
    'cancels': pl.Float64,
    'centralFBRevenueNet': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralGroupFBRevenueNet': pl.Float64,
    'centralGroupFBRevenueTax': pl.Float64,
    'centralGroupOtherRevenueNet': pl.Float64,
    'centralGroupOtherRevenueTax': pl.Float64,
    'centralGroupRoomRevenueNet': pl.Float64,
    'centralGroupRoomRevenueTax': pl.Float64,
    'centralGroupTotalRevenueNet': pl.Float64,
    'centralGroupTotalRevenueTax': pl.Float64,
    'centralIndividualFBRevenueNet': pl.Float64,
    'centralIndividualFBRevenueTax': pl.Float64,
    'centralIndividualOtherRevenueNet': pl.Float64,
    'centralIndividualOtherRevenueTax': pl.Float64,
    'centralIndividualRoomRevenueNet': pl.Float64,
    'centralIndividualRoomRevenueTax': pl.Float64,
    'centralIndividualTotalRevenueNet': pl.Float64,
    'centralIndividualTotalRevenueTax': pl.Float64,
    'centralOtherRevenueNet': pl.Float64,
    'centralOtherRevenueTax': pl.Float64,
    'centralRoomRevenueNet': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralTotalRevenueNet': pl.Float64,
    'centralTotalRevenueTax': pl.Float64,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenueNet': pl.Float64,
    'fBRevenueTax': pl.Float64,
    'groupCancels': pl.Float64,
    'groupFBRevenueNet': pl.Float64,
    'groupFBRevenueTax': pl.Float64,
    'groupNoShows': pl.Float64,
    'groupOtherRevenueNet': pl.Float64,
    'groupOtherRevenueTax': pl.Float64,
    'groupRoomNights': pl.Float64,
    'groupRoomRevenueNet': pl.Float64,
    'groupRoomRevenueTax': pl.Float64,
    'groupStays': pl.Float64,
    'groupTotalRevenueNet': pl.Float64,
    'groupTotalRevenueTax': pl.Float64,
    'grpAverageDailyRate': pl.Float64,
    'individualCancels': pl.Float64,
    'individualFBRevenueNet': pl.Float64,
    'individualFBRevenueTax': pl.Float64,
    'individualNoShows': pl.Float64,
    'individualOtherRevenueNet': pl.Float64,
    'individualOtherRevenueTax': pl.Float64,
    'individualRoomNights': pl.Float64,
    'individualRoomRevenueNet': pl.Float64,
    'individualRoomRevenueTax': pl.Float64,
    'individualStays': pl.Float64,
    'individualTotalRevenueNet': pl.Float64,
    'individualTotalRevenueTax': pl.Float64,
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
    'organizationID': pl.Float64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenueNet': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayDate': pl.Utf8,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'stays': pl.Float64,
    'totalAdr': pl.Float64,
    'totalRevenueNet': pl.Float64,
    'totalRevenueTax': pl.Float64,
}

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

profile_relationship_hier_details_schema = {
    'bottomId': pl.Float64,
    'bottomNameType': pl.Utf8,
    'chainCode': pl.Utf8,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'relToType': pl.Utf8,
    'relType': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'topId': pl.Float64,
    'totalLevels': pl.Float64,
}

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

account_yearly_statistics_details_schema = {
    'adr': pl.Float64,
    'cCcRoomRevenueTax': pl.Float64,
    'cCcTotalRevenue': pl.Float64,
    'cCcTotalRevenueTax': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cancels': pl.Float64,
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
    'centralCcFbRevenue': pl.Float64,
    'centralCcFbRevenueTax': pl.Float64,
    'centralCcGrpFBRevenue': pl.Float64,
    'centralCcGrpFBRevenueTax': pl.Float64,
    'centralCcGrpMiscellaneousRevenue': pl.Float64,
    'centralCcGrpMiscellaneousRevenueTax': pl.Float64,
    'centralCcGrpOtherRevenue': pl.Float64,
    'centralCcGrpOtherRevenueTax': pl.Float64,
    'centralCcGrpRoomRevenue': pl.Float64,
    'centralCcGrpRoomRevenueTax': pl.Float64,
    'centralCcGrpTotalRevenue': pl.Float64,
    'centralCcGrpTotalRevenueTax': pl.Float64,
    'centralCcMiscRevenue': pl.Float64,
    'centralCcMiscRevenueTax': pl.Float64,
    'centralCcOtherRevenue': pl.Float64,
    'centralCcOtherRevenueTax': pl.Float64,
    'centralCcRoomRevenue': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralFBRevenueNet': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralGroupFBRevenueNet': pl.Float64,
    'centralGroupFBRevenueTax': pl.Float64,
    'centralGroupOtherRevenueNet': pl.Float64,
    'centralGroupOtherRevenueTax': pl.Float64,
    'centralGroupRoomRevenueNet': pl.Float64,
    'centralGroupRoomRevenueTax': pl.Float64,
    'centralGroupTotalRevenueNet': pl.Float64,
    'centralGroupTotalRevenueTax': pl.Float64,
    'centralIndividualFBRevenueNet': pl.Float64,
    'centralIndividualFBRevenueTax': pl.Float64,
    'centralIndividualOtherRevenueNet': pl.Float64,
    'centralIndividualOtherRevenueTax': pl.Float64,
    'centralIndividualRoomRevenueNet': pl.Float64,
    'centralIndividualRoomRevenueTax': pl.Float64,
    'centralIndividualTotalRevenueNet': pl.Float64,
    'centralIndividualTotalRevenueTax': pl.Float64,
    'centralOtherRevenueNet': pl.Float64,
    'centralOtherRevenueTax': pl.Float64,
    'centralRoomRevenueNet': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralTotalRevenueNet': pl.Float64,
    'centralTotalRevenueTax': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fBRevenueNet': pl.Float64,
    'fBRevenueTax': pl.Float64,
    'groupCancels': pl.Float64,
    'groupFBRevenueNet': pl.Float64,
    'groupFBRevenueTax': pl.Float64,
    'groupNoShows': pl.Float64,
    'groupOtherRevenueNet': pl.Float64,
    'groupOtherRevenueTax': pl.Float64,
    'groupRoomNights': pl.Float64,
    'groupRoomRevenueNet': pl.Float64,
    'groupRoomRevenueTax': pl.Float64,
    'groupStays': pl.Float64,
    'groupTotalRevenueNet': pl.Float64,
    'groupTotalRevenueTax': pl.Float64,
    'grpAverageDailyRate': pl.Float64,
    'individualCancels': pl.Float64,
    'individualFBRevenueNet': pl.Float64,
    'individualFBRevenueTax': pl.Float64,
    'individualNoShows': pl.Float64,
    'individualOtherRevenueNet': pl.Float64,
    'individualOtherRevenueTax': pl.Float64,
    'individualRoomNights': pl.Float64,
    'individualRoomRevenueNet': pl.Float64,
    'individualRoomRevenueTax': pl.Float64,
    'individualStays': pl.Float64,
    'individualTotalRevenueNet': pl.Float64,
    'individualTotalRevenueTax': pl.Float64,
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
    'noShows': pl.Float64,
    'organizationID': pl.Float64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenueNet': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayYear': pl.Float64,
    'stayedBooked': pl.Utf8,
    'stays': pl.Float64,
    'totalAdr': pl.Float64,
    'totalRevenueNet': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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

sale_profile_owner_details_schema = {
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
    'property': pl.Utf8,
    'relationship': pl.Utf8,
    'relationshipid': pl.Utf8,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'saleProfileOwnerId': pl.Float64,
    'toType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'userId': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'webBookable': pl.Utf8,
    'webOverbookYN': pl.Utf8,
    'xudescription': pl.Utf8,
}

```