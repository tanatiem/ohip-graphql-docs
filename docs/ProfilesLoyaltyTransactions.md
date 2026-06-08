# ProfilesLoyaltyTransactions
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
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

| Field | Type | Description |
| --- | --- | --- |
| membershipTransactionsDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionsDetailsType`](#profilesloyaltytransactionsmembershiptransactionsdetailstype) | Membership Transactions Details |
| loyaltyProfileMembershipDetails | [`ProfilesLoyaltyTransactionsLoyaltyProfileMembershipDetailsType`](#profilesloyaltytransactionsloyaltyprofilemembershipdetailstype) | Loyalty Profile Membership Details |
| membershipRejectCommentsDetails | [`ProfilesLoyaltyTransactionsMembershipRejectCommentsDetailsType`](#profilesloyaltytransactionsmembershiprejectcommentsdetailstype) | Membership Reject Comments Details |
| membershipTransactionRevenuesDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionRevenuesDetailsType`](#profilesloyaltytransactionsmembershiptransactionrevenuesdetailstype) | Membership Transaction Revenues |
| membershipTransactionDailyRatesDetails | [`ProfilesLoyaltyTransactionsMembershipTransactionDailyRatesDetailsType`](#profilesloyaltytransactionsmembershiptransactiondailyratesdetailstype) | Membership Transaction Daily Rates |
| propertyPropertyDetails | [`ProfilesLoyaltyTransactionsPropertyPropertyDetailsType`](#profilesloyaltytransactionspropertypropertydetailstype) | Resort Details |
| profilesLoyaltyTransactionsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentYn | `String` | Adjustment Y/N |
| arrivalDate | `Date` | Arrival Date |
| automaticYn | `String` | Points calculated automatically |
| averageRateAmount | `Float` | Average Rate Amount |
| awardOrderNo | `Float` | Unique Identifier assigned to that award |
| awardRequestId | `Float` | Unique award request id. |
| baseBillingGroup | `String` | Billing group for base award points. |
| baseNights | `Float` | Base Nights |
| basePoints | `Float` | Base Points |
| baseRevenue | `Float` | Base Revenue |
| baseStay | `Float` | Base Stay |
| billingGroup | `String` | Billing Group |
| bonusBillingGroup | `String` | Billing group for bonus award points. |
| bonusNights | `Float` | Bonus Nights |
| bonusPoints | `Float` | Bonus Points |
| bonusRevenue | `Float` | Bonus Revenue |
| bonusStay | `Float` | Bonus Stay |
| bookedRoomLabel | `String` | Booked Room Label |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cTotalEligibleCreditEarn | `Float` | Central Total Eligible Credit Earn |
| cTotalRevenue | `Float` | Central Total Revenue |
| cRSBookingNumber | `String` | CRS Booking Number |
| centralBaseRevenue | `Float` | Central Base Revenue |
| centralBonusRevenue | `Float` | Central Bonus Revenue |
| centralPointsCost | `Float` | Central Points Cost |
| chainCode | `String` | Chain Code |
| claimAdjLimitCode | `String` | Claim Adj Limit Code |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dataExportedDate | `Date` | Date when the record was exported. |
| dataExportedYn | `String` | Flag to indicate if record was exported. |
| deletedFlag | `String` | Deleted Flag |
| departureDate | `Date` | Departure Date |
| exceptionType | `String` | Exception Type |
| exchRateId | `Float` | Exchange rate ID for 'TRF' transactions. |
| expirationDate | `DateTime` | Point Expiration date. |
| graceRenewalFlg | `String` | This flag indicate if grace renewals was done. |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| memberStatementId | `Float` | Member Statement ID |
| membershipCardNo | `String` | Membership Card Number |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipTransactionId | `Float` | Membership Trx ID |
| membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| membershipType | `String` | Membership Type |
| miscPoints | `Float` | Miscellaneous Points |
| multipleMembershipId | `Float` | Multiple Membership ID |
| nameId | `Float` | Name ID |
| newMemberLevel | `String` | Used in membership tier upgrade rule to indicate new membership level. |
| nights | `Float` | Nights |
| nightsNo | `Float` | Nights Number |
| notes | `String` | Notes |
| oldBalancePoints | `Float` | Points prior to this transaction |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origMemberLevel | `String` | Used in membership tier upgrade rule to indicate original member level was upgraded to. |
| origPointsExpirationDate | `DateTime` | Date when points expired before it was extended. |
| pMSReservationNo | `String` | PMS Reservation Number |
| parentMembershipTransactionId | `Float` | Ref to parent transaction. |
| pmsNameId | `String` | Pms Name ID |
| pmsReservationNameId | `String` | Pms Resv Name ID |
| pointsAcYn | `String` | Iindicate membership exceptions of back to back stay and multiple rooms. Valid values are YN and E. |
| pointsCalculationYN | `String` | Flag to indicate if points are calculated. |
| pointsCost | `Float` | Points Cost |
| pointsCreditDate | `Date` | Date when points were created. |
| pointsRejectedReason | `String` | Point reject reason. |
| pointsRule | `String` | Rule code for adjustment transactions. |
| populationMethod | `String` | Population Method |
| posCode | `String` | Pos Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processingMessages | `String` | Any error messages generated during calculation. |
| profilePromotion1 | `String` | Profile Promotion 1 |
| profilePromotion2 | `String` | Profile Promotion 2 |
| property | `String` | Code to uniquely identify the Property |
| qualifyingNights | `Float` | Number of membership qualifying nights on a reservation. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ratePromotionCode | `String` | Rate Promotion Code |
| ratePromotionDescription | `String` | Rate Promotion Description |
| recordTypeCode | `String` | Record Type Code |
| recordTypeDescription | `String` | Record Type Description |
| reference | `String` | Reference |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| roomLabel | `String` | Room Label |
| statementId | `Float` | Statement ID |
| stay | `Float` | Total stay. |
| stayRecordId | `Float` | Stay Record ID |
| tierAction | `String` | Type of action performed. |
| totalEligibleAwardRedeem | `Float` | Total monetary value of transactions on the guest account eligible to redeem Instant Award payments. |
| totalEligibleCreditEarn | `Float` | Total monetary value of transactions on the guest account eligible to earn membership credits. |
| totalPoints | `Float` | Total Points |
| totalRevenue | `Float` | Total Revenue |
| transactionDate | `Date` | Transaction date. |
| transactionType | `String` | Transaction Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| username | `String` | Username |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsLoyaltyProfileMembershipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowAdhocMultiplierYn | `String` | Indicates if program allows Ad Hoc multipliers for points calculation. |
| allowDupCardYn | `String` | Allow Dup Card Y/N |
| allowSharesYn | `String` | Flag indicating if points should be calculated for shared rooms. |
| autoCardNoBasedOn | `String` | This is used when the card no is auto generated and is based on some other value  like enrollment code. |
| awardGenerationMethod | `String` | Not used |
| batchDelayPeriod | `Float` | Not used |
| bookerProgramYn | `String` | Flag to mark the booker program membership types. |
| cCostPerPoint | `Float` | Central Cost Per Point |
| cCreditLimit | `Float` | Central Credit Limit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| calculationMethod | `String` | Valid values are ROLLING or CALENDAR.Rolling ? Indicates the membership will run from the same month for a determined amount of time.Calendar ? Indicates the calculation will occur every year at the end of the year. |
| calculationMonths | `Float` | This signifies the number of months that points are valid for a membership type |
| canDeleteYn | `String` | Can Delete Y/N |
| cardLength | `Float` | The length of the card number for default card validation. |
| cardPrefix | `String` | Card Prefix |
| cardValidYears | `Float` | Number of years card will be valid for this level. |
| centralSetupYn | `String` | Indicates if program is managed centrally or at Local property. If central then points will be calculated at ECIS else if program is local then points will be calculated and stored locally. |
| chainCode | `String` | Chain Code |
| changesRestrictedYn | `String` | Indicates whether a change to this level is restricted once a guest attains this level. |
| chipAndPinYn | `String` | Indicates if this membership type is Chip and Pin. |
| comments | `String` | Comments |
| costPerPoint | `Float` | Cost Per Point |
| creditLimit | `Float` | Credit Limit |
| currencyCode | `String` | Currency Code |
| currentPoints | `Float` | Used in the EIS Module. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultMemStatus | `String` | Default value for membership status. |
| deletedFlag | `String` | Deleted Flag |
| deviceCode | `String` | Device Code |
| deviceDisableDate | `Date` | Date when device was disabled. |
| displayColor | `String` | Display Color |
| downgrade | `String` | Downgrade |
| downgradePeriod | `Float` | Number of months to consider for downgrade. |
| earningPreference | `String` | Earning Preference |
| enrolledAt | `String` | Resort/CRO where enrollment is done. |
| enrollmentCode | `String` | Code to indicate source used to enroll the member. |
| enrollmentCodeReqYn | `String` | Enrollment code required flag. |
| enrollmentDescription | `String` | Enrollment Description |
| enrollmentSource | `String` | Source from where the enrollment is done. |
| exceptionType | `String` | Exception Type |
| exchangeRateType | `String` | Exchange Rate Type |
| excludeFromBatch | `String` | Flag to determine member actions to include in the fulfillment extract |
| expiration | `Date` | Expiration date of the Card. |
| expirationDateRequired | `String` | Expiration Date Required |
| expirationMonth | `Float` | Expiration month for membership types having a ROLLING calculation method. |
| externalProcessDays | `Float` | Maximum number of days to process the External Processing Exception. |
| externallyControlledYn | `String` | Flag that affects how a Membership Type is added edited or deleted from a profile. |
| folioMessage | `String` | Free form text that can ve configured to display on the folio of clients earning points under this program. |
| folioMessageCredits | `String` | Folio Message for Credits. |
| folioMessageNonmembers | `String` | Folio Message Nonmembers |
| folioMessageNonmembersNq | `String` | Folio message for non members who have a non-qualifying rate code. |
| folioMessageNq | `String` | Folio message for members who have a non-qualifying rate code. |
| fulfillmentYn | `String` | Fulfillment Y/N |
| fulfilmentYn | `String` | Fulfilment Y/N |
| graceExpirationMonth | `Float` | Used in EIS Module. |
| gracePeriodIndicator | `String` | Grace Period Indicator |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `String` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| joinDate | `Date` | Used by EIS Module. |
| label | `String` | Label |
| levelRequired | `String` | Level Required |
| loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| maxDowngradeLevel | `String` | Used in EIS Module. |
| mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| memClassDescription | `String` | Membership Class Description |
| memClassInsertDate | `DateTime` | Membership Class Insert Date |
| memClassInsertUser | `Float` | Membership Class Insert User |
| memClassUpdateDate | `DateTime` | Membership Class Update Date |
| memClassUpdateUser | `Float` | Membership Class Update User |
| memLevelDeletedFlag | `String` | Membership Level Deleted Flag |
| memLevelInactiveDate | `DateTime` | Membership Level Inactive Date |
| memLevelInsertDate | `DateTime` | Membership Level Insert Date |
| memLevelInsertUser | `Float` | Membership Level Insert User |
| memLevelUpdateDate | `DateTime` | Membership Level Update Date |
| memLevelUpdateUser | `Float` | Membership Level Update User |
| memTypeCardValidYears | `Float` | Membership Type Card Valid Years |
| memTypeInactiveDate | `DateTime` | Membership Type Inactive Date |
| memTypeInsertDate | `DateTime` | Membership Type Insert Date |
| memTypeInsertUser | `Float` | Membership Type Insert User |
| memTypeOrderBy | `Float` | Membership Type Order By |
| memTypeUpdateDate | `DateTime` | Membership Type Update Date |
| memTypeUpdateUser | `Float` | Membership Type Update User |
| memberIndicator | `String` | Used in the EIS Module. |
| memberInfoDispSet | `String` | Display set used for member info. |
| memberName | `String` | Not Used |
| memberStatus | `String` | User defined field used by external system. Not used by OCIS upgradedowngrade or renewal process. |
| memberSubtype | `String` | Used in the EIS Module. |
| membershipAction | `String` | [A]utopopulate on Reservation [P]rompt on Reservation; Al[W]ays Prompt [N]o action. |
| membershipCardNumber | `String` | Membership Card Number |
| membershipClass | `String` | Primary key of this table |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipLevelCExchangeDate | `Date` | Mem Level Central Xchange Date |
| membershipLevelCExchangeRate | `Float` | Mem Level Central Xchange Rate |
| membershipLevelDesc | `String` | Membership Level Description |
| membershipLevelRank | `Float` | The sequence of membership levels starting with 1 (The starting level) and increasing to the highest level. |
| membershipType | `String` | Membership Type |
| membershipTypeCExchangeDate | `Date` | Mem Type Central Xchange Date |
| membershipTypeCExchangeRate | `Float` | Mem Type Central Xchange Rate |
| membershipTypeDesc | `String` | Membership Type Description |
| multipleRoomsLimit | `Float` | Multiple rooms allowed for points exception. |
| nameId | `Float` | Name ID |
| nameOnCard | `String` | Name as appeared on the Membership Card. |
| numberOfTrx | `Float` | Number of transaction(s) for each stay. Value will be 2 in case of double dipping otherwise it will be null or 1. |
| numericValidation | `String` | Indicates the type of card number validation which should be done. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| partnerMembershipId | `Float` | Membership ID that accrues Miles. |
| pointsIssuedCentrallyYn | `String` | Indicates that points are issued by central system |
| pointsLabel | `String` | Label for points (i.e. Points or Miles) |
| preferredCardYN | `String` | Used in the EIS Module. |
| primaryAirlinePartner | `String` | Used in the EIS Module. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryMembershipYn | `String` | Primary Membership Y/N |
| processExpirationDate | `Date` | Used in the EIS Module. |
| promptAtCheckOut | `String` | Indicates if resv_memberships should popup when a reservation is checked out. |
| promptAtCheckin | `String` | Indicates if a prompt is required at checkin of a reservation if a membership number exists on profile and not attached to the reservation. |
| promptAtNewReservation | `String` | Indicates if resv_memberships should popup when a reservation is created. |
| promptAtUpdateReservation | `String` | Indicates if resv_memberships should popup when a reservation is updated. |
| rankValue | `Float` | Rank Value |
| ranking | `Float` | Ranking |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomAssignmentValue | `Float` | Room Assignment Value |
| sendChkoutToIfc | `String` | Send checkout reservation information to the interface for Courtesy Cards? |
| sequence | `Float` | Sequence |
| tierAdministration | `String` | Tier Administration |
| trackData | `String` | Stores key track information for a universal card that may be different than the membership number. |
| transactionMaxPoints | `Float` | Indicates the maximum points that can be accrued per membership transaction. |
| tscDateFlag | `String` | Tier Management Based on Date. |
| udfCardValidationYn | `String` | Indicates if card number validation is a UDF(User defined function) or Default validation is used. |
| udfFormula | `String` | Udf Formula |
| updateDate | `DateTime` | Update Date |
| updateUser | `String` | Update User |
| upgradePeriod | `Float` | Number of months to consider for upgrade. |
| validationByIfc | `String` | Indicates if the card is to be validated by an external system. |
| vipStatus | `String` | VIP Status |
| yearsToExpire | `Float` | Years To Expire |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipRejectCommentsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipPointsSeqno | `Float` | Membership Points Seqno |
| membershipTransactionId | `Float` | Membership Trx ID |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rejectionReason | `String` | Rejection Reason |
| rule | `String` | Rule |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionRevenuesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralCentralRevenue | `Float` | Central - Central Revenue |
| centralPMSRevenue | `Float` | Central PMS Revenue |
| centralRevenue | `Float` | Revenue calculated by Central System. |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| date | `Date` | Date |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pMSRevenue | `Float` | Revnue calculated by PMS. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| qualifiedYN | `String` | Indicates if the revenue was qualified for any membership points. This is only for information purpose only. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueType | `String` | Transaction code. |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsMembershipTransactionDailyRatesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookedRoomLabel | `String` | Booked Room Label |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralCentralRateAmount | `Float` | Central - Central Rate Amount |
| centralPMSRateAmount | `Float` | Central PMS Rate Amount |
| centralRateAmount | `Float` | central rate amount in the central currency |
| chainCode | `String` | Chain Code |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromDate | `Date` | initial date that rate code was part of the reservation |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketCode | `String` | Market Code |
| membershipTransactionLinkId | `Float` | Membership Trx Link ID |
| numberDays | `Float` | number days rate code was part of the reservation |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pMSRateAmount | `Float` | rate code amount in the property currency |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoYn | `String` | Pseudo Y/N |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| resourceId | `String` | Resource ID |
| roomLabel | `String` | Room Label |
| roomNumber | `String` | Room Number |
| shareNights | `Float` | Computed share nights. |
| toDate | `Date` | To Date |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyTransactionsPropertyPropertyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| property | `String` | The property that the record belongs to |
| aRAccountNoFormat | `String` | Number format of AR account no. |
| aRAccountNumberMandatoryYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| aRAgent | `String` | Default Account Type for an Agent for the Property |
| aRBalanceTrxCode | `String` | Internal |
| aRCompany | `String` | Default Account Type for a Company for the Property |
| aRCreditTrxCode | `String` | Internal |
| aRGroups | `String` | Default Account Type for a Group for the Property |
| aRIndividuals | `String` | Default Account Type for Individual for the Property |
| aRSettleCode | `String` | Internal |
| aRTypewriter | `String` | Internal |
| accessCode | `String` | Access Code |
| accessibleRooms | `Float` | Number of handicapped rooms. |
| agingLevel1 | `Float` | Aging bucket 1 |
| agingLevel2 | `Float` | Aging bucket 2 |
| agingLevel3 | `Float` | Aging bucket 3 |
| agingLevel4 | `Float` | Aging bucket 4 |
| agingLevel5 | `Float` | Aging bucket 3 |
| airport | `String` | The Airport Code for the airport near the property |
| airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| allowLoginYN | `String` | Allow loggin in to this resort(Y/N) |
| allowancePeriodAdj | `String` | Period for the allowance |
| awardsTimeout | `Float` | Internal |
| ballroomArea | `String` | Ball Room Area |
| ballroomSeats | `Float` | No of Ballroom Seats |
| baseLanguage | `String` | The base language of the Hotel |
| block | `String` | It contains the reservation type to be used when making group block |
| brandCode | `String` | Brand Code of the property. |
| budgetMonth | `Float` | Financial Year of the Property |
| businessDate | `Date` | The date this resort becomes valid for use by the system |
| businessID | `String` | Value for the parameter. |
| businessRegistrationCode | `String` | Value for the parameter. |
| cROCODE | `String` | Code for the CRO |
| cashShiftDrop | `String` | Internal |
| cateringCurrencyCode | `String` | Catering Currency Code used when Catering Currency differs from base currency. |
| cateringCurrencyFormat | `String` | Catering currency format. |
| centralXchangeDate | `Date` | Central  Exchange Date |
| centralXchangeRate | `Float` | Central  Exchange Rate |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralCurrencyCode | `String` | Central Currency Code |
| centralCurrencyDescription | `String` | Central Currency Description |
| centralDblRate2 | `Float` | Central Double Rate2 |
| centralDblRate1 | `Float` | Central Double Rate1 |
| centralPasserbyMarket | `String` | Central Passerby Market |
| centralPasserbySource | `String` | Central Passerby Source |
| centralPropertyType | `String` | Central Property Type |
| centralSglRate1 | `Float` | Central Sgl Rate1 |
| centralSglRate2 | `Float` | Central Sgl Rate 2 |
| centralState | `String` | Central State |
| centralStateDescription | `String` | Central State Description |
| centralSuiRate1 | `Float` | Central Sui Rate1 |
| centralSuiRate2 | `Float` | Central Sui Rate 2 |
| centralTplRate1 | `Float` | Central Tpl Rate1 |
| centralTplRate2 | `Float` | Central Tpl Rate 2 |
| centralWarningAmount | `Float` | Central Warning Amount |
| chainCode | `String` | Chain Code for the chain to which the property belongs |
| chainDescription | `String` | The description of this chain. |
| chainMode | `String` | Chain Mode |
| checkExgPaidout | `String` | Internal |
| checkOutTime | `DateTime` | The Hotel official check out time |
| checkShiftDrop | `String` | Internal |
| checkTrxcode | `String` | Internal |
| checkInTime | `DateTime` | The Hotel official check intime |
| city | `String` | The physical city in which this property resides. |
| cityDescription | `String` | City Description |
| comAddress | `String` | Internal |
| comMethod | `String` | Internal |
| comNameXrefId | `Float` | Internal |
| companyAddressType | `String` | Internal |
| companyPhoneType | `String` | Internal |
| configurationMode | `String` | Internal |
| confirmRegcardPrinter | `String` | Internal |
| connectingRooms | `Float` | Number of connecting rooms. |
| contacts | `String` | The unique name of application user |
| copies | `Float` | Number of copies to be printed |
| country | `String` | Country name. |
| countryCode | `String` | The name of the country in which this property resides. |
| countryMode | `String` | Value for the parameter. |
| creditLimit | `Float` | The default credit limit for guests. |
| currencyCode | `String` | Currency Code. |
| currencyCodeSymbol | `String` | Currency Symbol like $ or EURO symbol |
| currencyDescription | `String` | A description of this currency. |
| currencyFormat | `String` | Format for the local currency. |
| curtainColor | `String` | Color that of the background |
| dSI | `Float` | DSI |
| dateForAging | `String` | Date the aging should begin |
| dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| decimalPlaces | `Float` | Number of places for the default currency |
| decimalSeparator | `String` | Type of decimal separator |
| decimals | `Float` | Number of decimals to designate currency |
| defaultFolioStyle | `Float` | Folio style to be used for all guests |
| defaultGuestAddress | `String` | Default guest address format. |
| defaultMembershipType | `String` | Future use |
| defaultPostingRoom | `String` | Future use |
| defaultPropertyAddress | `String` | Default property address format. |
| defaultRateCode | `String` | Future use |
| defaultRatecodePcr | `String` | Rate code used to default a PCR rate code used in FIT Contracts. |
| defaultRatecodeRack | `String` | Rate code used to default a RACK rate code used for FIT Contracts. |
| defaultRegistrationCard | `String` | Default registration card for the property. |
| defaultReservationType | `String` | The Default reservation type for this property |
| deletedFlag | `String` | Deleted Flag |
| depositLedgerTrxCode | `String` | Future use |
| destinationId | `String` | Destination ID |
| dfltPkgTranCode | `String` | Future use |
| dfltTranCodeRateCode | `String` | Future use |
| directions | `String` | Internal |
| dirsales | `String` | Future use |
| disableLoginYN | `String` | LOGIN into the application is disabled. |
| doubleRooms | `Float` | Number of double rooms. |
| downloadRestYN | `String` | Download Rest YN |
| dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| email | `String` | Email id for the property. |
| endDate | `Date` | Future use. |
| exchangePostingType | `String` | Default Exchange posting status for the property |
| executiveFloorNumber | `String` | Floor number of executive floor. |
| expHotelCode | `String` | Hotel code used for third party exports |
| extExpFileLocation | `String` | Future use |
| extPropertyCode | `String` | Future use |
| externalSCYN | `String` | Indicates that the property uses an external SC system. |
| familyRooms | `Float` | Number of family rooms. |
| faxNoFormat | `String` | Fax number formats. |
| faxNumber | `String` | The fax phone number |
| fiscalEndDate | `Date` | Future use |
| fiscalPeriodType | `String` | Future use |
| fiscalStartDate | `Date` | Future use |
| fiscalYearBeginMonth | `Float` | Fiscal Year Begin Month |
| fiscalYearBeginYear | `Float` | Fiscal Year Begin Year |
| flags | `String` | Screen Painter flags to indicate whether an item is changable/ movable etc. |
| flowCode | `String` | Future use |
| fnsTier | `String` | Property Free Nights Stay Tier. |
| folioLanguage1 | `String` | Other languages |
| folioLanguage2 | `String` | Other languages |
| folioLanguage3 | `String` | Other languages |
| folioLanguage4 | `String` | Other languages |
| genmgr | `String` | Future use |
| groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| guestLookupTimeout | `Float` | Future use |
| guestRoomElevators | `Float` | Number of guest elevators. |
| guestRoomFloors | `Float` | Total of guest rooms floors. |
| hotelCode | `String` | Future use |
| hotelFC | `String` | Future use |
| hotelID | `String` | Hotel id |
| hotelType | `String` | Future use |
| iMGDirectionID | `Float` | Future use |
| iMGHotelID | `Float` | Future use |
| iMGMapID | `Float` | Future use |
| inactiveDaysForGuestProfile | `Float` | Future use |
| inactiveFlag | `String` | Inactive Flag |
| individualAddressType | `String` | Future use |
| individualPhoneType | `String` | Future use |
| individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `Float` | The user that created the record |
| intTaxIncludedYN | `String` | Int Tax Included YN |
| inventoryYN | `String` | Future use |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| latitude | `Float` | Latitude of the property in decimal |
| leadsend | `String` | Future use |
| legalOwner | `String` | The owner who owns this property |
| locationID | `String` | The property that the record belongs to |
| longDateFormat | `String` | Long date format for the property. |
| longStayControl | `Float` | The default length of stay |
| longitude | `Float` | Longitude of the property in decimal |
| maxAdultsInFamilyRoom | `Float` | Maximum adults in family rooms. |
| maxChildrenInFamilyRoom | `Float` | Maximum children in family rooms. |
| maxOccupancy | `Float` | Future use |
| maximumCreditDays | `Float` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |
| mbsSupportedYN | `String` | Indicates whether the property supports MBS. Used in some file exports. |
| meetRooms | `Float` | Future use |
| meetSeats | `Float` | Future use |
| meetSpace | `Float` | Future use |
| meetingFC | `String` | Future use |
| minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| nameIdLink | `Float` | Internal |
| nightAuditCashierID | `String` | Future use |
| nonSmokingRooms | `Float` | Number of non smoking rooms. |
| noteDetails | `String` | Notes for the property |
| numberOfBeds | `Float` | Total number of beds in this property |
| numberOfFloors | `Float` | Total number of floors in this property |
| numberOfRooms | `Float` | Number of Rooms |
| opusCurrencyCode | `String` | Future use |
| organizationID | `Float` | Organization ID |
| organizationInternalID | `Float` | Organization Internal ID |
| ownership | `String` | Future use |
| packageLoss | `String` | Package Loss code for a particular package |
| packageProfit | `String` | Package Profit code for a particular Package |
| parentOrgCode | `String` | Parent Org Code |
| passerbyMarket | `String` | Market code |
| passerbySource | `String` | Source code |
| path | `String` | Path |
| paymentDate | `DateTime` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| perReservationRoomLimit | `Float` | Future use |
| phoneNumber | `String` | The direct dial phone number of this property |
| postalCode | `String` | The postal code of this property. |
| primaryKeyID | `Float` | Primary Key ID |
| proinfoUrl | `String` | URL where property information is located. |
| propMapUrl | `String` | Property MAP URL. |
| propPicUrl | `String` | Property picture URL. |
| propertyCode | `String` | The property that the record belongs to |
| propertyName | `String` | The name of this property. |
| propertyType | `String` | Type of resort. |
| quotedCurrency | `String` | Future use |
| rNAInsertdate | `DateTime` | RNA Insert Date |
| rNAUpdatedate | `DateTime` | RNA Update Date |
| reconcileDate | `DateTime` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |
| regionCode | `String` | Future use |
| regionDescription | `String` | Description of the Region. |
| restaurant | `Float` | Future use |
| rhythmSheets | `Float` | Total number of Sheets |
| rhythmTowels | `Float` | Total number of Towels |
| roomAmenities | `String` | Room amenity. |
| sGLNum | `String` | Future use |
| sGLRate1 | `Float` | Future use |
| sGLRate2 | `Float` | Future use |
| sUINum | `String` | Future use |
| sUIRate1 | `Float` | Future use |
| sUIRate2 | `Float` | Future use |
| saveProfiles | `Float` | To store number of days before deleting the gest profile |
| scriptID | `Float` | Future use |
| season1 | `String` | Future use |
| season2 | `String` | Future use |
| season3 | `String` | Future use |
| season4 | `String` | Future use |
| season5 | `String` | Future use |
| sendLeadAsBooking | `String` | Indicates that the property accepts leads as bookings. |
| shopDescription | `String` | Shop description. |
| shortDateFormat | `String` | Short date format for the property. |
| singleRooms | `Float` | Number of single rooms. |
| sourceCommission | `String` | For default commission percentage |
| state | `String` | The state in which this property is located. |
| stateDescription | `String` | Description of the state. |
| street | `String` | The street of the property. |
| suites | `Float` | Number of suites. |
| summCurrencyCode | `String` | Internal |
| tACommission | `String` | For default commission percentage |
| tPLNum | `String` | Future use |
| tPLRate1 | `Float` | Future use |
| tPLRate2 | `Float` | Future use |
| telephoneNoFormat | `String` | Formats for telephone number |
| thousandSeparator | `String` | Separator for monetory values |
| timeFormat | `String` | Default time format for the property. |
| timeZone | `String` | Time zone region selected by the employee. |
| tollFree | `String` | Toll free telephone number. |
| totalRooms | `Float` | Future use |
| touristNumber | `String` | Tourist Number |
| translateMulticharYN | `String` | Indicates whether the property handles multi byte characters and whether they are translateable or not |
| turnawayCode | `String` | Turnaway code for the property. |
| twinRooms | `Float` | Number of twin rooms. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |
| vatID | `String` | VAT ID of this property. |
| videoCheckoutPrinter | `String` | Future use |
| videoCheckoutStart | `DateTime` | Video check out start time. |
| videoCheckoutStop | `DateTime` | Video check out end time. |
| wakeUpDelay | `Float` | Future use |
| warningAmount | `Float` | Amount at which warning is raised. |
| web | `String` | Webaddress of the property |
| weekendDays | `String` | Weekend days for the property. |
| zeroInvPurDays | `Float` | Internal |

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

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'username': pl.Utf8,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Utf8,
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
    'organizationID': pl.Float64,
    'partnerMembershipId': pl.Float64,
    'pointsIssuedCentrallyYn': pl.Utf8,
    'pointsLabel': pl.Utf8,
    'preferredCardYN': pl.Utf8,
    'primaryAirlinePartner': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
    'upgradePeriod': pl.Float64,
    'validationByIfc': pl.Utf8,
    'vipStatus': pl.Utf8,
    'yearsToExpire': pl.Float64,
}

membership_reject_comments_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipPointsSeqno': pl.Float64,
    'membershipTransactionId': pl.Float64,
    'membershipType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rejectionReason': pl.Utf8,
    'rule': pl.Utf8,
}

membership_transaction_revenues_details_schema = {
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralCentralRevenue': pl.Float64,
    'centralPMSRevenue': pl.Float64,
    'centralRevenue': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'date': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipTransactionLinkId': pl.Float64,
    'organizationID': pl.Float64,
    'pMSRevenue': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'qualifiedYN': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueType': pl.Utf8,
}

membership_transaction_daily_rates_details_schema = {
    'bookedRoomLabel': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralCentralRateAmount': pl.Float64,
    'centralPMSRateAmount': pl.Float64,
    'centralRateAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'fromDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketCode': pl.Utf8,
    'membershipTransactionLinkId': pl.Float64,
    'numberDays': pl.Float64,
    'organizationID': pl.Float64,
    'pMSRateAmount': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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