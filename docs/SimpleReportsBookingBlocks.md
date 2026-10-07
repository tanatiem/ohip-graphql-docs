# SimpleReportsBookingBlocks
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `simpleReportsBookingBlocks`
> The Simple Reports Booking Blocks Subject Area simplifies creating and building adhoc reports including the ability to create new reports.
  
**Return:** [`[SimpleReportsBookingBlocksType]`](#simplereportsbookingblockstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`SimpleReportsBookingBlocksQueryArgumentsType!`](#simplereportsbookingblocksqueryargumentstype) |  |

## Object Types

### SimpleReportsBookingBlocksType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | salesEventBusinessBlockInformationDetails | [`SimpleReportsBookingBlocksSalesEventBusinessBlockInformationDetailsType`](#simplereportsbookingblockssaleseventbusinessblockinformationdetailstype) | Sales Event Business Block Information |
| 2 | propertyPropertyDetails | [`SimpleReportsBookingBlocksPropertyPropertyDetailsType`](#simplereportsbookingblockspropertypropertydetailstype) | Resort Details |
| 3 | simpleReportsBookingBlocksRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingBlocksSalesEventBusinessBlockInformationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | CHAIN_CODE |
| 2 | accountActionCode | `String` | Account Action Code |
| 3 | accountActiveYN | `String` | Acc Active Y/N |
| 4 | accountAddressType | `String` | Account Address Type |
| 5 | accountAddress1 | `String` | Account Address1 |
| 6 | accountAddress2 | `String` | Account Address2 |
| 7 | accountAlternateLanguage | `String` | Account Alternate Language |
| 8 | accountAlternateLanguageDesc | `String` | Acc Xlanguage Description |
| 9 | accountAlternateSalutation | `String` | Account Alternate Salutation |
| 10 | accountAlternateTitle | `String` | Account Alternate Title |
| 11 | accountArNumber | `String` | Acc AR No |
| 12 | accountAvailoverYN | `String` | Acc Availover Y/N |
| 13 | accountBlMsg | `String` | Account Bl Msg |
| 14 | accountBookingId | `Float` | Acc Booking ID |
| 15 | accountCblIndividual | `String` | Account Cbl Ind |
| 16 | accountCity | `String` | Account City. |
| 17 | accountCityExt | `String` | Account City Ext |
| 18 | accountCommissionCode | `String` | Account Commission Code |
| 19 | accountCompetitionCode | `String` | Account Competition Code |
| 20 | accountCountry | `String` | Account Country. |
| 21 | accountCountryDesc | `String` | Acc Country Description |
| 22 | accountDsi | `Float` | Account Dsi |
| 23 | accountEmail | `String` | Account Email |
| 24 | accountFax | `String` | Account Fax |
| 25 | accountHistoryYN | `String` | Acc History Y/N |
| 26 | accountHoldCode | `String` | Account Hold Code |
| 27 | accountIATACompType | `String` | Account Iata Comp Type |
| 28 | accountId | `Float` | Acc ID |
| 29 | accountIndustryCode | `String` | Account Industry Code |
| 30 | accountKeyword | `String` | Account Keyword |
| 31 | accountLanguage | `String` | Account Language |
| 32 | accountLanguageDesc | `String` | Acc Language Description |
| 33 | accountLinkId | `Float` | Acc Link ID |
| 34 | accountLinkType | `String` | Account Link Type |
| 35 | accountMailList | `String` | Account Mail List |
| 36 | accountMailType | `String` | Account Mail Type |
| 37 | accountMarkets | `String` | Account Markets |
| 38 | accountName | `String` | Account Name |
| 39 | accountNameKeywords | `String` | Account Name Keywords |
| 40 | accountNameType | `String` | Account Name Type |
| 41 | accountName2 | `String` | Account Name2 |
| 42 | accountName3 | `String` | Account Name3 |
| 43 | accountOrganizationid | `Float` | Account Organizationid |
| 44 | accountPhone | `String` | Account Phone |
| 45 | accountPhoneId | `Float` | Acc Phone ID |
| 46 | accountPhoneNumber | `String` | Account Phone No. |
| 47 | accountPrimaryYN | `String` | Acc Primary Y/N |
| 48 | accountPriority | `String` | Account Priority |
| 49 | accountProductInterest | `String` | Account Product Interest |
| 50 | accountProperty | `String` | Account Resort |
| 51 | accountRelationship | `String` | Account Relationship |
| 52 | accountRelationshipDesc | `String` | Acc Relationship Description |
| 53 | accountRepActionCode | `String` | Acc Reporting Actioncode |
| 54 | accountRepCompetionCode | `String` | Acc Reporting Competion Code |
| 55 | accountRepIATACompType | `String` | Acc Reporting Iata Comp Type |
| 56 | accountRepIndustryCode | `String` | Acc Reporting Industry Code |
| 57 | accountRepMarkets | `String` | Acc Reporting Markets |
| 58 | accountRepNameType | `String` | Acc Reporting Name Type |
| 59 | accountRepScope | `String` | Acc Reporting Scope |
| 60 | accountRepScopeCity | `String` | Acc Reporting Scope City |
| 61 | accountRepSource | `String` | Acc Reporting Source |
| 62 | accountRepStateCode | `String` | Acc Reporting State Code |
| 63 | accountRepStateDescription | `String` | Acc Reporting State Desc |
| 64 | accountRepTerritory | `String` | Acc Reporting Territory |
| 65 | accountRepType | `String` | Acc Reporting Type |
| 66 | accountRoomsPotential | `String` | Account Rooms Potential |
| 67 | accountScope | `String` | Account Scope |
| 68 | accountScopeCity | `String` | Account Scope City |
| 69 | accountSname | `String` | Account Sname |
| 70 | accountSource | `String` | Account Source |
| 71 | accountSrepCode | `String` | Account Srep Code |
| 72 | accountState | `String` | Account State. |
| 73 | accountStateDesc | `String` | Acc State Description |
| 74 | accountSxname | `String` | Account Sxname |
| 75 | accountTerritory | `String` | Account Territory |
| 76 | accountType | `String` | Account Type |
| 77 | accountXdisplayName | `String` | Account Xdisplay Name |
| 78 | accountXenvelopeGreeting | `String` | Account Xenvelope Greeting |
| 79 | accountXfirstName | `String` | Account Xfirst Name |
| 80 | accountZipcode | `String` | Account Zipcode |
| 81 | actionId | `Float` | Action ID |
| 82 | agentActiveYn | `String` | Agent Active Y/N |
| 83 | agentAddressType | `String` | Agent Address Type |
| 84 | agentAddress1 | `String` | Agent Address1 |
| 85 | agentAddress2 | `String` | Agent Address2 |
| 86 | agentAlternateLanguage | `String` | Agent Alternate Language |
| 87 | agentAlternateLanguageDesc | `String` | Agent Xlanguage Description |
| 88 | agentAlternateSalutation | `String` | Agent Alternate Salutation |
| 89 | agentAlternateTitle | `String` | Agent Alternate Title |
| 90 | agentArNumber | `String` | Agent AR No |
| 91 | agentAuSrepCode | `String` | Agent Au Srep Code |
| 92 | agentAvailabilityOverride | `String` | Agent Availability Override |
| 93 | agentBookingId | `Float` | Agent Booking ID |
| 94 | agentCblInd | `String` | Agent Cbl Individual |
| 95 | agentCity | `String` | Agent City |
| 96 | agentCityExt | `String` | Agent City Ext |
| 97 | agentConActionCode | `String` | Agent Con Action Code |
| 98 | agentConActiveYn | `String` | Agent Con Active Y/N |
| 99 | agentConAddressType | `String` | Agent Con Address Type |
| 100 | agentConAddress1 | `String` | Agent Con Address1 |
| 101 | agentConAddress2 | `String` | Agent Con Address2 |
| 102 | agentConAddress3 | `String` | Agent Con Address3 |
| 103 | agentConAddress4 | `String` | Agent Con Address4 |
| 104 | agentConAlternateLanguage | `String` | Agent Con Alternate Language |
| 105 | agentConAlternateLanguageDesc | `String` | Agent Con Xlanguage Description |
| 106 | agentConAlternateSalutation | `String` | Agent Con Alternate Salutation |
| 107 | agentConAlternateTitle | `String` | Agent Con Alternate Title |
| 108 | agentConArNumber | `String` | Agent Con AR No |
| 109 | agentConAuSrepCode | `String` | Agent Con Au Srep Code |
| 110 | agentConAvailabilityOverride | `String` | Agent Con Availability Override |
| 111 | agentConBirthDate | `Date` | Agent Con Birth Date |
| 112 | agentConBirthDateStr | `String` | Agent Con Birth Date Str |
| 113 | agentConBookingId | `Float` | Agent Con Booking ID |
| 114 | agentConBusinessGreeting | `String` | Agent Con Business Greeting |
| 115 | agentConCashBlInd | `String` | Agent Con Cash Bl Individual |
| 116 | agentConCity | `String` | Agent Con City |
| 117 | agentConCityExt | `String` | Agent Con City Ext |
| 118 | agentConContactYn | `String` | Agent Con Contact Y/N |
| 119 | agentConCountry | `String` | Agent Con Country |
| 120 | agentConCountryDesc | `String` | Agent Con Country Description |
| 121 | agentConDepartment | `String` | Agent Con Department |
| 122 | agentConDsi | `Float` | Agent Con Dsi |
| 123 | agentConEmail | `String` | Agent Con Email |
| 124 | agentConFax | `String` | Agent Con Fax |
| 125 | agentConFirst | `String` | Agent Con First |
| 126 | agentConHistoryYn | `String` | Agent Con History Y/N |
| 127 | agentConIataCompType | `String` | Agent Con IATA Comp Type |
| 128 | agentConId | `Float` | Agent Con ID |
| 129 | agentConIndustryCode | `String` | Agent Con Industry Code |
| 130 | agentConInfluence | `String` | Agent Con Influence |
| 131 | agentConLanguage | `String` | Agent Con Language |
| 132 | agentConLanguageDesc | `String` | Agent Con Language Description |
| 133 | agentConLast | `String` | Agent Con Last |
| 134 | agentConLetterGreeting | `String` | Agent Con Letter Greeting |
| 135 | agentConLinkId | `Float` | Agent Con Link ID |
| 136 | agentConLinkType | `String` | Agent Con Link Type |
| 137 | agentConMailType | `String` | Agent Con Mail Type |
| 138 | agentConMarkets | `String` | Agent Con Markets |
| 139 | agentConMiddle | `String` | Agent Con Middle |
| 140 | agentConName | `String` | Agent Con Name |
| 141 | agentConNameType | `String` | Agent Con Name Type |
| 142 | agentConName2 | `String` | Agent Con Name2 |
| 143 | agentConName3 | `String` | Agent Con Name3 |
| 144 | agentConOrganizationid | `Float` | Agent Con Organizationid |
| 145 | agentConPhone | `String` | Agent Con Phone |
| 146 | agentConPosition | `String` | Agent Con Position |
| 147 | agentConPrimaryYn | `String` | Agent Con Primary Y/N |
| 148 | agentConProductInterest | `String` | Agent Con Product Interest |
| 149 | agentConRelationship | `String` | Agent Con Relationship |
| 150 | agentConRelationshipDesc | `String` | Agent Con Relationship Description |
| 151 | agentConRepAccountType | `String` | Agent Con Reporting Account Type |
| 152 | agentConRepAccountsource | `String` | Agent Con Reporting Accountsource |
| 153 | agentConRepActionCode | `String` | Agent Con Reporting Actioncode |
| 154 | agentConRepIATACompType | `String` | Agent Con Reporting Iata Comp Type |
| 155 | agentConRepIndustryCode | `String` | Agent Con Reporting Industry Code |
| 156 | agentConRepInfluence | `String` | Agent Con Reporting Influence |
| 157 | agentConRepMarkets | `String` | Agent Con Reporting Markets |
| 158 | agentConRepNameType | `String` | Agent Con Reporting Name Type |
| 159 | agentConRepScope | `String` | Agent Con Reporting Scope |
| 160 | agentConRepScopeCity | `String` | Agent Con Reporting Scope City |
| 161 | agentConRepStateCode | `String` | Agent Con Reporting State Code |
| 162 | agentConRepStateDescription | `String` | Agent Con Reporting State Desc |
| 163 | agentConRepTerritory | `String` | Agent Con Reporting Territory |
| 164 | agentConRepTitle | `String` | Agent Con Reporting Title |
| 165 | agentConResort | `String` | Agent Con Property |
| 166 | agentConScope | `String` | Agent Con Scope |
| 167 | agentConScopeCity | `String` | Agent Con Scope City |
| 168 | agentConSfirst | `String` | Agent Con Sfirst |
| 169 | agentConSname | `String` | Agent Con Sname |
| 170 | agentConSrepId | `Float` | Agent Con Srep ID |
| 171 | agentConSrepName | `String` | Agent Con Srep Name |
| 172 | agentConState | `String` | Agent Con State |
| 173 | agentConStateDesc | `String` | Agent Con State Description |
| 174 | agentConSxfirstName | `String` | Agent Con Sxfirst Name |
| 175 | agentConSxname | `String` | Agent Con Sxname |
| 176 | agentConTerritory | `String` | Agent Con Territory |
| 177 | agentConTitle | `String` | Agent Con Title |
| 178 | agentConXfirst | `String` | Agent Con Xfirst |
| 179 | agentConXlast | `String` | Agent Con Xlast |
| 180 | agentConXletterGreeting | `String` | Agent Con Xletter Greeting |
| 181 | agentConXname | `String` | Agent Con Xname |
| 182 | agentConZipcode | `String` | Agent Con Zipcode |
| 183 | agentCountry | `String` | Agent Country |
| 184 | agentCountryDesc | `String` | Agent Country Description |
| 185 | agentDsi | `Float` | Agent Dsi |
| 186 | agentEmail | `String` | Agent Email |
| 187 | agentFax | `String` | Agent Fax |
| 188 | agentHistoryYn | `String` | Agent History Y/N |
| 189 | agentIataCompType | `String` | Agent IATA Comp Type |
| 190 | agentId | `Float` | Agent ID |
| 191 | agentIndustryCode | `String` | Agent Industry Code |
| 192 | agentLanguage | `String` | Agent Language |
| 193 | agentLanguageDesc | `String` | Agent Language Description |
| 194 | agentLinkId | `Float` | Agent Link ID |
| 195 | agentLinkType | `String` | Agent Link Type |
| 196 | agentMailType | `String` | Agent Mail Type |
| 197 | agentMarkets | `String` | Agent Markets |
| 198 | agentName | `String` | Agent Name |
| 199 | agentNameId | `Float` | Agent Name ID |
| 200 | agentNameType | `String` | Agent Name Type |
| 201 | agentName2 | `String` | Agent Name2 |
| 202 | agentName3 | `String` | Agent Name3 |
| 203 | agentOrganizationid | `Float` | Agent Organizationid |
| 204 | agentPhone | `String` | Agent Phone |
| 205 | agentPrimaryYn | `String` | Agent Primary Y/N |
| 206 | agentProductInterest | `String` | Agent Product Interest |
| 207 | agentRelationship | `String` | Agent Relationship |
| 208 | agentRelationshipDesc | `String` | Agent Relationship Description |
| 209 | agentRepStateCode | `String` | Agent Reporting State Code |
| 210 | agentResort | `String` | Agent Property |
| 211 | agentScope | `String` | Agent Scope |
| 212 | agentScopeCity | `String` | Agent Scope City |
| 213 | agentSname | `String` | Agent Sname |
| 214 | agentState | `String` | Agent State |
| 215 | agentStateDesc | `String` | Agent State Description |
| 216 | agentSxname | `String` | Agent Sxname |
| 217 | agentTerritory | `String` | Agent Territory |
| 218 | agentXdisplayName | `String` | Agent Xdisplay Name |
| 219 | agentXenvelopeGreeting | `String` | Agent Xenvelope Greeting |
| 220 | agentXfirstName | `String` | Agent Xfirst Name |
| 221 | agentZipcode | `String` | Agent Zipcode |
| 222 | alias | `String` | Alias |
| 223 | allOwners | `String` | All Owners |
| 224 | allotmentCode | `String` | Allotment Code |
| 225 | allotmentHeaderId | `Float` | Allotment Header ID |
| 226 | allotmentOrigion | `String` | Allotment Origion |
| 227 | allotmentType | `String` | Type of Block alloted for the group. |
| 228 | arrivalTime | `DateTime` | Arrival Time |
| 229 | attendees | `Float` | Attendees |
| 230 | avgPeoplePerRoom | `Float` | Avg People Per Room |
| 231 | avgRateNet | `Float` | Avg Rate Net |
| 232 | beginDate | `Date` | Begin Date |
| 233 | bookingStatus | `String` | Booking Status |
| 234 | bookingStatusOrderby | `Float` | Booking Status Orderby |
| 235 | bookingStatusType | `String` | Booking Status Type |
| 236 | bookingStatusorder | `Float` | Booking Statusorder |
| 237 | bookingmethod | `String` | Bookingmethod |
| 238 | bookingmethoddesc | `String` | Bookingmethoddesc |
| 239 | bookingtype | `String` | Bookingtype |
| 240 | breakfastDesc | `String` | Bfst Description |
| 241 | breakfastPrice | `Float` | Breakfast Price |
| 242 | breakfastYn | `String` | Bfst Y/N |
| 243 | busblockId | `Float` | Busblock ID |
| 244 | busblockProperty | `String` | Busblock Property |
| 245 | cBreakfastPrice | `Float` | Central Bfst Price |
| 246 | cCompRoomValue | `Float` | Central Comp Room Value |
| 247 | cExchangeDate | `Date` | Central Xchange Date |
| 248 | cExchangeRate | `Float` | Central Xchange Rate |
| 249 | cMtgBudget | `Float` | Central Mtg Budget |
| 250 | cPorteragePrice | `Float` | Central Porterage Price |
| 251 | cPotRoomRevenue | `Float` | Central Pot Room Revenue |
| 252 | cServiceCharge | `Float` | Central Service Charge |
| 253 | cTaxAmount | `Float` | Central Tax Amount |
| 254 | cancelRule | `String` | Not Used |
| 255 | cancellationCode | `String` | Cancellation Code |
| 256 | cancellationDate | `Date` | Cancellation Date |
| 257 | cancellationDescription | `String` | Cancellation Description |
| 258 | cancellationNo | `Float` | Cancellation Number |
| 259 | catCanxCode | `String` | Catering Canx Code |
| 260 | catCanxDate | `Date` | Catering Canx Date |
| 261 | catCanxNumber | `Float` | Catering Canx No |
| 262 | catCurrency | `String` | Catering Currency |
| 263 | catCutoff | `Date` | Catering Cutoff |
| 264 | catDecision | `Date` | Catering Decision |
| 265 | catExchange | `Float` | Catering Exchange |
| 266 | catFollowup | `Date` | Catering Followup |
| 267 | catOwner | `Float` | Catering Owner |
| 268 | catOwnerCode | `String` | Catering Owner Code |
| 269 | catOwnerEmail | `String` | Catering Owner Email |
| 270 | catOwnerFax | `String` | Catering Owner Fax |
| 271 | catOwnerPhone | `String` | Catering Owner Phone |
| 272 | catOwnerProperty | `String` | Property of Catering Owner |
| 273 | catOwnerSrepname | `String` | Catering Owner Srepname |
| 274 | catOwnerTitle | `String` | Catering Owner Title |
| 275 | catOwners | `String` | Catering Owners |
| 276 | catQuoteCurrency | `String` | Catering Quote Curr |
| 277 | catStatus | `String` | Catering Status |
| 278 | catStatusOrderby | `Float` | Catering Status Orderby |
| 279 | catStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 280 | catStatusorder | `Float` | Catering Statusorder |
| 281 | cateringCanxDesc | `String` | Cat Canx Description |
| 282 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 283 | cateringonlyYn | `String` | Cateringonly Y/N |
| 284 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 285 | channel | `String` | Channel |
| 286 | commission | `String` | Commission |
| 287 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 288 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 289 | compRooms | `Float` | Number of complimentary Rooms |
| 290 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 291 | companyNameId | `Float` | Company Name ID |
| 292 | competition | `String` | Competition |
| 293 | conActionCode | `String` | Con Action Code |
| 294 | conActiveYn | `String` | Con Active Y/N |
| 295 | conAddressType | `String` | Con Address Type |
| 296 | conAddress1 | `String` | Con Address1 |
| 297 | conAddress2 | `String` | Con Address2 |
| 298 | conAddress3 | `String` | Con Address3 |
| 299 | conAddress4 | `String` | Con Address4 |
| 300 | conAlternateLanguage | `String` | Con Alternate Language |
| 301 | conAlternateLanguageDesc | `String` | Con Xlanguage Description |
| 302 | conAlternateSalutation | `String` | Con Alternate Salutation |
| 303 | conAlternateTitle | `String` | Con Alternate Title |
| 304 | conArNumber | `String` | Con AR No |
| 305 | conAvailabilityOverride | `String` | Con Availability Override |
| 306 | conBirthDate | `Date` | Con Birth Date |
| 307 | conBirthDateStr | `String` | Con Birth Date Str |
| 308 | conBookingId | `Float` | Con Booking ID |
| 309 | conBusinessGreeting | `String` | Con Business Greeting |
| 310 | conCashBlInd | `String` | Con Cash Bl Individual |
| 311 | conCity | `String` | Con City |
| 312 | conCityExt | `String` | Con City Ext |
| 313 | conContactYn | `String` | Con Contact Y/N |
| 314 | conCountry | `String` | Con Country |
| 315 | conCountryDesc | `String` | Con Country Description |
| 316 | conDepartment | `String` | Con Department |
| 317 | conDsi | `Float` | Con Dsi |
| 318 | conFirst | `String` | Con First |
| 319 | conHistoryYn | `String` | Con History Y/N |
| 320 | conIataCompType | `String` | Con IATA Comp Type |
| 321 | conId | `Float` | Con ID |
| 322 | conIndustryCode | `String` | Con Industry Code |
| 323 | conInfluence | `String` | Con Influence |
| 324 | conLanguage | `String` | Con Language |
| 325 | conLanguageDesc | `String` | Con Language Description |
| 326 | conLast | `String` | Con Last |
| 327 | conLetterGreeting | `String` | Con Letter Greeting |
| 328 | conLinkId | `Float` | Con Link ID |
| 329 | conLinkType | `String` | Con Link Type |
| 330 | conMailType | `String` | Con Mail Type |
| 331 | conMarkets | `String` | Con Markets |
| 332 | conMiddle | `String` | Con Middle |
| 333 | conName | `String` | Con Name |
| 334 | conNameType | `String` | Con Name Type |
| 335 | conName2 | `String` | Con Name2 |
| 336 | conName3 | `String` | Con Name3 |
| 337 | conOrganizationid | `Float` | Con Organizationid |
| 338 | conPosition | `String` | Con Position |
| 339 | conPrimaryYn | `String` | Con Primary Y/N |
| 340 | conProductInterest | `String` | Con Product Interest |
| 341 | conRelationship | `String` | Con Relationship |
| 342 | conRelationshipDesc | `String` | Con Relationship Description |
| 343 | conRepActionCode | `String` | Con Reporting Actioncode |
| 344 | conRepInfluence | `String` | Con Reporting Influence |
| 345 | conRepMarkets | `String` | Con Reporting Markets |
| 346 | conRepNameType | `String` | Con Reporting Name Type |
| 347 | conRepScope | `String` | Con Reporting Scope |
| 348 | conRepScopeCity | `String` | Con Reporting Scope City |
| 349 | conRepStateCode | `String` | Con Reporting State Code |
| 350 | conRepStateDescription | `String` | Con Reporting State Desc |
| 351 | conRepTerritory | `String` | Con Reporting Territory |
| 352 | conRepTitle | `String` | Con Reporting Title |
| 353 | conResort | `String` | Con Property |
| 354 | conScope | `String` | Con Scope |
| 355 | conScopeCity | `String` | Con Scope City |
| 356 | conSfirst | `String` | Con Sfirst |
| 357 | conSname | `String` | Con Sname |
| 358 | conSrepCode | `String` | Con Srep Code |
| 359 | conSrepId | `Float` | Con Srep ID |
| 360 | conSrepName | `String` | Con Srep Name |
| 361 | conState | `String` | Con State |
| 362 | conStateDesc | `String` | Con State Description |
| 363 | conSxfirstName | `String` | Con Sxfirst Name |
| 364 | conSxname | `String` | Con Sxname |
| 365 | conTerritory | `String` | Con Territory |
| 366 | conTitle | `String` | Con Title |
| 367 | conXfirst | `String` | Con Xfirst |
| 368 | conXlast | `String` | Con Xlast |
| 369 | conXletterGreeting | `String` | Con Xletter Greeting |
| 370 | conXname | `String` | Con Xname |
| 371 | contactEmail | `String` | Reservation Contact id salutation information. |
| 372 | contactFax | `String` | Contact Fax |
| 373 | contactNameId | `Float` | Contact Name ID |
| 374 | contactPhone | `String` | Contact Phone |
| 375 | contactZipcode | `String` | Contact Zipcode |
| 376 | contractNr | `String` | Contract Nr |
| 377 | conversionCode | `String` | Conversion Code |
| 378 | currencyCode | `String` | Currency Code |
| 379 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 380 | dateOpenedForPickup | `Date` | Business Date when the business block was opened for pickup. |
| 381 | datePro | `DateTime` | Date Pro |
| 382 | dateTen | `DateTime` | Date Ten |
| 383 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 384 | deletedflag | `String` | Deleted Flag |
| 385 | departureTime | `DateTime` | Departure Time |
| 386 | description | `String` | Description |
| 387 | destination | `String` | Destination |
| 388 | detailsOkYn | `String` | Details Ok Y/N |
| 389 | distributedYn | `String` | Distributed Y/N |
| 390 | dmlSeqNumber | `Float` | Dml Sequence No |
| 391 | downloadDate | `Date` | Download Date |
| 392 | downloadResort | `String` | Download Property |
| 393 | downloadSrep | `Float` | Download Srep |
| 394 | dueDate | `Date` | Due Date |
| 395 | elastic | `String` | Elastic |
| 396 | endDate | `Date` | End Date |
| 397 | eventsGuaranteedYn | `String` | Events Guaranteed Y/N |
| 398 | exchangePostingType | `String` | Exchange Posting Type |
| 399 | exchangeRate | `Float` | Exchange Rate |
| 400 | externalLocked | `String` | External Locked |
| 401 | functiontype | `String` | Functiontype |
| 402 | giid | `String` | Group IATA Number. |
| 403 | guaranteeCode | `String` | Guarantee Code |
| 404 | iataCorpNumber | `String` | IATA Corp No |
| 405 | inactiveDate | `Date` | Inactive Date |
| 406 | info | `String` | Not Used |
| 407 | infoboard | `String` | Infoboard |
| 408 | insertDate | `DateTime` | Insert Date |
| 409 | insertUser | `Float` | Insert User |
| 410 | insertUserName | `String` | The name of the user who created the record. |
| 411 | invCutoffDate | `Date` | Invoice Cutoff Date |
| 412 | invCutoffDays | `Float` | Invoice Cutoff Days |
| 413 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 414 | isacQuoteId | `String` | Isac Quote ID |
| 415 | jRNUpdateDate | `Date` | JRN Update Date |
| 416 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 417 | laptopChange | `Float` | Laptop Change |
| 418 | leadOrigin | `String` | Lead Origin |
| 419 | leadSource | `String` | Lead Source |
| 420 | linkDate | `DateTime` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 421 | lostToProperty | `String` | Competitor to whom the booking was lost. |
| 422 | mainmarket | `String` | Mainmarket |
| 423 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 424 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 425 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 426 | marketCode | `String` | Market Code |
| 427 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 428 | methodDue | `Date` | Method Due |
| 429 | mtgBudget | `Float` | Meeting Budget |
| 430 | nonCompete | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 431 | nonCompeteCode | `String` | Indicates the Non-Compete code of a block. |
| 432 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 433 | originalRateCode | `String` | Not used |
| 434 | owner | `Float` | Owner |
| 435 | ownerCode | `String` | Owner Code |
| 436 | ownerCodeSrepname | `String` | Owner Code Srepname |
| 437 | ownerEmail | `String` | Owner Email |
| 438 | ownerFax | `String` | Owner Fax |
| 439 | ownerPhone | `String` | Owner Phone |
| 440 | ownerResort | `String` | Owner Property |
| 441 | ownerTitle | `String` | Owner Title |
| 442 | paymentMethod | `String` | Payment Method |
| 443 | peakRooms | `Float` | Peak Rooms |
| 444 | porteragePrice | `Float` | Porterage Price |
| 445 | porterageYn | `String` | Porterage Y/N |
| 446 | printAccountActiveYN | `String` | Print Acc Active Y/N |
| 447 | printAccountAddress1 | `String` | Print Account Address1 |
| 448 | printAccountAddress2 | `String` | Print Account Address2 |
| 449 | printAccountAddress3 | `String` | Print Account Address3 |
| 450 | printAccountAddress4 | `String` | Print Account Address4 |
| 451 | printAccountBookingId | `Float` | Print Acc Booking ID |
| 452 | printAccountCity | `String` | Print Account City |
| 453 | printAccountCityExt | `String` | Print Account City Ext |
| 454 | printAccountCountry | `String` | Print Account Country |
| 455 | printAccountCountryDesc | `String` | Print Acc Country Description |
| 456 | printAccountDsi | `Float` | Print Account Dsi |
| 457 | printAccountId | `Float` | Print Acc ID |
| 458 | printAccountLinkId | `Float` | Print Acc Link ID |
| 459 | printAccountLinkType | `String` | Print Account Link Type |
| 460 | printAccountName | `String` | Print Account Name |
| 461 | printAccountName2 | `String` | Print Account Name2 |
| 462 | printAccountName3 | `String` | Print Account Name3 |
| 463 | printAccountOrganizationid | `Float` | Print Account Organizationid |
| 464 | printAccountPhone | `String` | Print Account Phone |
| 465 | printAccountPosition | `String` | Print Account Position |
| 466 | printAccountPrimaryYN | `String` | Print Acc Primary Y/N |
| 467 | printAccountProperty | `String` | Print Account Resort |
| 468 | printAccountRepStateCode | `String` | Print Acc Reporting State Code |
| 469 | printAccountRepStateDescription | `String` | Print Acc Reporting State Desc |
| 470 | printAccountRepTerritory | `String` | Print Acc Reporting Territory |
| 471 | printAccountScope | `String` | Print Account Scope |
| 472 | printAccountScopeCity | `String` | Print Account Scope City |
| 473 | printAccountSname | `String` | Print Account Sname |
| 474 | printAccountState | `String` | Print Account State |
| 475 | printAccountStateDesc | `String` | Print Acc State Description |
| 476 | printAccountSxname | `String` | Print Account Sxname |
| 477 | printAccountTerritory | `String` | Print Account Territory |
| 478 | printAccountXdisplayName | `String` | Print Account Xdisplay Name |
| 479 | printAccountXenvelopeGreeting | `String` | Print Account Xenvelope Greeting |
| 480 | printAccountXfirstName | `String` | Print Account Xfirst Name |
| 481 | printAccountXname | `String` | Print Account Xname |
| 482 | printAccountZipcode | `String` | Print Account Zipcode |
| 483 | printConAddress1 | `String` | Print Con Address1 |
| 484 | printConAddress2 | `String` | Print Con Address2 |
| 485 | printConAddress3 | `String` | Print Con Address3 |
| 486 | printConAddress4 | `String` | Print Con Address4 |
| 487 | printConAlternateSalutation | `String` | Print Con Alternate Salutation |
| 488 | printConBusinessGreeting | `String` | Print Con Business Greeting |
| 489 | printConCity | `String` | Print Con City |
| 490 | printConCityExt | `String` | Print Con City Ext |
| 491 | printConCountry | `String` | Print Con Country |
| 492 | printConCountryDesc | `String` | Print Con Country Description |
| 493 | printConDepartment | `String` | Print Con Department |
| 494 | printConDsi | `Float` | Print Con Dsi |
| 495 | printConEmail | `String` | Print Con Email |
| 496 | printConFirst | `String` | Print Con First |
| 497 | printConId | `Float` | Print Con ID |
| 498 | printConLast | `String` | Print Con Last |
| 499 | printConLetterGreeting | `String` | Print Con Letter Greeting |
| 500 | printConLinkId | `Float` | Print Con Link ID |
| 501 | printConLinkType | `String` | Print Con Link Type |
| 502 | printConMiddle | `String` | Print Con Middle |
| 503 | printConName | `String` | Print Con Name |
| 504 | printConName2 | `String` | Print Con Name2 |
| 505 | printConName3 | `String` | Print Con Name3 |
| 506 | printConOrganizationid | `Float` | Print Con Organizationid |
| 507 | printConPhone | `String` | Print Con Phone |
| 508 | printConPosition | `String` | Print Con Position |
| 509 | printConPrimaryYn | `String` | Print Con Primary Y/N |
| 510 | printConProductInterest | `String` | Print Con Product Interest |
| 511 | printConRelationship | `String` | Print Con Relationship |
| 512 | printConRelationshipDesc | `String` | Print Con Relationship Description |
| 513 | printConRepStateCode | `String` | Print Con Reporting State Code |
| 514 | printConRepTitle | `String` | Print Con Reporting Title |
| 515 | printConResort | `String` | Print Con Property |
| 516 | printConScope | `String` | Print Con Scope |
| 517 | printConScopeCity | `String` | Print Con Scope City |
| 518 | printConSname | `String` | Print Con Sname |
| 519 | printConState | `String` | Print Con State |
| 520 | printConStateDesc | `String` | Print Con State Description |
| 521 | printConSxname | `String` | Print Con Sxname |
| 522 | printConTerritory | `String` | Print Con Territory |
| 523 | printConTitle | `String` | Print Con Title |
| 524 | printConXdisplayName | `String` | Print Con Xdisplay Name |
| 525 | printConXfirst | `String` | Print Con Xfirst |
| 526 | printConXlast | `String` | Print Con Xlast |
| 527 | printConXletterGreeting | `String` | Print Con Xletter Greeting |
| 528 | printConZipcode | `String` | Print Con Zipcode |
| 529 | profileDesc | `String` | Profile Description |
| 530 | profileId | `Float` | Profile ID |
| 531 | program | `String` | Program |
| 532 | property | `String` | Code to uniquely identify the Property |
| 533 | rankingCode | `String` | Indicates the ranking of a block. |
| 534 | rateCode | `String` | Rate Code |
| 535 | rateGuaranteedYn | `String` | Rate Guaranteed Y/N. |
| 536 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 537 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 538 | rateProtection | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 539 | relatedResorts | `String` | Related Resorts |
| 540 | repBlockStatusDescription | `String` | Reporting Block Status Description |
| 541 | repBookingmethod | `String` | Reporting Bookingmethod |
| 542 | repBookingmethodDescription | `String` | Reporting Bookingmethod Desc |
| 543 | repBookingtype | `String` | Reporting Bookingtype |
| 544 | repBsOrderBy | `Float` | Reporting Bs Order By |
| 545 | repCateringOrderBy | `Float` | Reporting Cat Order By |
| 546 | repCateringStatus | `String` | Reporting Cat Status |
| 547 | repCateringStatusDescription | `String` | Reporting Cat Status Description |
| 548 | repChannel | `String` | Reporting Channel |
| 549 | repConversionCode | `String` | Reporting Conversion Code |
| 550 | repDestination | `String` | Reporting Destination |
| 551 | repGuaranteeCode | `String` | Reporting Guarantee Code |
| 552 | repMarketCode | `String` | Reporting Market Code |
| 553 | repNonCompeteCode | `String` | Reporting Non Compete Code |
| 554 | repPaymentMethod | `String` | Reporting Payment Method |
| 555 | repRankingCode | `String` | Reporting Ranking Code |
| 556 | repSourceCode | `String` | Reporting Source Code |
| 557 | representative | `String` | Representative |
| 558 | reserveInventoryYn | `String` | Reserve Inventory Y/N |
| 559 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 560 | revBlocked | `Float` | Revenue Blocked |
| 561 | revBlockedNet | `Float` | Revenue Blocked Net |
| 562 | revContracted | `Float` | Revenue Contracted |
| 563 | rivMarketSegment | `String` | Not used |
| 564 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 565 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 566 | roomsBlocked | `Float` | Rooms Blocked |
| 567 | roomsContracted | `Float` | Rooms Contracted |
| 568 | roomsCurrency | `String` | Rooms Currency |
| 569 | roomsDecision | `Date` | Rooms Decision |
| 570 | roomsExchange | `Float` | Rooms Exchange |
| 571 | roomsFollowup | `Date` | Rooms Followup |
| 572 | roomsOwner | `Float` | Rooms Owner |
| 573 | roomsOwnerCode | `String` | Rooms Owner Code |
| 574 | roomsOwnerEmail | `String` | Rooms Owner Email |
| 575 | roomsOwnerFax | `String` | Rooms Owner Fax |
| 576 | roomsOwnerPhone | `String` | Rooms Owner Phone |
| 577 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 578 | roomsOwnerSrepname | `String` | Rooms Owner Srepname |
| 579 | roomsOwnerTitle | `String` | Rooms Owner Title |
| 580 | roomsOwners | `String` | Rooms Owners |
| 581 | roomsPerDay | `Float` | Rooms Per Day |
| 582 | roomsQuoteCurr | `String` | Rms Quote Currency |
| 583 | salesId | `String` | Not used |
| 584 | sbegindate | `Date` | Sbegindate |
| 585 | secConActionCode | `String` | Sec Con Action Code |
| 586 | secConActiveYn | `String` | Sec Con Active Y/N |
| 587 | secConAddress1 | `String` | Sec Con Address1 |
| 588 | secConAddress2 | `String` | Sec Con Address2 |
| 589 | secConAddress3 | `String` | Sec Con Address3 |
| 590 | secConAddress4 | `String` | Sec Con Address4 |
| 591 | secConAlternateLanguage | `String` | Sec Con Alternate Language |
| 592 | secConAlternateLanguageDesc | `String` | Sec Con Xlanguage Description |
| 593 | secConAlternateSalutation | `String` | Sec Con Alternate Salutation |
| 594 | secConAlternateTitle | `String` | Sec Con Alternate Title |
| 595 | secConBirthDate | `Date` | Sec Con Birth Date |
| 596 | secConBirthDateStr | `String` | Sec Con Birth Date Str |
| 597 | secConBookingId | `Float` | Sec Con Booking ID |
| 598 | secConBusinessGreeting | `String` | Sec Con Business Greeting |
| 599 | secConCashBlInd | `String` | Sec Con Cash Bl Individual |
| 600 | secConCity | `String` | Sec Con City |
| 601 | secConCityExt | `String` | Sec Con City Ext |
| 602 | secConContactYn | `String` | Sec Con Contact Y/N |
| 603 | secConCountry | `String` | Sec Con Country |
| 604 | secConCountryDesc | `String` | Sec Con Country Description |
| 605 | secConDepartment | `String` | Sec Con Department |
| 606 | secConDsi | `Float` | Sec Con Dsi |
| 607 | secConEmail | `String` | Sec Con Email |
| 608 | secConFax | `String` | Sec Con Fax |
| 609 | secConFirstName | `String` | Sec Con First Name |
| 610 | secConFullName | `String` | Sec Con Full Name |
| 611 | secConId | `Float` | Sec Con ID |
| 612 | secConInfluence | `String` | Sec Con Influence |
| 613 | secConLanguage | `String` | Sec Con Language |
| 614 | secConLanguageDesc | `String` | Sec Con Language Description |
| 615 | secConLastName | `String` | Sec Con Last Name |
| 616 | secConLetterGreeting | `String` | Sec Con Letter Greeting |
| 617 | secConLinkId | `Float` | Sec Con Link ID |
| 618 | secConLinkType | `String` | Sec Con Link Type |
| 619 | secConMarkets | `String` | Sec Con Markets |
| 620 | secConMiddleName | `String` | Sec Con Middle Name |
| 621 | secConNameType | `String` | Sec Con Name Type |
| 622 | secConName2 | `String` | Sec Con Name2 |
| 623 | secConName3 | `String` | Sec Con Name3 |
| 624 | secConOrganizationid | `Float` | Sec Con Organizationid |
| 625 | secConPhone | `String` | Sec Con Phone |
| 626 | secConPosition | `String` | Sec Con Position |
| 627 | secConPrimaryYn | `String` | Sec Con Primary Y/N |
| 628 | secConProductInterest | `String` | Sec Con Product Interest |
| 629 | secConRelationship | `String` | Sec Con Relationship |
| 630 | secConRelationshipDesc | `String` | Sec Con Relationship Description |
| 631 | secConRepActionCode | `String` | Sec Con Reporting Actioncode |
| 632 | secConRepInfluence | `String` | Sec Con Reporting Influence |
| 633 | secConRepMarkets | `String` | Sec Con Reporting Markets |
| 634 | secConRepNameType | `String` | Sec Con Reporting Name Type |
| 635 | secConRepScope | `String` | Sec Con Reporting Scope |
| 636 | secConRepScopeCity | `String` | Sec Con Reporting Scope City |
| 637 | secConRepStateCode | `String` | Sec Con Reporting State Code |
| 638 | secConRepStateDescription | `String` | Sec Con Reporting State Desc |
| 639 | secConRepTerritory | `String` | Sec Con Reporting Territory |
| 640 | secConRepTitle | `String` | Sec Con Reporting Title |
| 641 | secConResort | `String` | Sec Con Property |
| 642 | secConScope | `String` | Sec Con Scope |
| 643 | secConScopeCity | `String` | Sec Con Scope City |
| 644 | secConSfirst | `String` | Sec Con Sfirst |
| 645 | secConSname | `String` | Sec Con Sname |
| 646 | secConSrepCode | `String` | Sec Con Srep Code |
| 647 | secConSrepId | `Float` | Sec Con Srep ID |
| 648 | secConSrepName | `String` | Sec Con Srep Name |
| 649 | secConState | `String` | Sec Con State |
| 650 | secConStateDesc | `String` | Sec Con State Description |
| 651 | secConSxfirstName | `String` | Sec Con Sxfirst Name |
| 652 | secConSxname | `String` | Sec Con Sxname |
| 653 | secConTerritory | `String` | Sec Con Territory |
| 654 | secConTitle | `String` | Sec Con Title |
| 655 | secConXenvelopeGreeting | `String` | Sec Con Xenvelope Greeting |
| 656 | secConXfirstName | `String` | Sec Con Xfirst Name |
| 657 | secConXfullName | `String` | Sec Con Xfull Name |
| 658 | secConXlastName | `String` | Sec Con Xlast Name |
| 659 | secConZipCode | `String` | Sec Con Zipcode Code |
| 660 | senddate | `Date` | Senddate |
| 661 | sentDate | `DateTime` | Sent Date |
| 662 | serviceCharge | `Float` | Service Charge |
| 663 | shoulderBeginDate | `Date` | Shoulder Begin Date |
| 664 | shoulderEndDate | `Date` | Shoulder End Date |
| 665 | source | `String` | Source |
| 666 | sourceActiveYn | `String` | Source Active Y/N |
| 667 | sourceAddressType | `String` | Source Address Type |
| 668 | sourceAddress1 | `String` | Source Address1 |
| 669 | sourceAddress2 | `String` | Source Address2 |
| 670 | sourceAlternateLanguage | `String` | Source Alternate Language |
| 671 | sourceAlternateLanguageDesc | `String` | Source Xlanguage Description |
| 672 | sourceAlternateSalutation | `String` | Source Alternate Salutation |
| 673 | sourceAlternateTitle | `String` | Source Alternate Title |
| 674 | sourceBookingId | `Float` | Source Booking ID |
| 675 | sourceBusinessGreeting | `String` | Source Business Greeting |
| 676 | sourceCity | `String` | Source City |
| 677 | sourceCityExt | `String` | Source City Ext |
| 678 | sourceConActionCode | `String` | Source Con Action Code |
| 679 | sourceConActiveYn | `String` | Source Con Active Y/N |
| 680 | sourceConAddressType | `String` | Source Con Address Type |
| 681 | sourceConAddress1 | `String` | Source Con Address1 |
| 682 | sourceConAddress2 | `String` | Source Con Address2 |
| 683 | sourceConAddress3 | `String` | Source Con Address3 |
| 684 | sourceConAddress4 | `String` | Source Con Address4 |
| 685 | sourceConAlternateLanguage | `String` | Source Con Alternate Language |
| 686 | sourceConAlternateLanguageDesc | `String` | Source Con Xlanguage Description |
| 687 | sourceConAlternateSalutation | `String` | Source Con Alternate Salutation |
| 688 | sourceConAlternateTitle | `String` | Source Con Alternate Title |
| 689 | sourceConArNumber | `String` | Source Con AR No |
| 690 | sourceConAuSrepCode | `String` | Source Con Au Srep Code |
| 691 | sourceConAvailabilityOverride | `String` | Source Con Availability Override |
| 692 | sourceConBirthDate | `Date` | Source Con Birth Date |
| 693 | sourceConBirthDateStr | `String` | Source Con Birth Date Str |
| 694 | sourceConBookingId | `Float` | Source Con Booking ID |
| 695 | sourceConBusinessGreeting | `String` | Source Con Business Greeting |
| 696 | sourceConCashBlInd | `String` | Source Con Cash Bl Individual |
| 697 | sourceConCity | `String` | Source Con City |
| 698 | sourceConCityExt | `String` | Source Con City Ext |
| 699 | sourceConContactYn | `String` | Source Con Contact Y/N |
| 700 | sourceConCountry | `String` | Source Con Country |
| 701 | sourceConCountryDesc | `String` | Source Con Country Description |
| 702 | sourceConDepartment | `String` | Source Con Department |
| 703 | sourceConDsi | `Float` | Source Con Dsi |
| 704 | sourceConEmail | `String` | Source Con Email |
| 705 | sourceConFax | `String` | Source Con Fax |
| 706 | sourceConFirst | `String` | Source Con First |
| 707 | sourceConHistoryYn | `String` | Source Con History Y/N |
| 708 | sourceConIataCompType | `String` | Source Con IATA Comp Type |
| 709 | sourceConId | `Float` | Source Con ID |
| 710 | sourceConIndustryCode | `String` | Source Con Industry Code |
| 711 | sourceConInfluence | `String` | Source Con Influence |
| 712 | sourceConLanguage | `String` | Source Con Language |
| 713 | sourceConLanguageDesc | `String` | Source Con Language Description |
| 714 | sourceConLast | `String` | Source Con Last |
| 715 | sourceConLetterGreeting | `String` | Source Con Letter Greeting |
| 716 | sourceConLinkId | `Float` | Source Con Link ID |
| 717 | sourceConLinkType | `String` | Source Con Link Type |
| 718 | sourceConMailType | `String` | Source Con Mail Type |
| 719 | sourceConMarkets | `String` | Source Con Markets |
| 720 | sourceConMiddle | `String` | Source Con Middle |
| 721 | sourceConName | `String` | Source Con Name |
| 722 | sourceConNameType | `String` | Source Con Name Type |
| 723 | sourceConName2 | `String` | Source Con Name2 |
| 724 | sourceConName3 | `String` | Source Con Name3 |
| 725 | sourceConOrganizationid | `Float` | Source Con Organizationid |
| 726 | sourceConPhone | `String` | Source Con Phone |
| 727 | sourceConPosition | `String` | Source Con Position |
| 728 | sourceConPrimaryYn | `String` | Source Con Primary Y/N |
| 729 | sourceConProductInterest | `String` | Source Con Product Interest |
| 730 | sourceConRelationship | `String` | Source Con Relationship |
| 731 | sourceConRelationshipDesc | `String` | Source Con Relationship Description |
| 732 | sourceConRepActionCode | `String` | Source Con Reporting Actioncode |
| 733 | sourceConRepInfluence | `String` | Source Con Reporting Influence |
| 734 | sourceConRepMarkets | `String` | Source Con Reporting Markets |
| 735 | sourceConRepNameType | `String` | Source Con Reporting Name Type |
| 736 | sourceConRepScope | `String` | Source Con Reporting Scope |
| 737 | sourceConRepScopeCity | `String` | Source Con Reporting Scope City |
| 738 | sourceConRepStateCode | `String` | Source Con Reporting State Code |
| 739 | sourceConRepStateDescription | `String` | Source Con Reporting State Desc |
| 740 | sourceConRepTerritory | `String` | Source Con Reporting Territory |
| 741 | sourceConRepTitle | `String` | Source Con Reporting Title |
| 742 | sourceConResort | `String` | Source Con Property |
| 743 | sourceConScope | `String` | Source Con Scope |
| 744 | sourceConScopeCity | `String` | Source Con Scope City |
| 745 | sourceConSfirst | `String` | Source Con Sfirst |
| 746 | sourceConSname | `String` | Source Con Sname |
| 747 | sourceConSrepId | `Float` | Source Con Srep ID |
| 748 | sourceConSrepName | `String` | Source Con Srep Name |
| 749 | sourceConState | `String` | Source Con State |
| 750 | sourceConStateDesc | `String` | Source Con State Description |
| 751 | sourceConSxfirstName | `String` | Source Con Sxfirst Name |
| 752 | sourceConSxname | `String` | Source Con Sxname |
| 753 | sourceConTerritory | `String` | Source Con Territory |
| 754 | sourceConTitle | `String` | Source Con Title |
| 755 | sourceConXfirst | `String` | Source Con Xfirst |
| 756 | sourceConXlast | `String` | Source Con Xlast |
| 757 | sourceConXletterGreeting | `String` | Source Con Xletter Greeting |
| 758 | sourceConXname | `String` | Source Con Xname |
| 759 | sourceConZipcode | `String` | Source Con Zipcode |
| 760 | sourceCountry | `String` | Source Country |
| 761 | sourceCountryDesc | `String` | Source Country Description |
| 762 | sourceDsi | `Float` | Source Dsi |
| 763 | sourceEmail | `String` | Source Email |
| 764 | sourceFax | `String` | Source Fax |
| 765 | sourceId | `Float` | Source ID |
| 766 | sourceLinkId | `Float` | Source Link ID |
| 767 | sourceLinkType | `String` | Source Link Type |
| 768 | sourceName | `String` | Source Name |
| 769 | sourceNameId | `Float` | Source Name ID |
| 770 | sourceNameType | `String` | Source Name Type |
| 771 | sourceName2 | `String` | Source Name2 |
| 772 | sourceName3 | `String` | Source Name3 |
| 773 | sourceOrganizationid | `Float` | Source Organizationid |
| 774 | sourcePhone | `String` | Source Phone |
| 775 | sourcePrimaryYn | `String` | Source Primary Y/N |
| 776 | sourceRelationship | `String` | Source Relationship |
| 777 | sourceRelationshipDesc | `String` | Source Relationship Description |
| 778 | sourceRepStateCode | `String` | Source Reporting State Code |
| 779 | sourceResort | `String` | Comma separated list of properties to migrate. |
| 780 | sourceScope | `String` | Source Scope |
| 781 | sourceScopeCity | `String` | Source Scope City |
| 782 | sourceSname | `String` | Source Sname |
| 783 | sourceState | `String` | Source State |
| 784 | sourceStateDesc | `String` | Source State Description |
| 785 | sourceSxname | `String` | Source Sxname |
| 786 | sourceTerritory | `String` | Source Territory |
| 787 | sourceXdisplayName | `String` | Source Xdisplay Name |
| 788 | sourceXenvelopeGreeting | `String` | Source Xenvelope Greeting |
| 789 | sourceXfirstName | `String` | Source Xfirst Name |
| 790 | sourceZipcode | `String` | Source Zipcode |
| 791 | status | `String` | Status |
| 792 | superBlockId | `Float` | Parent Block ID |
| 793 | superBlockResort | `String` | Parent Resort |
| 794 | taxAmount | `Float` | Tax Amount |
| 795 | tbdRates | `String` | To be Determined Rates |
| 796 | tentativeLevel | `Float` | Not used |
| 797 | tracecode | `String` | Tracecode |
| 798 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 799 | udfc01 | `String` | Udfc01 |
| 800 | udfc02 | `String` | Udfc02 |
| 801 | udfc03 | `String` | Udfc03 |
| 802 | udfc04 | `String` | Udfc04 |
| 803 | udfc05 | `String` | Udfc05 |
| 804 | udfc06 | `String` | Udfc06 |
| 805 | udfc07 | `String` | Udfc07 |
| 806 | udfc08 | `String` | Udfc08 |
| 807 | udfc09 | `String` | Udfc09 |
| 808 | udfc10 | `String` | Udfc10 |
| 809 | udfc11 | `String` | Udfc11 |
| 810 | udfc12 | `String` | Udfc12 |
| 811 | udfc13 | `String` | Udfc13 |
| 812 | udfc14 | `String` | Udfc14 |
| 813 | udfc15 | `String` | Udfc15 |
| 814 | udfc16 | `String` | Udfc16 |
| 815 | udfc17 | `String` | Udfc17 |
| 816 | udfc18 | `String` | Udfc18 |
| 817 | udfc19 | `String` | Udfc19 |
| 818 | udfc20 | `String` | Udfc20 |
| 819 | udfc21 | `String` | Udfc21 |
| 820 | udfc22 | `String` | Udfc22 |
| 821 | udfc23 | `String` | Udfc23 |
| 822 | udfc24 | `String` | Udfc24 |
| 823 | udfc25 | `String` | Udfc25 |
| 824 | udfc26 | `String` | Udfc26 |
| 825 | udfc27 | `String` | Udfc27 |
| 826 | udfc28 | `String` | Udfc28 |
| 827 | udfc29 | `String` | Udfc29 |
| 828 | udfc30 | `String` | Udfc30 |
| 829 | udfc31 | `String` | Udfc31 |
| 830 | udfc32 | `String` | Udfc32 |
| 831 | udfc33 | `String` | Udfc33 |
| 832 | udfc34 | `String` | Udfc34 |
| 833 | udfc35 | `String` | Udfc35 |
| 834 | udfc36 | `String` | Udfc36 |
| 835 | udfc37 | `String` | Udfc37 |
| 836 | udfc38 | `String` | Udfc38 |
| 837 | udfc39 | `String` | Udfc39 |
| 838 | udfc40 | `String` | Udfc40 |
| 839 | udfd01 | `Date` | Udfd01 |
| 840 | udfd02 | `Date` | Udfd02 |
| 841 | udfd03 | `Date` | Udfd03 |
| 842 | udfd04 | `Date` | Udfd04 |
| 843 | udfd05 | `Date` | Udfd05 |
| 844 | udfd06 | `Date` | Udfd06 |
| 845 | udfd07 | `Date` | Udfd07 |
| 846 | udfd08 | `Date` | Udfd08 |
| 847 | udfd09 | `Date` | Udfd09 |
| 848 | udfd10 | `Date` | Udfd10 |
| 849 | udfd11 | `Date` | Udfd11 |
| 850 | udfd12 | `Date` | Udfd12 |
| 851 | udfd13 | `Date` | Udfd13 |
| 852 | udfd14 | `Date` | Udfd14 |
| 853 | udfd15 | `Date` | Udfd15 |
| 854 | udfd16 | `Date` | Udfd16 |
| 855 | udfd17 | `Date` | Udfd17 |
| 856 | udfd18 | `Date` | Udfd18 |
| 857 | udfd19 | `Date` | Udfd19 |
| 858 | udfd20 | `Date` | Udfd20 |
| 859 | udfn01 | `Float` | Udfn01 |
| 860 | udfn02 | `Float` | Udfn02 |
| 861 | udfn03 | `Float` | Udfn03 |
| 862 | udfn04 | `Float` | Udfn04 |
| 863 | udfn05 | `Float` | Udfn05 |
| 864 | udfn06 | `Float` | Udfn06 |
| 865 | udfn07 | `Float` | Udfn07 |
| 866 | udfn08 | `Float` | Udfn08 |
| 867 | udfn09 | `Float` | Udfn09 |
| 868 | udfn10 | `Float` | Udfn10 |
| 869 | udfn11 | `Float` | Udfn11 |
| 870 | udfn12 | `Float` | Udfn12 |
| 871 | udfn13 | `Float` | Udfn13 |
| 872 | udfn14 | `Float` | Udfn14 |
| 873 | udfn15 | `Float` | Udfn15 |
| 874 | udfn16 | `Float` | Udfn16 |
| 875 | udfn17 | `Float` | Udfn17 |
| 876 | udfn18 | `Float` | Udfn18 |
| 877 | udfn19 | `Float` | Udfn19 |
| 878 | udfn20 | `Float` | Udfn20 |
| 879 | udfn21 | `Float` | Udfn21 |
| 880 | udfn22 | `Float` | Udfn22 |
| 881 | udfn23 | `Float` | Udfn23 |
| 882 | udfn24 | `Float` | Udfn24 |
| 883 | udfn25 | `Float` | Udfn25 |
| 884 | udfn26 | `Float` | Udfn26 |
| 885 | udfn27 | `Float` | Udfn27 |
| 886 | udfn28 | `Float` | Udfn28 |
| 887 | udfn29 | `Float` | Udfn29 |
| 888 | udfn30 | `Float` | Udfn30 |
| 889 | udfn31 | `Float` | Udfn31 |
| 890 | udfn32 | `Float` | Udfn32 |
| 891 | udfn33 | `Float` | Udfn33 |
| 892 | udfn34 | `Float` | Udfn34 |
| 893 | udfn35 | `Float` | Udfn35 |
| 894 | udfn36 | `Float` | Udfn36 |
| 895 | udfn37 | `Float` | Udfn37 |
| 896 | udfn38 | `Float` | Udfn38 |
| 897 | udfn39 | `Float` | Udfn39 |
| 898 | udfn40 | `Float` | Udfn40 |
| 899 | updateDate | `DateTime` | Update Date |
| 900 | updateUser | `Float` | Update User |
| 901 | updateUserName | `String` | Update User Name |
| 902 | uploadDate | `Date` | Upload Date |
| 903 | xaccName | `String` | Xacc Name |
| 904 | xagentName | `String` | Xagent Name |
| 905 | xsourceName | `String` | Extended Byte Source Name |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingBlocksPropertyPropertyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | property | `String` | The property that the record belongs to |
| 2 | aRAccountNoFormat | `String` | Number format of AR account no. |
| 3 | aRAccountNumberMandatoryYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| 4 | aRAgent | `String` | Default Account Type for an Agent for the Property |
| 5 | aRBalanceTrxCode | `String` | Internal |
| 6 | aRCompany | `String` | Default Account Type for a Company for the Property |
| 7 | aRCreditTrxCode | `String` | Internal |
| 8 | aRGroups | `String` | Default Account Type for a Group for the Property |
| 9 | aRIndividuals | `String` | Default Account Type for Individual for the Property |
| 10 | aRSettleCode | `String` | Internal |
| 11 | aRTypewriter | `String` | Internal |
| 12 | accessCode | `String` | Access Code |
| 13 | accessibleRooms | `Float` | Number of handicapped rooms. |
| 14 | agingLevel1 | `Float` | Aging bucket 1 |
| 15 | agingLevel2 | `Float` | Aging bucket 2 |
| 16 | agingLevel3 | `Float` | Aging bucket 3 |
| 17 | agingLevel4 | `Float` | Aging bucket 4 |
| 18 | agingLevel5 | `Float` | Aging bucket 3 |
| 19 | airport | `String` | The Airport Code for the airport near the property |
| 20 | airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| 21 | airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| 22 | allowLoginYN | `String` | Allow loggin in to this resort(Y/N) |
| 23 | allowancePeriodAdj | `String` | Period for the allowance |
| 24 | awardsTimeout | `Float` | Internal |
| 25 | ballroomArea | `String` | Ball Room Area |
| 26 | ballroomSeats | `Float` | No of Ballroom Seats |
| 27 | baseLanguage | `String` | The base language of the Hotel |
| 28 | block | `String` | It contains the reservation type to be used when making group block |
| 29 | brandCode | `String` | Brand Code of the property. |
| 30 | budgetMonth | `Float` | Financial Year of the Property |
| 31 | businessDate | `Date` | The date this resort becomes valid for use by the system |
| 32 | businessID | `String` | Value for the parameter. |
| 33 | businessRegistrationCode | `String` | Value for the parameter. |
| 34 | cROCODE | `String` | Code for the CRO |
| 35 | cashShiftDrop | `String` | Internal |
| 36 | cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| 37 | cateringCurrencyFormat | `String` | Catering currency format. |
| 38 | centralXchangeDate | `Date` | Central  Exchange Date |
| 39 | centralXchangeRate | `Float` | Central  Exchange Rate |
| 40 | centralCreditLimit | `Float` | Central Credit Limit |
| 41 | centralCurrencyCode | `String` | Central Currency Code |
| 42 | centralCurrencyDescription | `String` | Central Currency Description |
| 43 | centralDblRate2 | `Float` | Central Double Rate2 |
| 44 | centralDblRate1 | `Float` | Central Double Rate1 |
| 45 | centralPasserbyMarket | `String` | Central Passerby Market |
| 46 | centralPasserbySource | `String` | Central Passerby Source |
| 47 | centralPropertyType | `String` | Central Property Type |
| 48 | centralSglRate1 | `Float` | Central Sgl Rate1 |
| 49 | centralSglRate2 | `Float` | Central Sgl Rate 2 |
| 50 | centralState | `String` | Central State |
| 51 | centralStateDescription | `String` | Central State Description |
| 52 | centralSuiRate1 | `Float` | Central Sui Rate1 |
| 53 | centralSuiRate2 | `Float` | Central Sui Rate 2 |
| 54 | centralTplRate1 | `Float` | Central Tpl Rate1 |
| 55 | centralTplRate2 | `Float` | Central Tpl Rate 2 |
| 56 | centralWarningAmount | `Float` | Central Warning Amount |
| 57 | chainCode | `String` | Chain Code for the chain to which the property belongs |
| 58 | chainDescription | `String` | The description of this chain. |
| 59 | chainMode | `String` | Chain Mode |
| 60 | checkExgPaidout | `String` | Internal |
| 61 | checkOutTime | `DateTime` | The Hotel official check out time |
| 62 | checkShiftDrop | `String` | Internal |
| 63 | checkTrxcode | `String` | Internal |
| 64 | checkInTime | `DateTime` | The Hotel official check intime |
| 65 | city | `String` | The physical city in which this property resides. |
| 66 | cityDescription | `String` | City Description |
| 67 | comAddress | `String` | Internal |
| 68 | comMethod | `String` | Internal |
| 69 | comNameXrefId | `Float` | Internal |
| 70 | companyAddressType | `String` | Internal |
| 71 | companyPhoneType | `String` | Internal |
| 72 | configurationMode | `String` | Internal |
| 73 | confirmRegcardPrinter | `String` | Internal |
| 74 | connectingRooms | `Float` | Number of connecting rooms. |
| 75 | contacts | `String` | The unique name of application user |
| 76 | copies | `Float` | Number of copies to be printed |
| 77 | country | `String` | Country name. |
| 78 | countryCode | `String` | The name of the country in which this property resides. |
| 79 | countryMode | `String` | Value for the parameter. |
| 80 | creditLimit | `Float` | The default credit limit for guests. |
| 81 | currencyCode | `String` | Currency Code. |
| 82 | currencyCodeSymbol | `String` | Currency Symbol like $ or EURO symbol |
| 83 | currencyDescription | `String` | A description of this currency. |
| 84 | currencyFormat | `String` | Format for the local currency. |
| 85 | curtainColor | `String` | Color that of the background |
| 86 | dSI | `Float` | DSI |
| 87 | dateForAging | `String` | Date the aging should begin |
| 88 | dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| 89 | decimalPlaces | `Float` | Number of places for the default currency |
| 90 | decimalSeparator | `String` | Type of decimal separator |
| 91 | decimals | `Float` | Number of decimals to designate currency |
| 92 | defaultFolioStyle | `Float` | Folio style to be used for all guests |
| 93 | defaultGuestAddress | `String` | Default guest address format. |
| 94 | defaultMembershipType | `String` | Future use |
| 95 | defaultPostingRoom | `String` | Future use |
| 96 | defaultPropertyAddress | `String` | Default property address format. |
| 97 | defaultRateCode | `String` | Future use |
| 98 | defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| 99 | defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| 100 | defaultRegistrationCard | `String` | Default registration card for the property. |
| 101 | defaultReservationType | `String` | The Default reservation type for this property |
| 102 | deletedFlag | `String` | Deleted Flag |
| 103 | depositLedgerTrxCode | `String` | Future use |
| 104 | destinationId | `String` | Destination ID |
| 105 | dfltPkgTranCode | `String` | Future use |
| 106 | dfltTranCodeRateCode | `String` | Future use |
| 107 | directions | `String` | Internal |
| 108 | dirsales | `String` | Future use |
| 109 | disableLoginYN | `String` | LOGIN into the application is disabled. |
| 110 | doubleRooms | `Float` | Number of double rooms. |
| 111 | downloadRestYN | `String` | Download Rest YN |
| 112 | dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| 113 | email | `String` | Email id for the property. |
| 114 | endDate | `Date` | Future use. |
| 115 | exchangePostingType | `String` | Default Exchange posting status for the property |
| 116 | executiveFloorNumber | `String` | Floor number of executive floor. |
| 117 | expHotelCode | `String` | Hotel code used for third party exports |
| 118 | extExpFileLocation | `String` | Future use |
| 119 | extPropertyCode | `String` | Future use |
| 120 | externalSCYN | `String` | Indicates that the property uses an external SC system. |
| 121 | familyRooms | `Float` | Number of family rooms. |
| 122 | faxNoFormat | `String` | Fax number formats. |
| 123 | faxNumber | `String` | The fax phone number |
| 124 | fiscalEndDate | `Date` | Future use |
| 125 | fiscalPeriodType | `String` | Future use |
| 126 | fiscalStartDate | `Date` | Future use |
| 127 | fiscalYearBeginMonth | `Float` | Fiscal Year Begin Month |
| 128 | fiscalYearBeginYear | `Float` | Fiscal Year Begin Year |
| 129 | flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| 130 | flowCode | `String` | Future use |
| 131 | fnsTier | `String` | Property Free Nights Stay Tier. |
| 132 | folioLanguage1 | `String` | Other languages |
| 133 | folioLanguage2 | `String` | Other languages |
| 134 | folioLanguage3 | `String` | Other languages |
| 135 | folioLanguage4 | `String` | Other languages |
| 136 | genmgr | `String` | Future use |
| 137 | groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| 138 | guestLookupTimeout | `Float` | Future use |
| 139 | guestRoomElevators | `Float` | Number of guest elevators. |
| 140 | guestRoomFloors | `Float` | Total of guest rooms floors. |
| 141 | hotelCode | `String` | Future use |
| 142 | hotelFC | `String` | Future use |
| 143 | hotelID | `String` | Hotel id |
| 144 | hotelType | `String` | Future use |
| 145 | iMGDirectionID | `Float` | Future use |
| 146 | iMGHotelID | `Float` | Future use |
| 147 | iMGMapID | `Float` | Future use |
| 148 | inactiveDaysForGuestProfile | `Float` | Future use |
| 149 | inactiveFlag | `String` | Inactive Flag |
| 150 | individualAddressType | `String` | Future use |
| 151 | individualPhoneType | `String` | Future use |
| 152 | individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| 153 | insertDate | `DateTime` | The date the record was created |
| 154 | insertUser | `Float` | The user that created the record |
| 155 | intTaxIncludedYN | `String` | Int Tax Included YN |
| 156 | inventoryYN | `String` | Future use |
| 157 | jRNUpdateDate | `Date` | JRN Update Date |
| 158 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 159 | keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| 160 | latitude | `Float` | Latitude of the property in decimal |
| 161 | leadsend | `String` | Future use |
| 162 | legalOwner | `String` | The owner who owns this property |
| 163 | locationID | `String` | The property that the record belongs to |
| 164 | longDateFormat | `String` | Long date format for the property. |
| 165 | longStayControl | `Float` | The default length of stay |
| 166 | longitude | `Float` | Longitude of the property in decimal |
| 167 | maxAdultsInFamilyRoom | `Float` | Maximum adults in family rooms. |
| 168 | maxChildrenInFamilyRoom | `Float` | Maximum children in family rooms. |
| 169 | maxOccupancy | `Float` | Future use |
| 170 | maximumCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| 171 | mbsSupportedYN | `String` | Indicates whether the property supports MBS. Used in some file exports. |
| 172 | meetRooms | `Float` | Future use |
| 173 | meetSeats | `Float` | Future use |
| 174 | meetSpace | `Float` | Future use |
| 175 | meetingFC | `String` | Future use |
| 176 | minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| 177 | nameIdLink | `Float` | Internal |
| 178 | nightAuditCashierID | `String` | Future use |
| 179 | nonSmokingRooms | `Float` | Number of non smoking rooms. |
| 180 | noteDetails | `String` | Notes for the property |
| 181 | numberOfBeds | `Float` | Total number of beds in this property |
| 182 | numberOfFloors | `Float` | Total number of floors in this property |
| 183 | numberOfRooms | `Float` | Number of Rooms |
| 184 | opusCurrencyCode | `String` | Future use |
| 185 | organizationID | `Float` | Organization ID |
| 186 | organizationInternalID | `Float` | Organization Internal ID |
| 187 | ownership | `String` | Future use |
| 188 | packageLoss | `String` | Package Loss code for a particular package |
| 189 | packageProfit | `String` | Package Profit code for a particular Package |
| 190 | parentOrgCode | `String` | Parent Org Code |
| 191 | passerbyMarket | `String` | Market code |
| 192 | passerbySource | `String` | Source code |
| 193 | path | `String` | Path |
| 194 | paymentDate | `DateTime` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| 195 | perReservationRoomLimit | `Float` | Future use |
| 196 | phoneNumber | `String` | The direct dial phone number of this property |
| 197 | postalCode | `String` | The postal code of this property. |
| 198 | primaryKeyID | `Float` | Primary Key ID |
| 199 | proinfoUrl | `String` | URL where property information is located. |
| 200 | propMapUrl | `String` | Property MAP URL. |
| 201 | propPicUrl | `String` | Property picture URL. |
| 202 | propertyCode | `String` | The property that the record belongs to |
| 203 | propertyName | `String` | The name of this property. |
| 204 | propertyType | `String` | Type of resort. |
| 205 | quotedCurrency | `String` | Future use |
| 206 | rNAInsertdate | `DateTime` | RNA Insert Date |
| 207 | rNAUpdatedate | `DateTime` | RNA Update Date |
| 208 | reconcileDate | `DateTime` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| 209 | regionCode | `String` | Future use |
| 210 | regionDescription | `String` | Description of the Region. |
| 211 | restaurant | `Float` | Future use |
| 212 | rhythmSheets | `Float` | Total number of Sheets |
| 213 | rhythmTowels | `Float` | Total number of Towels |
| 214 | roomAmenities | `String` | Room amenity. |
| 215 | sGLNum | `String` | Future use |
| 216 | sGLRate1 | `Float` | Future use |
| 217 | sGLRate2 | `Float` | Future use |
| 218 | sUINum | `String` | Future use |
| 219 | sUIRate1 | `Float` | Future use |
| 220 | sUIRate2 | `Float` | Future use |
| 221 | saveProfiles | `Float` | To store number of days before deleting the gest profile |
| 222 | scriptID | `Float` | Future use |
| 223 | season1 | `String` | Future use |
| 224 | season2 | `String` | Future use |
| 225 | season3 | `String` | Future use |
| 226 | season4 | `String` | Future use |
| 227 | season5 | `String` | Future use |
| 228 | sendLeadAsBooking | `String` | Indicates that the property accepts leads as bookings. |
| 229 | shopDescription | `String` | Shop description. |
| 230 | shortDateFormat | `String` | Short date format for the property. |
| 231 | singleRooms | `Float` | Number of single rooms. |
| 232 | sourceCommission | `String` | For default commission percentage |
| 233 | state | `String` | The state in which this property is located. |
| 234 | stateDescription | `String` | Description of the state. |
| 235 | street | `String` | The street of the property. |
| 236 | suites | `Float` | Number of suites. |
| 237 | summCurrencyCode | `String` | Internal |
| 238 | tACommission | `String` | For default commission percentage |
| 239 | tPLNum | `String` | Future use |
| 240 | tPLRate1 | `Float` | Future use |
| 241 | tPLRate2 | `Float` | Future use |
| 242 | telephoneNoFormat | `String` | Formats for telephone number |
| 243 | thousandSeparator | `String` | Separator for monetory values |
| 244 | timeFormat | `String` | Default time format for the property. |
| 245 | timeZone | `String` | Time zone region selected by the employee. |
| 246 | tollFree | `String` | Toll free telephone number. |
| 247 | totalRooms | `Float` | Future use |
| 248 | touristNumber | `String` | Tourist Number |
| 249 | translateMulticharYN | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| 250 | turnawayCode | `String` | Turnaway code for the property. |
| 251 | twinRooms | `Float` | Number of twin rooms. |
| 252 | updateDate | `DateTime` | The date the record was modified |
| 253 | updateUser | `Float` | The user that modified the record |
| 254 | vatID | `String` | VAT ID of this property. |
| 255 | videoCheckoutPrinter | `String` | Future use |
| 256 | videoCheckoutStart | `DateTime` | Video check out start time. |
| 257 | videoCheckoutStop | `DateTime` | Video check out end time. |
| 258 | wakeUpDelay | `Float` | Future use |
| 259 | warningAmount | `Float` | Amount at which warning is raised. |
| 260 | web | `String` | Webaddress of the property |
| 261 | weekendDays | `String` | Weekend days for the property. |
| 262 | zeroInvPurDays | `Float` | Internal |

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

### SimpleReportsBookingBlocksQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| saleseventbusinessblockinformationdetailsChainCode | `StringInput` | CHAIN_CODE<br>`@conditionalInputPair(pair: 1)` |
| scbusblockinfoDetailsAgentNameId | `FloatInput` | Agent Name ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsAllotmentCode | `StringInput` | Allotment Code<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsBeginDate | `DateInput` | Begin Date<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsBookingStatus | `StringInput` | Booking Status<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsBookingStatusorder | `FloatInput` | Booking Statusorder<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsBusblockId | `FloatInput` | Busblock ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsCXchangeDate | `DateInput` | Central Xchange Date<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsCompanyNameId | `FloatInput` | Company Name ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsContactNameId | `FloatInput` | Contact Name ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| scbusblockinfoDetailsEndDate | `DateInput` | End Date<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsGuaranteeCode | `StringInput` | Guarantee Code<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsInsertDate | `DateTimeInput` | Insert Date<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsInsertUser | `FloatInput` | Insert User<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID.<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsMarketCode | `StringInput` | Market Code<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block.<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| scbusblockinfoDetailsOwner | `FloatInput` | Owner<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsOwnerCode | `StringInput` | Owner Code<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsResort | `StringInput` | Code to uniquely identify the Property<br>`@conditionalInputPair(pair: 1)` |
| scbusblockinfoDetailsRateCode | `StringInput` | Rate Code<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsShoulderBeginDate | `DateInput` | Shoulder Begin Date |
| scbusblockinfoDetailsShoulderEndDate | `DateInput` | Shoulder End Date |
| scbusblockinfoDetailsSourceNameId | `FloatInput` | Source Name ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsSuperBlockId | `FloatInput` | Parent Block ID<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsSuperBlockResort | `StringInput` | Parent Resort<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search<br>`@conditionalInputPair(pair: 2)` |
| scbusblockinfoDetailsUpdateDate | `DateTimeInput` | Update Date<br>`@conditionalInputPair(pair: 2)` |
| resortDetailsResort | `StringInput` | The property that the record belongs to |
| resortDetailsArAcctNoFormat | `StringInput` | Number format of AR account no. |
| resortDetailsArAcctNoMandYn | `StringInput` | Specifies if the AR acct No is mandatory(Y/N) |
| resortDetailsArAgent | `StringInput` | Default Account Type for an Agent for the Property |
| resortDetailsArBalTrxCode | `StringInput` | Internal |
| resortDetailsArCompany | `StringInput` | Default Account Type for a Company for the Property |
| resortDetailsArCreditTrxCode | `StringInput` | Internal |
| resortDetailsArGroups | `StringInput` | Default Account Type for a Group for the Property |
| resortDetailsArIndividuals | `StringInput` | Default Account Type for Individual for the Property |
| resortDetailsArSettleCode | `StringInput` | Internal |
| resortDetailsArTypewriter | `StringInput` | Internal |
| resortDetailsAccessCode | `StringInput` | Access Code |
| resortDetailsQtyHandicappedRooms | `FloatInput` | Number of handicapped rooms. |
| resortDetailsAgingLevel1 | `FloatInput` | Aging bucket 1 |
| resortDetailsAgingLevel2 | `FloatInput` | Aging bucket 2 |
| resortDetailsAgingLevel3 | `FloatInput` | Aging bucket 3 |
| resortDetailsAgingLevel4 | `FloatInput` | Aging bucket 4 |
| resortDetailsAgingLevel5 | `FloatInput` | Aging bucket 3 |
| resortDetailsAirport | `StringInput` | The Airport Code for the airport near the property |
| resortDetailsAirportDistance | `StringInput` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| resortDetailsAirportTime | `StringInput` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| resortDetailsAllowLoginYn | `StringInput` | Allow loggin in to this resort(Y/N) |
| resortDetailsAllowancePeriodAdj | `StringInput` | Period for the allowance |
| resortDetailsAwardsTimeout | `FloatInput` | Internal |
| resortDetailsBrArea | `StringInput` | Ball Room Area |
| resortDetailsBrSeats | `FloatInput` | No of Ballroom Seats |
| resortDetailsBaseLanguage | `StringInput` | The base language of the Hotel |
| resortDetailsBlock | `StringInput` | It contains the reservation type to be used when making group block |
| resortDetailsBrandCode | `StringInput` | Brand Code of the property. |
| resortDetailsBudgetMonth | `FloatInput` | Financial Year of the Property |
| resortDetailsBeginDate | `DateInput` | The date this resort becomes valid for use by the system |
| resortDetailsBusinessId | `StringInput` | Value for the parameter. |
| resortDetailsBusinessRegCode | `StringInput` | Value for the parameter. |
| resortDetailsCroCode | `StringInput` | Code for the CRO |
| resortDetailsCashShiftDrop | `StringInput` | Internal |
| resortDetailsCateringCurrencyCode | `StringInput` | Catering Currency Code used when Catering Currency differs from base currency. |
| resortDetailsCateringCurrencyFormat | `StringInput` | Catering currency format. |
| resortDetailsCXchangeDate | `DateInput` | Central  Exchange Date |
| resortDetailsCXchangeRate | `FloatInput` | Central  Exchange Rate |
| resortDetailsCCreditLimit | `FloatInput` | Central Credit Limit |
| resortDetailsCentralCurrencyCode | `StringInput` | Central Currency Code |
| resortDetailsCentralCurrencyDesc | `StringInput` | Central Currency Description |
| resortDetailsCDblRate2 | `FloatInput` | Central Double Rate2 |
| resortDetailsCDblRate1 | `FloatInput` | Central Double Rate1 |
| resortDetailsRepPasserbyMarket | `StringInput` | Central Passerby Market |
| resortDetailsRepPasserbySource | `StringInput` | Central Passerby Source |
| resortDetailsRepResortType | `StringInput` | Central Property Type |
| resortDetailsCSglRate1 | `FloatInput` | Central Sgl Rate1 |
| resortDetailsCSglRate2 | `FloatInput` | Central Sgl Rate 2 |
| resortDetailsRepState | `StringInput` | Central State |
| resortDetailsRepStateDesc | `StringInput` | Central State Description |
| resortDetailsCSuiRate1 | `FloatInput` | Central Sui Rate1 |
| resortDetailsCSuiRate2 | `FloatInput` | Central Sui Rate 2 |
| resortDetailsCTplRate1 | `FloatInput` | Central Tpl Rate1 |
| resortDetailsCTplRate2 | `FloatInput` | Central Tpl Rate 2 |
| resortDetailsCWarningAmount | `FloatInput` | Central Warning Amount |
| resortDetailsChainCode | `StringInput` | Chain Code for the chain to which the property belongs |
| resortDetailsChainDescription | `StringInput` | The description of this chain. |
| resortDetailsChainMode | `StringInput` | Chain Mode |
| resortDetailsCheckExgPaidout | `StringInput` | Internal |
| resortDetailsCheckOutTime | `DateTimeInput` | The Hotel official check out time |
| resortDetailsCheckShiftDrop | `StringInput` | Internal |
| resortDetailsCheckTrxcode | `StringInput` | Internal |
| resortDetailsCheckInTime | `DateTimeInput` | The Hotel official check intime |
| resortDetailsCity | `StringInput` | The physical city in which this property resides. |
| resortDetailsCityDescription | `StringInput` | City Description |
| resortDetailsComAddress | `StringInput` | Internal |
| resortDetailsComMethod | `StringInput` | Internal |
| resortDetailsComNameXrefId | `FloatInput` | Internal |
| resortDetailsCompanyAddressType | `StringInput` | Internal |
| resortDetailsCompanyPhoneType | `StringInput` | Internal |
| resortDetailsConfigurationMode | `StringInput` | Internal |
| resortDetailsConfirmRegcardPrinter | `StringInput` | Internal |
| resortDetailsQtyConnectingRooms | `FloatInput` | Number of connecting rooms. |
| resortDetailsAllContacts | `StringInput` | The unique name of application user |
| resortDetailsCopies | `FloatInput` | Number of copies to be printed |
| resortDetailsCountryName | `StringInput` | Country name. |
| resortDetailsCountryCode | `StringInput` | The name of the country in which this property resides. |
| resortDetailsCountryMode | `StringInput` | Value for the parameter. |
| resortDetailsCreditLimit | `FloatInput` | The default credit limit for guests. |
| resortDetailsCurrencyCode | `StringInput` | Currency Code. |
| resortDetailsCurrencySymbol | `StringInput` | Currency Symbol like $ or EURO symbol |
| resortDetailsCurrencyName | `StringInput` | A description of this currency. |
| resortDetailsLocalCurrencyFormat | `StringInput` | Format for the local currency. |
| resortDetailsCurtainColor | `StringInput` | Color that of the background |
| resortDetailsDsi | `FloatInput` | DSI |
| resortDetailsDateForAging | `StringInput` | Date the aging should begin |
| resortDetailsDateSeparator | `StringInput` | Type of separator to distinguish between DD MM and YYYY |
| resortDetailsDecimalPlaces | `FloatInput` | Number of places for the default currency |
| resortDetailsDecimalSeparator | `StringInput` | Type of decimal separator |
| resortDetailsCurrencyDecimals | `FloatInput` | Number of decimals to designate currency |
| resortDetailsDefaultFolioStyle | `FloatInput` | Folio style to be used for all guests |
| resortDetailsDefaultGuestAddress | `StringInput` | Default guest address format. |
| resortDetailsDefaultMembershipType | `StringInput` | Future use |
| resortDetailsDefaultPostingRoom | `StringInput` | Future use |
| resortDetailsDefaultPropertyAddress | `StringInput` | Default property address format. |
| resortDetailsDefaultRateCode | `StringInput` | Future use |
| resortDetailsDefaultRatecodePcr | `StringInput` | Rate code used to default a PCR rate code used in FIT Contracts. |
| resortDetailsDefaultRatecodeRack | `StringInput` | Rate code used to default a RACK rate code used for FIT Contracts. |
| resortDetailsDefaultRegistrationCard | `StringInput` | Default registration card for the property. |
| resortDetailsDefaultReservationType | `StringInput` | The Default reservation type for this property |
| resortDetailsDeletedFlag | `StringInput` | Deleted Flag |
| resortDetailsDepositLedTrxCode | `StringInput` | Future use |
| resortDetailsDestinationId | `StringInput` | Destination ID |
| resortDetailsDfltPkgTranCode | `StringInput` | Future use |
| resortDetailsDfltTranCodeRateCode | `StringInput` | Future use |
| resortDetailsDirections | `StringInput` | Internal |
| resortDetailsDirsales | `StringInput` | Future use |
| resortDetailsDisableLoginYn | `StringInput` | LOGIN into the application is disabled. |
| resortDetailsQtyDoubleRooms | `FloatInput` | Number of double rooms. |
| resortDetailsDownloadRestYn | `StringInput` | Download Rest YN |
| resortDetailsDutyManagerPager | `StringInput` | Pager number for the Manager on duty for the property. |
| resortDetailsEmail | `StringInput` | Email id for the property. |
| resortDetailsEndDate | `DateInput` | Future use. |
| resortDetailsExchangePostingType | `StringInput` | Default Exchange posting status for the property |
| resortDetailsFloorNumExecutiveFloor | `StringInput` | Floor number of executive floor. |
| resortDetailsExpHotelCode | `StringInput` | Hotel code used for third party exports |
| resortDetailsExtExpFileLocation | `StringInput` | Future use |
| resortDetailsExtPropertyCode | `StringInput` | Future use |
| resortDetailsExternalScYn | `StringInput` | Indicates that the property uses an external SC system. |
| resortDetailsQtyFamilyRooms | `FloatInput` | Number of family rooms. |
| resortDetailsFaxNoFormat | `StringInput` | Fax number formats. |
| resortDetailsFax | `StringInput` | The fax phone number |
| resortDetailsFiscalEndDate | `DateInput` | Future use |
| resortDetailsFiscalPeriodType | `StringInput` | Future use |
| resortDetailsFiscalStartDate | `DateInput` | Future use |
| resortDetailsFiscalStartMonth | `FloatInput` | Fiscal Year Begin Month |
| resortDetailsFiscalStartYear | `FloatInput` | Fiscal Year Begin Year |
| resortDetailsFlags | `StringInput` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| resortDetailsFlowCode | `StringInput` | Future use |
| resortDetailsFnsTier | `StringInput` | Property Free Nights Stay Tier. |
| resortDetailsFolioLanguage1 | `StringInput` | Other languages |
| resortDetailsFolioLanguage2 | `StringInput` | Other languages |
| resortDetailsFolioLanguage3 | `StringInput` | Other languages |
| resortDetailsFolioLanguage4 | `StringInput` | Other languages |
| resortDetailsGenmgr | `StringInput` | Future use |
| resortDetailsGroupRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for Group |
| resortDetailsGuestLookupTimeout | `FloatInput` | Future use |
| resortDetailsQtyGuestElevators | `FloatInput` | Number of guest elevators. |
| resortDetailsQtyGuestRoomFloors | `FloatInput` | Total of guest rooms floors. |
| resortDetailsHotelCode | `StringInput` | Future use |
| resortDetailsHotelFc | `StringInput` | Future use |
| resortDetailsHotelId | `StringInput` | Hotel id |
| resortDetailsHotelType | `StringInput` | Future use |
| resortDetailsImgDirectionId | `FloatInput` | Future use |
| resortDetailsImgHotelId | `FloatInput` | Future use |
| resortDetailsImgMapId | `FloatInput` | Future use |
| resortDetailsInactiveDaysForGuestProfil | `FloatInput` | Future use |
| resortDetailsInactiveFlag | `StringInput` | Inactive Flag |
| resortDetailsIndividualAddressType | `StringInput` | Future use |
| resortDetailsIndividualPhoneType | `StringInput` | Future use |
| resortDetailsIndividualRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for group |
| resortDetailsInsertDate | `DateTimeInput` | The date the record was created |
| resortDetailsInsertUser | `FloatInput` | The user that created the record |
| resortDetailsIntTaxIncludedYn | `StringInput` | Int Tax Included YN |
| resortDetailsInventoryYn | `StringInput` | Future use |
| resortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortDetailsKeepAvailability | `FloatInput` | To calculate the entire availability of the Hotel for future reservations |
| resortDetailsLatitude | `FloatInput` | Latitude of the property in decimal |
| resortDetailsLeadsend | `StringInput` | Future use |
| resortDetailsLegalOwner | `StringInput` | The owner who owns this property |
| resortDetailsLocationId | `StringInput` | The property that the record belongs to |
| resortDetailsLongDateFormat | `StringInput` | Long date format for the property. |
| resortDetailsLongStayControl | `FloatInput` | The default length of stay |
| resortDetailsLongitude | `FloatInput` | Longitude of the property in decimal |
| resortDetailsMaxAdultsFamilyRoom | `FloatInput` | Maximum adults in family rooms. |
| resortDetailsMaxChildrenFamilyRoom | `FloatInput` | Maximum children in family rooms. |
| resortDetailsMaxOccupancy | `FloatInput` | Future use |
| resortDetailsMaxcreditdays | `FloatInput` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| resortDetailsMbsSupportedYn | `StringInput` | Indicates whether the property supports MBS. Used in some file exports. |
| resortDetailsMeetRooms | `FloatInput` | Future use |
| resortDetailsMeetSeats | `FloatInput` | Future use |
| resortDetailsMeetSpace | `FloatInput` | Future use |
| resortDetailsMeetingFc | `StringInput` | Future use |
| resortDetailsMinDaysBet2ReminderLetter | `FloatInput` | Minimum days for reminder letter. |
| resortDetailsNameIdLink | `FloatInput` | Internal |
| resortDetailsNightAuditCashierId | `StringInput` | Future use |
| resortDetailsQtyNonSmokingRooms | `FloatInput` | Number of non smoking rooms. |
| resortDetailsNotes | `StringInput` | Notes for the property |
| resortDetailsNumberBeds | `FloatInput` | Total number of beds in this property |
| resortDetailsNumberFloors | `FloatInput` | Total number of floors in this property |
| resortDetailsNumberRooms | `FloatInput` | Number of Rooms |
| resortDetailsOpusCurrencyCode | `StringInput` | Future use |
| resortDetailsOrganizationId | `FloatInput` | Organization ID |
| resortDetailsOrganizationid | `FloatInput` | Organization Internal ID |
| resortDetailsOwnership | `StringInput` | Future use |
| resortDetailsPackageLoss | `StringInput` | Package Loss code for a particular package |
| resortDetailsPackageProfit | `StringInput` | Package Profit code for a particular Package |
| resortDetailsParentOrgCode | `StringInput` | Parent Org Code |
| resortDetailsPasserbyMarket | `StringInput` | Market code |
| resortDetailsPasserbySource | `StringInput` | Source code |
| resortDetailsPath | `StringInput` | Path |
| resortDetailsPaymentDate | `DateTimeInput` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| resortDetailsPerReservationRoomLimit | `FloatInput` | Future use |
| resortDetailsTelephone | `StringInput` | The direct dial phone number of this property |
| resortDetailsPostCode | `StringInput` | The postal code of this property. |
| resortDetailsPkid | `FloatInput` | Primary Key ID |
| resortDetailsProinfoUrl | `StringInput` | URL where property information is located. |
| resortDetailsPropMapUrl | `StringInput` | Property MAP URL. |
| resortDetailsPropPicUrl | `StringInput` | Property picture URL. |
| resortDetailsLocationid | `StringInput` | The property that the record belongs to |
| resortDetailsName | `StringInput` | The name of this property. |
| resortDetailsResortType | `StringInput` | Type of resort. |
| resortDetailsQuotedCurrency | `StringInput` | Future use |
| resortDetailsRnaInsertdate | `DateTimeInput` | RNA Insert Date |
| resortDetailsRnaUpdatedate | `DateTimeInput` | RNA Update Date |
| resortDetailsReconcileDate | `DateTimeInput` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| resortDetailsRegionCode | `StringInput` | Future use |
| resortDetailsRegionDescription | `StringInput` | Description of the Region. |
| resortDetailsRestaurant | `FloatInput` | Future use |
| resortDetailsRhythmSheets | `FloatInput` | Total number of Sheets |
| resortDetailsRhythmTowels | `FloatInput` | Total number of Towels |
| resortDetailsRoomAmenity | `StringInput` | Room amenity. |
| resortDetailsSglNum | `StringInput` | Future use |
| resortDetailsSglRate1 | `FloatInput` | Future use |
| resortDetailsSglRate2 | `FloatInput` | Future use |
| resortDetailsSuiNum | `StringInput` | Future use |
| resortDetailsSuiRate1 | `FloatInput` | Future use |
| resortDetailsSuiRate2 | `FloatInput` | Future use |
| resortDetailsSaveProfiles | `FloatInput` | To store number of days before deleting the gest profile |
| resortDetailsScriptId | `FloatInput` | Future use |
| resortDetailsSeason1 | `StringInput` | Future use |
| resortDetailsSeason2 | `StringInput` | Future use |
| resortDetailsSeason3 | `StringInput` | Future use |
| resortDetailsSeason4 | `StringInput` | Future use |
| resortDetailsSeason5 | `StringInput` | Future use |
| resortDetailsSendLeadAsBooking | `StringInput` | Indicates that the property accepts leads as bookings. |
| resortDetailsShopDescription | `StringInput` | Shop description. |
| resortDetailsShortDateFormat | `StringInput` | Short date format for the property. |
| resortDetailsQtySingleRooms | `FloatInput` | Number of single rooms. |
| resortDetailsSourceCommission | `StringInput` | For default commission percentage |
| resortDetailsState | `StringInput` | The state in which this property is located. |
| resortDetailsStateDesc | `StringInput` | Description of the state. |
| resortDetailsStreet | `StringInput` | The street of the property. |
| resortDetailsQtySuites | `FloatInput` | Number of suites. |
| resortDetailsSummCurrencyCode | `StringInput` | Internal |
| resortDetailsTaCommission | `StringInput` | For default commission percentage |
| resortDetailsTplNum | `StringInput` | Future use |
| resortDetailsTplRate1 | `FloatInput` | Future use |
| resortDetailsTplRate2 | `FloatInput` | Future use |
| resortDetailsTelephoneNoFormat | `StringInput` | Formats for telephone number |
| resortDetailsThousandSeparator | `StringInput` | Separator for monetory values |
| resortDetailsTimeFormat | `StringInput` | Default time format for the property. |
| resortDetailsTimezoneRegion | `StringInput` | Time zone region selected by the employee. |
| resortDetailsTollfree | `StringInput` | Toll free telephone number. |
| resortDetailsTotRooms | `FloatInput` | Future use |
| resortDetailsTouristNumber | `StringInput` | Tourist Number |
| resortDetailsTranslateMulticharYn | `StringInput` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| resortDetailsTurnawayCode | `StringInput` | Turnaway code for the property. |
| resortDetailsQtyTwinRooms | `FloatInput` | Number of twin rooms. |
| resortDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| resortDetailsUpdateUser | `FloatInput` | The user that modified the record |
| resortDetailsVatId | `StringInput` | VAT ID of this property. |
| resortDetailsVideocheckoutPrinter | `StringInput` | Future use |
| resortDetailsVideoCoStart | `DateTimeInput` | Video check out start time. |
| resortDetailsVideoCoStop | `DateTimeInput` | Video check out end time. |
| resortDetailsWakeUpDelay | `FloatInput` | Future use |
| resortDetailsWarningAmount | `FloatInput` | Amount at which warning is raised. |
| resortDetailsWebaddress | `StringInput` | Webaddress of the property |
| resortDetailsWeekendDays | `StringInput` | Weekend days for the property. |
| resortDetailsZeroInvPurDays | `FloatInput` | Internal |
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- saleseventbusinessblockinformationdetailsChainCode
- scbusblockinfoDetailsResort

**`conditionalInputPair(pair: 2)`**
- scbusblockinfoDetailsAgentNameId
- scbusblockinfoDetailsAllotmentCode
- scbusblockinfoDetailsAllotmentHeaderId
- scbusblockinfoDetailsBeginDate
- scbusblockinfoDetailsBookingStatus
- scbusblockinfoDetailsBookingStatusorder
- scbusblockinfoDetailsBusblockId
- scbusblockinfoDetailsCXchangeDate
- scbusblockinfoDetailsCompanyNameId
- scbusblockinfoDetailsContactNameId
- scbusblockinfoDetailsEndDate
- scbusblockinfoDetailsGuaranteeCode
- scbusblockinfoDetailsInsertDate
- scbusblockinfoDetailsInsertUser
- scbusblockinfoDetailsIsacOpptyId
- scbusblockinfoDetailsJrnupdatedttm
- scbusblockinfoDetailsMarketCode
- scbusblockinfoDetailsMasterNameId
- scbusblockinfoDetailsOwner
- scbusblockinfoDetailsOwnerCode
- scbusblockinfoDetailsRateCode
- scbusblockinfoDetailsSourceNameId
- scbusblockinfoDetailsSuperBlockId
- scbusblockinfoDetailsSuperBlockResort
- scbusblockinfoDetailsUdescription
- scbusblockinfoDetailsUpdateDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query simpleReportsBookingBlocks($input: SimpleReportsBookingBlocksQueryArgumentsType!) {
  simpleReportsBookingBlocks(input: $input) @stream {
    salesEventBusinessBlockInformationDetails {
      chainCode
      accountActionCode
      accountActiveYN
      accountAddressType
      accountAddress1
      accountAddress2
      accountAlternateLanguage
      accountAlternateLanguageDesc
      accountAlternateSalutation
      accountAlternateTitle
      accountArNumber
      accountAvailoverYN
      accountBlMsg
      accountBookingId
      accountCblIndividual
      accountCity
      accountCityExt
      accountCommissionCode
      accountCompetitionCode
      accountCountry
      accountCountryDesc
      accountDsi
      accountEmail
      accountFax
      accountHistoryYN
      accountHoldCode
      accountIATACompType
      accountId
      accountIndustryCode
      accountKeyword
      accountLanguage
      accountLanguageDesc
      accountLinkId
      accountLinkType
      accountMailList
      accountMailType
      accountMarkets
      accountName
      accountNameKeywords
      accountNameType
      accountName2
      accountName3
      accountOrganizationid
      accountPhone
      accountPhoneId
      accountPhoneNumber
      accountPrimaryYN
      accountPriority
      accountProductInterest
      accountProperty
      accountRelationship
      accountRelationshipDesc
      accountRepActionCode
      accountRepCompetionCode
      accountRepIATACompType
      accountRepIndustryCode
      accountRepMarkets
      accountRepNameType
      accountRepScope
      accountRepScopeCity
      accountRepSource
      accountRepStateCode
      accountRepStateDescription
      accountRepTerritory
      accountRepType
      accountRoomsPotential
      accountScope
      accountScopeCity
      accountSname
      accountSource
      accountSrepCode
      accountState
      accountStateDesc
      accountSxname
      accountTerritory
      accountType
      accountXdisplayName
      accountXenvelopeGreeting
      accountXfirstName
      accountZipcode
      actionId
      agentActiveYn
      agentAddressType
      agentAddress1
      agentAddress2
      agentAlternateLanguage
      agentAlternateLanguageDesc
      agentAlternateSalutation
      agentAlternateTitle
      agentArNumber
      agentAuSrepCode
      agentAvailabilityOverride
      agentBookingId
      agentCblInd
      agentCity
      agentCityExt
      agentConActionCode
      agentConActiveYn
      agentConAddressType
      agentConAddress1
      agentConAddress2
      agentConAddress3
      agentConAddress4
      agentConAlternateLanguage
      agentConAlternateLanguageDesc
      agentConAlternateSalutation
      agentConAlternateTitle
      agentConArNumber
      agentConAuSrepCode
      agentConAvailabilityOverride
      agentConBirthDate
      agentConBirthDateStr
      agentConBookingId
      agentConBusinessGreeting
      agentConCashBlInd
      agentConCity
      agentConCityExt
      agentConContactYn
      agentConCountry
      agentConCountryDesc
      agentConDepartment
      agentConDsi
      agentConEmail
      agentConFax
      agentConFirst
      agentConHistoryYn
      agentConIataCompType
      agentConId
      agentConIndustryCode
      agentConInfluence
      agentConLanguage
      agentConLanguageDesc
      agentConLast
      agentConLetterGreeting
      agentConLinkId
      agentConLinkType
      agentConMailType
      agentConMarkets
      agentConMiddle
      agentConName
      agentConNameType
      agentConName2
      agentConName3
      agentConOrganizationid
      agentConPhone
      agentConPosition
      agentConPrimaryYn
      agentConProductInterest
      agentConRelationship
      agentConRelationshipDesc
      agentConRepAccountType
      agentConRepAccountsource
      agentConRepActionCode
      agentConRepIATACompType
      agentConRepIndustryCode
      agentConRepInfluence
      agentConRepMarkets
      agentConRepNameType
      agentConRepScope
      agentConRepScopeCity
      agentConRepStateCode
      agentConRepStateDescription
      agentConRepTerritory
      agentConRepTitle
      agentConResort
      agentConScope
      agentConScopeCity
      agentConSfirst
      agentConSname
      agentConSrepId
      agentConSrepName
      agentConState
      agentConStateDesc
      agentConSxfirstName
      agentConSxname
      agentConTerritory
      agentConTitle
      agentConXfirst
      agentConXlast
      agentConXletterGreeting
      agentConXname
      agentConZipcode
      agentCountry
      agentCountryDesc
      agentDsi
      agentEmail
      agentFax
      agentHistoryYn
      agentIataCompType
      agentId
      agentIndustryCode
      agentLanguage
      agentLanguageDesc
      agentLinkId
      agentLinkType
      agentMailType
      agentMarkets
      agentName
      agentNameId
      agentNameType
      agentName2
      agentName3
      agentOrganizationid
      agentPhone
      agentPrimaryYn
      agentProductInterest
      agentRelationship
      agentRelationshipDesc
      agentRepStateCode
      agentResort
      agentScope
      agentScopeCity
      agentSname
      agentState
      agentStateDesc
      agentSxname
      agentTerritory
      agentXdisplayName
      agentXenvelopeGreeting
      agentXfirstName
      agentZipcode
      alias
      allOwners
      allotmentCode
      allotmentHeaderId
      allotmentOrigion
      allotmentType
      arrivalTime
      attendees
      avgPeoplePerRoom
      avgRateNet
      beginDate
      bookingStatus
      bookingStatusOrderby
      bookingStatusType
      bookingStatusorder
      bookingmethod
      bookingmethoddesc
      bookingtype
      breakfastDesc
      breakfastPrice
      breakfastYn
      busblockId
      busblockProperty
      cBreakfastPrice
      cCompRoomValue
      cExchangeDate
      cExchangeRate
      cMtgBudget
      cPorteragePrice
      cPotRoomRevenue
      cServiceCharge
      cTaxAmount
      cancelRule
      cancellationCode
      cancellationDate
      cancellationDescription
      cancellationNo
      catCanxCode
      catCanxDate
      catCanxNumber
      catCurrency
      catCutoff
      catDecision
      catExchange
      catFollowup
      catOwner
      catOwnerCode
      catOwnerEmail
      catOwnerFax
      catOwnerPhone
      catOwnerProperty
      catOwnerSrepname
      catOwnerTitle
      catOwners
      catQuoteCurrency
      catStatus
      catStatusOrderby
      catStatusType
      catStatusorder
      cateringCanxDesc
      cateringPkgsYn
      cateringonlyYn
      centralOwner
      channel
      commission
      compPerStayYn
      compRoomValue
      compRooms
      compRoomsFixedYn
      companyNameId
      competition
      conActionCode
      conActiveYn
      conAddressType
      conAddress1
      conAddress2
      conAddress3
      conAddress4
      conAlternateLanguage
      conAlternateLanguageDesc
      conAlternateSalutation
      conAlternateTitle
      conArNumber
      conAvailabilityOverride
      conBirthDate
      conBirthDateStr
      conBookingId
      conBusinessGreeting
      conCashBlInd
      conCity
      conCityExt
      conContactYn
      conCountry
      conCountryDesc
      conDepartment
      conDsi
      conFirst
      conHistoryYn
      conIataCompType
      conId
      conIndustryCode
      conInfluence
      conLanguage
      conLanguageDesc
      conLast
      conLetterGreeting
      conLinkId
      conLinkType
      conMailType
      conMarkets
      conMiddle
      conName
      conNameType
      conName2
      conName3
      conOrganizationid
      conPosition
      conPrimaryYn
      conProductInterest
      conRelationship
      conRelationshipDesc
      conRepActionCode
      conRepInfluence
      conRepMarkets
      conRepNameType
      conRepScope
      conRepScopeCity
      conRepStateCode
      conRepStateDescription
      conRepTerritory
      conRepTitle
      conResort
      conScope
      conScopeCity
      conSfirst
      conSname
      conSrepCode
      conSrepId
      conSrepName
      conState
      conStateDesc
      conSxfirstName
      conSxname
      conTerritory
      conTitle
      conXfirst
      conXlast
      conXletterGreeting
      conXname
      contactEmail
      contactFax
      contactNameId
      contactPhone
      contactZipcode
      contractNr
      conversionCode
      currencyCode
      dSI
      dateOpenedForPickup
      datePro
      dateTen
      defaultPmReservationNameId
      deletedflag
      departureTime
      description
      destination
      detailsOkYn
      distributedYn
      dmlSeqNumber
      downloadDate
      downloadResort
      downloadSrep
      dueDate
      elastic
      endDate
      eventsGuaranteedYn
      exchangePostingType
      exchangeRate
      externalLocked
      functiontype
      giid
      guaranteeCode
      iataCorpNumber
      inactiveDate
      info
      infoboard
      insertDate
      insertUser
      insertUserName
      invCutoffDate
      invCutoffDays
      isacOpptyId
      isacQuoteId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      leadOrigin
      leadSource
      linkDate
      lostToProperty
      mainmarket
      marEventType
      marHouseProtectYn
      marRollEndDateYn
      marketCode
      masterNameId
      methodDue
      mtgBudget
      nonCompete
      nonCompeteCode
      organizationID
      originalRateCode
      owner
      ownerCode
      ownerCodeSrepname
      ownerEmail
      ownerFax
      ownerPhone
      ownerResort
      ownerTitle
      paymentMethod
      peakRooms
      porteragePrice
      porterageYn
      printAccountActiveYN
      printAccountAddress1
      printAccountAddress2
      printAccountAddress3
      printAccountAddress4
      printAccountBookingId
      printAccountCity
      printAccountCityExt
      printAccountCountry
      printAccountCountryDesc
      printAccountDsi
      printAccountId
      printAccountLinkId
      printAccountLinkType
      printAccountName
      printAccountName2
      printAccountName3
      printAccountOrganizationid
      printAccountPhone
      printAccountPosition
      printAccountPrimaryYN
      printAccountProperty
      printAccountRepStateCode
      printAccountRepStateDescription
      printAccountRepTerritory
      printAccountScope
      printAccountScopeCity
      printAccountSname
      printAccountState
      printAccountStateDesc
      printAccountSxname
      printAccountTerritory
      printAccountXdisplayName
      printAccountXenvelopeGreeting
      printAccountXfirstName
      printAccountXname
      printAccountZipcode
      printConAddress1
      printConAddress2
      printConAddress3
      printConAddress4
      printConAlternateSalutation
      printConBusinessGreeting
      printConCity
      printConCityExt
      printConCountry
      printConCountryDesc
      printConDepartment
      printConDsi
      printConEmail
      printConFirst
      printConId
      printConLast
      printConLetterGreeting
      printConLinkId
      printConLinkType
      printConMiddle
      printConName
      printConName2
      printConName3
      printConOrganizationid
      printConPhone
      printConPosition
      printConPrimaryYn
      printConProductInterest
      printConRelationship
      printConRelationshipDesc
      printConRepStateCode
      printConRepTitle
      printConResort
      printConScope
      printConScopeCity
      printConSname
      printConState
      printConStateDesc
      printConSxname
      printConTerritory
      printConTitle
      printConXdisplayName
      printConXfirst
      printConXlast
      printConXletterGreeting
      printConZipcode
      profileDesc
      profileId
      program
      property
      rankingCode
      rateCode
      rateGuaranteedYn
      rateOverride
      rateOverrideReason
      rateProtection
      relatedResorts
      repBlockStatusDescription
      repBookingmethod
      repBookingmethodDescription
      repBookingtype
      repBsOrderBy
      repCateringOrderBy
      repCateringStatus
      repCateringStatusDescription
      repChannel
      repConversionCode
      repDestination
      repGuaranteeCode
      repMarketCode
      repNonCompeteCode
      repPaymentMethod
      repRankingCode
      repSourceCode
      representative
      reserveInventoryYn
      resortBooked
      revBlocked
      revBlockedNet
      revContracted
      rivMarketSegment
      rnaInsertDate
      rnaUpdateDate
      roomsBlocked
      roomsContracted
      roomsCurrency
      roomsDecision
      roomsExchange
      roomsFollowup
      roomsOwner
      roomsOwnerCode
      roomsOwnerEmail
      roomsOwnerFax
      roomsOwnerPhone
      roomsOwnerResort
      roomsOwnerSrepname
      roomsOwnerTitle
      roomsOwners
      roomsPerDay
      roomsQuoteCurr
      salesId
      sbegindate
      secConActionCode
      secConActiveYn
      secConAddress1
      secConAddress2
      secConAddress3
      secConAddress4
      secConAlternateLanguage
      secConAlternateLanguageDesc
      secConAlternateSalutation
      secConAlternateTitle
      secConBirthDate
      secConBirthDateStr
      secConBookingId
      secConBusinessGreeting
      secConCashBlInd
      secConCity
      secConCityExt
      secConContactYn
      secConCountry
      secConCountryDesc
      secConDepartment
      secConDsi
      secConEmail
      secConFax
      secConFirstName
      secConFullName
      secConId
      secConInfluence
      secConLanguage
      secConLanguageDesc
      secConLastName
      secConLetterGreeting
      secConLinkId
      secConLinkType
      secConMarkets
      secConMiddleName
      secConNameType
      secConName2
      secConName3
      secConOrganizationid
      secConPhone
      secConPosition
      secConPrimaryYn
      secConProductInterest
      secConRelationship
      secConRelationshipDesc
      secConRepActionCode
      secConRepInfluence
      secConRepMarkets
      secConRepNameType
      secConRepScope
      secConRepScopeCity
      secConRepStateCode
      secConRepStateDescription
      secConRepTerritory
      secConRepTitle
      secConResort
      secConScope
      secConScopeCity
      secConSfirst
      secConSname
      secConSrepCode
      secConSrepId
      secConSrepName
      secConState
      secConStateDesc
      secConSxfirstName
      secConSxname
      secConTerritory
      secConTitle
      secConXenvelopeGreeting
      secConXfirstName
      secConXfullName
      secConXlastName
      secConZipCode
      senddate
      sentDate
      serviceCharge
      shoulderBeginDate
      shoulderEndDate
      source
      sourceActiveYn
      sourceAddressType
      sourceAddress1
      sourceAddress2
      sourceAlternateLanguage
      sourceAlternateLanguageDesc
      sourceAlternateSalutation
      sourceAlternateTitle
      sourceBookingId
      sourceBusinessGreeting
      sourceCity
      sourceCityExt
      sourceConActionCode
      sourceConActiveYn
      sourceConAddressType
      sourceConAddress1
      sourceConAddress2
      sourceConAddress3
      sourceConAddress4
      sourceConAlternateLanguage
      sourceConAlternateLanguageDesc
      sourceConAlternateSalutation
      sourceConAlternateTitle
      sourceConArNumber
      sourceConAuSrepCode
      sourceConAvailabilityOverride
      sourceConBirthDate
      sourceConBirthDateStr
      sourceConBookingId
      sourceConBusinessGreeting
      sourceConCashBlInd
      sourceConCity
      sourceConCityExt
      sourceConContactYn
      sourceConCountry
      sourceConCountryDesc
      sourceConDepartment
      sourceConDsi
      sourceConEmail
      sourceConFax
      sourceConFirst
      sourceConHistoryYn
      sourceConIataCompType
      sourceConId
      sourceConIndustryCode
      sourceConInfluence
      sourceConLanguage
      sourceConLanguageDesc
      sourceConLast
      sourceConLetterGreeting
      sourceConLinkId
      sourceConLinkType
      sourceConMailType
      sourceConMarkets
      sourceConMiddle
      sourceConName
      sourceConNameType
      sourceConName2
      sourceConName3
      sourceConOrganizationid
      sourceConPhone
      sourceConPosition
      sourceConPrimaryYn
      sourceConProductInterest
      sourceConRelationship
      sourceConRelationshipDesc
      sourceConRepActionCode
      sourceConRepInfluence
      sourceConRepMarkets
      sourceConRepNameType
      sourceConRepScope
      sourceConRepScopeCity
      sourceConRepStateCode
      sourceConRepStateDescription
      sourceConRepTerritory
      sourceConRepTitle
      sourceConResort
      sourceConScope
      sourceConScopeCity
      sourceConSfirst
      sourceConSname
      sourceConSrepId
      sourceConSrepName
      sourceConState
      sourceConStateDesc
      sourceConSxfirstName
      sourceConSxname
      sourceConTerritory
      sourceConTitle
      sourceConXfirst
      sourceConXlast
      sourceConXletterGreeting
      sourceConXname
      sourceConZipcode
      sourceCountry
      sourceCountryDesc
      sourceDsi
      sourceEmail
      sourceFax
      sourceId
      sourceLinkId
      sourceLinkType
      sourceName
      sourceNameId
      sourceNameType
      sourceName2
      sourceName3
      sourceOrganizationid
      sourcePhone
      sourcePrimaryYn
      sourceRelationship
      sourceRelationshipDesc
      sourceRepStateCode
      sourceResort
      sourceScope
      sourceScopeCity
      sourceSname
      sourceState
      sourceStateDesc
      sourceSxname
      sourceTerritory
      sourceXdisplayName
      sourceXenvelopeGreeting
      sourceXfirstName
      sourceZipcode
      status
      superBlockId
      superBlockResort
      taxAmount
      tbdRates
      tentativeLevel
      tracecode
      udescription
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
      xaccName
      xagentName
      xsourceName
    }
    propertyPropertyDetails {
      property
      aRAccountNoFormat
      aRAccountNumberMandatoryYN
      aRAgent
      aRBalanceTrxCode
      aRCompany
      aRCreditTrxCode
      aRGroups
      aRIndividuals
      aRSettleCode
      aRTypewriter
      accessCode
      accessibleRooms
      agingLevel1
      agingLevel2
      agingLevel3
      agingLevel4
      agingLevel5
      airport
      airportDistance
      airportTime
      allowLoginYN
      allowancePeriodAdj
      awardsTimeout
      ballroomArea
      ballroomSeats
      baseLanguage
      block
      brandCode
      budgetMonth
      businessDate
      businessID
      businessRegistrationCode
      cROCODE
      cashShiftDrop
      cateringCurrencyCode
      cateringCurrencyFormat
      centralXchangeDate
      centralXchangeRate
      centralCreditLimit
      centralCurrencyCode
      centralCurrencyDescription
      centralDblRate2
      centralDblRate1
      centralPasserbyMarket
      centralPasserbySource
      centralPropertyType
      centralSglRate1
      centralSglRate2
      centralState
      centralStateDescription
      centralSuiRate1
      centralSuiRate2
      centralTplRate1
      centralTplRate2
      centralWarningAmount
      chainCode
      chainDescription
      chainMode
      checkExgPaidout
      checkOutTime
      checkShiftDrop
      checkTrxcode
      checkInTime
      city
      cityDescription
      comAddress
      comMethod
      comNameXrefId
      companyAddressType
      companyPhoneType
      configurationMode
      confirmRegcardPrinter
      connectingRooms
      contacts
      copies
      country
      countryCode
      countryMode
      creditLimit
      currencyCode
      currencyCodeSymbol
      currencyDescription
      currencyFormat
      curtainColor
      dSI
      dateForAging
      dateSeparator
      decimalPlaces
      decimalSeparator
      decimals
      defaultFolioStyle
      defaultGuestAddress
      defaultMembershipType
      defaultPostingRoom
      defaultPropertyAddress
      defaultRateCode
      defaultRatecodePcr
      defaultRatecodeRack
      defaultRegistrationCard
      defaultReservationType
      deletedFlag
      depositLedgerTrxCode
      destinationId
      dfltPkgTranCode
      dfltTranCodeRateCode
      directions
      dirsales
      disableLoginYN
      doubleRooms
      downloadRestYN
      dutyManagerPager
      email
      endDate
      exchangePostingType
      executiveFloorNumber
      expHotelCode
      extExpFileLocation
      extPropertyCode
      externalSCYN
      familyRooms
      faxNoFormat
      faxNumber
      fiscalEndDate
      fiscalPeriodType
      fiscalStartDate
      fiscalYearBeginMonth
      fiscalYearBeginYear
      flags
      flowCode
      fnsTier
      folioLanguage1
      folioLanguage2
      folioLanguage3
      folioLanguage4
      genmgr
      groupRoomWarning
      guestLookupTimeout
      guestRoomElevators
      guestRoomFloors
      hotelCode
      hotelFC
      hotelID
      hotelType
      iMGDirectionID
      iMGHotelID
      iMGMapID
      inactiveDaysForGuestProfile
      inactiveFlag
      individualAddressType
      individualPhoneType
      individualRoomWarning
      insertDate
      insertUser
      intTaxIncludedYN
      inventoryYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepAvailability
      latitude
      leadsend
      legalOwner
      locationID
      longDateFormat
      longStayControl
      longitude
      maxAdultsInFamilyRoom
      maxChildrenInFamilyRoom
      maxOccupancy
      maximumCreditDays
      mbsSupportedYN
      meetRooms
      meetSeats
      meetSpace
      meetingFC
      minDaysBet2ReminderLetter
      nameIdLink
      nightAuditCashierID
      nonSmokingRooms
      noteDetails
      numberOfBeds
      numberOfFloors
      numberOfRooms
      opusCurrencyCode
      organizationID
      organizationInternalID
      ownership
      packageLoss
      packageProfit
      parentOrgCode
      passerbyMarket
      passerbySource
      path
      paymentDate
      perReservationRoomLimit
      phoneNumber
      postalCode
      primaryKeyID
      proinfoUrl
      propMapUrl
      propPicUrl
      propertyCode
      propertyName
      propertyType
      quotedCurrency
      rNAInsertdate
      rNAUpdatedate
      reconcileDate
      regionCode
      regionDescription
      restaurant
      rhythmSheets
      rhythmTowels
      roomAmenities
      sGLNum
      sGLRate1
      sGLRate2
      sUINum
      sUIRate1
      sUIRate2
      saveProfiles
      scriptID
      season1
      season2
      season3
      season4
      season5
      sendLeadAsBooking
      shopDescription
      shortDateFormat
      singleRooms
      sourceCommission
      state
      stateDescription
      street
      suites
      summCurrencyCode
      tACommission
      tPLNum
      tPLRate1
      tPLRate2
      telephoneNoFormat
      thousandSeparator
      timeFormat
      timeZone
      tollFree
      totalRooms
      touristNumber
      translateMulticharYN
      turnawayCode
      twinRooms
      updateDate
      updateUser
      vatID
      videoCheckoutPrinter
      videoCheckoutStart
      videoCheckoutStop
      wakeUpDelay
      warningAmount
      web
      weekendDays
      zeroInvPurDays
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
sales_event_business_block_information_details_schema = {
    'chainCode': pl.Utf8,
    'accountActionCode': pl.Utf8,
    'accountActiveYN': pl.Utf8,
    'accountAddressType': pl.Utf8,
    'accountAddress1': pl.Utf8,
    'accountAddress2': pl.Utf8,
    'accountAlternateLanguage': pl.Utf8,
    'accountAlternateLanguageDesc': pl.Utf8,
    'accountAlternateSalutation': pl.Utf8,
    'accountAlternateTitle': pl.Utf8,
    'accountArNumber': pl.Utf8,
    'accountAvailoverYN': pl.Utf8,
    'accountBlMsg': pl.Utf8,
    'accountBookingId': pl.Float64,
    'accountCblIndividual': pl.Utf8,
    'accountCity': pl.Utf8,
    'accountCityExt': pl.Utf8,
    'accountCommissionCode': pl.Utf8,
    'accountCompetitionCode': pl.Utf8,
    'accountCountry': pl.Utf8,
    'accountCountryDesc': pl.Utf8,
    'accountDsi': pl.Float64,
    'accountEmail': pl.Utf8,
    'accountFax': pl.Utf8,
    'accountHistoryYN': pl.Utf8,
    'accountHoldCode': pl.Utf8,
    'accountIATACompType': pl.Utf8,
    'accountId': pl.Float64,
    'accountIndustryCode': pl.Utf8,
    'accountKeyword': pl.Utf8,
    'accountLanguage': pl.Utf8,
    'accountLanguageDesc': pl.Utf8,
    'accountLinkId': pl.Float64,
    'accountLinkType': pl.Utf8,
    'accountMailList': pl.Utf8,
    'accountMailType': pl.Utf8,
    'accountMarkets': pl.Utf8,
    'accountName': pl.Utf8,
    'accountNameKeywords': pl.Utf8,
    'accountNameType': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOrganizationid': pl.Float64,
    'accountPhone': pl.Utf8,
    'accountPhoneId': pl.Float64,
    'accountPhoneNumber': pl.Utf8,
    'accountPrimaryYN': pl.Utf8,
    'accountPriority': pl.Utf8,
    'accountProductInterest': pl.Utf8,
    'accountProperty': pl.Utf8,
    'accountRelationship': pl.Utf8,
    'accountRelationshipDesc': pl.Utf8,
    'accountRepActionCode': pl.Utf8,
    'accountRepCompetionCode': pl.Utf8,
    'accountRepIATACompType': pl.Utf8,
    'accountRepIndustryCode': pl.Utf8,
    'accountRepMarkets': pl.Utf8,
    'accountRepNameType': pl.Utf8,
    'accountRepScope': pl.Utf8,
    'accountRepScopeCity': pl.Utf8,
    'accountRepSource': pl.Utf8,
    'accountRepStateCode': pl.Utf8,
    'accountRepStateDescription': pl.Utf8,
    'accountRepTerritory': pl.Utf8,
    'accountRepType': pl.Utf8,
    'accountRoomsPotential': pl.Utf8,
    'accountScope': pl.Utf8,
    'accountScopeCity': pl.Utf8,
    'accountSname': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSrepCode': pl.Utf8,
    'accountState': pl.Utf8,
    'accountStateDesc': pl.Utf8,
    'accountSxname': pl.Utf8,
    'accountTerritory': pl.Utf8,
    'accountType': pl.Utf8,
    'accountXdisplayName': pl.Utf8,
    'accountXenvelopeGreeting': pl.Utf8,
    'accountXfirstName': pl.Utf8,
    'accountZipcode': pl.Utf8,
    'actionId': pl.Float64,
    'agentActiveYn': pl.Utf8,
    'agentAddressType': pl.Utf8,
    'agentAddress1': pl.Utf8,
    'agentAddress2': pl.Utf8,
    'agentAlternateLanguage': pl.Utf8,
    'agentAlternateLanguageDesc': pl.Utf8,
    'agentAlternateSalutation': pl.Utf8,
    'agentAlternateTitle': pl.Utf8,
    'agentArNumber': pl.Utf8,
    'agentAuSrepCode': pl.Utf8,
    'agentAvailabilityOverride': pl.Utf8,
    'agentBookingId': pl.Float64,
    'agentCblInd': pl.Utf8,
    'agentCity': pl.Utf8,
    'agentCityExt': pl.Utf8,
    'agentConActionCode': pl.Utf8,
    'agentConActiveYn': pl.Utf8,
    'agentConAddressType': pl.Utf8,
    'agentConAddress1': pl.Utf8,
    'agentConAddress2': pl.Utf8,
    'agentConAddress3': pl.Utf8,
    'agentConAddress4': pl.Utf8,
    'agentConAlternateLanguage': pl.Utf8,
    'agentConAlternateLanguageDesc': pl.Utf8,
    'agentConAlternateSalutation': pl.Utf8,
    'agentConAlternateTitle': pl.Utf8,
    'agentConArNumber': pl.Utf8,
    'agentConAuSrepCode': pl.Utf8,
    'agentConAvailabilityOverride': pl.Utf8,
    'agentConBirthDate': pl.Utf8,
    'agentConBirthDateStr': pl.Utf8,
    'agentConBookingId': pl.Float64,
    'agentConBusinessGreeting': pl.Utf8,
    'agentConCashBlInd': pl.Utf8,
    'agentConCity': pl.Utf8,
    'agentConCityExt': pl.Utf8,
    'agentConContactYn': pl.Utf8,
    'agentConCountry': pl.Utf8,
    'agentConCountryDesc': pl.Utf8,
    'agentConDepartment': pl.Utf8,
    'agentConDsi': pl.Float64,
    'agentConEmail': pl.Utf8,
    'agentConFax': pl.Utf8,
    'agentConFirst': pl.Utf8,
    'agentConHistoryYn': pl.Utf8,
    'agentConIataCompType': pl.Utf8,
    'agentConId': pl.Float64,
    'agentConIndustryCode': pl.Utf8,
    'agentConInfluence': pl.Utf8,
    'agentConLanguage': pl.Utf8,
    'agentConLanguageDesc': pl.Utf8,
    'agentConLast': pl.Utf8,
    'agentConLetterGreeting': pl.Utf8,
    'agentConLinkId': pl.Float64,
    'agentConLinkType': pl.Utf8,
    'agentConMailType': pl.Utf8,
    'agentConMarkets': pl.Utf8,
    'agentConMiddle': pl.Utf8,
    'agentConName': pl.Utf8,
    'agentConNameType': pl.Utf8,
    'agentConName2': pl.Utf8,
    'agentConName3': pl.Utf8,
    'agentConOrganizationid': pl.Float64,
    'agentConPhone': pl.Utf8,
    'agentConPosition': pl.Utf8,
    'agentConPrimaryYn': pl.Utf8,
    'agentConProductInterest': pl.Utf8,
    'agentConRelationship': pl.Utf8,
    'agentConRelationshipDesc': pl.Utf8,
    'agentConRepAccountType': pl.Utf8,
    'agentConRepAccountsource': pl.Utf8,
    'agentConRepActionCode': pl.Utf8,
    'agentConRepIATACompType': pl.Utf8,
    'agentConRepIndustryCode': pl.Utf8,
    'agentConRepInfluence': pl.Utf8,
    'agentConRepMarkets': pl.Utf8,
    'agentConRepNameType': pl.Utf8,
    'agentConRepScope': pl.Utf8,
    'agentConRepScopeCity': pl.Utf8,
    'agentConRepStateCode': pl.Utf8,
    'agentConRepStateDescription': pl.Utf8,
    'agentConRepTerritory': pl.Utf8,
    'agentConRepTitle': pl.Utf8,
    'agentConResort': pl.Utf8,
    'agentConScope': pl.Utf8,
    'agentConScopeCity': pl.Utf8,
    'agentConSfirst': pl.Utf8,
    'agentConSname': pl.Utf8,
    'agentConSrepId': pl.Float64,
    'agentConSrepName': pl.Utf8,
    'agentConState': pl.Utf8,
    'agentConStateDesc': pl.Utf8,
    'agentConSxfirstName': pl.Utf8,
    'agentConSxname': pl.Utf8,
    'agentConTerritory': pl.Utf8,
    'agentConTitle': pl.Utf8,
    'agentConXfirst': pl.Utf8,
    'agentConXlast': pl.Utf8,
    'agentConXletterGreeting': pl.Utf8,
    'agentConXname': pl.Utf8,
    'agentConZipcode': pl.Utf8,
    'agentCountry': pl.Utf8,
    'agentCountryDesc': pl.Utf8,
    'agentDsi': pl.Float64,
    'agentEmail': pl.Utf8,
    'agentFax': pl.Utf8,
    'agentHistoryYn': pl.Utf8,
    'agentIataCompType': pl.Utf8,
    'agentId': pl.Float64,
    'agentIndustryCode': pl.Utf8,
    'agentLanguage': pl.Utf8,
    'agentLanguageDesc': pl.Utf8,
    'agentLinkId': pl.Float64,
    'agentLinkType': pl.Utf8,
    'agentMailType': pl.Utf8,
    'agentMarkets': pl.Utf8,
    'agentName': pl.Utf8,
    'agentNameId': pl.Float64,
    'agentNameType': pl.Utf8,
    'agentName2': pl.Utf8,
    'agentName3': pl.Utf8,
    'agentOrganizationid': pl.Float64,
    'agentPhone': pl.Utf8,
    'agentPrimaryYn': pl.Utf8,
    'agentProductInterest': pl.Utf8,
    'agentRelationship': pl.Utf8,
    'agentRelationshipDesc': pl.Utf8,
    'agentRepStateCode': pl.Utf8,
    'agentResort': pl.Utf8,
    'agentScope': pl.Utf8,
    'agentScopeCity': pl.Utf8,
    'agentSname': pl.Utf8,
    'agentState': pl.Utf8,
    'agentStateDesc': pl.Utf8,
    'agentSxname': pl.Utf8,
    'agentTerritory': pl.Utf8,
    'agentXdisplayName': pl.Utf8,
    'agentXenvelopeGreeting': pl.Utf8,
    'agentXfirstName': pl.Utf8,
    'agentZipcode': pl.Utf8,
    'alias': pl.Utf8,
    'allOwners': pl.Utf8,
    'allotmentCode': pl.Utf8,
    'allotmentHeaderId': pl.Float64,
    'allotmentOrigion': pl.Utf8,
    'allotmentType': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'attendees': pl.Float64,
    'avgPeoplePerRoom': pl.Float64,
    'avgRateNet': pl.Float64,
    'beginDate': pl.Utf8,
    'bookingStatus': pl.Utf8,
    'bookingStatusOrderby': pl.Float64,
    'bookingStatusType': pl.Utf8,
    'bookingStatusorder': pl.Float64,
    'bookingmethod': pl.Utf8,
    'bookingmethoddesc': pl.Utf8,
    'bookingtype': pl.Utf8,
    'breakfastDesc': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'breakfastYn': pl.Utf8,
    'busblockId': pl.Float64,
    'busblockProperty': pl.Utf8,
    'cBreakfastPrice': pl.Float64,
    'cCompRoomValue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMtgBudget': pl.Float64,
    'cPorteragePrice': pl.Float64,
    'cPotRoomRevenue': pl.Float64,
    'cServiceCharge': pl.Float64,
    'cTaxAmount': pl.Float64,
    'cancelRule': pl.Utf8,
    'cancellationCode': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDescription': pl.Utf8,
    'cancellationNo': pl.Float64,
    'catCanxCode': pl.Utf8,
    'catCanxDate': pl.Utf8,
    'catCanxNumber': pl.Float64,
    'catCurrency': pl.Utf8,
    'catCutoff': pl.Utf8,
    'catDecision': pl.Utf8,
    'catExchange': pl.Float64,
    'catFollowup': pl.Utf8,
    'catOwner': pl.Float64,
    'catOwnerCode': pl.Utf8,
    'catOwnerEmail': pl.Utf8,
    'catOwnerFax': pl.Utf8,
    'catOwnerPhone': pl.Utf8,
    'catOwnerProperty': pl.Utf8,
    'catOwnerSrepname': pl.Utf8,
    'catOwnerTitle': pl.Utf8,
    'catOwners': pl.Utf8,
    'catQuoteCurrency': pl.Utf8,
    'catStatus': pl.Utf8,
    'catStatusOrderby': pl.Float64,
    'catStatusType': pl.Utf8,
    'catStatusorder': pl.Float64,
    'cateringCanxDesc': pl.Utf8,
    'cateringPkgsYn': pl.Utf8,
    'cateringonlyYn': pl.Utf8,
    'centralOwner': pl.Utf8,
    'channel': pl.Utf8,
    'commission': pl.Utf8,
    'compPerStayYn': pl.Utf8,
    'compRoomValue': pl.Float64,
    'compRooms': pl.Float64,
    'compRoomsFixedYn': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'conActionCode': pl.Utf8,
    'conActiveYn': pl.Utf8,
    'conAddressType': pl.Utf8,
    'conAddress1': pl.Utf8,
    'conAddress2': pl.Utf8,
    'conAddress3': pl.Utf8,
    'conAddress4': pl.Utf8,
    'conAlternateLanguage': pl.Utf8,
    'conAlternateLanguageDesc': pl.Utf8,
    'conAlternateSalutation': pl.Utf8,
    'conAlternateTitle': pl.Utf8,
    'conArNumber': pl.Utf8,
    'conAvailabilityOverride': pl.Utf8,
    'conBirthDate': pl.Utf8,
    'conBirthDateStr': pl.Utf8,
    'conBookingId': pl.Float64,
    'conBusinessGreeting': pl.Utf8,
    'conCashBlInd': pl.Utf8,
    'conCity': pl.Utf8,
    'conCityExt': pl.Utf8,
    'conContactYn': pl.Utf8,
    'conCountry': pl.Utf8,
    'conCountryDesc': pl.Utf8,
    'conDepartment': pl.Utf8,
    'conDsi': pl.Float64,
    'conFirst': pl.Utf8,
    'conHistoryYn': pl.Utf8,
    'conIataCompType': pl.Utf8,
    'conId': pl.Float64,
    'conIndustryCode': pl.Utf8,
    'conInfluence': pl.Utf8,
    'conLanguage': pl.Utf8,
    'conLanguageDesc': pl.Utf8,
    'conLast': pl.Utf8,
    'conLetterGreeting': pl.Utf8,
    'conLinkId': pl.Float64,
    'conLinkType': pl.Utf8,
    'conMailType': pl.Utf8,
    'conMarkets': pl.Utf8,
    'conMiddle': pl.Utf8,
    'conName': pl.Utf8,
    'conNameType': pl.Utf8,
    'conName2': pl.Utf8,
    'conName3': pl.Utf8,
    'conOrganizationid': pl.Float64,
    'conPosition': pl.Utf8,
    'conPrimaryYn': pl.Utf8,
    'conProductInterest': pl.Utf8,
    'conRelationship': pl.Utf8,
    'conRelationshipDesc': pl.Utf8,
    'conRepActionCode': pl.Utf8,
    'conRepInfluence': pl.Utf8,
    'conRepMarkets': pl.Utf8,
    'conRepNameType': pl.Utf8,
    'conRepScope': pl.Utf8,
    'conRepScopeCity': pl.Utf8,
    'conRepStateCode': pl.Utf8,
    'conRepStateDescription': pl.Utf8,
    'conRepTerritory': pl.Utf8,
    'conRepTitle': pl.Utf8,
    'conResort': pl.Utf8,
    'conScope': pl.Utf8,
    'conScopeCity': pl.Utf8,
    'conSfirst': pl.Utf8,
    'conSname': pl.Utf8,
    'conSrepCode': pl.Utf8,
    'conSrepId': pl.Float64,
    'conSrepName': pl.Utf8,
    'conState': pl.Utf8,
    'conStateDesc': pl.Utf8,
    'conSxfirstName': pl.Utf8,
    'conSxname': pl.Utf8,
    'conTerritory': pl.Utf8,
    'conTitle': pl.Utf8,
    'conXfirst': pl.Utf8,
    'conXlast': pl.Utf8,
    'conXletterGreeting': pl.Utf8,
    'conXname': pl.Utf8,
    'contactEmail': pl.Utf8,
    'contactFax': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactPhone': pl.Utf8,
    'contactZipcode': pl.Utf8,
    'contractNr': pl.Utf8,
    'conversionCode': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dateOpenedForPickup': pl.Utf8,
    'datePro': pl.Utf8,
    'dateTen': pl.Utf8,
    'defaultPmReservationNameId': pl.Float64,
    'deletedflag': pl.Utf8,
    'departureTime': pl.Utf8,
    'description': pl.Utf8,
    'destination': pl.Utf8,
    'detailsOkYn': pl.Utf8,
    'distributedYn': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dueDate': pl.Utf8,
    'elastic': pl.Utf8,
    'endDate': pl.Utf8,
    'eventsGuaranteedYn': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'externalLocked': pl.Utf8,
    'functiontype': pl.Utf8,
    'giid': pl.Utf8,
    'guaranteeCode': pl.Utf8,
    'iataCorpNumber': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'info': pl.Utf8,
    'infoboard': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'invCutoffDate': pl.Utf8,
    'invCutoffDays': pl.Float64,
    'isacOpptyId': pl.Utf8,
    'isacQuoteId': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'leadOrigin': pl.Utf8,
    'leadSource': pl.Utf8,
    'linkDate': pl.Utf8,
    'lostToProperty': pl.Utf8,
    'mainmarket': pl.Utf8,
    'marEventType': pl.Utf8,
    'marHouseProtectYn': pl.Utf8,
    'marRollEndDateYn': pl.Utf8,
    'marketCode': pl.Utf8,
    'masterNameId': pl.Float64,
    'methodDue': pl.Utf8,
    'mtgBudget': pl.Float64,
    'nonCompete': pl.Utf8,
    'nonCompeteCode': pl.Utf8,
    'organizationID': pl.Int64,
    'originalRateCode': pl.Utf8,
    'owner': pl.Float64,
    'ownerCode': pl.Utf8,
    'ownerCodeSrepname': pl.Utf8,
    'ownerEmail': pl.Utf8,
    'ownerFax': pl.Utf8,
    'ownerPhone': pl.Utf8,
    'ownerResort': pl.Utf8,
    'ownerTitle': pl.Utf8,
    'paymentMethod': pl.Utf8,
    'peakRooms': pl.Float64,
    'porteragePrice': pl.Float64,
    'porterageYn': pl.Utf8,
    'printAccountActiveYN': pl.Utf8,
    'printAccountAddress1': pl.Utf8,
    'printAccountAddress2': pl.Utf8,
    'printAccountAddress3': pl.Utf8,
    'printAccountAddress4': pl.Utf8,
    'printAccountBookingId': pl.Float64,
    'printAccountCity': pl.Utf8,
    'printAccountCityExt': pl.Utf8,
    'printAccountCountry': pl.Utf8,
    'printAccountCountryDesc': pl.Utf8,
    'printAccountDsi': pl.Float64,
    'printAccountId': pl.Float64,
    'printAccountLinkId': pl.Float64,
    'printAccountLinkType': pl.Utf8,
    'printAccountName': pl.Utf8,
    'printAccountName2': pl.Utf8,
    'printAccountName3': pl.Utf8,
    'printAccountOrganizationid': pl.Float64,
    'printAccountPhone': pl.Utf8,
    'printAccountPosition': pl.Utf8,
    'printAccountPrimaryYN': pl.Utf8,
    'printAccountProperty': pl.Utf8,
    'printAccountRepStateCode': pl.Utf8,
    'printAccountRepStateDescription': pl.Utf8,
    'printAccountRepTerritory': pl.Utf8,
    'printAccountScope': pl.Utf8,
    'printAccountScopeCity': pl.Utf8,
    'printAccountSname': pl.Utf8,
    'printAccountState': pl.Utf8,
    'printAccountStateDesc': pl.Utf8,
    'printAccountSxname': pl.Utf8,
    'printAccountTerritory': pl.Utf8,
    'printAccountXdisplayName': pl.Utf8,
    'printAccountXenvelopeGreeting': pl.Utf8,
    'printAccountXfirstName': pl.Utf8,
    'printAccountXname': pl.Utf8,
    'printAccountZipcode': pl.Utf8,
    'printConAddress1': pl.Utf8,
    'printConAddress2': pl.Utf8,
    'printConAddress3': pl.Utf8,
    'printConAddress4': pl.Utf8,
    'printConAlternateSalutation': pl.Utf8,
    'printConBusinessGreeting': pl.Utf8,
    'printConCity': pl.Utf8,
    'printConCityExt': pl.Utf8,
    'printConCountry': pl.Utf8,
    'printConCountryDesc': pl.Utf8,
    'printConDepartment': pl.Utf8,
    'printConDsi': pl.Float64,
    'printConEmail': pl.Utf8,
    'printConFirst': pl.Utf8,
    'printConId': pl.Float64,
    'printConLast': pl.Utf8,
    'printConLetterGreeting': pl.Utf8,
    'printConLinkId': pl.Float64,
    'printConLinkType': pl.Utf8,
    'printConMiddle': pl.Utf8,
    'printConName': pl.Utf8,
    'printConName2': pl.Utf8,
    'printConName3': pl.Utf8,
    'printConOrganizationid': pl.Float64,
    'printConPhone': pl.Utf8,
    'printConPosition': pl.Utf8,
    'printConPrimaryYn': pl.Utf8,
    'printConProductInterest': pl.Utf8,
    'printConRelationship': pl.Utf8,
    'printConRelationshipDesc': pl.Utf8,
    'printConRepStateCode': pl.Utf8,
    'printConRepTitle': pl.Utf8,
    'printConResort': pl.Utf8,
    'printConScope': pl.Utf8,
    'printConScopeCity': pl.Utf8,
    'printConSname': pl.Utf8,
    'printConState': pl.Utf8,
    'printConStateDesc': pl.Utf8,
    'printConSxname': pl.Utf8,
    'printConTerritory': pl.Utf8,
    'printConTitle': pl.Utf8,
    'printConXdisplayName': pl.Utf8,
    'printConXfirst': pl.Utf8,
    'printConXlast': pl.Utf8,
    'printConXletterGreeting': pl.Utf8,
    'printConZipcode': pl.Utf8,
    'profileDesc': pl.Utf8,
    'profileId': pl.Float64,
    'program': pl.Utf8,
    'property': pl.Utf8,
    'rankingCode': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateGuaranteedYn': pl.Utf8,
    'rateOverride': pl.Utf8,
    'rateOverrideReason': pl.Utf8,
    'rateProtection': pl.Utf8,
    'relatedResorts': pl.Utf8,
    'repBlockStatusDescription': pl.Utf8,
    'repBookingmethod': pl.Utf8,
    'repBookingmethodDescription': pl.Utf8,
    'repBookingtype': pl.Utf8,
    'repBsOrderBy': pl.Float64,
    'repCateringOrderBy': pl.Float64,
    'repCateringStatus': pl.Utf8,
    'repCateringStatusDescription': pl.Utf8,
    'repChannel': pl.Utf8,
    'repConversionCode': pl.Utf8,
    'repDestination': pl.Utf8,
    'repGuaranteeCode': pl.Utf8,
    'repMarketCode': pl.Utf8,
    'repNonCompeteCode': pl.Utf8,
    'repPaymentMethod': pl.Utf8,
    'repRankingCode': pl.Utf8,
    'repSourceCode': pl.Utf8,
    'representative': pl.Utf8,
    'reserveInventoryYn': pl.Utf8,
    'resortBooked': pl.Utf8,
    'revBlocked': pl.Float64,
    'revBlockedNet': pl.Float64,
    'revContracted': pl.Float64,
    'rivMarketSegment': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsBlocked': pl.Float64,
    'roomsContracted': pl.Float64,
    'roomsCurrency': pl.Utf8,
    'roomsDecision': pl.Utf8,
    'roomsExchange': pl.Float64,
    'roomsFollowup': pl.Utf8,
    'roomsOwner': pl.Float64,
    'roomsOwnerCode': pl.Utf8,
    'roomsOwnerEmail': pl.Utf8,
    'roomsOwnerFax': pl.Utf8,
    'roomsOwnerPhone': pl.Utf8,
    'roomsOwnerResort': pl.Utf8,
    'roomsOwnerSrepname': pl.Utf8,
    'roomsOwnerTitle': pl.Utf8,
    'roomsOwners': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'roomsQuoteCurr': pl.Utf8,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'secConActionCode': pl.Utf8,
    'secConActiveYn': pl.Utf8,
    'secConAddress1': pl.Utf8,
    'secConAddress2': pl.Utf8,
    'secConAddress3': pl.Utf8,
    'secConAddress4': pl.Utf8,
    'secConAlternateLanguage': pl.Utf8,
    'secConAlternateLanguageDesc': pl.Utf8,
    'secConAlternateSalutation': pl.Utf8,
    'secConAlternateTitle': pl.Utf8,
    'secConBirthDate': pl.Utf8,
    'secConBirthDateStr': pl.Utf8,
    'secConBookingId': pl.Float64,
    'secConBusinessGreeting': pl.Utf8,
    'secConCashBlInd': pl.Utf8,
    'secConCity': pl.Utf8,
    'secConCityExt': pl.Utf8,
    'secConContactYn': pl.Utf8,
    'secConCountry': pl.Utf8,
    'secConCountryDesc': pl.Utf8,
    'secConDepartment': pl.Utf8,
    'secConDsi': pl.Float64,
    'secConEmail': pl.Utf8,
    'secConFax': pl.Utf8,
    'secConFirstName': pl.Utf8,
    'secConFullName': pl.Utf8,
    'secConId': pl.Float64,
    'secConInfluence': pl.Utf8,
    'secConLanguage': pl.Utf8,
    'secConLanguageDesc': pl.Utf8,
    'secConLastName': pl.Utf8,
    'secConLetterGreeting': pl.Utf8,
    'secConLinkId': pl.Float64,
    'secConLinkType': pl.Utf8,
    'secConMarkets': pl.Utf8,
    'secConMiddleName': pl.Utf8,
    'secConNameType': pl.Utf8,
    'secConName2': pl.Utf8,
    'secConName3': pl.Utf8,
    'secConOrganizationid': pl.Float64,
    'secConPhone': pl.Utf8,
    'secConPosition': pl.Utf8,
    'secConPrimaryYn': pl.Utf8,
    'secConProductInterest': pl.Utf8,
    'secConRelationship': pl.Utf8,
    'secConRelationshipDesc': pl.Utf8,
    'secConRepActionCode': pl.Utf8,
    'secConRepInfluence': pl.Utf8,
    'secConRepMarkets': pl.Utf8,
    'secConRepNameType': pl.Utf8,
    'secConRepScope': pl.Utf8,
    'secConRepScopeCity': pl.Utf8,
    'secConRepStateCode': pl.Utf8,
    'secConRepStateDescription': pl.Utf8,
    'secConRepTerritory': pl.Utf8,
    'secConRepTitle': pl.Utf8,
    'secConResort': pl.Utf8,
    'secConScope': pl.Utf8,
    'secConScopeCity': pl.Utf8,
    'secConSfirst': pl.Utf8,
    'secConSname': pl.Utf8,
    'secConSrepCode': pl.Utf8,
    'secConSrepId': pl.Float64,
    'secConSrepName': pl.Utf8,
    'secConState': pl.Utf8,
    'secConStateDesc': pl.Utf8,
    'secConSxfirstName': pl.Utf8,
    'secConSxname': pl.Utf8,
    'secConTerritory': pl.Utf8,
    'secConTitle': pl.Utf8,
    'secConXenvelopeGreeting': pl.Utf8,
    'secConXfirstName': pl.Utf8,
    'secConXfullName': pl.Utf8,
    'secConXlastName': pl.Utf8,
    'secConZipCode': pl.Utf8,
    'senddate': pl.Utf8,
    'sentDate': pl.Utf8,
    'serviceCharge': pl.Float64,
    'shoulderBeginDate': pl.Utf8,
    'shoulderEndDate': pl.Utf8,
    'source': pl.Utf8,
    'sourceActiveYn': pl.Utf8,
    'sourceAddressType': pl.Utf8,
    'sourceAddress1': pl.Utf8,
    'sourceAddress2': pl.Utf8,
    'sourceAlternateLanguage': pl.Utf8,
    'sourceAlternateLanguageDesc': pl.Utf8,
    'sourceAlternateSalutation': pl.Utf8,
    'sourceAlternateTitle': pl.Utf8,
    'sourceBookingId': pl.Float64,
    'sourceBusinessGreeting': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCityExt': pl.Utf8,
    'sourceConActionCode': pl.Utf8,
    'sourceConActiveYn': pl.Utf8,
    'sourceConAddressType': pl.Utf8,
    'sourceConAddress1': pl.Utf8,
    'sourceConAddress2': pl.Utf8,
    'sourceConAddress3': pl.Utf8,
    'sourceConAddress4': pl.Utf8,
    'sourceConAlternateLanguage': pl.Utf8,
    'sourceConAlternateLanguageDesc': pl.Utf8,
    'sourceConAlternateSalutation': pl.Utf8,
    'sourceConAlternateTitle': pl.Utf8,
    'sourceConArNumber': pl.Utf8,
    'sourceConAuSrepCode': pl.Utf8,
    'sourceConAvailabilityOverride': pl.Utf8,
    'sourceConBirthDate': pl.Utf8,
    'sourceConBirthDateStr': pl.Utf8,
    'sourceConBookingId': pl.Float64,
    'sourceConBusinessGreeting': pl.Utf8,
    'sourceConCashBlInd': pl.Utf8,
    'sourceConCity': pl.Utf8,
    'sourceConCityExt': pl.Utf8,
    'sourceConContactYn': pl.Utf8,
    'sourceConCountry': pl.Utf8,
    'sourceConCountryDesc': pl.Utf8,
    'sourceConDepartment': pl.Utf8,
    'sourceConDsi': pl.Float64,
    'sourceConEmail': pl.Utf8,
    'sourceConFax': pl.Utf8,
    'sourceConFirst': pl.Utf8,
    'sourceConHistoryYn': pl.Utf8,
    'sourceConIataCompType': pl.Utf8,
    'sourceConId': pl.Float64,
    'sourceConIndustryCode': pl.Utf8,
    'sourceConInfluence': pl.Utf8,
    'sourceConLanguage': pl.Utf8,
    'sourceConLanguageDesc': pl.Utf8,
    'sourceConLast': pl.Utf8,
    'sourceConLetterGreeting': pl.Utf8,
    'sourceConLinkId': pl.Float64,
    'sourceConLinkType': pl.Utf8,
    'sourceConMailType': pl.Utf8,
    'sourceConMarkets': pl.Utf8,
    'sourceConMiddle': pl.Utf8,
    'sourceConName': pl.Utf8,
    'sourceConNameType': pl.Utf8,
    'sourceConName2': pl.Utf8,
    'sourceConName3': pl.Utf8,
    'sourceConOrganizationid': pl.Float64,
    'sourceConPhone': pl.Utf8,
    'sourceConPosition': pl.Utf8,
    'sourceConPrimaryYn': pl.Utf8,
    'sourceConProductInterest': pl.Utf8,
    'sourceConRelationship': pl.Utf8,
    'sourceConRelationshipDesc': pl.Utf8,
    'sourceConRepActionCode': pl.Utf8,
    'sourceConRepInfluence': pl.Utf8,
    'sourceConRepMarkets': pl.Utf8,
    'sourceConRepNameType': pl.Utf8,
    'sourceConRepScope': pl.Utf8,
    'sourceConRepScopeCity': pl.Utf8,
    'sourceConRepStateCode': pl.Utf8,
    'sourceConRepStateDescription': pl.Utf8,
    'sourceConRepTerritory': pl.Utf8,
    'sourceConRepTitle': pl.Utf8,
    'sourceConResort': pl.Utf8,
    'sourceConScope': pl.Utf8,
    'sourceConScopeCity': pl.Utf8,
    'sourceConSfirst': pl.Utf8,
    'sourceConSname': pl.Utf8,
    'sourceConSrepId': pl.Float64,
    'sourceConSrepName': pl.Utf8,
    'sourceConState': pl.Utf8,
    'sourceConStateDesc': pl.Utf8,
    'sourceConSxfirstName': pl.Utf8,
    'sourceConSxname': pl.Utf8,
    'sourceConTerritory': pl.Utf8,
    'sourceConTitle': pl.Utf8,
    'sourceConXfirst': pl.Utf8,
    'sourceConXlast': pl.Utf8,
    'sourceConXletterGreeting': pl.Utf8,
    'sourceConXname': pl.Utf8,
    'sourceConZipcode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceCountryDesc': pl.Utf8,
    'sourceDsi': pl.Float64,
    'sourceEmail': pl.Utf8,
    'sourceFax': pl.Utf8,
    'sourceId': pl.Float64,
    'sourceLinkId': pl.Float64,
    'sourceLinkType': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceNameType': pl.Utf8,
    'sourceName2': pl.Utf8,
    'sourceName3': pl.Utf8,
    'sourceOrganizationid': pl.Float64,
    'sourcePhone': pl.Utf8,
    'sourcePrimaryYn': pl.Utf8,
    'sourceRelationship': pl.Utf8,
    'sourceRelationshipDesc': pl.Utf8,
    'sourceRepStateCode': pl.Utf8,
    'sourceResort': pl.Utf8,
    'sourceScope': pl.Utf8,
    'sourceScopeCity': pl.Utf8,
    'sourceSname': pl.Utf8,
    'sourceState': pl.Utf8,
    'sourceStateDesc': pl.Utf8,
    'sourceSxname': pl.Utf8,
    'sourceTerritory': pl.Utf8,
    'sourceXdisplayName': pl.Utf8,
    'sourceXenvelopeGreeting': pl.Utf8,
    'sourceXfirstName': pl.Utf8,
    'sourceZipcode': pl.Utf8,
    'status': pl.Utf8,
    'superBlockId': pl.Float64,
    'superBlockResort': pl.Utf8,
    'taxAmount': pl.Float64,
    'tbdRates': pl.Utf8,
    'tentativeLevel': pl.Float64,
    'tracecode': pl.Utf8,
    'udescription': pl.Utf8,
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
    'xaccName': pl.Utf8,
    'xagentName': pl.Utf8,
    'xsourceName': pl.Utf8,
}
```
```python
property_property_details_schema = {
    'property': pl.Utf8,
    'aRAccountNoFormat': pl.Utf8,
    'aRAccountNumberMandatoryYN': pl.Utf8,
    'aRAgent': pl.Utf8,
    'aRBalanceTrxCode': pl.Utf8,
    'aRCompany': pl.Utf8,
    'aRCreditTrxCode': pl.Utf8,
    'aRGroups': pl.Utf8,
    'aRIndividuals': pl.Utf8,
    'aRSettleCode': pl.Utf8,
    'aRTypewriter': pl.Utf8,
    'accessCode': pl.Utf8,
    'accessibleRooms': pl.Float64,
    'agingLevel1': pl.Float64,
    'agingLevel2': pl.Float64,
    'agingLevel3': pl.Float64,
    'agingLevel4': pl.Float64,
    'agingLevel5': pl.Float64,
    'airport': pl.Utf8,
    'airportDistance': pl.Utf8,
    'airportTime': pl.Utf8,
    'allowLoginYN': pl.Utf8,
    'allowancePeriodAdj': pl.Utf8,
    'awardsTimeout': pl.Float64,
    'ballroomArea': pl.Utf8,
    'ballroomSeats': pl.Float64,
    'baseLanguage': pl.Utf8,
    'block': pl.Utf8,
    'brandCode': pl.Utf8,
    'budgetMonth': pl.Float64,
    'businessDate': pl.Utf8,
    'businessID': pl.Utf8,
    'businessRegistrationCode': pl.Utf8,
    'cROCODE': pl.Utf8,
    'cashShiftDrop': pl.Utf8,
    'cateringCurrencyCode': pl.Utf8,
    'cateringCurrencyFormat': pl.Utf8,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'centralCreditLimit': pl.Float64,
    'centralCurrencyCode': pl.Utf8,
    'centralCurrencyDescription': pl.Utf8,
    'centralDblRate2': pl.Float64,
    'centralDblRate1': pl.Float64,
    'centralPasserbyMarket': pl.Utf8,
    'centralPasserbySource': pl.Utf8,
    'centralPropertyType': pl.Utf8,
    'centralSglRate1': pl.Float64,
    'centralSglRate2': pl.Float64,
    'centralState': pl.Utf8,
    'centralStateDescription': pl.Utf8,
    'centralSuiRate1': pl.Float64,
    'centralSuiRate2': pl.Float64,
    'centralTplRate1': pl.Float64,
    'centralTplRate2': pl.Float64,
    'centralWarningAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'chainDescription': pl.Utf8,
    'chainMode': pl.Utf8,
    'checkExgPaidout': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'checkShiftDrop': pl.Utf8,
    'checkTrxcode': pl.Utf8,
    'checkInTime': pl.Utf8,
    'city': pl.Utf8,
    'cityDescription': pl.Utf8,
    'comAddress': pl.Utf8,
    'comMethod': pl.Utf8,
    'comNameXrefId': pl.Float64,
    'companyAddressType': pl.Utf8,
    'companyPhoneType': pl.Utf8,
    'configurationMode': pl.Utf8,
    'confirmRegcardPrinter': pl.Utf8,
    'connectingRooms': pl.Float64,
    'contacts': pl.Utf8,
    'copies': pl.Float64,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryMode': pl.Utf8,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyCodeSymbol': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencyFormat': pl.Utf8,
    'curtainColor': pl.Utf8,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'dateSeparator': pl.Utf8,
    'decimalPlaces': pl.Float64,
    'decimalSeparator': pl.Utf8,
    'decimals': pl.Float64,
    'defaultFolioStyle': pl.Float64,
    'defaultGuestAddress': pl.Utf8,
    'defaultMembershipType': pl.Utf8,
    'defaultPostingRoom': pl.Utf8,
    'defaultPropertyAddress': pl.Utf8,
    'defaultRateCode': pl.Utf8,
    'defaultRatecodePcr': pl.Utf8,
    'defaultRatecodeRack': pl.Utf8,
    'defaultRegistrationCard': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositLedgerTrxCode': pl.Utf8,
    'destinationId': pl.Utf8,
    'dfltPkgTranCode': pl.Utf8,
    'dfltTranCodeRateCode': pl.Utf8,
    'directions': pl.Utf8,
    'dirsales': pl.Utf8,
    'disableLoginYN': pl.Utf8,
    'doubleRooms': pl.Float64,
    'downloadRestYN': pl.Utf8,
    'dutyManagerPager': pl.Utf8,
    'email': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'executiveFloorNumber': pl.Utf8,
    'expHotelCode': pl.Utf8,
    'extExpFileLocation': pl.Utf8,
    'extPropertyCode': pl.Utf8,
    'externalSCYN': pl.Utf8,
    'familyRooms': pl.Float64,
    'faxNoFormat': pl.Utf8,
    'faxNumber': pl.Utf8,
    'fiscalEndDate': pl.Utf8,
    'fiscalPeriodType': pl.Utf8,
    'fiscalStartDate': pl.Utf8,
    'fiscalYearBeginMonth': pl.Float64,
    'fiscalYearBeginYear': pl.Float64,
    'flags': pl.Utf8,
    'flowCode': pl.Utf8,
    'fnsTier': pl.Utf8,
    'folioLanguage1': pl.Utf8,
    'folioLanguage2': pl.Utf8,
    'folioLanguage3': pl.Utf8,
    'folioLanguage4': pl.Utf8,
    'genmgr': pl.Utf8,
    'groupRoomWarning': pl.Float64,
    'guestLookupTimeout': pl.Float64,
    'guestRoomElevators': pl.Float64,
    'guestRoomFloors': pl.Float64,
    'hotelCode': pl.Utf8,
    'hotelFC': pl.Utf8,
    'hotelID': pl.Utf8,
    'hotelType': pl.Utf8,
    'iMGDirectionID': pl.Float64,
    'iMGHotelID': pl.Float64,
    'iMGMapID': pl.Float64,
    'inactiveDaysForGuestProfile': pl.Float64,
    'inactiveFlag': pl.Utf8,
    'individualAddressType': pl.Utf8,
    'individualPhoneType': pl.Utf8,
    'individualRoomWarning': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'intTaxIncludedYN': pl.Utf8,
    'inventoryYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepAvailability': pl.Float64,
    'latitude': pl.Float64,
    'leadsend': pl.Utf8,
    'legalOwner': pl.Utf8,
    'locationID': pl.Utf8,
    'longDateFormat': pl.Utf8,
    'longStayControl': pl.Float64,
    'longitude': pl.Float64,
    'maxAdultsInFamilyRoom': pl.Float64,
    'maxChildrenInFamilyRoom': pl.Float64,
    'maxOccupancy': pl.Float64,
    'maximumCreditDays': pl.Float64,
    'mbsSupportedYN': pl.Utf8,
    'meetRooms': pl.Float64,
    'meetSeats': pl.Float64,
    'meetSpace': pl.Float64,
    'meetingFC': pl.Utf8,
    'minDaysBet2ReminderLetter': pl.Float64,
    'nameIdLink': pl.Float64,
    'nightAuditCashierID': pl.Utf8,
    'nonSmokingRooms': pl.Float64,
    'noteDetails': pl.Utf8,
    'numberOfBeds': pl.Float64,
    'numberOfFloors': pl.Float64,
    'numberOfRooms': pl.Float64,
    'opusCurrencyCode': pl.Utf8,
    'organizationID': pl.Int64,
    'organizationInternalID': pl.Float64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'parentOrgCode': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'path': pl.Utf8,
    'paymentDate': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'phoneNumber': pl.Utf8,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'proinfoUrl': pl.Utf8,
    'propMapUrl': pl.Utf8,
    'propPicUrl': pl.Utf8,
    'propertyCode': pl.Utf8,
    'propertyName': pl.Utf8,
    'propertyType': pl.Utf8,
    'quotedCurrency': pl.Utf8,
    'rNAInsertdate': pl.Utf8,
    'rNAUpdatedate': pl.Utf8,
    'reconcileDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'regionDescription': pl.Utf8,
    'restaurant': pl.Float64,
    'rhythmSheets': pl.Float64,
    'rhythmTowels': pl.Float64,
    'roomAmenities': pl.Utf8,
    'sGLNum': pl.Utf8,
    'sGLRate1': pl.Float64,
    'sGLRate2': pl.Float64,
    'sUINum': pl.Utf8,
    'sUIRate1': pl.Float64,
    'sUIRate2': pl.Float64,
    'saveProfiles': pl.Float64,
    'scriptID': pl.Float64,
    'season1': pl.Utf8,
    'season2': pl.Utf8,
    'season3': pl.Utf8,
    'season4': pl.Utf8,
    'season5': pl.Utf8,
    'sendLeadAsBooking': pl.Utf8,
    'shopDescription': pl.Utf8,
    'shortDateFormat': pl.Utf8,
    'singleRooms': pl.Float64,
    'sourceCommission': pl.Utf8,
    'state': pl.Utf8,
    'stateDescription': pl.Utf8,
    'street': pl.Utf8,
    'suites': pl.Float64,
    'summCurrencyCode': pl.Utf8,
    'tACommission': pl.Utf8,
    'tPLNum': pl.Utf8,
    'tPLRate1': pl.Float64,
    'tPLRate2': pl.Float64,
    'telephoneNoFormat': pl.Utf8,
    'thousandSeparator': pl.Utf8,
    'timeFormat': pl.Utf8,
    'timeZone': pl.Utf8,
    'tollFree': pl.Utf8,
    'totalRooms': pl.Float64,
    'touristNumber': pl.Utf8,
    'translateMulticharYN': pl.Utf8,
    'turnawayCode': pl.Utf8,
    'twinRooms': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatID': pl.Utf8,
    'videoCheckoutPrinter': pl.Utf8,
    'videoCheckoutStart': pl.Utf8,
    'videoCheckoutStop': pl.Utf8,
    'wakeUpDelay': pl.Float64,
    'warningAmount': pl.Float64,
    'web': pl.Utf8,
    'weekendDays': pl.Utf8,
    'zeroInvPurDays': pl.Float64,
}
```