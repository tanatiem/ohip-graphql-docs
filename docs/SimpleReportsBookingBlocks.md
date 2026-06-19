# SimpleReportsBookingBlocks
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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
| 1 | accountActionCode | `String` | Account Action Code |
| 2 | accountActiveYN | `String` | Acc Active Y/N |
| 3 | accountAddressType | `String` | Account Address Type |
| 4 | accountAddress1 | `String` | Account Address1 |
| 5 | accountAddress2 | `String` | Account Address2 |
| 6 | accountAlternateLanguage | `String` | Account Alternate Language |
| 7 | accountAlternateLanguageDesc | `String` | Acc Xlanguage Description |
| 8 | accountAlternateSalutation | `String` | Account Alternate Salutation |
| 9 | accountAlternateTitle | `String` | Account Alternate Title |
| 10 | accountArNumber | `String` | Acc AR No |
| 11 | accountAvailoverYN | `String` | Acc Availover Y/N |
| 12 | accountBlMsg | `String` | Account Bl Msg |
| 13 | accountBookingId | `Float` | Acc Booking ID |
| 14 | accountCblIndividual | `String` | Account Cbl Ind |
| 15 | accountCity | `String` | Account City. |
| 16 | accountCityExt | `String` | Account City Ext |
| 17 | accountCommissionCode | `String` | Account Commission Code |
| 18 | accountCompetitionCode | `String` | Account Competition Code |
| 19 | accountCountry | `String` | Account Country. |
| 20 | accountCountryDesc | `String` | Acc Country Description |
| 21 | accountDsi | `Float` | Account Dsi |
| 22 | accountEmail | `String` | Account Email |
| 23 | accountFax | `String` | Account Fax |
| 24 | accountHistoryYN | `String` | Acc History Y/N |
| 25 | accountHoldCode | `String` | Account Hold Code |
| 26 | accountIATACompType | `String` | Account Iata Comp Type |
| 27 | accountId | `Float` | Acc ID |
| 28 | accountIndustryCode | `String` | Account Industry Code |
| 29 | accountKeyword | `String` | Account Keyword |
| 30 | accountLanguage | `String` | Account Language |
| 31 | accountLanguageDesc | `String` | Acc Language Description |
| 32 | accountLinkId | `Float` | Acc Link ID |
| 33 | accountLinkType | `String` | Account Link Type |
| 34 | accountMailList | `String` | Account Mail List |
| 35 | accountMailType | `String` | Account Mail Type |
| 36 | accountMarkets | `String` | Account Markets |
| 37 | accountName | `String` | Account Name |
| 38 | accountNameKeywords | `String` | Account Name Keywords |
| 39 | accountNameType | `String` | Account Name Type |
| 40 | accountName2 | `String` | Account Name2 |
| 41 | accountName3 | `String` | Account Name3 |
| 42 | accountOrganizationid | `Float` | Account Organizationid |
| 43 | accountPhone | `String` | Account Phone |
| 44 | accountPhoneId | `Float` | Acc Phone ID |
| 45 | accountPhoneNumber | `String` | Account Phone No. |
| 46 | accountPrimaryYN | `String` | Acc Primary Y/N |
| 47 | accountPriority | `String` | Account Priority |
| 48 | accountProductInterest | `String` | Account Product Interest |
| 49 | accountProperty | `String` | Account Resort |
| 50 | accountRelationship | `String` | Account Relationship |
| 51 | accountRelationshipDesc | `String` | Acc Relationship Description |
| 52 | accountRepActionCode | `String` | Acc Reporting Actioncode |
| 53 | accountRepCompetionCode | `String` | Acc Reporting Competion Code |
| 54 | accountRepIATACompType | `String` | Acc Reporting Iata Comp Type |
| 55 | accountRepIndustryCode | `String` | Acc Reporting Industry Code |
| 56 | accountRepMarkets | `String` | Acc Reporting Markets |
| 57 | accountRepNameType | `String` | Acc Reporting Name Type |
| 58 | accountRepScope | `String` | Acc Reporting Scope |
| 59 | accountRepScopeCity | `String` | Acc Reporting Scope City |
| 60 | accountRepSource | `String` | Acc Reporting Source |
| 61 | accountRepStateCode | `String` | Acc Reporting State Code |
| 62 | accountRepStateDescription | `String` | Acc Reporting State Desc |
| 63 | accountRepTerritory | `String` | Acc Reporting Territory |
| 64 | accountRepType | `String` | Acc Reporting Type |
| 65 | accountRoomsPotential | `String` | Account Rooms Potential |
| 66 | accountScope | `String` | Account Scope |
| 67 | accountScopeCity | `String` | Account Scope City |
| 68 | accountSname | `String` | Account Sname |
| 69 | accountSource | `String` | Account Source |
| 70 | accountSrepCode | `String` | Account Srep Code |
| 71 | accountState | `String` | Account State. |
| 72 | accountStateDesc | `String` | Acc State Description |
| 73 | accountSxname | `String` | Account Sxname |
| 74 | accountTerritory | `String` | Account Territory |
| 75 | accountType | `String` | Account Type |
| 76 | accountXdisplayName | `String` | Account Xdisplay Name |
| 77 | accountXenvelopeGreeting | `String` | Account Xenvelope Greeting |
| 78 | accountXfirstName | `String` | Account Xfirst Name |
| 79 | accountZipcode | `String` | Account Zipcode |
| 80 | actionId | `Float` | Action ID |
| 81 | agentActiveYn | `String` | Agent Active Y/N |
| 82 | agentAddressType | `String` | Agent Address Type |
| 83 | agentAddress1 | `String` | Agent Address1 |
| 84 | agentAddress2 | `String` | Agent Address2 |
| 85 | agentAlternateLanguage | `String` | Agent Alternate Language |
| 86 | agentAlternateLanguageDesc | `String` | Agent Xlanguage Description |
| 87 | agentAlternateSalutation | `String` | Agent Alternate Salutation |
| 88 | agentAlternateTitle | `String` | Agent Alternate Title |
| 89 | agentArNumber | `String` | Agent AR No |
| 90 | agentAuSrepCode | `String` | Agent Au Srep Code |
| 91 | agentAvailabilityOverride | `String` | Agent Availability Override |
| 92 | agentBookingId | `Float` | Agent Booking ID |
| 93 | agentCblInd | `String` | Agent Cbl Individual |
| 94 | agentCity | `String` | Agent City |
| 95 | agentCityExt | `String` | Agent City Ext |
| 96 | agentConActionCode | `String` | Agent Con Action Code |
| 97 | agentConActiveYn | `String` | Agent Con Active Y/N |
| 98 | agentConAddressType | `String` | Agent Con Address Type |
| 99 | agentConAddress1 | `String` | Agent Con Address1 |
| 100 | agentConAddress2 | `String` | Agent Con Address2 |
| 101 | agentConAddress3 | `String` | Agent Con Address3 |
| 102 | agentConAddress4 | `String` | Agent Con Address4 |
| 103 | agentConAlternateLanguage | `String` | Agent Con Alternate Language |
| 104 | agentConAlternateLanguageDesc | `String` | Agent Con Xlanguage Description |
| 105 | agentConAlternateSalutation | `String` | Agent Con Alternate Salutation |
| 106 | agentConAlternateTitle | `String` | Agent Con Alternate Title |
| 107 | agentConArNumber | `String` | Agent Con AR No |
| 108 | agentConAuSrepCode | `String` | Agent Con Au Srep Code |
| 109 | agentConAvailabilityOverride | `String` | Agent Con Availability Override |
| 110 | agentConBirthDate | `Date` | Agent Con Birth Date |
| 111 | agentConBirthDateStr | `String` | Agent Con Birth Date Str |
| 112 | agentConBookingId | `Float` | Agent Con Booking ID |
| 113 | agentConBusinessGreeting | `String` | Agent Con Business Greeting |
| 114 | agentConCashBlInd | `String` | Agent Con Cash Bl Individual |
| 115 | agentConCity | `String` | Agent Con City |
| 116 | agentConCityExt | `String` | Agent Con City Ext |
| 117 | agentConContactYn | `String` | Agent Con Contact Y/N |
| 118 | agentConCountry | `String` | Agent Con Country |
| 119 | agentConCountryDesc | `String` | Agent Con Country Description |
| 120 | agentConDepartment | `String` | Agent Con Department |
| 121 | agentConDsi | `Float` | Agent Con Dsi |
| 122 | agentConEmail | `String` | Agent Con Email |
| 123 | agentConFax | `String` | Agent Con Fax |
| 124 | agentConFirst | `String` | Agent Con First |
| 125 | agentConHistoryYn | `String` | Agent Con History Y/N |
| 126 | agentConIataCompType | `String` | Agent Con IATA Comp Type |
| 127 | agentConId | `Float` | Agent Con ID |
| 128 | agentConIndustryCode | `String` | Agent Con Industry Code |
| 129 | agentConInfluence | `String` | Agent Con Influence |
| 130 | agentConLanguage | `String` | Agent Con Language |
| 131 | agentConLanguageDesc | `String` | Agent Con Language Description |
| 132 | agentConLast | `String` | Agent Con Last |
| 133 | agentConLetterGreeting | `String` | Agent Con Letter Greeting |
| 134 | agentConLinkId | `Float` | Agent Con Link ID |
| 135 | agentConLinkType | `String` | Agent Con Link Type |
| 136 | agentConMailType | `String` | Agent Con Mail Type |
| 137 | agentConMarkets | `String` | Agent Con Markets |
| 138 | agentConMiddle | `String` | Agent Con Middle |
| 139 | agentConName | `String` | Agent Con Name |
| 140 | agentConNameType | `String` | Agent Con Name Type |
| 141 | agentConName2 | `String` | Agent Con Name2 |
| 142 | agentConName3 | `String` | Agent Con Name3 |
| 143 | agentConOrganizationid | `Float` | Agent Con Organizationid |
| 144 | agentConPhone | `String` | Agent Con Phone |
| 145 | agentConPosition | `String` | Agent Con Position |
| 146 | agentConPrimaryYn | `String` | Agent Con Primary Y/N |
| 147 | agentConProductInterest | `String` | Agent Con Product Interest |
| 148 | agentConRelationship | `String` | Agent Con Relationship |
| 149 | agentConRelationshipDesc | `String` | Agent Con Relationship Description |
| 150 | agentConRepAccountType | `String` | Agent Con Reporting Account Type |
| 151 | agentConRepAccountsource | `String` | Agent Con Reporting Accountsource |
| 152 | agentConRepActionCode | `String` | Agent Con Reporting Actioncode |
| 153 | agentConRepIATACompType | `String` | Agent Con Reporting Iata Comp Type |
| 154 | agentConRepIndustryCode | `String` | Agent Con Reporting Industry Code |
| 155 | agentConRepInfluence | `String` | Agent Con Reporting Influence |
| 156 | agentConRepMarkets | `String` | Agent Con Reporting Markets |
| 157 | agentConRepNameType | `String` | Agent Con Reporting Name Type |
| 158 | agentConRepScope | `String` | Agent Con Reporting Scope |
| 159 | agentConRepScopeCity | `String` | Agent Con Reporting Scope City |
| 160 | agentConRepStateCode | `String` | Agent Con Reporting State Code |
| 161 | agentConRepStateDescription | `String` | Agent Con Reporting State Desc |
| 162 | agentConRepTerritory | `String` | Agent Con Reporting Territory |
| 163 | agentConRepTitle | `String` | Agent Con Reporting Title |
| 164 | agentConResort | `String` | Agent Con Property |
| 165 | agentConScope | `String` | Agent Con Scope |
| 166 | agentConScopeCity | `String` | Agent Con Scope City |
| 167 | agentConSfirst | `String` | Agent Con Sfirst |
| 168 | agentConSname | `String` | Agent Con Sname |
| 169 | agentConSrepId | `Float` | Agent Con Srep ID |
| 170 | agentConSrepName | `String` | Agent Con Srep Name |
| 171 | agentConState | `String` | Agent Con State |
| 172 | agentConStateDesc | `String` | Agent Con State Description |
| 173 | agentConSxfirstName | `String` | Agent Con Sxfirst Name |
| 174 | agentConSxname | `String` | Agent Con Sxname |
| 175 | agentConTerritory | `String` | Agent Con Territory |
| 176 | agentConTitle | `String` | Agent Con Title |
| 177 | agentConXfirst | `String` | Agent Con Xfirst |
| 178 | agentConXlast | `String` | Agent Con Xlast |
| 179 | agentConXletterGreeting | `String` | Agent Con Xletter Greeting |
| 180 | agentConXname | `String` | Agent Con Xname |
| 181 | agentConZipcode | `String` | Agent Con Zipcode |
| 182 | agentCountry | `String` | Agent Country |
| 183 | agentCountryDesc | `String` | Agent Country Description |
| 184 | agentDsi | `Float` | Agent Dsi |
| 185 | agentEmail | `String` | Agent Email |
| 186 | agentFax | `String` | Agent Fax |
| 187 | agentHistoryYn | `String` | Agent History Y/N |
| 188 | agentIataCompType | `String` | Agent IATA Comp Type |
| 189 | agentId | `Float` | Agent ID |
| 190 | agentIndustryCode | `String` | Agent Industry Code |
| 191 | agentLanguage | `String` | Agent Language |
| 192 | agentLanguageDesc | `String` | Agent Language Description |
| 193 | agentLinkId | `Float` | Agent Link ID |
| 194 | agentLinkType | `String` | Agent Link Type |
| 195 | agentMailType | `String` | Agent Mail Type |
| 196 | agentMarkets | `String` | Agent Markets |
| 197 | agentName | `String` | Agent Name |
| 198 | agentNameId | `Float` | Agent Name ID |
| 199 | agentNameType | `String` | Agent Name Type |
| 200 | agentName2 | `String` | Agent Name2 |
| 201 | agentName3 | `String` | Agent Name3 |
| 202 | agentOrganizationid | `Float` | Agent Organizationid |
| 203 | agentPhone | `String` | Agent Phone |
| 204 | agentPrimaryYn | `String` | Agent Primary Y/N |
| 205 | agentProductInterest | `String` | Agent Product Interest |
| 206 | agentRelationship | `String` | Agent Relationship |
| 207 | agentRelationshipDesc | `String` | Agent Relationship Description |
| 208 | agentRepStateCode | `String` | Agent Reporting State Code |
| 209 | agentResort | `String` | Agent Property |
| 210 | agentScope | `String` | Agent Scope |
| 211 | agentScopeCity | `String` | Agent Scope City |
| 212 | agentSname | `String` | Agent Sname |
| 213 | agentState | `String` | Agent State |
| 214 | agentStateDesc | `String` | Agent State Description |
| 215 | agentSxname | `String` | Agent Sxname |
| 216 | agentTerritory | `String` | Agent Territory |
| 217 | agentXdisplayName | `String` | Agent Xdisplay Name |
| 218 | agentXenvelopeGreeting | `String` | Agent Xenvelope Greeting |
| 219 | agentXfirstName | `String` | Agent Xfirst Name |
| 220 | agentZipcode | `String` | Agent Zipcode |
| 221 | alias | `String` | Alias |
| 222 | allOwners | `String` | All Owners |
| 223 | allotmentCode | `String` | Allotment Code |
| 224 | allotmentHeaderId | `Float` | Allotment Header ID |
| 225 | allotmentOrigion | `String` | Allotment Origion |
| 226 | allotmentType | `String` | Type of Block alloted for the group. |
| 227 | arrivalTime | `DateTime` | Arrival Time |
| 228 | attendees | `Float` | Attendees |
| 229 | avgPeoplePerRoom | `Float` | Avg People Per Room |
| 230 | avgRateNet | `Float` | Avg Rate Net |
| 231 | beginDate | `Date` | Begin Date |
| 232 | bookingStatus | `String` | Booking Status |
| 233 | bookingStatusOrderby | `Float` | Booking Status Orderby |
| 234 | bookingStatusType | `String` | Booking Status Type |
| 235 | bookingStatusorder | `Float` | Booking Statusorder |
| 236 | bookingmethod | `String` | Bookingmethod |
| 237 | bookingmethoddesc | `String` | Bookingmethoddesc |
| 238 | bookingtype | `String` | Bookingtype |
| 239 | breakfastDesc | `String` | Bfst Description |
| 240 | breakfastPrice | `Float` | Breakfast Price |
| 241 | breakfastYn | `String` | Bfst Y/N |
| 242 | busblockId | `Float` | Busblock ID |
| 243 | busblockProperty | `String` | Busblock Property |
| 244 | cBreakfastPrice | `Float` | Central Bfst Price |
| 245 | cCompRoomValue | `Float` | Central Comp Room Value |
| 246 | cExchangeDate | `Date` | Central Xchange Date |
| 247 | cExchangeRate | `Float` | Central Xchange Rate |
| 248 | cMtgBudget | `Float` | Central Mtg Budget |
| 249 | cPorteragePrice | `Float` | Central Porterage Price |
| 250 | cPotRoomRevenue | `Float` | Central Pot Room Revenue |
| 251 | cServiceCharge | `Float` | Central Service Charge |
| 252 | cTaxAmount | `Float` | Central Tax Amount |
| 253 | cancelRule | `String` | Not Used |
| 254 | cancellationCode | `String` | Cancellation Code |
| 255 | cancellationDate | `Date` | Cancellation Date |
| 256 | cancellationDescription | `String` | Cancellation Description |
| 257 | cancellationNo | `Float` | Cancellation Number |
| 258 | catCanxCode | `String` | Catering Canx Code |
| 259 | catCanxDate | `Date` | Catering Canx Date |
| 260 | catCanxNumber | `Float` | Catering Canx No |
| 261 | catCurrency | `String` | Catering Currency |
| 262 | catCutoff | `Date` | Catering Cutoff |
| 263 | catDecision | `Date` | Catering Decision |
| 264 | catExchange | `Float` | Catering Exchange |
| 265 | catFollowup | `Date` | Catering Followup |
| 266 | catOwner | `Float` | Catering Owner |
| 267 | catOwnerCode | `String` | Catering Owner Code |
| 268 | catOwnerEmail | `String` | Catering Owner Email |
| 269 | catOwnerFax | `String` | Catering Owner Fax |
| 270 | catOwnerPhone | `String` | Catering Owner Phone |
| 271 | catOwnerProperty | `String` | Property of Catering Owner |
| 272 | catOwnerSrepname | `String` | Catering Owner Srepname |
| 273 | catOwnerTitle | `String` | Catering Owner Title |
| 274 | catOwners | `String` | Catering Owners |
| 275 | catQuoteCurrency | `String` | Catering Quote Curr |
| 276 | catStatus | `String` | Catering Status |
| 277 | catStatusOrderby | `Float` | Catering Status Orderby |
| 278 | catStatusType | `String` | Catering Status Type describes Inventory behaviour |
| 279 | catStatusorder | `Float` | Catering Statusorder |
| 280 | cateringCanxDesc | `String` | Cat Canx Description |
| 281 | cateringPkgsYn | `String` | Catering Pkgs Y/N |
| 282 | cateringonlyYn | `String` | Cateringonly Y/N |
| 283 | centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| 284 | channel | `String` | Channel |
| 285 | commission | `String` | Commission |
| 286 | compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| 287 | compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| 288 | compRooms | `Float` | Number of complimentary Rooms |
| 289 | compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| 290 | companyNameId | `Float` | Company Name ID |
| 291 | competition | `String` | Competition |
| 292 | conActionCode | `String` | Con Action Code |
| 293 | conActiveYn | `String` | Con Active Y/N |
| 294 | conAddressType | `String` | Con Address Type |
| 295 | conAddress1 | `String` | Con Address1 |
| 296 | conAddress2 | `String` | Con Address2 |
| 297 | conAddress3 | `String` | Con Address3 |
| 298 | conAddress4 | `String` | Con Address4 |
| 299 | conAlternateLanguage | `String` | Con Alternate Language |
| 300 | conAlternateLanguageDesc | `String` | Con Xlanguage Description |
| 301 | conAlternateSalutation | `String` | Con Alternate Salutation |
| 302 | conAlternateTitle | `String` | Con Alternate Title |
| 303 | conArNumber | `String` | Con AR No |
| 304 | conAvailabilityOverride | `String` | Con Availability Override |
| 305 | conBirthDate | `Date` | Con Birth Date |
| 306 | conBirthDateStr | `String` | Con Birth Date Str |
| 307 | conBookingId | `Float` | Con Booking ID |
| 308 | conBusinessGreeting | `String` | Con Business Greeting |
| 309 | conCashBlInd | `String` | Con Cash Bl Individual |
| 310 | conCity | `String` | Con City |
| 311 | conCityExt | `String` | Con City Ext |
| 312 | conContactYn | `String` | Con Contact Y/N |
| 313 | conCountry | `String` | Con Country |
| 314 | conCountryDesc | `String` | Con Country Description |
| 315 | conDepartment | `String` | Con Department |
| 316 | conDsi | `Float` | Con Dsi |
| 317 | conFirst | `String` | Con First |
| 318 | conHistoryYn | `String` | Con History Y/N |
| 319 | conIataCompType | `String` | Con IATA Comp Type |
| 320 | conId | `Float` | Con ID |
| 321 | conIndustryCode | `String` | Con Industry Code |
| 322 | conInfluence | `String` | Con Influence |
| 323 | conLanguage | `String` | Con Language |
| 324 | conLanguageDesc | `String` | Con Language Description |
| 325 | conLast | `String` | Con Last |
| 326 | conLetterGreeting | `String` | Con Letter Greeting |
| 327 | conLinkId | `Float` | Con Link ID |
| 328 | conLinkType | `String` | Con Link Type |
| 329 | conMailType | `String` | Con Mail Type |
| 330 | conMarkets | `String` | Con Markets |
| 331 | conMiddle | `String` | Con Middle |
| 332 | conName | `String` | Con Name |
| 333 | conNameType | `String` | Con Name Type |
| 334 | conName2 | `String` | Con Name2 |
| 335 | conName3 | `String` | Con Name3 |
| 336 | conOrganizationid | `Float` | Con Organizationid |
| 337 | conPosition | `String` | Con Position |
| 338 | conPrimaryYn | `String` | Con Primary Y/N |
| 339 | conProductInterest | `String` | Con Product Interest |
| 340 | conRelationship | `String` | Con Relationship |
| 341 | conRelationshipDesc | `String` | Con Relationship Description |
| 342 | conRepActionCode | `String` | Con Reporting Actioncode |
| 343 | conRepInfluence | `String` | Con Reporting Influence |
| 344 | conRepMarkets | `String` | Con Reporting Markets |
| 345 | conRepNameType | `String` | Con Reporting Name Type |
| 346 | conRepScope | `String` | Con Reporting Scope |
| 347 | conRepScopeCity | `String` | Con Reporting Scope City |
| 348 | conRepStateCode | `String` | Con Reporting State Code |
| 349 | conRepStateDescription | `String` | Con Reporting State Desc |
| 350 | conRepTerritory | `String` | Con Reporting Territory |
| 351 | conRepTitle | `String` | Con Reporting Title |
| 352 | conResort | `String` | Con Property |
| 353 | conScope | `String` | Con Scope |
| 354 | conScopeCity | `String` | Con Scope City |
| 355 | conSfirst | `String` | Con Sfirst |
| 356 | conSname | `String` | Con Sname |
| 357 | conSrepCode | `String` | Con Srep Code |
| 358 | conSrepId | `Float` | Con Srep ID |
| 359 | conSrepName | `String` | Con Srep Name |
| 360 | conState | `String` | Con State |
| 361 | conStateDesc | `String` | Con State Description |
| 362 | conSxfirstName | `String` | Con Sxfirst Name |
| 363 | conSxname | `String` | Con Sxname |
| 364 | conTerritory | `String` | Con Territory |
| 365 | conTitle | `String` | Con Title |
| 366 | conXfirst | `String` | Con Xfirst |
| 367 | conXlast | `String` | Con Xlast |
| 368 | conXletterGreeting | `String` | Con Xletter Greeting |
| 369 | conXname | `String` | Con Xname |
| 370 | contactEmail | `String` | Reservation Contact id salutation information. |
| 371 | contactFax | `String` | Contact Fax |
| 372 | contactNameId | `Float` | Contact Name ID |
| 373 | contactPhone | `String` | Contact Phone |
| 374 | contactZipcode | `String` | Contact Zipcode |
| 375 | contractNr | `String` | Contract Nr |
| 376 | conversionCode | `String` | Conversion Code |
| 377 | currencyCode | `String` | Currency Code |
| 378 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 379 | dateOpenedForPickup | `Date` | Business Date when the business block was opened for pickup. |
| 380 | datePro | `DateTime` | Date Pro |
| 381 | dateTen | `DateTime` | Date Ten |
| 382 | defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| 383 | deletedflag | `String` | Deleted Flag |
| 384 | departureTime | `DateTime` | Departure Time |
| 385 | description | `String` | Description |
| 386 | destination | `String` | Destination |
| 387 | detailsOkYn | `String` | Details Ok Y/N |
| 388 | distributedYn | `String` | Distributed Y/N |
| 389 | dmlSeqNumber | `Float` | Dml Sequence No |
| 390 | downloadDate | `Date` | Download Date |
| 391 | downloadResort | `String` | Download Property |
| 392 | downloadSrep | `Float` | Download Srep |
| 393 | dueDate | `Date` | Due Date |
| 394 | elastic | `String` | Elastic |
| 395 | endDate | `Date` | End Date |
| 396 | eventsGuaranteedYn | `String` | Events Guaranteed Y/N |
| 397 | exchangePostingType | `String` | Exchange Posting Type |
| 398 | exchangeRate | `Float` | Exchange Rate |
| 399 | externalLocked | `String` | External Locked |
| 400 | functiontype | `String` | Functiontype |
| 401 | giid | `String` | Group IATA Number. |
| 402 | guaranteeCode | `String` | Guarantee Code |
| 403 | iataCorpNumber | `String` | IATA Corp No |
| 404 | inactiveDate | `Date` | Inactive Date |
| 405 | info | `String` | Not Used |
| 406 | infoboard | `String` | Infoboard |
| 407 | insertDate | `DateTime` | Insert Date |
| 408 | insertUser | `Float` | Insert User |
| 409 | insertUserName | `String` | The name of the user who created the record. |
| 410 | invCutoffDate | `Date` | Invoice Cutoff Date |
| 411 | invCutoffDays | `Float` | Invoice Cutoff Days |
| 412 | isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| 413 | isacQuoteId | `String` | Isac Quote ID |
| 414 | jRNUpdateDate | `Date` | JRN Update Date |
| 415 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 416 | laptopChange | `Float` | Laptop Change |
| 417 | leadOrigin | `String` | Lead Origin |
| 418 | leadSource | `String` | Lead Source |
| 419 | linkDate | `DateTime` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| 420 | lostToProperty | `String` | Competitor to whom the booking was lost. |
| 421 | mainmarket | `String` | Mainmarket |
| 422 | marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| 423 | marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| 424 | marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| 425 | marketCode | `String` | Market Code |
| 426 | masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| 427 | methodDue | `Date` | Method Due |
| 428 | mtgBudget | `Float` | Meeting Budget |
| 429 | nonCompete | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| 430 | nonCompeteCode | `String` | Indicates the Non-Compete code of a block. |
| 431 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 432 | originalRateCode | `String` | Not used |
| 433 | owner | `Float` | Owner |
| 434 | ownerCode | `String` | Owner Code |
| 435 | ownerCodeSrepname | `String` | Owner Code Srepname |
| 436 | ownerEmail | `String` | Owner Email |
| 437 | ownerFax | `String` | Owner Fax |
| 438 | ownerPhone | `String` | Owner Phone |
| 439 | ownerResort | `String` | Owner Property |
| 440 | ownerTitle | `String` | Owner Title |
| 441 | paymentMethod | `String` | Payment Method |
| 442 | peakRooms | `Float` | Peak Rooms |
| 443 | porteragePrice | `Float` | Porterage Price |
| 444 | porterageYn | `String` | Porterage Y/N |
| 445 | printAccountActiveYN | `String` | Print Acc Active Y/N |
| 446 | printAccountAddress1 | `String` | Print Account Address1 |
| 447 | printAccountAddress2 | `String` | Print Account Address2 |
| 448 | printAccountAddress3 | `String` | Print Account Address3 |
| 449 | printAccountAddress4 | `String` | Print Account Address4 |
| 450 | printAccountBookingId | `Float` | Print Acc Booking ID |
| 451 | printAccountCity | `String` | Print Account City |
| 452 | printAccountCityExt | `String` | Print Account City Ext |
| 453 | printAccountCountry | `String` | Print Account Country |
| 454 | printAccountCountryDesc | `String` | Print Acc Country Description |
| 455 | printAccountDsi | `Float` | Print Account Dsi |
| 456 | printAccountId | `Float` | Print Acc ID |
| 457 | printAccountLinkId | `Float` | Print Acc Link ID |
| 458 | printAccountLinkType | `String` | Print Account Link Type |
| 459 | printAccountName | `String` | Print Account Name |
| 460 | printAccountName2 | `String` | Print Account Name2 |
| 461 | printAccountName3 | `String` | Print Account Name3 |
| 462 | printAccountOrganizationid | `Float` | Print Account Organizationid |
| 463 | printAccountPhone | `String` | Print Account Phone |
| 464 | printAccountPosition | `String` | Print Account Position |
| 465 | printAccountPrimaryYN | `String` | Print Acc Primary Y/N |
| 466 | printAccountProperty | `String` | Print Account Resort |
| 467 | printAccountRepStateCode | `String` | Print Acc Reporting State Code |
| 468 | printAccountRepStateDescription | `String` | Print Acc Reporting State Desc |
| 469 | printAccountRepTerritory | `String` | Print Acc Reporting Territory |
| 470 | printAccountScope | `String` | Print Account Scope |
| 471 | printAccountScopeCity | `String` | Print Account Scope City |
| 472 | printAccountSname | `String` | Print Account Sname |
| 473 | printAccountState | `String` | Print Account State |
| 474 | printAccountStateDesc | `String` | Print Acc State Description |
| 475 | printAccountSxname | `String` | Print Account Sxname |
| 476 | printAccountTerritory | `String` | Print Account Territory |
| 477 | printAccountXdisplayName | `String` | Print Account Xdisplay Name |
| 478 | printAccountXenvelopeGreeting | `String` | Print Account Xenvelope Greeting |
| 479 | printAccountXfirstName | `String` | Print Account Xfirst Name |
| 480 | printAccountXname | `String` | Print Account Xname |
| 481 | printAccountZipcode | `String` | Print Account Zipcode |
| 482 | printConAddress1 | `String` | Print Con Address1 |
| 483 | printConAddress2 | `String` | Print Con Address2 |
| 484 | printConAddress3 | `String` | Print Con Address3 |
| 485 | printConAddress4 | `String` | Print Con Address4 |
| 486 | printConAlternateSalutation | `String` | Print Con Alternate Salutation |
| 487 | printConBusinessGreeting | `String` | Print Con Business Greeting |
| 488 | printConCity | `String` | Print Con City |
| 489 | printConCityExt | `String` | Print Con City Ext |
| 490 | printConCountry | `String` | Print Con Country |
| 491 | printConCountryDesc | `String` | Print Con Country Description |
| 492 | printConDepartment | `String` | Print Con Department |
| 493 | printConDsi | `Float` | Print Con Dsi |
| 494 | printConEmail | `String` | Print Con Email |
| 495 | printConFirst | `String` | Print Con First |
| 496 | printConId | `Float` | Print Con ID |
| 497 | printConLast | `String` | Print Con Last |
| 498 | printConLetterGreeting | `String` | Print Con Letter Greeting |
| 499 | printConLinkId | `Float` | Print Con Link ID |
| 500 | printConLinkType | `String` | Print Con Link Type |
| 501 | printConMiddle | `String` | Print Con Middle |
| 502 | printConName | `String` | Print Con Name |
| 503 | printConName2 | `String` | Print Con Name2 |
| 504 | printConName3 | `String` | Print Con Name3 |
| 505 | printConOrganizationid | `Float` | Print Con Organizationid |
| 506 | printConPhone | `String` | Print Con Phone |
| 507 | printConPosition | `String` | Print Con Position |
| 508 | printConPrimaryYn | `String` | Print Con Primary Y/N |
| 509 | printConProductInterest | `String` | Print Con Product Interest |
| 510 | printConRelationship | `String` | Print Con Relationship |
| 511 | printConRelationshipDesc | `String` | Print Con Relationship Description |
| 512 | printConRepStateCode | `String` | Print Con Reporting State Code |
| 513 | printConRepTitle | `String` | Print Con Reporting Title |
| 514 | printConResort | `String` | Print Con Property |
| 515 | printConScope | `String` | Print Con Scope |
| 516 | printConScopeCity | `String` | Print Con Scope City |
| 517 | printConSname | `String` | Print Con Sname |
| 518 | printConState | `String` | Print Con State |
| 519 | printConStateDesc | `String` | Print Con State Description |
| 520 | printConSxname | `String` | Print Con Sxname |
| 521 | printConTerritory | `String` | Print Con Territory |
| 522 | printConTitle | `String` | Print Con Title |
| 523 | printConXdisplayName | `String` | Print Con Xdisplay Name |
| 524 | printConXfirst | `String` | Print Con Xfirst |
| 525 | printConXlast | `String` | Print Con Xlast |
| 526 | printConXletterGreeting | `String` | Print Con Xletter Greeting |
| 527 | printConZipcode | `String` | Print Con Zipcode |
| 528 | profileDesc | `String` | Profile Description |
| 529 | profileId | `Float` | Profile ID |
| 530 | program | `String` | Program |
| 531 | property | `String` | Code to uniquely identify the Property |
| 532 | rankingCode | `String` | Indicates the ranking of a block. |
| 533 | rateCode | `String` | Rate Code |
| 534 | rateGuaranteedYn | `String` | Rate Guaranteed Y/N. |
| 535 | rateOverride | `String` | Indicates if the rate code can be overridden. |
| 536 | rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| 537 | rateProtection | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| 538 | relatedResorts | `String` | Related Resorts |
| 539 | repBlockStatusDescription | `String` | Reporting Block Status Description |
| 540 | repBookingmethod | `String` | Reporting Bookingmethod |
| 541 | repBookingmethodDescription | `String` | Reporting Bookingmethod Desc |
| 542 | repBookingtype | `String` | Reporting Bookingtype |
| 543 | repBsOrderBy | `Float` | Reporting Bs Order By |
| 544 | repCateringOrderBy | `Float` | Reporting Cat Order By |
| 545 | repCateringStatus | `String` | Reporting Cat Status |
| 546 | repCateringStatusDescription | `String` | Reporting Cat Status Description |
| 547 | repChannel | `String` | Reporting Channel |
| 548 | repConversionCode | `String` | Reporting Conversion Code |
| 549 | repDestination | `String` | Reporting Destination |
| 550 | repGuaranteeCode | `String` | Reporting Guarantee Code |
| 551 | repMarketCode | `String` | Reporting Market Code |
| 552 | repNonCompeteCode | `String` | Reporting Non Compete Code |
| 553 | repPaymentMethod | `String` | Reporting Payment Method |
| 554 | repRankingCode | `String` | Reporting Ranking Code |
| 555 | repSourceCode | `String` | Reporting Source Code |
| 556 | representative | `String` | Representative |
| 557 | reserveInventoryYn | `String` | Reserve Inventory Y/N |
| 558 | resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| 559 | revBlocked | `Float` | Revenue Blocked |
| 560 | revBlockedNet | `Float` | Revenue Blocked Net |
| 561 | revContracted | `Float` | Revenue Contracted |
| 562 | rivMarketSegment | `String` | Not used |
| 563 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 564 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 565 | roomsBlocked | `Float` | Rooms Blocked |
| 566 | roomsContracted | `Float` | Rooms Contracted |
| 567 | roomsCurrency | `String` | Rooms Currency |
| 568 | roomsDecision | `Date` | Rooms Decision |
| 569 | roomsExchange | `Float` | Rooms Exchange |
| 570 | roomsFollowup | `Date` | Rooms Followup |
| 571 | roomsOwner | `Float` | Rooms Owner |
| 572 | roomsOwnerCode | `String` | Rooms Owner Code |
| 573 | roomsOwnerEmail | `String` | Rooms Owner Email |
| 574 | roomsOwnerFax | `String` | Rooms Owner Fax |
| 575 | roomsOwnerPhone | `String` | Rooms Owner Phone |
| 576 | roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| 577 | roomsOwnerSrepname | `String` | Rooms Owner Srepname |
| 578 | roomsOwnerTitle | `String` | Rooms Owner Title |
| 579 | roomsOwners | `String` | Rooms Owners |
| 580 | roomsPerDay | `Float` | Rooms Per Day |
| 581 | roomsQuoteCurr | `String` | Rms Quote Currency |
| 582 | salesId | `String` | Not used |
| 583 | sbegindate | `Date` | Sbegindate |
| 584 | secConActionCode | `String` | Sec Con Action Code |
| 585 | secConActiveYn | `String` | Sec Con Active Y/N |
| 586 | secConAddress1 | `String` | Sec Con Address1 |
| 587 | secConAddress2 | `String` | Sec Con Address2 |
| 588 | secConAddress3 | `String` | Sec Con Address3 |
| 589 | secConAddress4 | `String` | Sec Con Address4 |
| 590 | secConAlternateLanguage | `String` | Sec Con Alternate Language |
| 591 | secConAlternateLanguageDesc | `String` | Sec Con Xlanguage Description |
| 592 | secConAlternateSalutation | `String` | Sec Con Alternate Salutation |
| 593 | secConAlternateTitle | `String` | Sec Con Alternate Title |
| 594 | secConBirthDate | `Date` | Sec Con Birth Date |
| 595 | secConBirthDateStr | `String` | Sec Con Birth Date Str |
| 596 | secConBookingId | `Float` | Sec Con Booking ID |
| 597 | secConBusinessGreeting | `String` | Sec Con Business Greeting |
| 598 | secConCashBlInd | `String` | Sec Con Cash Bl Individual |
| 599 | secConCity | `String` | Sec Con City |
| 600 | secConCityExt | `String` | Sec Con City Ext |
| 601 | secConContactYn | `String` | Sec Con Contact Y/N |
| 602 | secConCountry | `String` | Sec Con Country |
| 603 | secConCountryDesc | `String` | Sec Con Country Description |
| 604 | secConDepartment | `String` | Sec Con Department |
| 605 | secConDsi | `Float` | Sec Con Dsi |
| 606 | secConEmail | `String` | Sec Con Email |
| 607 | secConFax | `String` | Sec Con Fax |
| 608 | secConFirstName | `String` | Sec Con First Name |
| 609 | secConFullName | `String` | Sec Con Full Name |
| 610 | secConId | `Float` | Sec Con ID |
| 611 | secConInfluence | `String` | Sec Con Influence |
| 612 | secConLanguage | `String` | Sec Con Language |
| 613 | secConLanguageDesc | `String` | Sec Con Language Description |
| 614 | secConLastName | `String` | Sec Con Last Name |
| 615 | secConLetterGreeting | `String` | Sec Con Letter Greeting |
| 616 | secConLinkId | `Float` | Sec Con Link ID |
| 617 | secConLinkType | `String` | Sec Con Link Type |
| 618 | secConMarkets | `String` | Sec Con Markets |
| 619 | secConMiddleName | `String` | Sec Con Middle Name |
| 620 | secConNameType | `String` | Sec Con Name Type |
| 621 | secConName2 | `String` | Sec Con Name2 |
| 622 | secConName3 | `String` | Sec Con Name3 |
| 623 | secConOrganizationid | `Float` | Sec Con Organizationid |
| 624 | secConPhone | `String` | Sec Con Phone |
| 625 | secConPosition | `String` | Sec Con Position |
| 626 | secConPrimaryYn | `String` | Sec Con Primary Y/N |
| 627 | secConProductInterest | `String` | Sec Con Product Interest |
| 628 | secConRelationship | `String` | Sec Con Relationship |
| 629 | secConRelationshipDesc | `String` | Sec Con Relationship Description |
| 630 | secConRepActionCode | `String` | Sec Con Reporting Actioncode |
| 631 | secConRepInfluence | `String` | Sec Con Reporting Influence |
| 632 | secConRepMarkets | `String` | Sec Con Reporting Markets |
| 633 | secConRepNameType | `String` | Sec Con Reporting Name Type |
| 634 | secConRepScope | `String` | Sec Con Reporting Scope |
| 635 | secConRepScopeCity | `String` | Sec Con Reporting Scope City |
| 636 | secConRepStateCode | `String` | Sec Con Reporting State Code |
| 637 | secConRepStateDescription | `String` | Sec Con Reporting State Desc |
| 638 | secConRepTerritory | `String` | Sec Con Reporting Territory |
| 639 | secConRepTitle | `String` | Sec Con Reporting Title |
| 640 | secConResort | `String` | Sec Con Property |
| 641 | secConScope | `String` | Sec Con Scope |
| 642 | secConScopeCity | `String` | Sec Con Scope City |
| 643 | secConSfirst | `String` | Sec Con Sfirst |
| 644 | secConSname | `String` | Sec Con Sname |
| 645 | secConSrepCode | `String` | Sec Con Srep Code |
| 646 | secConSrepId | `Float` | Sec Con Srep ID |
| 647 | secConSrepName | `String` | Sec Con Srep Name |
| 648 | secConState | `String` | Sec Con State |
| 649 | secConStateDesc | `String` | Sec Con State Description |
| 650 | secConSxfirstName | `String` | Sec Con Sxfirst Name |
| 651 | secConSxname | `String` | Sec Con Sxname |
| 652 | secConTerritory | `String` | Sec Con Territory |
| 653 | secConTitle | `String` | Sec Con Title |
| 654 | secConXenvelopeGreeting | `String` | Sec Con Xenvelope Greeting |
| 655 | secConXfirstName | `String` | Sec Con Xfirst Name |
| 656 | secConXfullName | `String` | Sec Con Xfull Name |
| 657 | secConXlastName | `String` | Sec Con Xlast Name |
| 658 | secConZipCode | `String` | Sec Con Zipcode Code |
| 659 | senddate | `Date` | Senddate |
| 660 | sentDate | `DateTime` | Sent Date |
| 661 | serviceCharge | `Float` | Service Charge |
| 662 | shoulderBeginDate | `Date` | Shoulder Begin Date |
| 663 | shoulderEndDate | `Date` | Shoulder End Date |
| 664 | source | `String` | Source |
| 665 | sourceActiveYn | `String` | Source Active Y/N |
| 666 | sourceAddressType | `String` | Source Address Type |
| 667 | sourceAddress1 | `String` | Source Address1 |
| 668 | sourceAddress2 | `String` | Source Address2 |
| 669 | sourceAlternateLanguage | `String` | Source Alternate Language |
| 670 | sourceAlternateLanguageDesc | `String` | Source Xlanguage Description |
| 671 | sourceAlternateSalutation | `String` | Source Alternate Salutation |
| 672 | sourceAlternateTitle | `String` | Source Alternate Title |
| 673 | sourceBookingId | `Float` | Source Booking ID |
| 674 | sourceBusinessGreeting | `String` | Source Business Greeting |
| 675 | sourceCity | `String` | Source City |
| 676 | sourceCityExt | `String` | Source City Ext |
| 677 | sourceConActionCode | `String` | Source Con Action Code |
| 678 | sourceConActiveYn | `String` | Source Con Active Y/N |
| 679 | sourceConAddressType | `String` | Source Con Address Type |
| 680 | sourceConAddress1 | `String` | Source Con Address1 |
| 681 | sourceConAddress2 | `String` | Source Con Address2 |
| 682 | sourceConAddress3 | `String` | Source Con Address3 |
| 683 | sourceConAddress4 | `String` | Source Con Address4 |
| 684 | sourceConAlternateLanguage | `String` | Source Con Alternate Language |
| 685 | sourceConAlternateLanguageDesc | `String` | Source Con Xlanguage Description |
| 686 | sourceConAlternateSalutation | `String` | Source Con Alternate Salutation |
| 687 | sourceConAlternateTitle | `String` | Source Con Alternate Title |
| 688 | sourceConArNumber | `String` | Source Con AR No |
| 689 | sourceConAuSrepCode | `String` | Source Con Au Srep Code |
| 690 | sourceConAvailabilityOverride | `String` | Source Con Availability Override |
| 691 | sourceConBirthDate | `Date` | Source Con Birth Date |
| 692 | sourceConBirthDateStr | `String` | Source Con Birth Date Str |
| 693 | sourceConBookingId | `Float` | Source Con Booking ID |
| 694 | sourceConBusinessGreeting | `String` | Source Con Business Greeting |
| 695 | sourceConCashBlInd | `String` | Source Con Cash Bl Individual |
| 696 | sourceConCity | `String` | Source Con City |
| 697 | sourceConCityExt | `String` | Source Con City Ext |
| 698 | sourceConContactYn | `String` | Source Con Contact Y/N |
| 699 | sourceConCountry | `String` | Source Con Country |
| 700 | sourceConCountryDesc | `String` | Source Con Country Description |
| 701 | sourceConDepartment | `String` | Source Con Department |
| 702 | sourceConDsi | `Float` | Source Con Dsi |
| 703 | sourceConEmail | `String` | Source Con Email |
| 704 | sourceConFax | `String` | Source Con Fax |
| 705 | sourceConFirst | `String` | Source Con First |
| 706 | sourceConHistoryYn | `String` | Source Con History Y/N |
| 707 | sourceConIataCompType | `String` | Source Con IATA Comp Type |
| 708 | sourceConId | `Float` | Source Con ID |
| 709 | sourceConIndustryCode | `String` | Source Con Industry Code |
| 710 | sourceConInfluence | `String` | Source Con Influence |
| 711 | sourceConLanguage | `String` | Source Con Language |
| 712 | sourceConLanguageDesc | `String` | Source Con Language Description |
| 713 | sourceConLast | `String` | Source Con Last |
| 714 | sourceConLetterGreeting | `String` | Source Con Letter Greeting |
| 715 | sourceConLinkId | `Float` | Source Con Link ID |
| 716 | sourceConLinkType | `String` | Source Con Link Type |
| 717 | sourceConMailType | `String` | Source Con Mail Type |
| 718 | sourceConMarkets | `String` | Source Con Markets |
| 719 | sourceConMiddle | `String` | Source Con Middle |
| 720 | sourceConName | `String` | Source Con Name |
| 721 | sourceConNameType | `String` | Source Con Name Type |
| 722 | sourceConName2 | `String` | Source Con Name2 |
| 723 | sourceConName3 | `String` | Source Con Name3 |
| 724 | sourceConOrganizationid | `Float` | Source Con Organizationid |
| 725 | sourceConPhone | `String` | Source Con Phone |
| 726 | sourceConPosition | `String` | Source Con Position |
| 727 | sourceConPrimaryYn | `String` | Source Con Primary Y/N |
| 728 | sourceConProductInterest | `String` | Source Con Product Interest |
| 729 | sourceConRelationship | `String` | Source Con Relationship |
| 730 | sourceConRelationshipDesc | `String` | Source Con Relationship Description |
| 731 | sourceConRepActionCode | `String` | Source Con Reporting Actioncode |
| 732 | sourceConRepInfluence | `String` | Source Con Reporting Influence |
| 733 | sourceConRepMarkets | `String` | Source Con Reporting Markets |
| 734 | sourceConRepNameType | `String` | Source Con Reporting Name Type |
| 735 | sourceConRepScope | `String` | Source Con Reporting Scope |
| 736 | sourceConRepScopeCity | `String` | Source Con Reporting Scope City |
| 737 | sourceConRepStateCode | `String` | Source Con Reporting State Code |
| 738 | sourceConRepStateDescription | `String` | Source Con Reporting State Desc |
| 739 | sourceConRepTerritory | `String` | Source Con Reporting Territory |
| 740 | sourceConRepTitle | `String` | Source Con Reporting Title |
| 741 | sourceConResort | `String` | Source Con Property |
| 742 | sourceConScope | `String` | Source Con Scope |
| 743 | sourceConScopeCity | `String` | Source Con Scope City |
| 744 | sourceConSfirst | `String` | Source Con Sfirst |
| 745 | sourceConSname | `String` | Source Con Sname |
| 746 | sourceConSrepId | `Float` | Source Con Srep ID |
| 747 | sourceConSrepName | `String` | Source Con Srep Name |
| 748 | sourceConState | `String` | Source Con State |
| 749 | sourceConStateDesc | `String` | Source Con State Description |
| 750 | sourceConSxfirstName | `String` | Source Con Sxfirst Name |
| 751 | sourceConSxname | `String` | Source Con Sxname |
| 752 | sourceConTerritory | `String` | Source Con Territory |
| 753 | sourceConTitle | `String` | Source Con Title |
| 754 | sourceConXfirst | `String` | Source Con Xfirst |
| 755 | sourceConXlast | `String` | Source Con Xlast |
| 756 | sourceConXletterGreeting | `String` | Source Con Xletter Greeting |
| 757 | sourceConXname | `String` | Source Con Xname |
| 758 | sourceConZipcode | `String` | Source Con Zipcode |
| 759 | sourceCountry | `String` | Source Country |
| 760 | sourceCountryDesc | `String` | Source Country Description |
| 761 | sourceDsi | `Float` | Source Dsi |
| 762 | sourceEmail | `String` | Source Email |
| 763 | sourceFax | `String` | Source Fax |
| 764 | sourceId | `Float` | Source ID |
| 765 | sourceLinkId | `Float` | Source Link ID |
| 766 | sourceLinkType | `String` | Source Link Type |
| 767 | sourceName | `String` | Source Name |
| 768 | sourceNameId | `Float` | Source Name ID |
| 769 | sourceNameType | `String` | Source Name Type |
| 770 | sourceName2 | `String` | Source Name2 |
| 771 | sourceName3 | `String` | Source Name3 |
| 772 | sourceOrganizationid | `Float` | Source Organizationid |
| 773 | sourcePhone | `String` | Source Phone |
| 774 | sourcePrimaryYn | `String` | Source Primary Y/N |
| 775 | sourceRelationship | `String` | Source Relationship |
| 776 | sourceRelationshipDesc | `String` | Source Relationship Description |
| 777 | sourceRepStateCode | `String` | Source Reporting State Code |
| 778 | sourceResort | `String` | Comma separated list of properties to migrate. |
| 779 | sourceScope | `String` | Source Scope |
| 780 | sourceScopeCity | `String` | Source Scope City |
| 781 | sourceSname | `String` | Source Sname |
| 782 | sourceState | `String` | Source State |
| 783 | sourceStateDesc | `String` | Source State Description |
| 784 | sourceSxname | `String` | Source Sxname |
| 785 | sourceTerritory | `String` | Source Territory |
| 786 | sourceXdisplayName | `String` | Source Xdisplay Name |
| 787 | sourceXenvelopeGreeting | `String` | Source Xenvelope Greeting |
| 788 | sourceXfirstName | `String` | Source Xfirst Name |
| 789 | sourceZipcode | `String` | Source Zipcode |
| 790 | status | `String` | Status |
| 791 | superBlockId | `Float` | Parent Block ID |
| 792 | superBlockResort | `String` | Parent Resort |
| 793 | taxAmount | `Float` | Tax Amount |
| 794 | tbdRates | `String` | To be Determined Rates |
| 795 | tentativeLevel | `Float` | Not used |
| 796 | tracecode | `String` | Tracecode |
| 797 | udescription | `String` | This is upper-case description of regular description column for fast search |
| 798 | udfc01 | `String` | Udfc01 |
| 799 | udfc02 | `String` | Udfc02 |
| 800 | udfc03 | `String` | Udfc03 |
| 801 | udfc04 | `String` | Udfc04 |
| 802 | udfc05 | `String` | Udfc05 |
| 803 | udfc06 | `String` | Udfc06 |
| 804 | udfc07 | `String` | Udfc07 |
| 805 | udfc08 | `String` | Udfc08 |
| 806 | udfc09 | `String` | Udfc09 |
| 807 | udfc10 | `String` | Udfc10 |
| 808 | udfc11 | `String` | Udfc11 |
| 809 | udfc12 | `String` | Udfc12 |
| 810 | udfc13 | `String` | Udfc13 |
| 811 | udfc14 | `String` | Udfc14 |
| 812 | udfc15 | `String` | Udfc15 |
| 813 | udfc16 | `String` | Udfc16 |
| 814 | udfc17 | `String` | Udfc17 |
| 815 | udfc18 | `String` | Udfc18 |
| 816 | udfc19 | `String` | Udfc19 |
| 817 | udfc20 | `String` | Udfc20 |
| 818 | udfc21 | `String` | Udfc21 |
| 819 | udfc22 | `String` | Udfc22 |
| 820 | udfc23 | `String` | Udfc23 |
| 821 | udfc24 | `String` | Udfc24 |
| 822 | udfc25 | `String` | Udfc25 |
| 823 | udfc26 | `String` | Udfc26 |
| 824 | udfc27 | `String` | Udfc27 |
| 825 | udfc28 | `String` | Udfc28 |
| 826 | udfc29 | `String` | Udfc29 |
| 827 | udfc30 | `String` | Udfc30 |
| 828 | udfc31 | `String` | Udfc31 |
| 829 | udfc32 | `String` | Udfc32 |
| 830 | udfc33 | `String` | Udfc33 |
| 831 | udfc34 | `String` | Udfc34 |
| 832 | udfc35 | `String` | Udfc35 |
| 833 | udfc36 | `String` | Udfc36 |
| 834 | udfc37 | `String` | Udfc37 |
| 835 | udfc38 | `String` | Udfc38 |
| 836 | udfc39 | `String` | Udfc39 |
| 837 | udfc40 | `String` | Udfc40 |
| 838 | udfd01 | `Date` | Udfd01 |
| 839 | udfd02 | `Date` | Udfd02 |
| 840 | udfd03 | `Date` | Udfd03 |
| 841 | udfd04 | `Date` | Udfd04 |
| 842 | udfd05 | `Date` | Udfd05 |
| 843 | udfd06 | `Date` | Udfd06 |
| 844 | udfd07 | `Date` | Udfd07 |
| 845 | udfd08 | `Date` | Udfd08 |
| 846 | udfd09 | `Date` | Udfd09 |
| 847 | udfd10 | `Date` | Udfd10 |
| 848 | udfd11 | `Date` | Udfd11 |
| 849 | udfd12 | `Date` | Udfd12 |
| 850 | udfd13 | `Date` | Udfd13 |
| 851 | udfd14 | `Date` | Udfd14 |
| 852 | udfd15 | `Date` | Udfd15 |
| 853 | udfd16 | `Date` | Udfd16 |
| 854 | udfd17 | `Date` | Udfd17 |
| 855 | udfd18 | `Date` | Udfd18 |
| 856 | udfd19 | `Date` | Udfd19 |
| 857 | udfd20 | `Date` | Udfd20 |
| 858 | udfn01 | `Float` | Udfn01 |
| 859 | udfn02 | `Float` | Udfn02 |
| 860 | udfn03 | `Float` | Udfn03 |
| 861 | udfn04 | `Float` | Udfn04 |
| 862 | udfn05 | `Float` | Udfn05 |
| 863 | udfn06 | `Float` | Udfn06 |
| 864 | udfn07 | `Float` | Udfn07 |
| 865 | udfn08 | `Float` | Udfn08 |
| 866 | udfn09 | `Float` | Udfn09 |
| 867 | udfn10 | `Float` | Udfn10 |
| 868 | udfn11 | `Float` | Udfn11 |
| 869 | udfn12 | `Float` | Udfn12 |
| 870 | udfn13 | `Float` | Udfn13 |
| 871 | udfn14 | `Float` | Udfn14 |
| 872 | udfn15 | `Float` | Udfn15 |
| 873 | udfn16 | `Float` | Udfn16 |
| 874 | udfn17 | `Float` | Udfn17 |
| 875 | udfn18 | `Float` | Udfn18 |
| 876 | udfn19 | `Float` | Udfn19 |
| 877 | udfn20 | `Float` | Udfn20 |
| 878 | udfn21 | `Float` | Udfn21 |
| 879 | udfn22 | `Float` | Udfn22 |
| 880 | udfn23 | `Float` | Udfn23 |
| 881 | udfn24 | `Float` | Udfn24 |
| 882 | udfn25 | `Float` | Udfn25 |
| 883 | udfn26 | `Float` | Udfn26 |
| 884 | udfn27 | `Float` | Udfn27 |
| 885 | udfn28 | `Float` | Udfn28 |
| 886 | udfn29 | `Float` | Udfn29 |
| 887 | udfn30 | `Float` | Udfn30 |
| 888 | udfn31 | `Float` | Udfn31 |
| 889 | udfn32 | `Float` | Udfn32 |
| 890 | udfn33 | `Float` | Udfn33 |
| 891 | udfn34 | `Float` | Udfn34 |
| 892 | udfn35 | `Float` | Udfn35 |
| 893 | udfn36 | `Float` | Udfn36 |
| 894 | udfn37 | `Float` | Udfn37 |
| 895 | udfn38 | `Float` | Udfn38 |
| 896 | udfn39 | `Float` | Udfn39 |
| 897 | udfn40 | `Float` | Udfn40 |
| 898 | updateDate | `DateTime` | Update Date |
| 899 | updateUser | `Float` | Update User |
| 900 | updateUserName | `String` | Update User Name |
| 901 | uploadDate | `Date` | Upload Date |
| 902 | xaccName | `String` | Xacc Name |
| 903 | xagentName | `String` | Xagent Name |
| 904 | xsourceName | `String` | Extended Byte Source Name |

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
| scbusblockinfoDetailsAgentNameId | `FloatInput` | Agent Name ID |
| scbusblockinfoDetailsAllotmentCode | `StringInput` | Allotment Code |
| scbusblockinfoDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| scbusblockinfoDetailsBeginDate | `DateInput!` | Begin Date<br>`@mandatoryInput` |
| scbusblockinfoDetailsBookingStatus | `StringInput` | Booking Status |
| scbusblockinfoDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| scbusblockinfoDetailsCompanyNameId | `FloatInput` | Company Name ID |
| scbusblockinfoDetailsContactNameId | `FloatInput` | Contact Name ID |
| scbusblockinfoDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| scbusblockinfoDetailsEndDate | `DateInput!` | End Date<br>`@mandatoryInput` |
| scbusblockinfoDetailsGuaranteeCode | `StringInput` | Guarantee Code |
| scbusblockinfoDetailsInsertDate | `DateTimeInput` | Insert Date |
| scbusblockinfoDetailsInsertUser | `FloatInput` | Insert User |
| scbusblockinfoDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |
| scbusblockinfoDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| scbusblockinfoDetailsMarketCode | `StringInput` | Market Code |
| scbusblockinfoDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| scbusblockinfoDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| scbusblockinfoDetailsOwner | `FloatInput` | Owner |
| scbusblockinfoDetailsOwnerCode | `StringInput` | Owner Code |
| scbusblockinfoDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| scbusblockinfoDetailsRateCode | `StringInput` | Rate Code |
| scbusblockinfoDetailsShoulderBeginDate | `DateInput` | Shoulder Begin Date |
| scbusblockinfoDetailsShoulderEndDate | `DateInput` | Shoulder End Date |
| scbusblockinfoDetailsSourceNameId | `FloatInput` | Source Name ID |
| scbusblockinfoDetailsSuperBlockId | `FloatInput` | Parent Block ID |
| scbusblockinfoDetailsSuperBlockResort | `StringInput` | Parent Resort |
| scbusblockinfoDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |
| scbusblockinfoDetailsUpdateDate | `DateTimeInput` | Update Date |
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

**`mandatoryInput`**
- scbusblockinfoDetailsBeginDate
- scbusblockinfoDetailsEndDate
- scbusblockinfoDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query simpleReportsBookingBlocks($input: SimpleReportsBookingBlocksQueryArgumentsType!) {
  simpleReportsBookingBlocks(input: $input) @stream {
    salesEventBusinessBlockInformationDetails {
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