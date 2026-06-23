# ProfilesLoyaltyTransactions
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `profilesLoyaltyTransactions`
> Detailed information on the Loyalty Program providing details on the Membership Profiles Stay Information and the ability to track Awards.
  
**Return:** [`[ProfilesLoyaltyTransactionsType]`](#profilesloyaltytransactionstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesLoyaltyTransactionsQueryArgumentsType!`](#profilesloyaltytransactionsqueryargumentstype) |  |

## Object Types

### ProfilesLoyaltyTransactionsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | membershipTransactionsDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionsDetailsType`](#profilesloyaltytransactionsmembershiptransactionsdetailstype) | Membership Transactions Details |
| 2 | loyaltyProfileMembershipDetails | [`ProfilesLoyaltyTransactionsLoyaltyProfileMembershipDetailsType`](#profilesloyaltytransactionsloyaltyprofilemembershipdetailstype) | Loyalty Profile Membership Details |
| 3 | membershipRejectCommentsDetails | [`ProfilesLoyaltyTransactionsMembershipRejectCommentsDetailsType`](#profilesloyaltytransactionsmembershiprejectcommentsdetailstype) | Membership Reject Comments Details |
| 4 | membershipTransactionRevenuesDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionRevenuesDetailsType`](#profilesloyaltytransactionsmembershiptransactionrevenuesdetailstype) | Membership Transaction Revenues |
| 5 | membershipTransactionDailyRatesDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionDailyRatesDetailsType`](#profilesloyaltytransactionsmembershiptransactiondailyratesdetailstype) | Membership Transaction Daily Rates |
| 6 | propertyPropertyDetails | [`ProfilesLoyaltyTransactionsPropertyPropertyDetailsType`](#profilesloyaltytransactionspropertypropertydetailstype) | Resort Details |
| 7 | profilesLoyaltyTransactionsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentYn | `String` | Adjustment Y/N |
| 2 | arrivalDate | `Date` | Arrival Date |
| 3 | automaticYn | `String` | Points calculated automatically |
| 4 | averageRateAmount | `Float` | Average Rate Amount |
| 5 | awardOrderNo | `Float` | Unique Identifier assigned to that award |
| 6 | awardRequestId | `Float` | Unique award request id. |
| 7 | baseBillingGroup | `String` | Billing group for base award points. |
| 8 | baseNights | `Float` | Base Nights |
| 9 | basePoints | `Float` | Base Points |
| 10 | baseRevenue | `Float` | Base Revenue |
| 11 | baseStay | `Float` | Base Stay |
| 12 | billingGroup | `String` | Billing Group |
| 13 | bonusBillingGroup | `String` | Billing group for bonus award points. |
| 14 | bonusNights | `Float` | Bonus Nights |
| 15 | bonusPoints | `Float` | Bonus Points |
| 16 | bonusRevenue | `Float` | Bonus Revenue |
| 17 | bonusStay | `Float` | Bonus Stay |
| 18 | bookedRoomLabel | `String` | Booked Room Label |
| 19 | cExchangeDate | `Date` | Central Xchange Date |
| 20 | cExchangeRate | `Float` | Central Xchange Rate |
| 21 | cTotalEligibleCreditEarn | `Float` | Central Total Eligible Credit Earn |
| 22 | cTotalRevenue | `Float` | Central Total Revenue |
| 23 | cRSBookingNumber | `String` | CRS Booking Number |
| 24 | centralBaseRevenue | `Float` | Central Base Revenue |
| 25 | centralBonusRevenue | `Float` | Central Bonus Revenue |
| 26 | centralPointsCost | `Float` | Central Points Cost |
| 27 | chainCode | `String` | Chain Code |
| 28 | claimAdjLimitCode | `String` | Claim Adj Limit Code |
| 29 | currencyCode | `String` | Currency Code |
| 30 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 31 | dataExportedDate | `Date` | Date when the record was exported. |
| 32 | dataExportedYn | `String` | Flag to indicate if record was exported. |
| 33 | deletedFlag | `String` | Deleted Flag |
| 34 | departureDate | `Date` | Departure Date |
| 35 | exceptionType | `String` | Exception Type |
| 36 | exchRateId | `Float` | Exchange rate ID for 'TRF' transactions. |
| 37 | expirationDate | `DateTime` | Point Expiration date. |
| 38 | graceRenewalFlg | `String` | This flag indicate if grace renewals was done. |
| 39 | inactiveDate | `Date` | Inactive Date |
| 40 | insertDate | `DateTime` | Insert Date |
| 41 | insertUser | `Float` | Insert User |
| 42 | jRNUpdateDate | `Date` | JRN Update Date |
| 43 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 44 | memberStatementId | `Float` | Member Statement ID |
| 45 | membershipCardNo | `String` | Membership Card Number |
| 46 | membershipId | `Float` | Membership ID |
| 47 | membershipLevel | `String` | Membership Level |
| 48 | membershipTransactionId | `Float` | Membership Trx ID |
| 49 | membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| 50 | membershipType | `String` | Membership Type |
| 51 | miscPoints | `Float` | Miscellaneous Points |
| 52 | multipleMembershipId | `Float` | Multiple Membership ID |
| 53 | nameId | `Float` | Name ID |
| 54 | newMemberLevel | `String` | Used in membership tier upgrade rule to indicate new membership level. |
| 55 | nights | `Float` | Nights |
| 56 | nightsNo | `Float` | Nights Number |
| 57 | notes | `String` | Notes |
| 58 | oldBalancePoints | `Float` | Points prior to this transaction |
| 59 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 60 | origMemberLevel | `String` | Used in membership tier upgrade rule to indicate original member level was upgraded to. |
| 61 | origPointsExpirationDate | `DateTime` | Date when points expired before it was extended. |
| 62 | pMSReservationNo | `String` | PMS Reservation Number |
| 63 | parentMembershipTransactionId | `Float` | Ref to parent transaction. |
| 64 | pmsNameId | `String` | Pms Name ID |
| 65 | pmsReservationNameId | `String` | Pms Resv Name ID |
| 66 | pointsAcYn | `String` | Iindicate membership exceptions of back to back stay and multiple rooms. Valid values are YN and E. |
| 67 | pointsCalculationYN | `String` | Flag to indicate if points are calculated. |
| 68 | pointsCost | `Float` | Points Cost |
| 69 | pointsCreditDate | `Date` | Date when points were created. |
| 70 | pointsRejectedReason | `String` | Point reject reason. |
| 71 | pointsRule | `String` | Rule code for adjustment transactions. |
| 72 | populationMethod | `String` | Population Method |
| 73 | posCode | `String` | Pos Code |
| 74 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 75 | processingMessages | `String` | Any error messages generated during calculation. |
| 76 | profilePromotion1 | `String` | Profile Promotion 1 |
| 77 | profilePromotion2 | `String` | Profile Promotion 2 |
| 78 | property | `String` | Code to uniquely identify the Property |
| 79 | qualifyingNights | `Float` | Number of membership qualifying nights on a reservation. |
| 80 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 81 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 82 | ratePromotionCode | `String` | Rate Promotion Code |
| 83 | ratePromotionDescription | `String` | Rate Promotion Description |
| 84 | recordTypeCode | `String` | Record Type Code |
| 85 | recordTypeDescription | `String` | Record Type Description |
| 86 | reference | `String` | Reference |
| 87 | reservationNameID | `Float` | Reservation Name ID |
| 88 | reservationStatus | `String` | Reservation Status |
| 89 | roomLabel | `String` | Room Label |
| 90 | statementId | `Float` | Statement ID |
| 91 | stay | `Float` | Total stay. |
| 92 | stayRecordId | `Float` | Stay Record ID |
| 93 | tierAction | `String` | Type of action performed. |
| 94 | totalEligibleAwardRedeem | `Float` | Total monetary value of transactions on the guest account eligible to redeem Instant Award payments. |
| 95 | totalEligibleCreditEarn | `Float` | Total monetary value of transactions on the guest account eligible to earn membership credits. |
| 96 | totalPoints | `Float` | Total Points |
| 97 | totalRevenue | `Float` | Total Revenue |
| 98 | transactionDate | `Date` | Transaction date. |
| 99 | transactionType | `String` | Transaction Type |
| 100 | updateDate | `DateTime` | Update Date |
| 101 | updateUser | `Float` | Update User |
| 102 | username | `String` | Username |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsLoyaltyProfileMembershipDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowAdhocMultiplierYn | `String` | Indicates if program allows Ad Hoc multipliers for points calculation. |
| 2 | allowDupCardYn | `String` | Allow Dup Card Y/N |
| 3 | allowSharesYn | `String` | Flag indicating if points should be calculated for shared rooms. |
| 4 | autoCardNoBasedOn | `String` | This is used when the card no is auto generated and is based on some other value  like enrollment code. |
| 5 | awardGenerationMethod | `String` | Not used |
| 6 | batchDelayPeriod | `Float` | Not used |
| 7 | bookerProgramYn | `String` | Flag to mark the booker program membership types. |
| 8 | cCostPerPoint | `Float` | Central Cost Per Point |
| 9 | cCreditLimit | `Float` | Central Credit Limit |
| 10 | cExchangeDate | `Date` | Central Xchange Date |
| 11 | cExchangeRate | `Float` | Central Xchange Rate |
| 12 | cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| 13 | calculationMethod | `String` | Valid values are ROLLING or CALENDAR.Rolling ? Indicates the membership will run from the same month for a determined amount of time.Calendar ? Indicates the calculation will occur every year at the end of the year. |
| 14 | calculationMonths | `Float` | This signifies the number of months that points are valid for a membership type |
| 15 | canDeleteYn | `String` | Can Delete Y/N |
| 16 | cardLength | `Float` | The length of the card number for default card validation. |
| 17 | cardPrefix | `String` | Card Prefix |
| 18 | cardValidYears | `Float` | Number of years card will be valid for this level. |
| 19 | centralSetupYn | `String` | Indicates if program is managed centrally or at Local property. If central then points will be calculated at ECIS else if program is local then points will be calculated and stored locally. |
| 20 | chainCode | `String` | Chain Code |
| 21 | changesRestrictedYn | `String` | Indicates whether a change to this level is restricted once a guest attains this level. |
| 22 | chipAndPinYn | `String` | Indicates if this membership type is Chip and Pin. |
| 23 | comments | `String` | Comments |
| 24 | costPerPoint | `Float` | Cost Per Point |
| 25 | creditLimit | `Float` | Credit Limit |
| 26 | currencyCode | `String` | Currency Code |
| 27 | currentPoints | `Float` | Used in the EIS Module. |
| 28 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 29 | defaultMemStatus | `String` | Default value for membership status. |
| 30 | deletedFlag | `String` | Deleted Flag |
| 31 | deviceCode | `String` | Device Code |
| 32 | deviceDisableDate | `Date` | Date when device was disabled. |
| 33 | displayColor | `String` | Display Color |
| 34 | downgrade | `String` | Downgrade |
| 35 | downgradePeriod | `Float` | Number of months to consider for downgrade. |
| 36 | earningPreference | `String` | Earning Preference |
| 37 | enrolledAt | `String` | Resort/CRO where enrollment is done. |
| 38 | enrollmentCode | `String` | Code to indicate source used to enroll the member. |
| 39 | enrollmentCodeReqYn | `String` | Enrollment code required flag. |
| 40 | enrollmentDescription | `String` | Enrollment Description |
| 41 | enrollmentSource | `String` | Source from where the enrollment is done. |
| 42 | exceptionType | `String` | Exception Type |
| 43 | exchangeRateType | `String` | Exchange Rate Type |
| 44 | excludeFromBatch | `String` | Flag to determine member actions to include in the fulfillment extract |
| 45 | expiration | `Date` | Expiration date of the Card. |
| 46 | expirationDateRequired | `String` | Expiration Date Required |
| 47 | expirationMonth | `Float` | Expiration month for membership types having a ROLLING calculation method. |
| 48 | externalProcessDays | `Float` | Maximum number of days to process the External Processing Exception. |
| 49 | externallyControlledYn | `String` | Flag that affects how a Membership Type is added edited or deleted from a profile. |
| 50 | folioMessage | `String` | Free form text that can ve configured to display on the folio of clients earning points under this program. |
| 51 | folioMessageCredits | `String` | Folio Message for Credits. |
| 52 | folioMessageNonmembers | `String` | Folio Message Nonmembers |
| 53 | folioMessageNonmembersNq | `String` | Folio message for non members who have a non-qualifying rate code. |
| 54 | folioMessageNq | `String` | Folio message for members who have a non-qualifying rate code. |
| 55 | fulfillmentYn | `String` | Fulfillment Y/N |
| 56 | fulfilmentYn | `String` | Fulfilment Y/N |
| 57 | graceExpirationMonth | `Float` | Used in EIS Module. |
| 58 | gracePeriodIndicator | `String` | Grace Period Indicator |
| 59 | inactiveDate | `DateTime` | Inactive Date |
| 60 | inactiveYN | `String` | Inactive YN |
| 61 | insertDate | `DateTime` | Insert Date |
| 62 | insertUser | `String` | Insert User |
| 63 | jRNUpdateDate | `Date` | JRN Update Date |
| 64 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 65 | joinDate | `Date` | Used by EIS Module. |
| 66 | label | `String` | Label |
| 67 | levelRequired | `String` | Level Required |
| 68 | loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| 69 | maxDowngradeLevel | `String` | Used in EIS Module. |
| 70 | mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| 71 | memClassDescription | `String` | Membership Class Description |
| 72 | memClassInsertDate | `DateTime` | Membership Class Insert Date |
| 73 | memClassInsertUser | `Float` | Membership Class Insert User |
| 74 | memClassUpdateDate | `DateTime` | Membership Class Update Date |
| 75 | memClassUpdateUser | `Float` | Membership Class Update User |
| 76 | memLevelDeletedFlag | `String` | Membership Level Deleted Flag |
| 77 | memLevelInactiveDate | `DateTime` | Membership Level Inactive Date |
| 78 | memLevelInsertDate | `DateTime` | Membership Level Insert Date |
| 79 | memLevelInsertUser | `Float` | Membership Level Insert User |
| 80 | memLevelUpdateDate | `DateTime` | Membership Level Update Date |
| 81 | memLevelUpdateUser | `Float` | Membership Level Update User |
| 82 | memTypeCardValidYears | `Float` | Membership Type Card Valid Years |
| 83 | memTypeInactiveDate | `DateTime` | Membership Type Inactive Date |
| 84 | memTypeInsertDate | `DateTime` | Membership Type Insert Date |
| 85 | memTypeInsertUser | `Float` | Membership Type Insert User |
| 86 | memTypeOrderBy | `Float` | Membership Type Order By |
| 87 | memTypeUpdateDate | `DateTime` | Membership Type Update Date |
| 88 | memTypeUpdateUser | `Float` | Membership Type Update User |
| 89 | memberIndicator | `String` | Used in the EIS Module. |
| 90 | memberInfoDispSet | `String` | Display set used for member info. |
| 91 | memberName | `String` | Not Used |
| 92 | memberStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| 93 | memberSubtype | `String` | Used in the EIS Module. |
| 94 | membershipAction | `String` | [A]utopopulate on Reservation [P]rompt on Reservation; Al[W]ays Prompt [N]o action. |
| 95 | membershipCardNumber | `String` | Membership Card Number |
| 96 | membershipClass | `String` | Primary key of this table |
| 97 | membershipId | `Float` | Membership ID |
| 98 | membershipLevel | `String` | Membership Level |
| 99 | membershipLevelCExchangeDate | `Date` | Mem Level Central Xchange Date |
| 100 | membershipLevelCExchangeRate | `Float` | Mem Level Central Xchange Rate |
| 101 | membershipLevelDesc | `String` | Membership Level Description |
| 102 | membershipLevelRank | `Float` | The sequence of membership levels starting with 1 (The starting level) and increasing to the highest level. |
| 103 | membershipType | `String` | Membership Type |
| 104 | membershipTypeCExchangeDate | `Date` | Mem Type Central Xchange Date |
| 105 | membershipTypeCExchangeRate | `Float` | Mem Type Central Xchange Rate |
| 106 | membershipTypeDesc | `String` | Membership Type Description |
| 107 | multipleRoomsLimit | `Float` | Multiple rooms allowed for points exception. |
| 108 | nameId | `Float` | Name ID |
| 109 | nameOnCard | `String` | Name as appeared on the Membership Card. |
| 110 | numberOfTrx | `Float` | Number of transaction(s) for each stay. Value will be 2 in case of double dipping otherwise it will be null or 1. |
| 111 | numericValidation | `String` | Indicates the type of card number validation which should be done. |
| 112 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 113 | partnerMembershipId | `Float` | Membership ID that accrues Miles. |
| 114 | pointsIssuedCentrallyYn | `String` | Indicates that points are issued by central system |
| 115 | pointsLabel | `String` | Label for points (i.e. Points or Miles) |
| 116 | preferredCardYN | `String` | Used in the EIS Module. |
| 117 | primaryAirlinePartner | `String` | Used in the EIS Module. |
| 118 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 119 | primaryMembershipYn | `String` | Primary Membership Y/N |
| 120 | processExpirationDate | `Date` | Used in the EIS Module. |
| 121 | promptAtCheckOut | `String` | Indicates if resv_memberships should popup when a reservation is checked out. |
| 122 | promptAtCheckin | `String` | Indicates if a prompt is required at checkin of a reservation if a membership number exists on profile and not attached to the reservation. |
| 123 | promptAtNewReservation | `String` | Indicates if resv_memberships should popup when a reservation is created. |
| 124 | promptAtUpdateReservation | `String` | Indicates if resv_memberships should popup when a reservation is updated. |
| 125 | rankValue | `Float` | Rank Value |
| 126 | ranking | `Float` | Ranking |
| 127 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 128 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 129 | roomAssignmentValue | `Float` | Room Assignment Value |
| 130 | sendChkoutToIfc | `String` | Send checkout reservation information to the interface for Courtesy Cards? |
| 131 | sequence | `Float` | Sequence |
| 132 | tierAdministration | `String` | Tier Administration |
| 133 | trackData | `String` | Stores key track information for a universal card that may be different than the membership number. |
| 134 | transactionMaxPoints | `Float` | Indicates the maximum points that can be accrued per membership transaction. |
| 135 | tscDateFlag | `String` | Tier Management Based on Date. |
| 136 | udfCardValidationYn | `String` | Indicates if card number validation is a UDF(User defined function) or Default validation is used. |
| 137 | udfFormula | `String` | Udf Formula |
| 138 | updateDate | `DateTime` | Update Date |
| 139 | updateUser | `String` | Update User |
| 140 | upgradePeriod | `Float` | Number of months to consider for upgrade. |
| 141 | validationByIfc | `String` | Indicates if the card is to be validated by an external system. |
| 142 | vipStatus | `String` | VIP Status |
| 143 | yearsToExpire | `Float` | Years To Expire |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipRejectCommentsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | jRNUpdateDate | `Date` | JRN Update Date |
| 6 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 7 | membershipPointsSeqno | `Float` | Membership Points Seqno |
| 8 | membershipTransactionId | `Float` | Membership Trx ID |
| 9 | membershipType | `String` | Membership Type |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | rejectionReason | `String` | Rejection Reason |
| 15 | rule | `String` | Rule |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionRevenuesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cExchangeDate | `Date` | Central Xchange Date |
| 2 | cExchangeRate | `Float` | Central Xchange Rate |
| 3 | centralCentralRevenue | `Float` | Central - Central Revenue |
| 4 | centralPMSRevenue | `Float` | Central PMS Revenue |
| 5 | centralRevenue | `Float` | Revenue calculated by Central System. |
| 6 | chainCode | `String` | Chain Code |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | date | `Date` | Date |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | pMSRevenue | `Float` | Revnue calculated by PMS. |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Code to uniquely identify the Property |
| 17 | qualifiedYN | `String` | Indicates if the revenue was qualified for any membership points. This is only for information purpose only. |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | revenueType | `String` | Transaction code. |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionDailyRatesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | bookedRoomLabel | `String` | Booked Room Label |
| 2 | cExchangeDate | `Date` | Central Xchange Date |
| 3 | cExchangeRate | `Float` | Central Xchange Rate |
| 4 | centralCentralRateAmount | `Float` | Central - Central Rate Amount |
| 5 | centralPMSRateAmount | `Float` | Central PMS Rate Amount |
| 6 | centralRateAmount | `Float` | central rate amount in the central currency |
| 7 | chainCode | `String` | Chain Code |
| 8 | currency | `String` | Currency |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | fromDate | `Date` | initial date that rate code was part of the reservation |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | marketCode | `String` | Market Code |
| 15 | membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| 16 | numberDays | `Float` | number days rate code was part of the reservation |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | pMSRateAmount | `Float` | rate code amount in the property currency |
| 19 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 20 | property | `String` | Code to uniquely identify the Property |
| 21 | pseudoYn | `String` | Pseudo Y/N |
| 22 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 23 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 24 | rateCode | `String` | Rate Code |
| 25 | resourceId | `String` | Resource ID |
| 26 | roomLabel | `String` | Room Label |
| 27 | roomNumber | `String` | Room Number |
| 28 | shareNights | `Float` | Computed share nights. |
| 29 | toDate | `Date` | To Date |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsPropertyPropertyDetailsType

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

### ProfilesLoyaltyTransactionsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| membershiptransactionsDetailsAdjustmentYn | `StringInput` | Adjustment Y/N |
| membershiptransactionsDetailsBeginDate | `DateInput!` | Arrival Date<br>`@mandatoryInput` |
| membershiptransactionsDetailsAutomaticYn | `StringInput` | Points calculated automatically |
| membershiptransactionsDetailsBaseBillingGroup | `StringInput` | Billing group for base award points. |
| membershiptransactionsDetailsBillingGroup | `StringInput` | Billing Group |
| membershiptransactionsDetailsBonusBillingGroup | `StringInput` | Billing group for bonus award points. |
| membershiptransactionsDetailsBookedRoomLabel | `StringInput` | Booked Room Label |
| membershiptransactionsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershiptransactionsDetailsCrsBookNo | `StringInput` | CRS Booking Number |
| membershiptransactionsDetailsChainCode | `StringInput` | Chain Code |
| membershiptransactionsDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |
| membershiptransactionsDetailsCurrencyCode | `StringInput` | Currency Code |
| membershiptransactionsDetailsDataExportedDate | `DateInput` | Date when the record was exported. |
| membershiptransactionsDetailsDataExportedYn | `StringInput` | Flag to indicate if record was exported. |
| membershiptransactionsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| membershiptransactionsDetailsEndDate | `DateInput!` | Departure Date<br>`@mandatoryInput` |
| membershiptransactionsDetailsExceptionType | `StringInput` | Exception Type |
| membershiptransactionsDetailsPointsExpirationDate | `DateTimeInput` | Point Expiration date. |
| membershiptransactionsDetailsGraceRenewalFlg | `StringInput` | This flag indicate if grace renewals was done. |
| membershiptransactionsDetailsInactiveDate | `DateInput` | Inactive Date |
| membershiptransactionsDetailsInsertDate | `DateTimeInput` | Insert Date |
| membershiptransactionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptransactionsDetailsMemberStatementId | `FloatInput` | Member Statement ID |
| membershiptransactionsDetailsMembershipCardNo | `StringInput` | Membership Card Number |
| membershiptransactionsDetailsMembershipId | `FloatInput` | Membership ID |
| membershiptransactionsDetailsMembershipLevel | `StringInput` | Membership Level |
| membershiptransactionsDetailsMembershipTrxId | `FloatInput` | Membership Trx ID |
| membershiptransactionsDetailsMembershipTrxLinkId | `FloatInput` | Membership Trx Link ID |
| membershiptransactionsDetailsMembershipType | `StringInput` | Membership Type |
| membershiptransactionsDetailsMultipleMembershipId | `FloatInput` | Multiple Membership ID |
| membershiptransactionsDetailsNameId | `FloatInput` | Name ID |
| membershiptransactionsDetailsNewMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate new membership level. |
| membershiptransactionsDetailsUserNotes | `StringInput` | Notes |
| membershiptransactionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptransactionsDetailsOrigMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate original member level was upgraded to. |
| membershiptransactionsDetailsOrigPointsExpirationDate | `DateTimeInput` | Date when points expired before it was extended. |
| membershiptransactionsDetailsPmsResvNo | `StringInput` | PMS Reservation Number |
| membershiptransactionsDetailsParentMembershipTrxId | `FloatInput` | Ref to parent transaction. |
| membershiptransactionsDetailsPmsNameId | `StringInput` | Pms Name ID |
| membershiptransactionsDetailsPmsResvNameId | `StringInput` | Pms Resv Name ID |
| membershiptransactionsDetailsPointsAcYn | `StringInput` | Iindicate membership exceptions of back to back stay and multiple rooms. Valid values are YN and E. |
| membershiptransactionsDetailsPointsCalculatedYn | `StringInput` | Flag to indicate if points are calculated. |
| membershiptransactionsDetailsPointsCreditDate | `DateInput` | Date when points were created. |
| membershiptransactionsDetailsPointsRejectedReason | `StringInput` | Point reject reason. |
| membershiptransactionsDetailsAdjRuleCode | `StringInput` | Rule code for adjustment transactions. |
| membershiptransactionsDetailsPopulationMethod | `StringInput` | Population Method |
| membershiptransactionsDetailsPosCode | `StringInput` | Pos Code |
| membershiptransactionsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| membershiptransactionsDetailsProcessingMessages | `StringInput` | Any error messages generated during calculation. |
| membershiptransactionsDetailsPromotionCode2 | `StringInput` | Profile Promotion 1 |
| membershiptransactionsDetailsPromotionCode3 | `StringInput` | Profile Promotion 2 |
| membershiptransactionsDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| membershiptransactionsDetailsPromotionCode1 | `StringInput` | Rate Promotion Code |
| membershiptransactionsDetailsPromotionCode1Desc | `StringInput` | Rate Promotion Description |
| membershiptransactionsDetailsRecordType | `StringInput` | Record Type Code |
| membershiptransactionsDetailsRecordTypeDesc | `StringInput` | Record Type Description |
| membershiptransactionsDetailsResvStatus | `StringInput` | Reservation Status |
| membershiptransactionsDetailsRoomLabel | `StringInput` | Room Label |
| membershiptransactionsDetailsStayRecordId | `FloatInput` | Stay Record ID |
| membershiptransactionsDetailsTierAction | `StringInput` | Type of action performed. |
| membershiptransactionsDetailsMembershipTrxDate | `DateInput` | Transaction date. |
| membershiptransactionsDetailsTransactionType | `StringInput` | Transaction Type |
| membershiptransactionsDetailsUpdateDate | `DateTimeInput` | Update Date |
| loyaltyprofilemembershipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| loyaltyprofilemembershipDetailsDeviceCode | `StringInput` | Device Code |
| loyaltyprofilemembershipDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| loyaltyprofilemembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| loyaltyprofilemembershipDetailsMembershipCardNo | `StringInput` | Membership Card Number |
| loyaltyprofilemembershipDetailsMembershipClass | `StringInput` | Primary key of this table |
| loyaltyprofilemembershipDetailsMembershipId | `FloatInput` | Membership ID |
| loyaltyprofilemembershipDetailsMembershipLevel | `StringInput` | Membership Level |
| loyaltyprofilemembershipDetailsMembershipType | `StringInput` | Membership Type |
| loyaltyprofilemembershipDetailsNameId | `FloatInput` | Name ID |
| loyaltyprofilemembershipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| loyaltyprofilemembershipDetailsPartnerMembershipId | `FloatInput` | Membership ID that accrues Miles. |
| loyaltyprofilemembershipDetailsUpdateDate | `DateTimeInput` | Update Date |
| membershiprejectcommentsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptrxrevenuesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershiptrxrevenuesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershiptrxrevenuesDetailsTransactionDate | `DateInput` | Date |
| membershiptrxrevenuesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptrxrevenuesDetailsMembershipTrxLinkId | `FloatInput` | Membership Trx Link ID |
| membershiptrxrevenuesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptrxrevenuesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| membershiptrxrevenuesDetailsTransactionRevenueType | `StringInput` | Transaction code. |
| membershiptrxdailyratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
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
- membershiptransactionsDetailsBeginDate
- membershiptransactionsDetailsEndDate
- membershiptransactionsDetailsResort


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesLoyaltyTransactions($input: ProfilesLoyaltyTransactionsQueryArgumentsType!) {
  profilesLoyaltyTransactions(input: $input) @stream {
    membershipTransactionsDetails {
      adjustmentYn
      arrivalDate
      automaticYn
      averageRateAmount
      awardOrderNo
      awardRequestId
      baseBillingGroup
      baseNights
      basePoints
      baseRevenue
      baseStay
      billingGroup
      bonusBillingGroup
      bonusNights
      bonusPoints
      bonusRevenue
      bonusStay
      bookedRoomLabel
      cExchangeDate
      cExchangeRate
      cTotalEligibleCreditEarn
      cTotalRevenue
      cRSBookingNumber
      centralBaseRevenue
      centralBonusRevenue
      centralPointsCost
      chainCode
      claimAdjLimitCode
      currencyCode
      dSI
      dataExportedDate
      dataExportedYn
      deletedFlag
      departureDate
      exceptionType
      exchRateId
      expirationDate
      graceRenewalFlg
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      memberStatementId
      membershipCardNo
      membershipId
      membershipLevel
      membershipTransactionId
      membershipTransactionLinkId
      membershipType
      miscPoints
      multipleMembershipId
      nameId
      newMemberLevel
      nights
      nightsNo
      notes
      oldBalancePoints
      organizationID
      origMemberLevel
      origPointsExpirationDate
      pMSReservationNo
      parentMembershipTransactionId
      pmsNameId
      pmsReservationNameId
      pointsAcYn
      pointsCalculationYN
      pointsCost
      pointsCreditDate
      pointsRejectedReason
      pointsRule
      populationMethod
      posCode
      primaryKeyID
      processingMessages
      profilePromotion1
      profilePromotion2
      property
      qualifyingNights
      rNAInsertDate
      rNAUpdateDate
      ratePromotionCode
      ratePromotionDescription
      recordTypeCode
      recordTypeDescription
      reference
      reservationNameID
      reservationStatus
      roomLabel
      statementId
      stay
      stayRecordId
      tierAction
      totalEligibleAwardRedeem
      totalEligibleCreditEarn
      totalPoints
      totalRevenue
      transactionDate
      transactionType
      updateDate
      updateUser
      username
    }
    loyaltyProfileMembershipDetails {
      allowAdhocMultiplierYn
      allowDupCardYn
      allowSharesYn
      autoCardNoBasedOn
      awardGenerationMethod
      batchDelayPeriod
      bookerProgramYn
      cCostPerPoint
      cCreditLimit
      cExchangeDate
      cExchangeRate
      cRoomAssignmentValue
      calculationMethod
      calculationMonths
      canDeleteYn
      cardLength
      cardPrefix
      cardValidYears
      centralSetupYn
      chainCode
      changesRestrictedYn
      chipAndPinYn
      comments
      costPerPoint
      creditLimit
      currencyCode
      currentPoints
      dSI
      defaultMemStatus
      deletedFlag
      deviceCode
      deviceDisableDate
      displayColor
      downgrade
      downgradePeriod
      earningPreference
      enrolledAt
      enrollmentCode
      enrollmentCodeReqYn
      enrollmentDescription
      enrollmentSource
      exceptionType
      exchangeRateType
      excludeFromBatch
      expiration
      expirationDateRequired
      expirationMonth
      externalProcessDays
      externallyControlledYn
      folioMessage
      folioMessageCredits
      folioMessageNonmembers
      folioMessageNonmembersNq
      folioMessageNq
      fulfillmentYn
      fulfilmentYn
      graceExpirationMonth
      gracePeriodIndicator
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      joinDate
      label
      levelRequired
      loyaltyProgramYn
      maxDowngradeLevel
      mbrprefChangedDate
      memClassDescription
      memClassInsertDate
      memClassInsertUser
      memClassUpdateDate
      memClassUpdateUser
      memLevelDeletedFlag
      memLevelInactiveDate
      memLevelInsertDate
      memLevelInsertUser
      memLevelUpdateDate
      memLevelUpdateUser
      memTypeCardValidYears
      memTypeInactiveDate
      memTypeInsertDate
      memTypeInsertUser
      memTypeOrderBy
      memTypeUpdateDate
      memTypeUpdateUser
      memberIndicator
      memberInfoDispSet
      memberName
      memberStatus
      memberSubtype
      membershipAction
      membershipCardNumber
      membershipClass
      membershipId
      membershipLevel
      membershipLevelCExchangeDate
      membershipLevelCExchangeRate
      membershipLevelDesc
      membershipLevelRank
      membershipType
      membershipTypeCExchangeDate
      membershipTypeCExchangeRate
      membershipTypeDesc
      multipleRoomsLimit
      nameId
      nameOnCard
      numberOfTrx
      numericValidation
      organizationID
      partnerMembershipId
      pointsIssuedCentrallyYn
      pointsLabel
      preferredCardYN
      primaryAirlinePartner
      primaryKeyID
      primaryMembershipYn
      processExpirationDate
      promptAtCheckOut
      promptAtCheckin
      promptAtNewReservation
      promptAtUpdateReservation
      rankValue
      ranking
      rnaInsertDate
      rnaUpdateDate
      roomAssignmentValue
      sendChkoutToIfc
      sequence
      tierAdministration
      trackData
      transactionMaxPoints
      tscDateFlag
      udfCardValidationYn
      udfFormula
      updateDate
      updateUser
      upgradePeriod
      validationByIfc
      vipStatus
      yearsToExpire
    }
    membershipRejectCommentsDetails {
      chainCode
      code
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipPointsSeqno
      membershipTransactionId
      membershipType
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      rejectionReason
      rule
    }
    membershipTransactionRevenuesDetails {
      cExchangeDate
      cExchangeRate
      centralCentralRevenue
      centralPMSRevenue
      centralRevenue
      chainCode
      dSI
      date
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipTransactionLinkId
      organizationID
      pMSRevenue
      primaryKeyID
      property
      qualifiedYN
      rNAInsertDate
      rNAUpdateDate
      revenueType
    }
    membershipTransactionDailyRatesDetails {
      bookedRoomLabel
      cExchangeDate
      cExchangeRate
      centralCentralRateAmount
      centralPMSRateAmount
      centralRateAmount
      chainCode
      currency
      dSI
      deletedFlag
      fromDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketCode
      membershipTransactionLinkId
      numberDays
      organizationID
      pMSRateAmount
      primaryKeyID
      property
      pseudoYn
      rNAInsertDate
      rNAUpdateDate
      rateCode
      resourceId
      roomLabel
      roomNumber
      shareNights
      toDate
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
membership_transactions_details_schema = {
    'adjustmentYn': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'automaticYn': pl.Utf8,
    'averageRateAmount': pl.Float64,
    'awardOrderNo': pl.Float64,
    'awardRequestId': pl.Float64,
    'baseBillingGroup': pl.Utf8,
    'baseNights': pl.Float64,
    'basePoints': pl.Float64,
    'baseRevenue': pl.Float64,
    'baseStay': pl.Float64,
    'billingGroup': pl.Utf8,
    'bonusBillingGroup': pl.Utf8,
    'bonusNights': pl.Float64,
    'bonusPoints': pl.Float64,
    'bonusRevenue': pl.Float64,
    'bonusStay': pl.Float64,
    'bookedRoomLabel': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cTotalEligibleCreditEarn': pl.Float64,
    'cTotalRevenue': pl.Float64,
    'cRSBookingNumber': pl.Utf8,
    'centralBaseRevenue': pl.Float64,
    'centralBonusRevenue': pl.Float64,
    'centralPointsCost': pl.Float64,
    'chainCode': pl.Utf8,
    'claimAdjLimitCode': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dataExportedDate': pl.Utf8,
    'dataExportedYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departureDate': pl.Utf8,
    'exceptionType': pl.Utf8,
    'exchRateId': pl.Float64,
    'expirationDate': pl.Utf8,
    'graceRenewalFlg': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'memberStatementId': pl.Float64,
    'membershipCardNo': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipTransactionId': pl.Float64,
    'membershipTransactionLinkId': pl.Float64,
    'membershipType': pl.Utf8,
    'miscPoints': pl.Float64,
    'multipleMembershipId': pl.Float64,
    'nameId': pl.Float64,
    'newMemberLevel': pl.Utf8,
    'nights': pl.Float64,
    'nightsNo': pl.Float64,
    'notes': pl.Utf8,
    'oldBalancePoints': pl.Float64,
    'organizationID': pl.Int64,
    'origMemberLevel': pl.Utf8,
    'origPointsExpirationDate': pl.Utf8,
    'pMSReservationNo': pl.Utf8,
    'parentMembershipTransactionId': pl.Float64,
    'pmsNameId': pl.Utf8,
    'pmsReservationNameId': pl.Utf8,
    'pointsAcYn': pl.Utf8,
    'pointsCalculationYN': pl.Utf8,
    'pointsCost': pl.Float64,
    'pointsCreditDate': pl.Utf8,
    'pointsRejectedReason': pl.Utf8,
    'pointsRule': pl.Utf8,
    'populationMethod': pl.Utf8,
    'posCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'processingMessages': pl.Utf8,
    'profilePromotion1': pl.Utf8,
    'profilePromotion2': pl.Utf8,
    'property': pl.Utf8,
    'qualifyingNights': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ratePromotionCode': pl.Utf8,
    'ratePromotionDescription': pl.Utf8,
    'recordTypeCode': pl.Utf8,
    'recordTypeDescription': pl.Utf8,
    'reference': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'roomLabel': pl.Utf8,
    'statementId': pl.Float64,
    'stay': pl.Float64,
    'stayRecordId': pl.Float64,
    'tierAction': pl.Utf8,
    'totalEligibleAwardRedeem': pl.Float64,
    'totalEligibleCreditEarn': pl.Float64,
    'totalPoints': pl.Float64,
    'totalRevenue': pl.Float64,
    'transactionDate': pl.Utf8,
    'transactionType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'username': pl.Utf8,
}
```
```python
loyalty_profile_membership_details_schema = {
    'allowAdhocMultiplierYn': pl.Utf8,
    'allowDupCardYn': pl.Utf8,
    'allowSharesYn': pl.Utf8,
    'autoCardNoBasedOn': pl.Utf8,
    'awardGenerationMethod': pl.Utf8,
    'batchDelayPeriod': pl.Float64,
    'bookerProgramYn': pl.Utf8,
    'cCostPerPoint': pl.Float64,
    'cCreditLimit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoomAssignmentValue': pl.Float64,
    'calculationMethod': pl.Utf8,
    'calculationMonths': pl.Float64,
    'canDeleteYn': pl.Utf8,
    'cardLength': pl.Float64,
    'cardPrefix': pl.Utf8,
    'cardValidYears': pl.Float64,
    'centralSetupYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'changesRestrictedYn': pl.Utf8,
    'chipAndPinYn': pl.Utf8,
    'comments': pl.Utf8,
    'costPerPoint': pl.Float64,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'currentPoints': pl.Float64,
    'dSI': pl.Int64,
    'defaultMemStatus': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'deviceCode': pl.Utf8,
    'deviceDisableDate': pl.Utf8,
    'displayColor': pl.Utf8,
    'downgrade': pl.Utf8,
    'downgradePeriod': pl.Float64,
    'earningPreference': pl.Utf8,
    'enrolledAt': pl.Utf8,
    'enrollmentCode': pl.Utf8,
    'enrollmentCodeReqYn': pl.Utf8,
    'enrollmentDescription': pl.Utf8,
    'enrollmentSource': pl.Utf8,
    'exceptionType': pl.Utf8,
    'exchangeRateType': pl.Utf8,
    'excludeFromBatch': pl.Utf8,
    'expiration': pl.Utf8,
    'expirationDateRequired': pl.Utf8,
    'expirationMonth': pl.Float64,
    'externalProcessDays': pl.Float64,
    'externallyControlledYn': pl.Utf8,
    'folioMessage': pl.Utf8,
    'folioMessageCredits': pl.Utf8,
    'folioMessageNonmembers': pl.Utf8,
    'folioMessageNonmembersNq': pl.Utf8,
    'folioMessageNq': pl.Utf8,
    'fulfillmentYn': pl.Utf8,
    'fulfilmentYn': pl.Utf8,
    'graceExpirationMonth': pl.Float64,
    'gracePeriodIndicator': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'joinDate': pl.Utf8,
    'label': pl.Utf8,
    'levelRequired': pl.Utf8,
    'loyaltyProgramYn': pl.Utf8,
    'maxDowngradeLevel': pl.Utf8,
    'mbrprefChangedDate': pl.Utf8,
    'memClassDescription': pl.Utf8,
    'memClassInsertDate': pl.Utf8,
    'memClassInsertUser': pl.Float64,
    'memClassUpdateDate': pl.Utf8,
    'memClassUpdateUser': pl.Float64,
    'memLevelDeletedFlag': pl.Utf8,
    'memLevelInactiveDate': pl.Utf8,
    'memLevelInsertDate': pl.Utf8,
    'memLevelInsertUser': pl.Float64,
    'memLevelUpdateDate': pl.Utf8,
    'memLevelUpdateUser': pl.Float64,
    'memTypeCardValidYears': pl.Float64,
    'memTypeInactiveDate': pl.Utf8,
    'memTypeInsertDate': pl.Utf8,
    'memTypeInsertUser': pl.Float64,
    'memTypeOrderBy': pl.Float64,
    'memTypeUpdateDate': pl.Utf8,
    'memTypeUpdateUser': pl.Float64,
    'memberIndicator': pl.Utf8,
    'memberInfoDispSet': pl.Utf8,
    'memberName': pl.Utf8,
    'memberStatus': pl.Utf8,
    'memberSubtype': pl.Utf8,
    'membershipAction': pl.Utf8,
    'membershipCardNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipLevelCExchangeDate': pl.Utf8,
    'membershipLevelCExchangeRate': pl.Float64,
    'membershipLevelDesc': pl.Utf8,
    'membershipLevelRank': pl.Float64,
    'membershipType': pl.Utf8,
    'membershipTypeCExchangeDate': pl.Utf8,
    'membershipTypeCExchangeRate': pl.Float64,
    'membershipTypeDesc': pl.Utf8,
    'multipleRoomsLimit': pl.Float64,
    'nameId': pl.Float64,
    'nameOnCard': pl.Utf8,
    'numberOfTrx': pl.Float64,
    'numericValidation': pl.Utf8,
    'organizationID': pl.Int64,
    'partnerMembershipId': pl.Float64,
    'pointsIssuedCentrallyYn': pl.Utf8,
    'pointsLabel': pl.Utf8,
    'preferredCardYN': pl.Utf8,
    'primaryAirlinePartner': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryMembershipYn': pl.Utf8,
    'processExpirationDate': pl.Utf8,
    'promptAtCheckOut': pl.Utf8,
    'promptAtCheckin': pl.Utf8,
    'promptAtNewReservation': pl.Utf8,
    'promptAtUpdateReservation': pl.Utf8,
    'rankValue': pl.Float64,
    'ranking': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'sendChkoutToIfc': pl.Utf8,
    'sequence': pl.Float64,
    'tierAdministration': pl.Utf8,
    'trackData': pl.Utf8,
    'transactionMaxPoints': pl.Float64,
    'tscDateFlag': pl.Utf8,
    'udfCardValidationYn': pl.Utf8,
    'udfFormula': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upgradePeriod': pl.Float64,
    'validationByIfc': pl.Utf8,
    'vipStatus': pl.Utf8,
    'yearsToExpire': pl.Float64,
}
```
```python
membership_reject_comments_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipPointsSeqno': pl.Float64,
    'membershipTransactionId': pl.Float64,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rejectionReason': pl.Utf8,
    'rule': pl.Utf8,
}
```
```python
membership_transaction_revenues_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralCentralRevenue': pl.Float64,
    'centralPMSRevenue': pl.Float64,
    'centralRevenue': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'date': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipTransactionLinkId': pl.Float64,
    'organizationID': pl.Int64,
    'pMSRevenue': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'qualifiedYN': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueType': pl.Utf8,
}
```
```python
membership_transaction_daily_rates_details_schema = {
    'bookedRoomLabel': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralCentralRateAmount': pl.Float64,
    'centralPMSRateAmount': pl.Float64,
    'centralRateAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fromDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketCode': pl.Utf8,
    'membershipTransactionLinkId': pl.Float64,
    'numberDays': pl.Float64,
    'organizationID': pl.Int64,
    'pMSRateAmount': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'resourceId': pl.Utf8,
    'roomLabel': pl.Utf8,
    'roomNumber': pl.Utf8,
    'shareNights': pl.Float64,
    'toDate': pl.Utf8,
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