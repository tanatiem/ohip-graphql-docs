# ProfilesAddresses
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `profilesAddresses`
> All associated addresses including primary and secondary addresses and address types which can be associated with the proper profile and profile type.
  
**Return:** [`[ProfilesAddressesType]`](#profilesaddressestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesAddressesQueryArgumentsType!`](#profilesaddressesqueryargumentstype) |  |

## Object Types

### ProfilesAddressesType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | profileAddressDetails | [`ProfilesAddressesProfileAddressDetailsType`](#profilesaddressesprofileaddressdetailstype) | Profile Address Details |
| 2 | profileInformationDetails | [`ProfilesAddressesProfileInformationDetailsType`](#profilesaddressesprofileinformationdetailstype) | Profile Details |
| 3 | profilesAddressesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesAddressesProfileAddressDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | address1 | `String` | The first line of street address. |
| 2 | address2 | `String` | The second line of street address. |
| 3 | address3 | `String` | The third line of street address. |
| 4 | address4 | `String` | The fourth line of street address. |
| 5 | addressID | `Float` | The primary key for this table. |
| 6 | addressLanguage | `String` | Address Language |
| 7 | addressLanguageDescription | `String` | Description for each language code. |
| 8 | addressType | `String` | The type of address. |
| 9 | addressTypeDesc | `String` | The description of this value. |
| 10 | barcode | `String` | The postal barcode for the address. |
| 11 | beginDate | `Date` | Not used. |
| 12 | centralState | `String` | Central State |
| 13 | centralStateDescription | `String` | Central State Description |
| 14 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 15 | city | `String` | The city for this address. |
| 16 | cleansedDatetime | `DateTime` | The Timestamp when this record was cleansed. |
| 17 | cleansedErrormsg | `String` | The error message why this record was not cleansed. |
| 18 | cleansedMatchstatus | `String` | Specifies how the address elements match with the postal reference data. |
| 19 | cleansedStatus | `String` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| 20 | cleansedValidationstatus | `String` | Validation Status as returned by the Address Cleansing System. |
| 21 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 22 | countryCode | `String` | Country . |
| 23 | countryDescription | `String` | Country name. |
| 24 | createdByUser | `Float` | The user that created the record |
| 25 | createdOnDate | `DateTime` | The date the record was created |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | deletedYN | `String` | Deleted Y/n |
| 28 | endDate | `Date` | Not used. |
| 29 | firstName | `String` | The first name of an individual name. |
| 30 | foreignCountry | `String` | Not used. |
| 31 | inCareOf | `String` | Not used. |
| 32 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 33 | inactiveYN | `String` | Inactive Y/n |
| 34 | internalOrganizationId | `Float` | Organization ID |
| 35 | jRNUpdateDate | `Date` | JRN Update Date |
| 36 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 37 | laptopChange | `Float` | Code to synchronize with Laptop. (not used) |
| 38 | lastUpdatedResort | `String` | Last property that updated this record. |
| 39 | name | `String` | Name |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | postalCode | `String` | The postal code of this address. |
| 42 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 43 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 44 | primaryYN | `String` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| 45 | profileAddressId | `Float` | The primary key for this table. |
| 46 | profileId | `Float` | The reference to the NAME record that owns this address. |
| 47 | profileIdx | `Float` | The reference to the NAME record that owns this address. |
| 48 | province | `String` | Province. |
| 49 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 50 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 51 | state | `String` | State |
| 52 | stateCode | `String` | The state of this address. |
| 53 | updateDate | `DateTime` | The date the record was modified |
| 54 | updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesAddressesProfileInformationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 2 | aRNumber | `String` | AR Number |
| 3 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 4 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 5 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 6 | accountEmailPrimary | `String` | Account Email Primary |
| 7 | accountName | `String` | Account Name |
| 8 | accountName2 | `String` | Account Name 2 |
| 9 | accountName3 | `String` | Account Name 3 |
| 10 | accountOwnerCode | `String` | Account Owner Code |
| 11 | accountPhonePrimary | `String` | Phone no. |
| 12 | accountSource | `String` | Account Source |
| 13 | accountType | `String` | Account Type |
| 14 | accountTypeDescription | `String` | Account Type Description |
| 15 | accountsourceDesc | `String` | Accountsource Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressId | `Float` | Address ID |
| 24 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 28 | allOwners | `String` | All Owners |
| 29 | allResorts | `String` | All Resorts |
| 30 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 31 | alternateLanguageDescription | `String` | Alternate Language Description |
| 32 | alternateName | `String` | Alternate Name |
| 33 | alternateSalutation | `String` | Alternate Salutation |
| 34 | alternateTitle | `String` | Alternate Title |
| 35 | anonymizationDate | `Date` | System Date when the guest was anonymized in OPERA. |
| 36 | anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| 37 | arNumberCentral | `String` | AR No Central |
| 38 | autoPopRouting | `String` | Auto Pop Routing |
| 39 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 40 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 41 | billingCode | `String` | The billing code for this name record. |
| 42 | billingInstruction | `String` | Billing Instruction |
| 43 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 44 | birthCountry | `String` | Country of birth. |
| 45 | birthDate | `Date` | Birth Date |
| 46 | birthDateStr | `String` | Birth Date Str |
| 47 | birthPlace | `String` | Place of birth. |
| 48 | blMsg | `String` | Bl Msg |
| 49 | businessPotential | `String` | Business Potential |
| 50 | businessSegement | `String` | Business Segement |
| 51 | businessTitle | `String` | Business Title |
| 52 | cExchangeDate | `Date` | Central Xchange Date |
| 53 | cExchangeRate | `Float` | Central Xchange Rate |
| 54 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 55 | cRSNameid | `Float` | The unique identifier of the CRS |
| 56 | cashBlInd | `String` | Cash Bl Individual |
| 57 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 58 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 59 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 60 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 61 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 62 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 63 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 64 | centralIATANumber | `String` | Central IATA Number |
| 65 | centralInactiveReason | `String` | Central Inactive Reason |
| 66 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 67 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 68 | centralKeyword | `String` | Central Keyword |
| 69 | centralMailActionDescription | `String` | Central Mail Action Description |
| 70 | centralPriority | `String` | Central Priority |
| 71 | centralPriorityDescription | `String` | Central Priority Description |
| 72 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 73 | centralScopeCityDescription | `String` | Central Scope City Description |
| 74 | centralScopeDescription | `String` | Central Scope Description |
| 75 | centralSourceOwnerTitle | `String` | Central Source Owner Title |
| 76 | centralState | `String` | Central State |
| 77 | centralTerritory | `String` | Central Territory |
| 78 | centralTerritoryDescription | `String` | Central Territory Description |
| 79 | chainCode | `String` | Chain Code |
| 80 | city | `String` | City |
| 81 | cityExt | `String` | City Ext |
| 82 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 83 | combinedName | `String` | Combined Name |
| 84 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 85 | commissionCode | `String` | Commission Code |
| 86 | commissionCodes | `String` | Commission Codes |
| 87 | commissionCurrencyId | `String` | Comm Curr ID |
| 88 | commissionid | `String` | Commissionid |
| 89 | communicationRole1 | `String` | Communication Role1 |
| 90 | communicationRole2 | `String` | Communication Role2 |
| 91 | communicationRole3 | `String` | Communication Role3 |
| 92 | communicationType1 | `String` | Communication Type1 |
| 93 | communicationType2 | `String` | Communication Type2 |
| 94 | communicationType3 | `String` | Communication Type3 |
| 95 | communicationValue1 | `String` | Communication Value1 |
| 96 | communicationValue2 | `String` | Communication Value2 |
| 97 | communicationValue3 | `String` | Communication Value3 |
| 98 | compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| 99 | company | `String` | Company |
| 100 | companyGroupId | `String` | Linked internal ID for booker. |
| 101 | companyNameId | `Float` | Company Name ID |
| 102 | competitionCode | `String` | Competition Code |
| 103 | competitionDesc | `String` | Competition Description |
| 104 | contactFlag | `String` | Contact Flag |
| 105 | contactOwnerCode | `String` | Contact Owner Code |
| 106 | contractNo | `String` | Contract Number (used for customers). |
| 107 | contractRecvDate | `Date` | The date the group contract was received. |
| 108 | corpID | `String` | Corp ID |
| 109 | corpTypeDesc | `String` | Corp Type Description |
| 110 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 111 | country | `String` | Country |
| 112 | countryCode | `String` | Country Code |
| 113 | countryDesc | `String` | Country Description |
| 114 | createdByUser | `String` | Created By User |
| 115 | createdOnDate | `DateTime` | Created On Date |
| 116 | creditCardName | `String` | Credit Card Name |
| 117 | creditCardType | `String` | Credit Card Type |
| 118 | creditRating | `String` | Credit Rating |
| 119 | currencyCode | `String` | Currency Code |
| 120 | currencyDescription | `String` | Currency Description |
| 121 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 122 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 123 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 124 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 125 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 126 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 127 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 128 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 129 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 130 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 131 | decimalPositions | `Float` | Decimal Positions |
| 132 | deletedFlag | `String` | Deleted Flag |
| 133 | department | `String` | Department |
| 134 | deptId | `String` | Dept ID |
| 135 | directBillBatchType | `String` | Direct Bill Batch Type |
| 136 | downloadDate | `Date` | Download Date |
| 137 | downloadResort | `String` | Download Property |
| 138 | downloadSrep | `Float` | Download Srep |
| 139 | eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| 140 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 141 | emailYn | `String` | Email Y/N |
| 142 | envelopeGreeting | `String` | Envelope Greeting |
| 143 | externalDisplayName | `String` | External Display Name |
| 144 | externalFirstName | `String` | External First Name |
| 145 | externalId | `String` | External ID |
| 146 | externalName | `String` | External Name |
| 147 | externalReferenceRequ | `String` | Not Used. |
| 148 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 149 | fMembershipCardNumbers | `String` | F Membership Card Numbers |
| 150 | fMembershipClassDesc | `String` | F Membership Class Description |
| 151 | fMembershipClasses | `String` | F Membership Classes |
| 152 | fMembershipCodes | `String` | F Membership Codes |
| 153 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 154 | fMembershipIds | `String` | F Membership Ids |
| 155 | fMembershipType | `String` | F Membership Type |
| 156 | fSubscriptionDb | `String` | F Subscription Db |
| 157 | fSubscriptionYn | `String` | F Subscription Y/N |
| 158 | faxNo | `String` | Fax Number |
| 159 | first | `String` | First |
| 160 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 161 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 162 | gDSTransactionNo | `String` | Not used. |
| 163 | gender | `String` | Gender |
| 164 | geographicRegion | `String` | Not used. |
| 165 | guestClassification | `String` | Not used. |
| 166 | guestPrivYn | `String` | Guest Priv Y/N |
| 167 | historyYn | `String` | History Y/N |
| 168 | holdCode | `String` | Hold Code |
| 169 | iataConsortia | `String` | IATA Consortia |
| 170 | idCountry | `String` | ID Country |
| 171 | idDate | `Date` | ID Date |
| 172 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 173 | idNumber | `String` | ID Number |
| 174 | idPlace | `String` | ID Place |
| 175 | idType | `String` | ID Type |
| 176 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 177 | inactiveDate | `Date` | Inactive Date |
| 178 | inactiveFlag | `String` | Inactive Flag |
| 179 | inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| 180 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 181 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 182 | incognitoFirstName | `String` | Incognito First Name |
| 183 | incognitoLastName | `String` | Incognito Last Name |
| 184 | indexName | `String` | Index Name |
| 185 | industryCode | `String` | Industry Code |
| 186 | industryDesc | `String` | Industry Description |
| 187 | influence | `String` | Influence |
| 188 | influenceDesc | `String` | Influence Description |
| 189 | insertUserId | `Float` | Insert User ID |
| 190 | interest | `String` | Interest Code. |
| 191 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 192 | internalDeletedflag | `String` | Deleted Flag |
| 193 | internalInactiveflag | `String` | Inactive Flag |
| 194 | internalOrganizationId | `Float` | Organization ID |
| 195 | jRNUpdateDate | `Date` | JRN Update Date |
| 196 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 197 | keyword | `String` | Keyword |
| 198 | laptopChange | `Float` | Laptop Change |
| 199 | last | `String` | Last |
| 200 | lastGroup | `String` | Last Group |
| 201 | lastRate | `Float` | Last Rate |
| 202 | lastRateCode | `String` | Last Rate Code |
| 203 | lastRoom | `String` | Not used. |
| 204 | lastRoomResort | `String` | Last Room Property |
| 205 | lastSource | `String` | Last Source |
| 206 | lastStay | `Date` | Last Stay |
| 207 | lastUpdatedResort | `String` | Last property that updated this record. |
| 208 | legalCompany | `String` | Legal Company |
| 209 | letterGreeting | `String` | Letter Greeting |
| 210 | mailActionCodes | `String` | Mail Action Codes |
| 211 | mailActionDesc | `String` | Mail Action Description |
| 212 | mailList | `String` | Mail List |
| 213 | mailType | `String` | The type of mail this user should be sent. |
| 214 | mailYn | `String` | Mail Y/N |
| 215 | marketResearchYn | `String` | Market Research Y/N |
| 216 | marketsDesc | `String` | Markets Description |
| 217 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 218 | middle | `String` | Middle |
| 219 | name | `String` | Name |
| 220 | nameComment | `String` | Not Used. |
| 221 | nameId | `Float` | Name ID |
| 222 | nameTaxType | `String` | Name Tax Type |
| 223 | nameTypeDescription | `String` | Name Type Description |
| 224 | nameWithTitle | `String` | Name With Title |
| 225 | nationalityCode | `String` | Nationality Code |
| 226 | nationalityDescription | `String` | Nationality Description |
| 227 | negotiatedRate | `String` | Negotiated Rate |
| 228 | nextStay | `Date` | Next Stay |
| 229 | nickname | `String` | The nickname of this individual. |
| 230 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 231 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 232 | passport | `String` | Passport |
| 233 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 234 | paymentMethodsCode | `String` | Payment Methods Code |
| 235 | paymentMethodsDesc | `String` | Payment Methods Description |
| 236 | phoneWeb | `String` | Phone Web |
| 237 | phoneYn | `String` | Phone Y/N |
| 238 | postalCode | `String` | Postal Code |
| 239 | preferredRoomNo | `String` | Preferred Room Number |
| 240 | primaryAddressId | `Float` | Not used. |
| 241 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 242 | primaryNameId | `Float` | Not Used. |
| 243 | primaryOwner | `String` | Primary Owner |
| 244 | primaryOwnerCode | `String` | Primary Owner Code |
| 245 | primaryPhoneId | `Float` | Not used. |
| 246 | priority | `String` | Priority |
| 247 | priorityDesc | `String` | Priority Description |
| 248 | productInterest | `String` | Product Interest |
| 249 | productInterestCodes | `String` | Product Interest Codes |
| 250 | profession | `String` | Profession of the guest |
| 251 | profileArrCodes | `String` | Profile Arrangement Codes |
| 252 | profileArrangementDesc | `String` | Profile Arr Description |
| 253 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 254 | profileLanguage | `String` | Profile Language |
| 255 | profileLanguageDescription | `String` | Profile Language Description |
| 256 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 257 | profileType | `String` | Profile Type |
| 258 | profileTypeCode | `String` | Profile Type Code |
| 259 | protected | `String` | Protected |
| 260 | province | `String` | Province |
| 261 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 262 | rateStructure | `String` | The default rate structure for this name. |
| 263 | region | `String` | Region |
| 264 | regionid | `String` | Regionid |
| 265 | repAccountType | `String` | Rep Account Type |
| 266 | repAccountsource | `String` | Reporting Accountsource |
| 267 | repCompetitionCode | `String` | Reporting Competition Code |
| 268 | repIataCompType | `String` | Rep IATA Comp Type |
| 269 | repIndustryCode | `String` | Reporting Industry Code |
| 270 | repInfluence | `String` | Reporting Influence |
| 271 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 272 | repMailActionCodes | `String` | Reporting Mail Action Codes |
| 273 | repMarkets | `String` | Reporting Markets |
| 274 | repNationalityCode | `String` | Reporting Nationality Code |
| 275 | repNationalityDescription | `String` | Reporting Nationality Description |
| 276 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 277 | repScope | `String` | Reporting Scope |
| 278 | repScopeCity | `String` | Reporting Scope City |
| 279 | repStateDescription | `String` | Reporting State Desc |
| 280 | repTaxType | `String` | Reporting Tax Type |
| 281 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 282 | repTitleName | `String` | Reporting Title Name |
| 283 | repVIPName | `String` | Reporting Vip Name |
| 284 | repVIPStatus | `String` | Reporting Vip Status |
| 285 | repeatGuestId | `String` | The primary membership # for this guest. |
| 286 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 287 | resortRegistered | `String` | Resort for which Job is registered. |
| 288 | restrictedRule | `String` | Restricted Rule |
| 289 | resvContact | `String` | Reservation Contact person. |
| 290 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 291 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 292 | roomsPotentialDesc | `String` | Rooms Potential Description |
| 293 | salutation | `String` | Salutation Greeting |
| 294 | scope | `String` | Scope |
| 295 | scopeCity | `String` | Scope City |
| 296 | scopeCityDesc | `String` | Scope City Description |
| 297 | scopeDesc | `String` | Scope Description |
| 298 | sfirst | `String` | Uppercase value of First Name. |
| 299 | smsYn | `String` | Use this alert to text a notification. |
| 300 | sname | `String` | The Uppercase value of Last or Company. |
| 301 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 302 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 303 | sourceOwnerTitle | `String` | Source Owner Title |
| 304 | state | `String` | State |
| 305 | stateDesc | `String` | State Description of the Guest of Payee |
| 306 | stateDescription | `String` | State Description |
| 307 | suffix | `String` | Suffix |
| 308 | summRefCc | `String` | Summ Ref Cc |
| 309 | summRefCurrencyId | `String` | Summ Ref Curr ID |
| 310 | superSearchIndexText | `String` | Super Search Index Text |
| 311 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 312 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 313 | tax1No | `String` | Tax1 Number |
| 314 | tax2No | `String` | Tax2 Number |
| 315 | taxCategory | `String` | Tax Category |
| 316 | taxExemptStatus | `String` | Not used. |
| 317 | taxOffice | `String` | Tax Office Name |
| 318 | taxType | `String` | Tax Type |
| 319 | taxTypeDesc | `String` | Tax Type Description |
| 320 | territory | `String` | Territory |
| 321 | territoryDesc | `String` | Territory Description |
| 322 | thirdPartyYn | `String` | Third Party Y/N |
| 323 | titleName | `String` | Title Name |
| 324 | titleSuffix | `Float` | Title Suffix |
| 325 | topAccountID | `Float` | Top Account ID |
| 326 | totalArrivals | `Float` | Total Arrivals |
| 327 | totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| 328 | totalCancelledReservations | `Float` | Total Cancelled Reservations |
| 329 | totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| 330 | totalCancelledRooms | `Float` | Total Cancelled Rooms |
| 331 | totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| 332 | totalDayUseReservations | `Float` | Total Day Use Reservations |
| 333 | totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| 334 | totalDayUseRooms | `Float` | Total Day Use Rooms |
| 335 | totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| 336 | totalFbRevenue | `Float` | Total FB Revenue |
| 337 | totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| 338 | totalNoShowReservations | `Float` | Total Number Show Reservations |
| 339 | totalNoShowRooms | `Float` | Total Number Show Rooms |
| 340 | totalNonRevenue | `Float` | Total Non Revenue |
| 341 | totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| 342 | totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| 343 | totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| 344 | totalOtherRevenue | `Float` | Total Other Revenue |
| 345 | totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| 346 | totalReservationNights | `Float` | Total Reservation Nights |
| 347 | totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| 348 | totalRevenue | `Float` | Total Revenue |
| 349 | totalRevenueLastyear | `Float` | Total Revenue Last Year |
| 350 | totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| 351 | totalRoomRevenue | `Float` | Total Room Revenue |
| 352 | totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| 353 | totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| 354 | totalStaysLastyear | `Float` | Total Stays Last Year |
| 355 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 356 | traceCode | `String` | Trace Code |
| 357 | tracecodeDesc | `String` | Tracecode Description |
| 358 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 359 | uDFC01 | `String` | UDFC01 |
| 360 | uDFC02 | `String` | UDFC02 |
| 361 | uDFC03 | `String` | UDFC03 |
| 362 | uDFC04 | `String` | UDFC04 |
| 363 | uDFC05 | `String` | UDFC05 |
| 364 | uDFC06 | `String` | UDFC06 |
| 365 | uDFC07 | `String` | UDFC07 |
| 366 | uDFC08 | `String` | UDFC08 |
| 367 | uDFC09 | `String` | UDFC09 |
| 368 | uDFC10 | `String` | UDFC10 |
| 369 | uDFC11 | `String` | UDFC11 |
| 370 | uDFC12 | `String` | UDFC12 |
| 371 | uDFC13 | `String` | UDFC13 |
| 372 | uDFC14 | `String` | UDFC14 |
| 373 | uDFC15 | `String` | UDFC15 |
| 374 | uDFC16 | `String` | UDFC16 |
| 375 | uDFC17 | `String` | UDFC17 |
| 376 | uDFC18 | `String` | UDFC18 |
| 377 | uDFC19 | `String` | UDFC19 |
| 378 | uDFC20 | `String` | UDFC20 |
| 379 | uDFC21 | `String` | UDFC21 |
| 380 | uDFC22 | `String` | UDFC22 |
| 381 | uDFC23 | `String` | UDFC23 |
| 382 | uDFC24 | `String` | UDFC24 |
| 383 | uDFC25 | `String` | UDFC25 |
| 384 | uDFC26 | `String` | UDFC26 |
| 385 | uDFC27 | `String` | UDFC27 |
| 386 | uDFC28 | `String` | UDFC28 |
| 387 | uDFC29 | `String` | UDFC29 |
| 388 | uDFC30 | `String` | UDFC30 |
| 389 | uDFC31 | `String` | UDFC31 |
| 390 | uDFC32 | `String` | UDFC32 |
| 391 | uDFC33 | `String` | UDFC33 |
| 392 | uDFC34 | `String` | UDFC34 |
| 393 | uDFC35 | `String` | UDFC35 |
| 394 | uDFC36 | `String` | UDFC36 |
| 395 | uDFC37 | `String` | UDFC37 |
| 396 | uDFC38 | `String` | UDFC38 |
| 397 | uDFC39 | `String` | UDFC39 |
| 398 | uDFC40 | `String` | UDFC40 |
| 399 | uDFD01 | `Date` | UDFD01 |
| 400 | uDFD02 | `Date` | UDFD02 |
| 401 | uDFD03 | `Date` | UDFD03 |
| 402 | uDFD04 | `Date` | UDFD04 |
| 403 | uDFD05 | `Date` | UDFD05 |
| 404 | uDFD06 | `Date` | UDFD06 |
| 405 | uDFD07 | `Date` | UDFD07 |
| 406 | uDFD08 | `Date` | UDFD08 |
| 407 | uDFD09 | `Date` | UDFD09 |
| 408 | uDFD10 | `Date` | UDFD10 |
| 409 | uDFD11 | `Date` | UDFD11 |
| 410 | uDFD12 | `Date` | UDFD12 |
| 411 | uDFD13 | `Date` | UDFD13 |
| 412 | uDFD14 | `Date` | UDFD14 |
| 413 | uDFD15 | `Date` | UDFD15 |
| 414 | uDFD16 | `Date` | UDFD16 |
| 415 | uDFD17 | `Date` | UDFD17 |
| 416 | uDFD18 | `Date` | UDFD18 |
| 417 | uDFD19 | `Date` | UDFD19 |
| 418 | uDFD20 | `Date` | UDFD20 |
| 419 | uDFN01 | `Float` | UDFN01 |
| 420 | uDFN02 | `Float` | UDFN02 |
| 421 | uDFN03 | `Float` | UDFN03 |
| 422 | uDFN04 | `Float` | UDFN04 |
| 423 | uDFN05 | `Float` | UDFN05 |
| 424 | uDFN06 | `Float` | UDFN06 |
| 425 | uDFN07 | `Float` | UDFN07 |
| 426 | uDFN08 | `Float` | UDFN08 |
| 427 | uDFN09 | `Float` | UDFN09 |
| 428 | uDFN10 | `Float` | UDFN10 |
| 429 | uDFN11 | `Float` | UDFN11 |
| 430 | uDFN12 | `Float` | UDFN12 |
| 431 | uDFN13 | `Float` | UDFN13 |
| 432 | uDFN14 | `Float` | UDFN14 |
| 433 | uDFN15 | `Float` | UDFN15 |
| 434 | uDFN16 | `Float` | UDFN16 |
| 435 | uDFN17 | `Float` | UDFN17 |
| 436 | uDFN18 | `Float` | UDFN18 |
| 437 | uDFN19 | `Float` | UDFN19 |
| 438 | uDFN20 | `Float` | UDFN20 |
| 439 | uDFN21 | `Float` | UDFN21 |
| 440 | uDFN22 | `Float` | UDFN22 |
| 441 | uDFN23 | `Float` | UDFN23 |
| 442 | uDFN24 | `Float` | UDFN24 |
| 443 | uDFN25 | `Float` | UDFN25 |
| 444 | uDFN26 | `Float` | UDFN26 |
| 445 | uDFN27 | `Float` | UDFN27 |
| 446 | uDFN28 | `Float` | UDFN28 |
| 447 | uDFN29 | `Float` | UDFN29 |
| 448 | uDFN30 | `Float` | UDFN30 |
| 449 | uDFN31 | `Float` | UDFN31 |
| 450 | uDFN32 | `Float` | UDFN32 |
| 451 | uDFN33 | `Float` | UDFN33 |
| 452 | uDFN34 | `Float` | UDFN34 |
| 453 | uDFN35 | `Float` | UDFN35 |
| 454 | uDFN36 | `Float` | UDFN36 |
| 455 | uDFN37 | `Float` | UDFN37 |
| 456 | uDFN38 | `Float` | UDFN38 |
| 457 | uDFN39 | `Float` | UDFN39 |
| 458 | uDFN40 | `Float` | UDFN40 |
| 459 | updateDate | `DateTime` | Update Date |
| 460 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 461 | updateUser | `String` | Update User |
| 462 | updateUserId | `Float` | Update User ID |
| 463 | uploadDate | `Date` | Upload Date |
| 464 | vendorId | `Float` | Vendor ID |
| 465 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 466 | vipAuthorization | `String` | Not Used. |
| 467 | vipName | `String` | VIP Name |
| 468 | vipStatus | `String` | VIP Status |
| 469 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 470 | xcompanyName | `String` | Extended Byte Company Name |
| 471 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 472 | xfirstName | `String` | Xfirst Name |
| 473 | xlastName | `String` | Xlast Name |
| 474 | xmiddleName | `String` | Extended Byte middle name. |

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

### ProfilesAddressesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
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
| profileaddressDetailsChainCode | `StringInput!` | The Chain code of the chain for which this record belongs to.<br>`@mandatoryInput` |
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
#### Validation Rules

**`mandatoryInput`**
- profileaddressDetailsChainCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesAddresses($input: ProfilesAddressesQueryArgumentsType!) {
  profilesAddresses(input: $input) @stream {
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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