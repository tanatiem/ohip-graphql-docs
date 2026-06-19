# ProfilesAccounts
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | profileAccountsDetails | [`ProfilesAccountsProfileAccountsDetailsType`](#profilesaccountsprofileaccountsdetailstype) | Profile Accounts Details |
| 2 | profileForecastDetails | [`ProfilesAccountsProfileForecastDetailsType`](#profilesaccountsprofileforecastdetailstype) | Profile Forecast Details |
| 3 | profileCommunicationDetails | [`ProfilesAccountsProfileCommunicationDetailsType`](#profilesaccountsprofilecommunicationdetailstype) | Profile Communication Details |
| 4 | profileCommissionDetails | [`ProfilesAccountsProfileCommissionDetailsType`](#profilesaccountsprofilecommissiondetailstype) | Profile Commission Details |
| 5 | profileRelationshipDetails | [`ProfilesAccountsProfileRelationshipDetailsType`](#profilesaccountsprofilerelationshipdetailstype) | Profile Relationship Details |
| 6 | accountMonthlyStatisticsDetails | [`ProfilesAccountsAccountMonthlyStatisticsDetailsType`](#profilesaccountsaccountmonthlystatisticsdetailstype) | Account Monthly Statistics |
| 7 | profileAddressDetails | [`ProfilesAccountsProfileAddressDetailsType`](#profilesaccountsprofileaddressdetailstype) | Profile Address Details |
| 8 | accountDailyStatisticsDetails | [`ProfilesAccountsAccountDailyStatisticsDetailsType`](#profilesaccountsaccountdailystatisticsdetailstype) | Account Daily Statistics |
| 9 | profileNoteDetails | [`ProfilesAccountsProfileNoteDetailsType`](#profilesaccountsprofilenotedetailstype) | Profile Note Details |
| 10 | profileRelationshipHierDetails | [`ProfilesAccountsProfileRelationshipHierDetailsType`](#profilesaccountsprofilerelationshiphierdetailstype) | Profile Relationship Hier Details |
| 11 | profilePreferenceDetails | [`ProfilesAccountsProfilePreferenceDetailsType`](#profilesaccountsprofilepreferencedetailstype) | Profile Preference Details |
| 12 | accountYearlyStatisticsDetails | [`ProfilesAccountsAccountYearlyStatisticsDetailsType`](#profilesaccountsaccountyearlystatisticsdetailstype) | Account Yearly Statistics |
| 13 | profileOwnerDetails | [`ProfilesAccountsProfileOwnerDetailsType`](#profilesaccountsprofileownerdetailstype) | Profile Owner Details |
| 14 | reservationDailyStatisticsDetails | [`ProfilesAccountsReservationDailyStatisticsDetailsType`](#profilesaccountsreservationdailystatisticsdetailstype) | Reservation Daily Statistics |
| 15 | saleProfileOwnerDetails | [`ProfilesAccountsSaleProfileOwnerDetailsType`](#profilesaccountssaleprofileownerdetailstype) | Sales Goals Profile Owner Details |
| 16 | blockDetails | [`ProfilesAccountsBlockDetailsType`](#profilesaccountsblockdetailstype) | Block |
| 17 | profilesAccountsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileAccountsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNumber | `String` | AR Number |
| 2 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 3 | accountEmailPrimary | `String` | Account Email Primary |
| 4 | accountID | `Float` | Account ID |
| 5 | accountName | `String` | Account Name |
| 6 | accountName2 | `String` | Account Name 2 |
| 7 | accountName3 | `String` | Account Name 3 |
| 8 | accountOwnerTitle | `String` | Account Owner Title |
| 9 | accountOwnersAll | `String` | Account Owners(All) |
| 10 | accountPhonePrimary | `String` | Phone no. |
| 11 | accountPhoneWeb | `String` | Account Phone Web |
| 12 | accountSource | `String` | Account Source |
| 13 | accountSourceDescription | `String` | Account Source Description |
| 14 | accountType | `String` | Account Type |
| 15 | accountTypeDescription | `String` | Account Type Description |
| 16 | acctContact | `String` | Billing contact person in company. |
| 17 | actionCode | `String` | Action Code |
| 18 | activeFlag | `String` | Active Flag |
| 19 | address1 | `String` | Address 1 |
| 20 | address2 | `String` | Address 2 |
| 21 | address3 | `String` | Address 3 |
| 22 | address4 | `String` | Address 4 |
| 23 | addressLangCodeDesc | `String` | Address Lang Code Description |
| 24 | addressLanguage | `String` | Address Language |
| 25 | addressLanguageCode | `String` | Address Language Code |
| 26 | addressType | `String` | Address Type |
| 27 | allProperties | `String` | All Properties |
| 28 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 29 | alternateLanguageDescription | `String` | Alternate Language Description |
| 30 | alternateName | `String` | Alternate Name |
| 31 | alternateSalutation | `String` | Alternate Salutation |
| 32 | alternateTitle | `String` | Alternate Title |
| 33 | arNumberCentral | `String` | AR No Central |
| 34 | autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| 35 | billingInstruction | `String` | Billing Instruction |
| 36 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 37 | birthDate | `Date` | Birth Date |
| 38 | birthDateStr | `String` | Birth Date Str |
| 39 | birthPlace | `String` | Place of birth. |
| 40 | blMsg | `String` | Bl Msg |
| 41 | businessPotential | `String` | Business Potential |
| 42 | businessPotentialDescription | `String` | Business Potential Description |
| 43 | businessSegement | `String` | Business Segement |
| 44 | businessSegementDescription | `String` | Business Segement Description |
| 45 | businessTitle | `String` | Business Title |
| 46 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 47 | centralAccountSource | `String` | Central Account Source |
| 48 | centralAccountSourceDescription | `String` | Central Account Source Description |
| 49 | centralAccountType | `String` | Central Account Type |
| 50 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 51 | centralBusinessPotential | `String` | Central Business Potential |
| 52 | centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| 53 | centralBusinessSegementDescription | `String` | Central Business Segement Description |
| 54 | centralBusinessSegment | `String` | Central Business Segment |
| 55 | centralCompetitionCode | `String` | Central Competition Code |
| 56 | centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| 57 | centralCorporateType | `String` | Central Corporate Type |
| 58 | centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| 59 | centralInactiveReason | `String` | Central Inactive Reason |
| 60 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 61 | centralIndustryCode | `String` | Central Industry Code |
| 62 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 63 | centralKeyword | `String` | Central Keyword |
| 64 | centralPriority | `String` | Central Priority |
| 65 | centralPriorityDescription | `String` | Central Priority Description |
| 66 | centralProfileTypeCode | `String` | Central Profile Type Code |
| 67 | centralProfileTypeDescription | `String` | Central Profile Type Description |
| 68 | centralScope | `String` | Central Scope |
| 69 | centralScopeCity | `String` | Central Scope City |
| 70 | centralScopeCityDescription | `String` | Central Scope City Description |
| 71 | centralScopeDescription | `String` | Central Scope Description |
| 72 | centralState | `String` | Central State |
| 73 | centralTerritory | `String` | Central Territory |
| 74 | centralTerritoryDescription | `String` | Central Territory Description |
| 75 | chainCode | `String` | Chain Code |
| 76 | city | `String` | City |
| 77 | cityExt | `String` | City Ext |
| 78 | combinedName | `String` | Combined Name |
| 79 | commissionCode | `String` | Commission Code |
| 80 | commissionCodeAll | `String` | Commission Code All |
| 81 | communicationRole1 | `String` | Communication Role1 |
| 82 | communicationRole2 | `String` | Communication Role2 |
| 83 | communicationRole3 | `String` | Communication Role3 |
| 84 | communicationType1 | `String` | Communication Type1 |
| 85 | communicationType2 | `String` | Communication Type2 |
| 86 | communicationType3 | `String` | Communication Type3 |
| 87 | communicationValue1 | `String` | Communication Value1 |
| 88 | communicationValue2 | `String` | Communication Value2 |
| 89 | communicationValue3 | `String` | Communication Value3 |
| 90 | company | `String` | Company |
| 91 | competitionCode | `String` | Competition Code |
| 92 | competitionCodeDescription | `String` | Competition Code Description |
| 93 | corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 94 | corporateTypeDescription | `String` | Corporate Type Description |
| 95 | country | `String` | Country |
| 96 | countryDescription | `String` | Country Description |
| 97 | createdByUser | `String` | Created By User |
| 98 | createdOnDate | `DateTime` | Created On Date |
| 99 | creditCardName | `String` | Credit Card Name |
| 100 | creditCardType | `String` | Credit Card Type |
| 101 | creditRating | `String` | Credit Rating |
| 102 | currencyCode | `String` | Currency Code |
| 103 | currencyDescription | `String` | Currency Description |
| 104 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | emailYn | `String` | Email Y/N |
| 107 | envelopeGreeting | `String` | Envelope Greeting |
| 108 | externalId | `String` | External ID |
| 109 | fSubscriptionDb | `String` | F Subscription Db |
| 110 | fSubscriptionYn | `String` | F Subscription Y/N |
| 111 | faxNo | `String` | Fax Number |
| 112 | first | `String` | First |
| 113 | gender | `String` | Gender |
| 114 | guestPrivYn | `String` | Guest Priv Y/N |
| 115 | historyYn | `String` | History Y/N |
| 116 | holdCode | `String` | Hold Code |
| 117 | iATANumber | `String` | IATA Number |
| 118 | iataConsortia | `String` | IATA Consortia |
| 119 | inactiveDate | `DateTime` | Inactive Date |
| 120 | inactiveFlag | `String` | Inactive Flag |
| 121 | inactiveReason | `String` | Reason Code for inactive status from REASON table |
| 122 | inactiveReasonDescription | `String` | Reason why record was inactivated. |
| 123 | industryCode | `String` | Industry Code |
| 124 | industryCodeDescription | `String` | Industry Code Description |
| 125 | interest | `String` | Interest Code. |
| 126 | internalDeletedflag | `String` | Deleted Flag |
| 127 | internalInactiveflag | `String` | Inactive Flag |
| 128 | internalOrganizationId | `Float` | Organization ID |
| 129 | jRNUpdateDate | `Date` | JRN Update Date |
| 130 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 131 | keyword | `String` | Keyword |
| 132 | last | `String` | Last |
| 133 | lastGroup | `String` | Last Group |
| 134 | lastRate | `Float` | Last Rate |
| 135 | lastRoom | `String` | Not used. |
| 136 | lastSource | `String` | Last Source |
| 137 | lastStay | `Date` | Last Stay |
| 138 | legalCompany | `String` | Legal Company |
| 139 | letterGreeting | `String` | Letter Greeting |
| 140 | mailAction | `String` | Mail Action |
| 141 | mailActionDescription | `String` | Mail Action Description |
| 142 | mailList | `String` | Mail List |
| 143 | mailType | `String` | The type of mail this user should be sent. |
| 144 | mailYn | `String` | Mail Y/N |
| 145 | marketResearchYn | `String` | Market Research Y/N |
| 146 | middle | `String` | Middle |
| 147 | nameId | `Float` | Name ID |
| 148 | nationalityCode | `String` | Nationality Code |
| 149 | nationalityDescription | `String` | Nationality Description |
| 150 | negotiatedRate | `String` | Negotiated Rate |
| 151 | nextStay | `Date` | Next Stay |
| 152 | nickname | `String` | The nickname of this individual. |
| 153 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 154 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 155 | postalCode | `String` | Postal Code |
| 156 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 157 | primaryOwner | `String` | Primary Owner |
| 158 | primaryOwnerCode | `String` | Primary Owner Code |
| 159 | priority | `String` | Priority |
| 160 | priorityDescription | `String` | Priority Description |
| 161 | productInterest | `String` | Product Interest |
| 162 | profession | `String` | Profession of the guest |
| 163 | profileLanguageDescription | `String` | Profile Language Description |
| 164 | profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 165 | profileType | `String` | Profile Type |
| 166 | profileTypeCode | `String` | Profile Type Code |
| 167 | profileTypeDescription | `String` | Profile Type Description |
| 168 | protected | `String` | Protected |
| 169 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 170 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 171 | referenceCurrency | `String` | Reference Currency |
| 172 | repInfluence | `String` | Reporting Influence |
| 173 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 174 | repMailActionCodes | `String` | Rep Mail Action Codes |
| 175 | repMailActionDesc | `String` | Rep Mail Action Desc |
| 176 | repNationalityCode | `String` | Reporting Nationality Code |
| 177 | repNationalityDescription | `String` | Reporting Nationality Description |
| 178 | repStateDescription | `String` | Reporting State Desc |
| 179 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 180 | repTitleName | `String` | Reporting Title Name |
| 181 | repVIPName | `String` | Reporting Vip Name |
| 182 | repVIPStatus | `String` | Reporting Vip Status |
| 183 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 184 | resortRegistered | `String` | Resort for which Job is registered. |
| 185 | restricted | `String` | Restricted |
| 186 | restrictedRule | `String` | Restricted Rule |
| 187 | salutation | `String` | Salutation Greeting |
| 188 | scope | `String` | Scope |
| 189 | scopeCity | `String` | Scope City |
| 190 | scopeCityDecription | `String` | Scope City Decription |
| 191 | scopeDescription | `String` | Scope Description |
| 192 | searchAccountName | `String` | The Uppercase value of Last or Company. |
| 193 | sfirst | `String` | Uppercase value of First Name. |
| 194 | state | `String` | State |
| 195 | stateCode | `String` | State Code |
| 196 | stateDesc | `String` | State Description of the Guest of Payee |
| 197 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 198 | sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 199 | tax1No | `String` | Tax1 Number |
| 200 | tax2No | `String` | Tax2 Number |
| 201 | taxCategory | `String` | Tax Category |
| 202 | taxType | `String` | Tax Type |
| 203 | taxTypeDescription | `String` | Tax Type Description |
| 204 | territory | `String` | Territory |
| 205 | territoryDescription | `String` | Territory Description |
| 206 | thirdPartyYn | `String` | Third Party Y/N |
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

### ProfilesAccountsProfileForecastDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cExchangeDate | `Date` | Central Xchange Date |
| 2 | cExchangeRate | `Float` | Central Xchange Rate |
| 3 | centralForecastFBRevenue | `Float` | Central Forecast FB Revenue |
| 4 | centralForecastOtherRevenue | `Float` | Central Forecast Other Revenue |
| 5 | centralForecastRoomAverageRate | `Float` | Central Forecast Room Average Rate |
| 6 | centralForecastRoomRevenue | `Float` | Central Forecast Room Revenue |
| 7 | chainCode | `String` | Chain Code |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | forecastFBRevenue | `Float` | Forecast FB Revenue |
| 12 | forecastInsertDate | `DateTime` | Forecast Insert Date |
| 13 | forecastInsertUser | `Float` | Forecast Insert User |
| 14 | forecastOtherRevenue | `Float` | Forecast Other Revenue |
| 15 | forecastPeriodCode | `String` | Forecast Period Code |
| 16 | forecastPeriodEnd | `Date` | Period End Date |
| 17 | forecastPeriodStart | `Date` | Period Start Date |
| 18 | forecastRoomAverageRate | `Float` | Average Room Rate |
| 19 | forecastRoomNights | `Float` | Forecast Room Nights |
| 20 | forecastRoomRevenue | `Float` | Forecast Room Revenue |
| 21 | forecastSplitMode | `String` | Specifies the forecast split mode. Possible values are: GROUP NON-GROUP and blank. |
| 22 | forecastType | `String` | Forecast Type |
| 23 | forecastUpdateDate | `DateTime` | Forecast Update Date |
| 24 | forecastUpdateUser | `Float` | Forecast Update User |
| 25 | inactiveDate | `DateTime` | Inactive Date |
| 26 | insertUserName | `String` | The name of the user who created the record. |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | laptopChange | `Float` | Laptop Change |
| 30 | linkChainCode | `String` | Link Chain Code |
| 31 | linkId | `Float` | Link ID |
| 32 | linkInsertDate | `DateTime` | Link Insert Date |
| 33 | linkInsertUser | `Float` | Link Insert User |
| 34 | linkLaptopChange | `Float` | Link Laptop Change |
| 35 | linkType | `String` | Link Type |
| 36 | locationID | `String` | Internal ID to uniquely identify the Property |
| 37 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 38 | period | `String` | Period |
| 39 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 40 | primaryYn | `String` | Primary Y/N |
| 41 | profileId | `Float` | Profile ID |
| 42 | property | `String` | Code to uniquely identify the Property |
| 43 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 44 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 45 | relationship | `String` | Relationship |
| 46 | toType | `String` | To Type |
| 47 | updateUserName | `String` | Update User Name |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileCommunicationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressId | `Float` | Not used. |
| 2 | beginDate | `Date` | Not used. |
| 3 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 4 | communicationID | `Float` | The primary key for this table. |
| 5 | communicationRole | `String` | Role in which this phone type belongs to. |
| 6 | communicationValue | `String` | The phone number for this record |
| 7 | countryCode | `String` | Country Code of the phone number. |
| 8 | countryDialingCode | `Float` | Numeric phone dialing prefix code for the country. |
| 9 | countryId | `String` | Country Code of the phone number. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | defaultMethodYN | `String` | Phone_role to be used for default confirmation. |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | displaySequence | `Float` | Order in which the phone numbers should be displayed. |
| 14 | emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| 15 | emailLanguage | `String` | Optional language for e-mail. |
| 16 | endDate | `Date` | The date this record becomes invalid for use in the system. User enterable. |
| 17 | extension | `String` | Telephone Extension. |
| 18 | firstName | `String` | The first name of an individual name. |
| 19 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 20 | inactiveFlag | `String` | Inactive Flag |
| 21 | indexPhone | `String` | Index Phone |
| 22 | insertDate | `DateTime` | The date the record was created |
| 23 | insertUser | `Float` | The user that created the record |
| 24 | internalOrganizationId | `Float` | Organization ID |
| 25 | internalProfileId | `Float` | The reference to the name that owns this phone. |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | laptopChange | `Float` | Code to synchronize with Laptop |
| 29 | lastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 30 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 31 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 32 | phoneId | `Float` | The primary key for this table. |
| 33 | phoneType | `String` | The type of this phone number. |
| 34 | phoneTypeDescription | `String` | Description of Phone Types. |
| 35 | phoneTypeId | `String` | The type of this phone number. |
| 36 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 37 | primaryYN | `String` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| 38 | profileID | `Float` | The reference to the name that owns this phone. |
| 39 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 40 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 41 | shareEmailYn | `String` | Used for uploading the email to holidex if the value is Y. |
| 42 | updateDate | `DateTime` | The date the record was modified |
| 43 | updateUser | `Float` | The user that modified the record |
| 44 | validYn | `String` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileCommissionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountId | `Float` | Account ID |
| 2 | centralCommissionCode | `String` | Central Commission Code |
| 3 | centralCommissionCodeDescription | `String` | Central Commission Code Description |
| 4 | commissionCode | `String` | Commission Code |
| 5 | commissionCodeDescription | `String` | Commission Code Description |
| 6 | createdByUser | `Float` | Created By User |
| 7 | createdOnDate | `DateTime` | Created On Date |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | laptopChange | `Float` | Laptop Change |
| 13 | locationID | `String` | Internal ID to uniquely identify the Property |
| 14 | nameId | `Float` | Name ID |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 19 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileRelationshipDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 2 | company | `String` | This column store the Name of the Company Profiles. |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | fromProfileID | `Float` | The reference to the name that owns this relationship. |
| 6 | guestName | `String` | Guest Name |
| 7 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 8 | inactiveFlag | `String` | Inactive Flag |
| 9 | insertDate | `DateTime` | The date the record was created |
| 10 | insertUser | `Float` | The user that created the record |
| 11 | internalLocationId | `String` | The property that the record belongs to |
| 12 | internalOrganizationId | `Float` | Organization ID |
| 13 | internalRelationshipId | `String` | The type of relationship this name id has to the relationship_to_name_id. |
| 14 | jRNUpdateDate | `Date` | JRN Update Date |
| 15 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 16 | laptopChange | `Float` | Changed by laptop Y or N |
| 17 | locationID | `String` | The property that the record belongs to |
| 18 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 19 | ownerProfileId | `Float` | The reference to the name that owns this relationship. |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | primaryYN | `String` | Indicates the Primary relationship where Multiple Relationships are attached to a profile. |
| 22 | profilerelationshipId | `Float` | The primary key for this table. |
| 23 | property | `String` | The property that the record belongs to |
| 24 | relationshipCode | `String` | The type of relationship this name id has to the relationship_to_name_id. |
| 25 | relationshipDescription | `String` | Description of the relationship. |
| 26 | relationshipID | `Float` | The primary key for this table. |
| 27 | relationshipRole | `String` | Used in S&C Module |
| 28 | relationshipTo | `String` | Relationship To |
| 29 | relationshipToNameID | `Float` | The reference to the name that the "Name_id" is related to. |
| 30 | resort | `String` | The property that the record belongs to |
| 31 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 32 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 33 | toProfileID | `Float` | The reference to the name that the "Name_id" is related to. |
| 34 | updateDate | `DateTime` | The date the record was modified |
| 35 | updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesAccountsAccountMonthlyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adr | `Float` | Average Daily Rate |
| 2 | cCcFBRevenue | `Float` | Central Cc Fb Revenue |
| 3 | cCcFBRevenueTax | `Float` | Central Cc Fb Revenue Tax |
| 4 | cCcGroupFBRevenue | `Float` | Central Cc Grp Fb Revenue |
| 5 | cCcGroupFBRevenueTax | `Float` | Central Cc Grp Fb Revenue Tax |
| 6 | cCcGroupMiscellaneousRevenue | `Float` | Central Cc Grp Misc Revenue |
| 7 | cCcGroupMiscellaneousRevenueTax | `Float` | Central Cc Grp Misc Revenue Tax |
| 8 | cCcGroupOtherRevenue | `Float` | Central Cc Grp Other Revenue |
| 9 | cCcGroupOtherRevenueTax | `Float` | Central Cc Grp Other Revenue Tax |
| 10 | cCcGroupRoomRevenue | `Float` | Central Cc Grp Room Revenue |
| 11 | cCcGroupRoomRevenueTax | `Float` | Central Cc Grp Room Revenue Tax |
| 12 | cCcGroupTotalRevenue | `Float` | Central Cc Grp Total Revenue |
| 13 | cCcGroupTotalRevenueTax | `Float` | Central Cc Grp Total Revenue Tax |
| 14 | cCcMiscellaneousRevenue | `Float` | Central Cc Misc Revenue |
| 15 | cCcMiscellaneousRevenueTax | `Float` | Central Cc Misc Revenue Tax |
| 16 | cCcOtherRevenue | `Float` | Central Cc Other Revenue |
| 17 | cCcOtherRevenueTax | `Float` | Central Cc Other Revenue Tax |
| 18 | cCcRoomRevenue | `Float` | Central Cc Room Revenue |
| 19 | cCcRoomRevenueTax | `Float` | Central Cc Room Revenue Tax |
| 20 | cCcTotalRevenue | `Float` | Central Cc Total Revenue |
| 21 | cCcTotalRevenueTax | `Float` | Central Cc Total Revenue Tax |
| 22 | cExchangeDate | `Date` | Central Xchange Date |
| 23 | cExchangeRate | `Float` | Central Xchange Rate |
| 24 | cancels | `Float` | Cancels |
| 25 | ccFbRevenue | `Float` | Central Currency F&B Revenue. |
| 26 | ccFbRevenueTax | `Float` | Central Currency F&B Revenue Tax. |
| 27 | ccGrpFBRevenue | `Float` | Central Currency Group F&B Revenue. |
| 28 | ccGrpFBRevenueTax | `Float` | Central Currency Group F&B Revenue Tax. |
| 29 | ccGrpMiscellaneousRevenue | `Float` | Central Currency Group Misc. Revenue Tax. |
| 30 | ccGrpMiscellaneousRevenueTax | `Float` | Central Currency Group Misc. Revenue Tax. |
| 31 | ccGrpOtherRevenue | `Float` | Central Currency Group Other Revenue. |
| 32 | ccGrpOtherRevenueTax | `Float` | Central Currency Group Other Revenue Tax. |
| 33 | ccGrpRoomRevenue | `Float` | Central Currency Group Room Revenue. |
| 34 | ccGrpRoomRevenueTax | `Float` | Central Currency Group Room Revenue Tax. |
| 35 | ccGrpTotalRevenue | `Float` | Central Currency Group Total Revenue. |
| 36 | ccGrpTotalRevenueTax | `Float` | Central Currency Group Total Revenue Tax. |
| 37 | ccMiscRevenue | `Float` | Central Currency Miscelleanous Revenue. |
| 38 | ccMiscRevenueTax | `Float` | Central Currency Misc. Revenue Tax. |
| 39 | ccOtherRevenue | `Float` | Central Currency Other Revenue. |
| 40 | ccOtherRevenueTax | `Float` | Central Currency Other Revenue Tax. |
| 41 | ccRoomRevenue | `Float` | Central Currency Room Revenue. |
| 42 | ccRoomRevenueTax | `Float` | Central Currency Room Revenue Tax. |
| 43 | ccTotalRevenue | `Float` | Central Currency Total Revenue. |
| 44 | ccTotalRevenueTax | `Float` | Central Currency Total Revenue Tax. |
| 45 | centralCurrencyCode | `String` | Central Currency Code |
| 46 | centralFBRevenueNet | `Float` | Central FB Revenue Net |
| 47 | centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| 48 | centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| 49 | centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| 50 | centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| 51 | centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| 52 | centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| 53 | centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| 54 | centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| 55 | centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| 56 | centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| 57 | centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| 58 | centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| 59 | centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| 60 | centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| 61 | centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| 62 | centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| 63 | centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| 64 | centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| 65 | centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 66 | centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| 67 | centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 68 | centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| 69 | centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 70 | contextCd | `String` | Context Cd |
| 71 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 72 | deletedFlag | `String` | Deleted Flag |
| 73 | fBRevenueNet | `Float` | FB Revenue Net |
| 74 | fBRevenueTax | `Float` | FB Revenue Tax |
| 75 | groupCancels | `Float` | Group Number of Cancellations. |
| 76 | groupFBRevenueNet | `Float` | Group F&B Revenue. |
| 77 | groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| 78 | groupNoShows | `Float` | Group Number of No Shows. |
| 79 | groupOtherRevenueNet | `Float` | Group Other Revenue. |
| 80 | groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| 81 | groupRoomNights | `Float` | Group Number of Nights. |
| 82 | groupRoomRevenueNet | `Float` | Group Room Revenue. |
| 83 | groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| 84 | groupStays | `Float` | Group Number of Stays. |
| 85 | groupTotalRevenueNet | `Float` | Group Total Revenue. |
| 86 | groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| 87 | grpAverageDailyRate | `Float` | Group Adr |
| 88 | individualCancels | `Float` | Individual Cancels |
| 89 | individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| 90 | individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| 91 | individualNoShows | `Float` | Individual Number Shows |
| 92 | individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| 93 | individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| 94 | individualRoomNights | `Float` | Individual Room Nights |
| 95 | individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| 96 | individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| 97 | individualStays | `Float` | Individual Stays |
| 98 | individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| 99 | individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
| 100 | insertDate | `DateTime` | Insert Date |
| 101 | insertUser | `Float` | Insert User |
| 102 | jRNUpdateDate | `Date` | JRN Update Date |
| 103 | jrnFilerba | `Float` | Journal Filerba |
| 104 | jrnFileseqno | `Float` | Journal Fileseqno |
| 105 | jrnFlag | `String` | Journal Flag |
| 106 | jrnScn | `Float` | Journal Scn |
| 107 | jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| 108 | jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| 109 | localCurrency | `String` | Local Currency Code. |
| 110 | locationID | `String` | Internal ID to uniquely identify the Property |
| 111 | nameId | `Float` | Name ID |
| 112 | nameType | `String` | Name Type |
| 113 | noShows | `Float` | Number Shows |
| 114 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 115 | otherRevenueNet | `Float` | Other Revenue Net |
| 116 | otherRevenueTax | `Float` | Other Revenue Tax |
| 117 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 118 | property | `String` | Code to uniquely identify the Property |
| 119 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 120 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 121 | roomNights | `Float` | Room Nights |
| 122 | roomRevenueNet | `Float` | Room Revenue Net |
| 123 | roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| 124 | stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| 125 | stayYear | `Float` | Year of Summary. |
| 126 | stayedBooked | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| 127 | stays | `Float` | Stays |
| 128 | totalAdr | `Float` | Total Average Daily Rate |
| 129 | totalRevenueNet | `Float` | Total Revenue Net |
| 130 | totalRevenueTax | `Float` | Total Revenue Tax |
| 131 | updateDate | `DateTime` | Update Date |
| 132 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileAddressDetailsType

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

### ProfilesAccountsAccountDailyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adr | `Float` | Average Daily Rate |
| 2 | cancels | `Float` | Cancels |
| 3 | centralFBRevenueNet | `Float` | Central FB Revenue Net |
| 4 | centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| 5 | centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| 6 | centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| 7 | centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| 8 | centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| 9 | centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| 10 | centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| 11 | centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| 12 | centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| 13 | centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| 14 | centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| 15 | centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| 16 | centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| 17 | centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| 18 | centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| 19 | centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| 20 | centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| 21 | centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| 22 | centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 23 | centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| 24 | centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 25 | centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| 26 | centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 27 | centralXchangeDate | `Date` | Central Exchange Date |
| 28 | centralXchangeRate | `Float` | Central Exchange Rate |
| 29 | contextCd | `String` | Context Cd |
| 30 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 31 | deletedFlag | `String` | Deleted Flag |
| 32 | fBRevenueNet | `Float` | FB Revenue Net |
| 33 | fBRevenueTax | `Float` | FB Revenue Tax |
| 34 | groupCancels | `Float` | Group Number of Cancellations. |
| 35 | groupFBRevenueNet | `Float` | Group F&B Revenue. |
| 36 | groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| 37 | groupNoShows | `Float` | Group Number of No Shows. |
| 38 | groupOtherRevenueNet | `Float` | Group Other Revenue. |
| 39 | groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| 40 | groupRoomNights | `Float` | Group Number of Nights. |
| 41 | groupRoomRevenueNet | `Float` | Group Room Revenue. |
| 42 | groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| 43 | groupStays | `Float` | Group Number of Stays. |
| 44 | groupTotalRevenueNet | `Float` | Group Total Revenue. |
| 45 | groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| 46 | grpAverageDailyRate | `Float` | Group Adr |
| 47 | individualCancels | `Float` | Individual Cancels |
| 48 | individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| 49 | individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| 50 | individualNoShows | `Float` | Individual Number Shows |
| 51 | individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| 52 | individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| 53 | individualRoomNights | `Float` | Individual Room Nights |
| 54 | individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| 55 | individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| 56 | individualStays | `Float` | Individual Stays |
| 57 | individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| 58 | individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
| 59 | jRNUpdateDate | `Date` | JRN Update Date |
| 60 | jrnFilerba | `Float` | Journal Filerba |
| 61 | jrnFileseqno | `Float` | Journal Fileseqno |
| 62 | jrnFlag | `String` | Journal Flag |
| 63 | jrnScn | `Float` | Journal Scn |
| 64 | jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| 65 | jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| 66 | localCurrency | `String` | Local Currency Code. |
| 67 | locationID | `String` | Internal ID to uniquely identify the Property |
| 68 | nameId | `Float` | Name ID |
| 69 | nameType | `String` | Name Type |
| 70 | noShows | `Float` | Number Shows |
| 71 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 72 | otherRevenueNet | `Float` | Other Revenue Net |
| 73 | otherRevenueTax | `Float` | Other Revenue Tax |
| 74 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 75 | property | `String` | Code to uniquely identify the Property |
| 76 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 77 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 78 | roomNights | `Float` | Room Nights |
| 79 | roomRevenueNet | `Float` | Room Revenue Net |
| 80 | roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| 81 | stayDate | `Date` | Stay Date |
| 82 | stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| 83 | stayYear | `Float` | Year of Summary. |
| 84 | stays | `Float` | Stays |
| 85 | totalAdr | `Float` | Total Average Daily Rate |
| 86 | totalRevenueNet | `Float` | Total Revenue Net |
| 87 | totalRevenueTax | `Float` | Total Revenue Tax |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileNoteDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activityDueDate | `Date` | Activity Due Date |
| 2 | activityType | `String` | Activity Type |
| 3 | chainCode | `String` | ASP chain code. |
| 4 | confidentialYN | `String` | Indicates if this note is confidential. |
| 5 | createdByUser | `Float` | The user that created the record |
| 6 | createdOnDate | `DateTime` | The date the record was created |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | externalNoteId | `String` | Unique ID in External System. |
| 10 | globalNoteYn | `String` | Global Note Y/N |
| 11 | globalYn | `String` | Can a global note be created for this note code or not. |
| 12 | inactiveDate | `Date` | Inactive date of the record. This indicates that record is no longer in use and can be purged in by purge routine. |
| 13 | inactiveFlag | `String` | Inactive Flag |
| 14 | internalDeletedflag | `String` | Deleted Flag |
| 15 | internalInactiveflag | `String` | Inactive Flag |
| 16 | internalLocationId | `String` | Location Id |
| 17 | internalOrganizationId | `Float` | Organization ID |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | laptopChange | `Float` | Indicator for Laptop change. |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | nameId | `Float` | Parent Name_id refers Name table. |
| 23 | nameType | `String` | The type of Profile. |
| 24 | noteCode | `String` | Indicates the Type of Note. |
| 25 | noteCodeDescription | `String` | Description of Note Code |
| 26 | noteId | `Float` | Primary Key for the Table |
| 27 | noteInternalYN | `String` | Indicates if this note should be shown to guest. Future use. |
| 28 | noteTitle | `String` | Title of the Note |
| 29 | notes | `String` | The actual Note. |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 32 | profileId | `Float` | Parent Name_id refers Name table. |
| 33 | profileNoteId | `Float` | Profile Note ID |
| 34 | resort | `String` | Property |
| 35 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 36 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 37 | updateDate | `DateTime` | The date the record was modified |
| 38 | updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileRelationshipHierDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | bottomId | `Float` | Level Ten Name ID. |
| 2 | bottomNameType | `String` | Lowest Level Name Type. |
| 3 | chainCode | `String` | Chain Code |
| 4 | contextCd | `String` | Context Cd |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | relToType | `String` | Relationship with Type. |
| 12 | relType | `String` | Relationship Type. |
| 13 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 14 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 15 | topId | `Float` | Master Name ID. |
| 16 | totalLevels | `Float` | Current Level or Record in relationship hierarchy. |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfilePreferenceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | centralPreferenceCode | `String` | Central Preference Code |
| 3 | centralPreferenceDescription | `String` | Central Preference Description |
| 4 | centralPreferenceGroup | `String` | Central Preference Group |
| 5 | chainCode | `String` | ASP chain code. |
| 6 | chargeYn | `String` | Not used. |
| 7 | createdByUser | `Float` | The user that created the record |
| 8 | createdOnDate | `DateTime` | The date the record was created |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | displaySequence | `Float` | The display sequence  of the Preferences. |
| 12 | externalPreferenceId | `String` | Unique ID in External System. |
| 13 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 14 | inactiveFlag | `String` | Inactive Flag |
| 15 | internalOrganizationId | `Float` | Organization ID |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | laptopChange | `Float` | Laptop Change Indicator |
| 19 | locationID | `String` | The property that the record belongs to |
| 20 | mpcode | `String` | Not Used. |
| 21 | nameId | `Float` | Reference to the name that owns this record. |
| 22 | noteProperty | `String` | The property that the record belongs to |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | preferenceCode | `String` | Preference Code. Part of the Primary Key. |
| 25 | preferenceDescription | `String` | Description of the Preference. |
| 26 | preferenceGroup | `String` | Description of the Preference Type. |
| 27 | preferenceId | `String` | Preference Code. |
| 28 | preferenceTypeCode | `String` | Preference Type. |
| 29 | preferenceTypeId | `String` | Preference Type. |
| 30 | preferenceValue | `String` | Preference Code. |
| 31 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 32 | profileId | `Float` | Reference to the name that owns this record. |
| 33 | profilePreferenceId | `String` | Preference Code. |
| 34 | property | `String` | The property that the record belongs to |
| 35 | repOrderby | `Float` | Reporting Orderby |
| 36 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 37 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 38 | updateDate | `DateTime` | The date the record was modified |
| 39 | updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### ProfilesAccountsAccountYearlyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adr | `Float` | Average Daily Rate |
| 2 | cCcRoomRevenueTax | `Float` | Central Cc Room Revenue Tax |
| 3 | cCcTotalRevenue | `Float` | Central Cc Total Revenue |
| 4 | cCcTotalRevenueTax | `Float` | Central Cc Total Revenue Tax |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cancels | `Float` | Cancels |
| 8 | ccFbRevenue | `Float` | Central Currency F&B Revenue. |
| 9 | ccFbRevenueTax | `Float` | Central Currency F&B Revenue Tax. |
| 10 | ccGrpFBRevenue | `Float` | Central Currency Group F&B Revenue. |
| 11 | ccGrpFBRevenueTax | `Float` | Central Currency Group F&B Revenue Tax. |
| 12 | ccGrpMiscellaneousRevenue | `Float` | Central Currency Group Misc. Revenue Tax. |
| 13 | ccGrpMiscellaneousRevenueTax | `Float` | Central Currency Group Misc. Revenue Tax. |
| 14 | ccGrpOtherRevenue | `Float` | Central Currency Group Other Revenue. |
| 15 | ccGrpOtherRevenueTax | `Float` | Central Currency Group Other Revenue Tax. |
| 16 | ccGrpRoomRevenue | `Float` | Central Currency Group Room Revenue. |
| 17 | ccGrpRoomRevenueTax | `Float` | Central Currency Group Room Revenue Tax. |
| 18 | ccGrpTotalRevenue | `Float` | Central Currency Group Total Revenue. |
| 19 | ccGrpTotalRevenueTax | `Float` | Central Currency Group Total Revenue Tax. |
| 20 | ccMiscRevenue | `Float` | Central Currency Miscelleanous Revenue. |
| 21 | ccMiscRevenueTax | `Float` | Central Currency Misc. Revenue Tax. |
| 22 | ccOtherRevenue | `Float` | Central Currency Other Revenue. |
| 23 | ccOtherRevenueTax | `Float` | Central Currency Other Revenue Tax. |
| 24 | ccRoomRevenue | `Float` | Central Currency Room Revenue. |
| 25 | ccRoomRevenueTax | `Float` | Central Currency Room Revenue Tax. |
| 26 | ccTotalRevenue | `Float` | Central Currency Total Revenue. |
| 27 | ccTotalRevenueTax | `Float` | Central Currency Total Revenue Tax. |
| 28 | centralCcFbRevenue | `Float` | Central Cc FB Revenue |
| 29 | centralCcFbRevenueTax | `Float` | Central Cc FB Revenue Tax |
| 30 | centralCcGrpFBRevenue | `Float` | Central Cc Group Fb Revenue |
| 31 | centralCcGrpFBRevenueTax | `Float` | Central Cc Group Fb Revenue Tax |
| 32 | centralCcGrpMiscellaneousRevenue | `Float` | Central Cc Group Misc Revenue |
| 33 | centralCcGrpMiscellaneousRevenueTax | `Float` | Central Cc Group Misc Revenue Tax |
| 34 | centralCcGrpOtherRevenue | `Float` | Central Cc Group Other Revenue |
| 35 | centralCcGrpOtherRevenueTax | `Float` | Central Cc Group Other Revenue Tax |
| 36 | centralCcGrpRoomRevenue | `Float` | Central Cc Group Room Revenue |
| 37 | centralCcGrpRoomRevenueTax | `Float` | Central Cc Group Room Revenue Tax |
| 38 | centralCcGrpTotalRevenue | `Float` | Central Cc Group Total Revenue |
| 39 | centralCcGrpTotalRevenueTax | `Float` | Central Cc Group Total Revenue Tax |
| 40 | centralCcMiscRevenue | `Float` | Central Cc Miscellaneous Revenue |
| 41 | centralCcMiscRevenueTax | `Float` | Central Cc Miscellaneous Revenue Tax |
| 42 | centralCcOtherRevenue | `Float` | Central Cc Other Revenue |
| 43 | centralCcOtherRevenueTax | `Float` | Central Cc Other Revenue Tax |
| 44 | centralCcRoomRevenue | `Float` | Central Cc Room Revenue |
| 45 | centralCurrencyCode | `String` | Central Currency Code |
| 46 | centralFBRevenueNet | `Float` | Central FB Revenue Net |
| 47 | centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| 48 | centralGroupFBRevenueNet | `Float` | Central Group FB Revenue Net |
| 49 | centralGroupFBRevenueTax | `Float` | Central Group FB Revenue Tax |
| 50 | centralGroupOtherRevenueNet | `Float` | Central Group Other Revenue Net |
| 51 | centralGroupOtherRevenueTax | `Float` | Central Group Other Revenue Tax |
| 52 | centralGroupRoomRevenueNet | `Float` | Central Group Room Revenue Net |
| 53 | centralGroupRoomRevenueTax | `Float` | Central Group Room Revenue Tax |
| 54 | centralGroupTotalRevenueNet | `Float` | Central Group Total Revenue Net |
| 55 | centralGroupTotalRevenueTax | `Float` | Central Group Total Revenue Tax |
| 56 | centralIndividualFBRevenueNet | `Float` | Central Individual FB Revenue Net |
| 57 | centralIndividualFBRevenueTax | `Float` | Central Individual FB Revenue Tax |
| 58 | centralIndividualOtherRevenueNet | `Float` | Central Individual Other Revenue Net |
| 59 | centralIndividualOtherRevenueTax | `Float` | Central Individual Other Revenue Tax |
| 60 | centralIndividualRoomRevenueNet | `Float` | Central Individual Room Revenue Net |
| 61 | centralIndividualRoomRevenueTax | `Float` | Central Individual Room Revenue Tax |
| 62 | centralIndividualTotalRevenueNet | `Float` | Central Individual Total Revenue Net |
| 63 | centralIndividualTotalRevenueTax | `Float` | Central Individual Total Revenue Tax |
| 64 | centralOtherRevenueNet | `Float` | Central Other Revenue Net |
| 65 | centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 66 | centralRoomRevenueNet | `Float` | Central Room Revenue Net |
| 67 | centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 68 | centralTotalRevenueNet | `Float` | Central Total Revenue Net |
| 69 | centralTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 70 | contextCd | `String` | Context Cd |
| 71 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 72 | deletedFlag | `String` | Deleted Flag |
| 73 | fBRevenueNet | `Float` | FB Revenue Net |
| 74 | fBRevenueTax | `Float` | FB Revenue Tax |
| 75 | groupCancels | `Float` | Group Number of Cancellations. |
| 76 | groupFBRevenueNet | `Float` | Group F&B Revenue. |
| 77 | groupFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| 78 | groupNoShows | `Float` | Group Number of No Shows. |
| 79 | groupOtherRevenueNet | `Float` | Group Other Revenue. |
| 80 | groupOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| 81 | groupRoomNights | `Float` | Group Number of Nights. |
| 82 | groupRoomRevenueNet | `Float` | Group Room Revenue. |
| 83 | groupRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| 84 | groupStays | `Float` | Group Number of Stays. |
| 85 | groupTotalRevenueNet | `Float` | Group Total Revenue. |
| 86 | groupTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| 87 | grpAverageDailyRate | `Float` | Group Adr |
| 88 | individualCancels | `Float` | Individual Cancels |
| 89 | individualFBRevenueNet | `Float` | Individual FB Revenue Net |
| 90 | individualFBRevenueTax | `Float` | F&B Revenue Tax. |
| 91 | individualNoShows | `Float` | Individual Number Shows |
| 92 | individualOtherRevenueNet | `Float` | Individual Other Revenue Net |
| 93 | individualOtherRevenueTax | `Float` | Individual Other Revenue Tax |
| 94 | individualRoomNights | `Float` | Individual Room Nights |
| 95 | individualRoomRevenueNet | `Float` | Individual Room Revenue Net |
| 96 | individualRoomRevenueTax | `Float` | Individual Room Revenue Tax |
| 97 | individualStays | `Float` | Individual Stays |
| 98 | individualTotalRevenueNet | `Float` | Individual Total Revenue Net |
| 99 | individualTotalRevenueTax | `Float` | Individual Total Revenue Tax |
| 100 | insertDate | `DateTime` | Insert Date |
| 101 | insertUser | `Float` | Insert User |
| 102 | jRNUpdateDate | `Date` | JRN Update Date |
| 103 | jrnFilerba | `Float` | Journal Filerba |
| 104 | jrnFileseqno | `Float` | Journal Fileseqno |
| 105 | jrnFlag | `String` | Journal Flag |
| 106 | jrnScn | `Float` | Journal Scn |
| 107 | jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| 108 | jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| 109 | localCurrency | `String` | Local Currency Code. |
| 110 | locationID | `String` | Internal ID to uniquely identify the Property |
| 111 | nameId | `Float` | Name ID |
| 112 | nameType | `String` | Name Type |
| 113 | noShows | `Float` | Number Shows |
| 114 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 115 | otherRevenueNet | `Float` | Other Revenue Net |
| 116 | otherRevenueTax | `Float` | Other Revenue Tax |
| 117 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 118 | property | `String` | Code to uniquely identify the Property |
| 119 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 120 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 121 | roomNights | `Float` | Room Nights |
| 122 | roomRevenueNet | `Float` | Room Revenue Net |
| 123 | roomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| 124 | stayYear | `Float` | Year of Summary. |
| 125 | stayedBooked | `String` | Used when name_type="CONTACT" to determine if stored information is booked or stayed statistics. Possible values [S]TAYED [B]OOKED [A]=ALL (STAYED and BOOKED). NULL will be considered [S]TAYED. |
| 126 | stays | `Float` | Stays |
| 127 | totalAdr | `Float` | Total Average Daily Rate |
| 128 | totalRevenueNet | `Float` | Total Revenue Net |
| 129 | totalRevenueTax | `Float` | Total Revenue Tax |
| 130 | updateDate | `DateTime` | Update Date |
| 131 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesAccountsProfileOwnerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountOwner | `String` | Account Owner |
| 2 | accountOwnerCode | `String` | Account Owner Code |
| 3 | accountOwnerEmail | `String` | Account Owner Email |
| 4 | accountOwnerPhone | `String` | Phone no. |
| 5 | accountOwnerTitle | `String` | Account Owner Title |
| 6 | accountSrepCode | `String` | Account Srep Code |
| 7 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 8 | chainCode | `String` | Chain Code |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveFlag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalOrganizationId | `Float` | Organization ID |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | laptopChange | `Float` | Laptop Change |
| 20 | locationId | `String` | Location ID |
| 21 | nameId | `Float` | Name ID |
| 22 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 23 | ownerProfileId | `Float` | Owner Profile ID |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | primaryYN | `String` | Primary YN |
| 26 | profileOwnerId | `Float` | Profile Owner ID |
| 27 | property | `String` | Indicates if the value set for the specific property. |
| 28 | relationship | `String` | Relationship |
| 29 | relationshipid | `String` | Relationshipid |
| 30 | resort | `String` | Property |
| 31 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 32 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 33 | toType | `String` | To Type |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |
| 36 | userId | `Float` | User ID |

[⬆ Back to Query](#query)

---

### ProfilesAccountsReservationDailyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adults | `Float` | Adults |
| 2 | adultsTaxFree | `Float` | Adults Tax Free |
| 3 | agentId | `Float` | Agent ID |
| 4 | agentprofileid | `Float` | Agentprofileid |
| 5 | allotmentHeaderId | `Float` | Allotment Header ID |
| 6 | allotmentid | `Float` | Block ID |
| 7 | arrivalPersons | `Float` | Arrival Persons |
| 8 | arrivalRooms | `Float` | Arrival Rooms |
| 9 | beginDate | `Date` | Begin Date |
| 10 | biReservationNameId | `Float` | Bi Resv Name ID |
| 11 | birthDate | `Date` | Birth Date |
| 12 | bookedRoomCategory | `String` | Booked Room Category |
| 13 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 14 | businessDate | `Date` | Business Date |
| 15 | businessDateCreated | `Date` | Business Date Created |
| 16 | cAdvanceTotalOtherTax | `Float` | Central Adv Total Other Tax |
| 17 | cCashRoomRevenue | `Float` | Central Cash Room Revenue |
| 18 | cCompRoomRevenue | `Float` | Central Comp Room Revenue |
| 19 | cExchangeDate | `Date` | Central Xchange Date |
| 20 | cExchangeRate | `Float` | Central Xchange Rate |
| 21 | cFlaggedFoodRevenue | `Float` | Central Flgd Food Revenue |
| 22 | cFlaggedNonRevenue | `Float` | Central Flgd Non Revenue |
| 23 | cFlaggedOtherRevenue | `Float` | Central Flgd Other Revenue |
| 24 | cFlaggedRoomRevenue | `Float` | Central Flgd Room Revenue |
| 25 | cFlaggedTotalFoodTax | `Float` | Central Flgd Total Food Tax |
| 26 | cFlaggedTotalNonRevenueTax | `Float` | Central Flgd Total Non Revenue Tax |
| 27 | cFlaggedTotalOtherTax | `Float` | Central Flgd Total Other Tax |
| 28 | cFlaggedTotalRevenue | `Float` | Central Flgd Total Revenue |
| 29 | cFlaggedTotalRoomTax | `Float` | Central Flgd Total Room Tax |
| 30 | cFlaggedTotalTax | `Float` | Central Flgd Total Tax |
| 31 | cPrAdvanceTotalFoodTax | `Float` | Central Pr Adv Total Food Tax |
| 32 | cRateAmount | `Float` | Central Rate Amount |
| 33 | cRsAdvanceFoodRevenue | `Float` | Central Rs Adv Food Revenue |
| 34 | cRsAdvanceFoodTax | `Float` | Central Rs Adv Food Tax |
| 35 | cRsAdvanceNonRevenue | `Float` | Central Rs Adv Non Revenue |
| 36 | cRsAdvanceNonRevenueTax | `Float` | Central Rs Adv Non Revenue Tax |
| 37 | cRsAdvanceOtherRevenue | `Float` | Central Rs Adv Other Revenue |
| 38 | cRsAdvanceOtherTax | `Float` | Central Rs Adv Other Tax |
| 39 | cRsAdvanceRoomRevenue | `Float` | Central Rs Adv Room Revenue |
| 40 | cRsAdvanceRoomTax | `Float` | Central Rs Adv Room Tax |
| 41 | cRsAdvanceTotalRevenue | `Float` | Central Rs Adv Total Revenue |
| 42 | cRsAdvanceTotalTax | `Float` | Central Rs Adv Total Tax |
| 43 | cUpsoldRevenue | `Float` | Central Upsold Revenue |
| 44 | cancellationDate | `DateTime` | Cancellation Date |
| 45 | cancelledPersons | `Float` | Cancelled Persons |
| 46 | cancelledReservations | `Float` | Cancelled Reservations |
| 47 | cancelledRooms | `Float` | Cancelled Rooms |
| 48 | cashRoomNts | `Float` | Cash Room Nts |
| 49 | cashRoomRevenue | `Float` | Cash Room Revenue |
| 50 | centralCurrencyCode | `String` | Central Currency Code |
| 51 | centralDistributedFoodRevenue | `Float` | Central Distributed Food Revenue |
| 52 | centralDistributedFoodRevenueAsPayee | `Float` | Central Distributed Food Revenue (as Payee |
| 53 | centralDistributedNonRevenue | `Float` | Central Distributed Non Revenue |
| 54 | centralDistributedNonRevenueAsPayee | `Float` | Central Distributed Non-Revenue (as Payee |
| 55 | centralDistributedOtherRevenue | `Float` | Central Distributed Other Revenue |
| 56 | centralDistributedOtherRevenueAsPayee | `Float` | Central Distributed Other Revenue (as Payee |
| 57 | centralDistributedRoomRevenue | `Float` | Central Distributed Room Revenue |
| 58 | centralDistributedRoomRevenueAsPayee | `Float` | Central Distributed Room Revenue (as Payee |
| 59 | centralDistributedTotalFoodTaxAsPayee | `Float` | Central Distributed Total Food Tax (as Payee |
| 60 | centralDistributedTotalNonRevenueTax | `Float` | Central Distributed Total Non Revenue Tax |
| 61 | centralDistributedTotalNonRevenueTaxAsPayee | `Float` | Central Distributed Total Non-Revenue Tax (as Payee |
| 62 | centralDistributedTotalOtherTaxAsPayee | `Float` | Central Distributed Total Other Tax (as Payee |
| 63 | centralDistributedTotalRevenue | `Float` | Central Distributed Total Revenue |
| 64 | centralDistributedTotalRevenueAsPayee | `Float` | Central Distributed Total Revenue (as Payee |
| 65 | centralDistributedTotalRoomTax | `Float` | Central Distributed Total Room Tax |
| 66 | centralDistributedTotalRoomTaxAsPayee | `Float` | Central Distributed Total Room Tax (as Payee |
| 67 | centralDistributedTotalTax | `Float` | Central Distributed Total Tax |
| 68 | centralDistributedTotalTaxAsPayee | `Float` | Central Distributed Total Tax (as Payee |
| 69 | centralExchangeRate | `Float` | Central Exchange Rate |
| 70 | centralFoodRevenue | `Float` | Central Food Revenue |
| 71 | centralFoodRevenueAsPayee | `Float` | Central Food Revenue (as Payee |
| 72 | centralMarketCode | `String` | Central Market Code |
| 73 | centralMarketDescription | `String` | Central Market Description |
| 74 | centralMarketGroupCode | `String` | Central Market Group Code |
| 75 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 76 | centralNonRevenue | `Float` | Central Non Revenue |
| 77 | centralNonRevenueAsPayee | `Float` | Central Non-Revenue (as Payee |
| 78 | centralOriginCode | `String` | Central Origin Code |
| 79 | centralOriginDescription | `String` | Central Origin Description |
| 80 | centralOriginalRoomType | `String` | Central Original Room Type |
| 81 | centralOtherRevenue | `Float` | Central Other Revenue |
| 82 | centralOtherRevenueAsPayee | `Float` | Central Other Revenue (as Payee |
| 83 | centralPackageFoodRevenue | `Float` | Central Package Food Revenue |
| 84 | centralPackageFoodRevenueAsPayee | `Float` | Central Package Food Revenue (as Payee |
| 85 | centralPackageNonRevenue | `Float` | Central Package Non Revenue |
| 86 | centralPackageNonRevenueAsPayee | `Float` | Central Package Non-Revenue (as Payee |
| 87 | centralPackageOtherRevenue | `Float` | Central Package Other Revenue |
| 88 | centralPackageOtherRevenueAsPayee | `Float` | Central Package Other Revenue (as Payee |
| 89 | centralPackageRoomRevenue | `Float` | Central Package Room Revenue |
| 90 | centralPackageRoomRevenueAsPayee | `Float` | Central Package Room Revenue (as Payee |
| 91 | centralRateCategory | `String` | Central Rate Category |
| 92 | centralRoomRevenue | `Float` | Central Room Revenue |
| 93 | centralRoomRevenueAsPayee | `Float` | Central Room Revenue (as Payee |
| 94 | centralSourceCode | `String` | Central Source Code |
| 95 | centralSourceDescription | `String` | Central Source Description |
| 96 | centralSourceGroupCode | `String` | Central Source Group Code |
| 97 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 98 | centralTotalFoodTax | `Float` | Central Total Food Tax |
| 99 | centralTotalFoodTaxGeneratedAsPayee | `Float` | Central Total Food Tax Generated (as Payee |
| 100 | centralTotalNonRevenueTax | `Float` | Central Total Non Revenue Tax |
| 101 | centralTotalNonRevenueTaxAsPayee | `Float` | Central Total Non-Revenue Tax (as Payee |
| 102 | centralTotalOtherTax | `Float` | Central Total Other Tax |
| 103 | centralTotalOtherTaxAsPayee | `Float` | Central Total Other Tax (as Payee |
| 104 | centralTotalPackageRevenue | `Float` | Central Total Package Revenue |
| 105 | centralTotalPackageRevenueAsPayee | `Float` | Central Total Package Revenue (as Payee |
| 106 | centralTotalRevenue | `Float` | Central Total Revenue |
| 107 | centralTotalRevenueAsPayee | `Float` | Central Total Revenue (as Payee |
| 108 | centralTotalRoomTax | `Float` | Central Total Room Tax |
| 109 | centralTotalRoomTaxAsPayee | `Float` | Central Total Room Tax (as Payee |
| 110 | centralTotalTax | `Float` | Central Total Tax |
| 111 | centralTotalTaxAsPayee | `Float` | Central Total Tax (as Payee |
| 112 | centralcurrencyid | `String` | Centralcurrencyid |
| 113 | channelid | `String` | Channelid |
| 114 | children | `Float` | Children |
| 115 | childrenTaxFree | `Float` | Children Tax Free |
| 116 | children1 | `Float` | Children1 |
| 117 | children2 | `Float` | Children2 |
| 118 | children3 | `Float` | Children3 |
| 119 | children4 | `Float` | Children4 |
| 120 | children5 | `Float` | Children5 |
| 121 | city | `String` | City |
| 122 | cityid | `String` | Cityid |
| 123 | compRoomNts | `Float` | Comp Room Nts |
| 124 | compRoomRevenue | `Float` | Comp Room Revenue |
| 125 | companyId | `Float` | Company ID |
| 126 | companyProfileID | `Float` | Company Profile ID |
| 127 | companyProfileName | `String` | Company Profile Name |
| 128 | compflag | `String` | Compflag |
| 129 | complimentaryYN | `String` | Complimentary YN |
| 130 | contactId | `Float` | Contact ID |
| 131 | contactProfileID | `Float` | Contact Profile ID |
| 132 | contactflag | `String` | Contactflag |
| 133 | country | `String` | Country |
| 134 | countryMainGroup | `String` | Country Main Group |
| 135 | countryName | `String` | Country Name |
| 136 | countrygroupid | `String` | Countrygroupid |
| 137 | countryid | `String` | Countryid |
| 138 | cribs | `Float` | Cribs |
| 139 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 140 | dayUsePersons | `Float` | Day Use Persons |
| 141 | dayUseReservations | `Float` | Day Use Reservations |
| 142 | dayUseRooms | `Float` | Day Use Rooms |
| 143 | deletedFlag | `String` | Deleted Flag |
| 144 | departurePersons | `Float` | Departure Persons |
| 145 | departureRooms | `Float` | Departure Rooms |
| 146 | distributedFoodRevenue | `Float` | Distributed Food Revenue |
| 147 | distributedFoodRevenueAsPayee | `Float` | Distributed Food Revenue (as Payee |
| 148 | distributedNonRevenue | `Float` | Distributed Non Revenue |
| 149 | distributedNonRevenueAsPayee | `Float` | Distributed Non-Revenue (as Payee |
| 150 | distributedOtherRevenue | `Float` | Distributed Other Revenue |
| 151 | distributedOtherRevenueAsPayee | `Float` | Distributed Other Revenue (as Payee |
| 152 | distributedRoomRevenue | `Float` | Distributed Room Revenue |
| 153 | distributedRoomRevenueAsPayee | `Float` | Distributed Room Revenue (as Payee |
| 154 | distributedTotalFoodTaxAsPayee | `Float` | Distributed Total Food Tax as Payee |
| 155 | distributedTotalNonRevenueTax | `Float` | Distributed Total Non Revenue Tax |
| 156 | distributedTotalNonRevenueTaxAsPayee | `Float` | Distributed Total Non-Revenue Tax (as Payee |
| 157 | distributedTotalOtherTax | `Float` | Distributed Total Other Tax |
| 158 | distributedTotalOtherTaxAsPayee | `Float` | Distributed Total Other Tax (as Payee |
| 159 | distributedTotalRevenue | `Float` | Distributed Total Revenue |
| 160 | distributedTotalRevenueAsPayee | `Float` | Distributed Total Revenue (as Payee |
| 161 | distributedTotalRoomTax | `Float` | Distributed Total Room Tax |
| 162 | distributedTotalRoomTaxAsPayee | `Float` | Distributed Total Room Tax (as Payee |
| 163 | distributedTotalTax | `Float` | Distributed Total Tax |
| 164 | distributedTotalTaxAsPayee | `Float` | Distributed Total Tax (as Payee |
| 165 | district | `String` | District |
| 166 | dueOutYn | `String` | Due Out Y/N |
| 167 | dueoutflag | `String` | Dueoutflag |
| 168 | endDate | `Date` | End Date |
| 169 | endbusinessdate | `Date` | Endbusinessdate |
| 170 | extendedStayTier | `Float` | Extended stay tier of the reservation on the business date. Based on the length of stay and the rate tier configuration if active or OPERA standard rate tiers. |
| 171 | extraBeds | `Float` | Extra Beds |
| 172 | fiscalregioncode | `String` | Fiscalregioncode |
| 173 | flgdFoodRevenue | `Float` | Flagged Food Revenue |
| 174 | flgdNonRevenue | `Float` | Flagged Non Revenue |
| 175 | flgdOtherRevenue | `Float` | Flagged Other Revenue |
| 176 | flgdRoomRevenue | `Float` | Flagged Room Revenue |
| 177 | flgdTotalFoodTax | `Float` | Flagged Total Food Tax |
| 178 | flgdTotalNonRevenueTax | `Float` | Flagged Total Non Revenue Tax |
| 179 | flgdTotalOtherTax | `Float` | Flagged Total Other Tax |
| 180 | flgdTotalRevenue | `Float` | Flagged Total Revenue |
| 181 | flgdTotalRoomTax | `Float` | Flagged Total Room Tax |
| 182 | flgdTotalTax | `Float` | Flagged Total Tax |
| 183 | foodRevenue | `Float` | Food Revenue |
| 184 | foodRevenueAsPayee | `Float` | Food Revenue (as Payee |
| 185 | freqflyermembtype | `String` | Freqflyermembtype |
| 186 | freqguestmembtype | `String` | Freqguestmembtype |
| 187 | groupId | `Float` | Group ID |
| 188 | groupProfileID | `Float` | Group Profile ID |
| 189 | groupProfileName | `String` | Group Profile Name |
| 190 | guestProfileID | `Float` | Guest Profile ID |
| 191 | gueststatusid | `String` | Gueststatusid |
| 192 | houseUseYn | `String` | House Use Y/N |
| 193 | houseuseflag | `String` | Houseuseflag |
| 194 | insertDate | `DateTime` | Insert Date |
| 195 | internalCompanyprofileid | `Float` | Companyprofileid |
| 196 | internalContactprofileid | `Float` | Contactprofileid |
| 197 | internalDeletedflag | `String` | Deleted Flag |
| 198 | internalGroupprofileid | `Float` | Groupprofileid |
| 199 | internalMembershipid | `Float` | Membershipid |
| 200 | internalReservationNameId | `Float` | Resv Name ID |
| 201 | jRNUpdateDate | `Date` | JRN Update Date |
| 202 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 203 | locationID | `String` | Internal ID to uniquely identify the Property |
| 204 | marketCode | `String` | Market Code |
| 205 | marketDescription | `String` | Market Description |
| 206 | marketDisplaySequence | `Float` | Market Display Sequence |
| 207 | marketGroupCode | `String` | Market Group Code |
| 208 | marketGroupDescription | `String` | Market Group Description |
| 209 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 210 | marketgroupid | `String` | Marketgroupid |
| 211 | marketid | `String` | Marketid |
| 212 | membershipCardNo | `String` | Membership Card Number |
| 213 | membershipId | `Float` | Membership ID |
| 214 | multipleOccupancyRooms | `Float` | Multiple Occupancy Rooms |
| 215 | nationality | `String` | Nationality |
| 216 | nationalityCode | `String` | Nationality Code |
| 217 | nationalityid | `String` | Nationalityid |
| 218 | nights | `Float` | Nights |
| 219 | noShowReservations | `Float` | Number Show Reservations |
| 220 | noShowPersons | `Float` | No-Show Persons |
| 221 | noShowRooms | `Float` | No-Show Rooms |
| 222 | nonRevenue | `Float` | Non Revenue |
| 223 | nonRevenueAsPayee | `Float` | Non-Revenue (as Payee |
| 224 | numberOfStays | `Float` | No of Stays |
| 225 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 226 | originCode | `String` | Origin Code |
| 227 | originDescription | `String` | Origin Description |
| 228 | originalEndDate | `Date` | Original End Date |
| 229 | originalRoomCategory | `String` | Stores the room type associated with the reservation at the moment of booking. |
| 230 | otherRevenue | `Float` | Other Revenue |
| 231 | otherRevenueAsPayee | `Float` | Other Revenue (as Payee |
| 232 | outOfOrderRooms | `Float` | Number of Rooms marked as Out of Order for today |
| 233 | outOfServiceRooms | `Float` | Out of Service Rooms |
| 234 | ownerRentalYn | `String` | Owner Rental Y/N |
| 235 | ownerfriendfamilyflag | `String` | Ownerfriendfamilyflag |
| 236 | ownerrentalflag | `String` | Ownerrentalflag |
| 237 | packageFoodRevenue | `Float` | Package Food Revenue |
| 238 | packageFoodRevenueAsPayee | `Float` | Package Food Revenue (as Payee |
| 239 | packageNonRevenue | `Float` | Package Non Revenue |
| 240 | packageNonRevenueAsPayee | `Float` | Package Non-Revenue (as Payee |
| 241 | packageOtherRevenue | `Float` | Package Other Revenue |
| 242 | packageOtherRevenueAsPayee | `Float` | Package Other Revenue (as Payee |
| 243 | packageRoomRevenue | `Float` | Package Room Revenue |
| 244 | packageRoomRevenueAsPayee | `Float` | Package Room Revenue (as Payee |
| 245 | parentCompanyId | `Float` | Parent Company ID |
| 246 | parentcompanyprofileid | `Float` | Parentcompanyprofileid |
| 247 | physicalQuantity | `Float` | Physical Quantity |
| 248 | physicalRooms | `Float` | Physical Rooms |
| 249 | prAdvTotalFoodTax | `Float` | Pr Advance Total Food Tax |
| 250 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 251 | primaryYn | `Float` | Primary Y/N |
| 252 | primaryflag | `Float` | Primaryflag |
| 253 | profiledailytotalid | `Float` | Profiledailytotalid |
| 254 | profileid | `Float` | Profileid |
| 255 | promotionCode | `String` | Promotion Code |
| 256 | promotionCodeDesc | `String` | Promotion Code Description |
| 257 | promotionid | `String` | Promotionid |
| 258 | property | `String` | Code to uniquely identify the Property |
| 259 | pseudoRoomYN | `String` | Pseudo Room YN |
| 260 | pseudoroomflag | `String` | Pseudoroomflag |
| 261 | quantity | `Float` | Quantity |
| 262 | rateAmount | `Float` | Rate Amount |
| 263 | rateCategory | `String` | Rate Category |
| 264 | rateCode | `String` | Rate Code |
| 265 | ratecategoryid | `String` | Ratecategoryid |
| 266 | ratecodeid | `String` | Ratecodeid |
| 267 | regionCode | `String` | Region Code |
| 268 | regionid | `String` | Regionid |
| 269 | repPromotionCode | `String` | Reporting Promotion Code |
| 270 | repPromotionCodeDescription | `String` | Reporting Promotion Code Desc |
| 271 | reservationArrivals | `Float` | Reservation Arrivals |
| 272 | reservationDate | `Date` | Reservation Date |
| 273 | reservationNameID | `Float` | Reservation Name ID |
| 274 | reservationNights | `Float` | Reservation Nights |
| 275 | reservationNumberOfStays | `Float` | Reservation No of Stays |
| 276 | reservationStatus | `String` | Reservation Status |
| 277 | reservationid | `Float` | Reservationid |
| 278 | resvenddate | `Date` | Resvenddate |
| 279 | resvinsertsource | `String` | Resvinsertsource |
| 280 | resvinsertsourcetype | `String` | Resvinsertsourcetype |
| 281 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 282 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 283 | room | `String` | Room |
| 284 | roomAdults | `Float` | Room Adults |
| 285 | roomCategory | `String` | Room Category |
| 286 | roomChildren | `Float` | Room Children |
| 287 | roomClass | `String` | Room Class |
| 288 | roomNights | `Float` | Room Nights |
| 289 | roomReservationStatus | `String` | Room Reservation Status |
| 290 | roomRevenue | `Float` | Room Revenue |
| 291 | roomRevenueAsPayee | `Float` | Room Revenue (as Payee |
| 292 | roomcategoryid | `String` | Roomcategoryid |
| 293 | roomclassid | `String` | Roomclassid |
| 294 | roomid | `String` | Roomid |
| 295 | rsAdvFoodRevenue | `Float` | Distributed food revenue generated as staying guest. |
| 296 | rsAdvFoodTax | `Float` | Distributed food tax generated as staying guest. |
| 297 | rsAdvNonRevenue | `Float` | Distributed non revenue generated as staying guest. |
| 298 | rsAdvNonRevenueTax | `Float` | Distributed non-revenue tax generated as staying guest |
| 299 | rsAdvOtherRevenue | `Float` | Distributed other revenue generated as staying guest. |
| 300 | rsAdvOtherTax | `Float` | Distributed other tax generated as staying guest. |
| 301 | rsAdvRoomRevenue | `Float` | Distributed room revenue generated as staying guest. |
| 302 | rsAdvRoomTax | `Float` | Distributed room tax generated as staying guest. |
| 303 | rsAdvTotalRevenue | `Float` | Distributed total revenue generated as staying guest. |
| 304 | rsAdvTotalTax | `Float` | Distributed total tax amount generated as staying guest. |
| 305 | singleOccupancyRooms | `Float` | Single Occupancy Rooms |
| 306 | sourceCode | `String` | Source Code |
| 307 | sourceDescription | `String` | Source Description |
| 308 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 309 | sourceGroupCode | `String` | Source Group Code |
| 310 | sourceGroupDescription | `String` | Source Group Description |
| 311 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 312 | sourceProfId | `Float` | Source Prof ID |
| 313 | sourceProfileID | `Float` | Source Profile ID |
| 314 | sourcegroupid | `String` | Sourcegroupid |
| 315 | sourceid | `String` | Sourceid |
| 316 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 317 | stateCode | `String` | State Code |
| 318 | stateid | `String` | Stateid |
| 319 | stayAdults | `Float` | Stay Adults |
| 320 | stayChildren | `Float` | Stay Children |
| 321 | stayPersons | `Float` | Stay Persons |
| 322 | totalFoodTax | `Float` | Total Food Tax |
| 323 | totalFoodTaxGeneratedAsPayee | `Float` | Total Food Tax Generated (as Payee |
| 324 | totalNonRevenueTax | `Float` | Total Non Revenue Tax |
| 325 | totalNonRevenueTaxAsPayee | `Float` | Total Non-Revenue Tax (as Payee |
| 326 | totalOtherTax | `Float` | Total Other Tax |
| 327 | totalOtherTaxAsPayee | `Float` | Total Other Tax (as Payee |
| 328 | totalPackageRevenue | `Float` | Total Package Revenue |
| 329 | totalPackageRevenueAsPayee | `Float` | Total Package Revenue (as Payee |
| 330 | totalRevenue | `Float` | Total Revenue |
| 331 | totalRevenueAsPayee | `Float` | Total Revenue (as Payee |
| 332 | totalRoomTax | `Float` | Total Room Tax |
| 333 | totalRoomTaxAsPayee | `Float` | Total Room Tax (as Payee |
| 334 | totalTax | `Float` | Total Tax |
| 335 | totalTaxAsPayee | `Float` | Total Tax (as Payee |
| 336 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 337 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 338 | updateDate | `DateTime` | Update Date |
| 339 | upsoldRevenue | `Float` | Upsold Revenue |
| 340 | vIPStatus | `String` | VIP Status |
| 341 | walkinYn | `String` | Walkin Y/N |
| 342 | walkinflag | `String` | Walkinflag |
| 343 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### ProfilesAccountsSaleProfileOwnerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountOwner | `String` | Account Owner |
| 2 | accountOwnerCode | `String` | Account Owner Code |
| 3 | accountOwnerEmail | `String` | Account Owner Email |
| 4 | accountOwnerPhone | `String` | Phone no. |
| 5 | accountOwnerTitle | `String` | Account Owner Title |
| 6 | accountSrepCode | `String` | Account Srep Code |
| 7 | centralAccountOwnerTitle | `String` | Central Account Owner Title |
| 8 | chainCode | `String` | Chain Code |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | inactiveDate | `Date` | Inactive Date |
| 13 | inactiveFlag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalOrganizationId | `Float` | Organization ID |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | laptopChange | `Float` | Laptop Change |
| 20 | locationId | `String` | Location ID |
| 21 | nameId | `Float` | Name ID |
| 22 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 23 | ownerProfileId | `Float` | Owner Profile ID |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | primaryYN | `String` | Primary YN |
| 26 | property | `String` | Indicates if the value set for the specific property. |
| 27 | relationship | `String` | Relationship |
| 28 | relationshipid | `String` | Relationshipid |
| 29 | resort | `String` | Property |
| 30 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 31 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 32 | saleProfileOwnerId | `Float` | Sale Profile Owner ID |
| 33 | toType | `String` | To Type |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |
| 36 | userId | `Float` | User ID |

[⬆ Back to Query](#query)

---

### ProfilesAccountsBlockDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionId | `Float` | Action ID |
| 2 | actualAverageRoomRate | `Float` | Actual Average Room Rate |
| 3 | actualFBRevenue | `Float` | Actual F&B Revenue |
| 4 | actualOtherRevenue | `Float` | Other revenue |
| 5 | actualRoomNightsSold | `Float` | Actual Room Nights Sold |
| 6 | actualRoomRevenue | `Float` | Actual revenue of the room |
| 7 | addInfo | `String` | Add Info |
| 8 | agentContactNameId | `Float` | Agent Contact Name ID |
| 9 | agentNameId | `Float` | Agent Name ID |
| 10 | agentprofileid | `Float` | Agentprofileid |
| 11 | allAliases | `String` | All Aliases |
| 12 | allBlockOwners | `String` | All Block Owners |
| 13 | allCateringOwners | `String` | All Catering Owners |
| 14 | allCompanyContacts | `String` | All Company Contacts |
| 15 | allRateCodes | `String` | All Rate Codes |
| 16 | allRoomOwners | `String` | All Room Owners |
| 17 | allRoomPools | `String` | All Room Pools |
| 18 | allRoomTypes | `String` | All Room Types |
| 19 | allSourceContacts | `String` | All Source Contacts |
| 20 | allTravelAgentContacts | `String` | All Travel Agent Contacts |
| 21 | allotmentOrigin | `String` | Allotment Origin |
| 22 | allotmentType | `String` | Type of Block alloted for the group. |
| 23 | allotmentcurrencyid | `String` | Allotmentcurrencyid |
| 24 | allotmentid | `Float` | Block ID |
| 25 | allowPickup | `String` | Allow a pickup for a group with this booking status |
| 26 | alternateBlockName | `String` | Multi Byte Description Field |
| 27 | alternateDates | `String` | Alternate Dates |
| 28 | arrivalTime | `DateTime` | Arrival Time |
| 29 | attachmentURL | `String` | URL pointing to Lead Attachments. |
| 30 | attendeesGuaranteed | `Float` | Attendees Guaranteed |
| 31 | autoLoadForecastYn | `String` | Indicates if forecast figures should be automatically loaded for this business block. |
| 32 | averageRate | `Float` | Average Rate |
| 33 | bEOLastPrint | `DateTime` | Date when the BEO report was last printed for this business block. |
| 34 | beginDateOriginal | `Date` | Stores the original block begin date. Any date ealier will be treated as a Shoulder date. |
| 35 | blockAlias | `String` | Block Alias |
| 36 | blockCode | `String` | Block Code |
| 37 | blockDateActual | `Date` | Block Date Actual |
| 38 | blockDateDefinite | `DateTime` | Block Date Definite |
| 39 | blockDateProspect | `DateTime` | Block Date Prospect |
| 40 | blockDateTentative | `DateTime` | Block Date Tentative |
| 41 | blockDescription | `String` | Block Description |
| 42 | blockID | `Float` | Block ID |
| 43 | blockMode | `String` | Classifies this allotment record: MASTER_ALLOCATION SUB_ALLOCATION SUB_BOOKING SUB_TOUR SUB_ITINERARY |
| 44 | blockOwnerCode | `String` | Block Owner Code |
| 45 | blockOwnerFullName | `String` | Block Owner Full Name |
| 46 | blockPackage | `String` | Block Package |
| 47 | blockPackageDescription | `String` | Block Package Description |
| 48 | blockStatus | `String` | Block Status |
| 49 | blockStatusDescription | `String` | Block Status Description |
| 50 | blockTypeCode | `String` | Block Type Code |
| 51 | blockTypeCodeDescription | `String` | Block Type Code Description |
| 52 | blockpackageid | `String` | Blockpackageid |
| 53 | bookingId | `String` | External S&C vendor booking ID and used in HYATT-mode. |
| 54 | bookingMethodOrderBy | `Float` | Booking Method Order By |
| 55 | bookingStatusOrder | `Float` | Booking Status Order |
| 56 | bookingType | `String` | Determines block being [G] - Group or [W] - Wholesale. |
| 57 | bookingTypeDescription | `String` | Booking Type Description |
| 58 | bookingmethodInactiveDate | `Date` | Bookingmethod Inactive Date |
| 59 | bookingsourceid | `String` | Bookingsourceid |
| 60 | bookingstatusid | `String` | Bookingstatusid |
| 61 | bookingtypeid | `String` | Bookingtypeid |
| 62 | breakfastDescription | `String` | Breakfast Description |
| 63 | breakfastInclPrice | `Float` | PCR: The estimated breakfast price for this ratecode. |
| 64 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 65 | breakfastIncluded | `String` | Breakfast Included |
| 66 | breakfastPrice | `Float` | Breakfast Price |
| 67 | bwiLeadId | `String` | BWI eLeadID for tracking purposes. |
| 68 | bwiUrl | `String` | URL populated bu CRS. |
| 69 | cBreakfastInclPrice | `Float` | Central Bfst Incl Price |
| 70 | cBreakfastPrice | `Float` | Central Bfst Price |
| 71 | cCompRoomValue | `Float` | Central Comp Room Value |
| 72 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 73 | cExchangeDate | `Date` | Central Xchange Date |
| 74 | cExchangeRate | `Float` | Central Xchange Rate |
| 75 | cFBCommission1 | `Float` | Central Fb Commission 1 |
| 76 | cFBCommission2 | `Float` | Central Fb Commission 2 |
| 77 | cPorteragePrice | `Float` | Central Porterage Price |
| 78 | cRoomCommission1 | `Float` | Central Rm Commission 1 |
| 79 | cRoomCommission2 | `Float` | Central Rm Commission 2 |
| 80 | cServiceCharge | `Float` | Central Service Charge |
| 81 | cServiceFee | `Float` | Central Service Fee |
| 82 | cRSGtdYn | `String` | CRS Guaranteed Y/N |
| 83 | cancelRule | `String` | Not Used |
| 84 | canceldestinationid | `String` | Canceldestinationid |
| 85 | cancellationDestination | `String` | Cancellation Destination |
| 86 | cancellationDestinationDescription | `String` | Cancellation Destination Description |
| 87 | cancellationNumber | `Float` | Cancellation Number |
| 88 | cancellationPenaltyAmount | `Float` | Cancellation Penalty Amount |
| 89 | cancellationreasonid | `String` | Cancellationreasonid |
| 90 | catCutoff | `Date` | Catering Cutoff |
| 91 | catDateProspect | `DateTime` | Cat Date Prospect |
| 92 | catOwner | `Float` | Catering Owner |
| 93 | catOwnerProperty | `String` | Property of Catering Owner |
| 94 | catReturnToInventory | `String` | Cat Return To Inventory |
| 95 | catStartingStatus | `String` | Cat Starting Status |
| 96 | catcurrencyid | `String` | Catcurrencyid |
| 97 | cateringCancellationDate | `Date` | Catering Cancellation Date |
| 98 | cateringCancellationDescription | `String` | Catering Cancellation Description |
| 99 | cateringCancellationNumber | `Float` | Catering Cancellation Number |
| 100 | cateringCancellationReason | `String` | Catering Cancellation Reason |
| 101 | cateringCurrency | `String` | Catering Currency |
| 102 | cateringDateActual | `Date` | Catering Date Actual |
| 103 | cateringDecisionDate | `Date` | Catering Decision Date |
| 104 | cateringDeductInventory | `String` | Catering Deduct Inventory |
| 105 | cateringExchangeRate | `Float` | Catering Exchange Rate |
| 106 | cateringFollowupDate | `Date` | Catering Followup Date |
| 107 | cateringOnlyYN | `String` | Catering only Revenue. |
| 108 | cateringOrderBy | `Float` | Catering Order By |
| 109 | cateringOwnerCode | `String` | Catering Owner Code |
| 110 | cateringOwnerFullName | `String` | Catering Owner Full Name |
| 111 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 112 | cateringQuoteCurrency | `String` | Catering Quote Currency |
| 113 | cateringStatus | `String` | Catering Status |
| 114 | cateringStatusColor | `String` | Catering Status Color |
| 115 | cateringStatusDescription | `String` | Catering Status Description |
| 116 | cateringStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 117 | cateringcancelreasonid | `Float` | Cateringcancelreasonid |
| 118 | cateringcurrencyid | `String` | Cateringcurrencyid |
| 119 | cateringowneremployeeid | `Float` | Catering Owner Employee ID |
| 120 | cateringquotecurrencyid | `String` | Catering Quote Currency ID |
| 121 | cateringstatusid | `String` | Cateringstatusid |
| 122 | cenralFBRevenue | `Float` | Cenral FB Revenue |
| 123 | centralActualAverageRoomRate | `Float` | Central Actual Average Room Rate |
| 124 | centralActualFBRevenue | `Float` | Central Actual FB Revenue |
| 125 | centralActualOtherRevenue | `Float` | Central Actual Other Revenue |
| 126 | centralActualRoomRevenue | `Float` | Central Actual Room Revenue |
| 127 | centralAverageRoomRate | `Float` | Central Average Room Rate |
| 128 | centralBlockPackage | `String` | Central Block Package |
| 129 | centralBlockPackageDescription | `String` | Central Block Package Description |
| 130 | centralBlockStatus | `String` | Central Block Status |
| 131 | centralBlockStatusDescription | `String` | Central Block Status Description |
| 132 | centralBlockTypeCode | `String` | Central Block Type Code |
| 133 | centralBlockTypeCodeDescription | `String` | Central Block Type Code Description |
| 134 | centralBookingType | `String` | Central Booking Type |
| 135 | centralBookingTypeDescription | `String` | Central Booking Type Description |
| 136 | centralCancellationDestination | `String` | Central Cancellation Destination |
| 137 | centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| 138 | centralCancellationPenaltyAmount | `Float` | Central Cancellation Penalty Amount |
| 139 | centralCateringStatus | `String` | Central Catering Status |
| 140 | centralCateringStatusDescription | `String` | Central Catering Status Description |
| 141 | centralConversionCode | `String` | Central Conversion Code |
| 142 | centralCoversionCodeDescription | `String` | Central Coversion Code Description |
| 143 | centralIndustryCode | `String` | Central Industry Code |
| 144 | centralIndustryCodeDescription | `String` | Central Industry Code Description |
| 145 | centralItemsForThisBlock | `String` | Central Items for this Block |
| 146 | centralMarketDescription | `String` | Central Market Description |
| 147 | centralMarketCode | `String` | Central Market code |
| 148 | centralMeetingBudget | `Float` | Central Meeting Budget |
| 149 | centralMeetingRevenue | `Float` | Central Meeting Revenue |
| 150 | centralOriginCode | `String` | Central Origin Code |
| 151 | centralOriginCodeDescription | `String` | Central Origin Code Description |
| 152 | centralOtherRevenue | `Float` | Central Other Revenue |
| 153 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 154 | centralPayment | `String` | Central Payment |
| 155 | centralPaymentDescription | `String` | Central Payment Description |
| 156 | centralRankingCode | `String` | Central Ranking Code |
| 157 | centralRankingCodeDescription | `String` | Central Ranking Code Description |
| 158 | centralReservationMethodCode | `String` | Central Reservation Method Code |
| 159 | centralReservationMethodDescription | `String` | Central Reservation Method Description |
| 160 | centralReservationType | `String` | Central Reservation Type |
| 161 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 162 | centralRoomRevenue | `Float` | Central Room Revenue |
| 163 | centralSourceCode | `String` | Central Source Code |
| 164 | centralSourceCodeDescription | `String` | Central Source Code Description |
| 165 | centralTaxAmount | `Float` | Central Tax Amount |
| 166 | chainCode | `String` | Chain Code |
| 167 | channelid | `String` | Channelid |
| 168 | code | `String` | Code |
| 169 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 170 | comAddress2 | `String` | Communication Address for Contact 2 (E-mail / Fax #) |
| 171 | comAddress3 | `String` | Communication Address for Contact 3 (E-mail / Fax #) |
| 172 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 173 | comMethod2 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 174 | comMethod3 | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT|DATA] |
| 175 | commissionAmount | `String` | Commission Amount |
| 176 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 177 | commissionableYn | `String` | Commissionable Y/N |
| 178 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 179 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 180 | compRooms | `Float` | Number of complimentary Rooms |
| 181 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 182 | companyAll | `String` | Company All |
| 183 | companyNameId | `Float` | Company Name ID |
| 184 | companyprofileid | `Float` | Companyprofileid |
| 185 | competition | `String` | Competition |
| 186 | contactNameId | `Float` | Contact Name ID |
| 187 | contactprofileid | `Float` | Contactprofileid |
| 188 | contractNumber | `String` | Contract Number |
| 189 | controlBlockLocally | `String` | Control Block Y/N |
| 190 | conversionCode | `String` | Conversion Code |
| 191 | coversionCodeDescription | `String` | Coversion Code Description |
| 192 | createdBy | `String` | The name of the user who created the record. |
| 193 | createdDate | `DateTime` | Created Date |
| 194 | createdAsOpportunityYN | `String` | Indicates if the block was created as an Opportunity |
| 195 | creditCardId | `Float` | Credit Card ID |
| 196 | currency | `String` | Currency |
| 197 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 198 | dateAcl | `Date` | Date Acl |
| 199 | dateCfl | `Date` | Date Cfl |
| 200 | dateDefinite | `DateTime` | Date Definite |
| 201 | dateLsl | `Date` | Date Lsl |
| 202 | dateOpenedForPickup | `Date` | Date Opened for Pickup |
| 203 | datePel | `DateTime` | Date Pel |
| 204 | dateTdl | `DateTime` | Date Tdl |
| 205 | dateTentative | `DateTime` | Date Tentative |
| 206 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 207 | deductInventory | `String` | Deduct the reservations with this booking status from the inventory |
| 208 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 209 | deletedflag | `String` | Deleted Flag |
| 210 | departureTime | `DateTime` | Departure Time |
| 211 | description | `String` | Description |
| 212 | distributed | `String` | Distributed |
| 213 | distributedDate | `DateTime` | Timestamp of the last date/time the distributed_yn flag was set to Y. |
| 214 | dmlSeqNumber | `Float` | Dml Sequence No |
| 215 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 216 | downloadDate | `Date` | Download Date |
| 217 | downloadResort | `String` | Download Property |
| 218 | downloadSrep | `Float` | Download Srep |
| 219 | dueDate | `Date` | Due Date |
| 220 | dueDateOrd | `Date` | Due Date Sorting Column. |
| 221 | endDate | `Date` | End Date |
| 222 | endDateOriginal | `Date` | Stores the original block End date.  Any date later will be treated as a Shoulder date. |
| 223 | endbusinessdate | `Date` | Endbusinessdate |
| 224 | eventAttendees | `Float` | Event Attendees |
| 225 | exchangePostingType | `String` | Exchange Posting Type |
| 226 | exchangeRate | `Float` | Exchange Rate |
| 227 | exclusionMessage | `String` | The message that will pop up if the block is excluded (not allowed) to modify/create reservation/cancel reservation. |
| 228 | externalReference | `String` | External Reference |
| 229 | externalRfpId | `String` | External RFP ID. |
| 230 | externalRfpSystem | `String` | External RFP System Identification Code. |
| 231 | externallyLocked | `String` | Externally Locked |
| 232 | fBRevenue | `Float` | Projected F&B Revenue. |
| 233 | fbAgendaCurrency | `String` | Currency code for the F&B Agendas attached to the business block. |
| 234 | fbCommission1 | `Float` | stores FB commission for Agent 1 |
| 235 | fbCommission2 | `Float` | stores FB commission for Agent 2 |
| 236 | fitContractMode | `String` | Operation Mode for FIT Contracts [ SFA=SFA control RC=Ratecode RA=RateAmounts ] |
| 237 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 238 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 239 | fitdiscounttype | `String` | Fitdiscounttype |
| 240 | flatRateYn | `String` | Determines if rate check is done for Occ1 or Occ1 and Additional Rate. |
| 241 | followupDate | `Date` | Followup Date |
| 242 | fsOverbookingYn | `String` | Can the Function space booked under master allocation or master block be overbooked by sub-allocations or sub-blocks ? |
| 243 | functionType | `String` | Function Type |
| 244 | giid | `String` | Group IATA Number. |
| 245 | greekContractNr | `String` | Greek Contract Number. |
| 246 | groupAccountID | `Float` | Group Account ID |
| 247 | guaranteecodeid | `String` | Guaranteecodeid |
| 248 | guaranteedRate | `String` | Rate Guaranteed Y/N. |
| 249 | guaranteedYN | `String` | Guaranteed YN |
| 250 | hideacctinfoflag | `String` | Hideacctinfoflag |
| 251 | hlxCanxNoticeDays | `Float` | SCH Mode: Number of days before the arrival date a reservation can be canceled without losing the deposit. |
| 252 | hlxCommissionableYn | `String` | SCH Mode: Determines if Travel Agent commission will be paid on reservations booked through the HOLIDEX Plus TACP program. |
| 253 | hlxDdSecuredYn | `String` | SCH Mode: All Description DD Secured. |
| 254 | hlxDepositDays | `Float` | SCH Mode: Number of Days Deposit due to guarantee the guest booking. |
| 255 | hlxDiSecuredYn | `String` | SCH Mode: Secured from DI Display. |
| 256 | hlxHousinginfoSecuredYn | `String` | SCH Mode: Housing Information Secured. |
| 257 | hlxRateAllSecuredYn | `String` | SCH Mode: Rates Secured from All Displays |
| 258 | hlxRatesGnrSecuredYn | `String` | SCH Mode: Rates Secured from GNR. |
| 259 | hlxReturnEachDayYn | `String` | SCH Mode: Return One Day at a time. |
| 260 | inactiveDate | `Date` | Inactive Date |
| 261 | inactiveflag | `String` | Inactive Flag |
| 262 | industryCode | `String` | Indicates the Non-Compete code of a block. |
| 263 | industryCodeDescription | `String` | Industry Code Description |
| 264 | info | `String` | Not Used |
| 265 | informationBoard | `String` | Information Board |
| 266 | insertUser | `Float` | Insert User |
| 267 | inventoryControl | `String` | Inventory Control |
| 268 | inventoryCutOffDate | `Date` | Inventory Cut-Off Date |
| 269 | inventoryCutOffDays | `Float` | Inventory Cut-Off Days |
| 270 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 271 | items | `String` | Items |
| 272 | itemsForThisBlock | `String` | Items for this Block |
| 273 | jRNUpdateDate | `Date` | JRN Update Date |
| 274 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 275 | keepLeadControlYN | `String` | If set to ?Y? lead will not be converted to booking upon lead sending. |
| 276 | laptopChange | `Float` | Laptop Change |
| 277 | leadOrigin | `String` | Lead Origin |
| 278 | leadSentYN | `String` | Lead Sent YN |
| 279 | leadSource | `String` | Lead Source |
| 280 | leadType | `String` | Lead Type |
| 281 | leadchangeBypropertyYn | `String` | Indication that the Property has updated the Lead Information will prevent further SFA updates. |
| 282 | leaderrorflag | `String` | Leaderrorflag |
| 283 | leadisnewflag | `String` | Leadisnewflag |
| 284 | leadoriginid | `String` | Leadoriginid |
| 285 | leadreceivedflag | `String` | Leadreceivedflag |
| 286 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 287 | leadsend2 | `String` | Name of Contact 2 (Free text or from RESORT_CONTACTS) |
| 288 | leadsend3 | `String` | Name of Contact 3 (Free text or from RESORT_CONTACTS) |
| 289 | leadserverpendingflag | `String` | Leadserverpendingflag |
| 290 | leadsourceid | `String` | Leadsourceid |
| 291 | leadstatus | `String` | Leadstatus |
| 292 | linkDate | `Date` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 293 | locationID | `String` | Internal ID to uniquely identify the Property |
| 294 | lostTo | `String` | Competitor to whom the booking was lost. |
| 295 | mainmarket | `String` | Mainmarket |
| 296 | mainmarketid | `String` | Mainmarketid |
| 297 | manuallyCutoffYN | `String` | Block was cutoff manullay |
| 298 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 299 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 300 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 301 | marketCode | `String` | Market  Code |
| 302 | marketDescription | `String` | Market Description |
| 303 | marketid | `String` | Marketid |
| 304 | masterBlockID | `Float` | Parent Block ID |
| 305 | masterBlockProperty | `String` | Parent Resort |
| 306 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 307 | meetingBudget | `Float` | Meeting Budget |
| 308 | meetingRevenue | `Float` | Meeting Revenue for SFA |
| 309 | offsetType | `String` | Offset Type |
| 310 | orderBy | `Float` | Order By |
| 311 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 312 | origAllotmentHeaderId | `Float` | Stores the original ALLOTMENT_HEADER_ID prior to a migration. |
| 313 | originCode | `String` | Origin Code |
| 314 | originCodeDescription | `String` | Origin Code Description |
| 315 | originalBeginDateHolidex | `Date` | Original Block Start Date used as identifier in the HOLIDEX interface. |
| 316 | originalEndDate | `Date` | Original End Date |
| 317 | originalRateCode | `String` | Not used |
| 318 | originalStartDate | `Date` | Original Start Date |
| 319 | originalratecodeid | `String` | Originalratecodeid |
| 320 | ormsBlockClass | `String` | ORMS Block Class |
| 321 | ormsFinalBlock | `String` | ORMS Final Block |
| 322 | ormsForecastReviewReason | `String` | Reason for which a review of the ORMS forecast is required. If the value is null it means forecast has been reviewed. If the value is Forecast increased (FI) Forecast decreased (FD) Blocked Rooms increased (BRI)  Blocked Rooms decreased (BRD)   New block (NB) User required review (URR) then it means forecast has not been reviewed. |
| 323 | ormsTransientBlock | `String` | ORMS Transient Block |
| 324 | otherRevenue | `Float` | Projected Other Revenue. |
| 325 | owner | `Float` | Owner |
| 326 | ownerResort | `String` | Owner Property |
| 327 | owneremployeeid | `Float` | Owneremployeeid |
| 328 | ownerlocationd | `String` | Ownerlocationd |
| 329 | parentallotmentid | `Float` | Parentallotmentid |
| 330 | payment | `String` | Payment |
| 331 | paymentDescription | `String` | Payment Description |
| 332 | paymentmethodid | `String` | Paymentmethodid |
| 333 | personsPerRoom | `Float` | Persons Per Room |
| 334 | porterageIncluded | `String` | Porterage Included |
| 335 | porteragePrice | `Float` | Porterage Price |
| 336 | potAverageRoomRate | `Float` | Pot Average Room Rate |
| 337 | potFbRevenue1 | `Float` | Pot FB Revenue1 |
| 338 | potOtherRevenue1 | `Float` | Pot Other Revenue1 |
| 339 | potRoomNights | `Float` | Projected Room Nights. |
| 340 | potRoomRevenue1 | `Float` | Pot Room Revenue1 |
| 341 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 342 | printRate | `String` | Print Rate |
| 343 | profileId | `Float` | Profile ID |
| 344 | program | `String` | Program |
| 345 | property | `String` | Code to uniquely identify the Property |
| 346 | proposalCombineEventsYn | `String` | Indicates if events in webProposal should be combined in the generated XML. |
| 347 | proposalDecisionSelection | `String` | Decision Date Selection: [R]ooms Decision Date /  [C]atering Decision Date. |
| 348 | proposalFollowupSelection | `String` | Stores the user choice for either [R]ooms or [C]atering follow-up date to be passed to webProposal. NULL is treated as Rooms follow-up date. |
| 349 | proposalInclAltNamesYn | `String` | If Y then Alternate Names will be used in the webProposal XML tags for <BOOKING_NAME> <ACC_NAME> <CON_FIRST_NAME> and <CON_LAST_NAME>. |
| 350 | proposalOwnerSelection | `String` | Owner Selection: [O]verall Owner /  [R]ooms Owner /  [C]atering Owner. |
| 351 | proposalSentDate | `DateTime` | Proposal Sent Date |
| 352 | proposalShowEventpriceYn | `String` | Show price per event on webProposal. |
| 353 | proposalShowPmsRoomTypeYn | `String` | Show PMS roomtypes on webProposal otherwise S&C roomtypes are shown. |
| 354 | proposalShowSpacenameYn | `String` | Show function space names on webProposal. |
| 355 | proposalSpaceMeasurement | `String` | Unit of measurement used for function spaces in webProposal XML. Possible values: METRIC IMPERIAL or NONE. |
| 356 | proposalViewToken | `String` | Proposal View Token |
| 357 | publishRatesYn | `String` | Indicates that negotiated rates need to be published. |
| 358 | rankingCode | `String` | Indicates the ranking of a block. |
| 359 | rankingCodeDescription | `String` | Ranking Code Description |
| 360 | rateCode | `String` | Rate Code |
| 361 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 362 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 363 | rateProtect | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 364 | rateTier | `Float` | Rate Tier |
| 365 | ratecodeid | `String` | Ratecodeid |
| 366 | readyForDistribution | `String` | Ready for Distribution |
| 367 | regeneratedLeadYn | `String` | Indicates if a lead has been regenerated (copied and lost) by the system and differentiates between leads that have been lost by the user or due to changes to the lead master. |
| 368 | repBookingmethodOrderby | `Float` | Rep Bookingmethod Orderby |
| 369 | repBsOrderBy | `Float` | Rep Bs Order By |
| 370 | repCatOrderBy | `Float` | Rep Cat Order By |
| 371 | replDate | `DateTime` | Reply Date |
| 372 | replVia | `String` | Reply Communication Method |
| 373 | replstatus | `String` | Lead Replystatus [ACL|TDL] |
| 374 | replyBy | `Float` | Reply By |
| 375 | representative | `String` | Representative |
| 376 | reservationMethod | `String` | Reservation Method |
| 377 | reservationType | `String` | Reservation Type |
| 378 | reservationTypeDescription | `String` | The Description of the Guarantee code. |
| 379 | reservationid | `Float` | Reservationid |
| 380 | reserveInventoryYN | `String` | Reserve Inventory YN |
| 381 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 382 | resourceDiscountPercent | `Float` | Default discount percentage applied to catering items. |
| 383 | respTime | `Float` | Response Time. |
| 384 | respTimeCode | `String` | The unit of time (from UNIT_OF_TIME table). |
| 385 | returnToInventory | `String` | Return the reservations with this booking status from the inventory |
| 386 | rivMarketSegment | `String` | Not used |
| 387 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 388 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 389 | roomCommission1 | `Float` | stores Rooms commission for Agent 1 |
| 390 | roomCommission2 | `Float` | stores Rooms commission for Agent 2 |
| 391 | roomNightsSold | `Float` | Room Nights Sold |
| 392 | roomOwnerCode | `String` | Room Owner Code |
| 393 | roomOwnerFullName | `String` | Room Owner Full Name |
| 394 | roomRevenue | `Float` | Projected Room Revenue. |
| 395 | roomRevenueTransactionCode | `String` | Transaction Code for posting room revenue from blocked reservations. |
| 396 | roomStatus | `String` | Room Status |
| 397 | roomingListDue | `Date` | Rooming List Due |
| 398 | roomingListRules | `String` | Stores Rooming List Rules. |
| 399 | roomsCancellationDate | `Date` | Rooms Cancellation Date |
| 400 | roomsCancellationReason | `String` | Rooms Cancellation Reason |
| 401 | roomsCancellationReasonDescription | `String` | Rooms Cancellation Reason Description |
| 402 | roomsCurrency | `String` | Rooms Currency |
| 403 | roomsDecisionDate | `Date` | Rooms Decision Date |
| 404 | roomsExchangeRate | `Float` | Rooms Exchange Rate |
| 405 | roomsOwner | `Float` | Rooms Owner |
| 406 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 407 | roomsPerDay | `Float` | Rooms Per Day |
| 408 | roomsQuoteCurrency | `String` | Rooms Quote Currency |
| 409 | roomsowneremployeeid | `Float` | Roomsowneremployeeid |
| 410 | salesId | `String` | Not used |
| 411 | sbegindate | `Date` | Sbegindate |
| 412 | scQuoteId | `String` | Quote ID reference for the last printed catering quote report (S&C Quotation Report). |
| 413 | sellThruYn | `String` | Sell Thru Indicator. |
| 414 | sendToCentralYn | `String` | Identifies if a business block needs to be send to Central based on KEY_PROFILE_YN in NAME. |
| 415 | senddate | `Date` | Senddate |
| 416 | sentBy | `Float` | Sent By |
| 417 | sentDate | `DateTime` | Sent Date |
| 418 | sentVia | `String` | Sent Via |
| 419 | serviceCharge | `Float` | Service Charge |
| 420 | serviceFee | `Float` | Service Fee Amount per room/night |
| 421 | serviceFeeYn | `String` | Service Fee applies? |
| 422 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 423 | servicePerc | `Float` | Service Percentage included. |
| 424 | shoulderEnd | `Date` | Shoulder End |
| 425 | shoulderStart | `Date` | Shoulder Start |
| 426 | showRateAmountYN | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 427 | snapshotSetup | `String` | Snapshot has been created |
| 428 | sourceCode | `String` | Source Code |
| 429 | sourceCodeDescription | `String` | Source Code Description |
| 430 | sourceContactAll | `String` | Source Contact All |
| 431 | sourceNameId | `Float` | Source Name ID |
| 432 | sourceid | `Float` | Sourceid |
| 433 | sourceprofprofileid | `Float` | Sourceprofprofileid |
| 434 | startDate | `Date` | Start Date |
| 435 | startingStatus | `String` | Booking starting status (intial pickup) |
| 436 | status | `String` | Status |
| 437 | statusColor | `String` | Status Color |
| 438 | statusType | `String` | Type of booking status (initial) |
| 439 | subAllocationYN | `String` | Sub Allocation YN |
| 440 | superSearchIndexText | `String` | Super Search Index Text |
| 441 | suppressRate | `String` | Suppress Rate |
| 442 | syncContractYn | `String` | Indicates if original grid will be copied to contract grid. Performed in the allotment_detail trigger. |
| 443 | synchronize | `String` | Synchronize Sub-Blocks with Master Block if  Y |
| 444 | taxAmount | `Float` | Tax Amount |
| 445 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 446 | taxIncludedYn | `String` | Tax is included in this rate. |
| 447 | taxType | `String` | Tax Type |
| 448 | taxtypeid | `String` | Taxtypeid |
| 449 | tbdRates | `String` | To be Determined Rates |
| 450 | tdlReason | `String` | Tdl Reason |
| 451 | tentativeLevel | `Float` | Not used |
| 452 | tlpResponseid | `String` | Stores the TLPe - Response ID |
| 453 | tlpUrl | `String` | Stores the TLPe - Result URL. |
| 454 | tourCode | `String` | Tour Code. |
| 455 | traceCode | `String` | Trace Code |
| 456 | traceDescription | `String` | Trace Description |
| 457 | trackChangesYN | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 458 | travelAgentAll | `String` | Travel Agent All |
| 459 | travelAgentRecordLocator | `String` | Travel Agent Record Locator |
| 460 | turndownreasonid | `Float` | Turndownreasonid |
| 461 | uDFC01 | `String` | UDFC01 |
| 462 | uDFC02 | `String` | UDFC02 |
| 463 | uDFC03 | `String` | UDFC03 |
| 464 | uDFC04 | `String` | UDFC04 |
| 465 | uDFC05 | `String` | UDFC05 |
| 466 | uDFC06 | `String` | UDFC06 |
| 467 | uDFC07 | `String` | UDFC07 |
| 468 | uDFC08 | `String` | UDFC08 |
| 469 | uDFC09 | `String` | UDFC09 |
| 470 | uDFC10 | `String` | UDFC10 |
| 471 | uDFC11 | `String` | UDFC11 |
| 472 | uDFC12 | `String` | UDFC12 |
| 473 | uDFC13 | `String` | UDFC13 |
| 474 | uDFC14 | `String` | UDFC14 |
| 475 | uDFC15 | `String` | UDFC15 |
| 476 | uDFC16 | `String` | UDFC16 |
| 477 | uDFC17 | `String` | UDFC17 |
| 478 | uDFC18 | `String` | UDFC18 |
| 479 | uDFC19 | `String` | UDFC19 |
| 480 | uDFC20 | `String` | UDFC20 |
| 481 | uDFC21 | `String` | UDFC21 |
| 482 | uDFC22 | `String` | UDFC22 |
| 483 | uDFC23 | `String` | UDFC23 |
| 484 | uDFC24 | `String` | UDFC24 |
| 485 | uDFC25 | `String` | UDFC25 |
| 486 | uDFC26 | `String` | UDFC26 |
| 487 | uDFC27 | `String` | UDFC27 |
| 488 | uDFC28 | `String` | UDFC28 |
| 489 | uDFC29 | `String` | UDFC29 |
| 490 | uDFC30 | `String` | UDFC30 |
| 491 | uDFC31 | `String` | UDFC31 |
| 492 | uDFC32 | `String` | UDFC32 |
| 493 | uDFC33 | `String` | UDFC33 |
| 494 | uDFC34 | `String` | UDFC34 |
| 495 | uDFC35 | `String` | UDFC35 |
| 496 | uDFC36 | `String` | UDFC36 |
| 497 | uDFC37 | `String` | UDFC37 |
| 498 | uDFC38 | `String` | UDFC38 |
| 499 | uDFC39 | `String` | UDFC39 |
| 500 | uDFC40 | `String` | UDFC40 |
| 501 | uDFD01 | `Date` | UDFD01 |
| 502 | uDFD02 | `Date` | UDFD02 |
| 503 | uDFD03 | `Date` | UDFD03 |
| 504 | uDFD04 | `Date` | UDFD04 |
| 505 | uDFD05 | `Date` | UDFD05 |
| 506 | uDFD06 | `Date` | UDFD06 |
| 507 | uDFD07 | `Date` | UDFD07 |
| 508 | uDFD08 | `Date` | UDFD08 |
| 509 | uDFD09 | `Date` | UDFD09 |
| 510 | uDFD10 | `Date` | UDFD10 |
| 511 | uDFD11 | `Date` | UDFD11 |
| 512 | uDFD12 | `Date` | UDFD12 |
| 513 | uDFD13 | `Date` | UDFD13 |
| 514 | uDFD14 | `Date` | UDFD14 |
| 515 | uDFD15 | `Date` | UDFD15 |
| 516 | uDFD16 | `Date` | UDFD16 |
| 517 | uDFD17 | `Date` | UDFD17 |
| 518 | uDFD18 | `Date` | UDFD18 |
| 519 | uDFD19 | `Date` | UDFD19 |
| 520 | uDFD20 | `Date` | UDFD20 |
| 521 | uDFN01 | `Float` | UDFN01 |
| 522 | uDFN02 | `Float` | UDFN02 |
| 523 | uDFN03 | `Float` | UDFN03 |
| 524 | uDFN04 | `Float` | UDFN04 |
| 525 | uDFN05 | `Float` | UDFN05 |
| 526 | uDFN06 | `Float` | UDFN06 |
| 527 | uDFN07 | `Float` | UDFN07 |
| 528 | uDFN08 | `Float` | UDFN08 |
| 529 | uDFN09 | `Float` | UDFN09 |
| 530 | uDFN10 | `Float` | UDFN10 |
| 531 | uDFN11 | `Float` | UDFN11 |
| 532 | uDFN12 | `Float` | UDFN12 |
| 533 | uDFN13 | `Float` | UDFN13 |
| 534 | uDFN14 | `Float` | UDFN14 |
| 535 | uDFN15 | `Float` | UDFN15 |
| 536 | uDFN16 | `Float` | UDFN16 |
| 537 | uDFN17 | `Float` | UDFN17 |
| 538 | uDFN18 | `Float` | UDFN18 |
| 539 | uDFN19 | `Float` | UDFN19 |
| 540 | uDFN20 | `Float` | UDFN20 |
| 541 | uDFN21 | `Float` | UDFN21 |
| 542 | uDFN22 | `Float` | UDFN22 |
| 543 | uDFN23 | `Float` | UDFN23 |
| 544 | uDFN24 | `Float` | UDFN24 |
| 545 | uDFN25 | `Float` | UDFN25 |
| 546 | uDFN26 | `Float` | UDFN26 |
| 547 | uDFN27 | `Float` | UDFN27 |
| 548 | uDFN28 | `Float` | UDFN28 |
| 549 | uDFN29 | `Float` | UDFN29 |
| 550 | uDFN30 | `Float` | UDFN30 |
| 551 | uDFN31 | `Float` | UDFN31 |
| 552 | uDFN32 | `Float` | UDFN32 |
| 553 | uDFN33 | `Float` | UDFN33 |
| 554 | uDFN34 | `Float` | UDFN34 |
| 555 | uDFN35 | `Float` | UDFN35 |
| 556 | uDFN36 | `Float` | UDFN36 |
| 557 | uDFN37 | `Float` | UDFN37 |
| 558 | uDFN38 | `Float` | UDFN38 |
| 559 | uDFN39 | `Float` | UDFN39 |
| 560 | uDFN40 | `Float` | UDFN40 |
| 561 | ualias | `String` | Not in use. |
| 562 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 563 | updateDateExternal | `Date` | Update Date by LEAD REPLY. |
| 564 | updateUser | `Float` | Update User |
| 565 | updatedBy | `String` | Updated By |
| 566 | updatedDate | `DateTime` | Updated Date |
| 567 | uploadDate | `Date` | Upload Date |
| 568 | webBookable | `String` | Indicates if this business block can be booked via the web (OWS). |
| 569 | webOverbookYN | `String` | Indicates if this business block allows overbooking when rooms are available on the non-deduct block grid even if there are no rooms available on the house level. |
| 570 | xudescription | `String` | Multi Byte Description in uppercase |

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
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- profileaccountsDetailsChainCode

**`conditionalInputPair(pair: 2)`**
- profileaccountsDetailsProfileId
- profileaccountsDetailsActiveYn
- profileaccountsDetailsInactiveDate
- profileaccountsDetailsOrganizationId
- profileaccountsDetailsJrnupdatedttm
- profileaccountsDetailsNameId
- profileaccountsDetailsSname
- profileaccountsDetailsSfirst
- profileaccountsDetailsSxfirstName
- profileaccountsDetailsSxname
- profileaccountsDetailsUpdateDate


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
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
profile_forecast_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralForecastFBRevenue': pl.Float64,
    'centralForecastOtherRevenue': pl.Float64,
    'centralForecastRoomAverageRate': pl.Float64,
    'centralForecastRoomRevenue': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'period': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYn': pl.Utf8,
    'profileId': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'relationship': pl.Utf8,
    'toType': pl.Utf8,
    'updateUserName': pl.Utf8,
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
profile_commission_details_schema = {
    'accountId': pl.Float64,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionCodeDescription': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeDescription': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_relationship_details_schema = {
    'chainCode': pl.Utf8,
    'company': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fromProfileID': pl.Float64,
    'guestName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalRelationshipId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Int64,
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
```
```python
profile_note_details_schema = {
    'activityDueDate': pl.Utf8,
    'activityType': pl.Utf8,
    'chainCode': pl.Utf8,
    'confidentialYN': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'profileId': pl.Float64,
    'profileNoteId': pl.Float64,
    'resort': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_relationship_hier_details_schema = {
    'bottomId': pl.Float64,
    'bottomNameType': pl.Utf8,
    'chainCode': pl.Utf8,
    'contextCd': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'relToType': pl.Utf8,
    'relType': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'topId': pl.Float64,
    'totalLevels': pl.Float64,
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'preferenceCode': pl.Utf8,
    'preferenceDescription': pl.Utf8,
    'preferenceGroup': pl.Utf8,
    'preferenceId': pl.Utf8,
    'preferenceTypeCode': pl.Utf8,
    'preferenceTypeId': pl.Utf8,
    'preferenceValue': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'profileId': pl.Float64,
    'profilePreferenceId': pl.Utf8,
    'property': pl.Utf8,
    'repOrderby': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'otherRevenueNet': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationId': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'userId': pl.Float64,
}
```
```python
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
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
    'primaryKeyID': pl.Int64,
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
```
```python
sale_profile_owner_details_schema = {
    'accountOwner': pl.Utf8,
    'accountOwnerCode': pl.Utf8,
    'accountOwnerEmail': pl.Utf8,
    'accountOwnerPhone': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountSrepCode': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'locationId': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'ownerProfileId': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'userId': pl.Float64,
}
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
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
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'webBookable': pl.Utf8,
    'webOverbookYN': pl.Utf8,
    'xudescription': pl.Utf8,
}
```