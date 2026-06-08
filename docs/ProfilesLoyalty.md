# ProfilesLoyalty
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `profilesLoyalty`
> Detailed information on the Loyalty Program providing details on the Membership Profiles Stay Information and the ability to  track Awards and Claims.
  
**Return:** [`[ProfilesLoyaltyType]`](#profilesloyaltytype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesLoyaltyQueryArgumentsType!`](#profilesloyaltyqueryargumentstype) |  |

## Object Types

### ProfilesLoyaltyType

| Field | Type | Description |
| --- | --- | --- |
| loyaltyProfileMembershipDetails | [`ProfilesLoyaltyLoyaltyProfileMembershipDetailsType`](#profilesloyaltyloyaltyprofilemembershipdetailstype) | Loyalty Profile Membership Details |
| membershipBenefitsDetails | [`ProfilesLoyaltyMembershipBenefitsDetailsType`](#profilesloyaltymembershipbenefitsdetailstype) | Membership Benefits Details |
| membershipClaimDetails | [`ProfilesLoyaltyMembershipClaimDetailsType`](#profilesloyaltymembershipclaimdetailstype) | Membership Claim Details |
| membershipHistoryDetails | [`ProfilesLoyaltyMembershipHistoryDetailsType`](#profilesloyaltymembershiphistorydetailstype) | Membership History Details |
| membershipIssuedAwardsDetails | [`ProfilesLoyaltyMembershipIssuedAwardsDetailsType`](#profilesloyaltymembershipissuedawardsdetailstype) | Membership Issued Awards Details |
| membershipTransactionsDetails | [`ProfilesLoyaltyMembershipTransactionsDetailsType`](#profilesloyaltymembershiptransactionsdetailstype) | Membership Transactions Details |
| membershipTransactionHeaderDetails | [`ProfilesLoyaltyMembershipTransactionHeaderDetailsType`](#profilesloyaltymembershiptransactionheaderdetailstype) | Membership Transaction Header |
| expirePointsByDateDetails | [`ProfilesLoyaltyExpirePointsByDateDetailsType`](#profilesloyaltyexpirepointsbydatedetailstype) | Expire Points By Date Details |
| profilesLoyaltyRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyLoyaltyProfileMembershipDetailsType

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

### ProfilesLoyaltyMembershipBenefitsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| levelBenefitsCode | `String` | Link to benefit code. |
| levelBenefitsDescription | `String` | Level Benefits Description |
| membershipId | `Float` | Membership ID |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processingMsg | `String` | Processing Msg |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipClaimDetailsType

| Field | Type | Description |
| --- | --- | --- |
| approvalStatus | `String` | Approval Status |
| approveReject | `String` | Approve/Reject/None |
| arrivalDate | `Date` | Arrival Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMembershipBaseRevenue | `Float` | Central Membership Base Revenue |
| cMembershipBonusRevenue | `Float` | Central Membership Bonus Revenue |
| callerInformation | `String` | Information about the caller. |
| callerName | `String` | name of the person who called. |
| chainCode | `String` | Chain Code |
| channel | `String` | Channel |
| claimAdjLimitCode | `String` | Claim Adj Limit Code |
| claimDate | `Date` | Date claim was posted in the database. |
| claimNumber | `Float` | Primary key. |
| claimOrigin | `String` | User defined origin of claim. |
| claimOwner | `Float` | Claim Owner |
| claimSource | `String` | Source of the Claim |
| claimStatus | `String` | Status of the claim. |
| claimType | `String` | User Defined Claim Types |
| closeDate | `Date` | Date and time cashier was closed. |
| comments | `String` | Comments |
| confirmationNumber | `String` | Confirmation Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| departureDate | `Date` | Departure Date |
| externalReferenceNumber | `String` | External Reference Number |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketCode | `String` | Market Code |
| membershipBaseNights | `Float` | Membership Base Nights |
| membershipBaseRevenue | `Float` | Membership Base Revenue |
| membershipBaseStay | `Float` | Membership Base Stay |
| membershipBonusNights | `Float` | Membership Bonus Nights |
| membershipBonusRevenue | `Float` | Membership Bonus Revenue |
| membershipBonusStay | `Float` | Membership Bonus Stay |
| membershipClaimProperty | `String` | Membership Claim Property |
| membershipId | `Float` | Membership ID |
| membershipNumber | `String` | Membership Number |
| membershipTransactionId | `Float` | Membership Trx ID |
| membershipType | `String` | Membership Type |
| name | `String` | Name |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originOfBooking | `String` | Origin of Booking |
| owner | `String` | Owner |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| purposeOfStay | `String` | Purpose of stay. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| recordType | `String` | Record Type |
| replyBy | `Date` | Date when the user gets a response to his/her claim. |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| room | `String` | Room |
| submitter | `String` | Submitter |
| totalBasePoints | `Float` | Total Base Points |
| totalBonusPoints | `Float` | Total Bonus Points |
| totalMiscPoints | `Float` | Total Miscellaneous Points |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipHistoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionID | `Float` | Action ID |
| actionType | `String` | Action Type |
| chainCode | `String` | Chain Code |
| changeType | `String` | Change Type |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| extractBatchId | `Float` | Internal batch id. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipID | `Float` | Membership ID |
| newValue | `String` | New Value |
| oldValue | `String` | Old Value |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipIssuedAwardsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualCancelPoints | `Float` | Actual penalty points applied while cancelling the reservation_award record. |
| arrivalDate | `Date` | Arrival Date |
| autoConsumedYn | `String` | Should award be auto consumed when. |
| awardBasedOn | `String` | Award Based On |
| awardCode | `String` | Award Code |
| awardCodeDescription | `String` | Award Code Description |
| awardConsumedYn | `String` | Flag to indicate that award has been consumed. |
| awardID | `Float` | Award ID |
| awardStatus | `String` | Current status of the award. |
| awardValue | `Float` | Value of the award in central currency. |
| awardVoucherNo | `String` | Award Voucher Number |
| billingGroup | `String` | Billing Group |
| cAwardValue | `Float` | Central Award Value |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRedeemedCentralAmount | `Float` | Central Redeemed Central Amount |
| cRedeemedLocalAmount | `Float` | Central Redeemed Local Amount |
| cTotalCentralAmount | `Float` | Central Total Central Amount |
| cTotalLocalAmount | `Float` | Central Total Local Amount |
| cancelDate | `Date` | When award was cancelled. |
| cancelDays | `Float` | Number days before arrival to apply penalty for cancellation. |
| cancelMemberStatementId | `Float` | Member statement ID. |
| cancelPolicyType | `String` | Cancel Policy Type |
| cancelStatementId | `Float` | Internal statement number. |
| cancellationNumber | `Float` | Unique id for the award cancellation if cancelled |
| cancelledYN | `String` | Cancelled YN |
| centralCurrencyCode | `String` | Central Currency Code |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| confirmationNumber | `String` | Confirmation Number |
| consumptionDate | `Date` | Consumption Date |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateAwarded | `Date` | Date when award was issued. |
| dateOfExpiry | `Date` | Date when award is going to expire. |
| deletedFlag | `String` | Deleted Flag |
| departureDate | `Date` | Departure Date |
| exchangeRate | `Float` | Exchange Rate |
| exchangeRateType | `String` | Exchange Rate Type |
| extTrxNumber | `String` | External system transaction no. |
| externalReferenceNumber | `String` | External Reference Number |
| fromRoomLabel | `String` | Room label before the upgrade in case of an upgrade award |
| fromRoomLabelName | `String` | Used when award is based on upgrade of room. Indicates the room label from which upgrade took place. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| invRoomCategory | `String` | The room category which is valid for this property. |
| issuedManuallyYn | `String` | Issued Manually? |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| localReservationNameId | `Float` | Local Resv Name ID |
| memberStatementId | `Float` | Member Statement ID |
| membershipAwardId | `Float` | Internal PK for the table. |
| membershipAwardProperty | `String` | Membership Award Property |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipNumber | `String` | Membership Number |
| membershipType | `String` | Membership Type |
| nameID | `Float` | Name ID |
| numberOfNights | `Float` | Number of Nights |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| penaltyPoints | `Float` | Number of cancel penalty points. |
| pmsCurrencyCode | `String` | Pms Currency Code |
| points | `Float` | Points |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| product | `String` | Product |
| ptsSchCode | `String` | Pts Sch Code |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| redeemedCentralAmount | `Float` | Amount value redeemed.(central/OCIS currency) |
| redeemedLocalAmount | `Float` | Redeemed amount for points on bill in local (PMS) currency. This column is for Information purpose only. |
| reservationCancelNumber | `String` | Reservation Cancel Number |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| roomLabel | `String` | Room Label |
| roomLabelName | `String` | Room label when award is based on rate. Indicates what room category was used with rate code. |
| source | `String` | Origin of the award. |
| statementId | `Float` | Statement ID |
| stayDate | `Date` | Stay Date |
| stayRecordId | `Float` | Stay Record ID |
| toRoomLabel | `String` | Room label after the upgrade for an upgrade award |
| toRoomLabelName | `String` | Used when award is based on upgrade of room. Indicates the room label to which upgrade took place. |
| totalCentralAmount | `Float` | Total amount.(central/OCIS currency) |
| totalLocalAmount | `Float` | Total amount on bill in local (PMS) currency. This column is for Information purpose only. |
| trxCode | `String` | Transaction Code |
| trxNumber | `Float` | Transaction No |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipTransactionsDetailsType

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

### ProfilesLoyaltyMembershipTransactionHeaderDetailsType

| Field | Type | Description |
| --- | --- | --- |
| batchIDCode | `Float` | Batch ID Code |
| cardNumber | `String` | Card Number |
| chainCode | `String` | Chain Code |
| complete | `Float` | Complete |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deleted | `Float` | Deleted |
| deletedFlag | `String` | Deleted Flag |
| error | `Float` | Error message. |
| evaluationDate | `Date` | Date for which routine had run. |
| expirationDate | `Date` | Old membership card expiration date before upgradedowngrade or renewal. |
| fromDate | `Date` | Period for which member transactions were evaluated. From date. |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| joinDate | `Date` | Join Date |
| level | `String` | Old membership level before upgrade or downgrade. |
| locked | `Float` | Locked |
| log | `String` | Shows log of how and what was evaluated for the member. |
| memError | `String` | Shows errors if any while processing for a member. |
| membershipId | `Float` | Membership ID |
| membershipType | `String` | Membership Type |
| membershipTypeDescription | `String` | Membership Type Description |
| name | `String` | Name |
| newExpirationDate | `Date` | New membership card expiration date after upgradedowngrade or renewal. |
| newMembershipLevel | `String` | New membership level. |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pending | `Float` | Pending |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| process | `String` | Process |
| processDate | `DateTime` | Process Date |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reQualifyYn | `String` | Indicates if the re-qualification process was done. |
| recordStatus | `String` | Status of the record. like (NEW ERROR). Initial value is  NEW. |
| recordType | `String` | Record Type |
| reportError | `String` | Shows errors if any while processing for report at report level. |
| reportLog | `String` | Report Log. |
| reportStatus | `String` | Status of the report. For future use. |
| rfmScoreHdrId | `Float` | Rfm Score Hdr ID |
| tmrActiveYn | `String` | Indicates if the batch is run for Tier Management Reset(TMR) flag active. |
| toDate | `Date` | Period for which member transactions were evaluated. To date. |
| total | `Float` | Total number of records to resync |
| user | `String` | User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyExpirePointsByDateDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expirationDate | `DateTime` | Point Expiration date. |
| expireByDate | `Float` | Expire By Date |
| membershipId | `Float` | Membership ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| totalExpire | `Float` | Total Expire |

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

### ProfilesLoyaltyQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| loyaltyprofilemembershipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| loyaltyprofilemembershipDetailsDeviceCode | `StringInput` | Device Code |
| loyaltyprofilemembershipDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| loyaltyprofilemembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| loyaltyprofilemembershipDetailsMembershipCardNo | `StringInput` | Membership Card Number |
| loyaltyprofilemembershipDetailsMembershipClass | `StringInput` | Primary key of this table |
| loyaltyprofilemembershipDetailsMembershipId | `FloatInput` | Membership ID |
| loyaltyprofilemembershipDetailsMembershipLevel | `StringInput` | Membership Level |
| loyaltyprofilemembershipDetailsMembershipType | `StringInput!` | Membership Type<br>`@mandatoryInput` |
| loyaltyprofilemembershipDetailsNameId | `FloatInput` | Name ID |
| loyaltyprofilemembershipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| loyaltyprofilemembershipDetailsPartnerMembershipId | `FloatInput` | Membership ID that accrues Miles. |
| loyaltyprofilemembershipDetailsUpdateDate | `DateTimeInput` | Update Date |
| membershipbenefitsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipclaimDetailsApprovalStatus | `StringInput` | Approval Status |
| membershipclaimDetailsApproveReject | `StringInput` | Approve/Reject/None |
| membershipclaimDetailsArrivalDate | `DateInput` | Arrival Date |
| membershipclaimDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershipclaimDetailsCallerInformation | `StringInput` | Information about the caller. |
| membershipclaimDetailsCallerName | `StringInput` | name of the person who called. |
| membershipclaimDetailsChainCode | `StringInput` | Chain Code |
| membershipclaimDetailsChannel | `StringInput` | Channel |
| membershipclaimDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |
| membershipclaimDetailsClaimDate | `DateInput` | Date claim was posted in the database. |
| membershipclaimDetailsMembershipClaimId | `FloatInput` | Primary key. |
| membershipclaimDetailsClaimOrigin | `StringInput` | User defined origin of claim. |
| membershipclaimDetailsClaimSource | `StringInput` | Source of the Claim |
| membershipclaimDetailsClaimStatus | `StringInput` | Status of the claim. |
| membershipclaimDetailsClaimType | `StringInput` | User Defined Claim Types |
| membershipclaimDetailsCloseDate | `DateInput` | Date and time cashier was closed. |
| membershipclaimDetailsComments | `StringInput` | Comments |
| membershipclaimDetailsPmsResvNo | `StringInput` | Confirmation Number |
| membershipclaimDetailsDeletedFlag | `StringInput` | Deleted Flag |
| membershipclaimDetailsDepartureDate | `DateInput` | Departure Date |
| membershipclaimDetailsCrsBookNo | `StringInput` | External Reference Number |
| membershipclaimDetailsInsertDate | `DateTimeInput` | Insert Date |
| membershipclaimDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipclaimDetailsMarketCode | `StringInput` | Market Code |
| membershipclaimDetailsResort | `StringInput` | Membership Claim Property |
| membershipclaimDetailsMembershipId | `FloatInput` | Membership ID |
| membershipclaimDetailsMembershipCardNo | `StringInput` | Membership Number |
| membershipclaimDetailsMembershipTrxId | `FloatInput` | Membership Trx ID |
| membershipclaimDetailsMembershipType | `StringInput` | Membership Type |
| membershipclaimDetailsName | `StringInput` | Name |
| membershipclaimDetailsNameId | `FloatInput` | Name ID |
| membershipclaimDetailsOriginOfBooking | `StringInput` | Origin of Booking |
| membershipclaimDetailsClaimOwnerName | `StringInput` | Owner |
| membershipclaimDetailsPurposeOfStay | `StringInput` | Purpose of stay. |
| membershipclaimDetailsRateCode | `StringInput` | Rate Code |
| membershipclaimDetailsRecordType | `StringInput` | Record Type |
| membershipclaimDetailsReplyByDate | `DateInput` | Date when the user gets a response to his/her claim. |
| membershipclaimDetailsResvStatus | `StringInput` | Reservation Status |
| membershipclaimDetailsRoom | `StringInput` | Room |
| membershipclaimDetailsSubmitter | `StringInput` | Submitter |
| membershipclaimDetailsUpdateDate | `DateTimeInput` | Update Date |
| membershiphistoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipissuedawardsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptransactionsDetailsAdjustmentYn | `StringInput` | Adjustment Y/N |
| membershiptransactionsDetailsBeginDate | `DateInput` | Arrival Date |
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
| membershiptransactionsDetailsEndDate | `DateInput` | Departure Date |
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
| membershiptransactionsDetailsResort | `StringInput` | Code to uniquely identify the Property |
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
| membershiptscheaderDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesLoyalty($input: ProfilesLoyaltyQueryArgumentsType!) {
  profilesLoyalty(input: $input) @stream {
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
    membershipBenefitsDetails {
      chainCode
      dSI
      deletedFlag
      inactiveDate
      inactiveYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      levelBenefitsCode
      levelBenefitsDescription
      membershipId
      membershipType
      organizationID
      primaryKeyID
      processingMsg
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    membershipClaimDetails {
      approvalStatus
      approveReject
      arrivalDate
      cExchangeDate
      cExchangeRate
      cMembershipBaseRevenue
      cMembershipBonusRevenue
      callerInformation
      callerName
      chainCode
      channel
      claimAdjLimitCode
      claimDate
      claimNumber
      claimOrigin
      claimOwner
      claimSource
      claimStatus
      claimType
      closeDate
      comments
      confirmationNumber
      dSI
      deletedFlag
      departureDate
      externalReferenceNumber
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketCode
      membershipBaseNights
      membershipBaseRevenue
      membershipBaseStay
      membershipBonusNights
      membershipBonusRevenue
      membershipBonusStay
      membershipClaimProperty
      membershipId
      membershipNumber
      membershipTransactionId
      membershipType
      name
      nameId
      organizationID
      originOfBooking
      owner
      primaryKeyID
      purposeOfStay
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateTier
      recordType
      replyBy
      reservationNameID
      reservationStatus
      room
      submitter
      totalBasePoints
      totalBonusPoints
      totalMiscPoints
      updateDate
      updateUser
    }
    membershipHistoryDetails {
      actionID
      actionType
      chainCode
      changeType
      dSI
      deletedFlag
      description
      extractBatchId
      insertDate
      insertUser
      insertUserName
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipID
      newValue
      oldValue
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
    }
    membershipIssuedAwardsDetails {
      actualCancelPoints
      arrivalDate
      autoConsumedYn
      awardBasedOn
      awardCode
      awardCodeDescription
      awardConsumedYn
      awardID
      awardStatus
      awardValue
      awardVoucherNo
      billingGroup
      cAwardValue
      cExchangeDate
      cExchangeRate
      cRedeemedCentralAmount
      cRedeemedLocalAmount
      cTotalCentralAmount
      cTotalLocalAmount
      cancelDate
      cancelDays
      cancelMemberStatementId
      cancelPolicyType
      cancelStatementId
      cancellationNumber
      cancelledYN
      centralCurrencyCode
      chainCode
      comments
      confirmationNumber
      consumptionDate
      dSI
      dateAwarded
      dateOfExpiry
      deletedFlag
      departureDate
      exchangeRate
      exchangeRateType
      extTrxNumber
      externalReferenceNumber
      fromRoomLabel
      fromRoomLabelName
      insertDate
      insertUser
      invRoomCategory
      issuedManuallyYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      localReservationNameId
      memberStatementId
      membershipAwardId
      membershipAwardProperty
      membershipId
      membershipLevel
      membershipNumber
      membershipType
      nameID
      numberOfNights
      organizationID
      penaltyPoints
      pmsCurrencyCode
      points
      primaryKeyID
      product
      ptsSchCode
      rNAInsertDate
      rNAUpdateDate
      rateCode
      redeemedCentralAmount
      redeemedLocalAmount
      reservationCancelNumber
      reservationNameID
      reservationStatus
      roomLabel
      roomLabelName
      source
      statementId
      stayDate
      stayRecordId
      toRoomLabel
      toRoomLabelName
      totalCentralAmount
      totalLocalAmount
      trxCode
      trxNumber
      updateDate
      updateUser
    }
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
    membershipTransactionHeaderDetails {
      batchIDCode
      cardNumber
      chainCode
      complete
      dSI
      deleted
      deletedFlag
      error
      evaluationDate
      expirationDate
      fromDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      joinDate
      level
      locked
      log
      memError
      membershipId
      membershipType
      membershipTypeDescription
      name
      newExpirationDate
      newMembershipLevel
      orderBy
      organizationID
      pending
      primaryKeyID
      process
      processDate
      rNAInsertDate
      rNAUpdateDate
      reQualifyYn
      recordStatus
      recordType
      reportError
      reportLog
      reportStatus
      rfmScoreHdrId
      tmrActiveYn
      toDate
      total
      user
    }
    expirePointsByDateDetails {
      chainCode
      dSI
      expirationDate
      expireByDate
      membershipId
      organizationID
      totalExpire
    }
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

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

membership_benefits_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelBenefitsCode': pl.Utf8,
    'levelBenefitsDescription': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'processingMsg': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

membership_claim_details_schema = {
    'approvalStatus': pl.Utf8,
    'approveReject': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMembershipBaseRevenue': pl.Float64,
    'cMembershipBonusRevenue': pl.Float64,
    'callerInformation': pl.Utf8,
    'callerName': pl.Utf8,
    'chainCode': pl.Utf8,
    'channel': pl.Utf8,
    'claimAdjLimitCode': pl.Utf8,
    'claimDate': pl.Utf8,
    'claimNumber': pl.Float64,
    'claimOrigin': pl.Utf8,
    'claimOwner': pl.Float64,
    'claimSource': pl.Utf8,
    'claimStatus': pl.Utf8,
    'claimType': pl.Utf8,
    'closeDate': pl.Utf8,
    'comments': pl.Utf8,
    'confirmationNumber': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'departureDate': pl.Utf8,
    'externalReferenceNumber': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketCode': pl.Utf8,
    'membershipBaseNights': pl.Float64,
    'membershipBaseRevenue': pl.Float64,
    'membershipBaseStay': pl.Float64,
    'membershipBonusNights': pl.Float64,
    'membershipBonusRevenue': pl.Float64,
    'membershipBonusStay': pl.Float64,
    'membershipClaimProperty': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipNumber': pl.Utf8,
    'membershipTransactionId': pl.Float64,
    'membershipType': pl.Utf8,
    'name': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'originOfBooking': pl.Utf8,
    'owner': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'purposeOfStay': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateTier': pl.Float64,
    'recordType': pl.Utf8,
    'replyBy': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'room': pl.Utf8,
    'submitter': pl.Utf8,
    'totalBasePoints': pl.Float64,
    'totalBonusPoints': pl.Float64,
    'totalMiscPoints': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

membership_history_details_schema = {
    'actionID': pl.Float64,
    'actionType': pl.Utf8,
    'chainCode': pl.Utf8,
    'changeType': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'extractBatchId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUserName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipID': pl.Float64,
    'newValue': pl.Utf8,
    'oldValue': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
}

membership_issued_awards_details_schema = {
    'actualCancelPoints': pl.Float64,
    'arrivalDate': pl.Utf8,
    'autoConsumedYn': pl.Utf8,
    'awardBasedOn': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCodeDescription': pl.Utf8,
    'awardConsumedYn': pl.Utf8,
    'awardID': pl.Float64,
    'awardStatus': pl.Utf8,
    'awardValue': pl.Float64,
    'awardVoucherNo': pl.Utf8,
    'billingGroup': pl.Utf8,
    'cAwardValue': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRedeemedCentralAmount': pl.Float64,
    'cRedeemedLocalAmount': pl.Float64,
    'cTotalCentralAmount': pl.Float64,
    'cTotalLocalAmount': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelDays': pl.Float64,
    'cancelMemberStatementId': pl.Float64,
    'cancelPolicyType': pl.Utf8,
    'cancelStatementId': pl.Float64,
    'cancellationNumber': pl.Float64,
    'cancelledYN': pl.Utf8,
    'centralCurrencyCode': pl.Utf8,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'confirmationNumber': pl.Utf8,
    'consumptionDate': pl.Utf8,
    'dSI': pl.Float64,
    'dateAwarded': pl.Utf8,
    'dateOfExpiry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departureDate': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeRateType': pl.Utf8,
    'extTrxNumber': pl.Utf8,
    'externalReferenceNumber': pl.Utf8,
    'fromRoomLabel': pl.Utf8,
    'fromRoomLabelName': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'invRoomCategory': pl.Utf8,
    'issuedManuallyYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'localReservationNameId': pl.Float64,
    'memberStatementId': pl.Float64,
    'membershipAwardId': pl.Float64,
    'membershipAwardProperty': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipType': pl.Utf8,
    'nameID': pl.Float64,
    'numberOfNights': pl.Float64,
    'organizationID': pl.Float64,
    'penaltyPoints': pl.Float64,
    'pmsCurrencyCode': pl.Utf8,
    'points': pl.Float64,
    'primaryKeyID': pl.Float64,
    'product': pl.Utf8,
    'ptsSchCode': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'redeemedCentralAmount': pl.Float64,
    'redeemedLocalAmount': pl.Float64,
    'reservationCancelNumber': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'roomLabel': pl.Utf8,
    'roomLabelName': pl.Utf8,
    'source': pl.Utf8,
    'statementId': pl.Float64,
    'stayDate': pl.Utf8,
    'stayRecordId': pl.Float64,
    'toRoomLabel': pl.Utf8,
    'toRoomLabelName': pl.Utf8,
    'totalCentralAmount': pl.Float64,
    'totalLocalAmount': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNumber': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

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

membership_transaction_header_details_schema = {
    'batchIDCode': pl.Float64,
    'cardNumber': pl.Utf8,
    'chainCode': pl.Utf8,
    'complete': pl.Float64,
    'dSI': pl.Float64,
    'deleted': pl.Float64,
    'deletedFlag': pl.Utf8,
    'error': pl.Float64,
    'evaluationDate': pl.Utf8,
    'expirationDate': pl.Utf8,
    'fromDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'joinDate': pl.Utf8,
    'level': pl.Utf8,
    'locked': pl.Float64,
    'log': pl.Utf8,
    'memError': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipType': pl.Utf8,
    'membershipTypeDescription': pl.Utf8,
    'name': pl.Utf8,
    'newExpirationDate': pl.Utf8,
    'newMembershipLevel': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Float64,
    'pending': pl.Float64,
    'primaryKeyID': pl.Float64,
    'process': pl.Utf8,
    'processDate': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reQualifyYn': pl.Utf8,
    'recordStatus': pl.Utf8,
    'recordType': pl.Utf8,
    'reportError': pl.Utf8,
    'reportLog': pl.Utf8,
    'reportStatus': pl.Utf8,
    'rfmScoreHdrId': pl.Float64,
    'tmrActiveYn': pl.Utf8,
    'toDate': pl.Utf8,
    'total': pl.Float64,
    'user': pl.Utf8,
}

expire_points_by_date_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Float64,
    'expirationDate': pl.Utf8,
    'expireByDate': pl.Float64,
    'membershipId': pl.Float64,
    'organizationID': pl.Float64,
    'totalExpire': pl.Float64,
}

```