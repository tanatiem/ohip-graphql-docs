# FinancialCommissions
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `financialCommissions`
> Detailed information on the commissions module including Reservation and Travel Agent profile information with commission codes amounts payment activity and processing status. Commission information can be reported across all properties by Travel Agent and Source profiles bank account guest information and dates.
  
**Return:** [`[FinancialCommissionsType]`](#financialcommissionstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`FinancialCommissionsQueryArgumentsType!`](#financialcommissionsqueryargumentstype) |  |

## Object Types

### FinancialCommissionsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | commissionAgentDetails | [`FinancialCommissionsCommissionAgentDetailsType`](#financialcommissionscommissionagentdetailstype) | Commission Agent Details |
| 2 | profileCommissionBankAccountDetails | [`FinancialCommissionsProfileCommissionBankAccountDetailsType`](#financialcommissionsprofilecommissionbankaccountdetailstype) | Profile Commission Bank Account Details |
| 3 | computedCommissionsReservationDetails | [`FinancialCommissionsComputedCommissionsReservationDetailsType`](#financialcommissionscomputedcommissionsreservationdetailstype) | Computed Commission Reservation Details |
| 4 | checkRegisterDetails | [`FinancialCommissionsCheckRegisterDetailsType`](#financialcommissionscheckregisterdetailstype) | Check Register Details |
| 5 | financialCommissionsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### FinancialCommissionsCommissionAgentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountName2 | `String` | Account Name 2 |
| 5 | accountName3 | `String` | Account Name 3 |
| 6 | accountOwnersAll | `String` | Account Owners(All) |
| 7 | accountPhonePrimary | `String` | Phone no. |
| 8 | accountPhoneWeb | `String` | Account Phone Web |
| 9 | accountSource | `String` | Account Source |
| 10 | accountSourceDescription | `String` | Account Source Description |
| 11 | accountType | `String` | Account Type |
| 12 | accountTypeDescription | `String` | Account Type Description |
| 13 | acctContact | `String` | Billing contact person in company. |
| 14 | actionCode | `String` | Action Code |
| 15 | activeFlag | `String` | Active Flag |
| 16 | address1 | `String` | Address 1 |
| 17 | address2 | `String` | Address 2 |
| 18 | address3 | `String` | Address 3 |
| 19 | address4 | `String` | Address 4 |
| 20 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 21 | addressLanguageCode | `String` | Address Language Code |
| 22 | addressType | `String` | Address Type |
| 23 | allResorts | `String` | All Resorts |
| 24 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 25 | alternateLanguageDescription | `String` | Alternate Language Description |
| 26 | alternateName | `String` | Alternate Name |
| 27 | alternateSalutation | `String` | Alternate Salutation |
| 28 | alternateTitle | `String` | Alternate Title |
| 29 | arNumberCentral | `String` | AR No Central |
| 30 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 31 | billingInstruction | `String` | Billing Instruction |
| 32 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 33 | birthDate | `Date` | Birth Date |
| 34 | birthDateStr | `String` | Birth Date Str |
| 35 | birthPlace | `String` | Place of birth. |
| 36 | blMsg | `String` | Bl Msg |
| 37 | businessPotential | `String` | Business Potential |
| 38 | businessPotentialDescription | `String` | Business Potential Description |
| 39 | businessSegementDescription | `String` | Business Segement Description |
| 40 | businessSegment | `String` | Business Segment |
| 41 | businessTitle | `String` | Business Title |
| 42 | centralAccountSource | `String` | Central Account Source |
| 43 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 44 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 45 | centralBusinessPotential | `String` | Central Business Potential |
| 46 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 47 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 48 | centralBusinessSegment | `String` | Central Business Segment |
| 49 | centralCompetitionCode | `String` | Central Competition Code |
| 50 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 51 | centralCorporateType | `String` | Central Corporate Type |
| 52 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 53 | centralInactiveReason | `String` | Central Inactive Reason |
| 54 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 55 | centralIndustryCode | `String` | Central Industry Code |
| 56 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 57 | centralKeyword | `String` | Central Keyword |
| 58 | centralMailAction | `String` | Central Mail Action |
| 59 | centralMailActionDescription | `String` | Central Mail Action Description |
| 60 | centralPriority | `String` | Central Priority |
| 61 | centralPriorityDescription | `String` | Central Priority Description |
| 62 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 63 | centralScope | `String` | Central Scope |
| 64 | centralScopeCity | `String` | Central Scope City |
| 65 | centralScopeCityDescription | `String` | Central Scope City Description |
| 66 | centralScopeDescription | `String` | Central Scope Description |
| 67 | centralState | `String` | Central State |
| 68 | centralTerritory | `String` | Central Territory |
| 69 | centralTerritoryDescription | `String` | Central Territory Description |
| 70 | chainCode | `String` | Chain Code |
| 71 | city | `String` | City |
| 72 | cityExt | `String` | City Ext |
| 73 | combinedName | `String` | Combined Name |
| 74 | commissionCode | `String` | Commission Code |
| 75 | commissionCodeAll | `String` | Commission Code(All) |
| 76 | communicationRole1 | `String` | Communication Role1 |
| 77 | communicationRole2 | `String` | Communication Role2 |
| 78 | communicationRole3 | `String` | Communication Role3 |
| 79 | communicationType1 | `String` | Communication Type1 |
| 80 | communicationType2 | `String` | Communication Type2 |
| 81 | communicationType3 | `String` | Communication Type3 |
| 82 | communicationValue1 | `String` | Communication Value1 |
| 83 | communicationValue2 | `String` | Communication Value2 |
| 84 | communicationValue3 | `String` | Communication Value3 |
| 85 | company | `String` | Company |
| 86 | competitionCode | `String` | Competition Code |
| 87 | competitionCodeDescription | `String` | Competition Code Description |
| 88 | corpID | `String` | Corp ID |
| 89 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 90 | corporateTypeDescription | `String` | Corporate Type Description |
| 91 | country | `String` | Country |
| 92 | countryCode | `String` | Country Code |
| 93 | createdByUser | `String` | Created By User |
| 94 | createdOnDate | `DateTime` | Created On Date |
| 95 | creditCardName | `String` | Credit Card Name |
| 96 | creditCardType | `String` | Credit Card Type |
| 97 | creditRating | `String` | Credit Rating |
| 98 | currencyCode | `String` | Currency Code |
| 99 | currencyDescription | `String` | Currency Description |
| 100 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 101 | deletedFlag | `String` | Deleted Flag |
| 102 | emailYn | `String` | Email Y/N |
| 103 | envelopeGreeting | `String` | Envelope Greeting |
| 104 | externalId | `String` | External ID |
| 105 | fSubscriptionDb | `String` | F Subscription Db |
| 106 | fSubscriptionYn | `String` | F Subscription Y/N |
| 107 | faxNo | `String` | Fax Number |
| 108 | first | `String` | First |
| 109 | gender | `String` | Gender |
| 110 | guestPrivYn | `String` | Guest Priv Y/N |
| 111 | historyYn | `String` | History Y/N |
| 112 | holdCode | `String` | Hold Code |
| 113 | iataConsortia | `String` | IATA Consortia |
| 114 | inactiveDate | `DateTime` | Inactive Date |
| 115 | inactiveFlag | `String` | Inactive Flag |
| 116 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 117 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 118 | industryCode | `String` | Industry Code |
| 119 | industryCodeDescription | `String` | Industry Code Description |
| 120 | interest | `String` | Interest Code. |
| 121 | internalDeletedflag | `String` | Deleted Flag |
| 122 | internalInactiveflag | `String` | Inactive Flag |
| 123 | internalOrganizationId | `Float` | Organization ID |
| 124 | jRNUpdateDate | `Date` | JRN Update Date |
| 125 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 126 | keyword | `String` | Keyword |
| 127 | last | `String` | Last |
| 128 | lastGroup | `String` | Last Group |
| 129 | lastRate | `Float` | Last Rate |
| 130 | lastRoom | `String` | Not used. |
| 131 | lastSource | `String` | Last Source |
| 132 | lastStay | `Date` | Last Stay |
| 133 | legalCompany | `String` | Legal Company |
| 134 | letterGreeting | `String` | Letter Greeting |
| 135 | mailAction | `String` | Mail Action |
| 136 | mailActionDescription | `String` | Mail Action Description |
| 137 | mailList | `String` | Mail List |
| 138 | mailType | `String` | The type of mail this user should be sent. |
| 139 | mailYn | `String` | Mail Y/N |
| 140 | marketResearchYn | `String` | Market Research Y/N |
| 141 | middle | `String` | Middle |
| 142 | nameId | `Float` | Name ID |
| 143 | nationalityCode | `String` | Nationality Code |
| 144 | nationalityDescription | `String` | Nationality Description |
| 145 | negotiatedRate | `String` | Negotiated Rate |
| 146 | nextStay | `Date` | Next Stay |
| 147 | nickname | `String` | The nickname of this individual. |
| 148 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 149 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 150 | postalCode | `String` | Postal Code |
| 151 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 152 | primaryOwner | `String` | Primary Owner |
| 153 | primaryOwnerCode | `String` | Primary Owner Code |
| 154 | priority | `String` | Priority |
| 155 | priorityDescription | `String` | Priority Description |
| 156 | productInterest | `String` | Product Interest |
| 157 | profession | `String` | Profession of the guest |
| 158 | profileLanguage | `String` | Profile Language |
| 159 | profileLanguageDescription | `String` | Profile Language Description |
| 160 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 161 | profileType | `String` | Profile Type |
| 162 | profileTypeCode | `String` | Profile Type Code |
| 163 | profileTypeDescription | `String` | Profile Type Description |
| 164 | protected | `String` | Protected |
| 165 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 166 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 167 | referenceCurrency | `String` | Reference Currency |
| 168 | repAccountType | `String` | Rep Account Type |
| 169 | repInfluence | `String` | Reporting Influence |
| 170 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 171 | repNameType | `String` | Rep Name Type |
| 172 | repNationalityCode | `String` | Reporting Nationality Code |
| 173 | repNationalityDescription | `String` | Reporting Nationality Description |
| 174 | repStateDescription | `String` | Reporting State Desc |
| 175 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 176 | repTitle | `String` | Reporting Title |
| 177 | repTitleName | `String` | Reporting Title Name |
| 178 | repVIPName | `String` | Reporting Vip Name |
| 179 | repVIPStatus | `String` | Reporting Vip Status |
| 180 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 181 | resortRegistered | `String` | Resort for which Job is registered. |
| 182 | restricted | `String` | Restricted |
| 183 | restrictedRule | `String` | Restricted Rule |
| 184 | salutation | `String` | Salutation Greeting |
| 185 | scope | `String` | Scope |
| 186 | scopeCity | `String` | Scope City |
| 187 | scopeCityDescription | `String` | Scope City Description |
| 188 | scopeDescription | `String` | Scope Description |
| 189 | sfirst | `String` | Uppercase value of First Name. |
| 190 | sname | `String` | The Uppercase value of Last or Company. |
| 191 | state | `String` | State |
| 192 | stateDesc | `String` | State Description of the Guest of Payee |
| 193 | stateDescription | `String` | State Description |
| 194 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 195 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 196 | tax1No | `String` | Tax1 Number |
| 197 | tax2No | `String` | Tax2 Number |
| 198 | taxCategory | `String` | Tax Category |
| 199 | taxType | `String` | Tax Type |
| 200 | taxTypeDescription | `String` | Tax Type Description |
| 201 | territory | `String` | Territory |
| 202 | territoryDescription | `String` | Territory Description |
| 203 | thirdPartyYn | `String` | Third Party Y/N |
| 204 | title | `String` | Title |
| 205 | topAccountID | `Float` | Top Account ID |
| 206 | topAccountName | `String` | Top Account Name |
| 207 | traceCode | `String` | Trace Code |
| 208 | traceCodeDescription | `String` | Trace Code Description |
| 209 | uDFC01 | `String` | UDFC01 |
| 210 | uDFC02 | `String` | UDFC02 |
| 211 | uDFC03 | `String` | UDFC03 |
| 212 | uDFC04 | `String` | UDFC04 |
| 213 | uDFC05 | `String` | UDFC05 |
| 214 | uDFC06 | `String` | UDFC06 |
| 215 | uDFC07 | `String` | UDFC07 |
| 216 | uDFC08 | `String` | UDFC08 |
| 217 | uDFC09 | `String` | UDFC09 |
| 218 | uDFC10 | `String` | UDFC10 |
| 219 | uDFC11 | `String` | UDFC11 |
| 220 | uDFC12 | `String` | UDFC12 |
| 221 | uDFC13 | `String` | UDFC13 |
| 222 | uDFC14 | `String` | UDFC14 |
| 223 | uDFC15 | `String` | UDFC15 |
| 224 | uDFC16 | `String` | UDFC16 |
| 225 | uDFC17 | `String` | UDFC17 |
| 226 | uDFC18 | `String` | UDFC18 |
| 227 | uDFC19 | `String` | UDFC19 |
| 228 | uDFC20 | `String` | UDFC20 |
| 229 | uDFC21 | `String` | UDFC21 |
| 230 | uDFC22 | `String` | UDFC22 |
| 231 | uDFC23 | `String` | UDFC23 |
| 232 | uDFC24 | `String` | UDFC24 |
| 233 | uDFC25 | `String` | UDFC25 |
| 234 | uDFC26 | `String` | UDFC26 |
| 235 | uDFC27 | `String` | UDFC27 |
| 236 | uDFC28 | `String` | UDFC28 |
| 237 | uDFC29 | `String` | UDFC29 |
| 238 | uDFC30 | `String` | UDFC30 |
| 239 | uDFC31 | `String` | UDFC31 |
| 240 | uDFC32 | `String` | UDFC32 |
| 241 | uDFC33 | `String` | UDFC33 |
| 242 | uDFC34 | `String` | UDFC34 |
| 243 | uDFC35 | `String` | UDFC35 |
| 244 | uDFC36 | `String` | UDFC36 |
| 245 | uDFC37 | `String` | UDFC37 |
| 246 | uDFC38 | `String` | UDFC38 |
| 247 | uDFC39 | `String` | UDFC39 |
| 248 | uDFC40 | `String` | UDFC40 |
| 249 | uDFD01 | `Date` | UDFD01 |
| 250 | uDFD02 | `Date` | UDFD02 |
| 251 | uDFD03 | `Date` | UDFD03 |
| 252 | uDFD04 | `Date` | UDFD04 |
| 253 | uDFD05 | `Date` | UDFD05 |
| 254 | uDFD06 | `Date` | UDFD06 |
| 255 | uDFD07 | `Date` | UDFD07 |
| 256 | uDFD08 | `Date` | UDFD08 |
| 257 | uDFD09 | `Date` | UDFD09 |
| 258 | uDFD10 | `Date` | UDFD10 |
| 259 | uDFD11 | `Date` | UDFD11 |
| 260 | uDFD12 | `Date` | UDFD12 |
| 261 | uDFD13 | `Date` | UDFD13 |
| 262 | uDFD14 | `Date` | UDFD14 |
| 263 | uDFD15 | `Date` | UDFD15 |
| 264 | uDFD16 | `Date` | UDFD16 |
| 265 | uDFD17 | `Date` | UDFD17 |
| 266 | uDFD18 | `Date` | UDFD18 |
| 267 | uDFD19 | `Date` | UDFD19 |
| 268 | uDFD20 | `Date` | UDFD20 |
| 269 | uDFN01 | `Float` | UDFN01 |
| 270 | uDFN02 | `Float` | UDFN02 |
| 271 | uDFN03 | `Float` | UDFN03 |
| 272 | uDFN04 | `Float` | UDFN04 |
| 273 | uDFN05 | `Float` | UDFN05 |
| 274 | uDFN06 | `Float` | UDFN06 |
| 275 | uDFN07 | `Float` | UDFN07 |
| 276 | uDFN08 | `Float` | UDFN08 |
| 277 | uDFN09 | `Float` | UDFN09 |
| 278 | uDFN10 | `Float` | UDFN10 |
| 279 | uDFN11 | `Float` | UDFN11 |
| 280 | uDFN12 | `Float` | UDFN12 |
| 281 | uDFN13 | `Float` | UDFN13 |
| 282 | uDFN14 | `Float` | UDFN14 |
| 283 | uDFN15 | `Float` | UDFN15 |
| 284 | uDFN16 | `Float` | UDFN16 |
| 285 | uDFN17 | `Float` | UDFN17 |
| 286 | uDFN18 | `Float` | UDFN18 |
| 287 | uDFN19 | `Float` | UDFN19 |
| 288 | uDFN20 | `Float` | UDFN20 |
| 289 | uDFN21 | `Float` | UDFN21 |
| 290 | uDFN22 | `Float` | UDFN22 |
| 291 | uDFN23 | `Float` | UDFN23 |
| 292 | uDFN24 | `Float` | UDFN24 |
| 293 | uDFN25 | `Float` | UDFN25 |
| 294 | uDFN26 | `Float` | UDFN26 |
| 295 | uDFN27 | `Float` | UDFN27 |
| 296 | uDFN28 | `Float` | UDFN28 |
| 297 | uDFN29 | `Float` | UDFN29 |
| 298 | uDFN30 | `Float` | UDFN30 |
| 299 | uDFN31 | `Float` | UDFN31 |
| 300 | uDFN32 | `Float` | UDFN32 |
| 301 | uDFN33 | `Float` | UDFN33 |
| 302 | uDFN34 | `Float` | UDFN34 |
| 303 | uDFN35 | `Float` | UDFN35 |
| 304 | uDFN36 | `Float` | UDFN36 |
| 305 | uDFN37 | `Float` | UDFN37 |
| 306 | uDFN38 | `Float` | UDFN38 |
| 307 | uDFN39 | `Float` | UDFN39 |
| 308 | uDFN40 | `Float` | UDFN40 |
| 309 | updateDate | `DateTime` | Update Date |
| 310 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 311 | updateUser | `String` | Update User |
| 312 | vipName | `String` | VIP Name |
| 313 | vipStatus | `String` | VIP Status |
| 314 | xcompanyName | `String` | Extended Byte Company Name |
| 315 | xenvelopeGreeting | `String` | Xenvelope Greeting |
| 316 | xfirstName | `String` | Xfirst Name |
| 317 | xlastName | `String` | Xlast Name |
| 318 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### FinancialCommissionsProfileCommissionBankAccountDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountId | `Float` | Account ID |
| 2 | accountNumber | `String` | Account Number |
| 3 | bankAcctType | `String` | Flag to identify bank type  [O] OVOS user |
| 4 | bankCode | `String` | Code for the bank account |
| 5 | branchCode | `String` | Code for the bank accounts branch |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | centralCommissionCode | `String` | Central Commission Code |
| 9 | centralCommissionCodeDescription | `String` | Central Commission Code Description |
| 10 | centralMinProcessingAmount | `Float` | Central Min. Processing Amount |
| 11 | checkReport | `String` | Check Report |
| 12 | checkSubLines | `Float` | Number of lines to be printed on check stub |
| 13 | commissionCode | `String` | Commission Code |
| 14 | commissionCodeDescription | `String` | Commission Code Description |
| 15 | currency | `String` | Currency |
| 16 | currencyDescription | `String` | Currency Description |
| 17 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 18 | defaultYN | `String` | Default YN |
| 19 | defaultForCurrencyYN | `String` | Only one 'Y' value is permitted per resort / currency combination used mainly by interface to figure out default bank for resort and currency combination |
| 20 | deletedFlag | `String` | Deleted Flag |
| 21 | description | `String` | Bank name |
| 22 | editCheckNumberYN | `String` | Check number allowed to be edited Y/N |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | jRNUpdateDate | `Date` | JRN Update Date |
| 26 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 27 | language | `String` | Language |
| 28 | laptopChange | `Float` | Laptop Change |
| 29 | lastExportDate | `Date` | Last Export File Run Date |
| 30 | lastExportedFile | `Float` | Last Export Run File Number |
| 31 | locationID | `String` | Internal ID to uniquely identify the Property |
| 32 | maxCheckNo | `Float` | Internal |
| 33 | minProcessingAmount | `Float` | Minimum amount required to produce a check through commission processing for the selected account. |
| 34 | nameId | `Float` | Name ID |
| 35 | nextCheckNumber | `Float` | Last check number used by commisison handling module for bank account selected |
| 36 | onHold | `Float` | On Hold |
| 37 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 38 | paidInAR | `Float` | Paid in AR |
| 39 | paymentMethod | `String` | Payment Method |
| 40 | positivePayExportYN | `String` | Indicate that the bank account uses Positive Pay Export. |
| 41 | potential | `Float` | Potential |
| 42 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 43 | profileCommissionAccountId | `Float` | Account ID |
| 44 | profileCommissionCreatedByUser | `Float` | Created By User |
| 45 | profileCommissionCreatedOnDate | `DateTime` | Created On Date |
| 46 | profileCommissionDSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 47 | profileCommissionDeletedFlag | `String` | Deleted Flag |
| 48 | profileCommissionJRNUpdateDate | `DateTime` | Profile Commission JRN Update Date |
| 49 | profileCommissionJRNUpdateDateAndTime | `DateTime` | Profile Commission JRN Update Date and Time |
| 50 | profileCommissionOrganizationID | `Float` | Internal ID to uniquely identify the Organization |
| 51 | profileCommissionPrimaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 52 | profileCommissionProperty | `String` | Code to uniquely identify the Property |
| 53 | profileCommissionRnaInsertDate | `DateTime` | RnA Insertdate |
| 54 | profileCommissionRnaUpdateDate | `DateTime` | RnA Updatedate |
| 55 | profileCommissionUpdateDate | `DateTime` | Update Date |
| 56 | profileCommissionUpdateUser | `Float` | Update User |
| 57 | property | `String` | Property |
| 58 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 59 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 60 | routingNumber | `String` | Routing number for the bank account |
| 61 | sourceImportDir | `String` | Source directory for importing commission information. |
| 62 | targetImportDir | `String` | Target directory where import files will be stored. |
| 63 | tax1099ReportYN | `String` | Indicate that bank account use 1099 report |
| 64 | toBePaid | `Float` | To Be Paid |
| 65 | updateDate | `DateTime` | Update Date |
| 66 | updateUser | `Float` | Update User |
| 67 | validateIATANumberYN | `String` | Force validation of TA/Source IATA number during commision payment process. |

[⬆ Back to Query](#query)

---

### FinancialCommissionsComputedCommissionsReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | accountsReceivablesOffset | `Float` | Receivables Amount. |
| 5 | accountsReceivablesYN | `String` | Indicate that this commission should be treated as a direct bill settlement. |
| 6 | actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| 7 | actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| 8 | actualCheckInDate | `Date` | Actual Check-In Date |
| 9 | actualCheckInTime | `String` | Actual Check-In Time |
| 10 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 11 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 12 | addressId | `Float` | Address ID |
| 13 | addresseeNameId | `Float` | Addressee Name ID |
| 14 | adjustmentNote | `String` | Contains notes about user actions when user manually adjusts commission. |
| 15 | adults | `Float` | Adults |
| 16 | adultsTaxFree | `Float` | Adults Tax Free |
| 17 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 18 | agencyprofileid | `Float` | Agencyprofileid |
| 19 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 20 | allotmentid | `Float` | Block ID |
| 21 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 22 | amenityLevelCode | `String` | Amenity Level Code |
| 23 | amount | `Float` | Commission for TA. |
| 24 | amountPercent | `Float` | Amount Percent |
| 25 | approvalAmount | `Float` | Approval Amount |
| 26 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 27 | approvalCode | `String` | Approval Code |
| 28 | arrivalComments | `String` | Arrival Comments |
| 29 | arrivalDate | `Date` | Arrival Date |
| 30 | arrivalDateTime | `DateTime` | Arrival Date Time |
| 31 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 32 | arrivalTime | `String` | Activity begin time |
| 33 | arrivaltransportid | `String` | Arrivaltransportid |
| 34 | authorizedBillingYN | `String` | Not used. |
| 35 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 36 | authorizerId | `Float` | Authorizer ID |
| 37 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 38 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 39 | autoSettleDays | `Float` | Auto Settle Days |
| 40 | autoSettleType | `String` | Auto Settle Type |
| 41 | autoSettleYN | `String` | Auto Settle YN |
| 42 | awardCode | `String` | Award Code |
| 43 | awardCode1 | `String` | Award code 1 |
| 44 | awardCode2 | `String` | Award code 2 |
| 45 | awardCode3 | `String` | Award code 3 |
| 46 | awardCode4 | `String` | Award Code 4 |
| 47 | awardCode5 | `String` | Award code 5 |
| 48 | awardMembershipID | `Float` | Award Membership ID |
| 49 | awardVoucher1 | `String` | Award Voucher number 1 |
| 50 | awardVoucher2 | `String` | Award Voucher number 2 |
| 51 | awardVoucher3 | `String` | Award Voucher number 3 |
| 52 | awardVoucher4 | `String` | Award Voucher number 4 |
| 53 | awardVoucher5 | `String` | Award Voucher number 5 |
| 54 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 55 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 56 | backToBackYN | `String` | Back To Back YN |
| 57 | balance | `Float` | Balance on the account. |
| 58 | baseRateAmount | `Float` | Base Rate Amount |
| 59 | baseRateCode | `String` | Base Rate Code |
| 60 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 61 | basedOnRule | `String` | Based On Rule |
| 62 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 63 | beginCity | `String` | Begin City |
| 64 | beginDatetime | `DateTime` | Begin Datetime |
| 65 | beginDistrict | `String` | Begin District |
| 66 | beginState | `String` | Begin State |
| 67 | beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| 68 | billNumber | `String` | Bill Number |
| 69 | billingContact | `String` | Billing Contact |
| 70 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 71 | billingContactId | `Float` | Billing Contact ID |
| 72 | billingContactName | `String` | Billing Contact Name |
| 73 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 74 | blockCode | `String` | Block Code |
| 75 | blockCreateDate | `DateTime` | Block Create Date |
| 76 | blockID | `Float` | Block ID |
| 77 | blockName | `String` | Block Name |
| 78 | blockResort | `String` | Property this block belongs to. |
| 79 | blockStatus | `String` | Block Status |
| 80 | bonusCheckId | `Float` | Bonus Check ID |
| 81 | bookedRoomCategory | `String` | Booked Room Category |
| 82 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 83 | businessDateCreated | `Date` | Business Date Created |
| 84 | businessDatetimeCreated | `DateTime` | Business Datetime Created |
| 85 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 86 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 87 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 88 | cCommissionableRevenue | `Float` | Central Commissionable Revenue |
| 89 | cDiscountAmount | `Float` | C Discount Amount |
| 90 | cDiscountAmt | `Float` | C Discount Amt |
| 91 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 92 | cExchangeDate | `Date` | Central Xchange Date |
| 93 | cExchangeRate | `Float` | Central Xchange Rate |
| 94 | cFixedCharge | `Float` | Central Fixed Charge |
| 95 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 96 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 97 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 98 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 99 | cPackageAmount | `Float` | Central Pkg Amt |
| 100 | cPackageTax | `Float` | Central Pkg Tax |
| 101 | cRateAmount | `Float` | C Rate Amount |
| 102 | cRoomCost | `Float` | Central Room Cost |
| 103 | cRoomTax | `Float` | Central Room Tax |
| 104 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 105 | cUpsellCharge | `Float` | Central Upsell Charge |
| 106 | cCJRNUpdateDate | `Date` | CC JRN Update Date |
| 107 | cCJRNUpdateDateAndTime | `DateTime` | CC JRN Update Date and Time |
| 108 | cCRNAInsertDate | `DateTime` | CC RNA Insertdate |
| 109 | cCRNAUpdateDate | `DateTime` | CC RNA Updatedate |
| 110 | cancelDate | `Date` | Cancel Date |
| 111 | cancelReason | `String` | Cancel Reason |
| 112 | cancelTime | `String` | Cancel Time |
| 113 | cancellationDate | `DateTime` | Cancellation Date |
| 114 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 115 | cancellationNumber | `String` | Cancellation Number |
| 116 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 117 | cancellationreasonid | `String` | Cancellationreasonid |
| 118 | cancelledBy | `String` | The user who canceled this Reservation. |
| 119 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 120 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 121 | centralAccountsReceivablesOffset | `Float` | Central Accounts Receivables Offset |
| 122 | centralAmount | `Float` | Central Amount |
| 123 | centralApprovalAmount | `Float` | Central Approval Amount |
| 124 | centralCancelReason | `String` | Central Cancel Reason |
| 125 | centralCommissionCode | `String` | Central Commission Code |
| 126 | centralCommissionDescription | `String` | Central Commission Description |
| 127 | centralCreditLimit | `Float` | Central Credit Limit |
| 128 | centralDiscountReason | `String` | Central Discount Reason |
| 129 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 130 | centralFBRevenue | `Float` | Central FB Revenue |
| 131 | centralGuestType | `String` | Central Guest Type |
| 132 | centralHurdle | `Float` | Central Hurdle |
| 133 | centralPackageCode | `String` | Central Package Code |
| 134 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 135 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 136 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 137 | centralPaymentAmount | `Float` | Central Payment Amount |
| 138 | centralPrepaid | `Float` | Central Prepaid |
| 139 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 140 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 141 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 142 | centralPromotionDescription | `String` | Central Promotion Description |
| 143 | centralRateableValue | `Float` | Central Rateable Value |
| 144 | centralReservationType | `String` | Central Reservation Type |
| 145 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 146 | centralRoomRevenue | `Float` | Central Room Revenue |
| 147 | centralRoomTypeCode | `String` | Central Room Type Code |
| 148 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 149 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 150 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 151 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 152 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 153 | centralTACommissionCode | `String` | Central Commission Code |
| 154 | centralTACommissionDescription | `String` | Central Commission Description |
| 155 | centralTax | `Float` | Central Tax |
| 156 | centralTaxType | `String` | Central Tax Type |
| 157 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 158 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 159 | centralTotalRevenue | `Float` | Central Total Revenue |
| 160 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 161 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 162 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 163 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 164 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 165 | channelDescription | `String` | Channel Description |
| 166 | channelOrderBy | `Float` | Channel Order By |
| 167 | channelid | `String` | Channelid |
| 168 | checkInInitiatedBy | `String` | Check In Initiated By |
| 169 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 170 | childBucket1 | `Float` | Child Bucket 1 |
| 171 | childBucket4 | `Float` | Child Bucket 4 |
| 172 | childBucket5 | `Float` | Child Bucket 5 |
| 173 | children | `Float` | Children |
| 174 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 175 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 176 | childrenAges | `String` | Children Ages |
| 177 | commStatus | `String` | Commission status. |
| 178 | commType | `String` | Commission Type |
| 179 | commissionCode | `String` | Commission Code |
| 180 | commissionCodeDifferenceYN | `String` | Whether reservation has different rates codes of different commission codes. |
| 181 | commissionDescription | `String` | Commission Description |
| 182 | commissionHoldCode | `String` | Commission Hold Code |
| 183 | commissionHoldDesc | `String` | Hold Code Description. |
| 184 | commissionPaid | `Float` | Commission Paid |
| 185 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 186 | commissionableRevenue | `Float` | Amount for which TA/Source receives commission. |
| 187 | commissionableYN | `String` | Commissionable YN |
| 188 | commissionid | `String` | Commissionid |
| 189 | compHouse | `String` | Comp House |
| 190 | compTypeCode | `String` | Comp Type Code |
| 191 | companyCity | `String` | Company City |
| 192 | companyCountry | `String` | Company Country |
| 193 | companyID | `Float` | Company ID |
| 194 | companyName | `String` | Company Name |
| 195 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 196 | companyProfileID | `Float` | Company Profile ID |
| 197 | complimentaryYN | `String` | Complimentary YN |
| 198 | compreasonid | `String` | Compreasonid |
| 199 | computedCommissionsBeginDate | `Date` | Begin Date |
| 200 | computedCommissionsBusinessDateCreated | `Date` | Business Date Created |
| 201 | computedCommissionsCExchangeDate | `Date` | Central Xchange Date |
| 202 | computedCommissionsCExchangeRate | `Float` | Central Xchange Rate |
| 203 | computedCommissionsCommissionId | `Float` | Primary Key. |
| 204 | computedCommissionsDSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 205 | computedCommissionsDeletedFlag | `String` | Deleted Flag |
| 206 | computedCommissionsEndDate | `Date` | End Date |
| 207 | computedCommissionsExchangeRate | `Float` | Exchange Rate |
| 208 | computedCommissionsHoldReasonCode | `String` | Hold Reason Code |
| 209 | computedCommissionsInsertDate | `DateTime` | Insert Date |
| 210 | computedCommissionsInsertUser | `Float` | Insert User |
| 211 | computedCommissionsOrganizationID | `Float` | Internal ID to uniquely identify the Organization |
| 212 | computedCommissionsPrimaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 213 | computedCommissionsProperty | `String` | Code to uniquely identify the Property |
| 214 | computedCommissionsReservationNameId | `Float` | Resv Name ID |
| 215 | computedCommissionsTravelAgentId | `Float` | Travel Agent ID |
| 216 | computedCommissionsUpdateDate | `DateTime` | Update Date |
| 217 | computedCommissionsUpdateUser | `Float` | Update User |
| 218 | computedResvStatus | `String` | Calculated reservation status. |
| 219 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 220 | consumerYn | `String` | Consumer Y/N |
| 221 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 222 | contactProfileID | `Float` | Contact Profile ID |
| 223 | contactProfileName | `String` | Contact Profile Name |
| 224 | createdBy | `String` | The name of the user who created the record. |
| 225 | createdByDefaultResort | `String` | Created By Default Property |
| 226 | createdDate | `Date` | Created Date |
| 227 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 228 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 229 | creditCardId | `Float` | Credit Card ID |
| 230 | creditLimit | `Float` | Credit Limit |
| 231 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 232 | cribs | `Float` | Cribs |
| 233 | currencyCode | `String` | Currency Code |
| 234 | customReferenceNumber | `String` | Custom Reference Number |
| 235 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 236 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 237 | decimalPositions | `Float` | Decimal Positions |
| 238 | deletedFlag | `String` | Deleted Flag |
| 239 | departtransportid | `String` | Departtransportid |
| 240 | departure | `Date` | Departure |
| 241 | departureComments | `String` | Departure Comments |
| 242 | departureDate | `Date` | Departure Date |
| 243 | departureDateTime | `DateTime` | Departure Date Time |
| 244 | departureTime | `String` | Departure Time |
| 245 | departureTransportCode | `String` | Departure Transport Code |
| 246 | departureTransportationYN | `String` | Departure Transportation YN |
| 247 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 248 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 249 | directbillauthby | `Float` | Directbillauthby |
| 250 | discountAmount | `Float` | Discount Amount |
| 251 | discountAmt | `Float` | Discount Amount |
| 252 | discountPercent | `Float` | Discount Percentage. |
| 253 | discountPrcnt | `Float` | Discount Prcnt |
| 254 | discountReason | `String` | Discount Reason |
| 255 | discountReasonDescription | `String` | Discount Reason Description |
| 256 | discountreasonid | `String` | Discountreasonid |
| 257 | displayColor | `String` | Display Color |
| 258 | dmlSeqNumber | `Float` | Dml Sequence No |
| 259 | doNotMoveRoom | `String` | Do Not Move Room |
| 260 | doNotMoveYN | `String` | Do not move room flag. |
| 261 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 262 | dropOffDate | `Date` | Drop Off Date |
| 263 | dropOffStation | `String` | Drop Off Station |
| 264 | dropOffTime | `String` | Drop Off Time |
| 265 | dropOffType | `String` | Drop Off Type |
| 266 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 267 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 268 | effectiveRateAmount | `Float` | Not used. |
| 269 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 270 | emailAddress | `String` | Email Address |
| 271 | emailFolioYn | `String` | Email Folio Y/N |
| 272 | emailId | `Float` | Email ID |
| 273 | emailYn | `String` | Email Y/N |
| 274 | endCity | `String` | End City |
| 275 | endDatetime | `DateTime` | End Datetime |
| 276 | endDistrict | `String` | End District |
| 277 | endState | `String` | End State |
| 278 | endbusinessdate | `Date` | Endbusinessdate |
| 279 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 280 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 281 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 282 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 283 | eventId | `Float` | Event ID |
| 284 | exchangePostingType | `String` | Exchange Posting Type |
| 285 | exchangeRate | `Float` | Exchange Rate |
| 286 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 287 | expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 288 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 289 | extSegNo | `Float` | Not used |
| 290 | extSeqNumber | `Float` | Not used |
| 291 | extensionId | `Float` | Internal extension number for the main reservation |
| 292 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 293 | externalReference | `String` | External Reference |
| 294 | externalReferencesList | `String` | External References List |
| 295 | extraBeds | `Float` | Extra Beds |
| 296 | fBRevenue | `Float` | FB Revenue |
| 297 | faxId | `Float` | Fax ID |
| 298 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 299 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 300 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 301 | fixedCharge | `Float` | Not used. |
| 302 | fixedRateYN | `String` | Fixed Rate YN |
| 303 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 304 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 305 | folioNumber | `String` | Folio Number |
| 306 | folioText1 | `String` | Folio Text1 |
| 307 | folioText2 | `String` | Folio Text2 |
| 308 | foreignCurrencyID | `String` | Foreign Currency ID |
| 309 | freeChild | `Float` | Free Child |
| 310 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 311 | grossRateFuture | `Float` | Gross Rate Future |
| 312 | grossRatePast | `Float` | Gross Rate Past |
| 313 | groupName | `String` | Group Name |
| 314 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 315 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 316 | groupProfileClientID | `String` | Group Profile Client ID |
| 317 | groupProfileID | `Float` | Group Profile ID |
| 318 | groupProfileName | `String` | Group Profile Name |
| 319 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 320 | guaranteecodeid | `String` | Guaranteecodeid |
| 321 | guestFirstName | `String` | Guest First Name |
| 322 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 323 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 324 | guestSignature | `String` | Signature of the guest |
| 325 | guestStatus | `String` | Used for Police/Tourist Export |
| 326 | guestType | `String` | Guest Type |
| 327 | guestprofileid | `Float` | Guestprofileid |
| 328 | gueststatusid | `String` | Gueststatusid |
| 329 | guesttypeid | `String` | Guesttypeid |
| 330 | holdAmount | `Float` | Hold Amount |
| 331 | holdReasonCodeDescription | `String` | Hold Reason Code Description |
| 332 | holdReasonDescription | `String` | Hold Reason Description |
| 333 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 334 | hurdle | `Float` | Hurdle |
| 335 | hurdleOverride | `String` | Hurdle Override |
| 336 | iDByMembershipClass | `String` | ID by Membership Class |
| 337 | iDByMembershipType | `String` | ID by Membership Type |
| 338 | individualCity | `String` | Guest Address. |
| 339 | individualCountry | `String` | Country of the guest |
| 340 | individualFirstName | `String` | Individual First Name |
| 341 | individualLastName | `String` | Individual Last Name |
| 342 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 343 | insertDate | `DateTime` | Insert Date |
| 344 | insertDateTime | `DateTime` | Insert DateTime |
| 345 | insertUser | `Float` | Insert User |
| 346 | intermediaryYn | `String` | Intermediary Y/N |
| 347 | internalAwardMembershipId | `Float` | Award Membership ID |
| 348 | internalBaseratecode | `String` | Baseratecode |
| 349 | internalBlockId | `Float` | Block ID. |
| 350 | internalCompanyprofileid | `Float` | Companyprofileid |
| 351 | internalGroupprofileid | `Float` | Groupprofileid |
| 352 | internalSourceprofileid | `Float` | Sourceprofileid |
| 353 | itemsQuantities | `String` | Items and Quantities |
| 354 | jRNUpdateDate | `Date` | JRN Update Date |
| 355 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 356 | keyValidUntil | `Date` | Key Valid Until |
| 357 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 358 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 359 | lastRoomNumber | `String` | Not used. |
| 360 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 361 | leadTimeDays | `Float` | Lead Time for ordering |
| 362 | lengthOfStay | `Float` | Length of Stay |
| 363 | linkedArrivalDate | `DateTime` | Linked Arrival Date |
| 364 | linkedDepartureDate | `DateTime` | Linked Departure Date |
| 365 | linkedRoomType | `String` | Linked Room Type |
| 366 | listOfMembershipID | `String` | Membership ID |
| 367 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 368 | locationID | `String` | Internal ID to uniquely identify the Property |
| 369 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 370 | mailYn | `String` | Mail Y/N |
| 371 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 372 | manualEditYn | `String` | Stores the manually entered amount. |
| 373 | manualReservationYN | `String` | Indicates if the reservation was added from the Commissions menu and attached to the travel agent or source. |
| 374 | marketCode | `String` | Market Code |
| 375 | marketid | `String` | Marketid |
| 376 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 377 | mcGenBeginState | `String` | Mc Gen Begin State |
| 378 | mcGenEndDistrict | `String` | Mc Gen End District |
| 379 | mcGenEndState | `String` | Mc Gen End State |
| 380 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 381 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 382 | memberDescription | `String` | Member Description |
| 383 | memberLevel | `String` | Member Level |
| 384 | memberNumber | `String` | Member Number |
| 385 | membershipClass | `String` | Membership Class |
| 386 | membershipClassDescription | `String` | Membership Class Description |
| 387 | membershipCode | `String` | Membership Code |
| 388 | membershipId | `Float` | Membership ID |
| 389 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 390 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 391 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 392 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 393 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 394 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 395 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 396 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 397 | name | `String` | Name |
| 398 | nameUsageType | `String` | Name Usage Type |
| 399 | nextCountry | `String` | Next Country |
| 400 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 401 | numberOfRooms | `Float` | No of Rooms |
| 402 | onHoldYN | `String` | On Hold YN |
| 403 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 404 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 405 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 406 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 407 | originCode | `String` | Origin Code |
| 408 | originOfBooking | `String` | Origin Of Booking |
| 409 | originalBaseRate | `Float` | Not used. |
| 410 | originalEndDate | `Date` | Original End Date |
| 411 | originalStartDate | `Date` | Original Start Date |
| 412 | ownerCommissionProcessedYN | `String` | Indicates if commission for owner has been processed. |
| 413 | ownerFfFlag | `String` | Owner Ff Flag |
| 414 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 415 | packageCode | `String` | Package Code |
| 416 | packageCodeDescription | `String` | Package Code Description |
| 417 | packageForecastGroup | `String` | Package Forecast Group |
| 418 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 419 | paidInArAmount | `Float` | Paid In AR Amount |
| 420 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 421 | parentreservationid | `Float` | Parentreservationid |
| 422 | partAllotment | `String` | Part Allotment |
| 423 | partyCode | `String` | Party Code |
| 424 | paxNo | `Float` | Pax Number |
| 425 | payeeType | `String` | Payee Type Code. |
| 426 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 427 | paymentId | `Float` | Payment ID |
| 428 | paymentMethod | `String` | Payment Method |
| 429 | paymentmethodid | `String` | Paymentmethodid |
| 430 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 431 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 432 | phoneId | `Float` | Phone ID |
| 433 | physicalQuantity | `Float` | Physical Quantity |
| 434 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 435 | pickUpDate | `Date` | Pick Up Date |
| 436 | pickUpStation | `String` | Pick Up Station |
| 437 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 438 | pickUpType | `String` | Pick Up Type |
| 439 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 440 | pickUpTime | `String` | Pick-Up Time |
| 441 | pickupRequiredYN | `String` | Pickup Required YN |
| 442 | points | `Float` | Points |
| 443 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 444 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 445 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 446 | postingAllowedYN | `String` | Posting Allowed YN |
| 447 | potentialAmount | `Float` | Potential Amount |
| 448 | ppdEditYn | `String` | Prepaid commission was edited Y/N. |
| 449 | ppdRemarks | `String` | Remarks for the prepaid commission. |
| 450 | preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 451 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 452 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 453 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 454 | preference | `String` | Preference |
| 455 | preferenceType | `String` | Preference Type |
| 456 | preferredRoomType | `String` | Preferred Room Type |
| 457 | prepaid | `Float` | Amount paid to TA/Source. |
| 458 | prepaidYN | `String` | Prepaid YN |
| 459 | previousCountry | `String` | Previous Country |
| 460 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 461 | primaryShare | `String` | Primary Share |
| 462 | printRateYN | `String` | Print Rate YN |
| 463 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 464 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 465 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 466 | promotionCode | `String` | Promotion Code |
| 467 | promotionDescription | `String` | Promotion Description |
| 468 | property | `String` | Indicates if the value set for the specific property. |
| 469 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 470 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 471 | purgeDate | `DateTime` | Purge Date |
| 472 | purposeOfStay | `String` | Purpose of stay. |
| 473 | quantity | `Float` | Number of Rooms |
| 474 | queuePriority | `Float` | Queue priority of the reservation. |
| 475 | queueWaitTime | `Float` | Queue Wait Time |
| 476 | quoteId | `String` | Quote ID provided by external system. |
| 477 | rateAmount | `Float` | Rate Amount |
| 478 | rateCode | `String` | Rate Code |
| 479 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 480 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 481 | rateableValue | `Float` | Stay rateable value. |
| 482 | ratecodeid | `String` | Ratecodeid |
| 483 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 484 | rdResvStatus | `String` | Rd Reservation Status |
| 485 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 486 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 487 | rdenReservationDate | `Date` | Rden Reservation Date |
| 488 | rdenResort | `String` | Rden Property |
| 489 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 490 | registrationCardNo | `String` | Registration Card Number |
| 491 | registrationNumber | `Float` | Registration Number |
| 492 | reinstateDate | `DateTime` | Reinstate Date |
| 493 | repChannel | `String` | Reporting Channel |
| 494 | repChannelDescription | `String` | Reporting Channel Description |
| 495 | reportId | `String` | Report ID |
| 496 | resInsertSource | `String` | Reservation Insert Source |
| 497 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 498 | reservationContactId | `Float` | Resv Contact ID |
| 499 | reservationDate | `DateTime` | Reservation Date |
| 500 | reservationNameID | `Float` | Reservation Name ID |
| 501 | reservationStatus | `String` | Reservation Status |
| 502 | reservationType | `String` | Reservation Type |
| 503 | reservationTypeDescription | `String` | Reservation Type Description |
| 504 | reservationid | `Float` | Reservationid |
| 505 | resort | `String` | Property |
| 506 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 507 | restrictionOverride | `String` | Restriction Override |
| 508 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 509 | resvNameid | `Float` | Reservation Nameid |
| 510 | resvNumber | `Float` | Not used in PMS currently. |
| 511 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 512 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 513 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 514 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 515 | rhRoomFeatures | `String` | Rh Room Features |
| 516 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 517 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 518 | room | `String` | Room |
| 519 | roomCategory | `String` | Room Category |
| 520 | roomClass | `String` | Room Class |
| 521 | roomCost | `Float` | Room Cost |
| 522 | roomInstructions | `String` | Room Instructions |
| 523 | roomResort | `String` | Meeting Room Property |
| 524 | roomRevenue | `Float` | Room Revenue |
| 525 | roomServiceTime | `String` | This is the Turndown room service time. |
| 526 | roomTypeDescription | `String` | Room Type Description |
| 527 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 528 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 529 | roomcategoryid | `String` | Roomcategoryid |
| 530 | roomid | `String` | Roomid |
| 531 | routingYN | `String` | Routing YN |
| 532 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 533 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 534 | sguestName | `String` | Sguest Name |
| 535 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 536 | shareId | `Float` | Share ID. |
| 537 | shareName | `String` | Share Name |
| 538 | sharePrcnt | `Float` | Not used. |
| 539 | shareSeqNumber | `Float` | Type of revenue |
| 540 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 541 | sharedConfirmationNo | `String` | Shared Confirmation Number |
| 542 | sharedGuestName | `String` | Shared Guest Name |
| 543 | sharedProfileID | `Float` | Shared Profile ID |
| 544 | sharedReservationStatus | `String` | Shared Reservation Status |
| 545 | sharingYN | `String` | Sharing YN |
| 546 | sourceCity | `String` | Source City |
| 547 | sourceCode | `String` | Source Code |
| 548 | sourceCountry | `String` | Source Country |
| 549 | sourceName | `String` | Source Name |
| 550 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 551 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 552 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 553 | sourceProfileID | `Float` | Source Profile ID |
| 554 | sourceProfileName | `String` | Source Profile Name |
| 555 | sourceid | `String` | Sourceid |
| 556 | specialRequest | `String` | Special Request |
| 557 | specialRequestDescription | `String` | Special Request Description |
| 558 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 559 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 560 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 561 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 562 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 563 | splitfromreservationid | `Float` | Splitfromreservationid |
| 564 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 565 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 566 | stayRecordId | `Float` | Stay Record ID |
| 567 | suiteNumber | `String` | Suite Number |
| 568 | superSearchIndexText | `String` | Super Search Index Text |
| 569 | tACommissionCode | `String` | Commission Code for TA/Source. |
| 570 | tACommissionDescription | `String` | Commission Description |
| 571 | taRecordLocator | `String` | Ta Record Locator |
| 572 | tax | `Float` | Tax Amount for Commission. |
| 573 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 574 | taxFileDate | `Date` | Date when this record has been extracted for 1099 report. |
| 575 | taxFileStatus | `String` | Record status for 1099 report ( [N]-not sent [Y]-sent [M]-modified ) |
| 576 | taxNumberOfStays | `Float` | Tax No of Stays |
| 577 | taxType | `String` | Tax Type |
| 578 | taxTypeDescription | `String` | Tax Type Description |
| 579 | taxtypeid | `String` | Taxtypeid |
| 580 | tiad | `String` | Tiad |
| 581 | ticketNos | `String` | Ticket Nos |
| 582 | toBePaidAmount | `Float` | To Be Paid Amount |
| 583 | totalCostOfStay | `Float` | Total Cost of Stay |
| 584 | totalRevenue | `Float` | Total Revenue |
| 585 | totalRoomRate | `Float` | Total Room Rate |
| 586 | trackItGroups | `String` | Track It Groups |
| 587 | trackItTypes | `String` | Track It Types |
| 588 | transactionid | `Float` | Transactionid |
| 589 | travelAgentCity | `String` | Travel Agent Address. |
| 590 | travelAgentCountry | `String` | Travel Agent Country |
| 591 | travelAgentID | `Float` | Travel Agent ID |
| 592 | travelAgentName | `String` | Travel Agent Name |
| 593 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 594 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 595 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 596 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 597 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 598 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 599 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 600 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 601 | uDFC01 | `String` | UDFC01 |
| 602 | uDFC02 | `String` | UDFC02 |
| 603 | uDFC03 | `String` | UDFC03 |
| 604 | uDFC04 | `String` | UDFC04 |
| 605 | uDFC05 | `String` | UDFC05 |
| 606 | uDFC06 | `String` | UDFC06 |
| 607 | uDFC07 | `String` | UDFC07 |
| 608 | uDFC08 | `String` | UDFC08 |
| 609 | uDFC09 | `String` | UDFC09 |
| 610 | uDFC10 | `String` | UDFC10 |
| 611 | uDFC11 | `String` | UDFC11 |
| 612 | uDFC12 | `String` | UDFC12 |
| 613 | uDFC13 | `String` | UDFC13 |
| 614 | uDFC14 | `String` | UDFC14 |
| 615 | uDFC15 | `String` | UDFC15 |
| 616 | uDFC16 | `String` | UDFC16 |
| 617 | uDFC17 | `String` | UDFC17 |
| 618 | uDFC18 | `String` | UDFC18 |
| 619 | uDFC19 | `String` | UDFC19 |
| 620 | uDFC20 | `String` | UDFC20 |
| 621 | uDFC21 | `String` | UDFC21 |
| 622 | uDFC22 | `String` | UDFC22 |
| 623 | uDFC23 | `String` | UDFC23 |
| 624 | uDFC24 | `String` | UDFC24 |
| 625 | uDFC25 | `String` | UDFC25 |
| 626 | uDFC26 | `String` | UDFC26 |
| 627 | uDFC27 | `String` | UDFC27 |
| 628 | uDFC28 | `String` | UDFC28 |
| 629 | uDFC29 | `String` | UDFC29 |
| 630 | uDFC30 | `String` | UDFC30 |
| 631 | uDFC31 | `String` | UDFC31 |
| 632 | uDFC32 | `String` | UDFC32 |
| 633 | uDFC33 | `String` | UDFC33 |
| 634 | uDFC34 | `String` | UDFC34 |
| 635 | uDFC35 | `String` | UDFC35 |
| 636 | uDFC36 | `String` | UDFC36 |
| 637 | uDFC37 | `String` | UDFC37 |
| 638 | uDFC38 | `String` | UDFC38 |
| 639 | uDFC39 | `String` | UDFC39 |
| 640 | uDFC40 | `String` | UDFC40 |
| 641 | uDFD01 | `Date` | UDFD01 |
| 642 | uDFD02 | `Date` | UDFD02 |
| 643 | uDFD03 | `Date` | UDFD03 |
| 644 | uDFD04 | `Date` | UDFD04 |
| 645 | uDFD05 | `Date` | UDFD05 |
| 646 | uDFD06 | `Date` | UDFD06 |
| 647 | uDFD07 | `Date` | UDFD07 |
| 648 | uDFD08 | `Date` | UDFD08 |
| 649 | uDFD09 | `Date` | UDFD09 |
| 650 | uDFD10 | `Date` | UDFD10 |
| 651 | uDFD11 | `Date` | UDFD11 |
| 652 | uDFD12 | `Date` | UDFD12 |
| 653 | uDFD13 | `Date` | UDFD13 |
| 654 | uDFD14 | `Date` | UDFD14 |
| 655 | uDFD15 | `Date` | UDFD15 |
| 656 | uDFD16 | `Date` | UDFD16 |
| 657 | uDFD17 | `Date` | UDFD17 |
| 658 | uDFD18 | `Date` | UDFD18 |
| 659 | uDFD19 | `Date` | UDFD19 |
| 660 | uDFD20 | `Date` | UDFD20 |
| 661 | uDFN01 | `Float` | UDFN01 |
| 662 | uDFN02 | `Float` | UDFN02 |
| 663 | uDFN03 | `Float` | UDFN03 |
| 664 | uDFN04 | `Float` | UDFN04 |
| 665 | uDFN05 | `Float` | UDFN05 |
| 666 | uDFN06 | `Float` | UDFN06 |
| 667 | uDFN07 | `Float` | UDFN07 |
| 668 | uDFN08 | `Float` | UDFN08 |
| 669 | uDFN09 | `Float` | UDFN09 |
| 670 | uDFN10 | `Float` | UDFN10 |
| 671 | uDFN11 | `Float` | UDFN11 |
| 672 | uDFN12 | `Float` | UDFN12 |
| 673 | uDFN13 | `Float` | UDFN13 |
| 674 | uDFN14 | `Float` | UDFN14 |
| 675 | uDFN15 | `Float` | UDFN15 |
| 676 | uDFN16 | `Float` | UDFN16 |
| 677 | uDFN17 | `Float` | UDFN17 |
| 678 | uDFN18 | `Float` | UDFN18 |
| 679 | uDFN19 | `Float` | UDFN19 |
| 680 | uDFN20 | `Float` | UDFN20 |
| 681 | uDFN21 | `Float` | UDFN21 |
| 682 | uDFN22 | `Float` | UDFN22 |
| 683 | uDFN23 | `Float` | UDFN23 |
| 684 | uDFN24 | `Float` | UDFN24 |
| 685 | uDFN25 | `Float` | UDFN25 |
| 686 | uDFN26 | `Float` | UDFN26 |
| 687 | uDFN27 | `Float` | UDFN27 |
| 688 | uDFN28 | `Float` | UDFN28 |
| 689 | uDFN29 | `Float` | UDFN29 |
| 690 | uDFN30 | `Float` | UDFN30 |
| 691 | uDFN31 | `Float` | UDFN31 |
| 692 | uDFN32 | `Float` | UDFN32 |
| 693 | uDFN33 | `Float` | UDFN33 |
| 694 | uDFN34 | `Float` | UDFN34 |
| 695 | uDFN35 | `Float` | UDFN35 |
| 696 | uDFN36 | `Float` | UDFN36 |
| 697 | uDFN37 | `Float` | UDFN37 |
| 698 | uDFN38 | `Float` | UDFN38 |
| 699 | uDFN39 | `Float` | UDFN39 |
| 700 | uDFN40 | `Float` | UDFN40 |
| 701 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 702 | updateDate | `DateTime` | Update Date |
| 703 | updateDatetime | `DateTime` | Update Datetime |
| 704 | updateUser | `Float` | Update User |
| 705 | updatedBy | `String` | Updated By |
| 706 | updatedByDefaultResort | `String` | Updated By Default Property |
| 707 | updatedDate | `Date` | Updated Date |
| 708 | updatedTime | `String` | Updated Time |
| 709 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 710 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 711 | visaExpiryDate | `Date` | Visa Expiry Date |
| 712 | visaIssueDate | `Date` | Visa Issue Date |
| 713 | visaNumber | `String` | Visa Number |
| 714 | waitlistComment | `String` | Waitlist Comment |
| 715 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 716 | waitlistPriority | `String` | Waitlist Priority |
| 717 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 718 | waitlistReason | `String` | Waitlist Reason |
| 719 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 720 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 721 | waitlistreasonid | `String` | Waitlistreasonid |
| 722 | walkInYN | `String` | Walk-In YN |
| 723 | yieldableYn | `String` | Yieldable Y/N |
| 724 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialCommissionsCheckRegisterDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountId | `Float` | Account ID |
| 2 | batchNumber | `Float` | Batch Number |
| 3 | cExchangeDate | `Date` | Central Xchange Date |
| 4 | cExchangeRate | `Float` | Central Xchange Rate |
| 5 | cFCTotalCheckAmount | `Float` | Central Fc Total Check Amt |
| 6 | cTotalCheckAmount | `Float` | Central Total Check Amt |
| 7 | cVatAmount | `Float` | Central Vat Amt |
| 8 | centralCheckAmount | `Float` | Central Check Amount |
| 9 | checkAmount | `Float` | Indicates Check Amount as Commission |
| 10 | checkCurrency | `String` | Indicates Check issued in which Currency |
| 11 | checkDate | `Date` | Check Date |
| 12 | checkNumber | `Float` | Indicates Check No |
| 13 | checkStatus | `String` | Check Status |
| 14 | clearedYn | `String` | Check Cleared   Y/N |
| 15 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | eftFileName | `String` | Name of the EFT file path |
| 18 | exchangeRate | `Float` | Exchange Rate |
| 19 | fCTotalCheckAmt | `Float` | Indiacates commission + Tax amounts  in Foreign Currency |
| 20 | failedYn | `String` | Indicate if this check has been voided/discarded. |
| 21 | insertDate | `DateTime` | Insert Date |
| 22 | insertUser | `Float` | Insert User |
| 23 | jRNUpdateDate | `Date` | JRN Update Date |
| 24 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 25 | micrNo | `Float` | Check number |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | payee | `String` | Payee |
| 28 | positivePayDate | `Date` | Date when current record has been exported for Positive Pay Check. |
| 29 | positivePayStatus | `String` | Indicate status of record for Positive Pay Export. |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Code to uniquely identify the Property |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | status | `String` | Status |
| 35 | statusDate | `DateTime` | Status Date |
| 36 | taPaymentId | `Float` | Payment Id |
| 37 | totalCheckAmt | `Float` | Total Check Amount is commission + Tax amounts |
| 38 | travelAgentId | `Float` | Travel Agent ID |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |
| 41 | vatAmt | `Float` | Tax Amount on Commission |
| 42 | vatPercnt | `Float` | Percentage of Tax on Commission |

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

### FinancialCommissionsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| commissionagentDetailsActiveYn | `StringInput` | Active Flag |
| commissionagentDetailsChainCode | `StringInput!` | Chain Code<br>`@mandatoryInput` |
| commissionagentDetailsCompany | `StringInput` | Company |
| commissionagentDetailsNameCode | `StringInput` | Corp ID |
| commissionagentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| commissionagentDetailsHistoryYn | `StringInput` | History Y/N |
| commissionagentDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| commissionagentDetailsOrganizationId | `FloatInput` | Organization ID |
| commissionagentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| commissionagentDetailsLast | `StringInput` | Last |
| commissionagentDetailsNameId | `FloatInput` | Name ID |
| commissionagentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| commissionagentDetailsProfileType | `StringInput` | Profile Type |
| commissionagentDetailsNameType | `StringInput` | Profile Type Code |
| commissionagentDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| commissionagentDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| commissionagentDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| commissionagentDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| commissionagentDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| commissionagentDetailsProfileId | `FloatInput` | Top Account ID |
| commissionagentDetailsUpdateDate | `DateTimeInput` | Update Date |
| profilecommbankaccountDetailsAccountId | `FloatInput` | Account ID |
| profilecommbankaccountDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| profilecommbankaccountDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilecommbankaccountDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilecommbankaccountDetailsNameId | `FloatInput` | Name ID |
| profilecommbankaccountDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilecommbankaccountDetailsPcAccountId | `FloatInput` | Account ID |
| profilecommbankaccountDetailsPcDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilecommbankaccountDetailsPcOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilecommbankaccountDetailsPcResort | `StringInput` | Code to uniquely identify the Property |
| profilecommbankaccountDetailsResort | `StringInput` | Property |
| computedcommresvDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |
| computedcommresvDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |
| computedcommresvDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| computedcommresvDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| computedcommresvDetailsTruncBeginDate | `DateInput` | Arrival Date |
| computedcommresvDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| computedcommresvDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| computedcommresvDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| computedcommresvDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| computedcommresvDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| computedcommresvDetailsCcjrnupdatedttm | `DateTimeInput` | CC JRN Update Date and Time |
| computedcommresvDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| computedcommresvDetailsCancellationNo | `StringInput` | Cancellation Number |
| computedcommresvDetailsCreditCardId | `FloatInput` | Credit Card ID |
| computedcommresvDetailsCustomReference | `StringInput` | Custom Reference Number |
| computedcommresvDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| computedcommresvDetailsTruncEndDate | `DateInput` | Departure Date |
| computedcommresvDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| computedcommresvDetailsEventId | `FloatInput` | Event ID |
| computedcommresvDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| computedcommresvDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| computedcommresvDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| computedcommresvDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| computedcommresvDetailsInsertDate | `DateTimeInput` | Insert Date |
| computedcommresvDetailsInsertUser | `FloatInput` | Insert User |
| computedcommresvDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| computedcommresvDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| computedcommresvDetailsEndDate | `DateTimeInput` | Linked Departure Date |
| computedcommresvDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| computedcommresvDetailsNameUsageType | `StringInput` | Name Usage Type |
| computedcommresvDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| computedcommresvDetailsOriginalEndDate | `DateInput` | Original End Date |
| computedcommresvDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| computedcommresvDetailsParentreservationid | `FloatInput` | Parentreservationid |
| computedcommresvDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| computedcommresvDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| computedcommresvDetailsResvContactId | `FloatInput` | Resv Contact ID |
| computedcommresvDetailsResvNameId | `FloatInput` | Reservation Name ID |
| computedcommresvDetailsResvStatus | `StringInput` | Reservation Status |
| computedcommresvDetailsGuaranteeCode | `StringInput` | Reservation Type |
| computedcommresvDetailsReservationid | `FloatInput` | Reservationid |
| computedcommresvDetailsResort | `StringInput` | Property |
| computedcommresvDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| computedcommresvDetailsResvNameid | `FloatInput` | Reservation Nameid |
| computedcommresvDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| computedcommresvDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| computedcommresvDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| computedcommresvDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| computedcommresvDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| computedcommresvDetailsSguestName | `StringInput` | Sguest Name |
| computedcommresvDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| computedcommresvDetailsNameId | `FloatInput` | Shared Profile ID |
| computedcommresvDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| computedcommresvDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| computedcommresvDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| computedcommresvDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| computedcommresvDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| computedcommresvDetailsUpdateDate | `DateTimeInput` | Update Date |
| checkregisterDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
#### Validation Rules

**`mandatoryInput`**
- commissionagentDetailsChainCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query financialCommissions($input: FinancialCommissionsQueryArgumentsType!) {
  financialCommissions(input: $input) @stream {
    commissionAgentDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountName2
      accountName3
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
      addressLanguageCode
      addressType
      allResorts
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
      businessSegementDescription
      businessSegment
      businessTitle
      centralAccountSource
      centralAccountSourceDescription
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
      centralMailAction
      centralMailActionDescription
      centralPriority
      centralPriorityDescription
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
      corpID
      corporateType
      corporateTypeDescription
      country
      countryCode
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
      profileLanguage
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      rNAInsertDate
      rNAUpdateDate
      referenceCurrency
      repAccountType
      repInfluence
      repInfluenceDescription
      repNameType
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitle
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
      scopeCityDescription
      scopeDescription
      sfirst
      sname
      state
      stateDesc
      stateDescription
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
      title
      topAccountID
      topAccountName
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
    profileCommissionBankAccountDetails {
      accountId
      accountNumber
      bankAcctType
      bankCode
      branchCode
      cExchangeDate
      cExchangeRate
      centralCommissionCode
      centralCommissionCodeDescription
      centralMinProcessingAmount
      checkReport
      checkSubLines
      commissionCode
      commissionCodeDescription
      currency
      currencyDescription
      dSI
      defaultYN
      defaultForCurrencyYN
      deletedFlag
      description
      editCheckNumberYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      laptopChange
      lastExportDate
      lastExportedFile
      locationID
      maxCheckNo
      minProcessingAmount
      nameId
      nextCheckNumber
      onHold
      organizationID
      paidInAR
      paymentMethod
      positivePayExportYN
      potential
      primaryKeyID
      profileCommissionAccountId
      profileCommissionCreatedByUser
      profileCommissionCreatedOnDate
      profileCommissionDSI
      profileCommissionDeletedFlag
      profileCommissionJRNUpdateDate
      profileCommissionJRNUpdateDateAndTime
      profileCommissionOrganizationID
      profileCommissionPrimaryKeyID
      profileCommissionProperty
      profileCommissionRnaInsertDate
      profileCommissionRnaUpdateDate
      profileCommissionUpdateDate
      profileCommissionUpdateUser
      property
      rNAInsertDate
      rNAUpdateDate
      routingNumber
      sourceImportDir
      targetImportDir
      tax1099ReportYN
      toBePaid
      updateDate
      updateUser
      validateIATANumberYN
    }
    computedCommissionsReservationDetails {
      aSBProratedYn
      accompaniedYN
      accompanyingName
      accountsReceivablesOffset
      accountsReceivablesYN
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      addressId
      addresseeNameId
      adjustmentNote
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      allotmentRecordType
      allotmentid
      amenityEligibleYn
      amenityLevelCode
      amount
      amountPercent
      approvalAmount
      approvalAmountCalcMethod
      approvalCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalTime
      arrivaltransportid
      authorizedBillingYN
      authorizedBy
      authorizerId
      autoCheckinYn
      autoPopulateRoutingYn
      autoSettleDays
      autoSettleType
      autoSettleYN
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipID
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      backToBackYN
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
      beginDatetime
      beginDistrict
      beginState
      beginSystemDateTime
      billNumber
      billingContact
      billingContactDisplayName
      billingContactId
      billingContactName
      billingcontactprofileid
      blockCode
      blockCreateDate
      blockID
      blockName
      blockResort
      blockStatus
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      businessDatetimeCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cCommissionableRevenue
      cDiscountAmount
      cDiscountAmt
      cEffectiveRateAmount
      cExchangeDate
      cExchangeRate
      cFixedCharge
      cGrossRateAmount
      cLocalBaseRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmountOriginal
      cUpsellCharge
      cCJRNUpdateDate
      cCJRNUpdateDateAndTime
      cCRNAInsertDate
      cCRNAUpdateDate
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationDatetime
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      cancelledBy
      cardNumberByMembershipClass
      cardNumberByMembershipType
      centralAccountsReceivablesOffset
      centralAmount
      centralApprovalAmount
      centralCancelReason
      centralCommissionCode
      centralCommissionDescription
      centralCreditLimit
      centralDiscountReason
      centralDiscountReasonDescription
      centralFBRevenue
      centralGuestType
      centralHurdle
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPaymentAmount
      centralPrepaid
      centralProjectedFBRevenue
      centralProjectedRoomRevenue
      centralProjectedTotalRevenue
      centralPromotionDescription
      centralRateableValue
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralRoomTypeCode
      centralRoomTypeDescription
      centralRoomTypeToChargeCode
      centralRoomTypeToChargeDescription
      centralSharedRoomRate
      centralSpecialRequestDescription
      centralTACommissionCode
      centralTACommissionDescription
      centralTax
      centralTaxType
      centralTaxTypeDescription
      centralTotalCostOfStay
      centralTotalRevenue
      centralTotalRoomRate
      centralWaitlistPriority
      centralWaitlistPriorityDescription
      centralWaitlistReason
      centralWaitlistReasonDescription
      channelDescription
      channelOrderBy
      channelid
      checkInInitiatedBy
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAges
      commStatus
      commType
      commissionCode
      commissionCodeDifferenceYN
      commissionDescription
      commissionHoldCode
      commissionHoldDesc
      commissionPaid
      commissionPayoutTo
      commissionableRevenue
      commissionableYN
      commissionid
      compHouse
      compTypeCode
      companyCity
      companyCountry
      companyID
      companyName
      companyProfileCorporateID
      companyProfileID
      complimentaryYN
      compreasonid
      computedCommissionsBeginDate
      computedCommissionsBusinessDateCreated
      computedCommissionsCExchangeDate
      computedCommissionsCExchangeRate
      computedCommissionsCommissionId
      computedCommissionsDSI
      computedCommissionsDeletedFlag
      computedCommissionsEndDate
      computedCommissionsExchangeRate
      computedCommissionsHoldReasonCode
      computedCommissionsInsertDate
      computedCommissionsInsertUser
      computedCommissionsOrganizationID
      computedCommissionsPrimaryKeyID
      computedCommissionsProperty
      computedCommissionsReservationNameId
      computedCommissionsTravelAgentId
      computedCommissionsUpdateDate
      computedCommissionsUpdateUser
      computedResvStatus
      confirmationLegNumber
      consumerYn
      contactName
      contactProfileID
      contactProfileName
      createdBy
      createdByDefaultResort
      createdDate
      createdTime
      creditCardAuthDate
      creditCardId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      decimalPositions
      deletedFlag
      departtransportid
      departure
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      depositMaturityType
      directBillVerifyResponse
      directbillauthby
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountReasonDescription
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      dropOffType
      dropOffTypeDescription
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endCity
      endDatetime
      endDistrict
      endState
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      excludeFromAutoAuthorizationYN
      expectedTimeOfReturnETR
      exportCheckinresId
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externalReferencesList
      extraBeds
      fBRevenue
      faxId
      faxYn
      feature
      financiallyResponsibleYn
      fixedCharge
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioNumber
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      frequentFlyerMembershipYN
      grossRateFuture
      grossRatePast
      groupName
      groupProfileARNumber
      groupProfileARNumberCentral
      groupProfileClientID
      groupProfileID
      groupProfileName
      guaranteeCodePreCi
      guaranteecodeid
      guestFirstName
      guestFirstNameSdx
      guestLastNameSdx
      guestSignature
      guestStatus
      guestType
      guestprofileid
      gueststatusid
      guesttypeid
      holdAmount
      holdReasonCodeDescription
      holdReasonDescription
      housekeepingServiceTime
      hurdle
      hurdleOverride
      iDByMembershipClass
      iDByMembershipType
      individualCity
      individualCountry
      individualFirstName
      individualLastName
      insertActionInstanceId
      insertDate
      insertDateTime
      insertUser
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      itemsQuantities
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyValidUntil
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoomNumber
      lastSettleDate
      leadTimeDays
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      linkedRoomType
      listOfMembershipID
      localBaseRateAmount
      locationID
      loyaltySchemeMembershipYN
      mailYn
      manualCheckoutStatus
      manualEditYn
      manualReservationYN
      marketCode
      marketid
      mcGenBeginDistrict
      mcGenBeginState
      mcGenEndDistrict
      mcGenEndState
      mcGenNextCountry
      mcGenPreviousCountry
      memberDescription
      memberLevel
      memberNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipId
      membershipLevelByMembershipClass
      membershipTypeByMembershipClass
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextCountry
      nextDestination
      numberOfRooms
      onHoldYN
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCode
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      ownerCommissionProcessedYN
      ownerFfFlag
      ownerOrFriendsFamily
      packageCode
      packageCodeDescription
      packageForecastGroup
      packageForecastGroupDescription
      paidInArAmount
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      paxNo
      payeeType
      paymentAmount
      paymentId
      paymentMethod
      paymentmethodid
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pickUpCarrierCode
      pickUpDate
      pickUpStation
      pickUpTransportNumber
      pickUpType
      pickUpTypeDescription
      pickUpTime
      pickupRequiredYN
      points
      pointsEligibilityCode
      postCoFlag
      postStayChargingYN
      postingAllowedYN
      potentialAmount
      ppdEditYn
      ppdRemarks
      preArrReviewedDt
      preArrReviewedUser
      preChargingYn
      preRegisteredYn
      preference
      preferenceType
      preferredRoomType
      prepaid
      prepaidYN
      previousCountry
      primaryKeyID
      primaryShare
      printRateYN
      projectedFBRevenue
      projectedRoomRevenue
      projectedTotalRevenue
      promotionCode
      promotionDescription
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      queuePriority
      queueWaitTime
      quoteId
      rateAmount
      rateCode
      rateCodeDescriptions
      rateTier
      rateableValue
      ratecodeid
      rdHousekeepingExpectedServiceTime
      rdResvStatus
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      repChannel
      repChannelDescription
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationDate
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reservationid
      resort
      resortChargeNumber
      restrictionOverride
      resvGuid
      resvNameid
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rhRoomFeatures
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomResort
      roomRevenue
      roomServiceTime
      roomTypeDescription
      roomTypeToChargeCode
      roomTypeToChargeDescription
      roomcategoryid
      roomid
      routingYN
      scheduleCheckoutYn
      sguestFirstname
      sguestName
      shareConfirmationNumbers
      shareId
      shareName
      sharePrcnt
      shareSeqNumber
      shareOfRateAmount
      sharedConfirmationNo
      sharedGuestName
      sharedProfileID
      sharedReservationStatus
      sharingYN
      sourceCity
      sourceCode
      sourceCountry
      sourceName
      sourceProfileARNumber
      sourceProfileARNumberCentral
      sourceProfileIATANumber
      sourceProfileID
      sourceProfileName
      sourceid
      specialRequest
      specialRequestDescription
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      suiteNumber
      superSearchIndexText
      tACommissionCode
      tACommissionDescription
      taRecordLocator
      tax
      taxExemptNumber
      taxFileDate
      taxFileStatus
      taxNumberOfStays
      taxType
      taxTypeDescription
      taxtypeid
      tiad
      ticketNos
      toBePaidAmount
      totalCostOfStay
      totalRevenue
      totalRoomRate
      trackItGroups
      trackItTypes
      transactionid
      travelAgentCity
      travelAgentCountry
      travelAgentID
      travelAgentName
      travelAgentProfileARNumber
      travelAgentProfileARNumberCentral
      travelAgentProfileIATANumber
      travelAgentProfileID
      travelAgentProfileName
      truncActualCheckOutDate
      turndownStatus
      turndownYN
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
      uniCardId
      updateDate
      updateDatetime
      updateUser
      updatedBy
      updatedByDefaultResort
      updatedDate
      updatedTime
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      waitlistPriority
      waitlistPriorityDescription
      waitlistReason
      waitlistReasonDescription
      waitlistpriorityid
      waitlistreasonid
      walkInYN
      yieldableYn
      ymCode
    }
    checkRegisterDetails {
      accountId
      batchNumber
      cExchangeDate
      cExchangeRate
      cFCTotalCheckAmount
      cTotalCheckAmount
      cVatAmount
      centralCheckAmount
      checkAmount
      checkCurrency
      checkDate
      checkNumber
      checkStatus
      clearedYn
      dSI
      deletedFlag
      eftFileName
      exchangeRate
      fCTotalCheckAmt
      failedYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      micrNo
      organizationID
      payee
      positivePayDate
      positivePayStatus
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      status
      statusDate
      taPaymentId
      totalCheckAmt
      travelAgentId
      updateDate
      updateUser
      vatAmt
      vatPercnt
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
commission_agent_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
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
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allResorts': pl.Utf8,
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
    'businessSegementDescription': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
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
    'centralMailAction': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
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
    'corpID': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguage': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repAccountType': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitle': pl.Utf8,
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
    'scopeCityDescription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'sfirst': pl.Utf8,
    'sname': pl.Utf8,
    'state': pl.Utf8,
    'stateDesc': pl.Utf8,
    'stateDescription': pl.Utf8,
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
    'title': pl.Utf8,
    'topAccountID': pl.Float64,
    'topAccountName': pl.Utf8,
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
    'updateUser': pl.Int64,
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
profile_commission_bank_account_details_schema = {
    'accountId': pl.Float64,
    'accountNumber': pl.Utf8,
    'bankAcctType': pl.Utf8,
    'bankCode': pl.Utf8,
    'branchCode': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionCodeDescription': pl.Utf8,
    'centralMinProcessingAmount': pl.Float64,
    'checkReport': pl.Utf8,
    'checkSubLines': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionCodeDescription': pl.Utf8,
    'currency': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYN': pl.Utf8,
    'defaultForCurrencyYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'editCheckNumberYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastExportDate': pl.Utf8,
    'lastExportedFile': pl.Float64,
    'locationID': pl.Utf8,
    'maxCheckNo': pl.Float64,
    'minProcessingAmount': pl.Float64,
    'nameId': pl.Float64,
    'nextCheckNumber': pl.Float64,
    'onHold': pl.Float64,
    'organizationID': pl.Int64,
    'paidInAR': pl.Float64,
    'paymentMethod': pl.Utf8,
    'positivePayExportYN': pl.Utf8,
    'potential': pl.Float64,
    'primaryKeyID': pl.Int64,
    'profileCommissionAccountId': pl.Float64,
    'profileCommissionCreatedByUser': pl.Float64,
    'profileCommissionCreatedOnDate': pl.Utf8,
    'profileCommissionDSI': pl.Float64,
    'profileCommissionDeletedFlag': pl.Utf8,
    'profileCommissionJRNUpdateDate': pl.Utf8,
    'profileCommissionJRNUpdateDateAndTime': pl.Utf8,
    'profileCommissionOrganizationID': pl.Float64,
    'profileCommissionPrimaryKeyID': pl.Float64,
    'profileCommissionProperty': pl.Utf8,
    'profileCommissionRnaInsertDate': pl.Utf8,
    'profileCommissionRnaUpdateDate': pl.Utf8,
    'profileCommissionUpdateDate': pl.Utf8,
    'profileCommissionUpdateUser': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'routingNumber': pl.Utf8,
    'sourceImportDir': pl.Utf8,
    'targetImportDir': pl.Utf8,
    'tax1099ReportYN': pl.Utf8,
    'toBePaid': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validateIATANumberYN': pl.Utf8,
}
```
```python
computed_commissions_reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'accountsReceivablesOffset': pl.Float64,
    'accountsReceivablesYN': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adjustmentNote': pl.Utf8,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amount': pl.Float64,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cCommissionableRevenue': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cCJRNUpdateDate': pl.Utf8,
    'cCJRNUpdateDateAndTime': pl.Utf8,
    'cCRNAInsertDate': pl.Utf8,
    'cCRNAUpdateDate': pl.Utf8,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralAccountsReceivablesOffset': pl.Float64,
    'centralAmount': pl.Float64,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralPrepaid': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTACommissionCode': pl.Utf8,
    'centralTACommissionDescription': pl.Utf8,
    'centralTax': pl.Float64,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commStatus': pl.Utf8,
    'commType': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeDifferenceYN': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionHoldDesc': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableRevenue': pl.Float64,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedCommissionsBeginDate': pl.Utf8,
    'computedCommissionsBusinessDateCreated': pl.Utf8,
    'computedCommissionsCExchangeDate': pl.Utf8,
    'computedCommissionsCExchangeRate': pl.Float64,
    'computedCommissionsCommissionId': pl.Float64,
    'computedCommissionsDSI': pl.Float64,
    'computedCommissionsDeletedFlag': pl.Utf8,
    'computedCommissionsEndDate': pl.Utf8,
    'computedCommissionsExchangeRate': pl.Float64,
    'computedCommissionsHoldReasonCode': pl.Utf8,
    'computedCommissionsInsertDate': pl.Utf8,
    'computedCommissionsInsertUser': pl.Float64,
    'computedCommissionsOrganizationID': pl.Float64,
    'computedCommissionsPrimaryKeyID': pl.Float64,
    'computedCommissionsProperty': pl.Utf8,
    'computedCommissionsReservationNameId': pl.Float64,
    'computedCommissionsTravelAgentId': pl.Float64,
    'computedCommissionsUpdateDate': pl.Utf8,
    'computedCommissionsUpdateUser': pl.Float64,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'decimalPositions': pl.Float64,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departure': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'holdAmount': pl.Float64,
    'holdReasonCodeDescription': pl.Utf8,
    'holdReasonDescription': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'manualEditYn': pl.Utf8,
    'manualReservationYN': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'onHoldYN': pl.Utf8,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerCommissionProcessedYN': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'paidInArAmount': pl.Float64,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'payeeType': pl.Utf8,
    'paymentAmount': pl.Float64,
    'paymentId': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'potentialAmount': pl.Float64,
    'ppdEditYn': pl.Utf8,
    'ppdRemarks': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'prepaid': pl.Float64,
    'prepaidYN': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedConfirmationNo': pl.Utf8,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'tACommissionCode': pl.Utf8,
    'tACommissionDescription': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'tax': pl.Float64,
    'taxExemptNumber': pl.Utf8,
    'taxFileDate': pl.Utf8,
    'taxFileStatus': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'toBePaidAmount': pl.Float64,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
check_register_details_schema = {
    'accountId': pl.Float64,
    'batchNumber': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFCTotalCheckAmount': pl.Float64,
    'cTotalCheckAmount': pl.Float64,
    'cVatAmount': pl.Float64,
    'centralCheckAmount': pl.Float64,
    'checkAmount': pl.Float64,
    'checkCurrency': pl.Utf8,
    'checkDate': pl.Utf8,
    'checkNumber': pl.Float64,
    'checkStatus': pl.Utf8,
    'clearedYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'eftFileName': pl.Utf8,
    'exchangeRate': pl.Float64,
    'fCTotalCheckAmt': pl.Float64,
    'failedYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'micrNo': pl.Float64,
    'organizationID': pl.Int64,
    'payee': pl.Utf8,
    'positivePayDate': pl.Utf8,
    'positivePayStatus': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'status': pl.Utf8,
    'statusDate': pl.Utf8,
    'taPaymentId': pl.Float64,
    'totalCheckAmt': pl.Float64,
    'travelAgentId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatAmt': pl.Float64,
    'vatPercnt': pl.Float64,
}
```