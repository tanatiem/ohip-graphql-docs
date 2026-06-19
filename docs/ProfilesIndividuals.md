# ProfilesIndividuals
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `profilesIndividuals`
> Guest profile data including contact information VIP codes memberships and stay statistics with room and revenue details.
  
**Return:** [`[ProfilesIndividualsType]`](#profilesindividualstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesIndividualsQueryArgumentsType!`](#profilesindividualsqueryargumentstype) |  |

## Object Types

### ProfilesIndividualsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | profileAllInformationDetails | [`ProfilesIndividualsProfileAllInformationDetailsType`](#profilesindividualsprofileallinformationdetailstype) | Profile All Details |
| 2 | profileAddressDetails | [`ProfilesIndividualsProfileAddressDetailsType`](#profilesindividualsprofileaddressdetailstype) | Profile Address Details |
| 3 | profileCommunicationDetails | [`ProfilesIndividualsProfileCommunicationDetailsType`](#profilesindividualsprofilecommunicationdetailstype) | Profile Communication Details |
| 4 | profilePreferenceDetails | [`ProfilesIndividualsProfilePreferenceDetailsType`](#profilesindividualsprofilepreferencedetailstype) | Profile Preference Details |
| 5 | profileDocumentsDetails | [`ProfilesIndividualsProfileDocumentsDetailsType`](#profilesindividualsprofiledocumentsdetailstype) | Profile Documents Details |
| 6 | profileMembershipDetails | [`ProfilesIndividualsProfileMembershipDetailsType`](#profilesindividualsprofilemembershipdetailstype) | Profile Membership Details |
| 7 | profileNoteDetails | [`ProfilesIndividualsProfileNoteDetailsType`](#profilesindividualsprofilenotedetailstype) | Profile Note Details |
| 8 | profileRelationshipDetails | [`ProfilesIndividualsProfileRelationshipDetailsType`](#profilesindividualsprofilerelationshipdetailstype) | Profile Relationship Details |
| 9 | individualDailyStatisticsDetails | [`ProfilesIndividualsIndividualDailyStatisticsDetailsType`](#profilesindividualsindividualdailystatisticsdetailstype) | Individual Daily Statistics |
| 10 | profileKeywordsDetails | [`ProfilesIndividualsProfileKeywordsDetailsType`](#profilesindividualsprofilekeywordsdetailstype) | Profile Keywords |
| 11 | profileSubscriptionDetails | [`ProfilesIndividualsProfileSubscriptionDetailsType`](#profilesindividualsprofilesubscriptiondetailstype) | Profile Subscription Details |
| 12 | profilesIndividualsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileAllInformationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | guestProfileID | `Float` | The primary key for this table. |
| 2 | aRNumber | `String` | Account number. |
| 3 | aRNumberCentral | `String` | Account Receivable No. of this profile. |
| 4 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 5 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 6 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 7 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 8 | accountBillingContact | `String` | Billing contact person in company. |
| 9 | accountSource | `String` | Used in S&C Module. |
| 10 | accountType | `String` | Account Type of this Profile |
| 11 | accountTypeDescription | `String` | The description of this value. |
| 12 | accountsourceDesc | `String` | The description of this value. |
| 13 | actionCode | `String` | Mailing action codes. |
| 14 | activeYN | `String` | Profile is active or not. |
| 15 | address1 | `String` | The first line of street address. |
| 16 | address2 | `String` | The second line of street address. |
| 17 | address3 | `String` | The third line of street address. |
| 18 | address4 | `String` | The fourth line of street address. |
| 19 | addressId | `Float` | The primary key for this table. |
| 20 | addressLangCodeDesc | `String` | Description for each language code. |
| 21 | addressLanguageCode | `String` | Address Language Code |
| 22 | addressType | `String` | The type of address. |
| 23 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 24 | allResorts | `String` | All Resorts |
| 25 | alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
| 26 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 27 | alternateLanguageDescription | `String` | Description for each language code. |
| 28 | alternateSalutation | `String` | Alternate Salutation |
| 29 | autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| 30 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 31 | billingCode | `String` | The billing code for this name record. |
| 32 | billingInstruction | `String` | Billing Instruction |
| 33 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 34 | birthCountry | `String` | Country of Birth |
| 35 | birthDate | `Date` | Date of Birth of the Individual Profiles. |
| 36 | birthDateStr | `String` | Stores the encrypted birth date. |
| 37 | birthPlace | `String` | Place of Birth |
| 38 | blMsg | `String` | Any Message for the Restricted profile. |
| 39 | businessSegment | `String` | Used in S&C Module. |
| 40 | businessSegmentDescription | `String` | The description of this value. |
| 41 | businessTitle | `String` | The business title for this individual. |
| 42 | cExchangeDate | `Date` | Central Xchange Date |
| 43 | cExchangeRate | `Float` | Central Xchange Rate |
| 44 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 45 | cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| 46 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 47 | centralAccountType | `String` | Central Account Type |
| 48 | centralBusinessSegment | `String` | Central Business Segment |
| 49 | centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| 50 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 51 | centralDefaultKeyword | `String` | The keyword to search on. |
| 52 | centralGuestTitleCode | `String` | Central Guest Title Code |
| 53 | centralInactiveReason | `String` | Central Inactive Reason |
| 54 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 55 | centralMailActionDescription | `String` | Central Mail Action Description |
| 56 | centralMailingActionCode | `String` | Central Mailing Action Code |
| 57 | centralPriority | `String` | Central Priority |
| 58 | centralStateCode | `String` | Central State Code |
| 59 | centralTerritory | `String` | Central Territory |
| 60 | centralVIPCode | `String` | Central VIP Code |
| 61 | centralVIPDescription | `String` | Central VIP Description |
| 62 | chainCode | `String` | Chain Code |
| 63 | city | `String` | The city for this address. |
| 64 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 65 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 66 | combinedName | `String` | Combined Name |
| 67 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 68 | comments | `String` | Not Used. |
| 69 | commissionCode | `String` | Commission Code for the Commission Percentage. |
| 70 | commissionCodes | `String` | Code for the commission for Travel Agent |
| 71 | commissionCurrencyId | `String` | Comm Curr ID |
| 72 | commissionid | `String` | Commission Code for the Commission Percentage. |
| 73 | communicationRole1 | `String` | Role in which this phone type belongs to. |
| 74 | communicationRole2 | `String` | Role in which this phone type belongs to. |
| 75 | communicationRole3 | `String` | Role in which this phone type belongs to. |
| 76 | communicationType1 | `String` | The type of this phone number. |
| 77 | communicationType2 | `String` | The type of this phone number. |
| 78 | communicationType3 | `String` | The type of this phone number. |
| 79 | communicationValue1 | `String` | The phone number for this record |
| 80 | communicationValue2 | `String` | The phone number for this record |
| 81 | communicationValue3 | `String` | The phone number for this record |
| 82 | companyAlternate | `String` | Extended Byte Company Name |
| 83 | companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| 84 | companyNameId | `Float` | Not used. |
| 85 | competition | `String` | Competaion code . |
| 86 | competitionDesc | `String` | The description of this value. |
| 87 | contactYN | `String` | Used in S&C Module. |
| 88 | contractNo | `String` | Group Contract number. |
| 89 | contractRecvDate | `Date` | The date the group contract was received. |
| 90 | corpTypeDesc | `String` | Corp Type Description |
| 91 | corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 92 | country | `String` | Country name. |
| 93 | countryCode | `String` | Country . |
| 94 | createdByUser | `String` | The user that created the record |
| 95 | createdOnDate | `DateTime` | The date the record was created |
| 96 | creditRating | `String` | Credit rating. |
| 97 | currencyCode | `String` | Currency Code |
| 98 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 99 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 100 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 101 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 102 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 103 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 104 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 105 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 106 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 107 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 108 | debtorName | `String` | Debtor Name |
| 109 | decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| 110 | defaultKeyword | `String` | The keyword to search on. |
| 111 | deletedFlag | `String` | Deleted Flag |
| 112 | department | `String` | Used in S&C Module. |
| 113 | deptId | `String` | Used in S&C Module. |
| 114 | description | `String` | Used in QMS Module |
| 115 | directBillBatchType | `String` | Direct Bill Batch Type |
| 116 | displayName | `String` | Display Name |
| 117 | downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| 118 | downloadResort | `String` | REsort name which has downloaded on the laptop. |
| 119 | downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| 120 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 121 | eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| 122 | email | `String` | The phone number for this record |
| 123 | emailYN | `String` | Email YN |
| 124 | envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| 125 | externalDisplayName | `String` | External Display Name |
| 126 | externalFirstName | `String` | The first name of an individual. |
| 127 | externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| 128 | externalName | `String` | The last name of the individual profile. |
| 129 | externalReferenceRequ | `String` | Not Used. |
| 130 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 131 | fMembershipCardNumbers | `String` | Membership Card Number. |
| 132 | fMembershipClassDesc | `String` | Descripion of membership class |
| 133 | fMembershipClasses | `String` | F Membership Classes |
| 134 | fMembershipCodes | `String` | F Membership Codes |
| 135 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 136 | fMembershipIds | `String` | Primary Key for this table. |
| 137 | fMembershipType | `String` | Type of the Membership. |
| 138 | fSubscriptionDb | `String` | The ID of the external Database. |
| 139 | fSubscriptionYn | `String` | The ID of the external Database. |
| 140 | faxNumber | `String` | The phone number for this record |
| 141 | firstName | `String` | The first name of an individual name. |
| 142 | firstNameAlternate | `String` | First Name Alternate |
| 143 | firstNameIncognito | `String` | The keyword to search on. |
| 144 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 145 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 146 | gDSTransactionNo | `String` | Not used. |
| 147 | gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| 148 | geographicRegion | `String` | Not used. |
| 149 | guestClassification | `String` | Not used. |
| 150 | guestCountry | `String` | Country name. |
| 151 | guestCurrencyCode | `String` | Currency code for the Commission payment. |
| 152 | guestLanguageCode | `String` | Description for each language code. |
| 153 | guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 154 | guestMiddleName | `String` | The middle name of this individual. |
| 155 | guestNameSuffix | `String` | Guest Name Suffix |
| 156 | guestPrivilegeYN | `String` | Guest Privilege YN |
| 157 | guestTitleCode | `String` | The title of the individual. |
| 158 | hasRequestedMailYN | `String` | Has Requested Mail YN |
| 159 | historyYN | `String` | Keep guest in history Y/N |
| 160 | holdCode | `String` | Hold code for the Commission handling purposes. |
| 161 | iataConsortia | `String` | Consortia for the IATA number. |
| 162 | idCountry | `String` | The country where ID was issued |
| 163 | idDate | `Date` | Issued date of Identification |
| 164 | idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| 165 | idPlace | `String` | The place where ID was issued |
| 166 | idType | `String` | Identification Type. Eg Passport Driving License etc |
| 167 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 168 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 169 | inactiveFlag | `String` | Inactive Flag |
| 170 | inactiveReason | `String` | Reason why record was inactivated. |
| 171 | inactiveReasonDescription | `String` | The description of this value. |
| 172 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 173 | indexName | `String` | Index Name |
| 174 | industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| 175 | industryDesc | `String` | The description of this value. |
| 176 | influence | `String` | Used in S&C Module. |
| 177 | influenceDesc | `String` | The description of this value. |
| 178 | interest | `String` | Interest Code. |
| 179 | internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| 180 | internalDeletedflag | `String` | Deleted Flag |
| 181 | internalInactiveflag | `String` | Inactive Flag |
| 182 | internalOrganizationId | `Float` | Organization ID |
| 183 | jRNUpdateDate | `Date` | JRN Update Date |
| 184 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 185 | languageCode | `String` | Primary language used for the profile. |
| 186 | laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| 187 | lastGroup | `String` | Last Group |
| 188 | lastNameAlternate | `String` | Last Name Alternate |
| 189 | lastNameIncognito | `String` | The keyword to search on. |
| 190 | lastRate | `Float` | Last Rate |
| 191 | lastRateCode | `String` | Last Rate Code |
| 192 | lastRoom | `String` | The room that is booked for this reservation leg. |
| 193 | lastRoomProperty | `String` | Last Room Property |
| 194 | lastSource | `String` | Last Source |
| 195 | lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| 196 | lastUpdatedResort | `String` | Last property that updated this record. |
| 197 | legalCompany | `String` | The legal company name for this company. |
| 198 | letterGreeting | `String` | Used in S&C Module. |
| 199 | mailActionDescription | `String` | The description of this value. |
| 200 | mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| 201 | mailType | `String` | The type of mail this user should be sent. |
| 202 | mailingActionCode | `String` | Mailing action codes. |
| 203 | marketResearchYN | `String` | Market Research YN |
| 204 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 205 | nameTaxType | `String` | Not used. |
| 206 | nameType | `String` | The type of Profile. |
| 207 | nameTypeDescription | `String` | The description of this value. |
| 208 | name2 | `String` | Not Used. |
| 209 | name3 | `String` | Not used. |
| 210 | nationality | `String` | Nationality |
| 211 | nationalityCode | `String` | Nationality of the individual. |
| 212 | negotiatedRateCodes | `String` | The rate code for which this record applies. |
| 213 | nextStay | `Date` | This is a begin_date  with no  time component. |
| 214 | nickname | `String` | The nickname of this individual. |
| 215 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 216 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 217 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 218 | phone | `String` | The phone number for this record |
| 219 | phoneWeb | `String` | The phone number for this record |
| 220 | phoneYN | `String` | Phone YN |
| 221 | postalCode | `String` | The postal code of this address. |
| 222 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 223 | preferredRoomNo | `String` | Preferred Room Number |
| 224 | primaryAddressId | `Float` | Not used. |
| 225 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 226 | primaryNameId | `Float` | Not Used. |
| 227 | primaryOwner | `String` | Primary Owner |
| 228 | primaryOwnerCode | `String` | Primary Owner Code |
| 229 | primaryPhoneId | `Float` | Not used. |
| 230 | priority | `String` | Priority of the account |
| 231 | priorityDesc | `String` | The description of this value. |
| 232 | privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 233 | productInterest | `String` | Preference Code. Part of the Primary Key. |
| 234 | profession | `String` | The profession of the Individual |
| 235 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 236 | profileId | `Float` | The primary key for this table. |
| 237 | profileType | `String` | The type of Profile. |
| 238 | propertyRegistered | `String` | Resort for which Job is registered. |
| 239 | protected | `String` | Protected |
| 240 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 241 | rateStructure | `String` | The default rate structure for this name. |
| 242 | region | `String` | The region for this name. |
| 243 | regionid | `String` | The region for this name. |
| 244 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 245 | repAccountsource | `String` | Reporting Accountsource |
| 246 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 247 | repCompetitionCode | `String` | Reporting Competition Code |
| 248 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 249 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 250 | repIndustryCode | `String` | Reporting Industry Code |
| 251 | repIndustryDescription | `String` | Reporting Industry Desc |
| 252 | repInfluence | `String` | Reporting Influence |
| 253 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 254 | repNameType | `String` | Reporting Name Type |
| 255 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 256 | repNationalityCode | `String` | Rep Nationality Code |
| 257 | repNationalityDescription | `String` | Rep Nationality Description |
| 258 | repPriorityDescription | `String` | Reporting Priority Desc |
| 259 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 260 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 261 | repScope | `String` | Reporting Scope |
| 262 | repScopeCity | `String` | Reporting Scope City |
| 263 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 264 | repScopeDescription | `String` | Reporting Scope Desc |
| 265 | repStateDescription | `String` | Reporting State Desc |
| 266 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 267 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 268 | repTitleName | `String` | Reporting Title Name |
| 269 | repeatGuestId | `String` | The primary membership # for this guest. |
| 270 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 271 | requestType | `String` | This column store the Name of the Company Profiles. |
| 272 | restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| 273 | restrictedRule | `String` | The description of this value. |
| 274 | resvContact | `String` | Reservation Contact person. |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomsPotential | `String` | Potential no of rooms per year for a account |
| 278 | roomsPotentialDesc | `String` | The description of this value. |
| 279 | sMSYN | `String` | Use this alert to text a notification. |
| 280 | salutation | `String` | Salutation Greeting |
| 281 | scope | `String` | Scope of the account |
| 282 | scopeCity | `String` | Scope City |
| 283 | scopeCityDesc | `String` | The description of this value. |
| 284 | scopeDesc | `String` | The description of this value. |
| 285 | searchName | `String` | The Uppercase value of Last or Company. |
| 286 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 287 | sfirst | `String` | Uppercase value of First Name. |
| 288 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 289 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 290 | srepCode | `String` | Used in QMS Module |
| 291 | state | `String` | The state of this address. |
| 292 | stateCode | `String` | State Code |
| 293 | stateDescription | `String` | Description of the state. |
| 294 | summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| 295 | summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| 296 | superSearchIndexText | `String` | Used in Oracle Text Index. |
| 297 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 298 | taxCategory | `String` | Tax Category |
| 299 | taxExemptStatus | `String` | Not used. |
| 300 | taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| 301 | taxID2 | `String` | Tax No |
| 302 | taxOffice | `String` | Tax Office Name |
| 303 | taxType | `String` | Tax Type |
| 304 | territory | `String` | TERRITORY of  a account |
| 305 | territoryDesc | `String` | The description of this value. |
| 306 | thirdPartyYN | `String` | Third Party YN |
| 307 | titleAlternate | `String` | Title Alternate |
| 308 | titleName | `String` | The description of this value. |
| 309 | titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| 310 | totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| 311 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 312 | traceCode | `String` | Code to Trace a record for all Triggered actions. |
| 313 | tracecodeDesc | `String` | Description |
| 314 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 315 | uDFC01 | `String` | User defined character field. |
| 316 | uDFC02 | `String` | User defined character field. |
| 317 | uDFC03 | `String` | User defined character field. |
| 318 | uDFC04 | `String` | User defined character field. |
| 319 | uDFC05 | `String` | User defined character field. |
| 320 | uDFC06 | `String` | User defined character field. |
| 321 | uDFC07 | `String` | User defined character field. |
| 322 | uDFC08 | `String` | User defined character field. |
| 323 | uDFC09 | `String` | User defined character field. |
| 324 | uDFC10 | `String` | User defined character field. |
| 325 | uDFC11 | `String` | User defined character field. |
| 326 | uDFC12 | `String` | User defined character field. |
| 327 | uDFC13 | `String` | User defined character field. |
| 328 | uDFC14 | `String` | User defined character field. |
| 329 | uDFC15 | `String` | User defined character field. |
| 330 | uDFC16 | `String` | User defined character field. |
| 331 | uDFC17 | `String` | User defined character field. |
| 332 | uDFC18 | `String` | User defined character field. |
| 333 | uDFC19 | `String` | User defined character field. |
| 334 | uDFC20 | `String` | User defined character field. |
| 335 | uDFC21 | `String` | User defined character field. |
| 336 | uDFC22 | `String` | User defined character field. |
| 337 | uDFC23 | `String` | User defined character field. |
| 338 | uDFC24 | `String` | User defined character field. |
| 339 | uDFC25 | `String` | User defined character field. |
| 340 | uDFC26 | `String` | User defined character field. |
| 341 | uDFC27 | `String` | User defined character field. |
| 342 | uDFC28 | `String` | User defined character field. |
| 343 | uDFC29 | `String` | User defined character field. |
| 344 | uDFC30 | `String` | User defined character field. |
| 345 | uDFC31 | `String` | User defined character field. |
| 346 | uDFC32 | `String` | User defined character field. |
| 347 | uDFC33 | `String` | User defined character field. |
| 348 | uDFC34 | `String` | User defined character field. |
| 349 | uDFC35 | `String` | User defined character field. |
| 350 | uDFC36 | `String` | User defined character field. |
| 351 | uDFC37 | `String` | User defined character field. |
| 352 | uDFC38 | `String` | User defined character field. |
| 353 | uDFC39 | `String` | User defined character field. |
| 354 | uDFC40 | `String` | User defined character field. |
| 355 | uDFD01 | `Date` | User defined date field. |
| 356 | uDFD02 | `Date` | User defined date field. |
| 357 | uDFD03 | `Date` | User defined date field. |
| 358 | uDFD04 | `Date` | User defined date field. |
| 359 | uDFD05 | `Date` | User defined date field. |
| 360 | uDFD06 | `Date` | User defined date field. |
| 361 | uDFD07 | `Date` | User defined date field. |
| 362 | uDFD08 | `Date` | User defined date field. |
| 363 | uDFD09 | `Date` | User defined date field. |
| 364 | uDFD10 | `Date` | User defined date field. |
| 365 | uDFD11 | `Date` | User defined date field. |
| 366 | uDFD12 | `Date` | User defined date field. |
| 367 | uDFD13 | `Date` | User defined date field. |
| 368 | uDFD14 | `Date` | User defined date field. |
| 369 | uDFD15 | `Date` | User defined date field. |
| 370 | uDFD16 | `Date` | User defined date field. |
| 371 | uDFD17 | `Date` | User defined date field. |
| 372 | uDFD18 | `Date` | User defined date field. |
| 373 | uDFD19 | `Date` | User defined date field. |
| 374 | uDFD20 | `Date` | User defined date field. |
| 375 | uDFN01 | `Float` | User defined number field. |
| 376 | uDFN02 | `Float` | User defined number field. |
| 377 | uDFN03 | `Float` | User defined number field. |
| 378 | uDFN04 | `Float` | User defined number field. |
| 379 | uDFN05 | `Float` | User defined number field. |
| 380 | uDFN06 | `Float` | User defined number field. |
| 381 | uDFN07 | `Float` | User defined number field. |
| 382 | uDFN08 | `Float` | User defined number field. |
| 383 | uDFN09 | `Float` | User defined number field. |
| 384 | uDFN10 | `Float` | User defined number field. |
| 385 | uDFN11 | `Float` | User defined number field. |
| 386 | uDFN12 | `Float` | User defined number field. |
| 387 | uDFN13 | `Float` | User defined number field. |
| 388 | uDFN14 | `Float` | User defined number field. |
| 389 | uDFN15 | `Float` | User defined number field. |
| 390 | uDFN16 | `Float` | User defined number field. |
| 391 | uDFN17 | `Float` | User defined number field. |
| 392 | uDFN18 | `Float` | User defined number field. |
| 393 | uDFN19 | `Float` | User defined number field. |
| 394 | uDFN20 | `Float` | User defined number field. |
| 395 | uDFN21 | `Float` | User defined number field. |
| 396 | uDFN22 | `Float` | User defined number field. |
| 397 | uDFN23 | `Float` | User defined number field. |
| 398 | uDFN24 | `Float` | User defined number field. |
| 399 | uDFN25 | `Float` | User defined number field. |
| 400 | uDFN26 | `Float` | User defined number field. |
| 401 | uDFN27 | `Float` | User defined number field. |
| 402 | uDFN28 | `Float` | User defined number field. |
| 403 | uDFN29 | `Float` | User defined number field. |
| 404 | uDFN30 | `Float` | User defined number field. |
| 405 | uDFN31 | `Float` | User defined number field. |
| 406 | uDFN32 | `Float` | User defined number field. |
| 407 | uDFN33 | `Float` | User defined number field. |
| 408 | uDFN34 | `Float` | User defined number field. |
| 409 | uDFN35 | `Float` | User defined number field. |
| 410 | uDFN36 | `Float` | User defined number field. |
| 411 | uDFN37 | `Float` | User defined number field. |
| 412 | uDFN38 | `Float` | User defined number field. |
| 413 | uDFN39 | `Float` | User defined number field. |
| 414 | uDFN40 | `Float` | User defined number field. |
| 415 | updateDate | `DateTime` | The date the record was modified |
| 416 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 417 | updateUser | `String` | The user that modified the record |
| 418 | uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| 419 | vIPCode | `String` | VIP Status of the Individual. |
| 420 | vIPDescription | `String` | The description of this value. |
| 421 | vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| 422 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 423 | vipAuthorization | `String` | Not Used. |
| 424 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 425 | xdisplayName | `String` | Xdisplay Name |
| 426 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileAddressDetailsType

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

### ProfilesIndividualsProfileCommunicationDetailsType

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

### ProfilesIndividualsProfilePreferenceDetailsType

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

### ProfilesIndividualsProfileDocumentsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | documentId | `Float` | Unique ID for this table. |
| 5 | guestIdentificationIDIssuePlace | `String` | The place where the ID was issued. |
| 6 | idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| 7 | identificationIDCountry | `String` | The country where the ID was issued |
| 8 | identificationIDExpirationDate | `Date` | Expiration date of the ID document. |
| 9 | identificationIDIssueDate | `Date` | Identification Issued date. |
| 10 | identificationIDNumber | `String` | Encrypted identification number. |
| 11 | identificationIDPrimaryYN | `String` | Indicates if this record is the primary one for the ID type. |
| 12 | identificationIDType | `String` | Identification type e.g: PASSPORT DRIVING LICENSE etc. |
| 13 | inactiveDate | `DateTime` | Date this record was inactivated. |
| 14 | insertDate | `DateTime` | The date the record was created. |
| 15 | insertUser | `Float` | The user that created the record. |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | locationID | `String` | The property this record belongs to can be "_GLOBAL". |
| 19 | nameId | `Float` | The profile ID reference who owns this document. |
| 20 | orderBy | `Float` | Display Sequence. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | The property this record belongs to can be "_GLOBAL". |
| 24 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 25 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 26 | sIdNumber | `String` | Internal indexed field to search for ID_NUMBER. |
| 27 | updateDate | `DateTime` | The date the record was modified. |
| 28 | updateUser | `Float` | The user that modified the record. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileMembershipDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cCreditLimit | `Float` | Central Credit Limit |
| 2 | cExchangeDate | `Date` | Central Xchange Date |
| 3 | cExchangeRate | `Float` | Central Xchange Rate |
| 4 | chainCode | `String` | Chain code. |
| 5 | comments | `String` | Used by EIS Module. |
| 6 | creditLimit | `Float` | Used in the EIS Module. |
| 7 | currentPoints | `Float` | Used in the EIS Module. |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | deviceCode | `String` | Encoded string on the device. |
| 11 | deviceDisableDate | `Date` | Date when device was disabled. |
| 12 | earningPreference | `String` | Points or miles earning preference. |
| 13 | enrollmentCode | `String` | Code to indicate source used to enroll the member. |
| 14 | enrollmentProperty | `String` | Resort/CRO where enrollment is done. |
| 15 | enrollmentSource | `String` | Source from where the enrollment is done. |
| 16 | excludeFromBatch | `String` | Flag to determine member actions to include in the fulfillment extract |
| 17 | expirationDate | `Date` | Expiration date of the Card. |
| 18 | gracePeriodIndicator | `String` | Grace Period Indicator |
| 19 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 20 | insertDate | `DateTime` | The date the record was created |
| 21 | insertUser | `String` | The unique name of application user |
| 22 | internalMembershipid | `Float` | Primary Key for this table. |
| 23 | jRNUpdateDate | `Date` | JRN Update Date |
| 24 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 25 | joinedDate | `Date` | Used by EIS Module. |
| 26 | mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| 27 | memberIndicator | `String` | Used in the EIS Module. |
| 28 | memberSubtype | `String` | Used in the EIS Module. |
| 29 | membergueststatusid | `String` | Membergueststatusid |
| 30 | membershipActiveYN | `String` | Membership Active YN |
| 31 | membershipClass | `String` | Primary key of this table |
| 32 | membershipID | `Float` | Primary Key for this table. |
| 33 | membershipLevel | `String` | Level of this Membership Type. |
| 34 | membershipLevelDescription | `String` | Membership Level Description |
| 35 | membershipNumber | `String` | Membership Card Number. |
| 36 | membershipStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| 37 | membershipType | `String` | Type of the Membership. |
| 38 | membershipTypeDescription | `String` | Description of membership program type. |
| 39 | membershipenrollid | `String` | Membershipenrollid |
| 40 | membershiplevelid | `String` | Level of this Membership Type. |
| 41 | membershiptypeid | `String` | Type of the Membership. |
| 42 | nameId | `Float` | Reference to the name that owns this record. |
| 43 | nameOnCard | `String` | Name as appeared on the Membership Card. |
| 44 | orderBy | `Float` | The display sequence of the membership cards held by this profile if there are multiple membership cards. |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | partnerMembershipId | `Float` | Membership ID that accrues Miles. |
| 47 | pointflag | `String` | Used in the EIS Module. |
| 48 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 49 | primaryMembershipYN | `String` | Primary Membership YN |
| 50 | primaryairlineflag | `String` | Used in the EIS Module. |
| 51 | processExpirationDate | `Date` | Used in the EIS Module. |
| 52 | profileid | `Float` | Reference to the name that owns this record. |
| 53 | ranking | `Float` | Current membership ranking value for this profile possible values: 1-10. |
| 54 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 55 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 56 | trackData | `String` | Stores key track information for a universal card that may be different than the membership number. |
| 57 | updateDate | `DateTime` | The date the record was modified |
| 58 | updateUser | `String` | The unique name of application user |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileNoteDetailsType

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

### ProfilesIndividualsProfileRelationshipDetailsType

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

### ProfilesIndividualsIndividualDailyStatisticsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cExchangeDate | `Date` | Central Xchange Date |
| 2 | cExchangeRate | `Float` | Central Xchange Rate |
| 3 | cFBRevenue | `Float` | Central Fb Revenue |
| 4 | cFBRevenueTax | `Float` | Central Fb Revenue Tax |
| 5 | cGroupFBRevenue | `Float` | Central Grp Fb Revenue |
| 6 | cGroupFBRevenueTax | `Float` | Central Grp Fb Revenue Tax |
| 7 | cGroupOtherRevenue | `Float` | Central Grp Other Revenue |
| 8 | cGroupOtherRevenueTax | `Float` | Central Grp Other Revenue Tax |
| 9 | cGroupRoomRevenue | `Float` | Central Grp Room Revenue |
| 10 | cGroupRoomRevenueTax | `Float` | Central Grp Room Revenue Tax |
| 11 | cGroupTotalRevenue | `Float` | Central Grp Total Revenue |
| 12 | cGroupTotalRevenueTax | `Float` | Central Grp Total Revenue Tax |
| 13 | cOtherRevenue | `Float` | Central Other Revenue |
| 14 | cOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 15 | cRoomRevenue | `Float` | Central Room Revenue |
| 16 | cRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 17 | cTotalFBRevenueTax | `Float` | Central Total Fb Revenue Tax |
| 18 | cTotalOtherRevenueTax | `Float` | Central Total Other Revenue Tax |
| 19 | cTotalRevenue | `Float` | Central Total Revenue |
| 20 | cTotalRevenueTax | `Float` | Central Total Revenue Tax |
| 21 | cTotalRoomRevenueTax | `Float` | Central Total Room Revenue Tax |
| 22 | cTotalTotalRevenueTax | `Float` | Central Total Total Revenue Tax |
| 23 | cancels | `Float` | Cancels |
| 24 | centralFBRevenue | `Float` | Central FB Revenue |
| 25 | centralOtherRevenue | `Float` | Central Other Revenue |
| 26 | centralRoomRevenue | `Float` | Central Room Revenue |
| 27 | centralTotalRevenue | `Float` | Central Total Revenue |
| 28 | contextCd | `String` | Context Cd |
| 29 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 30 | deletedFlag | `String` | Deleted Flag |
| 31 | fBRevenue | `Float` | FB Revenue |
| 32 | fbRevenue | `Float` | FB Revenue |
| 33 | fbRevenueTax | `Float` | F&B Revenue Tax. |
| 34 | grpFBRevenue | `Float` | Group F&B Revenue. |
| 35 | grpFBRevenueTax | `Float` | Group F&B Revenue Tax. |
| 36 | grpNumberCancels | `Float` | Group Number of Cancellations. |
| 37 | grpNumberNights | `Float` | Group Number of Nights. |
| 38 | grpNumberNumberShows | `Float` | Group Number of No Shows. |
| 39 | grpNumberStays | `Float` | Group Number of Stays. |
| 40 | grpOtherRevenue | `Float` | Group Other Revenue. |
| 41 | grpOtherRevenueTax | `Float` | Group Other Revenue Tax. |
| 42 | grpRoomRevenue | `Float` | Group Room Revenue. |
| 43 | grpRoomRevenueTax | `Float` | Group Room Revenue Tax. |
| 44 | grpTotalRevenue | `Float` | Group Total Revenue. |
| 45 | grpTotalRevenueTax | `Float` | Group Total Revenue Tax. |
| 46 | jRNUpdateDate | `Date` | JRN Update Date |
| 47 | jrnFilerba | `Float` | Journal Filerba |
| 48 | jrnFileseqno | `Float` | Journal Fileseqno |
| 49 | jrnFlag | `String` | Journal Flag |
| 50 | jrnScn | `Float` | Journal Scn |
| 51 | jrnSlicingTs | `DateTime` | Journal Slicing Ts |
| 52 | jrnUpdateDttm | `DateTime` | Journal Update Dttm |
| 53 | locationID | `String` | The property that the record belongs to |
| 54 | nameId | `Float` | The system-generated Internal numeric ID that corresponds to the Travel Agent for which the current record applies. Part of Primary Key. |
| 55 | nameType | `String` | Name Type |
| 56 | noShows | `Float` | Number Shows |
| 57 | numberCancels | `Float` | Number Cancels |
| 58 | numberNights | `Float` | Number Nights |
| 59 | numberNoShows | `Float` | Number Number Shows |
| 60 | numberStays | `Float` | Number Stays |
| 61 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 62 | otherRevenue | `Float` | Other Revenue |
| 63 | otherRevenueTax | `Float` | Other Revenue Tax |
| 64 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 65 | property | `String` | The property that the record belongs to |
| 66 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 67 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 68 | roomNights | `Float` | Room Nights |
| 69 | roomRevenue | `Float` | Room Revenue |
| 70 | roomRevenueTax | `Float` | Room Revenue Tax |
| 71 | stayDate | `Date` | The Business Date for which the current record applies. Part of Primary Key. |
| 72 | stayMonth | `Float` | Month of Summary. Stores Year and Month as YYYYMM. |
| 73 | stayYear | `Float` | Year of Summary. |
| 74 | stays | `Float` | Stays |
| 75 | totalFbRevenueTax | `Float` | Total FB Revenue Tax |
| 76 | totalOtherRevenue | `Float` | Total of All Revenue for the current record's key value that does not fall under Room/Food/Beverage category. |
| 77 | totalOtherRevenueTax | `Float` | Total Other Revenue Tax |
| 78 | totalRevenue | `Float` | Total Revenue Amount for the current record's key value. |
| 79 | totalRevenueTax | `Float` | Total Revenue Tax |
| 80 | totalRoomRevenue | `Float` | Total Room Revenue Amount for the current record's key value. |
| 81 | totalRoomRevenueTax | `Float` | Total Room Amount (Inc Packages and Taxes) for the Stay. |
| 82 | totalTotalRevenue | `Float` | Total Total Revenue |
| 83 | totalTotalRevenueTax | `Float` | Total Total Revenue Tax |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileKeywordsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralKeywordType | `String` | Central Keyword Type |
| 2 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | interfaceUpdatedYn | `String` | Interface  update status |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | keyword | `String` | The keyword to search on. |
| 9 | keywordSoundex | `String` | The soundex of this keyword. |
| 10 | keywordType | `String` | Derived value based on the Type of the profile for the Search purpose. |
| 11 | laptopChange | `Float` | Code to synchronize with Laptop. |
| 12 | nameId | `Float` | The name these keywords are derived from. |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 16 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 17 | updateAllowedYn | `String` | Update allowed status. |

[⬆ Back to Query](#query)

---

### ProfilesIndividualsProfileSubscriptionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowDuplicateYn | `String` | Allow Duplicate Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| 6 | extDBNameID | `String` | Ext DB Name ID |
| 7 | externalDatabaseName | `String` | External Database Name |
| 8 | externalProfileId | `String` | External Profile ID |
| 9 | forceYn | `String` | Indicates if profile distribution should be forced. |
| 10 | inactiveDate | `Date` | Inactive Date |
| 11 | inactiveFlag | `String` | Inactive Flag |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | internalOrganizationId | `Float` | Organization ID |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | lastActivityDate | `Date` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| 18 | lastDistributeDate | `Date` | The data when profile was last distributed. |
| 19 | nameId | `Float` | Name ID |
| 20 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 21 | pendingAction | `Float` | Indicates action is pending for queque. It can take values 124 |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | profileId | `Float` | Profile ID |
| 24 | profilesubscriptionId | `Float` | Profilesubscription ID |
| 25 | queryCode | `String` | Query Code |
| 26 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 27 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 28 | updateDate | `DateTime` | Update Date |
| 29 | updateUser | `Float` | Update User |

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

### ProfilesIndividualsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| profileallDetailsNameId | `FloatInput` | The primary key for this table.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsIndexName | `StringInput` | Index Name<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsNameType | `StringInput` | The type of Profile. |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name.<br>`@conditionalInputPair(pair: 2)` |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified<br>`@conditionalInputPair(pair: 2)` |
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
| profiledocumentsDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profiledocumentsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profiledocumentsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profiledocumentsDetailsDocumentId | `FloatInput` | Unique ID for this table. |
| profiledocumentsDetailsIdPlace | `StringInput` | The place where the ID was issued. |
| profiledocumentsDetailsIdDocumentAttachId | `FloatInput` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| profiledocumentsDetailsIdCountry | `StringInput` | The country where the ID was issued |
| profiledocumentsDetailsIdExpirationDate | `DateInput` | Expiration date of the ID document. |
| profiledocumentsDetailsIdDate | `DateInput` | Identification Issued date. |
| profiledocumentsDetailsIdNumber | `StringInput` | Encrypted identification number. |
| profiledocumentsDetailsPrimaryYn | `StringInput` | Indicates if this record is the primary one for the ID type. |
| profiledocumentsDetailsIdType | `StringInput` | Identification type e.g: PASSPORT DRIVING LICENSE etc. |
| profiledocumentsDetailsInactiveDate | `DateTimeInput` | Date this record was inactivated. |
| profiledocumentsDetailsInsertDate | `DateTimeInput` | The date the record was created. |
| profiledocumentsDetailsInsertUser | `FloatInput` | The user that created the record. |
| profiledocumentsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profiledocumentsDetailsLocationid | `StringInput` | The property this record belongs to can be "_GLOBAL". |
| profiledocumentsDetailsNameId | `FloatInput` | The profile ID reference who owns this document. |
| profiledocumentsDetailsOrderBy | `FloatInput` | Display Sequence. |
| profiledocumentsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profiledocumentsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profiledocumentsDetailsResort | `StringInput` | The property this record belongs to can be "_GLOBAL". |
| profiledocumentsDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profiledocumentsDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profiledocumentsDetailsSIdNumber | `StringInput` | Internal indexed field to search for ID_NUMBER. |
| profiledocumentsDetailsUpdateDate | `DateTimeInput` | The date the record was modified. |
| profiledocumentsDetailsUpdateUser | `FloatInput` | The user that modified the record. |
| profilemembershipDetailsCCreditLimit | `FloatInput` | Central Credit Limit |
| profilemembershipDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| profilemembershipDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| profilemembershipDetailsChainCode | `StringInput` | Chain code. |
| profilemembershipDetailsComments | `StringInput` | Used by EIS Module. |
| profilemembershipDetailsCreditLimit | `FloatInput` | Used in the EIS Module. |
| profilemembershipDetailsCurrentPoints | `FloatInput` | Used in the EIS Module. |
| profilemembershipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilemembershipDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilemembershipDetailsDeviceCode | `StringInput` | Encoded string on the device. |
| profilemembershipDetailsDeviceDisableDate | `DateInput` | Date when device was disabled. |
| profilemembershipDetailsEarningPreference | `StringInput` | Points or miles earning preference. |
| profilemembershipDetailsEnrollmentCode | `StringInput` | Code to indicate source used to enroll the member. |
| profilemembershipDetailsEnrolledAt | `StringInput` | Resort/CRO where enrollment is done. |
| profilemembershipDetailsEnrollmentSource | `StringInput` | Source from where the enrollment is done. |
| profilemembershipDetailsExcludeFromBatch | `StringInput` | Flag to determine member actions to include in the fulfillment extract |
| profilemembershipDetailsExpirationDate | `DateInput` | Expiration date of the Card. |
| profilemembershipDetailsGracePeriodIndicator | `StringInput` | Grace Period Indicator |
| profilemembershipDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilemembershipDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilemembershipDetailsInsertUser | `StringInput` | The unique name of application user |
| profilemembershipDetailsMembershipid | `FloatInput` | Primary Key for this table. |
| profilemembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilemembershipDetailsJoinedDate | `DateInput` | Used by EIS Module. |
| profilemembershipDetailsMbrprefChangedDate | `DateInput` | Last Date Earning Preference was changed. |
| profilemembershipDetailsMemberIndicator | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsMemberSubtype | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsMembergueststatusid | `StringInput` | Membergueststatusid |
| profilemembershipDetailsInactiveflag | `StringInput` | Membership Active YN |
| profilemembershipDetailsMembershipClass | `StringInput` | Primary key of this table |
| profilemembershipDetailsMembershipId | `FloatInput` | Primary Key for this table. |
| profilemembershipDetailsMembershipLevel | `StringInput` | Level of this Membership Type. |
| profilemembershipDetailsMembershipLevelDesc | `StringInput` | Membership Level Description |
| profilemembershipDetailsMembershipCardNo | `StringInput` | Membership Card Number. |
| profilemembershipDetailsMembershipStatus | `StringInput` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| profilemembershipDetailsMembershipType | `StringInput` | Type of the Membership. |
| profilemembershipDetailsMembershipTypeDesc | `StringInput` | Description of membership program type. |
| profilemembershipDetailsMembershipenrollid | `StringInput` | Membershipenrollid |
| profilemembershipDetailsMembershiplevelid | `StringInput` | Level of this Membership Type. |
| profilemembershipDetailsMembershiptypeid | `StringInput` | Type of the Membership. |
| profilemembershipDetailsNameId | `FloatInput` | Reference to the name that owns this record. |
| profilemembershipDetailsNameOnCard | `StringInput` | Name as appeared on the Membership Card. |
| profilemembershipDetailsOrderBy | `FloatInput` | The display sequence of the membership cards held by this profile if there are multiple membership cards. |
| profilemembershipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilemembershipDetailsPartnerMembershipId | `FloatInput` | Membership ID that accrues Miles. |
| profilemembershipDetailsPointflag | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilemembershipDetailsPrimaryMembershipYn | `StringInput` | Primary Membership YN |
| profilemembershipDetailsPrimaryairlineflag | `StringInput` | Used in the EIS Module. |
| profilemembershipDetailsProcessExpirationDate | `DateInput` | Used in the EIS Module. |
| profilemembershipDetailsProfileid | `FloatInput` | Reference to the name that owns this record. |
| profilemembershipDetailsRankValue | `FloatInput` | Current membership ranking value for this profile possible values: 1-10. |
| profilemembershipDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilemembershipDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilemembershipDetailsTrackData | `StringInput` | Stores key track information for a universal card that may be different than the membership number. |
| profilemembershipDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilemembershipDetailsUpdateUser | `StringInput` | The unique name of application user |
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
| individualdailystatDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| individualdailystatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| individualdailystatDetailsJrnUpdateDttm | `DateTimeInput` | Journal Update Dttm |
| individualdailystatDetailsNameId | `FloatInput` | The system-generated Internal numeric ID that corresponds to the Travel Agent for which the current record applies. Part of Primary Key. |
| individualdailystatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| individualdailystatDetailsResort | `StringInput` | The property that the record belongs to |
| individualdailystatDetailsStayDate | `DateInput` | The Business Date for which the current record applies. Part of Primary Key. |
| namekeywordsDetailsRepKeywordType | `StringInput` | Central Keyword Type |
| namekeywordsDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| namekeywordsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| namekeywordsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| namekeywordsDetailsInterfaceUpdatedYn | `StringInput` | Interface  update status |
| namekeywordsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| namekeywordsDetailsKeyword | `StringInput` | The keyword to search on. |
| namekeywordsDetailsKeywordSoundex | `StringInput` | The soundex of this keyword. |
| namekeywordsDetailsKeywordType | `StringInput` | Derived value based on the Type of the profile for the Search purpose. |
| namekeywordsDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop. |
| namekeywordsDetailsNameId | `FloatInput` | The name these keywords are derived from. |
| namekeywordsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| namekeywordsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| namekeywordsDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| namekeywordsDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| namekeywordsDetailsUpdateAllowedYn | `StringInput` | Update allowed status. |
| profilesubscriptionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- profileallDetailsChainCode

**`conditionalInputPair(pair: 2)`**
- profileallDetailsNameId
- profileallDetailsActiveYn
- profileallDetailsCrsNameid
- profileallDetailsNameCode
- profileallDetailsCompanyGroupId
- profileallDetailsInactiveDate
- profileallDetailsIndexName
- profileallDetailsOrganizationId
- profileallDetailsJrnupdatedttm
- profileallDetailsProfileId
- profileallDetailsSname
- profileallDetailsSxname
- profileallDetailsSfirst
- profileallDetailsSrepCode
- profileallDetailsSxfirstName
- profileallDetailsUpdateDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesIndividuals($input: ProfilesIndividualsQueryArgumentsType!) {
  profilesIndividuals(input: $input) @stream {
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
    profileDocumentsDetails {
      chainCode
      dSI
      deletedFlag
      documentId
      guestIdentificationIDIssuePlace
      idDocumentAttachId
      identificationIDCountry
      identificationIDExpirationDate
      identificationIDIssueDate
      identificationIDNumber
      identificationIDPrimaryYN
      identificationIDType
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      nameId
      orderBy
      organizationID
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      sIdNumber
      updateDate
      updateUser
    }
    profileMembershipDetails {
      cCreditLimit
      cExchangeDate
      cExchangeRate
      chainCode
      comments
      creditLimit
      currentPoints
      dSI
      deletedFlag
      deviceCode
      deviceDisableDate
      earningPreference
      enrollmentCode
      enrollmentProperty
      enrollmentSource
      excludeFromBatch
      expirationDate
      gracePeriodIndicator
      inactiveDate
      insertDate
      insertUser
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      joinedDate
      mbrprefChangedDate
      memberIndicator
      memberSubtype
      membergueststatusid
      membershipActiveYN
      membershipClass
      membershipID
      membershipLevel
      membershipLevelDescription
      membershipNumber
      membershipStatus
      membershipType
      membershipTypeDescription
      membershipenrollid
      membershiplevelid
      membershiptypeid
      nameId
      nameOnCard
      orderBy
      organizationID
      partnerMembershipId
      pointflag
      primaryKeyID
      primaryMembershipYN
      primaryairlineflag
      processExpirationDate
      profileid
      ranking
      rnaInsertDate
      rnaUpdateDate
      trackData
      updateDate
      updateUser
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
    individualDailyStatisticsDetails {
      cExchangeDate
      cExchangeRate
      cFBRevenue
      cFBRevenueTax
      cGroupFBRevenue
      cGroupFBRevenueTax
      cGroupOtherRevenue
      cGroupOtherRevenueTax
      cGroupRoomRevenue
      cGroupRoomRevenueTax
      cGroupTotalRevenue
      cGroupTotalRevenueTax
      cOtherRevenue
      cOtherRevenueTax
      cRoomRevenue
      cRoomRevenueTax
      cTotalFBRevenueTax
      cTotalOtherRevenueTax
      cTotalRevenue
      cTotalRevenueTax
      cTotalRoomRevenueTax
      cTotalTotalRevenueTax
      cancels
      centralFBRevenue
      centralOtherRevenue
      centralRoomRevenue
      centralTotalRevenue
      contextCd
      dSI
      deletedFlag
      fBRevenue
      fbRevenue
      fbRevenueTax
      grpFBRevenue
      grpFBRevenueTax
      grpNumberCancels
      grpNumberNights
      grpNumberNumberShows
      grpNumberStays
      grpOtherRevenue
      grpOtherRevenueTax
      grpRoomRevenue
      grpRoomRevenueTax
      grpTotalRevenue
      grpTotalRevenueTax
      jRNUpdateDate
      jrnFilerba
      jrnFileseqno
      jrnFlag
      jrnScn
      jrnSlicingTs
      jrnUpdateDttm
      locationID
      nameId
      nameType
      noShows
      numberCancels
      numberNights
      numberNoShows
      numberStays
      organizationID
      otherRevenue
      otherRevenueTax
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomNights
      roomRevenue
      roomRevenueTax
      stayDate
      stayMonth
      stayYear
      stays
      totalFbRevenueTax
      totalOtherRevenue
      totalOtherRevenueTax
      totalRevenue
      totalRevenueTax
      totalRoomRevenue
      totalRoomRevenueTax
      totalTotalRevenue
      totalTotalRevenueTax
    }
    profileKeywordsDetails {
      centralKeywordType
      chainCode
      dSI
      deletedFlag
      interfaceUpdatedYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      keywordSoundex
      keywordType
      laptopChange
      nameId
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      updateAllowedYn
    }
    profileSubscriptionDetails {
      allowDuplicateYn
      chainCode
      dSI
      deletedFlag
      distributeYn
      extDBNameID
      externalDatabaseName
      externalProfileId
      forceYn
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastActivityDate
      lastDistributeDate
      nameId
      organizationID
      pendingAction
      primaryKeyID
      profileId
      profilesubscriptionId
      queryCode
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
profile_all_information_details_schema = {
    'guestProfileID': pl.Float64,
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountsourceDesc': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressId': pl.Float64,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allResorts': pl.Utf8,
    'alternateEnvelopeGreeting': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'autoEnrollMemberYN': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessSegmentDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralBusinessSegmentDescription': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralGuestTitleCode': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralMailingActionCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'comments': pl.Utf8,
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
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'competitionDesc': pl.Utf8,
    'contactYN': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corpTypeDesc': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
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
    'debtorName': pl.Utf8,
    'decimalPositions': pl.Float64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYN': pl.Utf8,
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
    'faxNumber': pl.Utf8,
    'firstName': pl.Utf8,
    'firstNameAlternate': pl.Utf8,
    'firstNameIncognito': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestCountry': pl.Utf8,
    'guestCurrencyCode': pl.Utf8,
    'guestLanguageCode': pl.Utf8,
    'guestLastName': pl.Utf8,
    'guestMiddleName': pl.Utf8,
    'guestNameSuffix': pl.Utf8,
    'guestPrivilegeYN': pl.Utf8,
    'guestTitleCode': pl.Utf8,
    'hasRequestedMailYN': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryDesc': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDesc': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastGroup': pl.Utf8,
    'lastNameAlternate': pl.Utf8,
    'lastNameIncognito': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRateCode': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastRoomProperty': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYN': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'priorityDesc': pl.Utf8,
    'privacyFlagYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'requestType': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'roomsPotentialDesc': pl.Utf8,
    'sMSYN': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDesc': pl.Utf8,
    'scopeDesc': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDescription': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDesc': pl.Utf8,
    'thirdPartyYN': pl.Utf8,
    'titleAlternate': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalStay': pl.Float64,
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
    'uploadDate': pl.Utf8,
    'vIPCode': pl.Utf8,
    'vIPDescription': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xdisplayName': pl.Utf8,
    'xmiddleName': pl.Utf8,
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
profile_documents_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'documentId': pl.Float64,
    'guestIdentificationIDIssuePlace': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'identificationIDCountry': pl.Utf8,
    'identificationIDExpirationDate': pl.Utf8,
    'identificationIDIssueDate': pl.Utf8,
    'identificationIDNumber': pl.Utf8,
    'identificationIDPrimaryYN': pl.Utf8,
    'identificationIDType': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sIdNumber': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_membership_details_schema = {
    'cCreditLimit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'creditLimit': pl.Float64,
    'currentPoints': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'deviceCode': pl.Utf8,
    'deviceDisableDate': pl.Utf8,
    'earningPreference': pl.Utf8,
    'enrollmentCode': pl.Utf8,
    'enrollmentProperty': pl.Utf8,
    'enrollmentSource': pl.Utf8,
    'excludeFromBatch': pl.Utf8,
    'expirationDate': pl.Utf8,
    'gracePeriodIndicator': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'joinedDate': pl.Utf8,
    'mbrprefChangedDate': pl.Utf8,
    'memberIndicator': pl.Utf8,
    'memberSubtype': pl.Utf8,
    'membergueststatusid': pl.Utf8,
    'membershipActiveYN': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipID': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipLevelDescription': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipStatus': pl.Utf8,
    'membershipType': pl.Utf8,
    'membershipTypeDescription': pl.Utf8,
    'membershipenrollid': pl.Utf8,
    'membershiplevelid': pl.Utf8,
    'membershiptypeid': pl.Utf8,
    'nameId': pl.Float64,
    'nameOnCard': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'partnerMembershipId': pl.Float64,
    'pointflag': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryMembershipYN': pl.Utf8,
    'primaryairlineflag': pl.Utf8,
    'processExpirationDate': pl.Utf8,
    'profileid': pl.Float64,
    'ranking': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'trackData': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
individual_daily_statistics_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFBRevenue': pl.Float64,
    'cFBRevenueTax': pl.Float64,
    'cGroupFBRevenue': pl.Float64,
    'cGroupFBRevenueTax': pl.Float64,
    'cGroupOtherRevenue': pl.Float64,
    'cGroupOtherRevenueTax': pl.Float64,
    'cGroupRoomRevenue': pl.Float64,
    'cGroupRoomRevenueTax': pl.Float64,
    'cGroupTotalRevenue': pl.Float64,
    'cGroupTotalRevenueTax': pl.Float64,
    'cOtherRevenue': pl.Float64,
    'cOtherRevenueTax': pl.Float64,
    'cRoomRevenue': pl.Float64,
    'cRoomRevenueTax': pl.Float64,
    'cTotalFBRevenueTax': pl.Float64,
    'cTotalOtherRevenueTax': pl.Float64,
    'cTotalRevenue': pl.Float64,
    'cTotalRevenueTax': pl.Float64,
    'cTotalRoomRevenueTax': pl.Float64,
    'cTotalTotalRevenueTax': pl.Float64,
    'cancels': pl.Float64,
    'centralFBRevenue': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'contextCd': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fBRevenue': pl.Float64,
    'fbRevenue': pl.Float64,
    'fbRevenueTax': pl.Float64,
    'grpFBRevenue': pl.Float64,
    'grpFBRevenueTax': pl.Float64,
    'grpNumberCancels': pl.Float64,
    'grpNumberNights': pl.Float64,
    'grpNumberNumberShows': pl.Float64,
    'grpNumberStays': pl.Float64,
    'grpOtherRevenue': pl.Float64,
    'grpOtherRevenueTax': pl.Float64,
    'grpRoomRevenue': pl.Float64,
    'grpRoomRevenueTax': pl.Float64,
    'grpTotalRevenue': pl.Float64,
    'grpTotalRevenueTax': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jrnFilerba': pl.Float64,
    'jrnFileseqno': pl.Float64,
    'jrnFlag': pl.Utf8,
    'jrnScn': pl.Float64,
    'jrnSlicingTs': pl.Utf8,
    'jrnUpdateDttm': pl.Utf8,
    'locationID': pl.Utf8,
    'nameId': pl.Float64,
    'nameType': pl.Utf8,
    'noShows': pl.Float64,
    'numberCancels': pl.Float64,
    'numberNights': pl.Float64,
    'numberNoShows': pl.Float64,
    'numberStays': pl.Float64,
    'organizationID': pl.Int64,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'stayDate': pl.Utf8,
    'stayMonth': pl.Float64,
    'stayYear': pl.Float64,
    'stays': pl.Float64,
    'totalFbRevenueTax': pl.Float64,
    'totalOtherRevenue': pl.Float64,
    'totalOtherRevenueTax': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueTax': pl.Float64,
    'totalRoomRevenue': pl.Float64,
    'totalRoomRevenueTax': pl.Float64,
    'totalTotalRevenue': pl.Float64,
    'totalTotalRevenueTax': pl.Float64,
}
```
```python
profile_keywords_details_schema = {
    'centralKeywordType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'interfaceUpdatedYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'keywordSoundex': pl.Utf8,
    'keywordType': pl.Utf8,
    'laptopChange': pl.Float64,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateAllowedYn': pl.Utf8,
}
```
```python
profile_subscription_details_schema = {
    'allowDuplicateYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'distributeYn': pl.Utf8,
    'extDBNameID': pl.Utf8,
    'externalDatabaseName': pl.Utf8,
    'externalProfileId': pl.Utf8,
    'forceYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastActivityDate': pl.Utf8,
    'lastDistributeDate': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'pendingAction': pl.Float64,
    'primaryKeyID': pl.Int64,
    'profileId': pl.Float64,
    'profilesubscriptionId': pl.Float64,
    'queryCode': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```