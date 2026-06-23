# ConfigurationChain
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `configurationChain`
> The Chain Configuration Subject Area contains configuration/setting attributes from components such as Enterprise Administration Financial Administration Booking Administration and Client Relations Administration in OPERA.
  
**Return:** [`[ConfigurationChainType]`](#configurationchaintype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ConfigurationChainQueryArgumentsType!`](#configurationchainqueryargumentstype) |  |

## Object Types

### ConfigurationChainType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainDetails | [`ConfigurationChainChainDetailsType`](#configurationchainchaindetailstype) | Chain Details |
| 2 | membershipEnrollmentCodeDetails | [`ConfigurationChainMembershipEnrollmentCodeDetailsType`](#configurationchainmembershipenrollmentcodedetailstype) | Membership Enrollment Code |
| 3 | membershipEnrollGroupDetails | [`ConfigurationChainMembershipEnrollGroupDetailsType`](#configurationchainmembershipenrollgroupdetailstype) | Membership Enroll Group |
| 4 | membershipMarketGroupMembershipMarketGroupDetails | [`ConfigurationChainMembershipMarketGroupMembershipMarketGroupDetailsType`](#configurationchainmembershipmarketgroupmembershipmarketgroupdetailstype) | Membership Market Group |
| 5 | membershipMarketGroupDetails | [`ConfigurationChainMembershipMarketGroupDetailsType`](#configurationchainmembershipmarketgroupdetailstype) | Membership Market Group |
| 6 | membershipTypeDetails | [`ConfigurationChainMembershipTypeDetailsType`](#configurationchainmembershiptypedetailstype) | Membership Type Details |
| 7 | membershipPropertyGroupDetails | [`ConfigurationChainMembershipPropertyGroupDetailsType`](#configurationchainmembershippropertygroupdetailstype) | Membership Property Group |
| 8 | membershipRateGroupDetails | [`ConfigurationChainMembershipRateGroupDetailsType`](#configurationchainmembershiprategroupdetailstype) | Membership Rate Group |
| 9 | membershipRevenueGroupDetails | [`ConfigurationChainMembershipRevenueGroupDetailsType`](#configurationchainmembershiprevenuegroupdetailstype) | Membership Revenue Group |
| 10 | membershipRevenueTypeDetails | [`ConfigurationChainMembershipRevenueTypeDetailsType`](#configurationchainmembershiprevenuetypedetailstype) | Membership Revenue Type |
| 11 | membershipRoomGroupDetails | [`ConfigurationChainMembershipRoomGroupDetailsType`](#configurationchainmembershiproomgroupdetailstype) | Membership Room Group |
| 12 | hubDetails | [`ConfigurationChainHubDetailsType`](#configurationchainhubdetailstype) | Hub Details |
| 13 | noteTypeDetails | [`ConfigurationChainNoteTypeDetailsType`](#configurationchainnotetypedetailstype) | Note Type Details |
| 14 | propertyTypeDetails | [`ConfigurationChainPropertyTypeDetailsType`](#configurationchainpropertytypedetailstype) | Property Type |
| 15 | foreignCurrencyDetails | [`ConfigurationChainForeignCurrencyDetailsType`](#configurationchainforeigncurrencydetailstype) | Foreign Currency Details |
| 16 | itemRateRulesDetails | [`ConfigurationChainItemRateRulesDetailsType`](#configurationchainitemraterulesdetailstype) | Item Rate Rules Details |
| 17 | postalCodeDetails | [`ConfigurationChainPostalCodeDetailsType`](#configurationchainpostalcodedetailstype) | Postal Code Details |
| 18 | iDDocumentTypeDetails | [`ConfigurationChainIDDocumentTypeDetailsType`](#configurationchainiddocumenttypedetailstype) | ID Document Type |
| 19 | languageDetails | [`ConfigurationChainLanguageDetailsType`](#configurationchainlanguagedetailstype) | Language Details |
| 20 | regionDetails | [`ConfigurationChainRegionDetailsType`](#configurationchainregiondetailstype) | Region Details |
| 21 | stateDetails | [`ConfigurationChainStateDetailsType`](#configurationchainstatedetailstype) | State Details |
| 22 | membershipClassDetails | [`ConfigurationChainMembershipClassDetailsType`](#configurationchainmembershipclassdetailstype) | Membership Class Details |
| 23 | confirmationFormatDetails | [`ConfigurationChainConfirmationFormatDetailsType`](#configurationchainconfirmationformatdetailstype) | Confirmation Format Details |
| 24 | communicationTypeDetails | [`ConfigurationChainCommunicationTypeDetailsType`](#configurationchaincommunicationtypedetailstype) | Communication Type Details |
| 25 | profilePreferenceTypeDetails | [`ConfigurationChainProfilePreferenceTypeDetailsType`](#configurationchainprofilepreferencetypedetailstype) | Profile Preference Type Details |
| 26 | profileProfileDetails | [`ConfigurationChainProfileProfileDetailsType`](#configurationchainprofileprofiledetailstype) | Profile Profile |
| 27 | configurationRelationshipDetails | [`ConfigurationChainConfigurationRelationshipDetailsType`](#configurationchainconfigurationrelationshipdetailstype) | Configuration Relationship |
| 28 | membershipClaimTypeDetails | [`ConfigurationChainMembershipClaimTypeDetailsType`](#configurationchainmembershipclaimtypedetailstype) | Membership Claim Type |
| 29 | membershipAwardsDetails | [`ConfigurationChainMembershipAwardsDetailsType`](#configurationchainmembershipawardsdetailstype) | Membership Awards |
| 30 | membershipEnrollDetails | [`ConfigurationChainMembershipEnrollDetailsType`](#configurationchainmembershipenrolldetailstype) | Membership Enroll Details |
| 31 | membershipLevelDetails | [`ConfigurationChainMembershipLevelDetailsType`](#configurationchainmembershipleveldetailstype) | Membership Level Details |
| 32 | membershipCardRangesDetails | [`ConfigurationChainMembershipCardRangesDetailsType`](#configurationchainmembershipcardrangesdetailstype) | Membership Card Ranges |
| 33 | membershipLevelBenefitsDetails | [`ConfigurationChainMembershipLevelBenefitsDetailsType`](#configurationchainmembershiplevelbenefitsdetailstype) | Membership Level Benefits |
| 34 | membershipMarketGroupCodeDetails | [`ConfigurationChainMembershipMarketGroupCodeDetailsType`](#configurationchainmembershipmarketgroupcodedetailstype) | Membership Market Group Code |
| 35 | membershipRateGroupCodeDetails | [`ConfigurationChainMembershipRateGroupCodeDetailsType`](#configurationchainmembershiprategroupcodedetailstype) | Membership Rate Group Code |
| 36 | membershipRevenueGroupCodeDetails | [`ConfigurationChainMembershipRevenueGroupCodeDetailsType`](#configurationchainmembershiprevenuegroupcodedetailstype) | Membership Revenue Group Code |
| 37 | propertyBookingStatusNextDetails | [`ConfigurationChainPropertyBookingStatusNextDetailsType`](#configurationchainpropertybookingstatusnextdetailstype) | Property Booking Status Next |
| 38 | configurationChainRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ConfigurationChainChainDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aspYn | `String` | Chain used for ASP Y/N. |
| 2 | beginDate | `Date` | Begin Date |
| 3 | bookingConditions | `String` | Booking conditions chainwide such as commission policies for TA Group policies Cancellation/Deposit/Guarantee and family and child rules. |
| 4 | centralChain | `String` | Central Chain |
| 5 | centralDescription | `String` | Central Description |
| 6 | chain | `String` | Chain |
| 7 | chainName | `String` | Chain Name |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | endDate | `Date` | End Date |
| 12 | frequentFlierCardsAcceptYn | `String` | Specifies if frequent flier cards are accepted by the chain (Y/N). |
| 13 | hoCity | `String` | The city of the Head Office of the chain. |
| 14 | hoCountry | `String` | The country of the Head Office of the chain. |
| 15 | hoEmail | `String` | The email ID of the Head Office of the chain. |
| 16 | hoFax | `String` | The fax number of the Head Office of the chain. |
| 17 | hoPostCode | `String` | The postal code of the Head Office of the chain. |
| 18 | hoState | `String` | The state of the Head Office of the chain. |
| 19 | hoStreet | `String` | The street of the Head Office of the chain. |
| 20 | hoTelephone | `String` | The phone number of the Head Office of the chain. |
| 21 | imgChainId | `Float` | Img Chain ID |
| 22 | inactiveDate | `Date` | Inactive Date |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | jRNUpdateDate | `Date` | JRN Update Date |
| 26 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 27 | logoFileName | `String` | File name of the chains' logo |
| 28 | loyaltyProgram | `String` | Loyalty program data. |
| 29 | marketingText | `String` | Marketing Text |
| 30 | nameId | `Float` | Name ID |
| 31 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 34 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 35 | repItem | `String` | Reporting Item |
| 36 | repItemName | `String` | Reporting Item Name |
| 37 | repItemOrderby | `Float` | Reporting Item Orderby |
| 38 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 39 | scriptId | `Float` | Script ID |
| 40 | shareProfilesYN | `String` | Sharing Profiles across the Chain. |
| 41 | updateDate | `DateTime` | Update Date |
| 42 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollmentCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | comments | `String` | Comments |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedflag | `String` | Deleted Flag |
| 7 | displayColor | `String` | Display Color |
| 8 | enrollmentCode | `String` | Enrollment Code |
| 9 | enrollmentDescription | `String` | Enrollment Description |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | enrollmentGroupCode | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| 5 | enrollmentGroupDescription | `String` | Enrollment Group Description |
| 6 | includeExclude | `String` | Include Exclude |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 15 | sequence | `Float` | Sequence |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupMembershipMarketGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | includeExclude | `String` | Include Exclude |
| 5 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 6 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | insertDate | `DateTime` | Insert Date |
| 2 | insertUser | `Float` | Insert User |
| 3 | jRNUpdateDate | `Date` | JRN Update Date |
| 4 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 5 | marketGroupCode | `String` | Market Group Code |
| 6 | marketGroupDescription | `String` | Market Group Description |
| 7 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 8 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 9 | sequence | `Float` | Sequence |
| 10 | updateDate | `DateTime` | Update Date |
| 11 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | activityPeriodYears | `String` | Activity Period Years |
| 3 | allowAdhocMultiplierYn | `String` | Indicates if program allows Ad Hoc multipliers for points calculation. |
| 4 | allowDuplicateCardNumbersYN | `String` | Allow Duplicate Card Numbers YN |
| 5 | allowSharesYn | `String` | Flag indicating if points should be calculated for shared rooms. |
| 6 | alternateNameProtectedYN | `String` | Alternate Name Protected YN |
| 7 | autoCardNoBasedOn | `String` | This is used when the card no is auto generated and is based on some other value  like enrollment code. |
| 8 | autoGenCardPrefix | `String` | Auto Gen Card Prefix |
| 9 | autoPopulateNumberFromNameYN | `String` | Auto Populate Number From Name YN |
| 10 | awardGenerationMethod | `String` | Not used |
| 11 | awardPointExpiryDateYears | `String` | Award Point Expiry Date Years |
| 12 | awardRedeemThreshold | `String` | Award Redeem Threshold |
| 13 | basedOn | `String` | Defines what the rule is based on the type of condition which need to be satisfied in order to qualify for this rule. Valid values are MEMBERSHIP RATE_CODE REFERENCE VIP. |
| 14 | bookerProgramYn | `String` | Flag to mark the booker program membership types. |
| 15 | cCostPerPoint | `Float` | Central Cost Per Point |
| 16 | cExchangeDate | `Date` | Central Xchange Date |
| 17 | cExchangeRate | `Float` | Central Xchange Rate |
| 18 | calculationMethod | `String` | Valid values are ROLLING or CALENDAR.Rolling ? Indicates the membership will run from the same month for a determined amount of time.Calendar ? Indicates the calculation will occur every year at the end of the year. |
| 19 | calculationMonths | `Float` | This signifies the number of months that points are valid for a membership type |
| 20 | calculationPeriod | `String` | Valid values are ROLLING_MONTHS and CALENDAR_MONTHS. |
| 21 | canDeleteYn | `String` | Can Delete Y/N |
| 22 | cardLength | `Float` | The length of the card number for default card validation. |
| 23 | cardPrefix | `String` | Card Prefix |
| 24 | cardValidYears | `Float` | Number of years card will be valid for this level. |
| 25 | centrallyManagedYN | `String` | Indicates if program is managed centrally or at Local property. If central then points will be calculated at ECIS else if program is local then points will be calculated and stored locally. |
| 26 | chainCode | `String` | Chain Code |
| 27 | checkInYN | `String` | Indicates if a prompt is required at checkin of a reservation if a membership number exists on profile and not attached to the reservation. |
| 28 | checkOutYN | `String` | Indicates if resv_memberships should popup when a reservation is checked out. |
| 29 | chipAndPinYn | `String` | Indicates if this membership type is Chip and Pin. |
| 30 | class | `String` | Primary key of this table |
| 31 | costPerPoint | `Float` | Cost Per Point |
| 32 | currencyCode | `String` | Currency Code |
| 33 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 34 | defaultMemberStatus | `String` | Default value for membership status. |
| 35 | delayInDays | `Float` | Not used |
| 36 | deletedFlag | `String` | Deleted Flag |
| 37 | description | `String` | Description |
| 38 | downgradePeriod | `Float` | Number of months to consider for downgrade. |
| 39 | downgradePeriodYr | `String` | Downgrade Period Year |
| 40 | downgradeRenewalYN | `String` | Downgrade/Renewal YN |
| 41 | enrollcoderequiredflag | `String` | Enrollcoderequiredflag |
| 42 | enrollmentCodeRequiredYN | `String` | Enrollment code required flag. |
| 43 | exceptionType | `String` | Exception Type |
| 44 | exchangeRateType | `String` | Exchange Rate Type |
| 45 | excludeProfileFromPurgeYN | `String` | Exclude Profile From Purge YN |
| 46 | expirationDateRequiredYN | `String` | Expiration Date Required YN |
| 47 | expirationMonth | `Float` | Expiration month for membership types having a ROLLING calculation method. |
| 48 | expiryPeriod | `String` | Expiry Period |
| 49 | externalDatabase | `String` | External Database |
| 50 | externalProcessDays | `Float` | Maximum number of days to process the External Processing Exception. |
| 51 | externallyControlledYN | `String` | Flag that affects how a Membership Type is added edited or deleted from a profile. |
| 52 | folioMessageCredits | `String` | Folio Message for Credits. |
| 53 | folioMessageNonmembers | `String` | Folio Message Nonmembers |
| 54 | folioMessageNonmembersNq | `String` | Folio message for non members who have a non-qualifying rate code. |
| 55 | folioMessageNq | `String` | Folio message for members who have a non-qualifying rate code. |
| 56 | foreignCurrencyID | `String` | Foreign Currency ID |
| 57 | format | `String` | Format for Random Number Generation. |
| 58 | fromSequenceNumber | `Float` | From Sequence Number |
| 59 | fulfillmentYN | `String` | Fulfillment YN |
| 60 | graceExpirationMonth | `Float` | Used in EIS Module. |
| 61 | gracePeriodYears | `String` | Grace Period Years |
| 62 | inactiveDate | `DateTime` | Inactive Date |
| 63 | inactiveflag | `String` | Inactive Flag |
| 64 | insertDate | `DateTime` | Insert Date |
| 65 | insertUser | `Float` | Insert User |
| 66 | internalDeletedflag | `String` | Deleted Flag |
| 67 | jRNUpdateDate | `Date` | JRN Update Date |
| 68 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 69 | levelRequiredYN | `String` | Level Required YN |
| 70 | memberFolioMessage | `String` | Free form text that can ve configured to display on the folio of clients earning points under this program. |
| 71 | memberInfoDispSet | `String` | Display set used for member info. |
| 72 | membershipAction | `String` | [A]utopopulate on Reservation [P]rompt on Reservation; Al[W]ays Prompt [N]o action. |
| 73 | membershipActionDetails | `String` | Membership Action Details |
| 74 | membershipclassid | `String` | Membershipclassid |
| 75 | membershiptypeid | `String` | Membershiptypeid |
| 76 | multipleRoomsLimit | `Float` | Multiple rooms allowed for points exception. |
| 77 | nameProtectedYN | `String` | Name Protected YN |
| 78 | nameOnCardFromAltNameYN | `String` | Name on Card From Alt Name YN |
| 79 | newReservationYN | `String` | Indicates if resv_memberships should popup when a reservation is created. |
| 80 | numericValidation | `String` | Indicates the type of card number validation which should be done. |
| 81 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 82 | pointsCalculationMethod | `String` | Points Calculation Method |
| 83 | pointsIssuedCentrallyYn | `String` | Indicates that points are issued by central system |
| 84 | pointsLabel | `String` | Label for points (i.e. Points or Miles) |
| 85 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 86 | primaryYN | `String` | Primary YN |
| 87 | printFolioMessageOnConfirmationYN | `String` | Print Folio Message On Confirmation YN |
| 88 | promptatcheckinflag | `String` | Promptatcheckinflag |
| 89 | randomGenerationYN | `String` | Random Generation YN |
| 90 | rank | `Float` | Rank |
| 91 | requalifyOnUpgradeYN | `String` | Requalify on Upgrade YN |
| 92 | requiredOnStayPeriodYN | `String` | Required on Stay Period YN |
| 93 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 94 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 95 | rule | `String` | Rule for posting NOSHOW revenue. |
| 96 | saveCardNumberHistoryYN | `String` | Save Card Number History YN |
| 97 | sendChkoutToIfc | `String` | Send checkout reservation information to the interface for Courtesy Cards? |
| 98 | sendcheckouttoifcflag | `String` | Sendcheckouttoifcflag |
| 99 | sequence | `Float` | Sequence |
| 100 | tierExpirationMonth | `String` | Tier Expiration Month |
| 101 | tierManagementResetYN | `String` | Tier Management Reset YN |
| 102 | toSequenceNumber | `Float` | To Sequence Number |
| 103 | transactionMaxPoints | `Float` | Indicates the maximum points that can be accrued per membership transaction. |
| 104 | tscDateFlag | `String` | Tier Management Based on Date. |
| 105 | type | `String` | Type |
| 106 | udfCardValidationYn | `String` | Indicates if card number validation is a UDF(User defined function) or Default validation is used. |
| 107 | udfFormula | `String` | Udf Formula |
| 108 | updateDate | `DateTime` | Update Date |
| 109 | updateReservationYN | `String` | Indicates if resv_memberships should popup when a reservation is updated. |
| 110 | updateUser | `Float` | Update User |
| 111 | upgradePeriod | `Float` | Number of months to consider for upgrade. |
| 112 | upgradePeriodYr | `String` | Upgrade Period Year |
| 113 | validationByIfc | `String` | Indicates if the card is to be validated by an external system. |
| 114 | validationRule | `String` | Validation Rule |
| 115 | validationbyifcflag | `String` | Validationbyifcflag |
| 116 | yearsToExpire | `Float` | Years To Expire |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipPropertyGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | backToBack | `String` | Used to indicate the specific grouping in order to eliminate stay exceptions like back to back stays. |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | includeExclude | `String` | Include Exclude |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | propertyGroupCode | `String` | Property Group Code |
| 13 | propertyGroupDescription | `String` | Property Group Description |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | sequence | `Float` | Sequence |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRateGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | includeExclude | `String` | Include Exclude |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | rateGroupCode | `String` | Rate Group Code |
| 14 | rateGroupDescription | `String` | Rate Group Description |
| 15 | sequence | `Float` | Sequence |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | includeExclude | `String` | Include Exclude |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | revenueGroupCode | `String` | Membership rate group. |
| 14 | revenueGroupDescription | `String` | Revenue Group Description |
| 15 | sequence | `Float` | Sequence |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | frequentFlyerPoints | `String` | Indicates if the Revenue Type is valid for calculating Frequent Flyer Points. |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | label | `String` | Label |
| 10 | membershipPoints | `String` | Indicates if the Revenue Type is valid for calculating Membership Points. |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 15 | revenueBucketCode | `String` | Revenue Bucket Code |
| 16 | revenueBucketDescription | `String` | Revenue Bucket Description |
| 17 | revenueTypeCode | `String` | Revenue Types defined for OIS memberships. |
| 18 | revenueTypeDescription | `String` | Revenue Type Description |
| 19 | sequence | `Float` | Sequence |
| 20 | tierPoints | `String` | Filled in case of bucket rules where Award and Tier points can be computed same but implemented differently. |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRoomGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | insertDate | `DateTime` | Insert Date |
| 5 | insertUser | `Float` | Insert User |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 10 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 11 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 12 | roomGroupCode | `String` | Room Group Code |
| 13 | roomGroupDescription | `String` | Room Group Description |
| 14 | roomTypes | `String` | Room Types |
| 15 | sequence | `Float` | Sequence |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainHubDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| 2 | aRBalanceTrxCode | `String` | Internal |
| 3 | aRCreditTrxCode | `String` | Internal |
| 4 | accessCode | `String` | Access Code |
| 5 | address | `String` | Default property address format. |
| 6 | agingLevel1 | `Float` | Aging bucket 1 |
| 7 | agingLevel2 | `Float` | Aging bucket 2 |
| 8 | agingLevel3 | `Float` | Aging bucket 3 |
| 9 | agingLevel4 | `Float` | Aging bucket 4 |
| 10 | agingLevel5 | `Float` | Aging bucket 5 |
| 11 | airport | `String` | The Airport Code for the airport near the property |
| 12 | airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| 13 | airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| 14 | allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| 15 | allowancePeriodAdj | `String` | Period for the allowance |
| 16 | arAccountNumberFormat | `String` | Number format of AR account no. |
| 17 | arAgent | `String` | Default Account Type for an Agent for the Property |
| 18 | arCompany | `String` | Default Account Type for a Company for the Property |
| 19 | arGroups | `String` | Default Account Type for a Group for the Property |
| 20 | arIndividuals | `String` | Default Account Type for Individual for the Property |
| 21 | arSettleCode | `String` | Internal |
| 22 | arTypewriter | `String` | Internal |
| 23 | awardsTimeout | `Float` | Internal |
| 24 | baseLanguage | `String` | The base language of the Hotel |
| 25 | beginDate | `Date` | Begin Date |
| 26 | blackoutPeriodNotes | `String` | Blackout period notes defaulted onto the FIT Contract at time of creation. |
| 27 | block | `String` | Block |
| 28 | brArea | `String` | Ball Room Area |
| 29 | brSeats | `Float` | No of Ballroom Seats |
| 30 | brandCode | `String` | Brand Code |
| 31 | budgetMonth | `Float` | Financial Year of the Property |
| 32 | cCreditLimit | `Float` | Central Credit Limit |
| 33 | cDoubleRate2 | `Float` | Central Dbl Rate2 |
| 34 | cDoubleRate1 | `Float` | Central Dbl Rate1 |
| 35 | cExchangeDate | `Date` | Central Xchange Date |
| 36 | cExchangeRate | `Float` | Central Xchange Rate |
| 37 | cSglRate2 | `Float` | Central Sgl Rate2 |
| 38 | cSglRate1 | `Float` | Central Sgl Rate1 |
| 39 | cSuiRate2 | `Float` | Central Sui Rate2 |
| 40 | cSuiRate1 | `Float` | Central Sui Rate1 |
| 41 | cTplRate2 | `Float` | Central Tpl Rate2 |
| 42 | cTplRate1 | `Float` | Central Tpl Rate1 |
| 43 | cWarningAmount | `Float` | Central Warning Amount |
| 44 | cRSResort | `String` | Not used |
| 45 | cashShiftDrop | `String` | Internal |
| 46 | cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| 47 | cateringCurrencyFormat | `String` | Catering currency format. |
| 48 | chainCode | `String` | Chain Code |
| 49 | checkExgPaidout | `String` | Internal |
| 50 | checkInTime | `Date` | The Hotel official check intime |
| 51 | checkOutTime | `Date` | The Hotel official check out time |
| 52 | checkShiftDrop | `String` | Internal |
| 53 | checkTrxcode | `String` | Internal |
| 54 | city | `String` | City |
| 55 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 56 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 57 | comNameXrefId | `Float` | Internal |
| 58 | companyAddressType | `String` | Internal |
| 59 | companyPhoneType | `String` | Internal |
| 60 | configurationMode | `String` | Internal |
| 61 | confirmRegcardPrinter | `String` | Internal |
| 62 | copies | `Float` | Copies |
| 63 | country | `String` | Country |
| 64 | creditLimit | `Float` | Credit Limit |
| 65 | croCode | `String` | Cro Code |
| 66 | currency | `String` | Currency |
| 67 | currencyDecimals | `Float` | Number of decimals to designate currency |
| 68 | currencyExgPaidout | `String` | Not used |
| 69 | currencyFormat | `String` | Format for the local currency. |
| 70 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 71 | curtainColor | `String` | Color that of the background |
| 72 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 73 | dateForAging | `String` | Date the aging should begin |
| 74 | dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| 75 | dblNum | `String` | Not used |
| 76 | dblRate2 | `Float` | Not used |
| 77 | dblRate1 | `Float` | Not used |
| 78 | decimalPlaces | `Float` | Number of places for the default currency |
| 79 | decimalSeparator | `String` | Type of decimal separator |
| 80 | defaultCommissionPercentage | `String` | Not used |
| 81 | defaultFaxType | `String` | Not used |
| 82 | defaultFolioStyle | `Float` | Folio style to be used for all guests |
| 83 | defaultGroupsRateCode | `String` | Not used |
| 84 | defaultGuestAddress | `String` | Default guest address format. |
| 85 | defaultMembershipType | `String` | Future use |
| 86 | defaultPostingRoom | `String` | Future use |
| 87 | defaultPrepaidComm | `String` | Not used. |
| 88 | defaultPrinter | `String` | Not Used |
| 89 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 90 | defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| 91 | defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| 92 | defaultRegistrationCard | `String` | Default registration card for the property. |
| 93 | defaultReservationType | `String` | The Default reservation type for this property |
| 94 | defaultTrxCommissionCode | `String` | Not used. |
| 95 | deletedFlag | `String` | Deleted Flag |
| 96 | depositLedgerTrxCode | `String` | Future use |
| 97 | destinationId | `String` | Destination ID |
| 98 | dfltPkgTranCode | `String` | Future use |
| 99 | dfltTranCodeRateCode | `String` | Future use |
| 100 | directions | `String` | Internal |
| 101 | dirsales | `String` | Future use |
| 102 | disableLoginYn | `String` | LOGIN into the application is disabled. |
| 103 | downloadRestYn | `String` | Download Rest Y/N |
| 104 | dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| 105 | email | `String` | Email |
| 106 | endDate | `Date` | End Date |
| 107 | exchangePostingType | `String` | Exchange Posting Type |
| 108 | expHotelCode | `String` | Hotel code used for third party exports |
| 109 | expiryDate | `Date` | Expiry Date |
| 110 | extExpFileLocation | `String` | Future use |
| 111 | extPropertyCode | `String` | Future use |
| 112 | externalScYn | `String` | Indicates that the property uses an external SC system. |
| 113 | fax | `String` | Fax |
| 114 | faxNoFormat | `String` | Fax number formats. |
| 115 | fileTransferFormat | `String` | Not used. |
| 116 | fiscalEndDate | `Date` | Future use |
| 117 | fiscalPeriodType | `String` | Future use |
| 118 | fiscalStartDate | `Date` | Future use |
| 119 | flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| 120 | floorNumExecutiveFloor | `String` | Floor number of executive floor. |
| 121 | flowCode | `String` | Future use |
| 122 | fnsTier | `String` | Property Free Nights Stay Tier. |
| 123 | folioLanguage1 | `String` | Other languages |
| 124 | folioLanguage2 | `String` | Other languages |
| 125 | folioLanguage3 | `String` | Other languages |
| 126 | folioLanguage4 | `String` | Other languages |
| 127 | font | `Float` | Not used |
| 128 | genmgr | `String` | Future use |
| 129 | groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| 130 | guestLookupTimeout | `Float` | Future use |
| 131 | hotelCode | `String` | Property Code. |
| 132 | hotelFc | `String` | Future use |
| 133 | hotelId | `String` | Hotel ID |
| 134 | hotelType | `String` | Hotel Type |
| 135 | hub | `String` | HUB |
| 136 | imgDirectionId | `Float` | Future use |
| 137 | imgHotelId | `Float` | Future use |
| 138 | imgMapId | `Float` | Future use |
| 139 | inactiveDaysForGuestProfil | `Float` | Future use |
| 140 | individualAddressType | `String` | Future use |
| 141 | individualPhoneType | `String` | Future use |
| 142 | individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| 143 | insertDate | `DateTime` | Insert Date |
| 144 | insertUser | `Float` | Insert User |
| 145 | intTaxIncludedYn | `String` | Int Tax Included Y/N |
| 146 | inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| 147 | jRNUpdateDate | `Date` | JRN Update Date |
| 148 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 149 | keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| 150 | latitude | `Float` | Latitude of the property in decimal |
| 151 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 152 | legalOwner | `String` | The owner who owns this property |
| 153 | licenseCode | `String` | License Code |
| 154 | longDateFormat | `String` | Long date format for the property. |
| 155 | longStayControl | `Float` | The default length of stay |
| 156 | longitude | `Float` | Longitude of the property in decimal |
| 157 | maxAdultsFamilyRoom | `Float` | Maximum adults in family rooms. |
| 158 | maxChildrenFamilyRoom | `Float` | Maximum children in family rooms. |
| 159 | maxCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| 160 | maxNoNights | `Float` | Not used |
| 161 | maxOccupancy | `Float` | Max Occupancy |
| 162 | mbsSupportedYn | `String` | Indicates if the property supports MBS. Used in some file exports. |
| 163 | meetRooms | `Float` | Future use |
| 164 | meetSeats | `Float` | Future use |
| 165 | meetSpace | `Float` | Future use |
| 166 | meetingFc | `String` | Future use |
| 167 | minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| 168 | name | `String` | Name |
| 169 | nameIdLink | `Float` | Internal |
| 170 | nightAuditCashierId | `String` | Future use |
| 171 | notes | `String` | Notes |
| 172 | numberBeds | `Float` | Total number of beds in this property |
| 173 | numberFloors | `Float` | Total number of floors in this property |
| 174 | numberRooms | `Float` | Number Rooms |
| 175 | opusCurrencyCode | `String` | Future use |
| 176 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 177 | ownership | `String` | Future use |
| 178 | packageLoss | `String` | Package Loss code for a particular package |
| 179 | packageProfit | `String` | Package Profit code for a particular Package |
| 180 | passerbyMarket | `String` | Market code for passerby |
| 181 | passerbySource | `String` | Source code for passerby |
| 182 | path | `String` | Path |
| 183 | pathId | `Float` | This is the value used in Interfaces to map  to a Resort Code. |
| 184 | paymentDate | `Date` | Payment Date |
| 185 | perReservationRoomLimit | `Float` | Future use |
| 186 | postalCode | `String` | Postal Code |
| 187 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 188 | propMapUrl | `String` | Property MAP URL. |
| 189 | propPicUrl | `String` | Property picture URL. |
| 190 | propinfoUrl | `String` | URL where property information is located. |
| 191 | qtyConnectingRooms | `Float` | Number of connecting rooms. |
| 192 | qtyDoubleRooms | `Float` | Number of double rooms. |
| 193 | qtyFamilyRooms | `Float` | Number of family rooms. |
| 194 | qtyGuestElevators | `Float` | Number of guest elevators. |
| 195 | qtyGuestRoomFloors | `Float` | Total of guest rooms floors. |
| 196 | qtyHandicappedRooms | `Float` | Number of handicapped rooms. |
| 197 | qtyNonSmokingRooms | `Float` | Number of non smoking rooms. |
| 198 | qtySingleRooms | `Float` | Number of single rooms. |
| 199 | qtySuites | `Float` | Number of suites. |
| 200 | qtyTwinRooms | `Float` | Number of twin rooms. |
| 201 | quotedCurrency | `String` | Future use |
| 202 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 203 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 204 | reconcileDate | `Date` | Records the date on which the reconciliation is done |
| 205 | regionCode | `String` | Region Code |
| 206 | resortType | `String` | Property Type |
| 207 | restaurant | `Float` | Future use |
| 208 | rhythmSheets | `Float` | Total number of Sheets |
| 209 | rhythmTowels | `Float` | Total number of Towels |
| 210 | roomAmenity | `String` | Room amenity. |
| 211 | saveProfiles | `Float` | To store number of days before deleting the gest profile |
| 212 | scriptId | `Float` | Script ID |
| 213 | season1 | `String` | Future use |
| 214 | season2 | `String` | Future use |
| 215 | season3 | `String` | Future use |
| 216 | season4 | `String` | Future use |
| 217 | season5 | `String` | Future use |
| 218 | sendLeadAsBookingYn | `String` | Indicates that the property accepts leads as bookings. |
| 219 | sglNum | `String` | Future use |
| 220 | sglRate1 | `Float` | Future use |
| 221 | sglRate2 | `Float` | Future use |
| 222 | shopDescription | `String` | Shop description. |
| 223 | shortDateFormat | `String` | Short date format for the property. |
| 224 | sourceCommission | `String` | For default commission percentage |
| 225 | state | `String` | State |
| 226 | street | `String` | The street of the property. |
| 227 | suiNum | `String` | Future use |
| 228 | suiRate1 | `Float` | Future use |
| 229 | suiRate2 | `Float` | Future use |
| 230 | summCurrencyCode | `String` | Internal |
| 231 | taCommission | `String` | For default commission percentage |
| 232 | telephone | `String` | The direct dial phone number of this property |
| 233 | telephoneNoFormat | `String` | Formats for telephone number |
| 234 | thousandSeparator | `String` | Separator for monetory values |
| 235 | timeFormat | `String` | Default time format for the property. |
| 236 | timeZone | `String` | Time zone region selected by the employee. |
| 237 | tollFree | `String` | Toll free telephone number. |
| 238 | totalRooms | `Float` | Future use |
| 239 | touristNumber | `String` | Tourist Number |
| 240 | tplNum | `String` | Future use |
| 241 | tplRate1 | `Float` | Future use |
| 242 | tplRate2 | `Float` | Future use |
| 243 | translateMulticharYn | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| 244 | turnawayCode | `String` | Turnaway Code |
| 245 | updateDate | `DateTime` | Update Date |
| 246 | updateUser | `Float` | Update User |
| 247 | vatId | `String` | VAT ID of this property. |
| 248 | videoCoStart | `Date` | Video check out start time. |
| 249 | videoCoStop | `Date` | Video check out end time. |
| 250 | videocheckoutPrinter | `String` | Future use |
| 251 | wakeUpDelay | `Float` | Future use |
| 252 | warningAmount | `Float` | Amount at which warning is raised. |
| 253 | webaddress | `String` | Webaddress of the property |
| 254 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 255 | xresortNumber | `Float` | Numbers (1 thru 10) given to the resorts in the schema to print the tax collected by that resort in the gstfolio when proper merge codes are selected. |
| 256 | zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### ConfigurationChainNoteTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | defaultNoteText | `String` | Stores the default note text. |
| 5 | defaultNoteTextYN | `String` | Specifies if the note type has default note to be populated when selected. |
| 6 | defaultNoteTypeYN | `String` | Default Note Type YN |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | deptNoteYn | `String` | Indicate if the note is for departments. |
| 9 | globalYn | `String` | Global Y/N |
| 10 | helpText | `String` | Hel text for notes. |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | inactiveflag | `String` | Inactive Flag |
| 13 | internalDeletedflag | `String` | Deleted Flag |
| 14 | internalYN | `String` | Internal YN |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | noteClass | `String` | User defined note class. |
| 18 | noteType | `String` | Note Type |
| 19 | noteTypeCode | `String` | Note Type Code |
| 20 | noteTypeDescription | `String` | Note Type Description |
| 21 | notesGroup | `String` | Notes Group |
| 22 | notetypeid | `String` | Notetypeid |
| 23 | notetypepmsref | `String` | Notetypepmsref |
| 24 | notificationAreas | `String` | Comma separated list of areas where this notification will be shown. Possible values are 'PROFILE' 'CHECK IN' 'RESERVATION' 'CHECK OUT' 'NEVER'. |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | overrideInternalYN | `String` | Changing internal_yn is allowed for Y and changing internal_yn is not allowed for N while creating/modifying notes. |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | protectDescriptionYn | `String` | Indicates whether the description can be modified by the user or not |
| 29 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 30 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 31 | sequence | `Float` | Sequence |
| 32 | webProposalYn | `String` | Determines if notes of this note type will be included in the webProposal XML. |

[⬆ Back to Query](#query)

---

### ConfigurationChainPropertyTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralCode | `String` | Central Code |
| 2 | centralDescription | `String` | Central Description |
| 3 | centralSequence | `Float` | Central Sequence |
| 4 | chainCode | `String` | Chain Code |
| 5 | code | `String` | Code |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | repItem | `String` | Reporting Item |
| 18 | repItemName | `String` | Reporting Item Name |
| 19 | repItemOrderby | `Float` | Reporting Item Orderby |
| 20 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 21 | sequence | `Float` | Sequence |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainForeignCurrencyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | abbreviation | `String` | Abbreviation |
| 2 | activeYN | `String` | Active YN |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | chainCode | `String` | Chain Code |
| 5 | currencyActionId | `Float` | Curr Action ID |
| 6 | currencyCode | `String` | Currency Code |
| 7 | currencyDescription | `String` | Currency Description |
| 8 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | decimals | `Float` | Decimals |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | foreignCurrencyID | `String` | Foreign Currency ID |
| 13 | formatMask | `String` | Format Mask |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | internalDeletedflag | `String` | Deleted Flag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | mobileYn | `String` | Indicates if this Currency Exchange Rate is available for consumer mobility. |
| 22 | multiply | `Float` | Multiply |
| 23 | orderBy | `Float` | Order By |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | previousLocalCurrencyYn | `String` | This will be significant after EURO conversion. The currency before the Euro conversion gets a value Y. |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | sellCurrency | `String` | Indicates whether this currency code can be sold though currency exchange. |
| 30 | trianMethodYn | `String` | Indicates whether the currency is Euro participant. |
| 31 | updateDate | `DateTime` | Update Date |
| 32 | updateUser | `Float` | Update User |
| 33 | usedForCcPaymentsYn | `String` | Indicates if this currency can be used for Credit Card payments. |

[⬆ Back to Query](#query)

---

### ConfigurationChainItemRateRulesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralDescription | `String` | Central Description |
| 2 | centralSequence | `Float` | Central Sequence |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | codeId | `Float` | Code ID |
| 6 | codeType | `String` | Code Type |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | description | `String` | Description |
| 10 | displayYn | `String` | Display Y/N |
| 11 | fulldayYn | `String` | Specifies that the space is not available for this setup style for the entire day. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | repItem | `String` | Reporting Item |
| 20 | repItemName | `String` | Reporting Item Name |
| 21 | repItemOrderby | `Float` | Reporting Item Orderby |
| 22 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 23 | reportingCodeId | `String` | Rep Code ID |
| 24 | sequence | `Float` | Sequence |
| 25 | webBookingYn | `String` | Web Booking Y/N |
| 26 | webSetdown | `Float` | Setdown Time for web bookings. |
| 27 | webSetup | `Float` | Setup Time for web bookings. |

[⬆ Back to Query](#query)

---

### ConfigurationChainPostalCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | city | `String` | City |
| 3 | country | `String` | Country |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 7 | description | `String` | Description |
| 8 | district | `String` | District |
| 9 | fiscalRegion | `String` | Fiscal Region |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | postalCodeFrom | `String` | The Beginning Postal Code Range for this state. |
| 16 | postalCodeTo | `String` | The ending Postal Code for the State. |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | regionCode | `String` | Region Code |
| 21 | scity | `String` | Uppercase value of CITY column. |
| 22 | seq | `Float` | Sequence |
| 23 | state | `String` | State |
| 24 | territory | `String` | Territory code related to this Postal Code. |
| 25 | updateDate | `DateTime` | Update Date |
| 26 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainIDDocumentTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | checkForDuplicatesYn | `String` | Check for Duplicates flag. |
| 3 | code | `String` | Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | iDRole | `String` | Possible values are: PASSPORT DRIVER_LICENSE VISA ID UNKNOWN or NULL. |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | sequence | `Float` | Sequence |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainLanguageDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description for each language code. |
| 6 | enrollmentAltYn | `String` | Indicates if this language is a valid Alternate Language for Enrollment / Lookup. |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | locale | `String` | Specific geographic political or cultural region (used in the OperaXMLP Java servlet for translation and formatting) |
| 10 | nativeWritingSystem | `String` | Type of characters that this language uses i.e.: LATIN ARABIC CYRILLIC CHINESE_CANTONESE or CHINESE_MANDARIN. |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | preferredLanguageAdV5 | `String` | Preferred Language for Return Addresses. Used for Address Cleansing using AddressDoctor V5. |
| 13 | preferredScriptAdV5 | `String` | Character set used for the returned address. Used for Address Cleansing using AddressDoctor V5. |
| 14 | preferredlanguage | `String` | Language of the Returned address. |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | reportDateLanguage | `String` | NLS_DATE_LANGUAGE code used in Reports |
| 19 | translationLanguage | `String` | ISO Country code |

[⬆ Back to Query](#query)

---

### ConfigurationChainRegionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedflag | `String` | Deleted Flag |
| 5 | inactiveflag | `String` | Inactive Flag |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | regionDescription | `String` | Region Description |
| 13 | regionid | `String` | Regionid |
| 14 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 15 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 16 | sequence | `Float` | Sequence |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainStateDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | country | `String` | Country |
| 4 | countryid | `String` | Countryid |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedflag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveflag | `String` | Inactive Flag |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | repDescription | `String` | Reporting Description |
| 17 | repItem | `String` | Reporting Item |
| 18 | repItemName | `String` | Reporting Item Name |
| 19 | repItemOrderby | `Float` | Reporting Item Orderby |
| 20 | repOrderBy | `Float` | Reporting Order By |
| 21 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 22 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 23 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 24 | sequence | `Float` | Sequence |
| 25 | stateCode | `String` | State Code |
| 26 | stateid | `String` | Stateid |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipClassDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Primary key of this table |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | frequentFlyerYN | `String` | Frequent Flyer YN |
| 7 | inactiveflag | `Float` | Inactive Flag |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | internalDeletedflag | `String` | Deleted Flag |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | loyaltyProgramYN | `String` | Loyalty Program YN |
| 14 | membershipclassid | `String` | Membershipclassid |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 18 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 19 | sequence | `Float` | Sequence |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainConfirmationFormatDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | code | `String` | Primary key column for the table |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | formatDefinition | `String` | The format definition which includes the elements of address. |
| 8 | formatType | `String` | Format Type |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | salesAddressFormatYN | `String` | Sales Address Format YN |
| 19 | sequence | `Float` | Sequence |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainCommunicationTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | role | `String` | Role |
| 15 | sequence | `Float` | Sequence |
| 16 | textMessagingEnabledYN | `String` | Indicate if SMS text messages can be send via this communication type. |
| 17 | type | `String` | Type |
| 18 | updateDate | `DateTime` | Update Date |
| 19 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainProfilePreferenceTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowSubTypesYn | `String` | Indicates if Sub Types are allowed. |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | insertDate | `DateTime` | Insert Date |
| 12 | insertUser | `Float` | Insert User |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | quantity | `Float` | Maximum quantity of preferences which can be selected for this preference type. |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | repItem | `String` | Reporting Item |
| 21 | repItemName | `String` | Reporting Item Name |
| 22 | repItemOrderby | `Float` | Reporting Item Orderby |
| 23 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 24 | reservationYN | `String` | Indicator whether this preference type can be used in reservations. |
| 25 | sequence | `Float` | Sequence |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainProfileProfileDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | insertDate | `DateTime` | Insert Date |
| 5 | insertUser | `Float` | Insert User |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | name | `String` | Set of words that represent a profile name. |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | type | `String` | Type |
| 14 | updateDate | `DateTime` | Update Date |
| 15 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainConfigurationRelationshipDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | fromDescription | `String` | From Description |
| 6 | fromRelationshipCode | `String` | From Relationship Code |
| 7 | fromRelationshipType | `String` | From Relationship Type. |
| 8 | globalYn | `String` | Global Y/N |
| 9 | hasHierarchyYN | `String` | Has Hierarchy YN |
| 10 | ignoreProtectionYn | `String` | Indicates if custom profile protection is not applicable for this relationship type. |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | inactiveFlag | `String` | Inactive Flag |
| 13 | individualflag | `String` | Individualflag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalInactiveflag | `String` | Inactive Flag |
| 17 | internalOrganizationId | `Float` | Organization ID |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | primaryflag | `String` | Primaryflag |
| 23 | rate | `String` | Rate |
| 24 | relationCategory | `String` | Module related to this Name Type whether it is used in PMS S&C etc. |
| 25 | relationshipId | `String` | Relationship ID |
| 26 | relationshipRole | `String` | Used in S&C Module |
| 27 | relationshippms | `String` | Relationshippms |
| 28 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 29 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 30 | tempFlag | `String` | Temp Flag |
| 31 | toDescription | `String` | Description of the To Relationship. |
| 32 | toRelationshipCode | `String` | To Relationship type. |
| 33 | toRelationshipType | `String` | To Relationship Type |
| 34 | toindividualflag | `String` | Toindividualflag |
| 35 | toinheritratesflag | `String` | Toinheritratesflag |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipClaimTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | claimTypeCode | `String` | Claim Type Code |
| 5 | claimTypeDescription | `String` | Claim Type Description |
| 6 | comments | `String` | Comments |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipAwardsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | autoConsumeYn | `String` | Indicates if award consumtion is tracked  by the system. If value is Y then system keeps a track of availability of award after it is issued. |
| 2 | awardBasedOn | `String` | Indicates if the Award is a Stay Pkg Element or other. |
| 3 | awardBasedOnDesc | `String` | Award Based On Desc |
| 4 | awardCode | `String` | Award Code |
| 5 | awardDescription | `String` | Award Description |
| 6 | awardQuantity | `Float` | Enter a number to indicate the number of awards to be given. |
| 7 | awardValue | `Float` | Value of the award in central currency. |
| 8 | billingGroup | `String` | Billing Group |
| 9 | cAwardValue | `Float` | Central Award Value |
| 10 | cExchangeDate | `Date` | Central Xchange Date |
| 11 | cExchangeRate | `Float` | Central Xchange Rate |
| 12 | cancelPenaltyChargePoints | `Float` | Number points deducted is award is cancelled. |
| 13 | cancelPenaltyDays | `Float` | Number days before arrival to apply penalty for cancellation. |
| 14 | cancelPenaltyType | `String` | Cancel Penalty Type |
| 15 | cancelPolicyType | `String` | Cancel Policy Type |
| 16 | chainCode | `String` | Chain Code |
| 17 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 18 | deletedFlag | `String` | Deleted Flag |
| 19 | displaySet | `String` | Display Set |
| 20 | endSellDate | `Date` | End Sell Date |
| 21 | exchangeRateType | `String` | Exchange Rate Type |
| 22 | forceVerificationYn | `String` | Force verification whether Rate or Product for the Award is valid at reservation. |
| 23 | ignoreFtTransactionYN | `String` | This column identify that should we ignore Financial transactions in OPERA or not? Y -  Financial transaction is not required in OPERA while giving award as it may be recorded in some external system and only points accounting is done in OCIS. |
| 24 | inactiveDate | `Date` | Inactive Date |
| 25 | inactiveYN | `String` | Inactive YN |
| 26 | insertDate | `DateTime` | Insert Date |
| 27 | insertUser | `Float` | Insert User |
| 28 | jRNUpdateDate | `Date` | JRN Update Date |
| 29 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 30 | label | `String` | Label |
| 31 | maxPercentAllowed | `Float` | Max percent of total value to be allowed to convert money to points. |
| 32 | membershipLevel | `String` | Membership Level |
| 33 | membershipType | `String` | Membership Type |
| 34 | messageLine1 | `String` | Message for Other awards. |
| 35 | messageLine2 | `String` | Message for Other awards. |
| 36 | messageLine3 | `String` | Message for Other awards. |
| 37 | messageLine4 | `String` | Message for Other awards. |
| 38 | nightsYN | `String` | Nights YN |
| 39 | numberOfNights | `Float` | Number of Nights |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | pointsRequired | `Float` | Points Required |
| 42 | pointsRequiredDesc | `Float` | Points Required Desc |
| 43 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 44 | ptsSchCode | `String` | Pts Sch Code |
| 45 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 46 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 47 | roomCategoryGroupYN | `String` | Indicates if the membership award upgrade is based on room category (N) or room category group (Y). |
| 48 | sequence | `Float` | Sequence |
| 49 | startSellDate | `Date` | Start Sell Date |
| 50 | updateDate | `DateTime` | Update Date |
| 51 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attachedEnrollmentCode | `String` | Code to indicate source used to enroll the member. |
| 2 | attachedEnrollmentDescription | `String` | Attached Enrollment Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | inactiveflag | `String` | Inactive Flag |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | internalDeletedflag | `String` | Deleted Flag |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | memEnrollGroup | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| 14 | membershipenrollid | `String` | Membershipenrollid |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 18 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 19 | updateDate | `DateTime` | Update Date |
| 20 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipLevelDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | autoRenewalAfter | `String` | Auto-Renewal After |
| 2 | centralVIPCode | `String` | Central VIP Code |
| 3 | centralVIPCodeDescription | `String` | Central VIP Code Description |
| 4 | chainCode | `String` | Chain Code |
| 5 | changesRestrictedYN | `String` | Indicates whether a change to this level is restricted once a guest attains this level. |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | displayColorCode | `String` | Display Color Code |
| 9 | displayColorDescription | `String` | Display Color Description |
| 10 | doubleDippingYN | `String` | Double Dipping YN |
| 11 | expiryPeriod | `Float` | Number of years card will be valid for this level. |
| 12 | fulfillmentYN | `String` | Fulfillment YN |
| 13 | inactiveDate | `DateTime` | Inactive Date |
| 14 | inactiveYN | `String` | Inactive YN |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | internalDeletedflag | `String` | Deleted Flag |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | label | `String` | Label |
| 21 | levelCode | `String` | Level Code |
| 22 | maxDowngradeLevel | `String` | Used in EIS Module. |
| 23 | maxDowngradeLevelDescription | `String` | Max. Downgrade Level Description |
| 24 | membershipType | `String` | Membership Type |
| 25 | membershiplevelid | `String` | Membershiplevelid |
| 26 | membershiplevelpmsref | `String` | Membershiplevelpmsref |
| 27 | membershiptypeid | `String` | Membershiptypeid |
| 28 | numberOfTrx | `Float` | Number of transaction(s) for each stay. Value will be 2 in case of double dipping otherwise it will be null or 1. |
| 29 | orderBy | `Float` | Order By |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 32 | rank | `Float` | The sequence of membership levels starting with 1 (The starting level) and increasing to the highest level. |
| 33 | renewCardOnStayYN | `String` | Renew Card on Stay YN |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |
| 38 | vIPCode | `String` | VIP Code |
| 39 | vIPCodeDescription | `String` | VIP Code Description |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipCardRangesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cardRangeFrom | `String` | Start range of credit card no |
| 2 | cardRangeTo | `String` | End range of credit card no |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | membershipType | `String` | Membership Type |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 15 | updateDate | `DateTime` | Update Date |
| 16 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipLevelBenefitsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | fromDate | `Date` | From Date |
| 5 | inactiveDate | `Date` | Inactive Date |
| 6 | inactiveYN | `String` | Inactive YN |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | levelCode | `String` | Link to benefit code. |
| 12 | levelDescription | `String` | Level Description |
| 13 | membershipType | `String` | Membership Type |
| 14 | minimumMembershipLevel | `String` | Min value for membership level. This is the minumum membership level member gets for enrolling into this program. |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | toDate | `Date` | To Date |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attachedMarketCodes | `String` | Attached Market Codes |
| 2 | attachedMarketDescription | `String` | Attached Market Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | memMarketGroup | `String` | Membership Market Group |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRateGroupCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attachedRateCode | `String` | Attached Rate Code |
| 2 | attachedRateCodeDescription | `String` | Attached Rate Code Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | inactiveDate | `Date` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | memRateGroup | `String` | Membership Rate Group |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueGroupCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attachedRevenueGroupCode | `String` | Revenue Types defined for OIS memberships. |
| 2 | attachedRevenueGroupDescription | `String` | Attached Revenue Group Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | memRevenueGroup | `String` | Membership rate group. |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | updateDate | `DateTime` | Update Date |
| 17 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainPropertyBookingStatusNextDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralCode | `String` | Central Code |
| 2 | centralDescription | `String` | Central Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Next status of the status column |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | displayColor | `String` | Display Color |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | orderBy | `Float` | Order By |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | status | `String` | Status |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

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

### ConfigurationChainQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| chainDetailsChainCode | `StringInput!` | Chain<br>`@mandatoryInput` |
| chainDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| chainDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| chainDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memenrollmentcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memenrollmentcodeDetailsAttributeCode | `StringInput` | Enrollment Code |
| memenrollmentcodeDetailsEntityName | `StringInput` | Entity Name |
| memenrollmentcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memenrollmentcodeDetailsLanguageCode | `StringInput` | Language Code |
| memenrollmentcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memenrollmentcodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| memenrollgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memenrollgroupDetailsMemEnrollGroup | `StringInput` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| memenrollgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memenrollgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memmarketgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memmarketgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memmarketgroupDetailsMemMarketGroup | `StringInput` | Market Group Code |
| memmarketgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershiptypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptypeDetailsMembershiptypeid | `StringInput` | Membershiptypeid |
| membershiptypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptypeDetailsMembershipType | `StringInput` | Type |
| memresortgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memresortgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memresortgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memresortgroupDetailsMemResortGroup | `StringInput` | Property Group Code |
| memrategroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memrevenuegroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memrevenuegroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memrevenuegroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memrevenuegroupDetailsMemRevenueGroup | `StringInput` | Membership rate group. |
| memrevenuetypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memrevenuetypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memrevenuetypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memrevenuetypeDetailsExportBucketCode | `StringInput` | Revenue Bucket Code |
| memrevenuetypeDetailsMembershipRevenueType | `StringInput` | Revenue Types defined for OIS memberships. |
| memroomgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memroomgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memroomgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memroomgroupDetailsMemRoomGroup | `StringInput` | Room Group Code |
| hubDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| hubDetailsCrsResort | `StringInput` | Not used |
| hubDetailsCountryCode | `StringInput` | Country |
| hubDetailsCurrencyCode | `StringInput` | Currency |
| hubDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| hubDetailsResort | `StringInput` | HUB |
| hubDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hubDetailsNameIdLink | `FloatInput` | Internal |
| hubDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| hubDetailsResortType | `StringInput` | Property Type |
| notetypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| notetypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| notetypeDetailsNoteCode | `StringInput` | Note Type |
| notetypeDetailsNoteTypeCode | `StringInput` | Note Type Code |
| notetypeDetailsNoteType | `StringInput` | Notes Group |
| notetypeDetailsNotetypeid | `StringInput` | Notetypeid |
| notetypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resorttypeDetailsResortType | `StringInput` | Code |
| resorttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resorttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resorttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foreigncurrencyDetailsCurrencyCode | `StringInput` | Currency Code |
| foreigncurrencyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foreigncurrencyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foreigncurrencyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| itemraterulesDetailsCode | `StringInput` | Code |
| itemraterulesDetailsCodeId | `FloatInput` | Code ID |
| itemraterulesDetailsCodeType | `StringInput` | Code Type |
| itemraterulesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| itemraterulesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| itemraterulesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| postalcodeDetailsCountryCode | `StringInput` | Country |
| postalcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| postalcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| postalcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| postalcodeDetailsPostalCodeFrom | `StringInput` | The Beginning Postal Code Range for this state. |
| postalcodeDetailsPostalCodeTo | `StringInput` | The ending Postal Code for the State. |
| postalcodeDetailsScity | `StringInput` | Uppercase value of CITY column. |
| postalcodeDetailsSeq | `FloatInput` | Sequence |
| postalcodeDetailsStateCode | `StringInput` | State |
| iddocumenttypeDetailsDocumentType | `StringInput` | Code |
| iddocumenttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| iddocumenttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| iddocumenttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| languageDetailsLanguageCode | `StringInput` | Code |
| languageDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| languageDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| languageDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| languageDetailsTranslationLanguageCode | `StringInput` | ISO Country code |
| regionDetailsRegionCode | `StringInput` | Code |
| regionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| regionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| regionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| regionDetailsRegionid | `StringInput` | Regionid |
| stateDetailsStateCode | `StringInput` | Code |
| stateDetailsCountryCode | `StringInput` | Country |
| stateDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| stateDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| stateDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| stateDetailsStateid | `StringInput` | Stateid |
| membershipclassDetailsMembershipClass | `StringInput` | Primary key of this table |
| membershipclassDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershipclassDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipclassDetailsMembershipclassid | `StringInput` | Membershipclassid |
| membershipclassDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| confirmationformatDetailsChainCode | `StringInput` | Chain Code |
| confirmationformatDetailsFormatCode | `StringInput` | Primary key column for the table |
| confirmationformatDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| confirmationformatDetailsFormatType | `StringInput` | Format Type |
| confirmationformatDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| confirmationformatDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| communicationtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| communicationtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| communicationtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| communicationtypeDetailsPhoneType | `StringInput` | Type |
| profilepreferencetypeDetailsPreferenceType | `StringInput` | Code |
| profilepreferencetypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilepreferencetypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilepreferencetypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilenameDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilenameDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilenameDetailsNameString | `StringInput` | Set of words that represent a profile name. |
| profilenameDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilenameDetailsNameType | `StringInput` | Type |
| configrelationshipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| configrelationshipDetailsRelationship | `StringInput` | From Relationship Code |
| configrelationshipDetailsOrganizationId | `FloatInput` | Organization ID |
| configrelationshipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| configrelationshipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| configrelationshipDetailsRelationCategory | `StringInput` | Module related to this Name Type whether it is used in PMS S&C etc. |
| configrelationshipDetailsRelationshipId | `StringInput` | Relationship ID |
| memclaimtypeDetailsAttributeCode | `StringInput` | Claim Type Code |
| memclaimtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memclaimtypeDetailsEntityName | `StringInput` | Entity Name |
| memclaimtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memclaimtypeDetailsLanguageCode | `StringInput` | Language Code |
| memclaimtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memclaimtypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| memawardsDetailsAwardType | `StringInput` | Award Code |
| memawardsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memawardsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memawardsDetailsMembershipType | `StringInput` | Membership Type |
| memawardsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memawardsDetailsPtsSchCode | `StringInput` | Pts Sch Code |
| membershipenrollDetailsEnrollmentCode | `StringInput` | Code to indicate source used to enroll the member. |
| membershipenrollDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershipenrollDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipenrollDetailsMemEnrollGroup | `StringInput` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| membershipenrollDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiplevelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershiplevelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiplevelDetailsMembershipLevel | `StringInput` | Level Code |
| membershiplevelDetailsMembershipType | `StringInput` | Membership Type |
| membershiplevelDetailsMembershiplevelid | `StringInput` | Membershiplevelid |
| membershiplevelDetailsMembershiptypeid | `StringInput` | Membershiptypeid |
| membershiplevelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memcardrangesDetailsCardnoFrom | `StringInput` | Start range of credit card no |
| memcardrangesDetailsCardnoTo | `StringInput` | End range of credit card no |
| memcardrangesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memcardrangesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memcardrangesDetailsMembershipType | `StringInput` | Membership Type |
| memcardrangesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memlevelbenefitsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memlevelbenefitsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memlevelbenefitsDetailsBenefitCode | `StringInput` | Link to benefit code. |
| memlevelbenefitsDetailsMembershipType | `StringInput` | Membership Type |
| memlevelbenefitsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memmarketgroupcodeDetailsMarketCode | `StringInput` | Attached Market Codes |
| memmarketgroupcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memmarketgroupcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memmarketgroupcodeDetailsMemMarketGroup | `StringInput` | Membership Market Group |
| memmarketgroupcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memrategroupcodeDetailsRateCode | `StringInput` | Attached Rate Code |
| memrategroupcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memrategroupcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memrategroupcodeDetailsMemRateGroup | `StringInput` | Membership Rate Group |
| memrategroupcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memrevenuegroupcodeDetailsMembershipRevenueType | `StringInput` | Revenue Types defined for OIS memberships. |
| memrevenuegroupcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memrevenuegroupcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memrevenuegroupcodeDetailsMemRevenueGroup | `StringInput` | Membership rate group. |
| memrevenuegroupcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortbookingstatusnextDetailsNextStatus | `StringInput` | Next status of the status column |
| resortbookingstatusnextDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortbookingstatusnextDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortbookingstatusnextDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortbookingstatusnextDetailsStatus | `StringInput` | Status |
#### Validation Rules

**`mandatoryInput`**
- chainDetailsChainCode


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query configurationChain($input: ConfigurationChainQueryArgumentsType!) {
  configurationChain(input: $input) @stream {
    chainDetails {
      aspYn
      beginDate
      bookingConditions
      centralChain
      centralDescription
      chain
      chainName
      dSI
      deletedFlag
      description
      endDate
      frequentFlierCardsAcceptYn
      hoCity
      hoCountry
      hoEmail
      hoFax
      hoPostCode
      hoState
      hoStreet
      hoTelephone
      imgChainId
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      logoFileName
      loyaltyProgram
      marketingText
      nameId
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      scriptId
      shareProfilesYN
      updateDate
      updateUser
    }
    membershipEnrollmentCodeDetails {
      businessTitle
      canDeleteYn
      chainCode
      comments
      dSI
      deletedflag
      displayColor
      enrollmentCode
      enrollmentDescription
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    membershipEnrollGroupDetails {
      chainCode
      dSI
      deletedFlag
      enrollmentGroupCode
      enrollmentGroupDescription
      includeExclude
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    membershipMarketGroupMembershipMarketGroupDetails {
      chainCode
      dSI
      deletedFlag
      includeExclude
      rNAInsertDate
      rNAUpdateDate
    }
    membershipMarketGroupDetails {
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketGroupCode
      marketGroupDescription
      organizationID
      primaryKeyID
      sequence
      updateDate
      updateUser
    }
    membershipTypeDetails {
      activeYN
      activityPeriodYears
      allowAdhocMultiplierYn
      allowDuplicateCardNumbersYN
      allowSharesYn
      alternateNameProtectedYN
      autoCardNoBasedOn
      autoGenCardPrefix
      autoPopulateNumberFromNameYN
      awardGenerationMethod
      awardPointExpiryDateYears
      awardRedeemThreshold
      basedOn
      bookerProgramYn
      cCostPerPoint
      cExchangeDate
      cExchangeRate
      calculationMethod
      calculationMonths
      calculationPeriod
      canDeleteYn
      cardLength
      cardPrefix
      cardValidYears
      centrallyManagedYN
      chainCode
      checkInYN
      checkOutYN
      chipAndPinYn
      class
      costPerPoint
      currencyCode
      dSI
      defaultMemberStatus
      delayInDays
      deletedFlag
      description
      downgradePeriod
      downgradePeriodYr
      downgradeRenewalYN
      enrollcoderequiredflag
      enrollmentCodeRequiredYN
      exceptionType
      exchangeRateType
      excludeProfileFromPurgeYN
      expirationDateRequiredYN
      expirationMonth
      expiryPeriod
      externalDatabase
      externalProcessDays
      externallyControlledYN
      folioMessageCredits
      folioMessageNonmembers
      folioMessageNonmembersNq
      folioMessageNq
      foreignCurrencyID
      format
      fromSequenceNumber
      fulfillmentYN
      graceExpirationMonth
      gracePeriodYears
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      levelRequiredYN
      memberFolioMessage
      memberInfoDispSet
      membershipAction
      membershipActionDetails
      membershipclassid
      membershiptypeid
      multipleRoomsLimit
      nameProtectedYN
      nameOnCardFromAltNameYN
      newReservationYN
      numericValidation
      organizationID
      pointsCalculationMethod
      pointsIssuedCentrallyYn
      pointsLabel
      primaryKeyID
      primaryYN
      printFolioMessageOnConfirmationYN
      promptatcheckinflag
      randomGenerationYN
      rank
      requalifyOnUpgradeYN
      requiredOnStayPeriodYN
      rnaInsertDate
      rnaUpdateDate
      rule
      saveCardNumberHistoryYN
      sendChkoutToIfc
      sendcheckouttoifcflag
      sequence
      tierExpirationMonth
      tierManagementResetYN
      toSequenceNumber
      transactionMaxPoints
      tscDateFlag
      type
      udfCardValidationYn
      udfFormula
      updateDate
      updateReservationYN
      updateUser
      upgradePeriod
      upgradePeriodYr
      validationByIfc
      validationRule
      validationbyifcflag
      yearsToExpire
    }
    membershipPropertyGroupDetails {
      backToBack
      chainCode
      dSI
      deletedFlag
      includeExclude
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      propertyGroupCode
      propertyGroupDescription
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    membershipRateGroupDetails {
      chainCode
      dSI
      deletedFlag
      includeExclude
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      rateGroupCode
      rateGroupDescription
      sequence
      updateDate
      updateUser
    }
    membershipRevenueGroupDetails {
      chainCode
      dSI
      deletedFlag
      includeExclude
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      revenueGroupCode
      revenueGroupDescription
      sequence
      updateDate
      updateUser
    }
    membershipRevenueTypeDetails {
      chainCode
      dSI
      deletedFlag
      frequentFlyerPoints
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      membershipPoints
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      revenueBucketCode
      revenueBucketDescription
      revenueTypeCode
      revenueTypeDescription
      sequence
      tierPoints
      updateDate
      updateUser
    }
    membershipRoomGroupDetails {
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      roomGroupCode
      roomGroupDescription
      roomTypes
      sequence
      updateDate
      updateUser
    }
    hubDetails {
      aRAccountNumberMandYN
      aRBalanceTrxCode
      aRCreditTrxCode
      accessCode
      address
      agingLevel1
      agingLevel2
      agingLevel3
      agingLevel4
      agingLevel5
      airport
      airportDistance
      airportTime
      allowLoginYn
      allowancePeriodAdj
      arAccountNumberFormat
      arAgent
      arCompany
      arGroups
      arIndividuals
      arSettleCode
      arTypewriter
      awardsTimeout
      baseLanguage
      beginDate
      blackoutPeriodNotes
      block
      brArea
      brSeats
      brandCode
      budgetMonth
      cCreditLimit
      cDoubleRate2
      cDoubleRate1
      cExchangeDate
      cExchangeRate
      cSglRate2
      cSglRate1
      cSuiRate2
      cSuiRate1
      cTplRate2
      cTplRate1
      cWarningAmount
      cRSResort
      cashShiftDrop
      cateringCurrencyCode
      cateringCurrencyFormat
      chainCode
      checkExgPaidout
      checkInTime
      checkOutTime
      checkShiftDrop
      checkTrxcode
      city
      comAddress
      comMethod
      comNameXrefId
      companyAddressType
      companyPhoneType
      configurationMode
      confirmRegcardPrinter
      copies
      country
      creditLimit
      croCode
      currency
      currencyDecimals
      currencyExgPaidout
      currencyFormat
      currencySymbol
      curtainColor
      dSI
      dateForAging
      dateSeparator
      dblNum
      dblRate2
      dblRate1
      decimalPlaces
      decimalSeparator
      defaultCommissionPercentage
      defaultFaxType
      defaultFolioStyle
      defaultGroupsRateCode
      defaultGuestAddress
      defaultMembershipType
      defaultPostingRoom
      defaultPrepaidComm
      defaultPrinter
      defaultRateCode
      defaultRatecodePcr
      defaultRatecodeRack
      defaultRegistrationCard
      defaultReservationType
      defaultTrxCommissionCode
      deletedFlag
      depositLedgerTrxCode
      destinationId
      dfltPkgTranCode
      dfltTranCodeRateCode
      directions
      dirsales
      disableLoginYn
      downloadRestYn
      dutyManagerPager
      email
      endDate
      exchangePostingType
      expHotelCode
      expiryDate
      extExpFileLocation
      extPropertyCode
      externalScYn
      fax
      faxNoFormat
      fileTransferFormat
      fiscalEndDate
      fiscalPeriodType
      fiscalStartDate
      flags
      floorNumExecutiveFloor
      flowCode
      fnsTier
      folioLanguage1
      folioLanguage2
      folioLanguage3
      folioLanguage4
      font
      genmgr
      groupRoomWarning
      guestLookupTimeout
      hotelCode
      hotelFc
      hotelId
      hotelType
      hub
      imgDirectionId
      imgHotelId
      imgMapId
      inactiveDaysForGuestProfil
      individualAddressType
      individualPhoneType
      individualRoomWarning
      insertDate
      insertUser
      intTaxIncludedYn
      inventoryYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepAvailability
      latitude
      leadsend
      legalOwner
      licenseCode
      longDateFormat
      longStayControl
      longitude
      maxAdultsFamilyRoom
      maxChildrenFamilyRoom
      maxCreditDays
      maxNoNights
      maxOccupancy
      mbsSupportedYn
      meetRooms
      meetSeats
      meetSpace
      meetingFc
      minDaysBet2ReminderLetter
      name
      nameIdLink
      nightAuditCashierId
      notes
      numberBeds
      numberFloors
      numberRooms
      opusCurrencyCode
      organizationID
      ownership
      packageLoss
      packageProfit
      passerbyMarket
      passerbySource
      path
      pathId
      paymentDate
      perReservationRoomLimit
      postalCode
      primaryKeyID
      propMapUrl
      propPicUrl
      propinfoUrl
      qtyConnectingRooms
      qtyDoubleRooms
      qtyFamilyRooms
      qtyGuestElevators
      qtyGuestRoomFloors
      qtyHandicappedRooms
      qtyNonSmokingRooms
      qtySingleRooms
      qtySuites
      qtyTwinRooms
      quotedCurrency
      rNAInsertDate
      rNAUpdateDate
      reconcileDate
      regionCode
      resortType
      restaurant
      rhythmSheets
      rhythmTowels
      roomAmenity
      saveProfiles
      scriptId
      season1
      season2
      season3
      season4
      season5
      sendLeadAsBookingYn
      sglNum
      sglRate1
      sglRate2
      shopDescription
      shortDateFormat
      sourceCommission
      state
      street
      suiNum
      suiRate1
      suiRate2
      summCurrencyCode
      taCommission
      telephone
      telephoneNoFormat
      thousandSeparator
      timeFormat
      timeZone
      tollFree
      totalRooms
      touristNumber
      tplNum
      tplRate1
      tplRate2
      translateMulticharYn
      turnawayCode
      updateDate
      updateUser
      vatId
      videoCoStart
      videoCoStop
      videocheckoutPrinter
      wakeUpDelay
      warningAmount
      webaddress
      weekendDays
      xresortNumber
      zeroInvPurDays
    }
    noteTypeDetails {
      canDeleteYn
      chainCode
      dSI
      defaultNoteText
      defaultNoteTextYN
      defaultNoteTypeYN
      deletedFlag
      deptNoteYn
      globalYn
      helpText
      inactiveDate
      inactiveflag
      internalDeletedflag
      internalYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      noteClass
      noteType
      noteTypeCode
      noteTypeDescription
      notesGroup
      notetypeid
      notetypepmsref
      notificationAreas
      organizationID
      overrideInternalYN
      primaryKeyID
      protectDescriptionYn
      rnaInsertDate
      rnaUpdateDate
      sequence
      webProposalYn
    }
    propertyTypeDetails {
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      updateDate
      updateUser
    }
    foreignCurrencyDetails {
      abbreviation
      activeYN
      canDeleteYn
      chainCode
      currencyActionId
      currencyCode
      currencyDescription
      currencySymbol
      dSI
      decimals
      deletedFlag
      foreignCurrencyID
      formatMask
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      mobileYn
      multiply
      orderBy
      organizationID
      previousLocalCurrencyYn
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      sellCurrency
      trianMethodYn
      updateDate
      updateUser
      usedForCcPaymentsYn
    }
    itemRateRulesDetails {
      centralDescription
      centralSequence
      chainCode
      code
      codeId
      codeType
      dSI
      deletedFlag
      description
      displayYn
      fulldayYn
      inactiveDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reportingCodeId
      sequence
      webBookingYn
      webSetdown
      webSetup
    }
    postalCodeDetails {
      chainCode
      city
      country
      dSI
      deletedFlag
      deletedYn
      description
      district
      fiscalRegion
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      postalCodeFrom
      postalCodeTo
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      regionCode
      scity
      seq
      state
      territory
      updateDate
      updateUser
    }
    iDDocumentTypeDetails {
      chainCode
      checkForDuplicatesYn
      code
      dSI
      deletedFlag
      description
      iDRole
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    languageDetails {
      chainCode
      code
      dSI
      deletedFlag
      description
      enrollmentAltYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      locale
      nativeWritingSystem
      organizationID
      preferredLanguageAdV5
      preferredScriptAdV5
      preferredlanguage
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      reportDateLanguage
      translationLanguage
    }
    regionDetails {
      chainCode
      code
      dSI
      deletedflag
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      regionDescription
      regionid
      rnaInsertDate
      rnaUpdateDate
      sequence
      updateDate
      updateUser
    }
    stateDetails {
      chainCode
      code
      country
      countryid
      dSI
      deletedflag
      description
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      stateCode
      stateid
      updateDate
      updateUser
    }
    membershipClassDetails {
      chainCode
      code
      dSI
      deletedFlag
      description
      frequentFlyerYN
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      loyaltyProgramYN
      membershipclassid
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      sequence
      updateDate
      updateUser
    }
    confirmationFormatDetails {
      canDeleteYn
      chainCode
      code
      dSI
      deletedFlag
      description
      formatDefinition
      formatType
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      salesAddressFormatYN
      sequence
      updateDate
      updateUser
    }
    communicationTypeDetails {
      canDeleteYn
      chainCode
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      role
      sequence
      textMessagingEnabledYN
      type
      updateDate
      updateUser
    }
    profilePreferenceTypeDetails {
      allowSubTypesYn
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      quantity
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reservationYN
      sequence
      updateDate
      updateUser
    }
    profileProfileDetails {
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      name
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      type
      updateDate
      updateUser
    }
    configurationRelationshipDetails {
      canDeleteYn
      chainCode
      dSI
      deletedFlag
      fromDescription
      fromRelationshipCode
      fromRelationshipType
      globalYn
      hasHierarchyYN
      ignoreProtectionYn
      inactiveDate
      inactiveFlag
      individualflag
      insertDate
      insertUser
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      primaryflag
      rate
      relationCategory
      relationshipId
      relationshipRole
      relationshippms
      rnaInsertDate
      rnaUpdateDate
      tempFlag
      toDescription
      toRelationshipCode
      toRelationshipType
      toindividualflag
      toinheritratesflag
      updateDate
      updateUser
    }
    membershipClaimTypeDetails {
      businessTitle
      canDeleteYn
      chainCode
      claimTypeCode
      claimTypeDescription
      comments
      dSI
      deletedflag
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    membershipAwardsDetails {
      autoConsumeYn
      awardBasedOn
      awardBasedOnDesc
      awardCode
      awardDescription
      awardQuantity
      awardValue
      billingGroup
      cAwardValue
      cExchangeDate
      cExchangeRate
      cancelPenaltyChargePoints
      cancelPenaltyDays
      cancelPenaltyType
      cancelPolicyType
      chainCode
      dSI
      deletedFlag
      displaySet
      endSellDate
      exchangeRateType
      forceVerificationYn
      ignoreFtTransactionYN
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      maxPercentAllowed
      membershipLevel
      membershipType
      messageLine1
      messageLine2
      messageLine3
      messageLine4
      nightsYN
      numberOfNights
      organizationID
      pointsRequired
      pointsRequiredDesc
      primaryKeyID
      ptsSchCode
      rNAInsertDate
      rNAUpdateDate
      roomCategoryGroupYN
      sequence
      startSellDate
      updateDate
      updateUser
    }
    membershipEnrollDetails {
      attachedEnrollmentCode
      attachedEnrollmentDescription
      chainCode
      dSI
      deletedFlag
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      memEnrollGroup
      membershipenrollid
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    membershipLevelDetails {
      autoRenewalAfter
      centralVIPCode
      centralVIPCodeDescription
      chainCode
      changesRestrictedYN
      dSI
      deletedFlag
      displayColorCode
      displayColorDescription
      doubleDippingYN
      expiryPeriod
      fulfillmentYN
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      levelCode
      maxDowngradeLevel
      maxDowngradeLevelDescription
      membershipType
      membershiplevelid
      membershiplevelpmsref
      membershiptypeid
      numberOfTrx
      orderBy
      organizationID
      primaryKeyID
      rank
      renewCardOnStayYN
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
      vIPCode
      vIPCodeDescription
    }
    membershipCardRangesDetails {
      cardRangeFrom
      cardRangeTo
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipType
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    membershipLevelBenefitsDetails {
      chainCode
      dSI
      deletedFlag
      fromDate
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      levelCode
      levelDescription
      membershipType
      minimumMembershipLevel
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      toDate
      updateDate
      updateUser
    }
    membershipMarketGroupCodeDetails {
      attachedMarketCodes
      attachedMarketDescription
      chainCode
      dSI
      deletedFlag
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      memMarketGroup
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    membershipRateGroupCodeDetails {
      attachedRateCode
      attachedRateCodeDescription
      chainCode
      dSI
      deletedFlag
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      memRateGroup
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    membershipRevenueGroupCodeDetails {
      attachedRevenueGroupCode
      attachedRevenueGroupDescription
      chainCode
      dSI
      deletedFlag
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      memRevenueGroup
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    propertyBookingStatusNextDetails {
      centralCode
      centralDescription
      chainCode
      code
      dSI
      deletedFlag
      description
      displayColor
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      orderBy
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      status
      updateDate
      updateUser
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
```python
chain_details_schema = {
    'aspYn': pl.Utf8,
    'beginDate': pl.Utf8,
    'bookingConditions': pl.Utf8,
    'centralChain': pl.Utf8,
    'centralDescription': pl.Utf8,
    'chain': pl.Utf8,
    'chainName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'frequentFlierCardsAcceptYn': pl.Utf8,
    'hoCity': pl.Utf8,
    'hoCountry': pl.Utf8,
    'hoEmail': pl.Utf8,
    'hoFax': pl.Utf8,
    'hoPostCode': pl.Utf8,
    'hoState': pl.Utf8,
    'hoStreet': pl.Utf8,
    'hoTelephone': pl.Utf8,
    'imgChainId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'logoFileName': pl.Utf8,
    'loyaltyProgram': pl.Utf8,
    'marketingText': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'scriptId': pl.Float64,
    'shareProfilesYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_enrollment_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayColor': pl.Utf8,
    'enrollmentCode': pl.Utf8,
    'enrollmentDescription': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_enroll_group_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'enrollmentGroupCode': pl.Utf8,
    'enrollmentGroupDescription': pl.Utf8,
    'includeExclude': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_market_group_membership_market_group_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'includeExclude': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
membership_market_group_details_schema = {
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_type_details_schema = {
    'activeYN': pl.Utf8,
    'activityPeriodYears': pl.Utf8,
    'allowAdhocMultiplierYn': pl.Utf8,
    'allowDuplicateCardNumbersYN': pl.Utf8,
    'allowSharesYn': pl.Utf8,
    'alternateNameProtectedYN': pl.Utf8,
    'autoCardNoBasedOn': pl.Utf8,
    'autoGenCardPrefix': pl.Utf8,
    'autoPopulateNumberFromNameYN': pl.Utf8,
    'awardGenerationMethod': pl.Utf8,
    'awardPointExpiryDateYears': pl.Utf8,
    'awardRedeemThreshold': pl.Utf8,
    'basedOn': pl.Utf8,
    'bookerProgramYn': pl.Utf8,
    'cCostPerPoint': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'calculationMethod': pl.Utf8,
    'calculationMonths': pl.Float64,
    'calculationPeriod': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'cardLength': pl.Float64,
    'cardPrefix': pl.Utf8,
    'cardValidYears': pl.Float64,
    'centrallyManagedYN': pl.Utf8,
    'chainCode': pl.Utf8,
    'checkInYN': pl.Utf8,
    'checkOutYN': pl.Utf8,
    'chipAndPinYn': pl.Utf8,
    'class': pl.Utf8,
    'costPerPoint': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'defaultMemberStatus': pl.Utf8,
    'delayInDays': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'downgradePeriod': pl.Float64,
    'downgradePeriodYr': pl.Utf8,
    'downgradeRenewalYN': pl.Utf8,
    'enrollcoderequiredflag': pl.Utf8,
    'enrollmentCodeRequiredYN': pl.Utf8,
    'exceptionType': pl.Utf8,
    'exchangeRateType': pl.Utf8,
    'excludeProfileFromPurgeYN': pl.Utf8,
    'expirationDateRequiredYN': pl.Utf8,
    'expirationMonth': pl.Float64,
    'expiryPeriod': pl.Utf8,
    'externalDatabase': pl.Utf8,
    'externalProcessDays': pl.Float64,
    'externallyControlledYN': pl.Utf8,
    'folioMessageCredits': pl.Utf8,
    'folioMessageNonmembers': pl.Utf8,
    'folioMessageNonmembersNq': pl.Utf8,
    'folioMessageNq': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'format': pl.Utf8,
    'fromSequenceNumber': pl.Float64,
    'fulfillmentYN': pl.Utf8,
    'graceExpirationMonth': pl.Float64,
    'gracePeriodYears': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelRequiredYN': pl.Utf8,
    'memberFolioMessage': pl.Utf8,
    'memberInfoDispSet': pl.Utf8,
    'membershipAction': pl.Utf8,
    'membershipActionDetails': pl.Utf8,
    'membershipclassid': pl.Utf8,
    'membershiptypeid': pl.Utf8,
    'multipleRoomsLimit': pl.Float64,
    'nameProtectedYN': pl.Utf8,
    'nameOnCardFromAltNameYN': pl.Utf8,
    'newReservationYN': pl.Utf8,
    'numericValidation': pl.Utf8,
    'organizationID': pl.Int64,
    'pointsCalculationMethod': pl.Utf8,
    'pointsIssuedCentrallyYn': pl.Utf8,
    'pointsLabel': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYN': pl.Utf8,
    'printFolioMessageOnConfirmationYN': pl.Utf8,
    'promptatcheckinflag': pl.Utf8,
    'randomGenerationYN': pl.Utf8,
    'rank': pl.Float64,
    'requalifyOnUpgradeYN': pl.Utf8,
    'requiredOnStayPeriodYN': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rule': pl.Utf8,
    'saveCardNumberHistoryYN': pl.Utf8,
    'sendChkoutToIfc': pl.Utf8,
    'sendcheckouttoifcflag': pl.Utf8,
    'sequence': pl.Float64,
    'tierExpirationMonth': pl.Utf8,
    'tierManagementResetYN': pl.Utf8,
    'toSequenceNumber': pl.Float64,
    'transactionMaxPoints': pl.Float64,
    'tscDateFlag': pl.Utf8,
    'type': pl.Utf8,
    'udfCardValidationYn': pl.Utf8,
    'udfFormula': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateReservationYN': pl.Utf8,
    'updateUser': pl.Int64,
    'upgradePeriod': pl.Float64,
    'upgradePeriodYr': pl.Utf8,
    'validationByIfc': pl.Utf8,
    'validationRule': pl.Utf8,
    'validationbyifcflag': pl.Utf8,
    'yearsToExpire': pl.Float64,
}
```
```python
membership_property_group_details_schema = {
    'backToBack': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'includeExclude': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'propertyGroupCode': pl.Utf8,
    'propertyGroupDescription': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_rate_group_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'includeExclude': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateGroupCode': pl.Utf8,
    'rateGroupDescription': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_revenue_group_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'includeExclude': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueGroupCode': pl.Utf8,
    'revenueGroupDescription': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_revenue_type_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'frequentFlyerPoints': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'membershipPoints': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueBucketCode': pl.Utf8,
    'revenueBucketDescription': pl.Utf8,
    'revenueTypeCode': pl.Utf8,
    'revenueTypeDescription': pl.Utf8,
    'sequence': pl.Float64,
    'tierPoints': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_room_group_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'roomGroupCode': pl.Utf8,
    'roomGroupDescription': pl.Utf8,
    'roomTypes': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
hub_details_schema = {
    'aRAccountNumberMandYN': pl.Utf8,
    'aRBalanceTrxCode': pl.Utf8,
    'aRCreditTrxCode': pl.Utf8,
    'accessCode': pl.Utf8,
    'address': pl.Utf8,
    'agingLevel1': pl.Float64,
    'agingLevel2': pl.Float64,
    'agingLevel3': pl.Float64,
    'agingLevel4': pl.Float64,
    'agingLevel5': pl.Float64,
    'airport': pl.Utf8,
    'airportDistance': pl.Utf8,
    'airportTime': pl.Utf8,
    'allowLoginYn': pl.Utf8,
    'allowancePeriodAdj': pl.Utf8,
    'arAccountNumberFormat': pl.Utf8,
    'arAgent': pl.Utf8,
    'arCompany': pl.Utf8,
    'arGroups': pl.Utf8,
    'arIndividuals': pl.Utf8,
    'arSettleCode': pl.Utf8,
    'arTypewriter': pl.Utf8,
    'awardsTimeout': pl.Float64,
    'baseLanguage': pl.Utf8,
    'beginDate': pl.Utf8,
    'blackoutPeriodNotes': pl.Utf8,
    'block': pl.Utf8,
    'brArea': pl.Utf8,
    'brSeats': pl.Float64,
    'brandCode': pl.Utf8,
    'budgetMonth': pl.Float64,
    'cCreditLimit': pl.Float64,
    'cDoubleRate2': pl.Float64,
    'cDoubleRate1': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cSglRate2': pl.Float64,
    'cSglRate1': pl.Float64,
    'cSuiRate2': pl.Float64,
    'cSuiRate1': pl.Float64,
    'cTplRate2': pl.Float64,
    'cTplRate1': pl.Float64,
    'cWarningAmount': pl.Float64,
    'cRSResort': pl.Utf8,
    'cashShiftDrop': pl.Utf8,
    'cateringCurrencyCode': pl.Utf8,
    'cateringCurrencyFormat': pl.Utf8,
    'chainCode': pl.Utf8,
    'checkExgPaidout': pl.Utf8,
    'checkInTime': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'checkShiftDrop': pl.Utf8,
    'checkTrxcode': pl.Utf8,
    'city': pl.Utf8,
    'comAddress': pl.Utf8,
    'comMethod': pl.Utf8,
    'comNameXrefId': pl.Float64,
    'companyAddressType': pl.Utf8,
    'companyPhoneType': pl.Utf8,
    'configurationMode': pl.Utf8,
    'confirmRegcardPrinter': pl.Utf8,
    'copies': pl.Float64,
    'country': pl.Utf8,
    'creditLimit': pl.Float64,
    'croCode': pl.Utf8,
    'currency': pl.Utf8,
    'currencyDecimals': pl.Float64,
    'currencyExgPaidout': pl.Utf8,
    'currencyFormat': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'curtainColor': pl.Utf8,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'dateSeparator': pl.Utf8,
    'dblNum': pl.Utf8,
    'dblRate2': pl.Float64,
    'dblRate1': pl.Float64,
    'decimalPlaces': pl.Float64,
    'decimalSeparator': pl.Utf8,
    'defaultCommissionPercentage': pl.Utf8,
    'defaultFaxType': pl.Utf8,
    'defaultFolioStyle': pl.Float64,
    'defaultGroupsRateCode': pl.Utf8,
    'defaultGuestAddress': pl.Utf8,
    'defaultMembershipType': pl.Utf8,
    'defaultPostingRoom': pl.Utf8,
    'defaultPrepaidComm': pl.Utf8,
    'defaultPrinter': pl.Utf8,
    'defaultRateCode': pl.Utf8,
    'defaultRatecodePcr': pl.Utf8,
    'defaultRatecodeRack': pl.Utf8,
    'defaultRegistrationCard': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'defaultTrxCommissionCode': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositLedgerTrxCode': pl.Utf8,
    'destinationId': pl.Utf8,
    'dfltPkgTranCode': pl.Utf8,
    'dfltTranCodeRateCode': pl.Utf8,
    'directions': pl.Utf8,
    'dirsales': pl.Utf8,
    'disableLoginYn': pl.Utf8,
    'downloadRestYn': pl.Utf8,
    'dutyManagerPager': pl.Utf8,
    'email': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'expHotelCode': pl.Utf8,
    'expiryDate': pl.Utf8,
    'extExpFileLocation': pl.Utf8,
    'extPropertyCode': pl.Utf8,
    'externalScYn': pl.Utf8,
    'fax': pl.Utf8,
    'faxNoFormat': pl.Utf8,
    'fileTransferFormat': pl.Utf8,
    'fiscalEndDate': pl.Utf8,
    'fiscalPeriodType': pl.Utf8,
    'fiscalStartDate': pl.Utf8,
    'flags': pl.Utf8,
    'floorNumExecutiveFloor': pl.Utf8,
    'flowCode': pl.Utf8,
    'fnsTier': pl.Utf8,
    'folioLanguage1': pl.Utf8,
    'folioLanguage2': pl.Utf8,
    'folioLanguage3': pl.Utf8,
    'folioLanguage4': pl.Utf8,
    'font': pl.Float64,
    'genmgr': pl.Utf8,
    'groupRoomWarning': pl.Float64,
    'guestLookupTimeout': pl.Float64,
    'hotelCode': pl.Utf8,
    'hotelFc': pl.Utf8,
    'hotelId': pl.Utf8,
    'hotelType': pl.Utf8,
    'hub': pl.Utf8,
    'imgDirectionId': pl.Float64,
    'imgHotelId': pl.Float64,
    'imgMapId': pl.Float64,
    'inactiveDaysForGuestProfil': pl.Float64,
    'individualAddressType': pl.Utf8,
    'individualPhoneType': pl.Utf8,
    'individualRoomWarning': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'intTaxIncludedYn': pl.Utf8,
    'inventoryYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepAvailability': pl.Float64,
    'latitude': pl.Float64,
    'leadsend': pl.Utf8,
    'legalOwner': pl.Utf8,
    'licenseCode': pl.Utf8,
    'longDateFormat': pl.Utf8,
    'longStayControl': pl.Float64,
    'longitude': pl.Float64,
    'maxAdultsFamilyRoom': pl.Float64,
    'maxChildrenFamilyRoom': pl.Float64,
    'maxCreditDays': pl.Float64,
    'maxNoNights': pl.Float64,
    'maxOccupancy': pl.Float64,
    'mbsSupportedYn': pl.Utf8,
    'meetRooms': pl.Float64,
    'meetSeats': pl.Float64,
    'meetSpace': pl.Float64,
    'meetingFc': pl.Utf8,
    'minDaysBet2ReminderLetter': pl.Float64,
    'name': pl.Utf8,
    'nameIdLink': pl.Float64,
    'nightAuditCashierId': pl.Utf8,
    'notes': pl.Utf8,
    'numberBeds': pl.Float64,
    'numberFloors': pl.Float64,
    'numberRooms': pl.Float64,
    'opusCurrencyCode': pl.Utf8,
    'organizationID': pl.Int64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'path': pl.Utf8,
    'pathId': pl.Float64,
    'paymentDate': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'propMapUrl': pl.Utf8,
    'propPicUrl': pl.Utf8,
    'propinfoUrl': pl.Utf8,
    'qtyConnectingRooms': pl.Float64,
    'qtyDoubleRooms': pl.Float64,
    'qtyFamilyRooms': pl.Float64,
    'qtyGuestElevators': pl.Float64,
    'qtyGuestRoomFloors': pl.Float64,
    'qtyHandicappedRooms': pl.Float64,
    'qtyNonSmokingRooms': pl.Float64,
    'qtySingleRooms': pl.Float64,
    'qtySuites': pl.Float64,
    'qtyTwinRooms': pl.Float64,
    'quotedCurrency': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reconcileDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'resortType': pl.Utf8,
    'restaurant': pl.Float64,
    'rhythmSheets': pl.Float64,
    'rhythmTowels': pl.Float64,
    'roomAmenity': pl.Utf8,
    'saveProfiles': pl.Float64,
    'scriptId': pl.Float64,
    'season1': pl.Utf8,
    'season2': pl.Utf8,
    'season3': pl.Utf8,
    'season4': pl.Utf8,
    'season5': pl.Utf8,
    'sendLeadAsBookingYn': pl.Utf8,
    'sglNum': pl.Utf8,
    'sglRate1': pl.Float64,
    'sglRate2': pl.Float64,
    'shopDescription': pl.Utf8,
    'shortDateFormat': pl.Utf8,
    'sourceCommission': pl.Utf8,
    'state': pl.Utf8,
    'street': pl.Utf8,
    'suiNum': pl.Utf8,
    'suiRate1': pl.Float64,
    'suiRate2': pl.Float64,
    'summCurrencyCode': pl.Utf8,
    'taCommission': pl.Utf8,
    'telephone': pl.Utf8,
    'telephoneNoFormat': pl.Utf8,
    'thousandSeparator': pl.Utf8,
    'timeFormat': pl.Utf8,
    'timeZone': pl.Utf8,
    'tollFree': pl.Utf8,
    'totalRooms': pl.Float64,
    'touristNumber': pl.Utf8,
    'tplNum': pl.Utf8,
    'tplRate1': pl.Float64,
    'tplRate2': pl.Float64,
    'translateMulticharYn': pl.Utf8,
    'turnawayCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vatId': pl.Utf8,
    'videoCoStart': pl.Utf8,
    'videoCoStop': pl.Utf8,
    'videocheckoutPrinter': pl.Utf8,
    'wakeUpDelay': pl.Float64,
    'warningAmount': pl.Float64,
    'webaddress': pl.Utf8,
    'weekendDays': pl.Utf8,
    'xresortNumber': pl.Float64,
    'zeroInvPurDays': pl.Float64,
}
```
```python
note_type_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'defaultNoteText': pl.Utf8,
    'defaultNoteTextYN': pl.Utf8,
    'defaultNoteTypeYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'deptNoteYn': pl.Utf8,
    'globalYn': pl.Utf8,
    'helpText': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'noteClass': pl.Utf8,
    'noteType': pl.Utf8,
    'noteTypeCode': pl.Utf8,
    'noteTypeDescription': pl.Utf8,
    'notesGroup': pl.Utf8,
    'notetypeid': pl.Utf8,
    'notetypepmsref': pl.Utf8,
    'notificationAreas': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideInternalYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'protectDescriptionYn': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'webProposalYn': pl.Utf8,
}
```
```python
property_type_details_schema = {
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
foreign_currency_details_schema = {
    'abbreviation': pl.Utf8,
    'activeYN': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'currencyActionId': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dSI': pl.Int64,
    'decimals': pl.Float64,
    'deletedFlag': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'formatMask': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mobileYn': pl.Utf8,
    'multiply': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'previousLocalCurrencyYn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellCurrency': pl.Utf8,
    'trianMethodYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'usedForCcPaymentsYn': pl.Utf8,
}
```
```python
item_rate_rules_details_schema = {
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'codeId': pl.Float64,
    'codeType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayYn': pl.Utf8,
    'fulldayYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportingCodeId': pl.Utf8,
    'sequence': pl.Float64,
    'webBookingYn': pl.Utf8,
    'webSetdown': pl.Float64,
    'webSetup': pl.Float64,
}
```
```python
postal_code_details_schema = {
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'country': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'deletedYn': pl.Utf8,
    'description': pl.Utf8,
    'district': pl.Utf8,
    'fiscalRegion': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'postalCodeFrom': pl.Utf8,
    'postalCodeTo': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'scity': pl.Utf8,
    'seq': pl.Float64,
    'state': pl.Utf8,
    'territory': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
i_d_document_type_details_schema = {
    'chainCode': pl.Utf8,
    'checkForDuplicatesYn': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'iDRole': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
language_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'enrollmentAltYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locale': pl.Utf8,
    'nativeWritingSystem': pl.Utf8,
    'organizationID': pl.Int64,
    'preferredLanguageAdV5': pl.Utf8,
    'preferredScriptAdV5': pl.Utf8,
    'preferredlanguage': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reportDateLanguage': pl.Utf8,
    'translationLanguage': pl.Utf8,
}
```
```python
region_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'regionDescription': pl.Utf8,
    'regionid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
state_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'country': pl.Utf8,
    'countryid': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'stateCode': pl.Utf8,
    'stateid': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_class_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'frequentFlyerYN': pl.Utf8,
    'inactiveflag': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'loyaltyProgramYN': pl.Utf8,
    'membershipclassid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
confirmation_format_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'formatDefinition': pl.Utf8,
    'formatType': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'salesAddressFormatYN': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
communication_type_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'role': pl.Utf8,
    'sequence': pl.Float64,
    'textMessagingEnabledYN': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_preference_type_details_schema = {
    'allowSubTypesYn': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reservationYN': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_profile_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
configuration_relationship_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fromDescription': pl.Utf8,
    'fromRelationshipCode': pl.Utf8,
    'fromRelationshipType': pl.Utf8,
    'globalYn': pl.Utf8,
    'hasHierarchyYN': pl.Utf8,
    'ignoreProtectionYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'individualflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'primaryflag': pl.Utf8,
    'rate': pl.Utf8,
    'relationCategory': pl.Utf8,
    'relationshipId': pl.Utf8,
    'relationshipRole': pl.Utf8,
    'relationshippms': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'tempFlag': pl.Utf8,
    'toDescription': pl.Utf8,
    'toRelationshipCode': pl.Utf8,
    'toRelationshipType': pl.Utf8,
    'toindividualflag': pl.Utf8,
    'toinheritratesflag': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_claim_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'claimTypeCode': pl.Utf8,
    'claimTypeDescription': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_awards_details_schema = {
    'autoConsumeYn': pl.Utf8,
    'awardBasedOn': pl.Utf8,
    'awardBasedOnDesc': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardDescription': pl.Utf8,
    'awardQuantity': pl.Float64,
    'awardValue': pl.Float64,
    'billingGroup': pl.Utf8,
    'cAwardValue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cancelPenaltyChargePoints': pl.Float64,
    'cancelPenaltyDays': pl.Float64,
    'cancelPenaltyType': pl.Utf8,
    'cancelPolicyType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displaySet': pl.Utf8,
    'endSellDate': pl.Utf8,
    'exchangeRateType': pl.Utf8,
    'forceVerificationYn': pl.Utf8,
    'ignoreFtTransactionYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'maxPercentAllowed': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipType': pl.Utf8,
    'messageLine1': pl.Utf8,
    'messageLine2': pl.Utf8,
    'messageLine3': pl.Utf8,
    'messageLine4': pl.Utf8,
    'nightsYN': pl.Utf8,
    'numberOfNights': pl.Float64,
    'organizationID': pl.Int64,
    'pointsRequired': pl.Float64,
    'pointsRequiredDesc': pl.Float64,
    'primaryKeyID': pl.Int64,
    'ptsSchCode': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'roomCategoryGroupYN': pl.Utf8,
    'sequence': pl.Float64,
    'startSellDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_enroll_details_schema = {
    'attachedEnrollmentCode': pl.Utf8,
    'attachedEnrollmentDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'memEnrollGroup': pl.Utf8,
    'membershipenrollid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_level_details_schema = {
    'autoRenewalAfter': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPCodeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'changesRestrictedYN': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColorCode': pl.Utf8,
    'displayColorDescription': pl.Utf8,
    'doubleDippingYN': pl.Utf8,
    'expiryPeriod': pl.Float64,
    'fulfillmentYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'levelCode': pl.Utf8,
    'maxDowngradeLevel': pl.Utf8,
    'maxDowngradeLevelDescription': pl.Utf8,
    'membershipType': pl.Utf8,
    'membershiplevelid': pl.Utf8,
    'membershiplevelpmsref': pl.Utf8,
    'membershiptypeid': pl.Utf8,
    'numberOfTrx': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rank': pl.Float64,
    'renewCardOnStayYN': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vIPCode': pl.Utf8,
    'vIPCodeDescription': pl.Utf8,
}
```
```python
membership_card_ranges_details_schema = {
    'cardRangeFrom': pl.Utf8,
    'cardRangeTo': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_level_benefits_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fromDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelCode': pl.Utf8,
    'levelDescription': pl.Utf8,
    'membershipType': pl.Utf8,
    'minimumMembershipLevel': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'toDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_market_group_code_details_schema = {
    'attachedMarketCodes': pl.Utf8,
    'attachedMarketDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'memMarketGroup': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_rate_group_code_details_schema = {
    'attachedRateCode': pl.Utf8,
    'attachedRateCodeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'memRateGroup': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_revenue_group_code_details_schema = {
    'attachedRevenueGroupCode': pl.Utf8,
    'attachedRevenueGroupDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'memRevenueGroup': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_booking_status_next_details_schema = {
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'status': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```