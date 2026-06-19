# ProfilesLoyalty
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | loyaltyProfileMembershipDetails | [`ProfilesLoyaltyLoyaltyProfileMembershipDetailsType`](#profilesloyaltyloyaltyprofilemembershipdetailstype) | Loyalty Profile Membership Details |
| 2 | membershipBenefitsDetails | [`ProfilesLoyaltyMembershipBenefitsDetailsType`](#profilesloyaltymembershipbenefitsdetailstype) | Membership Benefits Details |
| 3 | membershipClaimDetails | [`ProfilesLoyaltyMembershipClaimDetailsType`](#profilesloyaltymembershipclaimdetailstype) | Membership Claim Details |
| 4 | membershipHistoryDetails | [`ProfilesLoyaltyMembershipHistoryDetailsType`](#profilesloyaltymembershiphistorydetailstype) | Membership History Details |
| 5 | membershipIssuedAwardsDetails | [`ProfilesLoyaltyMembershipIssuedAwardsDetailsType`](#profilesloyaltymembershipissuedawardsdetailstype) | Membership Issued Awards Details |
| 6 | membershipTransactionsDetails | [`ProfilesLoyaltyMembershipTransactionsDetailsType`](#profilesloyaltymembershiptransactionsdetailstype) | Membership Transactions Details |
| 7 | membershipTransactionHeaderDetails | [`ProfilesLoyaltyMembershipTransactionHeaderDetailsType`](#profilesloyaltymembershiptransactionheaderdetailstype) | Membership Transaction Header |
| 8 | expirePointsByDateDetails | [`ProfilesLoyaltyExpirePointsByDateDetailsType`](#profilesloyaltyexpirepointsbydatedetailstype) | Expire Points By Date Details |
| 9 | profilesLoyaltyRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyLoyaltyProfileMembershipDetailsType

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

### ProfilesLoyaltyMembershipBenefitsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | inactiveDate | `DateTime` | Inactive Date |
| 5 | inactiveYn | `String` | Inactive Y/N |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | levelBenefitsCode | `String` | Link to benefit code. |
| 11 | levelBenefitsDescription | `String` | Level Benefits Description |
| 12 | membershipId | `Float` | Membership ID |
| 13 | membershipType | `String` | Membership Type |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | processingMsg | `String` | Processing Msg |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | updateDate | `DateTime` | Update Date |
| 20 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipClaimDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | approvalStatus | `String` | Approval Status |
| 2 | approveReject | `String` | Approve/Reject/None |
| 3 | arrivalDate | `Date` | Arrival Date |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | cMembershipBaseRevenue | `Float` | Central Membership Base Revenue |
| 7 | cMembershipBonusRevenue | `Float` | Central Membership Bonus Revenue |
| 8 | callerInformation | `String` | Information about the caller. |
| 9 | callerName | `String` | name of the person who called. |
| 10 | chainCode | `String` | Chain Code |
| 11 | channel | `String` | Channel |
| 12 | claimAdjLimitCode | `String` | Claim Adj Limit Code |
| 13 | claimDate | `Date` | Date claim was posted in the database. |
| 14 | claimNumber | `Float` | Primary key. |
| 15 | claimOrigin | `String` | User defined origin of claim. |
| 16 | claimOwner | `Float` | Claim Owner |
| 17 | claimSource | `String` | Source of the Claim |
| 18 | claimStatus | `String` | Status of the claim. |
| 19 | claimType | `String` | User Defined Claim Types |
| 20 | closeDate | `Date` | Date and time cashier was closed. |
| 21 | comments | `String` | Comments |
| 22 | confirmationNumber | `String` | Confirmation Number |
| 23 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 24 | deletedFlag | `String` | Deleted Flag |
| 25 | departureDate | `Date` | Departure Date |
| 26 | externalReferenceNumber | `String` | External Reference Number |
| 27 | insertDate | `DateTime` | Insert Date |
| 28 | insertUser | `Float` | Insert User |
| 29 | jRNUpdateDate | `Date` | JRN Update Date |
| 30 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 31 | marketCode | `String` | Market Code |
| 32 | membershipBaseNights | `Float` | Membership Base Nights |
| 33 | membershipBaseRevenue | `Float` | Membership Base Revenue |
| 34 | membershipBaseStay | `Float` | Membership Base Stay |
| 35 | membershipBonusNights | `Float` | Membership Bonus Nights |
| 36 | membershipBonusRevenue | `Float` | Membership Bonus Revenue |
| 37 | membershipBonusStay | `Float` | Membership Bonus Stay |
| 38 | membershipClaimProperty | `String` | Membership Claim Property |
| 39 | membershipId | `Float` | Membership ID |
| 40 | membershipNumber | `String` | Membership Number |
| 41 | membershipTransactionId | `Float` | Membership Trx ID |
| 42 | membershipType | `String` | Membership Type |
| 43 | name | `String` | Name |
| 44 | nameId | `Float` | Name ID |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | originOfBooking | `String` | Origin of Booking |
| 47 | owner | `String` | Owner |
| 48 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 49 | purposeOfStay | `String` | Purpose of stay. |
| 50 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 51 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 52 | rateCode | `String` | Rate Code |
| 53 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 54 | recordType | `String` | Record Type |
| 55 | replyBy | `Date` | Date when the user gets a response to his/her claim. |
| 56 | reservationNameID | `Float` | Reservation Name ID |
| 57 | reservationStatus | `String` | Reservation Status |
| 58 | room | `String` | Room |
| 59 | submitter | `String` | Submitter |
| 60 | totalBasePoints | `Float` | Total Base Points |
| 61 | totalBonusPoints | `Float` | Total Bonus Points |
| 62 | totalMiscPoints | `Float` | Total Miscellaneous Points |
| 63 | updateDate | `DateTime` | Update Date |
| 64 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipHistoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionID | `Float` | Action ID |
| 2 | actionType | `String` | Action Type |
| 3 | chainCode | `String` | Chain Code |
| 4 | changeType | `String` | Change Type |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | extractBatchId | `Float` | Internal batch id. |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | insertUserName | `String` | The name of the user who created the record. |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | membershipID | `Float` | Membership ID |
| 15 | newValue | `String` | New Value |
| 16 | oldValue | `String` | Old Value |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 20 | rnaUpdateDate | `DateTime` | RnA Updatedate |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipIssuedAwardsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualCancelPoints | `Float` | Actual penalty points applied while cancelling the reservation_award record. |
| 2 | arrivalDate | `Date` | Arrival Date |
| 3 | autoConsumedYn | `String` | Should award be auto consumed when. |
| 4 | awardBasedOn | `String` | Award Based On |
| 5 | awardCode | `String` | Award Code |
| 6 | awardCodeDescription | `String` | Award Code Description |
| 7 | awardConsumedYn | `String` | Flag to indicate that award has been consumed. |
| 8 | awardID | `Float` | Award ID |
| 9 | awardStatus | `String` | Current status of the award. |
| 10 | awardValue | `Float` | Value of the award in central currency. |
| 11 | awardVoucherNo | `String` | Award Voucher Number |
| 12 | billingGroup | `String` | Billing Group |
| 13 | cAwardValue | `Float` | Central Award Value |
| 14 | cExchangeDate | `Date` | Central Xchange Date |
| 15 | cExchangeRate | `Float` | Central Xchange Rate |
| 16 | cRedeemedCentralAmount | `Float` | Central Redeemed Central Amount |
| 17 | cRedeemedLocalAmount | `Float` | Central Redeemed Local Amount |
| 18 | cTotalCentralAmount | `Float` | Central Total Central Amount |
| 19 | cTotalLocalAmount | `Float` | Central Total Local Amount |
| 20 | cancelDate | `Date` | When award was cancelled. |
| 21 | cancelDays | `Float` | Number days before arrival to apply penalty for cancellation. |
| 22 | cancelMemberStatementId | `Float` | Member statement ID. |
| 23 | cancelPolicyType | `String` | Cancel Policy Type |
| 24 | cancelStatementId | `Float` | Internal statement number. |
| 25 | cancellationNumber | `Float` | Unique id for the award cancellation if cancelled |
| 26 | cancelledYN | `String` | Cancelled YN |
| 27 | centralCurrencyCode | `String` | Central Currency Code |
| 28 | chainCode | `String` | Chain Code |
| 29 | comments | `String` | Comments |
| 30 | confirmationNumber | `String` | Confirmation Number |
| 31 | consumptionDate | `Date` | Consumption Date |
| 32 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 33 | dateAwarded | `Date` | Date when award was issued. |
| 34 | dateOfExpiry | `Date` | Date when award is going to expire. |
| 35 | deletedFlag | `String` | Deleted Flag |
| 36 | departureDate | `Date` | Departure Date |
| 37 | exchangeRate | `Float` | Exchange Rate |
| 38 | exchangeRateType | `String` | Exchange Rate Type |
| 39 | extTrxNumber | `String` | External system transaction no. |
| 40 | externalReferenceNumber | `String` | External Reference Number |
| 41 | fromRoomLabel | `String` | Room label before the upgrade in case of an upgrade award |
| 42 | fromRoomLabelName | `String` | Used when award is based on upgrade of room. Indicates the room label from which upgrade took place. |
| 43 | insertDate | `DateTime` | Insert Date |
| 44 | insertUser | `Float` | Insert User |
| 45 | invRoomCategory | `String` | The room category which is valid for this property. |
| 46 | issuedManuallyYn | `String` | Issued Manually? |
| 47 | jRNUpdateDate | `Date` | JRN Update Date |
| 48 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 49 | localReservationNameId | `Float` | Local Resv Name ID |
| 50 | memberStatementId | `Float` | Member Statement ID |
| 51 | membershipAwardId | `Float` | Internal PK for the table. |
| 52 | membershipAwardProperty | `String` | Membership Award Property |
| 53 | membershipId | `Float` | Membership ID |
| 54 | membershipLevel | `String` | Membership Level |
| 55 | membershipNumber | `String` | Membership Number |
| 56 | membershipType | `String` | Membership Type |
| 57 | nameID | `Float` | Name ID |
| 58 | numberOfNights | `Float` | Number of Nights |
| 59 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 60 | penaltyPoints | `Float` | Number of cancel penalty points. |
| 61 | pmsCurrencyCode | `String` | Pms Currency Code |
| 62 | points | `Float` | Points |
| 63 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 64 | product | `String` | Product |
| 65 | ptsSchCode | `String` | Pts Sch Code |
| 66 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 67 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 68 | rateCode | `String` | Rate Code |
| 69 | redeemedCentralAmount | `Float` | Amount value redeemed.(central/OCIS currency) |
| 70 | redeemedLocalAmount | `Float` | Redeemed amount for points on bill in local (PMS) currency. This column is for Information purpose only. |
| 71 | reservationCancelNumber | `String` | Reservation Cancel Number |
| 72 | reservationNameID | `Float` | Reservation Name ID |
| 73 | reservationStatus | `String` | Reservation Status |
| 74 | roomLabel | `String` | Room Label |
| 75 | roomLabelName | `String` | Room label when award is based on rate. Indicates what room category was used with rate code. |
| 76 | source | `String` | Origin of the award. |
| 77 | statementId | `Float` | Statement ID |
| 78 | stayDate | `Date` | Stay Date |
| 79 | stayRecordId | `Float` | Stay Record ID |
| 80 | toRoomLabel | `String` | Room label after the upgrade for an upgrade award |
| 81 | toRoomLabelName | `String` | Used when award is based on upgrade of room. Indicates the room label to which upgrade took place. |
| 82 | totalCentralAmount | `Float` | Total amount.(central/OCIS currency) |
| 83 | totalLocalAmount | `Float` | Total amount on bill in local (PMS) currency. This column is for Information purpose only. |
| 84 | trxCode | `String` | Transaction Code |
| 85 | trxNumber | `Float` | Transaction No |
| 86 | updateDate | `DateTime` | Update Date |
| 87 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyMembershipTransactionsDetailsType

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

### ProfilesLoyaltyMembershipTransactionHeaderDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | batchIDCode | `Float` | Batch ID Code |
| 2 | cardNumber | `String` | Card Number |
| 3 | chainCode | `String` | Chain Code |
| 4 | complete | `Float` | Complete |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deleted | `Float` | Deleted |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | error | `Float` | Error message. |
| 9 | evaluationDate | `Date` | Date for which routine had run. |
| 10 | expirationDate | `Date` | Old membership card expiration date before upgradedowngrade or renewal. |
| 11 | fromDate | `Date` | Period for which member transactions were evaluated. From date. |
| 12 | insertUser | `Float` | Insert User |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | joinDate | `Date` | Join Date |
| 16 | level | `String` | Old membership level before upgrade or downgrade. |
| 17 | locked | `Float` | Locked |
| 18 | log | `String` | Shows log of how and what was evaluated for the member. |
| 19 | memError | `String` | Shows errors if any while processing for a member. |
| 20 | membershipId | `Float` | Membership ID |
| 21 | membershipType | `String` | Membership Type |
| 22 | membershipTypeDescription | `String` | Membership Type Description |
| 23 | name | `String` | Name |
| 24 | newExpirationDate | `Date` | New membership card expiration date after upgradedowngrade or renewal. |
| 25 | newMembershipLevel | `String` | New membership level. |
| 26 | orderBy | `Float` | Order By |
| 27 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 28 | pending | `Float` | Pending |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | process | `String` | Process |
| 31 | processDate | `DateTime` | Process Date |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | reQualifyYn | `String` | Indicates if the re-qualification process was done. |
| 35 | recordStatus | `String` | Status of the record. like (NEW ERROR). Initial value is  NEW. |
| 36 | recordType | `String` | Record Type |
| 37 | reportError | `String` | Shows errors if any while processing for report at report level. |
| 38 | reportLog | `String` | Report Log. |
| 39 | reportStatus | `String` | Status of the report. For future use. |
| 40 | rfmScoreHdrId | `Float` | Rfm Score Hdr ID |
| 41 | tmrActiveYn | `String` | Indicates if the batch is run for Tier Management Reset(TMR) flag active. |
| 42 | toDate | `Date` | Period for which member transactions were evaluated. To date. |
| 43 | total | `Float` | Total number of records to resync |
| 44 | user | `String` | User |

[⬆ Back to Query](#query)

---

### ProfilesLoyaltyExpirePointsByDateDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | expirationDate | `DateTime` | Point Expiration date. |
| 4 | expireByDate | `Float` | Expire By Date |
| 5 | membershipId | `Float` | Membership ID |
| 6 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 7 | totalExpire | `Float` | Total Expire |

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
#### Validation Rules

**`mandatoryInput`**
- loyaltyprofilemembershipDetailsMembershipType


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
membership_benefits_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelBenefitsCode': pl.Utf8,
    'levelBenefitsDescription': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'processingMsg': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
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
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'departureDate': pl.Utf8,
    'externalReferenceNumber': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'originOfBooking': pl.Utf8,
    'owner': pl.Utf8,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
```python
membership_history_details_schema = {
    'actionID': pl.Float64,
    'actionType': pl.Utf8,
    'chainCode': pl.Utf8,
    'changeType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'extractBatchId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipID': pl.Float64,
    'newValue': pl.Utf8,
    'oldValue': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
}
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'penaltyPoints': pl.Float64,
    'pmsCurrencyCode': pl.Utf8,
    'points': pl.Float64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
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
membership_transaction_header_details_schema = {
    'batchIDCode': pl.Float64,
    'cardNumber': pl.Utf8,
    'chainCode': pl.Utf8,
    'complete': pl.Float64,
    'dSI': pl.Int64,
    'deleted': pl.Float64,
    'deletedFlag': pl.Utf8,
    'error': pl.Float64,
    'evaluationDate': pl.Utf8,
    'expirationDate': pl.Utf8,
    'fromDate': pl.Utf8,
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'pending': pl.Float64,
    'primaryKeyID': pl.Int64,
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
```
```python
expire_points_by_date_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'expirationDate': pl.Utf8,
    'expireByDate': pl.Float64,
    'membershipId': pl.Float64,
    'organizationID': pl.Int64,
    'totalExpire': pl.Float64,
}
```