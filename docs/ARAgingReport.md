# ARAgingReport
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
## Query
### `aRAgingReport`
> Detailed information on accounts receivable transactions including aging bucket of invoices open transaction amounts folio information and the account details.
  
**Return:** [`[ARAgingReportType]`](#aragingreporttype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ARAgingReportQueryArgumentsType!`](#aragingreportqueryargumentstype) |  |

## Object Types

### ARAgingReportType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRAgingReportDetails | [`ARAgingReportARAgingReportDetailsType`](#aragingreportaragingreportdetailstype) | AR Aging Report |
| 2 | transactionCodeDetails | [`ARAgingReportTransactionCodeDetailsType`](#aragingreporttransactioncodedetailstype) | Transaction Code |
| 3 | folioDetails | [`ARAgingReportFolioDetailsType`](#aragingreportfoliodetailstype) | Folio Details |
| 4 | financialTransactionDetails | [`ARAgingReportFinancialTransactionDetailsType`](#aragingreportfinancialtransactiondetailstype) | Financial Transaction |
| 5 | accountDetails | [`ARAgingReportAccountDetailsType`](#aragingreportaccountdetailstype) | Account Details |
| 6 | calendarPeriodDayDetails | [`ARAgingReportCalendarPeriodDayDetailsType`](#aragingreportcalendarperioddaydetailstype) | Calendar Period Daily Details |
| 7 | financialPeriodDayDetails | [`ARAgingReportFinancialPeriodDayDetailsType`](#aragingreportfinancialperioddaydetailstype) | Financial Period Daily Details |
| 8 | aRLedgerDetails | [`ARAgingReportARLedgerDetailsType`](#aragingreportarledgerdetailstype) | AR Ledger |
| 9 | invoiceHeaderDetails | [`ARAgingReportInvoiceHeaderDetailsType`](#aragingreportinvoiceheaderdetailstype) | Invoice Header Details |
| 10 | propertyPropertyDetails | [`ARAgingReportPropertyPropertyDetailsType`](#aragingreportpropertypropertydetailstype) | Resort Details |
| 11 | aRAgingReportRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ARAgingReportARAgingReportDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | CHAIN_CODE |
| 2 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 3 | accountCode | `Float` | Account Code |
| 4 | accountName | `String` | Account Name |
| 5 | accountNumber | `String` | NOT IN USE |
| 6 | accountType | `String` | Account Type |
| 7 | accountid | `Float` | Accountid |
| 8 | age1 | `Float` | Age 1 |
| 9 | age2 | `Float` | Age 2 |
| 10 | age3 | `Float` | Age 3 |
| 11 | age4 | `Float` | Age 4 |
| 12 | age5 | `Float` | Age 5 |
| 13 | age6 | `Float` | Age 6 |
| 14 | agingbucket | `Float` | Agingbucket |
| 15 | arTransferDate | `Date` | AR Transfer Date |
| 16 | billNumber | `Float` | Bill Number |
| 17 | billingContactName | `String` | Contact information. |
| 18 | businessDate | `Date` | Business Date |
| 19 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 20 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 21 | cAmount | `Float` | Central Amount |
| 22 | cContractCurrencyDifference | `Float` | Central Contract Curr Diff |
| 23 | cExchangeDate | `Date` | Central Xchange Date |
| 24 | cExchangeRate | `Float` | Central Xchange Rate |
| 25 | cOrganizationAmount | `Float` | Central Org Amt |
| 26 | cOrganizationAmountContract | `Float` | Central Org Amt Contract |
| 27 | cOrganizationAmountCurrencyDifference | `Float` | Central Org Amt Curr Diff |
| 28 | cOrganizationAmountParallel | `Float` | Central Org Amt Parallel |
| 29 | cParallelCurrencyDifference | `Float` | Central Parallel Curr Diff |
| 30 | centralAccountType | `String` | Central Account Type |
| 31 | centralOpenARTransactionAmount | `Float` | Central Open AR Transaction Amount |
| 32 | checkOutDate | `Date` | Date on which the guest was checked out. |
| 33 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 34 | dateForAging | `String` | Date the aging should begin |
| 35 | fintransid | `Float` | Fintransid |
| 36 | folioNo | `Float` | Folio Number |
| 37 | folioid | `Float` | Folioid |
| 38 | internalCheckoutDate | `Date` | Checkout Date |
| 39 | invoiceAge | `Float` | Invoice Age |
| 40 | invoiceCloseDate | `Date` | Invoice Close Date |
| 41 | invoiceNo | `Float` | Invoice Number |
| 42 | invoiceNumber | `Float` | Invoice Number |
| 43 | invoiceStatus | `String` | Invoice Status |
| 44 | invoiceamount | `Float` | Invoiceamount |
| 45 | invoiceid | `Float` | Invoiceid |
| 46 | invoiceprofileid | `Float` | Invoiceprofileid |
| 47 | jRNUpdateDate | `Date` | JRN Update Date |
| 48 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 49 | locationID | `String` | Internal ID to uniquely identify the Property |
| 50 | masterInvoiceNo | `Float` | Compressed Invoice No for which multiple invoices have been compressed to. |
| 51 | nameId | `Float` | Name ID |
| 52 | openARTransactionAmount | `Float` | Open AR Transaction Amount |
| 53 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 54 | ownerRoom | `String` | The owner room where this invoice/payment belongs to. |
| 55 | ownerroomid | `String` | Ownerroomid |
| 56 | pmsBusinessDate | `Date` | Pms Business Date |
| 57 | postDate | `Date` | Date + time the phone charge was posted. |
| 58 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 59 | property | `String` | Code to uniquely identify the Property |
| 60 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 61 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 62 | reservationNameId | `Float` | Resv Name ID |
| 63 | reservationid | `Float` | Reservationid |
| 64 | room | `String` | Room |
| 65 | roomid | `String` | Roomid |
| 66 | transactionFromAcct | `Float` | Trns From Account |
| 67 | transactionToAcct | `Float` | Trns To Account |
| 68 | transactionid | `Float` | Transactionid |
| 69 | transcodeid | `String` | Transcodeid |
| 70 | transferfromaccountid | `Float` | Transferfromaccountid |
| 71 | transfertoaccountid | `Float` | Transfertoaccountid |
| 72 | trxCode | `String` | Transaction Code |
| 73 | trxDate | `Date` | Transaction Date |
| 74 | trxNumber | `Float` | Transaction No |

[⬆ Back to Query](#query)

---

### ARAgingReportTransactionCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | CHAIN_CODE |
| 2 | aRLedgerPaymentsYN | `String` | AR Ledger Payments YN |
| 3 | aRNameId | `Float` | Ar Name ID |
| 4 | accountNumber | `String` | Account Number |
| 5 | accountingCode | `String` | Accounting Code |
| 6 | acctrecvprofileid | `Float` | Acctrecvprofileid |
| 7 | adjTrxCode | `String` | Adj Trx Code |
| 8 | adjtranscodeid | `String` | Adjtranscodeid |
| 9 | arrangeCode | `String` | Arrange Code |
| 10 | arrangementCode | `String` | Arrangement Code |
| 11 | cDefaultPrice | `Float` | Central Default Price |
| 12 | cExchangeDate | `Date` | Central Xchange Date |
| 13 | cExchangeRate | `Float` | Central Xchange Rate |
| 14 | cExportBucket | `Float` | Central Export Bucket |
| 15 | cMaxAmount | `Float` | Central Max Amt |
| 16 | cMinimumAmount | `Float` | Central Min Amt |
| 17 | cCCode | `String` | CC Code |
| 18 | cRSTaxDesc | `String` | Crs Tax Description |
| 19 | cashTransactionCodeYN | `String` | Cash Transaction Code YN |
| 20 | ccType | `String` | Cc Type |
| 21 | centalSubgroup | `String` | Cental Subgroup |
| 22 | centralAdjustmentTransactionCode | `String` | Central Adjustment Transaction Code |
| 23 | centralTransactionCode | `String` | Central Transaction Code |
| 24 | centralTransactionCodeGroup | `String` | Central Transaction Code Group |
| 25 | chargeDeferredUntilCheckoutYN | `String` | Charge Deferred Until Checkout YN |
| 26 | checkNumberMandatoryYN | `String` | Check Number Mandatory YN |
| 27 | class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| 28 | class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| 29 | commissionCode | `Float` | Commission Code |
| 30 | compNightsYn | `String` | Comp Nights Y/N |
| 31 | compPaymentYn | `String` | Comp Payment Y/N |
| 32 | complimentaryYN | `String` | Complimentary YN |
| 33 | corpPropFlag | `String` | Corp Prop Flag |
| 34 | corporateDescription | `String` | Corporate Description |
| 35 | crossPostingDepositYN | `String` | To indicate that the transaction code can be used as a Deposit Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 36 | crossPostingPaymentYN | `String` | To indicate that the transaction code can be used as a Payment Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 37 | crossPostingSalesYN | `String` | To indicate that the transaction code can be used as a Sales Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 38 | currencyCode | `String` | Currency Code |
| 39 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 40 | dailyPlanFolio | `Float` | Daily Plan Folio |
| 41 | dedOwnerRevenueYN | `String` | Ded Owner Rev Y/N |
| 42 | defaultPrice | `Float` | Default Price |
| 43 | deletedFlag | `String` | Deleted Flag |
| 44 | depositLedgerPaymentsYN | `String` | Deposit Ledger Payments YN |
| 45 | depositPostingOnlyYn | `String` | Deposit Posting Only Y/N |
| 46 | depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| 47 | eInvoiceYn | `String` | E Invoice Y/N |
| 48 | expenseFolio | `Float` | Expense Folio |
| 49 | exportBucket | `Float` | Export Bucket |
| 50 | externalPaymentCode | `String` | External Payment Code |
| 51 | fiscalPaymentYn | `String` | Fiscal Payment Y/N |
| 52 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 53 | foreignCurrencyID | `String` | Foreign Currency ID |
| 54 | gDeletedFlag | `String` | Group Deleted Flag |
| 55 | gDescription | `String` | Group Description |
| 56 | gInsertDate | `DateTime` | Group Insert Date |
| 57 | gInsertUser | `Float` | Group Insert User |
| 58 | gOrderBy | `Float` | Group Order By |
| 59 | gRepDescription | `String` | Group Rep Description |
| 60 | gResultIncludedInSumArray | `String` | Group Result Included In Sum Array |
| 61 | gRevenuegroupflag | `String` | Group Revenuegroupflag |
| 62 | gTctClassType1 | `String` | Group Tct Class Type1 |
| 63 | gTctClassType2 | `String` | Group Tct Class Type2 |
| 64 | gUpdateDate | `DateTime` | Group Update Date |
| 65 | gUpdateUser | `Float` | Group Update User |
| 66 | group | `String` | Group |
| 67 | groupClass1MandatoryYN | `String` | G Class 1 Mandatory Y/N |
| 68 | groupClass2MandatoryYN | `String` | G Class 2 Mandatory Y/N |
| 69 | groupFolio | `Float` | Group Folio |
| 70 | groupIndRevenueGroup | `String` | G Individual Revenue Gp |
| 71 | groupInternalYN | `String` | G Internal Y/N |
| 72 | groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| 73 | groupRepItem | `String` | G Reporting Item |
| 74 | groupRepItemName | `String` | G Reporting Item Name |
| 75 | groupRepItemOrderby | `Float` | G Reporting Item Orderby |
| 76 | groupRepOrderBy | `Float` | G Reporting Order By |
| 77 | groupRepUpdateDate | `DateTime` | G Reporting Updatedate |
| 78 | groupTcTransactionType | `String` | G Transaction Code Transaction Type |
| 79 | guestLedgerPaymentsYN | `String` | Guest Ledger Payments YN |
| 80 | inactiveDate | `Date` | Inactive Date |
| 81 | inactiveflag | `String` | Inactive Flag |
| 82 | includeIn8300Yn | `String` | Include In 8300 Y/N |
| 83 | includeInDepositRuleYn | `String` | Include In Deposit Rule Y/N |
| 84 | insertDate | `DateTime` | Insert Date |
| 85 | insertUser | `Float` | Insert User |
| 86 | internalDeletedflag | `String` | Deleted Flag |
| 87 | internalTransactionCodeSubGroup | `String` | Transaction Code Sub-Group |
| 88 | internalYn | `String` | Internal Y/N |
| 89 | jRNUpdateDate | `Date` | JRN Update Date |
| 90 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 91 | locationID | `String` | Internal ID to uniquely identify the Property |
| 92 | manualPostCoversYn | `String` | Manual Post Covers Y/N |
| 93 | manualPostingAllowedYN | `String` | Manual Posting Allowed YN |
| 94 | maximumAmount | `Float` | Maximum Amount |
| 95 | membershipYN | `String` | Membership YN |
| 96 | minimumAmount | `Float` | Minimum Amount |
| 97 | nonTaxableYn | `String` | Non Taxable Y/N |
| 98 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 99 | ownerRevenueYN | `String` | Owner Rev Y/N |
| 100 | paymentTaxInvoiceYn | `String` | Payment Tax Invoice Y/N |
| 101 | paymentType | `String` | Payment Type |
| 102 | paymentmethodid | `String` | Paymentmethodid |
| 103 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 104 | printReceiptYN | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| 105 | processingType | `String` | Type of process that generated this payment.  IE PaymentCheck out AR or Passerby. |
| 106 | property | `String` | Property |
| 107 | quantityCode | `String` | Quantity Code |
| 108 | repDescription | `String` | Rep Description |
| 109 | repItem | `String` | Reporting Item |
| 110 | repItemName | `String` | Reporting Item Name |
| 111 | repItemOrderby | `Float` | Reporting Item Orderby |
| 112 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 113 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 114 | revenueBucketId | `Float` | Rev Bucket ID |
| 115 | revenueGroupId | `Float` | Rev Gp ID |
| 116 | revenueYN | `String` | Revenue YN |
| 117 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 118 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 119 | rotationRevenueYN | `String` | Rotation Rev Y/N |
| 120 | roundFactorYn | `String` | Round Factor Y/N |
| 121 | serviceRecoveryTrxCode | `String` | Service Recovery Adjustment. |
| 122 | sgDeletedFlag | `String` | Sub-Group Deleted Flag |
| 123 | sgDescription | `String` | Sub-Group Description |
| 124 | sgInsertDate | `DateTime` | Sub-Group Insert Date |
| 125 | sgInsertUser | `Float` | Sub-Group Insert User |
| 126 | sgOrderBy | `Float` | Sub-Group Order By |
| 127 | sgResultIncludedInSumArray | `String` | Sub-Group Result Included In Sum Array |
| 128 | sgRevenuegroupflag | `String` | Sub-Group Revenuegroupflag |
| 129 | sgTaxflag | `String` | Sub-Group Taxflag |
| 130 | sgUpdateDate | `DateTime` | Sub-Group Update Date |
| 131 | sgUpdateUser | `Float` | Sub-Group Update User |
| 132 | subGroupClass1MandatoryYN | `String` | Sg Class 1 Mandatory Y/N |
| 133 | subGroupClass2MandatoryYN | `String` | Sg Class 2 Mandatory Y/N |
| 134 | subGroupFrequentFlyerYN | `String` | Sg Frequent Flyer Y/N |
| 135 | subGroupGroupPointsRedemptionYN | `String` | Sg Gp Points Redemption Y/N |
| 136 | subGroupIndRevenueGroup | `String` | Sg Individual Revenue Gp |
| 137 | subGroupInternalYN | `String` | Sg Internal Y/N |
| 138 | subGroupRepDescription | `String` | Sg Reporting Description |
| 139 | subGroupRepOrderBy | `Float` | Sg Reporting Order By |
| 140 | subGroupTcGroupAndSubgroup | `String` | Sg Transaction Code Group And Subgroup |
| 141 | subGroupTcTransactionType | `String` | Sg Transaction Code Transaction Type |
| 142 | subGroupType | `String` | Sub-Group Type |
| 143 | taxCodeNumber | `Float` | Tax Code Number |
| 144 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 145 | taxYN | `String` | Tax YN |
| 146 | tcBofInterface | `String` | Not Used. |
| 147 | tcBofInterface2 | `String` | Not Used. |
| 148 | tcBofRefCode | `String` | Not Used. |
| 149 | tcBofRefCode2 | `String` | Not Used. |
| 150 | tcResort2 | `String` | Not Used. |
| 151 | tcTransactionType | `String` | Transaction Code Transaction Type |
| 152 | tclCodeDfltCl1 | `String` | Tcl Code Dflt Cl1 |
| 153 | tclCodeDfltCl2 | `String` | Tcl Code Dflt Cl2 |
| 154 | transactionActionId | `Float` | Trx Action ID |
| 155 | transactionCodeDescription | `String` | Transaction Code Description |
| 156 | transactionCodeGroup | `String` | Transaction Code Group |
| 157 | transactionCodeResort | `String` | Not Used. |
| 158 | transactionCodeSubGroup | `String` | Transaction Code Sub-group |
| 159 | transactionCodeType | `String` | Transaction Code Type |
| 160 | transactionType | `String` | Transaction Type |
| 161 | transcodearrangementid | `String` | Transcodearrangementid |
| 162 | transcodeid | `String` | Transcodeid |
| 163 | trxCode | `String` | Trx Code |
| 164 | trxCodeDisplay | `String` | Transaction Code Display |
| 165 | trxServiceType | `String` | Transaction Service Type |
| 166 | trxTaxTypeCode | `String` | Transaction Tax Type Code |
| 167 | uPC | `String` | UPC |
| 168 | updateDate | `DateTime` | Update Date |
| 169 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportFolioDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | billGenerationDate | `Date` | Bill Generation Date |
| 2 | billNumber | `Float` | Bill Number |
| 3 | businessdate | `Date` | Businessdate |
| 4 | cashierId | `Float` | Cashier ID |
| 5 | checkExchangeReceiptNumber | `Float` | Check Exchange Receipt Number |
| 6 | currencyExchangeReceiptNumber | `Float` | Internal number to represent the currency exchange receipt number. |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | folioNo | `Float` | Folio Number |
| 10 | folioSeqNumber | `Float` | Unique number to identify the entry. |
| 11 | folioStatus | `String` | The status to identify whether a guest is getting checked out. |
| 12 | folioStyle | `String` | Folio Style |
| 13 | folioType | `String` | Identify the FOLIO TYPE. |
| 14 | folioView | `Float` | Folio View |
| 15 | folioid | `Float` | Folioid |
| 16 | frontOfficeDate | `Date` | Date when folio is created |
| 17 | fullFolioNo | `String` | Full Folio Number |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | internalUpdatedate | `DateTime` | Update Date |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | locationID | `String` | Internal ID to uniquely identify the Property |
| 24 | name | `String` | Name |
| 25 | nameId | `Float` | Name ID |
| 26 | numberReprints | `Float` | Number Reprints. |
| 27 | numberOfPersons | `Float` | No of persons currently using the account |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | phoneDetails | `String` | Phone Details |
| 30 | postitNo | `Float` | Postit Number |
| 31 | postityn | `String` | Postityn |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | processIdent | `String` | Identifying the process |
| 34 | profileid | `Float` | Profileid |
| 35 | property | `String` | Code to uniquely identify the Property |
| 36 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 37 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 38 | reservationNameId | `Float` | Resv Name ID |
| 39 | reservationid | `Float` | Reservationid |
| 40 | resvdeptrno | `Float` | Resvdeptrno |
| 41 | resvenddate | `Date` | Resvenddate |
| 42 | revisionNumber | `Float` | Revision Number |
| 43 | state | `String` | State |
| 44 | templatePath | `String` | Template path for report defination |
| 45 | timestamp | `Date` | Date on which the folio is created or date of the checkout. |
| 46 | updateDate | `DateTime` | Update Date |
| 47 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportFinancialTransactionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 4 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 5 | aRState | `String` | AR State |
| 6 | aRTransferDate | `Date` | AR Transfer Date |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountCode | `Float` | Account Code |
| 10 | accountName | `String` | Account Name |
| 11 | accountNumber | `String` | Account Number |
| 12 | accountTypeFlag | `String` | Account Type Flag |
| 13 | accountid | `Float` | Accountid |
| 14 | adjustmentYN | `String` | Adjustment YN |
| 15 | advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 17 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 18 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 19 | advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 20 | advgentranscodeid | `String` | Advgentranscodeid |
| 21 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 22 | apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 23 | approvalCode | `String` | Approval Code |
| 24 | approvalDate | `Date` | Approval Date |
| 25 | approvalStatus | `String` | Approval Status |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 31 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 32 | authemployeeid | `Float` | Authemployeeid |
| 33 | authorizer | `String` | Authorizer |
| 34 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 35 | autoSettleYn | `String` | Auto Settle Y/N |
| 36 | billingEventID | `Float` | Billing Event ID |
| 37 | bonusCheckId | `Float` | Bonus Check ID |
| 38 | bucketCode | `String` | Bucket code related to this redemption. |
| 39 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 40 | businessDate | `Date` | Business Date |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cChangeDue | `Float` | Central Change Due |
| 43 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 44 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 45 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 46 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 51 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 52 | cPackageAllowance | `Float` | Central Package Allowance |
| 53 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 54 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 55 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 56 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 57 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 58 | cTaxRate | `Float` | Central Tax Rate |
| 59 | cVatAmount | `Float` | Central Vat Amount |
| 60 | cCApproval | `String` | CC Approval Code |
| 61 | calculatePointsYN | `String` | Calculate Points YN |
| 62 | cashBagNumber | `String` | Cash Bag Number |
| 63 | cashier | `String` | Cashier |
| 64 | cashierCredit | `Float` | Cashier Credit |
| 65 | cashierDebit | `Float` | Cashier Debit |
| 66 | cashierID | `Float` | Cashier ID |
| 67 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 68 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 69 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 70 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 71 | centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| 72 | centralCashierCredit | `Float` | Central Cashier Credit |
| 73 | centralCashierDebit | `Float` | Central Cashier Debit |
| 74 | centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| 75 | centralDepositAmountPaid | `Float` | Central Deposit Amount Paid |
| 76 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 77 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 78 | centralGrossAmount | `Float` | Central Gross Amount |
| 79 | centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| 80 | centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| 81 | centralInHouseCredit | `Float` | Central In-House Credit |
| 82 | centralInHouseDebit | `Float` | Central In-House Debit |
| 83 | centralMarketCode | `String` | Central Market Code |
| 84 | centralMarketDescription | `String` | Central Market Description |
| 85 | centralMarketGroupCode | `String` | Central Market Group Code |
| 86 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 87 | centralNetAmount | `Float` | Central Net Amount |
| 88 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 89 | centralPackage | `String` | Central Package |
| 90 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 91 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 92 | centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| 93 | centralPricePerUnit | `Float` | Central Price Per Unit |
| 94 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 95 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 96 | centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 97 | centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 98 | chainCode | `String` | Chain Code |
| 99 | changeDue | `Float` | Change Due |
| 100 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 101 | checkNumber | `String` | Check Number |
| 102 | closureNumber | `Float` | Closure Number |
| 103 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 104 | comments | `String` | Comments |
| 105 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 106 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 107 | compTypeCode | `String` | Comp Type Code |
| 108 | complinktranscodeid | `String` | Complinktranscodeid |
| 109 | compressedYn | `String` | Compressed Y/N |
| 110 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 111 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 112 | couponNo | `String` | Coupon Number |
| 113 | covers | `String` | Covers |
| 114 | creditCardId | `Float` | Credit Card ID |
| 115 | creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 116 | creditYN | `String` | Credit YN |
| 117 | currencyCode | `String` | Currency Code |
| 118 | customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| 119 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 120 | debitYN | `String` | Debit YN |
| 121 | deferredYn | `String` | Deferred Y/N |
| 122 | deletedFlag | `String` | Deleted Flag |
| 123 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 124 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 125 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 126 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 127 | depositTransactionId | `String` | Deposit Transaction ID |
| 128 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 129 | displayflag | `String` | Displayflag |
| 130 | dualCurrency | `String` | Cuurency code for parrallel currency. |
| 131 | dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| 132 | dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 133 | dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 134 | dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| 135 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 136 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 137 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 138 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 139 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 140 | exchangeDate | `Date` | Exchange Date |
| 141 | exchangeDifferenceYN | `String` | Exchange Difference YN |
| 142 | exchangeRate | `Float` | Exchange Rate |
| 143 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 144 | expInvoiceType | `String` | Export Invoice Type |
| 145 | expOriginalInvoice | `String` | Export Original Invoice |
| 146 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 147 | extTransactionId | `String` | Transaction ID from external system. |
| 148 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 149 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 150 | financialTransactionCodeType | `String` | Financial Transaction Code Type |
| 151 | fintransactionid | `Float` | Fintransactionid |
| 152 | fintransid | `Float` | Fintransid |
| 153 | fiscalBillNo | `String` | Fiscal Bill Number |
| 154 | fixedChargesYN | `String` | Fixed Charges YN |
| 155 | folioNo | `Float` | Folio Number |
| 156 | folioType | `String` | Folio Type |
| 157 | folioTypeJoin | `String` | Folio Type Join |
| 158 | folioView | `Float` | Folio View |
| 159 | folioid | `Float` | Folioid |
| 160 | foreignCurrencyID | `String` | Foreign Currency ID |
| 161 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 162 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 163 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 164 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 165 | fromReservationId | `Float` | From Resv ID |
| 166 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 167 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 168 | genCashierId | `Float` | General Cashier Id. |
| 169 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 170 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 171 | grossAmount | `Float` | Gross Amount |
| 172 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 173 | guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| 174 | guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| 175 | guestCountry | `String` | Guest Country |
| 176 | guestCountryCode | `String` | Guest Country Code |
| 177 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 178 | inHouseCredit | `Float` | In-House Credit |
| 179 | inHouseDebit | `Float` | In-House Debit |
| 180 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 181 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 182 | insertDate | `DateTime` | Insert Date |
| 183 | insertUser | `Float` | Insert User |
| 184 | insertUserName | `String` | The name of the user who created the record. |
| 185 | installments | `Float` | Installments |
| 186 | internalArticleid | `Float` | Articleid |
| 187 | internalBusinessdate | `Date` | Businessdate |
| 188 | internalCashierid | `Float` | Cashierid |
| 189 | internalWindowId | `Float` | Internal Window ID |
| 190 | internalYN | `String` | Internal YN |
| 191 | invoiceCloseDate | `Date` | Invoice Close Date |
| 192 | invoiceNumber | `Float` | Invoice Number |
| 193 | invoiceType | `String` | Invoice Type |
| 194 | jRNUpdateDate | `Date` | JRN Update Date |
| 195 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 196 | linkTrxNumber | `Float` | Link Transaction No |
| 197 | locationID | `String` | Internal ID to uniquely identify the Property |
| 198 | marketCode | `String` | Market Code |
| 199 | marketDescription | `String` | Market Description |
| 200 | marketDisplaySequence | `Float` | Market Display Sequence |
| 201 | marketGroupCode | `String` | Market Group Code |
| 202 | marketGroupDescription | `String` | Market Group Description |
| 203 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 204 | marketid | `String` | Marketid |
| 205 | membershipID | `Float` | Membership ID |
| 206 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 207 | nameId | `Float` | Name ID |
| 208 | nameTaxType | `String` | Name Tax Type |
| 209 | netAmount | `Float` | Net Amount |
| 210 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 211 | numberDialed | `String` | Number Dialed. |
| 212 | oTransactionDesc | `String` | Transaction Description. |
| 213 | oVOSCurrency | `String` | Currency code for contract currency. |
| 214 | oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 215 | oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 216 | oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 217 | oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 218 | onHoldYN | `String` | On Hold YN |
| 219 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 220 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 221 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 222 | originalBillNumber | `Float` | Stores original bill number after void. |
| 223 | originalFolioNumber | `String` | Stores original folio type after void. |
| 224 | originalReservationNameId | `Float` | Original Resv Name ID |
| 225 | originalRoom | `String` | Original Room |
| 226 | originalresvid | `Float` | Originalresvid |
| 227 | othersBagNumber | `String` | Others Bag Number |
| 228 | package | `String` | Package |
| 229 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 230 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 231 | packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| 232 | packageLedgerDebit | `Float` | Debit amount on the guest package account |
| 233 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 234 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 235 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 236 | parentfintransid | `Float` | Parentfintransid |
| 237 | passerByName | `String` | Passerby Name. |
| 238 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 239 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 240 | paymentType | `String` | Payment Type |
| 241 | paymentsReference | `String` | Payments-Reference |
| 242 | postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| 243 | postedAmountInTransactionCurrency | `Float` | Posted Amount in Transaction Currency |
| 244 | postingDate | `DateTime` | Posting Date |
| 245 | postingRhythm | `String` | Posting Rhythm |
| 246 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 247 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 248 | postitNo | `Float` | Postit Number |
| 249 | postitYn | `String` | Postit Y/N |
| 250 | pricePerUnit | `Float` | Price Per Unit |
| 251 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 252 | processed8300YN | `String` | Processed 8300 YN |
| 253 | productid | `String` | Productid |
| 254 | profileid | `Float` | Profileid |
| 255 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 256 | proformaYn | `String` | Proforma Y/N |
| 257 | property | `String` | Code to uniquely identify the Property |
| 258 | propertyBillPrefix | `String` | Property Bill Prefix |
| 259 | quantity | `Float` | Quantity |
| 260 | queueName | `String` | Queue Name |
| 261 | rateCode | `String` | Rate Code |
| 262 | ratecodeid | `String` | Ratecodeid |
| 263 | receiptNumber | `Float` | Receipt Number |
| 264 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 265 | repTransactionCode | `String` | Reporting Trx Code |
| 266 | repTransactionCodeGroup | `String` | Reporting Tc Group |
| 267 | repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| 268 | repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| 269 | repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| 270 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 271 | reservationid | `Float` | Reservationid |
| 272 | resvenddate | `Date` | Resvenddate |
| 273 | revenueAmount | `Float` | Revenue Amount. |
| 274 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 275 | revisionNo | `Float` | Revision Number |
| 276 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 277 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 278 | roomClass | `String` | Room Class |
| 279 | roomNts | `Float` | Room Nts |
| 280 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 281 | roomNumber | `String` | Room Number |
| 282 | roomid | `String` | Roomid |
| 283 | roundFactorYn | `String` | Round Factor Y/N |
| 284 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 285 | routedYn | `String` | Indicates if the transaction has been routed. |
| 286 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 287 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 288 | serviceChargeIncludedRevenueTaxPercent | `Float` | Service Charge Included Revenue Tax Percent |
| 289 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 290 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 291 | settlementFlag | `String` | Settlement Flag |
| 292 | sourceCode | `String` | Source Code |
| 293 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 294 | sourceDescription | `String` | Source Description |
| 295 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 296 | sourceGroupCode | `String` | Source Group Code |
| 297 | sourceGroupDescription | `String` | Source Group Description |
| 298 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 299 | sourceResort | `String` | Source Resort where the transaction originates for cross posted transaction |
| 300 | sourceid | `String` | Sourceid |
| 301 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 302 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 303 | supplement | `String` | Supplement |
| 304 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 305 | targetResort | `String` | Target Property |
| 306 | targetlocationid | `String` | Targetlocationid |
| 307 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 308 | taxElements | `String` | Tax Elements |
| 309 | taxGeneratedYN | `String` | Tax Generated YN |
| 310 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 311 | taxInvNumber | `String` | Tax Invoice No |
| 312 | taxRate | `Float` | Tax Rate |
| 313 | taxRateType | `String` | Tax Rate Type |
| 314 | tcGroup | `String` | Transaction Code Group |
| 315 | tcSubgroup | `String` | Transaction Code Subgroup |
| 316 | tclCode1 | `String` | Class1 Code. |
| 317 | tclCode2 | `String` | Class1 Code. |
| 318 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 319 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 320 | thresholdEntityType | `String` | Threshold Entity Type |
| 321 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 322 | toReservationNameId | `Float` | To Resv Name ID |
| 323 | tranActionId | `Float` | Tran Action ID |
| 324 | transactionActivityDate | `Date` | Transaction Activity Date |
| 325 | transactionCode | `String` | Transaction Code |
| 326 | transactionCodeDescription | `String` | Transaction Code Description |
| 327 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 328 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 329 | transactionDate | `Date` | Transaction Date |
| 330 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 331 | transactionPostingDate | `Date` | Transaction Posting Date |
| 332 | transactionPostingTime | `String` | Time transaction was posted. |
| 333 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 334 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 335 | transactionStatus | `String` | Transaction Status |
| 336 | transactionType | `String` | Transaction Type |
| 337 | transactionFromAccount | `Float` | Transaction from Account |
| 338 | transactionToAccount | `Float` | Transaction to Account |
| 339 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 340 | transcodearrangementid | `Float` | Transcodearrangementid |
| 341 | transferfromaccountid | `Float` | Transferfromaccountid |
| 342 | transferfromresvid | `Float` | Transferfromresvid |
| 343 | transfertoaccountid | `Float` | Transfertoaccountid |
| 344 | transfertoresvid | `Float` | Transfertoresvid |
| 345 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 346 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 347 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 348 | trxCode | `String` | Transaction Code |
| 349 | trxNo | `Float` | Trx Number |
| 350 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 351 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 352 | trxNumberHeader | `Float` | Transaction No Header |
| 353 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 354 | trxServiceType | `String` | Transaction Service Type |
| 355 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 356 | updateDate | `DateTime` | Update Date |
| 357 | updateUser | `Float` | Update User |
| 358 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 359 | userID | `Float` | User ID |
| 360 | vatAmount | `Float` | Tax Amount for Commission. |
| 361 | vatOffsetYn | `String` | Vat Offset Y/N |
| 362 | vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### ARAgingReportAccountDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | CHAIN_CODE |
| 2 | accountCode | `Float` | Account Code |
| 3 | accountCreditLimitYn | `String` | Indicates if a Credit Limit amount will be required "Y" will take precedence over the credit limit amount on Profile level. |
| 4 | accountName | `String` | Account Name |
| 5 | accountNumber | `String` | Account Number |
| 6 | accountSname | `String` | Name on the account in upper case. |
| 7 | accountStatus | `String` | Status of an account. (Normal Restricted) |
| 8 | accountStatusMsg | `String` | Message prompt when the AR Account is defined as restricted. |
| 9 | accountType | `String` | Account Type |
| 10 | accountTypeFlag | `String` | Account Type Flag |
| 11 | accountTypeId | `Float` | Account Type ID |
| 12 | accountid | `Float` | Accountid |
| 13 | acctflagreasonid | `String` | Acctflagreasonid |
| 14 | activeYN | `String` | Active YN |
| 15 | addressId | `Float` | Address ID |
| 16 | address1 | `String` | Address1 |
| 17 | address2 | `String` | Address2 |
| 18 | address3 | `String` | Address3 |
| 19 | age | `Float` | Age. |
| 20 | agent | `String` | Agent |
| 21 | agentUserId | `Float` | Application User ID of the Account Controller/Agent |
| 22 | agentemployeeid | `Float` | Agentemployeeid |
| 23 | balance | `Float` | Balance on the account. |
| 24 | batchStmtYn | `String` | Include the account in batch statement |
| 25 | beginDate | `Date` | Begin Date |
| 26 | centralAccountType | `String` | Central Account Type |
| 27 | centralBalance | `Float` | Central Balance |
| 28 | centralCreditLimit | `Float` | Central Credit Limit |
| 29 | centralFlaggedReasonCode | `String` | Central Flagged Reason Code |
| 30 | centralState | `String` | Central State |
| 31 | centralXchangeDate | `Date` | Central Exchange Date |
| 32 | centralXchangeRate | `Float` | Central Exchange Rate |
| 33 | city | `String` | City |
| 34 | company | `String` | Company |
| 35 | contact | `String` | Contact information. |
| 36 | country | `String` | Country |
| 37 | countryCode | `String` | Country Code |
| 38 | countryName | `String` | Country Name |
| 39 | creditLimit | `Float` | Credit Limit |
| 40 | creditLimitUpdatedOn | `DateTime` | Date when the Credit Limit was updated. |
| 41 | currencyCode | `String` | Summary Currency Code |
| 42 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 43 | debtorName | `String` | Debtor Name |
| 44 | deletedflag | `String` | Deleted Flag |
| 45 | email | `String` | Email |
| 46 | emailAddr | `String` | Email Addr |
| 47 | emailId | `Float` | Email ID |
| 48 | emailOptInYn | `String` | Indicates if the email address can be used to send Statements and Reminders by default. |
| 49 | endDate | `Date` | End Date |
| 50 | fax | `String` | Fax |
| 51 | faxId | `Float` | Fax ID |
| 52 | faxNumber | `String` | Fax Number |
| 53 | flaggedReasonCode | `String` | The flagged reason code from table AR$_FLAGGED_REASONS. |
| 54 | inactiveDate | `DateTime` | Inactive Date |
| 55 | insertDate | `DateTime` | Insert Date |
| 56 | insertUser | `Float` | Insert User |
| 57 | internalAccounttypeid | `Float` | Accounttypeid |
| 58 | jRNUpdateDate | `Date` | JRN Update Date |
| 59 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 60 | lastActivityDate | `DateTime` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| 61 | lastRemFaxNo | `String` | Fax number to which the last reminder letter was sent. |
| 62 | lastStmtFaxNo | `String` | Fax number to which the last statement was sent. |
| 63 | locationID | `String` | Internal ID to uniquely identify the Property |
| 64 | lstRemPrtDate | `Date` | Date on which the last reminder letter was printed. |
| 65 | lstRemSent | `Date` | Date on which the last reminder letter was sent. |
| 66 | lstRemText | `String` | Name of the reminder letter |
| 67 | lstStmtNoSent | `Float` | Stores the statement number of the last statement sent for a particular AR account. |
| 68 | lstStmtSent | `DateTime` | Date of Last reminderletter sent |
| 69 | monthEndCalcYn | `String` | If Y the Payment due date calculation begins from the last day of the month of invoice generation date if N  then calculation starts from the day of the invoice generation. |
| 70 | nAAddress1 | `String` | NA Address 1 |
| 71 | nAAddress2 | `String` | NA Address 2 |
| 72 | nAAddress3 | `String` | NA Address 3 |
| 73 | naCity | `String` | Na City |
| 74 | naCountryName | `String` | Na Country Name |
| 75 | naState | `String` | Na State |
| 76 | naStateDescription | `String` | Na State Description |
| 77 | nameId | `Float` | Name ID |
| 78 | numberOfPersons | `Float` | No of persons currently using the account |
| 79 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 80 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 81 | permAccountYN | `String` | Status indicator to show the account as a permanent account. User will not be able to delete the account if it is Y |
| 82 | phone | `String` | Phone |
| 83 | phoneId | `Float` | Phone ID |
| 84 | phoneNumber | `String` | Phone Number |
| 85 | postalCode | `String` | Postal Code |
| 86 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 87 | primaryYn | `String` | Primary Y/N |
| 88 | profileid | `Float` | Profileid |
| 89 | property | `String` | Code to uniquely identify the Property |
| 90 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 91 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 92 | repStateDescription | `String` | Reporting State Description |
| 93 | revenuePool | `String` | Revenue Pool |
| 94 | state | `String` | State |
| 95 | stateDescription | `String` | State Description |
| 96 | status | `String` | Status |
| 97 | summaryforeigncurrid | `String` | Summaryforeigncurrid |
| 98 | superSearchIndexText | `String` | Super Search Index Text |
| 99 | supplement | `String` | Supplement |
| 100 | updateDate | `DateTime` | Update Date |
| 101 | updateUser | `Float` | Update User |
| 102 | upperCaseName | `String` | Upper Case Name |
| 103 | zip | `String` | Zip code. |

[⬆ Back to Query](#query)

---

### ARAgingReportCalendarPeriodDayDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | dayKey | `Date` | Day Key |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | endDate | `Date` | End Date |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | locationID | `String` | Internal ID to uniquely identify the Property |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| 11 | parentperiodid | `String` | Parentperiodid |
| 12 | periodCode | `String` | Period Code |
| 13 | periodDescription | `String` | Period Description |
| 14 | periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| 15 | periodType | `String` | Period Type |
| 16 | periodTypeDesc | `String` | Period Type Description |
| 17 | periodsetupid | `Float` | Periodsetupid |
| 18 | periodsetuppmsref | `String` | Periodsetuppmsref |
| 19 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 20 | property | `String` | Code to uniquely identify the Property |
| 21 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 22 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 23 | startDate | `Date` | Start Date |
| 24 | updateDate | `DateTime` | Update Date |
| 25 | updateUser | `Float` | Update User |
| 26 | year | `Float` | Year |
| 27 | yearDescription | `String` | Year Description |
| 28 | yearEndDate | `Date` | Year End Date. |
| 29 | yearId | `Float` | Year ID |
| 30 | yearStartDate | `Date` | Year Start Date. |
| 31 | yearType | `String` | Year Type. |
| 32 | yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### ARAgingReportFinancialPeriodDayDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | dayKey | `Date` | Day Key |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | endDate | `Date` | End Date |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | locationID | `String` | Internal ID to uniquely identify the Property |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| 11 | parentperiodid | `String` | Parentperiodid |
| 12 | periodCode | `String` | Period Code |
| 13 | periodDescription | `String` | Period Description |
| 14 | periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| 15 | periodType | `String` | Period Type |
| 16 | periodTypeDesc | `String` | Period Type Description |
| 17 | periodsetupid | `Float` | Periodsetupid |
| 18 | periodsetuppmsref | `String` | Periodsetuppmsref |
| 19 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 20 | property | `String` | Code to uniquely identify the Property |
| 21 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 22 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 23 | startDate | `Date` | Start Date |
| 24 | updateDate | `DateTime` | Update Date |
| 25 | updateUser | `Float` | Update User |
| 26 | year | `Float` | Year |
| 27 | yearDescription | `String` | Year Description |
| 28 | yearEndDate | `Date` | Year End Date. |
| 29 | yearId | `Float` | Year ID |
| 30 | yearStartDate | `Date` | Year Start Date. |
| 31 | yearType | `String` | Year Type. |
| 32 | yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### ARAgingReportARLedgerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | CHAIN_CODE |
| 2 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 3 | aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 4 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 5 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 6 | accountCode | `Float` | Account Code |
| 7 | accountName | `String` | Account Name |
| 8 | accountNumber | `String` | Account Number |
| 9 | accountTypeFlag | `String` | Account Type Flag |
| 10 | accountid | `Float` | Accountid |
| 11 | advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 12 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 13 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 14 | advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 15 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 16 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 17 | amount | `Float` | Amount |
| 18 | approvalCode | `String` | Approval Code |
| 19 | approvalDate | `Date` | Approval Date |
| 20 | approvalStatus | `String` | Approval Status |
| 21 | arLedgerCredit | `Float` | AR Led Credit |
| 22 | arLedgerDebit | `Float` | AR Led Debit |
| 23 | arNumber | `Float` | AR Number |
| 24 | arState | `String` | AR State |
| 25 | arTransferDate | `Date` | AR Transfer Date |
| 26 | arrangementId | `Float` | Arrangement ID |
| 27 | articleId | `Float` | Article ID |
| 28 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 29 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 30 | authorizerId | `Float` | Authorizer ID |
| 31 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 32 | autoSettleYn | `String` | Auto Settle Y/N |
| 33 | billNo | `Float` | Bill Number |
| 34 | bonusCheckId | `Float` | Bonus Check ID |
| 35 | bucketCode | `String` | Bucket code related to this redemption. |
| 36 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 37 | businessDate | `Date` | Business Date |
| 38 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 39 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 40 | cCashierCredit | `Float` | Central Cashier Credit |
| 41 | cCashierDebit | `Float` | Central Cashier Debit |
| 42 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 43 | cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| 44 | cChangeDue | `Float` | Central Change Due |
| 45 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 46 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 47 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 48 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 49 | cDepLedgerCredit | `Float` | Central Dep Led Credit |
| 50 | cDepLedgerDebit | `Float` | Central Dep Led Debit |
| 51 | cExchangeDate | `Date` | Central Xchange Date |
| 52 | cExchangeRate | `Float` | Central Xchange Rate |
| 53 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 54 | cGrossAmount | `Float` | Central Gross Amount |
| 55 | cGuestAccountCredit | `Float` | Central Guest Account Credit |
| 56 | cGuestAccountDebit | `Float` | Central Guest Account Debit |
| 57 | cInHouseCredit | `Float` | Central Inh Credit |
| 58 | cInHouseDebit | `Float` | Central Inh Debit |
| 59 | cNetAmount | `Float` | Central Net Amount |
| 60 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 61 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 62 | cPackageAllowance | `Float` | Central Package Allowance |
| 63 | cPackageCredit | `Float` | Central Package Credit |
| 64 | cPackageDebit | `Float` | Central Package Debit |
| 65 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 66 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 67 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 68 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 69 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 70 | cPostedAmount | `Float` | Central Posted Amount |
| 71 | cPricePerUnit | `Float` | Central Price Per Unit |
| 72 | cRevenueAmount | `Float` | Central Revenue Amt |
| 73 | cTaxRate | `Float` | Central Tax Rate |
| 74 | cTransactionAmount | `Float` | Central Trx Amount |
| 75 | calcPointsYn | `String` | Indicates if points are to be calculated. |
| 76 | cashierCredit | `Float` | Cashier Credit |
| 77 | cashierDebit | `Float` | Cashier Debit |
| 78 | cashierId | `Float` | Cashier ID |
| 79 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 80 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 81 | ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 82 | centralARLedgerAmount | `Float` | Central AR Ledger Amount |
| 83 | changeDue | `Float` | Change Due |
| 84 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 85 | chequeNumber | `String` | Cheque Number |
| 86 | closureNo | `Float` | Closure Number |
| 87 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 88 | comments | `String` | Comments |
| 89 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 90 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 91 | compTypeCode | `String` | Comp Type Code |
| 92 | compressedYn | `String` | Compressed Y/N |
| 93 | contractCurrency | `String` | Currency code for contract currency. |
| 94 | contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 95 | contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 96 | contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 97 | contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 98 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 99 | couponNo | `String` | Coupon Number |
| 100 | covers | `String` | Covers |
| 101 | currencyCode | `String` | Currency Code |
| 102 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 103 | deferredTaxesYn | `String` | Indicates whether the generated tax is because of a deferred tax generation scenario |
| 104 | deferredYn | `String` | Deferred Y/N |
| 105 | deletedFlag | `String` | Deleted Flag |
| 106 | depLedgerCredit | `Float` | Dep Ledger Credit |
| 107 | depLedgerDebit | `Float` | Dep Ledger Debit |
| 108 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 109 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 110 | depositTransactionId | `String` | Deposit Transaction ID |
| 111 | displayYn | `String` | Display Y/N |
| 112 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 113 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 114 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 115 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 116 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 117 | exchangeDate | `Date` | Exchange Date |
| 118 | exchangeDifferenceYn | `String` | The flag indicates if it is an exchange rate difference posting when dual currency is on. |
| 119 | exchangeRate | `Float` | Exchange Rate |
| 120 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 121 | expInvoiceType | `String` | Export Invoice Type |
| 122 | expOriginalInvoice | `String` | Export Original Invoice |
| 123 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 124 | extTransactionId | `String` | Transaction ID from external system. |
| 125 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 126 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 127 | financialTransactionSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 128 | fintransid | `Float` | Fintransid |
| 129 | fiscalBillNo | `String` | Fiscal Bill Number |
| 130 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 131 | fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| 132 | folioNo | `Float` | Folio Number |
| 133 | folioType | `String` | Folio Type |
| 134 | folioView | `Float` | Folio View |
| 135 | folioid | `Float` | Folioid |
| 136 | foreignCurrencyID | `String` | Foreign Currency ID |
| 137 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 138 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 139 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 140 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 141 | fromReservationId | `Float` | From Resv ID |
| 142 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 143 | genCashierId | `Float` | General Cashier Id. |
| 144 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 145 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 146 | grossAmount | `Float` | Gross Amount |
| 147 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 148 | guestAccountCredit | `Float` | Guest Account Credit |
| 149 | guestAccountDebit | `Float` | Debit amount on the guest account |
| 150 | holdYn | `String` | Indicates transaction is on hold. |
| 151 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 152 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 153 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 154 | inhCredit | `Float` | In House Credit |
| 155 | inhDebit | `Float` | In House Debit |
| 156 | insertDate | `DateTime` | Insert Date |
| 157 | insertUser | `Float` | Insert User |
| 158 | installments | `Float` | Installments |
| 159 | internalCashierid | `Float` | Cashierid |
| 160 | invoiceCloseDate | `Date` | Invoice Close Date |
| 161 | invoiceNo | `Float` | Invoice Number |
| 162 | invoiceType | `String` | Invoice Type |
| 163 | jRNUpdateDate | `Date` | JRN Update Date |
| 164 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 165 | linkTrxNumber | `Float` | Link Transaction No |
| 166 | locationID | `String` | Internal ID to uniquely identify the Property |
| 167 | marketCode | `String` | Market Code |
| 168 | membershipId | `Float` | Membership ID |
| 169 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 170 | nameId | `Float` | Name ID |
| 171 | nameTaxType | `String` | Name Tax Type |
| 172 | netAmount | `Float` | Net Amount |
| 173 | numberDialed | `String` | Number Dialed. |
| 174 | oTransactionDesc | `String` | Transaction Description. |
| 175 | orgBillNumber | `Float` | Stores original bill number after void. |
| 176 | orgFolioType | `String` | Stores original folio type after void. |
| 177 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 178 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 179 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 180 | originalReservationNameId | `Float` | Original Resv Name ID |
| 181 | originalRoom | `String` | Original Room |
| 182 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 183 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 184 | packageCredit | `Float` | Credit amount on the guest package account. |
| 185 | packageDebit | `Float` | Debit amount on the guest package account |
| 186 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 187 | parallelCurrency | `String` | Cuurency code for parrallel currency. |
| 188 | parallelGrossAmount | `Float` | Parallel Gross Amount |
| 189 | parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 190 | parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 191 | parallelNetAmount | `Float` | Parallel Net Amount |
| 192 | passerByName | `String` | Passerby Name. |
| 193 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 194 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 195 | paymentType | `String` | Payment Type |
| 196 | postedAmount | `Float` | Posted Amount |
| 197 | postingDate | `Date` | Posting Date |
| 198 | postingRhythm | `String` | Posting Rhythm |
| 199 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 200 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 201 | postitNo | `Float` | Postit Number |
| 202 | postitYn | `String` | Postit Y/N |
| 203 | pricePerUnit | `Float` | Price Per Unit |
| 204 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 205 | processed8300Yn | `String` | Indicates whether this particular transaction has been included in an 8300 tax form yet. |
| 206 | product | `String` | Product |
| 207 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 208 | proformaYn | `String` | Proforma Y/N |
| 209 | property | `String` | Code to uniquely identify the Property |
| 210 | propertyBillPrefix | `String` | Property Bill Prefix |
| 211 | quantity | `Float` | Quantity |
| 212 | queueName | `String` | Queue Name |
| 213 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 214 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 215 | rateCode | `String` | Rate Code |
| 216 | reasonCode | `String` | Reason Code |
| 217 | receiptNo | `Float` | Recpt Number |
| 218 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 219 | reference | `String` | Reference |
| 220 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 221 | reservationNameId | `Float` | Resv Name ID |
| 222 | reservationid | `Float` | Reservationid |
| 223 | revenueAmt | `Float` | Revenue Amount. |
| 224 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 225 | revisionNo | `Float` | Revision Number |
| 226 | room | `String` | Room |
| 227 | roomClass | `String` | Room Class |
| 228 | roomNts | `Float` | Room Nts |
| 229 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 230 | roundFactorYn | `String` | Round Factor Y/N |
| 231 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 232 | routedYn | `String` | Indicates if the transaction has been routed. |
| 233 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 234 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 235 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 236 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 237 | settlementFlag | `String` | Settlement Flag |
| 238 | sourceCode | `String` | Source Code |
| 239 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 240 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 241 | supplement | `String` | Supplement |
| 242 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 243 | taCommissionableYn | `String` | The value 'Y' indicates that the commission has been paid for the transaction. |
| 244 | targetResort | `String` | Target Property |
| 245 | taxElements | `String` | Tax Elements |
| 246 | taxGeneratedYn | `String` | Indicates whether tax has been generated for a particuar posting. |
| 247 | taxInclusiveYn | `String` | Tax Inclusive Y/N |
| 248 | taxInvNumber | `String` | Tax Invoice No |
| 249 | taxRate | `Float` | Tax Rate |
| 250 | taxRateType | `String` | Tax Rate Type |
| 251 | tcGroup | `String` | Transaction Code Group |
| 252 | tcSubgroup | `String` | Transaction Code Subgroup |
| 253 | tclCode1 | `String` | Class1 Code. |
| 254 | tclCode2 | `String` | Class1 Code. |
| 255 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 256 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 257 | thresholdEntityType | `String` | Threshold Entity Type |
| 258 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 259 | toReservationNameId | `Float` | To Resv Name ID |
| 260 | tranActionId | `Float` | Tran Action ID |
| 261 | transactionDate | `Date` | Transaction Date |
| 262 | transactionFromAcct | `Float` | Trns From Account |
| 263 | transactionNumber | `Float` | Transaction Number |
| 264 | transactionToAcct | `Float` | Trns To Account |
| 265 | transcodearrangementid | `Float` | Transcodearrangementid |
| 266 | transcodeid | `String` | Transcodeid |
| 267 | trnsActivityDate | `Date` | Transaction Activity Date |
| 268 | trxAmount | `Float` | Transaction Amount |
| 269 | trxCode | `String` | Transaction Code |
| 270 | trxNumberAddedBy | `Float` | Transaction No Added By |
| 271 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 272 | trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| 273 | trxNumberHeader | `Float` | Transaction No Header |
| 274 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 275 | trxServiceType | `String` | Transaction Service Type |
| 276 | updateDate | `DateTime` | Update Date |
| 277 | updateUser | `Float` | Update User |
| 278 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 279 | vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAgingReportInvoiceHeaderDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRDebit | `Float` | AR Debit |
| 2 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 3 | aRTransferDate | `Date` | AR Transfer Date |
| 4 | accountCode | `Float` | Account Code |
| 5 | accountTypeFlag | `String` | Account Type Flag |
| 6 | accountid | `Float` | Accountid |
| 7 | addresseeNameId | `Float` | Addressee Name ID |
| 8 | adjustmentYn | `String` | Adjustment Y/N |
| 9 | adjustmentflag | `String` | Adjustmentflag |
| 10 | agingBucket | `Float` | Aging bucket number. |
| 11 | agingBusinessDate | `Date` | Aging Business Date |
| 12 | amount | `Float` | Amount |
| 13 | billNumber | `Float` | Bill Number |
| 14 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 15 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 16 | cAmount | `Float` | Central Amount |
| 17 | cContractCurrencyDifference | `Float` | Central Contract Curr Diff |
| 18 | cExchangeDate | `Date` | Central Xchange Date |
| 19 | cExchangeRate | `Float` | Central Xchange Rate |
| 20 | cOrganizationAmount | `Float` | Central Org Amt |
| 21 | cOrganizationAmountContract | `Float` | Central Org Amt Contract |
| 22 | cOrganizationAmountCurrencyDifference | `Float` | Central Org Amt Curr Diff |
| 23 | cOrganizationAmountParallel | `Float` | Central Org Amt Parallel |
| 24 | cPaid | `Float` | Central Paid |
| 25 | cParallelCurrencyDifference | `Float` | Central Parallel Curr Diff |
| 26 | cashierId | `Float` | Cashier ID |
| 27 | centralProfileID | `String` | Central Profile ID |
| 28 | checkOutDate | `Date` | Date on which the guest was checked out. |
| 29 | compressDate | `Date` | Date of Compression. |
| 30 | compressedYn | `String` | Compressed Y/N |
| 31 | contractCurrDifference | `Float` | Currency difference for contract amount. Used for Dual Currency functionality. |
| 32 | contractCurrencyCode | `String` | Currency Code of the contract currency. Used for Dual Currency functionality. |
| 33 | creditedToTrxNumber | `Float` | Stores the transaction number for which this credit bill is created. |
| 34 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 35 | dateForAging | `String` | Date the aging should begin |
| 36 | deletedFlag | `String` | Deleted Flag |
| 37 | expInvoiceType | `String` | Export Invoice Type |
| 38 | expOriginalInvoice | `String` | Export Original Invoice |
| 39 | externalReceiptDate | `Date` | Receipt Date sent from external systems. |
| 40 | fintransid | `Float` | Fintransid |
| 41 | fiscalBillNo | `String` | Fiscal Bill Number |
| 42 | folioNo | `Float` | Folio Number |
| 43 | folioText1 | `String` | Folio Text 1 |
| 44 | folioText2 | `String` | Folio Text 2 |
| 45 | folioType | `String` | Folio Type |
| 46 | folioid | `Float` | Folioid |
| 47 | insertDate | `DateTime` | Insert Date |
| 48 | insertUser | `String` | Insert User |
| 49 | invoiceAge | `Float` | Invoice Age |
| 50 | invoiceCloseDate | `Date` | Invoice Close Date |
| 51 | invoiceClosedBy | `String` | Application User who closed the invoice. |
| 52 | invoiceNumber | `Float` | Invoice Number |
| 53 | invoiceStatus | `String` | Status of the invoice (H)old (O)pen or (C)losed. |
| 54 | invoiceType | `String` | Invoice Type |
| 55 | invoiceid | `Float` | Invoiceid |
| 56 | invoiceprofileid | `Float` | Invoiceprofileid |
| 57 | jRNUpdateDate | `Date` | JRN Update Date |
| 58 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 59 | locationID | `String` | Internal ID to uniquely identify the Property |
| 60 | masterInvoiceNumber | `Float` | Compressed Invoice No for which multiple invoices have been compressed to. |
| 61 | name | `String` | Name |
| 62 | nameId | `Float` | Name ID |
| 63 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 64 | originalAmount | `Float` | Original Amount |
| 65 | originalAmountContractCurrency | `Float` | Original Amount in contract currency. Used for Dual Currency functionality. |
| 66 | originalAmountCurrencyDifference | `Float` | Currency difference for the original amount in local currency.  Used for Dual Currency functionality. |
| 67 | originalAmountDualCurrency | `Float` | Original Amount in parallel currency. Used for Dual Currency functionality. |
| 68 | ownerRoom | `String` | The owner room where this invoice/payment belongs to. |
| 69 | ownerroomid | `String` | Ownerroomid |
| 70 | paid | `Float` | Amount paid. |
| 71 | parallelCurrDifference | `Float` | Currency difference for parallel amount. Used for Dual Currency functionality. |
| 72 | parallelCurrencyCode | `String` | Currency Code of the parallel currency. Used for Dual Currency functionality. |
| 73 | paymentNo | `String` | Payment Number used for chain specific functionality. |
| 74 | postDate | `Date` | Post Date |
| 75 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 76 | printedDate | `Date` | Printed Date |
| 77 | printedYn | `String` | Printed Y/N |
| 78 | profileID | `String` | Profile ID |
| 79 | property | `String` | Code to uniquely identify the Property |
| 80 | purgeYn | `String` | Indicator whether to purge the Account. |
| 81 | reference | `String` | Reference |
| 82 | remark | `String` | Remark |
| 83 | reminderCycle | `Float` | Reminder Cycle that was generated for this invoice |
| 84 | reminderDate | `Date` | Date of the reminder letter that was sent |
| 85 | reservationNameId | `Float` | Resv Name ID |
| 86 | reservationid | `Float` | Reservationid |
| 87 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 88 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 89 | room | `String` | Room |
| 90 | roomid | `String` | Roomid |
| 91 | statementNumber | `Float` | Statement Number |
| 92 | tranActionId | `Float` | Tran Action ID |
| 93 | transactionActivityDate | `DateTime` | Transaction Activity Date |
| 94 | transactionDate | `Date` | Transaction Date |
| 95 | transactionFromAcct | `Float` | Trns From Account |
| 96 | transactionToAcct | `Float` | Trns To Account |
| 97 | transcodeid | `String` | Transcodeid |
| 98 | transferfromaccountid | `Float` | Transferfromaccountid |
| 99 | transfertoaccountid | `Float` | Transfertoaccountid |
| 100 | trxCode | `String` | Transaction Code |
| 101 | trxNumber | `Float` | Transaction No |
| 102 | updateDate | `DateTime` | Update Date |
| 103 | updateUser | `String` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportPropertyPropertyDetailsType

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

### ARAgingReportQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| aragingreportdetailsChainCode | `StringInput` | CHAIN_CODE<br>`@conditionalInputPair(pair: 1)` |
| aragingreportDetailsAccountCode | `FloatInput` | Account Code<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsArTransferDate | `DateInput` | AR Transfer Date<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsBusinessDate | `DateInput` | Business Date<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsFolioNo | `FloatInput` | Folio Number<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsInvoiceNo | `FloatInput` | Invoice Number<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsInvoiceStatus | `StringInput` | Invoice Status<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsResort | `StringInput` | Code to uniquely identify the Property<br>`@conditionalInputPair(pair: 1)` |
| aragingreportDetailsResvNameId | `FloatInput` | Resv Name ID<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsTrxDate | `DateInput` | Transaction Date<br>`@conditionalInputPair(pair: 2)` |
| aragingreportDetailsTrxNo | `FloatInput` | Transaction No<br>`@conditionalInputPair(pair: 2)` |
| transactioncodedetailsChainCode | `StringInput` | CHAIN_CODE |
| transcodeDetailsArNameId | `FloatInput` | Ar Name ID |
| transcodeDetailsAdjTrxCode | `StringInput` | Adj Trx Code |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsTcGroup | `StringInput` | Group |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput` | Property |
| transcodeDetailsTrxActionId | `FloatInput` | Trx Action ID |
| transcodeDetailsTcSubgroup | `StringInput` | Transaction Code Sub-group |
| transcodeDetailsTrxCodeType | `StringInput` | Transaction Code Type |
| transcodeDetailsTranscodeid | `StringInput` | Transcodeid |
| transcodeDetailsTrxCode | `StringInput` | Trx Code |
| folioDetailsBillGenerationDate | `DateInput` | Bill Generation Date |
| folioDetailsBillNo | `FloatInput` | Bill Number |
| folioDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| folioDetailsFolioNo | `FloatInput` | Folio Number |
| folioDetailsFolioSeqNo | `FloatInput` | Unique number to identify the entry. |
| folioDetailsFltType | `StringInput` | Identify the FOLIO TYPE. |
| folioDetailsFolioView | `FloatInput` | Folio View |
| folioDetailsFoDate | `DateInput` | Date when folio is created |
| folioDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| folioDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| folioDetailsNameId | `FloatInput` | Name ID |
| folioDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| folioDetailsPostitNo | `FloatInput` | Postit Number |
| folioDetailsResort | `StringInput` | Code to uniquely identify the Property |
| folioDetailsResvNameId | `FloatInput` | Resv Name ID |
| folioDetailsTimestamp | `DateInput` | Date on which the folio is created or date of the checkout. |
| financialtransDetailsArLedCredit | `FloatInput` | AR Ledger Credit |
| financialtransDetailsArLedDebit | `FloatInput` | AR Ledger Debit |
| financialtransDetailsArState | `StringInput` | AR State |
| financialtransDetailsArNumber | `FloatInput` | Account Code |
| financialtransDetailsAccountid | `FloatInput` | Accountid |
| financialtransDetailsArticleId | `FloatInput` | Article ID |
| financialtransDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| financialtransDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| financialtransDetailsBusinessDate | `DateInput` | Business Date |
| financialtransDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| financialtransDetailsCXchangeRate | `FloatInput` | Central Xchange Rate |
| financialtransDetailsCashierId | `FloatInput` | Cashier ID |
| financialtransDetailsChainCode | `StringInput` | Chain Code |
| financialtransDetailsChequeNumber | `StringInput` | Check Number |
| financialtransDetailsClosureNo | `FloatInput` | Closure Number |
| financialtransDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialtransDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| financialtransDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtransDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| financialtransDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialtransDetailsFintransactionid | `FloatInput` | Fintransactionid |
| financialtransDetailsFintransid | `FloatInput` | Fintransid |
| financialtransDetailsBillNo | `FloatInput` | Folio Number |
| financialtransDetailsFolioView | `FloatInput` | Folio View |
| financialtransDetailsFolioid | `FloatInput` | Folioid |
| financialtransDetailsFromResvId | `FloatInput` | From Resv ID |
| financialtransDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtransDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialtransDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialtransDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| financialtransDetailsInsertDate | `DateTimeInput` | Insert Date |
| financialtransDetailsArticleid | `FloatInput` | Articleid |
| financialtransDetailsBusinessdate | `DateInput` | Businessdate |
| financialtransDetailsCashierid | `FloatInput` | Cashierid |
| financialtransDetailsFolioNo | `FloatInput` | Internal Window ID |
| financialtransDetailsInvoiceNo | `FloatInput` | Invoice Number |
| financialtransDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialtransDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| financialtransDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialtransDetailsNameId | `FloatInput` | Name ID |
| financialtransDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtransDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialtransDetailsOriginalRoom | `StringInput` | Original Room |
| financialtransDetailsOriginalresvid | `FloatInput` | Originalresvid |
| financialtransDetailsProduct | `StringInput` | Package |
| financialtransDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtransDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtransDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| financialtransDetailsParentfintransid | `FloatInput` | Parentfintransid |
| financialtransDetailsPostitNo | `FloatInput` | Postit Number |
| financialtransDetailsProductid | `StringInput` | Productid |
| financialtransDetailsProfileid | `FloatInput` | Profileid |
| financialtransDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialtransDetailsRateCode | `StringInput` | Rate Code |
| financialtransDetailsRatecodeid | `StringInput` | Ratecodeid |
| financialtransDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtransDetailsReservationid | `FloatInput` | Reservationid |
| financialtransDetailsRoom | `StringInput` | Room Number |
| financialtransDetailsRoomid | `StringInput` | Roomid |
| financialtransDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialtransDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialtransDetailsTaxElements | `StringInput` | Tax Elements |
| financialtransDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtransDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtransDetailsTranActionId | `FloatInput` | Tran Action ID |
| financialtransDetailsTranscodeid | `StringInput` | Transaction Code |
| financialtransDetailsTrxDate | `DateInput` | Transaction Date |
| financialtransDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialtransDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID |
| financialtransDetailsTrxCode | `StringInput` | Transaction Code |
| financialtransDetailsTrxNo | `FloatInput` | Trx Number |
| financialtransDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialtransDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialtransDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| financialtransDetailsAuthorizerId | `FloatInput` | User ID |
| accountdetailsChainCode | `StringInput` | CHAIN_CODE |
| accountDetailsAccountCode | `FloatInput` | Account Code |
| accountDetailsAccountNo | `StringInput` | Account Number |
| accountDetailsAccountSname | `StringInput` | Name on the account in upper case. |
| accountDetailsAccTypeFlag | `StringInput` | Account Type Flag |
| accountDetailsAccountTypeId | `FloatInput` | Account Type ID |
| accountDetailsAccountid | `FloatInput` | Accountid |
| accountDetailsAddressId | `FloatInput` | Address ID |
| accountDetailsBeginDate | `DateInput` | Begin Date |
| accountDetailsCXchangeDate | `DateInput` | Central Exchange Date |
| accountDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accountDetailsEmailId | `FloatInput` | Email ID |
| accountDetailsEndDate | `DateInput` | End Date |
| accountDetailsFaxId | `FloatInput` | Fax ID |
| accountDetailsAccounttypeid | `FloatInput` | Accounttypeid |
| accountDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| accountDetailsLastActivityDate | `DateTimeInput` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| accountDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| accountDetailsNameId | `FloatInput` | Name ID |
| accountDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accountDetailsPhoneId | `FloatInput` | Phone ID |
| accountDetailsProfileid | `FloatInput` | Profileid |
| accountDetailsResort | `StringInput` | Code to uniquely identify the Property |
| accountDetailsUpperCaseName | `StringInput` | Upper Case Name |
| calendarperioddayDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| calendarperioddayDetailsEndDate | `DateInput` | End Date |
| calendarperioddayDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| calendarperioddayDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| calendarperioddayDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| calendarperioddayDetailsCode | `StringInput` | Period Code |
| calendarperioddayDetailsPeriodScope | `StringInput` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| calendarperioddayDetailsPeriodTypeDesc | `StringInput` | Period Type Description |
| calendarperioddayDetailsResort | `StringInput` | Code to uniquely identify the Property |
| calendarperioddayDetailsStartDate | `DateInput` | Start Date |
| calendarperioddayDetailsYearId | `FloatInput` | Year ID |
| calendarperioddayDetailsYearsetupid | `FloatInput` | Yearsetupid |
| financialperioddayDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialperioddayDetailsEndDate | `DateInput` | End Date |
| financialperioddayDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialperioddayDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialperioddayDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialperioddayDetailsCode | `StringInput` | Period Code |
| financialperioddayDetailsPeriodScope | `StringInput` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| financialperioddayDetailsPeriodType | `StringInput` | Period Type |
| financialperioddayDetailsPeriodsetupid | `FloatInput` | Periodsetupid |
| financialperioddayDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialperioddayDetailsStartDate | `DateInput` | Start Date |
| financialperioddayDetailsYearId | `FloatInput` | Year ID |
| arledgerdetailsChainCode | `StringInput` | CHAIN_CODE |
| arledgerDetailsAccountid | `FloatInput` | Accountid |
| arledgerDetailsArLedCredit | `FloatInput` | AR Led Credit |
| arledgerDetailsArLedDebit | `FloatInput` | AR Led Debit |
| arledgerDetailsArNumber | `FloatInput` | AR Number |
| arledgerDetailsArState | `StringInput` | AR State |
| arledgerDetailsArticleId | `FloatInput` | Article ID |
| arledgerDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| arledgerDetailsBillNo | `FloatInput` | Bill Number |
| arledgerDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| arledgerDetailsBusinessDate | `DateInput` | Business Date |
| arledgerDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| arledgerDetailsCashierId | `FloatInput` | Cashier ID |
| arledgerDetailsChequeNumber | `StringInput` | Cheque Number |
| arledgerDetailsClosureNo | `FloatInput` | Closure Number |
| arledgerDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| arledgerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| arledgerDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| arledgerDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| arledgerDetailsFintransid | `FloatInput` | Fintransid |
| arledgerDetailsFolioNo | `FloatInput` | Folio Number |
| arledgerDetailsFolioView | `FloatInput` | Folio View |
| arledgerDetailsFromResvId | `FloatInput` | From Resv ID |
| arledgerDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |
| arledgerDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| arledgerDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| arledgerDetailsInsertDate | `DateTimeInput` | Insert Date |
| arledgerDetailsCashierid | `FloatInput` | Cashierid |
| arledgerDetailsInvoiceCloseDate | `DateInput` | Invoice Close Date |
| arledgerDetailsInvoiceNo | `FloatInput` | Invoice Number |
| arledgerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| arledgerDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| arledgerDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| arledgerDetailsNameId | `FloatInput` | Name ID |
| arledgerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| arledgerDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| arledgerDetailsOriginalRoom | `StringInput` | Original Room |
| arledgerDetailsPostitNo | `FloatInput` | Postit Number |
| arledgerDetailsProduct | `StringInput` | Product |
| arledgerDetailsResort | `StringInput` | Code to uniquely identify the Property |
| arledgerDetailsRateCode | `StringInput` | Rate Code |
| arledgerDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| arledgerDetailsResvNameId | `FloatInput` | Resv Name ID |
| arledgerDetailsRoom | `StringInput` | Room |
| arledgerDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| arledgerDetailsTaxElements | `StringInput` | Tax Elements |
| arledgerDetailsTcGroup | `StringInput` | Transaction Code Group |
| arledgerDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| arledgerDetailsTranActionId | `FloatInput` | Tran Action ID |
| arledgerDetailsTrxDate | `DateInput` | Transaction Date |
| arledgerDetailsTrxNo | `FloatInput` | Transaction Number |
| arledgerDetailsTrxCode | `StringInput` | Transaction Code |
| arledgerDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |
| arledgerDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| arledgerDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |
| arledgerDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| invoiceheaderDetailsArTransferDate | `DateInput` | AR Transfer Date |
| invoiceheaderDetailsAccountCode | `FloatInput` | Account Code |
| invoiceheaderDetailsAccountid | `FloatInput` | Accountid |
| invoiceheaderDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| invoiceheaderDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| invoiceheaderDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| invoiceheaderDetailsFintransid | `FloatInput` | Fintransid |
| invoiceheaderDetailsFolioNo | `FloatInput` | Folio Number |
| invoiceheaderDetailsFolioid | `FloatInput` | Folioid |
| invoiceheaderDetailsInvoiceNo | `FloatInput` | Invoice Number |
| invoiceheaderDetailsInvStatus | `StringInput` | Status of the invoice (H)old (O)pen or (C)losed. |
| invoiceheaderDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| invoiceheaderDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| invoiceheaderDetailsMasterInvoiceNo | `FloatInput` | Compressed Invoice No for which multiple invoices have been compressed to. |
| invoiceheaderDetailsNameId | `FloatInput` | Name ID |
| invoiceheaderDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| invoiceheaderDetailsBusinessDate | `DateInput` | Post Date |
| invoiceheaderDetailsResort | `StringInput` | Code to uniquely identify the Property |
| invoiceheaderDetailsPurgeYn | `StringInput` | Indicator whether to purge the Account. |
| invoiceheaderDetailsResvNameId | `FloatInput` | Resv Name ID |
| invoiceheaderDetailsTrxDate | `DateInput` | Transaction Date |
| invoiceheaderDetailsTranscodeid | `StringInput` | Transcodeid |
| invoiceheaderDetailsTrxCode | `StringInput` | Transaction Code |
| invoiceheaderDetailsTrxNo | `FloatInput` | Transaction No |
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

**`conditionalInputPair(pair: 1)`**
- aragingreportdetailsChainCode
- aragingreportDetailsResort

**`conditionalInputPair(pair: 2)`**
- aragingreportDetailsAccountCode
- aragingreportDetailsArTransferDate
- aragingreportDetailsBusinessDate
- aragingreportDetailsFolioNo
- aragingreportDetailsInvoiceNo
- aragingreportDetailsInvoiceStatus
- aragingreportDetailsJrnupdatedttm
- aragingreportDetailsResvNameId
- aragingreportDetailsTrxDate
- aragingreportDetailsTrxNo


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query aRAgingReport($input: ARAgingReportQueryArgumentsType!) {
  aRAgingReport(input: $input) @stream {
    aRAgingReportDetails {
      chainCode
      aRLedgerDebit
      accountCode
      accountName
      accountNumber
      accountType
      accountid
      age1
      age2
      age3
      age4
      age5
      age6
      agingbucket
      arTransferDate
      billNumber
      billingContactName
      businessDate
      cARLedgerCredit
      cARLedgerDebit
      cAmount
      cContractCurrencyDifference
      cExchangeDate
      cExchangeRate
      cOrganizationAmount
      cOrganizationAmountContract
      cOrganizationAmountCurrencyDifference
      cOrganizationAmountParallel
      cParallelCurrencyDifference
      centralAccountType
      centralOpenARTransactionAmount
      checkOutDate
      dSI
      dateForAging
      fintransid
      folioNo
      folioid
      internalCheckoutDate
      invoiceAge
      invoiceCloseDate
      invoiceNo
      invoiceNumber
      invoiceStatus
      invoiceamount
      invoiceid
      invoiceprofileid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      masterInvoiceNo
      nameId
      openARTransactionAmount
      organizationID
      ownerRoom
      ownerroomid
      pmsBusinessDate
      postDate
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationid
      room
      roomid
      transactionFromAcct
      transactionToAcct
      transactionid
      transcodeid
      transferfromaccountid
      transfertoaccountid
      trxCode
      trxDate
      trxNumber
    }
    transactionCodeDetails {
      chainCode
      aRLedgerPaymentsYN
      aRNameId
      accountNumber
      accountingCode
      acctrecvprofileid
      adjTrxCode
      adjtranscodeid
      arrangeCode
      arrangementCode
      cDefaultPrice
      cExchangeDate
      cExchangeRate
      cExportBucket
      cMaxAmount
      cMinimumAmount
      cCCode
      cRSTaxDesc
      cashTransactionCodeYN
      ccType
      centalSubgroup
      centralAdjustmentTransactionCode
      centralTransactionCode
      centralTransactionCodeGroup
      chargeDeferredUntilCheckoutYN
      checkNumberMandatoryYN
      class1MandatoryYn
      class2MandatoryYn
      commissionCode
      compNightsYn
      compPaymentYn
      complimentaryYN
      corpPropFlag
      corporateDescription
      crossPostingDepositYN
      crossPostingPaymentYN
      crossPostingSalesYN
      currencyCode
      dSI
      dailyPlanFolio
      dedOwnerRevenueYN
      defaultPrice
      deletedFlag
      depositLedgerPaymentsYN
      depositPostingOnlyYn
      depositType
      eInvoiceYn
      expenseFolio
      exportBucket
      externalPaymentCode
      fiscalPaymentYn
      fiscalTrxCodeType
      foreignCurrencyID
      gDeletedFlag
      gDescription
      gInsertDate
      gInsertUser
      gOrderBy
      gRepDescription
      gResultIncludedInSumArray
      gRevenuegroupflag
      gTctClassType1
      gTctClassType2
      gUpdateDate
      gUpdateUser
      group
      groupClass1MandatoryYN
      groupClass2MandatoryYN
      groupFolio
      groupIndRevenueGroup
      groupInternalYN
      groupPointsRedemptionYN
      groupRepItem
      groupRepItemName
      groupRepItemOrderby
      groupRepOrderBy
      groupRepUpdateDate
      groupTcTransactionType
      guestLedgerPaymentsYN
      inactiveDate
      inactiveflag
      includeIn8300Yn
      includeInDepositRuleYn
      insertDate
      insertUser
      internalDeletedflag
      internalTransactionCodeSubGroup
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualPostCoversYn
      manualPostingAllowedYN
      maximumAmount
      membershipYN
      minimumAmount
      nonTaxableYn
      organizationID
      ownerRevenueYN
      paymentTaxInvoiceYn
      paymentType
      paymentmethodid
      primaryKeyID
      printReceiptYN
      processingType
      property
      quantityCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      resultIncludedInSumArray
      revenueBucketId
      revenueGroupId
      revenueYN
      rnaInsertDate
      rnaUpdateDate
      rotationRevenueYN
      roundFactorYn
      serviceRecoveryTrxCode
      sgDeletedFlag
      sgDescription
      sgInsertDate
      sgInsertUser
      sgOrderBy
      sgResultIncludedInSumArray
      sgRevenuegroupflag
      sgTaxflag
      sgUpdateDate
      sgUpdateUser
      subGroupClass1MandatoryYN
      subGroupClass2MandatoryYN
      subGroupFrequentFlyerYN
      subGroupGroupPointsRedemptionYN
      subGroupIndRevenueGroup
      subGroupInternalYN
      subGroupRepDescription
      subGroupRepOrderBy
      subGroupTcGroupAndSubgroup
      subGroupTcTransactionType
      subGroupType
      taxCodeNumber
      taxInclusiveYN
      taxYN
      tcBofInterface
      tcBofInterface2
      tcBofRefCode
      tcBofRefCode2
      tcResort2
      tcTransactionType
      tclCodeDfltCl1
      tclCodeDfltCl2
      transactionActionId
      transactionCodeDescription
      transactionCodeGroup
      transactionCodeResort
      transactionCodeSubGroup
      transactionCodeType
      transactionType
      transcodearrangementid
      transcodeid
      trxCode
      trxCodeDisplay
      trxServiceType
      trxTaxTypeCode
      uPC
      updateDate
      updateUser
    }
    folioDetails {
      billGenerationDate
      billNumber
      businessdate
      cashierId
      checkExchangeReceiptNumber
      currencyExchangeReceiptNumber
      dSI
      deletedFlag
      folioNo
      folioSeqNumber
      folioStatus
      folioStyle
      folioType
      folioView
      folioid
      frontOfficeDate
      fullFolioNo
      insertDate
      insertUser
      internalUpdatedate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      name
      nameId
      numberReprints
      numberOfPersons
      organizationID
      phoneDetails
      postitNo
      postityn
      primaryKeyID
      processIdent
      profileid
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationid
      resvdeptrno
      resvenddate
      revisionNumber
      state
      templatePath
      timestamp
      updateDate
      updateUser
    }
    financialTransactionDetails {
      aRChargeTransferFlagYN
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      adjustmentYN
      advGenerateTrxCode
      advanceBillReversedYn
      advanceBillYn
      advancedGenerateYn
      advancedGeneratedAdjustment
      advgentranscodeid
      allowanceType
      apartmentStyleBillingType
      approvalCode
      approvalDate
      approvalStatus
      arrangementCode
      arrangementDesc
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authemployeeid
      authorizer
      autoCreditbillYn
      autoSettleYn
      billingEventID
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cCashierOpeningBalance
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cTaxRate
      cVatAmount
      cCApproval
      calculatePointsYN
      cashBagNumber
      cashier
      cashierCredit
      cashierDebit
      cashierID
      cashierOpeningBalance
      ccRefundPosting
      centralARLedgerCredit
      centralARLedgerDebit
      centralAdvancedGeneratedTransactionCode
      centralCashierCredit
      centralCashierDebit
      centralCreditCardSurcharge
      centralDepositAmountPaid
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralGrossAmount
      centralGuestAccountLedgerCredit
      centralGuestAccountLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralNetAmount
      centralNonRevenueAmount
      centralPackage
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralPostedAmountInBaseCurrency
      centralPricePerUnit
      centralRevenueIncluded
      centralTransactionCodeDescription
      centralTrialBalanceAmountGross
      centralTrialBalanceAmountNet
      chainCode
      changeDue
      checkFileId
      checkNumber
      closureNumber
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      complinktranscodeid
      compressedYn
      contractforeigncurrencyid
      correctionYn
      couponNo
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      customChargeDate
      dSI
      debitYN
      deferredYn
      deletedFlag
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      depositlinkfintransid
      displayflag
      dualCurrency
      dualCurrencyGrossAmount
      dualCurrencyGuestCredit
      dualCurrencyGuestDebit
      dualCurrencyNetAmount
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionCodeType
      fintransactionid
      fintransid
      fiscalBillNo
      fixedChargesYN
      folioNo
      folioType
      folioTypeJoin
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      guestCountry
      guestCountryCode
      hotelAcct
      inHouseCredit
      inHouseDebit
      incTaxDeductedYn
      individualAdjustmentYN
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketid
      membershipID
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      oTransactionDesc
      oVOSCurrency
      oVOSGrossAmount
      oVOSGuestCredit
      oVOSGuestDebit
      oVOSNetAmount
      onHoldYN
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      originalresvid
      othersBagNumber
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      packagelinkfintransid
      parallelforeigncurrencyid
      parentfintransid
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      paymentsReference
      postedAmountInBaseCurrency
      postedAmountInTransactionCurrency
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300YN
      productid
      profileid
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rateCode
      ratecodeid
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationid
      resvenddate
      revenueAmount
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roomid
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceChargeIncludedRevenueTaxPercent
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceResort
      sourceid
      splitType
      stampDutyYN
      supplement
      taCommissionNetYn
      targetResort
      targetlocationid
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionActivityDate
      transactionCode
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionReservationNameID
      transactionStatus
      transactionType
      transactionFromAccount
      transactionToAccount
      transactionsReasonCode
      transcodearrangementid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      travelAgentCommissionableYN
      trialBalanceAmountGross
      trialBalanceAmountNet
      trxCode
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxType
      updateDate
      updateUser
      upsellChargeYn
      userID
      vatAmount
      vatOffsetYn
      vendorTranID
    }
    accountDetails {
      chainCode
      accountCode
      accountCreditLimitYn
      accountName
      accountNumber
      accountSname
      accountStatus
      accountStatusMsg
      accountType
      accountTypeFlag
      accountTypeId
      accountid
      acctflagreasonid
      activeYN
      addressId
      address1
      address2
      address3
      age
      agent
      agentUserId
      agentemployeeid
      balance
      batchStmtYn
      beginDate
      centralAccountType
      centralBalance
      centralCreditLimit
      centralFlaggedReasonCode
      centralState
      centralXchangeDate
      centralXchangeRate
      city
      company
      contact
      country
      countryCode
      countryName
      creditLimit
      creditLimitUpdatedOn
      currencyCode
      dSI
      debtorName
      deletedflag
      email
      emailAddr
      emailId
      emailOptInYn
      endDate
      fax
      faxId
      faxNumber
      flaggedReasonCode
      inactiveDate
      insertDate
      insertUser
      internalAccounttypeid
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastActivityDate
      lastRemFaxNo
      lastStmtFaxNo
      locationID
      lstRemPrtDate
      lstRemSent
      lstRemText
      lstStmtNoSent
      lstStmtSent
      monthEndCalcYn
      nAAddress1
      nAAddress2
      nAAddress3
      naCity
      naCountryName
      naState
      naStateDescription
      nameId
      numberOfPersons
      organizationID
      paymentDueDays
      permAccountYN
      phone
      phoneId
      phoneNumber
      postalCode
      primaryKeyID
      primaryYn
      profileid
      property
      rNAInsertDate
      rNAUpdateDate
      repStateDescription
      revenuePool
      state
      stateDescription
      status
      summaryforeigncurrid
      superSearchIndexText
      supplement
      updateDate
      updateUser
      upperCaseName
      zip
    }
    calendarPeriodDayDetails {
      chainCode
      dSI
      dayKey
      deletedFlag
      endDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      parentPeriod
      parentperiodid
      periodCode
      periodDescription
      periodScope
      periodType
      periodTypeDesc
      periodsetupid
      periodsetuppmsref
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      startDate
      updateDate
      updateUser
      year
      yearDescription
      yearEndDate
      yearId
      yearStartDate
      yearType
      yearsetupid
    }
    financialPeriodDayDetails {
      chainCode
      dSI
      dayKey
      deletedFlag
      endDate
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      parentPeriod
      parentperiodid
      periodCode
      periodDescription
      periodScope
      periodType
      periodTypeDesc
      periodsetupid
      periodsetuppmsref
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      startDate
      updateDate
      updateUser
      year
      yearDescription
      yearEndDate
      yearId
      yearStartDate
      yearType
      yearsetupid
    }
    aRLedgerDetails {
      chainCode
      aRChargeTransferYN
      aSBFlag
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountName
      accountNumber
      accountTypeFlag
      accountid
      advGenerateAdjustment
      advanceBillReversedYn
      advanceBillYn
      advanceGenerateTrxCode
      advancedGenerateYn
      allowanceType
      amount
      approvalCode
      approvalDate
      approvalStatus
      arLedgerCredit
      arLedgerDebit
      arNumber
      arState
      arTransferDate
      arrangementId
      articleId
      associatedReceiptNo
      associatedTrxNumber
      authorizerId
      autoCreditbillYn
      autoSettleYn
      billNo
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      cARLedgerCredit
      cARLedgerDebit
      cCashierCredit
      cCashierDebit
      cCashierOpeningBalance
      cCcTransactionFeeAmount
      cChangeDue
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cDepLedgerCredit
      cDepLedgerDebit
      cExchangeDate
      cExchangeRate
      cForexCommissionAmount
      cGrossAmount
      cGuestAccountCredit
      cGuestAccountDebit
      cInHouseCredit
      cInHouseDebit
      cNetAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cPackageCredit
      cPackageDebit
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
      cPostedAmount
      cPricePerUnit
      cRevenueAmount
      cTaxRate
      cTransactionAmount
      calcPointsYn
      cashierCredit
      cashierDebit
      cashierId
      cashierOpeningBalance
      ccRefundPosting
      ccTrxFeeAmount
      centralARLedgerAmount
      changeDue
      checkFileId
      chequeNumber
      closureNo
      collectionAgentPostingYn
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      compressedYn
      contractCurrency
      contractGrossAmount
      contractGuestCredit
      contractGuestDebit
      contractNetAmount
      correctionYn
      couponNo
      covers
      currencyCode
      dSI
      deferredTaxesYn
      deferredYn
      deletedFlag
      depLedgerCredit
      depLedgerDebit
      depPostingFlag
      depTaxTransferedYn
      depositTransactionId
      displayYn
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYn
      exchangeRate
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      financialTransactionSubtype
      fintransid
      fiscalBillNo
      fiscalTrxCodeType
      fixedChargesYn
      folioNo
      folioType
      folioView
      folioid
      foreignCurrencyID
      forexCommAmount
      forexCommPerc
      forexTaxYn
      forexType
      fromReservationId
      ftGeneratedType
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountCredit
      guestAccountDebit
      holdYn
      hotelAcct
      incTaxDeductedYn
      individualAdjustmentYN
      inhCredit
      inhDebit
      insertDate
      insertUser
      installments
      internalCashierid
      invoiceCloseDate
      invoiceNo
      invoiceType
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkTrxNumber
      locationID
      marketCode
      membershipId
      mtrxNoAgainstPackage
      nameId
      nameTaxType
      netAmount
      numberDialed
      oTransactionDesc
      orgBillNumber
      orgFolioType
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalReservationNameId
      originalRoom
      packageAllowance
      packageArrangementCode
      packageCredit
      packageDebit
      packageTrxType
      parallelCurrency
      parallelGrossAmount
      parallelGuestCredit
      parallelGuestDebit
      parallelNetAmount
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      postedAmount
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      pricePerUnit
      primaryKeyID
      processed8300Yn
      product
      profitLossFlag
      proformaYn
      property
      propertyBillPrefix
      quantity
      queueName
      rNAInsertDate
      rNAUpdateDate
      rateCode
      reasonCode
      receiptNo
      receiptType
      reference
      reservationDepositId
      reservationNameId
      reservationid
      revenueAmt
      reversePaymentTrxNumber
      revisionNo
      room
      roomClass
      roomNts
      roomNtsEffective
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingDate
      routingInstrnId
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      settlementFlag
      sourceCode
      sourceCommissionNetYn
      splitType
      supplement
      taCommissionNetYn
      taCommissionableYn
      targetResort
      taxElements
      taxGeneratedYn
      taxInclusiveYn
      taxInvNumber
      taxRate
      taxRateType
      tcGroup
      tcSubgroup
      tclCode1
      tclCode2
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transactionDate
      transactionFromAcct
      transactionNumber
      transactionToAcct
      transcodearrangementid
      transcodeid
      trnsActivityDate
      trxAmount
      trxCode
      trxNumberAddedBy
      trxNumberAdjust
      trxNumberAgainstPackage
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      updateDate
      updateUser
      upsellChargeYn
      vatOffsetYn
    }
    invoiceHeaderDetails {
      aRDebit
      aRLedgerCredit
      aRTransferDate
      accountCode
      accountTypeFlag
      accountid
      addresseeNameId
      adjustmentYn
      adjustmentflag
      agingBucket
      agingBusinessDate
      amount
      billNumber
      cARLedgerCredit
      cARLedgerDebit
      cAmount
      cContractCurrencyDifference
      cExchangeDate
      cExchangeRate
      cOrganizationAmount
      cOrganizationAmountContract
      cOrganizationAmountCurrencyDifference
      cOrganizationAmountParallel
      cPaid
      cParallelCurrencyDifference
      cashierId
      centralProfileID
      checkOutDate
      compressDate
      compressedYn
      contractCurrDifference
      contractCurrencyCode
      creditedToTrxNumber
      dSI
      dateForAging
      deletedFlag
      expInvoiceType
      expOriginalInvoice
      externalReceiptDate
      fintransid
      fiscalBillNo
      folioNo
      folioText1
      folioText2
      folioType
      folioid
      insertDate
      insertUser
      invoiceAge
      invoiceCloseDate
      invoiceClosedBy
      invoiceNumber
      invoiceStatus
      invoiceType
      invoiceid
      invoiceprofileid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      masterInvoiceNumber
      name
      nameId
      organizationID
      originalAmount
      originalAmountContractCurrency
      originalAmountCurrencyDifference
      originalAmountDualCurrency
      ownerRoom
      ownerroomid
      paid
      parallelCurrDifference
      parallelCurrencyCode
      paymentNo
      postDate
      primaryKeyID
      printedDate
      printedYn
      profileID
      property
      purgeYn
      reference
      remark
      reminderCycle
      reminderDate
      reservationNameId
      reservationid
      rnaInsertDate
      rnaUpdateDate
      room
      roomid
      statementNumber
      tranActionId
      transactionActivityDate
      transactionDate
      transactionFromAcct
      transactionToAcct
      transcodeid
      transferfromaccountid
      transfertoaccountid
      trxCode
      trxNumber
      updateDate
      updateUser
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
a_r_aging_report_details_schema = {
    'chainCode': pl.Utf8,
    'aRLedgerDebit': pl.Float64,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountType': pl.Utf8,
    'accountid': pl.Float64,
    'age1': pl.Float64,
    'age2': pl.Float64,
    'age3': pl.Float64,
    'age4': pl.Float64,
    'age5': pl.Float64,
    'age6': pl.Float64,
    'agingbucket': pl.Float64,
    'arTransferDate': pl.Utf8,
    'billNumber': pl.Float64,
    'billingContactName': pl.Utf8,
    'businessDate': pl.Utf8,
    'cARLedgerCredit': pl.Float64,
    'cARLedgerDebit': pl.Float64,
    'cAmount': pl.Float64,
    'cContractCurrencyDifference': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cOrganizationAmount': pl.Float64,
    'cOrganizationAmountContract': pl.Float64,
    'cOrganizationAmountCurrencyDifference': pl.Float64,
    'cOrganizationAmountParallel': pl.Float64,
    'cParallelCurrencyDifference': pl.Float64,
    'centralAccountType': pl.Utf8,
    'centralOpenARTransactionAmount': pl.Float64,
    'checkOutDate': pl.Utf8,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'fintransid': pl.Float64,
    'folioNo': pl.Float64,
    'folioid': pl.Float64,
    'internalCheckoutDate': pl.Utf8,
    'invoiceAge': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNo': pl.Float64,
    'invoiceNumber': pl.Float64,
    'invoiceStatus': pl.Utf8,
    'invoiceamount': pl.Float64,
    'invoiceid': pl.Float64,
    'invoiceprofileid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterInvoiceNo': pl.Float64,
    'nameId': pl.Float64,
    'openARTransactionAmount': pl.Float64,
    'organizationID': pl.Int64,
    'ownerRoom': pl.Utf8,
    'ownerroomid': pl.Utf8,
    'pmsBusinessDate': pl.Utf8,
    'postDate': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'room': pl.Utf8,
    'roomid': pl.Utf8,
    'transactionFromAcct': pl.Float64,
    'transactionToAcct': pl.Float64,
    'transactionid': pl.Float64,
    'transcodeid': pl.Utf8,
    'transferfromaccountid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'trxCode': pl.Utf8,
    'trxDate': pl.Utf8,
    'trxNumber': pl.Float64,
}
```
```python
transaction_code_details_schema = {
    'chainCode': pl.Utf8,
    'aRLedgerPaymentsYN': pl.Utf8,
    'aRNameId': pl.Float64,
    'accountNumber': pl.Utf8,
    'accountingCode': pl.Utf8,
    'acctrecvprofileid': pl.Float64,
    'adjTrxCode': pl.Utf8,
    'adjtranscodeid': pl.Utf8,
    'arrangeCode': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'cDefaultPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cExportBucket': pl.Float64,
    'cMaxAmount': pl.Float64,
    'cMinimumAmount': pl.Float64,
    'cCCode': pl.Utf8,
    'cRSTaxDesc': pl.Utf8,
    'cashTransactionCodeYN': pl.Utf8,
    'ccType': pl.Utf8,
    'centalSubgroup': pl.Utf8,
    'centralAdjustmentTransactionCode': pl.Utf8,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeGroup': pl.Utf8,
    'chargeDeferredUntilCheckoutYN': pl.Utf8,
    'checkNumberMandatoryYN': pl.Utf8,
    'class1MandatoryYn': pl.Utf8,
    'class2MandatoryYn': pl.Utf8,
    'commissionCode': pl.Float64,
    'compNightsYn': pl.Utf8,
    'compPaymentYn': pl.Utf8,
    'complimentaryYN': pl.Utf8,
    'corpPropFlag': pl.Utf8,
    'corporateDescription': pl.Utf8,
    'crossPostingDepositYN': pl.Utf8,
    'crossPostingPaymentYN': pl.Utf8,
    'crossPostingSalesYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dailyPlanFolio': pl.Float64,
    'dedOwnerRevenueYN': pl.Utf8,
    'defaultPrice': pl.Float64,
    'deletedFlag': pl.Utf8,
    'depositLedgerPaymentsYN': pl.Utf8,
    'depositPostingOnlyYn': pl.Utf8,
    'depositType': pl.Utf8,
    'eInvoiceYn': pl.Utf8,
    'expenseFolio': pl.Float64,
    'exportBucket': pl.Float64,
    'externalPaymentCode': pl.Utf8,
    'fiscalPaymentYn': pl.Utf8,
    'fiscalTrxCodeType': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'gDeletedFlag': pl.Utf8,
    'gDescription': pl.Utf8,
    'gInsertDate': pl.Utf8,
    'gInsertUser': pl.Float64,
    'gOrderBy': pl.Float64,
    'gRepDescription': pl.Utf8,
    'gResultIncludedInSumArray': pl.Utf8,
    'gRevenuegroupflag': pl.Utf8,
    'gTctClassType1': pl.Utf8,
    'gTctClassType2': pl.Utf8,
    'gUpdateDate': pl.Utf8,
    'gUpdateUser': pl.Float64,
    'group': pl.Utf8,
    'groupClass1MandatoryYN': pl.Utf8,
    'groupClass2MandatoryYN': pl.Utf8,
    'groupFolio': pl.Float64,
    'groupIndRevenueGroup': pl.Utf8,
    'groupInternalYN': pl.Utf8,
    'groupPointsRedemptionYN': pl.Utf8,
    'groupRepItem': pl.Utf8,
    'groupRepItemName': pl.Utf8,
    'groupRepItemOrderby': pl.Float64,
    'groupRepOrderBy': pl.Float64,
    'groupRepUpdateDate': pl.Utf8,
    'groupTcTransactionType': pl.Utf8,
    'guestLedgerPaymentsYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'includeIn8300Yn': pl.Utf8,
    'includeInDepositRuleYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalTransactionCodeSubGroup': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualPostCoversYn': pl.Utf8,
    'manualPostingAllowedYN': pl.Utf8,
    'maximumAmount': pl.Float64,
    'membershipYN': pl.Utf8,
    'minimumAmount': pl.Float64,
    'nonTaxableYn': pl.Utf8,
    'organizationID': pl.Int64,
    'ownerRevenueYN': pl.Utf8,
    'paymentTaxInvoiceYn': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printReceiptYN': pl.Utf8,
    'processingType': pl.Utf8,
    'property': pl.Utf8,
    'quantityCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'revenueBucketId': pl.Float64,
    'revenueGroupId': pl.Float64,
    'revenueYN': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rotationRevenueYN': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'serviceRecoveryTrxCode': pl.Utf8,
    'sgDeletedFlag': pl.Utf8,
    'sgDescription': pl.Utf8,
    'sgInsertDate': pl.Utf8,
    'sgInsertUser': pl.Float64,
    'sgOrderBy': pl.Float64,
    'sgResultIncludedInSumArray': pl.Utf8,
    'sgRevenuegroupflag': pl.Utf8,
    'sgTaxflag': pl.Utf8,
    'sgUpdateDate': pl.Utf8,
    'sgUpdateUser': pl.Float64,
    'subGroupClass1MandatoryYN': pl.Utf8,
    'subGroupClass2MandatoryYN': pl.Utf8,
    'subGroupFrequentFlyerYN': pl.Utf8,
    'subGroupGroupPointsRedemptionYN': pl.Utf8,
    'subGroupIndRevenueGroup': pl.Utf8,
    'subGroupInternalYN': pl.Utf8,
    'subGroupRepDescription': pl.Utf8,
    'subGroupRepOrderBy': pl.Float64,
    'subGroupTcGroupAndSubgroup': pl.Utf8,
    'subGroupTcTransactionType': pl.Utf8,
    'subGroupType': pl.Utf8,
    'taxCodeNumber': pl.Float64,
    'taxInclusiveYN': pl.Utf8,
    'taxYN': pl.Utf8,
    'tcBofInterface': pl.Utf8,
    'tcBofInterface2': pl.Utf8,
    'tcBofRefCode': pl.Utf8,
    'tcBofRefCode2': pl.Utf8,
    'tcResort2': pl.Utf8,
    'tcTransactionType': pl.Utf8,
    'tclCodeDfltCl1': pl.Utf8,
    'tclCodeDfltCl2': pl.Utf8,
    'transactionActionId': pl.Float64,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroup': pl.Utf8,
    'transactionCodeResort': pl.Utf8,
    'transactionCodeSubGroup': pl.Utf8,
    'transactionCodeType': pl.Utf8,
    'transactionType': pl.Utf8,
    'transcodearrangementid': pl.Utf8,
    'transcodeid': pl.Utf8,
    'trxCode': pl.Utf8,
    'trxCodeDisplay': pl.Utf8,
    'trxServiceType': pl.Utf8,
    'trxTaxTypeCode': pl.Utf8,
    'uPC': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
folio_details_schema = {
    'billGenerationDate': pl.Utf8,
    'billNumber': pl.Float64,
    'businessdate': pl.Utf8,
    'cashierId': pl.Float64,
    'checkExchangeReceiptNumber': pl.Float64,
    'currencyExchangeReceiptNumber': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'folioNo': pl.Float64,
    'folioSeqNumber': pl.Float64,
    'folioStatus': pl.Utf8,
    'folioStyle': pl.Utf8,
    'folioType': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'frontOfficeDate': pl.Utf8,
    'fullFolioNo': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalUpdatedate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'name': pl.Utf8,
    'nameId': pl.Float64,
    'numberReprints': pl.Float64,
    'numberOfPersons': pl.Float64,
    'organizationID': pl.Int64,
    'phoneDetails': pl.Utf8,
    'postitNo': pl.Float64,
    'postityn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'processIdent': pl.Utf8,
    'profileid': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'resvdeptrno': pl.Float64,
    'resvenddate': pl.Utf8,
    'revisionNumber': pl.Float64,
    'state': pl.Utf8,
    'templatePath': pl.Utf8,
    'timestamp': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
financial_transaction_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
    'advGenerateTrxCode': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advancedGeneratedAdjustment': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'allowanceType': pl.Utf8,
    'apartmentStyleBillingType': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billingEventID': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCashierOpeningBalance': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'cCApproval': pl.Utf8,
    'calculatePointsYN': pl.Utf8,
    'cashBagNumber': pl.Utf8,
    'cashier': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAdvancedGeneratedTransactionCode': pl.Utf8,
    'centralCashierCredit': pl.Float64,
    'centralCashierDebit': pl.Float64,
    'centralCreditCardSurcharge': pl.Float64,
    'centralDepositAmountPaid': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestAccountLedgerCredit': pl.Float64,
    'centralGuestAccountLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackage': pl.Utf8,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralPostedAmountInBaseCurrency': pl.Float64,
    'centralPricePerUnit': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralTransactionCodeDescription': pl.Utf8,
    'centralTrialBalanceAmountGross': pl.Float64,
    'centralTrialBalanceAmountNet': pl.Float64,
    'chainCode': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'customChargeDate': pl.Utf8,
    'dSI': pl.Int64,
    'debitYN': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'dualCurrency': pl.Utf8,
    'dualCurrencyGrossAmount': pl.Float64,
    'dualCurrencyGuestCredit': pl.Float64,
    'dualCurrencyGuestDebit': pl.Float64,
    'dualCurrencyNetAmount': pl.Float64,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionCodeType': pl.Utf8,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'guestCountry': pl.Utf8,
    'guestCountryCode': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'incTaxDeductedYn': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketid': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'oVOSCurrency': pl.Utf8,
    'oVOSGrossAmount': pl.Float64,
    'oVOSGuestCredit': pl.Float64,
    'oVOSGuestDebit': pl.Float64,
    'oVOSNetAmount': pl.Float64,
    'onHoldYN': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'othersBagNumber': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentsReference': pl.Utf8,
    'postedAmountInBaseCurrency': pl.Float64,
    'postedAmountInTransactionCurrency': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300YN': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roomid': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceChargeIncludedRevenueTaxPercent': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceResort': pl.Utf8,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'stampDutyYN': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionReservationNameID': pl.Float64,
    'transactionStatus': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transactionsReasonCode': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'travelAgentCommissionableYN': pl.Utf8,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'userID': pl.Float64,
    'vatAmount': pl.Float64,
    'vatOffsetYn': pl.Utf8,
    'vendorTranID': pl.Utf8,
}
```
```python
account_details_schema = {
    'chainCode': pl.Utf8,
    'accountCode': pl.Float64,
    'accountCreditLimitYn': pl.Utf8,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountSname': pl.Utf8,
    'accountStatus': pl.Utf8,
    'accountStatusMsg': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountTypeId': pl.Float64,
    'accountid': pl.Float64,
    'acctflagreasonid': pl.Utf8,
    'activeYN': pl.Utf8,
    'addressId': pl.Float64,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'age': pl.Float64,
    'agent': pl.Utf8,
    'agentUserId': pl.Float64,
    'agentemployeeid': pl.Float64,
    'balance': pl.Float64,
    'batchStmtYn': pl.Utf8,
    'beginDate': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralBalance': pl.Float64,
    'centralCreditLimit': pl.Float64,
    'centralFlaggedReasonCode': pl.Utf8,
    'centralState': pl.Utf8,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'city': pl.Utf8,
    'company': pl.Utf8,
    'contact': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryName': pl.Utf8,
    'creditLimit': pl.Float64,
    'creditLimitUpdatedOn': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'debtorName': pl.Utf8,
    'deletedflag': pl.Utf8,
    'email': pl.Utf8,
    'emailAddr': pl.Utf8,
    'emailId': pl.Float64,
    'emailOptInYn': pl.Utf8,
    'endDate': pl.Utf8,
    'fax': pl.Utf8,
    'faxId': pl.Float64,
    'faxNumber': pl.Utf8,
    'flaggedReasonCode': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalAccounttypeid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastActivityDate': pl.Utf8,
    'lastRemFaxNo': pl.Utf8,
    'lastStmtFaxNo': pl.Utf8,
    'locationID': pl.Utf8,
    'lstRemPrtDate': pl.Utf8,
    'lstRemSent': pl.Utf8,
    'lstRemText': pl.Utf8,
    'lstStmtNoSent': pl.Float64,
    'lstStmtSent': pl.Utf8,
    'monthEndCalcYn': pl.Utf8,
    'nAAddress1': pl.Utf8,
    'nAAddress2': pl.Utf8,
    'nAAddress3': pl.Utf8,
    'naCity': pl.Utf8,
    'naCountryName': pl.Utf8,
    'naState': pl.Utf8,
    'naStateDescription': pl.Utf8,
    'nameId': pl.Float64,
    'numberOfPersons': pl.Float64,
    'organizationID': pl.Int64,
    'paymentDueDays': pl.Float64,
    'permAccountYN': pl.Utf8,
    'phone': pl.Utf8,
    'phoneId': pl.Float64,
    'phoneNumber': pl.Utf8,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYn': pl.Utf8,
    'profileid': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'revenuePool': pl.Utf8,
    'state': pl.Utf8,
    'stateDescription': pl.Utf8,
    'status': pl.Utf8,
    'summaryforeigncurrid': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'supplement': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upperCaseName': pl.Utf8,
    'zip': pl.Utf8,
}
```
```python
calendar_period_day_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'dayKey': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'parentPeriod': pl.Utf8,
    'parentperiodid': pl.Utf8,
    'periodCode': pl.Utf8,
    'periodDescription': pl.Utf8,
    'periodScope': pl.Utf8,
    'periodType': pl.Utf8,
    'periodTypeDesc': pl.Utf8,
    'periodsetupid': pl.Float64,
    'periodsetuppmsref': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearId': pl.Float64,
    'yearStartDate': pl.Utf8,
    'yearType': pl.Utf8,
    'yearsetupid': pl.Float64,
}
```
```python
financial_period_day_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'dayKey': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'parentPeriod': pl.Utf8,
    'parentperiodid': pl.Utf8,
    'periodCode': pl.Utf8,
    'periodDescription': pl.Utf8,
    'periodScope': pl.Utf8,
    'periodType': pl.Utf8,
    'periodTypeDesc': pl.Utf8,
    'periodsetupid': pl.Float64,
    'periodsetuppmsref': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearId': pl.Float64,
    'yearStartDate': pl.Utf8,
    'yearType': pl.Utf8,
    'yearsetupid': pl.Float64,
}
```
```python
a_r_ledger_details_schema = {
    'chainCode': pl.Utf8,
    'aRChargeTransferYN': pl.Utf8,
    'aSBFlag': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountName': pl.Utf8,
    'accountNumber': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'advGenerateAdjustment': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advanceGenerateTrxCode': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'allowanceType': pl.Utf8,
    'amount': pl.Float64,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arLedgerCredit': pl.Float64,
    'arLedgerDebit': pl.Float64,
    'arNumber': pl.Float64,
    'arState': pl.Utf8,
    'arTransferDate': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedReceiptNo': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billNo': pl.Float64,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cARLedgerCredit': pl.Float64,
    'cARLedgerDebit': pl.Float64,
    'cCashierCredit': pl.Float64,
    'cCashierDebit': pl.Float64,
    'cCashierOpeningBalance': pl.Float64,
    'cCcTransactionFeeAmount': pl.Float64,
    'cChangeDue': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cDepLedgerCredit': pl.Float64,
    'cDepLedgerDebit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cGrossAmount': pl.Float64,
    'cGuestAccountCredit': pl.Float64,
    'cGuestAccountDebit': pl.Float64,
    'cInHouseCredit': pl.Float64,
    'cInHouseDebit': pl.Float64,
    'cNetAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cPackageCredit': pl.Float64,
    'cPackageDebit': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
    'cPostedAmount': pl.Float64,
    'cPricePerUnit': pl.Float64,
    'cRevenueAmount': pl.Float64,
    'cTaxRate': pl.Float64,
    'cTransactionAmount': pl.Float64,
    'calcPointsYn': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierId': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'ccTrxFeeAmount': pl.Float64,
    'centralARLedgerAmount': pl.Float64,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'chequeNumber': pl.Utf8,
    'closureNo': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractCurrency': pl.Utf8,
    'contractGrossAmount': pl.Float64,
    'contractGuestCredit': pl.Float64,
    'contractGuestDebit': pl.Float64,
    'contractNetAmount': pl.Float64,
    'correctionYn': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'deferredTaxesYn': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depLedgerCredit': pl.Float64,
    'depLedgerDebit': pl.Float64,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositTransactionId': pl.Utf8,
    'displayYn': pl.Utf8,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYn': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'financialTransactionSubtype': pl.Utf8,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fiscalTrxCodeType': pl.Utf8,
    'fixedChargesYn': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioView': pl.Float64,
    'folioid': pl.Float64,
    'foreignCurrencyID': pl.Utf8,
    'forexCommAmount': pl.Float64,
    'forexCommPerc': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'forexType': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountCredit': pl.Float64,
    'guestAccountDebit': pl.Float64,
    'holdYn': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'incTaxDeductedYn': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'inhCredit': pl.Float64,
    'inhDebit': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'installments': pl.Float64,
    'internalCashierid': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNo': pl.Float64,
    'invoiceType': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'membershipId': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'oTransactionDesc': pl.Utf8,
    'orgBillNumber': pl.Float64,
    'orgFolioType': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageCredit': pl.Float64,
    'packageDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'parallelCurrency': pl.Utf8,
    'parallelGrossAmount': pl.Float64,
    'parallelGuestCredit': pl.Float64,
    'parallelGuestDebit': pl.Float64,
    'parallelNetAmount': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'postedAmount': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'pricePerUnit': pl.Float64,
    'primaryKeyID': pl.Int64,
    'processed8300Yn': pl.Utf8,
    'product': pl.Utf8,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'reasonCode': pl.Utf8,
    'receiptNo': pl.Float64,
    'receiptType': pl.Utf8,
    'reference': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'revenueAmt': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'room': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingInstrnId': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'splitType': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'taCommissionableYn': pl.Utf8,
    'targetResort': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYn': pl.Utf8,
    'taxInclusiveYn': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionDate': pl.Utf8,
    'transactionFromAcct': pl.Float64,
    'transactionNumber': pl.Float64,
    'transactionToAcct': pl.Float64,
    'transcodearrangementid': pl.Float64,
    'transcodeid': pl.Utf8,
    'trnsActivityDate': pl.Utf8,
    'trxAmount': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNumberAddedBy': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberAgainstPackage': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'vatOffsetYn': pl.Utf8,
}
```
```python
invoice_header_details_schema = {
    'aRDebit': pl.Float64,
    'aRLedgerCredit': pl.Float64,
    'aRTransferDate': pl.Utf8,
    'accountCode': pl.Float64,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adjustmentYn': pl.Utf8,
    'adjustmentflag': pl.Utf8,
    'agingBucket': pl.Float64,
    'agingBusinessDate': pl.Utf8,
    'amount': pl.Float64,
    'billNumber': pl.Float64,
    'cARLedgerCredit': pl.Float64,
    'cARLedgerDebit': pl.Float64,
    'cAmount': pl.Float64,
    'cContractCurrencyDifference': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cOrganizationAmount': pl.Float64,
    'cOrganizationAmountContract': pl.Float64,
    'cOrganizationAmountCurrencyDifference': pl.Float64,
    'cOrganizationAmountParallel': pl.Float64,
    'cPaid': pl.Float64,
    'cParallelCurrencyDifference': pl.Float64,
    'cashierId': pl.Float64,
    'centralProfileID': pl.Utf8,
    'checkOutDate': pl.Utf8,
    'compressDate': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractCurrDifference': pl.Float64,
    'contractCurrencyCode': pl.Utf8,
    'creditedToTrxNumber': pl.Float64,
    'dSI': pl.Int64,
    'dateForAging': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'externalReceiptDate': pl.Utf8,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'folioNo': pl.Float64,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'folioType': pl.Utf8,
    'folioid': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'invoiceAge': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceClosedBy': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceStatus': pl.Utf8,
    'invoiceType': pl.Utf8,
    'invoiceid': pl.Float64,
    'invoiceprofileid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterInvoiceNumber': pl.Float64,
    'name': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'originalAmount': pl.Float64,
    'originalAmountContractCurrency': pl.Float64,
    'originalAmountCurrencyDifference': pl.Float64,
    'originalAmountDualCurrency': pl.Float64,
    'ownerRoom': pl.Utf8,
    'ownerroomid': pl.Utf8,
    'paid': pl.Float64,
    'parallelCurrDifference': pl.Float64,
    'parallelCurrencyCode': pl.Utf8,
    'paymentNo': pl.Utf8,
    'postDate': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printedDate': pl.Utf8,
    'printedYn': pl.Utf8,
    'profileID': pl.Utf8,
    'property': pl.Utf8,
    'purgeYn': pl.Utf8,
    'reference': pl.Utf8,
    'remark': pl.Utf8,
    'reminderCycle': pl.Float64,
    'reminderDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomid': pl.Utf8,
    'statementNumber': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionFromAcct': pl.Float64,
    'transactionToAcct': pl.Float64,
    'transcodeid': pl.Utf8,
    'transferfromaccountid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'trxCode': pl.Utf8,
    'trxNumber': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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