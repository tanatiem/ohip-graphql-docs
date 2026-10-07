# ProfilesMembershipTransactions
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `profilesMembershipTransactions`
> Provides information on Stay Records statistics of guest stay and its respective Membership Transactions details for a profile
  
**Return:** [`[ProfilesMembershipTransactionsType]`](#profilesmembershiptransactionstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ProfilesMembershipTransactionsQueryArgumentsType!`](#profilesmembershiptransactionsqueryargumentstype) |  |

## Object Types

### ProfilesMembershipTransactionsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | membershipTransactionsDetails | [`ProfilesMembershipTransactionsMembershipTransactionsDetailsType`](#profilesmembershiptransactionsmembershiptransactionsdetailstype) | Membership Transactions Details |
| 2 | stayRecords | [`ProfilesMembershipTransactionsStayRecordsType`](#profilesmembershiptransactionsstayrecordstype) | Stay Records |
| 3 | stayRecordsMemberships | [`ProfilesMembershipTransactionsStayRecordsMembershipsType`](#profilesmembershiptransactionsstayrecordsmembershipstype) | Stay Records Memberships |
| 4 | membershipTransactionRevenuesDetails | [`ProfilesMembershipTransactionsMembershipTransactionRevenuesDetailsType`](#profilesmembershiptransactionsmembershiptransactionrevenuesdetailstype) | Membership Transaction Revenues |
| 5 | membershipTransactionDailyRatesDetails | [`ProfilesMembershipTransactionsMembershipTransactionDailyRatesDetailsType`](#profilesmembershiptransactionsmembershiptransactiondailyratesdetailstype) | Membership Transaction Daily Rates |
| 6 | membershipRejectCommentsDetails | [`ProfilesMembershipTransactionsMembershipRejectCommentsDetailsType`](#profilesmembershiptransactionsmembershiprejectcommentsdetailstype) | Membership Reject Comments Details |
| 7 | profilesMembershipTransactionsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ProfilesMembershipTransactionsMembershipTransactionsDetailsType

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
| 87 | referredMember | `String` | Name ID of member referred. |
| 88 | reservationNameID | `Float` | Reservation Name ID |
| 89 | reservationStatus | `String` | Reservation Status |
| 90 | roomLabel | `String` | Room Label |
| 91 | statementId | `Float` | Statement ID |
| 92 | stay | `Float` | Total stay. |
| 93 | stayRecordId | `Float` | Stay Record ID |
| 94 | tierAction | `String` | Type of action performed. |
| 95 | totalEligibleAwardRedeem | `Float` | Total monetary value of transactions on the guest account eligible to redeem Instant Award payments. |
| 96 | totalEligibleCreditEarn | `Float` | Total monetary value of transactions on the guest account eligible to earn membership credits. |
| 97 | totalPoints | `Float` | Total Points |
| 98 | totalRevenue | `Float` | Total Revenue |
| 99 | transactionDate | `Date` | Transaction date. |
| 100 | transactionType | `String` | Transaction Type |
| 101 | updateDate | `DateTime` | Update Date |
| 102 | updateUser | `Float` | Update User |
| 103 | username | `String` | Username |

[⬆ Back to Query](#query)

---

### ProfilesMembershipTransactionsStayRecordsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | address1 | `String` | Address 1 |
| 2 | address2 | `String` | Address 2 |
| 3 | address3 | `String` | Address 3 |
| 4 | address4 | `String` | Address 4 |
| 5 | adjustmentYN | `String` | Adjustment YN |
| 6 | adults | `Float` | Adults |
| 7 | allotmentCode | `String` | Allotment Code |
| 8 | allotmentHeaderID | `Float` | Allotment Header ID |
| 9 | arrival | `Date` | Arrival |
| 10 | averageRateAmount | `Float` | Block Code |
| 11 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 12 | bookedArrivalDate | `Date` | Booked Arrival Date |
| 13 | bookedDepartureDate | `Date` | Booked Departure Date |
| 14 | bookedRoomType | `String` | Booked Room Type |
| 15 | bookingDate | `Date` | Booking Date |
| 16 | cCentralBaseRateAmount | `Float` | Central Base Rate Amount |
| 17 | cRSBookNo | `String` | CRS Book No |
| 18 | cancellationDate | `Date` | Cancellation Date |
| 19 | cancelledRoomNights | `Float` | Cancelled Room Nights |
| 20 | centralBaseRateAmount | `Float` | Central Base Rate Amount |
| 21 | centralCurrency | `String` | Central Currency |
| 22 | centralFBRevenue | `Float` | Central FB Revenue |
| 23 | centralFBRevenueTax | `Float` | Central FB Revenue Tax |
| 24 | centralLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 25 | centralMiscRevenue | `Float` | Central Misc Revenue |
| 26 | centralMiscRevenueTax | `Float` | Central Misc Revenue Tax |
| 27 | centralOtherRevenue | `Float` | Central Other Revenue |
| 28 | centralOtherRevenueTax | `Float` | Central Other Revenue Tax |
| 29 | centralRoomRevenue | `Float` | Central Room Revenue |
| 30 | centralRoomRevenueTax | `Float` | Central Room Revenue Tax |
| 31 | centralTotalRevenue | `Float` | Central Total Revenue |
| 32 | centralXchangeDate | `Date` | Central Xchange Date |
| 33 | centralXchangeRate | `Float` | Central Xchange Rate |
| 34 | chainCode | `String` | Chain Code |
| 35 | children | `Float` | Children |
| 36 | city | `String` | City |
| 37 | companyName | `String` | Company Name |
| 38 | companyNameID | `Float` | Company Name ID |
| 39 | complimentary | `String` | Complimentary |
| 40 | country | `String` | Country |
| 41 | dSI | `Float` | DSI |
| 42 | dailyRoomDetailsYN | `String` | Daily Room Details YN |
| 43 | deletedFlag | `String` | Deleted Flag |
| 44 | departure | `Date` | Departure |
| 45 | exchangeRate | `Float` | Exchange Rate |
| 46 | fBRevenue | `Float` | F&B Revenue |
| 47 | fBRevenueTax | `Float` | F&B Revenue Tax |
| 48 | groupName | `String` | Group Name |
| 49 | groupNameID | `Float` | Group Name ID |
| 50 | guestName | `String` | Guest Name |
| 51 | guestNameID | `Float` | Guest Name ID |
| 52 | iATAConsortia | `String` | IATA Consortia |
| 53 | insertDate | `DateTime` | Insert Date |
| 54 | insertUser | `Float` | Insert user |
| 55 | internalShareID | `Float` | Internal Share ID |
| 56 | jRNUpdateDate | `Date` | JRN Update Date |
| 57 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 58 | legNo | `Float` | Leg No |
| 59 | localReservationNameID | `Float` | Local Reservation Name ID |
| 60 | marketCode | `String` | Market Code |
| 61 | membershipTRXLinkID | `Float` | Membership TRX Link ID |
| 62 | miscNameID | `Float` | Misc Name ID |
| 63 | miscRevenueTax | `Float` | Misc Revenue Tax |
| 64 | miscellaneousRevenue | `Float` | Miscellaneous Revenue |
| 65 | noShowRoomNights | `Float` | No Show Room Nights |
| 66 | numberStay | `Float` | Number Stay |
| 67 | numberOfNughts | `Float` | Number of Nughts |
| 68 | organizationID | `Float` | Organization ID |
| 69 | originCode | `String` | Origin Code |
| 70 | originalSource | `String` | Original Source |
| 71 | otherRevenue | `Float` | Other Revenue |
| 72 | otherRevenueTax | `Float` | Other Revenue Tax |
| 73 | pKID | `Float` | PKID |
| 74 | pMSGroupID | `String` | PMS  Group ID |
| 75 | pMSMiscID | `String` | PMS  Misc ID |
| 76 | pMSNameID | `String` | PMS  Name ID |
| 77 | pMSCompanyID | `String` | PMS Company ID |
| 78 | pMSConfirmationNumber | `String` | PMS Confirmation Number |
| 79 | pMSResvNo | `String` | PMS Resv No |
| 80 | pMSTravelID | `String` | PMS Travel ID |
| 81 | pMSWholesalerID | `String` | PMS Wholesaler ID |
| 82 | pOSCode | `String` | POS Code |
| 83 | paymentMethod | `String` | Payment Method |
| 84 | pointsYN | `String` | Points YN |
| 85 | primarySharer | `String` | Primary Sharer |
| 86 | promotionCode | `String` | Promotion Code |
| 87 | promotionCode2 | `String` | Promotion Code  2 |
| 88 | promotionCode3 | `String` | Promotion Code  3 |
| 89 | promotionCodeDesc | `String` | Promotion Code Desc |
| 90 | property | `String` | Property |
| 91 | propertyCurrency | `String` | Property Currency |
| 92 | pseudoYN | `String` | Pseudo YN |
| 93 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 94 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 95 | rate | `Float` | Rate |
| 96 | rateCode | `String` | Rate Code |
| 97 | reservationNameID | `Float` | Reservation Name ID |
| 98 | reservationSourceCode | `String` | Reservation Source Code |
| 99 | reservationSourceType | `String` | Reservation Source Type |
| 100 | reservationStatus | `String` | Reservation Status |
| 101 | roomNumber | `String` | Room Number |
| 102 | roomRevenue | `Float` | Room Revenue |
| 103 | roomRevenueTax | `Float` | Room Revenue Tax |
| 104 | roomType | `String` | Room Type |
| 105 | shareNumber | `String` | Share Number |
| 106 | sourceCode | `String` | Source Code |
| 107 | sourceName | `String` | Source Name |
| 108 | sourceNameID | `Float` | Source Name ID |
| 109 | sourceRecordLocator | `String` | Source Record Locator |
| 110 | state | `String` | State |
| 111 | status | `String` | Status |
| 112 | statusDescription | `String` | Status Description |
| 113 | stayRecordID | `Float` | Stay Record ID |
| 114 | totalRevenue | `Float` | Total Revenue |
| 115 | travelAgentName | `String` | Travel Agent Name |
| 116 | travelAgentNameID | `Float` | Travel Agent Name ID |
| 117 | uDFC01 | `String` | UDFC01 |
| 118 | uDFC02 | `String` | UDFC02 |
| 119 | uDFC03 | `String` | UDFC03 |
| 120 | uDFC04 | `String` | UDFC04 |
| 121 | uDFC05 | `String` | UDFC05 |
| 122 | uDFC06 | `String` | UDFC06 |
| 123 | uDFC07 | `String` | UDFC07 |
| 124 | uDFC08 | `String` | UDFC08 |
| 125 | uDFC09 | `String` | UDFC09 |
| 126 | uDFC10 | `String` | UDFC10 |
| 127 | uDFD01 | `Date` | UDFD01 |
| 128 | uDFD02 | `Date` | UDFD02 |
| 129 | uDFD03 | `Date` | UDFD03 |
| 130 | uDFD04 | `Date` | UDFD04 |
| 131 | uDFD05 | `Date` | UDFD05 |
| 132 | uDFN01 | `Float` | UDFN01 |
| 133 | uDFN02 | `Float` | UDFN02 |
| 134 | uDFN03 | `Float` | UDFN03 |
| 135 | uDFN04 | `Float` | UDFN04 |
| 136 | uDFN05 | `Float` | UDFN05 |
| 137 | updateDate | `Date` | Update Date |
| 138 | updateUser | `Float` | Update User |
| 139 | userNotes | `String` | User Notes |

[⬆ Back to Query](#query)

---

### ProfilesMembershipTransactionsStayRecordsMembershipsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | cRTCode | `String` | CRT Code |
| 2 | cRTMembershipLevel | `String` | CRT Membership Level |
| 3 | cRTProcessStatus | `String` | CRT Process Status |
| 4 | centralExchangeDate | `Date` | Central Exchange Date |
| 5 | centralExchangeRate | `Float` | Central Exchange Rate |
| 6 | centralMembershipBaseRevenue | `Float` | Central Membership Base Revenue |
| 7 | centralMembershipBonusRevenue | `Float` | Central Membership Bonus Revenue |
| 8 | centralPointsCost | `Float` | Central Points Cost |
| 9 | chainCode | `String` | Chain Code |
| 10 | dSI | `Float` | DSI |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | errorMessage | `String` | Error Message |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | membershipBaseNights | `Float` | Membership Base Nights |
| 15 | membershipBaseRevenue | `Float` | Membership Base Revenue |
| 16 | membershipBaseStay | `Float` | Membership Base Stay |
| 17 | membershipBonusNights | `Float` | Membership Bonus Nights |
| 18 | membershipBonusRevenue | `Float` | Membership Bonus Revenue |
| 19 | membershipBonusStay | `Float` | Membership Bonus Stay |
| 20 | membershipID | `Float` | Membership ID |
| 21 | membershipLevel | `String` | Membership Level |
| 22 | membershipNumber | `String` | Membership Number |
| 23 | membershipType | `String` | Membership Type |
| 24 | nameID | `Float` | Name ID |
| 25 | nameRole | `String` | Name Role |
| 26 | organizationID | `Float` | Organization ID |
| 27 | pointsComputedDate | `Date` | Points Computed Date |
| 28 | pointsCost | `Float` | Points Cost |
| 29 | pointsEligibleYN | `String` | Points Eligible YN |
| 30 | populationMethod | `String` | Population Method |
| 31 | primaryKeyID | `Float` | Primary Key ID |
| 32 | processingMessage | `String` | Processing Message |
| 33 | promotionCode1 | `String` | Promotion Code 1 |
| 34 | promotionCode2 | `String` | Promotion Code 2 |
| 35 | promotionCode3 | `String` | Promotion Code 3 |
| 36 | property | `String` | Property |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `Date` | RNA Update Date |
| 39 | recordType | `String` | Record Type |
| 40 | reportID | `Float` | Report ID |
| 41 | stayRecordID | `Float` | Stay Record ID |
| 42 | totalBasePoints | `Float` | Total Base Points |
| 43 | totalBonusPoints | `Float` | Total Bonus Points |
| 44 | totalMiscPoints | `Float` | Total Misc Points |
| 45 | totalPoints | `Float` | Total Points |
| 46 | validYN | `String` | Valid YN |

[⬆ Back to Query](#query)

---

### ProfilesMembershipTransactionsMembershipTransactionRevenuesDetailsType

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

### ProfilesMembershipTransactionsMembershipTransactionDailyRatesDetailsType

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

### ProfilesMembershipTransactionsMembershipRejectCommentsDetailsType

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

### ProfilesMembershipTransactionsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| membershiptransactionsDetailsAdjustmentYn | `StringInput` | Adjustment Y/N<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsBeginDate | `DateInput` | Arrival Date<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsAutomaticYn | `StringInput` | Points calculated automatically |
| membershiptransactionsDetailsBaseBillingGroup | `StringInput` | Billing group for base award points.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsBillingGroup | `StringInput` | Billing Group<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsBonusBillingGroup | `StringInput` | Billing group for bonus award points.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsBookedRoomLabel | `StringInput` | Booked Room Label |
| membershiptransactionsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershiptransactionsDetailsCrsBookNo | `StringInput` | CRS Booking Number |
| membershiptransactionsDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| membershiptransactionsDetailsClaimAdjLimitCode | `StringInput` | Claim Adj Limit Code |
| membershiptransactionsDetailsCurrencyCode | `StringInput` | Currency Code |
| membershiptransactionsDetailsDataExportedDate | `DateInput` | Date when the record was exported.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsDataExportedYn | `StringInput` | Flag to indicate if record was exported.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsDeletedFlag | `StringInput` | Deleted Flag |
| membershiptransactionsDetailsEndDate | `DateInput` | Departure Date<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsExceptionType | `StringInput` | Exception Type |
| membershiptransactionsDetailsPointsExpirationDate | `DateTimeInput` | Point Expiration date.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsGraceRenewalFlg | `StringInput` | This flag indicate if grace renewals was done. |
| membershiptransactionsDetailsInactiveDate | `DateInput` | Inactive Date |
| membershiptransactionsDetailsInsertDate | `DateTimeInput` | Insert Date |
| membershiptransactionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMemberStatementId | `FloatInput` | Member Statement ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMembershipCardNo | `StringInput` | Membership Card Number<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMembershipId | `FloatInput` | Membership ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMembershipLevel | `StringInput` | Membership Level |
| membershiptransactionsDetailsMembershipTrxId | `FloatInput` | Membership Trx ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMembershipTrxLinkId | `FloatInput` | Membership Trx Link ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMembershipType | `StringInput` | Membership Type<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsMultipleMembershipId | `FloatInput` | Multiple Membership ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsNameId | `FloatInput` | Name ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsNewMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate new membership level. |
| membershiptransactionsDetailsUserNotes | `StringInput` | Notes |
| membershiptransactionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptransactionsDetailsOrigMemberLevel | `StringInput` | Used in membership tier upgrade rule to indicate original member level was upgraded to. |
| membershiptransactionsDetailsOrigPointsExpirationDate | `DateTimeInput` | Date when points expired before it was extended. |
| membershiptransactionsDetailsPmsResvNo | `StringInput` | PMS Reservation Number<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsParentMembershipTrxId | `FloatInput` | Ref to parent transaction. |
| membershiptransactionsDetailsPmsNameId | `StringInput` | Pms Name ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsPmsResvNameId | `StringInput` | Pms Resv Name ID |
| membershiptransactionsDetailsPointsAcYn | `StringInput` | Iindicate membership exceptions of back to back stay and multiple rooms. Valid values are YN and E.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsPointsCalculatedYn | `StringInput` | Flag to indicate if points are calculated.<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsPointsCreditDate | `DateInput` | Date when points were created. |
| membershiptransactionsDetailsPointsRejectedReason | `StringInput` | Point reject reason. |
| membershiptransactionsDetailsAdjRuleCode | `StringInput` | Rule code for adjustment transactions. |
| membershiptransactionsDetailsPopulationMethod | `StringInput` | Population Method |
| membershiptransactionsDetailsPosCode | `StringInput` | Pos Code<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| membershiptransactionsDetailsProcessingMessages | `StringInput` | Any error messages generated during calculation. |
| membershiptransactionsDetailsPromotionCode2 | `StringInput` | Profile Promotion 1<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsPromotionCode3 | `StringInput` | Profile Promotion 2<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsResort | `StringInput` | Code to uniquely identify the Property<br>`@conditionalInputPair(pair: 1)` |
| membershiptransactionsDetailsPromotionCode1 | `StringInput` | Rate Promotion Code |
| membershiptransactionsDetailsPromotionCode1Desc | `StringInput` | Rate Promotion Description |
| membershiptransactionsDetailsRecordType | `StringInput` | Record Type Code<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsRecordTypeDesc | `StringInput` | Record Type Description |
| membershiptransactionsDetailsResvStatus | `StringInput` | Reservation Status |
| membershiptransactionsDetailsRoomLabel | `StringInput` | Room Label |
| membershiptransactionsDetailsStatementId | `FloatInput` | Statement ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsStayRecordId | `FloatInput` | Stay Record ID<br>`@conditionalInputPair(pair: 2)` |
| membershiptransactionsDetailsTierAction | `StringInput` | Type of action performed. |
| membershiptransactionsDetailsMembershipTrxDate | `DateInput` | Transaction date. |
| membershiptransactionsDetailsTransactionType | `StringInput` | Transaction Type |
| membershiptransactionsDetailsUpdateDate | `DateTimeInput` | Update Date |
| stayrecordsDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| stayrecordsDetailsArrivalDate | `DateInput` | Arrival |
| stayrecordsDetailsChainCode | `StringInput` | Chain Code |
| stayrecordsDetailsCompanyNameId | `FloatInput` | Company Name ID |
| stayrecordsDetailsDepartureDate | `DateInput` | Departure |
| stayrecordsDetailsGroupNameId | `FloatInput` | Group Name ID |
| stayrecordsDetailsGuestNameId | `FloatInput` | Guest Name ID |
| stayrecordsDetailsInternalShareId | `FloatInput` | Internal Share ID |
| stayrecordsDetailsJrnUpdateDttm | `DateTimeInput` | JRN Update Date and Time |
| stayrecordsDetailsLegNo | `FloatInput` | Leg No |
| stayrecordsDetailsLocalResvNameId | `FloatInput` | Local Reservation Name ID |
| stayrecordsDetailsMembershipTrxLinkId | `FloatInput` | Membership TRX Link ID |
| stayrecordsDetailsMiscNameId | `FloatInput` | Misc Name ID |
| stayrecordsDetailsPmsGroupId | `StringInput` | PMS  Group ID |
| stayrecordsDetailsPmsMiscId | `StringInput` | PMS  Misc ID |
| stayrecordsDetailsPmsNameId | `StringInput` | PMS  Name ID |
| stayrecordsDetailsPmsCompanyId | `StringInput` | PMS Company ID |
| stayrecordsDetailsPmsResvNameId | `StringInput` | PMS Confirmation Number |
| stayrecordsDetailsPmsResvNo | `StringInput` | PMS Resv No |
| stayrecordsDetailsPmsTravelId | `StringInput` | PMS Travel ID |
| stayrecordsDetailsPmsWholesalerId | `StringInput` | PMS Wholesaler ID |
| stayrecordsDetailsPosCode | `StringInput` | POS Code |
| stayrecordsDetailsResort | `StringInput` | Property |
| stayrecordsDetailsRoomNumber | `StringInput` | Room Number |
| stayrecordsDetailsWholesalerNameId | `FloatInput` | Source Name ID |
| stayrecordsDetailsStayRecordId | `FloatInput` | Stay Record ID |
| stayrecordsDetailsTravelNameId | `FloatInput` | Travel Agent Name ID |
| stayrecordsDetailsUpdateDate | `DateInput` | Update Date |
| stayrecordsmembershipsDetailsCtrProcessStatus | `StringInput` | CRT Process Status |
| stayrecordsmembershipsDetailsMembershipId | `FloatInput` | Membership ID |
| stayrecordsmembershipsDetailsMembershipType | `StringInput` | Membership Type |
| stayrecordsmembershipsDetailsNameId | `FloatInput` | Name ID |
| stayrecordsmembershipsDetailsResort | `StringInput` | Property |
| stayrecordsmembershipsDetailsRecordType | `StringInput` | Record Type |
| stayrecordsmembershipsDetailsReportId | `FloatInput` | Report ID |
| stayrecordsmembershipsDetailsStayRecordId | `FloatInput` | Stay Record ID |
| membershiptrxrevenuesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| membershiptrxrevenuesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershiptrxrevenuesDetailsTransactionDate | `DateInput` | Date |
| membershiptrxrevenuesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiptrxrevenuesDetailsMembershipTrxLinkId | `FloatInput` | Membership Trx Link ID |
| membershiptrxrevenuesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershiptrxrevenuesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| membershiptrxrevenuesDetailsTransactionRevenueType | `StringInput` | Transaction code. |
| membershiptrxdailyratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershiprejectcommentsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- membershiptransactionsDetailsChainCode
- membershiptransactionsDetailsResort

**`conditionalInputPair(pair: 2)`**
- membershiptransactionsDetailsAdjustmentYn
- membershiptransactionsDetailsBeginDate
- membershiptransactionsDetailsBaseBillingGroup
- membershiptransactionsDetailsBillingGroup
- membershiptransactionsDetailsBonusBillingGroup
- membershiptransactionsDetailsDataExportedDate
- membershiptransactionsDetailsDataExportedYn
- membershiptransactionsDetailsEndDate
- membershiptransactionsDetailsPointsExpirationDate
- membershiptransactionsDetailsJrnupdatedttm
- membershiptransactionsDetailsMemberStatementId
- membershiptransactionsDetailsMembershipCardNo
- membershiptransactionsDetailsMembershipId
- membershiptransactionsDetailsMembershipTrxId
- membershiptransactionsDetailsMembershipTrxLinkId
- membershiptransactionsDetailsMembershipType
- membershiptransactionsDetailsMultipleMembershipId
- membershiptransactionsDetailsNameId
- membershiptransactionsDetailsPmsResvNo
- membershiptransactionsDetailsPmsNameId
- membershiptransactionsDetailsPointsAcYn
- membershiptransactionsDetailsPointsCalculatedYn
- membershiptransactionsDetailsPosCode
- membershiptransactionsDetailsPromotionCode2
- membershiptransactionsDetailsPromotionCode3
- membershiptransactionsDetailsRecordType
- membershiptransactionsDetailsStatementId
- membershiptransactionsDetailsStayRecordId


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query profilesMembershipTransactions($input: ProfilesMembershipTransactionsQueryArgumentsType!) {
  profilesMembershipTransactions(input: $input) @stream {
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
      referredMember
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
    stayRecords {
      address1
      address2
      address3
      address4
      adjustmentYN
      adults
      allotmentCode
      allotmentHeaderID
      arrival
      averageRateAmount
      baseRateCurrencyCode
      bookedArrivalDate
      bookedDepartureDate
      bookedRoomType
      bookingDate
      cCentralBaseRateAmount
      cRSBookNo
      cancellationDate
      cancelledRoomNights
      centralBaseRateAmount
      centralCurrency
      centralFBRevenue
      centralFBRevenueTax
      centralLocalBaseRateAmount
      centralMiscRevenue
      centralMiscRevenueTax
      centralOtherRevenue
      centralOtherRevenueTax
      centralRoomRevenue
      centralRoomRevenueTax
      centralTotalRevenue
      centralXchangeDate
      centralXchangeRate
      chainCode
      children
      city
      companyName
      companyNameID
      complimentary
      country
      dSI
      dailyRoomDetailsYN
      deletedFlag
      departure
      exchangeRate
      fBRevenue
      fBRevenueTax
      groupName
      groupNameID
      guestName
      guestNameID
      iATAConsortia
      insertDate
      insertUser
      internalShareID
      jRNUpdateDate
      jRNUpdateDateAndTime
      legNo
      localReservationNameID
      marketCode
      membershipTRXLinkID
      miscNameID
      miscRevenueTax
      miscellaneousRevenue
      noShowRoomNights
      numberStay
      numberOfNughts
      organizationID
      originCode
      originalSource
      otherRevenue
      otherRevenueTax
      pKID
      pMSGroupID
      pMSMiscID
      pMSNameID
      pMSCompanyID
      pMSConfirmationNumber
      pMSResvNo
      pMSTravelID
      pMSWholesalerID
      pOSCode
      paymentMethod
      pointsYN
      primarySharer
      promotionCode
      promotionCode2
      promotionCode3
      promotionCodeDesc
      property
      propertyCurrency
      pseudoYN
      rNAInsertDate
      rNAUpdateDate
      rate
      rateCode
      reservationNameID
      reservationSourceCode
      reservationSourceType
      reservationStatus
      roomNumber
      roomRevenue
      roomRevenueTax
      roomType
      shareNumber
      sourceCode
      sourceName
      sourceNameID
      sourceRecordLocator
      state
      status
      statusDescription
      stayRecordID
      totalRevenue
      travelAgentName
      travelAgentNameID
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
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      updateDate
      updateUser
      userNotes
    }
    stayRecordsMemberships {
      cRTCode
      cRTMembershipLevel
      cRTProcessStatus
      centralExchangeDate
      centralExchangeRate
      centralMembershipBaseRevenue
      centralMembershipBonusRevenue
      centralPointsCost
      chainCode
      dSI
      deletedFlag
      errorMessage
      jRNUpdateDateAndTime
      membershipBaseNights
      membershipBaseRevenue
      membershipBaseStay
      membershipBonusNights
      membershipBonusRevenue
      membershipBonusStay
      membershipID
      membershipLevel
      membershipNumber
      membershipType
      nameID
      nameRole
      organizationID
      pointsComputedDate
      pointsCost
      pointsEligibleYN
      populationMethod
      primaryKeyID
      processingMessage
      promotionCode1
      promotionCode2
      promotionCode3
      property
      rNAInsertDate
      rNAUpdateDate
      recordType
      reportID
      stayRecordID
      totalBasePoints
      totalBonusPoints
      totalMiscPoints
      totalPoints
      validYN
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
    'referredMember': pl.Utf8,
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
stay_records_schema = {
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'adjustmentYN': pl.Utf8,
    'adults': pl.Float64,
    'allotmentCode': pl.Utf8,
    'allotmentHeaderID': pl.Float64,
    'arrival': pl.Utf8,
    'averageRateAmount': pl.Float64,
    'baseRateCurrencyCode': pl.Utf8,
    'bookedArrivalDate': pl.Utf8,
    'bookedDepartureDate': pl.Utf8,
    'bookedRoomType': pl.Utf8,
    'bookingDate': pl.Utf8,
    'cCentralBaseRateAmount': pl.Float64,
    'cRSBookNo': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancelledRoomNights': pl.Float64,
    'centralBaseRateAmount': pl.Float64,
    'centralCurrency': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralFBRevenueTax': pl.Float64,
    'centralLocalBaseRateAmount': pl.Float64,
    'centralMiscRevenue': pl.Float64,
    'centralMiscRevenueTax': pl.Float64,
    'centralOtherRevenue': pl.Float64,
    'centralOtherRevenueTax': pl.Float64,
    'centralRoomRevenue': pl.Float64,
    'centralRoomRevenueTax': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'chainCode': pl.Utf8,
    'children': pl.Float64,
    'city': pl.Utf8,
    'companyName': pl.Utf8,
    'companyNameID': pl.Float64,
    'complimentary': pl.Utf8,
    'country': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRoomDetailsYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departure': pl.Utf8,
    'exchangeRate': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueTax': pl.Float64,
    'groupName': pl.Utf8,
    'groupNameID': pl.Float64,
    'guestName': pl.Utf8,
    'guestNameID': pl.Float64,
    'iATAConsortia': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalShareID': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'legNo': pl.Float64,
    'localReservationNameID': pl.Float64,
    'marketCode': pl.Utf8,
    'membershipTRXLinkID': pl.Float64,
    'miscNameID': pl.Float64,
    'miscRevenueTax': pl.Float64,
    'miscellaneousRevenue': pl.Float64,
    'noShowRoomNights': pl.Float64,
    'numberStay': pl.Float64,
    'numberOfNughts': pl.Float64,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originalSource': pl.Utf8,
    'otherRevenue': pl.Float64,
    'otherRevenueTax': pl.Float64,
    'pKID': pl.Float64,
    'pMSGroupID': pl.Utf8,
    'pMSMiscID': pl.Utf8,
    'pMSNameID': pl.Utf8,
    'pMSCompanyID': pl.Utf8,
    'pMSConfirmationNumber': pl.Utf8,
    'pMSResvNo': pl.Utf8,
    'pMSTravelID': pl.Utf8,
    'pMSWholesalerID': pl.Utf8,
    'pOSCode': pl.Utf8,
    'paymentMethod': pl.Utf8,
    'pointsYN': pl.Utf8,
    'primarySharer': pl.Utf8,
    'promotionCode': pl.Utf8,
    'promotionCode2': pl.Utf8,
    'promotionCode3': pl.Utf8,
    'promotionCodeDesc': pl.Utf8,
    'property': pl.Utf8,
    'propertyCurrency': pl.Utf8,
    'pseudoYN': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rate': pl.Float64,
    'rateCode': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationSourceCode': pl.Utf8,
    'reservationSourceType': pl.Utf8,
    'reservationStatus': pl.Utf8,
    'roomNumber': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueTax': pl.Float64,
    'roomType': pl.Utf8,
    'shareNumber': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceNameID': pl.Float64,
    'sourceRecordLocator': pl.Utf8,
    'state': pl.Utf8,
    'status': pl.Utf8,
    'statusDescription': pl.Utf8,
    'stayRecordID': pl.Float64,
    'totalRevenue': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentNameID': pl.Float64,
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
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userNotes': pl.Utf8,
}
```
```python
stay_records_memberships_schema = {
    'cRTCode': pl.Utf8,
    'cRTMembershipLevel': pl.Utf8,
    'cRTProcessStatus': pl.Utf8,
    'centralExchangeDate': pl.Utf8,
    'centralExchangeRate': pl.Float64,
    'centralMembershipBaseRevenue': pl.Float64,
    'centralMembershipBonusRevenue': pl.Float64,
    'centralPointsCost': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'errorMessage': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipBaseNights': pl.Float64,
    'membershipBaseRevenue': pl.Float64,
    'membershipBaseStay': pl.Float64,
    'membershipBonusNights': pl.Float64,
    'membershipBonusRevenue': pl.Float64,
    'membershipBonusStay': pl.Float64,
    'membershipID': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipNumber': pl.Utf8,
    'membershipType': pl.Utf8,
    'nameID': pl.Float64,
    'nameRole': pl.Utf8,
    'organizationID': pl.Int64,
    'pointsComputedDate': pl.Utf8,
    'pointsCost': pl.Float64,
    'pointsEligibleYN': pl.Utf8,
    'populationMethod': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'processingMessage': pl.Utf8,
    'promotionCode1': pl.Utf8,
    'promotionCode2': pl.Utf8,
    'promotionCode3': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'recordType': pl.Utf8,
    'reportID': pl.Float64,
    'stayRecordID': pl.Float64,
    'totalBasePoints': pl.Float64,
    'totalBonusPoints': pl.Float64,
    'totalMiscPoints': pl.Float64,
    'totalPoints': pl.Float64,
    'validYN': pl.Utf8,
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