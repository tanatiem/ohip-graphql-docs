# ProfilesAddresses
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| profileAddressDetails | [`ProfilesAddressesProfileAddressDetailsType`](#profilesaddressesprofileaddressdetailstype) | Profile Address Details |
| profileInformationDetails | [`ProfilesAddressesProfileInformationDetailsType`](#profilesaddressesprofileinformationdetailstype) | Profile Details |
| profilesAddressesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesAddressesProfileAddressDetailsType

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

### ProfilesAddressesProfileInformationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRNumber | `String` | AR Number |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerCode | `String` | Account Owner Code |
| accountPhonePrimary | `String` | Phone no. |
| accountSource | `String` | Account Source |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| accountsourceDesc | `String` | Accountsource Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressId | `Float` | Address ID |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allOwners | `String` | All Owners |
| allResorts | `String` | All Resorts |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| anonymizationDate | `Date` | System Date when the guest was anonymized in OPERA. |
| anonymizationStatus | `String` | Anonymization Status possible values: REQUESTED ANONYMIZED. |
| arNumberCentral | `String` | AR No Central |
| autoPopRouting | `String` | Auto Pop Routing |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| availabilityOverride | `String` | Does profile have Availability Override Y/N |
| billingCode | `String` | The billing code for this name record. |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthCountry | `String` | Country of birth. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessSegement | `String` | Business Segement |
| businessTitle | `String` | Business Title |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | The unique identifier of the CRS |
| cashBlInd | `String` | Cash Bl Individual |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralIATANumber | `String` | Central IATA Number |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralSourceOwnerTitle | `String` | Central Source Owner Title |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| commissionCode | `String` | Commission Code |
| commissionCodes | `String` | Commission Codes |
| commissionCurrencyId | `String` | Comm Curr ID |
| commissionid | `String` | Commissionid |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| company | `String` | Company |
| companyGroupId | `String` | Linked internal ID for booker. |
| companyNameId | `Float` | Company Name ID |
| competitionCode | `String` | Competition Code |
| competitionDesc | `String` | Competition Description |
| contactFlag | `String` | Contact Flag |
| contactOwnerCode | `String` | Contact Owner Code |
| contractNo | `String` | Contract Number (used for customers). |
| contractRecvDate | `Date` | The date the group contract was received. |
| corpID | `String` | Corp ID |
| corpTypeDesc | `String` | Corp Type Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryDesc | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| decimalPositions | `Float` | Decimal Positions |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Department |
| deptId | `String` | Dept ID |
| directBillBatchType | `String` | Direct Bill Batch Type |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| eInvLiableLastUpdated | `Date` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Indicates if the payee profile ID is E_INVOICE liable. |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalDisplayName | `String` | External Display Name |
| externalFirstName | `String` | External First Name |
| externalId | `String` | External ID |
| externalName | `String` | External Name |
| externalReferenceRequ | `String` | Not Used. |
| externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| fMembershipCardNumbers | `String` | F Membership Card Numbers |
| fMembershipClassDesc | `String` | F Membership Class Description |
| fMembershipClasses | `String` | F Membership Classes |
| fMembershipCodes | `String` | F Membership Codes |
| fMembershipDescriptions | `String` | F Membership Descriptions |
| fMembershipIds | `String` | F Membership Ids |
| fMembershipType | `String` | F Membership Type |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Gender |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iataConsortia | `String` | IATA Consortia |
| idCountry | `String` | ID Country |
| idDate | `Date` | ID Date |
| idDocumentAttachId | `Float` | Store the ID value of linked_attachments.attach_id pointing to the physical table column that stores the scanned document. |
| idNumber | `String` | ID Number |
| idPlace | `String` | ID Place |
| idType | `String` | ID Type |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| incognitoFirstName | `String` | Incognito First Name |
| incognitoLastName | `String` | Incognito Last Name |
| indexName | `String` | Index Name |
| industryCode | `String` | Industry Code |
| industryDesc | `String` | Industry Description |
| influence | `String` | Influence |
| influenceDesc | `String` | Influence Description |
| insertUserId | `Float` | Insert User ID |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| laptopChange | `Float` | Laptop Change |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRateCode | `String` | Last Rate Code |
| lastRoom | `String` | Not used. |
| lastRoomResort | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailActionCodes | `String` | Mail Action Codes |
| mailActionDesc | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| marketsDesc | `String` | Markets Description |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| middle | `String` | Middle |
| name | `String` | Name |
| nameComment | `String` | Not Used. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| nameTypeDescription | `String` | Name Type Description |
| nameWithTitle | `String` | Name With Title |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| passport | `String` | Passport |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| paymentMethodsCode | `String` | Payment Methods Code |
| paymentMethodsDesc | `String` | Payment Methods Description |
| phoneWeb | `String` | Phone Web |
| phoneYn | `String` | Phone Y/N |
| postalCode | `String` | Postal Code |
| preferredRoomNo | `String` | Preferred Room Number |
| primaryAddressId | `Float` | Not used. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryNameId | `Float` | Not Used. |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| primaryPhoneId | `Float` | Not used. |
| priority | `String` | Priority |
| priorityDesc | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| productInterestCodes | `String` | Product Interest Codes |
| profession | `String` | Profession of the guest |
| profileArrCodes | `String` | Profile Arrangement Codes |
| profileArrangementDesc | `String` | Profile Arr Description |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileLanguage | `String` | Profile Language |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| protected | `String` | Protected |
| province | `String` | Province |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | Region |
| regionid | `String` | Regionid |
| repAccountType | `String` | Rep Account Type |
| repAccountsource | `String` | Reporting Accountsource |
| repCompetitionCode | `String` | Reporting Competition Code |
| repIataCompType | `String` | Rep IATA Comp Type |
| repIndustryCode | `String` | Reporting Industry Code |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Reporting Mail Action Codes |
| repMarkets | `String` | Reporting Markets |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repStateDescription | `String` | Reporting State Desc |
| repTaxType | `String` | Reporting Tax Type |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restrictedRule | `String` | Restricted Rule |
| resvContact | `String` | Reservation Contact person. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotentialDesc | `String` | Rooms Potential Description |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDesc | `String` | Scope City Description |
| scopeDesc | `String` | Scope Description |
| sfirst | `String` | Uppercase value of First Name. |
| smsYn | `String` | Use this alert to text a notification. |
| sname | `String` | The Uppercase value of Last or Company. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| sourceOwnerTitle | `String` | Source Owner Title |
| state | `String` | State |
| stateDesc | `String` | State Description of the Guest of Payee |
| stateDescription | `String` | State Description |
| suffix | `String` | Suffix |
| summRefCc | `String` | Summ Ref Cc |
| summRefCurrencyId | `String` | Summ Ref Curr ID |
| superSearchIndexText | `String` | Super Search Index Text |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| taxTypeDesc | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDesc | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| titleName | `String` | Title Name |
| titleSuffix | `Float` | Title Suffix |
| topAccountID | `Float` | Top Account ID |
| totalArrivals | `Float` | Total Arrivals |
| totalArrivalsLastyear | `Float` | Total Arrivals Last Year |
| totalCancelledReservations | `Float` | Total Cancelled Reservations |
| totalCancelledResvLastYear | `Float` | Total Cancelled Reservation Lastyear |
| totalCancelledRooms | `Float` | Total Cancelled Rooms |
| totalCancelledRoomsLastyear | `Float` | Total Cancelled Rooms Last Year |
| totalDayUseReservations | `Float` | Total Day Use Reservations |
| totalDayUseResvLastYear | `Float` | Total Day Use Reservation Lastyear |
| totalDayUseRooms | `Float` | Total Day Use Rooms |
| totalDayUseRoomsLastyear | `Float` | Total Day Use Rooms Last Year |
| totalFbRevenue | `Float` | Total FB Revenue |
| totalFbRevenueLastYear | `Float` | Total FB Revenue Lastyear |
| totalNoShowReservations | `Float` | Total Number Show Reservations |
| totalNoShowRooms | `Float` | Total Number Show Rooms |
| totalNonRevenue | `Float` | Total Non Revenue |
| totalNonRevenueLastyear | `Float` | Total Non Revenue Last Year |
| totalNumberShowResvLastYear | `Float` | Total No Show Reservation Lastyear |
| totalNumberShowRoomsLastyear | `Float` | Total No Show Rooms Last Year |
| totalOtherRevenue | `Float` | Total Other Revenue |
| totalOtherRevenueLastyear | `Float` | Total Other Revenue Last Year |
| totalReservationNights | `Float` | Total Reservation Nights |
| totalResvNightsLastYear | `Float` | Total Reservation Nights Lastyear |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueLastyear | `Float` | Total Revenue Last Year |
| totalRoomNightsLastyear | `Float` | Total Room Nights Last Year |
| totalRoomRevenue | `Float` | Total Room Revenue |
| totalRoomRevenueLastyear | `Float` | Total Room Revenue Last Year |
| totalStays | `Float` | Sum of total number of stays on stay records for the time period. |
| totalStaysLastyear | `Float` | Total Stays Last Year |
| tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| traceCode | `String` | Trace Code |
| tracecodeDesc | `String` | Tracecode Description |
| typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
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
| updateUserId | `Float` | Update User ID |
| uploadDate | `Date` | Upload Date |
| vendorId | `Float` | Vendor ID |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

## Input Types

### DateInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Date` |  |  |
| _ne | `Date` |  |  |
| _in | `[Date]` |  |  |
| _nin | `[Date]` |  |  |
| _gt | `Date` |  |  |
| _lt | `Date` |  |  |
| _gte | `Date` |  |  |
| _lte | `Date` |  |  |
| _btn | [`DateRangeInput`](#daterangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Date!` |  |  |
| end | `Date!` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `DateTime` |  |  |
| _ne | `DateTime` |  |  |
| _in | `[DateTime]` |  |  |
| _nin | `[DateTime]` |  |  |
| _gt | `DateTime` |  |  |
| _lt | `DateTime` |  |  |
| _gte | `DateTime` |  |  |
| _lte | `DateTime` |  |  |
| _btn | [`DateTimeRangeInput`](#datetimerangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### DateTimeRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `DateTime!` |  |  |
| end | `DateTime!` |  |  |

[⬆ Back to Query](#query)

---

### StringInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `String` |  |  |
| _ne | `String` |  |  |
| _in | `[String]` |  |  |
| _nin | `[String]` |  |  |
| _gt | `String` |  |  |
| _lt | `String` |  |  |
| _gte | `String` |  |  |
| _lte | `String` |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| _eq | `Float` |  |  |
| _ne | `Float` |  |  |
| _in | `[Float]` |  |  |
| _nin | `[Float]` |  |  |
| _gt | `Float` |  |  |
| _lt | `Float` |  |  |
| _gte | `Float` |  |  |
| _lte | `Float` |  |  |
| _btn | [`FloatRangeInput`](#floatrangeinput) |  |  |
| _isNull | `Boolean` |  |  |

[⬆ Back to Query](#query)

---

### FloatRangeInput

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| start | `Float!` |  |  |
| end | `Float!` |  |  |

[⬆ Back to Query](#query)

---

### ProfilesAddressesQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| profileaddressDetailsAddress1 | `StringInput` | The first line of street address. |  |
| profileaddressDetailsAddress2 | `StringInput` | The second line of street address. |  |
| profileaddressDetailsAddress3 | `StringInput` | The third line of street address. |  |
| profileaddressDetailsAddress4 | `StringInput` | The fourth line of street address. |  |
| profileaddressDetailsAddressId | `FloatInput` | The primary key for this table. |  |
| profileaddressDetailsLanguageCode | `StringInput` | Address Language |  |
| profileaddressDetailsLanguageDesc | `StringInput` | Description for each language code. |  |
| profileaddressDetailsAddressType | `StringInput` | The type of address. |  |
| profileaddressDetailsAddressTypeDesc | `StringInput` | The description of this value. |  |
| profileaddressDetailsBarcode | `StringInput` | The postal barcode for the address. |  |
| profileaddressDetailsBeginDate | `DateInput` | Not used. |  |
| profileaddressDetailsRepStateCode | `StringInput` | Central State |  |
| profileaddressDetailsRepState | `StringInput` | Central State Description |  |
| profileaddressDetailsChainCode | `StringInput!` | The Chain code of the chain for which this record belongs to. | `mandatoryInput` |
| profileaddressDetailsCity | `StringInput` | The city for this address. |  |
| profileaddressDetailsCleansedDatetime | `DateTimeInput` | The Timestamp when this record was cleansed. |  |
| profileaddressDetailsCleansedErrormsg | `StringInput` | The error message why this record was not cleansed. |  |
| profileaddressDetailsCleansedMatchstatus | `StringInput` | Specifies how the address elements match with the postal reference data. |  |
| profileaddressDetailsCleansedStatus | `StringInput` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |  |
| profileaddressDetailsCleansedValidationstatus | `StringInput` | Validation Status as returned by the Address Cleansing System. |  |
| profileaddressDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |  |
| profileaddressDetailsCountryCode | `StringInput` | Country . |  |
| profileaddressDetailsCountry | `StringInput` | Country name. |  |
| profileaddressDetailsInsertUser | `FloatInput` | The user that created the record |  |
| profileaddressDetailsInsertDate | `DateTimeInput` | The date the record was created |  |
| profileaddressDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| profileaddressDetailsDeletedFlag | `StringInput` | Deleted Y/n |  |
| profileaddressDetailsEndDate | `DateInput` | Not used. |  |
| profileaddressDetailsFirst | `StringInput` | The first name of an individual name. |  |
| profileaddressDetailsForeignCountry | `StringInput` | Not used. |  |
| profileaddressDetailsInCareOf | `StringInput` | Not used. |  |
| profileaddressDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |  |
| profileaddressDetailsInactiveFlag | `StringInput` | Inactive Y/n |  |
| profileaddressDetailsOrganizationId | `FloatInput` | Organization ID |  |
| profileaddressDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| profileaddressDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop. (not used) |  |
| profileaddressDetailsLastUpdatedResort | `StringInput` | Last property that updated this record. |  |
| profileaddressDetailsName | `StringInput` | Name |  |
| profileaddressDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| profileaddressDetailsZipCode | `StringInput` | The postal code of this address. |  |
| profileaddressDetailsCityExt | `StringInput` | City Extension mainly used for UK addresses. |  |
| profileaddressDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |  |
| profileaddressDetailsPrimaryYn | `StringInput` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |  |
| profileaddressDetailsProfileAddressId | `FloatInput` | The primary key for this table. |  |
| profileaddressDetailsNameId | `FloatInput` | The reference to the NAME record that owns this address. |  |
| profileaddressDetailsProfileId | `FloatInput` | The reference to the NAME record that owns this address. |  |
| profileaddressDetailsProvince | `StringInput` | Province. |  |
| profileaddressDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |  |
| profileaddressDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |  |
| profileaddressDetailsState | `StringInput` | State |  |
| profileaddressDetailsStateCode | `StringInput` | The state of this address. |  |
| profileaddressDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |
| profileaddressDetailsUpdateUser | `FloatInput` | The user that modified the record |  |
| profileDetailsActiveYn | `StringInput` | Active Flag |  |
| profileDetailsAnonymizationStatus | `StringInput` | Anonymization Status possible values: REQUESTED ANONYMIZED. |  |
| profileDetailsCrsNameid | `FloatInput` | The unique identifier of the CRS |  |
| profileDetailsCompany | `StringInput` | Company |  |
| profileDetailsCompanyGroupId | `StringInput` | Linked internal ID for booker. |  |
| profileDetailsContactFlag | `StringInput` | Contact Flag |  |
| profileDetailsSrepCode | `StringInput` | Contact Owner Code |  |
| profileDetailsNameCode | `StringInput` | Corp ID |  |
| profileDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| profileDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |  |
| profileDetailsHistoryYn | `StringInput` | History Y/N |  |
| profileDetailsInactiveDate | `DateInput` | Inactive Date |  |
| profileDetailsIndexName | `StringInput` | Index Name |  |
| profileDetailsOrganizationId | `FloatInput` | Organization ID |  |
| profileDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| profileDetailsLast | `StringInput` | Last |  |
| profileDetailsNameId | `FloatInput` | Name ID |  |
| profileDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| profileDetailsProfileType | `StringInput` | Profile Type |  |
| profileDetailsNameType | `StringInput` | Profile Type Code |  |
| profileDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |  |
| profileDetailsSfirst | `StringInput` | Uppercase value of First Name. |  |
| profileDetailsSname | `StringInput` | The Uppercase value of Last or Company. |  |
| profileDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |  |
| profileDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |  |
| profileDetailsProfileId | `FloatInput` | Top Account ID |  |
| profileDetailsUpdateDate | `DateTimeInput` | Update Date |  |

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