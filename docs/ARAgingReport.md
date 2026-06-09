# ARAgingReport
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

| Field | Type | Description |
| --- | --- | --- |
| aRAgingReportDetails | [`ARAgingReportARAgingReportDetailsType`](#aragingreportaragingreportdetailstype) | AR Aging Report |
| transactionCodeDetails | [`ARAgingReportTransactionCodeDetailsType`](#aragingreporttransactioncodedetailstype) | Transaction Code |
| folioDetails | [`ARAgingReportFolioDetailsType`](#aragingreportfoliodetailstype) | Folio Details |
| financialTransactionDetails | [`ARAgingReportFinancialTransactionDetailsType`](#aragingreportfinancialtransactiondetailstype) | Financial Transaction |
| accountDetails | [`ARAgingReportAccountDetailsType`](#aragingreportaccountdetailstype) | Account Details |
| calendarPeriodDayDetails | [`ARAgingReportCalendarPeriodDayDetailsType`](#aragingreportcalendarperioddaydetailstype) | Calendar Period Daily Details |
| financialPeriodDayDetails | [`ARAgingReportFinancialPeriodDayDetailsType`](#aragingreportfinancialperioddaydetailstype) | Financial Period Daily Details |
| aRLedgerDetails | [`ARAgingReportARLedgerDetailsType`](#aragingreportarledgerdetailstype) | AR Ledger |
| invoiceHeaderDetails | [`ARAgingReportInvoiceHeaderDetailsType`](#aragingreportinvoiceheaderdetailstype) | Invoice Header Details |
| propertyPropertyDetails | [`ARAgingReportPropertyPropertyDetailsType`](#aragingreportpropertypropertydetailstype) | Resort Details |
| aRAgingReportRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ARAgingReportARAgingReportDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRLedgerDebit | `Float` | AR Ledger Debit |
| accountCode | `Float` | Account Code |
| accountName | `String` | Account Name |
| accountNumber | `String` | NOT IN USE |
| accountType | `String` | Account Type |
| accountid | `Float` | Accountid |
| age1 | `Float` | Age 1 |
| age2 | `Float` | Age 2 |
| age3 | `Float` | Age 3 |
| age4 | `Float` | Age 4 |
| age5 | `Float` | Age 5 |
| age6 | `Float` | Age 6 |
| agingbucket | `Float` | Agingbucket |
| arTransferDate | `Date` | AR Transfer Date |
| billNumber | `Float` | Bill Number |
| billingContactName | `String` | Contact information. |
| businessDate | `Date` | Business Date |
| cARLedgerCredit | `Float` | Central Ar Led Credit |
| cARLedgerDebit | `Float` | Central Ar Led Debit |
| cAmount | `Float` | Central Amount |
| cContractCurrencyDifference | `Float` | Central Contract Curr Diff |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cOrganizationAmount | `Float` | Central Org Amt |
| cOrganizationAmountContract | `Float` | Central Org Amt Contract |
| cOrganizationAmountCurrencyDifference | `Float` | Central Org Amt Curr Diff |
| cOrganizationAmountParallel | `Float` | Central Org Amt Parallel |
| cParallelCurrencyDifference | `Float` | Central Parallel Curr Diff |
| centralAccountType | `String` | Central Account Type |
| centralOpenARTransactionAmount | `Float` | Central Open AR Transaction Amount |
| checkOutDate | `Date` | Date on which the guest was checked out. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateForAging | `String` | Date the aging should begin |
| fintransid | `Float` | Fintransid |
| folioNo | `Float` | Folio Number |
| folioid | `Float` | Folioid |
| internalCheckoutDate | `Date` | Checkout Date |
| invoiceAge | `Float` | Invoice Age |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNo | `Float` | Invoice Number |
| invoiceNumber | `Float` | Invoice Number |
| invoiceStatus | `String` | Invoice Status |
| invoiceamount | `Float` | Invoiceamount |
| invoiceid | `Float` | Invoiceid |
| invoiceprofileid | `Float` | Invoiceprofileid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterInvoiceNo | `Float` | Compressed Invoice No for which multiple invoices have been compressed to. |
| nameId | `Float` | Name ID |
| openARTransactionAmount | `Float` | Open AR Transaction Amount |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerRoom | `String` | The owner room where this invoice/payment belongs to. |
| ownerroomid | `String` | Ownerroomid |
| pmsBusinessDate | `Date` | Pms Business Date |
| postDate | `Date` | Date + time the phone charge was posted. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| room | `String` | Room |
| roomid | `String` | Roomid |
| transactionFromAcct | `Float` | Trns From Account |
| transactionToAcct | `Float` | Trns To Account |
| transactionid | `Float` | Transactionid |
| transcodeid | `String` | Transcodeid |
| transferfromaccountid | `Float` | Transferfromaccountid |
| transfertoaccountid | `Float` | Transfertoaccountid |
| trxCode | `String` | Transaction Code |
| trxDate | `Date` | Transaction Date |
| trxNumber | `Float` | Transaction No |

[⬆ Back to Query](#query)

---

### ARAgingReportTransactionCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRLedgerPaymentsYN | `String` | AR Ledger Payments YN |
| aRNameId | `Float` | Ar Name ID |
| accountNumber | `String` | Account Number |
| accountingCode | `String` | Accounting Code |
| acctrecvprofileid | `Float` | Acctrecvprofileid |
| adjTrxCode | `String` | Adj Trx Code |
| adjtranscodeid | `String` | Adjtranscodeid |
| arrangeCode | `String` | Arrange Code |
| arrangementCode | `String` | Arrangement Code |
| cDefaultPrice | `Float` | Central Default Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cExportBucket | `Float` | Central Export Bucket |
| cMaxAmount | `Float` | Central Max Amt |
| cMinimumAmount | `Float` | Central Min Amt |
| cCCode | `String` | CC Code |
| cRSTaxDesc | `String` | Crs Tax Description |
| cashTransactionCodeYN | `String` | Cash Transaction Code YN |
| ccType | `String` | Cc Type |
| centalSubgroup | `String` | Cental Subgroup |
| centralAdjustmentTransactionCode | `String` | Central Adjustment Transaction Code |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionCodeGroup | `String` | Central Transaction Code Group |
| chargeDeferredUntilCheckoutYN | `String` | Charge Deferred Until Checkout YN |
| checkNumberMandatoryYN | `String` | Check Number Mandatory YN |
| class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| commissionCode | `Float` | Commission Code |
| compNightsYn | `String` | Comp Nights Y/N |
| compPaymentYn | `String` | Comp Payment Y/N |
| complimentaryYN | `String` | Complimentary YN |
| corpPropFlag | `String` | Corp Prop Flag |
| corporateDescription | `String` | Corporate Description |
| crossPostingDepositYN | `String` | To indicate that the transaction code can be used as a Deposit Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| crossPostingPaymentYN | `String` | To indicate that the transaction code can be used as a Payment Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| crossPostingSalesYN | `String` | To indicate that the transaction code can be used as a Sales Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyPlanFolio | `Float` | Daily Plan Folio |
| dedOwnerRevenueYN | `String` | Ded Owner Rev Y/N |
| defaultPrice | `Float` | Default Price |
| deletedFlag | `String` | Deleted Flag |
| depositLedgerPaymentsYN | `String` | Deposit Ledger Payments YN |
| depositPostingOnlyYn | `String` | Deposit Posting Only Y/N |
| depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| eInvoiceYn | `String` | E Invoice Y/N |
| expenseFolio | `Float` | Expense Folio |
| exportBucket | `Float` | Export Bucket |
| externalPaymentCode | `String` | External Payment Code |
| fiscalPaymentYn | `String` | Fiscal Payment Y/N |
| fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| foreignCurrencyID | `String` | Foreign Currency ID |
| gDeletedFlag | `String` | Group Deleted Flag |
| gDescription | `String` | Group Description |
| gInsertDate | `DateTime` | Group Insert Date |
| gInsertUser | `Float` | Group Insert User |
| gOrderBy | `Float` | Group Order By |
| gRepDescription | `String` | Group Rep Description |
| gResultIncludedInSumArray | `String` | Group Result Included In Sum Array |
| gRevenuegroupflag | `String` | Group Revenuegroupflag |
| gTctClassType1 | `String` | Group Tct Class Type1 |
| gTctClassType2 | `String` | Group Tct Class Type2 |
| gUpdateDate | `DateTime` | Group Update Date |
| gUpdateUser | `Float` | Group Update User |
| group | `String` | Group |
| groupClass1MandatoryYN | `String` | G Class 1 Mandatory Y/N |
| groupClass2MandatoryYN | `String` | G Class 2 Mandatory Y/N |
| groupFolio | `Float` | Group Folio |
| groupIndRevenueGroup | `String` | G Individual Revenue Gp |
| groupInternalYN | `String` | G Internal Y/N |
| groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| groupRepItem | `String` | G Reporting Item |
| groupRepItemName | `String` | G Reporting Item Name |
| groupRepItemOrderby | `Float` | G Reporting Item Orderby |
| groupRepOrderBy | `Float` | G Reporting Order By |
| groupRepUpdateDate | `DateTime` | G Reporting Updatedate |
| groupTcTransactionType | `String` | G Transaction Code Transaction Type |
| guestLedgerPaymentsYN | `String` | Guest Ledger Payments YN |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| includeIn8300Yn | `String` | Include In 8300 Y/N |
| includeInDepositRuleYn | `String` | Include In Deposit Rule Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalTransactionCodeSubGroup | `String` | Transaction Code Sub-Group |
| internalYn | `String` | Internal Y/N |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualPostCoversYn | `String` | Manual Post Covers Y/N |
| manualPostingAllowedYN | `String` | Manual Posting Allowed YN |
| maximumAmount | `Float` | Maximum Amount |
| membershipYN | `String` | Membership YN |
| minimumAmount | `Float` | Minimum Amount |
| nonTaxableYn | `String` | Non Taxable Y/N |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerRevenueYN | `String` | Owner Rev Y/N |
| paymentTaxInvoiceYn | `String` | Payment Tax Invoice Y/N |
| paymentType | `String` | Payment Type |
| paymentmethodid | `String` | Paymentmethodid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printReceiptYN | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| processingType | `String` | Type of process that generated this payment.  IE PaymentCheck out AR or Passerby. |
| property | `String` | Property |
| quantityCode | `String` | Quantity Code |
| repDescription | `String` | Rep Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| revenueBucketId | `Float` | Rev Bucket ID |
| revenueGroupId | `Float` | Rev Gp ID |
| revenueYN | `String` | Revenue YN |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rotationRevenueYN | `String` | Rotation Rev Y/N |
| roundFactorYn | `String` | Round Factor Y/N |
| serviceRecoveryTrxCode | `String` | Service Recovery Adjustment. |
| sgDeletedFlag | `String` | Sub-Group Deleted Flag |
| sgDescription | `String` | Sub-Group Description |
| sgInsertDate | `DateTime` | Sub-Group Insert Date |
| sgInsertUser | `Float` | Sub-Group Insert User |
| sgOrderBy | `Float` | Sub-Group Order By |
| sgResultIncludedInSumArray | `String` | Sub-Group Result Included In Sum Array |
| sgRevenuegroupflag | `String` | Sub-Group Revenuegroupflag |
| sgTaxflag | `String` | Sub-Group Taxflag |
| sgUpdateDate | `DateTime` | Sub-Group Update Date |
| sgUpdateUser | `Float` | Sub-Group Update User |
| subGroupClass1MandatoryYN | `String` | Sg Class 1 Mandatory Y/N |
| subGroupClass2MandatoryYN | `String` | Sg Class 2 Mandatory Y/N |
| subGroupFrequentFlyerYN | `String` | Sg Frequent Flyer Y/N |
| subGroupGroupPointsRedemptionYN | `String` | Sg Gp Points Redemption Y/N |
| subGroupIndRevenueGroup | `String` | Sg Individual Revenue Gp |
| subGroupInternalYN | `String` | Sg Internal Y/N |
| subGroupRepDescription | `String` | Sg Reporting Description |
| subGroupRepOrderBy | `Float` | Sg Reporting Order By |
| subGroupTcGroupAndSubgroup | `String` | Sg Transaction Code Group And Subgroup |
| subGroupTcTransactionType | `String` | Sg Transaction Code Transaction Type |
| subGroupType | `String` | Sub-Group Type |
| taxCodeNumber | `Float` | Tax Code Number |
| taxInclusiveYN | `String` | Tax Inclusive YN |
| taxYN | `String` | Tax YN |
| tcBofInterface | `String` | Not Used. |
| tcBofInterface2 | `String` | Not Used. |
| tcBofRefCode | `String` | Not Used. |
| tcBofRefCode2 | `String` | Not Used. |
| tcResort2 | `String` | Not Used. |
| tcTransactionType | `String` | Transaction Code Transaction Type |
| tclCodeDfltCl1 | `String` | Tcl Code Dflt Cl1 |
| tclCodeDfltCl2 | `String` | Tcl Code Dflt Cl2 |
| transactionActionId | `Float` | Trx Action ID |
| transactionCodeDescription | `String` | Transaction Code Description |
| transactionCodeGroup | `String` | Transaction Code Group |
| transactionCodeResort | `String` | Not Used. |
| transactionCodeSubGroup | `String` | Transaction Code Sub-group |
| transactionCodeType | `String` | Transaction Code Type |
| transactionType | `String` | Transaction Type |
| transcodearrangementid | `String` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| trxCode | `String` | Trx Code |
| trxCodeDisplay | `String` | Transaction Code Display |
| trxServiceType | `String` | Transaction Service Type |
| trxTaxTypeCode | `String` | Transaction Tax Type Code |
| uPC | `String` | UPC |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportFolioDetailsType

| Field | Type | Description |
| --- | --- | --- |
| billGenerationDate | `Date` | Bill Generation Date |
| billNumber | `Float` | Bill Number |
| businessdate | `Date` | Businessdate |
| cashierId | `Float` | Cashier ID |
| checkExchangeReceiptNumber | `Float` | Check Exchange Receipt Number |
| currencyExchangeReceiptNumber | `Float` | Internal number to represent the currency exchange receipt number. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| folioNo | `Float` | Folio Number |
| folioSeqNumber | `Float` | Unique number to identify the entry. |
| folioStatus | `String` | The status to identify whether a guest is getting checked out. |
| folioStyle | `String` | Folio Style |
| folioType | `String` | Identify the FOLIO TYPE. |
| folioView | `Float` | Folio View |
| folioid | `Float` | Folioid |
| frontOfficeDate | `Date` | Date when folio is created |
| fullFolioNo | `String` | Full Folio Number |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalUpdatedate | `DateTime` | Update Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| name | `String` | Name |
| nameId | `Float` | Name ID |
| numberReprints | `Float` | Number Reprints. |
| numberOfPersons | `Float` | No of persons currently using the account |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneDetails | `String` | Phone Details |
| postitNo | `Float` | Postit Number |
| postityn | `String` | Postityn |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processIdent | `String` | Identifying the process |
| profileid | `Float` | Profileid |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| resvdeptrno | `Float` | Resvdeptrno |
| resvenddate | `Date` | Resvenddate |
| revisionNumber | `Float` | Revision Number |
| state | `String` | State |
| templatePath | `String` | Template path for report defination |
| timestamp | `Date` | Date on which the folio is created or date of the checkout. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportFinancialTransactionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aRLedgerCredit | `Float` | AR Ledger Credit |
| aRLedgerDebit | `Float` | AR Ledger Debit |
| aRState | `String` | AR State |
| aRTransferDate | `Date` | AR Transfer Date |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountCode | `Float` | Account Code |
| accountName | `String` | Account Name |
| accountNumber | `String` | Account Number |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| adjustmentYN | `String` | Adjustment YN |
| advGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| advancedGeneratedAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| advgentranscodeid | `String` | Advgentranscodeid |
| allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| apartmentStyleBillingType | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| approvalCode | `String` | Approval Code |
| approvalDate | `Date` | Approval Date |
| approvalStatus | `String` | Approval Status |
| arrangementCode | `String` | Arrangement Code |
| arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| arrangementId | `Float` | Arrangement ID |
| articleId | `Float` | Article ID |
| associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| authemployeeid | `Float` | Authemployeeid |
| authorizer | `String` | Authorizer |
| autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| autoSettleYn | `String` | Auto Settle Y/N |
| billingEventID | `Float` | Billing Event ID |
| bonusCheckId | `Float` | Bonus Check ID |
| bucketCode | `String` | Bucket code related to this redemption. |
| bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| businessDate | `Date` | Business Date |
| cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| cChangeDue | `Float` | Central Change Due |
| cContractGrossAmount | `Float` | Central Contract Gross Amount |
| cContractGuestCredit | `Float` | Central Contract Guest Credit |
| cContractGuestDebit | `Float` | Central Contract Guest Debit |
| cContractNetAmount | `Float` | Central Contract Net Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| cPackageAllowance | `Float` | Central Package Allowance |
| cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| cParallelNetAmount | `Float` | Central Parallel Net Amount |
| cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| cTaxRate | `Float` | Central Tax Rate |
| cVatAmount | `Float` | Central Vat Amount |
| cCApproval | `String` | CC Approval Code |
| calculatePointsYN | `String` | Calculate Points YN |
| cashBagNumber | `String` | Cash Bag Number |
| cashier | `String` | Cashier |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierID | `Float` | Cashier ID |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| centralAdvancedGeneratedTransactionCode | `String` | Central Advanced Generated Transaction Code |
| centralCashierCredit | `Float` | Central Cashier Credit |
| centralCashierDebit | `Float` | Central Cashier Debit |
| centralCreditCardSurcharge | `Float` | Central Credit Card Surcharge |
| centralDepositAmountPaid | `Float` | Central Deposit Amount Paid |
| centralDepositLedgerCredit | `Float` | Central Deposit Ledger Credit |
| centralDepositLedgerDebit | `Float` | Central Deposit Ledger Debit |
| centralGrossAmount | `Float` | Central Gross Amount |
| centralGuestAccountLedgerCredit | `Float` | Central Guest Account Ledger Credit |
| centralGuestAccountLedgerDebit | `Float` | Central Guest Account Ledger Debit |
| centralInHouseCredit | `Float` | Central In-House Credit |
| centralInHouseDebit | `Float` | Central In-House Debit |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralNetAmount | `Float` | Central Net Amount |
| centralNonRevenueAmount | `Float` | Central Non Revenue Amount |
| centralPackage | `String` | Central Package |
| centralPackageLedgerCredit | `Float` | Central Package Ledger Credit |
| centralPackageLedgerDebit | `Float` | Central Package Ledger Debit |
| centralPostedAmountInBaseCurrency | `Float` | Central Posted Amount in Base Currency |
| centralPricePerUnit | `Float` | Central Price Per Unit |
| centralRevenueIncluded | `Float` | Central Revenue Included |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| centralTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| centralTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| chainCode | `String` | Chain Code |
| changeDue | `Float` | Change Due |
| checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| checkNumber | `String` | Check Number |
| closureNumber | `Float` | Closure Number |
| collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| comments | `String` | Comments |
| compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| compTypeCode | `String` | Comp Type Code |
| complinktranscodeid | `String` | Complinktranscodeid |
| compressedYn | `String` | Compressed Y/N |
| contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| couponNo | `String` | Coupon Number |
| covers | `String` | Covers |
| creditCardId | `Float` | Credit Card ID |
| creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| creditYN | `String` | Credit YN |
| currencyCode | `String` | Currency Code |
| customChargeDate | `Date` | This is the custom charge date populated by Property Charge Adjustments. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debitYN | `String` | Debit YN |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| depositLedgerCredit | `Float` | Deposit Ledger Credit |
| depositLedgerDebit | `Float` | Deposit Ledger Debit |
| depositTransactionId | `String` | Deposit Transaction ID |
| depositlinkfintransid | `Float` | Depositlinkfintransid |
| displayflag | `String` | Displayflag |
| dualCurrency | `String` | Cuurency code for parrallel currency. |
| dualCurrencyGrossAmount | `Float` | Dual Currency Gross Amount |
| dualCurrencyGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| dualCurrencyGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| dualCurrencyNetAmount | `Float` | Dual Currency Net Amount |
| effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| exchangeDate | `Date` | Exchange Date |
| exchangeDifferenceYN | `String` | Exchange Difference YN |
| exchangeRate | `Float` | Exchange Rate |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| extTransactionId | `String` | Transaction ID from external system. |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| financialTransactionCodeType | `String` | Financial Transaction Code Type |
| fintransactionid | `Float` | Fintransactionid |
| fintransid | `Float` | Fintransid |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fixedChargesYN | `String` | Fixed Charges YN |
| folioNo | `Float` | Folio Number |
| folioType | `String` | Folio Type |
| folioTypeJoin | `String` | Folio Type Join |
| folioView | `Float` | Folio View |
| folioid | `Float` | Folioid |
| foreignCurrencyID | `String` | Foreign Currency ID |
| forexCommAmount | `Float` | Foreign Exchange commission amount. |
| forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| fromReservationId | `Float` | From Resv ID |
| ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| genCashierId | `Float` | General Cashier Id. |
| gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| grossAmount | `Float` | Gross Amount |
| groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| guestCountry | `String` | Guest Country |
| guestCountryCode | `String` | Guest Country Code |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| inHouseCredit | `Float` | In-House Credit |
| inHouseDebit | `Float` | In-House Debit |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| installments | `Float` | Installments |
| internalArticleid | `Float` | Articleid |
| internalBusinessdate | `Date` | Businessdate |
| internalCashierid | `Float` | Cashierid |
| internalWindowId | `Float` | Internal Window ID |
| internalYN | `String` | Internal YN |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNumber | `Float` | Invoice Number |
| invoiceType | `String` | Invoice Type |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkTrxNumber | `Float` | Link Transaction No |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketid | `String` | Marketid |
| membershipID | `Float` | Membership ID |
| mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| netAmount | `Float` | Net Amount |
| nonRevenueAmount | `Float` | Non Revenue Amount |
| numberDialed | `String` | Number Dialed. |
| oTransactionDesc | `String` | Transaction Description. |
| oVOSCurrency | `String` | Currency code for contract currency. |
| oVOSGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| oVOSGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| oVOSGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| oVOSNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| onHoldYN | `String` | On Hold YN |
| orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalBillNumber | `Float` | Stores original bill number after void. |
| originalFolioNumber | `String` | Stores original folio type after void. |
| originalReservationNameId | `Float` | Original Resv Name ID |
| originalRoom | `String` | Original Room |
| originalresvid | `Float` | Originalresvid |
| othersBagNumber | `String` | Others Bag Number |
| package | `String` | Package |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| packageLedgerDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| packagelinkfintransid | `Float` | Packagelinkfintransid |
| parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| parentfintransid | `Float` | Parentfintransid |
| passerByName | `String` | Passerby Name. |
| paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| paymentType | `String` | Payment Type |
| paymentsReference | `String` | Payments-Reference |
| postedAmountInBaseCurrency | `Float` | Posted Amount in Base Currency |
| postedAmountInTransactionCurrency | `Float` | Posted Amount in Transaction Currency |
| postingDate | `DateTime` | Posting Date |
| postingRhythm | `String` | Posting Rhythm |
| postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| postitNo | `Float` | Postit Number |
| postitYn | `String` | Postit Y/N |
| pricePerUnit | `Float` | Price Per Unit |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processed8300YN | `String` | Processed 8300 YN |
| productid | `String` | Productid |
| profileid | `Float` | Profileid |
| profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| proformaYn | `String` | Proforma Y/N |
| property | `String` | Code to uniquely identify the Property |
| propertyBillPrefix | `String` | Property Bill Prefix |
| quantity | `Float` | Quantity |
| queueName | `String` | Queue Name |
| rateCode | `String` | Rate Code |
| ratecodeid | `String` | Ratecodeid |
| receiptNumber | `Float` | Receipt Number |
| receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| repTransactionCode | `String` | Reporting Trx Code |
| repTransactionCodeGroup | `String` | Reporting Tc Group |
| repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationid | `Float` | Reservationid |
| resvenddate | `Date` | Resvenddate |
| revenueAmount | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| revisionNo | `Float` | Revision Number |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomClass | `String` | Room Class |
| roomNts | `Float` | Room Nts |
| roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| roomNumber | `String` | Room Number |
| roomid | `String` | Roomid |
| roundFactorYn | `String` | Round Factor Y/N |
| roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| routedYn | `String` | Indicates if the transaction has been routed. |
| routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| serviceChargeIncludedRevenueTaxPercent | `Float` | Service Charge Included Revenue Tax Percent |
| serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| settlementFlag | `String` | Settlement Flag |
| sourceCode | `String` | Source Code |
| sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceid | `String` | Sourceid |
| splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| supplement | `String` | Supplement |
| taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| targetResort | `String` | Target Property |
| targetlocationid | `String` | Targetlocationid |
| taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| taxElements | `String` | Tax Elements |
| taxGeneratedYN | `String` | Tax Generated YN |
| taxInclusiveYN | `String` | Tax Inclusive YN |
| taxInvNumber | `String` | Tax Invoice No |
| taxRate | `Float` | Tax Rate |
| taxRateType | `String` | Tax Rate Type |
| tcGroup | `String` | Transaction Code Group |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tclCode1 | `String` | Class1 Code. |
| tclCode2 | `String` | Class1 Code. |
| thresholdDiversionId | `Float` | Threshold Diversion ID |
| thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| thresholdEntityType | `String` | Threshold Entity Type |
| thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| toReservationNameId | `Float` | To Resv Name ID |
| tranActionId | `Float` | Tran Action ID |
| transactionActivityDate | `Date` | Transaction Activity Date |
| transactionCode | `String` | Transaction Code |
| transactionCodeDescription | `String` | Transaction Code Description |
| transactionCodeGroupDesc | `String` | Tc Group Description |
| transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| transactionDate | `Date` | Transaction Date |
| transactionNumberAddedBy | `Float` | Transaction Number Added By |
| transactionPostingDate | `Date` | Transaction Posting Date |
| transactionPostingTime | `String` | Time transaction was posted. |
| transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| transactionStatus | `String` | Transaction Status |
| transactionType | `String` | Transaction Type |
| transactionFromAccount | `Float` | Transaction from Account |
| transactionToAccount | `Float` | Transaction to Account |
| transactionsReasonCode | `String` | Transactions-Reason Code |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transferfromaccountid | `Float` | Transferfromaccountid |
| transferfromresvid | `Float` | Transferfromresvid |
| transfertoaccountid | `Float` | Transfertoaccountid |
| transfertoresvid | `Float` | Transfertoresvid |
| travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| trxCode | `String` | Transaction Code |
| trxNo | `Float` | Trx Number |
| trxNoAgainstPackage | `Float` | Trx Number Against Package |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberHeader | `Float` | Transaction No Header |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| trxType | `String` | Transaction type: possible values: [CACH]. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| userID | `Float` | User ID |
| vatAmount | `Float` | Tax Amount for Commission. |
| vatOffsetYn | `String` | Vat Offset Y/N |
| vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### ARAgingReportAccountDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountCode | `Float` | Account Code |
| accountCreditLimitYn | `String` | Indicates if a Credit Limit amount will be required "Y" will take precedence over the credit limit amount on Profile level. |
| accountName | `String` | Account Name |
| accountNumber | `String` | Account Number |
| accountSname | `String` | Name on the account in upper case. |
| accountStatus | `String` | Status of an account. (Normal Restricted) |
| accountStatusMsg | `String` | Message prompt when the AR Account is defined as restricted. |
| accountType | `String` | Account Type |
| accountTypeFlag | `String` | Account Type Flag |
| accountTypeId | `Float` | Account Type ID |
| accountid | `Float` | Accountid |
| acctflagreasonid | `String` | Acctflagreasonid |
| activeYN | `String` | Active YN |
| addressId | `Float` | Address ID |
| address1 | `String` | Address1 |
| address2 | `String` | Address2 |
| address3 | `String` | Address3 |
| age | `Float` | Age. |
| agent | `String` | Agent |
| agentUserId | `Float` | Application User ID of the Account Controller/Agent |
| agentemployeeid | `Float` | Agentemployeeid |
| balance | `Float` | Balance on the account. |
| batchStmtYn | `String` | Include the account in batch statement |
| beginDate | `Date` | Begin Date |
| centralAccountType | `String` | Central Account Type |
| centralBalance | `Float` | Central Balance |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralFlaggedReasonCode | `String` | Central Flagged Reason Code |
| centralState | `String` | Central State |
| centralXchangeDate | `Date` | Central Exchange Date |
| centralXchangeRate | `Float` | Central Exchange Rate |
| city | `String` | City |
| company | `String` | Company |
| contact | `String` | Contact information. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryName | `String` | Country Name |
| creditLimit | `Float` | Credit Limit |
| creditLimitUpdatedOn | `DateTime` | Date when the Credit Limit was updated. |
| currencyCode | `String` | Summary Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debtorName | `String` | Debtor Name |
| deletedflag | `String` | Deleted Flag |
| email | `String` | Email |
| emailAddr | `String` | Email Addr |
| emailId | `Float` | Email ID |
| emailOptInYn | `String` | Indicates if the email address can be used to send Statements and Reminders by default. |
| endDate | `Date` | End Date |
| fax | `String` | Fax |
| faxId | `Float` | Fax ID |
| faxNumber | `String` | Fax Number |
| flaggedReasonCode | `String` | The flagged reason code from table AR$_FLAGGED_REASONS. |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalAccounttypeid | `Float` | Accounttypeid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastActivityDate | `DateTime` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| lastRemFaxNo | `String` | Fax number to which the last reminder letter was sent. |
| lastStmtFaxNo | `String` | Fax number to which the last statement was sent. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lstRemPrtDate | `Date` | Date on which the last reminder letter was printed. |
| lstRemSent | `Date` | Date on which the last reminder letter was sent. |
| lstRemText | `String` | Name of the reminder letter |
| lstStmtNoSent | `Float` | Stores the statement number of the last statement sent for a particular AR account. |
| lstStmtSent | `DateTime` | Date of Last reminderletter sent |
| monthEndCalcYn | `String` | If Y the Payment due date calculation begins from the last day of the month of invoice generation date if N  then calculation starts from the day of the invoice generation. |
| nAAddress1 | `String` | NA Address 1 |
| nAAddress2 | `String` | NA Address 2 |
| nAAddress3 | `String` | NA Address 3 |
| naCity | `String` | Na City |
| naCountryName | `String` | Na Country Name |
| naState | `String` | Na State |
| naStateDescription | `String` | Na State Description |
| nameId | `Float` | Name ID |
| numberOfPersons | `Float` | No of persons currently using the account |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| permAccountYN | `String` | Status indicator to show the account as a permanent account. User will not be able to delete the account if it is Y |
| phone | `String` | Phone |
| phoneId | `Float` | Phone ID |
| phoneNumber | `String` | Phone Number |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYn | `String` | Primary Y/N |
| profileid | `Float` | Profileid |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repStateDescription | `String` | Reporting State Description |
| revenuePool | `String` | Revenue Pool |
| state | `String` | State |
| stateDescription | `String` | State Description |
| status | `String` | Status |
| summaryforeigncurrid | `String` | Summaryforeigncurrid |
| superSearchIndexText | `String` | Super Search Index Text |
| supplement | `String` | Supplement |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upperCaseName | `String` | Upper Case Name |
| zip | `String` | Zip code. |

[⬆ Back to Query](#query)

---

### ARAgingReportCalendarPeriodDayDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayKey | `Date` | Day Key |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| parentperiodid | `String` | Parentperiodid |
| periodCode | `String` | Period Code |
| periodDescription | `String` | Period Description |
| periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| periodType | `String` | Period Type |
| periodTypeDesc | `String` | Period Type Description |
| periodsetupid | `Float` | Periodsetupid |
| periodsetuppmsref | `String` | Periodsetuppmsref |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| year | `Float` | Year |
| yearDescription | `String` | Year Description |
| yearEndDate | `Date` | Year End Date. |
| yearId | `Float` | Year ID |
| yearStartDate | `Date` | Year Start Date. |
| yearType | `String` | Year Type. |
| yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### ARAgingReportFinancialPeriodDayDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayKey | `Date` | Day Key |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| parentperiodid | `String` | Parentperiodid |
| periodCode | `String` | Period Code |
| periodDescription | `String` | Period Description |
| periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| periodType | `String` | Period Type |
| periodTypeDesc | `String` | Period Type Description |
| periodsetupid | `Float` | Periodsetupid |
| periodsetuppmsref | `String` | Periodsetuppmsref |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| year | `Float` | Year |
| yearDescription | `String` | Year Description |
| yearEndDate | `Date` | Year End Date. |
| yearId | `Float` | Year ID |
| yearStartDate | `Date` | Year Start Date. |
| yearType | `String` | Year Type. |
| yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### ARAgingReportARLedgerDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountCode | `Float` | Account Code |
| accountName | `String` | Account Name |
| accountNumber | `String` | Account Number |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| amount | `Float` | Amount |
| approvalCode | `String` | Approval Code |
| approvalDate | `Date` | Approval Date |
| approvalStatus | `String` | Approval Status |
| arLedgerCredit | `Float` | AR Led Credit |
| arLedgerDebit | `Float` | AR Led Debit |
| arNumber | `Float` | AR Number |
| arState | `String` | AR State |
| arTransferDate | `Date` | AR Transfer Date |
| arrangementId | `Float` | Arrangement ID |
| articleId | `Float` | Article ID |
| associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| authorizerId | `Float` | Authorizer ID |
| autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| autoSettleYn | `String` | Auto Settle Y/N |
| billNo | `Float` | Bill Number |
| bonusCheckId | `Float` | Bonus Check ID |
| bucketCode | `String` | Bucket code related to this redemption. |
| bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| businessDate | `Date` | Business Date |
| cARLedgerCredit | `Float` | Central Ar Led Credit |
| cARLedgerDebit | `Float` | Central Ar Led Debit |
| cCashierCredit | `Float` | Central Cashier Credit |
| cCashierDebit | `Float` | Central Cashier Debit |
| cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| cChangeDue | `Float` | Central Change Due |
| cContractGrossAmount | `Float` | Central Contract Gross Amount |
| cContractGuestCredit | `Float` | Central Contract Guest Credit |
| cContractGuestDebit | `Float` | Central Contract Guest Debit |
| cContractNetAmount | `Float` | Central Contract Net Amount |
| cDepLedgerCredit | `Float` | Central Dep Led Credit |
| cDepLedgerDebit | `Float` | Central Dep Led Debit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| cGrossAmount | `Float` | Central Gross Amount |
| cGuestAccountCredit | `Float` | Central Guest Account Credit |
| cGuestAccountDebit | `Float` | Central Guest Account Debit |
| cInHouseCredit | `Float` | Central Inh Credit |
| cInHouseDebit | `Float` | Central Inh Debit |
| cNetAmount | `Float` | Central Net Amount |
| cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| cPackageAllowance | `Float` | Central Package Allowance |
| cPackageCredit | `Float` | Central Package Credit |
| cPackageDebit | `Float` | Central Package Debit |
| cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| cParallelNetAmount | `Float` | Central Parallel Net Amount |
| cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| cPostedAmount | `Float` | Central Posted Amount |
| cPricePerUnit | `Float` | Central Price Per Unit |
| cRevenueAmount | `Float` | Central Revenue Amt |
| cTaxRate | `Float` | Central Tax Rate |
| cTransactionAmount | `Float` | Central Trx Amount |
| calcPointsYn | `String` | Indicates if points are to be calculated. |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierId | `Float` | Cashier ID |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| centralARLedgerAmount | `Float` | Central AR Ledger Amount |
| changeDue | `Float` | Change Due |
| checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| chequeNumber | `String` | Cheque Number |
| closureNo | `Float` | Closure Number |
| collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| comments | `String` | Comments |
| compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| compTypeCode | `String` | Comp Type Code |
| compressedYn | `String` | Compressed Y/N |
| contractCurrency | `String` | Currency code for contract currency. |
| contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| couponNo | `String` | Coupon Number |
| covers | `String` | Covers |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deferredTaxesYn | `String` | Indicates whether the generated tax is because of a deferred tax generation scenario |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depLedgerCredit | `Float` | Dep Ledger Credit |
| depLedgerDebit | `Float` | Dep Ledger Debit |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| depositTransactionId | `String` | Deposit Transaction ID |
| displayYn | `String` | Display Y/N |
| effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| exchangeDate | `Date` | Exchange Date |
| exchangeDifferenceYn | `String` | The flag indicates if it is an exchange rate difference posting when dual currency is on. |
| exchangeRate | `Float` | Exchange Rate |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| extTransactionId | `String` | Transaction ID from external system. |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| financialTransactionSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| fintransid | `Float` | Fintransid |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| folioNo | `Float` | Folio Number |
| folioType | `String` | Folio Type |
| folioView | `Float` | Folio View |
| folioid | `Float` | Folioid |
| foreignCurrencyID | `String` | Foreign Currency ID |
| forexCommAmount | `Float` | Foreign Exchange commission amount. |
| forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| fromReservationId | `Float` | From Resv ID |
| ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| genCashierId | `Float` | General Cashier Id. |
| gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| grossAmount | `Float` | Gross Amount |
| groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| guestAccountCredit | `Float` | Guest Account Credit |
| guestAccountDebit | `Float` | Debit amount on the guest account |
| holdYn | `String` | Indicates transaction is on hold. |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| inhCredit | `Float` | In House Credit |
| inhDebit | `Float` | In House Debit |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| installments | `Float` | Installments |
| internalCashierid | `Float` | Cashierid |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNo | `Float` | Invoice Number |
| invoiceType | `String` | Invoice Type |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkTrxNumber | `Float` | Link Transaction No |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| membershipId | `Float` | Membership ID |
| mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| netAmount | `Float` | Net Amount |
| numberDialed | `String` | Number Dialed. |
| oTransactionDesc | `String` | Transaction Description. |
| orgBillNumber | `Float` | Stores original bill number after void. |
| orgFolioType | `String` | Stores original folio type after void. |
| orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalReservationNameId | `Float` | Original Resv Name ID |
| originalRoom | `String` | Original Room |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageCredit | `Float` | Credit amount on the guest package account. |
| packageDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| parallelCurrency | `String` | Cuurency code for parrallel currency. |
| parallelGrossAmount | `Float` | Parallel Gross Amount |
| parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| parallelNetAmount | `Float` | Parallel Net Amount |
| passerByName | `String` | Passerby Name. |
| paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| paymentType | `String` | Payment Type |
| postedAmount | `Float` | Posted Amount |
| postingDate | `Date` | Posting Date |
| postingRhythm | `String` | Posting Rhythm |
| postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| postitNo | `Float` | Postit Number |
| postitYn | `String` | Postit Y/N |
| pricePerUnit | `Float` | Price Per Unit |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processed8300Yn | `String` | Indicates whether this particular transaction has been included in an 8300 tax form yet. |
| product | `String` | Product |
| profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| proformaYn | `String` | Proforma Y/N |
| property | `String` | Code to uniquely identify the Property |
| propertyBillPrefix | `String` | Property Bill Prefix |
| quantity | `Float` | Quantity |
| queueName | `String` | Queue Name |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| reasonCode | `String` | Reason Code |
| receiptNo | `Float` | Recpt Number |
| receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| reference | `String` | Reference |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| revenueAmt | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| revisionNo | `Float` | Revision Number |
| room | `String` | Room |
| roomClass | `String` | Room Class |
| roomNts | `Float` | Room Nts |
| roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| roundFactorYn | `String` | Round Factor Y/N |
| roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| routedYn | `String` | Indicates if the transaction has been routed. |
| routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| settlementFlag | `String` | Settlement Flag |
| sourceCode | `String` | Source Code |
| sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| supplement | `String` | Supplement |
| taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| taCommissionableYn | `String` | The value 'Y' indicates that the commission has been paid for the transaction. |
| targetResort | `String` | Target Property |
| taxElements | `String` | Tax Elements |
| taxGeneratedYn | `String` | Indicates whether tax has been generated for a particuar posting. |
| taxInclusiveYn | `String` | Tax Inclusive Y/N |
| taxInvNumber | `String` | Tax Invoice No |
| taxRate | `Float` | Tax Rate |
| taxRateType | `String` | Tax Rate Type |
| tcGroup | `String` | Transaction Code Group |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tclCode1 | `String` | Class1 Code. |
| tclCode2 | `String` | Class1 Code. |
| thresholdDiversionId | `Float` | Threshold Diversion ID |
| thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| thresholdEntityType | `String` | Threshold Entity Type |
| thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| toReservationNameId | `Float` | To Resv Name ID |
| tranActionId | `Float` | Tran Action ID |
| transactionDate | `Date` | Transaction Date |
| transactionFromAcct | `Float` | Trns From Account |
| transactionNumber | `Float` | Transaction Number |
| transactionToAcct | `Float` | Trns To Account |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| trnsActivityDate | `Date` | Transaction Activity Date |
| trxAmount | `Float` | Transaction Amount |
| trxCode | `String` | Transaction Code |
| trxNumberAddedBy | `Float` | Transaction No Added By |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| trxNumberHeader | `Float` | Transaction No Header |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAgingReportInvoiceHeaderDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRDebit | `Float` | AR Debit |
| aRLedgerCredit | `Float` | AR Ledger Credit |
| aRTransferDate | `Date` | AR Transfer Date |
| accountCode | `Float` | Account Code |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| addresseeNameId | `Float` | Addressee Name ID |
| adjustmentYn | `String` | Adjustment Y/N |
| adjustmentflag | `String` | Adjustmentflag |
| agingBucket | `Float` | Aging bucket number. |
| agingBusinessDate | `Date` | Aging Business Date |
| amount | `Float` | Amount |
| billNumber | `Float` | Bill Number |
| cARLedgerCredit | `Float` | Central Ar Led Credit |
| cARLedgerDebit | `Float` | Central Ar Led Debit |
| cAmount | `Float` | Central Amount |
| cContractCurrencyDifference | `Float` | Central Contract Curr Diff |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cOrganizationAmount | `Float` | Central Org Amt |
| cOrganizationAmountContract | `Float` | Central Org Amt Contract |
| cOrganizationAmountCurrencyDifference | `Float` | Central Org Amt Curr Diff |
| cOrganizationAmountParallel | `Float` | Central Org Amt Parallel |
| cPaid | `Float` | Central Paid |
| cParallelCurrencyDifference | `Float` | Central Parallel Curr Diff |
| cashierId | `Float` | Cashier ID |
| centralProfileID | `String` | Central Profile ID |
| checkOutDate | `Date` | Date on which the guest was checked out. |
| compressDate | `Date` | Date of Compression. |
| compressedYn | `String` | Compressed Y/N |
| contractCurrDifference | `Float` | Currency difference for contract amount. Used for Dual Currency functionality. |
| contractCurrencyCode | `String` | Currency Code of the contract currency. Used for Dual Currency functionality. |
| creditedToTrxNumber | `Float` | Stores the transaction number for which this credit bill is created. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateForAging | `String` | Date the aging should begin |
| deletedFlag | `String` | Deleted Flag |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| externalReceiptDate | `Date` | Receipt Date sent from external systems. |
| fintransid | `Float` | Fintransid |
| fiscalBillNo | `String` | Fiscal Bill Number |
| folioNo | `Float` | Folio Number |
| folioText1 | `String` | Folio Text 1 |
| folioText2 | `String` | Folio Text 2 |
| folioType | `String` | Folio Type |
| folioid | `Float` | Folioid |
| insertDate | `DateTime` | Insert Date |
| insertUser | `String` | Insert User |
| invoiceAge | `Float` | Invoice Age |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceClosedBy | `String` | Application User who closed the invoice. |
| invoiceNumber | `Float` | Invoice Number |
| invoiceStatus | `String` | Status of the invoice (H)old (O)pen or (C)losed. |
| invoiceType | `String` | Invoice Type |
| invoiceid | `Float` | Invoiceid |
| invoiceprofileid | `Float` | Invoiceprofileid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterInvoiceNumber | `Float` | Compressed Invoice No for which multiple invoices have been compressed to. |
| name | `String` | Name |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalAmount | `Float` | Original Amount |
| originalAmountContractCurrency | `Float` | Original Amount in contract currency. Used for Dual Currency functionality. |
| originalAmountCurrencyDifference | `Float` | Currency difference for the original amount in local currency.  Used for Dual Currency functionality. |
| originalAmountDualCurrency | `Float` | Original Amount in parallel currency. Used for Dual Currency functionality. |
| ownerRoom | `String` | The owner room where this invoice/payment belongs to. |
| ownerroomid | `String` | Ownerroomid |
| paid | `Float` | Amount paid. |
| parallelCurrDifference | `Float` | Currency difference for parallel amount. Used for Dual Currency functionality. |
| parallelCurrencyCode | `String` | Currency Code of the parallel currency. Used for Dual Currency functionality. |
| paymentNo | `String` | Payment Number used for chain specific functionality. |
| postDate | `Date` | Post Date |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printedDate | `Date` | Printed Date |
| printedYn | `String` | Printed Y/N |
| profileID | `String` | Profile ID |
| property | `String` | Code to uniquely identify the Property |
| purgeYn | `String` | Indicator whether to purge the Account. |
| reference | `String` | Reference |
| remark | `String` | Remark |
| reminderCycle | `Float` | Reminder Cycle that was generated for this invoice |
| reminderDate | `Date` | Date of the reminder letter that was sent |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomid | `String` | Roomid |
| statementNumber | `Float` | Statement Number |
| tranActionId | `Float` | Tran Action ID |
| transactionActivityDate | `DateTime` | Transaction Activity Date |
| transactionDate | `Date` | Transaction Date |
| transactionFromAcct | `Float` | Trns From Account |
| transactionToAcct | `Float` | Trns To Account |
| transcodeid | `String` | Transcodeid |
| transferfromaccountid | `Float` | Transferfromaccountid |
| transfertoaccountid | `Float` | Transfertoaccountid |
| trxCode | `String` | Transaction Code |
| trxNumber | `Float` | Transaction No |
| updateDate | `DateTime` | Update Date |
| updateUser | `String` | Update User |

[⬆ Back to Query](#query)

---

### ARAgingReportPropertyPropertyDetailsType

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

### ARAgingReportQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| aragingreportDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| aragingreportDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| aragingreportDetailsTrxDate | `DateInput!` | Transaction Date<br>`@mandatoryInput` |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput` | Property |
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
| arledgerDetailsArLedDebit | `FloatInput` | AR Led Debit |
| arledgerDetailsArNumber | `FloatInput` | AR Number |
| arledgerDetailsArState | `StringInput` | AR State |
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

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query aRAgingReport($input: ARAgingReportQueryArgumentsType!) {
  aRAgingReport(input: $input) @stream {
    aRAgingReportDetails {
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