# ConfigurationChain
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| chainDetails | [`ConfigurationChainChainDetailsType`](#configurationchainchaindetailstype) | Chain Details |
| membershipEnrollmentCodeDetails | [`ConfigurationChainMembershipEnrollmentCodeDetailsType`](#configurationchainmembershipenrollmentcodedetailstype) | Membership Enrollment Code |
| membershipEnrollGroupDetails | [`ConfigurationChainMembershipEnrollGroupDetailsType`](#configurationchainmembershipenrollgroupdetailstype) | Membership Enroll Group |
| membershipMarketGroupMembershipMarketGroupDetails | [`ConfigurationChainMembershipMarketGroupMembershipMarketGroupDetailsType`](#configurationchainmembershipmarketgroupmembershipmarketgroupdetailstype) | Membership Market Group |
| membershipMarketGroupDetails | [`ConfigurationChainMembershipMarketGroupDetailsType`](#configurationchainmembershipmarketgroupdetailstype) | Membership Market Group |
| membershipTypeDetails | [`ConfigurationChainMembershipTypeDetailsType`](#configurationchainmembershiptypedetailstype) | Membership Type Details |
| membershipPropertyGroupDetails | [`ConfigurationChainMembershipPropertyGroupDetailsType`](#configurationchainmembershippropertygroupdetailstype) | Membership Property Group |
| membershipRateGroupDetails | [`ConfigurationChainMembershipRateGroupDetailsType`](#configurationchainmembershiprategroupdetailstype) | Membership Rate Group |
| membershipRevenueGroupDetails | [`ConfigurationChainMembershipRevenueGroupDetailsType`](#configurationchainmembershiprevenuegroupdetailstype) | Membership Revenue Group |
| membershipRevenueTypeDetails | [`ConfigurationChainMembershipRevenueTypeDetailsType`](#configurationchainmembershiprevenuetypedetailstype) | Membership Revenue Type |
| membershipRoomGroupDetails | [`ConfigurationChainMembershipRoomGroupDetailsType`](#configurationchainmembershiproomgroupdetailstype) | Membership Room Group |
| hubDetails | [`ConfigurationChainHubDetailsType`](#configurationchainhubdetailstype) | Hub Details |
| noteTypeDetails | [`ConfigurationChainNoteTypeDetailsType`](#configurationchainnotetypedetailstype) | Note Type Details |
| propertyTypeDetails | [`ConfigurationChainPropertyTypeDetailsType`](#configurationchainpropertytypedetailstype) | Property Type |
| foreignCurrencyDetails | [`ConfigurationChainForeignCurrencyDetailsType`](#configurationchainforeigncurrencydetailstype) | Foreign Currency Details |
| itemRateRulesDetails | [`ConfigurationChainItemRateRulesDetailsType`](#configurationchainitemraterulesdetailstype) | Item Rate Rules Details |
| postalCodeDetails | [`ConfigurationChainPostalCodeDetailsType`](#configurationchainpostalcodedetailstype) | Postal Code Details |
| iDDocumentTypeDetails | [`ConfigurationChainIDDocumentTypeDetailsType`](#configurationchainiddocumenttypedetailstype) | ID Document Type |
| languageDetails | [`ConfigurationChainLanguageDetailsType`](#configurationchainlanguagedetailstype) | Language Details |
| regionDetails | [`ConfigurationChainRegionDetailsType`](#configurationchainregiondetailstype) | Region Details |
| stateDetails | [`ConfigurationChainStateDetailsType`](#configurationchainstatedetailstype) | State Details |
| membershipClassDetails | [`ConfigurationChainMembershipClassDetailsType`](#configurationchainmembershipclassdetailstype) | Membership Class Details |
| confirmationFormatDetails | [`ConfigurationChainConfirmationFormatDetailsType`](#configurationchainconfirmationformatdetailstype) | Confirmation Format Details |
| communicationTypeDetails | [`ConfigurationChainCommunicationTypeDetailsType`](#configurationchaincommunicationtypedetailstype) | Communication Type Details |
| profilePreferenceTypeDetails | [`ConfigurationChainProfilePreferenceTypeDetailsType`](#configurationchainprofilepreferencetypedetailstype) | Profile Preference Type Details |
| profileProfileDetails | [`ConfigurationChainProfileProfileDetailsType`](#configurationchainprofileprofiledetailstype) | Profile Profile |
| configurationRelationshipDetails | [`ConfigurationChainConfigurationRelationshipDetailsType`](#configurationchainconfigurationrelationshipdetailstype) | Configuration Relationship |
| membershipClaimTypeDetails | [`ConfigurationChainMembershipClaimTypeDetailsType`](#configurationchainmembershipclaimtypedetailstype) | Membership Claim Type |
| membershipAwardsDetails | [`ConfigurationChainMembershipAwardsDetailsType`](#configurationchainmembershipawardsdetailstype) | Membership Awards |
| membershipEnrollDetails | [`ConfigurationChainMembershipEnrollDetailsType`](#configurationchainmembershipenrolldetailstype) | Membership Enroll Details |
| membershipLevelDetails | [`ConfigurationChainMembershipLevelDetailsType`](#configurationchainmembershipleveldetailstype) | Membership Level Details |
| membershipCardRangesDetails | [`ConfigurationChainMembershipCardRangesDetailsType`](#configurationchainmembershipcardrangesdetailstype) | Membership Card Ranges |
| membershipLevelBenefitsDetails | [`ConfigurationChainMembershipLevelBenefitsDetailsType`](#configurationchainmembershiplevelbenefitsdetailstype) | Membership Level Benefits |
| membershipMarketGroupCodeDetails | [`ConfigurationChainMembershipMarketGroupCodeDetailsType`](#configurationchainmembershipmarketgroupcodedetailstype) | Membership Market Group Code |
| membershipRateGroupCodeDetails | [`ConfigurationChainMembershipRateGroupCodeDetailsType`](#configurationchainmembershiprategroupcodedetailstype) | Membership Rate Group Code |
| membershipRevenueGroupCodeDetails | [`ConfigurationChainMembershipRevenueGroupCodeDetailsType`](#configurationchainmembershiprevenuegroupcodedetailstype) | Membership Revenue Group Code |
| propertyBookingStatusNextDetails | [`ConfigurationChainPropertyBookingStatusNextDetailsType`](#configurationchainpropertybookingstatusnextdetailstype) | Property Booking Status Next |
| configurationChainRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ConfigurationChainChainDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aspYn | `String` | Chain used for ASP Y/N. |
| beginDate | `Date` | Begin Date |
| bookingConditions | `String` | Booking conditions chainwide such as commission policies for TA Group policies Cancellation/Deposit/Guarantee and family and child rules. |
| centralChain | `String` | Central Chain |
| centralDescription | `String` | Central Description |
| chain | `String` | Chain |
| chainName | `String` | Chain Name |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| endDate | `Date` | End Date |
| frequentFlierCardsAcceptYn | `String` | Specifies if frequent flier cards are accepted by the chain (Y/N). |
| hoCity | `String` | The city of the Head Office of the chain. |
| hoCountry | `String` | The country of the Head Office of the chain. |
| hoEmail | `String` | The email ID of the Head Office of the chain. |
| hoFax | `String` | The fax number of the Head Office of the chain. |
| hoPostCode | `String` | The postal code of the Head Office of the chain. |
| hoState | `String` | The state of the Head Office of the chain. |
| hoStreet | `String` | The street of the Head Office of the chain. |
| hoTelephone | `String` | The phone number of the Head Office of the chain. |
| imgChainId | `Float` | Img Chain ID |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| logoFileName | `String` | File name of the chains' logo |
| loyaltyProgram | `String` | Loyalty program data. |
| marketingText | `String` | Marketing Text |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| scriptId | `Float` | Script ID |
| shareProfilesYN | `String` | Sharing Profiles across the Chain. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollmentCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| enrollmentCode | `String` | Enrollment Code |
| enrollmentDescription | `String` | Enrollment Description |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| enrollmentGroupCode | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| enrollmentGroupDescription | `String` | Enrollment Group Description |
| includeExclude | `String` | Include Exclude |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupMembershipMarketGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| includeExclude | `String` | Include Exclude |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| activityPeriodYears | `String` | Activity Period Years |
| allowAdhocMultiplierYn | `String` | Indicates if program allows Ad Hoc multipliers for points calculation. |
| allowDuplicateCardNumbersYN | `String` | Allow Duplicate Card Numbers YN |
| allowSharesYn | `String` | Flag indicating if points should be calculated for shared rooms. |
| alternateNameProtectedYN | `String` | Alternate Name Protected YN |
| autoCardNoBasedOn | `String` | This is used when the card no is auto generated and is based on some other value  like enrollment code. |
| autoGenCardPrefix | `String` | Auto Gen Card Prefix |
| autoPopulateNumberFromNameYN | `String` | Auto Populate Number From Name YN |
| awardGenerationMethod | `String` | Not used |
| awardPointExpiryDateYears | `String` | Award Point Expiry Date Years |
| awardRedeemThreshold | `String` | Award Redeem Threshold |
| basedOn | `String` | Defines what the rule is based on the type of condition which need to be satisfied in order to qualify for this rule. Valid values are MEMBERSHIP RATE_CODE REFERENCE VIP. |
| bookerProgramYn | `String` | Flag to mark the booker program membership types. |
| cCostPerPoint | `Float` | Central Cost Per Point |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| calculationMethod | `String` | Valid values are ROLLING or CALENDAR.Rolling ? Indicates the membership will run from the same month for a determined amount of time.Calendar ? Indicates the calculation will occur every year at the end of the year. |
| calculationMonths | `Float` | This signifies the number of months that points are valid for a membership type |
| calculationPeriod | `String` | Valid values are ROLLING_MONTHS and CALENDAR_MONTHS. |
| canDeleteYn | `String` | Can Delete Y/N |
| cardLength | `Float` | The length of the card number for default card validation. |
| cardPrefix | `String` | Card Prefix |
| cardValidYears | `Float` | Number of years card will be valid for this level. |
| centrallyManagedYN | `String` | Indicates if program is managed centrally or at Local property. If central then points will be calculated at ECIS else if program is local then points will be calculated and stored locally. |
| chainCode | `String` | Chain Code |
| checkInYN | `String` | Indicates if a prompt is required at checkin of a reservation if a membership number exists on profile and not attached to the reservation. |
| checkOutYN | `String` | Indicates if resv_memberships should popup when a reservation is checked out. |
| chipAndPinYn | `String` | Indicates if this membership type is Chip and Pin. |
| class | `String` | Primary key of this table |
| costPerPoint | `Float` | Cost Per Point |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultMemberStatus | `String` | Default value for membership status. |
| delayInDays | `Float` | Not used |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| downgradePeriod | `Float` | Number of months to consider for downgrade. |
| downgradePeriodYr | `String` | Downgrade Period Year |
| downgradeRenewalYN | `String` | Downgrade/Renewal YN |
| enrollcoderequiredflag | `String` | Enrollcoderequiredflag |
| enrollmentCodeRequiredYN | `String` | Enrollment code required flag. |
| exceptionType | `String` | Exception Type |
| exchangeRateType | `String` | Exchange Rate Type |
| excludeProfileFromPurgeYN | `String` | Exclude Profile From Purge YN |
| expirationDateRequiredYN | `String` | Expiration Date Required YN |
| expirationMonth | `Float` | Expiration month for membership types having a ROLLING calculation method. |
| expiryPeriod | `String` | Expiry Period |
| externalDatabase | `String` | External Database |
| externalProcessDays | `Float` | Maximum number of days to process the External Processing Exception. |
| externallyControlledYN | `String` | Flag that affects how a Membership Type is added edited or deleted from a profile. |
| folioMessageCredits | `String` | Folio Message for Credits. |
| folioMessageNonmembers | `String` | Folio Message Nonmembers |
| folioMessageNonmembersNq | `String` | Folio message for non members who have a non-qualifying rate code. |
| folioMessageNq | `String` | Folio message for members who have a non-qualifying rate code. |
| foreignCurrencyID | `String` | Foreign Currency ID |
| format | `String` | Format for Random Number Generation. |
| fromSequenceNumber | `Float` | From Sequence Number |
| fulfillmentYN | `String` | Fulfillment YN |
| graceExpirationMonth | `Float` | Used in EIS Module. |
| gracePeriodYears | `String` | Grace Period Years |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| levelRequiredYN | `String` | Level Required YN |
| memberFolioMessage | `String` | Free form text that can ve configured to display on the folio of clients earning points under this program. |
| memberInfoDispSet | `String` | Display set used for member info. |
| membershipAction | `String` | [A]utopopulate on Reservation [P]rompt on Reservation; Al[W]ays Prompt [N]o action. |
| membershipActionDetails | `String` | Membership Action Details |
| membershipclassid | `String` | Membershipclassid |
| membershiptypeid | `String` | Membershiptypeid |
| multipleRoomsLimit | `Float` | Multiple rooms allowed for points exception. |
| nameProtectedYN | `String` | Name Protected YN |
| nameOnCardFromAltNameYN | `String` | Name on Card From Alt Name YN |
| newReservationYN | `String` | Indicates if resv_memberships should popup when a reservation is created. |
| numericValidation | `String` | Indicates the type of card number validation which should be done. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pointsCalculationMethod | `String` | Points Calculation Method |
| pointsIssuedCentrallyYn | `String` | Indicates that points are issued by central system |
| pointsLabel | `String` | Label for points (i.e. Points or Miles) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Primary YN |
| printFolioMessageOnConfirmationYN | `String` | Print Folio Message On Confirmation YN |
| promptatcheckinflag | `String` | Promptatcheckinflag |
| randomGenerationYN | `String` | Random Generation YN |
| rank | `Float` | Rank |
| requalifyOnUpgradeYN | `String` | Requalify on Upgrade YN |
| requiredOnStayPeriodYN | `String` | Required on Stay Period YN |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rule | `String` | Rule for posting NOSHOW revenue. |
| saveCardNumberHistoryYN | `String` | Save Card Number History YN |
| sendChkoutToIfc | `String` | Send checkout reservation information to the interface for Courtesy Cards? |
| sendcheckouttoifcflag | `String` | Sendcheckouttoifcflag |
| sequence | `Float` | Sequence |
| tierExpirationMonth | `String` | Tier Expiration Month |
| tierManagementResetYN | `String` | Tier Management Reset YN |
| toSequenceNumber | `Float` | To Sequence Number |
| transactionMaxPoints | `Float` | Indicates the maximum points that can be accrued per membership transaction. |
| tscDateFlag | `String` | Tier Management Based on Date. |
| type | `String` | Type |
| udfCardValidationYn | `String` | Indicates if card number validation is a UDF(User defined function) or Default validation is used. |
| udfFormula | `String` | Udf Formula |
| updateDate | `DateTime` | Update Date |
| updateReservationYN | `String` | Indicates if resv_memberships should popup when a reservation is updated. |
| updateUser | `Float` | Update User |
| upgradePeriod | `Float` | Number of months to consider for upgrade. |
| upgradePeriodYr | `String` | Upgrade Period Year |
| validationByIfc | `String` | Indicates if the card is to be validated by an external system. |
| validationRule | `String` | Validation Rule |
| validationbyifcflag | `String` | Validationbyifcflag |
| yearsToExpire | `Float` | Years To Expire |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipPropertyGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| backToBack | `String` | Used to indicate the specific grouping in order to eliminate stay exceptions like back to back stays. |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| includeExclude | `String` | Include Exclude |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| propertyGroupCode | `String` | Property Group Code |
| propertyGroupDescription | `String` | Property Group Description |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRateGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| includeExclude | `String` | Include Exclude |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateGroupCode | `String` | Rate Group Code |
| rateGroupDescription | `String` | Rate Group Description |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| includeExclude | `String` | Include Exclude |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueGroupCode | `String` | Membership rate group. |
| revenueGroupDescription | `String` | Revenue Group Description |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| frequentFlyerPoints | `String` | Indicates if the Revenue Type is valid for calculating Frequent Flyer Points. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| membershipPoints | `String` | Indicates if the Revenue Type is valid for calculating Membership Points. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueBucketCode | `String` | Revenue Bucket Code |
| revenueBucketDescription | `String` | Revenue Bucket Description |
| revenueTypeCode | `String` | Revenue Types defined for OIS memberships. |
| revenueTypeDescription | `String` | Revenue Type Description |
| sequence | `Float` | Sequence |
| tierPoints | `String` | Filled in case of bucket rules where Award and Tier points can be computed same but implemented differently. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRoomGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| roomGroupCode | `String` | Room Group Code |
| roomGroupDescription | `String` | Room Group Description |
| roomTypes | `String` | Room Types |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainHubDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| aRBalanceTrxCode | `String` | Internal |
| aRCreditTrxCode | `String` | Internal |
| accessCode | `String` | Access Code |
| address | `String` | Default property address format. |
| agingLevel1 | `Float` | Aging bucket 1 |
| agingLevel2 | `Float` | Aging bucket 2 |
| agingLevel3 | `Float` | Aging bucket 3 |
| agingLevel4 | `Float` | Aging bucket 4 |
| agingLevel5 | `Float` | Aging bucket 5 |
| airport | `String` | The Airport Code for the airport near the property |
| airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| allowancePeriodAdj | `String` | Period for the allowance |
| arAccountNumberFormat | `String` | Number format of AR account no. |
| arAgent | `String` | Default Account Type for an Agent for the Property |
| arCompany | `String` | Default Account Type for a Company for the Property |
| arGroups | `String` | Default Account Type for a Group for the Property |
| arIndividuals | `String` | Default Account Type for Individual for the Property |
| arSettleCode | `String` | Internal |
| arTypewriter | `String` | Internal |
| awardsTimeout | `Float` | Internal |
| baseLanguage | `String` | The base language of the Hotel |
| beginDate | `Date` | Begin Date |
| blackoutPeriodNotes | `String` | Blackout period notes defaulted onto the FIT Contract at time of creation. |
| block | `String` | Block |
| brArea | `String` | Ball Room Area |
| brSeats | `Float` | No of Ballroom Seats |
| brandCode | `String` | Brand Code |
| budgetMonth | `Float` | Financial Year of the Property |
| cCreditLimit | `Float` | Central Credit Limit |
| cDoubleRate2 | `Float` | Central Dbl Rate2 |
| cDoubleRate1 | `Float` | Central Dbl Rate1 |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cSglRate2 | `Float` | Central Sgl Rate2 |
| cSglRate1 | `Float` | Central Sgl Rate1 |
| cSuiRate2 | `Float` | Central Sui Rate2 |
| cSuiRate1 | `Float` | Central Sui Rate1 |
| cTplRate2 | `Float` | Central Tpl Rate2 |
| cTplRate1 | `Float` | Central Tpl Rate1 |
| cWarningAmount | `Float` | Central Warning Amount |
| cRSResort | `String` | Not used |
| cashShiftDrop | `String` | Internal |
| cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| cateringCurrencyFormat | `String` | Catering currency format. |
| chainCode | `String` | Chain Code |
| checkExgPaidout | `String` | Internal |
| checkInTime | `Date` | The Hotel official check intime |
| checkOutTime | `Date` | The Hotel official check out time |
| checkShiftDrop | `String` | Internal |
| checkTrxcode | `String` | Internal |
| city | `String` | City |
| comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| comNameXrefId | `Float` | Internal |
| companyAddressType | `String` | Internal |
| companyPhoneType | `String` | Internal |
| configurationMode | `String` | Internal |
| confirmRegcardPrinter | `String` | Internal |
| copies | `Float` | Copies |
| country | `String` | Country |
| creditLimit | `Float` | Credit Limit |
| croCode | `String` | Cro Code |
| currency | `String` | Currency |
| currencyDecimals | `Float` | Number of decimals to designate currency |
| currencyExgPaidout | `String` | Not used |
| currencyFormat | `String` | Format for the local currency. |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| curtainColor | `String` | Color that of the background |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateForAging | `String` | Date the aging should begin |
| dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| dblNum | `String` | Not used |
| dblRate2 | `Float` | Not used |
| dblRate1 | `Float` | Not used |
| decimalPlaces | `Float` | Number of places for the default currency |
| decimalSeparator | `String` | Type of decimal separator |
| defaultCommissionPercentage | `String` | Not used |
| defaultFaxType | `String` | Not used |
| defaultFolioStyle | `Float` | Folio style to be used for all guests |
| defaultGroupsRateCode | `String` | Not used |
| defaultGuestAddress | `String` | Default guest address format. |
| defaultMembershipType | `String` | Future use |
| defaultPostingRoom | `String` | Future use |
| defaultPrepaidComm | `String` | Not used. |
| defaultPrinter | `String` | Not Used |
| defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| defaultRegistrationCard | `String` | Default registration card for the property. |
| defaultReservationType | `String` | The Default reservation type for this property |
| defaultTrxCommissionCode | `String` | Not used. |
| deletedFlag | `String` | Deleted Flag |
| depositLedgerTrxCode | `String` | Future use |
| destinationId | `String` | Destination ID |
| dfltPkgTranCode | `String` | Future use |
| dfltTranCodeRateCode | `String` | Future use |
| directions | `String` | Internal |
| dirsales | `String` | Future use |
| disableLoginYn | `String` | LOGIN into the application is disabled. |
| downloadRestYn | `String` | Download Rest Y/N |
| dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| email | `String` | Email |
| endDate | `Date` | End Date |
| exchangePostingType | `String` | Exchange Posting Type |
| expHotelCode | `String` | Hotel code used for third party exports |
| expiryDate | `Date` | Expiry Date |
| extExpFileLocation | `String` | Future use |
| extPropertyCode | `String` | Future use |
| externalScYn | `String` | Indicates that the property uses an external SC system. |
| fax | `String` | Fax |
| faxNoFormat | `String` | Fax number formats. |
| fileTransferFormat | `String` | Not used. |
| fiscalEndDate | `Date` | Future use |
| fiscalPeriodType | `String` | Future use |
| fiscalStartDate | `Date` | Future use |
| flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| floorNumExecutiveFloor | `String` | Floor number of executive floor. |
| flowCode | `String` | Future use |
| fnsTier | `String` | Property Free Nights Stay Tier. |
| folioLanguage1 | `String` | Other languages |
| folioLanguage2 | `String` | Other languages |
| folioLanguage3 | `String` | Other languages |
| folioLanguage4 | `String` | Other languages |
| font | `Float` | Not used |
| genmgr | `String` | Future use |
| groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| guestLookupTimeout | `Float` | Future use |
| hotelCode | `String` | Property Code. |
| hotelFc | `String` | Future use |
| hotelId | `String` | Hotel ID |
| hotelType | `String` | Hotel Type |
| hub | `String` | HUB |
| imgDirectionId | `Float` | Future use |
| imgHotelId | `Float` | Future use |
| imgMapId | `Float` | Future use |
| inactiveDaysForGuestProfil | `Float` | Future use |
| individualAddressType | `String` | Future use |
| individualPhoneType | `String` | Future use |
| individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| intTaxIncludedYn | `String` | Int Tax Included Y/N |
| inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| latitude | `Float` | Latitude of the property in decimal |
| leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| legalOwner | `String` | The owner who owns this property |
| licenseCode | `String` | License Code |
| longDateFormat | `String` | Long date format for the property. |
| longStayControl | `Float` | The default length of stay |
| longitude | `Float` | Longitude of the property in decimal |
| maxAdultsFamilyRoom | `Float` | Maximum adults in family rooms. |
| maxChildrenFamilyRoom | `Float` | Maximum children in family rooms. |
| maxCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| maxNoNights | `Float` | Not used |
| maxOccupancy | `Float` | Max Occupancy |
| mbsSupportedYn | `String` | Indicates if the property supports MBS. Used in some file exports. |
| meetRooms | `Float` | Future use |
| meetSeats | `Float` | Future use |
| meetSpace | `Float` | Future use |
| meetingFc | `String` | Future use |
| minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| name | `String` | Name |
| nameIdLink | `Float` | Internal |
| nightAuditCashierId | `String` | Future use |
| notes | `String` | Notes |
| numberBeds | `Float` | Total number of beds in this property |
| numberFloors | `Float` | Total number of floors in this property |
| numberRooms | `Float` | Number Rooms |
| opusCurrencyCode | `String` | Future use |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownership | `String` | Future use |
| packageLoss | `String` | Package Loss code for a particular package |
| packageProfit | `String` | Package Profit code for a particular Package |
| passerbyMarket | `String` | Market code for passerby |
| passerbySource | `String` | Source code for passerby |
| path | `String` | Path |
| pathId | `Float` | This is the value used in Interfaces to map  to a Resort Code. |
| paymentDate | `Date` | Payment Date |
| perReservationRoomLimit | `Float` | Future use |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| propMapUrl | `String` | Property MAP URL. |
| propPicUrl | `String` | Property picture URL. |
| propinfoUrl | `String` | URL where property information is located. |
| qtyConnectingRooms | `Float` | Number of connecting rooms. |
| qtyDoubleRooms | `Float` | Number of double rooms. |
| qtyFamilyRooms | `Float` | Number of family rooms. |
| qtyGuestElevators | `Float` | Number of guest elevators. |
| qtyGuestRoomFloors | `Float` | Total of guest rooms floors. |
| qtyHandicappedRooms | `Float` | Number of handicapped rooms. |
| qtyNonSmokingRooms | `Float` | Number of non smoking rooms. |
| qtySingleRooms | `Float` | Number of single rooms. |
| qtySuites | `Float` | Number of suites. |
| qtyTwinRooms | `Float` | Number of twin rooms. |
| quotedCurrency | `String` | Future use |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reconcileDate | `Date` | Records the date on which the reconciliation is done |
| regionCode | `String` | Region Code |
| resortType | `String` | Property Type |
| restaurant | `Float` | Future use |
| rhythmSheets | `Float` | Total number of Sheets |
| rhythmTowels | `Float` | Total number of Towels |
| roomAmenity | `String` | Room amenity. |
| saveProfiles | `Float` | To store number of days before deleting the gest profile |
| scriptId | `Float` | Script ID |
| season1 | `String` | Future use |
| season2 | `String` | Future use |
| season3 | `String` | Future use |
| season4 | `String` | Future use |
| season5 | `String` | Future use |
| sendLeadAsBookingYn | `String` | Indicates that the property accepts leads as bookings. |
| sglNum | `String` | Future use |
| sglRate1 | `Float` | Future use |
| sglRate2 | `Float` | Future use |
| shopDescription | `String` | Shop description. |
| shortDateFormat | `String` | Short date format for the property. |
| sourceCommission | `String` | For default commission percentage |
| state | `String` | State |
| street | `String` | The street of the property. |
| suiNum | `String` | Future use |
| suiRate1 | `Float` | Future use |
| suiRate2 | `Float` | Future use |
| summCurrencyCode | `String` | Internal |
| taCommission | `String` | For default commission percentage |
| telephone | `String` | The direct dial phone number of this property |
| telephoneNoFormat | `String` | Formats for telephone number |
| thousandSeparator | `String` | Separator for monetory values |
| timeFormat | `String` | Default time format for the property. |
| timeZone | `String` | Time zone region selected by the employee. |
| tollFree | `String` | Toll free telephone number. |
| totalRooms | `Float` | Future use |
| touristNumber | `String` | Tourist Number |
| tplNum | `String` | Future use |
| tplRate1 | `Float` | Future use |
| tplRate2 | `Float` | Future use |
| translateMulticharYn | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| turnawayCode | `String` | Turnaway Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vatId | `String` | VAT ID of this property. |
| videoCoStart | `Date` | Video check out start time. |
| videoCoStop | `Date` | Video check out end time. |
| videocheckoutPrinter | `String` | Future use |
| wakeUpDelay | `Float` | Future use |
| warningAmount | `Float` | Amount at which warning is raised. |
| webaddress | `String` | Webaddress of the property |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| xresortNumber | `Float` | Numbers (1 thru 10) given to the resorts in the schema to print the tax collected by that resort in the gstfolio when proper merge codes are selected. |
| zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### ConfigurationChainNoteTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultNoteText | `String` | Stores the default note text. |
| defaultNoteTextYN | `String` | Specifies if the note type has default note to be populated when selected. |
| defaultNoteTypeYN | `String` | Default Note Type YN |
| deletedFlag | `String` | Deleted Flag |
| deptNoteYn | `String` | Indicate if the note is for departments. |
| globalYn | `String` | Global Y/N |
| helpText | `String` | Hel text for notes. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| internalDeletedflag | `String` | Deleted Flag |
| internalYN | `String` | Internal YN |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| noteClass | `String` | User defined note class. |
| noteType | `String` | Note Type |
| noteTypeCode | `String` | Note Type Code |
| noteTypeDescription | `String` | Note Type Description |
| notesGroup | `String` | Notes Group |
| notetypeid | `String` | Notetypeid |
| notetypepmsref | `String` | Notetypepmsref |
| notificationAreas | `String` | Comma separated list of areas where this notification will be shown. Possible values are 'PROFILE' 'CHECK IN' 'RESERVATION' 'CHECK OUT' 'NEVER'. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideInternalYN | `String` | Changing internal_yn is allowed for Y and changing internal_yn is not allowed for N while creating/modifying notes. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| protectDescriptionYn | `String` | Indicates whether the description can be modified by the user or not |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| webProposalYn | `String` | Determines if notes of this note type will be included in the webProposal XML. |

[⬆ Back to Query](#query)

---

### ConfigurationChainPropertyTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainForeignCurrencyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| abbreviation | `String` | Abbreviation |
| activeYN | `String` | Active YN |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| currencyActionId | `Float` | Curr Action ID |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| decimals | `Float` | Decimals |
| deletedFlag | `String` | Deleted Flag |
| foreignCurrencyID | `String` | Foreign Currency ID |
| formatMask | `String` | Format Mask |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| mobileYn | `String` | Indicates if this Currency Exchange Rate is available for consumer mobility. |
| multiply | `Float` | Multiply |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| previousLocalCurrencyYn | `String` | This will be significant after EURO conversion. The currency before the Euro conversion gets a value Y. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sellCurrency | `String` | Indicates whether this currency code can be sold though currency exchange. |
| trianMethodYn | `String` | Indicates whether the currency is Euro participant. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| usedForCcPaymentsYn | `String` | Indicates if this currency can be used for Credit Card payments. |

[⬆ Back to Query](#query)

---

### ConfigurationChainItemRateRulesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| codeId | `Float` | Code ID |
| codeType | `String` | Code Type |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayYn | `String` | Display Y/N |
| fulldayYn | `String` | Specifies that the space is not available for this setup style for the entire day. |
| inactiveDate | `DateTime` | Inactive Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportingCodeId | `String` | Rep Code ID |
| sequence | `Float` | Sequence |
| webBookingYn | `String` | Web Booking Y/N |
| webSetdown | `Float` | Setdown Time for web bookings. |
| webSetup | `Float` | Setup Time for web bookings. |

[⬆ Back to Query](#query)

---

### ConfigurationChainPostalCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| country | `String` | Country |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| description | `String` | Description |
| district | `String` | District |
| fiscalRegion | `String` | Fiscal Region |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| postalCodeFrom | `String` | The Beginning Postal Code Range for this state. |
| postalCodeTo | `String` | The ending Postal Code for the State. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| regionCode | `String` | Region Code |
| scity | `String` | Uppercase value of CITY column. |
| seq | `Float` | Sequence |
| state | `String` | State |
| territory | `String` | Territory code related to this Postal Code. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainIDDocumentTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| checkForDuplicatesYn | `String` | Check for Duplicates flag. |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| iDRole | `String` | Possible values are: PASSPORT DRIVER_LICENSE VISA ID UNKNOWN or NULL. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainLanguageDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description for each language code. |
| enrollmentAltYn | `String` | Indicates if this language is a valid Alternate Language for Enrollment / Lookup. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locale | `String` | Specific geographic political or cultural region (used in the OperaXMLP Java servlet for translation and formatting) |
| nativeWritingSystem | `String` | Type of characters that this language uses i.e.: LATIN ARABIC CYRILLIC CHINESE_CANTONESE or CHINESE_MANDARIN. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| preferredLanguageAdV5 | `String` | Preferred Language for Return Addresses. Used for Address Cleansing using AddressDoctor V5. |
| preferredScriptAdV5 | `String` | Character set used for the returned address. Used for Address Cleansing using AddressDoctor V5. |
| preferredlanguage | `String` | Language of the Returned address. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reportDateLanguage | `String` | NLS_DATE_LANGUAGE code used in Reports |
| translationLanguage | `String` | ISO Country code |

[⬆ Back to Query](#query)

---

### ConfigurationChainRegionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| regionDescription | `String` | Region Description |
| regionid | `String` | Regionid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainStateDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| country | `String` | Country |
| countryid | `String` | Countryid |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| stateCode | `String` | State Code |
| stateid | `String` | Stateid |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipClassDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Primary key of this table |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| frequentFlyerYN | `String` | Frequent Flyer YN |
| inactiveflag | `Float` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| loyaltyProgramYN | `String` | Loyalty Program YN |
| membershipclassid | `String` | Membershipclassid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainConfirmationFormatDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Primary key column for the table |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| formatDefinition | `String` | The format definition which includes the elements of address. |
| formatType | `String` | Format Type |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| salesAddressFormatYN | `String` | Sales Address Format YN |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainCommunicationTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| role | `String` | Role |
| sequence | `Float` | Sequence |
| textMessagingEnabledYN | `String` | Indicate if SMS text messages can be send via this communication type. |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainProfilePreferenceTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowSubTypesYn | `String` | Indicates if Sub Types are allowed. |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| quantity | `Float` | Maximum quantity of preferences which can be selected for this preference type. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reservationYN | `String` | Indicator whether this preference type can be used in reservations. |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainProfileProfileDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| name | `String` | Set of words that represent a profile name. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainConfigurationRelationshipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromDescription | `String` | From Description |
| fromRelationshipCode | `String` | From Relationship Code |
| fromRelationshipType | `String` | From Relationship Type. |
| globalYn | `String` | Global Y/N |
| hasHierarchyYN | `String` | Has Hierarchy YN |
| ignoreProtectionYn | `String` | Indicates if custom profile protection is not applicable for this relationship type. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| individualflag | `String` | Individualflag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryflag | `String` | Primaryflag |
| rate | `String` | Rate |
| relationCategory | `String` | Module related to this Name Type whether it is used in PMS S&C etc. |
| relationshipId | `String` | Relationship ID |
| relationshipRole | `String` | Used in S&C Module |
| relationshippms | `String` | Relationshippms |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| tempFlag | `String` | Temp Flag |
| toDescription | `String` | Description of the To Relationship. |
| toRelationshipCode | `String` | To Relationship type. |
| toRelationshipType | `String` | To Relationship Type |
| toindividualflag | `String` | Toindividualflag |
| toinheritratesflag | `String` | Toinheritratesflag |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipClaimTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| claimTypeCode | `String` | Claim Type Code |
| claimTypeDescription | `String` | Claim Type Description |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipAwardsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| autoConsumeYn | `String` | Indicates if award consumtion is tracked  by the system. If value is Y then system keeps a track of availability of award after it is issued. |
| awardBasedOn | `String` | Indicates if the Award is a Stay Pkg Element or other. |
| awardBasedOnDesc | `String` | Award Based On Desc |
| awardCode | `String` | Award Code |
| awardDescription | `String` | Award Description |
| awardQuantity | `Float` | Enter a number to indicate the number of awards to be given. |
| awardValue | `Float` | Value of the award in central currency. |
| billingGroup | `String` | Billing Group |
| cAwardValue | `Float` | Central Award Value |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cancelPenaltyChargePoints | `Float` | Number points deducted is award is cancelled. |
| cancelPenaltyDays | `Float` | Number days before arrival to apply penalty for cancellation. |
| cancelPenaltyType | `String` | Cancel Penalty Type |
| cancelPolicyType | `String` | Cancel Policy Type |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displaySet | `String` | Display Set |
| endSellDate | `Date` | End Sell Date |
| exchangeRateType | `String` | Exchange Rate Type |
| forceVerificationYn | `String` | Force verification whether Rate or Product for the Award is valid at reservation. |
| ignoreFtTransactionYN | `String` | This column identify that should we ignore Financial transactions in OPERA or not? Y -  Financial transaction is not required in OPERA while giving award as it may be recorded in some external system and only points accounting is done in OCIS. |
| inactiveDate | `Date` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| maxPercentAllowed | `Float` | Max percent of total value to be allowed to convert money to points. |
| membershipLevel | `String` | Membership Level |
| membershipType | `String` | Membership Type |
| messageLine1 | `String` | Message for Other awards. |
| messageLine2 | `String` | Message for Other awards. |
| messageLine3 | `String` | Message for Other awards. |
| messageLine4 | `String` | Message for Other awards. |
| nightsYN | `String` | Nights YN |
| numberOfNights | `Float` | Number of Nights |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pointsRequired | `Float` | Points Required |
| pointsRequiredDesc | `Float` | Points Required Desc |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| ptsSchCode | `String` | Pts Sch Code |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| roomCategoryGroupYN | `String` | Indicates if the membership award upgrade is based on room category (N) or room category group (Y). |
| sequence | `Float` | Sequence |
| startSellDate | `Date` | Start Sell Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipEnrollDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attachedEnrollmentCode | `String` | Code to indicate source used to enroll the member. |
| attachedEnrollmentDescription | `String` | Attached Enrollment Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| memEnrollGroup | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| membershipenrollid | `String` | Membershipenrollid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipLevelDetailsType

| Field | Type | Description |
| --- | --- | --- |
| autoRenewalAfter | `String` | Auto-Renewal After |
| centralVIPCode | `String` | Central VIP Code |
| centralVIPCodeDescription | `String` | Central VIP Code Description |
| chainCode | `String` | Chain Code |
| changesRestrictedYN | `String` | Indicates whether a change to this level is restricted once a guest attains this level. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColorCode | `String` | Display Color Code |
| displayColorDescription | `String` | Display Color Description |
| doubleDippingYN | `String` | Double Dipping YN |
| expiryPeriod | `Float` | Number of years card will be valid for this level. |
| fulfillmentYN | `String` | Fulfillment YN |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| levelCode | `String` | Level Code |
| maxDowngradeLevel | `String` | Used in EIS Module. |
| maxDowngradeLevelDescription | `String` | Max. Downgrade Level Description |
| membershipType | `String` | Membership Type |
| membershiplevelid | `String` | Membershiplevelid |
| membershiplevelpmsref | `String` | Membershiplevelpmsref |
| membershiptypeid | `String` | Membershiptypeid |
| numberOfTrx | `Float` | Number of transaction(s) for each stay. Value will be 2 in case of double dipping otherwise it will be null or 1. |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rank | `Float` | The sequence of membership levels starting with 1 (The starting level) and increasing to the highest level. |
| renewCardOnStayYN | `String` | Renew Card on Stay YN |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vIPCode | `String` | VIP Code |
| vIPCodeDescription | `String` | VIP Code Description |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipCardRangesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cardRangeFrom | `String` | Start range of credit card no |
| cardRangeTo | `String` | End range of credit card no |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipLevelBenefitsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromDate | `Date` | From Date |
| inactiveDate | `Date` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| levelCode | `String` | Link to benefit code. |
| levelDescription | `String` | Level Description |
| membershipType | `String` | Membership Type |
| minimumMembershipLevel | `String` | Min value for membership level. This is the minumum membership level member gets for enrolling into this program. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| toDate | `Date` | To Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipMarketGroupCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attachedMarketCodes | `String` | Attached Market Codes |
| attachedMarketDescription | `String` | Attached Market Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| memMarketGroup | `String` | Membership Market Group |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRateGroupCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attachedRateCode | `String` | Attached Rate Code |
| attachedRateCodeDescription | `String` | Attached Rate Code Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| memRateGroup | `String` | Membership Rate Group |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainMembershipRevenueGroupCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attachedRevenueGroupCode | `String` | Revenue Types defined for OIS memberships. |
| attachedRevenueGroupDescription | `String` | Attached Revenue Group Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| memRevenueGroup | `String` | Membership rate group. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationChainPropertyBookingStatusNextDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| chainCode | `String` | Chain Code |
| code | `String` | Next status of the status column |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| status | `String` | Status |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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