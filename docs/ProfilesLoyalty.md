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

### ProfilesLoyaltyQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| loyaltyprofilemembershipDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| loyaltyprofilemembershipDetailsDeviceCode | `StringInput` | Device Code |  |
| loyaltyprofilemembershipDetailsInactiveDate | `DateTimeInput` | Inactive Date |  |
| loyaltyprofilemembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| loyaltyprofilemembershipDetailsMembershipCardNo | `StringInput` | Membership Card Number |  |
| loyaltyprofilemembershipDetailsMembershipClass | `StringInput` | Primary key of this table |  |
| loyaltyprofilemembershipDetailsMembershipId | `FloatInput` | Membership ID |  |
| loyaltyprofilemembershipDetailsMembershipLevel | `StringInput` | Membership Level |  |
| loyaltyprofilemembershipDetailsMembershipType | `StringInput!` | Membership Type | `mandatoryInput` |
| loyaltyprofilemembershipDetailsNameId | `FloatInput` | Name ID |  |
| loyaltyprofilemembershipDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| loyaltyprofilemembershipDetailsPartnerMembershipId | `FloatInput` | Membership ID that accrues Miles. |  |
| loyaltyprofilemembershipDetailsUpdateDate | `DateTimeInput` | Update Date |  |
| membershipbenefitsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| membershipclaimDetailsApprovalStatus | `StringInput` | Approval Status |  |
| membershipclaimDetailsApproveReject | `StringInput` | Approve/Reject/None |  |
| membershipclaimDetailsArrivalDate | `DateInput` | Arrival Date |  |
| membershipclaimDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| membershipclaimDetailsCallerInformation | `StringInput` | Information about the caller. |  |
| membershipclaimDetailsCallerName | `StringInput` | name of the person who called. |  |
| membershipclaimDetailsChainCode | `StringInput` | Chain Code |  |
| membershipclaimDetailsChannel | `StringInput` | Channel |  |
| membershipclaimDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |  |
| membershipclaimDetailsClaimDate | `DateInput` | Date claim was posted in the database. |  |
| membershipclaimDetailsMembershipClaimId | `FloatInput` | Primary key. |  |
| membershipclaimDetailsClaimOrigin | `StringInput` | User defined origin of claim. |  |
| membershipclaimDetailsClaimSource | `StringInput` | Source of the Claim |  |
| membershipclaimDetailsClaimStatus | `StringInput` | Status of the claim. |  |
| membershipclaimDetailsClaimType | `StringInput` | User Defined Claim Types |  |
| membershipclaimDetailsCloseDate | `DateInput` | Date and time cashier was closed. |  |
| membershipclaimDetailsComments | `StringInput` | Comments |  |
| membershipclaimDetailsPmsResvNo | `StringInput` | Confirmation Number |  |
| membershipclaimDetailsDeletedFlag | `StringInput` | Deleted Flag |  |
| membershipclaimDetailsDepartureDate | `DateInput` | Departure Date |  |
| membershipclaimDetailsCrsBookNo | `StringInput` | External Reference Number |  |
| membershipclaimDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| membershipclaimDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| membershipclaimDetailsMarketCode | `StringInput` | Market Code |  |
| membershipclaimDetailsResort | `StringInput` | Membership Claim Property |  |
| membershipclaimDetailsMembershipId | `FloatInput` | Membership ID |  |
| membershipclaimDetailsMembershipCardNo | `StringInput` | Membership Number |  |
| membershipclaimDetailsMembershipTrxId | `FloatInput` | Membership Trx ID |  |
| membershipclaimDetailsMembershipType | `StringInput` | Membership Type |  |
| membershipclaimDetailsName | `StringInput` | Name |  |
| membershipclaimDetailsNameId | `FloatInput` | Name ID |  |
| membershipclaimDetailsOriginOfBooking | `StringInput` | Origin of Booking |  |
| membershipclaimDetailsClaimOwnerName | `StringInput` | Owner |  |
| membershipclaimDetailsPurposeOfStay | `StringInput` | Purpose of stay. |  |
| membershipclaimDetailsRateCode | `StringInput` | Rate Code |  |
| membershipclaimDetailsRecordType | `StringInput` | Record Type |  |
| membershipclaimDetailsReplyByDate | `DateInput` | Date when the user gets a response to his/her claim. |  |
| membershipclaimDetailsResvStatus | `StringInput` | Reservation Status |  |
| membershipclaimDetailsRoom | `StringInput` | Room |  |
| membershipclaimDetailsSubmitter | `StringInput` | Submitter |  |
| membershipclaimDetailsUpdateDate | `DateTimeInput` | Update Date |  |
| membershiphistoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| membershipissuedawardsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| membershiptransactionsDetailsAdjustmentYn | `StringInput` | Adjustment Y/N |  |
| membershiptransactionsDetailsBeginDate | `DateInput` | Arrival Date |  |
| membershiptransactionsDetailsAutomaticYn | `StringInput` | Points calculated automatically |  |
| membershiptransactionsDetailsBaseBillingGroup | `StringInput` | Billing group for base award points. |  |
| membershiptransactionsDetailsBillingGroup | `StringInput` | Billing Group |  |
| membershiptransactionsDetailsBonusBillingGroup | `StringInput` | Billing group for bonus award points. |  |
| membershiptransactionsDetailsBookedRoomLabel | `StringInput` | Booked Room Label |  |
| membershiptransactionsDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| membershiptransactionsDetailsCrsBookNo | `StringInput` | CRS Booking Number |  |
| membershiptransactionsDetailsChainCode | `StringInput` | Chain Code |  |
| membershiptransactionsDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |  |
| membershiptransactionsDetailsCurrencyCode | `StringInput` | Currency Code |  |
| membershiptransactionsDetailsDataExportedDate | `DateInput` | Date when the record was exported. |  |
| membershiptransactionsDetailsDataExportedYn | `StringInput` | Flag to indicate if record was exported. |  |
| membershiptransactionsDetailsDeletedFlag | `StringInput` | Deleted Flag |  |
| membershiptransactionsDetailsEndDate | `DateInput` | Departure Date |  |
| membershiptransactionsDetailsExceptionType | `StringInput` | Exception Type |  |
| membershiptransactionsDetailsPointsExpirationDate | `DateTimeInput` | Point Expiration date. |  |
| membershiptransactionsDetailsGraceRenewalFlg | `StringInput` | This flag indicate if grace renewals was done. |  |
| membershiptransactionsDetailsInactiveDate | `DateInput` | Inactive Date |  |
| membershiptransactionsDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| membershiptransactionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| membershiptransactionsDetailsMemberStatementId | `FloatInput` | Member Statement ID |  |
| membershiptransactionsDetailsMembershipCardNo | `StringInput` | Membership Card Number |  |
| membershiptransactionsDetailsMembershipId | `FloatInput` | Membership ID |  |
| membershiptransactionsDetailsMembershipLevel | `StringInput` | Membership Level |  |
| membershiptransactionsDetailsMembershipTrxId | `FloatInput` | Membership Trx ID |  |
| membershiptransactionsDetailsMembershipTrxLinkId | `FloatInput` | Membership Trx Link ID |  |
| membershiptransactionsDetailsMembershipType | `StringInput` | Membership Type |  |
| membershiptransactionsDetailsMultipleMembershipId | `FloatInput` | Multiple Membership ID |  |
| membershiptransactionsDetailsNameId | `FloatInput` | Name ID |  |
| membershiptransactionsDetailsNewMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate new membership level. |  |
| membershiptransactionsDetailsUserNotes | `StringInput` | Notes |  |
| membershiptransactionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| membershiptransactionsDetailsOrigMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate original member level was upgraded to. |  |
| membershiptransactionsDetailsOrigPointsExpirationDate | `DateTimeInput` | Date when points expired before it was extended. |  |
| membershiptransactionsDetailsPmsResvNo | `StringInput` | PMS Reservation Number |  |
| membershiptransactionsDetailsParentMembershipTrxId | `FloatInput` | Ref to parent transaction. |  |
| membershiptransactionsDetailsPmsNameId | `StringInput` | Pms Name ID |  |
| membershiptransactionsDetailsPmsResvNameId | `StringInput` | Pms Resv Name ID |  |
| membershiptransactionsDetailsPointsAcYn | `StringInput` | Iindicate membership exceptions of back to back stay and multiple rooms. Valid values are YN and E. |  |
| membershiptransactionsDetailsPointsCalculatedYn | `StringInput` | Flag to indicate if points are calculated. |  |
| membershiptransactionsDetailsPointsCreditDate | `DateInput` | Date when points were created. |  |
| membershiptransactionsDetailsPointsRejectedReason | `StringInput` | Point reject reason. |  |
| membershiptransactionsDetailsAdjRuleCode | `StringInput` | Rule code for adjustment transactions. |  |
| membershiptransactionsDetailsPopulationMethod | `StringInput` | Population Method |  |
| membershiptransactionsDetailsPosCode | `StringInput` | Pos Code |  |
| membershiptransactionsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |  |
| membershiptransactionsDetailsProcessingMessages | `StringInput` | Any error messages generated during calculation. |  |
| membershiptransactionsDetailsPromotionCode2 | `StringInput` | Profile Promotion 1 |  |
| membershiptransactionsDetailsPromotionCode3 | `StringInput` | Profile Promotion 2 |  |
| membershiptransactionsDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| membershiptransactionsDetailsPromotionCode1 | `StringInput` | Rate Promotion Code |  |
| membershiptransactionsDetailsPromotionCode1Desc | `StringInput` | Rate Promotion Description |  |
| membershiptransactionsDetailsRecordType | `StringInput` | Record Type Code |  |
| membershiptransactionsDetailsRecordTypeDesc | `StringInput` | Record Type Description |  |
| membershiptransactionsDetailsResvStatus | `StringInput` | Reservation Status |  |
| membershiptransactionsDetailsRoomLabel | `StringInput` | Room Label |  |
| membershiptransactionsDetailsStayRecordId | `FloatInput` | Stay Record ID |  |
| membershiptransactionsDetailsTierAction | `StringInput` | Type of action performed. |  |
| membershiptransactionsDetailsMembershipTrxDate | `DateInput` | Transaction date. |  |
| membershiptransactionsDetailsTransactionType | `StringInput` | Transaction Type |  |
| membershiptransactionsDetailsUpdateDate | `DateTimeInput` | Update Date |  |
| membershiptscheaderDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |

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