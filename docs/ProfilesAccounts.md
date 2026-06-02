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