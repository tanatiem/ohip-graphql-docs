# SimpleReportsProfileIndividuals
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | profileDetails | [`SimpleReportsProfileIndividualsProfileDetailsType`](#simplereportsprofileindividualsprofiledetailstype) | Profile |
| 2 | profilePropertyDetails | [`SimpleReportsProfileIndividualsProfilePropertyDetailsType`](#simplereportsprofileindividualsprofilepropertydetailstype) | Profile Property |
| 3 | simpleReportsProfileIndividualsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SimpleReportsProfileIndividualsProfileDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 2 | accountType | `String` | Account Type |
| 3 | accountsource | `String` | Accountsource |
| 4 | acctContact | `String` | Billing contact person in company. |
| 5 | activeYn | `String` | Active Y/N |
| 6 | addrCleansedDatetime | `Date` | Addr Cleansed Datetime |
| 7 | addrCleansedErrormsg | `String` | Addr Cleansed Errormsg |
| 8 | addrCleansedStatus | `String` | Addr Cleansed Status |
| 9 | addrCleansedValstatus | `String` | Addr Cleansed Valstatus |
| 10 | addrLanguageCode | `String` | Addr Language Code |
| 11 | addrLanguageDesc | `String` | Addr Language Description |
| 12 | addressId | `Float` | Address ID |
| 13 | addressType | `String` | Address Type |
| 14 | addressTypeDesc | `String` | Address Type Description |
| 15 | address1 | `String` | Address1 |
| 16 | address2 | `String` | Address2 |
| 17 | address3 | `String` | Address3 |
| 18 | address4 | `String` | Address4 |
| 19 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 20 | allOwners | `String` | All Owners |
| 21 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 22 | alternateLanguageDesc | `String` | Xlanguage Description |
| 23 | alternateSalutation | `String` | Alternate Salutation |
| 24 | alternateTitle | `String` | Alternate Title |
| 25 | anonymizationDate | `Date` | System Date when the guest was anonymized in OPERA. |
| 26 | anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| 27 | arNumberCentral | `String` | AR No Central |
| 28 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 29 | availoverYn | `String` | Availover Y/N |
| 30 | barcode | `String` | Barcode |
| 31 | birthCountry | `String` | Country of birth. |
| 32 | birthPlace | `String` | Place of birth. |
| 33 | blMsg | `String` | Bl Msg |
| 34 | businessExtension | `String` | Business Extension |
| 35 | businessPhoneId | `Float` | Business Phone ID |
| 36 | businessPhoneNumber | `String` | Business Phone Number |
| 37 | businessTitle | `String` | Business Title |
| 38 | cRSNameid | `Float` | The unique identifier of the CRS |
| 39 | cblInd | `String` | Cbl Individual |
| 40 | chainCode | `String` | Chain Code |
| 41 | city | `String` | City |
| 42 | cityExt | `String` | City Ext |
| 43 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 44 | comm1CountryDialingCode | `Float` | Comm1 Country Dialing Code |
| 45 | comm1Id | `Float` | Comm1 ID |
| 46 | comm1PhoneCountryCode | `String` | Comm1 Phone Country Code |
| 47 | comm1Type | `String` | Comm1 Type |
| 48 | comm1ValidYn | `String` | Comm1 Valid Y/N |
| 49 | comm1ValidateDate | `Date` | Comm1 Validate Date |
| 50 | comm1ValidateStatus | `String` | Comm1 Validate Status |
| 51 | comm1Value | `String` | Comm1 Value |
| 52 | comm2CountryDialingCode | `Float` | Comm2 Country Dialing Code |
| 53 | comm2Id | `Float` | Comm2 ID |
| 54 | comm2PhoneCountryCode | `String` | Comm2 Phone Country Code |
| 55 | comm2Type | `String` | Comm2 Type |
| 56 | comm2ValidYn | `String` | Comm2 Valid Y/N |
| 57 | comm2ValidateDate | `Date` | Comm2 Validate Date |
| 58 | comm2ValidateStatus | `String` | Comm2 Validate Status |
| 59 | comm2Value | `String` | Comm2 Value |
| 60 | comm3CountryDialingCode | `Float` | Comm3 Country Dialing Code |
| 61 | comm3Id | `Float` | Comm3 ID |
| 62 | comm3PhoneCountryCode | `String` | Comm3 Phone Country Code |
| 63 | comm3Type | `String` | Comm3 Type |
| 64 | comm3ValidYn | `String` | Comm3 Valid Y/N |
| 65 | comm3ValidateDate | `Date` | Comm3 Validate Date |
| 66 | comm3ValidateStatus | `String` | Comm3 Validate Status |
| 67 | comm3Value | `String` | Comm3 Value |
| 68 | commissionAccountId | `Float` | Commission Account ID |
| 69 | commissionAccountName | `String` | Commission Account Name |
| 70 | compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| 71 | company | `String` | Company |
| 72 | companyGroupId | `String` | Linked internal ID for booker. |
| 73 | contactYn | `String` | Contact Y/N |
| 74 | contractNo | `String` | Contract Number (used for customers). |
| 75 | contractRecvDate | `Date` | The date the group contract was received. |
| 76 | country | `String` | Country |
| 77 | countryDesc | `String` | Country Description |
| 78 | creditRating | `String` | Credit Rating |
| 79 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 80 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 81 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 82 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 83 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 84 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 85 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 86 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 87 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 88 | department | `String` | Department |
| 89 | deptId | `String` | Dept ID |
| 90 | directBillBatchType | `String` | Direct Bill Batch Type |
| 91 | displayName | `String` | Display Name |
| 92 | downloadDate | `Date` | Download Date |
| 93 | downloadResort | `String` | Download Property |
| 94 | downloadSrep | `Float` | Download Srep |
| 95 | eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| 96 | eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| 97 | eMail | `String` | E Mail |
| 98 | eMailId | `Float` | E Mail ID |
| 99 | emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| 100 | emailValidateDate | `Date` | Email Validate Date |
| 101 | emailValidateStatus | `String` | Email Validate Status |
| 102 | emailYn | `String` | Email Y/N |
| 103 | envelopeGreeting | `String` | Envelope Greeting |
| 104 | faxCountryCode | `String` | Fax Country Code |
| 105 | faxCountryDialingCode | `Float` | Fax Country Dialing Code |
| 106 | faxId | `Float` | Fax ID |
| 107 | faxNo | `String` | Fax Number |
| 108 | faxValidYn | `String` | Fax Valid Y/N |
| 109 | first | `String` | First |
| 110 | folioAddressId | `Float` | Folio Address ID |
| 111 | gender | `String` | Gender |
| 112 | guestPrivYn | `String` | Guest Priv Y/N |
| 113 | hasnotes | `String` | Hasnotes |
| 114 | historyYn | `String` | History Y/N |
| 115 | holdCode | `String` | Hold Code |
| 116 | homePhoneId | `Float` | Home Phone ID |
| 117 | homePhoneNumber | `String` | Home Phone Number |
| 118 | iataCompType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 119 | iataConsortia | `String` | IATA Consortia |
| 120 | iataCorpNumber | `String` | IATA Corp No |
| 121 | idCountry | `String` | ID Country |
| 122 | idDate | `Date` | ID Date |
| 123 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 124 | idExpirationDate | `Date` | ID Expiration Date |
| 125 | idPlace | `String` | ID Place |
| 126 | idType | `String` | ID Type |
| 127 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 128 | inactiveDate | `Date` | Inactive Date |
| 129 | inactiveReason | `String` | Reason why record was inactivated. |
| 130 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 131 | incognitoDisplayname | `String` | Incognito Displayname |
| 132 | incognitoFirst | `String` | Incognito First |
| 133 | incognitoName | `String` | Incognito Name |
| 134 | incognitoYn | `String` | Incognito Y/N |
| 135 | industryCode | `String` | Industry Code |
| 136 | influence | `String` | Influence |
| 137 | insertDate | `DateTime` | Insert Date |
| 138 | insertUser | `Float` | Insert User |
| 139 | insertUserName | `String` | The name of the user who created the record. |
| 140 | interest | `String` | Interest Code. |
| 141 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 142 | internalPrimaryKeyIDToUniquelyIdentifyTheRow | `Float` | Primary Key ID |
| 143 | jRNUpdateDate | `Date` | JRN Update Date |
| 144 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 145 | keyword | `String` | Keyword |
| 146 | language | `String` | Language |
| 147 | languageDesc | `String` | Description for each language code. |
| 148 | lastGroup | `String` | Last Group |
| 149 | lastRate | `Float` | Last Rate |
| 150 | lastRoom | `String` | Not used. |
| 151 | lastSource | `String` | Last Source |
| 152 | lastStay | `Date` | Last Stay |
| 153 | lastUpdatedResort | `String` | Last property that updated this record. |
| 154 | legalCompany | `String` | Legal Company |
| 155 | letterGreeting | `String` | Letter Greeting |
| 156 | loggedSrepCode | `String` | Logged Srep Code |
| 157 | loyaltySegmentCodes | `String` | Loyalty Segment Codes |
| 158 | mailList | `String` | Mail List |
| 159 | mailType | `String` | The type of mail this user should be sent. |
| 160 | mailYn | `String` | Mail Y/N |
| 161 | marketResearchYn | `String` | Market Research Y/N |
| 162 | markets | `String` | Markets |
| 163 | membershipExpirationDate | `Date` | Membership Expiration Date |
| 164 | membershipId | `Float` | Membership ID |
| 165 | membershipLevel | `String` | Membership Level |
| 166 | membershipNameOnCard | `String` | Membership Name On Card |
| 167 | membershipNumber | `String` | Membership Number |
| 168 | membershipStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| 169 | membershipType | `String` | Membership Type |
| 170 | middle | `String` | Middle |
| 171 | mobilePhoneId | `Float` | Mobile Phone ID |
| 172 | mobilePhoneNumber | `String` | Mobile Phone Number |
| 173 | multipleAddressYn | `String` | Multiple Address Y/N |
| 174 | multipleCommentsYn | `String` | Not used. |
| 175 | multiplePhonesYn | `String` | Multiple Phones Y/N |
| 176 | name | `String` | Name |
| 177 | nameComment | `String` | Not Used. |
| 178 | nameId | `Float` | Name ID |
| 179 | nameKeywords | `String` | Name Keywords |
| 180 | nameType | `String` | Name Type |
| 181 | nameTypeDesc | `String` | Name Type Description |
| 182 | name2 | `String` | Name2 |
| 183 | name3 | `String` | Name3 |
| 184 | nationality | `String` | Nationality |
| 185 | nationalityDesc | `String` | Nationality Description |
| 186 | nextStay | `Date` | Next Stay |
| 187 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 188 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 189 | phoneCountryCode | `String` | Phone Country Code |
| 190 | phoneCountryDialingCode | `Float` | Phone Country Dialing Code |
| 191 | phoneExtension | `String` | Phone Extension |
| 192 | phoneId | `Float` | Phone ID |
| 193 | phoneNo | `String` | Phone no. |
| 194 | phoneType | `String` | Phone Type |
| 195 | phoneValidYn | `String` | Phone Valid Y/N |
| 196 | phoneYn | `String` | Phone Y/N |
| 197 | preferredRoomNo | `String` | Preferred Room Number |
| 198 | profession | `String` | Profession of the guest |
| 199 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 200 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 201 | propertyActionCode | `String` | Property Action Code |
| 202 | propertyCompetitionCode | `String` | Property Competition Code |
| 203 | propertyPriority | `String` | Property Priority |
| 204 | propertyRoomsPotential | `String` | Property Rooms Potential |
| 205 | protected | `String` | Protected |
| 206 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 207 | repAccountType | `String` | Reporting Account Type |
| 208 | repAccountsource | `String` | Reporting Accountsource |
| 209 | repActionCode | `String` | Reporting Actioncode |
| 210 | repIATACompType | `String` | Reporting Iata Comp Type |
| 211 | repInactiveReason | `String` | Reporting Inactive Reason |
| 212 | repIndustryCode | `String` | Reporting Industry Code |
| 213 | repInfluence | `String` | Reporting Influence |
| 214 | repKeyword | `String` | Reporting Keyword |
| 215 | repMarkets | `String` | Reporting Markets |
| 216 | repNameType | `String` | Reporting Name Type |
| 217 | repNationality | `String` | Reporting Nationality |
| 218 | repNationalityDescription | `String` | Reporting Nationality Desc |
| 219 | repPropertyPriority | `String` | Reporting Property Priority |
| 220 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 221 | repScope | `String` | Reporting Scope |
| 222 | repScopeCity | `String` | Reporting Scope City |
| 223 | repState | `String` | Reporting State |
| 224 | repStateDescription | `String` | Reporting State Desc |
| 225 | repTaxType | `String` | Reporting Tax Type |
| 226 | repTerritory | `String` | Reporting Territory |
| 227 | repTitle | `String` | Reporting Title |
| 228 | repTitleName | `String` | Reporting Title Name |
| 229 | repVIPName | `String` | Reporting Vip Name |
| 230 | repVIPStatus | `String` | Reporting Vip Status |
| 231 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 232 | resortRegistered | `String` | Resort for which Job is registered. |
| 233 | restrictReasonCode | `String` | Restrict Reason Code |
| 234 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 235 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 236 | salesrep | `String` | Sales Representative Code for this profile. |
| 237 | salutation | `String` | Salutation Greeting |
| 238 | scope | `String` | Scope |
| 239 | scopeCity | `String` | Scope City |
| 240 | sfirst | `String` | Uppercase value of First Name. |
| 241 | smsYn | `String` | Use this alert to text a notification. |
| 242 | sname | `String` | The Uppercase value of Last or Company. |
| 243 | srepCode | `String` | Srep Code |
| 244 | srepId | `Float` | Srep ID |
| 245 | state | `String` | State |
| 246 | stateDesc | `String` | State Description of the Guest of Payee |
| 247 | suffix | `String` | Suffix |
| 248 | summRefCc | `String` | Summ Ref Cc |
| 249 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 250 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 251 | tax1No | `String` | Tax1 Number |
| 252 | tax2No | `String` | Tax2 Number |
| 253 | taxCategory | `String` | Tax Category |
| 254 | taxOffice | `String` | Tax Office Name |
| 255 | taxType | `String` | Tax Type |
| 256 | territory | `String` | Territory |
| 257 | thirdPartyYn | `String` | Third Party Y/N |
| 258 | title | `String` | Title |
| 259 | titleName | `String` | Title Name |
| 260 | titleSuffix | `Float` | Title Suffix |
| 261 | totalStay | `Float` | Total Stay |
| 262 | tracecode | `String` | Tracecode |
| 263 | udfc01 | `String` | Udfc01 |
| 264 | udfc02 | `String` | Udfc02 |
| 265 | udfc03 | `String` | Udfc03 |
| 266 | udfc04 | `String` | Udfc04 |
| 267 | udfc05 | `String` | Udfc05 |
| 268 | udfc06 | `String` | Udfc06 |
| 269 | udfc07 | `String` | Udfc07 |
| 270 | udfc08 | `String` | Udfc08 |
| 271 | udfc09 | `String` | Udfc09 |
| 272 | udfc10 | `String` | Udfc10 |
| 273 | udfc11 | `String` | Udfc11 |
| 274 | udfc12 | `String` | Udfc12 |
| 275 | udfc13 | `String` | Udfc13 |
| 276 | udfc14 | `String` | Udfc14 |
| 277 | udfc15 | `String` | Udfc15 |
| 278 | udfc16 | `String` | Udfc16 |
| 279 | udfc17 | `String` | Udfc17 |
| 280 | udfc18 | `String` | Udfc18 |
| 281 | udfc19 | `String` | Udfc19 |
| 282 | udfc20 | `String` | Udfc20 |
| 283 | udfc21 | `String` | Udfc21 |
| 284 | udfc22 | `String` | Udfc22 |
| 285 | udfc23 | `String` | Udfc23 |
| 286 | udfc24 | `String` | Udfc24 |
| 287 | udfc25 | `String` | Udfc25 |
| 288 | udfc26 | `String` | Udfc26 |
| 289 | udfc27 | `String` | Udfc27 |
| 290 | udfc28 | `String` | Udfc28 |
| 291 | udfc29 | `String` | Udfc29 |
| 292 | udfc30 | `String` | Udfc30 |
| 293 | udfc31 | `String` | Udfc31 |
| 294 | udfc32 | `String` | Udfc32 |
| 295 | udfc33 | `String` | Udfc33 |
| 296 | udfc34 | `String` | Udfc34 |
| 297 | udfc35 | `String` | Udfc35 |
| 298 | udfc36 | `String` | Udfc36 |
| 299 | udfc37 | `String` | Udfc37 |
| 300 | udfc38 | `String` | Udfc38 |
| 301 | udfc39 | `String` | Udfc39 |
| 302 | udfc40 | `String` | Udfc40 |
| 303 | udfd01 | `Date` | Udfd01 |
| 304 | udfd02 | `Date` | Udfd02 |
| 305 | udfd03 | `Date` | Udfd03 |
| 306 | udfd04 | `Date` | Udfd04 |
| 307 | udfd05 | `Date` | Udfd05 |
| 308 | udfd06 | `Date` | Udfd06 |
| 309 | udfd07 | `Date` | Udfd07 |
| 310 | udfd08 | `Date` | Udfd08 |
| 311 | udfd09 | `Date` | Udfd09 |
| 312 | udfd10 | `Date` | Udfd10 |
| 313 | udfd11 | `Date` | Udfd11 |
| 314 | udfd12 | `Date` | Udfd12 |
| 315 | udfd13 | `Date` | Udfd13 |
| 316 | udfd14 | `Date` | Udfd14 |
| 317 | udfd15 | `Date` | Udfd15 |
| 318 | udfd16 | `Date` | Udfd16 |
| 319 | udfd17 | `Date` | Udfd17 |
| 320 | udfd18 | `Date` | Udfd18 |
| 321 | udfd19 | `Date` | Udfd19 |
| 322 | udfd20 | `Date` | Udfd20 |
| 323 | udfn01 | `Float` | Udfn01 |
| 324 | udfn02 | `Float` | Udfn02 |
| 325 | udfn03 | `Float` | Udfn03 |
| 326 | udfn04 | `Float` | Udfn04 |
| 327 | udfn05 | `Float` | Udfn05 |
| 328 | udfn06 | `Float` | Udfn06 |
| 329 | udfn07 | `Float` | Udfn07 |
| 330 | udfn08 | `Float` | Udfn08 |
| 331 | udfn09 | `Float` | Udfn09 |
| 332 | udfn10 | `Float` | Udfn10 |
| 333 | udfn11 | `Float` | Udfn11 |
| 334 | udfn12 | `Float` | Udfn12 |
| 335 | udfn13 | `Float` | Udfn13 |
| 336 | udfn14 | `Float` | Udfn14 |
| 337 | udfn15 | `Float` | Udfn15 |
| 338 | udfn16 | `Float` | Udfn16 |
| 339 | udfn17 | `Float` | Udfn17 |
| 340 | udfn18 | `Float` | Udfn18 |
| 341 | udfn19 | `Float` | Udfn19 |
| 342 | udfn20 | `Float` | Udfn20 |
| 343 | udfn21 | `Float` | Udfn21 |
| 344 | udfn22 | `Float` | Udfn22 |
| 345 | udfn23 | `Float` | Udfn23 |
| 346 | udfn24 | `Float` | Udfn24 |
| 347 | udfn25 | `Float` | Udfn25 |
| 348 | udfn26 | `Float` | Udfn26 |
| 349 | udfn27 | `Float` | Udfn27 |
| 350 | udfn28 | `Float` | Udfn28 |
| 351 | udfn29 | `Float` | Udfn29 |
| 352 | udfn30 | `Float` | Udfn30 |
| 353 | udfn31 | `Float` | Udfn31 |
| 354 | udfn32 | `Float` | Udfn32 |
| 355 | udfn33 | `Float` | Udfn33 |
| 356 | udfn34 | `Float` | Udfn34 |
| 357 | udfn35 | `Float` | Udfn35 |
| 358 | udfn36 | `Float` | Udfn36 |
| 359 | udfn37 | `Float` | Udfn37 |
| 360 | udfn38 | `Float` | Udfn38 |
| 361 | udfn39 | `Float` | Udfn39 |
| 362 | udfn40 | `Float` | Udfn40 |
| 363 | updateDate | `DateTime` | Update Date |
| 364 | updateUser | `Float` | Update User |
| 365 | updateUserName | `String` | Update User Name |
| 366 | uploadDate | `Date` | Upload Date |
| 367 | vipName | `String` | VIP Name |
| 368 | vipStatus | `String` | VIP Status |
| 369 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 370 | webPage | `String` | Web Page |
| 371 | webPageId | `Float` | Web Page ID |
| 372 | xdisplayName | `String` | Xdisplay Name |
| 373 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 374 | xfirstName | `String` | Xfirst Name |
| 375 | xmiddleName | `String` | Extended Byte middle name. |
| 376 | xname | `String` | Xname |
| 377 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### SimpleReportsProfileIndividualsProfilePropertyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionCode | `String` | Action Code |
| 2 | arNumber | `String` | AR No |
| 3 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 4 | billingInstruction | `String` | Billing Instruction |
| 5 | birGuestType | `String` | Guest type in PH country mode. Further used for showing proper adjustment options. |
| 6 | businessId | `String` | Business ID |
| 7 | businessRegistration | `String` | This column stores the BUSINESS REGISTRATION for a Profile for this property. |
| 8 | commissionCode | `String` | Commission Code |
| 9 | competitionCode | `String` | Competition Code |
| 10 | currencyCode | `String` | Currency Code |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | departmentNote | `String` | Department Note |
| 13 | electronicFiscalFlag | `String` | Indicates if a Profile can be marked to Generate Fiscal Folio/Payload. |
| 14 | features | `String` | Features |
| 15 | guestType | `Float` | Guest Type |
| 16 | internalPrimaryKeyIDToUniquelyIdentifyTheRow | `Float` | Primary Key ID |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | lastPrivacyPromptDate | `Date` | Last date the guest was prompted for privacy option. |
| 20 | nameId | `Float` | Name ID |
| 21 | nameTaxType | `String` | Name Tax Type |
| 22 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 23 | paymentMethod | `String` | Payment Method |
| 24 | potentialNights | `Float` | Potential Nights |
| 25 | potentialRevenue | `Float` | Potential Revenue |
| 26 | priority | `String` | Priority |
| 27 | productInterest | `String` | Product Interest |
| 28 | property | `String` | Code to uniquely identify the Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | rateCode | `String` | Rate Code |
| 32 | repActionCode | `String` | Reporting Actioncode |
| 33 | repCompetitionCode | `String` | Reporting Competition Code |
| 34 | repPriority | `String` | Reporting Priority |
| 35 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 36 | roomsPotential | `String` | Rooms Potential |
| 37 | specials | `String` | Specials |
| 38 | taxPerc1 | `Float` | Tax Perc1 |
| 39 | taxPerc2 | `Float` | Tax Perc2 |
| 40 | taxPerc3 | `Float` | Tax Perc3 |
| 41 | taxPerc4 | `Float` | Tax Perc4 |
| 42 | taxPerc5 | `Float` | Tax Perc5 |
| 43 | vatOffsetYn | `String` | Vat Offset Y/N |

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
#### Validation Rules

**`mandatoryInput`**
- nameDetailsChainCode


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
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
    'updateUser': pl.Int64,
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
```
```python
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
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