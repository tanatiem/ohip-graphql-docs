# FinancialTransactionsSummary
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `financialTransactionsSummary`
> Summarized information on posted transactions including transaction group sub group and codes broken down by property and business date.
  
**Return:** [`[FinancialTransactionsSummaryType]`](#financialtransactionssummarytype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`FinancialTransactionsSummaryQueryArgumentsType!`](#financialtransactionssummaryqueryargumentstype) |  |

## Object Types

### FinancialTransactionsSummaryType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | trialBalanceDetails | [`FinancialTransactionsSummaryTrialBalanceDetailsType`](#financialtransactionssummarytrialbalancedetailstype) | Trial Balance Details |
| 2 | transactionCodeDetails | [`FinancialTransactionsSummaryTransactionCodeDetailsType`](#financialtransactionssummarytransactioncodedetailstype) | Transaction Code |
| 3 | roomClassDetails | [`FinancialTransactionsSummaryRoomClassDetailsType`](#financialtransactionssummaryroomclassdetailstype) | Room Class Details |
| 4 | gregerianCalendarDetails | [`FinancialTransactionsSummaryGregerianCalendarDetailsType`](#financialtransactionssummarygregeriancalendardetailstype) | Gregerian Calendar |
| 5 | fiscalCalendarDetails | [`FinancialTransactionsSummaryFiscalCalendarDetailsType`](#financialtransactionssummaryfiscalcalendardetailstype) | Fiscal Calendar |
| 6 | propertyPropertyDetails | [`FinancialTransactionsSummaryPropertyPropertyDetailsType`](#financialtransactionssummarypropertypropertydetailstype) | Resort Details |
| 7 | financialTransactionsSummaryRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryTrialBalanceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 2 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 3 | arLedgerCreditMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 4 | arLedgerCreditYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 5 | arLedgerDebitMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 6 | arLedgerDebitYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 7 | cARLedgerCreditMonthToDate | `Float` | Central Ar Led Credit Mm |
| 8 | cARLedgerCreditYearToDate | `Float` | Central Ar Led Credit Yy |
| 9 | cARLedgerDebitMonthToDate | `Float` | Central Ar Led Debit Mm |
| 10 | cARLedgerDebitYearToDate | `Float` | Central Ar Led Debit Yy |
| 11 | cDepFolioDebit | `Float` | Central Dep Folio Debit |
| 12 | cDepLedgerCreditMonthToDate | `Float` | Central Dep Led Credit Mm |
| 13 | cDepLedgerCreditYearToDate | `Float` | Central Dep Led Credit Yy |
| 14 | cDepLedgerDebitMonthToDate | `Float` | Central Dep Led Debit Mm |
| 15 | cDepLedgerDebitYearToDate | `Float` | Central Dep Led Debit Yy |
| 16 | cExchangeDate | `Date` | Central Xchange Date |
| 17 | cExchangeRate | `Float` | Central Xchange Rate |
| 18 | cGrossAmountMonthToDate | `Float` | Central Gross Amount Mm |
| 19 | cGrossAmountYearToDate | `Float` | Central Gross Amount Yy |
| 20 | cGuestLedgerCreditMonthToDate | `Float` | Central Guest Led Credit Mm |
| 21 | cGuestLedgerCreditYearToDate | `Float` | Central Guest Led Credit Yy |
| 22 | cGuestLedgerDebitMonthToDate | `Float` | Central Guest Led Debit Mm |
| 23 | cGuestLedgerDebitYearToDate | `Float` | Central Guest Led Debit Yy |
| 24 | cInternalDbPayments | `Float` | Central Internal Db Payments |
| 25 | cNetAmountMonthToDate | `Float` | Central Net Amount Mm |
| 26 | cNetAmountYearToDate | `Float` | Central Net Amount Yy |
| 27 | cNet1Amount | `Float` | Central Net1 Amt |
| 28 | cNet10Amount | `Float` | Central Net10 Amt |
| 29 | cNet11Amount | `Float` | Central Net11 Amt |
| 30 | cNet12Amount | `Float` | Central Net12 Amt |
| 31 | cNet13Amount | `Float` | Central Net13 Amt |
| 32 | cNet14Amount | `Float` | Central Net14 Amt |
| 33 | cNet15Amount | `Float` | Central Net15 Amt |
| 34 | cNet16Amount | `Float` | Central Net16 Amt |
| 35 | cNet17Amount | `Float` | Central Net17 Amt |
| 36 | cNet18Amount | `Float` | Central Net18 Amt |
| 37 | cNet19Amount | `Float` | Central Net19 Amt |
| 38 | cNet2Amount | `Float` | Central Net2 Amt |
| 39 | cNet20Amount | `Float` | Central Net20 Amt |
| 40 | cNet3Amount | `Float` | Central Net3 Amt |
| 41 | cNet4Amount | `Float` | Central Net4 Amt |
| 42 | cNet5Amount | `Float` | Central Net5 Amt |
| 43 | cNet6Amount | `Float` | Central Net6 Amt |
| 44 | cNet7Amount | `Float` | Central Net7 Amt |
| 45 | cNet8Amount | `Float` | Central Net8 Amt |
| 46 | cNet9Amount | `Float` | Central Net9 Amt |
| 47 | cOwnerLedgerCredit | `Float` | Central Owner Led Credit |
| 48 | cOwnerLedgerDebit | `Float` | Central Owner Led Debit |
| 49 | cPackageLedgerCreditMonthToDate | `Float` | Central Package Led Credit Mm |
| 50 | cPackageLedgerCreditYearToDate | `Float` | Central Package Led Credit Yy |
| 51 | cPackageLedgerDebitMonthToDate | `Float` | Central Package Led Debit Mm |
| 52 | cPackageLedgerDebitYearToDate | `Float` | Central Package Led Debit Yy |
| 53 | cPackageLedgerTax | `Float` | Central Package Led Tax |
| 54 | cRevenueMonthToDate | `Float` | Central Revenue Mm |
| 55 | cRevenueYearToDate | `Float` | Central Revenue Yy |
| 56 | cTax1Amount | `Float` | Central Tax1 Amt |
| 57 | cTax2Amount | `Float` | Central Tax2 Amt |
| 58 | cTax10Amount | `Float` | Central Tax10 Amt |
| 59 | cTax11Amount | `Float` | Central Tax11 Amt |
| 60 | cTax12Amount | `Float` | Central Tax12 Amt |
| 61 | cTax13Amount | `Float` | Central Tax13 Amt |
| 62 | cTax14Amount | `Float` | Central Tax14 Amt |
| 63 | cTax15Amount | `Float` | Central Tax15 Amt |
| 64 | cTax16Amount | `Float` | Central Tax16 Amt |
| 65 | cTax17Amount | `Float` | Central Tax17 Amt |
| 66 | cTax18Amount | `Float` | Central Tax18 Amt |
| 67 | cTax19Amount | `Float` | Central Tax19 Amt |
| 68 | cTax20Amount | `Float` | Central Tax20 Amt |
| 69 | cTax3Amount | `Float` | Central Tax3 Amt |
| 70 | cTax4Amount | `Float` | Central Tax4 Amt |
| 71 | cTax5Amount | `Float` | Central Tax5 Amt |
| 72 | cTax6Amount | `Float` | Central Tax6 Amt |
| 73 | cTax7Amount | `Float` | Central Tax7 Amt |
| 74 | cTax8Amount | `Float` | Central Tax8 Amt |
| 75 | cTax9Amount | `Float` | Central Tax9 Amt |
| 76 | cTransactionAmountMonthToDate | `Float` | Central Trx Amount Mm |
| 77 | cTransactionAmountYearToDate | `Float` | Central Trx Amount Yy |
| 78 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 79 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 80 | centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| 81 | centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| 82 | centralGrossAmount | `Float` | Central Gross Amount |
| 83 | centralGuestLedgerCredit | `Float` | Central Guest Ledger Credit |
| 84 | centralGuestLedgerDebit | `Float` | Central Guest Ledger Debit |
| 85 | centralInHouseCredit | `Float` | Central In-House Credit |
| 86 | centralInHouseDebit | `Float` | Central In-House Debit |
| 87 | centralNetAmount | `Float` | Central Net Amount |
| 88 | centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 89 | centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| 90 | centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| 91 | centralRevenueAmount | `Float` | Central Revenue Amount |
| 92 | centralTransactionAmount | `Float` | Central Transaction Amount |
| 93 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 94 | depFolioDebit | `Float` | Deposit ledger debit of consumption records from Deposit Folios. |
| 95 | depLedgerCreditMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 96 | depLedgerCreditYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 97 | depLedgerDebitMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 98 | depLedgerDebitYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 99 | depositLedgerCredit | `Float` | Deposit Ledger Credit |
| 100 | depositLedgerDebit | `Float` | Deposit Ledger Debit |
| 101 | grossAmount | `Float` | Gross Amount |
| 102 | grossAmountMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 103 | grossAmountYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 104 | guestLedgerCredit | `Float` | Deposit ledger credit amount |
| 105 | guestLedgerCreditMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 106 | guestLedgerCreditYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 107 | guestLedgerDebit | `Float` | Deposit ledger debit amount |
| 108 | guestLedgerDebitMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 109 | guestLedgerDebitYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 110 | inHouseCredit | `Float` | In-House Credit |
| 111 | inHouseDebit | `Float` | In-House Debit |
| 112 | internalDbPayments | `Float` | Internal DB settlement Amount for Invoices Created in A/R excluding Credit Card Compressions. |
| 113 | jRNUpdateDate | `Date` | JRN Update Date |
| 114 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 115 | locationID | `String` | Internal ID to uniquely identify the Property |
| 116 | netAmount | `Float` | Net Amount |
| 117 | netAmountMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 118 | netAmountYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 119 | net1Amt | `Float` | Net1 Amount |
| 120 | net10Amt | `Float` | Net10 Amount |
| 121 | net11Amt | `Float` | Net11 Amount |
| 122 | net12Amt | `Float` | Net12 Amount |
| 123 | net13Amt | `Float` | Net13 Amount |
| 124 | net14Amt | `Float` | Net14 Amount |
| 125 | net15Amt | `Float` | Net15 Amount |
| 126 | net16Amt | `Float` | Net16 Amount |
| 127 | net17Amt | `Float` | Net17 Amount |
| 128 | net18Amt | `Float` | Net18 Amount |
| 129 | net19Amt | `Float` | Net19 Amount |
| 130 | net2Amt | `Float` | Net2 Amount |
| 131 | net20Amt | `Float` | Net20 Amount |
| 132 | net3Amt | `Float` | Net3 Amount |
| 133 | net4Amt | `Float` | Net4 Amount |
| 134 | net5Amt | `Float` | Net5 Amount |
| 135 | net6Amt | `Float` | Net6 Amount |
| 136 | net7Amt | `Float` | Net7 Amount |
| 137 | net8Amt | `Float` | Net8 Amount |
| 138 | net9Amt | `Float` | Net9 Amount |
| 139 | nonRevenueAmount | `Float` | Non revenue amount |
| 140 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 141 | ownerLedgerCredit | `Float` | Total credit amount of the Owner Ledger for the key value of this record. |
| 142 | ownerLedgerDebit | `Float` | Total debit amount of the Owner Ledger for the key value of this record. |
| 143 | packageLedgerCredit | `Float` | Package ledger credit amount |
| 144 | packageLedgerCreditMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 145 | packageLedgerCreditYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 146 | packageLedgerDebit | `Float` | Package ledger debit amount |
| 147 | packageLedgerDebitMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 148 | packageLedgerDebitYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 149 | packageLedgerTax | `Float` | Tax of a package allowance product. |
| 150 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 151 | property | `String` | Code to uniquely identify the Property |
| 152 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 153 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 154 | revenueAmount | `Float` | Revenue Amount |
| 155 | revenueMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 156 | revenueYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 157 | roomClass | `String` | Room Class |
| 158 | roomclassid | `String` | Roomclassid |
| 159 | tax1Amt | `Float` | Tax1 Amount |
| 160 | tax2Amt | `Float` | Tax2 Amount |
| 161 | tax10Amt | `Float` | Tax10 Amount |
| 162 | tax11Amt | `Float` | Tax11 Amount |
| 163 | tax12Amt | `Float` | Tax12 Amount |
| 164 | tax13Amt | `Float` | Tax13 Amount |
| 165 | tax14Amt | `Float` | Tax14 Amount |
| 166 | tax15Amt | `Float` | Tax15 Amount |
| 167 | tax16Amt | `Float` | Tax16 Amount |
| 168 | tax17Amt | `Float` | Tax17 Amount |
| 169 | tax18Amt | `Float` | Tax18 Amount |
| 170 | tax19Amt | `Float` | Tax19 Amount |
| 171 | tax20Amt | `Float` | Tax20 Amount |
| 172 | tax3Amt | `Float` | Tax3 Amount |
| 173 | tax4Amt | `Float` | Tax4 Amount |
| 174 | tax5Amt | `Float` | Tax5 Amount |
| 175 | tax6Amt | `Float` | Tax6 Amount |
| 176 | tax7Amt | `Float` | Tax7 Amount |
| 177 | tax8Amt | `Float` | Tax8 Amount |
| 178 | tax9Amt | `Float` | Tax9 Amount |
| 179 | transactionAmount | `Float` | Transaction Amount |
| 180 | transactionCodeDescription | `String` | Transaction Code Description |
| 181 | transactionDate | `Date` | Transaction Date |
| 182 | transcodeid | `String` | Transcodeid |
| 183 | trialbalanceid | `Float` | Trialbalanceid |
| 184 | trxAmountMonthToDate | `Float` | Month-to-Date value of the corresponding field in this table without the _MM suffix. |
| 185 | trxAmountYearToDate | `Float` | Year-to-Date value of the corresponding field in this table without the _YY suffix. |
| 186 | trxCode | `String` | Transaction Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryTransactionCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRLedgerPaymentsYN | `String` | AR Ledger Payments YN |
| 2 | aRNameId | `Float` | Ar Name ID |
| 3 | accountNumber | `String` | Account Number |
| 4 | accountingCode | `String` | Accounting Code |
| 5 | acctrecvprofileid | `Float` | Acctrecvprofileid |
| 6 | adjTrxCode | `String` | Adj Trx Code |
| 7 | adjtranscodeid | `String` | Adjtranscodeid |
| 8 | arrangeCode | `String` | Arrange Code |
| 9 | arrangementCode | `String` | Arrangement Code |
| 10 | cDefaultPrice | `Float` | Central Default Price |
| 11 | cExchangeDate | `Date` | Central Xchange Date |
| 12 | cExchangeRate | `Float` | Central Xchange Rate |
| 13 | cExportBucket | `Float` | Central Export Bucket |
| 14 | cMaxAmount | `Float` | Central Max Amt |
| 15 | cMinimumAmount | `Float` | Central Min Amt |
| 16 | cCCode | `String` | CC Code |
| 17 | cRSTaxDesc | `String` | Crs Tax Description |
| 18 | cashTransactionCodeYN | `String` | Cash Transaction Code YN |
| 19 | ccType | `String` | Cc Type |
| 20 | centalSubgroup | `String` | Cental Subgroup |
| 21 | centralAdjustmentTransactionCode | `String` | Central Adjustment Transaction Code |
| 22 | centralTransactionCode | `String` | Central Transaction Code |
| 23 | centralTransactionCodeGroup | `String` | Central Transaction Code Group |
| 24 | chargeDeferredUntilCheckoutYN | `String` | Charge Deferred Until Checkout YN |
| 25 | checkNumberMandatoryYN | `String` | Check Number Mandatory YN |
| 26 | class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| 27 | class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| 28 | commissionCode | `Float` | Commission Code |
| 29 | compNightsYn | `String` | Comp Nights Y/N |
| 30 | compPaymentYn | `String` | Comp Payment Y/N |
| 31 | complimentaryYN | `String` | Complimentary YN |
| 32 | corpPropFlag | `String` | Corp Prop Flag |
| 33 | corporateDescription | `String` | Corporate Description |
| 34 | crossPostingDepositYN | `String` | To indicate that the transaction code can be used as a Deposit Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 35 | crossPostingPaymentYN | `String` | To indicate that the transaction code can be used as a Payment Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 36 | crossPostingSalesYN | `String` | To indicate that the transaction code can be used as a Sales Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 37 | currencyCode | `String` | Currency Code |
| 38 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 39 | dailyPlanFolio | `Float` | Daily Plan Folio |
| 40 | dedOwnerRevenueYN | `String` | Ded Owner Rev Y/N |
| 41 | defaultPrice | `Float` | Default Price |
| 42 | deletedFlag | `String` | Deleted Flag |
| 43 | depositLedgerPaymentsYN | `String` | Deposit Ledger Payments YN |
| 44 | depositPostingOnlyYn | `String` | Deposit Posting Only Y/N |
| 45 | depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| 46 | eInvoiceYn | `String` | E Invoice Y/N |
| 47 | expenseFolio | `Float` | Expense Folio |
| 48 | exportBucket | `Float` | Export Bucket |
| 49 | externalPaymentCode | `String` | External Payment Code |
| 50 | fiscalPaymentYn | `String` | Fiscal Payment Y/N |
| 51 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 52 | foreignCurrencyID | `String` | Foreign Currency ID |
| 53 | gDeletedFlag | `String` | Group Deleted Flag |
| 54 | gDescription | `String` | Group Description |
| 55 | gInsertDate | `DateTime` | Group Insert Date |
| 56 | gInsertUser | `Float` | Group Insert User |
| 57 | gOrderBy | `Float` | Group Order By |
| 58 | gRepDescription | `String` | Group Rep Description |
| 59 | gResultIncludedInSumArray | `String` | Group Result Included In Sum Array |
| 60 | gRevenuegroupflag | `String` | Group Revenuegroupflag |
| 61 | gTctClassType1 | `String` | Group Tct Class Type1 |
| 62 | gTctClassType2 | `String` | Group Tct Class Type2 |
| 63 | gUpdateDate | `DateTime` | Group Update Date |
| 64 | gUpdateUser | `Float` | Group Update User |
| 65 | group | `String` | Group |
| 66 | groupClass1MandatoryYN | `String` | G Class 1 Mandatory Y/N |
| 67 | groupClass2MandatoryYN | `String` | G Class 2 Mandatory Y/N |
| 68 | groupFolio | `Float` | Group Folio |
| 69 | groupIndRevenueGroup | `String` | G Individual Revenue Gp |
| 70 | groupInternalYN | `String` | G Internal Y/N |
| 71 | groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| 72 | groupRepItem | `String` | G Reporting Item |
| 73 | groupRepItemName | `String` | G Reporting Item Name |
| 74 | groupRepItemOrderby | `Float` | G Reporting Item Orderby |
| 75 | groupRepOrderBy | `Float` | G Reporting Order By |
| 76 | groupRepUpdateDate | `DateTime` | G Reporting Updatedate |
| 77 | groupTcTransactionType | `String` | G Transaction Code Transaction Type |
| 78 | guestLedgerPaymentsYN | `String` | Guest Ledger Payments YN |
| 79 | inactiveDate | `Date` | Inactive Date |
| 80 | inactiveflag | `String` | Inactive Flag |
| 81 | includeIn8300Yn | `String` | Include In 8300 Y/N |
| 82 | includeInDepositRuleYn | `String` | Include In Deposit Rule Y/N |
| 83 | insertDate | `DateTime` | Insert Date |
| 84 | insertUser | `Float` | Insert User |
| 85 | internalDeletedflag | `String` | Deleted Flag |
| 86 | internalTransactionCodeSubGroup | `String` | Transaction Code Sub-Group |
| 87 | internalYn | `String` | Internal Y/N |
| 88 | jRNUpdateDate | `Date` | JRN Update Date |
| 89 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 90 | locationID | `String` | Internal ID to uniquely identify the Property |
| 91 | manualPostCoversYn | `String` | Manual Post Covers Y/N |
| 92 | manualPostingAllowedYN | `String` | Manual Posting Allowed YN |
| 93 | maximumAmount | `Float` | Maximum Amount |
| 94 | membershipYN | `String` | Membership YN |
| 95 | minimumAmount | `Float` | Minimum Amount |
| 96 | nonTaxableYn | `String` | Non Taxable Y/N |
| 97 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 98 | ownerRevenueYN | `String` | Owner Rev Y/N |
| 99 | paymentTaxInvoiceYn | `String` | Payment Tax Invoice Y/N |
| 100 | paymentType | `String` | Payment Type |
| 101 | paymentmethodid | `String` | Paymentmethodid |
| 102 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 103 | printReceiptYN | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| 104 | processingType | `String` | Type of process that generated this payment.  IE PaymentCheck out AR or Passerby. |
| 105 | property | `String` | Property |
| 106 | quantityCode | `String` | Quantity Code |
| 107 | repDescription | `String` | Rep Description |
| 108 | repItem | `String` | Reporting Item |
| 109 | repItemName | `String` | Reporting Item Name |
| 110 | repItemOrderby | `Float` | Reporting Item Orderby |
| 111 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 112 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 113 | revenueBucketId | `Float` | Rev Bucket ID |
| 114 | revenueGroupId | `Float` | Rev Gp ID |
| 115 | revenueYN | `String` | Revenue YN |
| 116 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 117 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 118 | rotationRevenueYN | `String` | Rotation Rev Y/N |
| 119 | roundFactorYn | `String` | Round Factor Y/N |
| 120 | serviceRecoveryTrxCode | `String` | Service Recovery Adjustment. |
| 121 | sgDeletedFlag | `String` | Sub-Group Deleted Flag |
| 122 | sgDescription | `String` | Sub-Group Description |
| 123 | sgInsertDate | `DateTime` | Sub-Group Insert Date |
| 124 | sgInsertUser | `Float` | Sub-Group Insert User |
| 125 | sgOrderBy | `Float` | Sub-Group Order By |
| 126 | sgResultIncludedInSumArray | `String` | Sub-Group Result Included In Sum Array |
| 127 | sgRevenuegroupflag | `String` | Sub-Group Revenuegroupflag |
| 128 | sgTaxflag | `String` | Sub-Group Taxflag |
| 129 | sgUpdateDate | `DateTime` | Sub-Group Update Date |
| 130 | sgUpdateUser | `Float` | Sub-Group Update User |
| 131 | subGroupClass1MandatoryYN | `String` | Sg Class 1 Mandatory Y/N |
| 132 | subGroupClass2MandatoryYN | `String` | Sg Class 2 Mandatory Y/N |
| 133 | subGroupFrequentFlyerYN | `String` | Sg Frequent Flyer Y/N |
| 134 | subGroupGroupPointsRedemptionYN | `String` | Sg Gp Points Redemption Y/N |
| 135 | subGroupIndRevenueGroup | `String` | Sg Individual Revenue Gp |
| 136 | subGroupInternalYN | `String` | Sg Internal Y/N |
| 137 | subGroupRepDescription | `String` | Sg Reporting Description |
| 138 | subGroupRepOrderBy | `Float` | Sg Reporting Order By |
| 139 | subGroupTcGroupAndSubgroup | `String` | Sg Transaction Code Group And Subgroup |
| 140 | subGroupTcTransactionType | `String` | Sg Transaction Code Transaction Type |
| 141 | subGroupType | `String` | Sub-Group Type |
| 142 | taxCodeNumber | `Float` | Tax Code Number |
| 143 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 144 | taxYN | `String` | Tax YN |
| 145 | tcBofInterface | `String` | Not Used. |
| 146 | tcBofInterface2 | `String` | Not Used. |
| 147 | tcBofRefCode | `String` | Not Used. |
| 148 | tcBofRefCode2 | `String` | Not Used. |
| 149 | tcResort2 | `String` | Not Used. |
| 150 | tcTransactionType | `String` | Transaction Code Transaction Type |
| 151 | tclCodeDfltCl1 | `String` | Tcl Code Dflt Cl1 |
| 152 | tclCodeDfltCl2 | `String` | Tcl Code Dflt Cl2 |
| 153 | transactionActionId | `Float` | Trx Action ID |
| 154 | transactionCodeDescription | `String` | Transaction Code Description |
| 155 | transactionCodeGroup | `String` | Transaction Code Group |
| 156 | transactionCodeResort | `String` | Not Used. |
| 157 | transactionCodeSubGroup | `String` | Transaction Code Sub-group |
| 158 | transactionCodeType | `String` | Transaction Code Type |
| 159 | transactionType | `String` | Transaction Type |
| 160 | transcodearrangementid | `String` | Transcodearrangementid |
| 161 | transcodeid | `String` | Transcodeid |
| 162 | trxCode | `String` | Trx Code |
| 163 | trxCodeDisplay | `String` | Transaction Code Display |
| 164 | trxServiceType | `String` | Transaction Service Type |
| 165 | trxTaxTypeCode | `String` | Transaction Tax Type Code |
| 166 | uPC | `String` | UPC |
| 167 | updateDate | `DateTime` | Update Date |
| 168 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryRoomClassDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | centralRoomClass | `String` | Central Room Class |
| 3 | centralRoomClassDescription | `String` | Central Room Class Description |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedflag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | inactiveflag | `String` | Inactive Flag |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Code to uniquely identify the Property |
| 16 | repItem | `String` | Reporting Item |
| 17 | repItemName | `String` | Reporting Item Name |
| 18 | repItemOrderby | `Float` | Reporting Item Orderby |
| 19 | repSellSequence | `Float` | Reporting Sell Sequence |
| 20 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 21 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 22 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 23 | roomClass | `String` | Room Class |
| 24 | roomClassDescription | `String` | Room Class Description |
| 25 | roomclassid | `String` | Roomclassid |
| 26 | sellSequence | `Float` | Sell Sequence |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryGregerianCalendarDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | calendar | `String` | Calendar |
| 3 | calendarDescription | `String` | Calendar Description |
| 4 | calendarpkid | `Float` | Calendarpkid |
| 5 | calendartype | `String` | Calendartype |
| 6 | daydesc | `String` | Daydesc |
| 7 | dayenddate | `Date` | Dayenddate |
| 8 | daytimespan | `Float` | Daytimespan |
| 9 | defaultCalendarYn | `String` | Default Calendar Y/N |
| 10 | monthDescription | `String` | Month Description |
| 11 | period | `String` | Period |
| 12 | periodEndDate | `Date` | Period End Date |
| 13 | periodStartDate | `Date` | Period Start Date |
| 14 | periodpkid | `Float` | Periodpkid |
| 15 | periodtimespan | `Float` | Periodtimespan |
| 16 | quarter | `String` | Quarter |
| 17 | quarterDescription | `String` | Quarter Description |
| 18 | quarterEndDate | `Date` | Quarter End Date |
| 19 | quarterStartDate | `Date` | Quarter Start Date |
| 20 | quarterpkid | `Float` | Quarterpkid |
| 21 | quartertimespan | `Float` | Quartertimespan |
| 22 | weekcode | `String` | Weekcode |
| 23 | weekdesc | `String` | Weekdesc |
| 24 | weekenddate | `Date` | Weekenddate |
| 25 | weekkey | `String` | Weekkey |
| 26 | weekstartdate | `Date` | Weekstartdate |
| 27 | weektimespan | `Float` | Weektimespan |
| 28 | year | `Float` | Year |
| 29 | yearDescription | `String` | Year Description |
| 30 | yearEndDate | `Date` | Year End Date |
| 31 | yearStartDate | `Date` | Year Start Date |
| 32 | yearpkid | `Float` | Yearpkid |
| 33 | yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryFiscalCalendarDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | calendar | `String` | Calendar |
| 3 | calendarDescription | `String` | Calendar Description |
| 4 | calendarpkid | `Float` | Calendarpkid |
| 5 | calendartype | `String` | Calendartype |
| 6 | daydesc | `String` | Daydesc |
| 7 | dayenddate | `Date` | Dayenddate |
| 8 | daytimespan | `Float` | Daytimespan |
| 9 | defaultCalendarYn | `String` | Default Calendar Y/N |
| 10 | monthDescription | `String` | Month Description |
| 11 | period | `String` | Period |
| 12 | periodEndDate | `Date` | Period End Date |
| 13 | periodStartDate | `Date` | Period Start Date |
| 14 | periodpkid | `Float` | Periodpkid |
| 15 | periodtimespan | `Float` | Periodtimespan |
| 16 | quarter | `String` | Quarter |
| 17 | quarterDescription | `String` | Quarter Description |
| 18 | quarterEndDate | `Date` | Quarter End Date |
| 19 | quarterStartDate | `Date` | Quarter Start Date |
| 20 | quarterpkid | `Float` | Quarterpkid |
| 21 | quartertimespan | `Float` | Quartertimespan |
| 22 | weekcode | `String` | Weekcode |
| 23 | weekdesc | `String` | Weekdesc |
| 24 | weekenddate | `Date` | Weekenddate |
| 25 | weekkey | `String` | Weekkey |
| 26 | weekstartdate | `Date` | Weekstartdate |
| 27 | weektimespan | `Float` | Weektimespan |
| 28 | year | `Float` | Year |
| 29 | yearDescription | `String` | Year Description |
| 30 | yearEndDate | `Date` | Year End Date |
| 31 | yearStartDate | `Date` | Year Start Date |
| 32 | yearpkid | `Float` | Yearpkid |
| 33 | yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### FinancialTransactionsSummaryPropertyPropertyDetailsType

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

### FinancialTransactionsSummaryQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| trialbalanceDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| trialbalanceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trialbalanceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trialbalanceDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| trialbalanceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trialbalanceDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| trialbalanceDetailsTrxDate | `DateInput!` | Transaction Date<br>`@mandatoryInput` |
| trialbalanceDetailsTrxCode | `StringInput` | Transaction Code |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput` | Property |
| transcodeDetailsTranscodeid | `StringInput` | Transcodeid |
| transcodeDetailsTrxCode | `StringInput` | Trx Code |
| roomclassDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomclassDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomclassDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomclassDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomclassDetailsRoomClass | `StringInput` | Room Class |
| gregeriancalendarDetailsDaykey | `DateInput` | Business Date |
| gregeriancalendarDetailsCalendarcode | `StringInput` | Calendar |
| gregeriancalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| gregeriancalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| gregeriancalendarDetailsQuartercode | `StringInput` | Quarter |
| gregeriancalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| gregeriancalendarDetailsYearcode | `FloatInput` | Year |
| gregeriancalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| fiscalcalendarDetailsDaykey | `DateInput` | Business Date |
| fiscalcalendarDetailsCalendarcode | `StringInput` | Calendar |
| fiscalcalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| fiscalcalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| fiscalcalendarDetailsQuartercode | `StringInput` | Quarter |
| fiscalcalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| fiscalcalendarDetailsYearcode | `FloatInput` | Year |
| fiscalcalendarDetailsYearpkid | `FloatInput` | Yearpkid |
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
- trialbalanceDetailsResort
- trialbalanceDetailsTrxDate


[⬆ Back to Query](#query)

---

## Query Template
```graphql
query financialTransactionsSummary($input: FinancialTransactionsSummaryQueryArgumentsType!) {
  financialTransactionsSummary(input: $input) @stream {
    trialBalanceDetails {
      aRLedgerCredit
      aRLedgerDebit
      arLedgerCreditMonthToDate
      arLedgerCreditYearToDate
      arLedgerDebitMonthToDate
      arLedgerDebitYearToDate
      cARLedgerCreditMonthToDate
      cARLedgerCreditYearToDate
      cARLedgerDebitMonthToDate
      cARLedgerDebitYearToDate
      cDepFolioDebit
      cDepLedgerCreditMonthToDate
      cDepLedgerCreditYearToDate
      cDepLedgerDebitMonthToDate
      cDepLedgerDebitYearToDate
      cExchangeDate
      cExchangeRate
      cGrossAmountMonthToDate
      cGrossAmountYearToDate
      cGuestLedgerCreditMonthToDate
      cGuestLedgerCreditYearToDate
      cGuestLedgerDebitMonthToDate
      cGuestLedgerDebitYearToDate
      cInternalDbPayments
      cNetAmountMonthToDate
      cNetAmountYearToDate
      cNet1Amount
      cNet10Amount
      cNet11Amount
      cNet12Amount
      cNet13Amount
      cNet14Amount
      cNet15Amount
      cNet16Amount
      cNet17Amount
      cNet18Amount
      cNet19Amount
      cNet2Amount
      cNet20Amount
      cNet3Amount
      cNet4Amount
      cNet5Amount
      cNet6Amount
      cNet7Amount
      cNet8Amount
      cNet9Amount
      cOwnerLedgerCredit
      cOwnerLedgerDebit
      cPackageLedgerCreditMonthToDate
      cPackageLedgerCreditYearToDate
      cPackageLedgerDebitMonthToDate
      cPackageLedgerDebitYearToDate
      cPackageLedgerTax
      cRevenueMonthToDate
      cRevenueYearToDate
      cTax1Amount
      cTax2Amount
      cTax10Amount
      cTax11Amount
      cTax12Amount
      cTax13Amount
      cTax14Amount
      cTax15Amount
      cTax16Amount
      cTax17Amount
      cTax18Amount
      cTax19Amount
      cTax20Amount
      cTax3Amount
      cTax4Amount
      cTax5Amount
      cTax6Amount
      cTax7Amount
      cTax8Amount
      cTax9Amount
      cTransactionAmountMonthToDate
      cTransactionAmountYearToDate
      centralARLedgerCredit
      centralARLedgerDebit
      centralDepositLedgerCredit
      centralDepositLedgerDebit
      centralGrossAmount
      centralGuestLedgerCredit
      centralGuestLedgerDebit
      centralInHouseCredit
      centralInHouseDebit
      centralNetAmount
      centralNonRevenueAmount
      centralPackageLedgerCredit
      centralPackageLedgerDebit
      centralRevenueAmount
      centralTransactionAmount
      dSI
      depFolioDebit
      depLedgerCreditMonthToDate
      depLedgerCreditYearToDate
      depLedgerDebitMonthToDate
      depLedgerDebitYearToDate
      depositLedgerCredit
      depositLedgerDebit
      grossAmount
      grossAmountMonthToDate
      grossAmountYearToDate
      guestLedgerCredit
      guestLedgerCreditMonthToDate
      guestLedgerCreditYearToDate
      guestLedgerDebit
      guestLedgerDebitMonthToDate
      guestLedgerDebitYearToDate
      inHouseCredit
      inHouseDebit
      internalDbPayments
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      netAmount
      netAmountMonthToDate
      netAmountYearToDate
      net1Amt
      net10Amt
      net11Amt
      net12Amt
      net13Amt
      net14Amt
      net15Amt
      net16Amt
      net17Amt
      net18Amt
      net19Amt
      net2Amt
      net20Amt
      net3Amt
      net4Amt
      net5Amt
      net6Amt
      net7Amt
      net8Amt
      net9Amt
      nonRevenueAmount
      organizationID
      ownerLedgerCredit
      ownerLedgerDebit
      packageLedgerCredit
      packageLedgerCreditMonthToDate
      packageLedgerCreditYearToDate
      packageLedgerDebit
      packageLedgerDebitMonthToDate
      packageLedgerDebitYearToDate
      packageLedgerTax
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueAmount
      revenueMonthToDate
      revenueYearToDate
      roomClass
      roomclassid
      tax1Amt
      tax2Amt
      tax10Amt
      tax11Amt
      tax12Amt
      tax13Amt
      tax14Amt
      tax15Amt
      tax16Amt
      tax17Amt
      tax18Amt
      tax19Amt
      tax20Amt
      tax3Amt
      tax4Amt
      tax5Amt
      tax6Amt
      tax7Amt
      tax8Amt
      tax9Amt
      transactionAmount
      transactionCodeDescription
      transactionDate
      transcodeid
      trialbalanceid
      trxAmountMonthToDate
      trxAmountYearToDate
      trxCode
    }
    transactionCodeDetails {
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
    roomClassDetails {
      canDeleteYn
      centralRoomClass
      centralRoomClassDescription
      dSI
      deletedflag
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      roomClass
      roomClassDescription
      roomclassid
      sellSequence
      updateDate
      updateUser
    }
    gregerianCalendarDetails {
      businessDate
      calendar
      calendarDescription
      calendarpkid
      calendartype
      daydesc
      dayenddate
      daytimespan
      defaultCalendarYn
      monthDescription
      period
      periodEndDate
      periodStartDate
      periodpkid
      periodtimespan
      quarter
      quarterDescription
      quarterEndDate
      quarterStartDate
      quarterpkid
      quartertimespan
      weekcode
      weekdesc
      weekenddate
      weekkey
      weekstartdate
      weektimespan
      year
      yearDescription
      yearEndDate
      yearStartDate
      yearpkid
      yeartimespan
    }
    fiscalCalendarDetails {
      businessDate
      calendar
      calendarDescription
      calendarpkid
      calendartype
      daydesc
      dayenddate
      daytimespan
      defaultCalendarYn
      monthDescription
      period
      periodEndDate
      periodStartDate
      periodpkid
      periodtimespan
      quarter
      quarterDescription
      quarterEndDate
      quarterStartDate
      quarterpkid
      quartertimespan
      weekcode
      weekdesc
      weekenddate
      weekkey
      weekstartdate
      weektimespan
      year
      yearDescription
      yearEndDate
      yearStartDate
      yearpkid
      yeartimespan
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
trial_balance_details_schema = {
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'arLedgerCreditMonthToDate': pl.Float64,
    'arLedgerCreditYearToDate': pl.Float64,
    'arLedgerDebitMonthToDate': pl.Float64,
    'arLedgerDebitYearToDate': pl.Float64,
    'cARLedgerCreditMonthToDate': pl.Float64,
    'cARLedgerCreditYearToDate': pl.Float64,
    'cARLedgerDebitMonthToDate': pl.Float64,
    'cARLedgerDebitYearToDate': pl.Float64,
    'cDepFolioDebit': pl.Float64,
    'cDepLedgerCreditMonthToDate': pl.Float64,
    'cDepLedgerCreditYearToDate': pl.Float64,
    'cDepLedgerDebitMonthToDate': pl.Float64,
    'cDepLedgerDebitYearToDate': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cGrossAmountMonthToDate': pl.Float64,
    'cGrossAmountYearToDate': pl.Float64,
    'cGuestLedgerCreditMonthToDate': pl.Float64,
    'cGuestLedgerCreditYearToDate': pl.Float64,
    'cGuestLedgerDebitMonthToDate': pl.Float64,
    'cGuestLedgerDebitYearToDate': pl.Float64,
    'cInternalDbPayments': pl.Float64,
    'cNetAmountMonthToDate': pl.Float64,
    'cNetAmountYearToDate': pl.Float64,
    'cNet1Amount': pl.Float64,
    'cNet10Amount': pl.Float64,
    'cNet11Amount': pl.Float64,
    'cNet12Amount': pl.Float64,
    'cNet13Amount': pl.Float64,
    'cNet14Amount': pl.Float64,
    'cNet15Amount': pl.Float64,
    'cNet16Amount': pl.Float64,
    'cNet17Amount': pl.Float64,
    'cNet18Amount': pl.Float64,
    'cNet19Amount': pl.Float64,
    'cNet2Amount': pl.Float64,
    'cNet20Amount': pl.Float64,
    'cNet3Amount': pl.Float64,
    'cNet4Amount': pl.Float64,
    'cNet5Amount': pl.Float64,
    'cNet6Amount': pl.Float64,
    'cNet7Amount': pl.Float64,
    'cNet8Amount': pl.Float64,
    'cNet9Amount': pl.Float64,
    'cOwnerLedgerCredit': pl.Float64,
    'cOwnerLedgerDebit': pl.Float64,
    'cPackageLedgerCreditMonthToDate': pl.Float64,
    'cPackageLedgerCreditYearToDate': pl.Float64,
    'cPackageLedgerDebitMonthToDate': pl.Float64,
    'cPackageLedgerDebitYearToDate': pl.Float64,
    'cPackageLedgerTax': pl.Float64,
    'cRevenueMonthToDate': pl.Float64,
    'cRevenueYearToDate': pl.Float64,
    'cTax1Amount': pl.Float64,
    'cTax2Amount': pl.Float64,
    'cTax10Amount': pl.Float64,
    'cTax11Amount': pl.Float64,
    'cTax12Amount': pl.Float64,
    'cTax13Amount': pl.Float64,
    'cTax14Amount': pl.Float64,
    'cTax15Amount': pl.Float64,
    'cTax16Amount': pl.Float64,
    'cTax17Amount': pl.Float64,
    'cTax18Amount': pl.Float64,
    'cTax19Amount': pl.Float64,
    'cTax20Amount': pl.Float64,
    'cTax3Amount': pl.Float64,
    'cTax4Amount': pl.Float64,
    'cTax5Amount': pl.Float64,
    'cTax6Amount': pl.Float64,
    'cTax7Amount': pl.Float64,
    'cTax8Amount': pl.Float64,
    'cTax9Amount': pl.Float64,
    'cTransactionAmountMonthToDate': pl.Float64,
    'cTransactionAmountYearToDate': pl.Float64,
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralDepositLedgerCredit': pl.Float64,
    'centralDepositLedgerDebit': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralGuestLedgerCredit': pl.Float64,
    'centralGuestLedgerDebit': pl.Float64,
    'centralInHouseCredit': pl.Float64,
    'centralInHouseDebit': pl.Float64,
    'centralNetAmount': pl.Float64,
    'centralNonRevenueAmount': pl.Float64,
    'centralPackageLedgerCredit': pl.Float64,
    'centralPackageLedgerDebit': pl.Float64,
    'centralRevenueAmount': pl.Float64,
    'centralTransactionAmount': pl.Float64,
    'dSI': pl.Int64,
    'depFolioDebit': pl.Float64,
    'depLedgerCreditMonthToDate': pl.Float64,
    'depLedgerCreditYearToDate': pl.Float64,
    'depLedgerDebitMonthToDate': pl.Float64,
    'depLedgerDebitYearToDate': pl.Float64,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'grossAmount': pl.Float64,
    'grossAmountMonthToDate': pl.Float64,
    'grossAmountYearToDate': pl.Float64,
    'guestLedgerCredit': pl.Float64,
    'guestLedgerCreditMonthToDate': pl.Float64,
    'guestLedgerCreditYearToDate': pl.Float64,
    'guestLedgerDebit': pl.Float64,
    'guestLedgerDebitMonthToDate': pl.Float64,
    'guestLedgerDebitYearToDate': pl.Float64,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'internalDbPayments': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'netAmount': pl.Float64,
    'netAmountMonthToDate': pl.Float64,
    'netAmountYearToDate': pl.Float64,
    'net1Amt': pl.Float64,
    'net10Amt': pl.Float64,
    'net11Amt': pl.Float64,
    'net12Amt': pl.Float64,
    'net13Amt': pl.Float64,
    'net14Amt': pl.Float64,
    'net15Amt': pl.Float64,
    'net16Amt': pl.Float64,
    'net17Amt': pl.Float64,
    'net18Amt': pl.Float64,
    'net19Amt': pl.Float64,
    'net2Amt': pl.Float64,
    'net20Amt': pl.Float64,
    'net3Amt': pl.Float64,
    'net4Amt': pl.Float64,
    'net5Amt': pl.Float64,
    'net6Amt': pl.Float64,
    'net7Amt': pl.Float64,
    'net8Amt': pl.Float64,
    'net9Amt': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'organizationID': pl.Int64,
    'ownerLedgerCredit': pl.Float64,
    'ownerLedgerDebit': pl.Float64,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerCreditMonthToDate': pl.Float64,
    'packageLedgerCreditYearToDate': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageLedgerDebitMonthToDate': pl.Float64,
    'packageLedgerDebitYearToDate': pl.Float64,
    'packageLedgerTax': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueAmount': pl.Float64,
    'revenueMonthToDate': pl.Float64,
    'revenueYearToDate': pl.Float64,
    'roomClass': pl.Utf8,
    'roomclassid': pl.Utf8,
    'tax1Amt': pl.Float64,
    'tax2Amt': pl.Float64,
    'tax10Amt': pl.Float64,
    'tax11Amt': pl.Float64,
    'tax12Amt': pl.Float64,
    'tax13Amt': pl.Float64,
    'tax14Amt': pl.Float64,
    'tax15Amt': pl.Float64,
    'tax16Amt': pl.Float64,
    'tax17Amt': pl.Float64,
    'tax18Amt': pl.Float64,
    'tax19Amt': pl.Float64,
    'tax20Amt': pl.Float64,
    'tax3Amt': pl.Float64,
    'tax4Amt': pl.Float64,
    'tax5Amt': pl.Float64,
    'tax6Amt': pl.Float64,
    'tax7Amt': pl.Float64,
    'tax8Amt': pl.Float64,
    'tax9Amt': pl.Float64,
    'transactionAmount': pl.Float64,
    'transactionCodeDescription': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transcodeid': pl.Utf8,
    'trialbalanceid': pl.Float64,
    'trxAmountMonthToDate': pl.Float64,
    'trxAmountYearToDate': pl.Float64,
    'trxCode': pl.Utf8,
}
```
```python
transaction_code_details_schema = {
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
room_class_details_schema = {
    'canDeleteYn': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomclassid': pl.Utf8,
    'sellSequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
gregerian_calendar_details_schema = {
    'businessDate': pl.Utf8,
    'calendar': pl.Utf8,
    'calendarDescription': pl.Utf8,
    'calendarpkid': pl.Float64,
    'calendartype': pl.Utf8,
    'daydesc': pl.Utf8,
    'dayenddate': pl.Utf8,
    'daytimespan': pl.Float64,
    'defaultCalendarYn': pl.Utf8,
    'monthDescription': pl.Utf8,
    'period': pl.Utf8,
    'periodEndDate': pl.Utf8,
    'periodStartDate': pl.Utf8,
    'periodpkid': pl.Float64,
    'periodtimespan': pl.Float64,
    'quarter': pl.Utf8,
    'quarterDescription': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterStartDate': pl.Utf8,
    'quarterpkid': pl.Float64,
    'quartertimespan': pl.Float64,
    'weekcode': pl.Utf8,
    'weekdesc': pl.Utf8,
    'weekenddate': pl.Utf8,
    'weekkey': pl.Utf8,
    'weekstartdate': pl.Utf8,
    'weektimespan': pl.Float64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearStartDate': pl.Utf8,
    'yearpkid': pl.Float64,
    'yeartimespan': pl.Float64,
}
```
```python
fiscal_calendar_details_schema = {
    'businessDate': pl.Utf8,
    'calendar': pl.Utf8,
    'calendarDescription': pl.Utf8,
    'calendarpkid': pl.Float64,
    'calendartype': pl.Utf8,
    'daydesc': pl.Utf8,
    'dayenddate': pl.Utf8,
    'daytimespan': pl.Float64,
    'defaultCalendarYn': pl.Utf8,
    'monthDescription': pl.Utf8,
    'period': pl.Utf8,
    'periodEndDate': pl.Utf8,
    'periodStartDate': pl.Utf8,
    'periodpkid': pl.Float64,
    'periodtimespan': pl.Float64,
    'quarter': pl.Utf8,
    'quarterDescription': pl.Utf8,
    'quarterEndDate': pl.Utf8,
    'quarterStartDate': pl.Utf8,
    'quarterpkid': pl.Float64,
    'quartertimespan': pl.Float64,
    'weekcode': pl.Utf8,
    'weekdesc': pl.Utf8,
    'weekenddate': pl.Utf8,
    'weekkey': pl.Utf8,
    'weekstartdate': pl.Utf8,
    'weektimespan': pl.Float64,
    'year': pl.Float64,
    'yearDescription': pl.Utf8,
    'yearEndDate': pl.Utf8,
    'yearStartDate': pl.Utf8,
    'yearpkid': pl.Float64,
    'yeartimespan': pl.Float64,
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